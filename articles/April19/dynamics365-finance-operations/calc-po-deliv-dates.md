---
title: リード タイムと就業日に基づいて発注書の配送日を計算する
description: 仕入先のリード タイムに基づいて明細行の配送日を計算します。
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 5a0218c165f05ed34413a91e75fa21fcab8f56e6
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224916"
---
# <a name="calculate-purchase-order-delivery-dates-based-on-lead-times-and-working-days"></a><span data-ttu-id="0c198-103">リード タイムと就業日に基づいて発注書の配送日を計算する</span><span class="sxs-lookup"><span data-stu-id="0c198-103">Calculate purchase order delivery dates based on lead times and working days</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="0c198-104">仕入先のリード タイム ([見積依頼の返信] フォーム、[見積] タブ) および組織の就業日カレンダーに基づいて、明細行の配送日を計算します。</span><span class="sxs-lookup"><span data-stu-id="0c198-104">Calculate a delivery date for a line based on a vendor's lead time (Request for quotation reply form, Quotation tab) and your organization's working days calendar.</span></span> <span data-ttu-id="0c198-105">仕入先は各明細行のリード タイムを入力できます。</span><span class="sxs-lookup"><span data-stu-id="0c198-105">Vendors can enter a lead time for each line.</span></span> <span data-ttu-id="0c198-106">発注書が確認されると、リード タイムと就業日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。</span><span class="sxs-lookup"><span data-stu-id="0c198-106">When a purchase order is confirmed, a delivery date for a line is calculated from the confirmation date, based on the lead time and the working days calendar.</span></span> <span data-ttu-id="0c198-107">リード タイムが指定されていない場合は、配送日が確認日になります。</span><span class="sxs-lookup"><span data-stu-id="0c198-107">If no lead time is specified, the delivery date is the confirmation date.</span></span> <span data-ttu-id="0c198-108">明細行のリード タイム情報は、見積依頼の返信、購買要求、購買契約、発注書の各フォームで利用できます。</span><span class="sxs-lookup"><span data-stu-id="0c198-108">The lead time information for a line is available on these forms: Request for quotation reply, Purchase requisitions, Purchase agreements, and Purchase order.</span></span> <span data-ttu-id="0c198-109">アクション ウィンドウの [計算] タブの [配送日] ボタンを使用してフォーム内のすべての明細行の配送日を計算しても、リード タイム詳細は上書きされません。</span><span class="sxs-lookup"><span data-stu-id="0c198-109">The lead time details are not overwritten when delivery dates are calculated for all lines in the form, by using the Delivery dates button on the Calculate tab, on the Action Pane.</span></span> <span data-ttu-id="0c198-110">未確認または未承認のレコードのリード タイム詳細を更新できます。</span><span class="sxs-lookup"><span data-stu-id="0c198-110">You can update the lead time details for unconfirmed or unapproved records.</span></span>
