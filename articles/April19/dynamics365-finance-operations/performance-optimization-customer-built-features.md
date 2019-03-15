---
title: 電子申告 - 顧客が構築した構成のパフォーマンスの最適化
description: 機能コンサルタントのペルソナは、頻繁に使用されるノードでキャッシュを設定することにより、電子申告の構成のパフォーマンスを最適化できます。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: c75b75f74dceb8eec20122c238f2de38ff605776
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288047"
---
#  <a name="electronic-reporting---performance-optimization-of-customer-built-configurations"></a><span data-ttu-id="5488c-103">電子申告 - 顧客が構築した構成のパフォーマンスの最適化</span><span class="sxs-lookup"><span data-stu-id="5488c-103">Electronic reporting - Performance optimization of customer-built configurations</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="5488c-104">機能コンサルタントのペルソナは、電子申告の構成の実行を追跡することができます。</span><span class="sxs-lookup"><span data-stu-id="5488c-104">A functional consultant persona can enable tracing of execution of electronic reporting configuration.</span></span> <span data-ttu-id="5488c-105">このコンサルタントは、生成されたトレースを分析し、頻繁に使用されるノードでキャッシュを設定することにより、電子申告の構成のパフォーマンスを最適化することもできます。</span><span class="sxs-lookup"><span data-stu-id="5488c-105">This consultant can also analyze generated trace and optimize electronic reporting configuration performance by setting caching on frequently used nodes.</span></span>

<span data-ttu-id="5488c-106">![モデル マッピング デザイナー](media/ER-perf-model-mapping.png "モデル マッピング デザイナー")</span><span class="sxs-lookup"><span data-stu-id="5488c-106">![Model mapping designer](media/ER-perf-model-mapping.png "Model mapping designer")</span></span>

<span data-ttu-id="5488c-107">現在、このキャッシュではレコードのフラット リストのみがサポートされているため、関連レコードはキャッシュされません。</span><span class="sxs-lookup"><span data-stu-id="5488c-107">Currently, this caching supports only flat list of records, so any related records are not cached.</span></span> <span data-ttu-id="5488c-108">この機能は入れ子になったレコードをキャッシュできます。</span><span class="sxs-lookup"><span data-stu-id="5488c-108">This feature will allow caching of nested records.</span></span> <span data-ttu-id="5488c-109">また、リスト全体ではなく、参照されているレコードのみがキャッシュされる場合、ユーザーは "遅延" キャッシュを有効にできます。</span><span class="sxs-lookup"><span data-stu-id="5488c-109">It also allows users to enable “lazy” caching, when only referenced records are being cached, not the whole list.</span></span>

<span data-ttu-id="5488c-110">![モデル マッピング デザイナーのパフォーマンス統計](media/ER-perf-statistics.png "モデル マッピング デザイナーのパフォーマンス統計")</span><span class="sxs-lookup"><span data-stu-id="5488c-110">![Model mapping designer performance statistics](media/ER-perf-statistics.png "Model mapping designer performance statistics")</span></span>
