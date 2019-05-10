---
title: クエリヒントの構成
description: Business Central で SQL Server のパフォーマンスを最適化するためのクエリ ヒントの構成
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: b0f99f5cad117407472dfc3915119de3e6471706
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225161"
---
# <a name="configuring-query-hints-for-optimizing-sql-server-performance"></a><span data-ttu-id="85d13-103">SQL Server のパフォーマンスを最適化するためのクエリ ヒントの構成</span><span class="sxs-lookup"><span data-stu-id="85d13-103">Configuring query hints for optimizing SQL Server performance</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="85d13-104">SQL Server クエリ オプティマイザーは、それ自体で、クエリに最適な実行プランを選択しようとします。</span><span class="sxs-lookup"><span data-stu-id="85d13-104">On its own, SQL Server query optimizer will try to select the best execution plan for queries.</span></span> <span data-ttu-id="85d13-105">ほとんどの場合、クエリ オプティマイザーは正しい選択をします。</span><span class="sxs-lookup"><span data-stu-id="85d13-105">Most of the time, query optimizer makes the right choice.</span></span> <span data-ttu-id="85d13-106">クエリ ヒントは、クエリ オプティマイザーによってクエリに対して選択される可能性のある実行プランをオーバーライドするために、SQL Server クエリ プロセッサによって適用される戦略です。</span><span class="sxs-lookup"><span data-stu-id="85d13-106">Query hints are strategies that can be enforced by the SQL Server query processor to override any execution plan that the query optimizer might select for a query.</span></span> <span data-ttu-id="85d13-107">Business Central Server インスタンスに含まれる以下の構成設定を使用すると、データベース内のクエリに対してヒントの使用を有効または無効にできます。</span><span class="sxs-lookup"><span data-stu-id="85d13-107">The Business Central Server instance includes the following configuration settings that let you enable or disable the use of hints on queries in the database:</span></span>

|<span data-ttu-id="85d13-108">ヒント</span><span class="sxs-lookup"><span data-stu-id="85d13-108">Hint</span></span>|<span data-ttu-id="85d13-109">説明</span><span class="sxs-lookup"><span data-stu-id="85d13-109">Description</span></span>|<span data-ttu-id="85d13-110">既定で使用</span><span class="sxs-lookup"><span data-stu-id="85d13-110">Used by default</span></span>|
|----|-----------|---------------|
|<span data-ttu-id="85d13-111">順序を強制</span><span class="sxs-lookup"><span data-stu-id="85d13-111">FORCE ORDER</span></span> |<span data-ttu-id="85d13-112">クエリ構文によって示されている結合順序を維持するようクエリ オプティマイザーに指示します。</span><span class="sxs-lookup"><span data-stu-id="85d13-112">Instructs the query optimizer to preserve the join order that is indicated by the query syntax.</span></span>|<span data-ttu-id="85d13-113">いいえ</span><span class="sxs-lookup"><span data-stu-id="85d13-113">No</span></span>|
|<span data-ttu-id="85d13-114">ループ結合</span><span class="sxs-lookup"><span data-stu-id="85d13-114">LOOP JOIN</span></span>|<span data-ttu-id="85d13-115">クエリ全体のすべての結合操作に LOOP JOIN を使用するようクエリ オプティマイザーに指示します。</span><span class="sxs-lookup"><span data-stu-id="85d13-115">Instructs the query optimizer to use LOOP JOIN for all join operations in the whole query.</span></span>|<span data-ttu-id="85d13-116">いいえ</span><span class="sxs-lookup"><span data-stu-id="85d13-116">No</span></span>|
|<span data-ttu-id="85d13-117">不明に対する最適化</span><span class="sxs-lookup"><span data-stu-id="85d13-117">OPTIMIZE FOR UNKNOWN</span></span>|<span data-ttu-id="85d13-118">クエリがコンパイルおよび最適化されるときに、強制パラメーター化で作成されるパラメーターを含め、すべてのローカル変数に対して初期値ではなく統計データを使用するようクエリ オプティマイザーに指示します。</span><span class="sxs-lookup"><span data-stu-id="85d13-118">Instructs the query optimizer to use statistical data instead of the initial values for all local variables when the query is compiled and optimized, including parameters created with forced parameterization.</span></span>|<span data-ttu-id="85d13-119">はい</span><span class="sxs-lookup"><span data-stu-id="85d13-119">Yes</span></span>|

<span data-ttu-id="85d13-120">Business Central クエリ オブジェクトの実行計画で、SQL Server のクエリ ヒントを使用するようにしました。</span><span class="sxs-lookup"><span data-stu-id="85d13-120">We have made the use of SQL Server query hints in the execution plans of Business Central query objects.</span></span>

<span data-ttu-id="85d13-121">また、これらの機能は Dynamics NAV の 2017 と 2018 で利用できるようにされました。</span><span class="sxs-lookup"><span data-stu-id="85d13-121">These features have also been made available in Dynamics NAV 2017 and 2018.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="85d13-122">フィードバック</span><span class="sxs-lookup"><span data-stu-id="85d13-122">Tell us what you think</span></span>
<span data-ttu-id="85d13-123">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="85d13-123">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="85d13-124">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="85d13-124">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
