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
ms.sourcegitcommit: c8f2816cfd27cf7451e4651aa0038cc8400098d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2019
ms.locfileid: "895557"
---
# <a name="calculate-purchase-order-delivery-dates-based-on-lead-times-and-working-days"></a>リード タイムと就業日に基づいて発注書の配送日を計算する 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


仕入先のリード タイム ([見積依頼の返信] フォーム、[見積] タブ) および組織の就業日カレンダーに基づいて、明細行の配送日を計算します。 仕入先は各明細行のリード タイムを入力できます。 発注書が確認されると、リード タイムと就業日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。 リード タイムが指定されていない場合は、配送日が確認日になります。 明細行のリード タイム情報は、見積依頼の返信、購買要求、購買契約、発注書の各フォームで利用できます。 アクション ウィンドウの [計算] タブの [配送日] ボタンを使用してフォーム内のすべての明細行の配送日を計算しても、リード タイム詳細は上書きされません。 未確認または未承認のレコードのリード タイム詳細を更新できます。
