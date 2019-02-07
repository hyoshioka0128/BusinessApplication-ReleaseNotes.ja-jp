---
title: パフォーマンスの向上
description: Dynamics 365 Layout の 2018 年 12 月のアップデートでのパフォーマンスの向上には、新しい Performance 設定と、シーンが複雑な場合にそれを示すバーが含まれています
author: ornellaalt
ms.author: ornella
ms.date: 12/05/2018
ms.topic: article
ms.service: business-applications
ms.reviewer: v-brycho
ms.openlocfilehash: 9a8e7f2126be879e8f39328eaf45cf9aa64602f3
ms.sourcegitcommit: 163b0e8ec8da8ef8bbe43f302c561bbaed43d0be
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2019
ms.locfileid: "290548"
---
# <a name="performance-improvements"></a><span data-ttu-id="f483e-103">パフォーマンスの向上</span><span class="sxs-lookup"><span data-stu-id="f483e-103">Performance improvements</span></span>
<span data-ttu-id="f483e-104">2018 年 12 月 5 日に次のようなパフォーマンス向上を行いました。</span><span class="sxs-lookup"><span data-stu-id="f483e-104">We made the following performance improvements on December 5, 2018.</span></span>

## <a name="performance-setting"></a><span data-ttu-id="f483e-105">パフォーマンス設定</span><span class="sxs-lookup"><span data-stu-id="f483e-105">Performance setting</span></span>

<span data-ttu-id="f483e-106">多くのお客様から、特定のシナリオでは 3D アセットのビジュアル化にテクスチャや複数色は重要でないとお聞きしました。</span><span class="sxs-lookup"><span data-stu-id="f483e-106">We've heard from many of our customers that in certain scenarios, textures or multiple colors aren't important for visualizing 3D assets.</span></span> <span data-ttu-id="f483e-107">それ以外の場合は、色やテクスチャを妥協できず、元の形式でアセットを表示できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="f483e-107">In other cases, they can't compromise on color or texture and need to be able to view assets in their original form.</span></span> <span data-ttu-id="f483e-108">テクスチャと複数色が重要でない場合にパフォーマンスを向上させるために、新しいパフォーマンス設定を追加しました。</span><span class="sxs-lookup"><span data-stu-id="f483e-108">To improve performance when textures and multiple colors aren't important, we added a new Performance setting.</span></span> <span data-ttu-id="f483e-109">設定をオンにすると、テクスチャが削除され、アセットが単一色で表示されます。</span><span class="sxs-lookup"><span data-stu-id="f483e-109">When the setting is turned on, textures are removed and assets are displayed as a single color.</span></span> <span data-ttu-id="f483e-110">状況に応じて、設定をオンまたはオフに切り替えます。</span><span class="sxs-lookup"><span data-stu-id="f483e-110">Switch the setting on or off, depending on the situation.</span></span> 

<span data-ttu-id="f483e-111">パフォーマンス モードをオンまたはオフにするには、**設定**に移動し、**パフォーマンス**を選択してから、**1 つの色だけを使用してオブジェクトを単純化する**オプションをオンまたはオフにします。</span><span class="sxs-lookup"><span data-stu-id="f483e-111">To turn performance mode on or off, go to **Settings**, select **Performance**, and then turn the **Simplify objects by using just one color** option on or off.</span></span> 

<span data-ttu-id="f483e-112">![パフォーマンスモードの設定](media/performance-mode-setting.PNG "パフォーマンスモードの設定")</span><span class="sxs-lookup"><span data-stu-id="f483e-112">![Performance mode setting](media/performance-mode-setting.PNG "Performance mode setting")</span></span> 


## <a name="view-complexity-bar"></a><span data-ttu-id="f483e-113">複雑度の表示バー</span><span class="sxs-lookup"><span data-stu-id="f483e-113">View Complexity bar</span></span>
<span data-ttu-id="f483e-114">一部のお客様は、多くのアセットを 1 つのシーンに配置します。</span><span class="sxs-lookup"><span data-stu-id="f483e-114">Some of our customers place many assets in a single scene.</span></span> <span data-ttu-id="f483e-115">より複雑なアセットがシーンに追加されると、各アセットが荷重を追加するためパフォーマンスが低下します。</span><span class="sxs-lookup"><span data-stu-id="f483e-115">As more complex assets get added to the scene, the performance drops, since each asset adds weight.</span></span> <span data-ttu-id="f483e-116">現在のシーンの複雑度を判断するために、**複雑度の表示**バーを追加しました。</span><span class="sxs-lookup"><span data-stu-id="f483e-116">To determine the complexity of the current scene, we added a **View Complexity** bar.</span></span>

<span data-ttu-id="f483e-117">![複雑度のバー](media/complexity-bar.PNG "複雑度のバー")</span><span class="sxs-lookup"><span data-stu-id="f483e-117">![Complexity bar](media/complexity-bar.PNG "Complexity bar")</span></span> 

<span data-ttu-id="f483e-118">バーを使用して、複雑度が高すぎる場合はそれを把握し、トレードオフの判断をします。</span><span class="sxs-lookup"><span data-stu-id="f483e-118">Use the bar to determine when complexity is too high, and to make tradeoffs.</span></span>

 


