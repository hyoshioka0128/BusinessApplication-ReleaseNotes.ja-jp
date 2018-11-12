---
title: "新しい Microsoft Flow ポータルとデザイナー エクスペリエンス"
description: "デザイナーの内部でのナビゲーションおよび検索アクション用の新しい Microsoft Flow エクスペリエンス。 これには、リッチ テキスト電子メール用の新しい HTML エディターによる編集機能の向上が含まれます。"
author: sunayv
manager: KVivek
ms.date: 10/20/2018
ms.assetid: 4f7e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sunayv
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: f569a3691cc7c3ac3d76ea67aaef6a06ce12ceef
ms.openlocfilehash: 3de0bdba57cb0d446ed27d55a9887f135019cbf8
ms.contentlocale: ja-jp
ms.lasthandoff: 10/27/2018

---
# <a name="new-flow-portal-and-designer-experience"></a><span data-ttu-id="b0092-104">新しい Flow ポータルとデザイナー エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="b0092-104">New Flow portal and designer experience</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="b0092-105">10 月のリリースの一環として、Microsoft Flow ポータルとデザイナーのエクスペリエンスのいくつかの重要な側面をオーバーホールしています。</span><span class="sxs-lookup"><span data-stu-id="b0092-105">As a part of the October release, we are overhauling several key aspects of the Microsoft Flow portal and designer experiences.</span></span>

## <a name="navigating-in-the-flow-portal"></a><span data-ttu-id="b0092-106">Flow ポータル内のナビゲーション</span><span class="sxs-lookup"><span data-stu-id="b0092-106">Navigating in the Flow portal</span></span>

<span data-ttu-id="b0092-107">Microsoft Flow ポータルには、さまざまな重要ページを見つけるまったく新しい方法があります。</span><span class="sxs-lookup"><span data-stu-id="b0092-107">We have an all-new way to find the different key pages on the Microsoft Flow portal.</span></span> <span data-ttu-id="b0092-108">以前は、ポータルの*上部*にいくつかのリンクがありました。</span><span class="sxs-lookup"><span data-stu-id="b0092-108">Previously, there were a few links along the *top* of the portal.</span></span> <span data-ttu-id="b0092-109">一部のページ (**接続**や**カスタム コネクタ**など) は右上の設定ギアに追いやられ、多くの人にとってこれらのページを見つけることは困難でした。</span><span class="sxs-lookup"><span data-stu-id="b0092-109">Some pages, such as **Connections** and **Custom connectors**, were relegated to the Settings gear in the top right, and many people had difficulty finding these pages.</span></span>

<span data-ttu-id="b0092-110">10 月のリリースでは、*左側*のナビゲーションに移動しています。</span><span class="sxs-lookup"><span data-stu-id="b0092-110">With the October release, we are moving to a *left-side* navigation.</span></span> <span data-ttu-id="b0092-111">この新しいナビゲーションには、**データ** セクションがあります。このセクションには**接続**面へのアクセスだけでなく、Common Data Service の**エンティティ**へのアクセスも含まれます。</span><span class="sxs-lookup"><span data-stu-id="b0092-111">This new navigation has a **Data** section, which includes access to aspects of **Connections**, but also to your Common Data Service **Entities**:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-112">![新しい左側のナビゲーション](media/flow-ui-enhancements-1.png "新しい左側のナビゲーション")</span><span class="sxs-lookup"><span data-stu-id="b0092-112">![New left-side navigation](media/flow-ui-enhancements-1.png "New left-side navigation")</span></span>

<span data-ttu-id="b0092-113">この変更が重要である理由として、近日中に提供されるソリューション管理機能など、将来的にナビゲーションに項目を追加できるようになることもあります。</span><span class="sxs-lookup"><span data-stu-id="b0092-113">This change is also important because it allows us to add more items into the navigation in the future, such as the solution management feature that is coming soon.</span></span> <span data-ttu-id="b0092-114">これにより、フローを論理コンポーネント (アイデア フォーラムの[上位のアイデア]( https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796)の 1 つ) にグループ化することができます。</span><span class="sxs-lookup"><span data-stu-id="b0092-114">This will enable you to group your flows into logical components (one of the [top ideas]( https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796) in the Ideas forum).</span></span>

<span data-ttu-id="b0092-115">最後に、左側のナビゲーションをナビゲーションの上部にあるボタンから展開および折りたたむことができます。</span><span class="sxs-lookup"><span data-stu-id="b0092-115">Finally, you can expand and collapse the left navigation from the button at the top of the nav.</span></span>

## <a name="the-my-flows-list"></a><span data-ttu-id="b0092-116">マイ フロー リスト</span><span class="sxs-lookup"><span data-stu-id="b0092-116">The My flows list</span></span>

<span data-ttu-id="b0092-117">マイ フロー リストのエクスペリエンスを簡略化し、他の Microsoft ユーザー インターフェイスと一貫させています。</span><span class="sxs-lookup"><span data-stu-id="b0092-117">We are simplifying the experience in the My flows list, and making it consistent with other Microsoft user interfaces.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-118">![簡略化されたマイ フロー リスト](media/flow-ui-enhancements-2.png "簡略化されたマイ フロー リスト")</span><span class="sxs-lookup"><span data-stu-id="b0092-118">![Simplified My flows list](media/flow-ui-enhancements-2.png "Simplified My flows list")</span></span>

<span data-ttu-id="b0092-119">この新しいエクスペリエンスでは、フロー リストから [実行] を選択することによって、*インスタント フロー* (モバイルの [フロー] ボタンによってトリガーされるフローなど) を実行できます。</span><span class="sxs-lookup"><span data-stu-id="b0092-119">In this new experience, you can run *Instant flows* (those flows triggered manually, such as flows triggered by the Flow button for mobile) by selecting the Run button from the Flow list.</span></span> <span data-ttu-id="b0092-120">また、オフになっているフローのアイコンを薄暗くすることで、どのフローがオンになっているのかを簡単に識別できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="b0092-120">We have also made it easier to identify which flows are on by dimming the icons of flows that are off.</span></span> 

## <a name="adding-triggers-and-actions-in-the-flow-designer"></a><span data-ttu-id="b0092-121">フロー デザイナーでのトリガーとアクションの追加</span><span class="sxs-lookup"><span data-stu-id="b0092-121">Adding triggers and actions in the Flow designer</span></span>

<span data-ttu-id="b0092-122">第 3 に、フロー デザイナーでトリガーとアクションを追加するための新しいエクスペリエンスがあります。</span><span class="sxs-lookup"><span data-stu-id="b0092-122">Third, we have a new experience for adding triggers and actions in the Flow designer.</span></span> <span data-ttu-id="b0092-123">**トリガー**を追加すると、次のようなエクスペリエンスが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b0092-123">When you add a **trigger** you will see an experience like this:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-124">![トリガーの追加](media/flow-ui-enhancements-3.png "トリガーの追加")</span><span class="sxs-lookup"><span data-stu-id="b0092-124">![Add a trigger](media/flow-ui-enhancements-3.png "Add a trigger")</span></span>

<span data-ttu-id="b0092-125">この新しいエクスペリエンスにより、コネクタをカテゴリ別に参照することができます。</span><span class="sxs-lookup"><span data-stu-id="b0092-125">This new experience gives you the ability to browse your connectors by category.</span></span> <span data-ttu-id="b0092-126">たとえば、環境内のどのコネクタが**プレミアム**または**カスタム** コネクタかを確認できます。</span><span class="sxs-lookup"><span data-stu-id="b0092-126">For example, you can see which connectors are **Premium** or the **Custom** connectors in your environment.</span></span>

<span data-ttu-id="b0092-127">次に、**新しいステップ**を選択したときに、アクションや条件などの追加の間に選択するセカンダリ ポップアップは表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="b0092-127">Next, when you select **New step**, you’ll no longer see the secondary flyout where you would choose between adding an action, condition, or more.</span></span> <span data-ttu-id="b0092-128">すぐに**アクションの選択**ダイアログが表示されるので、常に余分な選択を行う必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="b0092-128">Now, you’ll immediately be taken to the **Choose an action** dialog, which saves you from always making an extra selection.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-129">![アクションの選択](media/flow-ui-enhancements-4.png "アクションの選択")</span><span class="sxs-lookup"><span data-stu-id="b0092-129">![Choose an action](media/flow-ui-enhancements-4.png "Choose an action")</span></span>


<span data-ttu-id="b0092-130">すべての**コントロール** アクションをこのダイアログにまとめたので、依然として**条件**をすぐに選択できます。</span><span class="sxs-lookup"><span data-stu-id="b0092-130">We have combined all of the **Control** actions into this dialog, so you can still select **Condition** immediately.</span></span> <span data-ttu-id="b0092-131">**コントロール** コネクタを検索または選択して、Apply to Each やスコープのような他の制御フローの概念にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="b0092-131">You can search, or select the **Control** connector to get to the other control-flow concepts like Apply to Each or Scopes:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-132">![コントロール コネクタ](media/flow-ui-enhancements-5.png "コントロール コネクタ")</span><span class="sxs-lookup"><span data-stu-id="b0092-132">![Control connector](media/flow-ui-enhancements-5.png "Control connector")</span></span>


## <a name="edit-rich-html-content"></a><span data-ttu-id="b0092-133">豊富な HTML コンテンツの編集</span><span class="sxs-lookup"><span data-stu-id="b0092-133">Edit rich HTML content</span></span> 

<span data-ttu-id="b0092-134">HTML ベースの電子メール、Yammer 投稿用の HTML コンテンツ、ツイートなどの作成に役立ちつ新しいリッチな HTML ベースのテキスト エディターを追加しました。</span><span class="sxs-lookup"><span data-stu-id="b0092-134">We have added a new, rich HTML-based text editor that will help you write HTML-based emails, HTML content for your Yammer posts, tweets, and more.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0092-135">![HTML エディター](media/flow-ui-enhancements-6.png "HTML エディター")</span><span class="sxs-lookup"><span data-stu-id="b0092-135">![HTML editor](media/flow-ui-enhancements-6.png "HTML editor")</span></span>

<span data-ttu-id="b0092-136">このエディターでは、フォントのカスタマイズ、太字、イタリック、下線の使用、色のカスタマイズ、リストやリンクの作成を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="b0092-136">This editor allows you to customize the font, use bold, italic or underline, customize the color, create lists or links.</span></span> <span data-ttu-id="b0092-137">現時点では、表などの高度な機能はサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="b0092-137">At this time, it does not support advanced capabilities like Tables.</span></span>

