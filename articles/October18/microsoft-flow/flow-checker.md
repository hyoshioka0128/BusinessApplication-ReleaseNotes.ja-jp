---
title: フロー チェッカー
description: フロー チェッカーは、向上した検証およびエラー修正エクスペリエンスを提供します。 フロー内のエラーや警告がある場所についてのコンテキスト内ヘルプを取得し、それらのエラーを修正する方法のガイドを参照できます。
author: sunayv
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: 4d7e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: sunayv
audience: Power user
ms.openlocfilehash: f54b48a3ab71bde73ac2032f59b09cbd6bbc5ff9
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "390998"
---
# <a name="flow-checker"></a><span data-ttu-id="44490-104">フロー チェッカー</span><span class="sxs-lookup"><span data-stu-id="44490-104">Flow checker</span></span>




<span data-ttu-id="44490-105">新しい**フロー チェッカー**機能は、ベスト プラクティスに従うようにすることで高品質のフローを促進します。</span><span class="sxs-lookup"><span data-stu-id="44490-105">The new **Flow checker** feature will promote higher quality flows by ensuring you follow best practices.</span></span> <span data-ttu-id="44490-106">チェッカーを実行すると、フローの実装でパフォーマンスや信頼性のリスクがある部分はどこかといった疑問への回答を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="44490-106">By running the checker, you will be able to get answers to questions like: which areas of my flow implementation pose a performance or reliability risk?</span></span>

<span data-ttu-id="44490-107">検出された問題ごとに、**フロー チェッカー**はフロー内で改良が必要な可能性のある特定の場所を指摘します。</span><span class="sxs-lookup"><span data-stu-id="44490-107">For each issue identified, the **Flow checker** points to specific occurrences within the flow where improvements may be required.</span></span> <span data-ttu-id="44490-108">さらに重要なこととして、詳細なガイダンスに従うことで、これらの機能強化を導入する方法がわかるようになっています。</span><span class="sxs-lookup"><span data-stu-id="44490-108">And more importantly, you learn how to implement these improvements by following detailed guidance.</span></span> 

<span data-ttu-id="44490-109">まず、フロー チェッカーがデザイナーのコマンド バーに表示され、フローで 1 つ以上のエラーが識別されると赤いドットが表示されます。</span><span class="sxs-lookup"><span data-stu-id="44490-109">To begin, the Flow checker appears in the command bar in the designer and will show a red dot when one or more errors are identified in your flow.</span></span>

<span data-ttu-id="44490-110">![コマンド バーのフロー チェッカー](media/flow-checker-1.png "コマンド バーのフロー チェッカー")</span><span class="sxs-lookup"><span data-stu-id="44490-110">![Flow checker in the command bar](media/flow-checker-1.png "Flow checker in the command bar")</span></span>

<span data-ttu-id="44490-111">このボタンを選択して、チェッカーを開きます。</span><span class="sxs-lookup"><span data-stu-id="44490-111">Select this button to open the checker.</span></span> <span data-ttu-id="44490-112">フローにエラーがある場合は、保存しようとするとチェッカーが開きます。</span><span class="sxs-lookup"><span data-stu-id="44490-112">If there are errors in the flow, the checker opens when you try to save it.</span></span> <span data-ttu-id="44490-113">チェッカーが開くと、フロー内のすべてのエラーと警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="44490-113">Once the checker opens, it shows all errors and warnings in your flow.</span></span> <span data-ttu-id="44490-114">各セクションの内側で、チェッカーはエラーまたは警告が発生したアクションを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="44490-114">Inside each section, the checker calls out the actions where the error or warning occurs.</span></span>

<span data-ttu-id="44490-115">![開いているフロー チェッカー ウィンドウ](media/flow-checker-2.png "開いているフロー チェッカー ウィンドウ")</span><span class="sxs-lookup"><span data-stu-id="44490-115">![Flow checker pane open](media/flow-checker-2.png "Flow checker pane open")</span></span>

<span data-ttu-id="44490-116">エラーを修正するためにさらに詳細が必要な場合は、行を選択して追加のガイダンスを表示します。</span><span class="sxs-lookup"><span data-stu-id="44490-116">If you need more details to fix an error, select the row to receive additional guidance.</span></span> <span data-ttu-id="44490-117">フロー チェッカーはいくつかの基本的なシナリオで開始しますが、今後数か月にわたってガイダンスが追加される予定です。</span><span class="sxs-lookup"><span data-stu-id="44490-117">The Flow checker is now starting with some basic scenarios, but look forward to more guidance being added over the coming months.</span></span>