---
title: "倉庫管理での CW 製品処理"
description: "倉庫管理での CW 製品処理"
author: ShylaThompson
manager: AnnBe
ms.date: 09/24/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 4000f44f5648de2dcb2fa2f24e3409d6e031be1d
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="catch-weight-product-processing-with-warehouse-management"></a><span data-ttu-id="11a66-103">倉庫管理での CW 製品処理</span><span class="sxs-lookup"><span data-stu-id="11a66-103">Catch weight product processing with warehouse management</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="11a66-104">この機能は、CW 製品を倉庫管理プロセスの一部として使用するためのサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="11a66-104">This functionality will provide support for using catch weight products as part of the warehouse management processes.</span></span> <span data-ttu-id="11a66-105">CW 製品は、食品業界など、製品によって重量やサイズのいずれか、または両方が微妙に異なる業界でよく使用されます。</span><span class="sxs-lookup"><span data-stu-id="11a66-105">Catch weight products are often used in industries where products can vary slightly by weight or size, or both, such as the food industry.</span></span> <span data-ttu-id="11a66-106">CW 製品では、在庫単位 (Kg) と CW 単位 (箱) の 2 つの単位が使用されます。</span><span class="sxs-lookup"><span data-stu-id="11a66-106">Catch weight products use two units of measures—an inventory unit (Kg) and a catch weight unit (box).</span></span> <span data-ttu-id="11a66-107">在庫単位は、製品の計量と請求に使用される測定単位です。</span><span class="sxs-lookup"><span data-stu-id="11a66-107">The inventory unit is the unit of measure in which the product is weighed and invoiced.</span></span> <span data-ttu-id="11a66-108">CW 単位は、入庫、輸送、出荷などでの製品の処理単位です。</span><span class="sxs-lookup"><span data-stu-id="11a66-108">The catch weight unit is the unit in which the products are handled, such as received, transferred, and shipped.</span></span> 

<span data-ttu-id="11a66-109">倉庫管理プロセスでは、CW 製品をパレットや箱などの異なる単位で処理することができ、ビジネス プロセスを細かく定義して、たとえばパレット レベルごとに入庫計量を実行したり、CW 数量 (箱) あたりのピッキングまたは梱包時に出荷営業プロセスを取り込んだりできます。</span><span class="sxs-lookup"><span data-stu-id="11a66-109">Within the warehouse management processes, the catch weight products can be handled in different units, such as pallets and boxes, and the business processes can be granularly defined to, for example, perform the inbound weighing per pallet level and capture the outbound sales process during picking or packing per catch weight quantity (box).</span></span> 

<span data-ttu-id="11a66-110">別のオプションとして、CW 単位で重量を取得する CW タグを使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="11a66-110">Another option is to use a catch weight tag that will capture the weight per catch weight unit.</span></span> <span data-ttu-id="11a66-111">このアプローチの目的は、製品を受領時に 1 回のみ計量することです。</span><span class="sxs-lookup"><span data-stu-id="11a66-111">The goal of this approach is to weigh the product only once—at the time of receipt.</span></span> <span data-ttu-id="11a66-112">これは、冷凍エビなど、時間がたっても重量が変化せず、出荷可能な測定単位 (エビの箱など) がある製品に有効です。</span><span class="sxs-lookup"><span data-stu-id="11a66-112">This works for products that do not change weight over time, such as frozen shrimp, and have a handling unit of measure that is shippable (such as a box of shrimp).</span></span> <span data-ttu-id="11a66-113">このアプローチでは、ユーザーは CW タグをスキャンして、製品の構成に基づいてピッキングまたは梱包時に重量を識別し、取り込んだ CW タグに関連付けられている重量に基づいて請求できます。</span><span class="sxs-lookup"><span data-stu-id="11a66-113">With this approach, the user would scan the catch weight tag to identify the weight at the time of picking or packing, based on configuration of the product, and the invoicing will be based on the weight associated with the captured catch weight tag.</span></span>

