---
title: アプリケーション トラッカー
description: 高度な分析ツールを使用して、カスタム拡張機能の正常性とパフォーマンスを監視できます。
author: TJVass
ms.date: 03/2/2019
ms.topic: article
ms.service: business-applications
ms.author: TJVass
ms.openlocfilehash: c8cbf0471a121beaf93c18505b6443a0bccf92b2
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225155"
---
#  <a name="application-tracker---code-quality-tooling"></a><span data-ttu-id="3a005-103">アプリケーション トラッカー - コード品質ツール</span><span class="sxs-lookup"><span data-stu-id="3a005-103">Application Tracker - Code quality tooling</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="3a005-104">Dynamics 365 for Finance and Operations で、開発者が [Microsoft Azure の Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) を利用した分析ツールを活用して、カスタム拡張機能の正常性とパフォーマンスを監視できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3a005-104">Dynamics 365 for Finance and Operations now allows developers to take advantage of analytical tools powered by [Microsoft Azure's Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) to monitor the health and performance of custom extensions.</span></span> <span data-ttu-id="3a005-105">これらのツールでは、サービスの組み込みのテレメトリ インフラストラクチャによって抽出された詳細なプロセス イベント属性を使用して、ソリューションの品質を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="3a005-105">With these tools, you can improve the quality of your solutions by using detailed process event attributes extracted through the service's built-in telemetry infrastructure.</span></span> <span data-ttu-id="3a005-106">アプリケーション トラッカーは、詳細な手順分析を提供するプリミティブなインストルメンテーション情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="3a005-106">The Application Tracker provides primitive instrumentation information that offers detailed procedural analysis.</span></span> <span data-ttu-id="3a005-107">また、このツールを使用して、次のような一般的な診断手順を実行できます。</span><span class="sxs-lookup"><span data-stu-id="3a005-107">The tools also allow you to complete the following common diagnostic procedures:</span></span>

- <span data-ttu-id="3a005-108">SQL 操作から分析情報を収集する</span><span class="sxs-lookup"><span data-stu-id="3a005-108">Gather insights from SQL operations</span></span>
- <span data-ttu-id="3a005-109">フォームと拡張機能を収容するモジュールを追跡する (Forms のみ)</span><span class="sxs-lookup"><span data-stu-id="3a005-109">Track modules that house the Form and extensions (Forms only)</span></span>
- <span data-ttu-id="3a005-110">メタデータ テーブル、ダイレクト SQL ステートメント、GlobalObjectCache へのアクセスをカウントする</span><span class="sxs-lookup"><span data-stu-id="3a005-110">Count access to metadata tables, direct SQL statements, and GlobalObjectCache</span></span> 
- <span data-ttu-id="3a005-111">UserConnections の作成と破棄を監視する</span><span class="sxs-lookup"><span data-stu-id="3a005-111">Monitor the creation and disposal of UserConnections</span></span>

<span data-ttu-id="3a005-112">その他の機能として、実行時のサービス アクティビティに関するアクション可能な分析情報の提供、標準のアプリケーション拡張機能を使用したカスタム テレメトリ属性の定義などがあります。</span><span class="sxs-lookup"><span data-stu-id="3a005-112">Additional capabilities include actionable insights into runtime service activities and the ability to define custom telemetry attributes by using standard application extensions.</span></span> <span data-ttu-id="3a005-113">アプリケーション トラッカーは、有効でありながらプロセスのパフォーマンスに対する観測可能なオーバーヘッドが発生しない、効率的な診断ユーティリティです。</span><span class="sxs-lookup"><span data-stu-id="3a005-113">While active, the Application Tracker is an effective diagnostic utility that doesn't incur any observable overhead on the performance of the process.</span></span> 
