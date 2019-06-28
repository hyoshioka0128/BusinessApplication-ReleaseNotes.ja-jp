---
title: 自動フローによる Common Data Service でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/06/2019
ms.assetid: ff86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 3f1a1bf012b4d064cfca0038fa074a4fbad50f38
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621657"
---
# <a name="automated-flows-support-batch-operations-in-common-data-service"></a><span data-ttu-id="4f183-103">自動フローによる Common Data Service でのバッチ操作のサポート</span><span class="sxs-lookup"><span data-stu-id="4f183-103">Automated flows support batch operations in Common Data Service</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="4f183-104">Common Data Service で一度に多くのアクションを実行したい場合 (100 個の異なるレコードを一度に挿入するなど)、通常であれば Microsoft Flow によって Common Data Service に対する多くの異なる呼び出しが行われます。</span><span class="sxs-lookup"><span data-stu-id="4f183-104">If you want to perform many different actions in Common Data Service at once, such as inserting 100 different records at once, normally Microsoft Flow will make many different calls to Common Data Service.</span></span> <span data-ttu-id="4f183-105">これでもうまくいきますが、そのようなフローを実行すると長い時間がかかることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="4f183-105">Although this works fine, it can often take a long time for such a flow to run.</span></span>

<span data-ttu-id="4f183-106">このリリースでは、フローに**バッチ** スコープを追加して、すべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。</span><span class="sxs-lookup"><span data-stu-id="4f183-106">Now, you can add a **Batch** scope to your flows that will group all these different operations into a single call to Common Data Service to dramatically improve performance.</span></span> <span data-ttu-id="4f183-107">これを使用するには、**Common Data Service** コネクタで**バッチ**を探します。</span><span class="sxs-lookup"><span data-stu-id="4f183-107">To use this, search for **Batch** under the **Common Data Service** connector.</span></span> <span data-ttu-id="4f183-108">このスコープを Microsoft Flow デザイナーに追加したら、任意の Common Data Service アクションをその中に追加できます。</span><span class="sxs-lookup"><span data-stu-id="4f183-108">Once you add this scope into the Microsoft Flow designer, you can then add any Common Data Service action inside of it.</span></span> <span data-ttu-id="4f183-109">バッチ スコープに他のサービスのアクションを含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="4f183-109">You cannot include actions for other services inside of a Batch scope.</span></span> <span data-ttu-id="4f183-110">そのような場合は、バッチの前後で他のアクションを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4f183-110">Instead, you will need to perform those other actions before or after the Batch.</span></span>

<span data-ttu-id="4f183-111">![フローのバッチ スコープ](media/BatchOperations-1.png "フローのバッチ スコープ")</span><span class="sxs-lookup"><span data-stu-id="4f183-111">![Batch scope in Flow](media/BatchOperations-1.png "Batch scope in Flow")</span></span>

<span data-ttu-id="4f183-112">バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4f183-112">Remember, batch requests are best used when performing operations on entities that aren’t associated with each other.</span></span> <span data-ttu-id="4f183-113">取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。</span><span class="sxs-lookup"><span data-stu-id="4f183-113">Some operations on associated records, such as getting the primary contact of an account, can be performed in a single operation without using batching.</span></span>
