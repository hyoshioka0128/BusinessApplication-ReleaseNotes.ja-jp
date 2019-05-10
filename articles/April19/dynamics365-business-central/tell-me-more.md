---
title: コンテキスト検索エクスペリエンスの改善
description: 操作アシスト ウィンドウの機能強化。
author: kotelko
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: blazkote
audience: developer, end user
ms.openlocfilehash: 3b5f0573d7499e283916a8f77479c259f40dec41
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224989"
---
# <a name="improved-contextual-search-experience"></a><span data-ttu-id="16c64-103">コンテキスト検索エクスペリエンスの改善</span><span class="sxs-lookup"><span data-stu-id="16c64-103">Improved contextual search experience</span></span>

## <a name="search-results-from-appsource"></a><span data-ttu-id="16c64-104">AppSource からの検索結果</span><span class="sxs-lookup"><span data-stu-id="16c64-104">Search results from AppSource</span></span>
<span data-ttu-id="16c64-105">Microsoft では、AppSource でより柔軟な用語を使用してパートナー ソリューションを検索できるようにすることで、操作アシスト (Alt+Q) 機能を改善しました。</span><span class="sxs-lookup"><span data-stu-id="16c64-105">We have improved the Tell me (Alt+Q) feature by allowing more flexible terms and surfacing results for partner solutions on AppSource.</span></span> <span data-ttu-id="16c64-106">これによりユーザーは、パートナー コミュニティから入手できる幅広いソリューションの中から目的に合うソリューションを探し、Business Central を簡単に拡張できるようになります。</span><span class="sxs-lookup"><span data-stu-id="16c64-106">This allows users to seek help and easily extend Business Central with the many solutions that are available from the partner community.</span></span>

<span data-ttu-id="16c64-107">![AppSource からの検索結果のスクリーンショット](media/search_commission.png "検索結果には AppSource 検索からの結果も含まれています")</span><span class="sxs-lookup"><span data-stu-id="16c64-107">![Screenshot of search results from AppSource](media/search_commission.png "Search results now also include results from AppSource search")</span></span>

## <a name="additional-search-terms"></a><span data-ttu-id="16c64-108">追加の検索語</span><span class="sxs-lookup"><span data-stu-id="16c64-108">Additional search terms</span></span>

<span data-ttu-id="16c64-109">新規ユーザーの場合は、Business Central にある関連エンティティの名前とは異なるビジネス用語を使用することがよくあります。</span><span class="sxs-lookup"><span data-stu-id="16c64-109">New users often use different business terms than those used to name the related entities in Business Central.</span></span> <span data-ttu-id="16c64-110">たとえば、"項目" ではなく "製品" を使用したり、"顧客" ではなく "クライアント" を使用したりすることがあります。</span><span class="sxs-lookup"><span data-stu-id="16c64-110">For example, they might use "product" instead of "item," or "client" instead of "customer."</span></span>

<span data-ttu-id="16c64-111">開発者は、ページやレポートに代替の検索語を追加することで、ユーザーが目的のエンティティをより簡単に見つけられるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="16c64-111">Developers can now add alternate search terms to pages and reports to make it easier for users to find what they are looking for.</span></span> <span data-ttu-id="16c64-112">開発者は、ページやレポートの AdditionalSearchTermsML プロパティで、会社固有の用語を追加することができます。ユーザーはその用語を [操作アシスト] ボックスに入力して、目的のページやレポートを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="16c64-112">In the AdditionalSearchTermsML property on pages and reports, developers can add company-specific terms that users can then enter in the Tell me box to find the page or report in question.</span></span>

<span data-ttu-id="16c64-113">Business Central では、一部のページやレポート用に、約 200 の代替検索語が公開されています (項目ページを検索するための "製品"や、アセンブリ BOM ページを検索するための "キット" など)。</span><span class="sxs-lookup"><span data-stu-id="16c64-113">Business Central is published with around 200 such alternate search terms for selected pages and reports, such as "product" to find the Items page and "kit" to find the Assembly BOM page.</span></span>

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
