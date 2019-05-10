---
title: エージェント固有の構成のキャッシュ
description: エージェント固有の構成のキャッシュについて説明します。
keywords: ''
ms.date: 03/12/2019
ms.service:
- business-applications
ms.topic: article
ms.assetid: AF34A5B0-7F0D-4DBD-9B83-258CC1FB3B23
author: DeepapMS
ms.author: deepap
ms.openlocfilehash: 304d402ab127cc2c66748013412fee0e0088fc08
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225385"
---
# <a name="cache-specific-configurations-for-agents"></a><span data-ttu-id="e8133-103">エージェント固有の構成のキャッシュ</span><span class="sxs-lookup"><span data-stu-id="e8133-103">Cache specific configurations for agents</span></span>
[!include[unified-service-desk banner](../../../includes/unified-service-desk.md)]
<span data-ttu-id="e8133-104">クライアント キャッシュ機能で [構成キャッシュのバージョン] オプションを使用すると、すべての構成を取得せずに、変更を加えられた構成を Customer Engagement サーバーからエージェントのデスクトップに取得することができます。</span><span class="sxs-lookup"><span data-stu-id="e8133-104">The Configuration Cache Version option causes the client caching feature to retrieve the configuration that has undergone change from the Customer Engagement server to the agent’s desktop and avoid retrieving all configurations.</span></span>

<span data-ttu-id="e8133-105">組織に複数の部署があり、それぞれの部署にロールに基づいてエージェントが追加された構成が存在する場合があります。</span><span class="sxs-lookup"><span data-stu-id="e8133-105">Your organization might have several departments and each department has a configuration with agents added to them based on their roles.</span></span> <span data-ttu-id="e8133-106">これらの構成のいずれかに変更を加えた場合、[構成キャッシュのバージョン] 機能を使用すると、変更を加えた構成のみをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="e8133-106">Whenever you a make a change to one of those configurations, the Configuration Cache Version feature helps to download only the configuration for which you've made a change.</span></span>

<span data-ttu-id="e8133-107">また、他の構成に割り当てられているエージェントがクライアント アプリケーションにサインインするときは、この機能を使用すると構成がダウンロードされないため、Unified Service Desk の起動時のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="e8133-107">Also, when the agents assigned to other configurations sign in to the client application, the feature doesn't download the configurations and thus improves the startup performance of Unified Service Desk.</span></span> <span data-ttu-id="e8133-108">この機能は、組織が実稼働ユーザーに影響を与えずにパイロット構成を変更したい場合に、Unified Service Desk のアプリケーション ライフサイクル管理を改善するのにも役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e8133-108">This is also helpful in better application lifecycle management for Unified Service Desk in cases where organizations want to make changes in their pilot configurations without impacting the production users.</span></span>
