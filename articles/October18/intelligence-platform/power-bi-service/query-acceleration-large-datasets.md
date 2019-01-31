---
title: 大きなデータセットに対するクエリの迅速化
description: 大きなデータセットに対するクエリの迅速化
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 53a14ef61ef0d2ba7b794e6fc5070f6588852da2
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199125"
---
#  <a name="query-acceleration-for-large-datasets-public-preview"></a><span data-ttu-id="64b61-103">大きなデータセットに対するクエリの迅速化 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="64b61-103">Query acceleration for large datasets (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="64b61-104">ユーザーは、Spark や Azure SQL Data Warehouse などのソース内の任意のサイズのデータに対して [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) モデルを作成し、一部のデータに対してメモリ内集約を構築することで一般的なクエリを高速化できます。</span><span class="sxs-lookup"><span data-stu-id="64b61-104">Users can create [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) models over any size data in sources, such as Spark and Azure SQL Data Warehouse, and then accelerate common queries by building in-memory aggregations over some of the data.</span></span> <span data-ttu-id="64b61-105">一般的なクエリでは、ソースを直接クエリする代わりに集約されたキャッシュを使用して結果を 1 秒以内に返します。</span><span class="sxs-lookup"><span data-stu-id="64b61-105">Common queries use the aggregated cache to return results in a fraction of a second instead of directly querying the source.</span></span> <span data-ttu-id="64b61-106">ユーザーはサイズの大きなデータセットを作成でき、対話型クエリも引き続き提供できます。</span><span class="sxs-lookup"><span data-stu-id="64b61-106">Users can create datasets of massive size and still provide interactive querying.</span></span>
