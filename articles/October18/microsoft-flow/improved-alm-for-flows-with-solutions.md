---
title: "ソリューションを使用したフローの ALM の向上"
description: "ソリューションには、キャンバス アプリ、およびモデル駆動型アプリ、フロー、他のコンポーネントを含めることができます。"
author: stepsic-microsoft-com
manager: KVivek
ms.date: 11/27/2018
ms.assetid: 66861f2b-56e1-e811-a976-000d3a137a43
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: stepsic
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: deb13c779fe624fc20d8a5ab1fb3c1c0a548371b
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---
# <a name="improved-alm-for-flows-with-solutions"></a><span data-ttu-id="289db-103">ソリューションを使用したフローの ALM の向上</span><span class="sxs-lookup"><span data-stu-id="289db-103">Improved ALM for flows with solutions</span></span>




<span data-ttu-id="289db-104">Microsoft は最近、PowerApps と Microsoft Flow の新しいアプリケーション ライフサイクル管理 (ALM) 機能についてのニュースを[発表](https://powerapps.microsoft.com/blog/apps-and-flows-lifecycle-management-just-got-easier/)しました。</span><span class="sxs-lookup"><span data-stu-id="289db-104">In a recent [announcement](https://powerapps.microsoft.com/blog/apps-and-flows-lifecycle-management-just-got-easier/), Microsoft shared news about a new application lifecycle management (ALM) capability for PowerApps and Microsoft Flow.</span></span> <span data-ttu-id="289db-105">この新しい機能は Common Data Service (CDS) ソリューションが基になっており、関連するフロー (およびアプリ) を単一の展開可能ユニットにバンドルすることができます。</span><span class="sxs-lookup"><span data-stu-id="289db-105">This new capability is built upon Common Data Service (CDS) solutions, and allows you to bundle related flows (and apps) within a single deployable unit.</span></span>

<span data-ttu-id="289db-106">以前は、単一のフローをある環境からエクスポートして別の環境にインポートする機能が提供されていました。</span><span class="sxs-lookup"><span data-stu-id="289db-106">Previously, we provided the ability to export and import a single flow from one environment to another environment.</span></span> <span data-ttu-id="289db-107">この機能は環境間で個別のフローをプロモートするのには役立ちましたが、複数のフローを移動するには多くの労力が必要でした。</span><span class="sxs-lookup"><span data-stu-id="289db-107">While this feature was useful for promoting individual flows between environments, it required much effort to move multiple flows.</span></span>

<span data-ttu-id="289db-108">また、お客様から、フローを構築したり管理したりするときに[*関連するフローを論理的にグループ化する*](https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796)ための機能に関するフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="289db-108">We have also received feedback from our customers regarding the ability to [logically *group related flows*](https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796) as they are being built and managing them.</span></span> <span data-ttu-id="289db-109">たとえば、作業中のプロジェクトの一部である複数のフローがあるとします。</span><span class="sxs-lookup"><span data-stu-id="289db-109">For example, you may have multiple flows that are part of a project you are working on.</span></span> <span data-ttu-id="289db-110">これらのフローを作業または管理する際、フローにアクセスしたいときにスクロールして検索することが必要なのは好ましくありません。</span><span class="sxs-lookup"><span data-stu-id="289db-110">While working on, or managing these flows, you don’t want to have to scroll, and then search for these flows when you want to access them.</span></span>

<span data-ttu-id="289db-111">ソリューションは、一連のフロー (およびアプリ) をエクスポートおよびインポートできるようにすることで、展開のニーズに対応します。</span><span class="sxs-lookup"><span data-stu-id="289db-111">Solutions address deployment needs by allowing you to export and import a set of flows (and apps).</span></span> <span data-ttu-id="289db-112">さらに、これらのフローを単一の「コンテナー」内に整理することができ、フローのナビゲートと管理が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="289db-112">In addition, you can organize these flows within a single ‘container,’ which simplifies navigating and managing them.</span></span>

## <a name="accessing-solutions"></a><span data-ttu-id="289db-113">ソリューションへのアクセス</span><span class="sxs-lookup"><span data-stu-id="289db-113">Accessing solutions</span></span>

<span data-ttu-id="289db-114">新しい**ソリューション** リンクが、Microsoft Flow ポータルの左側のナビゲーション内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="289db-114">A new **Solutions** link will appear within the left navigation of the Microsoft Flow portal.</span></span> <span data-ttu-id="289db-115">このエクスペリエンスは、Common Data Service データベース バージョン 9.1.0.267 以降の環境で使用できます。</span><span class="sxs-lookup"><span data-stu-id="289db-115">This experience is available in environments that have a Common Data Service database with version 9.1.0.267 or later.</span></span> <span data-ttu-id="289db-116">**ソリューション**が表示されず、環境の管理者である場合は、**[Microsoft Flow 管理センター](https://admin.flow.microsoft.com/)** > **環境** > ***環境の選択*** > **詳細**タブに移動します。**自分のデータベースを作成**ボタンが表示されたら、そのボタンを選択して、ソリューションを格納するための Common Data Service データベースを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="289db-116">If you don't see **Solutions**, and you are the administrator of the environment, go to the **[Microsoft Flow admin center](https://admin.flow.microsoft.com/)** > **Environments** > ***Select your environment*** > **Details** tab. If you see a **Create my database** button, you will need to select that button to create a Common Data Service database to store the solution.</span></span> <span data-ttu-id="289db-117">データベースがある場合は、**インスタンスのバージョン**を確認できます。</span><span class="sxs-lookup"><span data-stu-id="289db-117">If there is a database, you can check the **Instance version**.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-118">![ソリューションへのアクセス](media/improve-alm-solutions/solutions-1-accessingsolutions.png "ソリューションへのアクセス")</span><span class="sxs-lookup"><span data-stu-id="289db-118">![Accessing solutions](media/improve-alm-solutions/solutions-1-accessingsolutions.png "Accessing solutions")</span></span>

<span data-ttu-id="289db-119">**ソリューション**を選択すると、環境内のすべてのソリューションのリストが表示されます。</span><span class="sxs-lookup"><span data-stu-id="289db-119">Selecting **Solutions** gives you a list of all solutions in your environment.</span></span> <span data-ttu-id="289db-120">このエクスペリエンスの一部として、ソリューションが作成された**日付**、**バージョン**、およびソリューションに関するその他の詳細を確認できます。</span><span class="sxs-lookup"><span data-stu-id="289db-120">As part of this experience you can see the **Date** it was created, the **Version**, and other details about the solution.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-121">![ソリューションの参照](media/improve-alm-solutions/solutions-2-solutionsexplorer.png)</span><span class="sxs-lookup"><span data-stu-id="289db-121">![Browsing solutions](media/improve-alm-solutions/solutions-2-solutionsexplorer.png)</span></span>

## <a name="creating-a-new-solution"></a><span data-ttu-id="289db-122">新しいソリューションの作成</span><span class="sxs-lookup"><span data-stu-id="289db-122">Creating a new solution</span></span>

<span data-ttu-id="289db-123">フローをグループ化する新しいソリューションを作成するには、ソリューション エクスペリエンスから、**新しいソリューション** ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="289db-123">To create a new solution to group your flows, from the Solutions experience, select the **New Solution** button.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-124">![新しいソリューション](media/improve-alm-solutions/solutions-3-newsolution.png)</span><span class="sxs-lookup"><span data-stu-id="289db-124">![New solution](media/improve-alm-solutions/solutions-3-newsolution.png)</span></span>

<span data-ttu-id="289db-125">新しいタブが開き、ソリューションの**表示名**、**発行元**、および**バージョン**を提供できます。</span><span class="sxs-lookup"><span data-stu-id="289db-125">A new tab will open where you can provide the **Display Name**, **Publisher**, and **Version** of your solution.</span></span> <span data-ttu-id="289db-126">これらの詳細を入力したら、**保存**を選択し、**閉じる**を選択します。</span><span class="sxs-lookup"><span data-stu-id="289db-126">Once you have provided these details, select **Save** and **Close**.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-127">![ソリューションの保存](media/improve-alm-solutions/solutions-4-savesolution.png)</span><span class="sxs-lookup"><span data-stu-id="289db-127">![Save solution](media/improve-alm-solutions/solutions-4-savesolution.png)</span></span>

## <a name="adding-flows-to-a-solution"></a><span data-ttu-id="289db-128">ソリューションへのフローの追加</span><span class="sxs-lookup"><span data-stu-id="289db-128">Adding flows to a solution</span></span>

<span data-ttu-id="289db-129">ソリューション エクスペリエンスから、新しく作成したソリューションを選択して、既定のビューに移動できます。</span><span class="sxs-lookup"><span data-stu-id="289db-129">From the Solutions experience, you can select your newly created solution and navigate to its default view.</span></span> <span data-ttu-id="289db-130">状況に応じたメニューが表示され、**新規**および**既存**の資産をソリューションに追加できます。</span><span class="sxs-lookup"><span data-stu-id="289db-130">A context-aware menu will appear that allows you to add **New** and **Existing** assets to your solution.</span></span> <span data-ttu-id="289db-131">ソリューションに新しいフローを追加するには、**新規 – フロー**を選択します。</span><span class="sxs-lookup"><span data-stu-id="289db-131">Select **New – Flow** to add a new flow to your solution.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-132">![新しいフロー](media/improve-alm-solutions/solutions-5-newflow.png)</span><span class="sxs-lookup"><span data-stu-id="289db-132">![New flow](media/improve-alm-solutions/solutions-5-newflow.png)</span></span>

<span data-ttu-id="289db-133">新しいタブが開いてフロー デザイナーに移動し、そこではフローを構築して、関連するトリガーとアクションを追加することができます。</span><span class="sxs-lookup"><span data-stu-id="289db-133">A new tab will open that will take you to the flow designer where you can construct your flow and add your related trigger and action(s).</span></span> <span data-ttu-id="289db-134">フローの編集が完了したら、**保存**を選択してフローを保存します。</span><span class="sxs-lookup"><span data-stu-id="289db-134">Once you are done editing your flow, press **Save** to save your flow.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-135">![フローの保存](media/improve-alm-solutions/solutions-6-saveflow.png)</span><span class="sxs-lookup"><span data-stu-id="289db-135">![Save flow](media/improve-alm-solutions/solutions-6-saveflow.png)</span></span>

<span data-ttu-id="289db-136">フローを保存すると、このフローはソリューションの一部になります。</span><span class="sxs-lookup"><span data-stu-id="289db-136">Once you have saved your flow, this flow will be part of your solution.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-137">![ソリューション内のフロー](media/improve-alm-solutions/solutions-7-newflow.png)</span><span class="sxs-lookup"><span data-stu-id="289db-137">![Flow in solution](media/improve-alm-solutions/solutions-7-newflow.png)</span></span>

<span data-ttu-id="289db-138">以上の手順を繰り返して、後続のフローをソリューションに追加することができます。</span><span class="sxs-lookup"><span data-stu-id="289db-138">You can repeat these steps to add subsequent flows in your solution.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-139">![複数のフロー](media/improve-alm-solutions/solutions-8-multipleflows.png)</span><span class="sxs-lookup"><span data-stu-id="289db-139">![Multiple flows](media/improve-alm-solutions/solutions-8-multipleflows.png)</span></span>

## <a name="exporting-your-solution"></a><span data-ttu-id="289db-140">ソリューションのエクスポート</span><span class="sxs-lookup"><span data-stu-id="289db-140">Exporting your solution</span></span>

<span data-ttu-id="289db-141">ALM の重要な側面は、最初にサンドボックスまたはテスト環境でフローが動作することを検証した後、単一のアクションで、フローを実稼働環境に移動できることです。</span><span class="sxs-lookup"><span data-stu-id="289db-141">An important aspect of ALM is you can validate if your flows work in a sandbox or test environment first, and then in a single action, move your flows to your production environment.</span></span> <span data-ttu-id="289db-142">ソリューションをエクスポートするには、**ソリューション** エクスペリエンスでソリューションを探し、**…** を選択し、**エクスポート**を選択した後、**アンマネージドとして**を選択します。</span><span class="sxs-lookup"><span data-stu-id="289db-142">Export your solution by finding it in your **Solutions** experience, selecting **…**, selecting **Export**, and then selecting **As unmanaged**.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-143">![エクスポート](media/improve-alm-solutions/solutions-9-export.png)</span><span class="sxs-lookup"><span data-stu-id="289db-143">![Export](media/improve-alm-solutions/solutions-9-export.png)</span></span>

<span data-ttu-id="289db-144">**アンマネージドとして**を選択すると、ローカルにダウンロードして保存できる zip ファイルが用意されます。</span><span class="sxs-lookup"><span data-stu-id="289db-144">Once you select **As unmanaged**, a zip file will be made available for you that you can download and store locally.</span></span>

## <a name="importing-your-solution"></a><span data-ttu-id="289db-145">ソリューションのインポート</span><span class="sxs-lookup"><span data-stu-id="289db-145">Importing your solution</span></span>

<span data-ttu-id="289db-146">ソリューションをエクスポートすると、実稼働環境などの別の環境にソリューションをインポートできるようになります。</span><span class="sxs-lookup"><span data-stu-id="289db-146">With your solution exported, you can now import it into another environment, such as a production environment.</span></span> <span data-ttu-id="289db-147">環境ピッカーで実稼働環境を選択すると、**インポート**を選択することでパッケージのインポートを選択できます。</span><span class="sxs-lookup"><span data-stu-id="289db-147">With your production environment selected from the environment picker, you can now choose to import your package by selecting **Import**.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-148">![インポート](media/improve-alm-solutions/solutions-10-import.png)</span><span class="sxs-lookup"><span data-stu-id="289db-148">![Import](media/improve-alm-solutions/solutions-10-import.png)</span></span>

<span data-ttu-id="289db-149">ソリューション パッケージを**参照**して選択し、ウィザードを完了してソリューションをロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="289db-149">You now need to **browse** to select your solution package and then complete the wizard to load the solution.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-150">![パッケージの選択](media/improve-alm-solutions/solutions-11-selectpackage.png)</span><span class="sxs-lookup"><span data-stu-id="289db-150">![Select package](media/improve-alm-solutions/solutions-11-selectpackage.png)</span></span>

<span data-ttu-id="289db-151">インポート プロセスが完了すると、新しい環境内に展開されたソリューションが表示されます。</span><span class="sxs-lookup"><span data-stu-id="289db-151">Once you complete the import process, you will find your solution deployed within your new environment.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-152">![インポートされた新しいソリューション](media/improve-alm-solutions/solutions-12-newsolution.png)</span><span class="sxs-lookup"><span data-stu-id="289db-152">![New solution imported](media/improve-alm-solutions/solutions-12-newsolution.png)</span></span>

## <a name="configuring-and-enabling-your-solution"></a><span data-ttu-id="289db-153">ソリューションの構成と有効化</span><span class="sxs-lookup"><span data-stu-id="289db-153">Configuring and enabling your solution</span></span>

<span data-ttu-id="289db-154">ソリューションをインポートした後は、実行する必要があるアクティビティがいくつかあります。</span><span class="sxs-lookup"><span data-stu-id="289db-154">With your solution imported, there are still a couple of activities that you must perform:</span></span>

- <span data-ttu-id="289db-155">インポートした各フローについて、トリガーとアクションに対する接続を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="289db-155">For each flow that you have imported, you need to wire up connections for your triggers and actions.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="289db-156">![接続](media/improve-alm-solutions/solutions-13-connections.png)</span><span class="sxs-lookup"><span data-stu-id="289db-156">![Connections](media/improve-alm-solutions/solutions-13-connections.png)</span></span>

- <span data-ttu-id="289db-157">既定では、インポートされたフローは、接続をまだ確立する必要があるため、無効な状態になっています。</span><span class="sxs-lookup"><span data-stu-id="289db-157">By default, when flows are imported, they will be in a disabled state since connections still need to be established.</span></span> <span data-ttu-id="289db-158">接続を確立してフローを保存すると、フローがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="289db-158">Upon establishing connections and saving the flow, the flow will become activated.</span></span>

  > [!NOTE]
  > <span data-ttu-id="289db-159">アクティブになっているフローに変更を保存することはできません。</span><span class="sxs-lookup"><span data-stu-id="289db-159">You cannot save changes to a flow that is activated.</span></span> <span data-ttu-id="289db-160">先に、ソリューション エクスペリエンスまたはフロー作成ポータルでフローをオフにして、フローを非アクティブにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="289db-160">You need to deactivate it first either from the Solutions experience or from the flow maker portal by turning the flow off.</span></span>
