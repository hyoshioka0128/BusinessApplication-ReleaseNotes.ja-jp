---
title: "二重通貨"
description: "二重通貨"
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 7256af54b5d02188d150b37520142196b0b38b4a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="dual-currency"></a>二重通貨

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



レポート通貨は、真の第 2 の会計通貨に目的変更されます。 総勘定元帳の観点からは、レポート通貨は引き続き総勘定元帳に転記されるすべてのトランザクションに対して計算されます。  一部の総勘定元帳プロセスは強化され、レポート通貨でのみトランザクションを転記するための新しい仕訳が追加されます。 固定資産などのさまざまな補助元帳については、より大きな変更があります。 固定資産の場合、すべてのトランザクションをレポート通貨の補助元帳に保持するようになります。 減価償却を実行すると、会計通貨の場合と同じように、減価償却方法を使用してレポート通貨の金額が減価償却されます。 影響を受ける他の補助元帳モジュールとしては、買掛金勘定、売掛金勘定、現金管理があります。

