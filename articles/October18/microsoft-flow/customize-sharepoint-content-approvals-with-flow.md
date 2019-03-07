---
title: Microsoft Flow による SharePoint ページの承認のカスタマイズ
description: SharePoint ライブラリのページの承認フローを作成して、すべての新規ページと更新されたページのレビュー プロセスを追加します。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: fbc151eb-4a98-e811-a969-000d3a1378f6
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: b3be7e0cd0cde47d7872a3de179a3e5742656957
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391040"
---
# <a name="customize-sharepoint-page-approvals-with-microsoft-flow"></a><span data-ttu-id="e8112-103">Microsoft Flow による SharePoint ページの承認のカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="e8112-103">Customize SharePoint page approvals with Microsoft Flow</span></span>




<span data-ttu-id="e8112-104">最近の SharePointサイトでは、所有者はサイトの標準公開プロセスを向上させるためにページの承認を構成できます。</span><span class="sxs-lookup"><span data-stu-id="e8112-104">For any modern SharePoint site, owners can configure page approvals to improve the standard publishing process for the site.</span></span> <span data-ttu-id="e8112-105">ページの承認フローを追加した後、新規ページと更新されたページは直接公開されなくなります。</span><span class="sxs-lookup"><span data-stu-id="e8112-105">After adding a page approval flow, new and updated pages will be not be published directly.</span></span> <span data-ttu-id="e8112-106">代わりに、ページに変更が加えられるたびに、そのページは保留中モードになり、承認のために送信されます。</span><span class="sxs-lookup"><span data-stu-id="e8112-106">Instead, whenever a change is made to a page, it's put into pending mode and then submitted for approval.</span></span> <span data-ttu-id="e8112-107">その結果、指定された承認者の新しい承認項目が作成されます。</span><span class="sxs-lookup"><span data-stu-id="e8112-107">This in turn results in a new approval item for the designated approvers.</span></span> <span data-ttu-id="e8112-108">承認者は変更をレビューし、埋め込み Microsoft Flow エクスペリエンスを使用して SharePoint で直接承認するか、承認センターを介して応答します。</span><span class="sxs-lookup"><span data-stu-id="e8112-108">An approver reviews changes and then either approves them directly in SharePoint by using the embedded Microsoft Flow experience or responds via the approvals center.</span></span> <span data-ttu-id="e8112-109">応答は電話で、または電子メールから直接行われます。</span><span class="sxs-lookup"><span data-stu-id="e8112-109">Responses are done by phone or directly from email.</span></span> <span data-ttu-id="e8112-110">承認者が応答すると、コンテンツ作成者に通知され、変更が公開され、ページが更新されます。</span><span class="sxs-lookup"><span data-stu-id="e8112-110">When an approver responds, the content author is notified, the change is published, and then the page is updated.</span></span>

<span data-ttu-id="e8112-111">[ページの承認フロー](https://support.office.com/article/page-approval-flow-a8b2e689-d4a1-4639-8028-333c0ece30d9)の動作と[ページの承認を構成する](https://support.office.com/article/configure-page-approval-14ce6976-a0a7-427b-b4ab-d28d344a5222)方法の詳細をお読みください。</span><span class="sxs-lookup"><span data-stu-id="e8112-111">Read more about how [page approval flows](https://support.office.com/article/page-approval-flow-a8b2e689-d4a1-4639-8028-333c0ece30d9) work and how to [configure page approvals](https://support.office.com/article/configure-page-approval-14ce6976-a0a7-427b-b4ab-d28d344a5222).</span></span>

## <a name="configure-page-approval"></a><span data-ttu-id="e8112-112">ページの承認を構成する</span><span class="sxs-lookup"><span data-stu-id="e8112-112">Configure page approval</span></span>

<span data-ttu-id="e8112-113">サイト所有者は、ページのライブラリの**フロー** メニューからページの承認フローを構成します。</span><span class="sxs-lookup"><span data-stu-id="e8112-113">Site owners configure page approval flows from the **Flow** menu of a page’s library.</span></span>

<span data-ttu-id="e8112-114">![ページの承認フローを作成する](media/sharepoint-page-approvals-1.png "ページの承認フローを作成する")</span><span class="sxs-lookup"><span data-stu-id="e8112-114">![Create page approval flow](media/sharepoint-page-approvals-1.png "Create page approval flow")</span></span>

## <a name="submitting-a-page-for-approval"></a><span data-ttu-id="e8112-115">承認のためのページの送信</span><span class="sxs-lookup"><span data-stu-id="e8112-115">Submitting a page for approval</span></span>

<span data-ttu-id="e8112-116">ページの承認が構成されたら、作成者は承認のためにそれらを送信します。</span><span class="sxs-lookup"><span data-stu-id="e8112-116">Once the page approval is configured, authors submit them for approval.</span></span> <span data-ttu-id="e8112-117">[公開] ボタンが [承認のために送信] ボタンに変わります。</span><span class="sxs-lookup"><span data-stu-id="e8112-117">The publish button is replaced by a submit for approval button.</span></span>

<span data-ttu-id="e8112-118">![承認のためのページの送信](media/sharepoint-page-approvals-2.png "承認のためのページの送信")</span><span class="sxs-lookup"><span data-stu-id="e8112-118">![Submit page for approval](media/sharepoint-page-approvals-2.png "Submit page for approval")</span></span>

<span data-ttu-id="e8112-119">ページは承認後に公開されます。</span><span class="sxs-lookup"><span data-stu-id="e8112-119">The page is published after it is approved.</span></span> <span data-ttu-id="e8112-120">却下された場合、ページはドラフト ステータスに戻ります。</span><span class="sxs-lookup"><span data-stu-id="e8112-120">The page goes back to draft status if it is rejected.</span></span>

## <a name="approving-a-page"></a><span data-ttu-id="e8112-121">ページの承認</span><span class="sxs-lookup"><span data-stu-id="e8112-121">Approving a page</span></span>

<span data-ttu-id="e8112-122">承認者は、ページの承認要求に関する電子メールを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="e8112-122">Approvers get an email regarding page approval requests.</span></span> <span data-ttu-id="e8112-123">電子メールでページを直接承認する (アクション可能なメッセージをサポートする電子メール クライアントの場合) か、電子メールからページを開いてレビューしてから SharePoint でページを承認することができます。</span><span class="sxs-lookup"><span data-stu-id="e8112-123">They can either approve the page directly in the email (in email clients that support actionable messages) or open the page from the email to review, and then approve the page in SharePoint.</span></span>

<span data-ttu-id="e8112-124">![ページの承認](media/sharepoint-page-approvals-3.png "ページの承認")</span><span class="sxs-lookup"><span data-stu-id="e8112-124">![Approve page](media/sharepoint-page-approvals-3.png "Approve page")</span></span>

<span data-ttu-id="e8112-125">承認フローが完了すると、変更はサイトのすべての閲覧者に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="e8112-125">The changes become visible to all readers of the site after the approval flow completes.</span></span>

## <a name="customizing-the-page-approval-flow"></a><span data-ttu-id="e8112-126">ページの承認フローのカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="e8112-126">Customizing the page approval flow</span></span>

<span data-ttu-id="e8112-127">ページの承認はバックグラウンドで Microsoft Flow を使用するので、サイト所有者はページの承認フローを利用してフロー内のカスタム ビジネス プロセス アイテムを変更および追加することができます。</span><span class="sxs-lookup"><span data-stu-id="e8112-127">Since page approvals use Microsoft Flow behind the scenes, the page approval flow is available to site owners to modify and add any custom business process items in the flow.</span></span> <span data-ttu-id="e8112-128">フローを作成した後、サイト所有者はページ ライブラリで**フロー** > **フローの表示**を選択してページの承認フローを検索できます。</span><span class="sxs-lookup"><span data-stu-id="e8112-128">After creating the flow, the site owner can select **Flows** > **See your flows** in the pages library to find the page approval flow.</span></span>

<span data-ttu-id="e8112-129">たとえば、既定の承認タイプは**だれでも承認できる**ように設定されています。</span><span class="sxs-lookup"><span data-stu-id="e8112-129">For example, the default approval type is set to **anyone can approve**.</span></span> <span data-ttu-id="e8112-130">サイト所有者はフローを変更し、必要に応じて承認タイプを**全員の承認が必要**なように変更できます。</span><span class="sxs-lookup"><span data-stu-id="e8112-130">Site owners can modify the flow and change the approval type to **everyone must approve** if that's the requirement.</span></span>

<span data-ttu-id="e8112-131">![承認タイプの変更](media/sharepoint-page-approvals-4.png "承認タイプの変更")</span><span class="sxs-lookup"><span data-stu-id="e8112-131">![Change approval type](media/sharepoint-page-approvals-4.png "Change approval type")</span></span>

## <a name="known-issues"></a><span data-ttu-id="e8112-132">既知の問題</span><span class="sxs-lookup"><span data-stu-id="e8112-132">Known issues</span></span>

- <span data-ttu-id="e8112-133">ページが別のユーザーによってチェックアウトされていて、ユーザー (この場合は作成者) が承認のためにページを送信した場合、そのページは通知せずに承認を続行します。</span><span class="sxs-lookup"><span data-stu-id="e8112-133">If the page is checked out by another user and you (the author in this case) submit the page for approval, the page will not notify and proceed with the approval.</span></span> <span data-ttu-id="e8112-134">フローが実行され、ページの公開中にエラーが発生したことを示す電子メールが作成者に送信されます。</span><span class="sxs-lookup"><span data-stu-id="e8112-134">The flow will run and send an email indicating to the author that an error occurred in publishing the page.</span></span> 
- <span data-ttu-id="e8112-135">サイト ページ ライブラリに対して有効になっているメジャー バージョンのみがある場合は、承認の送信結果として次のエラーが発生します: `Could not complete that action: The type of data at position 0 is different than the one expected.`</span><span class="sxs-lookup"><span data-stu-id="e8112-135">If you have only major versions enabled for the Site Pages library, submit for approval results in the following error: `Could not complete that action: The type of data at position 0 is different than the one expected.`</span></span>
- <span data-ttu-id="e8112-136">英国地域でのみ、2018 年 3 月より後に作成されたテナントでは、この機能がサポートされません。</span><span class="sxs-lookup"><span data-stu-id="e8112-136">In the UK region only, tenants created after March 2018 do not support this feature.</span></span> <span data-ttu-id="e8112-137">これは 9 月末までに解決する予定です。</span><span class="sxs-lookup"><span data-stu-id="e8112-137">We expect to have this resolved by the end of September.</span></span> <span data-ttu-id="e8112-138">詳しくは、[このスレッドをご覧ください](https://techcommunity.microsoft.com/t5/SharePoint/Announcing-SharePoint-page-approvals/m-p/225587/highlight/true#M20376)。</span><span class="sxs-lookup"><span data-stu-id="e8112-138">[See this thread](https://techcommunity.microsoft.com/t5/SharePoint/Announcing-SharePoint-page-approvals/m-p/225587/highlight/true#M20376) for more information.</span></span>
