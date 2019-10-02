---
title: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
description: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
author: yifwang
ms.reviewer: pehecke
ms.date: 04/24/2019
ms.assetid: 2187bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: yifwang
audience: Power user
ms.openlocfilehash: ba0b6363ca61897676a4ce6e4731b9b6263b19d7
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994000"
---
# <a name="compose-and-reuse-rich-components-and-controls-in-canvas-apps-public-preview"></a><span data-ttu-id="a6137-103">キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="a6137-103">Compose and reuse rich components and controls in canvas apps (Public Preview)</span></span>



<span data-ttu-id="a6137-104">作成者は、メニューやカレンダーなどの要素を作成し、同じアプリまたは複数のアプリの複数の画面で共有できます。</span><span class="sxs-lookup"><span data-stu-id="a6137-104">Makers can build and share elements, such as menus or calendars, on multiple screens of the same app or in multiple apps.</span></span> <span data-ttu-id="a6137-105">作成者は、これらの再利用可能なコンポーネントと複合コントロールを、キャンバス アプリを構築するのと同じように、PowerApps Studio で作成できます。</span><span class="sxs-lookup"><span data-stu-id="a6137-105">Makers can build these reusable components and composite controls in PowerApps Studio, just as they build canvas apps.</span></span>

<span data-ttu-id="a6137-106">これらに関する改善点は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a6137-106">These improvements include:</span></span>

- <span data-ttu-id="a6137-107">PowerApps Studio を使用し、キャンバス コントロールと式を使用してコンポーネントを構築する。</span><span class="sxs-lookup"><span data-stu-id="a6137-107">Use PowerApps Studio to build components by using canvas controls and expressions.</span></span>
- <span data-ttu-id="a6137-108">1 つのアプリ内でコンポーネントを複数回使用する。</span><span class="sxs-lookup"><span data-stu-id="a6137-108">Use a component multiple times within a single app.</span></span>
- <span data-ttu-id="a6137-109">異なるアプリ間でコンポーネントを使用する。</span><span class="sxs-lookup"><span data-stu-id="a6137-109">Use a component across different apps.</span></span>
- <span data-ttu-id="a6137-110">コンポーネントを使用するときに必要な入力と出力を定義する。</span><span class="sxs-lookup"><span data-stu-id="a6137-110">Define the inputs and outputs that are required when a component is consumed.</span></span>
- <span data-ttu-id="a6137-111">一箇所でコンポーネントを更新し、アプリで使用されるコンポーネントの更新とバージョンを管理する。</span><span class="sxs-lookup"><span data-stu-id="a6137-111">Update components in a single location, and manage updates and versions of components that are consumed in apps.</span></span>
- <span data-ttu-id="a6137-112">コンポーネントを環境からエクスポートし、環境にインポートする。</span><span class="sxs-lookup"><span data-stu-id="a6137-112">Export and import components from environments.</span></span>
- <span data-ttu-id="a6137-113">一般的なシナリオ用の組み込みコンポーネントを使用する。</span><span class="sxs-lookup"><span data-stu-id="a6137-113">Consume built-in components for common scenarios.</span></span>

<span data-ttu-id="a6137-114">キャンバス コンポーネントを使用することで、作成者は、画面やアプリ間で構成要素をすばやく作成、使用、共有し、アプリをより迅速に構築し、アプリをより簡単に維持することができます。</span><span class="sxs-lookup"><span data-stu-id="a6137-114">By using canvas components, makers can quickly create, consume, and share their building blocks across screens and apps, build apps more quickly, and maintain apps more easily.</span></span>

<span data-ttu-id="a6137-115">![キャンバス コンポーネントを作成する](media/createcomponent.JPG "キャンバス コンポーネントを作成する")</span><span class="sxs-lookup"><span data-stu-id="a6137-115">![Create canvas component](media/createcomponent.JPG "Create canvas component")</span></span>
