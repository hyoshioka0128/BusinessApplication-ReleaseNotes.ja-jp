---
title: レスポンシブ レイアウトでのキャンバス アプリの作成
description: 上級の作成者は、レスポンシブなアプリを作成して、さまざまな環境に動的に調整できます。
author: emcoope-msft
ms.reviewer: anneta
ms.date: 04/29/2019
ms.assetid: 3f87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: emcoope
audience: Power user
ms.openlocfilehash: 02bd3c28646b823eabf9e8e6b82d59b2c3160ec0
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446168"
---
# <a name="create-canvas-apps-with-responsive-layout-public-preview"></a><span data-ttu-id="627e2-103">レスポンシブ レイアウトでのキャンバス アプリの作成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="627e2-103">Create canvas apps with responsive layout (Public Preview)</span></span>



<span data-ttu-id="627e2-104">通常、キャンバス アプリの画面は、アプリ ホストが提供するスペースに収まるように拡張または縮小されます。</span><span class="sxs-lookup"><span data-stu-id="627e2-104">The screens of a canvas app are usually scaled to fit the space that the app host provide.</span></span> <span data-ttu-id="627e2-105">これにより、任意の画面で正しい比率で表示されるアプリを作成するのが簡単になります。</span><span class="sxs-lookup"><span data-stu-id="627e2-105">This makes it easy to create an app and know that it will look proportionally correct on any screen in which it's used.</span></span> <span data-ttu-id="627e2-106">ただし、デメリットもあります。画面が大きくなると、アプリは余分な領域を有効活用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="627e2-106">But it comes at a price - as screens get bigger, the app can't adapt to take advantage of the additional real estate.</span></span> <span data-ttu-id="627e2-107">今日の多くの Web サイトは "レスポンシブ" です。表示される画面に応じてサイズを調整し、スマートフォンの小さな画面からデスクトップの大きな画面にまで対応しています。</span><span class="sxs-lookup"><span data-stu-id="627e2-107">Many websites today are "responsive" in that they adjust to the size of the screen on which they appear, adapting from small screens on phones to large screens on desktops.</span></span>  

<span data-ttu-id="627e2-108">この機能を使用して、経験豊富なアプリ作成者はレスポンシブなキャンバス アプリを作成できます。</span><span class="sxs-lookup"><span data-stu-id="627e2-108">With this feature, experienced app makers can create responsive canvas apps.</span></span> <span data-ttu-id="627e2-109">ランタイム時の画面のサイズに基づいて、コントロールのサイズと位置を調整する式を記述する必要があります。</span><span class="sxs-lookup"><span data-stu-id="627e2-109">You must write formulas that adapt the size and position of controls based on the size of the screen at runtime.</span></span> <span data-ttu-id="627e2-110">既定のスケーリング動作は無効にできます。</span><span class="sxs-lookup"><span data-stu-id="627e2-110">You can turn off the default scaling behavior.</span></span> <span data-ttu-id="627e2-111">その結果、適切なフォント サイズの情報が画面に表示されるようになり、アプリのエクスペリエンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="627e2-111">As a result, screens show more information with more appropriate font sizes, all making for a better app experience.</span></span>
