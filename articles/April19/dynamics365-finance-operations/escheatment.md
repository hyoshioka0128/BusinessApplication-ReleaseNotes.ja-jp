---
title: 没収
description: 休眠状態の支払勘定から未請求の資金勘定へ資金を振り替えます。
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 66b303437117a417dede99161f2b5c36e11619c7
ms.sourcegitcommit: c8f2816cfd27cf7451e4651aa0038cc8400098d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2019
ms.locfileid: "895528"
---
# <a name="escheatment"></a>没収 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


現金および銀行管理モジュールを使用して、期限切れの証券または小切手を没収するように勘定を設定できます。 没収プロセスでは、元の受取人または指定された代理人による将来の請求の可能性に備えて、休眠状態の支払勘定から未請求の資金勘定へ資金を振り替える高度な元帳エントリが作成されます。

未請求の支払は、[転記の定義] フォームで設定されている没収の転記の定義に基づいて再分類され、[トランザクションの転記の定義] フォームの [一般会計] タブで設定されている没収トランザクションに割り当てられます。

