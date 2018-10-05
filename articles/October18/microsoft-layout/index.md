---
title: "2018 年 10 月リリースの Dynamics 365 レイアウトの概要"
description: "レイアウトによって、物理デザインのコンセプトから完成に至るまで新たな方法がもたらされます。"
author: ReneeW-CPub
manager: AnnBe
ms.date: 09/24/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gkaralis
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 9a509b6e98583d8782e00c5c0e081f7ec451180b
ms.openlocfilehash: b9e8131b30e54920935262a02889d73097076888
ms.contentlocale: ja-jp
ms.lasthandoff: 09/22/2018

---

# <a name="overview-of-dynamics-365-layout-october-18-release"></a><span data-ttu-id="bc64f-103">2018 年 10 月リリースの Dynamics 365 レイアウトの概要</span><span class="sxs-lookup"><span data-stu-id="bc64f-103">Overview of Dynamics 365 Layout October ’18 release</span></span>

[!include[microsoft-layout banner](../includes/microsoft-layout.md)]

<span data-ttu-id="bc64f-104">製造、プロフェッショナル サービス、小売りなどの複数の業界に空間プランニングのニーズがあります。</span><span class="sxs-lookup"><span data-stu-id="bc64f-104">Multiple industries, including manufacturing, professional services, and retail, have needs for space planning.</span></span> <span data-ttu-id="bc64f-105">非常に複雑な CAD ソフトウェアから 2D ビジュアル化ソフトウェア、ボール紙や発泡体コアでの構築などのアナログ ソリューションまで、今日のさまざまな空間プランニング ツールがこうしたニーズを満たします。</span><span class="sxs-lookup"><span data-stu-id="bc64f-105">A variety of space planning tools today fill these needs, ranging from extremely complex CAD software to 2D visualization software to analog solutions such as building in cardboard and foamcore.</span></span> <span data-ttu-id="bc64f-106">それぞれに短所があります。</span><span class="sxs-lookup"><span data-stu-id="bc64f-106">Each has its drawbacks.</span></span> <span data-ttu-id="bc64f-107">CAD プログラムは高い忠実性を発揮しますが、エキスパート以外が理解するのは困難です。</span><span class="sxs-lookup"><span data-stu-id="bc64f-107">CAD programs offer a high degree of fidelity, but are difficult for non-experts to understand.</span></span> <span data-ttu-id="bc64f-108">2D 描画では空間の見た目や感触が現実の世界でどうなるかが完全にはわからず、ボール紙や発泡体コアは取り扱いが面倒で高価です。</span><span class="sxs-lookup"><span data-stu-id="bc64f-108">2D drawings often don’t tell a complete story of what a space will truly look or feel like in real life, and cardboard and foamcore are messy and expensive.</span></span>

<span data-ttu-id="bc64f-109">Microsoft Dynamics 365 レイアウトによって、物理デザインのコンセプトから完成に至るまで信頼度の高い新たな方法がもたらされます。</span><span class="sxs-lookup"><span data-stu-id="bc64f-109">Microsoft Dynamics 365 Layout provides a new way to bring physical designs from concept to completion with confidence.</span></span> <span data-ttu-id="bc64f-110">3D モデルをインポートし、現実の世界または仮想現実でホログラムを利用して室内のレイアウトを体験します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-110">Import 3D models to experience room layouts as holograms in the physical world or in virtual reality.</span></span> <span data-ttu-id="bc64f-111">関係者とビジョンを共有し、実際の規模でレイアウトを簡単に編集できるため、構築する前により適切な意思決定を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="bc64f-111">Share your vision with stakeholders and easily edit layouts in real-world scale, so you can make better decisions before you build.</span></span>

> [!NOTE]
> <span data-ttu-id="bc64f-112">レイアウトは 2018 年 4 月にプレビュー アプリとしてリリースされました。</span><span class="sxs-lookup"><span data-stu-id="bc64f-112">Layout was released as a preview app in April 2018.</span></span> <span data-ttu-id="bc64f-113">10 月のリリース時点で、レイアウトは一般提供されます。</span><span class="sxs-lookup"><span data-stu-id="bc64f-113">As of the October release, Layout is Generally Available.</span></span>

## <a name="define-your-space"></a><span data-ttu-id="bc64f-114">空間の定義</span><span class="sxs-lookup"><span data-stu-id="bc64f-114">Define your space</span></span>

-   <span data-ttu-id="bc64f-115">HoloLens で空間をスキャンすると、新しい部屋のレイアウトがすぐに作成されます。</span><span class="sxs-lookup"><span data-stu-id="bc64f-115">Scan your space with HoloLens to quickly create a new room layout.</span></span>

-   <span data-ttu-id="bc64f-116">または、Microsoft Visio で基本的なフロア プランを作成してから、HoloLens または Windows Mixed Reality にインポートします。</span><span class="sxs-lookup"><span data-stu-id="bc64f-116">Or create a basic floor plan in Microsoft Visio, and then import it into HoloLens or Windows Mixed Reality.</span></span>

## <a name="import-3d-models"></a><span data-ttu-id="bc64f-117">3D モデルのインポート</span><span class="sxs-lookup"><span data-stu-id="bc64f-117">Import 3D models</span></span>

-   <span data-ttu-id="bc64f-118">Microsoft Dynamics 365 インポート ツールを (プレビュー) 使用してカスタム 3D モデルを準備します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-118">Use the Microsoft Dynamics 365 Import Tool (Preview) to prepare your custom 3D models.</span></span> <span data-ttu-id="bc64f-119">ツールでは、FBX、OBJ、SKP、STP、JT、STEP および GLTF 形式のモデルを Microsoft Simplygon サービスにアップロードして GLB に変換し、必要に応じて縮小してデバイス上のパフォーマンスを向上させ、必要なメタデータを追加します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-119">The tool uploads your models in FBX, OBJ, SKP, STP, JT, STEP, and GLTF formats to the Microsoft Simplygon service, converts them to GLB, decimates them if necessary for improved on-device performance, and adds necessary metadata.</span></span> <span data-ttu-id="bc64f-120">クラウド サービスを使用したくない場合には、ご使用の PC で GLB 形式を変換することもできます。</span><span class="sxs-lookup"><span data-stu-id="bc64f-120">You have the option of converting GLB formats with your PC if you don’t want to use the cloud service.</span></span>

-   <span data-ttu-id="bc64f-121">一般的な製造、オフィス、グレーボックス資産のライブラリから選択して空間を計画します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-121">Select from a library of common manufacturing, office, and graybox assets to plan your space.</span></span>

## <a name="design-your-space"></a><span data-ttu-id="bc64f-122">空間のデザイン</span><span class="sxs-lookup"><span data-stu-id="bc64f-122">Design your space</span></span>

-   <span data-ttu-id="bc64f-123">カスタムまたは定義済みの資産を空間に配置します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-123">Place custom or predefined assets into your space.</span></span>

-   <span data-ttu-id="bc64f-124">必要に応じて資産をサイズ変更、回転、移動、複製、または削除します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-124">Resize, rotate, move, duplicate, or delete assets as necessary.</span></span>

-   <span data-ttu-id="bc64f-125">レイアウトを再読み込みして部屋に再配置します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-125">Reload layouts and realign them to your room.</span></span>

## <a name="review-with-stakeholders"></a><span data-ttu-id="bc64f-126">関係者によるレビュー</span><span class="sxs-lookup"><span data-stu-id="bc64f-126">Review with stakeholders</span></span>

-   <span data-ttu-id="bc64f-127">Cortana を使用して、写真を撮るかビデオを作成します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-127">Use Cortana to take a picture or create a video.</span></span>

-   <span data-ttu-id="bc64f-128">HoloLens で Dynamics 365 リモート アシストを使用して、HoloLens ユーザーに見えているものをストリーム配信します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-128">On HoloLens, use Dynamics 365 Remote Assist to stream what the HoloLens user is seeing.</span></span>

-   <span data-ttu-id="bc64f-129">Windows Mixed Reality では、画面共有を使用します。</span><span class="sxs-lookup"><span data-stu-id="bc64f-129">In Windows Mixed Reality, use screen sharing.</span></span>

## <a name="export-your-design"></a><span data-ttu-id="bc64f-130">デザインのエクスポート</span><span class="sxs-lookup"><span data-stu-id="bc64f-130">Export your design</span></span>

-   <span data-ttu-id="bc64f-131">PC で (たとえば Windows Mixed Reality ビューアーで) 表示するために空間を 3D GLTF にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="bc64f-131">Export your space to a 3D GLTF for viewing on a PC (in Windows Mixed Reality Viewer, for example).</span></span>

<!-- link to docs 
### See also
[Device options and requirements](requirements.md) <br>
[Buy and deploy](licensing/buy-and-deploy.md) <br>
[User Guide](user-guide.md) <br>
[FAQ](faq.md)
-->

