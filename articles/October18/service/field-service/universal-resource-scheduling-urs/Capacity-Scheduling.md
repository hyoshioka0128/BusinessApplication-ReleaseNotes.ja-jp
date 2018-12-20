---
title: "キャパシティのスケジューリング"
description: "キャパシティのスケジューリング"
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
ms.sourcegitcommit: 564b2b697e5130b078dc81d04f3541919e4f1b8a
ms.openlocfilehash: 3315fe5725455f860b3e82a9c08ce8ef50dd123f
ms.contentlocale: ja-jp
ms.lasthandoff: 11/08/2018

---




#  <a name="capacity-scheduling"></a><span data-ttu-id="2a7f0-103">キャパシティのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="2a7f0-103">Capacity scheduling</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="2a7f0-104">リソース要件では、要件でリソースに要求される作業量を指定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-104">Resource requirements can now specify how much effort a requirement needs from a resource.</span></span> <span data-ttu-id="2a7f0-105">スケジュールのとき、スケジュール アシスタントはリソースに定義されている作業時間キャパシティを調べて、必要な作業量を確保できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-105">When scheduling, the Schedule Assistant will look at a resource’s defined capacity on its work hours to check if the necessary effort is available.</span></span> <span data-ttu-id="2a7f0-106">リソースのキャパシティは 1 日のうちでも変換することがあります。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-106">A resource's capacity can vary even within a day.</span></span>

<span data-ttu-id="2a7f0-107">キャパシティ スケジューリングは、設備を予約するときに特に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-107">Capacity scheduling is exceptionally useful when booking a facility.</span></span> <span data-ttu-id="2a7f0-108">たとえば、バンでは標準的な自動車の 2 倍のスペースが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-108">By way of example, a van may require twice the space as a standard car.</span></span> <span data-ttu-id="2a7f0-109">特定のキャパシティの設備を作成できますが、バンで作業時間を予約するときは、2 台の自動車または 6 台のオートバイを登録する場合と同じ設備キャパシティが消費されます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-109">You can now create a facility with a certain capacity, but when booking time to work on a van, it consumes the capacity of the facility as if you were booking two cars or six motorcycles.</span></span>

<span data-ttu-id="2a7f0-110">スケジュール ボードでは、特定の時間にリソースが予約されていてもリソースに追加キャパシティがあるときのビジュアル インジケーターも提供されます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-110">The Schedule Board will also offer a visual indicator when a resource has additional capacity even though there is a booking at a given time.</span></span>

* <span data-ttu-id="2a7f0-111">サンプル使用事例</span><span class="sxs-lookup"><span data-stu-id="2a7f0-111">Sample use cases</span></span>
    * <span data-ttu-id="2a7f0-112">リソースが指定されていないときのスタッフの増強。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-112">Staff augmentation where resources are unnamed.</span></span>
    * <span data-ttu-id="2a7f0-113">効率的なリソース。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-113">Efficient resources.</span></span>
        * <span data-ttu-id="2a7f0-114">標準的なユーザーが 1 台のバイクを手配できるときに、ユーザーは 2 台のバイクを手配できます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-114">Person can fix two bikes in the time a typical person can fix one.</span></span>
    * <span data-ttu-id="2a7f0-115">物理的な空間。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-115">Physical space.</span></span>
        * <span data-ttu-id="2a7f0-116">1 つのワークスペースが 2 台の自動車または 1 台のバンを手配できます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-116">One workspace can fit two cars or one van.</span></span>
        * <span data-ttu-id="2a7f0-117">リソースとして「クラス」を作成し、最大 10 人の顧客をクラスに予約できます。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-117">Create a “class” as a resource, and allow up to 10 customers to be booked to the class.</span></span>
> <span data-ttu-id="2a7f0-118">オンサイト作業を実行するリソースは、複数のキャパシティを持つことはできません。</span><span class="sxs-lookup"><span data-stu-id="2a7f0-118">Resources that perform onsite work cannot have a capacity of more than one.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="2a7f0-119">![追加容量行が展開されたリソースを示すスケジュール ボード](media/Additional-Capacity.png "追加キャパシティ")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="2a7f0-119">![Schedule Board showing a resource with additional capacity row expanded](media/Additional-Capacity.png "Additional capacity")
<!-- picture --></span></span>

<span data-ttu-id="2a7f0-120">*追加容量行が展開されたリソースを示すスケジュール ボード*</span><span class="sxs-lookup"><span data-stu-id="2a7f0-120">*Schedule Board showing a resource with additional capacity row expanded*</span></span>

