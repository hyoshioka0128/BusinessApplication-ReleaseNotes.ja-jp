---
title: 拡張性の向上
description: 拡張性の向上
author: Annbe
manager: AnnBe
ms.date: 11/09/2018
ms.assetid: 999c9a76-4cc9-4409-a92b-cc232c2bc5ad
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: daedc0690f83b6cda3d878fa67910a27652dde38
ms.sourcegitcommit: 44ed9eddd89e00c08da16c86bae997d3110a6e26
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "392064"
---
#  <a name="improved-extensibility"></a><span data-ttu-id="7fc9e-103">拡張性の向上</span><span class="sxs-lookup"><span data-stu-id="7fc9e-103">Improved extensibility</span></span> 



<span data-ttu-id="7fc9e-104">さまざまな拡張シナリオをサポートするために、多くの新しい拡張ポイントを追加しました。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-104">We added many new extension points to support different extension scenarios.</span></span> <span data-ttu-id="7fc9e-105">POS および Commerce ランタイム (CRT) に、さらに多くのユーザー インターフェースと API 拡張が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-105">More user interface and API extensions have been added to the POS and Commerce run-time (CRT).</span></span> <span data-ttu-id="7fc9e-106">開発者は、カスタム コントロール、アプリ バー ボタン、カスタム列でユーザー インターフェイスを拡張したり、カスタム ビューを作成したりできます。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-106">Developers can now extend the user interface with custom controls, app bar buttons, and custom columns, or build custom views.</span></span> <span data-ttu-id="7fc9e-107">POS オペレーション フレームワークは、新しいオペレーションでのカスタム構成可能なパラメーターをサポートするように拡張されています。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-107">POS Operation framework is enhanced to support custom configurable parameters on new operations.</span></span> <span data-ttu-id="7fc9e-108">さまざまな拡張シナリオをサポートするため、多くの新しいオーバーライド可能な要求とトリガーが POS に追加されました。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-108">Many new overridable requests and triggers have been added in the POS to support different extension scenarios.</span></span> <span data-ttu-id="7fc9e-109">カートとジャーナル ビューにはカスタム コメントのサポートが追加され、POS UI 拡張を簡素化するために多くのダイアログ コントロールと POS コントロールが追加されました。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-109">We added support for custom comment in cart and journal view, and more dialog controls and POS controls to simplify the POS UI extensions.</span></span> <span data-ttu-id="7fc9e-110">また、POS 画面レイアウト デザイナーは、成果物タブのカスタム列および合計パネルのカスタム コントロールとカスタム フィールドをサポートするように拡張されました。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-110">Also, the POS screen layout designer has been enhanced to support custom columns on the deliverable tab, and custom controls and custom fields in the totals panel.</span></span>

<span data-ttu-id="7fc9e-111">**新しい拡張ポイントの完全なリストについては、以下のドキュメントを参照してください。**</span><span class="sxs-lookup"><span data-stu-id="7fc9e-111">**For the full list of new extension points, please see the below docs:**</span></span>

[<span data-ttu-id="7fc9e-112">POS API </span><span class="sxs-lookup"><span data-stu-id="7fc9e-112">POS APIs</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-apis "Retail POS API ")

[<span data-ttu-id="7fc9e-113">POS ビュー</span><span class="sxs-lookup"><span data-stu-id="7fc9e-113">POS Views</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-view-extension "POS ビュー拡張")

[<span data-ttu-id="7fc9e-114">POS トリガー</span><span class="sxs-lookup"><span data-stu-id="7fc9e-114">POS Triggers</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-trigger-printing "POS トリガー拡張")

[<span data-ttu-id="7fc9e-115">CRT サービス</span><span class="sxs-lookup"><span data-stu-id="7fc9e-115">CRT Services</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/crt-services "CRT サービス")

[<span data-ttu-id="7fc9e-116">POS カスタム列</span><span class="sxs-lookup"><span data-stu-id="7fc9e-116">POS Custom column</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-custom-transaction-column "POS カスタム列")

[<span data-ttu-id="7fc9e-117">POS カスタム フィールド</span><span class="sxs-lookup"><span data-stu-id="7fc9e-117">POS Custom field</span></span>](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/custom-field-pos-totals "POS 合計パネル")


<span data-ttu-id="7fc9e-118">ユーザー インターフェイスと API 拡張機能が小売用バックオフィス、POS (Retail Modern POS と Cloud POS)、および Commerce ランタイム (CRT) に追加され、コア アプリケーションに影響を与えることなく、カスタマイズを含む環境を簡単に保守および更新できます。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-118">More user interface and API extensions have been added to the Retail headquarters, POS (Retail Modern POS and Cloud POS, and Commerce run-time (CRT), allowing environments with customization to easily be serviced and updated without impacting the core application.</span></span>

<span data-ttu-id="7fc9e-119">開発者は、カスタム コントロールを使用してユーザー インターフェイスを拡張し、セクションやアプリ バー ボタンを追加したり非表示にしたりできます。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-119">Developers can now extend the user interface with custom controls and add or hide sections or app bar buttons.</span></span> <span data-ttu-id="7fc9e-120">要求やトリガーを上書きし、コア操作の前または後にカスタム ロジックを実行できます。</span><span class="sxs-lookup"><span data-stu-id="7fc9e-120">Requests and triggers can be overridden to allow custom logic before or after core operations.</span></span>
