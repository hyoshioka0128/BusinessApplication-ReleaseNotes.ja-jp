---
title: "レスポンシブ レイアウトでのキャンバス アプリの作成"
description: "上級の作成者は、レスポンシブなアプリを作成して、さまざまな環境に動的に調整できます。"
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 1f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 5b2badd67a697d89e63973f5afe0977e402aead0
ms.openlocfilehash: 3c31db17f2fecfe0b96c281ef9579648c8a7dfc6
ms.contentlocale: ja-jp
ms.lasthandoff: 09/10/2018

---
# <a name="create-canvas-apps-with-responsive-layout-public-preview"></a><span data-ttu-id="3ce4b-103">レスポンシブ レイアウトでのキャンバス アプリの作成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="3ce4b-103">Create canvas apps with responsive layout (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="3ce4b-104">通常、キャンバス アプリの画面はアプリ ホストが提供するスペースに収まるように拡張または縮小されます。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-104">Normally the screens of a canvas app are scaled to fit the space provided by the app host.</span></span>  <span data-ttu-id="3ce4b-105">これにより、任意の画面で正しい比率で表示されるアプリを作成するのが簡単になります。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-105">This makes it easy to create an app and know that it will look proportionally correct on any screen in which it's used.</span></span>  <span data-ttu-id="3ce4b-106">ただし、デメリットもあります。画面が大きくなると、アプリは余分な領域を有効活用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-106">But it comes at a price - as screens get bigger, the app can't adapt to take advantage of the additional real estate.</span></span>  <span data-ttu-id="3ce4b-107">今日の多くの Web サイトは "レスポンシブ" です。表示される画面に応じてサイズを調整し、スマートフォンの小さな画面からデスクトップの大きな画面にまで対応しています。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-107">Many websites today are "responsive" - they adjust depending on the size of the screen they are shown on, adapting from small screens on phones to large screens on desktops.</span></span>  

<span data-ttu-id="3ce4b-108">この機能を使用して、経験豊富なアプリ開発者はレスポンシブなキャンバス アプリを作成できます。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-108">With this feature, experienced app makers can create responsive canvas apps.</span></span>  <span data-ttu-id="3ce4b-109">ランタイム時の画面のサイズに基づいて、コントロールのサイズと位置を調整する式を記述する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-109">You must write formulas that adapt the size and position of controls based on the size of the screen at runtime.</span></span>  <span data-ttu-id="3ce4b-110">既定のスケーリング動作は無効にできます。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-110">You can turn off the default scaling behavior.</span></span>  <span data-ttu-id="3ce4b-111">その結果、適切なフォント サイズの情報が画面に表示されるようになり、アプリのエクスペリエンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="3ce4b-111">As a result, screens show more information with more appropriate font sizes, all making for a better app experience.</span></span>

