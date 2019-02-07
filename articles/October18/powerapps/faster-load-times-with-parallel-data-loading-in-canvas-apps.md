---
title: キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮
description: アプリ開発者は、複数の読み込みオペレーションを並列で実行して、アプリ ユーザーの全体的な待ち時間を短縮できます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 01/11/2019
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: 9aa41de0a9b58960c631e188205e7dcde3656650
ms.sourcegitcommit: abbfbdaff6d71a53e5dd36fecb6673080c49e5d6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/26/2019
ms.locfileid: "290009"
---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="6d272-103">キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮</span><span class="sxs-lookup"><span data-stu-id="6d272-103">Faster load times with parallel data loading in canvas apps</span></span>




<span data-ttu-id="6d272-104">多くのキャンバス アプリ開発者は、パフォーマンスを向上させるために、アプリの開始時に複数のテーブルやエンティティを事前読み込みします。</span><span class="sxs-lookup"><span data-stu-id="6d272-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="6d272-105">今日、これはロードごとに順次行われており、多くの場合はアプリの **OnStart** 式で行われます。</span><span class="sxs-lookup"><span data-stu-id="6d272-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="6d272-106">この機能を使用すると、アプリ開発者は複数のデータセットを並列で読み込むことができ、エンドユーザーの待ち時間を大幅に短縮できます。</span><span class="sxs-lookup"><span data-stu-id="6d272-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="6d272-107">この機能は起動時だけに限定されておらず、並列処理がパフォーマンスを向上するどの場所でも使用できます。</span><span class="sxs-lookup"><span data-stu-id="6d272-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>

## <a name="related-topic"></a><span data-ttu-id="6d272-108">関連項目</span><span class="sxs-lookup"><span data-stu-id="6d272-108">Related topic</span></span>

[<span data-ttu-id="6d272-109">新しい同時実行機能によって起動時間が短縮されます</span><span class="sxs-lookup"><span data-stu-id="6d272-109">Enjoy faster startup times with the new Concurrent function</span></span>](https://powerapps.microsoft.com/blog/enjoy-faster-startup-times-with-the-new-concurrent-function/)