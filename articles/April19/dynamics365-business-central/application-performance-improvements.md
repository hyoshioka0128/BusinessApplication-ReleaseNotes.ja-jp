---
title: アプリケーションのパフォーマンスの向上
description: Business Central におけるアプリケーションのパフォーマンスの向上
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 3b90d7b310c45ffe6b98005f206e8c3f2ca57319
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878726"
---
# <a name="application-performance-improvements"></a><span data-ttu-id="52738-103">アプリケーションのパフォーマンスの向上</span><span class="sxs-lookup"><span data-stu-id="52738-103">Application performance improvements</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="52738-104">ユーザー テレメトリから、Business Central アプリケーションの多数のパフォーマンスの問題が特定され、修正されました。</span><span class="sxs-lookup"><span data-stu-id="52738-104">From user telemetry, numerous performance issues in the Business Central application have been identified and fixed:</span></span>

- <span data-ttu-id="52738-105">実行時間の長い SQL クエリを分析した結果、キーが最適化され、予期しないロックの問題が発見されて除去されました。</span><span class="sxs-lookup"><span data-stu-id="52738-105">Analysis of long running SQL queries yielded key optimizations, and unexpected locking issues were discovered and removed.</span></span>
- <span data-ttu-id="52738-106">販売明細行および購買注文明細行テーブルの SIFT インデックスにおけるロックの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="52738-106">Locking issues in SIFT indexes on the Sales- and Purchase Line tables have been fixed.</span></span>
- <span data-ttu-id="52738-107">上位 5/10 件の顧客グラフ、アクティビティ パーツ、およびミニ試算表でデータがキャッシュされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52738-107">Data is now cached on the Customer top 5/10 chart, Activities parts, and Mini Trial Balance.</span></span>
- <span data-ttu-id="52738-108">品目、仕入先、顧客の検索を高速化するために、それぞれの専用の検索ページが追加されました。</span><span class="sxs-lookup"><span data-stu-id="52738-108">Dedicated lookup pages for Items, Vendors, and Customers have been added to make these lookups faster.</span></span>
- <span data-ttu-id="52738-109">静的コード分析の結果、インデックスを減らした FlowFields とインデックスのない FlowFields がいくつか発生し、はるかに高速に読み取ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52738-109">Static code analysis yielded several under-indexed or non-indexed FlowFields, which are now much faster to read from.</span></span>
- <span data-ttu-id="52738-110">販売ドキュメントおよび購買ドキュメントの編集ページで、データ入力を高速化するためにフィールドごとのすべての明細行の再計算が廃止されました。</span><span class="sxs-lookup"><span data-stu-id="52738-110">In the Edit Sales and Purchase Documents pages, recalculation of all lines for every field has been removed to speed up data entry.</span></span>
- <span data-ttu-id="52738-111">ワークフロー サブシステムがより速く実行できるように最適化されました。</span><span class="sxs-lookup"><span data-stu-id="52738-111">The workflow subsystem has been optimized to run faster.</span></span>
- <span data-ttu-id="52738-112">[自分の顧客]、[自分の仕入先]、[自分の項目]、[自社会社コード] の実行が高速になりました。</span><span class="sxs-lookup"><span data-stu-id="52738-112">My Customer, My Vendor, My Item, and My Account run faster.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="52738-113">フィードバック</span><span class="sxs-lookup"><span data-stu-id="52738-113">Tell us what you think</span></span>

<span data-ttu-id="52738-114">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="52738-114">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="52738-115">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="52738-115">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
