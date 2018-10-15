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
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: 675d9136f9d13c43bd36aa00a5c2da1f89242edf
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="configure-dependent-option-sets-public-preview"></a>依存オプション セットの構成 (パブリック プレビュー)


[!include[banner](../../includes/banner.md)]

依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。 As an example, you can create a **Country/region** option set and a **States** option set. If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region. You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.

