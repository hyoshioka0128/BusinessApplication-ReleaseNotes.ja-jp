---
title: "失敗したフローに対する電子メールでの修復のヒント"
description: "フローが失敗した場合に、特定のエラーに関する具体的かつアクション可能なフィードバックを含むメールを受け取ります。 修復のヒントでは、フローが失敗した理由と解決方法が正確に示されます。 Flow ポータルで実行失敗をクリックして、修復のヒントを見ることもできます。"
author: sunayv
ms.reviewer: deonhe
ms.date: 01/17/2019
ms.assetid: 36726ff5-4a98-e811-a96c-000d3a137a43
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sunayv
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 1de869f4ccb74ccc9b9cd26817e3d5c30734c3c3
ms.openlocfilehash: 4aaad3a867d9a124f53e0110c930a074a580645e
ms.contentlocale: ja-jp
ms.lasthandoff: 01/25/2019

---
# <a name="repair-tips-in-email-for-failed-flows"></a><span data-ttu-id="bf797-105">失敗したフローに対する電子メールでの修復のヒント</span><span class="sxs-lookup"><span data-stu-id="bf797-105">Repair tips in email for failed flows</span></span>




<span data-ttu-id="bf797-106">作成したフローが失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="bf797-106">The flows that you build may fail sometimes.</span></span> <span data-ttu-id="bf797-107">そうなった場合は、修正方法を素早く知ることが重要です。</span><span class="sxs-lookup"><span data-stu-id="bf797-107">If they do, it is important that you know how to fix them quickly.</span></span> <span data-ttu-id="bf797-108">フローが失敗したときは、そのフローに関するメール通知が常に送信されています。</span><span class="sxs-lookup"><span data-stu-id="bf797-108">When you have flows that are failing, we have always sent you an email notification about those flows:</span></span>

<span data-ttu-id="bf797-109">![失敗に関するダイジェスト メール](media/repair-tips-0.png "失敗に関するダイジェスト メール")</span><span class="sxs-lookup"><span data-stu-id="bf797-109">![Failure digest email](media/repair-tips-0.png "Failure digest email")</span></span>

<span data-ttu-id="bf797-110">ただし、これらの通知には、フローを修復するためにできることについての具体的な推奨は含まれません。</span><span class="sxs-lookup"><span data-stu-id="bf797-110">However, these notifications do not contain specific recommendations on what you can do to repair your flows.</span></span> <span data-ttu-id="bf797-111">修復に役立つように、**修復のヒント**が導入されました。</span><span class="sxs-lookup"><span data-stu-id="bf797-111">To help, we are now introducing **Repair tips**.</span></span> <span data-ttu-id="bf797-112">修復のヒントでは、特定のエラーに関する具体的かつアクション可能なフィードバックを含むメールが送られます。</span><span class="sxs-lookup"><span data-stu-id="bf797-112">Repair tips send you emails with specific, actionable feedback about certain errors.</span></span> <span data-ttu-id="bf797-113">たとえば、よくあるエラーの 1 つは、Office 365 でユーザーのマネージャーを取得するフローを設定したのに、Azure AD でマネージャーが構成されていない場合です。</span><span class="sxs-lookup"><span data-stu-id="bf797-113">For example, one common error is setting up a flow that attempts to get a person’s manager in Office 365—but there is no manager configured in Azure AD.</span></span> <span data-ttu-id="bf797-114">これまでは `404 – Not Found` とだけ表示されており、ほとんどの人にはその意味がわかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="bf797-114">Previously, you would just see a `404 – Not Found` error, and most people don’t know what that means.</span></span> <span data-ttu-id="bf797-115">現在では、次のようなメールが届きます。</span><span class="sxs-lookup"><span data-stu-id="bf797-115">Now, you get an email like this:</span></span>


<span data-ttu-id="bf797-116">![修復のヒントのメール](media/repair-tips-1.png "修復のヒントのメール")</span><span class="sxs-lookup"><span data-stu-id="bf797-116">![Repair tips email](media/repair-tips-1.png "Repair tips email")</span></span>


<span data-ttu-id="bf797-117">このメールには、**起こったこと** (マネージャが構成されていなかった) と、**修正方法**</span><span class="sxs-lookup"><span data-stu-id="bf797-117">This email contains sections for **What happened** (no manager was configured), and, **How do I fix it?**</span></span> <span data-ttu-id="bf797-118">(Azure AD でマネージャーを設定する) に関するセクションが含まれます。</span><span class="sxs-lookup"><span data-stu-id="bf797-118">(set up a manager in Azure AD).</span></span> <span data-ttu-id="bf797-119">また、多要素認証 (MFA) による接続エラーに関する修復のヒントも提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf797-119">We also provide repair tips for connection failures due to multi-factor authentication (MFA).</span></span>

<span data-ttu-id="bf797-120">特定のフローに対する修復のヒントを受け取りたくない場合は、[フローのプロパティ] ページの**詳細...**</span><span class="sxs-lookup"><span data-stu-id="bf797-120">If you do not want to receive repair tips for a given flow, you can disable them from the **More…**</span></span> <span data-ttu-id="bf797-121">メニューで無効にできます。</span><span class="sxs-lookup"><span data-stu-id="bf797-121">menu on the Flow properties page.</span></span> <span data-ttu-id="bf797-122">新しいメニュー項目**修復のヒント**が表示されるので、それを選択してオフにできます。</span><span class="sxs-lookup"><span data-stu-id="bf797-122">You’ll see a new menu item for **Repair tips** that you can select to turn them off:</span></span>

<span data-ttu-id="bf797-123">![[修復のヒント] メニュー項目](media/repair-tips-3.png "[修復のヒント] メニュー項目")</span><span class="sxs-lookup"><span data-stu-id="bf797-123">![Repair tips menu item](media/repair-tips-3.png "Repair tips menu item")</span></span>

<span data-ttu-id="bf797-124">最後に、メールを受け取りたくない場合でも、修復のヒントが提供されているエラーがあるフロー実行を開くと常に、修復のヒントが表示されます。</span><span class="sxs-lookup"><span data-stu-id="bf797-124">Finally, even if you don’t want to receive emails, you will now see repair tips whenever you open a flow run that has a failure with a repair tip available.</span></span> <span data-ttu-id="bf797-125">実行の**詳細**ウィンドウで、**エラーの詳細**セクションと**修正方法**セクションを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="bf797-125">You can see the **Error details** and **How do I fix it?** sections in the run’s **Details** pane:</span></span>


<span data-ttu-id="bf797-126">![[修復のヒント] メニュー項目](media/repair-tips-2.png "[修復のヒント] メニュー項目")</span><span class="sxs-lookup"><span data-stu-id="bf797-126">![Repair tips menu item](media/repair-tips-2.png "Repair tips menu item")</span></span>

