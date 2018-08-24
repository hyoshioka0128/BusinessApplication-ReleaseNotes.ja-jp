---
title: "依存オプション セットの構成"
description: "依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。"
author: clwesene
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 22c0a725d5f46f6ec89fafeb05ea1b00fb183fc1
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="configure-dependent-option-sets"></a>依存オプション セットの構成

[!include[powerapps banner](../includes/powerapps.md)]




依存オプション セットを作成することで、オプション セット間で簡単に規則を設定して、選択した値の整合性を保てます。 たとえば、**国/地域**オプション セットおよび**州**オプション セットを作成できます。 ユーザーが最初のオプション セットのドロップダウン リストで**米国**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある州だけが表示されます。 この構成がすべてのアプリで使用されるようエンティティ レベルで定義するなら、データの整合性と正確性を確保できます。

