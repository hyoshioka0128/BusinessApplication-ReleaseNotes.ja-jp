---
title: 式ベースの書式設定
description: 式ベースの書式設定
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: 09117ce6ac57bacd95e1443c1de7ad643f88df76
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225214"
---
# <a name="expression-based-formatting"></a><span data-ttu-id="2ca64-103">式ベースの書式設定</span><span class="sxs-lookup"><span data-stu-id="2ca64-103">Expression-based formatting</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="2ca64-104">Power BI ではそのすべてのビジュアルに対してさまざまな書式設定オプションが用意されており、このリリースでは、レポート作成者のために、モデル内のデータに基づいて書式設定を動的に変更するためのより高度な制御が追加されています。</span><span class="sxs-lookup"><span data-stu-id="2ca64-104">Power BI provides a variety of formatting options for all its visuals, and this semester we’re adding more advanced controls for report authors to dynamically change formatting based on the data in their model.</span></span> <span data-ttu-id="2ca64-105">アナリストは、グラフ内のすべての要素の色、スタイル、または表示設定を変更する式を定義できます。</span><span class="sxs-lookup"><span data-stu-id="2ca64-105">Analysts can define expressions that modify the color, style or visibility of all elements within their charts.</span></span> <span data-ttu-id="2ca64-106">たとえば、金額が目標を超えるたらデータポイントの色が変わるように構成できます。</span><span class="sxs-lookup"><span data-stu-id="2ca64-106">For example, they might change the color of a datapoint when the amount exceeds a target:</span></span>

<span data-ttu-id="2ca64-107">![式ベースの書式設定を使用したデータの色](media/expression-based-formatting-1.png "式ベースの書式設定を使用したデータの色")</span><span class="sxs-lookup"><span data-stu-id="2ca64-107">![Data colors using expression-based formatting](media/expression-based-formatting-1.png "Data colors using expression-based formatting")</span></span>
<!-- picture -->
<span data-ttu-id="2ca64-108">*式ベースの書式設定を使用したデータの色*</span><span class="sxs-lookup"><span data-stu-id="2ca64-108">*Data colors using expression-based formatting*</span></span>

<span data-ttu-id="2ca64-109">または、シリーズの中の 1 行だけスタイルを調整して注意を促すこともできます。</span><span class="sxs-lookup"><span data-stu-id="2ca64-109">Or they might adjust the style of one line in a series to call attention to it:</span></span>

<span data-ttu-id="2ca64-110">![式ベースの書式設定を使用した線のスタイル](media/expression-based-formatting-2.png "式ベースの書式設定を使用した線のスタイル")</span><span class="sxs-lookup"><span data-stu-id="2ca64-110">![Line styles using expression-based formatting](media/expression-based-formatting-2.png "Line styles using expression-based formatting")</span></span>
<!-- picture -->
<span data-ttu-id="2ca64-111">*式ベースの書式設定を使用した線のスタイル*</span><span class="sxs-lookup"><span data-stu-id="2ca64-111">*Line styles using expression-based formatting*</span></span>

<span data-ttu-id="2ca64-112">書式設定は、任意の DAX 式に基づくことができ、レポート内のフィルターのコンテキストの影響を受けます。</span><span class="sxs-lookup"><span data-stu-id="2ca64-112">Formatting can be based on any DAX expression and is affected by the context of any filters in the report.</span></span>

<span data-ttu-id="2ca64-113">この機能は、次の Power BI アイデア要求に応えたものです。</span><span class="sxs-lookup"><span data-stu-id="2ca64-113">This feature addresses the following Power BI Ideas requests:</span></span>

-   [<span data-ttu-id="2ca64-114">全体的な条件付き書式設定</span><span class="sxs-lookup"><span data-stu-id="2ca64-114">Conditional formatting throughout</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/9588453-conditional-formatting-throughout)

-   [<span data-ttu-id="2ca64-115">より良い条件付き書式設定ツール</span><span class="sxs-lookup"><span data-stu-id="2ca64-115">Better conditional formatting tools</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/15495174-better-conditional-formatting-tools)

-   [<span data-ttu-id="2ca64-116">テキストの条件付き書式設定</span><span class="sxs-lookup"><span data-stu-id="2ca64-116">Conditional formatting for text</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/32184037-conditional-formatting-for-text)

-   [<span data-ttu-id="2ca64-117">列を使用してデータの色を動的に指定する (例: \#A66999)</span><span class="sxs-lookup"><span data-stu-id="2ca64-117">Dynamically specify data color using column e.g. \#A66999</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/13757925-dynamically-specify-data-colour-using-column-e-g)

[!include[feedback](../includes/desktop-feedback.md)]