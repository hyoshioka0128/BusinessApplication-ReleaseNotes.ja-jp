---
title: Dynamics 365 Remote Assist ユーザーと Microsoft Teams のエキスパートの間のグループ通話
description: 新しいグループ通話機能を使用すると、Microsoft Teams の複数のエキスパートが Dynamics 365 Remote Assist でユーザーを支援できます。
author: bencorn
ms.date: 04/02/2019
ms.topic: article
ms.service: business-applications
ms.author: becorn
ms.reviewer: v-brycho
ms.openlocfilehash: 714a9fab41a06022af75be118950544d5587fe68
ms.sourcegitcommit: 400975521747b572d34c7758bc5c887ff6fb55fc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/16/2019
ms.locfileid: "1755736"
---
#  <a name="group-calling"></a><span data-ttu-id="3537f-103">グループ通話</span><span class="sxs-lookup"><span data-stu-id="3537f-103">Group calling</span></span>
[!include[microsoft-dynamics365-remote-assist banner](../../includes/microsoft-dynamics365-remote-assist.md)]


<span data-ttu-id="3537f-104">グループ通話はお客様からの要望が最も多い機能です。</span><span class="sxs-lookup"><span data-stu-id="3537f-104">Group calling is our #1 customer request.</span></span> <span data-ttu-id="3537f-105">以前は、Remote Assist の通話には 2 人のユーザーしか参加できませんでした。HoloLens を利用する 1 人 (フィールド サービス作業者などの第一線の作業者) と、Microsoft Teams の 1 人 (エキスパート) です。</span><span class="sxs-lookup"><span data-stu-id="3537f-105">Previously Remote Assist calls could include just two users — one on HoloLens (the first-line worker, such as a field service worker) and one on Microsoft Teams (the expert).</span></span> <span data-ttu-id="3537f-106">グループ通話では、最大 50 人の Microsoft Teams のエキスパートが 1 つの通話に接続して注釈を付け、Remote Assist のユーザーが困難な問題の解決策を見つけ出せるように支援することができます。</span><span class="sxs-lookup"><span data-stu-id="3537f-106">With group calling, up to 50 experts on Microsoft Teams can connect and annotate in a single call to help the Remote Assist user figure out a difficult solution.</span></span>

<span data-ttu-id="3537f-107">グループ通話によって可能になるシナリオは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="3537f-107">Scenarios enabled by group calling include:</span></span>

- <span data-ttu-id="3537f-108">複数のエキスパートによるメンテナンス。</span><span class="sxs-lookup"><span data-stu-id="3537f-108">Maintenance involving multiple experts.</span></span>

- <span data-ttu-id="3537f-109">同じ通話に複数の検査担当者が参加して遠隔検査の品質を向上させたり、複雑な検査に協力したりできる検査。</span><span class="sxs-lookup"><span data-stu-id="3537f-109">Inspections where multiple inspectors on the same call can improve the quality of the remote inspection or work together on complex inspections.</span></span> 

- <span data-ttu-id="3537f-110">複数のエキスパートによるライブ トレーニング。</span><span class="sxs-lookup"><span data-stu-id="3537f-110">Live training involving multiple experts.</span></span> <span data-ttu-id="3537f-111">たとえば、修復作業を見て問題の解決方法を学びます。</span><span class="sxs-lookup"><span data-stu-id="3537f-111">For example, watch a repair to learn how to solve a problem.</span></span>

<span data-ttu-id="3537f-112">手順は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="3537f-112">Here's how it works.</span></span> <span data-ttu-id="3537f-113">HoloLens 上の 1 対 1 の通話から、ビデオ フィードの右上隅にある**参加者を開く**ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="3537f-113">From any one-to-one call on HoloLens, select the **Open Participants** button in the upper-right corner of the video feed.</span></span> 

<span data-ttu-id="3537f-114">![\[参加者を開く\] の選択のアニメーション](media/GC_OpenParticipantsList.gif "\[参加者を開く\] の選択のアニメーション")</span><span class="sxs-lookup"><span data-stu-id="3537f-114">![Animation of selecting Open Participants](media/GC_OpenParticipantsList.gif "Animation of selecting Open Participants")</span></span>

<span data-ttu-id="3537f-115">現在通話中の参加者のリストが表示されます。</span><span class="sxs-lookup"><span data-stu-id="3537f-115">In the list that appears, you’ll see a list of the participants currently in the call.</span></span> <span data-ttu-id="3537f-116">別の参加者を追加するには、リストの一番下にある**ユーザーの招待**を選択します。</span><span class="sxs-lookup"><span data-stu-id="3537f-116">To add another participant, select **Invite Someone** at the bottom of the list.</span></span> <span data-ttu-id="3537f-117">最近の連絡先のリストが表示されます。</span><span class="sxs-lookup"><span data-stu-id="3537f-117">You’ll see a list of your recent contacts appear.</span></span> <span data-ttu-id="3537f-118">通話したい相手がリストに含まれていない場合は、ホログラフィック キーボードで名前を入力して連絡先を検索し、名前を選択して通話に追加します。</span><span class="sxs-lookup"><span data-stu-id="3537f-118">If the list doesn’t contain the person you’d like to call, enter a name using the holographic keyboard to search for the contact, and then select their name to add them to the call.</span></span>

<span data-ttu-id="3537f-119">![通話の検索のアニメーション](media/GC_SearchCall.gif "通話の検索のアニメーション")</span><span class="sxs-lookup"><span data-stu-id="3537f-119">![Animation of searching for a call](media/GC_SearchCall.gif "Animation of searching for a call")</span></span>

<span data-ttu-id="3537f-120">通話に複数の参加者を追加したら、参加者リストで名前を選択してビデオ フィードを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="3537f-120">After you have several participants in your call, you can switch between video feeds by selecting a name in the participants list.</span></span> 

<span data-ttu-id="3537f-121">![ビデオ フィードの切り替えのアニメーション](media/GC_SwitchfromList.gif "ビデオ フィードの切り替えのアニメーション")</span><span class="sxs-lookup"><span data-stu-id="3537f-121">![Animation of video feed switch](media/GC_SwitchfromList.gif "Animation of video feed switch")</span></span>

<span data-ttu-id="3537f-122">この操作は、ビデオ フィードの下の領域からアバターを選択して行うこともできます。</span><span class="sxs-lookup"><span data-stu-id="3537f-122">You can also do this from the area below the video feed by selecting an avatar.</span></span>

<span data-ttu-id="3537f-123">![トレイの切り替えのアニメーション](media/GC_SwitchfromBar.gif "トレイの切り替えのアニメーション")</span><span class="sxs-lookup"><span data-stu-id="3537f-123">![Animation of tray switch](media/GC_SwitchfromBar.gif "Animation of tray switch")</span></span>

<span data-ttu-id="3537f-124">Teams デスクトップからも同じ操作ができます。</span><span class="sxs-lookup"><span data-stu-id="3537f-124">You can do the same thing from Teams Desktop.</span></span> <span data-ttu-id="3537f-125">1 対 1 の通話で、**参加者を表示**ボタンを選択し、Team で通常行うのと同様に追加の参加者を通話に招待します。</span><span class="sxs-lookup"><span data-stu-id="3537f-125">In any one-to-one call, select the **Show Participants** button and invite additional participants to the call, just like you normally would in Teams.</span></span> <span data-ttu-id="3537f-126">Teams の既存の 1 対 1 の通話またはグループ通話から HoloLens を呼び出すこともできます。</span><span class="sxs-lookup"><span data-stu-id="3537f-126">You can also call HoloLens from any existing Teams one-to-one or group call.</span></span> 

<span data-ttu-id="3537f-127">会議はまだサポートされていないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3537f-127">Keep in mind that we don’t support meetings yet.</span></span> 

<span data-ttu-id="3537f-128">Remote Assist でグループ通話を使用する方法の詳細については、「[Remote Assist ユーザー ガイド](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3537f-128">For more information on using group calling with Remote Assist, see the [Remote Assist User Guide](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide).</span></span> 

