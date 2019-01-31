---
title: Teams の Microsoft Flow タブ
description: チーム チャネルのユーザーは、チャネルにコマンドを入力してやり取りするだけで、新しいタブやテキストを使用して対話できます。
author: Mhade
ms.reviewer: deonhe
ms.date: 01/02/2019
ms.assetid: 450627f1-ce73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mhade
audience: Power user
ms.openlocfilehash: 8f10c60ec195bb2f5e813c3cf4b26b33e54d1868
ms.sourcegitcommit: 851bbbbeaac02e33829dfbf5f6f8e4055acf0822
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "203530"
---
# <a name="microsoft-flow-tab-in-teams"></a><span data-ttu-id="b73b4-103">Teams の Microsoft Flow タブ</span><span class="sxs-lookup"><span data-stu-id="b73b4-103">Microsoft Flow tab in Teams</span></span>

<span data-ttu-id="b73b4-104">当社は最近、_ユーザー_がフローを作成および管理し、フロー ボットからフローを起動できる[個人用 Teams アプリ](https://flow.microsoft.com/blog/microsoft-flow-in-microsoft-teams/)をリリースしました。これらの操作はすべて Teams 内で行います。</span><span class="sxs-lookup"><span data-stu-id="b73b4-104">Recently, we released a [personal Teams app](https://flow.microsoft.com/blog/microsoft-flow-in-microsoft-teams/) that allowed _you_ to create and manage flows and launch flows from the Flow Bot—all within Teams.</span></span> <span data-ttu-id="b73b4-105">これらの機能を [フロー] タブで_チーム全員_に拡張しました。コントソの戦略・計画チームのメンバーになったつもりで考えてみてください。</span><span class="sxs-lookup"><span data-stu-id="b73b4-105">We’ve now extended these capabilities to _everyone in the team_ with a Flow Tab. Let’s imagine that you’re a member of the Strategy and Planning team at Contoso.</span></span> <span data-ttu-id="b73b4-106">"仕様" という単語を含むドキュメントが SharePoint にアップロードされるたびに、チームに通知する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b73b4-106">You’d like to alert the team whenever a document that contains the word "spec" is uploaded to SharePoint.</span></span> <span data-ttu-id="b73b4-107">Teams での Microsoft Flow の統合により、それを正確に行うフローをすばやく作成し、すぐにチームと共有して、必要に応じて他のユーザーが編集できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-107">With the Microsoft Flow integration in Teams, you can quickly create a flow that does exactly that, and immediately share it with your team so that others can make edits if required.</span></span> 

## <a name="flow-tab-in-teams"></a><span data-ttu-id="b73b4-108">Teams の [フロー] タブ</span><span class="sxs-lookup"><span data-stu-id="b73b4-108">Flow tab in Teams</span></span>

<span data-ttu-id="b73b4-109">まず、Teams で戦略・計画チームに移動し、[フロー] タブを [全般] チャネルに追加します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-109">To get started, navigate to the Strategy and Planning team in Teams and add the Flow tab to the General channel.</span></span> <span data-ttu-id="b73b4-110">そのためには、タブの追加 (＋) ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-110">To do so, select the Add a tab (+) button.</span></span>

<span data-ttu-id="b73b4-111">![タブの追加](media/flow-tab-teams-1.png "タブの追加")</span><span class="sxs-lookup"><span data-stu-id="b73b4-111">![Add a tab](media/flow-tab-teams-1.png "Add a tab")</span></span>

<span data-ttu-id="b73b4-112">次に、**すべてのタブ** カテゴリから**フロー**を選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-112">Next, select **Flow** from the **All Tabs** category.</span></span> <span data-ttu-id="b73b4-113">**インストール**に続いて**保存**を選択して、インストールを終了します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-113">Finish the installation by choosing **Install**, followed by **Save**.</span></span> <span data-ttu-id="b73b4-114">プロンプトが表示されたら、サインインします。</span><span class="sxs-lookup"><span data-stu-id="b73b4-114">If prompted, sign in.</span></span>

<span data-ttu-id="b73b4-115">![すべてのタブから選択](media/flow-tab-teams-2.png "すべてのタブから選択")</span><span class="sxs-lookup"><span data-stu-id="b73b4-115">![Select from all tabs](media/flow-tab-teams-2.png "Select from all tabs")</span></span>

## <a name="create-a-flow"></a><span data-ttu-id="b73b4-116">フローの作成</span><span class="sxs-lookup"><span data-stu-id="b73b4-116">Create a flow</span></span>

<span data-ttu-id="b73b4-117">Microsoft Flow にサインインしたら、空白からフローを作成するかテンプレートから選ぶかを選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-117">Once you’ve signed in to Microsoft Flow, choose to create a flow from blank or select from a template.</span></span> <span data-ttu-id="b73b4-118">Microsoft Flow では、チームを SharePoint、Microsoft Forms、Twitter、UserVoice などのさまざまなサービスに接続できます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-118">With Microsoft Flow, you can connect your team to a wide variety of services like SharePoint, Microsoft Forms, Twitter, and UserVoice.</span></span> <span data-ttu-id="b73b4-119">**テンプレートからの作成**を選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-119">Select **Create from template.**</span></span>  

<span data-ttu-id="b73b4-120">![テンプレートからの作成](media/flow-tab-teams-3.png "テンプレートからの作成")</span><span class="sxs-lookup"><span data-stu-id="b73b4-120">![Create from template](media/flow-tab-teams-3.png "Create from template")</span></span>

<span data-ttu-id="b73b4-121">**特定のドキュメントがアップロードされたらチームに通知**というラベルの付いたテンプレートを選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-121">Now choose the template labeled **Alert the team when specific documents are uploaded.**</span></span>

<span data-ttu-id="b73b4-122">![テンプレートの選択](media/flow-tab-teams-4.png "テンプレートの選択")</span><span class="sxs-lookup"><span data-stu-id="b73b4-122">![Select template](media/flow-tab-teams-4.png "Select template")</span></span>

<span data-ttu-id="b73b4-123">プロンプトが表示されたら、接続を確認し、**続行**を選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-123">When prompted, verify your connections and select **Continue**.</span></span>

<span data-ttu-id="b73b4-124">![続行を選択](media/flow-tab-teams-5.png "続行を選択")</span><span class="sxs-lookup"><span data-stu-id="b73b4-124">![Select Continue](media/flow-tab-teams-5.png "Select Continue")</span></span>

<span data-ttu-id="b73b4-125">Microsoft Flow デザイナーで、Teams アクションである [チームに通知] に現在のチームとチャネルに事前に入力されています。</span><span class="sxs-lookup"><span data-stu-id="b73b4-125">In the Microsoft Flow designer, the Teams action, Alert the team, is pre-populated with your current Team and Channel.</span></span>

<span data-ttu-id="b73b4-126">![「はい」の分岐アクション設定の設定](media/flow-tab-teams-6.png "「はい」の分岐アクション設定の設定")</span><span class="sxs-lookup"><span data-stu-id="b73b4-126">![Set the Yes branch action setting](media/flow-tab-teams-6.png "Set the Yes branch action setting")</span></span>

<span data-ttu-id="b73b4-127">トリガー - [ファイルが作成されたとき (プロパティのみ)] の [サイト アドレス] と [ライブラリ名] を選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-127">Choose a Site Address and Library Name for the trigger - When a file is created (properties only).</span></span> <span data-ttu-id="b73b4-128">この例では、戦略・計画サイトとドキュメント ライブラリを選択します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-128">In this example, we’ll choose the Strategy and Planning site and the Documents library.</span></span> <span data-ttu-id="b73b4-129">条件では、ファイル名に "仕様" が含まれている場合にチームに通知します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-129">In the Condition, we’ll Alert the team when the file name contains “Spec.”</span></span>

<span data-ttu-id="b73b4-130">![フロー条件](media/flow-tab-teams-6_a.png "フロー条件")</span><span class="sxs-lookup"><span data-stu-id="b73b4-130">![Flow condition](media/flow-tab-teams-6_a.png "Flow condition")</span></span>

<span data-ttu-id="b73b4-131">最後に、[チームに通知] アクションで、メッセージを次のようにカスタマイズします。</span><span class="sxs-lookup"><span data-stu-id="b73b4-131">Finally, in the Alert the team action, customize the message to look like the following:</span></span>

<span data-ttu-id="b73b4-132">![メッセージの内容](media/flow-tab-teams-7.png "メッセージの内容")</span><span class="sxs-lookup"><span data-stu-id="b73b4-132">![Message content](media/flow-tab-teams-7.png "Message content")</span></span>

<span data-ttu-id="b73b4-133">**保存**を選択してフローを保存してから閉じます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-133">Save and then close the flow by choosing **Save.**</span></span> <span data-ttu-id="b73b4-134">フローが保存されると、自動的にチームと共有され、チームのメンバーはだれでもフローを編集できます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-134">Once the flow is saved, it is automatically shared with the team and any member of the team can edit the flow.</span></span>

<span data-ttu-id="b73b4-135">![フローの一覧](media/flow-tab-teams-7_a.png "フローの一覧")</span><span class="sxs-lookup"><span data-stu-id="b73b4-135">![List of flows](media/flow-tab-teams-7_a.png "List of flows")</span></span>

<span data-ttu-id="b73b4-136">![チームの所有権](media/flow-tab-teams-8.png "チームの所有権")</span><span class="sxs-lookup"><span data-stu-id="b73b4-136">![Team ownership](media/flow-tab-teams-8.png "Team ownership")</span></span>

<span data-ttu-id="b73b4-137">"仕様" という単語を含む新しいドキュメントがアップロードされると、ファイルへのリンクおよびフローに設定したテキストと共に、新しいメッセージがチャネルに投稿されます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-137">When a new document containing the word “spec” is uploaded, a new message is posted to the channel with a link to the file and the text you set in the flow.</span></span>   

<span data-ttu-id="b73b4-138">![投稿されたメッセージ](media/flow-tab-teams-9.png "投稿されたメッセージ")</span><span class="sxs-lookup"><span data-stu-id="b73b4-138">![Message posted](media/flow-tab-teams-9.png "Message posted")</span></span>

## <a name="use-the-bot-to-launch-flows"></a><span data-ttu-id="b73b4-139">ボットを使用してフローを起動する</span><span class="sxs-lookup"><span data-stu-id="b73b4-139">Use the bot to launch flows</span></span>

<span data-ttu-id="b73b4-140">個人用アプリと同じように、[フロー] タブには手動フローやスケジュールに基づいてトリガーされるフローを実行できるボットが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b73b4-140">Just like the personal app, the Flow tab includes a bot that enables you to run manual flows and those triggered on a schedule.</span></span> <span data-ttu-id="b73b4-141">毎週実行され、チームにメッセージを投稿して今後の技術デモを全員に知らせるフローがあるとしましょう。</span><span class="sxs-lookup"><span data-stu-id="b73b4-141">Let’s suppose that we have a flow that runs weekly and posts a message to the team reminding everyone of upcoming tech demos.</span></span> <span data-ttu-id="b73b4-142">[このブログ投稿](https://flow.microsoft.com/blog/email-digest-date-manipulations/)で、そのようなフローの作成方法を確認できます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-142">You can check out [this blog post](https://flow.microsoft.com/blog/email-digest-date-manipulations/) on how to create such a flow.</span></span> <span data-ttu-id="b73b4-143">フロー ボットを使用すると、このフローをすぐに実行できます。</span><span class="sxs-lookup"><span data-stu-id="b73b4-143">With the Flow Bot, you can run this flow immediately.</span></span>

<span data-ttu-id="b73b4-144">[会話] タブで、「\@Flow」に続けてコマンド `List flows` を入力します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-144">In the Conversations tab, enter \@Flow followed by the command `List flows`.</span></span> <span data-ttu-id="b73b4-145">フローの一覧に戻ったら、コマンド `Run flow` に続けて実行するフローのインデックスを入力します。</span><span class="sxs-lookup"><span data-stu-id="b73b4-145">Once you get back a list of flows, enter the command `Run flow` followed by the index of the flow you want to run.</span></span> <span data-ttu-id="b73b4-146">たとえば、`Run flow 1` などとします。</span><span class="sxs-lookup"><span data-stu-id="b73b4-146">For example, `Run flow 1`.</span></span>

<span data-ttu-id="b73b4-147">![ボット メッセージ](media/flow-tab-teams-10.png "ボット メッセージ")</span><span class="sxs-lookup"><span data-stu-id="b73b4-147">![Bot messages](media/flow-tab-teams-10.png "Bot messages")</span></span>
