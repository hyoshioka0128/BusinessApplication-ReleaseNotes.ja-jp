---
title: イベント ランタイムの最適化
description: イベント ランタイムの最適化
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 75431586a629ec25bd5399789e1f242fa7287798
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878727"
---
# <a name="event-runtime-optimization"></a><span data-ttu-id="be659-103">イベント ランタイムの最適化</span><span class="sxs-lookup"><span data-stu-id="be659-103">Event runtime optimization</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="be659-104">Business Central Server 内のイベント サブシステムは、AL 拡張プログラミング モデルのランタイムの中核をなすものです。</span><span class="sxs-lookup"><span data-stu-id="be659-104">The event subsystem inside the Business Central server is the core of the runtime for the AL extension programming model.</span></span> <span data-ttu-id="be659-105">2019 年 4 月のリリースでは、このサブシステムが 1.5 - 2.5 倍高速になるように最適化されました。</span><span class="sxs-lookup"><span data-stu-id="be659-105">In the April 2019 release, we have optimized the subsystem so that it is now 1.5 to 2.5 times faster.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="be659-106">フィードバック</span><span class="sxs-lookup"><span data-stu-id="be659-106">Tell us what you think</span></span>
<span data-ttu-id="be659-107">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="be659-107">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="be659-108">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="be659-108">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
