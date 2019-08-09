---
title: Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上
description: ソリューション機能の一般提供
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: ab87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 39fec21e1bd6ecacc939f0d716e786bdc846ad4f
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756734"
---
# <a name="improved-application-lifecycle-management-for-flows-using-common-data-service"></a><span data-ttu-id="d5512-103">Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上</span><span class="sxs-lookup"><span data-stu-id="d5512-103">Improved application lifecycle management for flows using Common Data Service</span></span>

<span data-ttu-id="d5512-104">11 月に、マイクロソフトは Common Data Service ソリューションでの自動化およびスケジュールされたインスタント フローのサポートを[リリース](https://flow.microsoft.com/blog/solutions-in-microsoft-flow/)しました。</span><span class="sxs-lookup"><span data-stu-id="d5512-104">In [November, we released](https://flow.microsoft.com/blog/solutions-in-microsoft-flow/) support for automated, scheduled, and instant flows in Common Data Service solutions.</span></span> <span data-ttu-id="d5512-105">**ソリューション**により、フローや Common Data Service エンティティなどのコンポーネントのグループを作成、パッケージ化、メンテナンスできます。</span><span class="sxs-lookup"><span data-stu-id="d5512-105">**Solutions** allow you to author, package, and maintain groups of components, such as flows and Common Data Service entities.</span></span> <span data-ttu-id="d5512-106">ソリューションを配布することで、自分 (または他のユーザー) が、環境全体でソリューションによって定義されているビジネス機能のインストールやアンインストールをできるようになります。</span><span class="sxs-lookup"><span data-stu-id="d5512-106">You can distribute solutions allowing you (or others) to install and uninstall the business functionality defined by the solution across environments.</span></span>

<span data-ttu-id="d5512-107">ソリューションの機能を向上させる新しい機能を現在リリースしています。</span><span class="sxs-lookup"><span data-stu-id="d5512-107">We are now releasing new functionality that improves the way solutions work.</span></span> <span data-ttu-id="d5512-108">具体的には、Common Data Service を使用する一部のフローを、新しい環境へのソリューションのインポート後に自動的にアクティブ化できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d5512-108">In particular, some flows that use Common Data Service can now be automatically activated after you import a solution to a new environment.</span></span>

<span data-ttu-id="d5512-109">自動的にオンにすることができるフローを構築するには、最初に左のナビゲーションで **ソリューション** に移動し、ソリューションを選択してからフローを追加することで、フローを構築する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d5512-109">To build flows that can automatically be turned on, the flow must be built by first going to **Solutions** in the left navigation, choosing a solution, and then adding the flow.</span></span> <span data-ttu-id="d5512-110">フローを構築する際には、新しい **Common Data Service (現在の環境)** コネクタを使用します。</span><span class="sxs-lookup"><span data-stu-id="d5512-110">When you build the flow, use the new **Common Data Service (Current Environment)** connector:</span></span>

![コネクタの検索](media/CDS-Native-1.png)

<span data-ttu-id="d5512-112">既定では、このコネクタは、それが展開されている環境を使用し、フローの所有者のユーザー コンテキストを自動的に取得できます。</span><span class="sxs-lookup"><span data-stu-id="d5512-112">By default, this connector uses the environment in which it's deployed and automatically picks up the user context of the owner of the flow.</span></span> <span data-ttu-id="d5512-113">つまり、接続先の環境を選択する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d5512-113">This means you don’t have to select the environment to which to connect:</span></span>

![完全トリガー](media/CDS-Native-2.png)

<span data-ttu-id="d5512-115">この例では、取引先企業の親会社が変更されたときにすべての関連取引先企業に自動的にメモを追加するフローを作成できます。</span><span class="sxs-lookup"><span data-stu-id="d5512-115">In this example, we can create a flow that automatically adds a note to all related accounts when a parent account changes:</span></span>

![完全フロー](media/CDS-Native-3.png)

<span data-ttu-id="d5512-117">フローを保存したら、それを[管理ソリューションまたは非管理ソリューション](https://docs.microsoft.com/dynamics365/customer-engagement/developer/introduction-solutions#unmanaged-and-managed-solutions)としてエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="d5512-117">Once you save the flow, you can export it as either a [managed or unmanaged solution](https://docs.microsoft.com/dynamics365/customer-engagement/developer/introduction-solutions#unmanaged-and-managed-solutions).</span></span> <span data-ttu-id="d5512-118">Microsoft Flow で完全にサポートされるようになった管理ソリューションは、フローを運用環境に移行するときに便利です。</span><span class="sxs-lookup"><span data-stu-id="d5512-118">Managed solutions, which Microsoft Flow now fully supports, are useful when you want to move a flow to a production environment.</span></span>

![ソリューションのエクスポート](media/CDS-Native-4.png)

<span data-ttu-id="d5512-120">ソリューションをエクスポートした後、移行先の環境に移動してソリューションをインポートできます。</span><span class="sxs-lookup"><span data-stu-id="d5512-120">After exporting the solution, you can go to the destination environment and import the solution.</span></span>

![ソリューションのインポート](media/CDS-Native-5.png)

<span data-ttu-id="d5512-122">このソリューションのフローは、更新されている取引先企業のリスニングとメモの作成をすぐに開始します。</span><span class="sxs-lookup"><span data-stu-id="d5512-122">The flow in this solution immediately begins listening to accounts being updated and creating notes.</span></span> <span data-ttu-id="d5512-123">追加の構成やアクティブ化は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d5512-123">No additional configuration or activation is required.</span></span>

![フローの結果](media/CDS-Native-6.png)

<span data-ttu-id="d5512-125">この機能は **Common Data Service (現在の環境)** 以外のサービスへの接続がないフローに対してのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="d5512-125">This functionality only works for flows that do not have connectivity to services besides the **Common Data Service (Current Environment)**.</span></span> <span data-ttu-id="d5512-126">これは、インポート後に接続所有者によって他のサービスが明示的に許可される必要があるためです。</span><span class="sxs-lookup"><span data-stu-id="d5512-126">This is because other services must be explicitly authorized by the connection owner after import.</span></span> <span data-ttu-id="d5512-127">ただし、データを操作したり HTTP コネクタを使用したりする組み込みアクションは、インポート後すぐに機能します。</span><span class="sxs-lookup"><span data-stu-id="d5512-127">However, built-in actions that manipulate data or use the HTTP connector work immediately after import.</span></span>

## <a name="known-issues"></a><span data-ttu-id="d5512-128">既知の問題</span><span class="sxs-lookup"><span data-stu-id="d5512-128">Known issues</span></span>

<span data-ttu-id="d5512-129">新しい **Common Data Service (現在の環境)** 機能は、現在プレビュー版が利用可能で、間もなく世界的に展開されます。</span><span class="sxs-lookup"><span data-stu-id="d5512-129">The new **Common Data Service (Current Environment)** capability is available for preview today and is rolling out globally soon.</span></span> <span data-ttu-id="d5512-130">ソリューション内に構築されているフローにはいくつかの既知の問題があります。</span><span class="sxs-lookup"><span data-stu-id="d5512-130">There are a few known issues for flows that are built inside solutions:</span></span>

*   <span data-ttu-id="d5512-131">Microsoft Flow モバイル アプリでソリューション フローにアクセスする方法はありません。</span><span class="sxs-lookup"><span data-stu-id="d5512-131">There is no way to access solution flows in the Microsoft Flow mobile app.</span></span>
*   <span data-ttu-id="d5512-132">ソリューション内のボタンが Microsoft Flow モバイル アプリの [ボタン] タブに表示されず、ボタンの一部のフィールドを使用できません。</span><span class="sxs-lookup"><span data-stu-id="d5512-132">Buttons inside solutions will not show up in the Buttons tab in the Microsoft Flow mobile app, and some fields from buttons cannot be used.</span></span>
*   <span data-ttu-id="d5512-133">現在、カスタム コネクタをソリューションに含めることができません。</span><span class="sxs-lookup"><span data-stu-id="d5512-133">Custom connectors cannot currently be included in solutions.</span></span>
*   <span data-ttu-id="d5512-134">レコード上で列またはフィールドのセットが変更されると、フローが失敗する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d5512-134">If the set of columns or fields changes on a record, this might cause the flow to fail.</span></span>
*   <span data-ttu-id="d5512-135">実行履歴には現在、各アクションの単純なプロパティではなく、アクションに対する未加工の JSON 入力および出力が表示されます。</span><span class="sxs-lookup"><span data-stu-id="d5512-135">The Run history currently shows the raw JSON inputs and outputs for actions instead of the simple properties of each action.</span></span>
*   <span data-ttu-id="d5512-136">PowerApps からトリガーされるフローは現在サポートされていません。</span><span class="sxs-lookup"><span data-stu-id="d5512-136">Flows triggered from PowerApps are not currently supported.</span></span>

<span data-ttu-id="d5512-137">現在、これらのフローに残っている問題の解決に取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="d5512-137">We are currently working on closing out the remaining issues with these flows.</span></span>
