---
title: 買掛金勘定仕入先請求書の為替レート フィールドでの変更
description: 仕入先請求書承認仕訳帳での為替レートのロック
author: aprilolson
ms.date: 04/25/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: f064903bbb37e5674ca9da7d04e6ef4cc4526e2c
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225534"
---
# <a name="accounts-payable-vendor-invoice-change-with-exchange-rate-field"></a><span data-ttu-id="96026-103">買掛金勘定仕入先請求書の為替レート フィールドでの変更</span><span class="sxs-lookup"><span data-stu-id="96026-103">Accounts payable vendor invoice change with exchange rate field</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="96026-104">仕入先請求書の承認プロセスで使用される為替レートが、請求書の登録に使用されたレートと同じになります。</span><span class="sxs-lookup"><span data-stu-id="96026-104">The exchange rate used during the vendor invoice approval process will be the same rate that was used to register the invoice.</span></span> <span data-ttu-id="96026-105">これにより、請求書登録の見越計上エントリが承認仕訳帳の転記プロセスで正しく取り消されるようになります。</span><span class="sxs-lookup"><span data-stu-id="96026-105">This will ensure that the invoice registration’s accrual entries will be reversed properly by the approval journal posting process.</span></span> <span data-ttu-id="96026-106">仕入先請求書承認仕訳帳の為替レート フィールドは、変更を防ぐためにロックされます。</span><span class="sxs-lookup"><span data-stu-id="96026-106">The exchange rate field on the vendor invoice approval journal will be locked to prevent changes.</span></span>
