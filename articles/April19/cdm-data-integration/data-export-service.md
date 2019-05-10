---
title: データ エクスポート サービス
description: データ エクスポート サービス
author: sabinn-msft
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: 4857be750a818575adda6d6c93570072e4ab28ea
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225057"
---
# <a name="data-export-service"></a>データ エクスポート サービス

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

Microsoft Dynamics365 のデータ エクスポート サービス (DES) は Microsoft AppSource 提供の無料アドオンであり、Microsoft Dynamics 365 (online) のデータを、顧客が所有する Microsoft Azure サブスクリプションの Microsoft Azure SQL Database に同期します。

サポートされているターゲットの同期先は、Microsoft Azure 仮想マシン上の Microsoft Azure SQL Database と Microsoft SQL Server です。 データ エクスポート サービスは、完全な書き込みを行った後、Microsoft Dynamics 365 (online) システムでの発生に合わせてデルタ変更を継続的に行います。 これにより、Dynamics 365 データに関するいくつかの分析およびレポート作成シナリオが可能になります。

2019 年 4 月リリースでは、お客様からのフィードバックに基づき、データ エクスポート サービスの信頼性とパフォーマンスの向上に関して以下の作業が行われています。

## <a name="show-count-and-trend-of-records-to-validate-and-notify-on-convergence-status"></a>収束の状態を検証および通知するためにレコードの数と傾向を表示する

Dynamics 365 for Sales (CRM) および Azure SQL Database からのレコードの数と傾向を表示することは、変更が正常に書き込まれたことを確認するために、同期元と同期先両方のレコード数を見たいというお客様からの最大の要望です。 さらに、この機能では、1 時間ごとに Dynamics 365 for Sales (CRM) と Azure SQL Database 両方のエンティティ別のレコード数を比較することによって、レコード数の傾向が提供されます。 また、Dynamics 365 for Sales (CRM) と Azure SQL Database の両方で、最新のバージョンと、エンティティごとのレコードのメタデータのバージョンも比較されます。

これらの機能強化により、お客様はレコードの収束 (または発散) を予測し、必要に応じて適切な措置を講じることができます。 また、データが同期していないためにエンティティ レコードに失敗通知がある場合にユーザーに知らせるアラート メカニズムを追加しています。

## <a name="minimize-write-failures-by-prioritizing-metadata-before-data"></a>データの前のメタデータを優先することで書き込みの失敗を最小限に抑える

お客様の環境でよく見られる失敗の 1 つは、データがメタデータよりも前に表示され、書き込みが失敗することです。 この機能を利用して、データ メッセージよりメタデータ メッセージを優先させるためのキューを実装し、メタデータ メッセージの処理が失敗した場合にデータ メッセージの処理を一時停止するようにしました。 また、データ メッセージの "受信メタデータ バージョン" 部分を検証し、それが SQL のものと異なる場合は、データ メッセージを処理せずにキューに入れます。

## <a name="show-unsupported-entities-for-change-tracking"></a>変更追跡でサポートされていないエンティティを表示する

これまでは、変更追跡が有効になっていないエンティティを識別する簡単な方法がありませんでした。 それらのエンティティはサポートされませんでした。 今回の変更により、すべてのエンティティがユーザー インターフェイスに表示され、変更追跡の対象としてサポートされていないエンティティはグレー表示されます。 これにより、いっそう直感的なエクスペリエンスが提供されます。

## <a name="reduce-latency-and-improve-performance"></a>待機時間を短縮してパフォーマンスを向上させる

データ エクスポート サービスでは、プロファイルごとに 1 つの削除ログが保持されます。 このログを使用して、削除とそのタイムスタンプが追跡されます。 お客様との話し合いによれば、特に多数のエンティティを含む大規模なプロファイルでは、単一の削除ログがパフォーマンスのボトルネックの原因になります。 この変更では、エンティティごとに削除ログを分割して、エンティティごとに 1 つ作成し、それによって削除処理の待機時間を大幅に短縮しました。 削除ログ テーブルにインデックスを追加することで、クエリのパフォーマンスがさらに向上します。
