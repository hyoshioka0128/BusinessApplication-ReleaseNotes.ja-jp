---
title: スケジューリング機能
description: スケジューリング
author: dgittler
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dgittler
ms.reviewer: shellyha
ms.openlocfilehash: f6a6140b50c8d7bd352e9274398c9b7951240088
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225490"
---
#  <a name="scheduling-capabilities"></a><span data-ttu-id="7eac6-103">スケジューリング機能</span><span class="sxs-lookup"><span data-stu-id="7eac6-103">Scheduling capabilities</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]


<span data-ttu-id="7eac6-104">この記事では、2019 年 4 月リリースの新しいスケジューリング機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="7eac6-104">This article describes the new scheduling capabilities in the April '19 release.</span></span>

## <a name="variable-resource-location-optimization"></a><span data-ttu-id="7eac6-105">さまざまな場所へのリソースの配置 (最適化)</span><span class="sxs-lookup"><span data-stu-id="7eac6-105">Variable resource location (optimization)</span></span>

<span data-ttu-id="7eac6-106">チームのスタッフ配置場所を日によって変えることで、チーム運営の変革をサポートします。</span><span class="sxs-lookup"><span data-stu-id="7eac6-106">Transform your operation with support for staffing your team in different locations on different days.</span></span> <span data-ttu-id="7eac6-107">顧客の要望によっては、リソースをさまざまな場所に派遣する必要があることがあります。</span><span class="sxs-lookup"><span data-stu-id="7eac6-107">Based on customer demand, you might need to send resources to different areas.</span></span> <span data-ttu-id="7eac6-108">その場所は近隣地域である場合もあれば、遠隔地や国外の場合もあります。</span><span class="sxs-lookup"><span data-stu-id="7eac6-108">These might be local areas, or even outside the country or region.</span></span> <span data-ttu-id="7eac6-109">場合によっては、リソースを月に 1 回遠隔地に派遣してそこで作業をしてもらうことや、チームが 1 か所に駐在せずに顧客の所在地を転々と移動することもあります。</span><span class="sxs-lookup"><span data-stu-id="7eac6-109">In some cases, resources might travel to a remote area once a month and perform work in that area, or perhaps your team travels from customer location to customer location without having a home base.</span></span> <span data-ttu-id="7eac6-110">毎週水曜日にリソースは倉庫から部品をピックアップし、それ以外の曜日は本部から仕事を開始するケースも考えられます。</span><span class="sxs-lookup"><span data-stu-id="7eac6-110">Maybe resources pick up their parts at the warehouse every Wednesday but start from their homes on other days.</span></span>
<span data-ttu-id="7eac6-111">日付に応じて場所を設定できる機能がサポートされたことで、API を使用してリソースの場所を変更し、これらの場所に関わるさまざまな要望を満たすことができます。</span><span class="sxs-lookup"><span data-stu-id="7eac6-111">With date-effective location support, you can meet these variant location-based demands interacting with an API that allows you to change your resources' location.</span></span> 

<span data-ttu-id="7eac6-112">リソースをさまざまな場所に配置して最適化する機能により、日次ベースで技術者の始業場所と終業場所を設定できます。これは、サービス マネージャー、派遣担当者、別の従業員が実行できます。</span><span class="sxs-lookup"><span data-stu-id="7eac6-112">Variable resource location optimization enables setting start and end locations for a technician on a daily basis, which can be done by a service manager, dispatcher, or another employee.</span></span>

## <a name="optimization-insights"></a><span data-ttu-id="7eac6-113">最適化の分析情報</span><span class="sxs-lookup"><span data-stu-id="7eac6-113">Optimization insights</span></span>

<span data-ttu-id="7eac6-114">サービス マネージャーと派遣担当者は、リソースのスケジュールが効果的であり、スケジューリングの結果がビジネスの目標と一致していることを確認する責任があります。</span><span class="sxs-lookup"><span data-stu-id="7eac6-114">Service managers and dispatchers are responsible to assure resources are being effectively scheduled and also to assure scheduling results are consistent with their business goals.</span></span>

<span data-ttu-id="7eac6-115">この機能が提供する Power BI ベースの分析ダッシュボードからは数多くの分析情報が得られ、単純な実行や複数の実行にわたる最適化の要約や統計を表示することで、企業が最適化の結果を評価し、スケジューリングの目標やリソースの使用状況などを測定するのを支援します。</span><span class="sxs-lookup"><span data-stu-id="7eac6-115">This feature provides an insightful Power BI-based analytical dashboard to show optimization summarization and statistics for simple run or across multiple runs to help business evaluate optimization results, measure scheduling objectives and resource usage, and more.</span></span>

<span data-ttu-id="7eac6-116">![最適化の分析情報](media/scheduling-1.png "最適化の分析情報")</span><span class="sxs-lookup"><span data-stu-id="7eac6-116">![Optimization insights](media/scheduling-1.png "Optimization insights")</span></span>
<!-- picture -->

## <a name="optimization-objective-for-as-soon-as-possible-asap"></a><span data-ttu-id="7eac6-117">「できるだけ早く (ASAP)」の最適化目標</span><span class="sxs-lookup"><span data-stu-id="7eac6-117">Optimization objective for as soon as possible (ASAP)</span></span> 

<span data-ttu-id="7eac6-118">たまに (作業指示書などで) リソースのキャパシティがリソースの需要を超えることがあります。</span><span class="sxs-lookup"><span data-stu-id="7eac6-118">Occasionally, there might be more resource capacity than there is demand for resources (for example, work orders).</span></span> <span data-ttu-id="7eac6-119">そのような状況において、リソースの予定を完全に埋めてしまうか、緊急時や予定外の作業に備えてリソースを残しておくか、経営上の判断を求められます。</span><span class="sxs-lookup"><span data-stu-id="7eac6-119">In these circumstances, there is a business decision about whether to fully book some resources or leave resources with some capacity as a contingency for emergency or unplanned work.</span></span>

<span data-ttu-id="7eac6-120">2019 年 4 月のリリースでは、「できるだけ早く (ASAP)」という新しい目標が設定できるようになります。これにより、組織は他のスケジューリングの目標を選択して再度ランク付けすることで、一部のリソースを余裕を持って残しておくか、1 日の予定をすべて埋めてしまうか、バランスを取ることができます。</span><span class="sxs-lookup"><span data-stu-id="7eac6-120">The April '19 release enables a new objective for as soon as possible (ASAP), so that organizations can select and rerank with other scheduling objectives to balance the need to reserve some capacity with the need to keep resources busy all day.</span></span>
