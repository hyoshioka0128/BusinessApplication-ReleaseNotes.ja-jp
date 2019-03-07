---
title: キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み
description: アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/04/2019
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: a8e17d4fafd163d177d453ed9f0c327e1043193c
ms.sourcegitcommit: b0c22af04369d4d8d0d0a5d67c06d26b3474ceb6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/11/2019
ms.locfileid: "379456"
---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)




アプリを作成中にエラーが発生するのは仕方がないことです。 キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。 この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。

以前は、エラーと Null 値を判別できてないにもかかわらず、データベースに Null 値を書き込むのは問題でした。 Null は多くのデータベース システムでは正当な値です。 キャンバス アプリでエラーの場合と適切に分離することにより、すべてのデータベースに Null 値を書き込めます。