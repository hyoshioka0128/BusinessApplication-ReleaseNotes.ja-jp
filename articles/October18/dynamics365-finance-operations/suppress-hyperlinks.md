---
title: ハイパーリンクの抑制
description: 開発者はコントロールのハイパーリンクを抑制できます
author: jasongre
manager: AnnBe
ms.date: 11/08/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: developer
ms.openlocfilehash: b47a7ced56943263e3795b860770d6b988a806e8
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199650"
---
# <a name="suppressing-hyperlinks"></a>ハイパーリンクの抑制

開発者は、**EnableFormRef** プロパティを **No** に設定することによって、フォーム コントロールのハイパーリンクを抑制できます。 このプロパティは、フォームとフォーム拡張機能の両方で設定できます。 ハイパーリンクを抑制すると、右クリック コンテキスト メニューの対応する**詳細の表示**オプションも表示されなくなります。 
 
現在は、ユーザーがいずれかのハイパーリンクをクリックすると、ナビゲーションが試行され、開く対象のフォームがないと、エラー メッセージが表示されます。 これらのシナリオでハイパーリンクを抑制すると、まぎらわしいハイパーリンクがなくなり、ユーザー エクスペリエンスが改善されます。  
