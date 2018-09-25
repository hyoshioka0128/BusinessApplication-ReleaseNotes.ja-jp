---
title: "バックグラウンドでの位置情報の共有"
description: "バックグラウンドでの位置情報の共有"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 6bb0ba1e-1805-4cf8-bd49-7fc45cffbefd
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 5c40ff13a6805ebaeaca6fc7fabdc664bbfdee9f
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---

#  <a name="background-location-sharing"></a><span data-ttu-id="23669-103">バックグラウンドでの位置情報の共有</span><span class="sxs-lookup"><span data-stu-id="23669-103">Background location sharing</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="23669-104">技術者は、モバイル アプリケーションで現在の位置情報を共有できるようになりました。その結果、位置情報データ ストリームを Dynamics 365 for Field Service に送信してスケジュール ボードに技術者の位置情報を表示し、技術者の現在位置に基づいてイベントをトリガーできます。</span><span class="sxs-lookup"><span data-stu-id="23669-104">Our mobile application now allows for technicians to share their current locations, which will result in a location data stream getting sent to Dynamics 365 for Field Service that surfaces a technician’s location on the schedule board and allows for events to be triggered based on a technician’s current location.</span></span> <span data-ttu-id="23669-105">たとえば、技術者がサイトに着いたら、プッシュ通知を送信して技術者にステータスの更新を思い出させることができます。</span><span class="sxs-lookup"><span data-stu-id="23669-105">For example, when technicians arrive on site, a push notification can be sent to remind them to update their status.</span></span> <span data-ttu-id="23669-106">また、現在位置に基づいて技術者が作業指示書より遅れていることを検出し、近くにいる別の技術者に作業指示書を割り当て直すようなことがもきます。</span><span class="sxs-lookup"><span data-stu-id="23669-106">This will also open scenarios where we can detect that a technician is going to be late to a work order based on current location and consequently reassign the work order to another technician nearby.</span></span>

