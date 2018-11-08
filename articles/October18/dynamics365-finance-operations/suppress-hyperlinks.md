---
title: "ハイパーリンクの抑制"
description: "開発者はコントロールのハイパーリンクを抑制できます"
author: jasongre
manager: AnnBe
ms.date: 11/08/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 76aaf7ff6926e396df13155a5df8bd2013d407c2
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---

# <a name="suppressing-hyperlinks"></a>ハイパーリンクの抑制

開発者は、**EnableFormRef** プロパティを **No** に設定することによって、フォーム コントロールのハイパーリンクを抑制できます。 このプロパティは、フォームとフォーム拡張機能の両方で設定できます。 ハイパーリンクを抑制すると、右クリック コンテキスト メニューの対応する**詳細の表示**オプションも表示されなくなります。 
 
現在は、ユーザーがいずれかのハイパーリンクをクリックすると、ナビゲーションが試行され、開く対象のフォームがないと、エラー メッセージが表示されます。 これらのシナリオでハイパーリンクを抑制すると、まぎらわしいハイパーリンクがなくなり、ユーザー エクスペリエンスが改善されます。  

