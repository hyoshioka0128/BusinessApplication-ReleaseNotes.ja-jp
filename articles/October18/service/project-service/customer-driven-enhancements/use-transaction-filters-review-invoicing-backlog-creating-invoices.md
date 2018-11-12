---
title: "トランザクション フィルターを使用した、請求書作成時の請求バックログのレビュー"
description: "Project Service では、プロジェクトで記録されたすべての未請求売上実績から請求書が作成されます。"
author: krbjoran
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: krbjoran
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 0bd46ff906bbc9766b3471909ace33c40d3ba953
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="use-transaction-filters-to-review-invoicing-backlog-when-creating-invoices"></a><span data-ttu-id="b2433-103">トランザクション フィルターを使用した、請求書作成時の請求バックログのレビュー</span><span class="sxs-lookup"><span data-stu-id="b2433-103">Use transaction filters to review invoicing backlog when creating invoices</span></span> 

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="b2433-104">Project Service では、プロジェクトで記録されたすべての未請求売上実績から請求書が作成されます。</span><span class="sxs-lookup"><span data-stu-id="b2433-104">Project Service creates invoices from all unbilled sales actuals that were recorded on a project.</span></span> <span data-ttu-id="b2433-105">この機能では、ネイティブの XRM フィルター機能を使用して実績を絞り込み、請求の準備ができているトランザクションをマークできるビューが導入されます。</span><span class="sxs-lookup"><span data-stu-id="b2433-105">This feature will introduce a view where you can filter actuals using the native XRM filter capabilities and mark the transactions that are ready for invoicing.</span></span> <span data-ttu-id="b2433-106">これにより、プロジェクト マネージャーは顧客への請求項目を期間ごとに制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="b2433-106">This will provide better control for the project managers on what gets invoiced to the customer for each period.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b2433-107">![](media/use-transaction-filters-review-invoicing-backlog-creating-invoices-1.png "トランザクション フィルターを使用して請求バックログをレビューする")
<!-- Picture 1 --></span><span class="sxs-lookup"><span data-stu-id="b2433-107">![](media/use-transaction-filters-review-invoicing-backlog-creating-invoices-1.png "Use of transaction filters to review invoicing backlog")
<!-- Picture 1 --></span></span>


