---
title: アプリケーション トラッカー
description: 高度な分析ツールを使用して、カスタム拡張機能の正常性とパフォーマンスを監視できます。
author: TJVass
ms.date: 03/2/2019
ms.topic: article
ms.service: business-applications
ms.author: TJVass
ms.openlocfilehash: c8cbf0471a121beaf93c18505b6443a0bccf92b2
ms.sourcegitcommit: 09cd9749fbd3933da176c42992104a585fa9e3f8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/06/2019
ms.locfileid: "778043"
---
#  <a name="application-tracker---code-quality-tooling"></a>アプリケーション トラッカー - コード品質ツール
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Dynamics 365 for Finance and Operations で、開発者が [Microsoft Azure の Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) を利用した分析ツールを活用して、カスタム拡張機能の正常性とパフォーマンスを監視できるようになりました。 これらのツールでは、サービスの組み込みのテレメトリ インフラストラクチャによって抽出された詳細なプロセス イベント属性を使用して、ソリューションの品質を向上させることができます。 アプリケーション トラッカーは、詳細な手順分析を提供するプリミティブなインストルメンテーション情報を提供します。 また、このツールを使用して、次のような一般的な診断手順を実行できます。

- SQL 操作から分析情報を収集する
- フォームと拡張機能を収容するモジュールを追跡する (Forms のみ)
- メタデータ テーブル、ダイレクト SQL ステートメント、GlobalObjectCache へのアクセスをカウントする 
- UserConnections の作成と破棄を監視する

その他の機能として、実行時のサービス アクティビティに関するアクション可能な分析情報の提供、標準のアプリケーション拡張機能を使用したカスタム テレメトリ属性の定義などがあります。 アプリケーション トラッカーは、有効でありながらプロセスのパフォーマンスに対する観測可能なオーバーヘッドが発生しない、効率的な診断ユーティリティです。 
