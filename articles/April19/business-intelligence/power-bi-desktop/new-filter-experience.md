---
title: 新しいフィルター エクスペリエンス
description: フィルタリング エクスペリエンスを改良しています。
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: 2659a547729cb83f9ff15b9b0e15a6ba6f9c9600
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "211033"
---
# <a name="new-filter-experience"></a><span data-ttu-id="b5e9f-103">新しいフィルター エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="b5e9f-103">New filter experience</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="b5e9f-104">この改良されたフィルター エクスペリエンスのパブリック プレビューは、Power BI Desktop の 2018 年 11 月のリリースで提供されました。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-104">This public preview of the revamped filter experience went live with the November 2018 release of Power BI Desktop.</span></span> <span data-ttu-id="b5e9f-105">このエクスペリエンスは、レポートの利用者がビジュアルに影響を与えているフィルターをよりよく理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-105">This experience helps consumers of reports to better understand which filters are affecting a visual.</span></span> <span data-ttu-id="b5e9f-106">また、発見しやすさに役立ち、レポート作成者にはルック アンド フィールの完全な制御が提供されます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-106">It also helps with discoverability and gives report authors full control over the look and feel.</span></span> 

-   <span data-ttu-id="b5e9f-107">作成者は、フィルター カードがレポートに適用されていても、エンド ユーザーに対してそのフィルター カードを非表示にすることができます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-107">Authors can hide a filter card from end users even though it is applied to the report.</span></span>

-   <span data-ttu-id="b5e9f-108">作成者は、フィルターを適用してロックできるので、エンド ユーザーはフィルターを変更できませんが、その情報を参照することはできます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-108">Authors can apply a filter and lock it, so end users will not be able to modify the filter but will show it to them for their information.</span></span>

<span data-ttu-id="b5e9f-109">再設計されたフィルター ウィンドウには、次の機能があります。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-109">The redesigned filter pane includes the ability to:</span></span>

- <span data-ttu-id="b5e9f-110">レポートの利用者に対して個々のフィルターまたはフィルター ウィンドウ全体を非表示にする。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-110">Hide individual filters or the entire filter pane from report consumers.</span></span>
- <span data-ttu-id="b5e9f-111">レポートの利用者に対してフィルターを読み取り専用としてロックする。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-111">Lock filters as read-only for report consumers.</span></span>
- <span data-ttu-id="b5e9f-112">フィルター ウィンドウの書式を設定して、レポート デザインの一部のように見せる。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-112">Format the filter pane to make it feel like a part of the report design.</span></span>
- <span data-ttu-id="b5e9f-113">レポートの利用者がレポートを読み込むときの既定のエクスペリエンス (展開または縮小) を定義する。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-113">Define the default experience, expanded or collapsed, at report load time for report consumers.</span></span>
- <span data-ttu-id="b5e9f-114">スライサー、フィルター、クロスハイライトなど、ビジュアルに適用されているフィルターを理解する。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-114">Understand what filters are being applied to a visual, including slicers, filters, and cross-highlighting.</span></span> 
- <span data-ttu-id="b5e9f-115">フィルターの値を検索する。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-115">Search for filter values.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b5e9f-116">![新しいフィルター ウィンドウが表示されているレポート](media/new-filter-experience-1.png "新しいフィルター ウィンドウが表示されているレポート")
*新しいフィルター ウィンドウ エクスペリエンスを使用しているレポート*</span><span class="sxs-lookup"><span data-stu-id="b5e9f-116">![Report showing new filter pane](media/new-filter-experience-1.png "Report showing new filter pane")
*Report using the new filter pane experience*</span></span>

<span data-ttu-id="b5e9f-117">フィルター ウィンドウに対する変更に加えて、作成者には、ビジュアルに影響するフィルター (スライサーを含む) を表示する柔軟性も与えられます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-117">In addition to the changes to the filter pane, we are also giving authors the flexibility to show filters (including slicers) that are affecting a visual.</span></span>
<span data-ttu-id="b5e9f-118">作成者は、フィルター アイコンをビジュアル ヘッダーとして有効にすることができ、エンド ユーザーがそのフィルター アイコンにカーソルを合わせるかクリックすると、そのビジュアルに影響を与えるすべてのフィルターが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-118">Authors can enable a filter icon as a visual header and all the filters affecting that visual will show up when the end user hovers or clicks on that filter icon.</span></span> <span data-ttu-id="b5e9f-119">これによりエンド ユーザーは、どのフィルターがビジュアルに影響を与えているかを理解し、分析情報をより適切に解釈することができます。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-119">This will help end users to understand which filters are impacting the visual to better interpret the insights.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b5e9f-120">![ポイントしてビジュアルに適用されているフィルターを表示する](media/new-filter-experience-2.png "ポイントしてビジュアルに適用されているフィルターを表示する")
*ビジュアルのフィルター アイコンをポイントして、適用されているフィルターを確認する*</span><span class="sxs-lookup"><span data-stu-id="b5e9f-120">![Hover to display filters applied to a visual](media/new-filter-experience-2.png "Hover to display filters applied to a visual")
*Hover on the filter icon for any visual to see which filters have been applied*</span></span>

<span data-ttu-id="b5e9f-121">パブリック プレビューのユーザーからのフィードバックに積極的に耳を傾けており、一般に提供される前にエクスペリエンスを改善しています。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-121">We are actively listening to feedback from users of the public preview and improving the experience before making it generally available.</span></span> <span data-ttu-id="b5e9f-122">次の機能が計画されており、新しいフィルタリング エクスペリエンスの一般提供の前またはそれと同時に提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-122">The following capabilities are planned and will ship before or alongside general availability of the new filtering experience:</span></span>

- <span data-ttu-id="b5e9f-123">エンド ユーザーおよびレポート作成者のためのアクセシビリティ。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-123">Accessibility for end users and report authors.</span></span>
- <span data-ttu-id="b5e9f-124">追加の書式設定機能。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-124">Additional formatting capabilities.</span></span>
- <span data-ttu-id="b5e9f-125">フィルタリング エクスペリエンスの単一ウィンドウへの統合。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-125">Consolidating the filtering experience to a single pane.</span></span>
- <span data-ttu-id="b5e9f-126">作成者がフィルター カードを並べ替える機能。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-126">Ability for authors to sort and reorder filter cards.</span></span>

<span data-ttu-id="b5e9f-127">新しいフィルター エクスペリエンスでは、以下の Power BI アイデア要求に対応しています。</span><span class="sxs-lookup"><span data-stu-id="b5e9f-127">The new filter experience addresses the following Power BI Ideas requests:</span></span>

- [<span data-ttu-id="b5e9f-128">アクティブなフィルターの指示</span><span class="sxs-lookup"><span data-stu-id="b5e9f-128">Active filter indication</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/16413433-active-filter-indication)
- [<span data-ttu-id="b5e9f-129">フィルターでの検索オプション</span><span class="sxs-lookup"><span data-stu-id="b5e9f-129">Search options in filter</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/18956419-seaech-option-in-filters)
- [<span data-ttu-id="b5e9f-130">フィルターの非表示</span><span class="sxs-lookup"><span data-stu-id="b5e9f-130">Hide filter</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/17936422-more-control-over-report-filters-pane-hide-certa)
- [<span data-ttu-id="b5e9f-131">ユーザーによるフィルターの変更の禁止</span><span class="sxs-lookup"><span data-stu-id="b5e9f-131">Prevent user from changing filters</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/10319553-hide-filters-for-shared-reports-or-prevent-user-fr)