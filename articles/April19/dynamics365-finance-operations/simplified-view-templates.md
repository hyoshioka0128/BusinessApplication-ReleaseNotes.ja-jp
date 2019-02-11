---
title: 簡素化されたビュー - テンプレート
description: 簡素化されたビュー - テンプレート
author: ReneeW-CPub
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 852eb7460a9d4fa2efd89f733e65b0080e5b20bb
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210359"
---
#  <a name="simplified-view---templates"></a><span data-ttu-id="67cf1-103">簡素化されたビュー - テンプレート</span><span class="sxs-lookup"><span data-stu-id="67cf1-103">Simplified view - templates</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="67cf1-104">2019 年 4 月リリースでは、独自のパーソナライズ ページ ビューを作成し、それらを管理、公開できるようになります。</span><span class="sxs-lookup"><span data-stu-id="67cf1-104">With the April '19 release, you will be able to create, manage, and publish your own personalized views of the pages so that the experience and interaction with the application becomes simple, highly discoverable, and efficient.</span></span>

<span data-ttu-id="67cf1-105">この新機能をベースに、一連の事前構成済みビュー テンプレートが一部のドキュメントとエンティティで利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="67cf1-105">Built on this new facility, a set of preconfigured view templates will be available on selected documents and entities.</span></span> <span data-ttu-id="67cf1-106">テンプレートの構成は、特定のユーザー ロールと、同じユーザー ロールによって実行される特定のタスクの両方に関連する情報によって決まります。</span><span class="sxs-lookup"><span data-stu-id="67cf1-106">The composition of a template will be driven by information relevant to both a specific user role and a given task performed by the same user role.</span></span> <span data-ttu-id="67cf1-107">ビュー テンプレートが利用可能になるドキュメントとエンティティの種類は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="67cf1-107">Types of documents and entities for which view templates will be available are as follows:</span></span>

<span data-ttu-id="67cf1-108">**ドキュメント**</span><span class="sxs-lookup"><span data-stu-id="67cf1-108">**Documents**</span></span>

- <span data-ttu-id="67cf1-109">販売注文</span><span class="sxs-lookup"><span data-stu-id="67cf1-109">Sales orders</span></span>
- <span data-ttu-id="67cf1-110">発注書</span><span class="sxs-lookup"><span data-stu-id="67cf1-110">Purchase orders</span></span>
- <span data-ttu-id="67cf1-111">購買要求</span><span class="sxs-lookup"><span data-stu-id="67cf1-111">Purchase requisitions</span></span>
- <span data-ttu-id="67cf1-112">仕訳帳 (の選択)</span><span class="sxs-lookup"><span data-stu-id="67cf1-112">(Select) journals</span></span>

<span data-ttu-id="67cf1-113">**エンティティ**</span><span class="sxs-lookup"><span data-stu-id="67cf1-113">**Entities**</span></span>

- <span data-ttu-id="67cf1-114">顧客</span><span class="sxs-lookup"><span data-stu-id="67cf1-114">Customers</span></span>
- <span data-ttu-id="67cf1-115">ベンダー</span><span class="sxs-lookup"><span data-stu-id="67cf1-115">Vendors</span></span>
- <span data-ttu-id="67cf1-116">製品</span><span class="sxs-lookup"><span data-stu-id="67cf1-116">Products</span></span>

<span data-ttu-id="67cf1-117">具体的には、顧客サービス担当者と売掛金担当者向けに、販売注文詳細ページの 2 つのビューが個別に用意され、ロールに関連する注文詳細にそれぞれの異なるニーズが反映されます。</span><span class="sxs-lookup"><span data-stu-id="67cf1-117">More specifically, two separate views of a sales order detail page will be available out of the box for a customer service representative and A/R clerk, to reflect their different needs for order details relevant to their roles.</span></span> <span data-ttu-id="67cf1-118">顧客サービス担当者には、注文の処理と履行の段階に応じて異なる注文情報を参照できるよう、2 つの追加ページ ビューが提供されます。</span><span class="sxs-lookup"><span data-stu-id="67cf1-118">Two additional page views will be provided for a customer service representative to accommodate the need to see different order information depending on the stage of the order processing and fulfilment.</span></span>

<span data-ttu-id="67cf1-119">**注文入力**ビューは、注文入力と注文準備に不可欠な注文明細行詳細 (製品名と属性、数量、価格とマージン関連の値、合計金額など) の表示に特化しています。</span><span class="sxs-lookup"><span data-stu-id="67cf1-119">The **Order entry** view will focus on displaying order line details that are essential to order entry and order preparation, such as product name and attributes, quantity, price- and margin-related values, and total amounts:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="67cf1-120">![簡素化されたビュー テンプレートの例 1](media/simplified-view-templates-1.png "簡素化されたビュー テンプレートの例 1")</span><span class="sxs-lookup"><span data-stu-id="67cf1-120">![Simplified view templates example 1](media/simplified-view-templates-1.png "Simplified view templates example 1")</span></span>

<span data-ttu-id="67cf1-121">注文が履行された後、顧客サービス担当者が顧客の問合せに回答する必要があるときには、フルフィルメントの状態に関する詳細に特化した**注文フォローアップ** ビューが役に立ちます。</span><span class="sxs-lookup"><span data-stu-id="67cf1-121">When an order has moved into fulfilment, and the customer service rep needs to answer the customer’s inquiry, the **Order follow-up** view that prioritizes details related to fulfilment status will be of use:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="67cf1-122">![簡素化されたビュー テンプレートの例 2](media/simplified-view-templates-2.png "簡素化されたビュー テンプレートの例 2")</span><span class="sxs-lookup"><span data-stu-id="67cf1-122">![Simplified view templates example 2](media/simplified-view-templates-2.png "Simplified view templates example 2")</span></span>

