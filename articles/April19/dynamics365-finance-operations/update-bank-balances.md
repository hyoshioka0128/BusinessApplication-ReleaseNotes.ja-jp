---
title: 詳細な元帳エントリを使用してトランザクションを転記するときに銀行残高を更新する
description: トランザクションを転記するときに銀行残高を更新します。
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 0cab0a8baa0cf24b2f28c6ca531b217cf1a5c578
ms.sourcegitcommit: c8f2816cfd27cf7451e4651aa0038cc8400098d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2019
ms.locfileid: "895506"
---
# <a name="update-bank-balances-when-posting-transactions-using-advanced-ledger-entry"></a><span data-ttu-id="6b76a-103">詳細な元帳エントリを使用してトランザクションを転記するときに銀行残高を更新する</span><span class="sxs-lookup"><span data-stu-id="6b76a-103">Update bank balances when posting transactions using advanced ledger entry</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="6b76a-104">銀行口座を 1 つ以上の主勘定に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="6b76a-104">You can associate a bank account with one or more main accounts.</span></span> <span data-ttu-id="6b76a-105">銀行口座が主勘定に関連付けられている場合、その銀行口座の残高は、関連付けられている主勘定に詳細な元帳エントリが転記されたときに更新できます。</span><span class="sxs-lookup"><span data-stu-id="6b76a-105">If a bank account is associated with a main account, the bank account's balances can be updated when advanced ledger entries are posted to the associated main account.</span></span> <span data-ttu-id="6b76a-106">銀行口座には、口座番号と支店コードが関連付けられている必要があります。</span><span class="sxs-lookup"><span data-stu-id="6b76a-106">Note that the bank account must have an account number and routing number associated with it.</span></span>
