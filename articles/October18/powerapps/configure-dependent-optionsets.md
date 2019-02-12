---
title: 依存オプション セットの構成
description: 依存オプション セットを構成すると、アプリでカスケード ドロップダウンを提供し、ドロップダウン間で簡単なデータ検証を行えます。
author: matthewbolanos
ms.reviewer: anneta
ms.date: 01/10/2019
ms.assetid: 641c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mabolan
audience: Power user
ms.openlocfilehash: 936b47e4464c41e9de3c1fbcb2d812d55b1f5e0b
ms.sourcegitcommit: abbfbdaff6d71a53e5dd36fecb6673080c49e5d6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/26/2019
ms.locfileid: "290044"
---
# <a name="configure-dependent-option-sets-public-preview"></a>依存オプション セットの構成 (パブリック プレビュー)


[!include[powerapps banner](../includes/powerapps.md)]

依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。 たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。 ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。 この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。
