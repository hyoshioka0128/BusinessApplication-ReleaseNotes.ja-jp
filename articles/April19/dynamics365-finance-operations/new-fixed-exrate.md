---
title: 仕入先請求書、販売注文、および販売契約書の新しい固定為替レート
description: レポート通貨用の新しい固定為替レートが複数の場所に追加されました。
author: aprilolson
ms.date: 05/21/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 65dbb726c64baa6c7ca8793201dd62384e8d47f2
ms.sourcegitcommit: d82ae752fb528c3b0b5e418efa27b7150e6f6613
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1594855"
---
# <a name="new-fixed-exchange-rate-in-vendor-invoices-sales-orders-and-sales-agreements"></a><span data-ttu-id="ed0a1-103">仕入先請求書、販売注文、および販売契約書の新しい固定為替レート</span><span class="sxs-lookup"><span data-stu-id="ed0a1-103">New fixed exchange rate in vendor invoices, sales orders, and sales agreements</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="ed0a1-104">仕入先請求書、販売注文、および販売契約書は、レポート通貨の固定為替レートを含むように更新されました。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-104">Vendor invoices, sales orders, and sales agreements have been updated to include a fixed exchange rate for the reporting currency.</span></span> <span data-ttu-id="ed0a1-105">取引通貨が異なる場合は、会計通貨とレポート通貨の両方に固定為替レートを定義できます。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-105">A fixed exchange rate can be defined for both the accounting and reporting currency when the transaction currency is different.</span></span> <span data-ttu-id="ed0a1-106">これで二重通貨に必要なレートが完成します。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-106">This completes the rates needed for dual currency.</span></span>

<span data-ttu-id="ed0a1-107">会計通貨とレポート通貨が同じ場合、会計通貨の固定レートの既定をレポート通貨の固定レートに設定することで、固定為替レートの同期が維持されます。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-107">When the accounting currency and reporting currency are the same, the fixed exchange rate will be kept in sync by defaulting the accounting currency’s fixed rate into the reporting currency’s fixed rate.</span></span> <span data-ttu-id="ed0a1-108">このセットアップ構成では、レポート通貨の固定為替レートを変更できません。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-108">The reporting currency fixed exchange rate cannot be changed for this setup configuration.</span></span> <span data-ttu-id="ed0a1-109">会計通貨とレポート通貨が異なる場合は、取引の入力時に会計通貨とレポート通貨の両方に固定為替レートを定義できます。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-109">When the accounting currency and the reporting currency differ, a fixed exchange rate can be defined for both the accounting and reporting currency during transaction entry.</span></span> <span data-ttu-id="ed0a1-110">元帳にレポート通貨が定義されていない場合、レポート通貨の固定為替レート フィールドは有効にならず、レポート通貨金額は計算されません。</span><span class="sxs-lookup"><span data-stu-id="ed0a1-110">If the reporting currency has not been defined on the ledger, the reporting currency fixed exchange rate field is not enabled, and no reporting currency amount is calculated.</span></span>
