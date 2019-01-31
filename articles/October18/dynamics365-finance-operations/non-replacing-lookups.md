---
title: 非置換ルックアップの動作の向上
description: Finance and Operations での非置換ルックアップに関して、いくつかの機能向上が行われています。
author: jasongre
manager: AnnBe
ms.date: 11/08/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.openlocfilehash: e96d971401afdd4b178c6d5c6a1be74dbf92a7bd
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199730"
---
# <a name="improved-behavior-of-non-replacing-lookups"></a>非置換ルックアップの動作の向上

Finance and Operations の一部のルックアップは*非置換*です。つまり、ルックアップから値を選択しても、フィールドの既存の値は置き換えられず、選択した値がフィールドに追加されます。 たとえば、**フィルター/並べ替えの編集**ダイアログのルックアップは、既定では非置換です。  

非置換ルックアップの動作が、次のように向上しました。 

- タイプアヘッド動作は、非置換ルックアップの場合はオフになります。 

- ルックアップが開かれた後で入力された文字のみが、ルックアップ グリッドへの配置に使用されます。

- ルックアップで選択した値は、ルックアップが開かれる前にフィールドに設定されていた内容に追加されます (つまり、ルックアップが開かされている間に入力されたすべての文字は、ルックアップから選択した値を追加すると置き換えられます)。  

- 非置換ルックアップには新しいアイコンが表示されるようになり、通常のルックアップと視覚的に区別されます。

これらの調整により、**フィルター/並べ替えの編集**ダイアログを使用したデータのフィルター処理が簡単になります。
