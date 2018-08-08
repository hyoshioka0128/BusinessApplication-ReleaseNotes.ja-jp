---
title: "キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮"
description: "アプリ開発者は、複数の読み込みオペレーションを並列で実行して、アプリ ユーザーの全体的な待ち時間を短縮できます。"
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
ms.openlocfilehash: 587d76f50fead1766f5dc810e2f9b0bf34bd760a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="6b377-103">キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮</span><span class="sxs-lookup"><span data-stu-id="6b377-103">Faster load times with parallel data loading in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="6b377-104">多くのキャンバス アプリ開発者は、パフォーマンスを向上させるために、アプリの開始時に複数のテーブルやエンティティをプリロードします。</span><span class="sxs-lookup"><span data-stu-id="6b377-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="6b377-105">今日、これはロードごとに順次行われており、多くの場合はアプリの **OnStart** 式で行われます。</span><span class="sxs-lookup"><span data-stu-id="6b377-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="6b377-106">この機能を使用すると、アプリ開発者は複数のデータセットを並列で読み込むことができ、エンドユーザーの待ち時間を大幅に短縮できます。</span><span class="sxs-lookup"><span data-stu-id="6b377-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="6b377-107">この機能は起動時だけに限定されておらず、並列処理がパフォーマンスを向上するどの場所でも使用できます。</span><span class="sxs-lookup"><span data-stu-id="6b377-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>

