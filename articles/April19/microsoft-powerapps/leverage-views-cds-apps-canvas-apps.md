---
title: キャンバス アプリで Common Data Service からのビューを活用する
description: キャンバス アプリで Common Data Service からのビューを活用する
author: aorth
ms.reviewer: anneta
ms.date: 03/14/2019
ms.assetid: 5165dbf9-41e4-e811-a987-000d3a1362e3
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: 80816cd56bdb6f97dd8c4b698ab5b372f19eaf34
ms.sourcegitcommit: ca3b94f829721c2ba02b25134536a58babed2d2b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/27/2019
ms.locfileid: "900472"
---
# <a name="leverage-views-from-common-data-service-in-canvas-apps-public-preview"></a><span data-ttu-id="94bc3-103">キャンバス アプリで Common Data Service からのビューを活用する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="94bc3-103">Leverage views from Common Data Service in canvas apps (Public Preview)</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="94bc3-104">キャンバス アプリで、作成者は、Common Data Service のビューに基づいて、ギャラリーを並べ替えたりフィルター処理したりできます。</span><span class="sxs-lookup"><span data-stu-id="94bc3-104">In canvas apps, makers can sort and filter a gallery based on a view in Common Data Service.</span></span> <span data-ttu-id="94bc3-105">これにより、ビュー デザイナーの機能が解放され、複雑な一連のフィルター、並べ替え、関連するエンティティ フィールドを集中的に定義できます。</span><span class="sxs-lookup"><span data-stu-id="94bc3-105">This unlocks the power of the modern View Designer, in which you can centrally define a more complex set of filter, sort, and related entity fields.</span></span> <span data-ttu-id="94bc3-106">キャンバス デザイナーは、ギャラリーまたはデータ テーブルのコントロールでガイド付きエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="94bc3-106">The canvas designer then provides a guided experience on the gallery or data table controls.</span></span> <span data-ttu-id="94bc3-107">これにより、使用するエンティティを推奨し、そのエンティティのパブリック ビューを選択することで、Common Data Service でのデータ ソースの選択が向上します。</span><span class="sxs-lookup"><span data-stu-id="94bc3-107">It improves the selection of data sources in Common Data Service by recommending entities to use and selecting the public views for the entity.</span></span> <span data-ttu-id="94bc3-108">作成者はアプリのフィルター処理と並べ替えで**アイテム** プロパティを拡張することができ、それはビューとマージされます。</span><span class="sxs-lookup"><span data-stu-id="94bc3-108">The maker can then extend the **Items** property with app filtering and sorting, which is merged with the view.</span></span> <span data-ttu-id="94bc3-109">これにより、共有ビューの値を取得するときにアプリ固有の動作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="94bc3-109">This allows app-specific behavior while getting the value of a shared view.</span></span>
