---
title: キャンバス アプリで式や下位式の結果を表示する
description: キャンバス アプリで式や下位式の結果を表示する
author: gregli-msft
ms.reviewer: pehecke
ms.date: 04/22/2019
ms.assetid: c188bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: dff4496aae1dc166426dfbc188263e90e04c536b
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1993943"
---
# <a name="view-results-of-formulas-and-subformulas-in-canvas-apps-public-preview"></a><span data-ttu-id="64ecb-103">キャンバス アプリで式や下位式の結果を表示する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="64ecb-103">View results of formulas and subformulas in canvas apps (Public Preview)</span></span>



<span data-ttu-id="64ecb-104">キャンバス アプリは、**フィルター**や**ソート**などの関数を使って、強力な式を構成することで機能します。</span><span class="sxs-lookup"><span data-stu-id="64ecb-104">Canvas apps operate by composing functions, such as **Filter** and **Sort**, to form powerful formulas.</span></span> <span data-ttu-id="64ecb-105">式の結果は、ギャラリーなどのコントロールに直接送られ、さらなる解析にかけられることもあります。</span><span class="sxs-lookup"><span data-stu-id="64ecb-105">The result is often fed directly into a control, such as a gallery, which can interpret it further.</span></span>

<span data-ttu-id="64ecb-106">構成がさらに複雑になってくると、それぞれの関数が結果に及ぼす影響を把握するのが難しくなります。</span><span class="sxs-lookup"><span data-stu-id="64ecb-106">As compositions get more complex, it can become difficult to understand the impact of each function on the result.</span></span> <span data-ttu-id="64ecb-107">作成者は、中間結果を変数にキャプチャしたり、別のデバッグ画面でそれを表示したりすることがあります。</span><span class="sxs-lookup"><span data-stu-id="64ecb-107">Makers will sometimes capture intermediate results into variables or create separate debug screens to display them.</span></span> <span data-ttu-id="64ecb-108">透過性が欠如していると、何が起きているのか把握し、問題をデバッグするのが難しくなります。</span><span class="sxs-lookup"><span data-stu-id="64ecb-108">The lack of transparency makes it difficult to understand what's happening and debug issues.</span></span>

<span data-ttu-id="64ecb-109">この機能により、式の中身を把握し、何が起きているのか理解することができます。</span><span class="sxs-lookup"><span data-stu-id="64ecb-109">This feature helps you get into the middle of the formula and understand what's happening.</span></span> <span data-ttu-id="64ecb-110">他の多くのプログラミング環境と同様に、式バーでは、式全体や式の一部を直接選択して、その部分から流れているデータを表示することができます。</span><span class="sxs-lookup"><span data-stu-id="64ecb-110">As in many other programming environments, you can select the entire formula or parts of the formula directly from the formula bar and see the data that's flowing from just that portion.</span></span> <span data-ttu-id="64ecb-111">これにより、アプリ コードの把握やデバッグが大幅に簡単で迅速になります。</span><span class="sxs-lookup"><span data-stu-id="64ecb-111">Understanding and debugging apps get a lot easier and quicker.</span></span>

<span data-ttu-id="64ecb-112">次に示すのは、数式バーでコンテンツとアカウントの種類を選択したときの画面を表した初期概念図です。</span><span class="sxs-lookup"><span data-stu-id="64ecb-112">Here is an early conceptual sketch that shows the contents and type of account simply by selecting it in the formula bar:</span></span>

<span data-ttu-id="64ecb-113">![初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)](media/ResultView.png "初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)")</span><span class="sxs-lookup"><span data-stu-id="64ecb-113">![In an early conceptual sketch, Result View shows the value of what is selected in the formula bar, in this case the contents of Account table](media/ResultView.png "In an early conceptual sketch, Result View shows the value of what is selected in the formula bar, in this case the contents of Account table")</span></span>
