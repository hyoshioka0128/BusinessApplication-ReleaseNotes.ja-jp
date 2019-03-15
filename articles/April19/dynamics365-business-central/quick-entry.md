---
title: 簡単入力
description: 簡単入力機能は、使用頻度の低いフィールドはスキップすることで、レコードの繰り返し入力に要する時間を短縮します。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: 8ab1b587dfb80b177b290429cec4f2dd5a47a697
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "285315"
---
# <a name="quick-entry"></a><span data-ttu-id="59345-103">簡単入力</span><span class="sxs-lookup"><span data-stu-id="59345-103">Quick Entry</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="59345-104">デスクトップ ブラウザーおよび Windows デスクトップ アプリ用の強力な簡単入力機能を使用して、レコードの繰り返し入力に要する時間を短縮します。</span><span class="sxs-lookup"><span data-stu-id="59345-104">Accelerate repetitive entry of records with the powerful Quick Entry feature for the desktop browser and Windows desktop app.</span></span>

## <a name="business-value"></a><span data-ttu-id="59345-105">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="59345-105">Business value</span></span>
<span data-ttu-id="59345-106">デスクトップ ユーザーは、電話での注文の受付、領収書のデジタル化、新しい品目の登録など、情報を繰り返し入力して連続するレコードを作成するのに、かなりの時間を費やしています。</span><span class="sxs-lookup"><span data-stu-id="59345-106">Desktop users spend significant time on repeatedly typing in information to create records in sequence, such as taking orders over the phone, digitizing receipts or registering new items.</span></span> <span data-ttu-id="59345-107">ユーザーはページ上でできるだけ多くの詳細を表示することを求める一方で、レコードを作成するときに一貫して入力する必要があるフィールドはほんの一部に過ぎません。</span><span class="sxs-lookup"><span data-stu-id="59345-107">While users want to view as much detail as possible on a page, only a fraction of those fields must consistently be filled in when creating the record.</span></span> <span data-ttu-id="59345-108">Tab キーを使用したページ上のフィールドの移動順序は決まっているため、マウスを使用せずに作業しているユーザーにとって、それらの必須フィールドを移動することは負担になります。</span><span class="sxs-lookup"><span data-stu-id="59345-108">Navigating to those essential fields becomes cumbersome when working mouse-free, as users are forced to follow the standard tab order of fields on the page.</span></span>

<span data-ttu-id="59345-109">簡単入力は、ページ上の編集可能なフィールドを移動する代替手段を提供する、シンプルかつ強力な機能です。</span><span class="sxs-lookup"><span data-stu-id="59345-109">Quick Entry is a powerful and simple feature that provides an alternate path through editable fields on a page.</span></span> <span data-ttu-id="59345-110">Enter キーの動作は Tab キーの動作とは異なり、必須でないフィールドをスキップし、そのページの次の簡単入力フィールドにフォーカスを移動します。</span><span class="sxs-lookup"><span data-stu-id="59345-110">It changes the behavior of the Enter key to be different from the Tab key, moving the focus to the next Quick Entry field across the page and skipping over non-essential fields.</span></span>

<span data-ttu-id="59345-111">![簡単入力の対象のフィールドが人為的にハイライト表示されている、複数のフィールドが存在するページのスクリーンショット](media/quick-entry-animated.gif "簡単入力の対象のフィールドが人為的にハイライト表示されている文書ページ")</span><span class="sxs-lookup"><span data-stu-id="59345-111">![Screen grab of a page with multiple fields, artificially highlighting those included in Quick Entry](media/quick-entry-animated.gif "A document page artificially highlighting Quick Entry fields")</span></span>

## <a name="including-or-excluding-fields-from-the-quick-entry-path"></a><span data-ttu-id="59345-112">簡単入力パスに対するフィールドの追加または除外</span><span class="sxs-lookup"><span data-stu-id="59345-112">Including or excluding fields from the Quick Entry path</span></span>
<span data-ttu-id="59345-113">簡単入力は最新かつイマーシブなパーソナル化エクスペリエンスを使用してパーソナライズ可能で、ユーザーは Business Central を自身または自身の部署のデータ入力方法に合わせてカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="59345-113">Quick Entry can be personalized using the modern and immersive personalization experience, empowering users to tailor Business Central to how they or their department typically enters data.</span></span>

<span data-ttu-id="59345-114">開発者は自身のアプリケーションで簡単入力フィールドの初期パスをページごとに定義し、それを拡張機能でカスタマイズできるほか、特定のロールのプロファイルに合わせてカスタマイズすることもできます。</span><span class="sxs-lookup"><span data-stu-id="59345-114">Developers can define an initial path of Quick Entry fields per page in their application, customize that in extensions, and also tailor it to specific role profiles.</span></span> <span data-ttu-id="59345-115">さらに、簡単入力 AL プロパティは簡単入力の動的パスを別個のフィールドに作成する式をサポートします。</span><span class="sxs-lookup"><span data-stu-id="59345-115">Furthermore, the Quick Entry AL property supports expressions to create dynamic Quick Entry paths to different fields.</span></span>

## <a name="a-truly-productive-experience"></a><span data-ttu-id="59345-116">生産性の高いエクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="59345-116">A truly productive experience</span></span>
<span data-ttu-id="59345-117">簡単入力は集中的に利用するユーザーのニーズに合わせて慎重に設計されており、Dynamics NAV の以前の簡単入力機能から次のように改善されています。</span><span class="sxs-lookup"><span data-stu-id="59345-117">Carefully designed for the needs of intensive users, Quick Entry includes improvements over the earlier Quick Entry feature in Dynamics NAV, such as:</span></span>

- <span data-ttu-id="59345-118">**Enter** キー、**Shift+Enter** キー、**Shift+Ctrl+Enter** などの強力なキーの組み合わせを使用することで、編集可能な部分 (リスト部分など) の内外への移動を含め、そのページのすべての簡単入力フィールドに移動できる。</span><span class="sxs-lookup"><span data-stu-id="59345-118">Moving to any Quick Entry field across the page, including moving in and out of editable parts such as list parts, by using a powerful combination of keys: **Enter**, **Shift+Enter** and **Shift+Ctrl+Enter**.</span></span>
- <span data-ttu-id="59345-119">次の簡単入力フィールドがそのグループ内にある場合に、折りたたまれたクイック タブ (フィールド グループ) を展開する。</span><span class="sxs-lookup"><span data-stu-id="59345-119">Expanding a collapsed FastTab (field group) if the next Quick Entry field is in that group.</span></span>
- <span data-ttu-id="59345-120">そのページの最後の簡単入力フィールドに到達すると一回りして最初のフィールドに戻る。</span><span class="sxs-lookup"><span data-stu-id="59345-120">Cycling from the last Quick Entry field to the first Quick Entry field on the page.</span></span>
 
<!--
## Try it now
Experience the difference between using Tab and Enter keys on a new sales order by signing in to your online environment at https://businesscentral.dynamics.com/?page=42&mode=create
## Resources
Using Quick Entry 
Keyboard Shortcuts
Personalize your workspace
Technical Documentation: QuickEntry property
Technical Documentation: Using the Designer
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="59345-121">フィードバック</span><span class="sxs-lookup"><span data-stu-id="59345-121">Tell us what you think</span></span>
<span data-ttu-id="59345-122">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="59345-122">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="59345-123">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="59345-123">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
