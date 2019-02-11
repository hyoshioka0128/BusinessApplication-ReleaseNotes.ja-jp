---
title: 自動フローによる CDS for Apps での変更セットのサポート
description: 変更セットのスコープについてのネイティブな理解が Microsoft Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 1b7458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 471ee505cf85a9f8db8c4c8b725bdbd74e3cff43
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210717"
---
# <a name="automated-flows-support-change-sets-in-cds-for-apps"></a><span data-ttu-id="c32a2-103">自動フローによる CDS for Apps での変更セットのサポート</span><span class="sxs-lookup"><span data-stu-id="c32a2-103">Automated flows support change sets in CDS for Apps</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="c32a2-104">すべての操作はアトミックと見なされ、これはいずれかの操作が失敗した場合は完了したすべての操作がロールバックされることを意味するので、変更セットは Common Data Service (CDS) for Apps の処理における重要な部分です。</span><span class="sxs-lookup"><span data-stu-id="c32a2-104">Change sets are an important part of working with Common Data Service (CDS) for Apps because all operations are considered atomic, which means that if any one of the operations fails, any completed operations will be rolled back.</span></span> <span data-ttu-id="c32a2-105">これは、*トランザクション*と呼ばれることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="c32a2-105">This is often referred to as a *transaction*.</span></span>

<span data-ttu-id="c32a2-106">変更セットのスコープについてのネイティブな理解が Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c32a2-106">We have now added native understanding of Change set scopes to the Flow designer so that users can replace classic Common Data Service workflows that previously needed atomic transactions.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="c32a2-107">![Flow での変更セット](media/ChangeSets-1.png "Flow での変更セット")</span><span class="sxs-lookup"><span data-stu-id="c32a2-107">![Change sets in Flow](media/ChangeSets-1.png "Change sets in Flow")</span></span>

<span data-ttu-id="c32a2-108">変更セットは**バッチ** スコープの内部に追加することができます。</span><span class="sxs-lookup"><span data-stu-id="c32a2-108">Change sets can be added inside of **Batch** scopes.</span></span> <span data-ttu-id="c32a2-109">これを使用するには、**Common Data Service** コネクタで**変更セット**を探します。</span><span class="sxs-lookup"><span data-stu-id="c32a2-109">To use this, search for **Change set** under the **Common Data Service** connector.</span></span> <span data-ttu-id="c32a2-110">このスコープを Microsoft Flow デザイナーに追加した後は、CDS の作成、更新、または削除アクションをその中に追加できます (読み取り操作を変更セットに含めることはできません)。</span><span class="sxs-lookup"><span data-stu-id="c32a2-110">Once you add this scope into the Microsoft Flow designer, you can add CDS create, update, or delete actions inside of it (read operations cannot be in a change set).</span></span>

> [!NOTE]
> <span data-ttu-id="c32a2-111">変更セット スコープに他のサービスのアクションを含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="c32a2-111">You cannot include actions for other services inside of a change set scope.</span></span> <span data-ttu-id="c32a2-112">そのような場合は、バッチの前後で他のアクションを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c32a2-112">Instead, you will need to perform those other actions before or after the Batch.</span></span>
