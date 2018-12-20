---
title: "共有およびコネクタ管理分析レポート"
description: "共有レポートとコネクタ レポートはどちらも Microsoft Flow 管理分析で使用できます。"
author: KentWeareMSFT
manager: KVivek
ms.date: 11/20/2018
ms.assetid: a3632f34-4ad9-e811-a987-000d3a1362e3
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: keweare
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: 41f95820675c4c01b18c6fbb4c346639d4e3edc8
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---
# <a name="sharing-and-connectors-admin-analytics-reports-public-preview"></a><span data-ttu-id="1cfc7-103">共有およびコネクタ管理分析レポート (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="1cfc7-103">Sharing and Connectors Admin Analytics Reports (Public Preview)</span></span>




<span data-ttu-id="1cfc7-104">9 月後半に、Power プラットフォーム管理分析の[パブリック プレビュー リリースを発表](https://flow.microsoft.com/blog/admin-analytics/)しました </span><span class="sxs-lookup"><span data-stu-id="1cfc7-104">In late September, we [announced the public preview release](https://flow.microsoft.com/blog/admin-analytics/) of Power platform Admin Analytics.</span></span> <span data-ttu-id="1cfc7-105">その投稿では、共有とコネクタを含む今後のいくつかのレポートについて説明しました。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-105">In that post, we discussed a couple of upcoming reports, including sharing and connectors.</span></span> <span data-ttu-id="1cfc7-106">共有レポートとコネクタ レポートはどちらも Microsoft Flow 管理分析で使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-106">Both the sharing and connectors reports now are available in Microsoft Flow Admin Analytics.</span></span> 

> [!NOTE]
> <span data-ttu-id="1cfc7-107">これらのレポートにアクセスするための前提条件は変更されていませんが、現在その作業に取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-107">The prerequisites for accessing these reports have not changed, but we are working on them.</span></span> <span data-ttu-id="1cfc7-108">以前の投稿で要件をご確認ください。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-108">Please review the requirements in our previous post.</span></span>

<span data-ttu-id="1cfc7-109">どちらのレポートでも、テナント内でのユーザーによる Microsoft Flow の使用状況の分析情報が提供されます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-109">Both reports provide insight into how users are using Microsoft Flow within your tenant.</span></span> <span data-ttu-id="1cfc7-110">共有の観点からは、だれが最高意思決定者であるかを理解し、さらに自動化されたソリューションを組織に提供するための権限をそれらの人物に与える方法を判断することができます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-110">From a sharing perspective, you are able to understand who your champions are and then figure out how you can empower them to provide even more automated solutions for your organization.</span></span> <span data-ttu-id="1cfc7-111">コネクタ レポートでは、組織内で使用されている Microsoft、サードパーティ、カスタムのコネクタが示されます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-111">The connectors report will identify Microsoft, third party, and custom connectors that are in use within your organization.</span></span> 

<span data-ttu-id="1cfc7-112">[Power プラットフォーム管理センター](https://admin.powerplatform.microsoft.com/) に移動すると、Common Data Service、Microsoft Flow、PowerApps の分析を参照するために選択できる [分析] メニューが見つかります。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-112">When you navigate to the [Power platform admin center](https://admin.powerplatform.microsoft.com/), you will find an Analytics menu where you can choose to browse analytics for the Common Data Service, Microsoft Flow, and PowerApps.</span></span> <span data-ttu-id="1cfc7-113">共有およびコネクタ レポートの場合は、[Microsoft Flow] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-113">For the Sharing and Connectors report, select Microsoft Flow.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="1cfc7-114">![実行の使用方法](media/sharing-connectors-analytics-1.png "実行の使用方法")</span><span class="sxs-lookup"><span data-stu-id="1cfc7-114">![Run usage](media/sharing-connectors-analytics-1.png "Run usage")</span></span>

<span data-ttu-id="1cfc7-115">Microsoft Flow 分析機能から、**共有**を選択して共有レポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-115">From within the Microsoft Flow Analytics feature, you can select **Shared** to access your sharing report.</span></span> <span data-ttu-id="1cfc7-116">このレポートには、キャプチャする 3 つの異なるビジュアル化が表示されます。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-116">Within this report you will see three different visualizations that capture:</span></span>

- <span data-ttu-id="1cfc7-117">共有されるフローの種類 (システム イベント、スケジュール済み、またはボタンのクリック)。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-117">The types of flows shared (System Events, Scheduled, or Button clicked).</span></span>
- <span data-ttu-id="1cfc7-118">共有されたフローの名前。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-118">The name of the flow that has been shared.</span></span>
- <span data-ttu-id="1cfc7-119">発生した共有の数。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-119">The number of shares that have taken place.</span></span>
- <span data-ttu-id="1cfc7-120">これらの共有イベントのトレンドライン レポート。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-120">A trendline report of these shared events.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="1cfc7-121">![共有レポート](media/sharing-connectors-analytics-2.png "共有レポート")</span><span class="sxs-lookup"><span data-stu-id="1cfc7-121">![Sharing report](media/sharing-connectors-analytics-2.png "Sharing report")</span></span>

<span data-ttu-id="1cfc7-122">共有レポートに加えて、コネクタの使用状況を強調するレポートもリリースしました。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-122">In addition to the sharing report, we have also released a report that highlights connector usage.</span></span> <span data-ttu-id="1cfc7-123">コネクタ レポートには、次の項目があります。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-123">The Connectors report provides:</span></span>

- <span data-ttu-id="1cfc7-124">コネクタの使用状況を表示する 2 つのビジュアル化:</span><span class="sxs-lookup"><span data-stu-id="1cfc7-124">Two visualizations that display connector usage by:</span></span>
  - <span data-ttu-id="1cfc7-125">フロー実行。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-125">Flow runs.</span></span>
  - <span data-ttu-id="1cfc7-126">コネクタ接続 (コネクタの呼び出し)。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-126">Connector connections (calls to the connector).</span></span>

- <span data-ttu-id="1cfc7-127">次のものを一覧表示する表のビジュアル化。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-127">A table visualization that lists:</span></span>
  - <span data-ttu-id="1cfc7-128">コネクタの名前。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-128">The name of connector.</span></span>
  - <span data-ttu-id="1cfc7-129">接続の数。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-129">Number of connections.</span></span> 
  - <span data-ttu-id="1cfc7-130">関係するフローの数。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-130">Number of flows involved.</span></span>
  - <span data-ttu-id="1cfc7-131">そのコネクタを使用して実行されているフローの数。</span><span class="sxs-lookup"><span data-stu-id="1cfc7-131">Number of flow runs using that connector.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="1cfc7-132">![コネクタ レポート](media/sharing-connectors-analytics-3.png "コネクタ レポート")</span><span class="sxs-lookup"><span data-stu-id="1cfc7-132">![Connector report](media/sharing-connectors-analytics-3.png "Connector report")</span></span>
