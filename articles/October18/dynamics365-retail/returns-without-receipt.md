---
title: 領収書のない返品に対する支払方法の制限
description: 領収書のない返品に対する支払方法を制限する機能
author: rapraj
manager: AnnBe
ms.date: 01/17/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rapraj
audience: admin, IT admin
ms.openlocfilehash: 014b314b951ef43e36505a6962e2789edd6611a6
ms.sourcegitcommit: 44ed9eddd89e00c08da16c86bae997d3110a6e26
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "392078"
---
# <a name="payment-method-restrictions-for-returns-without-a-receipt"></a><span data-ttu-id="c48fe-103">領収書のない返品に対する支払方法の制限</span><span class="sxs-lookup"><span data-stu-id="c48fe-103">Payment method restrictions for returns without a receipt</span></span>



<span data-ttu-id="c48fe-104">返品は小売業者にとって不可欠な操作です。</span><span class="sxs-lookup"><span data-stu-id="c48fe-104">Returns are an integral operation for a retailer.</span></span> <span data-ttu-id="c48fe-105">返品条件と払戻のガイドラインは通常、会社レベルで設定され、店舗レベルで適用されます。レジ担当者には特定の特権が与えられ、マネージャー/上級スタッフにはいくつかの上書きアクセス許可が与えられます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-105">Return policies and refund guidelines are generally set at a company level and enforced at a store level with certain privileges for cashiers and a few override permissions for the managers/senior staff.</span></span> 

<span data-ttu-id="c48fe-106">Dynamics 365 for Retail には、小売業者が返品とその払戻を処理できる返品機能があります。</span><span class="sxs-lookup"><span data-stu-id="c48fe-106">Dynamics 365 for Retail has returns capabilities that allow retailers to process returns and their refunds.</span></span> 

<span data-ttu-id="c48fe-107">この新しい機能を使用して、小売業者は領収書の要件に制限を設定したり、資金を複数の支払/入金タイプに処理したり、返品が領収書なしで処理されたときの払戻を特定の支払方法に制限したりできます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-107">This new feature enables retailers to set restrictions on requirements for receipts, process funds to multiple tender types, or restrict the refunds to certain payment methods when the returns are processed without receipts.</span></span> 

## <a name="business-value"></a><span data-ttu-id="c48fe-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c48fe-108">Business value</span></span>
<span data-ttu-id="c48fe-109">小売店舗は返品と払戻の要求を頻繁に受けます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-109">Retail stores get returns and refund requests frequently.</span></span> <span data-ttu-id="c48fe-110">これはコール センターやオンライン チャネルにも当てはまります。</span><span class="sxs-lookup"><span data-stu-id="c48fe-110">This is true for call centers and online channels as well.</span></span> <span data-ttu-id="c48fe-111">場合によっては領収書とトランザクション ID がなくても返品が要求されることがあり、小売業者にとっては、それが正当な返品であることを確認するというリスク要因が増加します。</span><span class="sxs-lookup"><span data-stu-id="c48fe-111">In some cases the returns may be requested without the presence of a receipt and transaction ID, increasing the risk factor for the retailer to confirm it is a genuine return.</span></span> 

<span data-ttu-id="c48fe-112">顧客ロイヤルティとブランド イメージを維持するために、領収書のない返品が受け入れられることはよくあります。</span><span class="sxs-lookup"><span data-stu-id="c48fe-112">To maintain customer loyalty and brand consciousness, returns are often accepted without a receipt.</span></span> <span data-ttu-id="c48fe-113">ただし、不正な返品のリスクを低減するために、現金や小切手などの払戻の支払方法を制限し、ギフト カードなどの特定の支払方法を許可することができます。これにより、ビジネスの継続を保証し、収益の損失を防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-113">However, to lower the risk of fraudulent returns, the refund payment methods like cash or check can be restricted and certain payment methods such as gift cards can be allowed to ensure continued business and prevent loss of revenue.</span></span> 

## <a name="how-to-use-the-returns-feature"></a><span data-ttu-id="c48fe-114">返品機能の使用方法</span><span class="sxs-lookup"><span data-stu-id="c48fe-114">How to use the returns feature</span></span>
<span data-ttu-id="c48fe-115">小売店舗の設定に対する新しい機能強化により、各店舗で支払方法タイプごとに支払方法を制限または許可できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c48fe-115">With the new enhancements to the retail store setup, payment methods can be restricted or allowed at each store for the payment method type.</span></span> <span data-ttu-id="c48fe-116">これにより小売業者は、領収書のない返品が処理されるときに店舗のタイプに基づいて特定の支払方法を許可または制限するよう、きめ細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-116">This gives very granular control to the retailers based on the type of store to allow or restrict certain payment methods when the returns are processed without a receipt.</span></span> 

<span data-ttu-id="c48fe-117">構成は**小売店舗の設定** \> **支払方法**から行います。</span><span class="sxs-lookup"><span data-stu-id="c48fe-117">Configuration is done from **Retail Store Setup** \> **Payment Methods**.</span></span>

<span data-ttu-id="c48fe-118">![小売店舗の設定](../../media/NoReceiptReturns1.png "小売店舗の設定")</span><span class="sxs-lookup"><span data-stu-id="c48fe-118">![Retail Store Setup](../../media/NoReceiptReturns1.png "Retail Store Setup")</span></span> 

<span data-ttu-id="c48fe-119">店舗で使用できる支払方法ごとに、**領収書のない払戻の制限**という新しい構成パラメーターを設定できます。</span><span class="sxs-lookup"><span data-stu-id="c48fe-119">For each payment method that is available to the store, a new configuration parameter called **Restrict refunds without receipt** is available.</span></span> 

<span data-ttu-id="c48fe-120">![支払方法の構成](../../media/NoReceiptReturns2.png  "支払方法の構成")</span><span class="sxs-lookup"><span data-stu-id="c48fe-120">![Payment method configuration](../../media/NoReceiptReturns2.png  "Payment method configuration")</span></span> 

<span data-ttu-id="c48fe-121">このパラメーターが**はい**に設定された場合、領収書のない返品が処理されるときにプロンプトが表示され、レジ担当者がその支払方法を選択できなくなります。</span><span class="sxs-lookup"><span data-stu-id="c48fe-121">If the parameter is set to **Yes**, a prompt will be displayed that stops the cashier from selecting the payment method if there is return without receipt being processed.</span></span> 
