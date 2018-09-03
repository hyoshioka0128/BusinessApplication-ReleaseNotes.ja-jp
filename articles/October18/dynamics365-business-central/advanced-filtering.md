---
title: "高度なフィルター"
description: "強力なフィルター機能によりデスクトップでの生産性が向上します。"
author: mikebcMSFT
manager: edupont04
ms.date: 07/22/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 655306cb22bb19d608dc90c6435fd91047efa488
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
# <a name="advanced-filtering"></a><span data-ttu-id="16d48-103">高度なフィルター</span><span class="sxs-lookup"><span data-stu-id="16d48-103">Advanced filtering</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]



<span data-ttu-id="16d48-104">計算を制御し、複数のフィールドにフィルターを適用することにより、Dynamics 365 Business Central のリストでの作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="16d48-104">Work efficiently in lists in Dynamics 365 Business Central by influencing calculations and applying filters to multiple fields.</span></span>

<span data-ttu-id="16d48-105">バックオフィスのインフォメーション ワーカーは、データの入力や変更、傾向や異常の分析、特定のレコードの単純な検索など、リストに関する作業に多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="16d48-105">Back-office information workers spend significant time working with lists: entering or modifying data, analyzing trends and anomalies, or simply looking for specific records.</span></span> <span data-ttu-id="16d48-106">簡易検索ではすべての列で最も近い一致を検索することによりリストを縮小できますが、ビジネス データベースのサイズが大きくなるとユーザーはさらに高度な制御を必要とすることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="16d48-106">While a quick search can reduce the list by finding the closest matches across all columns, users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="16d48-107">Business Central の強力なフィルター機能は、最新の直感的なエクスペリエンスによりフィルター処理の完全な制御を提供することで、リスト関連のタスクにかかる時間を短縮します。</span><span class="sxs-lookup"><span data-stu-id="16d48-107">The powerful filtering capabilities in Business Central accelerate list-related tasks by providing absolute control over filtering in a modern and intuitive experience.</span></span>

## <a name="filtering-lists"></a><span data-ttu-id="16d48-108">リストのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="16d48-108">Filtering lists</span></span>
<span data-ttu-id="16d48-109">リストの横に固定された新しいフィルター ウィンドウは、わかりやすく、効率よく作業できる使い慣れたデザインになっています。</span><span class="sxs-lookup"><span data-stu-id="16d48-109">Anchored to the side of your lists, the new filter pane has a familiar design that is easy to learn and efficient to work with.</span></span> <span data-ttu-id="16d48-110">リストのあらかじめ定義されたフィルター ビューを切り替え、独自のフィルターを追加してビューを調整し、何もない状態からでも簡単に始めることができます。</span><span class="sxs-lookup"><span data-stu-id="16d48-110">Switch between predefined filtered views of your list, adjust a view by adding your own filters, or simply start from scratch.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="16d48-111">![alt text](media/list-page-with-advanced-filter.png "リストの横に固定されたフィルター ウィンドウの初期の設計概念。")</span><span class="sxs-lookup"><span data-stu-id="16d48-111">![alt text](media/list-page-with-advanced-filter.png "Early design concept for a filter pane anchored alongside a list.")</span></span>

<span data-ttu-id="16d48-112">フィルター ウィンドウでは次のことができます。</span><span class="sxs-lookup"><span data-stu-id="16d48-112">The filter pane allows you to:</span></span>

-   <span data-ttu-id="16d48-113">現在適用されているフィルターの概要を取得し、自分、フィルター ビュー、またはアプリケーション自体のいずれによって設定されたかを確認します。</span><span class="sxs-lookup"><span data-stu-id="16d48-113">Get an overview of the currently applied filters, and see if they were set by you, by a filtered view, or by the application itself.</span></span>
-   <span data-ttu-id="16d48-114">入力によって列のフィルターを好きなだけ追加し、ソース テーブルでより多くのフィールドをすばやく検索します。</span><span class="sxs-lookup"><span data-stu-id="16d48-114">Add as many filtered columns as you like by typing to quickly search for more fields on the source table.</span></span>
-   <span data-ttu-id="16d48-115">ルックアップまたはフィールドのデータ型を使用してフィルター値指定のサポートを利用します。</span><span class="sxs-lookup"><span data-stu-id="16d48-115">Get assistance with specifying filter values using lookups or the field's data type.</span></span>
-   <span data-ttu-id="16d48-116">演算子、範囲、変数、省略形を使用して複雑なフィルターを作成します。</span><span class="sxs-lookup"><span data-stu-id="16d48-116">Create complex filters using operators, ranges, variables, and shorthand.</span></span>
-   <span data-ttu-id="16d48-117">リストの現在のセル値でフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="16d48-117">Filter to the current cell value in the list.</span></span>

<span data-ttu-id="16d48-118">Business Central は、ユーザーがページ間をあちこち移動しても、セッションを通してユーザーが適用したフィルターを憶えています。</span><span class="sxs-lookup"><span data-stu-id="16d48-118">Business Central remembers the filters you applied throughout the session as you navigate back and forth across pages.</span></span> <span data-ttu-id="16d48-119">変更をフィルター ビューとして永続的に保存する機能は後日提供されます。</span><span class="sxs-lookup"><span data-stu-id="16d48-119">The ability to permanently save your changes as a filtered view will be available at a later date.</span></span>

<span data-ttu-id="16d48-120">フィルター ウィンドウは、ワークシート、ドキュメントの行、一覧部分など、リストが表示されるすべてのページで使用できます。</span><span class="sxs-lookup"><span data-stu-id="16d48-120">The filter pane is available on all pages that display lists, including worksheets, document lines, and list parts.</span></span>
<span data-ttu-id="16d48-121">この機能は、個々の列見出しから使用可能な以前のフィルター ウィンドウに代わるもので、検索や並べ替えなど、特定の行の発見やデータの分析を補助する他の機能を補完します。</span><span class="sxs-lookup"><span data-stu-id="16d48-121">This feature replaces the previous filter window reachable from each column header, and it complements other features that help you find specific rows or analyze your data, such as searching and sorting.</span></span>

## <a name="limit-totals"></a><span data-ttu-id="16d48-122">集計の絞り込み</span><span class="sxs-lookup"><span data-stu-id="16d48-122">Limit totals</span></span>
<span data-ttu-id="16d48-123">Dynamics NAV の最も好評な機能の 1 つが、Business Central に組み込まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="16d48-123">One of the most popular features of Dynamics NAV now makes its way to Business Central.</span></span> <span data-ttu-id="16d48-124">リストでは、合計金額など、集計値や計算値が表示されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="16d48-124">Lists often display aggregated or computed values, such as currency amount totals.</span></span> <span data-ttu-id="16d48-125">このリリースの Business Central で提供されているまったく新しいレベルの制御機能を利用すると、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。</span><span class="sxs-lookup"><span data-stu-id="16d48-125">With this release, Business Central gives you a whole new level of control through which you can apply filters to one or more dimensions that influence computed values.</span></span> <span data-ttu-id="16d48-126">これをフィルター、並べ替え、検索と組み合わせて使用し、データを探索および分析します。</span><span class="sxs-lookup"><span data-stu-id="16d48-126">Use this in combination with filters, sort, and search to explore and analyze your data.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="16d48-127">キーボード ショートカット</span><span class="sxs-lookup"><span data-stu-id="16d48-127">Keyboard shortcuts</span></span>
<span data-ttu-id="16d48-128">フィルター ウィンドウはワン クリックで利用できますが、多彩なキーボード ショートカットの組み合わせによるマウスなしのエクスペリエンスも利用できます。たとえば、Alt + F3 ショートカットは現在の値でフィルターを適用します。</span><span class="sxs-lookup"><span data-stu-id="16d48-128">Although the filter pane is just a click away, you can also have a mouse-free experience with a variety of keyboard shortcut combinations, including the Alt+F3 shortcut to filter to the current value.</span></span> <span data-ttu-id="16d48-129">リストを離れることなくオンザフライで複合フィルターを作成でき、ショートカットを使用してセル間を移動し、現在フォーカスがある値にフィルターを適用したり、現在の列のフィルターをクリアしたりできます。</span><span class="sxs-lookup"><span data-stu-id="16d48-129">You can now create compound filters on the fly without ever leaving the list, using shortcuts to navigate across cells and then filter to the currently focused value or clear the filter on the current column.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup, in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available in all Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="16d48-130">フィードバック</span><span class="sxs-lookup"><span data-stu-id="16d48-130">Tell us what you think</span></span>
<span data-ttu-id="16d48-131">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="16d48-131">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="16d48-132">Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="16d48-132">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>

