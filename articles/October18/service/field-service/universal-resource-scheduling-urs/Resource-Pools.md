---
title: "リソース プール"
description: "リソース プールを使用すると、スケジュール担当者は、実際に作業を実行するリソースを決定する必要なしに、汎用プールに作業を予約できます。"
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: dbd8a17e3e500201426a03a48feb4bf5a2c7d024
ms.openlocfilehash: 6e374ca408d70db7c85a40ecec03aa7b13a7e1a4
ms.contentlocale: ja-jp
ms.lasthandoff: 11/01/2018

---

#  <a name="resource-pools"></a><span data-ttu-id="62b8b-103">リソース プール</span><span class="sxs-lookup"><span data-stu-id="62b8b-103">Resource pools</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="62b8b-104">リソースをリソース プールに関連付けて、スケジュール担当者が、実際に作業を実行するリソースを決定する必要なしに、汎用プールに要件を予約できるようにします。</span><span class="sxs-lookup"><span data-stu-id="62b8b-104">Associate resources to resource pools to enable schedulers to book requirements to a generic pool without needing to decide which resource will actually perform the work.</span></span>

## <a name="why"></a><span data-ttu-id="62b8b-105">理由</span><span class="sxs-lookup"><span data-stu-id="62b8b-105">Why</span></span>

- <span data-ttu-id="62b8b-106">特定のリソースを強制的に事前予約することを回避し、代わりに "リソース プール" を予約してオーバーコミットを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="62b8b-106">Avoid being forced to book specific resources up front and instead book the “resource pool” while ensuring you are not overcommitting.</span></span>
- <span data-ttu-id="62b8b-107">中央のスケジュール担当者には詳細を隠し、ローカル リソース マネージャーに詳細を任すことができます。</span><span class="sxs-lookup"><span data-stu-id="62b8b-107">Enable central schedulers to be shielded from details and leave the details to the local resource manager.</span></span>
- <span data-ttu-id="62b8b-108">特定のリソースはまだ指名できず、プールのキャパシティが設定されてリソースは後で指名されます。</span><span class="sxs-lookup"><span data-stu-id="62b8b-108">Specific resources may not be named yet but capacity of the pool is established and resources will be named later.</span></span> <span data-ttu-id="62b8b-109">すべてのリソースが指名されたかのようにプールのキャパシティを設定できるので、スケジュール担当者は引き続きスケジュールできます (キャパシティ管理)。</span><span class="sxs-lookup"><span data-stu-id="62b8b-109">Schedulers can still schedule since capacity of the pool can be set as if all the resources were named (capacity management).</span></span>
- <span data-ttu-id="62b8b-110">キャンセルを予想して予約超過を意図的に有効にします。</span><span class="sxs-lookup"><span data-stu-id="62b8b-110">Deliberately enable overbooking for expected cancellations.</span></span>

## <a name="what"></a><span data-ttu-id="62b8b-111">対象</span><span class="sxs-lookup"><span data-stu-id="62b8b-111">What</span></span>

- <span data-ttu-id="62b8b-112">リソース プールは、設備のプール、取引先企業/取引先担当者/ユーザーのプール、または備品プールのいずれかです。</span><span class="sxs-lookup"><span data-stu-id="62b8b-112">Resource pools can be either pools of facilities, or pools of accounts/contacts/users, or pools of equipment.</span></span> <span data-ttu-id="62b8b-113">プールは、同種のリソースのセットにすることが意図されています。</span><span class="sxs-lookup"><span data-stu-id="62b8b-113">Pools are intended to be a set of homogenous resources.</span></span>
- <span data-ttu-id="62b8b-114">プール メンバーは、有効日に永久または一時的にプールに割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="62b8b-114">Pool members can be permanently or temporarily assigned to pools, date effective.</span></span>
- <span data-ttu-id="62b8b-115">必要に応じてプール メンバーから全体的なプール キャパシティを取得します。</span><span class="sxs-lookup"><span data-stu-id="62b8b-115">Optionally derive overall pool capacity from pool members.</span></span> </br>

  <span data-ttu-id="62b8b-116">(リソース プールでのサポートが計画されていないオンサイト要件。)</span><span class="sxs-lookup"><span data-stu-id="62b8b-116">(Onsite requirements not planned to be supported with resource pools.)</span></span>

  > [!div class="mx-imgBorder"]
  > <span data-ttu-id="62b8b-117">![リソース プールのシナリオ](media/ResourcePools.png "リソース プールのシナリオ")</span><span class="sxs-lookup"><span data-stu-id="62b8b-117">![Resource pool scenarios](media/ResourcePools.png "Resource pool scenarios")</span></span>
  
  <span data-ttu-id="62b8b-118">*リソース プールのシナリオ*</span><span class="sxs-lookup"><span data-stu-id="62b8b-118">*Resource pool scenarios*</span></span>

