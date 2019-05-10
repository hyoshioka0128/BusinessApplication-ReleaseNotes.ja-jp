---
title: 依存オプション セットの構成
description: 依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。
author: matthewbolanos
ms.reviewer: anneta
ms.date: 04/14/2019
ms.assetid: 2387bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: mabolan
audience: Power user
ms.openlocfilehash: e2309b95dbc1c78315a33ca36e5a33e122a60a0a
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446104"
---
# <a name="configure-dependent-option-sets-public-preview"></a><span data-ttu-id="9b53d-103">依存オプション セットの構成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="9b53d-103">Configure dependent option sets (Public Preview)</span></span>

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="9b53d-104">依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。</span><span class="sxs-lookup"><span data-stu-id="9b53d-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="9b53d-105">たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。</span><span class="sxs-lookup"><span data-stu-id="9b53d-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="9b53d-106">ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。</span><span class="sxs-lookup"><span data-stu-id="9b53d-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="9b53d-107">この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="9b53d-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>

