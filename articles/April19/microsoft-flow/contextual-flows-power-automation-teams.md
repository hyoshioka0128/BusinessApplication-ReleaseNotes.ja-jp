---
title: Microsoft Teams でのコンテキスト フローによる高度な自動化
description: Microsoft Flow は、すべてのユーザーが Microsoft Teams で高度な自動動作を使用できる手段になっています。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: f37358cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ad7835bf82f4e2a20196fe657f8fdc4de4d55c8e
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210733"
---
# <a name="contextual-flows-power-automation-in-microsoft-teams"></a><span data-ttu-id="807b7-103">Microsoft Teams でのコンテキスト フローによる高度な自動化</span><span class="sxs-lookup"><span data-stu-id="807b7-103">Contextual flows power automation in Microsoft Teams</span></span>




<span data-ttu-id="807b7-104">Microsoft Flow は、すべてのユーザーが Microsoft Teams で高度な自動動作を使用できる手段になっています。</span><span class="sxs-lookup"><span data-stu-id="807b7-104">Microsoft Flow is now the way that any user can have rich automatic behaviors in Microsoft Teams.</span></span> <span data-ttu-id="807b7-105">構想されているのは、Outlook の仕訳ルールのようなワールド クラスのエクスペリエンスを Microsoft Teams に提供することです。</span><span class="sxs-lookup"><span data-stu-id="807b7-105">Our vision is to deliver a world-class experience—like Outlook rules—for Microsoft Teams.</span></span> <span data-ttu-id="807b7-106">つまり、ユーザーが次のことをできるようにします。</span><span class="sxs-lookup"><span data-stu-id="807b7-106">This means that users can:</span></span>

- <span data-ttu-id="807b7-107">チームでの重要な更新に関する通知を外部のサービスから受け取り、それらに基づいて行動します。</span><span class="sxs-lookup"><span data-stu-id="807b7-107">Get notified about important updates in their teams from external services and act on them.</span></span>
- <span data-ttu-id="807b7-108">Teams のエクスペリエンスに直接組み込まれたコマンドとアクションを通じてサービスと対話します。</span><span class="sxs-lookup"><span data-stu-id="807b7-108">Interact with services through commands and actions directly built into the Teams experience.</span></span>
- <span data-ttu-id="807b7-109">Teams のイベントに基づいてワークフローを設定することで、チームワークを自動化します。</span><span class="sxs-lookup"><span data-stu-id="807b7-109">Automate teamwork by setting up workflows based on Teams events.</span></span>

<span data-ttu-id="807b7-110">これらの新機能は、Teams *アプリ* (専用の [フロー] タブなど) からだけでなく、メッセージやファイルなどのエンティティからメニュー項目を介してコンテキストに応じて有効にすることもできます。</span><span class="sxs-lookup"><span data-stu-id="807b7-110">These new capabilities are enabled through both the Teams *apps* (for example, a dedicated Flow tab) as well as contextually via menu items from entities like messages or files:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="807b7-111">![Microsoft Teams の統合ポイント](./media/TeamsIntegrationPoints-1.png "Microsoft Teams の統合ポイント")</span><span class="sxs-lookup"><span data-stu-id="807b7-111">![Microsoft Teams integration points](./media/TeamsIntegrationPoints-1.png "Microsoft Teams integration points")</span></span>

<span data-ttu-id="807b7-112">セットアップが簡単になっただけでなく、Microsoft Flow では、適応型カードによるチャネル通知、個人通知、さらには Team イベントやチャネル イベントのワークフローを作成する機能もサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="807b7-112">Beyond just easier setup, Microsoft Flow now supports channel notifications with adaptive cards, personal notifications, and even the ability to create workflows for Team or channel events.</span></span> <span data-ttu-id="807b7-113">シナリオの例をいくつか示します。</span><span class="sxs-lookup"><span data-stu-id="807b7-113">Some example scenarios include:</span></span>

- <span data-ttu-id="807b7-114">プロジェクト リーダーは、チームのプロジェクトについてだれかが話したときに通知を受けることができます。</span><span class="sxs-lookup"><span data-stu-id="807b7-114">As a project lead, you can get notified when someone talks about your project in a team.</span></span>
- <span data-ttu-id="807b7-115">チーム管理者は、新しいユーザーがチームに参加したときに、オンボーディング リソースへのリンクが含まれるウェルカム メッセージを送信することができます。</span><span class="sxs-lookup"><span data-stu-id="807b7-115">As a team admin, you can send out a welcome message, which includes links to onboarding resources to new users when they join your team.</span></span>
