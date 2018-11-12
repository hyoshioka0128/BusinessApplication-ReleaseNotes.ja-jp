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
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 3c5fbf4a44a8de37d7b750f4c30a28967c62c10b
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a><span data-ttu-id="56bfe-103">キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="56bfe-103">Catch, handle, and report errors, and write Null values to databases with canvas apps (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="56bfe-104">アプリを作成中にエラーが発生するのは仕方がないことです。</span><span class="sxs-lookup"><span data-stu-id="56bfe-104">Errors happen.</span></span> <span data-ttu-id="56bfe-105">キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="56bfe-105"> Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span> <span data-ttu-id="56bfe-106">この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。</span><span class="sxs-lookup"><span data-stu-id="56bfe-106"> With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="56bfe-107">以前は、エラーと Null 値を判別できてないにもかかわらず、データベースに Null 値を書き込むのは問題でした。</span><span class="sxs-lookup"><span data-stu-id="56bfe-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span> <span data-ttu-id="56bfe-108">Null は多くのデータベース システムでは正当な値です。</span><span class="sxs-lookup"><span data-stu-id="56bfe-108"> Null is a legitimate value in many database systems.</span></span> <span data-ttu-id="56bfe-109">キャンバス アプリでエラーの場合と適切に分離することにより、すべてのデータベースに Null 値を書き込めます。</span><span class="sxs-lookup"><span data-stu-id="56bfe-109"> With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>

