---
title: "依存オプション セットの構成"
description: "依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。"
author: matthewbolanos
ms.reviewer: anneta
ms.date: 01/10/2019
ms.assetid: 641c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mabolan
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 9f8ad56cb1f4ec5ae14e890c656573e917dcd1a8
ms.openlocfilehash: 936b47e4464c41e9de3c1fbcb2d812d55b1f5e0b
ms.contentlocale: ja-jp
ms.lasthandoff: 01/25/2019

---
# <a name="configure-dependent-option-sets-public-preview"></a><span data-ttu-id="2dcb6-103">依存オプション セットの構成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="2dcb6-103">Configure dependent option sets (Public Preview)</span></span>


[!include[powerapps banner](../includes/powerapps.md)]

<span data-ttu-id="2dcb6-104">依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。</span><span class="sxs-lookup"><span data-stu-id="2dcb6-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="2dcb6-105">たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。</span><span class="sxs-lookup"><span data-stu-id="2dcb6-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="2dcb6-106">ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2dcb6-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="2dcb6-107">この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="2dcb6-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

