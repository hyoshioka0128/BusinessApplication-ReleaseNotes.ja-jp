---
title: AI 支援クエリ ビルダー
description: Market Insights に対する関連検索トピックの作成を AI で支援します。
author: m-hartmann
ms.date: 03/20/2019
ms.topic: article
ms.service: business-applications
ms.author: mhart
ms.reviewer: m-hartmann
ms.openlocfilehash: 920f89b009e611a551a42a7cec815bc44803943c
ms.sourcegitcommit: 4db495226091126eecdfb6795702b2d7a4c22a3d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "881190"
---
#  <a name="ai-assisted-query-builder"></a><span data-ttu-id="504da-103">AI 支援クエリ ビルダー</span><span class="sxs-lookup"><span data-stu-id="504da-103">AI assisted query builder</span></span>
[!include[dynamics365-ai-market-insights banner](../../includes/dynamics365-ai-market-insights.md)]


<span data-ttu-id="504da-104">関連する市場のインサイトを得るためには、検索ルールを正しく設定し、ブランド、製品、およびトピックに関する、ユーザーのニーズとの関連性が高い正確なインサイトを提供することが極めて重要です。</span><span class="sxs-lookup"><span data-stu-id="504da-104">To get relevant market insights, it is extremely important to ensure that search rules are set up correctly to provide insights on brands, products, and topics that are very relevant and precise to the user’s needs.</span></span> <span data-ttu-id="504da-105">現在、必要な精度レベルまでルールを調整するには通常何週間も作業を繰り返す必要があるため、ユーザーが最初の実行で正しく検索ルールを構成することは困難です。</span><span class="sxs-lookup"><span data-stu-id="504da-105">Currently, it can be difficult for users to get the configuration of search rules correct on the first run because it typically takes weeks of iterations before the rules are refined to the level of precision required.</span></span> 

<span data-ttu-id="504da-106">この難しさにはいくつかの理由があります。</span><span class="sxs-lookup"><span data-stu-id="504da-106">A few reasons make this difficult:</span></span>

- <span data-ttu-id="504da-107">消費者がブランドについて検索したり言及したりするときの呼び方は一通りではありません (たとえば、マクドナルドの代わりにマックや、Facebook の代わりに FB など)。</span><span class="sxs-lookup"><span data-stu-id="504da-107">Consumers search for and mention brands in many ways (for example, Chevy for Chevrolet, FB for Facebook).</span></span> 
- <span data-ttu-id="504da-108">ブランド名は競合していて、複数の業界のエンティティを参照することがあります (たとえば、Dove は石鹸のブランドでもチョコレートのブランドでもあります)。</span><span class="sxs-lookup"><span data-stu-id="504da-108">Brand names can conflict and refer to entities in more than one industry (for example, Dove is a soap and a chocolate brand).</span></span> 
- <span data-ttu-id="504da-109">ユーザーはトピックから特定のエンティティを除外したいことがよくあります (たとえば、ユーザーは "Nike Air Jordan 1" のトレンドを追いたくても、"High Zip" モデルは除きたい場合があります)。</span><span class="sxs-lookup"><span data-stu-id="504da-109">Users often want to exclude specific entities from their topics (for example, a user might want to track trends on “Nike Air Jordan 1” but not the “High Zip” model).</span></span> 
- <span data-ttu-id="504da-110">ユーザーは注目する価値のある関連トピックが何か予測できないことがあります (たとえば、Nike Air を検索した消費者は他に何を検索したでしょうか)。</span><span class="sxs-lookup"><span data-stu-id="504da-110">Users can’t always anticipate what related topics are worth monitoring (for example, consumers who searched for Nike Air searched for what else?).</span></span> 

<span data-ttu-id="504da-111">その結果、インサイト生成の関連性とコストは、ノイズのカットと適切な検索の設定に大きく依存します。</span><span class="sxs-lookup"><span data-stu-id="504da-111">As a result, the relevance and cost of generating insights heavily depend on cutting out the noise and getting your search set up right.</span></span>

<span data-ttu-id="504da-112">![支援クエリの入力候補](media/assisted-query-list.png "支援クエリの入力候補")</span><span class="sxs-lookup"><span data-stu-id="504da-112">![Assisted query suggestions](media/assisted-query-list.png "Assisted query suggestions")</span></span>

<span data-ttu-id="504da-113">Microsoft の AI 支援クエリ ビルダーはこの核心的な問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="504da-113">Our AI-powered assisted query builder solves this core problem.</span></span> <span data-ttu-id="504da-114">ユーザーが検索語を入力し始めると、最も関連性の高い候補の語が表示されます。</span><span class="sxs-lookup"><span data-stu-id="504da-114">As users start typing their search term, they will be presented with suggested terms most relevant to them.</span></span> <span data-ttu-id="504da-115">たとえば、ユーザーが「Eag」と入力し始めると、"Eagle" (鳥)、""Philadelphia Eagles" (フットボール チーム)、"Eagle Scout" (ボーイスカウト) などから選択できます。</span><span class="sxs-lookup"><span data-stu-id="504da-115">For example, if a user types “Eag...,” they can choose from “Eagle” (the bird), “Philadelphia Eagles” (the football team), “Eagle Scout” (the Boy Scouts), and more.</span></span> <span data-ttu-id="504da-116">AI 支援クエリ ビルダーは、選択候補として関連性の高いブランド、製品、エンティティのリストをユーザーに提供することにより、検索設定の認知的負荷を軽減し、検索の設定にかかる時間を短縮して、インサイトにより多くの時間を費やすことができるようにします。</span><span class="sxs-lookup"><span data-stu-id="504da-116">By providing users with a highly relevant list of brands, products, and entities to select, the assisted query builder helps to reduce the cognitive load of search setup so that they spend less time setting up their searches and more time acting on the insights.</span></span>
