---
title: 倉庫管理での CW 製品処理
description: 倉庫管理での CW 製品処理
author: ShylaThompson
manager: AnnBe
ms.date: 11/30/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: shylaw
audience: end-user
ms.openlocfilehash: ce2b140153ad67195a792c5db409df442029562d
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199401"
---
#  <a name="catch-weight-product-processing-with-warehouse-management"></a><span data-ttu-id="37507-103">倉庫管理での CW 製品処理</span><span class="sxs-lookup"><span data-stu-id="37507-103">Catch weight product processing with warehouse management</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="37507-104">この機能では、倉庫管理プロセス内で CW 製品を使用するためのサポートが提供されます。</span><span class="sxs-lookup"><span data-stu-id="37507-104">This functionality will provide support for using catch weight products within warehouse management processes.</span></span> <span data-ttu-id="37507-105">CW 製品は、食品業界など、製品によって重量やサイズが異なる業界でよく使用されます。</span><span class="sxs-lookup"><span data-stu-id="37507-105">Catch weight products are often used in industries where products vary by weight and/or size, such as the food industry.</span></span> <span data-ttu-id="37507-106">CW 製品では、在庫単位 (Kg、lb、oz など) と CW 単位 (箱、1 つ、パレットなど) の 2 つの測定単位が使用されます。</span><span class="sxs-lookup"><span data-stu-id="37507-106">Catch weight products use two units of measure - an inventory unit (such as kg, lb, or oz) and a catch weight unit (such as box, each, or pallet).</span></span> <span data-ttu-id="37507-107">在庫単位は、製品の計量と請求に使用される測定単位です。</span><span class="sxs-lookup"><span data-stu-id="37507-107">The inventory unit is the unit of measure in which the product is weighed and invoiced.</span></span> <span data-ttu-id="37507-108">CW 単位は、入庫、輸送、出荷などでの製品の処理単位です。</span><span class="sxs-lookup"><span data-stu-id="37507-108">The catch weight unit is the unit in which the products are handled, such as received, transferred, and shipped.</span></span>

<span data-ttu-id="37507-109">倉庫管理プロセスでは、CW 製品をパレットや箱などの異なる単位で処理することができ、ビジネス プロセスを細かく定義して、たとえばパレット レベルごとに入庫計量を実行したり、CW 数量 (箱) あたりのピッキングまたは梱包時に出荷営業プロセスを取り込んだりできます。</span><span class="sxs-lookup"><span data-stu-id="37507-109">Within the warehouse management processes, the catch weight products can be handled in different units, such as pallets and boxes, and the business processes can be granularly defined to, for example, perform the inbound weighing per pallet level and capture the outbound sales process during picking or packing per catch weight quantity (box).</span></span>

<span data-ttu-id="37507-110">この機能では、割り当てられている CW 単位ごとにキャプチャされた重量を取得する CW タグを使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="37507-110">This feature also allows you to use a catch weight tag that will get the captured weight per catch weight unit assigned.</span></span> <span data-ttu-id="37507-111">このアプローチの目的は、製品を受領時に 1 回のみ計量することです。</span><span class="sxs-lookup"><span data-stu-id="37507-111">The goal of this approach is to weigh the product only once at the time of receipt.</span></span> <span data-ttu-id="37507-112">これは、時間がたっても重量が変化しない製品 (冷凍エビなど)、および出荷可能な材料取り扱い測定単位 (エビの箱など) がある製品に有効です。</span><span class="sxs-lookup"><span data-stu-id="37507-112">This works for products that do not change weight over time (frozen shrimp, for example) and products that have a handling unit of measure that is shippable (such as a box of shrimp).</span></span> <span data-ttu-id="37507-113">このアプローチでは、ユーザーは CW タグをスキャンして、製品の構成に基づいてピッキングまたは梱包時に重量を識別し、取り込んだ CW タグに関連付けられている重量に基づいて請求できます。</span><span class="sxs-lookup"><span data-stu-id="37507-113">With this approach, the user scans the catch weight tag to identify the weight at the time of picking or packing based on product configuration and then invoicing is based on the weight that is associated with the captured catch weight tag.</span></span> 

## <a name="supported-scenarios"></a><span data-ttu-id="37507-114">サポートされているシナリオ</span><span class="sxs-lookup"><span data-stu-id="37507-114">Supported scenarios</span></span>

<span data-ttu-id="37507-115">倉庫管理での CW 製品処理をサポートしていないワークフローもあります。</span><span class="sxs-lookup"><span data-stu-id="37507-115">Not all workflows support catch weight product processing with warehouse management.</span></span> <span data-ttu-id="37507-116">現在は、次の制限があります。</span><span class="sxs-lookup"><span data-stu-id="37507-116">The following restrictions currently exist:</span></span>
 
<span data-ttu-id="37507-117">**倉庫管理プロセス用に CW 製品を有効にする**</span><span class="sxs-lookup"><span data-stu-id="37507-117">**Enable catch weight product for warehouse management processes**</span></span>
- <span data-ttu-id="37507-118">品目の保管分析コード グループの変更 (倉庫管理プロセスを有効にする) は、CW 製品についてはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-118">Change storage dimension group for items (to become warehouse management process enabled) is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-119">CW 製品では、フォーミュラの "完成品" 部分のみがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="37507-119">Only 'Finished goods' part of formulas are supported for catch weight products.</span></span>
- <span data-ttu-id="37507-120">CW 製品では、フォーミュラの一部としての "未加工コンポーネント" のみがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="37507-120">Only 'Raw components' as part of formulas are supported for catch weight products.</span></span>
- <span data-ttu-id="37507-121">CW 商品は、所有者分析コードを使用して追跡用分析コード グループに関連付けることはできません。</span><span class="sxs-lookup"><span data-stu-id="37507-121">Catch weight products cannot be associated with a tracking dimension group using the owner dimension.</span></span>
- <span data-ttu-id="37507-122">CW 製品はサービスとして使用できません。</span><span class="sxs-lookup"><span data-stu-id="37507-122">Catch weight products cannot be used as services.</span></span>
- <span data-ttu-id="37507-123">CW 製品は、品目モデル グループの一部としての "在庫製品" としてのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="37507-123">Catch weight products can only be used as 'Stocked product' as part the Item model group.</span></span>
- <span data-ttu-id="37507-124">CW 商品は、"販売プロセスで有効" 追跡機能と併用することはできません。</span><span class="sxs-lookup"><span data-stu-id="37507-124">Catch weight products cannot be used together with the 'Active in sales process' tracking functionality.</span></span>
- <span data-ttu-id="37507-125">CW 製品は "シリアル番号のキャプチャ" 機能と併用できず、したがって、ピッキング/梱包プロセスの一部としての "ブランク" からシリアル番号への転送プロセスはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-125">Catch weight products cannot be used together with the 'Capture serial number' functionality and thereby the process of transferring from a 'blank' to serial number as part of the picking/packing process is not supported.</span></span>
- <span data-ttu-id="37507-126">CW 商品は、"消費前にシリアルを登録" 機能と併用することはできません。</span><span class="sxs-lookup"><span data-stu-id="37507-126">Catch weight products cannot be used together with the register serials before consumption functionality.</span></span>
- <span data-ttu-id="37507-127">バリアントを有効にされた CW 製品は、"バリアントの測定単位換算" 機能と併用できません。</span><span class="sxs-lookup"><span data-stu-id="37507-127">Catch weight products being variant-enabled cannot be used together with the variant unit of measure conversion functionality.</span></span>
- <span data-ttu-id="37507-128">CW 製品は、小売 "製品キット" としてマークできません。</span><span class="sxs-lookup"><span data-stu-id="37507-128">Catch weight products cannot be marked as being retail 'Product kit'.</span></span>
- <span data-ttu-id="37507-129">CW 製品では、CW 材料取り扱い単位を含む単位順序グループで使用されること、および CW 単位を最も低い順序にすることだけがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="37507-129">Catch weight products only support being used with a unit sequence group with catch weight handling units and having the catch weight unit as the lowest sequence.</span></span>
- <span data-ttu-id="37507-130">CW では、名目数量が 1 より大きくなる CW 単位換算に対する在庫単位のみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="37507-130">Catch weight products only support the inventory unit to catch weight unit conversion resulting in a nominal quantity greater than one.</span></span>
- <span data-ttu-id="37507-131">CW 製品のバーコード設定では、可変重量設定はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-131">Catch weight product barcode setup does not support variable weight setup.</span></span>
 
<span data-ttu-id="37507-132">**注文処理**</span><span class="sxs-lookup"><span data-stu-id="37507-132">**Order processing**</span></span>
- <span data-ttu-id="37507-133">会社間受注処理はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-133">Intercompany order processing is not supported.</span></span>
- <span data-ttu-id="37507-134">ASN 作成 (梱包構造) では、重量情報はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-134">ASN creation (packing structures) does not support weight information.</span></span>
- <span data-ttu-id="37507-135">注文数量は、CW 単位に基づいてのみ維持できます。</span><span class="sxs-lookup"><span data-stu-id="37507-135">The ordering quantity can only be maintained based on the catch weight unit.</span></span>
 
<span data-ttu-id="37507-136">**入庫倉庫処理**</span><span class="sxs-lookup"><span data-stu-id="37507-136">**Inbound warehouse processing**</span></span>
- <span data-ttu-id="37507-137">高度な出荷通知の一部として重量情報はサポートされていないため、登録時には、ライセンス プレートの受取に重量割り当てが必要です。</span><span class="sxs-lookup"><span data-stu-id="37507-137">License plate receiving will require weight assignment during registration because weight information is not supported as part of the advanced shipping notification.</span></span> <span data-ttu-id="37507-138">CW グプ ロセスを使用するときは、CW 単位ごとにタグ番号を手動で割り当てる必要があります。</span><span class="sxs-lookup"><span data-stu-id="37507-138">When using catch weight tag processes, the tag number must be manually assigned per catch weight unit.</span></span>
- <span data-ttu-id="37507-139">混合ライセンス プレートの受取は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-139">Mixed license plate receiving is not supported for catch weight products.</span></span>
 
<span data-ttu-id="37507-140">**在庫および倉庫オペレーション**</span><span class="sxs-lookup"><span data-stu-id="37507-140">**Inventory and warehouse operations**</span></span>
- <span data-ttu-id="37507-141">検査指示の手動作成は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-141">Manual creation of quarantine orders is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-142">作業に関連付けられている在庫の手動移動は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-142">Manual movement of inventory related with work is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-143">ライセンス プレートの連結は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-143">Consolidate license plates is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-144">定期処理タスクの一部としての倉庫の在庫状態の変更は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-144">Warehouse inventory status change  as part of a periodic task is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-145">クエリによって定義された在庫状態の変更は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-145">Change inventory status, defined by a query, is not supported for catch weight products.</span></span> <span data-ttu-id="37507-146">(品質指示の在庫状態の変更もサポートされていません。)</span><span class="sxs-lookup"><span data-stu-id="37507-146">(Quality order inventory status change is not supported, either.)</span></span>
- <span data-ttu-id="37507-147">場所フォームによる手持からの在庫状態の変更は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-147">Inventory status change from on-hand by location form is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-148">倉庫アプリ移動作業の一部としての在庫状態の変更は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-148">Inventory status change as part of warehouse app movement work is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-149">倉庫作業棚卸処理の間の重量の割り当ては、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-149">Assignment of weight during warehouse work counting processing is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-150">倉庫の在庫を初期化するためのライセンス プレートの読み込みは、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-150">License plate loading - to initialize warehouse stock - is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-151">バッチ バランシング プロセスは、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-151">Batch balancing processes are not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-152">マイナスの現物在庫処理は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-152">Negative physical inventory handling is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-153">在庫マーキングの使用は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-153">Use of inventory marking is not supported for catch weight products.</span></span>
 
<span data-ttu-id="37507-154">**出庫倉庫処理**</span><span class="sxs-lookup"><span data-stu-id="37507-154">**Outbound warehouse processing**</span></span>
- <span data-ttu-id="37507-155">クラスター ピッキング機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-155">Cluster picking functionality is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-156">ピッキングと梱包の倉庫処理は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-156">Pick and pack warehouse processing is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-157">作業フォームからの作業の完了は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-157">Work completion from work form is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-158">作業テンプレートで定義されている作業の自動実行は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-158">Automatic execution of work defined on work template is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-159">作業の取り消し機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-159">Reverse work functionality is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-160">コンテナー終了後の作業作成での手動梱包ステーション処理は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-160">Manual packing station processing with work creation after container close is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-161">個数別のスキャン機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-161">Pcs-by-pcs scanning functionality is not supported for catch weight products.</span></span> 
 
<span data-ttu-id="37507-162">**生産処理**</span><span class="sxs-lookup"><span data-stu-id="37507-162">**Production processing**</span></span>
- <span data-ttu-id="37507-163">CW 製品では、フォーミュラ製品のバッチ オーダーのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="37507-163">Only batch orders for formula products are supported for catch weight products.</span></span>
- <span data-ttu-id="37507-164">かんばん機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-164">Kanban functionality is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-165">消費前のシリアルの登録は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-165">Register serials before consumption is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-166">ライセンス プレートの取り消し機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-166">Reverse license plate functionality is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-167">シリアル番号別完了登録レポートは、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-167">Register report as finished by serial number is not supported for catch weight products.</span></span>

<span data-ttu-id="37507-168">**輸送管理処理**</span><span class="sxs-lookup"><span data-stu-id="37507-168">**Transportation management processing**</span></span>
- <span data-ttu-id="37507-169">積荷構築ワークベンチ処理は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-169">Load building workbench processing is not supported for catch weight products.</span></span>
- <span data-ttu-id="37507-170">輸送要求明細行は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-170">Transport request lines are not supported for catch weight products.</span></span> 
 
<span data-ttu-id="37507-171">**倉庫管理での CW 製品の処理に関するその他の制限事項と動作**</span><span class="sxs-lookup"><span data-stu-id="37507-171">**Other restrictions and behaviors for catch weight product processing with warehouse management**</span></span>
- <span data-ttu-id="37507-172">倉庫アプリ処理の一部として CW タグをキャプチャするとき、ワーク フローをキャンセルすることはできません。</span><span class="sxs-lookup"><span data-stu-id="37507-172">When capturing catch weight tags as part of the warehouse app processing, it is not be possible to cancel out of the work flow.</span></span>
- <span data-ttu-id="37507-173">追跡用分析コードを示すようユーザーが要求されないピッキング プロセスでは、重量の割り当ては平均重量に基づいて行われます。</span><span class="sxs-lookup"><span data-stu-id="37507-173">During picking processes where the user will not be prompted to identify tracking dimensions, the weight assignment will be done based on the average weight.</span></span> <span data-ttu-id="37507-174">このプロセスは、たとえば、同じ場所とユーザー プロセス ピッキングで複数の追跡用分析コードの組み合わせを使用すると発生し、その場所に対する追跡用分析コードの値は 1 つだけになります。</span><span class="sxs-lookup"><span data-stu-id="37507-174">This process will happen, for example, when using a mix of tracking dimensions within the same location and user process picking, resulting in only one tracking dimension value left on the location.</span></span>
- <span data-ttu-id="37507-175">倉庫管理プロセスが有効な CW 製品について在庫を引き当てると、それが手持ちの最後の取扱数量であったとしても、引当は定義されている最小重量に基づいて行われます。</span><span class="sxs-lookup"><span data-stu-id="37507-175">When reserving inventory for a warehouse management process-enabled catch weight product, the reservation will be done based on the defined minimum weight even though this is the last handling quantity on hand.</span></span> <span data-ttu-id="37507-176">これは、倉庫管理プロセスが有効ではない品目の場合とは異なる動作です。</span><span class="sxs-lookup"><span data-stu-id="37507-176">This is a different behavior than for non-warehouse management process-enabled items.</span></span> 
- <span data-ttu-id="37507-177">キャパシティ計算の一部として重量を使用するすべてのプロセスでは (ウェーブのしきい値、作業の最大分割、コンテナー最大、場所の負荷キャパシティなど)、在庫の実際の重量は使用されず、製品に対して定義されている現物取り扱い重量に基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="37507-177">All processes that use the weight as part of capacity calculations (wave thresholds, work maximum breaks, container maximums, location load capacities, and so on) will not use the actual weight of the inventory, but be based on the physical handling weight defined for the product.</span></span>
- <span data-ttu-id="37507-178">一般的な小売機能は、CW 製品ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="37507-178">Retail functionality in general is not supported for catch weight products.</span></span>
 
### <a name="the-catch-weight-tags-functionality-is-currently-only-supported-as-part-of-the-following-scenarios"></a><span data-ttu-id="37507-179">現在、CW タグ機能は、次のシナリオの一部としてのみサポートされています。</span><span class="sxs-lookup"><span data-stu-id="37507-179">The catch weight tags functionality is currently only supported as part of the following scenarios:</span></span>
- <span data-ttu-id="37507-180">発注書倉庫アプリ受取処理。</span><span class="sxs-lookup"><span data-stu-id="37507-180">Purchase order warehouse app receiving processing.</span></span>
- <span data-ttu-id="37507-181">積荷入庫倉庫アプリ処理。</span><span class="sxs-lookup"><span data-stu-id="37507-181">Load receiving warehouse app processing.</span></span>
- <span data-ttu-id="37507-182">発注書積荷に関連するライセンス プレート受取では、受取プロセスの間に重量の割り当てが要求されますが、移動オーダー受取プロセスでは、重量は移動オーダー出荷データのものが使用されます。</span><span class="sxs-lookup"><span data-stu-id="37507-182">License plate receiving related to a purchase order load will request weight assignment during the receiving process, whereas for the transfer order receiving process, the weight will be used from the transfer order shipment data.</span></span>
- <span data-ttu-id="37507-183">非倉庫管理プロセス倉庫からの移動オーダー品目と明細の入庫。</span><span class="sxs-lookup"><span data-stu-id="37507-183">Transfer order item and line receiving coming from a non-warehouse management process warehouse.</span></span>    
- <span data-ttu-id="37507-184">販売返品注文の受取処理では CW タグを記録できますが、それらが特定の販売注文明細行に関連してもともと出荷されたタグであったかどうかは検証されません。</span><span class="sxs-lookup"><span data-stu-id="37507-184">Sales return order receive processing will be able to record catch weight tags, but it will not be validated if these were the tags that originally got shipped related to a particular sales order line.</span></span>
- <span data-ttu-id="37507-185">倉庫アプリによる在庫状態の変更。</span><span class="sxs-lookup"><span data-stu-id="37507-185">Inventory status change via the warehouse app.</span></span>
- <span data-ttu-id="37507-186">倉庫アプリによる倉庫間の移動。</span><span class="sxs-lookup"><span data-stu-id="37507-186">Warehouse transfer via the warehouse app.</span></span>
- <span data-ttu-id="37507-187">倉庫アプリによる調整内および調整外。</span><span class="sxs-lookup"><span data-stu-id="37507-187">Adjustment in and out via the warehouse app.</span></span>
- <span data-ttu-id="37507-188">販売注文および移動オーダーのピッキング作業処理。</span><span class="sxs-lookup"><span data-stu-id="37507-188">Sales and transfer order picking work processing.</span></span> <span data-ttu-id="37507-189">(生産コンポーネントのピッキングでは CW タグの記録がサポートされていないことに注意してください。)</span><span class="sxs-lookup"><span data-stu-id="37507-189">(Note that production component picking does not support catch weight tag recording.)</span></span>
- <span data-ttu-id="37507-190">積荷明細行からのピッキング済数量の削減 (コンテナー使用の有無にかかわらず)。</span><span class="sxs-lookup"><span data-stu-id="37507-190">Reducing picked quantities from load lines (with and without container usage).</span></span>
- <span data-ttu-id="37507-191">梱包ステーションでのコンテナーへの製品の梱包。</span><span class="sxs-lookup"><span data-stu-id="37507-191">Packing of products into containers at packing station.</span></span>
- <span data-ttu-id="37507-192">コンテナーの再オープン。</span><span class="sxs-lookup"><span data-stu-id="37507-192">Reopening of containers.</span></span>
- <span data-ttu-id="37507-193">倉庫アプリによる完了したフォーミュラ製品としての報告。</span><span class="sxs-lookup"><span data-stu-id="37507-193">Report as finished formula products via warehouse app.</span></span>
- <span data-ttu-id="37507-194">倉庫アプリによる輸送積荷処理。</span><span class="sxs-lookup"><span data-stu-id="37507-194">Transport load processing via warehouse app.</span></span>


