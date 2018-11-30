---
title: "依存オプション セットの構成"
description: "依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。"
author: matthewbolanos
manager: KVivek
ms.date: 11/20/2018
ms.assetid: 641c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mabolan
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 47474939488d1eb295a7da01faa359c0f5859a37
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="configure-dependent-option-sets-public-preview"></a>依存オプション セットの構成 (パブリック プレビュー)


[!include[banner](../../includes/banner.md)]

依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。 たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。 ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。 この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。

