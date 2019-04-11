---
title: スレッド ディスパッチャーはバックグラウンド スレッドより UI スレッドを優先する
description: スレッド ディスパッチャーはバックグラウンド スレッドより UI スレッドを優先する
author: KennieNP
ms.reviewer: edupont
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: f02b8fd756e1f2c93c159ccf3bb18132cae6f89d
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878730"
---
# <a name="thread-dispatcher-favors-ui-threads-over-background-threads"></a>スレッド ディスパッチャーはバックグラウンド スレッドより UI スレッドを優先する

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Business Central Server 内のスレッド ディスパッチャーと呼ばれるコンポーネントにより、すべてのユーザー スレッド (UI タスクまたはバックグラウンド タスクに関連するもの) にサーバー上の CPU リソースが公平に分配されます。 2019 年 4 月より前のリリースでは、すべてのスレッドに対して作業実行用に 50 ミリ秒のタイム スライスが与えられていました。 多くのバックグラウンド タスクがある多いビジー状態のシステムでは、UI を提供するスレッドは短時間キューに入れられ、バックグラウンド タスクを処理するスレッドに譲ることがありました。 2019 年 4 月のリリースでは、サーバーで利用可能なコアより UI スレッドの方が多い場合を除き (この場合は、ラウンドロビンの優先順位で実行されます)、実行する必要があるバックグラウンド スレッドのために UI スレッドがスリープ状態にされることはなくなります。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
