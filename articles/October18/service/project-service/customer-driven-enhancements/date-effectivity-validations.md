---
title: "価格表の日付の有効期間の検証"
description: "検証により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 45118e9b8562da5b617c2ad1e983ffddc466259c
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#   <a name="date-effectivity-validation-on-price-lists"></a><span data-ttu-id="a1372-103">価格表の日付の有効期間の検証</span><span class="sxs-lookup"><span data-stu-id="a1372-103">Date effectivity validation on price lists</span></span>

[!include[project-service banner](../../../includes/project-service.md)]





<span data-ttu-id="a1372-104">この機能により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。</span><span class="sxs-lookup"><span data-stu-id="a1372-104">This feature ensures that Project Service users avoid errors in price defaulting arising from having more than one price list effective for a certain date.</span></span> <span data-ttu-id="a1372-105">Project Service では、複数のプロジェクト価格表を見積もり、プロジェクト契約、および組織単位に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="a1372-105">As Project Service customers are aware, the product allows for multiple project price lists to be associated to quotes, project contracts, and organizational units.</span></span> <span data-ttu-id="a1372-106">これは、有効な日付が異なる価格表によって表されるインフレ価格変化を有効にするためです。</span><span class="sxs-lookup"><span data-stu-id="a1372-106">This is to allow for inflationary pricing changes represented by price lists with different date effectivities.</span></span> 

<span data-ttu-id="a1372-107">この機能により、システムは価格表のセットアップを検証して、プロジェクトや契約などの 1 つのコンテキストで有効な日付がオーバーラップしていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="a1372-107">With this feature, the system will validate the price list setup to ensure no overlapping date effectivities given a single context such as a project or a contract.</span></span> <span data-ttu-id="a1372-108">また、システムは、見積もりまたは契約での予測に複数の価格期間が含まれる場合、作業に正しく価格を設定できることを確認します。</span><span class="sxs-lookup"><span data-stu-id="a1372-108">Also, the system will ensure that when an estimate on a quote or contract spans multiple price periods, the system is able to correctly price the work.</span></span> 

