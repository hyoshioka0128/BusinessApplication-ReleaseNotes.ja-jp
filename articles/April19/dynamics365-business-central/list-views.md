---
title: リスト ビュー
description: 独自の名前付きのフィルター処理されたリスト ビューを保存し、名前を変更し、削除し、他のユーザーと共有します。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 02/25/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: 4e6dc8b2a04bf91b8dba9279db5466405de3673e
ms.sourcegitcommit: 92b7053f06513207fc880a7ce9dabb00b4df5816
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/25/2019
ms.locfileid: "723647"
---
# <a name="list-views"></a><span data-ttu-id="63d45-103">リスト ビュー</span><span class="sxs-lookup"><span data-stu-id="63d45-103">List views</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="a-new-view-api-for-developers"></a><span data-ttu-id="63d45-104">開発者向けの新しいビュー API</span><span class="sxs-lookup"><span data-stu-id="63d45-104">A new view API for developers</span></span>

<span data-ttu-id="63d45-105">開発者には、最近のクライアント用に Visual Studio Code でカスタム リスト ビューを作成するための新しいシンプルで直感的なモデルもあります。</span><span class="sxs-lookup"><span data-stu-id="63d45-105">Developers have a new, simple and intuitive model to build custom list views in Visual Studio Code for the modern clients.</span></span> <span data-ttu-id="63d45-106">開発者がそれぞれに固有のカスタム列レイアウトを使用してリストの代替ビューを作成できるようになるだけでなく、新しいビューによって以前のモデルの欠点のほとんどが解消されます。</span><span class="sxs-lookup"><span data-stu-id="63d45-106">Not only does it empower developers to create alternate views of a list with each their own custom column layout, but the new views also overcome most of the shortcomings with the earlier model.</span></span> <span data-ttu-id="63d45-107">たとえば、移動方法に関係なく、ビューが 1 つのリスト ページに表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63d45-107">For example, views now appear on a list page irrespective of how you navigate to it.</span></span>

## <a name="saving-and-personalizing-list-views"></a><span data-ttu-id="63d45-108">リスト ビューの保存とパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="63d45-108">Saving and personalizing list views</span></span>

<span data-ttu-id="63d45-109">2019 年 4 月以降のマイナー更新で使用可能になり、ユーザーが自分のリスト フィルターや同様の個人用設定を保存して、異なるデータ スライス方法を作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="63d45-109">Available in a minor update after April '19, users will be able to save their list filters and similar personalizations to create different ways of slicing their data.</span></span> <span data-ttu-id="63d45-110">リスト ビューには、"販売する品目" のような名前が設定されていて、合計や分析コードに対するフィルター、適切なデータに動的にフィルターを適用するためのフィルター トークン (%MyCustomers など)、さらに複雑で調整されたリストのビューを作成できる異なる並べ替えが含まれる場合があります。</span><span class="sxs-lookup"><span data-stu-id="63d45-110">List views are given a name, such as "Items I sell," and might include filters on totals and dimensions, filter tokens (such as %MyCustomers) to dynamically filter to the right data, as well as different sorting allowing more complex and tailored views of a list.</span></span> <span data-ttu-id="63d45-111">ユーザーはリストの異なるビューをすばやく切り替えることができます。これには、独自の個人的なビューや、ビジネス アプリケーションやロールに標準で付属するビューが含まれます。</span><span class="sxs-lookup"><span data-stu-id="63d45-111">Users can quickly switch between different views of a list, which includes their own personal views or views that come as standard in their business application or for their role.</span></span> <span data-ttu-id="63d45-112">他の個人用設定と同様に、リスト ビューは、ユーザーがサインインしているデバイスやブラウザーに関係なく、ユーザーと一緒に移動します。</span><span class="sxs-lookup"><span data-stu-id="63d45-112">Similar to other personalizations, list views roam with the user, no matter which device or browser they sign in to.</span></span>

<span data-ttu-id="63d45-113">![フィルター ウィンドウのメニューを使用してリスト ビューへの変更を保存する方法を示す概念設計](media/list-views.png "リスト ビューへの変更の保存に関する概念設計")</span><span class="sxs-lookup"><span data-stu-id="63d45-113">![Concept design illustrating how changes to a list view could be saved using a menu in the filter pane](media/list-views.png "Concept design for saving changes to a list view")</span></span>


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
