---
title: "キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み"
description: "アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。"
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: c198c53f04636c4cbef3f6723cfa5246afc06cfa
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)


[!include[banner](../../includes/banner.md)]

エラーが発生します。  キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、これは希望するものとは異なる場合があります。  この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。

以前は、エラーと Null 値を判別できず、データベースに Null 値をプッシュするのは問題でした。  Null は多くのデータベース システムでは正当な値です。  キャンバス アプリではエラーが適切に分離されるため、すべてのデータベースに Null 値を書き込めます。

