---
title: フロー チェッカー
description: フロー チェッカーは、向上した検証およびエラー修正エクスペリエンスを提供します。 フロー内のエラーや警告がある場所についてのコンテキスト内ヘルプを取得し、それらのエラーを修正する方法のガイドを参照できます。
author: sunayv
ms.reviewer: deonhe
ms.date: 01/02/2019
ms.assetid: 4d7e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: sunayv
audience: Power user
ms.openlocfilehash: 8a899a8318be46179187f04560465f3a61879cfb
ms.sourcegitcommit: 851bbbbeaac02e33829dfbf5f6f8e4055acf0822
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "203712"
---
# <a name="flow-checker"></a><span data-ttu-id="b34bd-104">フロー チェッカー</span><span class="sxs-lookup"><span data-stu-id="b34bd-104">Flow checker</span></span>




<span data-ttu-id="b34bd-105">新しい**フロー チェッカー**機能は、ベスト プラクティスに従うようにすることで高品質のフローを促進します。</span><span class="sxs-lookup"><span data-stu-id="b34bd-105">The new **Flow checker** feature will promote higher quality flows by ensuring you follow best practices.</span></span> <span data-ttu-id="b34bd-106">チェッカーを実行すると、フローの実装でパフォーマンスや信頼性のリスクがある部分はどこかといった疑問への回答を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="b34bd-106">By running the checker, you will be able to get answers to questions like: which areas of my flow implementation pose a performance or reliability risk?</span></span>

<span data-ttu-id="b34bd-107">検出された問題ごとに、**フロー チェッカー**はフロー内で改良が必要な可能性のある特定の場所を指摘します。</span><span class="sxs-lookup"><span data-stu-id="b34bd-107">For each issue identified, the **Flow checker** points to specific occurrences within the flow where improvements may be required.</span></span> <span data-ttu-id="b34bd-108">さらに重要なのは、詳細なガイダンスに従うことで、これらの機能強化をどのように導入できるがわかります。</span><span class="sxs-lookup"><span data-stu-id="b34bd-108">And more importantly, you learn how to implement these improvements by following detailed guidance.</span></span> 

<span data-ttu-id="b34bd-109">まず、フローチェッカーがデザイナーのコマンド バーに表示され、フローで 1 つ以上のエラーが識別されると赤いドットが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b34bd-109">To begin, the Flow checker appears in the command bar in the designer and will show a red dot when one or more errors are identified in your flow:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b34bd-110">![コマンド バーのフロー チェッカー](media/flow-checker-1.png "コマンド バーのフロー チェッカー")</span><span class="sxs-lookup"><span data-stu-id="b34bd-110">![Flow checker in the command bar](media/flow-checker-1.png "Flow checker in the command bar")</span></span>

<span data-ttu-id="b34bd-111">このボタンを選択して、チェッカーを開きます。</span><span class="sxs-lookup"><span data-stu-id="b34bd-111">Select this button to open the checker.</span></span> <span data-ttu-id="b34bd-112">フローにエラーがある場合は、保存しようとするとチェッカーが開きます。</span><span class="sxs-lookup"><span data-stu-id="b34bd-112">If there are errors in the flow, the checker opens when you try to save it.</span></span> <span data-ttu-id="b34bd-113">チェッカーが開くと、フロー内のすべてのエラーと警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="b34bd-113">Once the checker opens, it shows all errors and warnings in your flow.</span></span> <span data-ttu-id="b34bd-114">各セクションの内側で、チェッカーはエラーまたは警告が発生したアクションを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="b34bd-114">Inside each section, the checker calls out the actions where the error or warning occurs:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b34bd-115">![開いているフロー チェッカー ウィンドウ](media/flow-checker-2.png "開いているフロー チェッカー ウィンドウ")</span><span class="sxs-lookup"><span data-stu-id="b34bd-115">![Flow checker pane open](media/flow-checker-2.png "Flow checker pane open")</span></span>

<span data-ttu-id="b34bd-116">エラーを修正するためにさらに詳細が必要な場合は、行を選択して追加のガイダンスを表示します。</span><span class="sxs-lookup"><span data-stu-id="b34bd-116">If you need more details to fix an error, select the row to receive additional guidance.</span></span> <span data-ttu-id="b34bd-117">フロー チェッカーはいくつかの基本的なシナリオで開始しますが、今後数か月にわたってガイダンスが追加される予定です。</span><span class="sxs-lookup"><span data-stu-id="b34bd-117">The Flow checker is now starting with some basic scenarios, but look forward to more guidance being added over the coming months.</span></span>