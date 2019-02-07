---
title: インポート ツールの改善
description: 2019 年 1 月の更新プログラムでの Dynamics 365 インポート ツール (プレビュー) の改善。
author: ornellaalt
ms.date: 01/16/2019
ms.topic: article
ms.service: business-applications
ms.author: ornella
ms.reviewer: v-brycho
ms.openlocfilehash: b31cdcfd5674f88fb9bafcef260f7a545fb7b0e6
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288232"
---
# <a name="import-tool-improvements"></a><span data-ttu-id="ce6c9-103">インポート ツールの改善</span><span class="sxs-lookup"><span data-stu-id="ce6c9-103">Import Tool improvements</span></span>

<span data-ttu-id="ce6c9-104">インポート ツールに対する 2019 年 1 月の更新プログラムでは、3D モデルのインポートを容易にするいくつかの改善が行われています。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-104">The January 2019 update for the Import Tool provides several improvements that make it easier to import 3D models.</span></span>

## <a name="improved-control-with-microsoft-cloud-service"></a><span data-ttu-id="ce6c9-105">Microsoft クラウド サービスによる制御の改善</span><span class="sxs-lookup"><span data-stu-id="ce6c9-105">Improved control with Microsoft Cloud Service</span></span>

<span data-ttu-id="ce6c9-106">Microsoft クラウド サービスを使用するときに、資産最適化プロセスをより細かく制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-106">You now have more control over the asset optimization process when using the Microsoft Cloud Service.</span></span> <span data-ttu-id="ce6c9-107">通常は 1 つのシーンに配置されるいくつかのモデルと共に、モデルのターゲット デバイスを指定できます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-107">You can specify the target device for your model along with the number of models usually placed in a single scene.</span></span> <span data-ttu-id="ce6c9-108">インポート ツールでは、目的の使用シナリオに適したモデルが生成されます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-108">The Import Tool will then produce models suited to the intended usage scenario.</span></span>

<span data-ttu-id="ce6c9-109">![クラウド サービス オプション](media/cloud-service-option.PNG "クラウド サービス オプション")</span><span class="sxs-lookup"><span data-stu-id="ce6c9-109">![Cloud Service option](media/cloud-service-option.PNG "Cloud Service option")</span></span>

## <a name="iterative-optimization-with-microsoft-cloud-service"></a><span data-ttu-id="ce6c9-110">Microsoft クラウド サービスによる反復的な最適化</span><span class="sxs-lookup"><span data-stu-id="ce6c9-110">Iterative optimization with Microsoft Cloud Service</span></span>

<span data-ttu-id="ce6c9-111">既定では、インポート ツールは指定された使用シナリオとの互換性が非常に高いモデルを生成します。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-111">By default, the Import Tool will produce models that are most compatible with the specified usage scenario.</span></span> <span data-ttu-id="ce6c9-112">ただし、Microsoft クラウド サービス オプションを使用する場合は、パフォーマンスまたは品質の観点からモデルを繰り返し再最適化することを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-112">However, you can choose to iteratively re-optimize a model for performance or for quality when using the Microsoft Cloud Service option.</span></span> <span data-ttu-id="ce6c9-113">パフォーマンスを最適化すると、HoloLens または Windows Mixed Reality ヘッドセットでのモデルのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-113">Optimizing for performance results in models that perform better on a HoloLens or Windows Mixed Reality headset.</span></span> <span data-ttu-id="ce6c9-114">品質を最適化すると、視覚的な品質は向上しますが、HoloLens または Windows Mixed Reality ヘッドセットではうまくレンダリングされない可能性のあるモデルが生成されます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-114">Optimizing for quality results in models that have better visual quality but may not render as well on a HoloLens or Windows Mixed Reality headset.</span></span>

<span data-ttu-id="ce6c9-115">![3D モデルの再最適化](media/reoptimize-slider.PNG "3D モデルの再最適化")</span><span class="sxs-lookup"><span data-stu-id="ce6c9-115">![Re-optimize 3D model](media/reoptimize-slider.PNG "Re-optimize 3D model")</span></span>

## <a name="make-your-models-compatible-without-optimizing-them"></a><span data-ttu-id="ce6c9-116">モデルを最適化せずに互換性を持たせる</span><span class="sxs-lookup"><span data-stu-id="ce6c9-116">Make your models compatible without optimizing them</span></span>

<span data-ttu-id="ce6c9-117">現在は、モデルを最適化しなくても、Microsoft クラウド サービスを使用してモデルを HoloLens または Windows Mixed Reality ヘッドセットと互換にすることができます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-117">You can now use the Microsoft Cloud Service to make your models compatible with HoloLens or Windows Mixed Reality headsets without optimizing the models.</span></span> <span data-ttu-id="ce6c9-118">これを行うには、[最適化なしで変換] オプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-118">To do this, choose the Convert without optimizing option.</span></span> 

<span data-ttu-id="ce6c9-119">![最適化なしで変換オプション](media/convert-without-optimizing.PNG "最適化なしで変換オプション")</span><span class="sxs-lookup"><span data-stu-id="ce6c9-119">![Convert without optimizing option](media/convert-without-optimizing.PNG "Convert without optimizing option")</span></span>

<span data-ttu-id="ce6c9-120">最適化なしでの変換がサポートされているソース ファイルの種類には、FBX、OBJ、SKP、JT、STP、STEP、GLTF があります。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-120">Supported source file types for converting without optimizing include FBX, OBJ, SKP, JT, STP, STEP, and GLTF.</span></span>

## <a name="change-the-background-of-a-model-to-make-it-easier-to-view"></a><span data-ttu-id="ce6c9-121">見やすくするためにモデルの背景を変更する</span><span class="sxs-lookup"><span data-stu-id="ce6c9-121">Change the background of a model to make it easier to view</span></span>

<span data-ttu-id="ce6c9-122">インポートしたモデルを表示するときに、明るい背景と暗い背景を切り替えられるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-122">You can now toggle between a light and dark background when viewing your imported models.</span></span>

<span data-ttu-id="ce6c9-123">![暗い背景](media/dark-background.PNG "暗い背景")
![明るい背景](media/light-background.PNG "明るい背景")</span><span class="sxs-lookup"><span data-stu-id="ce6c9-123">![Dark background](media/dark-background.PNG "Dark background")
![Light background](media/light-background.PNG "Light background")</span></span>

## <a name="provide-feedback-for-each-imported-model"></a><span data-ttu-id="ce6c9-124">インポートされた各モデルにフィードバックを提供する</span><span class="sxs-lookup"><span data-stu-id="ce6c9-124">Provide feedback for each imported model</span></span>

<span data-ttu-id="ce6c9-125">**プロパティ** ウィンドウの**良好**または**不良**ボタンを選択して、インポートされたモデルの品質に関するフィードバックを提供できます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-125">You can provide feedback on the quality of an imported model by selecting the **Looks good** or **Looks broken** button in the **Properties** pane.</span></span>

<span data-ttu-id="ce6c9-126">![フィードバック](media/feedback.PNG "フィードバック")</span><span class="sxs-lookup"><span data-stu-id="ce6c9-126">![Feedback](media/feedback.PNG "Feedback")</span></span>

<span data-ttu-id="ce6c9-127">モデルの品質を 3 以下と評価した場合は、追加コストなしで手動処理するためにモデルを Microsoft に送信するように求められます (オプション)。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-127">If you rate the quality of the model at 3 or lower, you’ll be prompted to submit the model (optional) to Microsoft for manual processing at no additional cost.</span></span> <span data-ttu-id="ce6c9-128">Microsoft によるモデル最適化の後、それをインポート ツールでダウンロードし、レイアウト アプリケーションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-128">After Microsoft optimizes the model, you can download it in the Import Tool and use it with the Layout application.</span></span>

<span data-ttu-id="ce6c9-129">インポート ツールを使用した資産のインポートについて詳しくは、「[Dynamics 365 Layout ユーザー ガイド](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/layout/user-guide)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="ce6c9-129">For more information on importing assets with the Import Tool, see the [Dynamics 365 Layout User Guide](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/layout/user-guide).</span></span> 



