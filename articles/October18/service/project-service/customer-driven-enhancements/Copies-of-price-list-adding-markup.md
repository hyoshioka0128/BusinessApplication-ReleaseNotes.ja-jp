---
title: "利幅率を追加することで価格表のコピーを作成する機能"
description: "目標価格表の価格を上げたり下げたりできるよう、価格表をコピーするときに利幅率を追加します。"
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
ms.openlocfilehash: 557a26f9185f09b2ab5f5e207b7c5c3c95ae1991
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="ability-to-make-copies-of-price-lists-by-adding-a-markup-percentage"></a><span data-ttu-id="059ec-103">利幅率を追加することで価格表のコピーを作成する機能</span><span class="sxs-lookup"><span data-stu-id="059ec-103">Ability to make copies of price lists by adding a markup percentage</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="059ec-104">Project Service では、簡単にデータを作成および保守できるように、価格表のコピーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="059ec-104">Project Service allows you to make copies of price lists for ease of data creation and maintenance.</span></span> <span data-ttu-id="059ec-105">現時点では、同じ通貨と時間単位で価格表のコピーを作成すること、またはある通貨と時間単位の価格表を別の通貨または時間単位を使用してコピーを作成することにより変換することができます。</span><span class="sxs-lookup"><span data-stu-id="059ec-105">You're currently able to make copies of price lists in the same currency and time unit, or convert a price list in one currency and time unit to another by making a copy, using a different currency or time unit.</span></span> 

<span data-ttu-id="059ec-106">これらのシナリオでは、ソースの通貨および時間単位をターゲットに指定されている通貨および時間単位に変換することによって、新しい価格表が作成されます。</span><span class="sxs-lookup"><span data-stu-id="059ec-106">In these scenarios, the new price list is created by converting the currency and/or the time unit on the source to the currency and/or time unit specified for the target.</span></span> <span data-ttu-id="059ec-107">この機能が強化され、ユーザーは古い価格表から新しい価格表を作成するときに、利幅率を指定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="059ec-107">This feature goes one step further by allowing users to specify a markup percentage when creating a new price list from an old one.</span></span> <span data-ttu-id="059ec-108">これは、インフレ価格変化を適用することによって将来の期間の新しい価格表を作成するときに便利です。</span><span class="sxs-lookup"><span data-stu-id="059ec-108">This will be useful when creating new price lists for a future period by applying inflationary price changes.</span></span>

