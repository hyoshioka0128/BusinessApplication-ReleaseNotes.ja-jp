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
#  <a name="query-acceleration-for-large-datasets-public-preview"></a>大きなデータセットに対するクエリの迅速化 (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



ユーザーは、Spark や Azure SQL Data Warehouse などのソース内の任意のサイズのデータに対して [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) モデルを作成し、一部のデータに対してメモリ内集約を構築することで一般的なクエリを高速化できます。 一般的なクエリでは、ソースを直接クエリする代わりに集約されたキャッシュを使用して結果を 1 秒以内に返します。 ユーザーはサイズの大きなデータセットを作成でき、対話型クエリも引き続き提供できます。
