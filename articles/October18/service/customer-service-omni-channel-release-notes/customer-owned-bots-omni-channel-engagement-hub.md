---
title: "Omni-channel Engagement Hub 用の顧客所有ボット"
description: "Omni-channel Engagement Hub を使用すると、顧客は、(Microsoft Bot Framework で構築された) 独自のボットを持ち込み、それを Omni-channel Engagement Hub のエコシステムと接続できます。"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 87a3a126-6e1d-4e5a-b061-907bb91ab8dd
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 630b39675f950ea34b8a72b70cff3d2c3acc5416
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

#  <a name="enable-customers-to-bring-their-bots"></a><span data-ttu-id="86d51-103">お客様が自分のボットを持ち込める機能</span><span class="sxs-lookup"><span data-stu-id="86d51-103">Enable customers to bring their bots</span></span>

[!include[customer-service-omni-channel-release-notes banner](../../includes/customer-service-omni-channel-release-notes.md)]




<span data-ttu-id="86d51-104">現在、会社がニーズに対応して、要件をすばやく効率的かつ正確に持たすことへの顧客の要求がますます高まっています。</span><span class="sxs-lookup"><span data-stu-id="86d51-104">Today, consumers are increasingly demanding that companies serve their needs and meet their requirements quickly, efficiently, and accurately.</span></span> <span data-ttu-id="86d51-105">同時に、顧客が自分で製品やサービスの問題の解決方法を調べるセルフサービス チャネルの使用への戦略的シフトが存在します。</span><span class="sxs-lookup"><span data-stu-id="86d51-105">At the same time, there is a strategic shift toward use of self-service channels, with customers looking to solve product or service issues themselves.</span></span> 

<span data-ttu-id="86d51-106">機械学習テクノロジ、自然言語リサーチ、言語分析、およびスケーラブルで即時の状況依存アシスタンスを提供する機能の最近の発達により、チャットボット (または仮想エージェント) のようなセルフサービス ツールは、組織の顧客サービス業務に組み込むことが必要なものになっています。</span><span class="sxs-lookup"><span data-stu-id="86d51-106">Recent evolution in machine learning technologies, natural language research, and linguistic analysis, along with the ability to provide scalable, immediate, and contextual assistance, has made self-service tools like chatbots (or virtual agents) a key necessity to be incorporated within an organization’s customer service operations.</span></span> 

<span data-ttu-id="86d51-107">これらのチャットボットによって提供されるユビキタス性とノンストップの可用性とは別に、これらとのやり取りも、コンシューマーのセンチメント、エンゲージメントのレベル、製品のフィードバックの理解に関して分析されることがあります。</span><span class="sxs-lookup"><span data-stu-id="86d51-107">Apart from the ubiquity and nonstop availability offered by these chatbots, interactions with them could also be analyzed in regard to understanding consumer sentiment, level of engagement, and product feedback.</span></span> <span data-ttu-id="86d51-108">顧客サービス業務内のインテリジェント ボットの統合は、平均処理時間や平均サポート案件数などの顧客サービス KPI に好影響を与えるだけでなく、同時にコストを削減します。</span><span class="sxs-lookup"><span data-stu-id="86d51-108">Integration of intelligent bots within customer service operations positively impacts customer service KPIs like average handling time and average number of cases, while simultaneously reducing cost.</span></span>

<span data-ttu-id="86d51-109">**Omni-channel Engagement Hub へのボットの持ち込み**</span><span class="sxs-lookup"><span data-stu-id="86d51-109">**Bring your bot to Omni-channel Engagement Hub**</span></span>

<span data-ttu-id="86d51-110">Omni-channel Engagement Hub を使用すると、顧客は、(Microsoft Bot Framework で構築された) 独自のボットを持ち込み、それを Omni-channel Engagement Hub のエコシステムと接続できます。</span><span class="sxs-lookup"><span data-stu-id="86d51-110">With Omni-channel Engagement Hub, customers can now bring their own bots (built on Microsoft Bot Framework) and connect them with the Omni-channel Engagement Hub ecosystem.</span></span>

<span data-ttu-id="86d51-111">BYOB (Bring Your Own Bot) 機能の一環として、顧客は次のことができます。</span><span class="sxs-lookup"><span data-stu-id="86d51-111">As part of the Bring Your Own Bot feature, customers can now:</span></span>

- <span data-ttu-id="86d51-112">簡素化されたセットアップ エクスペリエンスを使用して Omni-channel Engagement Hub 内のボットを構成し、ボットに会話をルーティングできるようにします。</span><span class="sxs-lookup"><span data-stu-id="86d51-112">Configure their bots in Omni-channel Engagement Hub through a simplified setup experience to enable routing of conversations to bots.</span></span>
- <span data-ttu-id="86d51-113">エンド ユーザー用の一貫したエクスペリエンスで、シームレスな状況依存のエスカレーションを提供します。</span><span class="sxs-lookup"><span data-stu-id="86d51-113">Provide seamless, contextual escalation with consistent experience for end users.</span></span>
- <span data-ttu-id="86d51-114">豊富なボット ユーザー会話トランスクリプトとチャット コンテキストで、エージェントの生産性を高めます。</span><span class="sxs-lookup"><span data-stu-id="86d51-114">Enable agent productivity with rich bot-user conversation transcript and chat context.</span></span>   

<span data-ttu-id="86d51-115">最先端のインテリジェントな会話ボットは、定型クエリを意識させずに自然なユーザー エクスペリエンスを維持するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="86d51-115">Intelligent conversational bots at the frontline help to deflect the routine queries, while maintaining a natural experience for users.</span></span> <span data-ttu-id="86d51-116">Omni-channel Engagement Hub との統合により、エージェントへのスムーズで状況依存のハンドオフが可能になり、複雑なクエリに注目するのに役立ち、関連する情報で機能を強化して、エンド ユーザーに優れたエクスペリエンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="86d51-116">Integration with Omni-channel Engagement Hub enables a smooth, contextual handoff to the agents, helping them to focus on complex queries, while empowering them with relevant information, leading to a good experience for end users.</span></span>

<span data-ttu-id="86d51-117">**Omni-channel Engagement Hub での顧客所有ボットの概略図**</span><span class="sxs-lookup"><span data-stu-id="86d51-117">**Schematic representation for customer-owned bots with Omni-channel Engagement Hub**</span></span>

<span data-ttu-id="86d51-118">![Omni-channel Engagement Hub での顧客所有ボットの概略図](media/bring-your-bot-to-omnichannel.png "Omni-channel Engagement Hub での顧客所有ボットの概略図")</span><span class="sxs-lookup"><span data-stu-id="86d51-118">![Schematic representation for customer-owned bots with Omni-channel Engagement Hub](media/bring-your-bot-to-omnichannel.png "Schematic representation for customer-owned bots with Omni-channel Engagement Hub")</span></span>

