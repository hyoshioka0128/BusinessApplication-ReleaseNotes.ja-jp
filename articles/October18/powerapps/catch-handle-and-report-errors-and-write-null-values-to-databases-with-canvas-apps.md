---
title: キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み
description: アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 12/10/2018
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: 6dfc4bf64710b662a68cb4e5ec522a3df8eb00c8
ms.sourcegitcommit: 4516c399d430cc569513d46822c70670809fe5c6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/12/2019
ms.locfileid: "202320"
---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a><span data-ttu-id="bc054-103">キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="bc054-103">Catch, handle, and report errors, and write Null values to databases with canvas apps (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="bc054-104">アプリを作成中にエラーが発生するのは仕方がないことです。</span><span class="sxs-lookup"><span data-stu-id="bc054-104">Errors happen.</span></span> <span data-ttu-id="bc054-105">キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="bc054-105"> Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span> <span data-ttu-id="bc054-106">この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。</span><span class="sxs-lookup"><span data-stu-id="bc054-106"> With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="bc054-107">以前は、エラーと Null 値を判別できてないにもかかわらず、データベースに Null 値を書き込むのは問題でした。</span><span class="sxs-lookup"><span data-stu-id="bc054-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span> <span data-ttu-id="bc054-108">Null は多くのデータベース システムでは正当な値です。</span><span class="sxs-lookup"><span data-stu-id="bc054-108"> Null is a legitimate value in many database systems.</span></span> <span data-ttu-id="bc054-109">キャンバス アプリでエラーの場合と適切に分離することにより、すべてのデータベースに Null 値を書き込めます。</span><span class="sxs-lookup"><span data-stu-id="bc054-109"> With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>
