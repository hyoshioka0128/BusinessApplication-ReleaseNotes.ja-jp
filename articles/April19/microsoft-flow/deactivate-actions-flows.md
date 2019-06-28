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
# <a name="deactivate-actions-in-flows"></a><span data-ttu-id="ccfbb-103">フロー内のアクションを無効にする</span><span class="sxs-lookup"><span data-stu-id="ccfbb-103">Deactivate actions in flows</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="ccfbb-104">[コミュニティからのこの提案](https://powerusers.microsoft.com/t5/Flow-Ideas/activate-deactivate-actions-in-flows/idi-p/7099)で説明されているように、失敗するアクションがフローに含まれている場合があります。</span><span class="sxs-lookup"><span data-stu-id="ccfbb-104">As covered by [this suggestion from the community](https://powerusers.microsoft.com/t5/Flow-Ideas/activate-deactivate-actions-in-flows/idi-p/7099), you may sometimes have an action that’s failing in your flow.</span></span> <span data-ttu-id="ccfbb-105">しかし、そのコア タスクを実行することはフローにとって必須ではない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ccfbb-105">However, it may not be essential for the flow to perform its core tasks.</span></span> <span data-ttu-id="ccfbb-106">そこで、その特定のアクションの修正に時間を費やす代わりに、そのアクションに対して**静的な結果**を指定することができます。</span><span class="sxs-lookup"><span data-stu-id="ccfbb-106">Thus, instead of spending the time to fix that particular action you can specify **Static results** for that action.</span></span> <span data-ttu-id="ccfbb-107">これにより、残りのフローの構築とテストを続行できます。</span><span class="sxs-lookup"><span data-stu-id="ccfbb-107">This allows you to continue building out and testing the rest of your flow.</span></span> <span data-ttu-id="ccfbb-108">フロー内の他のアクションでそのアクションからのデータが必要な場合は、コネクタを呼び出す (そして失敗する) 代わりに、定義した**静的結果**が使用されます。</span><span class="sxs-lookup"><span data-stu-id="ccfbb-108">If any other action in your flow needs data from that action it will use the **Static results** you have defined, instead of calling the Connector (and failing).</span></span>
