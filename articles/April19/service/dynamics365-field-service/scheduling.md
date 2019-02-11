---
title: スケジューリング機能
description: スケジューリング
author: dgittler
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dgittler
ms.reviewer: shellyha
ms.openlocfilehash: 3018dcebdd4e5c490d0a379cc5de1ebfe814bcd1
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210744"
---
#  <a name="scheduling-capabilities"></a><span data-ttu-id="a34c0-103">スケジューリング機能</span><span class="sxs-lookup"><span data-stu-id="a34c0-103">Scheduling capabilities</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]


<span data-ttu-id="a34c0-104">この記事では、2019 年 4 月リリースの新しいスケジューリング機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="a34c0-104">This article describes the new scheduling capabilities in the April '19 release.</span></span>

## <a name="variable-resource-location-optimization"></a><span data-ttu-id="a34c0-105">さまざまな場所へのリソースの配置 (最適化)</span><span class="sxs-lookup"><span data-stu-id="a34c0-105">Variable resource location (optimization)</span></span>

<span data-ttu-id="a34c0-106">チームのスタッフ配置場所を日によって変えることで、チーム運営の変革をサポートします。</span><span class="sxs-lookup"><span data-stu-id="a34c0-106">Transform your operation with support for staffing your team in different locations on different days.</span></span> <span data-ttu-id="a34c0-107">顧客の要望によっては、リソースをさまざまな場所に派遣する必要があることがあります。</span><span class="sxs-lookup"><span data-stu-id="a34c0-107">Based on customer demand, you might need to send resources to different areas.</span></span> <span data-ttu-id="a34c0-108">その場所は近隣地域である場合もあれば、遠隔地や国外の場合もあります。</span><span class="sxs-lookup"><span data-stu-id="a34c0-108">These might be local areas, or even outside the country or region.</span></span> <span data-ttu-id="a34c0-109">場合によっては、リソースを月に 1 回遠隔地に派遣してそこで作業をしてもらうことや、チームが 1 か所に駐在せずに顧客の所在地を転々と移動することもあります。</span><span class="sxs-lookup"><span data-stu-id="a34c0-109">In some cases, resources might travel to a remote area once a month and perform work in that area, or perhaps your team travels from customer location to customer location without having a home base.</span></span> <span data-ttu-id="a34c0-110">毎週水曜日にリソースは倉庫から部品をピックアップし、それ以外の曜日は本部から仕事を開始するケースも考えられます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-110">Maybe resources pick up their parts at the warehouse every Wednesday but start from their homes on other days.</span></span>
<span data-ttu-id="a34c0-111">日付に応じて場所を設定できる機能がサポートされたことで、API を使用してリソースの場所を変更し、これらの場所に関わるさまざまな要望を満たすことができます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-111">With date-effective location support, you can meet these variant location-based demands interacting with an API that allows you to change your resources' location.</span></span> 

<span data-ttu-id="a34c0-112">リソースをさまざまな場所に配置して最適化する機能により、日次ベースで技術者の始業場所と終業場所を設定できます。これは、サービス マネージャー、派遣担当者、別の従業員が実行できます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-112">Variable resource location optimization enables setting start and end locations for a technician on a daily basis, which can be done by a service manager, dispatcher, or another employee.</span></span>

## <a name="self-service-scheduling-via-a-portal"></a><span data-ttu-id="a34c0-113">ポータルを介したセルフサービス スケジューリング</span><span class="sxs-lookup"><span data-stu-id="a34c0-113">Self-service scheduling via a portal</span></span>

<span data-ttu-id="a34c0-114">セルフサービス スケジューリングにより、時間と都合を顧客に合わせてスケジュールを設定できます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-114">Engage your customers on their time, and at their convenience with self-service scheduling.</span></span> <span data-ttu-id="a34c0-115">予定のスケジューリングは時間のかかる作業であり、リソースの消費が大きく、よく連絡ミスが発生します。</span><span class="sxs-lookup"><span data-stu-id="a34c0-115">Scheduling appointments can be time consuming, resource intensive, and prone to communication mistakes.</span></span> <span data-ttu-id="a34c0-116">今ではスタッフのスキルや空き時間を十分に考慮しつつ、顧客の都合に合わせて独自に予定をスケジューリングできます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-116">Now, you can empower your customers to simply schedule appointments on their own, at their convenience, while ensuring the skills and availability of your staff are fully considered.</span></span>  

<span data-ttu-id="a34c0-117">セルフサービス スケジューリング機能を使用すると、最新の利便性の高い方法で顧客と連携できるのに加えて、営業やマーケティングに従事する組織が自社のマーケティング ジャーニーにセルフ スケジューリングを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-117">In addition to engaging customers in a modern and convenient manner, self-service scheduling empowers your sales and marketing organization to embed self-scheduling into your organization's marketing journey.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="a34c0-118">![ポータルを介したセルフサービス スケジューリング](media/scheduling-2.png "ポータルを介したセルフサービス スケジューリング")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="a34c0-118">![Self-service scheduling via a portal](media/scheduling-2.png "Self-service scheduling via a portal")
<!-- picture --></span></span>
 
<span data-ttu-id="a34c0-119">自社のフィールド サービス部門で、四半期に 1 回予防保全のための訪問を予約する必要があるとします。</span><span class="sxs-lookup"><span data-stu-id="a34c0-119">Let's say your field service division has quarterly preventive maintenance visits that need to be booked.</span></span> <span data-ttu-id="a34c0-120">あるいは自社の Web サイトからリードをキャプチャし、このリードを引き込むためにドリップ マーケティング キャンペーンを使用してフォローアップしているとも考えられます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-120">Perhaps you captured a lead from your website and are following up with a drip marketing campaign to engage this lead.</span></span> <span data-ttu-id="a34c0-121">マーケティング計画のアクション項目としてセルフスケジューリングを提供することで、コンバージョン率を高め、フォローアップに要する時間を削減できます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-121">By offering self-scheduling as an action item in the marketing plan, you can increase conversion rates and decrease follow-up time.</span></span> 

<span data-ttu-id="a34c0-122">ポータルを通じて、顧客はその日のうちに空いている時間枠を検索して予約できます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-122">Through a portal, your customers can search for and book an available time slot within a day.</span></span> <span data-ttu-id="a34c0-123">顧客には適切なスキルを持ったリソースに空きがある時間枠が提示されます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-123">Customers are presented with time slots that have available resources with the proper skills.</span></span> <span data-ttu-id="a34c0-124">顧客は予定を予約した後の段階で予約をキャンセルすることも再予約することもできます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-124">After booking an appointment, at a later point in time, customers are able to cancel or rebook the appointment.</span></span>

## <a name="optimization-insights"></a><span data-ttu-id="a34c0-125">最適化の分析情報</span><span class="sxs-lookup"><span data-stu-id="a34c0-125">Optimization insights</span></span>

<span data-ttu-id="a34c0-126">サービス マネージャーと派遣担当者は、リソースのスケジュールが効果的であり、スケジューリングの結果がビジネスの目標と一致していることを確認する責任があります。</span><span class="sxs-lookup"><span data-stu-id="a34c0-126">Service managers and dispatchers are responsible to assure resources are being effectively scheduled and also to assure scheduling results are consistent with their business goals.</span></span>

<span data-ttu-id="a34c0-127">この機能が提供する Power BI ベースの分析ダッシュボードからは数多くの分析情報が得られ、単純な実行や複数の実行にわたる最適化の要約や統計を表示することで、企業が最適化の結果を評価し、スケジューリングの目標やリソースの使用状況などを測定するのを支援します。</span><span class="sxs-lookup"><span data-stu-id="a34c0-127">This feature provides an insightful Power BI-based analytical dashboard to show optimization summarization and statistics for simple run or across multiple runs to help business evaluate optimization results, measure scheduling objectives and resource usage, and more.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="a34c0-128">![最適化の分析情報](media/scheduling-1.png "最適化の分析情報")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="a34c0-128">![Optimization insights](media/scheduling-1.png "Optimization insights")
<!-- picture --></span></span>

## <a name="optimization-objective-for-as-soon-as-possible-asap"></a><span data-ttu-id="a34c0-129">「できるだけ早く (ASAP)」の最適化目標</span><span class="sxs-lookup"><span data-stu-id="a34c0-129">Optimization objective for as soon as possible (ASAP)</span></span> 

<span data-ttu-id="a34c0-130">たまに (作業指示書などで) リソースのキャパシティがリソースの需要を超えることがあります。</span><span class="sxs-lookup"><span data-stu-id="a34c0-130">Occasionally, there might be more resource capacity than there is demand for resources (for example, work orders).</span></span> <span data-ttu-id="a34c0-131">そのような状況において、リソースの予定を完全に埋めてしまうか、緊急時や予定外の作業に備えてリソースを残しておくか、経営上の判断を求められます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-131">In these circumstances, there is a business decision about whether to fully book some resources or leave resources with some capacity as a contingency for emergency or unplanned work.</span></span>

<span data-ttu-id="a34c0-132">2019 年 4 月のリリースでは、「できるだけ早く (ASAP)」という新しい目標が設定できるようになります。これにより、組織は他のスケジューリングの目標を選択して再度ランク付けすることで、一部のリソースを余裕を持って残しておくか、1 日の予定をすべて埋めてしまうか、バランスを取ることができます。</span><span class="sxs-lookup"><span data-stu-id="a34c0-132">The April '19 release enables a new objective for as soon as possible (ASAP), so that organizations can select and rerank with other scheduling objectives to balance the need to reserve some capacity with the need to keep resources busy all day.</span></span>


