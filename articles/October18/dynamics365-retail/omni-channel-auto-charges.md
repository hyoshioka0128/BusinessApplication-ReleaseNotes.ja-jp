---
title: "オムニチャネル自動請求"
description: "自動請求がすべての小売チャネルで機能します。"
author: hhainesms
manager: AnnBe
ms.date: 10/24/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: hhainesms
audience: 
ms.translationtype: HT
ms.sourcegitcommit: dbd8a17e3e500201426a03a48feb4bf5a2c7d024
ms.openlocfilehash: 7c3ee7600df9386cbf0b8c9e4221b23b164a97ee
ms.contentlocale: ja-jp
ms.lasthandoff: 11/01/2018

---

# <a name="omni-channel-auto-charges"></a><span data-ttu-id="313f5-103">オムニチャネル自動請求</span><span class="sxs-lookup"><span data-stu-id="313f5-103">Omni-channel auto-charges</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

<span data-ttu-id="313f5-104">小売業者は、購入品目の種類や注文に適用される出荷モードなど、販売注文の特性に基づいて顧客の販売取引に事前定義された料金を適用する機能を必要とします。</span><span class="sxs-lookup"><span data-stu-id="313f5-104">Retailers need the ability to have predefined charges applied to a customer’s sales transaction based on the characteristics of the sales order, including the types of items purchased and the delivery modes applied to the order.</span></span> <span data-ttu-id="313f5-105">多くの場合、顧客に対するこれらの料金は、運送費に関連する追加料金です (ただし、他の料金に関連する場合もあります)。</span><span class="sxs-lookup"><span data-stu-id="313f5-105">Often these charges to the customer are additional fees related to the cost of shipping (but could be related to other fees).</span></span>

<span data-ttu-id="313f5-106">Dynamics 365 for Finance and Operations の既存の自動請求機能が強化および拡張されて、販売チャネルに関係なく、すべての小売販売取引に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="313f5-106">The existing auto-charges features of Dynamics 365 for Finance and Operations will be enhanced and extended to be available for all Retail sales transactions regardless of sales channel.</span></span>

<span data-ttu-id="313f5-107">新しい計算ロジックが追加されます。</span><span class="sxs-lookup"><span data-stu-id="313f5-107">Additional calculation logic will be added.</span></span> <span data-ttu-id="313f5-108">この新しいロジックを構成すると、個々の販売明細とそれに関連する配送モードに基づいて、料金をいっそうきめ細かく計算できるようになります。</span><span class="sxs-lookup"><span data-stu-id="313f5-108">If configured, this new logic will allow for a more detailed calculation of charges based on the individual sales lines and their related delivery modes.</span></span>  <span data-ttu-id="313f5-109">これにより、各品目の配送モードに基づいて配送料金をより正確に計算することができ、明細レベルで料金を詳細に追跡できます。これは、返品処理時に役立つ可能性があります。</span><span class="sxs-lookup"><span data-stu-id="313f5-109">This allows for a more accurate calculation of delivery fees based on mode of delivery for each item and allows for more detailed tracking of the charges at the line level, which can be useful when processing returns.</span></span>

<span data-ttu-id="313f5-110">この機能の目標は、すべての小売販売チャネルで機能する一貫した構成と計算ロジックを提供することです。</span><span class="sxs-lookup"><span data-stu-id="313f5-110">Our goal with this feature is to provide a consistent set of configurations and calculation logic that will work in every Retail sales channel.</span></span>

