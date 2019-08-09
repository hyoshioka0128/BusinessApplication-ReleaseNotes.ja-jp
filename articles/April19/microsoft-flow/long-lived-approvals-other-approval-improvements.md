---
title: 長期にわたる承認のサポートとその他の改善点
description: Microsoft Flow の承認には、30 日を超える承認のサポート、送信された承認を取り消す機能、受信トレイ内の承認要求の自動クリーンアップ、承認メールを制御する機能など、多くの改善点があります。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: 76e85cbf-1397-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 482b368a762f0fb1b288c96fae1963e4d52aef1b
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757245"
---
# <a name="long-running-approvals-and-other-improvements"></a><span data-ttu-id="fb038-103">長期にわたる承認とその他の改善点</span><span class="sxs-lookup"><span data-stu-id="fb038-103">Long-running approvals and other improvements</span></span>



<span data-ttu-id="fb038-104">Microsoft Flow では、承認を要求し、それらの応答に基づいて動作するワークフローを簡単に自動化できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-104">Microsoft Flow makes it easy to automate workflows that request approvals and act on their responses.</span></span> <span data-ttu-id="fb038-105">現在、[フローの実行は 30 日後にタイムアウトになり](https://docs.microsoft.com/flow/limits-and-config#run-duration-and-retention)、保留中のステップ (承認など) もタイムアウトになります。</span><span class="sxs-lookup"><span data-stu-id="fb038-105">Currently, [flow runs time out after 30 days](https://docs.microsoft.com/flow/limits-and-config#run-duration-and-retention), causing any pending steps (like approvals) to time out as well.</span></span> <span data-ttu-id="fb038-106">これはほとんどの承認にとって問題ではありませんが、承認への応答に 30 日より長くかかる場合もあります。</span><span class="sxs-lookup"><span data-stu-id="fb038-106">While this isn’t a problem for most approvals, there are cases where responding to an approval can take longer than 30 days.</span></span>

<span data-ttu-id="fb038-107">承認が Common Data Service に保存されている場合、元のフロー実行がタイムアウトになった後でも、承認要求に対する応答に基づいて動作するフローを作成できるようになりました。これを行うには、2 つのフローを使用します。1 つは承認要求を送信するためのもので、もう 1 つは新しい**承認の作成 (v2)** に基づいて承認要求への応答に対してビジネス ロジックを実行するためのものです。</span><span class="sxs-lookup"><span data-stu-id="fb038-107">With approvals stored in Common Data Service, you can now create flows that act on responses to approval requests, even after the original flow run times out. To do this, use two flows—one to send an approval request and the other to run business logic on the responses to the approval request, based on the new **Create an approval (v2)**.</span></span>

<span data-ttu-id="fb038-108">[無期限に実行される承認プロセスを作成する方法に関するステップバイステップの説明を入手してください](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Build-long-running-Approval-Flows/ba-p/279890)。</span><span class="sxs-lookup"><span data-stu-id="fb038-108">[Get step-by-step instructions on how to create approval processes that run indefinitely](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Build-long-running-Approval-Flows/ba-p/279890).</span></span>

## <a name="cancel-sent-approvals"></a><span data-ttu-id="fb038-109">送信済みの承認を取り消す</span><span class="sxs-lookup"><span data-stu-id="fb038-109">Cancel sent approvals</span></span>

<span data-ttu-id="fb038-110">自分が送信した承認要求を取り消したい場合があります。</span><span class="sxs-lookup"><span data-stu-id="fb038-110">Sometimes you might want to retract an approval request that you've sent.</span></span> <span data-ttu-id="fb038-111">要求に間違いがあったか、要求が不要になった可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fb038-111">Possibly you made a mistake in the request, or it’s no longer relevant.</span></span> <span data-ttu-id="fb038-112">どちらの場合でも、要求を送信した人は今すぐそれを**キャンセル**できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-112">In either case, the person who sent the request can now **Cancel** it.</span></span>

![[キャンセル] ボタン](media/cancelbuttoninpanel.png)

<span data-ttu-id="fb038-114">そのためには、承認を選択してから、サイド ペインで**承認を取り消し**を選択します。</span><span class="sxs-lookup"><span data-stu-id="fb038-114">To do so, select the approval and then select **Cancel approval** in the side pane.</span></span> <span data-ttu-id="fb038-115">いつでも**履歴**タブを選択して、取り消した承認要求を表示できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-115">You can always select the **History** tab to view the approval requests that you've canceled.</span></span>

![履歴内でのキャンセル](media/cancelapprovals.png)

> [!NOTE]
> <span data-ttu-id="fb038-117">キャンセル機能は、**承認の作成 (v2)** アクションでのみ動作します。</span><span class="sxs-lookup"><span data-stu-id="fb038-117">The cancel feature only works with the **Create an approval (v2)** action.</span></span>

## <a name="automatic-cleanup-of-approval-requests-in-your-inbox"></a><span data-ttu-id="fb038-118">受信トレイ内の承認要求の自動クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="fb038-118">Automatic cleanup of approval requests in your inbox</span></span>

<span data-ttu-id="fb038-119">Microsoft Flow の承認要求は受信トレイに直接送信できるため、迅速に応答できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-119">Microsoft Flow approval requests can be sent directly to your inbox, which makes it easy to quickly respond.</span></span> <span data-ttu-id="fb038-120">ただし、メールは自分 (および他の承認者) の受信トレイに保存されるため、既に処理された承認に関するメールが残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fb038-120">However, since the email is saved in your (and other approvers') inbox, you might end up with emails for approvals that have already been handled.</span></span>

![更新された承認](media/approvalupdatedinemail.png)

<span data-ttu-id="fb038-122">現在、最新の電子メール クライアントでは、承認が完了したことを示すために電子メールが自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="fb038-122">Now, with modern email clients, we will automatically update the email to indicate that the approval is completed.</span></span> <span data-ttu-id="fb038-123">つまり、特定の承認が既に承認または拒否されているかどうかを気にする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="fb038-123">This means you’ll never have to wonder if a given approval has already been approved or rejected.</span></span>

## <a name="control-the-approval-email"></a><span data-ttu-id="fb038-124">承認メールの管理</span><span class="sxs-lookup"><span data-stu-id="fb038-124">Control the approval email</span></span>

<span data-ttu-id="fb038-125">最後に、送信された承認メールを構成するフロー作成者がサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fb038-125">Finally, we now support the flow author configuring the approval emails that are sent.</span></span> <span data-ttu-id="fb038-126">**承認の作成 (v2)** アクションでは、**詳細オプションの表示**を選択した場合に、新しい**通知の有効化**オプションがあります。</span><span class="sxs-lookup"><span data-stu-id="fb038-126">For the **Create an approval (v2)** action, if you select **Show advanced options**, there is a new **Enable notifications** option.</span></span> <span data-ttu-id="fb038-127">組み込みのメール テンプレートが組織の要件を満たしていない場合は、これを**いいえ**に設定し、組み込みの通知メールを抑制できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-127">If the built-in email template doesn’t meet your organization’s requirements, you can set this to **No** and suppress the built-in notification email.</span></span>

<span data-ttu-id="fb038-128">組み込みのメールを無効にしたら、承認の詳細を使用し、組み込みの汎用アカウントや共有メールボックスの使用など、Microsoft Flow のメール送信方法のいずれかを使用して、承認に関する完全にカスタマイズされたメールを送信できます。</span><span class="sxs-lookup"><span data-stu-id="fb038-128">Once you’ve disabled the built-in email, you can use the details of the approval to send a fully customized email about the approval, using any of the ways to send emails in Microsoft Flow, including the built-in generic account or using shared mailboxes.</span></span>


