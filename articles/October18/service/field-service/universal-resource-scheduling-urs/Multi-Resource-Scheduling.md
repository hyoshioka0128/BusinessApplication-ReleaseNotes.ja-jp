---
title: "複数リソースのスケジューリング"
description: "同日のスケジュールに対してリソースのグループを動的に招集して同時に集合させます"
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 64b1bac2d2aedc375f04e9f73ae8532f727977a3
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---




#  <a name="multi-resource-scheduling"></a><span data-ttu-id="ed8ae-103">複数リソースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="ed8ae-103">Multi-resource scheduling</span></span>

[!include[field-service banner](../../../includes/field-service.md)]

<span data-ttu-id="ed8ae-104">同日のスケジュールに対してリソースのグループを動的に招集して同時に集合させます。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-104">Dynamically assemble a group of resources to converge at the same time for intraday scheduling.</span></span> <span data-ttu-id="ed8ae-105">リソースをチームにまとめて、オンサイトの顧客所在地で集合したり、リモートで連携したり、施設での予定を履行したりできます。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-105">Resources can be teamed together to meet onsite at a customer location, work together remotely, or fulfill appointments at facilities.</span></span>

* <span data-ttu-id="ed8ae-106">チームを招集する方法について複数の構成を検索し、要件グループに設定します。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-106">Search across the multiple configurations of how the team can be assembled, set up on the requirement group.</span></span>
* <span data-ttu-id="ed8ae-107">さまざまな組み合わせ:</span><span class="sxs-lookup"><span data-stu-id="ed8ae-107">Mix and match:</span></span>
    * <span data-ttu-id="ed8ae-108">プールと個々のリソース</span><span class="sxs-lookup"><span data-stu-id="ed8ae-108">Pools and individual resources</span></span>
    * <span data-ttu-id="ed8ae-109">個人とスタッフ</span><span class="sxs-lookup"><span data-stu-id="ed8ae-109">Individuals and crews</span></span>
    * <span data-ttu-id="ed8ae-110">人、備品、設備</span><span class="sxs-lookup"><span data-stu-id="ed8ae-110">People, equipment, and facilities</span></span>
* <span data-ttu-id="ed8ae-111">リソースの空き時間と現在の確約を考慮します。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-111">Consider resource availability and current commitments.</span></span> 
* <span data-ttu-id="ed8ae-112">移動時間を予測し、チームを招集して、事前に招集されたスタッフと動的にチームに加えられるスタッフの両方がお客様とオンサイトで会います。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-112">Predict travel time and assemble a team to meet onsite with a customer both for preassembled crews and dynamically putting a team together.</span></span>
* <span data-ttu-id="ed8ae-113">設備 - 特定の場所に割り当てられたリソースのグループを招集します。</span><span class="sxs-lookup"><span data-stu-id="ed8ae-113">Facility - Assemble a group of resources staffed at a specific location.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="ed8ae-114">![](media/Multi-Resource-Scheduling-PPT.png "チーム スケジュールのシナリオ")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="ed8ae-114">![](media/Multi-Resource-Scheduling-PPT.png "Team scheduling scenarios")
<!-- picture --></span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="ed8ae-115">![](media/Team-Scheduling.png "チーム スケジュールのシナリオ")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="ed8ae-115">![](media/Team-Scheduling.png "Team scheduling scenarios")
<!-- picture --></span></span>

<span data-ttu-id="ed8ae-116">*リソースのチームの空き時間の検索*</span><span class="sxs-lookup"><span data-stu-id="ed8ae-116">*Finding availability for a team of resources*</span></span>

