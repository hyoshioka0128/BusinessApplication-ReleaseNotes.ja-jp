---
title: 自動フローによる Common Data Service でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/30/2019
ms.assetid: ff86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 1dc8637555002cc65bb75829a629971f9d6071d5
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445790"
---
# <a name="automated-flows-support-batch-operations-in-common-data-service"></a><span data-ttu-id="6fdee-103">自動フローによる Common Data Service でのバッチ操作のサポート</span><span class="sxs-lookup"><span data-stu-id="6fdee-103">Automated flows support batch operations in Common Data Service</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="6fdee-104">Common Data Service で一括操作 (100 個の異なるレコードを挿入するなど) を実行する場合、通常であれば、Microsoft Flow によって Common Data Service に対する複数の呼び出しが行われます。</span><span class="sxs-lookup"><span data-stu-id="6fdee-104">If you want to perform bulk actions in Common Data Service, such as inserting 100 different records, normally Microsoft Flow will make several calls to Common Data Service.</span></span> <span data-ttu-id="6fdee-105">これでも問題なく機能しますが、フローの実行に長い時間がかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="6fdee-105">Although this works fine, it can take a long time for the flow to run.</span></span>

<span data-ttu-id="6fdee-106">今回、フローに **バッチ** スコープを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="6fdee-106">Now, you can add a **Batch** scope to your flows.</span></span> <span data-ttu-id="6fdee-107">このスコープにより、すべての操作を Common Data Service の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。</span><span class="sxs-lookup"><span data-stu-id="6fdee-107">This scope groups all operations into a single call to Common Data Service, dramatically improving performance.</span></span> <span data-ttu-id="6fdee-108">このスコープを使用するには、**Common Data Service** コネクタで**バッチ**を探します。</span><span class="sxs-lookup"><span data-stu-id="6fdee-108">To use this scope, search for **Batch** under the **Common Data Service** connector.</span></span> <span data-ttu-id="6fdee-109">このスコープを Microsoft Flow デザイナーに追加したら、任意の Common Data Service アクションをその中に追加できます。</span><span class="sxs-lookup"><span data-stu-id="6fdee-109">Once you add this scope into the Microsoft Flow designer, you can then add any Common Data Service action inside of it.</span></span> <span data-ttu-id="6fdee-110">**バッチ** スコープに他のサービスのアクションを含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="6fdee-110">You cannot include actions for other services inside of a **Batch** scope.</span></span> <span data-ttu-id="6fdee-111">そのような場合は、**バッチ**の前後で他のアクションを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6fdee-111">Instead, you will need to perform those other actions before or after the **Batch**.</span></span>

<span data-ttu-id="6fdee-112">![Flow のバッチ スコープ](media/BatchOperations-1.png "Microsoft Flow のバッチ スコープ")</span><span class="sxs-lookup"><span data-stu-id="6fdee-112">![Batch scope in Flow](media/BatchOperations-1.png "Batch scope in Microsoft Flow")</span></span>

<span data-ttu-id="6fdee-113">バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="6fdee-113">Remember, batch requests are best used when performing operations on entities that aren’t associated with each other.</span></span> <span data-ttu-id="6fdee-114">取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。</span><span class="sxs-lookup"><span data-stu-id="6fdee-114">Some operations on associated records, such as getting the primary contact of an account, can be performed in a single operation without using batching.</span></span>
