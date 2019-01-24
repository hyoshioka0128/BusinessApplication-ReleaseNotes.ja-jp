---
title: "2018 年 10 月リリースでのリソース スケジュール最適化のその他の機能拡張"
description: "2018 年 10 月リリースでの Dynamics 365 向けリソース スケジュール最適化ソリューションのその他の機能拡張"
author: krbjoran
manager: shellyhaverkamp
ms.date: 10/16/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: FieldServiceDave
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: c7e67ca8c13a21ccc8d5616b6fd1f6ee564ee115
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

#  <a name="other-enhancements-to-resource-scheduling-optimization"></a><span data-ttu-id="158a4-103">リソース スケジュール最適化のその他の機能拡張</span><span class="sxs-lookup"><span data-stu-id="158a4-103">Other enhancements to Resource Scheduling Optimization</span></span> 

[!include[field-service banner](../../../includes/field-service.md)]

## <a name="default-optimization-goal"></a><span data-ttu-id="158a4-104">既定の最適化ゴール</span><span class="sxs-lookup"><span data-stu-id="158a4-104">Default optimization goal</span></span>

<span data-ttu-id="158a4-105">リソース スケジュール最適化ソリューションを展開すると、既定の制約と目標が有効になった既定のゴールが自動的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="158a4-105">When the Resource Scheduling Optimization solution is deployed, the system automatically creates a default goal with default constraints and objectives enabled.</span></span> 

<span data-ttu-id="158a4-106">リソース スケジュール最適化ソリューションでは、ゴールはソリューションが最適化する対象です。</span><span class="sxs-lookup"><span data-stu-id="158a4-106">In the Resource Scheduling Optimization solution, a goal is what the solution optimizes.</span></span> <span data-ttu-id="158a4-107">たとえば、一般的なゴールとして、勤務時間の最大化と移動時間の最小化の 2 つがあります。</span><span class="sxs-lookup"><span data-stu-id="158a4-107">For example, two common goals are maximizing working hours and minimizing travel time.</span></span> <span data-ttu-id="158a4-108">既定では、ゴールに対して制約と目的が有効になっています。</span><span class="sxs-lookup"><span data-stu-id="158a4-108">By default, a goal has constraints and objectives enabled.</span></span> <span data-ttu-id="158a4-109">これらはいずれも必要に応じて変更できます。</span><span class="sxs-lookup"><span data-stu-id="158a4-109">Any of these can be modified as needed.</span></span>

<span data-ttu-id="158a4-110">![生産性を最大化するための既定のゴールのスクリーンショット](../media/rso-default-goal-2.png "生産性を最大化するための既定のゴールのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="158a4-110">![Screenshot of a default goal to maximize productivity](../media/rso-default-goal-2.png "Screenshot of a default goal to maximize productivity")</span></span>

<span data-ttu-id="158a4-111">*生産性を最大化するための既定のゴール*</span><span class="sxs-lookup"><span data-stu-id="158a4-111">*Default goal to maximize productivity*</span></span>

<span data-ttu-id="158a4-112">既定のゴールは、スケジュール ボードで単一リソース最適化が選択されているときに使用されます。</span><span class="sxs-lookup"><span data-stu-id="158a4-112">The default goal is used when single resource optimization is selected from the schedule board.</span></span> <span data-ttu-id="158a4-113">必要に応じて、ユーザーは新しい最適化ゴールを作成し、それを既定のゴールとして関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="158a4-113">If needed, a user can create a new optimization goal and associate it as a default goal.</span></span>

<span data-ttu-id="158a4-114">![リソース スケジュール最適化で展開された既定のゴールのスクリーンショット](../media/rso-single-resource-1.png "リソース スケジュール最適化で展開された既定のゴールのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="158a4-114">![Screenshot of default goal deployed with Resource Scheduling Optimization](../media/rso-single-resource-1.png "Screenshot of default goal deployed with Resource Scheduling Optimization")</span></span>

<span data-ttu-id="158a4-115">*リソース スケジュール最適化で展開された既定のゴール*</span><span class="sxs-lookup"><span data-stu-id="158a4-115">*Default goal deployed with Resource Scheduling Optimization*</span></span>

## <a name="new-constraint-for-matching-resource-type"></a><span data-ttu-id="158a4-116">リソースの種類と一致させるための新しい制約</span><span class="sxs-lookup"><span data-stu-id="158a4-116">New constraint for matching resource type</span></span>

<span data-ttu-id="158a4-117">リソース スケジュール最適化には、**リソースの種類に一致する**という新しい制約が含まれます。</span><span class="sxs-lookup"><span data-stu-id="158a4-117">Resource Scheduling Optimization includes a new constraint called **Matches Resource Type**.</span></span> <span data-ttu-id="158a4-118">制約は、最適化ソリューションがジョブを自動的に割り当てるときに考慮するリソースと要件の属性です。</span><span class="sxs-lookup"><span data-stu-id="158a4-118">A constraint is a resource and requirement attribute that the optimization solution considers when automatically assigning jobs.</span></span> 

<span data-ttu-id="158a4-119">この制約では、最適化は要件とリソースの間でリソースの種類を一致させて、どの種類のリソースで要件を満たすことができるかを決定します。</span><span class="sxs-lookup"><span data-stu-id="158a4-119">With this constraint, the optimization matches the resource type between requirements and resources to decide which type of resource can fulfill a requirement.</span></span> <span data-ttu-id="158a4-120">この機能により、リソース スケジュール最適化とリソース空き時間検索の機能がより密接に連携します。</span><span class="sxs-lookup"><span data-stu-id="158a4-120">This capability aligns Resource Scheduling Optimization more closely with the functionality of resource availability search.</span></span>

<span data-ttu-id="158a4-121">予約可能なリソースには、次のリソースの種類が含まれます。</span><span class="sxs-lookup"><span data-stu-id="158a4-121">Bookable resources include these resource types:</span></span>

- <span data-ttu-id="158a4-122">汎用 \*</span><span class="sxs-lookup"><span data-stu-id="158a4-122">Generic \*</span></span>
- <span data-ttu-id="158a4-123">ユーザー \*</span><span class="sxs-lookup"><span data-stu-id="158a4-123">Users \*</span></span>
- <span data-ttu-id="158a4-124">取引先担当者 \*</span><span class="sxs-lookup"><span data-stu-id="158a4-124">Contacts \*</span></span>
- <span data-ttu-id="158a4-125">取引先企業 \*</span><span class="sxs-lookup"><span data-stu-id="158a4-125">Accounts \*</span></span>
- <span data-ttu-id="158a4-126">備品 \*</span><span class="sxs-lookup"><span data-stu-id="158a4-126">Equipment \*</span></span>
- <span data-ttu-id="158a4-127">設備 \*</span><span class="sxs-lookup"><span data-stu-id="158a4-127">Facility \*</span></span>
- <span data-ttu-id="158a4-128">スタッフ</span><span class="sxs-lookup"><span data-stu-id="158a4-128">Crew</span></span>
- <span data-ttu-id="158a4-129">プール</span><span class="sxs-lookup"><span data-stu-id="158a4-129">Pool</span></span>

<span data-ttu-id="158a4-130">\* 最適化で考慮されるリソースの種類を示します</span><span class="sxs-lookup"><span data-stu-id="158a4-130">\* Indicates resource types the optimization considers</span></span>

<span data-ttu-id="158a4-131">一般に、リソースの種類では、リソースが組織とどのように関係するかが定義されます。</span><span class="sxs-lookup"><span data-stu-id="158a4-131">In general, resource types define how the resource relates to the organization.</span></span> <span data-ttu-id="158a4-132">たとえば、リソースの種類が**ユーザー**であるリソースは通常は従業員ですが、リソースの種類が**取引先担当者**または**取引先企業**であるリソースは通常は契約社員です。</span><span class="sxs-lookup"><span data-stu-id="158a4-132">As an example, resources with the resource type **Users** are usually employees, whereas the resource type **Contacts** or **Accounts** are usually contractors.</span></span>

<span data-ttu-id="158a4-133">さらに、要件では複数選択が可能なので、特定の要件に必要な複数のリソースの種類を指定できます。</span><span class="sxs-lookup"><span data-stu-id="158a4-133">Additionally, requirements allow multi-select so you can specify which resource types are needed for a given requirement.</span></span>

<span data-ttu-id="158a4-134">![要件での複数選択のリソースの種類属性のスクリーンショット](../media/rso-requirement-resource-type-field.png "要件での複数選択のリソースの種類属性のスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="158a4-134">![Screenshot of multi-select resource type attribute on requirement](../media/rso-requirement-resource-type-field.png "Screenshot of multi-select resource type attribute on requirement")</span></span>

<span data-ttu-id="158a4-135">*要件での複数選択のリソースの種類属性*</span><span class="sxs-lookup"><span data-stu-id="158a4-135">*Multi-select resource type attribute on requirement*</span></span>

<span data-ttu-id="158a4-136">このリリースでは、要件にリソースを割り当てるときに、最適化で次のリソースの種類が考慮されます。</span><span class="sxs-lookup"><span data-stu-id="158a4-136">With this release, when assigning resources to requirements, the optimization now considers these resource types:</span></span>

- <span data-ttu-id="158a4-137">汎用</span><span class="sxs-lookup"><span data-stu-id="158a4-137">Generic</span></span>
- <span data-ttu-id="158a4-138">ユーザー</span><span class="sxs-lookup"><span data-stu-id="158a4-138">Users</span></span>
- <span data-ttu-id="158a4-139">取引先担当者</span><span class="sxs-lookup"><span data-stu-id="158a4-139">Contacts</span></span>
- <span data-ttu-id="158a4-140">取引先企業</span><span class="sxs-lookup"><span data-stu-id="158a4-140">Accounts</span></span>
- <span data-ttu-id="158a4-141">備品</span><span class="sxs-lookup"><span data-stu-id="158a4-141">Equipment</span></span>
- <span data-ttu-id="158a4-142">設備</span><span class="sxs-lookup"><span data-stu-id="158a4-142">Facility</span></span>

<span data-ttu-id="158a4-143">リソースの種類を一致させる機能を有効にするには、**最適化の目的**に移動し、制約として機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="158a4-143">To enable the matching resource type capability, go to **Optimization Goals** and add it as a constraint.</span></span>

<span data-ttu-id="158a4-144">![最適化セットアップでのリソースの種類一致制約のスクリーンショット](../media/rso-resource-type-constraint.png "最適化セットアップでのリソースの種類一致制約のスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="158a4-144">![Screenshot of match resource type constraint in optimization setup](../media/rso-resource-type-constraint.png "Screenshot of match resource type constraint in optimization setup")</span></span>

<span data-ttu-id="158a4-145">*最適化セットアップでのリソースの種類一致制約*</span><span class="sxs-lookup"><span data-stu-id="158a4-145">*Match resource type constraint in optimization setup*</span></span>

<span data-ttu-id="158a4-146">最適化のゴールがアクティブな最適化スケジュールに関連している場合は、スケジュールを再公開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="158a4-146">If the Optimization Goal is related to an active Optimization Schedule, you will need to republish the schedule.</span></span>

## <a name="additional-notes"></a><span data-ttu-id="158a4-147">追加注記</span><span class="sxs-lookup"><span data-stu-id="158a4-147">Additional notes</span></span>

- <span data-ttu-id="158a4-148">リソース スケジュール最適化では、プールまたはスタッフのリソースの種類による要件は無視されます。</span><span class="sxs-lookup"><span data-stu-id="158a4-148">Resource Scheduling Optimization ignores requirements with the pool or crew resource type.</span></span>

- <span data-ttu-id="158a4-149">要件にリソースの種類**ユーザー**と**スタッフ**が含まれる場合 (たとえば、最適化によって考慮されるリソースの種類と考慮されないリソースの種類がある場合)、最適化はユーザー リソースを検索して要件を満たそうとします。</span><span class="sxs-lookup"><span data-stu-id="158a4-149">If a requirement includes the resource type **user** and **crew** (for example, if one resource type is considered by optimization and one isn't), the optimization attempts to find a user resource to fulfill the requirement.</span></span>

