---
title: "二重通貨"
description: "二重通貨"
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 348510b1dddd8228b6dd579a79fbeee5d65bf16c
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---
#  <a name="dual-currency"></a><span data-ttu-id="b6eeb-103">二重通貨</span><span class="sxs-lookup"><span data-stu-id="b6eeb-103">Dual currency</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="b6eeb-104">レポート通貨は、真の第 2 の会計通貨に目的変更されます。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-104">The reporting currency will be repurposed into a true second accounting currency.</span></span> <span data-ttu-id="b6eeb-105">総勘定元帳の観点からは、レポート通貨は引き続き総勘定元帳に転記されるすべてのトランザクションに対して計算されます。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-105">From a general ledger perspective, the reporting currency will continue to be calculated for every transaction posted to a general ledger.</span></span>  <span data-ttu-id="b6eeb-106">一部の総勘定元帳プロセスは強化され、レポート通貨でのみトランザクションを転記するための新しい仕訳が追加されます。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-106">Some general ledger processes will be enhanced, and a new journal will be added to post transactions in only the reporting currency.</span></span> <span data-ttu-id="b6eeb-107">固定資産などのさまざまな補助元帳については、より大きな変更があります。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-107">For various subledgers, such as fixed assets, there will be larger changes.</span></span> <span data-ttu-id="b6eeb-108">固定資産の場合、すべてのトランザクションをレポート通貨の補助元帳に保持するようになります。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-108">For fixed assets, we will start to maintain all transactions in the subledger for the reporting currency.</span></span> <span data-ttu-id="b6eeb-109">減価償却を実行すると、会計通貨の場合と同じように、減価償却方法を使用してレポート通貨の金額が減価償却されます。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-109">When running depreciation, it will depreciate the reporting currency amounts using the depreciation methods, just as it does the accounting currency.</span></span> <span data-ttu-id="b6eeb-110">影響を受ける他の補助元帳モジュールとしては、買掛金勘定、売掛金勘定、現金管理があります。</span><span class="sxs-lookup"><span data-stu-id="b6eeb-110">Other subledger modules impacted will be Accounts payable, Accounts receivable, and Cash management.</span></span>

