---
title: キャンバス アプリで式や下位式の結果を表示する
description: キャンバス アプリで式や下位式の結果を表示する
author: gregli-msft
ms.reviewer: anneta
ms.date: 01/08/2019
ms.assetid: 97840ead-fbf0-e811-a976-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: 1f5fdaf8daa35d4be35eaccb078cda565cc9213c
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "286573"
---
# <a name="view-results-of-formulas-and-subformulas-in-canvas-apps"></a><span data-ttu-id="4ac53-103">キャンバス アプリで式や下位式の結果を表示する</span><span class="sxs-lookup"><span data-stu-id="4ac53-103">View results of formulas and subformulas in canvas apps</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="4ac53-104">キャンバス アプリは、**フィルター**や**ソート**などの関数を使って、強力な式を構成することで機能します。</span><span class="sxs-lookup"><span data-stu-id="4ac53-104">Canvas apps operate by composing functions, such as **Filter** and **Sort**, to form powerful formulas.</span></span> <span data-ttu-id="4ac53-105">式の結果は、ギャラリーなどのコントロールに直接送られ、さらなる解析にかけられることもあります。</span><span class="sxs-lookup"><span data-stu-id="4ac53-105">The result is often fed directly into a control, such as a gallery, which can interpret it further.</span></span>

<span data-ttu-id="4ac53-106">構成がさらに複雑になってくると、それぞれの関数が結果に及ぼす影響を把握するのが難しくなります。</span><span class="sxs-lookup"><span data-stu-id="4ac53-106">As compositions get more complex, it can become difficult to understand the impact of each function on the result.</span></span> <span data-ttu-id="4ac53-107">作成者は、中間結果を変数にキャプチャしたり、別のデバッグ画面でそれを表示したりすることがあります。</span><span class="sxs-lookup"><span data-stu-id="4ac53-107">Makers will sometimes capture intermediate results into variables or create separate debug screens to display them.</span></span> <span data-ttu-id="4ac53-108">透過性が欠如していると、何が起きているのか把握し、問題をデバッグするのが難しくなります。</span><span class="sxs-lookup"><span data-stu-id="4ac53-108">The lack of transparency makes it difficult to understand what's happening and debug issues.</span></span>

<span data-ttu-id="4ac53-109">この機能により、式の中身を把握し、何が起きているのか理解することができます。</span><span class="sxs-lookup"><span data-stu-id="4ac53-109">This feature helps you get into the middle of the formula and understand what's happening.</span></span> <span data-ttu-id="4ac53-110">他の多くのプログラミング環境と同様に、式バーでは、式全体や式の一部を直接選択して、その部分から流れているデータを表示することができます。</span><span class="sxs-lookup"><span data-stu-id="4ac53-110">As in many other programming environments, you can select the entire formula or parts of the formula directly from the formula bar and see the data that's flowing from just that portion.</span></span> <span data-ttu-id="4ac53-111">これにより、アプリ コードの把握やデバッグが大幅に簡単で迅速になります。</span><span class="sxs-lookup"><span data-stu-id="4ac53-111">Understanding and debugging apps get a lot easier and quicker.</span></span>

<span data-ttu-id="4ac53-112">次に示すのは、数式バーでコンテンツとアカウントの種類を選択したときの画面を表した初期概念図です。</span><span class="sxs-lookup"><span data-stu-id="4ac53-112">Here is an early conceptual sketch that shows the contents and type of account simply by selecting it in the formula bar:</span></span>

<span data-ttu-id="4ac53-113">![初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)](media/ResultView.png "初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)")</span><span class="sxs-lookup"><span data-stu-id="4ac53-113">![In an early conceptual sketch, Result View shows the value of what is selected in the formula bar, in this case the contents of Account table](media/ResultView.png "In an early conceptual sketch, Result View shows the value of what is selected in the formula bar, in this case the contents of Account table")</span></span>
