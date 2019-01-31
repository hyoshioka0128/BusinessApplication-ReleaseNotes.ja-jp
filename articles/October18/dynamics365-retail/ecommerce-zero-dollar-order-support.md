---
title: e コマースでのサンプル注文のサポート
description: このトピックでは、総額が $0 の場合でもエラーなしに e コマースの注文を処理できる機能拡張について説明します。
author: hhaines
manager: AnnBe
ms.date: 11/27/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: hhainesms
audience: Admin
ms.openlocfilehash: 1a28ad3a70a2c506575e6d2ca66b854aef3800ea
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199574"
---
# <a name="support-for-sample-orders-in-ecommerce"></a><span data-ttu-id="a694f-103">e コマースでのサンプル注文のサポート</span><span class="sxs-lookup"><span data-stu-id="a694f-103">Support for sample orders in Ecommerce</span></span>

<span data-ttu-id="a694f-104">一部の小売業者は、顧客にオンライン サイトを通じてサンプルを購入する機会を提供しています。</span><span class="sxs-lookup"><span data-stu-id="a694f-104">Certain retailers offer customers the opportunity to purchase samples through their online sites.</span></span> <span data-ttu-id="a694f-105">サンプルにはコストがかからず、顧客はサンプル品目の代金を支払う必要はありません </span><span class="sxs-lookup"><span data-stu-id="a694f-105">The samples have no cost and the customer doesn't have to pay for the sample item.</span></span> <span data-ttu-id="a694f-106">(これは、カーペット/フローリング、ペイント、窓処理などの業界では一般的です)。場合によっては、小売業者はサンプルを一定の期間内に返却してもらう必要があります。</span><span class="sxs-lookup"><span data-stu-id="a694f-106">(This is common in industries like carpet/flooring, paint, and window treatments.) In some cases, the retailer requires the samples be returned within a certain time frame.</span></span> <span data-ttu-id="a694f-107">顧客が指定された期間内にサンプルを返さないと、クレジット カードに請求されます。</span><span class="sxs-lookup"><span data-stu-id="a694f-107">If the customer fails to return the samples within the given time frame, their credit card is charged.</span></span> 

<span data-ttu-id="a694f-108">Dynamics 365 for Retail の現在の e コマース チェックアウトでは、ユーザーが価格 $0 で注文を送信しようとするとエラーがスローされます。</span><span class="sxs-lookup"><span data-stu-id="a694f-108">The current Ecommerce checkout in Dynamics 365 for Retail throws errors when a user attempts to submit an order with a $0 value.</span></span> <span data-ttu-id="a694f-109">新しい設計変更により、$0 での注文が許可されます。</span><span class="sxs-lookup"><span data-stu-id="a694f-109">With the new design change, orders for $0 will be permitted.</span></span>

<span data-ttu-id="a694f-110">この修正により、サンプルを提供する業界の小売業者や、オンライン ストアからの注文が可能な他の無料品目がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="a694f-110">With this fix, retailers in industries offering samples or other free items available to order from an online store will be supported.</span></span> <span data-ttu-id="a694f-111">サンプル注文は、これらの小売業者の e コマース サイトから作成および処理することができます。</span><span class="sxs-lookup"><span data-stu-id="a694f-111">Sample orders can be created and processed from these retailers' e-commerce sites.</span></span>


<!--
## License Required
No specific licensing requirements are required.
## Setup Required
No specific setup is required.
## Status
Development complete
## Target Timeframe
8.1.3 update
## Regional Availability
Global
-->
