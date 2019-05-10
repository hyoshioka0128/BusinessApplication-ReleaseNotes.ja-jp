---
title: 古い計画データの削除の改善
description: マスター プランが正常に実行された後は、不要になった計画データを削除するためのクリーンアップ ジョブをスケジュールします。
author: Mirzaab
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
ms.openlocfilehash: 07f30fc98a6247923d57e7e1efbba1fea03b7dcb
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224891"
---
#  <a name="improved-removal-of-obsolete-planning-data"></a><span data-ttu-id="4dc77-103">古い計画データの削除の改善</span><span class="sxs-lookup"><span data-stu-id="4dc77-103">Improved removal of obsolete planning data</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="4dc77-104">マスター プランが正常に実行された後は、不要になった計画データを削除するためのクリーンアップ ジョブをスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4dc77-104">After a successful master planning run, a clean-up job is scheduled to remove planning data that is no longer necessary.</span></span> <span data-ttu-id="4dc77-105">ただし、マスター プランの実行が失敗したときなど、場合によっては、データがクリーンアップされず、それによって不要なデータが集計される危険性があります。</span><span class="sxs-lookup"><span data-stu-id="4dc77-105">In some cases, however, such as a failed master planning run, the data would not be cleaned up thereby incurring risk of aggregating unnecessary data.</span></span> 

<span data-ttu-id="4dc77-106">クリーンアップ ジョブは、以前に失敗したマスター プランの実行からデータを削除するように強化されました。また、設計は他のスレッドをブロックしないように最適化されて、すべてのヘルパーをマスター プランの実行に使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4dc77-106">The clean-up job has now been enhanced to remove data from previously failed master planning runs, and the design has been optimized to never block other threads, leaving all helpers available for the master planning run.</span></span> <span data-ttu-id="4dc77-107">これらの改善は、会社間のマスター プランにも適用されます。</span><span class="sxs-lookup"><span data-stu-id="4dc77-107">These improvements also apply to intercompany master planning.</span></span>
