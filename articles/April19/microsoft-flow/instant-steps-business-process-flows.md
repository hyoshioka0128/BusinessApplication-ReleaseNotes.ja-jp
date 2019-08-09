---
title: ビジネス プロセス フローのインスタント フロー ステップ
description: このプレビューでは、ユーザーはインスタント フローを実行して、反復的なタスクの自動化、ドキュメントの生成、承認の追跡などをビジネス プロセス フローのステップからオンデマンドで実行できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: beaaf2bd-1597-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 44f12f6f984855582d252a70896b5011a1992e22
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757226"
---
# <a name="instant-flows-in-business-process-flows-public-preview"></a><span data-ttu-id="a25de-103">ビジネス プロセス フロー内のインスタント フロー (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="a25de-103">Instant flows in business process flows (Public Preview)</span></span>

<span data-ttu-id="a25de-104">ビジネス プロセス フローでは、ステージとステップの形式で作業を行う手順がガイドされます。</span><span class="sxs-lookup"><span data-stu-id="a25de-104">Business process flows provide a guided way to get work done in the form of stages and steps.</span></span> <span data-ttu-id="a25de-105">ステージはプロセス内での位置を示すのに対し、ステップは目的の結果に至るアクション項目です。</span><span class="sxs-lookup"><span data-stu-id="a25de-105">Stages tell you where you are in the process, while steps are action items that lead to a desired outcome.</span></span> <span data-ttu-id="a25de-106">以前は、ステップは Common Data Service での情報の入力やアクションの実行にのみ使用できました。</span><span class="sxs-lookup"><span data-stu-id="a25de-106">Previously, steps could only be used to enter information or run actions in Common Data Service.</span></span>

<span data-ttu-id="a25de-107">このプレビューでは、**インスタント フロー**を実行して、反復的なタスクの自動化、ドキュメントの生成、承認の追跡などをビジネス プロセスのステージ内から実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a25de-107">With this preview, you can now run an **instant flow** to automate repetitive tasks, generate documents, track approvals, and more, from inside a stage in the business process.</span></span>

![ランタイム](media/flow-step-in-a-business-process-2.jpg)

## <a name="add-an-instant-flow-as-a-step-in-a-business-process"></a><span data-ttu-id="a25de-109">インスタント フローをビジネス プロセスのステップとして追加する</span><span class="sxs-lookup"><span data-stu-id="a25de-109">Add an instant flow as a step in a business process</span></span>

<span data-ttu-id="a25de-110">たとえば、プリンターを企業に販売していて、商談の成立を支援するためにリードから営業案件への営業プロセスを使用するとします。</span><span class="sxs-lookup"><span data-stu-id="a25de-110">Let’s say that you sell printers to enterprises, and to help close deals, you use the Lead to Opportunity Sales Process:</span></span>

![デザイナー](media/lead-to-opportunity-sales-process-1.jpg)

<span data-ttu-id="a25de-112">このプロセスの一環として、ビジネス プロセス フローの**提案**ステージで販売チームがまとめた提案を顧客と共有する前に、チーム リーダーがそれをレビューし、承認するようにします。</span><span class="sxs-lookup"><span data-stu-id="a25de-112">As part of this process, you’d like to have the team lead review and approve proposals put together by the sales team in the **Propose** stage of the business process flow before sharing it with the customer.</span></span>

<span data-ttu-id="a25de-113">これを行うには、以下の手順に従います。</span><span class="sxs-lookup"><span data-stu-id="a25de-113">Follow these steps do this:</span></span>

1.  <span data-ttu-id="a25de-114">チームから提案のレビューと承認を要求するソリューション対応のインスタント フローを構築します。</span><span class="sxs-lookup"><span data-stu-id="a25de-114">Build a solution-aware instant flow that requests review and approval of the proposal from the team.</span></span>
2.  <span data-ttu-id="a25de-115">このフローをリードから営業案件への営業プロセスのステップとして追加します。</span><span class="sxs-lookup"><span data-stu-id="a25de-115">Add this flow as a step in the Lead to Opportunity Sales Process.</span></span>

## <a name="build-the-instant-flow"></a><span data-ttu-id="a25de-116">インスタント フローを構築する</span><span class="sxs-lookup"><span data-stu-id="a25de-116">Build the instant flow</span></span>

<span data-ttu-id="a25de-117">ビジネス プロセスのステップとして追加できるのは、[ソリューション対応のフロー](https://docs.microsoft.com/flow/overview-solution-flows)だけです。</span><span class="sxs-lookup"><span data-stu-id="a25de-117">Only [solution-aware flows](https://docs.microsoft.com/flow/overview-solution-flows) can be added as a step in a business process.</span></span> <span data-ttu-id="a25de-118">例では、**既定のソリューション**にインスタント フローを作成します。</span><span class="sxs-lookup"><span data-stu-id="a25de-118">In the example, create an instant flow in the **Default Solution**.</span></span> <span data-ttu-id="a25de-119">これを行うには、ナビゲーション メニューの**ソリューション**を選択し、ソリューションの一覧で**既定のソリューション**を選択して開き、**+ 新規**メニューからこのソリューション内にフローを作成します。</span><span class="sxs-lookup"><span data-stu-id="a25de-119">To do this, select **Solutions** in the navigation menu, select **Default Solution** in the list of solutions to open it, and then create a flow in this solution from the **+ New** menu.</span></span>

![ソリューション フロー](media/creating-a-solution-aware-flow.jpg)

<span data-ttu-id="a25de-121">このバージョンのプレビューでは、最初に Common Data Service コネクタから**レコードが選択されたとき**トリガーを追加します。</span><span class="sxs-lookup"><span data-stu-id="a25de-121">In this version of the preview, begin by adding the **When a record is selected** trigger from the Common Data Service connector.</span></span> <span data-ttu-id="a25de-122">**環境**フィールドを**既定**に設定し、**エンティティ名**を**リードから営業案件への営業プロセス**に設定します。</span><span class="sxs-lookup"><span data-stu-id="a25de-122">Set the **Environment** field to **Default** and set **Entity Name** to **Lead to Opportunity Sales Process**.</span></span> <span data-ttu-id="a25de-123">最後に、テキスト入力フィールドを追加して、提案へのリンクをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="a25de-123">Finally, add a text input field to capture a link to the proposal:</span></span>

![トリガー](media/when-a-record-is-selected-trigger.jpg)

<span data-ttu-id="a25de-125">次に、ビジネス プロセス フロー インスタンスから情報を取得して、レビューのコンテキストを提供できます。</span><span class="sxs-lookup"><span data-stu-id="a25de-125">Next, we can get information from the business process flow instance to help provide context for the review.</span></span> <span data-ttu-id="a25de-126">このバージョンのプレビューでは、**JSON の解析**アクションを追加することでこれを行います。</span><span class="sxs-lookup"><span data-stu-id="a25de-126">In this version of the preview, we do this by adding the **Parse JSON** action.</span></span> <span data-ttu-id="a25de-127">トリガーの動的な値の一覧から選択することで**コンテンツ** フィールドを**エンティティ**に設定し、次の内容を**スキーマ** フィールドに貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="a25de-127">Set the **Content** field to **entity** by selecting it from the list of dynamic values of the trigger and then paste the following content into the **Schema** field:</span></span>

```json
{
  "type": "object",
    "properties": {
        "entity": {
            "type": "object",
            "properties": {
                "FlowsWorkflowLogId": {
                    "type": "string"
                },
                "BPFInstanceId": {
                    "type": "string"
                },
                "BPFInstanceEntityName": {
                    "type": "string"
                },
                "BPFDefinitionId": {
                    "type": "string"
                },
                "BPFDefinitionEntityName": {
                    "type": "string"
                },
                "StepId": {
                    "type": "string"
                },
                "BPFDefinitionName": {
                    "type": "string"
                },
                "BPFInstanceName": {
                    "type": "string"
                },
                "BPFFlowStageLocalizedName": {
                    "type": "string"
                },
                "BPFFlowStageEntityName": {
                    "type": "string"
                },
                "BPFFlowStageEntityCollectionName": {
                    "type": "string"
                },
                "BPFFlowStageEntityRecordId": {
                    "type": "string"
                },
                "BPFActiveStageId": {
                    "type": "string"
                },
                "BPFActiveStageEntityName": {
                    "type": "string"
                },
                "BPFActiveStageLocalizedName": {
                    "type": "string"
                }
            }
        }
    }
}
```

![エンティティを使用する](media/parse-json-to-get-bpf-details.jpg)

<span data-ttu-id="a25de-129">ビジネス プロセスの提案ステージは営業案件エンティティで定義されているため、関連する営業案件レコードから情報を取得して、承認要求に追加のコンテキストを提供しましょう。</span><span class="sxs-lookup"><span data-stu-id="a25de-129">Since the Propose stage of our business process is defined on the Opportunity entity, let’s get information from the related Opportunity record to provide additional context in the approval requests.</span></span> <span data-ttu-id="a25de-130">これを行うには、Common Data Service コネクタの**レコードの取得**アクションを追加します。</span><span class="sxs-lookup"><span data-stu-id="a25de-130">To do this, add the **Get record** action of the Common Data Service connector.</span></span> <span data-ttu-id="a25de-131">**環境**を **(現在)** に、**エンティティ名**を**営業案件**に、**品目の識別子**を動的な値の一覧から選択した **BPFFlowStageEntityRecordID** に設定します。</span><span class="sxs-lookup"><span data-stu-id="a25de-131">Set the **Environment** to **(Current)**, the **Entity Name** to **Opportunities**, and the **Item Identifier** to **BPFFlowStageEntityRecordID**, picked from the list of dynamic values:</span></span>

![JSON の使用](media/get-opportunity-information-related-to-the-bpf.jpg)

<span data-ttu-id="a25de-133">データが得られたので、**承認の開始と待機 (V2)** アクション追加して承認プロセスを定義しましょう。</span><span class="sxs-lookup"><span data-stu-id="a25de-133">Now that we have the data, lets define the approval process by adding the **Start and wait for an approval (V2)** action.</span></span> <span data-ttu-id="a25de-134">動的コンテンツ ピッカーを使用して、**レコードの取得**アクションからフィールドを追加して、営業案件に関する関連情報を追加します。</span><span class="sxs-lookup"><span data-stu-id="a25de-134">Use the dynamic content picker to add fields from the **Get record** action to add the relevant information about the Opportunity.</span></span> <span data-ttu-id="a25de-135">ビジネス プロセスが属するアクティブなステージのコンテキストをさらに提供するには、動的な値の一覧から **BPFActiveStageLocalizedName** フィールドを選択します。</span><span class="sxs-lookup"><span data-stu-id="a25de-135">To provide further context of the active stage that the business process is in, select the **BPFActiveStageLocalizedName** field from the list of dynamic values.</span></span>

![ローカライズされた情報](media/send-an-approval-containing-bpf-and-opportunity-information.jpg)

<span data-ttu-id="a25de-137">次に、承認の結果に基づいて要求者にメールを送信しましょう。</span><span class="sxs-lookup"><span data-stu-id="a25de-137">Next, let’s send an email to the requestor based on the outcome of the approval.</span></span> <span data-ttu-id="a25de-138">これを行うには、承認の**結果**フィールドに基づいて条件を追加し (動的な値の一覧から選択)、**電子メールの送信**アクションを**はいの場合**と**いいえの場合**の両方のパスに追加します。</span><span class="sxs-lookup"><span data-stu-id="a25de-138">To do this, add a condition based on the **Outcome** field of the approval (picked from the list of dynamic values) and add a **Send an email** action to both the **If yes** and **If no** paths.</span></span>

![分岐](media/branch-on-approval-outcome.jpg)

<span data-ttu-id="a25de-140">最後に、フローを保存してオンにします。</span><span class="sxs-lookup"><span data-stu-id="a25de-140">Finally, save the flow and turn it on.</span></span> <span data-ttu-id="a25de-141">まとめると、ビジネス プロセスおよび関連する営業案件レコードからの情報を使用して承認を要求し、その結果に基づいて動作するフローは以下のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a25de-141">Altogether, our flow that requests an approval with information from the business process and the related opportunity record, and acts based on the outcome is below:</span></span>

![概要](media/entire-flow.jpg)

## <a name="add-an-instant-flow-as-a-step-in-a-business-process"></a><span data-ttu-id="a25de-143">インスタント フローをビジネス プロセスのステップとして追加する</span><span class="sxs-lookup"><span data-stu-id="a25de-143">Add an instant flow as a step in a business process</span></span>

<span data-ttu-id="a25de-144">まず、BPF デザイナーでリードから営業案件への営業プロセスを開きます。</span><span class="sxs-lookup"><span data-stu-id="a25de-144">We begin by opening the Lead to Opportunity Sales Process in the BPF designer.</span></span> <span data-ttu-id="a25de-145">BPF の提案ステージのステップとしてフローを追加するには、単純に**フロー ステップ (プレビュー)** コンポーネントを提案ステージにドラッグ アンド ドロップします。</span><span class="sxs-lookup"><span data-stu-id="a25de-145">To add a flow as a step in the Propose stage of our BPF, simply drag and drop the **Flow Step (preview)** component onto the Propose stage:</span></span>

![ステップをドラッグする](media/add-a-flow-step-to-a-bpf.jpg)

<span data-ttu-id="a25de-147">次に、**フローの選択**フィールドの検索アイコンを選択して、BPF に追加できるすべてのフローを一覧表示し、一覧から 1 つを選択します。</span><span class="sxs-lookup"><span data-stu-id="a25de-147">Next, select the search icon in the **Select a Flow** field to list all flows that can be added to a BPF, and select one from the list.</span></span> <span data-ttu-id="a25de-148">変更を保存するには、プロパティ ウィンドウの下部にある**適用**ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="a25de-148">To save your changes, select the **Apply** button at the bottom of the properties pane:</span></span>

![ピック](media/pick-a-flow-to-run-from-the-flow-step.jpg)

<span data-ttu-id="a25de-150">最後に、**更新**ボタンを選択して、このビジネス プロセス フローとその新しいフロー ステップをユーザーが使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="a25de-150">Finally, select the **Update** button to make this business process flow with its new flow step available to users.</span></span>

<span data-ttu-id="a25de-151">これで完了です。</span><span class="sxs-lookup"><span data-stu-id="a25de-151">And we’re done!</span></span> <span data-ttu-id="a25de-152">**フローの実行**ボタンを選択して、リードから営業案件への営業プロセスの**提案**ステージからフローを実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a25de-152">You can now run your flow from the **Propose** stage of the Lead to Opportunity Sales Process by selecting the **Run Flow** button:</span></span>

![最終](media/flow-step-in-a-business-process-2.jpg)
