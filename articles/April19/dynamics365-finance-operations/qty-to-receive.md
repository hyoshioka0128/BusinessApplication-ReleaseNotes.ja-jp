---
title: 受け取る数量を入力するための受領書フォームの新しいフィールド
description: 受け取った数量を記録し、部分出荷の残量を追跡します。
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 6e09d491a31aaaf6acbe3a00d7daa07921d16c4f
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225235"
---
# <a name="new-field-on-receipt-form-for-entering-quantity-to-receive"></a><span data-ttu-id="7bc64-103">受け取る数量を入力するための受領書フォームの新しいフィールド</span><span class="sxs-lookup"><span data-stu-id="7bc64-103">New field on receipt form for entering quantity to receive</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="7bc64-104">発注書が複数の出荷で受領されることがあります。</span><span class="sxs-lookup"><span data-stu-id="7bc64-104">Sometimes purchase orders are received over multiple shipments.</span></span> <span data-ttu-id="7bc64-105">実際に受け取った数量を正確に記録し、部分的な出荷から履行待ちのものを追跡するのが簡単になります。</span><span class="sxs-lookup"><span data-stu-id="7bc64-105">Now it is easier to correctly record the actual quantities received and keep track of what remains to be fulfilled from a partial shipment.</span></span> <span data-ttu-id="7bc64-106">[製品受領書] フォームには以下の列があります。</span><span class="sxs-lookup"><span data-stu-id="7bc64-106">The Product receipt form contains the following columns:</span></span>

- <span data-ttu-id="7bc64-107">[注文済数量] には、それに対して処理された変更注文を含む、元の発注書 (PO) の数量が反映されます。</span><span class="sxs-lookup"><span data-stu-id="7bc64-107">Quantity ordered reflects the original purchase order (PO) quantity, including any change orders processed against it.</span></span>
- <span data-ttu-id="7bc64-108">\[受け取った数量\] (既定では空白) には、現在受け取っている数量の値を入力する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7bc64-108">Quantity received (blank by default) requires you to enter a value for the quantity currently being received.</span></span>
- <span data-ttu-id="7bc64-109">[残余数量] には、元の PO 明細行から、その明細行に対して転記されたすべての受領の量を引いた数量が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7bc64-109">Quantity remaining displays the quantity from the original PO line reduced by amount of all posted receipts for the line.</span></span>

