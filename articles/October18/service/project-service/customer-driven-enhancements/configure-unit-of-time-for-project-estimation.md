---
title: プロジェクト タスクでの作業を見積もるための時間単位の構成
description: 構成可能な時間単位を使用して、プロジェクト タスクでの工数を見積もります
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: 3d9c093dc2928be990b3737ca3d94d61a485c9a9
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199665"
---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a>プロジェクト タスクでの作業を見積もるための時間単位の構成

[!include[project-service banner](../../../includes/project-service.md)]




Project Service では、プロジェクト タスクでの工数見積の時間単位として*時間*だけが使用されます。 世界の多くの領域では「作業日数」で見積が行われており、一般的な 1 作業日の時間数は国や地域ごとに独自の定義があります。 したがって、プロジェクトの納品を所有する部署に応じて、プロジェクトでの見積の単位の既定値を、その部署における作業日の定義に設定する必要があります。 

この機能により、各組織単位は作業カレンダーを識別し、作業の見積に対する優先単位を指定できます。 その組織単位によって所有されるすべてのプロジェクトは、その作業カレンダーと作業見積単位を使用します。 

例: Contoso Scotland での 1 日の作業時間が 7.5 時間で、優先される工数見積単位が「スコットランド作業日」である場合、Contoso Scotland が所有するすべてのプロジェクトでは、見積の単位としてスコットランド作業日が使用され、その見積を時間数に変換するには 7.5 の倍数が使用されます。 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a>組織単位での時間単位とカレンダーのセットアップ

![組織単位での時間単位とカレンダーのセットアップ](media/Setting-time-unit-on-the-orgunit.png "組織単位での時間単位とカレンダーのセットアップ")

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a>組織単位での設定からの、プロジェクトの既定の時間単位とカレンダーの設定

![プロジェクトの既定の時間単位とカレンダーの設定](media/Defaulting-time-unit-calendar-on-the-project.png "プロジェクトの既定の時間単位とカレンダーの設定")
<!-- Picture 2 -->
