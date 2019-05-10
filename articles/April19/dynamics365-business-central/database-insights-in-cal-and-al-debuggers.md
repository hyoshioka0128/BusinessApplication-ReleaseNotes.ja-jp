---
title: C/AL および AL デバッガーでのデータベース分析情報
description: C/AL および AL デバッガーでのデータベース分析情報
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 4f37c61df9f1d9fed98d06365c2e71deed40dafe
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225066"
---
# <a name="database-insights-in-cal-and-al-debuggers"></a><span data-ttu-id="48f2b-103">C/AL および AL デバッガーでのデータベース分析情報</span><span class="sxs-lookup"><span data-stu-id="48f2b-103">Database insights in C/AL and AL debuggers</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="debugging-sql-behavior"></a><span data-ttu-id="48f2b-104">SQL の動作のデバッグ</span><span class="sxs-lookup"><span data-stu-id="48f2b-104">Debugging SQL behavior</span></span>

<span data-ttu-id="48f2b-105">従来、AL のデバッグは、言語ランタイムの動作を調べる (たとえば、ブレークポイントでのローカル変数の内容を調べる) ことを目的としていました。</span><span class="sxs-lookup"><span data-stu-id="48f2b-105">Traditionally, debugging AL has been about examining behavior of the language runtime—for example, looking into the content of local variables at a breakpoint.</span></span> <span data-ttu-id="48f2b-106">Business Central の 2019 年 4 月リリースから、C/AL および AL デバッガーで、AL コードが Business Central データベースに与える影響を調べる機能も提供されるようになります。</span><span class="sxs-lookup"><span data-stu-id="48f2b-106">As of the Business Central April 2019 release, the C/AL and AL debuggers also offer you the capability to examine the impact that your AL code has on the Business Central database.</span></span> <span data-ttu-id="48f2b-107">デバッガーの**変数**ボックスで **\<データベースの統計情報\>** ノードを展開すると、Business Central Server と Business Central データベースの間の待機時間、実行された SQL ステートメントの合計数、読み取られた行の合計数などの分析情報と、サーバーによって実行された最近の SQL ステートメントに関する分析情報を取得できます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-107">In the **variables** box of the debugger, expand the **\<Database statistics\>** node to get insights such as the current network latency between the Business Central Server and the Business Central database, the total number of SQL statements executed, the total number of rows read, as well as insights into the most recent SQL statements executed by the server.</span></span>
 
<span data-ttu-id="48f2b-108">データベースの統計情報には、次の分析情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-108">The following insights are part of the database statistics:</span></span>


|    |    |
| -- | -- |
|<span data-ttu-id="48f2b-109">現在の SQL 待機時間 (ミリ秒)</span><span class="sxs-lookup"><span data-stu-id="48f2b-109">Current SQL latency (ms)</span></span> | <span data-ttu-id="48f2b-110">デバッガーがブレークポイントにヒットすると、サーバーは短い SQL ステートメントをデータベースに送信し、それにかかる時間を測定します。</span><span class="sxs-lookup"><span data-stu-id="48f2b-110">When the debugger hits a breakpoint, the server will send a short SQL statement to the database and measure how long it takes.</span></span> <span data-ttu-id="48f2b-111">この値はミリ秒単位で表示されます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-111">The value is shown in milliseconds.</span></span>|
|<span data-ttu-id="48f2b-112">SQL の実行数</span><span class="sxs-lookup"><span data-stu-id="48f2b-112">Number of SQL Executes</span></span> | <span data-ttu-id="48f2b-113">デバッガーの起動以降にデバッグ セッションで実行された SQL ステートメントの合計数を示します。</span><span class="sxs-lookup"><span data-stu-id="48f2b-113">This shows the total number of SQL statements executed in the debugging session since the debugger was started.</span></span>|
|<span data-ttu-id="48f2b-114">読み取られた SQL 行の数</span><span class="sxs-lookup"><span data-stu-id="48f2b-114">Number of SQL Rows Read</span></span> | <span data-ttu-id="48f2b-115">デバッガーの起動以降にデバッグ セッションで Business Central データベースから読み取られた行の合計数を示します。</span><span class="sxs-lookup"><span data-stu-id="48f2b-115">This shows the total number of rows read from the Business Central database in the debugging session since the debugger was started.</span></span>|

<span data-ttu-id="48f2b-116">データベース分析情報では、サーバーによって実行された最新の SQL ステートメントと最近の実行時間の長い SQL ステートメントを調べることもできます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-116">Database insights also make it possible for you to peek into the most recent and the latest long running SQL statements executed by the server.</span></span> <span data-ttu-id="48f2b-117">これらのリストをデバッガーで表示するには、**\<最後に実行された SQL ステートメント\>** または**\<最近の実行時間の長い SQL ステートメント\>** ノードを展開します。</span><span class="sxs-lookup"><span data-stu-id="48f2b-117">To get a list of these in debugger, expand either the **\<Last Executed SQL Statements\>** or the **\<Last Long Running SQL Statements\>** node.</span></span>  
 
<span data-ttu-id="48f2b-118">SQL ステートメントの統計情報には、次の分析情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-118">The following insights are part of the SQL statement statistics:</span></span>

|||
|-|-|
|<span data-ttu-id="48f2b-119">ステートメント</span><span class="sxs-lookup"><span data-stu-id="48f2b-119">Statement</span></span> | <span data-ttu-id="48f2b-120">AL サーバーが Business Central データベースに送信した SQL ステートメント。</span><span class="sxs-lookup"><span data-stu-id="48f2b-120">The SQL statement that the AL server sent to the Business Central database.</span></span> <span data-ttu-id="48f2b-121">これを SQL Server Management Studio などの他のデータベース ツールにコピーして、さらに分析できます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-121">You can copy this into other database tools, such as SQL Server Management Studio, for further analysis.</span></span>|
|<span data-ttu-id="48f2b-122">実行時間 (UTC)</span><span class="sxs-lookup"><span data-stu-id="48f2b-122">Execution time (UTC)</span></span> | <span data-ttu-id="48f2b-123">SQL ステートメントが実行されたときのタイムスタンプ (UTC)。</span><span class="sxs-lookup"><span data-stu-id="48f2b-123">The timestamp in UTC of when the SQL statement was executed.</span></span> <span data-ttu-id="48f2b-124">これを使用して、SQL ステートメントが現在のブレークポイントと最後のブレークポイント (設定されている場合) の間の AL コードに含まれていたかどうかを推測できます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-124">You can use this to infer whether the SQL statement was part of the AL code between the current and last breakpoint (if set).</span></span>|
|<span data-ttu-id="48f2b-125">期間 (ミリ秒)</span><span class="sxs-lookup"><span data-stu-id="48f2b-125">Duration (ms)</span></span> | <span data-ttu-id="48f2b-126">Business Central Server 内で測定された SQL ステートメントの合計実行時間の期間 (ミリ秒)。</span><span class="sxs-lookup"><span data-stu-id="48f2b-126">The duration in milliseconds of the total execution time of the SQL statement measured inside the Business Central Server.</span></span><br /><br /><span data-ttu-id="48f2b-127">これを使用して、インデックス (Business Central キー) が欠落しているかどうかを調べたり、データベースのパーティション分割や圧縮のパフォーマンスを実験したりできます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-127">You can use this to analyze if you are missing indexes (Business Central keys), or to experiment with performance of database partitioning and/or compression.</span></span>|
|<span data-ttu-id="48f2b-128">読み取られた行の概数</span><span class="sxs-lookup"><span data-stu-id="48f2b-128">Approx. Rows Read</span></span> | <span data-ttu-id="48f2b-129">SQL ステートメントによって Business Central データベースから読み取られた行の概数を示します。</span><span class="sxs-lookup"><span data-stu-id="48f2b-129">This shows the approximate number of rows read from the Business Central database by the SQL statement.</span></span><br /><br /><span data-ttu-id="48f2b-130">これを使用して、フィルターが不足しているかどうかを分析できます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-130">You can use this to analyze whether you are missing filters.</span></span>|

<span data-ttu-id="48f2b-131">デバッガーによって追跡される SQL ステートメントの数は、Business Central Server で構成できます。</span><span class="sxs-lookup"><span data-stu-id="48f2b-131">The number of SQL statements tracked by the debugger can be configured in the Business Central Server.</span></span> <span data-ttu-id="48f2b-132">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="48f2b-132">The default value is 10.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="48f2b-133">フィードバック</span><span class="sxs-lookup"><span data-stu-id="48f2b-133">Tell us what you think</span></span>
<span data-ttu-id="48f2b-134">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="48f2b-134">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="48f2b-135">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="48f2b-135">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
