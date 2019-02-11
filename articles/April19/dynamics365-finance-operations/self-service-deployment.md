---
title: セルフサービス展開
description: Tier 2 以上および本番環境へのセルフサービス展開
author: sarvanisathish
manager: AnnBe
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: sarvanis
audience: admin, end user, IT pro
ms.openlocfilehash: 51f10ce499d8fc5e4681740f18330c09bba9a318
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210304"
---
# <a name="self-service-deployment"></a><span data-ttu-id="dab22-103">セルフサービス展開</span><span class="sxs-lookup"><span data-stu-id="dab22-103">Self-service deployment</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="dab22-104">新規導入プロジェクト向けのセルフサービス展開オプションが、2018 年 12 月に制限付きで提供開始されました。</span><span class="sxs-lookup"><span data-stu-id="dab22-104">The self-service deployment option for new implementation projects was released with limited availability in December 2018.</span></span> <span data-ttu-id="dab22-105">今回は、本番環境向けのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="dab22-105">We are now adding  support for production environments.</span></span> <span data-ttu-id="dab22-106">これにより本番環境は、セルフサービス展開用に構成されたすべての Lifecycle Services (LCS) プロジェクトに展開できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="dab22-106">Production environments can now be deployed for all Lifecycle Services (LCS) projects that are configured for self-service deployments.</span></span>

<span data-ttu-id="dab22-107">現時点では、セルフサービス展開オプションの対象となる新規プロジェクトはごく一部に限られています。</span><span class="sxs-lookup"><span data-stu-id="dab22-107">Currently only a small percentage of new projects are onboarded to the self-service deployment option.</span></span> <span data-ttu-id="dab22-108">Microsoft では、新規プロジェクトの割合を今後徐々に増やしていく予定です。</span><span class="sxs-lookup"><span data-stu-id="dab22-108">We will incrementally increase the percentage of new projects onboarded over time.</span></span> <span data-ttu-id="dab22-109">既存のプロジェクトや環境への影響はありません。</span><span class="sxs-lookup"><span data-stu-id="dab22-109">There is no impact to any pre-existing projects and environments.</span></span> <span data-ttu-id="dab22-110">Microsoft では、お客様の環境に新しいエクスペリエンスをもたらすべく、セルフサービス展開を使用していないお客様と連携して取り組んでいく予定です。</span><span class="sxs-lookup"><span data-stu-id="dab22-110">We will work with the customers, not on self-service deployment, to bring the new experience to their environments.</span></span>

<span data-ttu-id="dab22-111">Tier 2 以上のサンドボックス環境に適用可能な機能についてはすべて、本番環境との整合性が確保されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-111">All features applicable to Tier 2+ sandbox environments will be consistent with the production environments.</span></span>

## <a name="production-environments"></a><span data-ttu-id="dab22-112">本番環境</span><span class="sxs-lookup"><span data-stu-id="dab22-112">Production environments</span></span>
1. <span data-ttu-id="dab22-113">本番環境は、セルフサービス アクションとして展開できるようになります。</span><span class="sxs-lookup"><span data-stu-id="dab22-113">You will be able to deploy production environments as a self-service action.</span></span> <span data-ttu-id="dab22-114">Microsoft のサービス要求を発行する必要はなくなります。</span><span class="sxs-lookup"><span data-stu-id="dab22-114">You will no longer need to raise a Microsoft service request.</span></span>
2. <span data-ttu-id="dab22-115">展開は 3 時間以内に完了します (つまり、現在の方法で展開する場合の 3 分の 1 の時間)。</span><span class="sxs-lookup"><span data-stu-id="dab22-115">Deployments will be complete in less than 3 hours, or a third of the time taken to deploy using the current method.</span></span>
3. <span data-ttu-id="dab22-116">更新を適用するため、結合された展開可能パッケージが Tier 2 サンドボックス環境に適用されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-116">In order to apply updates, the combined deployable package will be applied to the Tier 2 sandbox environment.</span></span> <span data-ttu-id="dab22-117">パッケージが適用されて検証されると、パッケージが本番環境に昇格されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-117">Once the package is applied and validated, it will be promoted to the production environment.</span></span> 

## <a name="tier-1-through-tier-5-sandbox-environments"></a><span data-ttu-id="dab22-118">Tier 1 から Tier 5 のサンドボックス環境</span><span class="sxs-lookup"><span data-stu-id="dab22-118">Tier 1 through Tier 5 sandbox environments</span></span>

### <a name="configure-tier-1-build-environment"></a><span data-ttu-id="dab22-119">Tier 1 ビルド環境の構成</span><span class="sxs-lookup"><span data-stu-id="dab22-119">Configure Tier 1 build environment</span></span>
<span data-ttu-id="dab22-120">Tier 2 以上および本番環境に更新を適用できるようにするには、Tier 1 ビルド環境を構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dab22-120">You will need to configure a Tier 1 build environment to be able to apply updates to Tier 2+ and production environments.</span></span> <span data-ttu-id="dab22-121">その Tier 1 ビルド環境を使用して、ISV ソリューションとカスタマイズを組み合わせた、単一の展開可能な更新パッケージを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dab22-121">Using the Tier 1 build environment, you will need to create a single, deployable update package that combines ISV solutions and customizations.</span></span> <span data-ttu-id="dab22-122">パッケージ内に含まれているものはすべて環境に適用され、環境内にすでに存在しているものは上書きされます。</span><span class="sxs-lookup"><span data-stu-id="dab22-122">Whatever is supplied in the package is applied to the environment and it overwrites what is already present in the environment.</span></span>

### <a name="remote-desktop-access"></a><span data-ttu-id="dab22-123">リモート デスクトップ アクセス</span><span class="sxs-lookup"><span data-stu-id="dab22-123">Remote desktop access</span></span>
<span data-ttu-id="dab22-124">現在、本番環境へのリモート デスクトップ アクセスはありません。</span><span class="sxs-lookup"><span data-stu-id="dab22-124">Today there is no remote desktop access to production environments.</span></span> <span data-ttu-id="dab22-125">今後は、Tier 2 から Tier 5 のサンドボックス環境に対するリモート デスクトップ アクセスはできなくなります。</span><span class="sxs-lookup"><span data-stu-id="dab22-125">Going forward, you will not have remote desktop access to the Tier 2 to Tier 5 sandbox environments.</span></span> <span data-ttu-id="dab22-126">ただし、Tier 2、Tier 3、Tier 4、および Tier 5 のサンドボックス環境に関連付けられている Azure SQL データベースには、引き続きアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="dab22-126">However, you will continue to have access to the Azure SQL database associated with the Tier 2, Tier 3, Tier 4, and Tier 5 sandbox environments.</span></span> <span data-ttu-id="dab22-127">このアクセスは永続的ではありません。必要に応じて付与されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-127">The access will not be persistent; but rather, it will be granted as and when needed.</span></span> 

<span data-ttu-id="dab22-128">Azure SQL データベースにアクセスするには:</span><span class="sxs-lookup"><span data-stu-id="dab22-128">To access the Azure SQL database:</span></span>

1.  <span data-ttu-id="dab22-129">Lifecycle Services (LCS) から、SQL Server Management Studio を使用して、Azure SQL データベースへの接続に使用するコンピューターの IP アドレスを追加します。</span><span class="sxs-lookup"><span data-stu-id="dab22-129">From Lifecycle Services (LCS), add the IP address of the machine that you will use to connect to the Azure SQL database using SQL Server Management Studio.</span></span>

2.  <span data-ttu-id="dab22-130">LCS を使用して、データベースの資格情報を参照するためのアクセス権を要求します。</span><span class="sxs-lookup"><span data-stu-id="dab22-130">Use LCS to request access to see the database credentials.</span></span> <span data-ttu-id="dab22-131">その際、アクセス権を要求する理由を明示する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dab22-131">You must provide a reason for requesting access.</span></span>

<span data-ttu-id="dab22-132">要求を送信すると、要求がすぐに自動で承認されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-132">As soon as you submit the request, it's automatically approved.</span></span> <span data-ttu-id="dab22-133">1〜2 分以内に、LCS の **環境の詳細** ページにデータベース アクセスの資格情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="dab22-133">Within a minute or two, you will be able to see the database access credentials on the **Environment Details** page in LCS.</span></span> <span data-ttu-id="dab22-134">この資格情報を使用して、SQL データベースに接続できます。</span><span class="sxs-lookup"><span data-stu-id="dab22-134">You can use the credentials to connect to the SQL database.</span></span>

> [!NOTE]
> <span data-ttu-id="dab22-135">資格情報の有効期限は 8 時間で、その後は期限切れとなります。</span><span class="sxs-lookup"><span data-stu-id="dab22-135">The credentials are valid for eight hours, and then they expire.</span></span> <span data-ttu-id="dab22-136">資格情報が期限切れになると、アクセス権をもう一度要求しなければならなくなります。</span><span class="sxs-lookup"><span data-stu-id="dab22-136">After the credentials expire, you will have to request access again.</span></span>

<span data-ttu-id="dab22-137">コンピューターへのリモート アクセスを必要とするその他のアクション (環境間でのデータベース移動、CPU やメモリの消費量などといった正常性指標の確認、障害ログへのアクセス権の取得、リグレッション ツールの実行など) はすべて、LCS か、コンピューターへのリモート アクセスを必要としない方法を通じて利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="dab22-137">All other actions that require remote access into the machine, such as database movement across environments, seeing the health metrics such as CPU and memory consumption, getting access to the failure logs, and running regression tools, will be made available through LCS or in a way that does not require remote access into the machine.</span></span>
