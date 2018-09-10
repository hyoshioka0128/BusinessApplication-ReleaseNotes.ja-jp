---
title: "依存オプション セットの構成"
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

依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。 たとえば、**国/地域**オプション セットおよび**州**オプション セットを作成できます。 ユーザーが最初のオプション セットのドロップダウン リストで**米国**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある州だけが表示されます。 この構成がすべてのアプリで使用されるようエンティティ レベルで定義するなら、データの整合性と正確性を確保できます。

