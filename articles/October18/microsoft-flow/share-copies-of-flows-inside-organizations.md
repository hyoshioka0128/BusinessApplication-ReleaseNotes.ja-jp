---
title: 組織内でフローのコピーを共有
description: フローのコピーを共有することによってフロー テンプレートを配布します。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/20/2019
ms.assetid: 584a5018-e70e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ec6b4f69019c4a5b8e882da60c4d06dc83f61527
ms.sourcegitcommit: 1de869f4ccb74ccc9b9cd26817e3d5c30734c3c3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2019
ms.locfileid: "288639"
---
# <a name="share-copies-of-flows-inside-organizations-public-preview"></a><span data-ttu-id="c4f23-103">組織内でフローのコピーを共有 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="c4f23-103">Share copies of flows inside organizations (Public Preview)</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="c4f23-104">自分のフローのコピーを組織内の他のユーザーが作成できるようにする場合は、新しい**コピーの送信**機能を使用できます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-104">If you have a flow that you want other people in your organization to create copies of, there is a new **Send a copy** feature available.</span></span> <span data-ttu-id="c4f23-105">フローのコピーを送信するには、まず、そのフローに個人情報が含まれていないことを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-105">To send a copy of the flow, you must first ensure that it does not contain any personal information.</span></span> <span data-ttu-id="c4f23-106">たとえば、自分の電子メール アドレス宛てに何かを送信するフローは、他のユーザーにコピーとして送信するのに適していない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-106">For example, a flow that sends something to your email address would likely not be appropriate to send as a copy to others.</span></span>

<span data-ttu-id="c4f23-107">フローのコピーを送信すると、受信者が元のフローのコピーを自分で作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-107">Sending a copy of a flow means that recipients will be able to create their own copies of the original flow.</span></span> <span data-ttu-id="c4f23-108">これらのコピーは受信者のつながりを使用し、受信者がフロー作成後に変更を加えることを希望する場合は、受信者によって所有されることになります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-108">These copies will use the recipient's connections and be owned by the recipient if they want to make changes after creating the flow.</span></span>

<span data-ttu-id="c4f23-109">フローのコピーを送信するための主なエントリ ポイントは 2 つあります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-109">There are two main entry points for sending a copy of your flow.</span></span> <span data-ttu-id="c4f23-110">1 つ目は、フローの一覧からです。</span><span class="sxs-lookup"><span data-stu-id="c4f23-110">First, from the flows list:</span></span>

<span data-ttu-id="c4f23-111">![フローの一覧での "コピーの送信" オプション](media/send_a_copy_from_flow_list.png "フローの一覧での "コピーの送信" オプション")</span><span class="sxs-lookup"><span data-stu-id="c4f23-111">!["Send a copy" option in flow list](media/send_a_copy_from_flow_list.png ""Send a copy" option in flow list")</span></span>

<span data-ttu-id="c4f23-112">2 つ目は、フローのプロパティ ページからです。</span><span class="sxs-lookup"><span data-stu-id="c4f23-112">Second, from the flow properties page:</span></span>

<span data-ttu-id="c4f23-113">![フローのプロパティ ページからの "コピーの送信" オプション](media/send_a_copy_from_flow_properties.png "フローのプロパティ ページからの "コピーの送信" オプション")</span><span class="sxs-lookup"><span data-stu-id="c4f23-113">!["Send a copy" option from flow properties page](media/send_a_copy_from_flow_properties.png ""Send a copy" option from flow properties page")</span></span>

<span data-ttu-id="c4f23-114">フローをコピーとして送信する前に、最後にフローを更新してから少なくとも 1 回はフローを正常に実行している必要があります。</span><span class="sxs-lookup"><span data-stu-id="c4f23-114">Before sending your flow as a copy you must have at least one successful run since the last time you updated the flow.</span></span> <span data-ttu-id="c4f23-115">これは、フローが送信先のあらゆるユーザーに対して機能することを確認するために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-115">This helps to ensure that the flow will work for anyone you send it to.</span></span> <span data-ttu-id="c4f23-116">また、フローをコピーとして共有した後はコピーを取り消すことができないため、送信する前にフローから個人情報を削除することが重要です。</span><span class="sxs-lookup"><span data-stu-id="c4f23-116">Also, it is important that you remove any personal information from the flow before sending it out, especially because after you share the flow as a copy, the copy cannot be retracted.</span></span>

<span data-ttu-id="c4f23-117">だれかがフローのコピーを使用するとき、コピー作成時にその構成を調整する方法はありません。コピーはそのまま作成されますが、その人物のつながりが使用されます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-117">When someone uses a copy of a flow, there is no way for them to adjust its configuration when creating it—the copy will be created as-is, but with that person's connections.</span></span> <span data-ttu-id="c4f23-118">そのため、受信者のつながりに基づいてすべてのデータを動的に取得するようにフローを設計することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="c4f23-118">Thus, we recommend designing your flow to retrieve all data dynamically based on the recipient's connections.</span></span> <span data-ttu-id="c4f23-119">たとえば、自分や受信者の電子メール アドレスをフローにハード コーディングするのではなく、**[自分のプロファイルを取得](https://docs.microsoft.com/connectors/office365users/#get-my-profile--v2-)** のようなアクションを使用できます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-119">For example, you can use actions such **[Get my profile](https://docs.microsoft.com/connectors/office365users/#get-my-profile--v2-)** rather than hard-coding your or the recipient's email address into the flow.</span></span>

<span data-ttu-id="c4f23-120">**コピーの送信**を選択すると、受信者だけでなくテンプレートのタイトルと説明をカスタマイズするように求められます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-120">When you select **Send a copy**, you are prompted to customize the title and description of the template as well as the recipients.</span></span> <span data-ttu-id="c4f23-121">組織内のユーザーとセキュリティ グループの任意の組み合わせを受信者にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-121">These recipients can be any combination of users and security groups within your organization.</span></span> <span data-ttu-id="c4f23-122">フロー送信先のユーザーだけが、フローにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-122">Only the people you send the flow to will have access to it.</span></span>

<span data-ttu-id="c4f23-123">!["コピーの送信" パネルの入力](media/send_a_copy_panel.png ""コピーの送信" パネルの入力")</span><span class="sxs-lookup"><span data-stu-id="c4f23-123">!["Send a copy" panel input](media/send_a_copy_panel.png ""Send a copy" panel input")</span></span>

<span data-ttu-id="c4f23-124">受信者は、送信されたフローの自分用のコピーを作成するように促す電子メールを受信します。</span><span class="sxs-lookup"><span data-stu-id="c4f23-124">The recipients receive an email prompting them to create their own copy of the flow you just sent.</span></span>

<span data-ttu-id="c4f23-125">!["コピーの送信" で受信された電子メール](media/send_a_copy_email.png ""コピーの送信" で受信された電子メール")</span><span class="sxs-lookup"><span data-stu-id="c4f23-125">!["Send a copy" received email](media/send_a_copy_email.png ""Send a copy" received email")</span></span>

<span data-ttu-id="c4f23-126">さらに、自分と共有されたテンプレートを**共有アイテム** タブで確認できます。</span><span class="sxs-lookup"><span data-stu-id="c4f23-126">Additionally, you can view any templates shared with you from the **Shared with me** tab.</span></span>

<span data-ttu-id="c4f23-127">!["共有アイテム" テンプレート ギャラリー](media/send_a_copy_shared_with_me.png ""共有アイテム" テンプレート ギャラリー")</span><span class="sxs-lookup"><span data-stu-id="c4f23-127">![The "Shared with me" template gallery](media/send_a_copy_shared_with_me.png ""Shared with me" template gallery")</span></span>
