---
title: コンテンツのレコメンデーションを含むプレイブックの機能強化
description: プレイブックからのコンテンツのレコメンデーションを使用して力を得て、より多くの取引を成立させてください。
keywords: ''
ms.date: 02/06/2019
ms.service:
- business-applications
ms.topic: article
ms.assetid: d9319480-1ec0-9202-ee03-94b7c9584de0
author: snaitik
ms.author: naitikds
ms.reviewer: shujoshi
ms.openlocfilehash: 1106bf4d770e601170ac38192397508a4184ddb8
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224867"
---
#  <a name="playbook-enhancements-with-content-recommendations"></a><span data-ttu-id="c1210-103">コンテンツのレコメンデーションを含むプレイブックの機能強化</span><span class="sxs-lookup"><span data-stu-id="c1210-103">Playbook enhancements with content recommendations</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]



<span data-ttu-id="c1210-104">2018 年 10 月リリースで導入された強力なプレイブック機能により、販売組織は知識とベスト プラクティスを取得し、それらをスクリプト化された活動のリスト (電話、タスク、予定など) に変換できます。</span><span class="sxs-lookup"><span data-stu-id="c1210-104">The October '18 release introduced a powerful playbook capability that enables a sales organization to capture knowledge and best practices and convert them to scripted lists of activities (including phone calls, tasks, and appointments).</span></span> <span data-ttu-id="c1210-105">プレイブックは、手動でトリガーするか、エンティティ レコード イベント (新しい営業案件やリードの作成など) に基づいて実行されるように事前構成します。</span><span class="sxs-lookup"><span data-stu-id="c1210-105">Playbook is manually triggered or preconfigured to run based on entity record events (for example, a new opportunity or lead creation).</span></span> 

## <a name="business-value"></a><span data-ttu-id="c1210-106">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c1210-106">Business value</span></span> 

<span data-ttu-id="c1210-107">2019 年 4 月リリースでは、営業担当者はプレイブックを介してコンテンツのレコメンデーションを受け取ることもできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c1210-107">With the April '19 release, sales professionals will also be able to receive content recommendations via playbooks.</span></span> <span data-ttu-id="c1210-108">これにより、プレイブックの起動時に作成される活動に取り組むときに参照するコンテンツについての詳細が販売担当者に提供されます。</span><span class="sxs-lookup"><span data-stu-id="c1210-108">This gives sellers additional details on what content to refer to while working on the activities that are created when playbook is launched.</span></span>

## <a name="personas"></a><span data-ttu-id="c1210-109">ペルソナ</span><span class="sxs-lookup"><span data-stu-id="c1210-109">Personas</span></span>

-   <span data-ttu-id="c1210-110">営業マネージャーは、営業資料、製品トレーニング コンテンツ、および取引成立に必要な情報をチームに提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="c1210-110">Sales managers want to provide their teams with the sales materials, product training content, and information needed to close any deal.</span></span> <span data-ttu-id="c1210-111">この情報はすべて、Dynamics 365 内でコンテキストに応じて利用可能である必要があります。</span><span class="sxs-lookup"><span data-stu-id="c1210-111">All this information needs to be contextually available within Dynamics 365.</span></span>

-   <span data-ttu-id="c1210-112">営業担当者は、最新の情報、ニュース、および更新されたコンテンツにアクセスでき、常に自分たちが取り組んでいる取引をサポートできるようにしたいと考えています。</span><span class="sxs-lookup"><span data-stu-id="c1210-112">Sales representatives want the latest information, news, and updated content to be accessible and always ready to support the deals they are working on.</span></span>

## <a name="features"></a><span data-ttu-id="c1210-113">機能</span><span class="sxs-lookup"><span data-stu-id="c1210-113">Features</span></span>

-   <span data-ttu-id="c1210-114">Dynamics 365 for Sales では、セールスの有効化の基盤を提供され、コンテキストに従ってセールス チームに必要なすべてのコンテンツが提供されます。</span><span class="sxs-lookup"><span data-stu-id="c1210-114">Dynamics 365 for Sales provides the foundation of sales enablement, which gives sales teams all the necessary content contextually.</span></span> <span data-ttu-id="c1210-115">正確なコンテンツは、営業担当者が購買プロセス全体を通じて購入者との関わりを深め、目的の成果を達成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c1210-115">Having accurate content helps sales reps successfully engage the buyer throughout the buying process and achieve the desired outcome.</span></span>
    
-   <span data-ttu-id="c1210-116">営業マネージャーは、営業資料やドキュメント文書を参照し、プレイブック活動にそれを添付することができます</span><span class="sxs-lookup"><span data-stu-id="c1210-116">Sales managers can refer and attach sales literature and documents to playbook activities</span></span>

> [!NOTE]
> <span data-ttu-id="c1210-117">プレイブックによるコンテンツのレコメンデーションは、営業ハブでのみ利用でき、Sales Professional アプリケーションでは利用できません。</span><span class="sxs-lookup"><span data-stu-id="c1210-117">Content recommendation through playbooks is expected to be available only for Sales Hub, not for Sales Professional applications.</span></span>
>
> <span data-ttu-id="c1210-118">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="c1210-118">This feature is available in Unified Interface only.</span></span>
