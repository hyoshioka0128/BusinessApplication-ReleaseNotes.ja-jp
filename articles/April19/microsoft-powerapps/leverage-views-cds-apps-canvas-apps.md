---
title: キャンバス アプリで CDS for Apps からのビューを活用する
description: キャンバス アプリで CDS for Apps からのビューを活用する
author: aorth
ms.reviewer: anneta
ms.date: 01/09/2019
ms.assetid: 5165dbf9-41e4-e811-a987-000d3a1362e3
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: 9db812529d1c411d161da047f7c8f0485ebc8647
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210700"
---
# <a name="leverage-views-from-cds-for-apps-in-canvas-apps-public-preview"></a><span data-ttu-id="c4375-103">キャンバス アプリで CDS for Apps からのビューを活用する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="c4375-103">Leverage views from CDS for Apps in canvas apps (Public Preview)</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="c4375-104">キャンバス アプリで、作成者は、Common Data Service (CDS) for Apps のビューに基づいて、ギャラリーを並べ替えたりフィルター処理したりできます。</span><span class="sxs-lookup"><span data-stu-id="c4375-104">In canvas apps, makers can sort and filter a gallery based on a view in Common Data Service (CDS) for Apps.</span></span> <span data-ttu-id="c4375-105">これにより、ビュー デザイナーの機能が解放され、複雑な一連のフィルター、並べ替え、関連するエンティティ フィールドを集中的に定義できます。</span><span class="sxs-lookup"><span data-stu-id="c4375-105">This unlocks the power of the modern View Designer, in which you can centrally define more a complex set of filter, sort, and related entity fields.</span></span> <span data-ttu-id="c4375-106">キャンバス デザイナーは、ギャラリーまたはデータ テーブルのコントロールでガイド付きエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c4375-106">The canvas designer then provides a guided experience on the gallery or data table controls.</span></span> <span data-ttu-id="c4375-107">これにより、使用するエンティティを推奨し、そのエンティティのパブリック ビューを選択することで、CDS for Apps でのデータ ソースの選択が向上します。</span><span class="sxs-lookup"><span data-stu-id="c4375-107">It improves the selection of data sources in CDS for Apps by recommending entities to use and selecting the public views for the entity.</span></span> <span data-ttu-id="c4375-108">作成者はアプリのフィルター処理と並べ替えで**アイテム** プロパティを拡張することができ、それはビューとマージされます。</span><span class="sxs-lookup"><span data-stu-id="c4375-108">The maker can then extend the **Items** property with app filtering and sorting, which is merged with the view.</span></span> <span data-ttu-id="c4375-109">これにより、共有ビューの値を取得するときにアプリ固有の動作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="c4375-109">This allows app-specific behavior while getting the value of a shared view.</span></span>
