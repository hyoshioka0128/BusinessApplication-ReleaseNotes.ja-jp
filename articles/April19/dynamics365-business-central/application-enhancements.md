---
title: アプリケーションの機能強化
description: アプリケーションの機能強化
author: bnielse
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: bnielse
audience: developer, end user, customizer
ms.openlocfilehash: 550755306fa9a20d9f2937a6b8ff50f1a3e15419
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210923"
---
# <a name="application-enhancements"></a><span data-ttu-id="69a46-103">アプリケーションの機能強化</span><span class="sxs-lookup"><span data-stu-id="69a46-103">Application enhancements</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="69a46-104">最もよく使用される部分のパフォーマンスに重点を置いて、引き続きアプリケーションを強化していきます。</span><span class="sxs-lookup"><span data-stu-id="69a46-104">We will continue to enhance the application through our focus on performance in the most used areas.</span></span> <span data-ttu-id="69a46-105">熟練したユーザーは、フォーカス モードで最適化することによりデータの入力が速くなります。</span><span class="sxs-lookup"><span data-stu-id="69a46-105">Proficient users will experience faster entry of data through the optimization with focus mode.</span></span> <span data-ttu-id="69a46-106">同時に、ホーム ページの読み込み速度の最適化など、アプリケーション コードの最適化の結果として応答が速くなり、日常的に使用する主要なアプリケーション シナリオでのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="69a46-106">At the same time, they will experience faster responses as a result of optimizing the application code, such as optimizing how quickly the Home page loads, and performance improvements in key application scenarios that are used on a daily basis.</span></span>

<span data-ttu-id="69a46-107">既定の分析コードの拡張性、単体テスト実行中のメッセージ処理の改善、簡単に拡張できるような運用および計画エンジンのリファクタリングなど、ISV がアプリケーションの拡張を簡単に構築できるようにするための、アプリケーションの改良が続けられています。</span><span class="sxs-lookup"><span data-stu-id="69a46-107">We will continue to improve the application to make it easier for ISVs to build extensions on top of our applications, such as extensibility for default dimensions, better handling of messages during unit test execution, refactoring production and planning engines so that it can be easily extended, and many more.</span></span> <span data-ttu-id="69a46-108">[Business Central のアイデア サイト](https://aka.ms/bcideas)が引き続きアプリケーションの機能強化に関する情報源です。</span><span class="sxs-lookup"><span data-stu-id="69a46-108">The [Business Central Ideas site](https://aka.ms/bcideas) continues to be a source for application enhancements.</span></span> <span data-ttu-id="69a46-109">このリリースには、以下の機能強化が含まれています。</span><span class="sxs-lookup"><span data-stu-id="69a46-109">This release includes the following enhancements:</span></span>

## <a name="write-longer-names-and-descriptions"></a><span data-ttu-id="69a46-110">入力できる名前と説明の文字数の増加</span><span class="sxs-lookup"><span data-stu-id="69a46-110">Write longer names and descriptions</span></span>
<span data-ttu-id="69a46-111">Business Central 全体のすべての**説明**および**名前**フィールドに、最大で 100 文字まで入力できるようになりました (以前は 50 文字)。</span><span class="sxs-lookup"><span data-stu-id="69a46-111">You can now enter up to 100 characters (used to be 50) in all **Description** and **Name** fields across Business Central.</span></span> <span data-ttu-id="69a46-112">この変更は以下に適用されます。</span><span class="sxs-lookup"><span data-stu-id="69a46-112">This change applies to:</span></span>

- <span data-ttu-id="69a46-113">顧客、仕入先、品目、取引先担当者、リソース カードなどのマスター データ カードの**名前**および **説明** フィールド。</span><span class="sxs-lookup"><span data-stu-id="69a46-113">The **Name** and **Description** field on master data cards, such as customer, vendor, item, contact, and resource cards.</span></span>
- <span data-ttu-id="69a46-114">販売注文書、発注書、請求書、見積もりなどの文書の**名前**および **説明** フィールド。</span><span class="sxs-lookup"><span data-stu-id="69a46-114">The **Name** and **Description** field on documents, such as sales and purchase orders, invoices, and quotes.</span></span>
- <span data-ttu-id="69a46-115">一般仕訳帳や品目仕訳帳などの仕訳帳の **説明** フィールド。</span><span class="sxs-lookup"><span data-stu-id="69a46-115">The **Description** field on journals, such as general journal and item journal.</span></span>
- <span data-ttu-id="69a46-116">顧客、仕入先、品目などの元帳エントリの **説明** フィールド。</span><span class="sxs-lookup"><span data-stu-id="69a46-116">The **Description** field on ledger entries, such as customer, vendor, and item ledger entries.</span></span>

<span data-ttu-id="69a46-117">さらに、**測定単位の説明**フィールドに入力できる文字が最大 50 文字に増えました (以前は 10 文字)。</span><span class="sxs-lookup"><span data-stu-id="69a46-117">In addition, you can now enter up to 50 characters (used to be 10) in the **Unit of Measure Description** field.</span></span>

## <a name="use-physical-inventory-orders-to-better-structure-your-physical-inventory-counting"></a><span data-ttu-id="69a46-118">現物在庫注文を使用して現物在庫棚卸をより適切に構成する</span><span class="sxs-lookup"><span data-stu-id="69a46-118">Use physical inventory orders to better structure your physical inventory counting</span></span>
<span data-ttu-id="69a46-119">現物在庫棚卸は、すべての流通会社において 1 年に 1 回または 1 年に複数回発生する、中核的な在庫プロセスの 1 つです。</span><span class="sxs-lookup"><span data-stu-id="69a46-119">Physical inventory counting is one of core inventory processes happening in all distribution companies either once a year or multiple times per year.</span></span> <span data-ttu-id="69a46-120">このプロセスの既存の機能は仕訳帳に基づいているため、大規模な在庫棚卸でプロセスを追跡して作業を分散させることは困難です。</span><span class="sxs-lookup"><span data-stu-id="69a46-120">The existing functionality for this process is based on journals, which makes it difficult to track the process and distribute work in larger-scale inventory counting.</span></span> <span data-ttu-id="69a46-121">**現物在庫注文**ページと**現物在庫記録**ページを使用すると生産性が向上し、既存の機能のギャップに対応できます。</span><span class="sxs-lookup"><span data-stu-id="69a46-121">The **Physical Inventory Order** and **Physical Inventory Recording** pages increase productivity and address gaps in the existing functionality.</span></span> <span data-ttu-id="69a46-122">新しい機能はドイツの一般的なローカル機能に基づいており、これは大規模な在庫棚卸が必要なほとんどすべての実装で広く使用されています。</span><span class="sxs-lookup"><span data-stu-id="69a46-122">The new feature is based on the popular German local functionality, which has been widely used in practically all implementations where larger-scale inventory counting is needed.</span></span>

## <a name="select-multiple-items-to-add-to-a-sales-or-purchase-document"></a><span data-ttu-id="69a46-123">複数の品目を選択して販売ドキュメントまたは購買ドキュメントに追加する</span><span class="sxs-lookup"><span data-stu-id="69a46-123">Select multiple items to add to a sales or purchase document</span></span>
<span data-ttu-id="69a46-124">品目リストで複数の品目を一度に選択して、販売ドキュメントまたは購買ドキュメントに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-124">You can now select multiple items at once from the items list to add to sales or purchase documents.</span></span> <span data-ttu-id="69a46-125">いずれかの販売ドキュメントまたは購買ドキュメントで、**アイテムの選択**明細行アクションを選択します。</span><span class="sxs-lookup"><span data-stu-id="69a46-125">On any sales or purchase document, choose the **Select Items** line action.</span></span>  

<span data-ttu-id="69a46-126">ヒント: **販売および売掛金設定**ページの**既定の品目数量**チェック ボックスをオンにすると、販売ドキュメントに追加されるように選択されているすべての品目の販売明細行の**数量**フィールドが事前入力されます。</span><span class="sxs-lookup"><span data-stu-id="69a46-126">TIP: If you select the **Default Item Quantity** check box on the **Sales & Receivables Setup** page, the **Quantity** field on sales lines will be prefilled for all selected items as they get added to the sales document.</span></span>

## <a name="use-a-sales-quote-validity-policy-to-control-when-sales-quotes-expire"></a><span data-ttu-id="69a46-127">販売見積の有効性ポリシーを使用して売上見積の有効期限を制御する</span><span class="sxs-lookup"><span data-stu-id="69a46-127">Use a sales quote validity policy to control when sales quotes expire</span></span>
<span data-ttu-id="69a46-128">**販売および売掛金設定**ページの**見積有効期限計算**フィールドで、販売見積の**見積有効期限**フィールドの計算に使用される日付式を設定できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-128">You can now set date formula in the **Quote Validity Calculation** field on the **Sales & Receivables Setup** page that will be used to calculate the **Quote Valid Until Date** field on sales quotes.</span></span>

<span data-ttu-id="69a46-129">ヒント: 有効期限が切れた販売見積を確実に削除するには、**期限切れの見積もりの削除**バッチ ジョブを実行します。</span><span class="sxs-lookup"><span data-stu-id="69a46-129">TIP: To make sure that sales quotes with expired quote validity dates are deleted, you can run the **Delete Expired Quotes** batch job.</span></span> <span data-ttu-id="69a46-130">販売見積のアーカイブを有効にすると (**販売および売掛金設定**ページ)、削除された販売見積もアーカイブされるため、顧客から再び問い合わせがあったらアーカイブから復元できます。</span><span class="sxs-lookup"><span data-stu-id="69a46-130">And if you enable sales quote archiving (**Sales & Receivables Setup** page), deleted sales quotes will also be archived, so you can restore them from the archive if customers calls again.</span></span>

## <a name="control-item-and-customer-creation-from-lookups-on-sales-documents"></a><span data-ttu-id="69a46-131">販売ドキュメントのルックアップから品目と顧客の作成を制御する</span><span class="sxs-lookup"><span data-stu-id="69a46-131">Control item and customer creation from lookups on sales documents</span></span>
<span data-ttu-id="69a46-132">販売明細に存在しない品目を入力すると、新しい品目カードを作成するか既存の品目を選択するように求められます。</span><span class="sxs-lookup"><span data-stu-id="69a46-132">When you enter an item that does not exist on a sales line, you are prompted to either create a new item card or select an existing item.</span></span> <span data-ttu-id="69a46-133">多くの新しい品目をインポートするときなど、場合によっては、この確認によってプロセスがブロックされます。</span><span class="sxs-lookup"><span data-stu-id="69a46-133">In some cases, such as when importing many new items, this prompts blocks the process.</span></span> <span data-ttu-id="69a46-134">したがって、確認をスキップできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-134">Therefore, you can now select to skip the prompt.</span></span> <span data-ttu-id="69a46-135">**在庫設定**ページで、**品目作成の確認をスキップする**チェック ボックスをオンにします。</span><span class="sxs-lookup"><span data-stu-id="69a46-135">On the **Inventory Setup** page, select the **Skip Prompt to Create Item** check box.</span></span>

<span data-ttu-id="69a46-136">![新しい品目作成の確認をスキップする設定が表示されている在庫設定ページ](media/skip-prompt-create-item.png " 新しい品目作成の確認をスキップする設定が表示されている在庫設定ページ")</span><span class="sxs-lookup"><span data-stu-id="69a46-136">![Inventory setup page showing the new Skip Prompt to Create Item setting](media/skip-prompt-create-item.png "Visualization of new Skip Prompt to Create Item setting in Inventory Setup page")</span></span>

## <a name="copy-customer-dimensions-to-jobs-created-for-the-customer"></a><span data-ttu-id="69a46-137">顧客に対して作成されたジョブに顧客の分析コードをコピーする</span><span class="sxs-lookup"><span data-stu-id="69a46-137">Copy customer dimensions to jobs created for the customer</span></span>
<span data-ttu-id="69a46-138">ジョブが作成されて、顧客がそのジョブに割り当てられると、顧客の既定の分析コード値がジョブにコピーされます。</span><span class="sxs-lookup"><span data-stu-id="69a46-138">When a job is created and a customer is assigned to the job, default dimension values from the customer are copied to the job.</span></span> <span data-ttu-id="69a46-139">つまり、ユーザーは必要な場合はジョブの分析コード値を変更するだけでよく、顧客の既存の分析コードがジョブに割り当てられるためレポートの一貫性が維持されます。</span><span class="sxs-lookup"><span data-stu-id="69a46-139">This means that users only have to modify the dimension values of the job, if needed, and that reporting is consistent because the customer's existing dimensions are assigned to a job.</span></span>

## <a name="copy-templates-used-to-create-customers-vendors-and-items"></a><span data-ttu-id="69a46-140">顧客、仕入先、品目の作成に使用されるテンプレートをコピーする</span><span class="sxs-lookup"><span data-stu-id="69a46-140">Copy templates used to create customers, vendors, and items</span></span>
<span data-ttu-id="69a46-141">新しいデータ テンプレートを作成するときに、既存のデータ テンプレートをコピーできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-141">You can now copy existing data templates when you create new ones.</span></span> <span data-ttu-id="69a46-142">データ テンプレート (構成テンプレート) を使用すると、顧客、仕入先、品目、または取引先担当者のカードをすばやく作成できます。</span><span class="sxs-lookup"><span data-stu-id="69a46-142">Data templates (configuration templates) can be used to quickly create cards for customers, vendors, items, or contacts.</span></span> <span data-ttu-id="69a46-143">既存のデータ テンプレートをコピーするには、**構成テンプレート ヘッダー** ページの**構成テンプレートのコピー** アクションを選択します。</span><span class="sxs-lookup"><span data-stu-id="69a46-143">To copy an existing data template, choose the **Copy Config. Template** action on the **Config. Template Header** page.</span></span>

<span data-ttu-id="69a46-144">![構成テンプレート ヘッダー ページの構成テンプレートのコピー アクション](media/copy-master-template.png "構成テンプレート ヘッダー ページの構成テンプレートのコピー アクションの図")</span><span class="sxs-lookup"><span data-stu-id="69a46-144">![Config. Template Header page showing the Copy Config. Template action](media/copy-master-template.png "Visualization of Config. Template Header page showing Copy Config. Template action")</span></span>

## <a name="merge-duplicate-customers-or-vendors"></a><span data-ttu-id="69a46-145">重複する顧客または仕入先を統合する</span><span class="sxs-lookup"><span data-stu-id="69a46-145">Merge duplicate customers or vendors</span></span>
<span data-ttu-id="69a46-146">顧客または仕入先の重複するレコードが誤って作成されたときは、そのような重複レコードを単一のレコードに統合できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-146">When a duplicate customer or vendor record is created by mistake, you can now merge such duplicate records to a single record.</span></span>

## <a name="dynamically-set-shortcut-dimension-columns-in-lists-documents-and-journal-lines"></a><span data-ttu-id="69a46-147">リスト、ドキュメント、仕訳帳明細行にショートカット分析コード列を動的に設定する</span><span class="sxs-lookup"><span data-stu-id="69a46-147">Dynamically set shortcut dimension columns in lists, documents, and journal lines</span></span>
<span data-ttu-id="69a46-148">**総勘定元帳の設定**ページで設定した 2 つのグローバル分析コードのフィールドは、仕訳帳とドキュメントの明細行で常に使用できます。</span><span class="sxs-lookup"><span data-stu-id="69a46-148">Fields for the two global dimensions that you set up on the **General Ledger Setup** page are always available on journal and document lines.</span></span> <span data-ttu-id="69a46-149">その設定ページで設定したショートカット分析コードも、常に使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-149">Now, also the shortcut dimensions that you have set up that setup page are always available.</span></span> <span data-ttu-id="69a46-150">つまり、ショートカット分析コードの値も、**分析コード** ページを開かずに、仕訳帳とドキュメントの明細行に直接追加できます。</span><span class="sxs-lookup"><span data-stu-id="69a46-150">This means that you can also add shortcut dimension values directly to journal and document lines without opening the **Dimensions** page.</span></span>

## <a name="bulk-import-item-pictures"></a><span data-ttu-id="69a46-151">品目の画像を一括インポートする</span><span class="sxs-lookup"><span data-stu-id="69a46-151">Bulk import item pictures</span></span>
<span data-ttu-id="69a46-152">一度に複数の品目の画像をインポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-152">You can now import multiple item pictures in one go.</span></span> <span data-ttu-id="69a46-153">品目の番号に対応する名前で画像ファイルに名前を付け、それらを zip ファイルに圧縮してから、**品目の画像のインポート** ページを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="69a46-153">Simply name your picture files with a name corresponding to your item numbers, compress them to a zip file, and then use the **Import Item Pictures** page.</span></span> <span data-ttu-id="69a46-154">または、**品目の画像を設定する**アシスト セットアップ ガイドを使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="69a46-154">Alternatively, you can use the **Set Up Item Pictures** assisted setup guide.</span></span> <span data-ttu-id="69a46-155">まだ画像が設定されていない品目カードだけが更新されます。</span><span class="sxs-lookup"><span data-stu-id="69a46-155">Only item cards that do not already have pictures will be updated.</span></span>

<span data-ttu-id="69a46-156">![品目の画像のインポート ページの画像のインポート アクション](media/bulk-import-item-pictures.png "品目画像の一括インポートの図")</span><span class="sxs-lookup"><span data-stu-id="69a46-156">![Import Item Pictures page showing the Import Pictures action](media/bulk-import-item-pictures.png "Visualization of bulk import of item pictures")</span></span>

## <a name="view-payment-information-on-customer-and-vendor-statistics-factboxes"></a><span data-ttu-id="69a46-157">顧客および仕入先の統計情報ボックスで支払情報を表示する</span><span class="sxs-lookup"><span data-stu-id="69a46-157">View payment information on customer and vendor statistics FactBoxes</span></span>
<span data-ttu-id="69a46-158">顧客および仕入先の統計情報ボックスで、支払と最終支払日に関する情報を表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-158">Information about payments and last payment dates is now available on customer and vendor statistics FactBoxes.</span></span>

<span data-ttu-id="69a46-159">![領収済支払と最終支払日に関する情報が含まれる情報ボックスが表示されている顧客リスト ページ](media/cash-receipt-last-payment.png "顧客統計情報ボックス内の領収済支払と最終支払日の図")</span><span class="sxs-lookup"><span data-stu-id="69a46-159">![Customer list page showing FactBox with information about payments received and last payment date](media/cash-receipt-last-payment.png "Visualization of payments received and last payment date in customer statistics factbox")</span></span>

## <a name="look-up-swift-codes"></a><span data-ttu-id="69a46-160">SWIFT コードを検索する</span><span class="sxs-lookup"><span data-stu-id="69a46-160">Look up SWIFT codes</span></span>
<span data-ttu-id="69a46-161">取り引きのある銀行の SWIFT コードのリストを保持し、銀行口座を使用するページでそれを使用することができます。</span><span class="sxs-lookup"><span data-stu-id="69a46-161">You can now keep a list of SWIFT codes for banks that you work with and use it on pages where you use bank accounts.</span></span> <span data-ttu-id="69a46-162">これにより、支払の正確な準備が可能になり、ユーザーは SWIFT コードを自由書式として入力するのではなく、定義済みの SWIFT コードのリストから選択することができます。</span><span class="sxs-lookup"><span data-stu-id="69a46-162">This allows for accurate preparation of payments and forces users to pick from predefined lists of SWIFT codes rather than entering SWIFT codes as free text.</span></span>

<span data-ttu-id="69a46-163">![SWIFT コード フィールドのルックアップが示されている銀行口座ページ](media/lookup-swift-codes.png " SWIFT コード ルックアップ テーブルの図")</span><span class="sxs-lookup"><span data-stu-id="69a46-163">![Bank Account page showing lookup on SWIFT Code field](media/lookup-swift-codes.png "Visualization of SWIFT Codes lookup table.")</span></span>

## <a name="ensure-that-approval-users-are-set-up-to-run-approval-workflows"></a><span data-ttu-id="69a46-164">承認ユーザーが承認ワークフローを実行するように設定されていることを確認する</span><span class="sxs-lookup"><span data-stu-id="69a46-164">Ensure that approval users are set up to run approval workflows</span></span>
<span data-ttu-id="69a46-165">ユーザーが承認ワークフローを開始する前に、ユーザーが**承認ユーザー** ページで設定されていることを確認するチェックが追加されています。</span><span class="sxs-lookup"><span data-stu-id="69a46-165">A check is added to ensure that the user is set up on the **Approval Users** page before they can initiate an approval workflow.</span></span>

## <a name="configure-reports-for-warehouse-documents"></a><span data-ttu-id="69a46-166">倉庫ドキュメント用のレポートを構成する</span><span class="sxs-lookup"><span data-stu-id="69a46-166">Configure reports for warehouse documents</span></span>
<span data-ttu-id="69a46-167">**集荷**、**プット アウェイ**、**出荷**などの倉庫ドキュメントについて、他の分野のドキュメントと同様に、どのレポートを印刷するかをレポート選択機能を使用して構成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-167">You can now configure which reports will be printed for warehouse documents such as **Pick**, **Put-away**, and **Shipment** by using the Report Selection feature as for documents in other areas.</span></span>

<span data-ttu-id="69a46-168">![倉庫管理で選択可能なレポートを示すレポート選択ページ](media/report-select-whse.png "レポート選択使用フィールドの図")</span><span class="sxs-lookup"><span data-stu-id="69a46-168">![Report select page showing reports available for selection in warehouse management](media/report-select-whse.png "Visualization of Report Selection Usage field")</span></span>

## <a name="view-vendor-invoice-number-on-purchase-invoice-and-credit-memo-lists"></a><span data-ttu-id="69a46-169">仕入請求書およびクレジット メモのリストに仕入先請求書番号を表示する</span><span class="sxs-lookup"><span data-stu-id="69a46-169">View vendor invoice number on purchase invoice and credit memo lists</span></span>
<span data-ttu-id="69a46-170">**仕入先請求書番号**列が**仕入請求書**ページと**購買クレジット メモ** ページに表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-170">The **Vendor Invoice Number** column is now shown on the **Purchase Invoices** and **Purchase Credit Memos** pages.</span></span>

## <a name="view-time-information-on-registers"></a><span data-ttu-id="69a46-171">登録の時刻情報を表示する</span><span class="sxs-lookup"><span data-stu-id="69a46-171">View time information on registers</span></span>
<span data-ttu-id="69a46-172">**G/L登録**、**品目登録**、**ジョブ登録**などのさまざまな登録ページで、時刻情報を見ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69a46-172">You can now view time information on various Register pages, such as **G/L Register**, **Item Register**, and **Job Register**.</span></span> <span data-ttu-id="69a46-173">これにより、日付だけでなく、トランザクションが作成された時刻も使用して、登録のトランザクションをより早く見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="69a46-173">This allows you to find transactions in registers faster, not just by date but also by the time that the transactions were created.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="69a46-174">フィードバック</span><span class="sxs-lookup"><span data-stu-id="69a46-174">Tell us what you think</span></span>
<span data-ttu-id="69a46-175">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="69a46-175">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="69a46-176">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="69a46-176">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>

<!--
Describe the new feature, and then give an elevator pitch of the business value for it. Include high-value capabilities that light up something exciting for our customers. The feature should be something that a customer needs to plan for...definitely larger than a hotfix or bug fix.
If the feature has been designated as a key feature, complete the entire template. Otherwise, only complete the **Business value**, **Describe the feature**, and **Status** sections.
## Business value (Required)
Describe the top capabilities of the feature and and the business problems it solves.  
**Example**
End-of-day processing is a crucial element of retail operational workflow. This involves aggregation of raw transactions into meaningful business data to ensure that business and accounting rules are conformed to, before posting transactions as official business records. Improving the reliability and performance of this batch process and increasing the visibility of the processing for the administrator improves the user experience. Users can easily monitor the progress of the processing and see exactly what caused a validation failure. As a result, they can quickly resolve the issue and reliably retry the process without contacting Microsoft Support.
## Describe the feature (Required)
Describe how the feature works and the scenarios the feature enables. Include concrete examples and screenshots.
**Example**
New capabilities include improved statement posting performance by removing table deadlocks and optimizing batch processing. The introduction of a state model in the posting process aids in rollback and recovery, which eliminates data corruption and the need for manual intervention. Enhanced in-app diagnostics with detailed status, errors, and logs (including details of transactions included in the scope of the statement, transactions resulting in errors, and possible steps to correct issues) allow for easy troubleshooting.
<<screenshot goes here>>
### Who uses this feature (Required)
Indicate each persona impacted:  end user, admin, customizer, citizen developer, developer, business analyst, IT Pro
**Example**
This feature is intended for retail administrators. It works without any additional setup.
### License required
List the license(s) a customer must have to use the feature.
### Setup required (if any beyond standard product setup)
**Example**
This feature must be enabled in System parameters by an administrator.
### Quick steps (provide if feature is done enough)
**Example**
To get started with model‑driven apps, use designers to:
- Define your site map. Model your app's navigation, pulling in only the subset of information your users need. Take advantage of multiple levels of hierarchy and the ability to reference external resources.
- Add dashboards. Include model‑driven dashboards or embedded Power BI content within your app.
- Include entities and components. Add specific forms, views, dashboards, and charts for targeted entities to craft your user experience.
> [!div class="mx-imgBorder"]
> ![Photograph of a man using a Hololens to view augmented reality in Connected Field Service](/articles/Spring18/media/507e34a661a1b831d21ea3dadda9c6cf.jpg "Field Service IoT")
## Compliance, privacy and security considerations
List any compliance, privacy and security considerations that customers should plan for, including any steps or tools provided to help customers comply with GDPR.
## Status (Required)
### Development status
Pick one: Generally available, Public preview, In development
Notes: In development features are features that some teams may have previously included on the roadmap site. Anything in Private preview is considered to be In development.
#### Target timeframe
Enter the release, month, or month or later if dubious. (Release if committed to a release, Month if committed to a month, Month or later if dubious)
### Availability (current availability)
Cloud, On-premises, Government cloud
### Regional availability
List whether this feature is available globally or restricted to specific regions.
## Tell us what you think
Include an alias or link for feedback for the feature.
## We'd like to thank
Link to item from Ideas or User voice.
-->
