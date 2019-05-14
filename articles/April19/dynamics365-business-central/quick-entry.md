---
title: 簡単入力
description: 簡単入力機能は、使用頻度の低いフィールドはスキップすることで、レコードの繰り返し入力に要する時間を短縮します。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 04/04/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: c93d104d0687cebeba3af05bccf9bd3177d0fd74
ms.sourcegitcommit: d38444f318edcbde1d3c922cbf676072b87e5fbb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/02/2019
ms.locfileid: "1447142"
---
# <a name="quick-entry"></a><span data-ttu-id="0a2ae-103">簡単入力</span><span class="sxs-lookup"><span data-stu-id="0a2ae-103">Quick Entry</span></span>
<span data-ttu-id="0a2ae-104">デスクトップ ブラウザーおよび Windows デスクトップ アプリ用の強力な簡単入力機能を使用して、レコードの繰り返し入力に要する時間を短縮します。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-104">Accelerate repetitive entry of records with the powerful Quick Entry feature for the desktop browser and Windows desktop app.</span></span>

## <a name="business-value"></a><span data-ttu-id="0a2ae-105">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0a2ae-105">Business value</span></span>
<span data-ttu-id="0a2ae-106">デスクトップ ユーザーは、電話での注文の受付、領収書のデジタル化、新しい品目の登録など、情報を繰り返し入力して連続するレコードを作成するのに、かなりの時間を費やしています。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-106">Desktop users spend significant time on repeatedly typing in information to create records in sequence, such as taking orders over the phone, digitizing receipts or registering new items.</span></span> <span data-ttu-id="0a2ae-107">ユーザーはページ上でできるだけ多くの詳細を表示することを求める一方で、レコードを作成するときに一貫して入力する必要があるフィールドはほんの一部に過ぎません。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-107">While users want to view as much detail as possible on a page, only a fraction of those fields must consistently be filled in when creating the record.</span></span> <span data-ttu-id="0a2ae-108">Tab キーを使用したページ上のフィールドの移動順序は決まっているため、マウスを使用せずに作業しているユーザーにとって、それらの必須フィールドを移動することは負担になります。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-108">Navigating to those essential fields becomes cumbersome when working mouse-free, as users are forced to follow the standard tab order of fields on the page.</span></span>

<span data-ttu-id="0a2ae-109">簡単入力は、ページ上の編集可能なフィールドを移動する代替手段を提供する、シンプルかつ強力な機能です。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-109">Quick Entry is a powerful and simple feature that provides an alternate path through editable fields on a page.</span></span> <span data-ttu-id="0a2ae-110">Enter キーの動作は Tab キーの動作とは異なり、必須でないフィールドをスキップし、そのページの次の簡単入力フィールドにフォーカスを移動します。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-110">It changes the behavior of the Enter key to be different from the Tab key, moving the focus to the next Quick Entry field across the page and skipping over non-essential fields.</span></span>

<span data-ttu-id="0a2ae-111">![簡単入力の対象のフィールドが人為的にハイライト表示されている、複数のフィールドが存在するページのスクリーンショット](media/quick-entry-animated.gif "簡単入力の対象のフィールドが人為的にハイライト表示されている文書ページ")</span><span class="sxs-lookup"><span data-stu-id="0a2ae-111">![Screen grab of a page with multiple fields, artificially highlighting those included in Quick Entry](media/quick-entry-animated.gif "A document page artificially highlighting Quick Entry fields")</span></span>

## <a name="including-or-excluding-fields-from-the-quick-entry-path"></a><span data-ttu-id="0a2ae-112">簡単入力パスに対するフィールドの追加または除外</span><span class="sxs-lookup"><span data-stu-id="0a2ae-112">Including or excluding fields from the Quick Entry path</span></span>
<span data-ttu-id="0a2ae-113">簡単入力は最新かつイマーシブなパーソナル化エクスペリエンスを使用してパーソナライズ可能で、ユーザーは Business Central を自身または自身の部署のデータ入力方法に合わせてカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-113">Quick Entry can be personalized using the modern and immersive personalization experience, empowering users to tailor Business Central to how they or their department typically enters data.</span></span>

<span data-ttu-id="0a2ae-114">開発者は自身のアプリケーションで簡単入力フィールドの初期パスをページごとに定義し、それを拡張機能でカスタマイズできるほか、特定のロールのプロファイルに合わせてカスタマイズすることもできます。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-114">Developers can define an initial path of Quick Entry fields per page in their application, customize that in extensions, and also tailor it to specific role profiles.</span></span> <span data-ttu-id="0a2ae-115">さらに、簡単入力 AL プロパティは簡単入力の動的パスを別個のフィールドに作成する式をサポートします。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-115">Furthermore, the Quick Entry AL property supports expressions to create dynamic Quick Entry paths to different fields.</span></span>

## <a name="a-truly-productive-experience"></a><span data-ttu-id="0a2ae-116">生産性の高いエクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="0a2ae-116">A truly productive experience</span></span>
<span data-ttu-id="0a2ae-117">簡単入力は集中的に利用するユーザーのニーズに合わせて慎重に設計されており、Dynamics NAV の以前の簡単入力機能から次のように改善されています。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-117">Carefully designed for the needs of intensive users, Quick Entry includes improvements over the earlier Quick Entry feature in Dynamics NAV, such as:</span></span>

- <span data-ttu-id="0a2ae-118">**Enter** キー、**Shift+Enter** キー、**Shift+Ctrl+Enter** などの強力なキーの組み合わせを使用することで、編集可能な部分 (リスト部分など) の内外への移動を含め、そのページのすべての簡単入力フィールドに移動できる。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-118">Moving to any Quick Entry field across the page, including moving in and out of editable parts such as list parts, by using a powerful combination of keys: **Enter**, **Shift+Enter** and **Shift+Ctrl+Enter**.</span></span>
- <span data-ttu-id="0a2ae-119">次の簡単入力フィールドがそのグループ内にある場合に、折りたたまれたクイック タブ (フィールド グループ) を展開する。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-119">Expanding a collapsed FastTab (field group) if the next Quick Entry field is in that group.</span></span>
- <span data-ttu-id="0a2ae-120">そのページの最後の簡単入力フィールドに到達すると一回りして最初のフィールドに戻る。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-120">Cycling from the last Quick Entry field to the first Quick Entry field on the page.</span></span>
 
## <a name="try-it-now"></a><span data-ttu-id="0a2ae-121">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="0a2ae-121">Try it now</span></span>
<span data-ttu-id="0a2ae-122">[https://businesscentral.dynamics.com/?page=42&mode=create](https://businesscentral.dynamics.com/?page=42&mode=create) でオンライン環境にログインして、新しい販売注文で Tab キーを使用する場合と Enter キーを使用する場合の違いを体験してください。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-122">Experience the difference between using Tab and Enter keys on a new sales order by signing in to your online environment at [https://businesscentral.dynamics.com/?page=42&mode=create](https://businesscentral.dynamics.com/?page=42&mode=create).</span></span>

## <a name="resources"></a><span data-ttu-id="0a2ae-123">リソース</span><span class="sxs-lookup"><span data-stu-id="0a2ae-123">Resources</span></span>
[<span data-ttu-id="0a2ae-124">簡単入力の使用</span><span class="sxs-lookup"><span data-stu-id="0a2ae-124">Using Quick Entry</span></span>](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data#QuickEntry)<br>  
[<span data-ttu-id="0a2ae-125">キーボード ショートカット</span><span class="sxs-lookup"><span data-stu-id="0a2ae-125">Keyboard Shortcuts</span></span>](https://aka.ms/bckeys)  <br>
[<span data-ttu-id="0a2ae-126">ワークスペースのパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="0a2ae-126">Personalize your workspace</span></span>](https://docs.microsoft.com/dynamics365/business-central/ui-personalization-user)  <br>
[<span data-ttu-id="0a2ae-127">技術文書: QuickEntry プロパティ</span><span class="sxs-lookup"><span data-stu-id="0a2ae-127">Technical Documentation: QuickEntry property</span></span>](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-quickentry-property)  <br>
[<span data-ttu-id="0a2ae-128">技術文書: デザイナーの使用</span><span class="sxs-lookup"><span data-stu-id="0a2ae-128">Technical Documentation: Using the Designer</span></span>](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-inclient-designer)  

## <a name="tell-us-what-you-think"></a><span data-ttu-id="0a2ae-129">フィードバック</span><span class="sxs-lookup"><span data-stu-id="0a2ae-129">Tell us what you think</span></span>
<span data-ttu-id="0a2ae-130">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-130">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="0a2ae-131">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="0a2ae-131">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
