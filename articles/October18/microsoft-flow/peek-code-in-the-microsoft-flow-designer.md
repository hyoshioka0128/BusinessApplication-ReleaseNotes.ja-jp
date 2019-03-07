---
title: Microsoft Flow デザイナーでのコードのプレビュー
description: Microsoft Flow デザイナーでアクションの JSON コードをプレビューします
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/04/2019
ms.assetid: c4ffc9c8-c521-e911-a966-000d3a1d531d
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 55f39e856c798c7e8406cc2ba64680012288819c
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391317"
---
# <a name="peek-code-in-the-microsoft-flow-designer"></a>Microsoft Flow デザイナーでのコードのプレビュー


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

多くの異なる入力がある大きなアクションを実行している場合、フローからコネクタに送信される内容を正確に理解するのが難しい場合があります。 Flow デザイナーのすべてのトリガーとアクションの `...` メニューに、新しい**コードのプレビュー** オプションが追加されています。 

![コードのプレビュー メニュー項目](media/peek_code_01.png "コードのプレビュー メニュー項目")

このオプションを選択すると、アクションの完全な JSON 表現が表示されます。 これには、アクションへのすべての入力 (直接入力したテキストなど) および使用されている式が含まれます。 たとえば、ここで式を選択して、動的コンテンツ式エディターに貼り付けることができます。 これはまた、期待するデータがフロー内に存在することを確認するための方法にもなります。

![コード プレビュー ビュー](media/peek_code_02.png "コード プレビュー ビュー")

通常のアクション ビューに戻るには、アクションの下部にある**完了**を選択します。
