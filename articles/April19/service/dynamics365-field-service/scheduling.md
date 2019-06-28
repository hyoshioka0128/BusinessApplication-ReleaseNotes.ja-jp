---
title: スケジューリング機能
description: スケジューリング
author: dgittler
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dgittler
ms.reviewer: shellyha
ms.openlocfilehash: c0fef0a5704f73eb2d2a444d2d607ab01355bc63
ms.sourcegitcommit: 738a9a637dcc50b6ac52d47433e684ea61cedd52
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/07/2019
ms.locfileid: "1623898"
---
#  <a name="scheduling-capabilities"></a><span data-ttu-id="3be08-103">スケジューリング機能</span><span class="sxs-lookup"><span data-stu-id="3be08-103">Scheduling capabilities</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]


<span data-ttu-id="3be08-104">この記事では、2019 年 4 月リリースの新しいスケジューリング機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="3be08-104">This article describes the new scheduling capabilities in the April '19 release.</span></span>

## <a name="support-for-greater-than-1-resource-capacity"></a><span data-ttu-id="3be08-105">複数のリソース キャパシティのサポート</span><span class="sxs-lookup"><span data-stu-id="3be08-105">Support for greater than 1 resource capacity</span></span>

<span data-ttu-id="3be08-106">場合によっては、すべてのリソースが同じように生産的とは限りません。</span><span class="sxs-lookup"><span data-stu-id="3be08-106">In some cases, not all resources are equally productive.</span></span> <span data-ttu-id="3be08-107">たとえば、経験豊富な技術者は 2 台の自転車を同時に修理できますが、経験の浅い技術者は一度に 1 台の自転車しか作業できない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3be08-107">For example, a more experienced technician might be able to repair two bicycles simultaneously, while a less experienced technician can only work on one bicycle at a time.</span></span> <span data-ttu-id="3be08-108">このようなケースに対応するために、リソース スケジュール最適化は 1 を超えるキャパシティでリソースをスケジュールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3be08-108">To accommodate for such cases, Resource Scheduling Optimization is now able to schedule resources with a capacity greater than 1.</span></span>


## <a name="support-for-matches-resource-role-constraints"></a><span data-ttu-id="3be08-109">"リソースの種類に一致する" 制約のサポート</span><span class="sxs-lookup"><span data-stu-id="3be08-109">Support for "Matches Resource Role" constraints</span></span>

<span data-ttu-id="3be08-110">組織は要件に対するリソース ロールを定義できるようになりました。オプティマイザーは、一致したリソース ロールを持つリソースに予約を割り当てると同時に、他の定義済み制約を満たします。</span><span class="sxs-lookup"><span data-stu-id="3be08-110">Organizations can now define a resource role for requirements; the optimizer will assign bookings to resources with the matched resource role, while simultaneously meeting other defined constraints.</span></span>

## <a name="support-for-must-choose-resource-constraints"></a><span data-ttu-id="3be08-111">"リソースの選択が必要" 制約のサポート</span><span class="sxs-lookup"><span data-stu-id="3be08-111">Support for "Must Choose Resource" constraints</span></span>

<span data-ttu-id="3be08-112">特定のリソースを常に重要な顧客に派遣するなど、企業は顧客との間に特別な契約を結ぶことがあります。</span><span class="sxs-lookup"><span data-stu-id="3be08-112">Sometimes, businesses might have special commitments with their customers, like always dispatching specific resources to an important customer.</span></span> <span data-ttu-id="3be08-113">新しい**リソースの選択が必要**制約では、企業が要件に対するリソースの基本設定を定義できます。</span><span class="sxs-lookup"><span data-stu-id="3be08-113">With the new **Must Choose Resource** constraint, businesses will be able to define a resource preference for requirements.</span></span> <span data-ttu-id="3be08-114">オプティマイザーは、他の定義済み制約も満たしながら、**リソースの選択が必要**リストでリソースに予約を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="3be08-114">The optimizer will assign bookings to the resource in the **Must Choose Resource** list, while also meeting other defined constraints.</span></span>

## <a name="optimization-objective-for-as-soon-as-possible-asap"></a><span data-ttu-id="3be08-115">「できるだけ早く (ASAP)」の最適化目標</span><span class="sxs-lookup"><span data-stu-id="3be08-115">Optimization objective for as soon as possible (ASAP)</span></span> 

<span data-ttu-id="3be08-116">たまに (作業指示書などで) リソースのキャパシティがリソースの需要を超えることがあります。</span><span class="sxs-lookup"><span data-stu-id="3be08-116">Occasionally, there might be more resource capacity than there is demand for resources (for example, work orders).</span></span> <span data-ttu-id="3be08-117">そのような状況において、リソースの予定を完全に埋めてしまうか、緊急時や予定外の作業に備えてリソースを残しておくか、経営上の判断を求められます。</span><span class="sxs-lookup"><span data-stu-id="3be08-117">In these circumstances, there is a business decision about whether to fully book some resources or leave resources with some capacity as a contingency for emergency or unplanned work.</span></span>

<span data-ttu-id="3be08-118">2019 年 4 月のリリースでは、「できるだけ早く (ASAP)」という新しい目標が設定できるようになります。これにより、組織は他のスケジューリングの目標を選択して再度ランク付けすることで、一部のリソースを余裕を持って残しておくか、1 日の予定をすべて埋めてしまうか、バランスを取ることができます。</span><span class="sxs-lookup"><span data-stu-id="3be08-118">The April '19 release enables a new objective for as soon as possible (ASAP), so that organizations can select and rerank with other scheduling objectives to balance the need to reserve some capacity with the need to keep resources busy all day.</span></span>
