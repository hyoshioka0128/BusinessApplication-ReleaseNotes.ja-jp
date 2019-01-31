---
title: マスター プランの再開
description: マスター プランの再開
author: josaw1
manager: AnnBe
ms.date: 11/29/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: josaw
audience: end-user
ms.openlocfilehash: cef4f35c4f7718ef0329aca340f3a5c153c89709
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199830"
---
#  <a name="resume-master-planning"></a><span data-ttu-id="67584-103">マスター プランの再開</span><span class="sxs-lookup"><span data-stu-id="67584-103">Resume master planning</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="67584-104">強化された計画エンジン機能により、メイン スレッドが予期せず停止した場合に、マスター プランのバッチ ジョブが自動的に再開されます。</span><span class="sxs-lookup"><span data-stu-id="67584-104">Enhanced planning engine functionality ensures that master planning batch jobs automatically resume in the case where the main thread stops unexpectedly.</span></span> <span data-ttu-id="67584-105">この状況は、なんらかの理由により、マスター プランの実行中にバッチ サーバー接続が失われた場合に発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="67584-105">This can happen if, for some reason, the batch server connection is lost during the master planning run.</span></span> <span data-ttu-id="67584-106">この機能が実装される前は、マスター プランの完全な再実行が必要でした。</span><span class="sxs-lookup"><span data-stu-id="67584-106">Before this feature was implemented, a complete rerun of master planning was needed.</span></span> <span data-ttu-id="67584-107">現在は、マスター プランのバッチ ジョブが自動的に再開され、中断された場所から続行されます。</span><span class="sxs-lookup"><span data-stu-id="67584-107">Now the master planning batch jobs automatically resume and continue at the place where they were interrupted.</span></span> <span data-ttu-id="67584-108">プランナーは、**マスター プラン履歴ログ**から、メイン スレッドが予期せず停止し、プロセスが再開されたことを確認できます。</span><span class="sxs-lookup"><span data-stu-id="67584-108">From the **Master planning history log**, the planner can see that the main thread was stopped unexpectedly and that the process was resumed.</span></span>

<span data-ttu-id="67584-109">再開は 1 回だけ行われるので、メイン スレッドが再開中に再び予期せず停止した場合は、失敗したものとしてログに記録され、再開は再試行されません。</span><span class="sxs-lookup"><span data-stu-id="67584-109">Resume will only happen once, so if the main thread is stopped unexpectedly again, during the resume, it will mark it as failed in the log and not try to resume again.</span></span> <span data-ttu-id="67584-110">また、再開は、少なくともマスター プラン計算のカバレッジ状態に達した再生成とジョブにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="67584-110">Also, resume is only applied to regeneration and jobs that have reached at least the coverage state of the master planning calculation.</span></span> <span data-ttu-id="67584-111">ヘルパー スレッドが予期せず停止した場合、プランは残りのヘルパーで続行されます。</span><span class="sxs-lookup"><span data-stu-id="67584-111">In case a helper thread stops unexpectedly, planning will continue with the remaining helpers.</span></span>

