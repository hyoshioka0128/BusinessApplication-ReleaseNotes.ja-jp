---
title: デザイナーの機能強化
description: Visual Studio Code が付属するデザイナーでは、アクション、リスト ビュー、フィールドの重要度、簡単入力など、いっそう多くのコンテンツをページ上で調整できます。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 02/25/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, customizer
ms.openlocfilehash: e30845ac756e5e136b59a5cbff7c1db3e59dd658
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225054"
---
# <a name="designer-enhancements-for-developers"></a><span data-ttu-id="25aaf-103">開発者向けデザイナーの機能強化</span><span class="sxs-lookup"><span data-stu-id="25aaf-103">Designer enhancements for developers</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="25aaf-104">デザイナーは Visual Studio Code が付属しており、開発者がページ オブジェクトのビジュアル コンテンツをテストしてすばやく調整するための便利な方法です。</span><span class="sxs-lookup"><span data-stu-id="25aaf-104">The Designer accompanies Visual Studio Code and is a convenient way for developers to test and rapidly adjust visual content on page objects.</span></span>

<span data-ttu-id="25aaf-105">デザイナーでは、テスト環境に展開されたすべての拡張機能に対する依存関係が自動的に追加されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="25aaf-105">Designing no longer automatically adds dependencies to all deployed extensions on the test environment.</span></span> <span data-ttu-id="25aaf-106">デザイナーを終了するとき、依存関係が取得されなかった拡張機能は暗黙のうちに削除されます。</span><span class="sxs-lookup"><span data-stu-id="25aaf-106">When exiting the Designer, extensions upon which no dependency was taken are silently removed.</span></span>

## <a name="designing-actions"></a><span data-ttu-id="25aaf-107">設計アクション</span><span class="sxs-lookup"><span data-stu-id="25aaf-107">Designing actions</span></span>
<span data-ttu-id="25aaf-108">リスト、ワークシート、カード、またはドキュメント ページを拡張するときは、デザイナーを使用してページ アクションのレイアウトを微調整します。</span><span class="sxs-lookup"><span data-stu-id="25aaf-108">When extending a list, worksheet, card or document page, use the Designer to make minor adjustments to the layout of page actions.</span></span> <span data-ttu-id="25aaf-109">関係のないアクションを隠したり、グループ間でアクションを移動したり、グループを隠したり並べ替えたりします。</span><span class="sxs-lookup"><span data-stu-id="25aaf-109">Hide away actions that are not relevant, move actions across groups and hide or re-order groups.</span></span> <span data-ttu-id="25aaf-110">繊細なビジュアル インジケーターは、Business Central の 2019 年 4 月のリリースで何が可能であるかを開発者にガイドします。</span><span class="sxs-lookup"><span data-stu-id="25aaf-110">Subtle visual indicators guide developers to what is possible with the April '19 release of Business Central.</span></span>

## <a name="designing-quick-entry"></a><span data-ttu-id="25aaf-111">簡単入力の設計</span><span class="sxs-lookup"><span data-stu-id="25aaf-111">Designing Quick Entry</span></span>
<span data-ttu-id="25aaf-112">簡単入力はデスクトップ ユーザーにとって生産性の高い機能であり、レコードの繰り返し入力に要する時間を短縮します。</span><span class="sxs-lookup"><span data-stu-id="25aaf-112">Quick Entry is a productivity feature for desktop users that accelerates repetitive entry of records.</span></span> <span data-ttu-id="25aaf-113">フィールドで Enter キーを押すと、フォーカスは次の編集可能な簡単入力フィールドまたはセルに移動します。常に必要ではないフィールドまたは自動入力されるフィールドはスキップされます。</span><span class="sxs-lookup"><span data-stu-id="25aaf-113">When the Enter key is pressed on a field, the focus moves to the next editable Quick Entry field or cell, skipping over other fields that are not always needed or are auto-filled.</span></span> <span data-ttu-id="25aaf-114">任意のフィールドのメニューを使用して、デザイナーの簡単入力パスのフィールドを含めたり除外したりすることができ、ページ全体で変更の結果をすぐにテストできます。</span><span class="sxs-lookup"><span data-stu-id="25aaf-114">You can include or exclude fields from the Quick Entry path in the Designer using the menu on any field, and immediately test the outcome of your changes across the page.</span></span> <span data-ttu-id="25aaf-115">これは、Visual Studio Code で簡単入力を微調整するよりはるかに効率的です。</span><span class="sxs-lookup"><span data-stu-id="25aaf-115">This is far more efficient than fine-tuning Quick Entry in Visual Studio Code.</span></span>

## <a name="designing-field-importance"></a><span data-ttu-id="25aaf-116">フィールドの重要度の設計</span><span class="sxs-lookup"><span data-stu-id="25aaf-116">Designing field importance</span></span>
<span data-ttu-id="25aaf-117">たまにしか必要とされないフィールドもあれば、ビジネス ユーザーが毎回参照する必要がある重要なフィールドもあります。</span><span class="sxs-lookup"><span data-stu-id="25aaf-117">Some fields are only needed occasionally, while others are so important that business users need them visible at all times.</span></span> <span data-ttu-id="25aaf-118">フィールドを移動、非表示化、追加する機能に加えて、デザイナーでは、開発者は視覚的でインタラクティブな方法でフィールドの重要度プロパティを微調整することもできるようになります。</span><span class="sxs-lookup"><span data-stu-id="25aaf-118">Along with the ability to move, hide, and add fields, the Designer now also allows developers to fine-tune a field's Importance property in a highly visual and interactive way.</span></span>

## <a name="designing-list-views"></a><span data-ttu-id="25aaf-119">リスト ビューの設計</span><span class="sxs-lookup"><span data-stu-id="25aaf-119">Designing list views</span></span>
<span data-ttu-id="25aaf-120">2019 年 4 月の更新後間もなく利用可能になり、開発者は拡張機能内でリスト ページの代替ビューを設計することができるようになります。</span><span class="sxs-lookup"><span data-stu-id="25aaf-120">Available shortly after the April '19 update, developers will be able to design alternate views of list pages within extensions.</span></span> <span data-ttu-id="25aaf-121">テスト データを使用してリアルタイムでフィルターを作成、テスト、調整してから、ビューを拡張機能に保存します。</span><span class="sxs-lookup"><span data-stu-id="25aaf-121">Author, test, and refine filters using your test data in real time and then save the view to your extension.</span></span> <span data-ttu-id="25aaf-122">デザイナーを使用すると、個々のビューごとの特定の列レイアウトや列の並べ替えのの設計など、顧客からのより要求の厳しい要件も簡単に満たすことができます。</span><span class="sxs-lookup"><span data-stu-id="25aaf-122">The Designer also makes it easy to satisfy the more demanding requirements from your customers, including designing specific column layouts and column sorting for each individual view.</span></span>

<span data-ttu-id="25aaf-123">詳細については、「[リスト ビュー](list-views.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25aaf-123">For additional information, see [List Views](list-views.md).</span></span>

## <a name="designing-the-navigation-bar"></a><span data-ttu-id="25aaf-124">ナビゲーション バーの設計</span><span class="sxs-lookup"><span data-stu-id="25aaf-124">Designing the navigation bar</span></span>
<span data-ttu-id="25aaf-125">Business Central に対する 2019 年 4 月の更新の後、今年後半には、開発者はナビゲーション リンクやリンクのグループを各ロール センター ページで直接設計できるようになります。</span><span class="sxs-lookup"><span data-stu-id="25aaf-125">Coming later this year after the April '19 update to Business Central, developers will be able to design navigation links and groups of links directly on each role center page.</span></span> <span data-ttu-id="25aaf-126">空のナビゲーション バーから始めて、リストをピン留めし、よく使用されるテーブルへのリンクのセットを構築します。</span><span class="sxs-lookup"><span data-stu-id="25aaf-126">Start with an empty navigation bar and pin any list to build up the set of links to commonly-used tables.</span></span>
<span data-ttu-id="25aaf-127">詳しくは、「[ロール センターの設計](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-role-centers)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="25aaf-127">Learn more about [Designing Role Centers](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-role-centers)</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="25aaf-128">フィードバック</span><span class="sxs-lookup"><span data-stu-id="25aaf-128">Tell us what you think</span></span>
<span data-ttu-id="25aaf-129">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="25aaf-129">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="25aaf-130">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="25aaf-130">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>


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

![Photograph of a man using a Hololens to view augmented reality in Connected Field Service](/articles/Spring18/media/507e34a661a1b831d21ea3dadda9c6cf.jpg "Field Service IoT") 

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
