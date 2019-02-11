---
title: 計画サービス
description: 企業が動的計画をほぼリアルタイムで管理できる、高データ量に対応した、スケーラビリティの非常に高いマルチテナント型のリアルタイムでの流通所要量計画サービス。
author: crytt
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: crytt
ms.openlocfilehash: 182d96becf2435d90cd12898e0365e3819dc3929
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210630"
---
#  <a name="planning-service"></a><span data-ttu-id="e6e80-103">計画サービス</span><span class="sxs-lookup"><span data-stu-id="e6e80-103">Planning service</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="e6e80-104">スケーラビリティの非常に高いマルチテナント型のリアルタイムでの流通所要量計画サービス。</span><span class="sxs-lookup"><span data-stu-id="e6e80-104">A hyper-scalable multitenant real-time distribution requirement planning service.</span></span> <span data-ttu-id="e6e80-105">このサービスにより、企業は動的計画をほぼリアルタイムで管理できるほか、高データ量にも対応します。</span><span class="sxs-lookup"><span data-stu-id="e6e80-105">The service enables companies to maintain a dynamic plan that's close to real time and supports high data volume.</span></span> 

<span data-ttu-id="e6e80-106">現代の企業は即座に応答するシステムに頼っており、ほぼ年中無休で稼働する企業にとって、必要なマスター プランの生成に毎晩数時間も実行されるバッチ ジョブを計画する余裕がありません。</span><span class="sxs-lookup"><span data-stu-id="e6e80-106">Customers today are relying on prompt system reply, and companies that operate close to 24/7 can't afford a planning batch job that runs for several hours every night to generate the needed master plan.</span></span> <span data-ttu-id="e6e80-107">多くの企業は、需要や供給の変化に合わせて最新の状態に保つために、計画を勤務時間中に複数回実行することを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-107">Many companies would like to run the planning multiple times during working hours to stay updated on demand and supply changes.</span></span> <span data-ttu-id="e6e80-108">計画サービスは、自社の ERP システムからマスター プラン実行の負荷を取り除き、最新の動的計画を一貫して提供することで、要件の変更についてほぼリアルタイムの分析情報を得ることを可能にし、新しい需要を早期の段階で検出、管理して合計リード時間を削減することで、節約を達成できる場合があります。</span><span class="sxs-lookup"><span data-stu-id="e6e80-108">The planning service will remove the load of master planning from their ERP system and provide a constantly updated dynamic plan that will give them close to real-time insight to requirement changes and potentially enable them to achieve savings by reduction of the total lead time, as new demands are detected and managed earlier.</span></span>  

## <a name="planning-hub"></a><span data-ttu-id="e6e80-109">計画ハブ</span><span class="sxs-lookup"><span data-stu-id="e6e80-109">Planning hub</span></span>
<span data-ttu-id="e6e80-110">スタンドアロンの計画サービスを使用すると、複数の ERP システムや他のデータソースを計画エンジンに接続し、計画を組み合わせて最適化できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-110">With the standalone planning service, you can connect multiple ERP systems or other data sources to the planning engine for a combined optimized plan.</span></span> <span data-ttu-id="e6e80-111">IoT や追加の予測データなどの外部データ ソースからの入力に対応するよう設計されています。</span><span class="sxs-lookup"><span data-stu-id="e6e80-111">The design is prepared for input from external data sources like IoT or additional forecasts data.</span></span> 

<span data-ttu-id="e6e80-112">これにより、顧客は次のことを達成できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-112">This enables customers to achieve:</span></span>

-   <span data-ttu-id="e6e80-113">複数の ERP システムにわたるハブを計画する。発生元に基づいて供給提案が配布されます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-113">Planning hub cross-multiple ERP systems where supply suggestions are distributed based on origin.</span></span>
-   <span data-ttu-id="e6e80-114">汎用 API インターフェイスを使用して複数の種類の ERP システムに接続する。これにより、企業はさまざまなシステムを運用しつつ、計画を一元化できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-114">Connections to multiple types of ERP systems with a generic API interface allowing enterprises to operate a variety of systems and still get a centralized plan.</span></span>
-   <span data-ttu-id="e6e80-115">仕入先業者と顧客間のコミュニケーションを通じてコネクテッド サプライ チェーンを計画する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-115">Planning in a connected supply chain with communication between suppliers and customers.</span></span>

## <a name="real-time-planning"></a><span data-ttu-id="e6e80-116">リアルタイムでの計画</span><span class="sxs-lookup"><span data-stu-id="e6e80-116">Real-time planning</span></span>
<span data-ttu-id="e6e80-117">計画サービスでは、最新の動的計画を一貫して提供することで、供給側と影響を受ける既存の注文の要件の変更についてほぼリアルタイムの分析情報を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-117">The planning service provides a constantly updated dynamic plan with close to real-time insight to requirement changes on the supply side as well as affected existing orders.</span></span>

<span data-ttu-id="e6e80-118">これにより、顧客は次のことを達成できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-118">This enables customers to achieve:</span></span>

-   <span data-ttu-id="e6e80-119">新しい重要を早期の段階で検出して管理することで合計リード時間を短縮し、コスト削減や売上の改善が見込まれる。毎晩の計画の実行まで待つ必要がないため、同じ日に注文できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-119">Potential savings and improved sales by reduction of the total lead time, as new demands are detected and managed earlier—order same day because you don’t have to wait for the nightly plan.</span></span>
-   <span data-ttu-id="e6e80-120">顧客サービスと受注に関わる処理が改善される。その他の変更や入力された販売注文の影響が検出され、計画がそれに従って完全に最適化されます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-120">Improved customer service and order taking, as the impact of other changes as well as the entered sales order is detected and the plan is fully optimized accordingly.</span></span>

## <a name="performance"></a><span data-ttu-id="e6e80-121">パフォーマンス</span><span class="sxs-lookup"><span data-stu-id="e6e80-121">Performance</span></span>

<span data-ttu-id="e6e80-122">Dynamics 365 for Finance and Operations に長期にわたって実行されるマスター プランがある場合、計画サービスは役に立つのでしょうか。</span><span class="sxs-lookup"><span data-stu-id="e6e80-122">If you have long-running master plans in Dynamics 365 for Finance and Operations, will the planning service work for you?</span></span> <span data-ttu-id="e6e80-123">はい。計画サービスは、大量のデータを迅速に処理するために特別に設計されています。</span><span class="sxs-lookup"><span data-stu-id="e6e80-123">Yes, the planning service is specifically designed for very fast calculations with massive data volume.</span></span> <span data-ttu-id="e6e80-124">これはスケーラビリティの非常に高いマルチテナント型のサービスとして構築されています。つまり、複数のテナントを同時に連携させて計画を処理できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-124">It’s built as a hyper-scalable multitenant service, meaning that multiple tenants can cooperate simultaneously to calculate the plan.</span></span> <span data-ttu-id="e6e80-125">また、計画サービスは ERP システムからマスター プラン実行の負荷を取り除き、サーバーの負荷を最小に抑えるようデータ ストリームを処理します。</span><span class="sxs-lookup"><span data-stu-id="e6e80-125">Also, the planning service will remove the load of master planning from your ERP system and work with a data stream that minimizes the server load.</span></span> 

<span data-ttu-id="e6e80-126">これにより、顧客は次のことを達成できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-126">This enables customers to achieve:</span></span>

-   <span data-ttu-id="e6e80-127">より短い実行時間で計画実行のパフォーマンスを大幅に改善する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-127">Greatly improved planning performance with shorter run time.</span></span>
-   <span data-ttu-id="e6e80-128">ERP システムからマスター プラン実行の負荷を取り除く。</span><span class="sxs-lookup"><span data-stu-id="e6e80-128">Ability to unload master planning from the ERP system.</span></span>
-   <span data-ttu-id="e6e80-129">日次または週次よりも高い頻度で計画を実行できる。</span><span class="sxs-lookup"><span data-stu-id="e6e80-129">More frequent planning runs—not just daily or weekly.</span></span>
-   <span data-ttu-id="e6e80-130">将来の事業の成長により計画システムが過負荷にならないという安心感を与える。</span><span class="sxs-lookup"><span data-stu-id="e6e80-130">Comfort that future business growth will not overload the planning system.</span></span>

## <a name="availability"></a><span data-ttu-id="e6e80-131">利用可能性</span><span class="sxs-lookup"><span data-stu-id="e6e80-131">Availability</span></span>
<span data-ttu-id="e6e80-132">計画サービスは、最初はプレビュー プログラムを通じて一部のお客様がご利用になれます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-132">At first the planning service will be available to selected customers via a preview program.</span></span> <span data-ttu-id="e6e80-133">その後、より幅広いお客様へのプレビュー提供を経て、一般提供となります。</span><span class="sxs-lookup"><span data-stu-id="e6e80-133">Later the preview will open up to a wider range of customers before becoming generally available.</span></span> 

## <a name="feature-highlights"></a><span data-ttu-id="e6e80-134">主な機能</span><span class="sxs-lookup"><span data-stu-id="e6e80-134">Feature highlights</span></span>

*   <span data-ttu-id="e6e80-135">計画サービスの最初のバージョンは、流通業者と卸売業者 (流通所要量計画: DRP) の両方のニーズに対応。</span><span class="sxs-lookup"><span data-stu-id="e6e80-135">The first version of the planning service will address the needs of both distributors and wholesalers (Distribution Requirement Planning, or DRP).</span></span>
* <span data-ttu-id="e6e80-136">リアルタイムでの計画に対応するために Dynamics 365 for Finance and Operations とすぐに統合できる。</span><span class="sxs-lookup"><span data-stu-id="e6e80-136">Out-of-the-box integration with Dynamics 365 for Finance and Operations to support real-time planning.</span></span>
* <span data-ttu-id="e6e80-137">Dynamics 365 for Finance and Operations 以外の追加の ERP システムに対応するスタンドアロンの計画サービス。</span><span class="sxs-lookup"><span data-stu-id="e6e80-137">Standalone planning service that can support additional ERP systems, besides Dynamics 365 for Finance and Operations.</span></span>
*   <span data-ttu-id="e6e80-138">複数の ERP システムへの統合に対応する汎用 API インターフェース。</span><span class="sxs-lookup"><span data-stu-id="e6e80-138">Generic API interface that can support integration to multiple ERP systems.</span></span> <span data-ttu-id="e6e80-139">たとえば、Finance and Operations、Business Central、Dynamics NAV AX2012、SAP、Salesforce のいずれか 1 つ以上に対応します。</span><span class="sxs-lookup"><span data-stu-id="e6e80-139">For example, one or more of the following: Finance and Operations, Business Central, Dynamics NAV, AX2012, SAP, or Salesforce.</span></span> 
*   <span data-ttu-id="e6e80-140">購入をサポートし、供給提案を転送する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-140">Support purchase and transfer supply suggestions.</span></span>
*   <span data-ttu-id="e6e80-141">手元にある在庫レベルと将来の需要に基づいて、固定の安全在庫レベルを維持するための供給提案を確保する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-141">Ensure supply suggestions to maintain fixed safety stock levels, based on on-hand levels and future demand.</span></span>
*   <span data-ttu-id="e6e80-142">需要の変動と季節性に対応する時間ベースの安全在庫オプション。</span><span class="sxs-lookup"><span data-stu-id="e6e80-142">Time-based safety stock option, to support fluctuation and seasonality in demand.</span></span>
*   <span data-ttu-id="e6e80-143">期間や注文日の計算のために、購入や移動のリード時間を含める。</span><span class="sxs-lookup"><span data-stu-id="e6e80-143">Include purchase and transfers lead times, for duration and order date calculation.</span></span>
*   <span data-ttu-id="e6e80-144">需要と供給を紐付け、特定の需要がどのようにして満たされるか、特定の供給がどのような需要を満たすかについて完全に視覚化できる。</span><span class="sxs-lookup"><span data-stu-id="e6e80-144">Pegging between supply and demand, providing full visibility for how a given demand is fulfilled or what demand a given supply fulfills.</span></span>
*   <span data-ttu-id="e6e80-145">ロットごとの再注文ポリシーに対応。定義された期間内のすべての需要を 1 つの供給提案にまとめます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-145">Lot-for-lot reordering policy support, combining all demand within a defined period into one supply suggestion.</span></span>
*   <span data-ttu-id="e6e80-146">カレンダーで制御された固定日間のロット フォー ロットの需要期間。</span><span class="sxs-lookup"><span data-stu-id="e6e80-146">Calendar-controlled lot-for-lot demand period between fixed days.</span></span> <span data-ttu-id="e6e80-147">例: 祝日を除く毎週月曜日。</span><span class="sxs-lookup"><span data-stu-id="e6e80-147">As an example, every Monday with exceptions for holidays.</span></span> 
*   <span data-ttu-id="e6e80-148">注文候補を希望の最小数量、倍数、最大数量に調整する注文数量修飾子。</span><span class="sxs-lookup"><span data-stu-id="e6e80-148">Order quantity modifiers that adjust order suggestions to a desired minimum, multiple, and/or maximum quantity.</span></span> 
*   <span data-ttu-id="e6e80-149">特定の計画実行に含まれる製品をフィルターすることで、1 つの品目または全製品のサブセットのみを計画する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-149">Plan just one item or a subset of all products by filtering the products included in a given planning run.</span></span>
*   <span data-ttu-id="e6e80-150">具体的な設定により複数の計画に対応。計画担当者は毎日の静的計画、リアルタイムの動的計画、複数の what-if 計画を同時に運用できます。</span><span class="sxs-lookup"><span data-stu-id="e6e80-150">Multiple plans with specific setup, allowing the planner to simultaneously operate with a daily static plan, a dynamic real-time plan, as well as multiple what-if plans.</span></span>
*   <span data-ttu-id="e6e80-151">リアルタイムの動的計画。</span><span class="sxs-lookup"><span data-stu-id="e6e80-151">Real-time dynamic plan.</span></span>
* <span data-ttu-id="e6e80-152">計画がすべての需要に合わせて最適化できないときに、注文の遅延を検出して履行日の候補を通知する。</span><span class="sxs-lookup"><span data-stu-id="e6e80-152">Detect and communicate order delays and possible fulfillment dates, when the plan can’t be optimized to fit all demands.</span></span>
*   <span data-ttu-id="e6e80-153">倉庫、仕入先、顧客などに関連する利用できる期間と利用できない期間の処理をカレンダーで対応。</span><span class="sxs-lookup"><span data-stu-id="e6e80-153">Calendar support to handle available and closed periods related to warehouses, vendors, customers, and more.</span></span>
*   <span data-ttu-id="e6e80-154">商品の再注文、受け取り、発行に必要な実際の時間をシミュレートするための時間の幅。</span><span class="sxs-lookup"><span data-stu-id="e6e80-154">Time margins to simulate the actual time needed to reorder, receive, and issue goods.</span></span>
*   <span data-ttu-id="e6e80-155">計画エンジンにより需要と供給間の予約のサポートが記録され考慮される。</span><span class="sxs-lookup"><span data-stu-id="e6e80-155">Support for reservations between supply and demand are recorded and respected by the planning engine.</span></span>
*   <span data-ttu-id="e6e80-156">記録された需要に基づいて削減を伴う需要予測を含めるオプション。</span><span class="sxs-lookup"><span data-stu-id="e6e80-156">Option to include demand forecast with reduction based on recorded demand.</span></span>
*   <span data-ttu-id="e6e80-157">事前定義された最大在庫レベルへの補充に対応する再注文ポリシー。</span><span class="sxs-lookup"><span data-stu-id="e6e80-157">Reordering policy that supports refilling to a predefined maximum inventory level.</span></span>
*   <span data-ttu-id="e6e80-158">計画された注文のルールベースの自動確定に対応。注文を ERP システムによって自動確定されるようにマークします。</span><span class="sxs-lookup"><span data-stu-id="e6e80-158">Support for rule-based auto-firming of planned orders—mark orders to be auto-firmed by the ERP system.</span></span>
*   <span data-ttu-id="e6e80-159">既存の供給注文を修正することで供給計画の最適化を提案する (既存の発注書の移動、引き下げ、キャンセルなど)。</span><span class="sxs-lookup"><span data-stu-id="e6e80-159">Suggestions to optimize the supply plan by modifying existing supply orders—for example, move, decrease or cancel an existing purchase order.</span></span>
*   <span data-ttu-id="e6e80-160">ローカライズや翻訳サポートなどのグローバリゼーションによりグローバルに使用可能に。</span><span class="sxs-lookup"><span data-stu-id="e6e80-160">Global usage with globalization to include localization and translation support.</span></span>

