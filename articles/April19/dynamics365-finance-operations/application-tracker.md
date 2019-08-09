---
title: アプリケーション トラッカー
description: 高度な分析ツールを使用して、カスタム拡張機能の正常性とパフォーマンスを監視できます。
author: TJVass
ms.date: 03/2/2019
ms.topic: article
ms.service: business-applications
ms.author: TJVass
ms.openlocfilehash: cd95d11431c9e04dead05eb64d751cca78016df4
ms.sourcegitcommit: 667ed3d965bd10435ad5775136a74d6ec085f5bc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/29/2019
ms.locfileid: "1792234"
---
#  <a name="application-tracker---code-quality-tooling"></a>アプリケーション トラッカー - コード品質ツール
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Dynamics 365 for Finance and Operations で、開発者が [Microsoft Azure の Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) を利用した分析ツールを活用して、カスタム拡張機能の正常性とパフォーマンスを監視できるようになりました。 これらのツールでは、サービスの組み込みのテレメトリ インフラストラクチャによって抽出された詳細なプロセス イベント属性を使用して、ソリューションの品質を向上させることができます。 アプリケーション トラッカーは、詳細な手順分析を提供するプリミティブなインストルメンテーション情報を提供します。 また、このツールを使用して、次のような一般的な診断手順を実行できます。

- SQL 操作から分析情報を収集する
- フォームと拡張機能を収容するモジュールを追跡する (Forms のみ)
- メタデータ テーブル、ダイレクト SQL ステートメント、GlobalObjectCache へのアクセスをカウントする 
- UserConnections の作成と破棄を監視する

その他の機能として、実行時のサービス アクティビティに関するアクション可能な分析情報の提供、標準のアプリケーション拡張機能を使用したカスタム テレメトリ属性の定義などがあります。 アプリケーション トラッカーは、有効でありながらプロセスのパフォーマンスに対する観測可能なオーバーヘッドが発生しない、効率的な診断ユーティリティです。 

Platform update 26 以降を実行しているすべての開発環境とテスト環境でアプリケーション トラッカーを使用できるようになりました。 開始するには、「[アプリケーション トラッカー - パフォーマンス テレメトリの発行](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax/posts/application-tracker---emit-telemetry-from-your-development-environment-to-application-insights)」を参照してください。
