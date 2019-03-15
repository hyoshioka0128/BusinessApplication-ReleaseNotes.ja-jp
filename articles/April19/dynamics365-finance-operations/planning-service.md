---
title: 計画サービス
description: 企業が動的計画をほぼリアルタイムで管理できる、高データ量に対応した、スケーラビリティの非常に高いマルチテナント型のリアルタイムでの流通所要量計画サービス。
author: crytt
ms.date: 02/06/2019
ms.topic: article
ms.service: business-applications
ms.author: crytt
ms.openlocfilehash: bac973de00c180f063e896e3e997da9ca8f5fbbf
ms.sourcegitcommit: b9767a09372408f15b665101ae38d17e1c1875dc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/08/2019
ms.locfileid: "377501"
---
#  <a name="planning-service"></a><span data-ttu-id="f20dc-103">計画サービス</span><span class="sxs-lookup"><span data-stu-id="f20dc-103">Planning service</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="f20dc-104">スケーラビリティの非常に高いマルチテナント型のリアルタイムでの流通所要量計画サービス。</span><span class="sxs-lookup"><span data-stu-id="f20dc-104">A hyper-scalable multitenant real-time distribution requirement planning service.</span></span> <span data-ttu-id="f20dc-105">このサービスにより、企業は動的計画をほぼリアルタイムで管理できるほか、高データ量にも対応します。</span><span class="sxs-lookup"><span data-stu-id="f20dc-105">The service enables companies to maintain a dynamic plan that's close to real time and supports high data volume.</span></span> 

<span data-ttu-id="f20dc-106">現代の企業は即座に応答するシステムに頼っており、ほぼ年中無休で稼働する企業にとって、必要なマスター プランの生成に毎晩数時間も実行されるバッチ ジョブを計画する余裕がありません。</span><span class="sxs-lookup"><span data-stu-id="f20dc-106">Customers today are relying on prompt system reply, and companies that operate close to 24/7 can't afford a planning batch job that runs for several hours every night to generate the needed master plan.</span></span> <span data-ttu-id="f20dc-107">多くの企業は、需要や供給の変化に合わせて最新の状態に保つために、計画を勤務時間中に複数回実行することを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-107">Many companies would like to run the planning multiple times during working hours to stay updated on demand and supply changes.</span></span> <span data-ttu-id="f20dc-108">計画サービスは、自社の ERP システムからマスター プラン実行の負荷を取り除き、最新の動的計画を一貫して提供することで、要件の変更についてほぼリアルタイムの分析情報を得ることを可能にし、新しい需要を早期の段階で検出、管理して合計リード時間を削減することで、節約を達成できる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f20dc-108">The planning service will remove the load of master planning from their ERP system and provide a constantly updated dynamic plan that will give them close to real-time insight to requirement changes and potentially enable them to achieve savings by reduction of the total lead time, as new demands are detected and managed earlier.</span></span>  

## <a name="real-time-planning"></a><span data-ttu-id="f20dc-109">リアルタイムでの計画</span><span class="sxs-lookup"><span data-stu-id="f20dc-109">Real-time planning</span></span>
<span data-ttu-id="f20dc-110">計画サービスでは、最新の動的計画を一貫して提供することで、供給側と影響を受ける既存の注文の要件の変更についてほぼリアルタイムの分析情報を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-110">The planning service provides a constantly updated dynamic plan with close to real-time insight to requirement changes on the supply side as well as affected existing orders.</span></span>

<span data-ttu-id="f20dc-111">これにより、顧客は次のことを達成できます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-111">This enables customers to achieve:</span></span>

-   <span data-ttu-id="f20dc-112">新しい重要を早期の段階で検出して管理することで合計リード時間を短縮し、コスト削減や売上の改善が見込まれる。毎晩の計画の実行まで待つ必要がないため、同じ日に注文できます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-112">Potential savings and improved sales by reduction of the total lead time, as new demands are detected and managed earlier—order same day because you don’t have to wait for the nightly plan.</span></span>
-   <span data-ttu-id="f20dc-113">顧客サービスと受注に関わる処理が改善される。その他の変更や入力された販売注文の影響が検出され、計画がそれに従って完全に最適化されます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-113">Improved customer service and order taking, as the impact of other changes as well as the entered sales order is detected and the plan is fully optimized accordingly.</span></span>

## <a name="performance"></a><span data-ttu-id="f20dc-114">パフォーマンス</span><span class="sxs-lookup"><span data-stu-id="f20dc-114">Performance</span></span>

<span data-ttu-id="f20dc-115">Dynamics 365 for Finance and Operations に長期にわたって実行されるマスター プランがある場合、計画サービスは役に立つのでしょうか。</span><span class="sxs-lookup"><span data-stu-id="f20dc-115">If you have long-running master plans in Dynamics 365 for Finance and Operations, will the planning service work for you?</span></span> <span data-ttu-id="f20dc-116">はい。計画サービスは、大量のデータを迅速に処理するために特別に設計されています。</span><span class="sxs-lookup"><span data-stu-id="f20dc-116">Yes, the planning service is specifically designed for very fast calculations with massive data volume.</span></span> <span data-ttu-id="f20dc-117">これはスケーラビリティの非常に高いマルチテナント型のサービスとして構築されています。つまり、複数のテナントを同時に連携させて計画を処理できます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-117">It’s built as a hyper-scalable multitenant service, meaning that multiple tenants can cooperate simultaneously to calculate the plan.</span></span> <span data-ttu-id="f20dc-118">また、計画サービスは ERP システムからマスター プラン実行の負荷を取り除き、サーバーの負荷を最小に抑えるようデータ ストリームを処理します。</span><span class="sxs-lookup"><span data-stu-id="f20dc-118">Also, the planning service will remove the load of master planning from your ERP system and work with a data stream that minimizes the server load.</span></span> 

<span data-ttu-id="f20dc-119">これにより、顧客は次のことを達成できます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-119">This enables customers to achieve:</span></span>

-   <span data-ttu-id="f20dc-120">より短い実行時間で計画実行のパフォーマンスを大幅に改善する。</span><span class="sxs-lookup"><span data-stu-id="f20dc-120">Greatly improved planning performance with shorter run time.</span></span>
-   <span data-ttu-id="f20dc-121">ERP システムからマスター プラン実行の負荷を取り除く。</span><span class="sxs-lookup"><span data-stu-id="f20dc-121">Ability to unload master planning from the ERP system.</span></span>
-   <span data-ttu-id="f20dc-122">日次または週次よりも高い頻度で計画を実行できる。</span><span class="sxs-lookup"><span data-stu-id="f20dc-122">More frequent planning runs—not just daily or weekly.</span></span>
-   <span data-ttu-id="f20dc-123">将来の事業の成長により計画システムが過負荷にならないという安心感を与える。</span><span class="sxs-lookup"><span data-stu-id="f20dc-123">Comfort that future business growth will not overload the planning system.</span></span>

## <a name="availability"></a><span data-ttu-id="f20dc-124">利用可能性</span><span class="sxs-lookup"><span data-stu-id="f20dc-124">Availability</span></span>
<span data-ttu-id="f20dc-125">計画サービスは、最初はプレビュー プログラムを通じて一部のお客様がご利用になれます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-125">At first the planning service will be available to selected customers via a preview program.</span></span> <span data-ttu-id="f20dc-126">その後、より幅広いお客様へのプレビュー提供を経て、一般提供となります。</span><span class="sxs-lookup"><span data-stu-id="f20dc-126">Later the preview will open up to a wider range of customers before becoming generally available.</span></span> 

## <a name="feature-highlights"></a><span data-ttu-id="f20dc-127">主な機能</span><span class="sxs-lookup"><span data-stu-id="f20dc-127">Feature highlights</span></span>

*   <span data-ttu-id="f20dc-128">計画サービスの最初のバージョンは、流通業者と卸売業者の両方のニーズに対応。</span><span class="sxs-lookup"><span data-stu-id="f20dc-128">The first version of the planning service will address the needs of both distributors and wholesalers.</span></span>
* <span data-ttu-id="f20dc-129">ほぼリアルタイムでの計画に対応するために Dynamics 365 for Finance and Operations とすぐに統合できる。</span><span class="sxs-lookup"><span data-stu-id="f20dc-129">Out-of-the-box integration with Dynamics 365 for Finance and Operations to support near real-time planning.</span></span>
*   <span data-ttu-id="f20dc-130">購入をサポートし、供給提案を転送する。</span><span class="sxs-lookup"><span data-stu-id="f20dc-130">Support purchase and transfer supply suggestions.</span></span>
*   <span data-ttu-id="f20dc-131">手元にある在庫レベルと将来の需要に基づいて、固定の安全在庫レベルを維持するための供給提案を確保する。</span><span class="sxs-lookup"><span data-stu-id="f20dc-131">Ensure supply suggestions to maintain fixed safety stock levels, based on on-hand levels and future demand.</span></span>
*   <span data-ttu-id="f20dc-132">需要の変動と季節性に対応する時間ベースの安全在庫オプション。</span><span class="sxs-lookup"><span data-stu-id="f20dc-132">Time-based safety stock option, to support fluctuation and seasonality in demand.</span></span>
*   <span data-ttu-id="f20dc-133">期間や注文日の計算のために、購入や移動のリード時間を含める。</span><span class="sxs-lookup"><span data-stu-id="f20dc-133">Include purchase and transfers lead times, for duration and order date calculation.</span></span>
*   <span data-ttu-id="f20dc-134">需要と供給を紐付け、特定の需要がどのようにして満たされるか、特定の供給がどのような需要を満たすかについて完全に視覚化できる。</span><span class="sxs-lookup"><span data-stu-id="f20dc-134">Pegging between supply and demand, providing full visibility for how a given demand is fulfilled or what demand a given supply fulfills.</span></span>
*   <span data-ttu-id="f20dc-135">ロットごとの再注文ポリシーに対応。定義された期間内のすべての需要を 1 つの供給提案にまとめます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-135">Lot-for-lot reordering policy support, combining all demand within a defined period into one supply suggestion.</span></span>
*   <span data-ttu-id="f20dc-136">注文候補を希望の最小数量、倍数、最大数量に調整する注文数量修飾子。</span><span class="sxs-lookup"><span data-stu-id="f20dc-136">Order quantity modifiers that adjust order suggestions to a desired minimum, multiple, and/or maximum quantity.</span></span> 
*   <span data-ttu-id="f20dc-137">特定の計画実行に含まれる製品をフィルターすることで、1 つの品目または全製品のサブセットのみを計画する。</span><span class="sxs-lookup"><span data-stu-id="f20dc-137">Plan just one item or a subset of all products by filtering the products included in a given planning run.</span></span>
*   <span data-ttu-id="f20dc-138">具体的な設定により複数の計画に対応。計画担当者は毎日の静的計画、リアルタイムの動的計画、複数の what-if 計画を同時に運用できます。</span><span class="sxs-lookup"><span data-stu-id="f20dc-138">Multiple plans with specific setup, allowing the planner to simultaneously operate with a daily static plan, a dynamic real-time plan, as well as multiple what-if plans.</span></span>
*   <span data-ttu-id="f20dc-139">ほぼリアルタイムの動的計画。</span><span class="sxs-lookup"><span data-stu-id="f20dc-139">Near real-time dynamic plan.</span></span>
* <span data-ttu-id="f20dc-140">計画がすべての需要に合わせて最適化できないときに、注文の遅延を検出して履行日の候補を通知する。</span><span class="sxs-lookup"><span data-stu-id="f20dc-140">Detect and communicate order delays and possible fulfillment dates, when the plan can’t be optimized to fit all demands.</span></span>
*   <span data-ttu-id="f20dc-141">倉庫、仕入先、顧客などに関連する利用できる期間と利用できない期間の処理をカレンダーで対応。</span><span class="sxs-lookup"><span data-stu-id="f20dc-141">Calendar support to handle available and closed periods related to warehouses, vendors, customers, and more.</span></span>
*   <span data-ttu-id="f20dc-142">計画エンジンにより需要と供給間の予約のサポートが記録され考慮される。</span><span class="sxs-lookup"><span data-stu-id="f20dc-142">Support for reservations between supply and demand are recorded and respected by the planning engine.</span></span>
*   <span data-ttu-id="f20dc-143">記録された需要に基づいて削減を伴う需要予測を含めるオプション。</span><span class="sxs-lookup"><span data-stu-id="f20dc-143">Option to include demand forecast with reduction based on recorded demand.</span></span>
*   <span data-ttu-id="f20dc-144">事前定義された最大在庫レベルへの補充に対応する再注文ポリシー。</span><span class="sxs-lookup"><span data-stu-id="f20dc-144">Reordering policy that supports refilling to a predefined maximum inventory level.</span></span>

