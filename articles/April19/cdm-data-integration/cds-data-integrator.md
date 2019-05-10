---
title: CDS データ インテグレーター
description: CDS データ インテグレーター
author: sabinn-msft
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: c9b023592a6da6d8a45575e5cfb2671dc3601472
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225196"
---
# <a name="cds-data-integrator"></a>CDS データ インテグレーター

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

CDS データ インテグレーター (管理者用) は、データを Common Data Service に統合するために使用されるポイント ツー ポイント統合サービスです。 複数のソースから Common Data Service へのデータの統合がサポートされています。 Dynamics 365 for Finance and Operations と Dynamics 365 for Sales の間の直接同期を提供する見込顧客を現金化のようなプロセス ベースの統合シナリオをサポートしています。 データ統合で使用できる見込顧客を現金化テンプレートを使用すると、Finance and Operations と Sales の間で、取引先企業、取引先担当者、製品、販売見積、販売注文、および売上請求書のデータをフローできます。 2019 年 4 月リリースでは以下の投資を行うことにより、顧客の使用とフィードバックに基づいてこのサービスの強化を続けます。

## <a name="enhancements-in-error-handling-and-troubleshooting"></a>エラー処理とトラブルシューティングの機能強化

これらの機能により、プロジェクト全体のアクティブなエラーのリストを表示し、失敗したレコードを再試行できるようにします。

## <a name="ability-to-propagate-template-updates-to-projects"></a>テンプレートの更新をプロジェクトに反映する機能

以前は、テンプレートを更新するときに、古いテンプレートを使用しているプロジェクトを手動で更新する必要がありました。 この機能を使用すると、ソース テンプレートを更新した場合に、更新をプロジェクトにプッシュできます。

## <a name="richer-dashboard-with-meaningful-insights-and-views"></a>有意義な分析情報とビューを提供するさらに豊富なダッシュボード

顧客からのフィードバックに基づいて、すべての実行とそのステータスを 1 つの場所でリアルタイムに表示する管理ダッシュボードが提供されています。 このビューでは、実行の詳細を見ることができました。

今回のリリースでは、このダッシュボードがさらに強化され、実行別の上位 5 つのデータ統合プロジェクト、実行状態別のプロジェクト数など、さらに豊富なビューを利用できるようになりました。

## <a name="guidance-for-performance-tuning-and-integration-write-patterns"></a>パフォーマンス チューニングと統合書き込みパターンに関するガイダンス

当社の経験と顧客とのやり取りに基づいて、大容量統合のためにパフォーマンスの最適化方法に関するガイダンスのドキュメントを提供しています。 さらに、多対一および一対多のパターンでのエンティティ データの移動に関する一般的な要求をカバーした、統合のための書き込みパターンに関するガイダンスを公開しています。

## <a name="compliance-for-government-cloud"></a>政府機関クラウドへのコンプライアンス

また、政府機関の顧客がサービスの恩恵を受けて利用できるように、データ インテグレーターを GCC に準拠させるようにしています。
