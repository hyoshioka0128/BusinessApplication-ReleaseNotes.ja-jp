---
title: Retail 拡張プラットフォームと開発者エクスペリエンスの改善
description: Retail 拡張プラットフォームと開発者エクスペリエンスの改善
author: ReneeW-CPub
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 1d183bedf009adc5dd3156e378d0874545fbf598
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224876"
---
#  <a name="retail-extension-platform-and-developer-experience-enhancement"></a><span data-ttu-id="5d160-103">Retail 拡張プラットフォームと開発者エクスペリエンスの改善</span><span class="sxs-lookup"><span data-stu-id="5d160-103">Retail extension platform and developer experience enhancement</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


<span data-ttu-id="5d160-104">注文属性などの新機能の導入や拡張ポイントの増加 (API、トリガー、オーバーライド可能なハンドラー) により、カスタマイズ、パッケージ化、展開エクスペリエンスを簡略化する Retail の拡張フレームワークを大幅に強化しています。</span><span class="sxs-lookup"><span data-stu-id="5d160-104">We are making major enhancements in our Retail extensibility framework to simplify the customization, packaging, and deployment experience by introducing new features like Order attributes and more extension points (APIs, triggers, and overridable handlers).</span></span>

## <a name="business-value"></a><span data-ttu-id="5d160-105">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5d160-105">Business value</span></span>

<span data-ttu-id="5d160-106">新しいフレームワークと拡張ポイントにより、新しいバージョンをカスタマイズするのに必要な作業が軽減され、簡単にアップグレードできます。</span><span class="sxs-lookup"><span data-stu-id="5d160-106">The new framework and extension point will reduce the effort required to customize and upgrade to the new version easily.</span></span>

### <a name="development-enhancements"></a><span data-ttu-id="5d160-107">開発に関わる機能の強化</span><span class="sxs-lookup"><span data-stu-id="5d160-107">Development enhancements</span></span>

<span data-ttu-id="5d160-108">さまざまな拡張シナリオに対応するために、多くの新しい拡張ポイントを追加しました。</span><span class="sxs-lookup"><span data-stu-id="5d160-108">We added many new extension points to support different extension scenarios.</span></span> <span data-ttu-id="5d160-109">開発者は、カスタム コントロール、アプリ バー ボタン、カスタム列でユーザー インターフェイスを拡張したり、カスタム ビューを作成したりできます。</span><span class="sxs-lookup"><span data-stu-id="5d160-109">Developers can now extend the user interface with custom controls, app bar buttons, and custom columns, or build custom views.</span></span> <span data-ttu-id="5d160-110">さまざまな拡張シナリオに対応するために、多くの新しいオーバーライド可能な要求とトリガーが POS に追加されました。</span><span class="sxs-lookup"><span data-stu-id="5d160-110">Many new overridable requests and triggers have been added in the POS to support different extension scenarios.</span></span> <span data-ttu-id="5d160-111">カートとジャーナル ビューにはカスタム コメントのサポートが追加され、POS UI 拡張を簡素化するために多くのダイアログ コントロールと POS コントロールが追加されました。</span><span class="sxs-lookup"><span data-stu-id="5d160-111">We added support for custom comment in cart and journal view, and more dialog and POS controls to simplify the POS UI extensions.</span></span> <span data-ttu-id="5d160-112">また、POS 画面レイアウト デザイナーは、成果物タブのカスタム列および合計パネルのカスタム コントロールとカスタム フィールドをサポートするように拡張されました。</span><span class="sxs-lookup"><span data-stu-id="5d160-112">Also, the POS screen layout designer has been enhanced to support custom columns on the deliverable tab, and custom controls and custom fields in the totals panel.</span></span>

<span data-ttu-id="5d160-113">**新しい拡張ポイントの完全なリストについては、次のトピックを参照してください。**</span><span class="sxs-lookup"><span data-stu-id="5d160-113">**For the full list of new extension points, see the following topics:**</span></span>

[<span data-ttu-id="5d160-114">POS API </span><span class="sxs-lookup"><span data-stu-id="5d160-114">POS APIs</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-apis "Retail POS API ")

[<span data-ttu-id="5d160-115">POS ビュー</span><span class="sxs-lookup"><span data-stu-id="5d160-115">POS Views</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-view-extension "POS ビュー拡張")

[<span data-ttu-id="5d160-116">POS トリガー</span><span class="sxs-lookup"><span data-stu-id="5d160-116">POS Triggers</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-trigger-printing "POS トリガー拡張")

[<span data-ttu-id="5d160-117">CRT サービス</span><span class="sxs-lookup"><span data-stu-id="5d160-117">CRT Services</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/crt-services "CRT サービス")

[<span data-ttu-id="5d160-118">POS カスタム列</span><span class="sxs-lookup"><span data-stu-id="5d160-118">POS Custom column</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-custom-transaction-column "POS カスタム列")

[<span data-ttu-id="5d160-119">POS カスタム フィールド</span><span class="sxs-lookup"><span data-stu-id="5d160-119">POS Custom field</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/custom-field-pos-totals "POS 合計パネル") 

### <a name="order-attributes"></a><span data-ttu-id="5d160-120">注文属性</span><span class="sxs-lookup"><span data-stu-id="5d160-120">Order attributes</span></span>

<span data-ttu-id="5d160-121">現金持ち帰り (C&C) トランザクションと顧客注文の属性値を POS から直接表示し、更新するように注文属性フレームワークの機能を強化しています。</span><span class="sxs-lookup"><span data-stu-id="5d160-121">We are enhancing the order attribute framework to show and update the attribute values for the cash-and-carry (C&C) transaction and customer order directly from the POS.</span></span> <span data-ttu-id="5d160-122">この新機能により、小売業者は小売用バックオフィスの画面レイアウト デザイナーで属性コントロールのレイアウト位置を構成し、POS でそのパネルにアクセスして C&C トランザクションと顧客注文ヘッダーおよび明細行の両方の属性値をコードを使用せずに設定できます。</span><span class="sxs-lookup"><span data-stu-id="5d160-122">With this new feature, retailers can configure the attribute control layout position in the Retail headquarters screen layout designer and access it in the POS to set the attribute values for both C&C transaction and customer order header and lines without any code.</span></span>


#### <a name="display-attribute-in-pos"></a><span data-ttu-id="5d160-123">POS の属性を表示する</span><span class="sxs-lookup"><span data-stu-id="5d160-123">Display attribute in POS</span></span>

<span data-ttu-id="5d160-124">![POS トランザクション ビューの新しい属性コントロール](media/retail-extension-platform-developer-experience-enhancement-4.png "POS トランザクション ビューの新しい属性コントロール")</span><span class="sxs-lookup"><span data-stu-id="5d160-124">![New attribute control in POS transaction view](media/retail-extension-platform-developer-experience-enhancement-4.png "New attribute control in POS transaction view")</span></span>


#### <a name="edit-attribute-in-pos"></a><span data-ttu-id="5d160-125">POS の属性を編集する</span><span class="sxs-lookup"><span data-stu-id="5d160-125">Edit attribute in POS</span></span>

<span data-ttu-id="5d160-126">![POS の属性値を編集するためのダイアログ コントロール](media/retail-extension-platform-developer-experience-enhancement-5.png "POS の属性値を編集するためのダイアログ コントロール")</span><span class="sxs-lookup"><span data-stu-id="5d160-126">![Dialog control to edit the attribute value in POS](media/retail-extension-platform-developer-experience-enhancement-5.png "Dialog control to edit the attribute value in POS")</span></span>


