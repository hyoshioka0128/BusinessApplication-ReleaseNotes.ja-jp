---
title: 明細行間に割引を分散する
description: 最安値組み合わせ割引のために明細行間に割引を分散させます
author: ReneeW-CPub
ms.date: 05/21/2019
ms.topic: article
ms.service: business-applications
ms.author: shajain
ms.openlocfilehash: 2d6d642fc799748799259ede89cd040cf11f7842
ms.sourcegitcommit: cab3880e061232d8975a39a1fb6952556bd55274
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1595039"
---
#  <a name="distribute-discount-across-lines-for-least-expensive-discounts"></a><span data-ttu-id="3faed-103">最安値割引のために明細行間に割引を分散させる</span><span class="sxs-lookup"><span data-stu-id="3faed-103">Distribute discount across lines for least expensive discounts</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


## <a name="business-value"></a><span data-ttu-id="3faed-104">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3faed-104">Business value</span></span>

<span data-ttu-id="3faed-105">今日の小売業者は、顧客に製品を購入させるために複数の種類のプロモーションを行っています。</span><span class="sxs-lookup"><span data-stu-id="3faed-105">Retailers today run multiple types of promotions that encourage customers to purchase products.</span></span> <span data-ttu-id="3faed-106">しかし、顧客は購入した商品の一部または全部を返品することがあります。</span><span class="sxs-lookup"><span data-stu-id="3faed-106">Sometimes, however, customers return some or all of the purchased merchandise.</span></span> <span data-ttu-id="3faed-107">一般に、返品された商品は高い割引で販売されるため、小売業者の収益に大きな影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="3faed-107">The returned merchandise is generally sold at high discounts and thus has a huge impact on the bottom line of the retailer.</span></span> <span data-ttu-id="3faed-108">返品による損失を減らすことができる改善は、小売業者にとって非常に有益です。</span><span class="sxs-lookup"><span data-stu-id="3faed-108">Improvements that can reduce the loss for returns are very beneficial for retailers.</span></span>

## <a name="feature-description"></a><span data-ttu-id="3faed-109">機能の説明</span><span class="sxs-lookup"><span data-stu-id="3faed-109">Feature description</span></span>

<span data-ttu-id="3faed-110">Dynamics 365 for Retail では、カートに入っている他の品目に依存する多くの割引がサポートされています。たとえば、数量、組み合わせ、しきい値などの割引です。</span><span class="sxs-lookup"><span data-stu-id="3faed-110">Dynamics 365 for Retail supports many discounts that depend on other items present in the cart; for example, quantity, mix and match, and threshold discounts.</span></span> <span data-ttu-id="3faed-111">ほとんどの場合、適用可能な割引はすべての割引明細行に比例的に分散されます。</span><span class="sxs-lookup"><span data-stu-id="3faed-111">In most cases, the applicable discount is distributed proportionally on all the discount lines.</span></span> <span data-ttu-id="3faed-112">ただし、"最安値組み合わせ" 割引の場合は、割引は最も安い明細行にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="3faed-112">However, for "least expensive mix and match" discounts, the discount is applied only on the least expensive lines.</span></span> <span data-ttu-id="3faed-113">たとえば、"2 つ買えば 1 つ無料" では、最も安い品目は無料になり、カートには他の 2 つの品目の全額が表示されます。</span><span class="sxs-lookup"><span data-stu-id="3faed-113">For example, "buy 2 get 1 free" would result in the least expensive item to be free and the cart would show full price for the other two items.</span></span> <span data-ttu-id="3faed-114">顧客が全額品目を両方とも返品した場合、顧客は 3 番目の品目を無料で入手することになり、小売業者にとっての損失となります。</span><span class="sxs-lookup"><span data-stu-id="3faed-114">If the customer returns both of the full-priced items, they would get the third item for free, which causes a loss for the retailer.</span></span> <span data-ttu-id="3faed-115">この機能を使用すると、小売業者はオプションで該当するすべての明細行に割引を分散できるため、返品による損失を減らすことができます。</span><span class="sxs-lookup"><span data-stu-id="3faed-115">With this feature, retailers can optionally distribute the discount on all the applicable lines, thus reducing the loss on the returns.</span></span> <span data-ttu-id="3faed-116">この機能は、**小売パラメーター** ページの**割引**タブにある**最安値割引の割引を分散させる**パラメーターをオンにすることで有効にできます。</span><span class="sxs-lookup"><span data-stu-id="3faed-116">This capability can be easily enabled by turning on the **Distribute discount for least expensive discounts** parameter located on the **Discounts** tab on the **Retail parameters** page.</span></span>
