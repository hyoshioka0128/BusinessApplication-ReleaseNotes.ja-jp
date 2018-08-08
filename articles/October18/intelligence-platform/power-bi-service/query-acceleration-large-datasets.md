---
title: "大きなデータセットに対するクエリの迅速化"
description: "大きなデータセットに対するクエリの迅速化"
author: MargoC
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 285bf3e5cbfb965d27f0b717b5cdc8fa332e28d6
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

#  <a name="query-acceleration-for-large-datasets-public-preview"></a><span data-ttu-id="b3b96-103">大きなデータセットに対するクエリの迅速化 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="b3b96-103">Query acceleration for large datasets (Public Preview)</span></span>

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="b3b96-104">ユーザーは、Spark や Azure SQL Data Warehouse などのソース内の任意のサイズのデータに対して [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) モデルを作成し、一部のデータに対してメモリ内集約を構築することで一般的なクエリを高速化できます。</span><span class="sxs-lookup"><span data-stu-id="b3b96-104">Users can create [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) models over any size data in sources, such as Spark and Azure SQL Data Warehouse, and then accelerate common queries by building in-memory aggregations over some of the data.</span></span> <span data-ttu-id="b3b96-105">一般的なクエリでは、ソースを直接クエリする代わりに集約されたキャッシュを使用して結果を 1 秒以内に返します。</span><span class="sxs-lookup"><span data-stu-id="b3b96-105">Common queries use the aggregated cache to return results in a fraction of a second instead of directly querying the source.</span></span> <span data-ttu-id="b3b96-106">ユーザーはサイズの大きなデータセットを作成でき、対話型クエリも引き続き提供できます。</span><span class="sxs-lookup"><span data-stu-id="b3b96-106">Users can create datasets of massive size and still provide interactive querying.</span></span>

