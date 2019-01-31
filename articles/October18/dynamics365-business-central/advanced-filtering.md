---
title: 高度なフィルター
description: 強力なフィルター機能によりデスクトップでの生産性が向上します。
author: mikebcMSFT
manager: edupont04
ms.date: 09/23/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: end user
ms.openlocfilehash: 8c2bc84d8e3e8291d5cc07b49e7ae853a5cb5df3
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199494"
---
# <a name="advanced-filtering"></a><span data-ttu-id="20b27-103">高度なフィルター</span><span class="sxs-lookup"><span data-stu-id="20b27-103">Advanced filtering</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]



<span data-ttu-id="20b27-104">計算を制御し、複数のフィールドにフィルターを適用することにより、Dynamics 365 Business Central のリストでの作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="20b27-104">Work efficiently in lists in Dynamics 365 Business Central by influencing calculations and applying filters to multiple fields.</span></span>

<span data-ttu-id="20b27-105">バックオフィスのインフォメーション ワーカーは、データの入力や変更、傾向や異常の分析、特定のレコードの単純な検索など、リストに関する作業に多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="20b27-105">Back-office information workers spend significant time working with lists: entering or modifying data, analyzing trends and anomalies, or simply looking for specific records.</span></span> <span data-ttu-id="20b27-106">簡易検索ではすべての列で最も近い一致を検索することによりリストを縮小できますが、ビジネス データベースのサイズが大きくなるとユーザーはさらに高度な制御を必要とすることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="20b27-106">While a quick search can reduce the list by finding the closest matches across all columns, users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="20b27-107">Business Central の強力なフィルター機能は、最新の直感的なエクスペリエンスによりフィルター処理の完全な制御を提供することで、リスト関連のタスクにかかる時間を短縮します。</span><span class="sxs-lookup"><span data-stu-id="20b27-107">The powerful filtering capabilities in Business Central accelerate list-related tasks by providing absolute control over filtering in a modern and intuitive experience.</span></span>

## <a name="filtering-lists"></a><span data-ttu-id="20b27-108">リストのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="20b27-108">Filtering lists</span></span>
<span data-ttu-id="20b27-109">リストの横に固定された新しいフィルター ウィンドウは、わかりやすく、効率よく作業できる使い慣れたデザインになっています。</span><span class="sxs-lookup"><span data-stu-id="20b27-109">Anchored to the side of your lists, the new filter pane has a familiar design that is easy to learn and efficient to work with.</span></span> <span data-ttu-id="20b27-110">リストのあらかじめ定義されたフィルター ビューを切り替え、独自のフィルターを追加してビューを調整し、何もない状態からでも簡単に始めることができます。</span><span class="sxs-lookup"><span data-stu-id="20b27-110">Switch between predefined filtered views of your list, adjust a view by adding your own filters, or simply start from scratch.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="20b27-111">![alt text](media/list-page-with-advanced-filter.png "リストの横に表示されているフィルター ウィンドウ。")</span><span class="sxs-lookup"><span data-stu-id="20b27-111">![alt text](media/list-page-with-advanced-filter.png "The filter pane, shown alongside a list.")</span></span>

<span data-ttu-id="20b27-112">フィルター ウィンドウでは次のことができます。</span><span class="sxs-lookup"><span data-stu-id="20b27-112">The filter pane allows you to:</span></span>

-   <span data-ttu-id="20b27-113">自分、フィルター ビュー、またはアプリケーション自体のいずれによって設定されたかに関わらず、現在適用されているフィルターの概要を取得します。</span><span class="sxs-lookup"><span data-stu-id="20b27-113">Get an overview of the currently applied filters, no matter if they were set by you, by a filtered view, or by the application itself.</span></span>
-   <span data-ttu-id="20b27-114">入力してソース テーブルの任意のフィールドからすばやく選択することにより、フィルター処理された列を好きなだけ追加します。</span><span class="sxs-lookup"><span data-stu-id="20b27-114">Add as many filtered columns as you like by typing to quickly pick from any field on the source table.</span></span>
-   <span data-ttu-id="20b27-115">ルックアップまたはフィールドのデータ型を使用してフィルター値指定のサポートを利用します。</span><span class="sxs-lookup"><span data-stu-id="20b27-115">Get assistance with specifying filter values using lookups or the field's data type.</span></span>
-   <span data-ttu-id="20b27-116">演算子、範囲、数式、%MyCustomers などの新しいフィルター トークンを使用して、複雑なフィルターを作成します。</span><span class="sxs-lookup"><span data-stu-id="20b27-116">Create complex filters using operators, ranges, formulas and the new filter tokens such as %MyCustomers.</span></span>
-   <span data-ttu-id="20b27-117">フィルターの変更を、リストのフィルターされていないビューまたは事前定義されたビューに戻します。</span><span class="sxs-lookup"><span data-stu-id="20b27-117">Revert your filter changes back to the unfiltered view or predefined view of the list.</span></span>

<span data-ttu-id="20b27-118">Business Central は、ユーザーがページ間をあちこち移動しても、セッションを通してユーザーが適用したフィルターを憶えています。</span><span class="sxs-lookup"><span data-stu-id="20b27-118">Business Central remembers the filters you applied throughout the session as you navigate back and forth across pages.</span></span> <span data-ttu-id="20b27-119">変更をフィルター ビューとして永続的に保存する機能は後日提供されます。</span><span class="sxs-lookup"><span data-stu-id="20b27-119">The ability to permanently save your changes as a filtered view will be available at a later date.</span></span>

<span data-ttu-id="20b27-120">フィルター ウィンドウは、リストがワークシートなどの主要コンテンツを表すすべてのページで使用できます。</span><span class="sxs-lookup"><span data-stu-id="20b27-120">The filter pane is available on all pages where the list represents the primary content, such as worksheets.</span></span> <span data-ttu-id="20b27-121">リスト パーツとして埋め込まれたリストは、引き続き簡単なフィルタリングを使用しており、フィルター ウィンドウは後日採用されます。</span><span class="sxs-lookup"><span data-stu-id="20b27-121">Lists embedded as list parts continue to use simple filtering and will adopt the filter pane at a later date.</span></span>

## <a name="filtering-totals"></a><span data-ttu-id="20b27-122">合計のフィルター処理</span><span class="sxs-lookup"><span data-stu-id="20b27-122">Filtering totals</span></span>
<span data-ttu-id="20b27-123">Dynamics NAV の最も好評な機能の 1 つが、Business Central に組み込まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="20b27-123">One of the most popular features of Dynamics NAV now makes its way to Business Central.</span></span> <span data-ttu-id="20b27-124">リストでは、合計金額など、集計値や計算値が FlowField で表示されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="20b27-124">Lists often display aggregated or computed values through FlowFields, such as currency amount totals.</span></span> <span data-ttu-id="20b27-125">このリリースの Business Central で提供されているまったく新しいレベルの制御機能を利用すると、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。</span><span class="sxs-lookup"><span data-stu-id="20b27-125">With this release, Business Central gives you a whole new level of control through which you can apply filters to one or more dimensions that influence computed values.</span></span> <span data-ttu-id="20b27-126">これをフィルター、並べ替え、検索と組み合わせて使用し、データを探索および分析します。</span><span class="sxs-lookup"><span data-stu-id="20b27-126">Use this in combination with filters, sort, and search to explore and analyze your data.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="20b27-127">キーボード ショートカット</span><span class="sxs-lookup"><span data-stu-id="20b27-127">Keyboard shortcuts</span></span>
<span data-ttu-id="20b27-128">フィルター ウィンドウはワン クリックで利用できますが、多彩で強力なキーボード ショートカットを使用して、マウスを使わずに作業することもできます。たとえば、Alt + F3 ショートカットは現在の値でフィルターを適用します。</span><span class="sxs-lookup"><span data-stu-id="20b27-128">Although the filter pane is just a click away, you can work mouse-free using a variety of powerful keyboard shortcuts, including the Alt+F3 shortcut to filter to the current value.</span></span> <span data-ttu-id="20b27-129">リストを離れることなくオンザフライで複合フィルターを作成でき、ショートカットを使用してセル間を移動し、現在フォーカスがある値にフィルターを適用したり、現在の列のフィルターをクリアしたりできます。</span><span class="sxs-lookup"><span data-stu-id="20b27-129">You can now create compound filters on the fly without ever leaving the list, using shortcuts to navigate across cells and then filter to the currently focused value or clear the filter on the current column.</span></span> <span data-ttu-id="20b27-130">すべてのキーボード ショートカットの一覧については、https://aka.ms/bckeys を参照してください。</span><span class="sxs-lookup"><span data-stu-id="20b27-130">Find the full list of keyboard shortcuts at https://aka.ms/bckeys.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup, in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available in all Dynamics 365 Business Central supported markets.
-->

## <a name="try-it-now"></a><span data-ttu-id="20b27-131">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="20b27-131">Try it now</span></span>
<span data-ttu-id="20b27-132">https://businesscentral.dynamics.com/?page=31 でオンライン環境にサインインし、**Shift + F3** キーを押してフィルター ウィンドウを表示して、品目リストで新しいフィルター ウィンドウをお試しください。</span><span class="sxs-lookup"><span data-stu-id="20b27-132">Try the new filter pane on the Items list by signing in to your online environment at https://businesscentral.dynamics.com/?page=31 and typing **Shift+F3** to show the filter pane.</span></span>

## <a name="resources"></a><span data-ttu-id="20b27-133">リソース</span><span class="sxs-lookup"><span data-stu-id="20b27-133">Resources</span></span>
[<span data-ttu-id="20b27-134">リストの並べ替え、検索、およびフィルター処理</span><span class="sxs-lookup"><span data-stu-id="20b27-134">Sorting, Searching and Filtering Lists</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-enter-criteria-filters)

[<span data-ttu-id="20b27-135">カレンダーの日付と時刻の操作</span><span class="sxs-lookup"><span data-stu-id="20b27-135">Working with calendar dates and times</span></span>](https://docs.microsoft.com/en-US/dynamics365/business-central/ui-enter-date-ranges)

[<span data-ttu-id="20b27-136">技術文書: フィルター トークンの追加</span><span class="sxs-lookup"><span data-stu-id="20b27-136">Technical documentation: adding Filter Tokens</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-adding-filter-tokens)

[<span data-ttu-id="20b27-137">検索とフィルター処理に関するよくある質問</span><span class="sxs-lookup"><span data-stu-id="20b27-137">Frequently asked questions about searching and filtering</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-search-filter-faq)

## <a name="tell-us-what-you-think"></a><span data-ttu-id="20b27-138">フィードバック</span><span class="sxs-lookup"><span data-stu-id="20b27-138">Tell us what you think</span></span>
<span data-ttu-id="20b27-139">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="20b27-139">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="20b27-140">Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="20b27-140">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>
