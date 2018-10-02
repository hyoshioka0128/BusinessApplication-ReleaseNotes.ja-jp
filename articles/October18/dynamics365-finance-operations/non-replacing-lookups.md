---
title: "非置換ルックアップの動作の向上"
description: "Finance and Operations での非置換ルックアップに関して、いくつかの機能向上が行われています。"
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: bc5017cc0df74ed2071e2b77c65d62dc3cc5a198
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---

# <a name="improved-behavior-of-non-replacing-lookups"></a>非置換ルックアップの動作の向上

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Finance and Operations の一部のルックアップは*非置換*です。つまり、ルックアップから値を選択しても、フィールドの既存の値は置き換えられず、選択した値がフィールドに追加されます。 たとえば、**フィルター/並べ替えの編集**ダイアログのルックアップは、既定では非置換です。  

非置換ルックアップの動作が、次のように向上しました。 

- タイプアヘッド動作は、非置換ルックアップの場合はオフになります。 

- ルックアップが開かれた後で入力された文字のみが、ルックアップ グリッドへの配置に使用されます。

- ルックアップで選択した値は、ルックアップが開かれる前にフィールドに設定されていた内容に追加されます (つまり、ルックアップが開かされている間に入力されたすべての文字は、ルックアップから選択した値を追加すると置き換えられます)。  

- 非置換ルックアップには新しいアイコンが表示されるようになり、通常のルックアップと視覚的に区別されます。

これらの調整により、**フィルター/並べ替えの編集**ダイアログを使用したデータのフィルター処理が簡単になります。

