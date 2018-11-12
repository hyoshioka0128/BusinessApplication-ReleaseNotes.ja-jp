---
title: "プロジェクトでの複数通貨の原価価格表の解決"
description: "プロジェクトでの複数通貨の原価価格表の解決"
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
ms.openlocfilehash: bac9c35f91f43541a6597feb3973c9bf40fe1a44
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a><span data-ttu-id="26ff3-103">プロジェクトでの複数通貨の原価価格表の解決</span><span class="sxs-lookup"><span data-stu-id="26ff3-103">Resolution of multi-currency cost price list on projects</span></span> 

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="26ff3-104">Project Service は、プロジェクトを所有する組織単位の通貨を価格表の通貨と一致させることで、プロジェクトの原価率の価格表を解決します。</span><span class="sxs-lookup"><span data-stu-id="26ff3-104">Project Service resolves the price list for cost rates on projects by matching the currency of the organizational unit that owns the project to the price list currency.</span></span> <span data-ttu-id="26ff3-105">価格表に複数通貨の価格がある場合、1 つのマスター価格表に複数通貨の原価率行があり、この価格表がすべてのプロジェクトでグローバルに使用されることが予想されます。</span><span class="sxs-lookup"><span data-stu-id="26ff3-105">In the case where a price list may have prices in multiple currencies, it's expected that there would be one master price list with cost rate lines in multiple currencies, and that this price list would be used by all projects globally.</span></span> 

<span data-ttu-id="26ff3-106">その状況では、価格表のヘッダーの通貨を使用したプロジェクトの原価価格表の解決が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="26ff3-106">In that situation, resolving a cost price list for a project using the currency on the header of the price list would not work.</span></span> <span data-ttu-id="26ff3-107">この機能では、プロジェクトの原価価格表の既定の解決を設定するように構成できます。</span><span class="sxs-lookup"><span data-stu-id="26ff3-107">With this feature, it will be configurable to set up the default resolution of the project cost price list.</span></span> <span data-ttu-id="26ff3-108">使用可能なオプションは、プロジェクトのコスト通貨を現在機能している価格表のヘッダーと一致させるか、ヘッダー通貨に関係なく、グローバルに管理されている価格表を使用することです。</span><span class="sxs-lookup"><span data-stu-id="26ff3-108">The options available would be to match the project’s cost currency with the header of the price list as it works today or to use the globally managed price list regardless of its header currency.</span></span>  



