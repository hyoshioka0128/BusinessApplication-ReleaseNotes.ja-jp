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

#  <a name="query-acceleration-for-large-datasets-public-preview"></a>大きなデータセットに対するクエリの迅速化 (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



ユーザーは、Spark や Azure SQL Data Warehouse などのソース内の任意のサイズのデータに対して [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) モデルを作成し、一部のデータに対してメモリ内集約を構築することで一般的なクエリを高速化できます。 一般的なクエリでは、ソースを直接クエリする代わりに集約されたキャッシュを使用して結果を 1 秒以内に返します。 ユーザーはサイズの大きなデータセットを作成でき、対話型クエリも引き続き提供できます。

