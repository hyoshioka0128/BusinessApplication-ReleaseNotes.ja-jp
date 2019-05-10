---
title: 現金管理
description: 現金残高がない場合に転記を防ぐための限度を定義します
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 48178ebd03ff4fe987e4a22449b1fa64cacd58e6
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224898"
---
# <a name="cash-control"></a><span data-ttu-id="96f27-103">現金管理</span><span class="sxs-lookup"><span data-stu-id="96f27-103">Cash control</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="96f27-104">現金管理では、利用可能な現金残高がない場合、またはトランザクションが原因で残高が定義済みの限度を下回る場合に追加のトランザクションが転記されるのを防ぐための限度を定義できます。</span><span class="sxs-lookup"><span data-stu-id="96f27-104">Cash control allows you to define a limit for preventing additional transactions from posting if no cash balance is available or if the transaction causes the balance to be reduced below the defined limit.</span></span> <span data-ttu-id="96f27-105">買掛金勘定仕入先請求書および一般会計の詳細な元帳エントリは、作成、編集、および転記時に検証されます。</span><span class="sxs-lookup"><span data-stu-id="96f27-105">Accounts payable vendor invoices and General ledger advanced ledger entries are validated when they are created, edited, and posted.</span></span> <span data-ttu-id="96f27-106">トランザクションの転記が原因で、関連する現金勘定の残高がその勘定に定義されている限度を下回ると、エラー メッセージが表示され、続行するにはユーザーが勘定を変更する必要があります。</span><span class="sxs-lookup"><span data-stu-id="96f27-106">If the transaction’s posting would cause the related cash account’s balance to be reduced below the limit defined for the account, the user receives an error message and must change the account to continue.</span></span>

<span data-ttu-id="96f27-107">特定のユーザーが現金管理を上書きできるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="96f27-107">You can also allow specific users to override cash control.</span></span> <span data-ttu-id="96f27-108">許可されたユーザーが、勘定の現金残高が限度額を下回るという警告を受けた場合、ユーザーはトランザクションの転記を続けることを任意に選択できます。</span><span class="sxs-lookup"><span data-stu-id="96f27-108">If an authorized user receives a warning that the cash balance for the account will be reduced below the limit, the user can optionally choose to continue with posting the transaction.</span></span> <span data-ttu-id="96f27-109">経費をカバーするための資金を受け取る前にその経費を転記する必要がある場合、または承認された送金が行われる必要があるがまだ入力または転記されていない場合、ユーザーは現金管理限度額を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="96f27-109">Users might override the cash control limit when the expenditure must be posted in advance of receiving the funds to cover it; or when an approved transfer must happen, but has not been entered or posted yet.</span></span>

<span data-ttu-id="96f27-110">現金管理限度額は、現金管理残高 (現金勘定残高からすべての転記済み未払い AP 請求書を差し引いたもの) と比較されます。</span><span class="sxs-lookup"><span data-stu-id="96f27-110">The cash control limit is compared to the cash control balance (cash account balance minus all posted, unpaid AP invoices).</span></span> <span data-ttu-id="96f27-111">現金管理残高が現金管理限度額 (しきい値) を下回ると、限度額を超過します。</span><span class="sxs-lookup"><span data-stu-id="96f27-111">The limit is surpassed when the cash control balance is less than the cash control limit (threshold).</span></span>

