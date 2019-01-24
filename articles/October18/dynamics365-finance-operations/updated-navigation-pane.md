---
title: "ナビゲーション ウィンドウの使いやすさの向上"
description: "ナビゲーション ウィンドウにいくつかの機能拡張が追加され、使いやすさが向上しました。"
author: jasongre
manager: AnnBe
ms.date: 01/08/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 287edd26bf4a52d9f1d65fd4cbfa237080431db3
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

# <a name="improved-usability-of-the-navigation-pane"></a><span data-ttu-id="bb21d-103">ナビゲーション ウィンドウの使いやすさの向上</span><span class="sxs-lookup"><span data-stu-id="bb21d-103">Improved usability of the navigation pane</span></span>

<span data-ttu-id="bb21d-104">ナビゲーション ウィンドウは、Finance and Operations でよく使われるナビゲーション メカニズムであり、お気に入り、最近開いたページ、ワークスペース、メイン メニューへのアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="bb21d-104">The navigation pane is a highly used navigation mechanism in Finance and Operations that provides access to favorites, recently opened pages, workspaces, and the main menu.</span></span> <span data-ttu-id="bb21d-105">使用頻度が高いので、ナビゲーション ウィンドウは使いやすさを向上させるためにいくつかの方法で強化されています。</span><span class="sxs-lookup"><span data-stu-id="bb21d-105">Because of its high usage, the navigation pane has been enhanced in a few ways to improve its usability.</span></span> <span data-ttu-id="bb21d-106">これらの変更は、Platform Update 22 以降で利用できます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-106">These changes are available starting in Platform Update 22.</span></span> 

1. <span data-ttu-id="bb21d-107">**ビジュアル スタイルの向上**</span><span class="sxs-lookup"><span data-stu-id="bb21d-107">**Improved visual styling**</span></span>

    <span data-ttu-id="bb21d-108">メニュー構造内の異なる階層レベルをよりよく区別し、メニュー階層内でワークスペース タイルをより視覚的に整理するために、対象となるスタイル変更がナビゲーション ウィンドウに適用されています。</span><span class="sxs-lookup"><span data-stu-id="bb21d-108">Targeted styling changes have been applied to the navigation pane to better distinguish the different hierarchical levels in the menu structure and to make workspace tiles fit better visually inside the menu hierarchy.</span></span> 
    
    <span data-ttu-id="bb21d-109">たとえば、次の画像は、Platform Update 21 以前のナビゲーション ウィンドウを示しています。</span><span class="sxs-lookup"><span data-stu-id="bb21d-109">For example, the following image shows the navigation pane in Platform Update 21 and earlier.</span></span> <span data-ttu-id="bb21d-110">ワークスペース タイルが多くの空間を占めることにご注意ください。</span><span class="sxs-lookup"><span data-stu-id="bb21d-110">Notice that the workspace tiles take up a lot of room.</span></span>

    <span data-ttu-id="bb21d-111">![Platform Update 21 以前のナビゲーション ウィンドウ](media/oldNavPane.png "Platform Update 21 以前のナビゲーション ウィンドウ")</span><span class="sxs-lookup"><span data-stu-id="bb21d-111">![Navigation pane in Platform Update 21 and earlier](media/oldNavPane.png "Navigation pane in Platform Update 21 and earlier")</span></span>

    <span data-ttu-id="bb21d-112">*前: Platform Update 21 以前のナビゲーション ウィンドウ*</span><span class="sxs-lookup"><span data-stu-id="bb21d-112">*Before: The navigation pane in Platform Update 21 and earlier*</span></span>
    
    <span data-ttu-id="bb21d-113">次の画像は、Platform Update 22 のナビゲーション ウィンドウを示しています。</span><span class="sxs-lookup"><span data-stu-id="bb21d-113">The following image shows the navigation pane in Platform Update 22.</span></span> <span data-ttu-id="bb21d-114">ワークスペース タイルがよりよく整理されていることにご注意ください。</span><span class="sxs-lookup"><span data-stu-id="bb21d-114">Notice that the workspace tiles fit better.</span></span>

    <span data-ttu-id="bb21d-115">![Platform Update 22 より後のナビゲーション ウィンドウ](media/newNavPane.png  "Platform Update 22 より後のナビゲーション ウィンドウ")</span><span class="sxs-lookup"><span data-stu-id="bb21d-115">![Navigation pane after Platform Update 22](media/newNavPane.png  "Navigation pane after Platform Update 22")</span></span>

    <span data-ttu-id="bb21d-116">*後: Platform Update 22 以降のナビゲーション ウィンドウ*</span><span class="sxs-lookup"><span data-stu-id="bb21d-116">*After: The navigation pane in Platform Update 22 and later*</span></span>

2.  <span data-ttu-id="bb21d-117">**既定で折りたたまれているメニュー**</span><span class="sxs-lookup"><span data-stu-id="bb21d-117">**Collapsed menus by default**</span></span>

    <span data-ttu-id="bb21d-118">モジュール メニューをより使いやすく、ユーザーをわずらわせないものにするために、各ユーザーがほぼ完全に折りたたまれたモジュール メニューから開始するようにしています。次の画像に示すように、既定では**ワークスペース** フォルダーだけが展開されます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-118">To make our module menus more approachable and less overwhelming to users, we are now starting each user off with almost completely collapsed module menus; only the **Workspaces** folder is expanded by default, as shown in the following image.</span></span>

    <span data-ttu-id="bb21d-119">![メニューがほぼ完全に折りたたまれた状態で開始](media/collapsedNavPane.png  "メニューがほぼ完全に折りたたまれた状態で開始")</span><span class="sxs-lookup"><span data-stu-id="bb21d-119">![Menus now start out almost completely collapsed](media/collapsedNavPane.png  "Menus now start out almost completely collapsed")</span></span>

    <span data-ttu-id="bb21d-120">*ユーザーが初めてモジュールを開いたとき、最初はほとんどのモジュール メニューが折りたたまれて表示される*</span><span class="sxs-lookup"><span data-stu-id="bb21d-120">*When users first open a module, they will see that most module menus are collapsed initially*</span></span>

3.  <span data-ttu-id="bb21d-121">**メニュー全体をすばやく展開し、折りたたむ**</span><span class="sxs-lookup"><span data-stu-id="bb21d-121">**Quickly expand and collapse an entire menu**</span></span>

    <span data-ttu-id="bb21d-122">**すべて展開**と**すべて折りたたむ**のボタンが各モジュールのメニューの上部に追加されているので、ユーザーはシングル クリックでメニューを完全に展開または折りたたむことができます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-122">**Expand all** and **Collapse all** buttons have been added to the top of each module's menu to allow users to fully expand or collapse the menu with a single click.</span></span> <span data-ttu-id="bb21d-123">**すべて展開**は、ユーザーが探しているものが明確ではないが、完全なモジュール メニューを簡単に表示したいような閲覧シナリオに特に便利です。</span><span class="sxs-lookup"><span data-stu-id="bb21d-123">The **Expand all** button is particularly useful for browsing scenarios where users aren't exactly sure what they're looking for, but would like an easy way to see the full module menu.</span></span> <span data-ttu-id="bb21d-124">**すべて折りたたむ**を使用すると、ユーザーは基準の開始点にすばやく戻ることができます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-124">The **Collapse all** button lets users quickly return to a base starting point.</span></span>  

4.  <span data-ttu-id="bb21d-125">**メニュー状態を記憶する**</span><span class="sxs-lookup"><span data-stu-id="bb21d-125">**Remembering menu states**</span></span> 

    <span data-ttu-id="bb21d-126">ナビゲーション ウィンドウに対する最も魅力的な機能強化は、各メニューの展開/折りたたみ状態がシステムに記憶され、次回モジュールを開くときに、メニューが前回の終了時と同じ状態で表示されるようになったことです。</span><span class="sxs-lookup"><span data-stu-id="bb21d-126">The most exciting enhancement to the navigation pane is that the system now remembers the expand/collapse state of each menu, so that the next time you open a module, the menu will be in the same state that you left it in.</span></span> <span data-ttu-id="bb21d-127">これにより、ユーザーは決して使用しないフォルダーやめったに使用しないフォルダーを常時折りたたむと同時に、頻繁に使用するリンクがあるフォルダーを展開したままにすることができます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-127">This allows users to keep the folders they never or rarely use collapsed all the time, while at the same time the folders with links they frequently use stay expanded.</span></span>
    
    <span data-ttu-id="bb21d-128">たとえば、**ベンダー** フォルダーと**発注書**フォルダーに最も頻繁に使用するメニュー項目が含まれる場合、この 2 つのフォルダーを展開でき、次回このメニューを開いたときにそれらが展開されます。</span><span class="sxs-lookup"><span data-stu-id="bb21d-128">For example, if the **Vendors** and **Purchase orders** folders contain the menu items you use most often, you can expand those two folders, and they will be expanded for you the next time you open this menu.</span></span>

    <span data-ttu-id="bb21d-129">![次回](media/partialNavPane.png  "次回")</span><span class="sxs-lookup"><span data-stu-id="bb21d-129">![The next time](media/partialNavPane.png  "The next time")</span></span>

    <span data-ttu-id="bb21d-130">*システムに各メニューの拡大/縮小状態が記憶される*</span><span class="sxs-lookup"><span data-stu-id="bb21d-130">*The system now remembers the expand/collapse state of each menu*</span></span>


