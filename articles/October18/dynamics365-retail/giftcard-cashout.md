---
title: 小売顧客に対するギフト カード残高のキャッシュ アウト
description: この機能により、小売顧客に対してギフト カード残高をキャッシュ アウトできるようになります。
author: rapraj
manager: AnnBe
ms.date: 01/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rapraj
audience: admin, IT admin
ms.openlocfilehash: d21133d5717ad928550bdfd1bcc8e1fd3e05155c
ms.sourcegitcommit: 44ed9eddd89e00c08da16c86bae997d3110a6e26
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "392128"
---
# <a name="cash-out-gift-card-balance-for-a-retail-customer"></a><span data-ttu-id="f6fd8-103">小売顧客に対するギフト カード残高のキャッシュ アウト</span><span class="sxs-lookup"><span data-stu-id="f6fd8-103">Cash out gift card balance for a retail customer</span></span>



<span data-ttu-id="f6fd8-104">小売業者はこの新しい機能を使用して、ギフト カードをキャッシュ アウトする新しい操作を設定し、キャッシュ アウト操作を有効にできるギフト カード残高の上限を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-104">This new feature gives retailers the option to set a new operation to cash out a gift card and to set the gift card balance limits under which the cash out operation can be enabled.</span></span> 

## <a name="business-value"></a><span data-ttu-id="f6fd8-105">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f6fd8-105">Business value</span></span>
<span data-ttu-id="f6fd8-106">この機能の目的は、レジ担当者がギフト カードの残高をキャッシュ アウトできるようにすることです。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-106">The purpose of this feature is to allow cashiers to cash out the remaining amount on a gift card.</span></span> <span data-ttu-id="f6fd8-107">小売業者が、顧客の要求に応じて残高の少ないギフト カードを現金に交換できることを求められる場合はよくあります。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-107">Retailers often must be able to exchange a low balance gift card for cash at the customer's request.</span></span> <span data-ttu-id="f6fd8-108">たとえば、ワシントン州では、そのしきい値は $5 です。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-108">In Washington state, for example, that threshold is $5.</span></span> 

## <a name="feature-description"></a><span data-ttu-id="f6fd8-109">機能の説明</span><span class="sxs-lookup"><span data-stu-id="f6fd8-109">Feature description</span></span>
<span data-ttu-id="f6fd8-110">販売時点管理 (POS) で、ギフト カードを効率的に現金と引き換える操作が実装されました。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-110">We have implemented an operation at the point of sale (POS) that effectively redeems a gift card for cash.</span></span> <span data-ttu-id="f6fd8-111">この操作は、明細行品目の売上を必要とせずに、ギフト カードの "加算" 操作のように動作する必要がありますが、ギフト カードの未払い残高を 0 に減少させます。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-111">This operation should not require the sale of any line item and should act like the "Add to" gift card operation, but decrementing the balance due on the gift card to zero.</span></span>  

## <a name="how-to-set-up-the-gift-card-cashout-feature"></a><span data-ttu-id="f6fd8-112">ギフト カードのキャッシュ アウト機能の設定方法</span><span class="sxs-lookup"><span data-stu-id="f6fd8-112">How to set up the gift card cashout feature</span></span>

<span data-ttu-id="f6fd8-113">構成は**小売店舗の設定** \> **支払方法**から行います。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-113">Configuration is done from **Retail Store Setup** \> **Payment Methods**.</span></span>

<span data-ttu-id="f6fd8-114">![小売店舗の設定](../../media/NoReceiptReturns1.png "小売店舗の設定")</span><span class="sxs-lookup"><span data-stu-id="f6fd8-114">![Retail store setup](../../media/NoReceiptReturns1.png "Retail Store Setup")</span></span> 

<span data-ttu-id="f6fd8-115">ギフト カードをキャッシュ アウトできるしきい値は、Dynamics の構成から取得されます。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-115">The threshold for which a gift card can be cashed out comes from the Dynamics configuration.</span></span>

<span data-ttu-id="f6fd8-116">![キャッシュ アウトの構成](../../media/GiftCardCashout01.png "ギフト カードのキャッシュ アウトの構成")</span><span class="sxs-lookup"><span data-stu-id="f6fd8-116">![Cashout configuration](../../media/GiftCardCashout01.png "Cash out gift card configuration")</span></span> 

<span data-ttu-id="f6fd8-117">しきい値の制限が追加された後に、POS のレイアウト デザイナーを使用して**ギフト カードをキャッシュ アウトする**という新しい操作を追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-117">After the threshold limits are added, the new operation **Cash out gift card** must be added using the POS layout designer.</span></span>

<span data-ttu-id="f6fd8-118">![POS のレイアウト デザイナー](../../media/GiftCardCashout02.png "POS のレイアウト デザイナー")</span><span class="sxs-lookup"><span data-stu-id="f6fd8-118">![POS layout designer](../../media/GiftCardCashout02.png "POS Layout Designer")</span></span> 

<span data-ttu-id="f6fd8-119">店舗への POS レイアウトの発行が完了したら、レジ担当者はこの機能を使用できます。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-119">Once the POS layout publish to the stores is complete, cashiers can use the feature.</span></span> 

<span data-ttu-id="f6fd8-120">![ギフト カードのキャッシュ アウト](../../media/GiftCardCashout03.png "ギフト カードのキャッシュ アウト")</span><span class="sxs-lookup"><span data-stu-id="f6fd8-120">![Gift card cash out](../../media/GiftCardCashout03.png "Gift Card Cash Out")</span></span> 

## <a name="out-of-scope"></a><span data-ttu-id="f6fd8-121">スコープ外</span><span class="sxs-lookup"><span data-stu-id="f6fd8-121">Out of scope</span></span>
- <span data-ttu-id="f6fd8-122">トランザクションの処理中にギフト カード残高がしきい値を下回った場合の自動キャッシュ アウト。</span><span class="sxs-lookup"><span data-stu-id="f6fd8-122">Automatic cash out if the gift card balance goes below a threshold amount during a transaction.</span></span> 

