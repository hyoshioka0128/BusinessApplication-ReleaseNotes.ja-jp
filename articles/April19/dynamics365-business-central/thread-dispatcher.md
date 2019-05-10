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
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225158"
---
# <a name="thread-dispatcher-favors-ui-threads-over-background-threads"></a><span data-ttu-id="02508-103">スレッド ディスパッチャーはバックグラウンド スレッドより UI スレッドを優先する</span><span class="sxs-lookup"><span data-stu-id="02508-103">Thread dispatcher favors UI threads over background threads</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="02508-104">Business Central Server 内のスレッド ディスパッチャーと呼ばれるコンポーネントにより、すべてのユーザー スレッド (UI タスクまたはバックグラウンド タスクに関連するもの) にサーバー上の CPU リソースが公平に分配されます。</span><span class="sxs-lookup"><span data-stu-id="02508-104">Inside the Business Central server, a component called the thread dispatcher ensures that all user threads (related to UI or background tasks) get a fair share of the CPU resources on the server.</span></span> <span data-ttu-id="02508-105">2019 年 4 月より前のリリースでは、すべてのスレッドに対して作業実行用に 50 ミリ秒のタイム スライスが与えられていました。</span><span class="sxs-lookup"><span data-stu-id="02508-105">Prior to the April 2019 release, all threads were given time slices of 50 milliseconds to execute work.</span></span> <span data-ttu-id="02508-106">多くのバックグラウンド タスクがある多いビジー状態のシステムでは、UI を提供するスレッドは短時間キューに入れられ、バックグラウンド タスクを処理するスレッドに譲ることがありました。</span><span class="sxs-lookup"><span data-stu-id="02508-106">On a busy system with many background tasks, threads serving UI will sometimes be queued for a short time and yield to threads serving background tasks.</span></span> <span data-ttu-id="02508-107">2019 年 4 月のリリースでは、サーバーで利用可能なコアより UI スレッドの方が多い場合を除き (この場合は、ラウンドロビンの優先順位で実行されます)、実行する必要があるバックグラウンド スレッドのために UI スレッドがスリープ状態にされることはなくなります。</span><span class="sxs-lookup"><span data-stu-id="02508-107">In the April 2019 release, UI threads will not be put to sleep because of background threads that need to run, unless there are more UI threads than cores available on the server, in which case they will run in a round-robin priority.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="02508-108">フィードバック</span><span class="sxs-lookup"><span data-stu-id="02508-108">Tell us what you think</span></span>
<span data-ttu-id="02508-109">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="02508-109">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="02508-110">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="02508-110">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
