---
title: Catch, handle, and report errors, and write Null values to databases with canvas apps
description: App makers can take control of errors when they happen and, as a side benefit, write Null values.
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
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: 3c5fbf4a44a8de37d7b750f4c30a28967c62c10b
ms.contentlocale: ja-jp
ms.lasthandoff: 09/10/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a><span data-ttu-id="c884b-103">キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="c884b-103">Catch, handle, and report errors, and write Null values to databases with canvas apps (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="c884b-104">アプリを作成中にエラーが発生するのは仕方がないことです。</span><span class="sxs-lookup"><span data-stu-id="c884b-104">Errors happen.</span></span>  <span data-ttu-id="c884b-105">キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="c884b-105">Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span>  <span data-ttu-id="c884b-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span><span class="sxs-lookup"><span data-stu-id="c884b-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="c884b-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span><span class="sxs-lookup"><span data-stu-id="c884b-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span>  <span data-ttu-id="c884b-108">Null is a legitimate value in many database systems.</span><span class="sxs-lookup"><span data-stu-id="c884b-108">Null is a legitimate value in many database systems.</span></span>  <span data-ttu-id="c884b-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span><span class="sxs-lookup"><span data-stu-id="c884b-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>

