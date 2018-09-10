---
title: "キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮"
description: "アプリ開発者は、複数の読み込みオペレーションを並列で実行して、アプリ ユーザーの全体的な待ち時間を短縮できます。"
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: bef6215012791ea25a52186010f46fbdd00cc4f1
ms.contentlocale: ja-jp
ms.lasthandoff: 09/10/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="6b377-103">キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮</span><span class="sxs-lookup"><span data-stu-id="6b377-103">Faster load times with parallel data loading in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="6b377-104">多くのキャンバス アプリ開発者は、パフォーマンスを向上させるために、アプリの開始時に複数のテーブルやエンティティをプリロードします。</span><span class="sxs-lookup"><span data-stu-id="6b377-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="6b377-105">今日、これはロードごとに順次行われており、多くの場合はアプリの **OnStart** 式で行われます。</span><span class="sxs-lookup"><span data-stu-id="6b377-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="6b377-106">この機能を使用すると、アプリ開発者は複数のデータセットを並列で読み込むことができ、エンドユーザーの待ち時間を大幅に短縮できます。</span><span class="sxs-lookup"><span data-stu-id="6b377-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="6b377-107">この機能は起動時だけに限定されておらず、並列処理がパフォーマンスを向上するどの場所でも使用できます。</span><span class="sxs-lookup"><span data-stu-id="6b377-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>

