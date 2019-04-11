---
title: 現金管理
description: 現金残高がない場合に転記を防ぐための限度を定義します
author: aprilolson
ms.date: 03/06/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 48178ebd03ff4fe987e4a22449b1fa64cacd58e6
ms.sourcegitcommit: c8f2816cfd27cf7451e4651aa0038cc8400098d4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/25/2019
ms.locfileid: "895494"
---
# <a name="cash-control"></a>現金管理 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


現金管理では、利用可能な現金残高がない場合、またはトランザクションが原因で残高が定義済みの限度を下回る場合に追加のトランザクションが転記されるのを防ぐための限度を定義できます。 買掛金勘定仕入先請求書および一般会計の詳細な元帳エントリは、作成、編集、および転記時に検証されます。 トランザクションの転記が原因で、関連する現金勘定の残高がその勘定に定義されている限度を下回ると、エラー メッセージが表示され、続行するにはユーザーが勘定を変更する必要があります。

特定のユーザーが現金管理を上書きできるようにすることもできます。 許可されたユーザーが、勘定の現金残高が限度額を下回るという警告を受けた場合、ユーザーはトランザクションの転記を続けることを任意に選択できます。 経費をカバーするための資金を受け取る前にその経費を転記する必要がある場合、または承認された送金が行われる必要があるがまだ入力または転記されていない場合、ユーザーは現金管理限度額を上書きできます。

現金管理限度額は、現金管理残高 (現金勘定残高からすべての転記済み未払い AP 請求書を差し引いたもの) と比較されます。 現金管理残高が現金管理限度額 (しきい値) を下回ると、限度額を超過します。

