---
title: 請求スケジュール
description: 顧客は販売契約に対して柔軟な請求ルールを適用できる必要があります。
author: ReneeW-CPub
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 8cce930452d1ce7a836c0c1a321470a6fa3abccb
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210869"
---
<!--from editor: Please add ms.reviewer (CP owner's alias) to the metadata and update the author (PM's GitHub name) and ms.author (PM's Microsoft alias) entries.--> 

#  <a name="billing-schedules"></a><span data-ttu-id="e82da-103">請求スケジュール</span><span class="sxs-lookup"><span data-stu-id="e82da-103">Billing schedules</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="e82da-104">請求スケジュールは、顧客販売注文に対する柔軟な請求ルールに対応しています。</span><span class="sxs-lookup"><span data-stu-id="e82da-104">Billing schedules allows for flexible billing rules against customer sales orders.</span></span> <span data-ttu-id="e82da-105">販売注文の明細ごとに異なる請求スケジュールを定義できます。</span><span class="sxs-lookup"><span data-stu-id="e82da-105">Different billing schedules can be defined on each line of the sales order.</span></span> <span data-ttu-id="e82da-106">現在は、支払スケジュールを使用して、売掛金勘定に全額をすぐに転記し、支払スケジュールに基づいてさまざまな期間に振り分けることができます。</span><span class="sxs-lookup"><span data-stu-id="e82da-106">Currently you can use Payment schedules to immediately post the full amount to Accounts receivable, spread over various periods based on the payment schedule.</span></span> <span data-ttu-id="e82da-107">請求スケジュールでは、代わりに、未請求売掛金勘定に転記してから、請求スケジュールに基づいて請求書を作成します。</span><span class="sxs-lookup"><span data-stu-id="e82da-107">Billing schedules will instead post to Unbilled accounts receivable, and then create invoices based on the billing schedule.</span></span> <span data-ttu-id="e82da-108">請求書ごとに、未請求売掛金勘定から売掛金勘定に残高を移動するための簿記入力が作成されます。</span><span class="sxs-lookup"><span data-stu-id="e82da-108">Each invoice will create an accounting entry to move the balance from Unbilled accounts receivable to Accounts receivable.</span></span> <span data-ttu-id="e82da-109">これにより、請求書が転記されるまで将来の期間を保留中にすることもできます。</span><span class="sxs-lookup"><span data-stu-id="e82da-109">This allows future periods to also remain on hold until the invoice is posted.</span></span> 
