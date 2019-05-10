---
title: 倉庫管理での CW 製品処理
description: CW 機能では、CW 製品を倉庫管理プロセスの一部として使用するためのサポートが提供されます。
author: sorenva
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: perlynne
ms.openlocfilehash: fcdbef2b78fb6717e3970906d6a8b8c6c1596273
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225304"
---
#  <a name="catch-weight-product-processing-with-warehouse-management"></a><span data-ttu-id="40a7b-103">倉庫管理での CW 製品処理</span><span class="sxs-lookup"><span data-stu-id="40a7b-103">Catch weight product processing with warehouse management</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="40a7b-104">この機能では、倉庫管理プロセス内で CW 製品を使用するためのサポートが提供されます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-104">This functionality will provide support for using catch weight products within warehouse management processes.</span></span> <span data-ttu-id="40a7b-105">CW 製品は、食品業界など、製品によって重量やサイズが異なる業界でよく使用されます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-105">Catch weight products are often used in industries where products vary by weight and/or size, such as the food industry.</span></span> <span data-ttu-id="40a7b-106">CW 製品では、在庫単位 (Kg、lb、oz など) と CW 単位 (箱、1 つ、パレットなど) の 2 つの測定単位が使用されます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-106">Catch weight products use two units of measure—an inventory unit (such as kg, lb, or oz) and a catch weight unit (such as box, each, or pallet).</span></span> <span data-ttu-id="40a7b-107">在庫単位は、製品の計量と請求に使用される測定単位です。</span><span class="sxs-lookup"><span data-stu-id="40a7b-107">The inventory unit is the unit of measure in which the product is weighed and invoiced.</span></span> <span data-ttu-id="40a7b-108">CW 単位は、入庫、輸送、出荷などでの製品の処理単位です。</span><span class="sxs-lookup"><span data-stu-id="40a7b-108">The catch weight unit is the unit in which the products are handled, such as received, transferred, and shipped.</span></span> 

<span data-ttu-id="40a7b-109">![現物手持在庫ページで在庫数量と一緒に表示されている CW 数量](media/catch-weight-1.png "現物手持在庫ページで在庫数量と一緒に表示されている CW 数量")</span><span class="sxs-lookup"><span data-stu-id="40a7b-109">![Catch weight quantities shown together with inventory quantities on the Physical on-hand inventory page](media/catch-weight-1.png "Catch weight quantities shown together with inventory quantities on the Physical on-hand inventory page")</span></span>

<span data-ttu-id="40a7b-110">倉庫管理プロセスでは、CW 製品をパレットや箱などの異なる単位で処理することができ、ビジネス プロセスを細かく定義して、たとえばパレット レベルごとに入庫計量を実行したり、CW 数量 (箱) あたりのピッキングまたは梱包時に出荷営業プロセスを取り込んだりできます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-110">Within the warehouse management processes, the catch weight products can be handled in different units, such as pallets and boxes, and the business processes can be granularly defined to, for example, perform the inbound weighing per pallet level and capture the outbound sales process during picking or packing per catch weight quantity (box).</span></span>

<span data-ttu-id="40a7b-111">この機能では、割り当てられている CW 単位ごとにキャプチャされた重量を取得する CW タグを使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-111">This feature also allows you to use a catch weight tag that will get the captured weight per catch weight unit assigned.</span></span> <span data-ttu-id="40a7b-112">このアプローチの目的は、製品を受領時に 1 回のみ計量することです。</span><span class="sxs-lookup"><span data-stu-id="40a7b-112">The goal of this approach is to weigh the product only once at the time of receipt.</span></span> <span data-ttu-id="40a7b-113">これは、時間がたっても重量が変化しない製品 (冷凍エビなど)、および出荷可能な材料取り扱い測定単位 (エビの箱など) がある製品に有効です。</span><span class="sxs-lookup"><span data-stu-id="40a7b-113">This works for products that do not change weight over time (frozen shrimp, for example) and products that have a handling unit of measure that is shippable (such as a box of shrimp).</span></span> 

<span data-ttu-id="40a7b-114">![タグ重量のキャプチャ方法が示されているモバイル ウェアハウス アプリ](media/catch-weight-2.png "タグ重量のキャプチャ方法が示されているモバイル ウェアハウス アプリ")</span><span class="sxs-lookup"><span data-stu-id="40a7b-114">![Mobile warehouse app showing how tag weight is captured](media/catch-weight-2.png "Mobile warehouse app showing how tag weight is captured")</span></span>

<span data-ttu-id="40a7b-115">このアプローチでは、ユーザーは CW タグをスキャンして、製品の構成に基づいてピッキングまたは梱包時に重量を識別し、取り込んだ CW タグに関連付けられている重量に基づいて請求できます。</span><span class="sxs-lookup"><span data-stu-id="40a7b-115">With this approach, the user scans the catch weight tag to identify the weight at the time of picking or packing based on product configuration and then invoicing is based on the weight that is associated with the captured catch weight tag.</span></span>

<span data-ttu-id="40a7b-116">![CW 品目の取り扱いに関するポリシー ページで重量タグの追跡を有効にする](media/catch-weight-3.png "CW 品目の取り扱いに関するポリシー ページで重量タグの追跡を有効にする")</span><span class="sxs-lookup"><span data-stu-id="40a7b-116">![Enabling weight tag tracking on the Catch weight item handling policies page](media/catch-weight-3.png "Enabling weight tag tracking on the Catch weight item handling policies page")</span></span>

<span data-ttu-id="40a7b-117">![CW タグの登録ページに表示されている CW 登録](media/catch-weight-4.png "CW タグの登録ページに表示されている CW 登録")</span><span class="sxs-lookup"><span data-stu-id="40a7b-117">![Catch weight registrations shown on the Catch weight tag registration page](media/catch-weight-4.png "Catch weight registrations shown on the Catch weight tag registration page")</span></span>
