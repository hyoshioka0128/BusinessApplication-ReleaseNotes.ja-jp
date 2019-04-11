---
title: 依存オプション セットの構成
description: 依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。
author: matthewbolanos
ms.reviewer: anneta
ms.date: 02/19/2019
ms.assetid: 796b8de6-9314-e911-a986-000d3a137063
ms.topic: article
ms.service: business-applications
ms.author: mabolan
audience: Power user
ms.openlocfilehash: e06c548a7606fcd6ab1fae29146001d36fb3b9e9
ms.sourcegitcommit: ca3b94f829721c2ba02b25134536a58babed2d2b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/27/2019
ms.locfileid: "900720"
---
# <a name="configure-dependent-option-sets-public-preview"></a><span data-ttu-id="8a12b-103">依存オプション セットの構成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="8a12b-103">Configure dependent option sets (Public Preview)</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="8a12b-104">依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。</span><span class="sxs-lookup"><span data-stu-id="8a12b-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="8a12b-105">たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8a12b-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="8a12b-106">ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。</span><span class="sxs-lookup"><span data-stu-id="8a12b-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="8a12b-107">この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="8a12b-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

