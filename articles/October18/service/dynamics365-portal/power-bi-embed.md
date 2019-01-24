---
title: "Dynamics 365 ポータルへの Power BI ビジュアル化の埋め込み"
description: "ポータルのページに Power BI のビジュアル化を埋め込みます。"
author: neerajnandwana-ms
manager: rycu
ms.date: 11/20/2018
ms.assetid: e2a02c53-de53-4890-9a21-73cf97965494
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
ms.reviewer: shjais
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 8b036dfe01dc2effebc2c89debc5f50d648c8259
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---
# <a name="embed-power-bi-visualizations"></a><span data-ttu-id="30416-103">Power BI のビジュアル化の埋め込み</span><span class="sxs-lookup"><span data-stu-id="30416-103">Embed Power BI visualizations</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="30416-104">[Power BI](https://powerbi.microsoft.com) は、シンプルな対話型のビジュアル化によって分析情報を提供する最も優れたツールの 1 つです。</span><span class="sxs-lookup"><span data-stu-id="30416-104">[Power BI](https://powerbi.microsoft.com) is one of the best tools to deliver insights with simple and interactive visualization.</span></span> <span data-ttu-id="30416-105">ポータル ユーザーに対して有効にする Power BI の機能とユース ケースの検討において、この機能は現在も最も投票数の多いアイデアの 1 つです。</span><span class="sxs-lookup"><span data-stu-id="30416-105">Considering Power BI features and the use cases it enables for portal users, this feature remains one of the top-voted ideas.</span></span>

<span data-ttu-id="30416-106">現在、ポータルへの安全な Power BI レポートの埋め込みは複雑な作業です。</span><span class="sxs-lookup"><span data-stu-id="30416-106">Currently, embedding secure Power BI reports in a portal is a complex task.</span></span> <span data-ttu-id="30416-107">これには、セキュリティ トークンを処理および管理するためのカスタム ロジックの作成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="30416-107">It includes writing custom logic to handle and manage security token.</span></span> <span data-ttu-id="30416-108">この機能により、Dynamics 365 ポータルと Power BI の統合が合理化されます。</span><span class="sxs-lookup"><span data-stu-id="30416-108">This feature streamlines the Dynamics 365 Portal and Power BI integration.</span></span> 

## <a name="enable-power-bi"></a><span data-ttu-id="30416-109">Power BI の有効化</span><span class="sxs-lookup"><span data-stu-id="30416-109">Enable Power BI</span></span>

<span data-ttu-id="30416-110">管理者は、ポータルに対して Power BI を構成し、有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="30416-110">Administrators will be able to configure and enable Power BI for a portal.</span></span> <span data-ttu-id="30416-111">これには、適切な Power BI ライセンスが必要です。</span><span class="sxs-lookup"><span data-stu-id="30416-111">This will require an appropriate Power BI license.</span></span>

<span data-ttu-id="30416-112">![ポータル管理センターから Power BI 統合を有効にする](media/PBI_Admin_Center_EnablePBI.png "ポータル管理センターから Power BI 統合を有効にする")</span><span class="sxs-lookup"><span data-stu-id="30416-112">![Enable Power BI integration from Portal Admin Center](media/PBI_Admin_Center_EnablePBI.png "Enable Power BI integration from Portal Admin Center")</span></span>

## <a name="add-power-bi-visualization"></a><span data-ttu-id="30416-113">Power BI ビジュアル化の追加</span><span class="sxs-lookup"><span data-stu-id="30416-113">Add Power BI visualization</span></span>

<span data-ttu-id="30416-114">カスタマイズ担当者は、Liquid コードを使用して Power BI ダッシュボードとレポートをページ内に埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="30416-114">Customizers can use Liquid code to embed Power BI dashboards and reports within pages.</span></span> <span data-ttu-id="30416-115">Power BI コンテンツを埋め込むときに、カスタマイズ担当者は[フィルター パラメーター](https://docs.microsoft.com/power-bi/service-url-filters)を使用してパーソナライズされたビューを作成できます。</span><span class="sxs-lookup"><span data-stu-id="30416-115">While embedding the Power BI content, customizers can use [filter parameters](https://docs.microsoft.com/power-bi/service-url-filters) to create personalized views.</span></span> <span data-ttu-id="30416-116">Liquid の powerbi タグにより、Power BI ダッシュボードとレポートをページ内に埋め込みます。</span><span class="sxs-lookup"><span data-stu-id="30416-116">The powerbi Liquid tag embeds the Power BI dashboards and reports within pages.</span></span>

```
{% powerbi path:"https://app.powerbi.com/view?r=eyJrIjoiNjMzZTY1ZTItMDE2My00NGY5LWIwYmItNjUwMGY5NzEY3IiwidCI6IjU3NGMzZTU2LTQ5MjQtNDAwNC1hZDFhLWQ4NDI3ZTdkYjI0MSiOjZ9" %}
```

### <a name="parameters"></a><span data-ttu-id="30416-117">パラメーター</span><span class="sxs-lookup"><span data-stu-id="30416-117">Parameters</span></span>

<span data-ttu-id="30416-118">powerbi タグは、次のパラメーターを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="30416-118">The powerbi tag accepts the following parameters:</span></span>

<span data-ttu-id="30416-119">**path**</span><span class="sxs-lookup"><span data-stu-id="30416-119">**path**</span></span>

<span data-ttu-id="30416-120">Power BI レポートまたはダッシュボードのパス。</span><span class="sxs-lookup"><span data-stu-id="30416-120">Path of the Power BI report or dashboard.</span></span> <span data-ttu-id="30416-121">Power BI レポートまたはダッシュボードが安全である場合は、認証の種類を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="30416-121">If the Power BI report or dashboard is secure, you must provide the authentication type.</span></span>

<span data-ttu-id="30416-122">**認証の種類**</span><span class="sxs-lookup"><span data-stu-id="30416-122">**authentication_type**</span></span>

<span data-ttu-id="30416-123">Power BI レポートまたはダッシュボードに必要な認証の種類。</span><span class="sxs-lookup"><span data-stu-id="30416-123">Type of authentication required for the Power BI report or dashboard.</span></span> <span data-ttu-id="30416-124">このパラメーターの有効な値は **Anonymous** または **AAD** です。</span><span class="sxs-lookup"><span data-stu-id="30416-124">Valid values for this parameter are **Anonymous** or **AAD**.</span></span> <span data-ttu-id="30416-125">既定値は **Anonymous** です。</span><span class="sxs-lookup"><span data-stu-id="30416-125">The default value is **Anonymous**.</span></span>

<span data-ttu-id="30416-126">セキュリティ保護された Power BI レポートまたはダッシュボードを追加する場合は、Dynamics 365 ポータル Azure Active Directory の認証済みユーザーと共有されていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="30416-126">While adding the secure Power BI report or dashboard, ensure that it is shared with Dynamics 365 Portal Azure Active Directory authenticated users.</span></span> 

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/reports/00000000-0000-0000-0000-000000000001/ReportSectionc01" %}
```

<span data-ttu-id="30416-127">**tileid**</span><span class="sxs-lookup"><span data-stu-id="30416-127">**tileid**</span></span>

<span data-ttu-id="30416-128">ダッシュボードの指定されたタイルを表示します。</span><span class="sxs-lookup"><span data-stu-id="30416-128">Displays the specified tile of the dashboard.</span></span> <span data-ttu-id="30416-129">タイルの ID を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="30416-129">You must provide the ID of the tile.</span></span>

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/dashboards/00000000-0000-0000-0000-000000000001" tileid:"00000000-0000-0000-0000-000000000002" %}
```




<!--
### Who uses this feature
This feature is intended for end users and customizers. A customizer must configure Power BI in a portal to use this feature.
### License required
For Power BI configuration and content authoring, customers or administrators will need an appropriate Power BI license.
### Setup required
This feature must be configured and enabled in a portal by an administrator. 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

## <a name="wed-like-to-thank"></a><span data-ttu-id="30416-130">謝辞</span><span class="sxs-lookup"><span data-stu-id="30416-130">We'd like to thank</span></span>

<span data-ttu-id="30416-131">優先順位付けに役立つ投票とコメントを[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59)にお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="30416-131">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59) with votes and comments that helped us prioritize it.</span></span>

## <a name="resources"></a><span data-ttu-id="30416-132">リソース</span><span class="sxs-lookup"><span data-stu-id="30416-132">Resources</span></span>

[<span data-ttu-id="30416-133">Power BI 統合の設定</span><span class="sxs-lookup"><span data-stu-id="30416-133">Set up Power BI integration</span></span>](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/set-up-power-bi-integration)

