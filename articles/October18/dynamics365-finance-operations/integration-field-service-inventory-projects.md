---
title: "Dynamics 365 for Field Service との統合 - 在庫とプロジェクト"
description: "Dynamics 365 for Field Service との統合 - 在庫とプロジェクト"
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin, developer, end-user
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 3f6dc2e145bc06a060ac8b79d7401375b21908ef
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---
#  <a name="integration-with-dynamics-365-for-field-service--inventory-and-projects"></a><span data-ttu-id="1cc02-103">Dynamics 365 for Field Service との統合 - 在庫とプロジェクト</span><span class="sxs-lookup"><span data-stu-id="1cc02-103">Integration with Dynamics 365 for Field Service – inventory and projects</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="1cc02-104">CDS データ統合との統合は、Field Service 活動が Dynamics 365 for Finance and Operations の外部で行われるシナリオをサポートするために提供されます。</span><span class="sxs-lookup"><span data-stu-id="1cc02-104">Integration with CDS data integration will be provided to support scenarios where Field Service activities are done outside of Dynamics 365 for Finance and Operations.</span></span>

<span data-ttu-id="1cc02-105">このフェーズでは、Finance and Operations からの在庫情報の分析情報をフィールド技術者に提供して、フィールド技術者が在庫レベルの更新と材料の移動を行えるようにすることに重点を置きます。</span><span class="sxs-lookup"><span data-stu-id="1cc02-105">This phase focuses on giving field technicians insight to the inventory information from Finance and Operations, allowing them to update inventory levels and do material transfers.</span></span> <span data-ttu-id="1cc02-106">さらに、販売した製品をインストールまたは保守する企業では、プロジェクトから統合を利用して営業およびサービス プロセス全体をより適切に制御および可視化できるというメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="1cc02-106">In addition, companies installing or servicing sold goods will benefit from better control and visibility to the full sales and service process with integration from projects.</span></span>

<span data-ttu-id="1cc02-107">以下のデータを統合する機能です。</span><span class="sxs-lookup"><span data-stu-id="1cc02-107">Functionality includes integration of:</span></span>

-   <span data-ttu-id="1cc02-108">ウェアハウス情報</span><span class="sxs-lookup"><span data-stu-id="1cc02-108">Warehouse information</span></span>
-   <span data-ttu-id="1cc02-109">手持在庫情報</span><span class="sxs-lookup"><span data-stu-id="1cc02-109">On-hand inventory information</span></span>
-   <span data-ttu-id="1cc02-110">在庫移動</span><span class="sxs-lookup"><span data-stu-id="1cc02-110">Inventory transfers</span></span>
-   <span data-ttu-id="1cc02-111">在庫調整</span><span class="sxs-lookup"><span data-stu-id="1cc02-111">Inventory adjustments</span></span>
-   <span data-ttu-id="1cc02-112">Dynamics 365 for Field Service 作業指示書と接続された Dynamics 365 for Finance and Operations プロジェクト</span><span class="sxs-lookup"><span data-stu-id="1cc02-112">Dynamics 365 for Finance and Operations projects connected with Dynamics 365 for Field Service work orders</span></span>

<span data-ttu-id="1cc02-113">CDS データ インテグレーターはカスタマイズ可能なプロジェクトを使用してデータを同期します。</span><span class="sxs-lookup"><span data-stu-id="1cc02-113">The CDS data integrator synchronizes data by using customizable projects.</span></span>
<span data-ttu-id="1cc02-114">標準テンプレートを使用して、カスタム統合プロジェクトを作成できます。このプロジェクトでは、追加の標準およびカスタム フィールドおよびエンティティをマップして統合を調整し、特定のビジネス ニーズを満たすことができます。</span><span class="sxs-lookup"><span data-stu-id="1cc02-114">Standard templates can be used to create custom integration projects, where additional standard and custom fields and entities can be mapped to adjust the integration and meet specific business needs.</span></span> <span data-ttu-id="1cc02-115">フィールド サービスの統合は、既存の見込顧客の現金化機能を基に構築されます。</span><span class="sxs-lookup"><span data-stu-id="1cc02-115">The field service integration builds on top of the existing prospect-to-cash functionality.</span></span>

