---
title: 自動フローによる CDS for Apps でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 1f7458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 0018849723c6214f53a49660357b06a4b137fe49
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210479"
---
# <a name="automated-flows-support-batch-operations-in-cds-for-apps"></a><span data-ttu-id="07fbd-103">自動フローによる CDS for Apps でのバッチ操作のサポート</span><span class="sxs-lookup"><span data-stu-id="07fbd-103">Automated flows support batch operations in CDS for Apps</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="07fbd-104">Common Data Service (CDS) for Apps で一度に多くのアクションを実行したい場合 (100 個の異なるレコードを一度に挿入するなど)、通常であれば Microsoft Flow によって CDS for Apps に対する多くの異なる呼び出しが行われます。</span><span class="sxs-lookup"><span data-stu-id="07fbd-104">If you want to perform many different actions in Common Data Service (CDS) for Apps at once—such as inserting 100 different records at once—normally Microsoft Flow will make many different calls to CDS for Apps.</span></span> <span data-ttu-id="07fbd-105">これでもうまくいきますが、そのようなフローを実行すると長い時間がかかることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="07fbd-105">Although this works fine, it can often take a long time for such a flow to run.</span></span>

<span data-ttu-id="07fbd-106">このリリースでは、フローに**バッチ** スコープを追加して、すべての異なる操作を CDS for Apps の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。</span><span class="sxs-lookup"><span data-stu-id="07fbd-106">Now, you can add a **Batch** scope to your flows that will group all these different operations into a single call to CDS for Apps to dramatically improve performance.</span></span> <span data-ttu-id="07fbd-107">これを使用するには、**Common Data Service** コネクタで**バッチ**を探します。</span><span class="sxs-lookup"><span data-stu-id="07fbd-107">To use this, search for **Batch** under the **Common Data Service** connector.</span></span> <span data-ttu-id="07fbd-108">このスコープを Microsoft Flow デザイナーに追加した後は、任意の CDS for Apps アクションをその中に追加できます。</span><span class="sxs-lookup"><span data-stu-id="07fbd-108">Once you add this scope into the Microsoft Flow designer, you can then add any CDS for Apps action inside of it.</span></span> <span data-ttu-id="07fbd-109">バッチ スコープに他のサービスのアクションを含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="07fbd-109">You cannot include actions for other services inside of a Batch scope.</span></span> <span data-ttu-id="07fbd-110">そのような場合は、バッチの前後で他のアクションを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07fbd-110">Instead, you will need to perform those other actions before or after the Batch.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="07fbd-111">![フローのバッチ スコープ](media/BatchOperations-1.png "フローのバッチ スコープ")</span><span class="sxs-lookup"><span data-stu-id="07fbd-111">![Batch scope in Flow](media/BatchOperations-1.png "Batch scope in Flow")</span></span>

<span data-ttu-id="07fbd-112">バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="07fbd-112">Remember, batch requests are best used when performing operations on entities that aren’t associated with each other.</span></span> <span data-ttu-id="07fbd-113">取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。</span><span class="sxs-lookup"><span data-stu-id="07fbd-113">Some operations on associated records, such as getting the primary contact of an account, can be performed in a single operation without using batching.</span></span>
