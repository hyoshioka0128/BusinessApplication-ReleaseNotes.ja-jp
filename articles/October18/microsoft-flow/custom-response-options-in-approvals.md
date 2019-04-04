---
title: 承認のカスタム応答オプションの使用
description: 開発者は、必要などのようなオプションをいくつでも含む承認フローを構築することができます。
author: KaranSr
ms.reviewer: deonhe
ms.date: 03/15/2019
ms.assetid: e37358cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: karansr
audience: Power user
ms.openlocfilehash: 724cb6084bc713e1398d0001eb04c9812c717225
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880545"
---
# <a name="custom-response-options-in-approvals"></a><span data-ttu-id="e37a2-103">承認のカスタム応答オプション</span><span class="sxs-lookup"><span data-stu-id="e37a2-103">Custom response options in Approvals</span></span>

<span data-ttu-id="e37a2-104">組織のニーズに合わせて特別に調整した応答を使用する承認フローを作成するには、カスタム応答オプションを使用します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-104">Use custom response options to create approval flows with responses that you tailor specifically for your organization's needs.</span></span> <span data-ttu-id="e37a2-105">たとえば、カスタム応答を使用して、コンテンツのレビューなどで*承認*、*編集して承認*、*却下*のような詳細なフィードバックを提供できます。</span><span class="sxs-lookup"><span data-stu-id="e37a2-105">For example, you can use custom responses to provide granular feedback like *approve*, *approve with edits*, or *reject* for content reviews, and more.</span></span>

## <a name="create-an-approval-with-custom-responses"></a><span data-ttu-id="e37a2-106">カスタム応答を使用する承認を作成する</span><span class="sxs-lookup"><span data-stu-id="e37a2-106">Create an approval with custom responses</span></span>

<span data-ttu-id="e37a2-107">だれかが SharePoint に提案をアップロードするたびに承認依頼を送信し、承認者が*承認*、*編集して承認*、*却下*の 3 つのオプションのいずれかを使用して応答できるようにするとします。</span><span class="sxs-lookup"><span data-stu-id="e37a2-107">Let’s say we want to send an approval request each time someone uploads a proposal to SharePoint and then allow the approver to respond with one of three options: *Accept*, *Accept with edits*, or *Reject*.</span></span>

<span data-ttu-id="e37a2-108">開始するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-108">Follow these steps to get started:</span></span>

1. <span data-ttu-id="e37a2-109">承認を開始するアクションを追加します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-109">Add an action that starts an approval.</span></span>

     <span data-ttu-id="e37a2-110">![承認アクションの一覧](media/custom-response-options-in-approvals/customresponseoptions-1.png "承認アクションの一覧")</span><span class="sxs-lookup"><span data-stu-id="e37a2-110">![List of approvals actions](media/custom-response-options-in-approvals/customresponseoptions-1.png "List of approvals actions")</span></span>

1. <span data-ttu-id="e37a2-111">**承認タイプ**の一覧で、2 つのタイプのいずれかを選択します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-111">Select one of the two types from the **Approval type** list.</span></span>

     <span data-ttu-id="e37a2-112">![承認タイプ](media/custom-response-options-in-approvals/customresponseoptions-2.png "承認タイプ")</span><span class="sxs-lookup"><span data-stu-id="e37a2-112">![Approval types](media/custom-response-options-in-approvals/customresponseoptions-2.png "Approval types")</span></span>

1. <span data-ttu-id="e37a2-113">**応答オプション項目**フィールドにカスタム応答を入力します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-113">Enter your custom responses into the **Response Options Item** fields.</span></span>

    > [!TIP]
    > <span data-ttu-id="e37a2-114">さらにカスタム応答を追加する場合は、**新しい項目の追加**を選択します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-114">Select **Add new item** to add more custom responses.</span></span>

     <span data-ttu-id="e37a2-115">![応答オプション](media/custom-response-options-in-approvals/customresponseoptions-3.png "応答オプション")</span><span class="sxs-lookup"><span data-stu-id="e37a2-115">![Response options](media/custom-response-options-in-approvals/customresponseoptions-3.png "Response options")</span></span>

## <a name="use-approval-responses"></a><span data-ttu-id="e37a2-116">承認応答を使用する</span><span class="sxs-lookup"><span data-stu-id="e37a2-116">Use approval responses</span></span>

<span data-ttu-id="e37a2-117">承認者が依頼に対して意思決定を行った後に、異なる処理が必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="e37a2-117">After an approver provides a decision on a request, you might want to do different things.</span></span> <span data-ttu-id="e37a2-118">たとえば、依頼への応答が**承認**または**却下**の場合には提案を SharePoint の承認済み提案または却下済み提案のフォルダーに移動し、</span><span class="sxs-lookup"><span data-stu-id="e37a2-118">For instance, if the response to the request is **Accept** or **Reject**, move the proposal to a SharePoint folder for accepted or rejected proposals.</span></span> <span data-ttu-id="e37a2-119">応答が**編集して承認**の場合には作成者に電子メールを送信して提案の変更を依頼するとします。</span><span class="sxs-lookup"><span data-stu-id="e37a2-119">However, if the response is **Accept with edits**, send an email to the author to request changes to the proposal.</span></span>

<span data-ttu-id="e37a2-120">これを行うには、フローに条件または切り替えアクションを追加した後で、動的コンテンツピッカーから承認依頼の**結果**フィールドを選択します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-120">To do this, add a Condition or a Switch action to your flow, and then select the **Outcome** field of the approval request from the dynamic content picker.</span></span> <span data-ttu-id="e37a2-121">値が**承認**、**編集して承認**、**却下**のどれであるかを必ず確認してください。</span><span class="sxs-lookup"><span data-stu-id="e37a2-121">Be sure to confirm whether the value is **Accept**, **Accept with edits** or **Reject**.</span></span>

<span data-ttu-id="e37a2-122">![結果に基づく切り替え](media/custom-response-options-in-approvals/customresponseoptions-5.png "結果に基づく切り替え")</span><span class="sxs-lookup"><span data-stu-id="e37a2-122">![Switch based on outcome](media/custom-response-options-in-approvals/customresponseoptions-5.png "Switch based on outcome")</span></span>

## <a name="respond-to-approval-requests-with-a-custom-response"></a><span data-ttu-id="e37a2-123">カスタム応答を使用して承認依頼に応答する</span><span class="sxs-lookup"><span data-stu-id="e37a2-123">Respond to approval requests with a custom response</span></span>

<span data-ttu-id="e37a2-124">Microsoft Flow の承認センターに移動するか、アクション可能な電子メールにアクセスして、応答を選択します。</span><span class="sxs-lookup"><span data-stu-id="e37a2-124">Go to the Approvals Center in Microsoft Flow, or to the actionable email, and then select your response.</span></span>

   <span data-ttu-id="e37a2-125">![依頼への応答](media/custom-response-options-in-approvals/customresponseoptions-5-2.png "依頼への応答")</span><span class="sxs-lookup"><span data-stu-id="e37a2-125">![Respond to requests](media/custom-response-options-in-approvals/customresponseoptions-5-2.png "Respond to requests")</span></span>

