---
title: Dynamics 365 Channel Integration Framework
description: Web CTI 統合フレームワーク
keywords: ''
ms.date: 7/22/2018
ms.service:
- business-applications
ms.topic: article
ms.assetid: fbf6b3a6-d7f4-4315-ae47-ce53eb2cdea4
author: Annbe
ms.author: Annbe
manager: AnnBe
ms.openlocfilehash: eec8ffc11aac6e6f36916d7da8cc26c3bd754bb0
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200102"
---
#  <a name="channel-integration-framework"></a><span data-ttu-id="8afda-103">Channel Integration Framework</span><span class="sxs-lookup"><span data-stu-id="8afda-103">Channel Integration Framework</span></span>

[!include[customer-service-omni-channel-release-notes banner](../../includes/customer-service-omni-channel-release-notes.md)]



<span data-ttu-id="8afda-104">Dynamics 365 Channel Integration Framework では、サード パーティのチャネル プロバイダーとのイマーシブな通信エクスペリエンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8afda-104">The Dynamics 365 Channel Integration Framework enables building immersive communication experiences with third-party channel providers.</span></span>

<span data-ttu-id="8afda-105">このフレームワークのメリットは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8afda-105">These are the benefits of this framework:</span></span>

-   <span data-ttu-id="8afda-106">**独自のチャネル プロバイダーを Dynamics 365 に取り込む。**</span><span class="sxs-lookup"><span data-stu-id="8afda-106">**Bring your own channel providers into Dynamics 365.**</span></span> <span data-ttu-id="8afda-107">このフレームワークでは、通信ウィジェットを統一インターフェイス アプリに埋め込むことができ、標準 API セットを使って Dynamics 365 と通信できます。</span><span class="sxs-lookup"><span data-stu-id="8afda-107">The framework allows you to embed communication widgets in the Unified Interface apps, which can communicate with Dynamics 365 using a standard API set.</span></span> <span data-ttu-id="8afda-108">このフレームワークは本質的にチャネルに依存しないので、1 つ以上のチャネル (音声、チャット、メールなど) に対応する通信ウィジェットの統合に使用できます。</span><span class="sxs-lookup"><span data-stu-id="8afda-108">The framework is inherently channel-agnostic, and can be used to integrate communication widgets catering to one or many of the different channels—for example, voice, chat, and email.</span></span>
-   <span data-ttu-id="8afda-109">**クラウド ベースのソリューションで総保有コストを最小限に抑える。**</span><span class="sxs-lookup"><span data-stu-id="8afda-109">**Minimize total cost of ownership with cloud-based solutions.**</span></span> <span data-ttu-id="8afda-110">これは、通信ウィジェットを統合するための、プラットフォームとブラウザーに依存しないゼロ フットプリントの (エージェント デスクトップにアダプターを展開する必要がない) フレームワークです。</span><span class="sxs-lookup"><span data-stu-id="8afda-110">It is a platform-independent, browser-independent, and zero footprint (no adaptors need to be deployed on agent desktops) framework for integrating communication widgets.</span></span> <span data-ttu-id="8afda-111">Dynamics 365 は、フレームワークに基づく通信ウィジェットにプラグ アンド プレイの構成メカニズムを提供し、展開、管理、アップグレードを容易にします。</span><span class="sxs-lookup"><span data-stu-id="8afda-111">Dynamics 365 will provide a plug and play configuration mechanism for communication widgets based on the framework, making it easy to deploy, manage, and upgrade.</span></span> 
-   <span data-ttu-id="8afda-112">**ビジネス ワークフローに合わせてカスタマイズする。**</span><span class="sxs-lookup"><span data-stu-id="8afda-112">**Customize for your business workflows.**</span></span> <span data-ttu-id="8afda-113">このフレームワークでは、受信通信パラメーター (電話番号など) に基づく検索と画面ポップや、クリックによるダイヤルなど、多くの重要な通信シナリオを自動化できます。</span><span class="sxs-lookup"><span data-stu-id="8afda-113">With this framework, many key communication scenarios, such as search and screen pop based on incoming communication parameters (such as phone number) and click to dial, can be automated.</span></span> <span data-ttu-id="8afda-114">また、新しいレコードの作成や、通信ウィジェットからの既存レコードの更新のような、CRM 操作を実行する手段を提供します。</span><span class="sxs-lookup"><span data-stu-id="8afda-114">It also provides ways to perform CRM operations like creating a new record or updating an existing record from the communication widget.</span></span> 




