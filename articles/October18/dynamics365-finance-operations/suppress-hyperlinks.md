---
title: "ハイパーリンクの抑制"
description: "開発者はコントロールのハイパーリンクを抑制できます"
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 76aaf7ff6926e396df13155a5df8bd2013d407c2
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---

# <a name="suppressing-hyperlinks"></a><span data-ttu-id="dd11b-103">ハイパーリンクの抑制</span><span class="sxs-lookup"><span data-stu-id="dd11b-103">Suppressing hyperlinks</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="dd11b-104">開発者は、**EnableFormRef** プロパティを **No** に設定することによって、フォーム コントロールのハイパーリンクを抑制できます。</span><span class="sxs-lookup"><span data-stu-id="dd11b-104">Developers are able to suppress hyperlinks on form controls by setting the **EnableFormRef** property to **No**.</span></span> <span data-ttu-id="dd11b-105">このプロパティは、フォームとフォーム拡張機能の両方で設定できます。</span><span class="sxs-lookup"><span data-stu-id="dd11b-105">This property can be set on both forms and form extensions.</span></span> <span data-ttu-id="dd11b-106">ハイパーリンクを抑制すると、右クリック コンテキスト メニューの対応する**詳細の表示**オプションも表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="dd11b-106">When a hyperlink is suppressed, the corresponding **View details** option in the right-click context menu is also suppressed.</span></span> 
 
<span data-ttu-id="dd11b-107">現在は、ユーザーがいずれかのハイパーリンクをクリックすると、ナビゲーションが試行され、開く対象のフォームがないと、エラー メッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="dd11b-107">Currently when users click on some hyperlinks, it results in an attempted navigation and then an error message, as there is no target form to open.</span></span> <span data-ttu-id="dd11b-108">これらのシナリオでハイパーリンクを抑制すると、まぎらわしいハイパーリンクがなくなり、ユーザー エクスペリエンスが改善されます。</span><span class="sxs-lookup"><span data-stu-id="dd11b-108">Suppressing hyperlinks in these scenarios will improve the user experience by removing these confusing hyperlinks.</span></span>  

