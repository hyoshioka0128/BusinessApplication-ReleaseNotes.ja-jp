---
title: 利息配賦
description: 1 日の平均残高に基づいて利息金額のエントリを生成します。
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 80e17705cfe618b6cab727c442a1bc919893e1d0
ms.sourcegitcommit: c8f2816cfd27cf7451e4651aa0038cc8400098d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2019
ms.locfileid: "895521"
---
# <a name="interest-distribution"></a><span data-ttu-id="13f8d-103">利息配賦</span><span class="sxs-lookup"><span data-stu-id="13f8d-103">Interest distribution</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="13f8d-104">機関は、現金勘定の 1 日の平均残高に基づいて、特定の一般会計勘定に銀行口座の利息を配賦できます。</span><span class="sxs-lookup"><span data-stu-id="13f8d-104">Your agency can allocate interest on a bank account to specific General ledger accounts, based on the average daily balance in cash accounts.</span></span> <span data-ttu-id="13f8d-105">このプロセスを使用して、利息金額の詳細な元帳エントリを生成したり、転記なしでレビュー用に利息金額を生成したりできます。</span><span class="sxs-lookup"><span data-stu-id="13f8d-105">You can use this process to generate an advanced ledger entry for the interest amounts or generate the interest amounts for review without posting.</span></span>

<span data-ttu-id="13f8d-106">利息を配賦する前に、[利息配賦ルール] フォームで関係している現金勘定を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="13f8d-106">Before distributing the interest, you must set up your participating cash accounts in the Interest distribution rules form.</span></span> <span data-ttu-id="13f8d-107">各現金勘定と交付の組み合わせを使用して、異なる利息勘定に対する利息を計算できます。</span><span class="sxs-lookup"><span data-stu-id="13f8d-107">Each cash account and grant combination can be used to calculate interest for a different interest account.</span></span>

