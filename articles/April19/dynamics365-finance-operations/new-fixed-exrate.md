---
title: 仕入先請求書、販売注文、および販売契約書の新しい固定為替レート
description: レポート通貨用の新しい固定為替レートが複数の場所に追加されました。
author: aprilolson
ms.date: 05/21/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 65dbb726c64baa6c7ca8793201dd62384e8d47f2
ms.sourcegitcommit: d82ae752fb528c3b0b5e418efa27b7150e6f6613
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1594855"
---
# <a name="new-fixed-exchange-rate-in-vendor-invoices-sales-orders-and-sales-agreements"></a>仕入先請求書、販売注文、および販売契約書の新しい固定為替レート
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


仕入先請求書、販売注文、および販売契約書は、レポート通貨の固定為替レートを含むように更新されました。 取引通貨が異なる場合は、会計通貨とレポート通貨の両方に固定為替レートを定義できます。 これで二重通貨に必要なレートが完成します。

会計通貨とレポート通貨が同じ場合、会計通貨の固定レートの既定をレポート通貨の固定レートに設定することで、固定為替レートの同期が維持されます。 このセットアップ構成では、レポート通貨の固定為替レートを変更できません。 会計通貨とレポート通貨が異なる場合は、取引の入力時に会計通貨とレポート通貨の両方に固定為替レートを定義できます。 元帳にレポート通貨が定義されていない場合、レポート通貨の固定為替レート フィールドは有効にならず、レポート通貨金額は計算されません。
