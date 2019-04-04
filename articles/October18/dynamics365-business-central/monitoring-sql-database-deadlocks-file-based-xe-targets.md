---
title: SQL Database のデッドロックの監視 - ファイルベースの xe ターゲット
description: SQL Database のデッドロックの監視 - ファイルベースの xe ターゲット
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 710ffca59f8179558d8a623166b51f20e77b3055
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878520"
---
# <a name="monitoring-sql-database-deadlocks-using-file-based-xe-targets"></a><span data-ttu-id="370be-103">ファイルベースの xe ターゲットを使用した SQL Database のデッドロックの監視</span><span class="sxs-lookup"><span data-stu-id="370be-103">Monitoring SQL database deadlocks using file-based xe targets</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="370be-104">既定では、SQL Server は ring_buffer ターゲットと呼ばれるメモリ内データ構造を使用してデッドロック イベントを格納します。</span><span class="sxs-lookup"><span data-stu-id="370be-104">By default, SQL Server uses an in-memory data structure called a ring_buffer target to store deadlock events.</span></span> <span data-ttu-id="370be-105">Business Central Server はデッドロックに関する通知を受け取ると、対象の ring_buffer ターゲットからデータを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="370be-105">When the Business Central Server is notified about the deadlock, it reads data from the target ring_buffer target.</span></span> <span data-ttu-id="370be-106">これに加えて、イベントを SQL Server 上の event_file ターゲットと呼ばれるファイルに格納し、ring_buffer ターゲットの代わりにこのファイルからデータを読み取るように Business Central サーバーを構成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="370be-106">You now have the option to also store the events to a file on the SQL Server, called an event_file target, and configure the Business Central Server to read from this file instead of the ring_buffer target.</span></span> <span data-ttu-id="370be-107">ring_buffer ターゲットと event_file ターゲットの重要な違いは、ring_buffer ターゲットには 5 MB というストレージ サイズ制限があるのに対し、event_file ターゲットでははるかに大きいストレージ容量が提供されるという点です。</span><span class="sxs-lookup"><span data-stu-id="370be-107">An important difference between the ring_buffer target and event_file target is that the ring_buffer target has a storage size limitation of 5 MB, while the event_file target provides a much greater storage capacity.</span></span> <span data-ttu-id="370be-108">event_file ターゲットを使用すると、大量のデータを処理する状況で発生する可能性のある過負荷を解消できます。</span><span class="sxs-lookup"><span data-stu-id="370be-108">Using the event_file target can eliminate potential overloads in high-volume situations.</span></span> <span data-ttu-id="370be-109">そのため、設定で大量のデータベース トラフィックがあるときは、event_file ターゲットにデッドロックを書き込むように SQL Server を変更することが必要な場合があります。</span><span class="sxs-lookup"><span data-stu-id="370be-109">So, if your setup has a high volume of database traffic, you might have to change the SQL Server to write deadlock events to an event_file target.</span></span> <span data-ttu-id="370be-110">既定の ring_buffer ターゲットを使用する場合は、それ以上のアクションは不要です。</span><span class="sxs-lookup"><span data-stu-id="370be-110">If you want to use the default ring_buffer target, then no further action is required.</span></span>

<span data-ttu-id="370be-111">詳細については、「[SQL Database のデッドロックの監視](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-deadlocks#configure-where-to-store-deadlock-events)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="370be-111">For more information, see [Monitoring SQL Database Deadlocks](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-deadlocks#configure-where-to-store-deadlock-events).</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="370be-112">フィードバック</span><span class="sxs-lookup"><span data-stu-id="370be-112">Tell us what you think</span></span>
<span data-ttu-id="370be-113">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="370be-113">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="370be-114">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="370be-114">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
