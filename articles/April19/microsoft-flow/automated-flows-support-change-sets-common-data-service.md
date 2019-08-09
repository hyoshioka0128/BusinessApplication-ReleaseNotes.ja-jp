---
title: 自動フローによる Common Data Service での変更セットのサポート
description: 変更セットのスコープについてのネイティブな理解が Microsoft Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: 0187bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ad6380295e5727024c07f255177d04cf0d01f168
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757027"
---
# <a name="automated-flows-support-change-sets-in-common-data-service"></a><span data-ttu-id="fb484-103">自動フローによる Common Data Service での変更セットのサポート</span><span class="sxs-lookup"><span data-stu-id="fb484-103">Automated flows support change sets in Common Data Service</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="fb484-104">変更セットは Common Data Service に関する作業の重要な部分です。その理由は、すべての操作がアトミックと見なされることです。つまり、いずれかの操作が失敗した場合は、完了したすべての操作がロールバックされます。</span><span class="sxs-lookup"><span data-stu-id="fb484-104">Change sets are an important part of working with Common Data Service because all operations are considered atomic, which means that if any one of the operations fails, any completed operations will be rolled back.</span></span> <span data-ttu-id="fb484-105">これは、*トランザクション*と呼ばれることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="fb484-105">This is often referred to as a *transaction*.</span></span>

<span data-ttu-id="fb484-106">変更セットのスコープについてのネイティブな理解が Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fb484-106">We have now added native understanding of Change set scopes to the Flow designer so that users can replace classic Common Data Service workflows that previously needed atomic transactions.</span></span>

<span data-ttu-id="fb484-107">![Flow での変更セット](media/ChangeSets-1.png "Flow での変更セット")</span><span class="sxs-lookup"><span data-stu-id="fb484-107">![Change sets in Flow](media/ChangeSets-1.png "Change sets in Flow")</span></span>

<span data-ttu-id="fb484-108">変更セットは**バッチ** スコープの内部に追加することができます。</span><span class="sxs-lookup"><span data-stu-id="fb484-108">Change sets can be added inside of **Batch** scopes.</span></span> <span data-ttu-id="fb484-109">これを使用するには、**Common Data Service** コネクタで**変更セット**を探します。</span><span class="sxs-lookup"><span data-stu-id="fb484-109">To use this, search for **Change set** under the **Common Data Service** connector.</span></span> <span data-ttu-id="fb484-110">このスコープを Microsoft Flow デザイナーに追加した後は、Common Data Service の作成、更新、または削除アクションをスコープの内部に追加できます (読み取り操作を変更セットに含めることはできません)。</span><span class="sxs-lookup"><span data-stu-id="fb484-110">Once you add this scope into the Microsoft Flow designer, you can add Common Data Service create, update, or delete actions inside of it (read operations cannot be in a change set).</span></span>

> [!NOTE]
> <span data-ttu-id="fb484-111">変更セット スコープに他のサービスのアクションを含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="fb484-111">You cannot include actions for other services inside of a change set scope.</span></span> <span data-ttu-id="fb484-112">そのような場合は、バッチの前後で他のアクションを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fb484-112">Instead, you will need to perform those other actions before or after the Batch.</span></span>
