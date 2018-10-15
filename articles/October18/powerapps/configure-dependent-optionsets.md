---
title: Configure dependent option sets
description: "依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。"
author: clwesene
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 641c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: 47474939488d1eb295a7da01faa359c0f5859a37
ms.contentlocale: ja-jp
ms.lasthandoff: 09/10/2018

---
# <a name="configure-dependent-option-sets-public-preview"></a><span data-ttu-id="0c9b2-103">依存オプション セットの構成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="0c9b2-103">Configure dependent option sets (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="0c9b2-104">依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。</span><span class="sxs-lookup"><span data-stu-id="0c9b2-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="0c9b2-105">As an example, you can create a **Country/region** option set and a **States** option set.</span><span class="sxs-lookup"><span data-stu-id="0c9b2-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="0c9b2-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span><span class="sxs-lookup"><span data-stu-id="0c9b2-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="0c9b2-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span><span class="sxs-lookup"><span data-stu-id="0c9b2-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

