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
# <a name="cash-out-gift-card-balance-for-a-retail-customer"></a>小売顧客に対するギフト カード残高のキャッシュ アウト



小売業者はこの新しい機能を使用して、ギフト カードをキャッシュ アウトする新しい操作を設定し、キャッシュ アウト操作を有効にできるギフト カード残高の上限を設定することができます。 

## <a name="business-value"></a>ビジネス バリュー
この機能の目的は、レジ担当者がギフト カードの残高をキャッシュ アウトできるようにすることです。 小売業者が、顧客の要求に応じて残高の少ないギフト カードを現金に交換できることを求められる場合はよくあります。 たとえば、ワシントン州では、そのしきい値は $5 です。 

## <a name="feature-description"></a>機能の説明
販売時点管理 (POS) で、ギフト カードを効率的に現金と引き換える操作が実装されました。 この操作は、明細行品目の売上を必要とせずに、ギフト カードの "加算" 操作のように動作する必要がありますが、ギフト カードの未払い残高を 0 に減少させます。  

## <a name="how-to-set-up-the-gift-card-cashout-feature"></a>ギフト カードのキャッシュ アウト機能の設定方法

構成は**小売店舗の設定** \> **支払方法**から行います。

![小売店舗の設定](../../media/NoReceiptReturns1.png "小売店舗の設定") 

ギフト カードをキャッシュ アウトできるしきい値は、Dynamics の構成から取得されます。

![キャッシュ アウトの構成](../../media/GiftCardCashout01.png "ギフト カードのキャッシュ アウトの構成") 

しきい値の制限が追加された後に、POS のレイアウト デザイナーを使用して**ギフト カードをキャッシュ アウトする**という新しい操作を追加する必要があります。

![POS のレイアウト デザイナー](../../media/GiftCardCashout02.png "POS のレイアウト デザイナー") 

店舗への POS レイアウトの発行が完了したら、レジ担当者はこの機能を使用できます。 

![ギフト カードのキャッシュ アウト](../../media/GiftCardCashout03.png "ギフト カードのキャッシュ アウト") 

## <a name="out-of-scope"></a>スコープ外
- トランザクションの処理中にギフト カード残高がしきい値を下回った場合の自動キャッシュ アウト。 

