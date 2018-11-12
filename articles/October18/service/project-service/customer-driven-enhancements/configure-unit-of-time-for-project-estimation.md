---
title: "プロジェクト タスクでの作業を見積もるための時間単位の構成"
description: "構成可能な時間単位を使用して、プロジェクト タスクでの工数を見積もります"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 3d9c093dc2928be990b3737ca3d94d61a485c9a9
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a><span data-ttu-id="b40df-103">プロジェクト タスクでの作業を見積もるための時間単位の構成</span><span class="sxs-lookup"><span data-stu-id="b40df-103">Configure a unit of time for estimating work on project tasks</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="b40df-104">Project Service では、プロジェクト タスクでの工数見積の時間単位として*時間*だけが使用されます。</span><span class="sxs-lookup"><span data-stu-id="b40df-104">Project Service uses *hour* as the only time unit for estimating work effort on a project task.</span></span> <span data-ttu-id="b40df-105">世界の多くの領域では「作業日数」で見積が行われており、一般的な 1 作業日の時間数は国や地域ごとに独自の定義があります。</span><span class="sxs-lookup"><span data-stu-id="b40df-105">In many regions across the world, estimation is done in “work days,” with each country or region having its own definition of how many hours are in a typical work day.</span></span> <span data-ttu-id="b40df-106">したがって、プロジェクトの納品を所有する部署に応じて、プロジェクトでの見積の単位の既定値を、その部署における作業日の定義に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b40df-106">Therefore, depending on which division owns the delivery of the project, the unit of estimation on the project must default to that division's definition of work day.</span></span> 

<span data-ttu-id="b40df-107">この機能により、各組織単位は作業カレンダーを識別し、作業の見積に対する優先単位を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b40df-107">With this feature, each organizational unit will be able to identify a working calendar and specify a preferred unit for estimating effort.</span></span> <span data-ttu-id="b40df-108">その組織単位によって所有されるすべてのプロジェクトは、その作業カレンダーと作業見積単位を使用します。</span><span class="sxs-lookup"><span data-stu-id="b40df-108">All projects owned by that that organizational unit will then use that working calendar and that unit for estimating effort.</span></span> 

<span data-ttu-id="b40df-109">例: Contoso Scotland での 1 日の作業時間が 7.5 時間で、優先される工数見積単位が「スコットランド作業日」である場合、Contoso Scotland が所有するすべてのプロジェクトでは、見積の単位としてスコットランド作業日が使用され、その見積を時間数に変換するには 7.5 の倍数が使用されます。</span><span class="sxs-lookup"><span data-stu-id="b40df-109">Consider an example: If Contoso Scotland works 7.5-hour days and its preferred unit for estimating effort is a “Scottish working day,” then all projects owned by Contoso Scotland will use Scottish working day as the unit of estimation, and the multiplier of 7.5 will be used to translate that estimate into hours.</span></span> 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a><span data-ttu-id="b40df-110">組織単位での時間単位とカレンダーのセットアップ</span><span class="sxs-lookup"><span data-stu-id="b40df-110">Setting up time unit and calendar on the organizational unit</span></span>

<span data-ttu-id="b40df-111">![組織単位での時間単位とカレンダーのセットアップ](media/Setting-time-unit-on-the-orgunit.png "組織単位での時間単位とカレンダーのセットアップ")</span><span class="sxs-lookup"><span data-stu-id="b40df-111">![Setting up time unit and calendar on the Org. Unit](media/Setting-time-unit-on-the-orgunit.png "Setting up time unit and calendar on the organizational unit")</span></span>

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a><span data-ttu-id="b40df-112">組織単位での設定からの、プロジェクトの既定の時間単位とカレンダーの設定</span><span class="sxs-lookup"><span data-stu-id="b40df-112">Defaulting time unit and calendar on the project from the settings on the organizational unit</span></span>

<span data-ttu-id="b40df-113">![プロジェクトの既定の時間単位とカレンダーの設定](media/Defaulting-time-unit-calendar-on-the-project.png "プロジェクトの既定の時間単位とカレンダーの設定")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="b40df-113">![Defaulting time unit and calendar on the project](media/Defaulting-time-unit-calendar-on-the-project.png "Defaulting time unit and calendar on the project")
<!-- Picture 2 --></span></span>

