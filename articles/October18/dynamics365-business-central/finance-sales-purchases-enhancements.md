---
title: 財務、営業、購買の拡張
description: 財務、営業、購買機能が向上しました。
author: bnielse
manager: edupont04
ms.date: 11/07/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.openlocfilehash: f240b1860496e3d0f2a1d5e8f7ac8672836933c6
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199828"
---
# <a name="enhancements-to-finance-sales-and-purchasing"></a><span data-ttu-id="93856-103">財務、営業、購買の拡張</span><span class="sxs-lookup"><span data-stu-id="93856-103">Enhancements to Finance, Sales, and Purchasing</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="non-inventory-items"></a><span data-ttu-id="93856-104">非在庫品目</span><span class="sxs-lookup"><span data-stu-id="93856-104">Non-inventory items</span></span>

<span data-ttu-id="93856-105">Business Central では、非在庫品目 (購入または販売できるが在庫品目として保持しない品目) がサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="93856-105">Business Central now offers support for non-inventory items: Item that you can buy or sell but don’t want to keep as inventory items.</span></span>

<span data-ttu-id="93856-106">*例: オフィス消耗品、製造/サービス シナリオでの金属 (kg 単位で購入し、単位で消費)、イチゴを路上販売する農家。*</span><span class="sxs-lookup"><span data-stu-id="93856-106">*Examples: Consumed office supplies, metal-ware in manufacturing/service scenarios (buy in kg, consume units), or farmer selling strawberries at the roadside.*</span></span>

<span data-ttu-id="93856-107">非在庫品目では、価格/割引構造、数量単位、既定の仕入先と追加仕入先、詳細説明、交換品目、税目番号などの品目機能を利用できますが、在庫数量と金額の追跡は不要です。</span><span class="sxs-lookup"><span data-stu-id="93856-107">With non-inventory items you can benefit from item capabilities, such as pricing/discount structure, units of measure, default vendors and additional vendors, extended descriptions, replacements, tariff numbers, etc., but do not involve tracking of inventory quantity and value.</span></span> <span data-ttu-id="93856-108">非在庫品目では、以下の機能がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="93856-108">Non-inventory items support following features:</span></span>

* <span data-ttu-id="93856-109">営業</span><span class="sxs-lookup"><span data-stu-id="93856-109">Sales</span></span>
* <span data-ttu-id="93856-110">購買</span><span class="sxs-lookup"><span data-stu-id="93856-110">Purchasing</span></span>
* <span data-ttu-id="93856-111">作業消費</span><span class="sxs-lookup"><span data-stu-id="93856-111">Job Consumption</span></span>
* <span data-ttu-id="93856-112">サービス消費</span><span class="sxs-lookup"><span data-stu-id="93856-112">Service Consumption</span></span>
* <span data-ttu-id="93856-113">アセンブリ消費</span><span class="sxs-lookup"><span data-stu-id="93856-113">Assembly Consumption</span></span>
* <span data-ttu-id="93856-114">生産消費</span><span class="sxs-lookup"><span data-stu-id="93856-114">Production Consumption</span></span>

### <a name="resources-httpsdocsmicrosoftcomen-usdynamics365business-centralinventory-about-item-typeshttpsdocsmicrosoftcomen-usdynamics365business-centralinventory-about-item-types"></a><span data-ttu-id="93856-115">リソース [https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types](https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types)</span><span class="sxs-lookup"><span data-stu-id="93856-115">Resources [https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types](https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types)</span></span>  

## <a name="blocked-items-hidden-in-lookups"></a><span data-ttu-id="93856-116">ルックアップで非表示になっているブロックされた品目</span><span class="sxs-lookup"><span data-stu-id="93856-116">Blocked items hidden in lookups</span></span>

<span data-ttu-id="93856-117">時間の経過と共に、使用されないブロックされた品目が数千になることがあります。</span><span class="sxs-lookup"><span data-stu-id="93856-117">Over time customers can have thousands of blocked items that are not to be used.</span></span> <span data-ttu-id="93856-118">しかし、販売ドキュメントに品目を追加する際に、これらは依然としてルックアップに表示されます。</span><span class="sxs-lookup"><span data-stu-id="93856-118">However, they still show up in lookups when adding items to sales documents.</span></span> <span data-ttu-id="93856-119">そのため品目の一覧が長くなりすぎて、販売できる品目が混乱することになります。</span><span class="sxs-lookup"><span data-stu-id="93856-119">This makes the list of items too long and causes confusion about which items can be sold.</span></span>

<span data-ttu-id="93856-120">10 月のリリースでは、ブロックされた品目は複数の仕訳帳とドキュメントのルックアップで非表示になります。</span><span class="sxs-lookup"><span data-stu-id="93856-120">With the October release, blocked items are hidden in lookups in multiple journals and documents.</span></span>

### <a name="resources"></a><span data-ttu-id="93856-121">リソース</span><span class="sxs-lookup"><span data-stu-id="93856-121">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-how-block-items

## <a name="block-items-from-sales-and-purchasing"></a><span data-ttu-id="93856-122">販売と購買からの品目のブロック</span><span class="sxs-lookup"><span data-stu-id="93856-122">Block Items from Sales and Purchasing</span></span>

<span data-ttu-id="93856-123">特定の品目に対して許可される取引をより柔軟に指定できます。</span><span class="sxs-lookup"><span data-stu-id="93856-123">To have more flexibility in specifying which transactions are allowed for specific items.</span></span> <span data-ttu-id="93856-124">品目が販売明細行または購買注文明細行に入力されないようにしたり、その品目がどの取引でも転記されないようにブロックしたりできます。</span><span class="sxs-lookup"><span data-stu-id="93856-124">You can block an item from being entered on sales or purchase lines, and you can block it from being posted in any transaction.</span></span>

### <a name="resources"></a><span data-ttu-id="93856-125">リソース</span><span class="sxs-lookup"><span data-stu-id="93856-125">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-how-block-items

## <a name="updated-reports-layout"></a><span data-ttu-id="93856-126">更新されたレポート レイアウト</span><span class="sxs-lookup"><span data-stu-id="93856-126">Updated reports layout</span></span>

<span data-ttu-id="93856-127">頻繁に使用されるレポートは、レイアウトが更新され、よりモダンな外観になっています。</span><span class="sxs-lookup"><span data-stu-id="93856-127">Frequently used reports have gotten a layout refresh and a more modern look.</span></span>  

|<span data-ttu-id="93856-128">レポート ID</span><span class="sxs-lookup"><span data-stu-id="93856-128">Report ID</span></span>|<span data-ttu-id="93856-129">名前</span><span class="sxs-lookup"><span data-stu-id="93856-129">Name</span></span>|
|---------|----|
|<span data-ttu-id="93856-130">1</span><span class="sxs-lookup"><span data-stu-id="93856-130">1</span></span>|<span data-ttu-id="93856-131">勘定科目表</span><span class="sxs-lookup"><span data-stu-id="93856-131">Chart of Accounts</span></span>|
|<span data-ttu-id="93856-132">2</span><span class="sxs-lookup"><span data-stu-id="93856-132">2</span></span>|<span data-ttu-id="93856-133">一般仕訳帳 - テスト</span><span class="sxs-lookup"><span data-stu-id="93856-133">General Journal - Test</span></span>|
|<span data-ttu-id="93856-134">3</span><span class="sxs-lookup"><span data-stu-id="93856-134">3</span></span>|<span data-ttu-id="93856-135">G/L 登録</span><span class="sxs-lookup"><span data-stu-id="93856-135">G/L Register</span></span>|
|<span data-ttu-id="93856-136">4</span><span class="sxs-lookup"><span data-stu-id="93856-136">4</span></span>|<span data-ttu-id="93856-137">詳細な試算表</span><span class="sxs-lookup"><span data-stu-id="93856-137">Detail Trial Balance</span></span>|
|<span data-ttu-id="93856-138">5</span><span class="sxs-lookup"><span data-stu-id="93856-138">5</span></span>|<span data-ttu-id="93856-139">売掛金/買掛金</span><span class="sxs-lookup"><span data-stu-id="93856-139">Receivables-Payables</span></span>|
|<span data-ttu-id="93856-140">6</span><span class="sxs-lookup"><span data-stu-id="93856-140">6</span></span>|<span data-ttu-id="93856-141">試算表</span><span class="sxs-lookup"><span data-stu-id="93856-141">Trial Balance</span></span>|
|<span data-ttu-id="93856-142">8</span><span class="sxs-lookup"><span data-stu-id="93856-142">8</span></span>|<span data-ttu-id="93856-143">予算</span><span class="sxs-lookup"><span data-stu-id="93856-143">Budget</span></span>|
|<span data-ttu-id="93856-144">9</span><span class="sxs-lookup"><span data-stu-id="93856-144">9</span></span>|<span data-ttu-id="93856-145">試算表/予算</span><span class="sxs-lookup"><span data-stu-id="93856-145">Trial Balance/Budget</span></span>|
|<span data-ttu-id="93856-146">25</span><span class="sxs-lookup"><span data-stu-id="93856-146">25</span></span>|<span data-ttu-id="93856-147">会計スケジュール</span><span class="sxs-lookup"><span data-stu-id="93856-147">Account Schedule</span></span>|
|<span data-ttu-id="93856-148">38</span><span class="sxs-lookup"><span data-stu-id="93856-148">38</span></span>|<span data-ttu-id="93856-149">期間別試算表</span><span class="sxs-lookup"><span data-stu-id="93856-149">Trial Balance by Period</span></span>|
|<span data-ttu-id="93856-150">101</span><span class="sxs-lookup"><span data-stu-id="93856-150">101</span></span>|<span data-ttu-id="93856-151">顧客 - 一覧</span><span class="sxs-lookup"><span data-stu-id="93856-151">Customer - List</span></span>|
|<span data-ttu-id="93856-152">103</span><span class="sxs-lookup"><span data-stu-id="93856-152">103</span></span>|<span data-ttu-id="93856-153">顧客登録</span><span class="sxs-lookup"><span data-stu-id="93856-153">Customer Register</span></span>|
|<span data-ttu-id="93856-154">107</span><span class="sxs-lookup"><span data-stu-id="93856-154">107</span></span>|<span data-ttu-id="93856-155">顧客 - 受注の概要</span><span class="sxs-lookup"><span data-stu-id="93856-155">Customer - Order Summary</span></span>|
|<span data-ttu-id="93856-156">108</span><span class="sxs-lookup"><span data-stu-id="93856-156">108</span></span>|<span data-ttu-id="93856-157">顧客 - 受注の詳細</span><span class="sxs-lookup"><span data-stu-id="93856-157">Customer - Order Detail</span></span>|
|<span data-ttu-id="93856-158">111</span><span class="sxs-lookup"><span data-stu-id="93856-158">111</span></span>|<span data-ttu-id="93856-159">顧客 - 上位 10 リスト</span><span class="sxs-lookup"><span data-stu-id="93856-159">Customer - Top 10 List</span></span>|
|<span data-ttu-id="93856-160">112</span><span class="sxs-lookup"><span data-stu-id="93856-160">112</span></span>|<span data-ttu-id="93856-161">販売統計</span><span class="sxs-lookup"><span data-stu-id="93856-161">Sales Statistics</span></span>|
|<span data-ttu-id="93856-162">113</span><span class="sxs-lookup"><span data-stu-id="93856-162">113</span></span>|<span data-ttu-id="93856-163">顧客/品目販売</span><span class="sxs-lookup"><span data-stu-id="93856-163">Customer/Item Sales</span></span>|
|<span data-ttu-id="93856-164">114</span><span class="sxs-lookup"><span data-stu-id="93856-164">114</span></span>|<span data-ttu-id="93856-165">営業担当者 - 販売統計</span><span class="sxs-lookup"><span data-stu-id="93856-165">Salesperson - Sales Statistics</span></span>|
|<span data-ttu-id="93856-166">119</span><span class="sxs-lookup"><span data-stu-id="93856-166">119</span></span>|<span data-ttu-id="93856-167">顧客 - 販売リスト</span><span class="sxs-lookup"><span data-stu-id="93856-167">Customer - Sales List</span></span>|
|<span data-ttu-id="93856-168">120</span><span class="sxs-lookup"><span data-stu-id="93856-168">120</span></span>|<span data-ttu-id="93856-169">指定の期間に達している売掛金勘定</span><span class="sxs-lookup"><span data-stu-id="93856-169">Aged Accounts Receivable</span></span>|
|<span data-ttu-id="93856-170">129</span><span class="sxs-lookup"><span data-stu-id="93856-170">129</span></span>|<span data-ttu-id="93856-171">顧客 - 試算表</span><span class="sxs-lookup"><span data-stu-id="93856-171">Customer - Trial Balance</span></span>|
|<span data-ttu-id="93856-172">309</span><span class="sxs-lookup"><span data-stu-id="93856-172">309</span></span>|<span data-ttu-id="93856-173">仕入先 - 購買リスト</span><span class="sxs-lookup"><span data-stu-id="93856-173">Vendor - Purchase List</span></span>|
|<span data-ttu-id="93856-174">321</span><span class="sxs-lookup"><span data-stu-id="93856-174">321</span></span>|<span data-ttu-id="93856-175">仕入先 - 現在までの残高</span><span class="sxs-lookup"><span data-stu-id="93856-175">Vendor - Balance to Date</span></span>|
|<span data-ttu-id="93856-176">329</span><span class="sxs-lookup"><span data-stu-id="93856-176">329</span></span>|<span data-ttu-id="93856-177">仕入先 - 試算表</span><span class="sxs-lookup"><span data-stu-id="93856-177">Vendor - Trial Balance</span></span>|
|<span data-ttu-id="93856-178">715</span><span class="sxs-lookup"><span data-stu-id="93856-178">715</span></span>|<span data-ttu-id="93856-179">価格表</span><span class="sxs-lookup"><span data-stu-id="93856-179">Price List</span></span>|
|<span data-ttu-id="93856-180">720</span><span class="sxs-lookup"><span data-stu-id="93856-180">720</span></span>|<span data-ttu-id="93856-181">品目/仕入先カタログ</span><span class="sxs-lookup"><span data-stu-id="93856-181">Item/Vendor Catalog</span></span>|
|<span data-ttu-id="93856-182">1001</span><span class="sxs-lookup"><span data-stu-id="93856-182">1001</span></span>|<span data-ttu-id="93856-183">在庫評価</span><span class="sxs-lookup"><span data-stu-id="93856-183">Inventory Valuation</span></span>|
|<span data-ttu-id="93856-184">5605</span><span class="sxs-lookup"><span data-stu-id="93856-184">5605</span></span>|<span data-ttu-id="93856-185">固定資産 - 簿価額 01</span><span class="sxs-lookup"><span data-stu-id="93856-185">Fixed Asset - Book Value 01</span></span>|
|<span data-ttu-id="93856-186">5871</span><span class="sxs-lookup"><span data-stu-id="93856-186">5871</span></span>|<span data-ttu-id="93856-187">品目 - 作成可能 (タイムライン)</span><span class="sxs-lookup"><span data-stu-id="93856-187">Item - Able to Make (Timeline)</span></span>|
|<span data-ttu-id="93856-188">5872</span><span class="sxs-lookup"><span data-stu-id="93856-188">5872</span></span>|<span data-ttu-id="93856-189">BOM 原価共有配分</span><span class="sxs-lookup"><span data-stu-id="93856-189">BOM Cost Share Distribution</span></span>|

## <a name="standard-sales-and-purchase-codes-improvements"></a><span data-ttu-id="93856-190">標準販売および購入コードの改善</span><span class="sxs-lookup"><span data-stu-id="93856-190">Standard Sales and Purchase Codes Improvements</span></span>

<span data-ttu-id="93856-191">同様の情報を持つ販売明細行と購買注文明細行を頻繁に作成する必要がある場合は、定期補充注文など、定期的な販売および購買ドキュメントに挿入できる標準明細を設定できます。</span><span class="sxs-lookup"><span data-stu-id="93856-191">If you often need to create sales and purchase lines with similar information, you can set up standard lines that you can then insert on recurring sales and purchase documents, for example, for recurring replenishment orders.</span></span> <span data-ttu-id="93856-192">10 月のリリースでは、ユーザーは異なる販売または購買ドキュメントを作成する際に、標準の販売コードまたは購買コードの入力方法を指定できます。</span><span class="sxs-lookup"><span data-stu-id="93856-192">With October release users can specify how the standard sales or purchase codes are entered when you create different sales or purchase documents.</span></span>

### <a name="resources"></a><span data-ttu-id="93856-193">リソース</span><span class="sxs-lookup"><span data-stu-id="93856-193">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/sales-how-work-standard-lines

## <a name="fixed-assets-appreciation-posting-available-through-purchase-invoice"></a><span data-ttu-id="93856-194">購買請求書を通じて利用できる固定資産評価の転記</span><span class="sxs-lookup"><span data-stu-id="93856-194">Fixed assets appreciation posting available through purchase invoice</span></span>

<span data-ttu-id="93856-195">現在のリリースでは、ユーザーは固定資産 (FA) の価値上昇を簡単に登録することができます。</span><span class="sxs-lookup"><span data-stu-id="93856-195">With current release user can easily register the value increase of a fixed asset (FA).</span></span> <span data-ttu-id="93856-196">"FA 転記タイプ" フィールドは、これをサポートするために仕入請求書の [増加] の種類で拡張されています。</span><span class="sxs-lookup"><span data-stu-id="93856-196">The FA Posting Type field is extended with Appreciation type on purchase invoices to support this.</span></span> <span data-ttu-id="93856-197">したがって、一般的な仕訳を使用して個別の取引を転記する必要なしに、適切な FA 転記タイプを使用して購買請求書を転記することによって、保守だけでなく固定資産の増加も文書化できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="93856-197">Thus, not only maintenance but also appreciation of fixed assets can now be documented by posting a purchase invoice using the appropriate FA posting type, without need to post separate transactions via general journal.</span></span>

## <a name="multiple-interest-rates-finance-charge-terms"></a><span data-ttu-id="93856-198">複数の金利 (利息条件)</span><span class="sxs-lookup"><span data-stu-id="93856-198">Multiple interest rates (finance charge terms)</span></span>

<span data-ttu-id="93856-199">利息条件に複数の期間別金利のサポートを追加。</span><span class="sxs-lookup"><span data-stu-id="93856-199">Adding support for multiple period-specific interest rates for Finance Charge Terms.</span></span> <span data-ttu-id="93856-200">現在のリリースでは、利息条件とアラーム条件を支払遅延のペナルティとして作成するときに、複数の金利を指定して、異なる期間の異なる金利からペナルティ料金を計算することもできます。</span><span class="sxs-lookup"><span data-stu-id="93856-200">With current release when you create finance charge terms and reminder terms as penalty for delayed payment, you can also specify multiple interest rates so that the penalty fee is calculated from different interest rates in different periods.</span></span>  

## <a name="vat-reconciliation-report-country-consolidation"></a><span data-ttu-id="93856-201">VAT 調整レポート (国の連結)</span><span class="sxs-lookup"><span data-stu-id="93856-201">VAT Reconciliation report (country consolidation)</span></span>

<span data-ttu-id="93856-202">VAT 調整は、VAT 還付が税務当局に提出されるたびに、通常は会計士によって行われます。</span><span class="sxs-lookup"><span data-stu-id="93856-202">VAT reconciliation is often done by accountants each time a VAT return is submitted to the tax authorities.</span></span> <span data-ttu-id="93856-203">W1 バージョンには何年もの間 VAT と G/L の関係がありましたが、それを利用している特定の機能はありません。</span><span class="sxs-lookup"><span data-stu-id="93856-203">W1 version has had a VAT-to-G/L relationship for years, but with no specific feature utilizing it.</span></span> <span data-ttu-id="93856-204">確立された関係に基づいて G/L エントリと VAT エントリを調整する機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="93856-204">We added ability to reconcile G/L entries vs. VAT entries based on established relations.</span></span>

## <a name="archiving-of-blanket-orders-and-document-line-tracking"></a><span data-ttu-id="93856-205">一括発注のアーカイブとドキュメント明細行追跡</span><span class="sxs-lookup"><span data-stu-id="93856-205">Archiving of blanket orders and document line tracking</span></span>

<span data-ttu-id="93856-206">アーカイブ機能を整理し、一括発注を含むように拡張しました。</span><span class="sxs-lookup"><span data-stu-id="93856-206">We aligned archiving functionality and extended it to include Blanket Orders.</span></span> <span data-ttu-id="93856-207">また、追跡を改善したので、ユーザーは注文またはアーカイブされた注文から一括発注を検索することができ、その逆も可能です。</span><span class="sxs-lookup"><span data-stu-id="93856-207">We also improved tracking so user can look up the blanket order from the order or archived order and vice versa.</span></span>

### <a name="resources"></a><span data-ttu-id="93856-208">リソース</span><span class="sxs-lookup"><span data-stu-id="93856-208">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/across-how-to-archive-documents  
https://docs.microsoft.com/en-us/dynamics365/business-central/across-how-to-track-document-lines

## <a name="tell-us-what-you-think"></a><span data-ttu-id="93856-209">フィードバック</span><span class="sxs-lookup"><span data-stu-id="93856-209">Tell us what you think</span></span>
<span data-ttu-id="93856-210">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="93856-210">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="93856-211">Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="93856-211">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>
