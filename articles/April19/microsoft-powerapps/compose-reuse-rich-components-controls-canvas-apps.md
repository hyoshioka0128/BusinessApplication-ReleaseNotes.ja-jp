---
title: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
description: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
author: yifwang
ms.reviewer: anneta
ms.date: 01/09/2019
ms.assetid: a77bde74-bcc5-e811-a973-000d3a137a43
ms.topic: article
ms.service: business-applications
ms.author: yifwang
audience: Power user
ms.openlocfilehash: 25d392683f17ed64aec8b0f2370783c85f437f72
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287961"
---
# <a name="compose-and-reuse-rich-components-and-controls-in-canvas-apps-public-preview"></a><span data-ttu-id="6d703-103">キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="6d703-103">Compose and reuse rich components and controls in canvas apps (Public Preview)</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="6d703-104">作成者は、メニューやカレンダーなどの要素を作成し、同じアプリまたは複数のアプリの複数の画面で共有できます。</span><span class="sxs-lookup"><span data-stu-id="6d703-104">Makers can build and share elements, such as menus or calendars, on multiple screens of the same app or in multiple apps.</span></span> <span data-ttu-id="6d703-105">作成者は、これらの再利用可能なコンポーネントと複合コントロールを、キャンバス アプリを構築するのと同じように、PowerApps Studio で作成できます。</span><span class="sxs-lookup"><span data-stu-id="6d703-105">Makers can build these reusable components and composite controls in PowerApps Studio, just as they build canvas apps.</span></span>

<span data-ttu-id="6d703-106">これらに関する改善点は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="6d703-106">These improvements include:</span></span>

- <span data-ttu-id="6d703-107">PowerApps Studio を使用し、キャンバス コントロールと式を使用してコンポーネントを構築する。</span><span class="sxs-lookup"><span data-stu-id="6d703-107">Use PowerApps Studio to build components by using canvas controls and expressions.</span></span>
- <span data-ttu-id="6d703-108">1 つのアプリ内でコンポーネントを複数回使用する。</span><span class="sxs-lookup"><span data-stu-id="6d703-108">Use a component multiple times within a single app.</span></span>
- <span data-ttu-id="6d703-109">異なるアプリ間でコンポーネントを使用する。</span><span class="sxs-lookup"><span data-stu-id="6d703-109">Use a component across different apps.</span></span>
- <span data-ttu-id="6d703-110">コンポーネントを使用するときに必要な入力と出力を定義する。</span><span class="sxs-lookup"><span data-stu-id="6d703-110">Define the inputs and outputs that are required when a component is consumed.</span></span>
- <span data-ttu-id="6d703-111">一箇所でコンポーネントを更新し、アプリで使用されるコンポーネントの更新とバージョンを管理する。</span><span class="sxs-lookup"><span data-stu-id="6d703-111">Update components in a single location, and manage updates and versions of components that are consumed in apps.</span></span>
- <span data-ttu-id="6d703-112">コンポーネントを環境からエクスポートし、環境にインポートする。</span><span class="sxs-lookup"><span data-stu-id="6d703-112">Export and import components from environments.</span></span>
- <span data-ttu-id="6d703-113">一般的なシナリオ用の組み込みコンポーネントを使用する。</span><span class="sxs-lookup"><span data-stu-id="6d703-113">Consume built-in components for common scenarios.</span></span>

<span data-ttu-id="6d703-114">キャンバス コンポーネントを使用することで、作成者は、画面やアプリ間で構成要素をすばやく作成、使用、共有し、アプリをより迅速に構築し、アプリをより簡単に維持することができます。</span><span class="sxs-lookup"><span data-stu-id="6d703-114">By using canvas components, makers can quickly create, consume, and share their building blocks across screens and apps, build apps more quickly, and maintain apps more easily.</span></span>

<span data-ttu-id="6d703-115">![キャンバス コンポーネントを作成する](media/createcomponent.JPG "キャンバス コンポーネントを作成する")</span><span class="sxs-lookup"><span data-stu-id="6d703-115">![Create canvas component](media/createcomponent.JPG "Create canvas component")</span></span>
