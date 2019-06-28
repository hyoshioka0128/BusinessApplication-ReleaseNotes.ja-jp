---
title: 製品の見つけやすさの改善
description: 製品の見つけやすさの改善
author: ReneeW-CPub
ms.date: 05/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 7b1e31b07c3ec00757aef56f15e7682bad5c21bb
ms.sourcegitcommit: cab3880e061232d8975a39a1fb6952556bd55274
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1595000"
---
#  <a name="product-discoverability-enhancements"></a><span data-ttu-id="09723-103">製品の見つけやすさの改善</span><span class="sxs-lookup"><span data-stu-id="09723-103">Product discoverability enhancements</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


## <a name="business-value"></a><span data-ttu-id="09723-104">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="09723-104">Business value</span></span>

<span data-ttu-id="09723-105">すべての小売業者は顧客との対話において、全小売チャネルにわたって製品を見つけやすくすることを重要なツールであると見なしています。</span><span class="sxs-lookup"><span data-stu-id="09723-105">All retailers consider product discovery as a primary tool for customer interaction across all retail channels.</span></span>

<span data-ttu-id="09723-106">小売業者の顧客は、Web 検索エンジン、洗練された E コマース Web サイト、関連性の高い製品を提案するソーシャル アプリ、入力中の検索候補、ファセット ナビゲーション、ハイライト表示などの機能をすべてほぼ瞬時の応答時間で利用することに慣れています。</span><span class="sxs-lookup"><span data-stu-id="09723-106">Retail customers are used to web search engines, sophisticated e-commerce websites, and social apps that offer great relevance, search suggestions as they type, faceted navigation, highlighting, and more, all with near-instantaneous response times.</span></span> <span data-ttu-id="09723-107">適切な商品をすぐに見つけられない場合は、次の E コマース ストアに躊躇なく移動します。</span><span class="sxs-lookup"><span data-stu-id="09723-107">If they don't find the right product quickly, they don't hesitate to move to the next best e-commerce store, because it is that easy.</span></span>

<span data-ttu-id="09723-108">Dynamics 365 for Retail で製品の見つけやすさを改善することで、小売業者がすべてのチャネルにおいて消費者を維持し、コンバージョン率を継続的に高めるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="09723-108">This investment for enhancing product discoverability in Dynamics 365 for Retail will help retailers continue to grow their share of consumer retention and conversion rates across all channels.</span></span>

## <a name="feature-description"></a><span data-ttu-id="09723-109">機能の説明</span><span class="sxs-lookup"><span data-stu-id="09723-109">Feature description</span></span>

<span data-ttu-id="09723-110">この投資により、既存のエンドユーザーが触れる全クライアントにわたって Azure Search の力を活用し、全チャネルにわたって一貫したエクスペリエンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="09723-110">With this investment, we will be able to leverage the power of Azure Search across all of our existing end-user-facing clients and provide a consistent experience across all channels.</span></span>

<span data-ttu-id="09723-111">**閲覧と検索**</span><span class="sxs-lookup"><span data-stu-id="09723-111">**Browse and search**</span></span>

<span data-ttu-id="09723-112">製品の見つけやすさは、主に情報を取得するための検索とコンテンツのナビゲーションに依存するため、オムニチャネル エクスペリエンスにとって検索の関連性とパフォーマンスを高めることが重要です。</span><span class="sxs-lookup"><span data-stu-id="09723-112">Search relevance and performance is key to our omni-channel experience as product discovery relies primarily on search for information retrieval and content navigation.</span></span> <span data-ttu-id="09723-113">効果的かつ効率的な検索は、コンバージョン率の向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="09723-113">An effective and efficient search helps increase conversion.</span></span>

<span data-ttu-id="09723-114">**リファイナーとファセット ナビゲーション**</span><span class="sxs-lookup"><span data-stu-id="09723-114">**Refiners and faceted navigation**</span></span>

<span data-ttu-id="09723-115">ファセット ナビゲーションは、用語セット内の用語に紐付けられているリファイナーに対してフィルターを適用することで、ユーザーがコンテンツをより簡単に閲覧できるようにします。</span><span class="sxs-lookup"><span data-stu-id="09723-115">Faceted navigation helps users browse for content more easily by filtering on refiners that are tied to terms in a term set.</span></span> <span data-ttu-id="09723-116">ファセット ナビゲーションを使用すると、追加のページを作成することなく、用語セット内の異なる用語に対して別個のリファイナーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="09723-116">By using faceted navigation, you can configure different refiners for different terms in a term set without having to create additional pages.</span></span>

<span data-ttu-id="09723-117">**価格設定 API の機能強化**</span><span class="sxs-lookup"><span data-stu-id="09723-117">**Pricing API enhancement**</span></span>

<span data-ttu-id="09723-118">多くの顧客にとって、価格は購入決定を左右する最も重要な要素の 1 つであり、多くの顧客は購入する前にさまざまなサイトで価格を比較します。</span><span class="sxs-lookup"><span data-stu-id="09723-118">For many customers, price is one of the most important factors governing their buying decisions, and many customers compare prices on various sites before making a purchase.</span></span> <span data-ttu-id="09723-119">そこで、小売業者は競合企業に目を光らせ、頻繁にプロモーションを手がけて競争力のある価格を提供します。</span><span class="sxs-lookup"><span data-stu-id="09723-119">Thus, retailers keep a close eye on their competitors and frequently run promotions to ensure they are providing competitive prices.</span></span> <span data-ttu-id="09723-120">そのため、製品検索、閲覧、品目リスト、製品詳細ページで最も正確な価格を表示することが非常に重要です。</span><span class="sxs-lookup"><span data-stu-id="09723-120">Because of that, it's very important that we show the most accurate price on the product search, browse, item lists, and Product details page.</span></span> <span data-ttu-id="09723-121">この機能強化により、GetActivePrices API は、カート内の他の品目に依存しない単一明細割引などの単純な割引を含む価格を返します。そのため、表示される価格は、顧客が品目に対して実際に支払う金額に近くなります。</span><span class="sxs-lookup"><span data-stu-id="09723-121">With this ehancement, the GetActivePrices API will return prices that include simple discounts, such as single line discounts that are not dependent on other items in the cart, so that the prices shown are close to the actual amount the customer would pay for the item.</span></span> <span data-ttu-id="09723-122">さらに、API は適用された割引の名前と有効性を返して、小売業者が価格についてより詳しい説明を提供し、割引の有効期限がもうすぐ切れる場合に切迫感を生み出せるようにします。</span><span class="sxs-lookup"><span data-stu-id="09723-122">Additionally, the API will return the names and validity of the applied discounts to allow the retailers to provide more description on the price and create urgency if the discount validity is expiring soon.</span></span> 
