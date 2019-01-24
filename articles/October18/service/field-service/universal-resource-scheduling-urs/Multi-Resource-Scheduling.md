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
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 64ff44ddf43871896b6702cd6ef8a0a47be4ffd6
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---




#  <a name="multi-resource-scheduling"></a><span data-ttu-id="4425c-103">複数リソースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="4425c-103">Multi-resource scheduling</span></span>

[!include[field-service banner](../../../includes/field-service.md)]

<span data-ttu-id="4425c-104">同日のスケジュールに対してリソースのグループを動的に招集して同時に集合させます。</span><span class="sxs-lookup"><span data-stu-id="4425c-104">Dynamically assemble a group of resources to converge at the same time for intraday scheduling.</span></span> <span data-ttu-id="4425c-105">リソースをチームにまとめて、オンサイトの顧客所在地で集合したり、リモートで連携したり、施設での予定を履行したりできます。</span><span class="sxs-lookup"><span data-stu-id="4425c-105">Resources can be teamed together to meet onsite at a customer location, work together remotely, or fulfill appointments at facilities.</span></span>

- <span data-ttu-id="4425c-106">チームを招集する方法について複数の構成を検索し、要件グループに設定します。</span><span class="sxs-lookup"><span data-stu-id="4425c-106">Search across the multiple configurations of how the team can be assembled, set up on the requirement group.</span></span>
- <span data-ttu-id="4425c-107">さまざまな組み合わせ:</span><span class="sxs-lookup"><span data-stu-id="4425c-107">Mix and match:</span></span>
  - <span data-ttu-id="4425c-108">プールと個々のリソース</span><span class="sxs-lookup"><span data-stu-id="4425c-108">Pools and individual resources</span></span>
  - <span data-ttu-id="4425c-109">個人とスタッフ</span><span class="sxs-lookup"><span data-stu-id="4425c-109">Individuals and crews</span></span>
  - <span data-ttu-id="4425c-110">人、備品、設備</span><span class="sxs-lookup"><span data-stu-id="4425c-110">People, equipment, and facilities</span></span>
- <span data-ttu-id="4425c-111">リソースの空き時間と現在の確約を考慮します。</span><span class="sxs-lookup"><span data-stu-id="4425c-111">Consider resource availability and current commitments.</span></span> 
- <span data-ttu-id="4425c-112">移動時間を予測し、チームを招集して、事前に招集されたスタッフと動的にチームに加えられるスタッフの両方がお客様とオンサイトで会います。</span><span class="sxs-lookup"><span data-stu-id="4425c-112">Predict travel time and assemble a team to meet onsite with a customer both for preassembled crews and dynamically putting a team together.</span></span>
- <span data-ttu-id="4425c-113">設備 - 特定の場所に割り当てられたリソースのグループを招集します。</span><span class="sxs-lookup"><span data-stu-id="4425c-113">Facility - Assemble a group of resources staffed at a specific location.</span></span>

<span data-ttu-id="4425c-114">![チーム スケジュールのシナリオ](media/Multi-Resource-Scheduling-PPT.png "チーム スケジュールのシナリオ")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="4425c-114">![Team scheduling scenarios](media/Multi-Resource-Scheduling-PPT.png "Team scheduling scenarios")
<!-- picture --></span></span>

<span data-ttu-id="4425c-115">![リソースのチームの空き時間の検索](media/Team-Scheduling.png "チーム スケジュールのシナリオ")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="4425c-115">![Finding availability for a team of resources](media/Team-Scheduling.png "Team scheduling scenarios")
<!-- picture --></span></span>

<span data-ttu-id="4425c-116">*リソースのチームの空き時間の検索*</span><span class="sxs-lookup"><span data-stu-id="4425c-116">*Finding availability for a team of resources*</span></span>

