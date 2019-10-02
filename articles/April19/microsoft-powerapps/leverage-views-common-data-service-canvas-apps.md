---
title: キャンバス アプリで Common Data Service からのビューを活用する
description: キャンバス アプリで Common Data Service からのビューを活用する
author: aorth
ms.reviewer: pehecke
ms.date: 09/05/2019
ms.assetid: ed87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: 92428077f5b78ed5e24febf8aed67ef3e39d5777
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1993775"
---
# <a name="leverage-views-from-common-data-service-in-canvas-apps-public-preview"></a><span data-ttu-id="68f28-103">キャンバス アプリで Common Data Service からのビューを活用する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="68f28-103">Leverage views from Common Data Service in canvas apps (Public Preview)</span></span>



<span data-ttu-id="68f28-104">キャンバス アプリで、作成者は、Common Data Service のビューに基づいて、ギャラリーを並べ替えたりフィルター処理したりできます。</span><span class="sxs-lookup"><span data-stu-id="68f28-104">In canvas apps, makers can sort and filter a gallery based on a view in Common Data Service.</span></span> <span data-ttu-id="68f28-105">これにより、ビュー デザイナーの機能が解放され、複雑な一連のフィルター、並べ替え、関連するエンティティ フィールドを集中的に定義できます。</span><span class="sxs-lookup"><span data-stu-id="68f28-105">This unlocks the power of the modern View Designer, in which you can centrally define more a complex set of filter, sort, and related entity fields.</span></span> <span data-ttu-id="68f28-106">キャンバス デザイナーは、ギャラリーまたはデータ テーブルのコントロールでガイド付きエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="68f28-106">The canvas designer then provides a guided experience on the gallery or data table controls.</span></span> <span data-ttu-id="68f28-107">これにより、使用するエンティティを推奨し、そのエンティティのパブリック ビューを選択することで、Common Data Service でのデータ ソースの選択が向上します。</span><span class="sxs-lookup"><span data-stu-id="68f28-107">It improves the selection of data sources in Common Data Service by recommending entities to use and selecting the public views for the entity.</span></span> <span data-ttu-id="68f28-108">作成者はアプリのフィルター処理と並べ替えで**アイテム** プロパティを拡張することができ、それはビューとマージされます。</span><span class="sxs-lookup"><span data-stu-id="68f28-108">The maker can then extend the **Items** property with app filtering and sorting, which is merged with the view.</span></span> <span data-ttu-id="68f28-109">この改善により、共有ビューの値を取得するときにアプリ固有の動作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="68f28-109">This improvement allows app-specific behavior while getting the value of a shared view.</span></span>
