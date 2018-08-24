---
title: "キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み"
description: "アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。"
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: e79ea4939906626d448c7a389f7507061bed596b
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a>キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み

[!include[powerapps banner](../includes/powerapps.md)]




エラーは発生します。  キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、これは希望するものとは異なる場合があります。  この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。

以前は、エラーと Null 値を判別できず、データベースに Null 値をプッシュするのは問題でした。  Null は多くのデータベース システムでは正当な値です。  キャンバス アプリではエラーが適切に分離されるため、すべてのデータベースに Null 値を書き込めます。

