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
# <a name="configure-dependent-option-sets-public-preview"></a>依存オプション セットの構成 (パブリック プレビュー)

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

依存オプション セットを作成することで、オプション セット間で簡単にルールを設定して、選択した値の整合性を保てます。 たとえば、**国/地域**オプション セットおよび**都道府県**オプション セットを作成できます。 ユーザーが最初のオプション セットのドロップダウン リストで**日本**を選択した場合、2 番目のオプション セットのドロップダウン リストには、その国/地域にある都道府県だけが表示されます。 この構成がすべてのアプリで使用されるようエンティティ レベルで定義することで、データの整合性と正確性を確保できます。

