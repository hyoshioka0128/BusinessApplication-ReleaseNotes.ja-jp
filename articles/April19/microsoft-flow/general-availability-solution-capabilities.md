---
title: Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上
description: ソリューション機能の一般提供
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/09/2019
ms.assetid: ab87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: f3951a1a19e3639e997c825617a13991ab6b5658
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621745"
---
# <a name="improved-application-lifecycle-management-for-flows-using-common-data-service"></a><span data-ttu-id="b89b1-103">Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上</span><span class="sxs-lookup"><span data-stu-id="b89b1-103">Improved application lifecycle management for flows using Common Data Service</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="b89b1-104">11 月に、マイクロソフトは Common Data Service ソリューションでの自動化およびスケジュールされたインスタント フローのサポートを[リリース](https://flow.microsoft.com/blog/solutions-in-microsoft-flow/)しました。</span><span class="sxs-lookup"><span data-stu-id="b89b1-104">In November, we [released](https://flow.microsoft.com/blog/solutions-in-microsoft-flow/) support for automated, scheduled, and instant flows in Common Data Service solutions.</span></span> <span data-ttu-id="b89b1-105">**ソリューション**により、フローや Common Data Service エンティティなどのコンポーネントのグループを作成、パッケージ化、メンテナンスできます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-105">**Solutions** allow you to author, package, and maintain groups of components, such as flows and Common Data Service entities.</span></span> <span data-ttu-id="b89b1-106">ソリューションを配布することで、自分または他のユーザーが、環境全体でソリューションによって定義されているビジネス機能のインストールやアンインストールをできるようになります。</span><span class="sxs-lookup"><span data-stu-id="b89b1-106">You can distribute solutions allowing you or others to install and uninstall the business functionality defined by the solution across environments.</span></span>

<span data-ttu-id="b89b1-107">ソリューションの機能を向上させるために、現在新しい機能をリリースしています。</span><span class="sxs-lookup"><span data-stu-id="b89b1-107">We are now releasing new functionality to improve the way that solutions work.</span></span> <span data-ttu-id="b89b1-108">具体的には、Common Data Service を使用する特定のフローを、新しい環境へのソリューションのインポート時に自動的にアクティブ化できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b89b1-108">In particular, certain flows using Common Data Service can now be automatically activated on solution import to a new environment.</span></span>

<span data-ttu-id="b89b1-109">自動的にオンにすることができるフローを構築するには、最初に左のナビゲーションで **ソリューション** に移動し、ソリューションを選択してからフローを追加することで、フローを構築する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b89b1-109">To build flows that can automatically be turned on, the flow must be built by first going to **Solutions** in the left navigation, choosing a solution, and then adding the flow.</span></span> <span data-ttu-id="b89b1-110">フローを構築する際には、新しい **Common Data Service (現在の環境)** コネクタを使用します。</span><span class="sxs-lookup"><span data-stu-id="b89b1-110">When you build the flow, use the new **Common Data Service (Current Environment)** connector:</span></span>

![コネクタの検索](media/cds-native-1.png)

<span data-ttu-id="b89b1-112">このコネクタは、フローが展開されている環境を常に使用し、フローの所有者のユーザー コンテキストを自動的に取得できるという点で特殊です。</span><span class="sxs-lookup"><span data-stu-id="b89b1-112">This connector is special in that it will always use the environment that the flow is deployed in, and can automatically pick up the user context of the owner of the flow.</span></span> <span data-ttu-id="b89b1-113">つまり、接続先の環境を選択する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-113">This means you don’t have to select which environment to connect to:</span></span>

![完全トリガー](media/cds-native-2.png)

<span data-ttu-id="b89b1-115">この例では、取引先企業の親会社が変更されたときにすべての関連取引先企業に自動的にメモを追加するフローを作成できます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-115">In this example, we can create a flow that will automatically add a Note to all related accounts when a parent account is changed:</span></span>

![完全フロー](media/cds-native-3.png)

<span data-ttu-id="b89b1-117">フローを保存したら、それを管理ソリューションまたは非管理ソリューションとしてエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-117">Once you save the flow, you can export it as either a managed or unmanaged solution.</span></span> <span data-ttu-id="b89b1-118">フローによって完全にサポートされるようになった管理ソリューションは、フローを運用環境に移行する際に役立ちます。これらのソリューションの種類の違いについては、[こちらで詳細を読む](https://docs.microsoft.com/dynamics365/customer-engagement/developer/introduction-solutions#unmanaged-and-managed-solutions)ことができます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-118">Managed solutions, which are now fully supported by flow, are useful when you want to move a flow to a production environment – you can [read more here](https://docs.microsoft.com/dynamics365/customer-engagement/developer/introduction-solutions#unmanaged-and-managed-solutions) about the difference between these solution types.</span></span>

![ソリューションのエクスポート](media/cds-native-4.png)

<span data-ttu-id="b89b1-120">ソリューションをエクスポートした後、移行先の環境に移動してソリューションをインポートできます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-120">After exporting the solution, you can go to the destination environment and import the solution.</span></span>

![ソリューションのインポート](media/cds-native-5.png)

<span data-ttu-id="b89b1-122">このソリューションのフローは、更新されている取引先企業のリスニングとメモの作成をすぐに開始します。</span><span class="sxs-lookup"><span data-stu-id="b89b1-122">The flow in this solution will immediately begin listening to accounts being updated and creating notes.</span></span> <span data-ttu-id="b89b1-123">追加の構成やアクティブ化は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-123">No additional configuration or activation is required.</span></span>

![フローの結果](media/cds-native-6.png)

<span data-ttu-id="b89b1-125">この機能は  **Common Data Service (現在の環境)** 以外のサービスへの接続がないフローに対してのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="b89b1-125">Note that this functionality will only work for flows that do not have connectivity to services besides the **Common Data Service (Current Environment)**.</span></span> <span data-ttu-id="b89b1-126">これは、インポート後に接続所有者によって他のサービスが明示的に許可される必要があるためです。</span><span class="sxs-lookup"><span data-stu-id="b89b1-126">This is because other services must be explicitly authorized by the connection owner after import.</span></span> <span data-ttu-id="b89b1-127">ただし、データを操作したり HTTP コネクタを使用したりする組み込みアクションは、インポート後すぐに機能します。</span><span class="sxs-lookup"><span data-stu-id="b89b1-127">However, built-in actions that manipulate data or use the HTTP connector will work immediately upon import.</span></span>

## <a name="known-issues"></a><span data-ttu-id="b89b1-128">既知の問題</span><span class="sxs-lookup"><span data-stu-id="b89b1-128">Known issues</span></span>

<span data-ttu-id="b89b1-129">新しい **Common Data Service (現在の環境)** 機能は、現在プレビュー版が利用可能で、来週には世界的に展開されます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-129">The new **Common Data Service (Current Environment)** capability is available for preview today and is rolling out globally in the coming week.</span></span> <span data-ttu-id="b89b1-130">ソリューション内に構築されているフローにはいくつかの既知の問題があります。</span><span class="sxs-lookup"><span data-stu-id="b89b1-130">There are a few known issues for flows that are built inside solutions:</span></span>

*   <span data-ttu-id="b89b1-131">Flow モバイル アプリでソリューション フローにアクセスする方法はありません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-131">There is no way to access solution flows in the Flow mobile app.</span></span>
*   <span data-ttu-id="b89b1-132">ソリューション内のボタンが Flow モバイル アプリの [ボタン] タブに表示されず、ボタンの特定のフィールドを使用できません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-132">Buttons inside solutions will not show up in the Buttons tab in the Flow mobile app, and certain fields from buttons cannot be used.</span></span>
*   <span data-ttu-id="b89b1-133">現在、カスタム コネクタをソリューションに含めることができません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-133">Custom connectors cannot currently be included in solutions.</span></span>
*   <span data-ttu-id="b89b1-134">レコード上で列またはフィールドのセットが変更されると、フローが失敗する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="b89b1-134">If the set of columns or fields changes on a record, this might cause the flow to fail.</span></span>
*   <span data-ttu-id="b89b1-135">実行履歴には現在、各アクションの単純なプロパティではなく、アクションに対する未加工の JSON 入力および出力が表示されます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-135">The Run history currently shows the raw JSON inputs and outputs for actions instead of the simple properties of each action.</span></span>
*   <span data-ttu-id="b89b1-136">PowerApps からトリガーされるフローは現在サポートされていません。</span><span class="sxs-lookup"><span data-stu-id="b89b1-136">Flows triggered from PowerApps are not currently supported.</span></span>

<span data-ttu-id="b89b1-137">現在、これらのフローに残っている問題の解決に取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="b89b1-137">We are currently working on closing out the remaining issues with these flows.</span></span>
