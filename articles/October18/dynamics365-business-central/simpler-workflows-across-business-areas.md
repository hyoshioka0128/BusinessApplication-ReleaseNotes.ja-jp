---
title: ビジネス エリア全体で簡素化されたワークフロー
description: さまざまな一般的なユーザー タスクがより簡単になりました。
author: bnielse
manager: edupont04
ms.date: 11/07/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.openlocfilehash: 848e07d6bb4043fd2fbee1f753b73e3e94fc9b4c
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199848"
---
# <a name="simpler-workflows-across-business-areas"></a><span data-ttu-id="614aa-103">ビジネス エリア全体で簡素化されたワークフロー</span><span class="sxs-lookup"><span data-stu-id="614aa-103">Simpler workflows across business areas</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="simplified-payment-process"></a><span data-ttu-id="614aa-104">簡略化された支払プロセス</span><span class="sxs-lookup"><span data-stu-id="614aa-104">Simplified payment process</span></span>

<span data-ttu-id="614aa-105">お客様からのフィードバックに基づいて支払プロセスが改善され、顧客/仕入先/従業員帳エントリ ページへの検索可能なエイリアス (代替キーワード) の追加と、選択されたエントリを仕訳に転送する支払作成アクションの導入が行われました。</span><span class="sxs-lookup"><span data-stu-id="614aa-105">Based on customer feedback we introduced improvements into payment process, by adding searchable aliases (alternate keywords) for customer/vendor/employee ledger entries pages and by introducing a Create Payment action that transfer selected entries to journals.</span></span> <span data-ttu-id="614aa-106">その結果、以下のことがより簡単になります。</span><span class="sxs-lookup"><span data-stu-id="614aa-106">As a result, it is easier to:</span></span>

* <span data-ttu-id="614aa-107">未処理の仕入先請求書の表示。</span><span class="sxs-lookup"><span data-stu-id="614aa-107">View outstanding vendor invoices.</span></span> <span data-ttu-id="614aa-108">支払うものの選択。</span><span class="sxs-lookup"><span data-stu-id="614aa-108">Select and choose which to pay.</span></span> <span data-ttu-id="614aa-109">支払仕訳帳の自動記入。</span><span class="sxs-lookup"><span data-stu-id="614aa-109">Automatically fill in payment journal.</span></span>
* <span data-ttu-id="614aa-110">未処理の顧客請求書の表示、支払受け取りの選択。</span><span class="sxs-lookup"><span data-stu-id="614aa-110">View outstanding customer invoices, Select and choose to receive payment.</span></span> <span data-ttu-id="614aa-111">現金領収仕訳帳の自動記入。</span><span class="sxs-lookup"><span data-stu-id="614aa-111">Automatically fill in cash receipts journal.</span></span>

### <a name="resources"></a><span data-ttu-id="614aa-112">リソース</span><span class="sxs-lookup"><span data-stu-id="614aa-112">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/receivables-how-reconcile-customer-payments-list-unpaid-sales-documents#to-register-customer-payments-individually

## <a name="simplified-journals"></a><span data-ttu-id="614aa-113">簡略化された仕訳帳</span><span class="sxs-lookup"><span data-stu-id="614aa-113">Simplified journals</span></span>

<span data-ttu-id="614aa-114">新しいユーザーからのフィードバックに基づいて、仕訳帳の 2 つの表示モードのサポートを追加することで、一般仕訳帳、仕入仕訳帳、売上仕訳帳のページのレイアウトを簡素化しました。</span><span class="sxs-lookup"><span data-stu-id="614aa-114">Based on feedback from new users we simplified layout of the General, Purchase, and Sales Journal pages by adding support of two view modes for journals.</span></span>

<span data-ttu-id="614aa-115">簡素化されたビュー:</span><span class="sxs-lookup"><span data-stu-id="614aa-115">Simplified view:</span></span>

* <span data-ttu-id="614aa-116">列数の削減</span><span class="sxs-lookup"><span data-stu-id="614aa-116">Fewer columns</span></span>
* <span data-ttu-id="614aa-117">一般仕訳帳: 借方/貸方記入フィールド</span><span class="sxs-lookup"><span data-stu-id="614aa-117">General Journal: Debit/Credit entry fields</span></span>
* <span data-ttu-id="614aa-118">仕入仕訳帳: 購入に固有の勘定タイプのみを表示します</span><span class="sxs-lookup"><span data-stu-id="614aa-118">Purchase Journal: Show only account types specific to purchases</span></span>
* <span data-ttu-id="614aa-119">売上仕訳帳: 販売に固有の勘定タイプのみを表示します</span><span class="sxs-lookup"><span data-stu-id="614aa-119">Sales Journal: Show only account types specific to sales</span></span>

<span data-ttu-id="614aa-120">簡略化されたビューにより、新しいユーザーでもデータ入力が容易になり、高度なシナリオを処理するために標準ビューに簡単に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="614aa-120">Simplified view enables easier data entry for new users and can be easily switched to standard view for processing of advanced scenarios.</span></span>

## <a name="remind-user-to-release-purchasesales-order"></a><span data-ttu-id="614aa-121">発注書/販売注文のリリースをユーザーに通知</span><span class="sxs-lookup"><span data-stu-id="614aa-121">Remind user to release purchase/sales order</span></span>

<span data-ttu-id="614aa-122">発注書または販売注文のリリースをユーザーが忘れるのはよくあることであり、結果としてドキュメントを倉庫処理に使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="614aa-122">It is a common case when user forgets to release a sales or purchase order, which results in the documents not being available for warehouse handling.</span></span> <span data-ttu-id="614aa-123">次の条件に基づいて、ドキュメントを閉じるときに、ユーザーに対する新しいリリースの警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="614aa-123">A new release warning for users will be displayed when closing a document, based on the following conditions:</span></span>

* <span data-ttu-id="614aa-124">注文がまだリリースされていません。</span><span class="sxs-lookup"><span data-stu-id="614aa-124">The order is not released yet.</span></span>
* <span data-ttu-id="614aa-125">数量フィールドが記入された行が存在します。</span><span class="sxs-lookup"><span data-stu-id="614aa-125">Lines with the Quantity field filled in exist.</span></span>
* <span data-ttu-id="614aa-126">場所コード フィールドが行に入力されています。</span><span class="sxs-lookup"><span data-stu-id="614aa-126">The Location Code field is filled in on the lines.</span></span>
* <span data-ttu-id="614aa-127">場所には集荷/出荷または受入/プット アウェイが必要です。</span><span class="sxs-lookup"><span data-stu-id="614aa-127">The location requires Pick/Ship or Receive/Put-away.</span></span>

## <a name="warning-about-unposted-document-is-enabled-for-invoices-only-by-default"></a><span data-ttu-id="614aa-128">請求書に対してのみ有効な未転記ドキュメントに関する警告 (既定)</span><span class="sxs-lookup"><span data-stu-id="614aa-128">Warning about unposted document is enabled for invoices only (by default)</span></span>

<span data-ttu-id="614aa-129">未転記ドキュメントに関する警告を調整しました。</span><span class="sxs-lookup"><span data-stu-id="614aa-129">We adjusted the warning about unposted documents.</span></span> <span data-ttu-id="614aa-130">未転記ドキュメントに関する警告のための高度なフィルタリングを追加し、既定のフィルターを "ドキュメントの種類" = 請求書に設定しました。つまり、既定では請求書のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="614aa-130">We added advanced filtering for warning about unposted document and set default filter to “Document Type” = Invoice, which means that it by default only shows up for invoices.</span></span> <span data-ttu-id="614aa-131">ユーザーはこれを変更して他のドキュメントの種類を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="614aa-131">Users can change this to include other document types.</span></span>

## <a name="improved-handling-of-situations-when-currency-exchange-rates-are-missing"></a><span data-ttu-id="614aa-132">為替レートがない状況の処理の改善</span><span class="sxs-lookup"><span data-stu-id="614aa-132">Improved handling of situations when currency exchange rates are missing</span></span>

<span data-ttu-id="614aa-133">利用統計情報に基づいて、ユーザーは新しい通貨を作成したときに為替レートの追加を忘れることが多く、ドキュメントで通貨を選択しようとするとエラーになることがわかりました。</span><span class="sxs-lookup"><span data-stu-id="614aa-133">Based on telemetry we discovered that users often create new currency but forget to add exchange rates, which leads to errors when user tries to select the currency in documents.</span></span> <span data-ttu-id="614aa-134">ユーザーのエクスペリエンスを向上させるため、ユーザーを為替レート ページに誘導して為替レートの不足を修正できる確認ダイアログを追加しました。</span><span class="sxs-lookup"><span data-stu-id="614aa-134">To improve users’ experience, we added a confirmation dialogue that guides the user to the Exchange Rates page, so user can fix missing exchange rates.</span></span> <span data-ttu-id="614aa-135">また、新しい通貨コードを作成するときの為替レートの不足に関する注意を追加しました。</span><span class="sxs-lookup"><span data-stu-id="614aa-135">We also added reminder about missing exchange rates when creating a new currency code.</span></span>

## <a name="copy-account-schedules"></a><span data-ttu-id="614aa-136">会計スケジュールのコピー</span><span class="sxs-lookup"><span data-stu-id="614aa-136">Copy account schedules</span></span>

<span data-ttu-id="614aa-137">ユーザーは、詳細な損益計算書や要約損益計算書など、同じ財務レポートのわずかに異なるバージョンを実行することがよくあります。</span><span class="sxs-lookup"><span data-stu-id="614aa-137">Users often run the same financial report in slightly different versions, such as a detailed income statement or a summary income statement.</span></span> <span data-ttu-id="614aa-138">会計スケジュール ページにコピー アクションが追加され、ユーザーは会計スケジュールを最初から作成するのではなく、会計スケジュールをコピーして編集できるので、多くの時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="614aa-138">We added the Copy action on the Account Schedules page, so user can save a lot of time copying an account schedule and edit it, rather than build an account schedule from scratch.</span></span> <span data-ttu-id="614aa-139">また、"システム" 会計スケジュールに関する警告がダイアログに変更されたため、ユーザーは "システム" 会計スケジュールを確認するかコピーを編集するかを決定することができます。</span><span class="sxs-lookup"><span data-stu-id="614aa-139">We also transformed warning on “system” account schedules into dialog, so user can decide whether they want to review the “system” account schedule or edit a copy.</span></span>

### <a name="resources"></a><span data-ttu-id="614aa-140">リソース</span><span class="sxs-lookup"><span data-stu-id="614aa-140">Resources</span></span>
https://docs.microsoft.com/en-us/dynamics365/business-central/bi-how-work-account-schedule

## <a name="check-avail-period-calc-setting-is-not-needed-for-basic-available-to-order-scenarios"></a><span data-ttu-id="614aa-141">利用可能な期間の計算の確認の設定が基本的な注文可能シナリオには必要ない</span><span class="sxs-lookup"><span data-stu-id="614aa-141">Check-Avail. Period Calc. setting is not needed for basic Available-to-Order scenarios</span></span>

<span data-ttu-id="614aa-142">ユーザーは、受注から在庫が少ないことを通知されたときに最短入荷日フィールドが更新されない理由を忘れることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="614aa-142">Users often forget why the Earliest Receipt Date field is not updated when notified about low inventory from sales orders.</span></span> <span data-ttu-id="614aa-143">会社情報ページで利用可能な期間の計算の確認をオプションにしたため、入庫予定があるときに最短入荷日フィールドが常に計算されます。</span><span class="sxs-lookup"><span data-stu-id="614aa-143">We made Check-Avail. Period Calc. setting optional on the Company Information page, so the Earliest Receipt Date field is always calculated when there is expected inventory supplies.</span></span>

## <a name="eu-shipment-method-code-support-for-intrastat"></a><span data-ttu-id="614aa-144">Intrastat に対する EU 出荷方法コードのサポート</span><span class="sxs-lookup"><span data-stu-id="614aa-144">EU Shipment method code support for Intrastat</span></span>

<span data-ttu-id="614aa-145">EU Intrastat レポート定義には、EU ではオプションであるが、EU 内の一部の国では必須または条件付きで必須とされる多くのデータ要素が含まれています。</span><span class="sxs-lookup"><span data-stu-id="614aa-145">EU Intrastat report definition contains a number of data elements that are optional in EU but are required or conditionally required in some countries inside EU.</span></span> <span data-ttu-id="614aa-146">必須パラメータの強制は、ローカル バージョンでの一般的な変更でした。</span><span class="sxs-lookup"><span data-stu-id="614aa-146">The enforcing mandatory parameters was a common change in local versions.</span></span> <span data-ttu-id="614aa-147">したがって、これが必須または条件付き必須である国でローカライズする必要がないようにする新しい構成設定が追加されました。</span><span class="sxs-lookup"><span data-stu-id="614aa-147">We have, therefore, added a new configuration setting that removes the need for localizations in countries where this is required or conditionally required.</span></span>  

## <a name="address-format-consolidation"></a><span data-ttu-id="614aa-148">住所形式の統一</span><span class="sxs-lookup"><span data-stu-id="614aa-148">Address format consolidation</span></span>

<span data-ttu-id="614aa-149">住所の書式設定に関するさまざまな要件を分析して調整し、現在は次のようになっています。</span><span class="sxs-lookup"><span data-stu-id="614aa-149">We analyzed and aligned different requirements for formatting of addresses, so with current:</span></span>  

* <span data-ttu-id="614aa-150">郡フィールドのキャプションを州/地域/郡などに動的に更新することができます ([国/地域] ページの新しい市区郡名のフィールド)</span><span class="sxs-lookup"><span data-stu-id="614aa-150">We can dynamically update the County field caption to State/Region/Province etc. (New County Name field on the Country/Region page)</span></span>
* <span data-ttu-id="614aa-151">対応する国/地域コードの住所形式に応じて郡フィールドの表示を動的に変更できます</span><span class="sxs-lookup"><span data-stu-id="614aa-151">We can dynamically change the visibility of the County field dependent on the address format of the corresponding country/region code</span></span>
* <span data-ttu-id="614aa-152">あらかじめ定義された文字列に加えて、カスタム住所形式のオプションと、[国/地域] ページでオプションを作成するためのシンプルなビジュアル デザイナーが追加されました</span><span class="sxs-lookup"><span data-stu-id="614aa-152">In addition to predefined strings we added Custom Address Format option, and a simple visual designer to build the option in the Countries/Regions page</span></span>

## <a name="cancel-purchase-invoices-posted-from-order"></a><span data-ttu-id="614aa-153">注文から転記された仕入請求書の取り消し</span><span class="sxs-lookup"><span data-stu-id="614aa-153">Cancel purchase invoices posted from order</span></span>

<span data-ttu-id="614aa-154">機能を販売部門と連携させ、ユーザーが間違った転記を修正できるよう、発注書に関連する転記済仕入請求書のキャンセル アクションが有効にされました。</span><span class="sxs-lookup"><span data-stu-id="614aa-154">To align functionality with sales part and help user to fix wrong posting we enabled the Cancel action on posted purchase invoices related to purchase orders.</span></span>

## <a name="usca-users-can-update-tax-amount-on-general-journal-lines"></a><span data-ttu-id="614aa-155">US/CA: ユーザーは一般仕訳帳明細行で税額を更新できる</span><span class="sxs-lookup"><span data-stu-id="614aa-155">US/CA: Users can update Tax Amount on general journal lines</span></span>

<span data-ttu-id="614aa-156">機能を VAT に合わせて、ユーザーが税金差額を処理できるようにするため、US/CA ユーザーが一般仕訳帳明細行で税額を更新できるしました。</span><span class="sxs-lookup"><span data-stu-id="614aa-156">To align functionality with VAT and allow user to handle tax differences we enabled US/CA users to update the Tax Amount field on a general journal line.</span></span>

## <a name="items-purchased-for-specific-jobs-use-fixed-application"></a><span data-ttu-id="614aa-157">特定の職務のために購入されたアイテムでの固定申請の使用</span><span class="sxs-lookup"><span data-stu-id="614aa-157">Items purchased for specific jobs use Fixed application</span></span>

<span data-ttu-id="614aa-158">会計の観点から、在庫の変更を評価するには特定の申請を使用するのが好ましい方法です。</span><span class="sxs-lookup"><span data-stu-id="614aa-158">From an accounting perspective, a specific application is the preferred way to value any changes of your stock.</span></span> <span data-ttu-id="614aa-159">したがって、職務用にアイテムを直接購入したときは、原価計算方法が平均であっても、固定申請が使用されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="614aa-159">So, when Items are purchased directly for jobs, they are now consumed with Fixed application even if the costing method is Average.</span></span> <span data-ttu-id="614aa-160">また、その方が購買返品の処理がはるかに簡単です (それでも、マイナス調整に申請ワークシートをリンクする必要があります)</span><span class="sxs-lookup"><span data-stu-id="614aa-160">It is also much easier to handle purchase returns (Still requires application worksheet to link negative adjustments)</span></span>

## <a name="drill-down-on-the-inventory-field-on-the-item-card"></a><span data-ttu-id="614aa-161">アイテム カードの在庫フィールドでのドリルダウン</span><span class="sxs-lookup"><span data-stu-id="614aa-161">Drill-down on the Inventory field on the item card</span></span>

<span data-ttu-id="614aa-162">アイテム カードの "在庫 (手持ち)" フィールドに、在庫レベルの迅速な調整を行う AssistEdit と、取引履歴の簡単な調査のための DrillDown の両方が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="614aa-162">The Inventory (Available) field in Item card now contains both an AssistEdit to do quick adjustment of inventory level and DrillDown for easy investigation of the transaction history.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="614aa-163">フィードバック</span><span class="sxs-lookup"><span data-stu-id="614aa-163">Tell us what you think</span></span>
<span data-ttu-id="614aa-164">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="614aa-164">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="614aa-165">Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="614aa-165">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>
