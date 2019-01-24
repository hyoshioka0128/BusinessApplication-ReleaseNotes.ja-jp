---
title: "パフォーマンスの向上"
description: "Dynamics 365 レイアウトの 2018 年 12 月のアップデートでのパフォーマンスの向上には、新しいパフォーマンス設定と、シーンが複雑な場合にそれを示すバーが含まれています"
author: ornellaalt
ms.author: ornella
ms.date: 12/05/2018
ms.topic: article
ms.service: business-applications
ms.reviewer: v-brycho
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: a618e9d323e30e9583aaea7ecfd01f66f3e42b25
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

# <a name="performance-improvements"></a><span data-ttu-id="e2f27-103">パフォーマンスの向上</span><span class="sxs-lookup"><span data-stu-id="e2f27-103">Performance improvements</span></span>
<span data-ttu-id="e2f27-104">2018 年 12 月 5 日に次のようなパフォーマンス向上を行いました。</span><span class="sxs-lookup"><span data-stu-id="e2f27-104">We made the following performance improvements on December 5, 2018.</span></span>

## <a name="performance-setting"></a><span data-ttu-id="e2f27-105">パフォーマンス設定</span><span class="sxs-lookup"><span data-stu-id="e2f27-105">Performance setting</span></span>

<span data-ttu-id="e2f27-106">多くのお客様から、特定のシナリオでは 3D アセットのビジュアル化にテクスチャや複数色は重要でないと伺いました。</span><span class="sxs-lookup"><span data-stu-id="e2f27-106">We've heard from many of our customers that in certain scenarios, textures or multiple colors aren't important for visualizing 3D assets.</span></span> <span data-ttu-id="e2f27-107">それ以外の場合は、色やテクスチャを妥協できず、元の形式でアセットを表示できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2f27-107">In other cases, they can't compromise on color or texture and need to be able to view assets in their original form.</span></span> <span data-ttu-id="e2f27-108">テクスチャと複数色が重要でない場合にパフォーマンスを向上させるために、新しいパフォーマンス設定を追加しました。</span><span class="sxs-lookup"><span data-stu-id="e2f27-108">To improve perfomance when textures and multiple colors aren't important, we added a new Performance setting.</span></span> <span data-ttu-id="e2f27-109">設定をオンにすると、テクスチャが削除され、アセットが単一色で表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2f27-109">When the setting is turned on, textures are removed and assets are displayed as a single color.</span></span> <span data-ttu-id="e2f27-110">状況に応じて、設定をオンまたはオフに切り替えます。</span><span class="sxs-lookup"><span data-stu-id="e2f27-110">Switch the setting on or off, depending on the situation.</span></span> 

<span data-ttu-id="e2f27-111">パフォーマンス モードをオンまたはオフにするには、**設定**に移動し、**パフォーマンス**を選択してから、**1 つの色だけを使用してオブジェクトを単純化する**オプションをオンまたはオフにします。</span><span class="sxs-lookup"><span data-stu-id="e2f27-111">To turn performance mode on or off, go to **Settings**, select **Performance**, and then turn the **Simplify objects by using just one color** option on or off.</span></span> 

<span data-ttu-id="e2f27-112">![パフォーマンスモードの設定](media/performance-mode-setting.PNG "パフォーマンスモードの設定")</span><span class="sxs-lookup"><span data-stu-id="e2f27-112">![Performance mode setting](media/performance-mode-setting.PNG "Performance mode setting")</span></span> 


## <a name="view-complexity-bar"></a><span data-ttu-id="e2f27-113">複雑度の表示バー</span><span class="sxs-lookup"><span data-stu-id="e2f27-113">View Complexity bar</span></span>
<span data-ttu-id="e2f27-114">一部のお客様は、多くのアセットを 1 つのシーンに配置します。</span><span class="sxs-lookup"><span data-stu-id="e2f27-114">Some of our customers place many assets in a single scene.</span></span> <span data-ttu-id="e2f27-115">より複雑なアセットがシーンに追加されると、各アセットが荷重を追加するためパフォーマンスが低下します。</span><span class="sxs-lookup"><span data-stu-id="e2f27-115">As more complex assets get added to the scene, the performance drops, since each asset adds weight.</span></span> <span data-ttu-id="e2f27-116">現在のシーンの複雑度を判断するために、**複雑度の表示**バーを追加しました。</span><span class="sxs-lookup"><span data-stu-id="e2f27-116">To determine the complexity of the current scene, we added a **View Complexity** bar.</span></span>

<span data-ttu-id="e2f27-117">![複雑度のバー](media/complexity-bar.PNG "複雑度のバー")</span><span class="sxs-lookup"><span data-stu-id="e2f27-117">![Complexity bar](media/complexity-bar.PNG "Complexity bar")</span></span> 

<span data-ttu-id="e2f27-118">バーを使用して、複雑度が高すぎる場合はそれを把握し、トレードオフの判断をします。</span><span class="sxs-lookup"><span data-stu-id="e2f27-118">Use the bar to determine when complexity is too high, and to make tradeoffs.</span></span>

 



