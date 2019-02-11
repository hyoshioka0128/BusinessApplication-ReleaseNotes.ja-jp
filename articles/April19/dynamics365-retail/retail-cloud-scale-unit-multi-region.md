---
title: Retail Cloud Scale Unit - 複数地域
description: Retail Cloud Scale Unit - 複数地域
author: ReneeW-CPub
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 9827e558287bfeaa45f378d2126e2765e8a49f34
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210892"
---
#  <a name="retail-cloud-scale-unit--multi-region"></a><span data-ttu-id="81b2d-103">Retail Cloud Scale Unit - 複数地域</span><span class="sxs-lookup"><span data-stu-id="81b2d-103">Retail cloud scale unit – multi-region</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


<span data-ttu-id="81b2d-104">地理的に離れた場所に分散されているチャネルを運用する小売業者は、自社のプライマリ クラウド リージョンから遠く離れている従業員に待ち時間が少なく、応答性の高いユーザー エクスペリエンスを提供できていないことに気付いています。</span><span class="sxs-lookup"><span data-stu-id="81b2d-104">Retail organizations with channel operations across wide, geographically distributed locations find themselves unable to provide low latency, highly responsive user experiences for their employees in locations farther away from the primary cloud region for their environment.</span></span>

<span data-ttu-id="81b2d-105">このようなケースにおける高いネットワーク遅延に対処するために、一般的に今日の IT 管理者は自社の環境をハイブリッド トポロジに展開し、一部のコンポーネントはオンプレミス (実店舗内) または地域のプライベート データ センターに設置します。</span><span class="sxs-lookup"><span data-stu-id="81b2d-105">To mitigate high network latency in such cases, IT administrators today typically deploy the environment in a hybrid topology, with some components installed on-premises (in a physical retail store) or in a regional private data center.</span></span> <span data-ttu-id="81b2d-106">しかし、これには設備投資や運用にかかる費用や負担が発生します。</span><span class="sxs-lookup"><span data-stu-id="81b2d-106">This, however, imposes additional capex and operational burdens on these organizations.</span></span>

<span data-ttu-id="81b2d-107">小売業者向けのマルチ地域のサポートはこれらの問題を軽減します。管理者は Microsoft のデータ センターのグローバル ネットワークを活用し、各店舗が最寄りのクラウド リージョンのサービスを利用することで、待ち時間が短縮され、ユーザーが受ける応答性が向上します。</span><span class="sxs-lookup"><span data-stu-id="81b2d-107">Multi-geo support for retail alleviates this pain and enables administrators to leverage Microsoft’s global network of cloud data centers to serve each of their stores from cloud regions within much closer proximity, and thereby provide improved latency and user-perceived responsiveness.</span></span>

## <a name="business-value"></a><span data-ttu-id="81b2d-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="81b2d-108">Business value</span></span>

<span data-ttu-id="81b2d-109">この機能により、地理的に分散した場所にまたがって運営している小売業者の販売時点管理 (POS) 処理に関わる待ち時間が短縮されます。</span><span class="sxs-lookup"><span data-stu-id="81b2d-109">This feature allows for reduced latency for point of sale (POS) operations in a retail organization operating across geographically distributed locations.</span></span> <span data-ttu-id="81b2d-110">その小売チャネルの最寄りのクラウド リージョンからの要求を処理することで、販売時点管理の待ち時間とパフォーマンスが大幅に改善され、ピーク時間やピーク シーズン中にレジ待ちの長い列ができ、購入をあきらめる人が出るのを防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="81b2d-110">By serving requests from cloud regions closest to the retail channel, latency and performance at point of sale can be considerably better than otherwise, and prevent long checkout lines and purchase abandonment during peak hours and seasons.</span></span>

## <a name="feature-description"></a><span data-ttu-id="81b2d-111">機能の説明</span><span class="sxs-lookup"><span data-stu-id="81b2d-111">Feature description</span></span>

<span data-ttu-id="81b2d-112">小売業者の IT 管理者は、複数の異なるクラウド リージョンからのチャネルを提供することで、ネットワークの待ち時間や店舗内の販売時点管理処理の応答時間が全体的に短縮されます。</span><span class="sxs-lookup"><span data-stu-id="81b2d-112">Retail IT administrators can serve channels from multiple different cloud regions and provide improved network latency and overall faster response times for their point of sale operations in the store.</span></span> <span data-ttu-id="81b2d-113">これにより、小売組織はクラウド優先モデルで運用できるようになり、店舗内コンポーネント (RSSU や POS オフライン) をローカルに展開して待ち時間の改善があまり見られないことを経験することはなくなります。</span><span class="sxs-lookup"><span data-stu-id="81b2d-113">This allows retail organizations to operate in a cloud-first model and alleviates the need for local deployment of in-store components (such as RSSU and POS offline) to experience low improved latency.</span></span>

<span data-ttu-id="81b2d-114">IT 管理者は 1 つ以上のチャネルを構成して、特定のクラウド リージョンからサービスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="81b2d-114">IT administrators can configure one or more channels to be served from a specific cloud region.</span></span> <span data-ttu-id="81b2d-115">データの所在地は引き続き IT 管理者が管理し、どのリージョンからデータを提供するかを管理できます。</span><span class="sxs-lookup"><span data-stu-id="81b2d-115">IT administrators still retain control on data residency and can control which regions their data can be served from.</span></span>
