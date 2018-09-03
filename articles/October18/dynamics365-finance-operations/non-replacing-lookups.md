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

# <a name="improved-behavior-of-non-replacing-lookups"></a><span data-ttu-id="a00e9-103">非置換ルックアップの動作の向上</span><span class="sxs-lookup"><span data-stu-id="a00e9-103">Improved behavior of non-replacing lookups</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="a00e9-104">Finance and Operations の一部のルックアップは*非置換*です。つまり、ルックアップから値を選択しても、フィールドの既存の値は置き換えられず、選択した値がフィールドに追加されます。</span><span class="sxs-lookup"><span data-stu-id="a00e9-104">Some lookups in Finance and Operations are *non-replacing*, meaning that when a value is selected from the lookup, it doesn’t replace what was already in the field, but instead it appends the selected value into the field.</span></span> <span data-ttu-id="a00e9-105">たとえば、**フィルター/並べ替えの編集**ダイアログのルックアップは、既定では非置換です。</span><span class="sxs-lookup"><span data-stu-id="a00e9-105">As an example, the lookups in the **Advanced filter/sort** dialog are non-replacing by default.</span></span>  

<span data-ttu-id="a00e9-106">非置換ルックアップの動作が、次のように向上しました。</span><span class="sxs-lookup"><span data-stu-id="a00e9-106">The behavior of non-replacing lookups has been improved in the following ways:</span></span> 
- <span data-ttu-id="a00e9-107">タイプアヘッド動作は、非置換ルックアップの場合はオフになります。</span><span class="sxs-lookup"><span data-stu-id="a00e9-107">Type-ahead behavior has been turned off for non-replacing lookups.</span></span> 
- <span data-ttu-id="a00e9-108">ルックアップが開かれた後で入力された文字のみが、ルックアップ グリッドへの配置に使用されます。</span><span class="sxs-lookup"><span data-stu-id="a00e9-108">Only characters typed after the lookup has been opened are used to position in the lookup grid.</span></span>
- <span data-ttu-id="a00e9-109">ルックアップで選択した値は、ルックアップが開かれる前にフィールドに設定されていた内容に追加されます (つまり、ルックアップが開かされている間に入力されたすべての文字は、ルックアップから選択した値を追加すると置き換えられます)。</span><span class="sxs-lookup"><span data-stu-id="a00e9-109">The selected value from the lookup is appended to what was in the field before the lookup was opened (that is, any characters typed while the lookup was open are replaced when appending the selected value from the lookup).</span></span>  
- <span data-ttu-id="a00e9-110">非置換ルックアップには新しいアイコンが表示されるようになり、通常のルックアップと視覚的に区別されます。</span><span class="sxs-lookup"><span data-stu-id="a00e9-110">A new icon now appears on non-replacing lookups to visually differentiate them from regular lookups.</span></span>

<span data-ttu-id="a00e9-111">これらの調整により、**フィルター/並べ替えの編集**ダイアログを使用したデータのフィルター処理が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="a00e9-111">These adjustments make it easier for users to filter data using the **Advanced filter/sort** dialog.</span></span>

