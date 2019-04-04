---
title: Microsoft Teams のアダプティブ カード
description: Flow ボットでチャネルにメッセージを投稿できるようになり、これらのメッセージにアダプティブ カードを含められるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 03/15/2019
ms.assetid: 3d8ad1f3-d30e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ea053c76eb4bc96440b97e2e9482f4b44897ff50
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880538"
---
# <a name="adaptive-cards-for-microsoft-teams"></a><span data-ttu-id="2ba89-103">Microsoft Teams のアダプティブ カード</span><span class="sxs-lookup"><span data-stu-id="2ba89-103">Adaptive cards for Microsoft Teams</span></span>

<span data-ttu-id="2ba89-104">独自の_アダプティブ カード_を Flow ボットとしてチャネルに投稿できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2ba89-104">You can now post your own _adaptive card_ as the Flow bot to a channel.</span></span> <span data-ttu-id="2ba89-105">アダプティブ カードは、充実した書式設定を利用したコンテンツを Microsoft Teams (Teams) の会話に直接表示するための手段です。</span><span class="sxs-lookup"><span data-stu-id="2ba89-105">An adaptive card is a way to present richly formatted content directly into a Microsoft Teams (Teams) conversation.</span></span> <span data-ttu-id="2ba89-106">アダプティブ カードには、画像、グラフ、充実した書式設定を利用したテキストなどのコンポーネントを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-106">Adaptive cards can contain components like images, graphs, richly formatted text, and more.</span></span> <span data-ttu-id="2ba89-107">開始するには、Teams コネクタで新しいアクションを選択します。</span><span class="sxs-lookup"><span data-stu-id="2ba89-107">To get started, select the new action on the Teams connector:</span></span>

![Teams アクションの一覧](media/adaptive-cards-teams-1.png)

<span data-ttu-id="2ba89-109">アダプティブ カードでは、さまざまなチャネルで使用できる共通の JSON 形式を使用します。</span><span class="sxs-lookup"><span data-stu-id="2ba89-109">Adaptive cards use a common JSON format that you can use across many different channels.</span></span> <span data-ttu-id="2ba89-110">ただし、この JSON を手作業で作成する必要はありません。[アダプティブ カード Web サイトの機能豊富なドラッグ アンド ドロップ デザイナー](https://adaptivecards.io/designer/)を使用してカードを作成できます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-110">However, you don't need to author this JSON by hand - you can use the [rich drag-and-drop designer on the Adaptive Cards website](https://adaptivecards.io/designer/) to build your card.</span></span>

![アダプティブ カード デザイナー](media/adaptive-cards-teams-2.png)

<span data-ttu-id="2ba89-112">カードに必要なすべての要素を追加したら、下部の JSON ウィンドウを開き、そこに含まれるすべてのコンテンツをコピーします。</span><span class="sxs-lookup"><span data-stu-id="2ba89-112">Once you have added all of the elements that you want on the card, open the JSON pane at the bottom and copy everything there.</span></span> <span data-ttu-id="2ba89-113">次に、Microsoft Flow デザイナーで、アクションの**メッセージ** フィールドにそのコンテンツを貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-113">Then, paste that content into the **Message** field on the action in the Microsoft Flow designer.</span></span> <span data-ttu-id="2ba89-114">アクションが実行されると、選択した Teams チャネルに、見栄えよく書式設定されたアダプティブ カードが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-114">When the action runs, a nicely formatted adaptive card appears in the Teams channel you selected:</span></span>

![Teams チャネルに表示されたカード](media/adaptive-cards-teams-3.png)

<span data-ttu-id="2ba89-116">アダプティブ カードを投稿するだけでなく、単純なメッセージをボットとして Teams チャネルに投稿することもできます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-116">In addition to posting an adaptive card, you can also post a simple message as a bot to a Teams channel.</span></span> <span data-ttu-id="2ba89-117">これらのメッセージを、自分のユーザー アカウントではなく Flow ボットから送信できます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-117">These messages can come from the Flow bot instead of your user account.</span></span> <span data-ttu-id="2ba89-118">また、メッセージに他のユーザーの **@mentions** を含めて、メッセージを投稿したときに対象ユーザーに通知が送られるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="2ba89-118">In addition, these messages can contain **@mentions** of other users, so they will be notified when you post.</span></span> <span data-ttu-id="2ba89-119"> *\*@mention** を作成するには、そのユーザーの電子メール アドレスまたはユーザー ID を `<at>` タグで囲む必要があります。</span><span class="sxs-lookup"><span data-stu-id="2ba89-119">To create an **@mention** you need to surround their email address or user ID with the `<at>` tag.</span></span> <span data-ttu-id="2ba89-120">たとえば、次のようにします。</span><span class="sxs-lookup"><span data-stu-id="2ba89-120">For example:</span></span>

```
Hello <at>stephen@example.com</at> - your request has been completed!
```