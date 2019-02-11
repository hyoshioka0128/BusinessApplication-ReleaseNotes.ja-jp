---
title: 式ベースの書式設定
description: 式ベースの書式設定
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: 07322232f68cc9621c1236be8cf3a8d6484c946c
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210925"
---
# <a name="expression-based-formatting"></a><span data-ttu-id="a6047-103">式ベースの書式設定</span><span class="sxs-lookup"><span data-stu-id="a6047-103">Expression-based formatting</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="a6047-104">Power BI ではそのすべてのビジュアルに対してさまざまな書式設定オプションが用意されており、このリリースでは、レポート作成者のために、モデル内のデータに基づいて書式設定を動的に変更するためのより高度な制御が追加されています。</span><span class="sxs-lookup"><span data-stu-id="a6047-104">Power BI provides a variety of formatting options for all its visuals, and this semester we’re adding more advanced controls for report authors to dynamically change formatting based on the data in their model.</span></span> <span data-ttu-id="a6047-105">アナリストは、グラフ内のすべての要素の色、スタイル、または表示設定を変更する式を定義できます。</span><span class="sxs-lookup"><span data-stu-id="a6047-105">Analysts can define expressions that modify the color, style or visibility of all elements within their charts.</span></span> <span data-ttu-id="a6047-106">たとえば、金額が目標を超えるたらデータポイントの色が変わるように構成できます。</span><span class="sxs-lookup"><span data-stu-id="a6047-106">For example, they might change the color of a datapoint when the amount exceeds a target:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="a6047-107">![式ベースの書式設定を使用したデータの色](media/expression-based-formatting-1.png "式ベースの書式設定を使用したデータの色")
<!-- picture -->
*式ベースの書式設定を使用したデータの色*</span><span class="sxs-lookup"><span data-stu-id="a6047-107">![Data colors using expression-based formatting](media/expression-based-formatting-1.png "Data colors using expression-based formatting")
<!-- picture -->
*Data colors using expression-based formatting*</span></span>

<span data-ttu-id="a6047-108">または、シリーズの中の 1 行だけスタイルを調整して注意を促すこともできます。</span><span class="sxs-lookup"><span data-stu-id="a6047-108">Or they might adjust the style of one line in a series to call attention to it:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="a6047-109">![式ベースの書式設定を使用した線のスタイル](media/expression-based-formatting-2.png "式ベースの書式設定を使用した線のスタイル")
<!-- picture -->
*式ベースの書式設定を使用した線のスタイル*</span><span class="sxs-lookup"><span data-stu-id="a6047-109">![Line styles using expression-based formatting](media/expression-based-formatting-2.png "Line styles using expression-based formatting")
<!-- picture -->
*Line styles using expression-based formatting*</span></span>

<span data-ttu-id="a6047-110">書式設定は、任意の DAX 式に基づくことができ、レポート内のフィルターのコンテキストの影響を受けます。</span><span class="sxs-lookup"><span data-stu-id="a6047-110">Formatting can be based on any DAX expression and is affected by the context of any filters in the report.</span></span>

<span data-ttu-id="a6047-111">この機能は、次の Power BI アイデア要求に応えたものです。</span><span class="sxs-lookup"><span data-stu-id="a6047-111">This feature addresses the following Power BI Ideas requests:</span></span>

-   [<span data-ttu-id="a6047-112">全体的な条件付き書式設定</span><span class="sxs-lookup"><span data-stu-id="a6047-112">Conditional formatting throughout</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/9588453-conditional-formatting-throughout)

-   [<span data-ttu-id="a6047-113">より良い条件付き書式設定ツール</span><span class="sxs-lookup"><span data-stu-id="a6047-113">Better conditional formatting tools</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/15495174-better-conditional-formatting-tools)

-   [<span data-ttu-id="a6047-114">テキストの条件付き書式設定</span><span class="sxs-lookup"><span data-stu-id="a6047-114">Conditional formatting for text</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/32184037-conditional-formatting-for-text)

-   [<span data-ttu-id="a6047-115">列を使用してデータの色を動的に指定する (例: \#A66999)</span><span class="sxs-lookup"><span data-stu-id="a6047-115">Dynamically specify data color using column e.g. \#A66999</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/13757925-dynamically-specify-data-colour-using-column-e-g)
