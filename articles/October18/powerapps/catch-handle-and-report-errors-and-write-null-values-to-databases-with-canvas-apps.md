---
title: キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み
description: アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/19/2019
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: 33c9ca087eda8cc94604b32d65cc3729921a6630
ms.sourcegitcommit: 1a61095607f38831541a95f4ceb2a54bb756a41b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "879823"
---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)




アプリを作成中にエラーが発生するのは仕方がないことです。 キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。 この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。

以前は、エラーと Null 値を判別できてないにもかかわらず、データベースに Null 値を書き込むのは問題でした。 Null は多くのデータベース システムでは正当な値です。 キャンバス アプリでエラーの場合と適切に分離することにより、すべてのデータベースに Null 値を書き込めます。