---
title: データ エクスポート サービス
description: データ エクスポート サービス
author: sabinn-msft
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: ffacc429e692da74a6aa06259b3094b2a3255d77
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210290"
---
# <a name="data-export-service"></a>データ エクスポート サービス
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]


Microsoft Dynamics365 のデータ エクスポート サービス (DES) は Microsoft AppSource 提供の無料アドオンであり、Microsoft Dynamics 365 (online) のデータを、顧客が所有する Microsoft Azure サブスクリプションの Microsoft Azure SQL Database に同期します。

サポートされているターゲットの同期先は、Microsoft Azure 仮想マシン上の Microsoft Azure SQL Database と Microsoft SQL Server です。 データ エクスポート サービスは、完全な書き込みを行った後、Microsoft Dynamics 365 (online) システムでの発生に合わせてデルタ変更を継続的に行います。 これにより、Power BI などの Azure サービスで Dynamics 365 のデータに対する分析やレポート作成などの複数のシナリオが可能になり、新たに顧客やパートナーがカスタム ソリューションを構築できるようになります。

2019 年 4 月リリースでは、お客様からのフィードバックに基づき、データ エクスポート サービスの信頼性とパフォーマンスの向上に関して以下の作業が行われています。

## <a name="trending-insights-that-show-your-records-are-up-to-date"></a>レコードが最新のものであることを示す傾向分析情報

Dynamics 365 for Sales (CRM) および Azure SQL Database からのレコードの数と傾向を表示することは、変更が正常に書き込まれたことを確認するために、同期元と同期先両方のレコード数を見たいというお客様からの最大の要望です。 さらに、この機能では、1 時間ごとに Dynamics 365 for Sales (CRM) と Azure SQL Database 両方のエンティティ別のレコード数を比較することによって、レコード数の傾向が提供されます。 また、Dynamics 365 for Sales (CRM) と Azure SQL Database の両方で、最新のバージョンと、エンティティごとのレコードのメタデータのバージョンも比較されます。

これらの機能強化により、お客様はレコードの収束 (または発散) を予測し、必要に応じて適切な措置を講じることができます。 また、データが同期していないためにエンティティ レコードに失敗通知がある場合にユーザーに知らせるアラート メカニズムを追加しています。

## <a name="design-changes-to-mitigate-known-issues"></a>既知の問題を軽減するための設計変更

お客様の環境でよく見られる失敗の 1 つは、データがメタデータよりも前に表示され、書き込みが失敗することです。 この機能を利用して、データ メッセージよりメタデータ メッセージを優先させるためのキューを実装し、メタデータ メッセージの処理が失敗した場合にデータ メッセージの処理を一時停止するようにしました。 また、データ メッセージの "受信メタデータ バージョン" 部分を検証し、それが SQL のものと異なる場合は、データ メッセージを処理せずにキューに入れます。

これまでは、変更の追跡が有効になっていないエンティティを識別する簡単な方法がなかったため、サポートされていません。 今回の変更により、すべてのエンティティがユーザー インターフェイスに表示され、変更追跡のためにサポートされていないエンティティはグレー表示されます。 これにより、いっそう直感的なエクスペリエンスが提供されます。

また、Dynamics 365 for Sales と Azure SQL Database の間でフィールド長が誤っているためにエラーが発生することもよくあります。 この変更により、DES は Dynamics 365 for Sales の適切なプロパティを使用するようになり、フィールド長が正しくないために Azure SQL Database にデータをプッシュできない問題を回避できます。

## <a name="reduce-latency-and-improve-performance"></a>待機時間を短縮してパフォーマンスを向上させる

データ エクスポート サービスでは、プロファイルごとに 1 つの削除ログが保持されます。 このログを使用して、削除とそのタイムスタンプが追跡されます。 お客様との話し合いにより、特に多数のエンティティを含む大規模なプロファイルでは、単一の削除ログがパフォーマンスのボトルネックの原因になります。 この変更では、エンティティごとに削除ログを分割して、エンティティごとに 1 つ作成し、それによって削除処理の待機時間を大幅に短縮しました。 削除ログ テーブルにインデックスを追加することで、クエリのパフォーマンスがさらに向上します。
