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
# <a name="new-field-on-receipt-form-for-entering-quantity-to-receive"></a>受け取る数量を入力するための受領書フォームの新しいフィールド 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


発注書が複数の出荷で受領されることがあります。 実際に受け取った数量を正確に記録し、部分的な出荷から履行待ちのものを追跡するのが簡単になります。 [製品受領書] フォームには以下の列があります。

- [注文済数量] には、それに対して処理された変更注文を含む、元の発注書 (PO) の数量が反映されます。
- \[受け取った数量\] (既定では空白) には、現在受け取っている数量の値を入力する必要があります。
- [残余数量] には、元の PO 明細行から、その明細行に対して転記されたすべての受領の量を引いた数量が表示されます。

