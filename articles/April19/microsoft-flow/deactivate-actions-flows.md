---
title: フロー内のアクションを無効にする
description: フロー内の特定のアクションを無効にできます。これは、失敗を分離してフローのテストを続けるのに役立ちます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/06/2019
ms.assetid: 5387bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 7c777c0274e1c97d18b640e350e7c7ddb936a984
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621569"
---
# <a name="deactivate-actions-in-flows"></a>フロー内のアクションを無効にする

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

[コミュニティからのこの提案](https://powerusers.microsoft.com/t5/Flow-Ideas/activate-deactivate-actions-in-flows/idi-p/7099)で説明されているように、失敗するアクションがフローに含まれている場合があります。 しかし、そのコア タスクを実行することはフローにとって必須ではない可能性があります。 そこで、その特定のアクションの修正に時間を費やす代わりに、そのアクションに対して**静的な結果**を指定することができます。 これにより、残りのフローの構築とテストを続行できます。 フロー内の他のアクションでそのアクションからのデータが必要な場合は、コネクタを呼び出す (そして失敗する) 代わりに、定義した**静的結果**が使用されます。
