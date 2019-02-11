---
title: 製品バリアントの測定単位換算
description: 以前は、製品バリアント レベルでの測定単位 (UoM) の換算は、特定の倉庫管理シナリオのセットでのみサポートされていました。 この機能が、アプリケーション全体の製品バリアント レベルでの UoM 変換をサポートするように拡張されました。
author: sorenva
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: sorenand
ms.openlocfilehash: a488d97b2c925e4b2269bc3c79347c65d2085241
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210748"
---
#  <a name="unit-of-measure-conversions-for-product-variants"></a><span data-ttu-id="bc265-104">製品バリアントの測定単位換算</span><span class="sxs-lookup"><span data-stu-id="bc265-104">Unit of measure conversions for product variants</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="bc265-105">以前は、製品バリアント レベルでの測定単位 (UoM) の換算は、特定の倉庫管理シナリオのセットでのみサポートされていました。</span><span class="sxs-lookup"><span data-stu-id="bc265-105">Unit of measure (UoM) conversions at the product variant level have previously been supported only in a select set of warehouse management scenarios.</span></span> <span data-ttu-id="bc265-106">この機能が、アプリケーション全体の製品バリアント レベルでの UoM 変換をサポートするように拡張されました。</span><span class="sxs-lookup"><span data-stu-id="bc265-106">This functionality has now been expanded to provide support for UoM conversions at the product variant level throughout the application.</span></span>

<span data-ttu-id="bc265-107">製品バリアントを使用すると、個別のメンテナンスが必要な製品を複数作成する代わりに、製品のバリエーションを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="bc265-107">You can use product variants to create variations of a product instead of creating several individual products that have to be maintained.</span></span> <span data-ttu-id="bc265-108">たとえば、製品バリアントによって、特定のサイズや色の T シャツを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="bc265-108">A product variant could, for example, be a t-shirt of a given size and color.</span></span> <span data-ttu-id="bc265-109">これまで、単位換算は製品マスターに対してしか設定できなかったので、製品バリアントにはすべて同じ単位換算ルールが適用されていました。</span><span class="sxs-lookup"><span data-stu-id="bc265-109">So far, it has only been possible to set up the unit conversion on the product master, so all the product variants had the same unit conversion rules.</span></span> <span data-ttu-id="bc265-110">たとえば、T シャツが箱で販売されている場合、箱に収まる T シャツの数が T シャツのサイズによって異なる場合は、この新しい機能を使用することで、Tシャツの各サイズと、包装に使われる箱との間の単位変換を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="bc265-110">If the t-shirts, for example, are sold in boxes, and the number of t-shirts that can be packed in a box depends on the size of the t-shirts, then this new feature can be used to set up the unit conversions between the different shirt sizes and the boxes used for packaging.</span></span>

<span data-ttu-id="bc265-111">この機能の一般的な使用は、**製品情報管理パラメーター** ページで有効化します。</span><span class="sxs-lookup"><span data-stu-id="bc265-111">The general use of the feature is enabled in the **Product information management parameters** page.</span></span> <span data-ttu-id="bc265-112">この機能は、すべての製品マスターに対して有効にすることもできますし、倉庫プロセス用に有効化されている製品マスターに対してのみ有効化することもできます。</span><span class="sxs-lookup"><span data-stu-id="bc265-112">The feature is enabled for all products masters or only for product masters enabled for the warehouse processes.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="bc265-113">![[製品情報管理パラメーター] ページで製品バリアントによる測定単位換算を有効にする](media/uom-setup-1.png "[製品情報管理パラメーター] ページで製品バリアントによる測定単位換算を有効にする")</span><span class="sxs-lookup"><span data-stu-id="bc265-113">![Enabling unit of measure conversions by product variants on the Product information management parameters page](media/uom-setup-1.png "Enabling unit of measure conversions by product variants on the Product information management parameters page")</span></span>

<span data-ttu-id="bc265-114">特定の製品マスターの場合は、**製品詳細**ページの**測定単位換算の有効化**フィールドをオンにして機能を有効化します。</span><span class="sxs-lookup"><span data-stu-id="bc265-114">For a specific product master, the feature is enabled by selecting the **Enable unit of measure conversions** field on the **Product details** page.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="bc265-115">![[製品詳細] ページで特定の製品マスターの製品バリアントによる測定単位換算を有効にする](media/uom-setup-2.png "[製品詳細] ページで特定の製品マスターの製品バリアントによる測定単位換算を有効にする")</span><span class="sxs-lookup"><span data-stu-id="bc265-115">![Enabling unit of measure conversions by product variants for a specific product master on the Product details page](media/uom-setup-2.png "Enabling unit of measure conversions by product variants for a specific product master on the Product details page")</span></span>

<span data-ttu-id="bc265-116">この例では、T シャツに 3 つの製品バリアントがリリースされています (Large、Medium、Small)。</span><span class="sxs-lookup"><span data-stu-id="bc265-116">In this example the t-shirt has three released product variants: Large, Medium, and Small.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="bc265-117">![T シャツの 3 つのバリアント (Large、Medium、Small) が表示された [リリース済製品バリアント] ページ](media/uom-setup-3.png "T シャツの 3 つのバリアント (Large、Medium、Small) が表示された [リリース済製品バリアント] ページ")</span><span class="sxs-lookup"><span data-stu-id="bc265-117">![Released product variants page showing three t-shirt variants: Large, Medium, and Small](media/uom-setup-3.png "Released product variants page showing three t-shirt variants: Large, Medium, and Small")</span></span>

<span data-ttu-id="bc265-118">製品マスターから、**単位換算**ページを開くことができます。</span><span class="sxs-lookup"><span data-stu-id="bc265-118">From the Product master you can open the **Unit conversions** page.</span></span> <span data-ttu-id="bc265-119">このページではまず、単位換算を製品に対して設定するのか、それとも製品バリアントに対して設定するのかを選択します。</span><span class="sxs-lookup"><span data-stu-id="bc265-119">On this page, you first select whether you are setting up the unit conversion for the product or the product variant.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="bc265-120">![[単位変換] ページで、単位変換を製品バリアントに対して設定するのか、それとも製品マスターに対して設定するのかを選択する](media/uom-setup-4.png "[単位変換] ページで、単位変換を製品バリアントに対して設定するのか、それとも製品マスターに対して設定するのかを選択する")</span><span class="sxs-lookup"><span data-stu-id="bc265-120">![Selecting whether to set up unit of measure conversions for product variants or the product master on the Unit conversions page](media/uom-setup-4.png "Selecting whether to set up unit of measure conversions for product variants or the product master on the Unit conversions page")</span></span>

<span data-ttu-id="bc265-121">**製品バリアント**を選択した場合は、特定の製品バリアントに対して単位変換が設定されます。</span><span class="sxs-lookup"><span data-stu-id="bc265-121">If you select **Product variant**, you set up the unit conversion for a specific product variant.</span></span> <span data-ttu-id="bc265-122">この例では、単位 "Box" と単位 "Ea" の間の単位換算が、Small サイズのＴシャツに対して設定されます。</span><span class="sxs-lookup"><span data-stu-id="bc265-122">In this example, the unit conversion between the units "Box" and "Ea" is set up for the t-shirt in size small.</span></span> 

<span data-ttu-id="bc265-123">**製品**を選択した場合は、製品マスターに対して単位換算が設定されます。この単位換算は、単位換算が定義されていないすべての製品バリアントのフォールバックとして機能します。</span><span class="sxs-lookup"><span data-stu-id="bc265-123">If you select **Product**, you set up the unit conversion for the product master, and this unit conversion will serve as fallback for all product variants that have no unit conversion defined.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="bc265-124">![単位変換ページで製品マスターのフォールバック測定単位変換を定義する](media/uom-setup-5.png "単位変換ページで製品マスターのフォールバック測定単位変換を定義する")</span><span class="sxs-lookup"><span data-stu-id="bc265-124">![Defining fallback unit of measure conversions for the product master on the Unit conversions page](media/uom-setup-5.png "Defining fallback unit of measure conversions for the product master on the Unit conversions page")</span></span>
