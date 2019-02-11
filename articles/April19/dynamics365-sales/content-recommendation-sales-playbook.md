---
title: コンテンツのレコメンデーションを含むプレイブックの機能強化
description: プレイブックからのコンテンツのレコメンデーションを使用して力を得て、より多くの取引を成立させてください。
keywords: ''
ms.date: 01/21/2019
ms.service:
- business-applications
ms.topic: article
ms.assetid: d9319480-1ec0-9202-ee03-94b7c9584de0
author: snaitik
ms.author: naitikds
ms.reviewer: shujoshi
ms.openlocfilehash: f88d03ab39778e042f0b5fd216e7ae5c725dd156
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210272"
---
#  <a name="playbook-enhancements-including-content-recommendations"></a><span data-ttu-id="73c35-103">コンテンツのレコメンデーションを含むプレイブックの機能強化</span><span class="sxs-lookup"><span data-stu-id="73c35-103">Playbook enhancements, including content recommendations</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]



<span data-ttu-id="73c35-104">2018 年 10 月リリースで導入された強力なプレイブック機能により、販売組織は知識とベスト プラクティスを取得し、それらをスクリプト化された活動のリスト (電話、タスク、予定など) に変換できます。</span><span class="sxs-lookup"><span data-stu-id="73c35-104">The October '18 release introduced a powerful playbook capability that enables a sales organization to capture knowledge and best practices and convert them to scripted lists of activities (including phone calls, tasks, and appointments).</span></span> <span data-ttu-id="73c35-105">プレイブックは、手動でトリガーするか、エンティティ レコード イベント (新しい営業案件やリードの作成など) に基づいて実行されるように事前構成します。</span><span class="sxs-lookup"><span data-stu-id="73c35-105">Playbook is manually triggered or preconfigured to run based on entity record events (for example, a new opportunity or lead creation).</span></span> 

## <a name="business-value"></a><span data-ttu-id="73c35-106">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="73c35-106">Business value</span></span> 

<span data-ttu-id="73c35-107">2019 年 4 月リリースでは、営業担当者はプレイブックを介してコンテンツのレコメンデーションを受け取ることもできるようになります。</span><span class="sxs-lookup"><span data-stu-id="73c35-107">With the April '19 release, sales professionals will also be able to receive content recommendations via playbooks.</span></span> <span data-ttu-id="73c35-108">これにより、プレイブックの起動時に作成される活動に取り組むときに参照するコンテンツについての詳細が販売者に提供されます。</span><span class="sxs-lookup"><span data-stu-id="73c35-108">This gives sellers additional details on what content to refer to while working on the activities that are created when playbook is launched.</span></span>

## <a name="personas"></a><span data-ttu-id="73c35-109">ペルソナ</span><span class="sxs-lookup"><span data-stu-id="73c35-109">Personas</span></span>

-   <span data-ttu-id="73c35-110">営業マネージャーは、営業資料、製品トレーニング コンテンツ、および取引成立に必要な情報をチームに提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="73c35-110">Sales managers want to provide their teams with the sales materials, product training content, and information needed to close any deal.</span></span> <span data-ttu-id="73c35-111">これらの情報はすべて、Dynamics 365 for Customer Engagement 内でコンテキストに応じて利用可能である必要があります。</span><span class="sxs-lookup"><span data-stu-id="73c35-111">All this information needs to be contextually available within Dynamics 365 for Customer Engagement.</span></span>

-   <span data-ttu-id="73c35-112">営業担当者は、最新の情報、ニュース、および更新されたコンテンツにアクセスでき、常に自分たちが取り組んでいる取引をサポートできるようにしたいと考えています。</span><span class="sxs-lookup"><span data-stu-id="73c35-112">Sales representatives want the latest information, news, and updated content to be accessible and always ready to support the deals they are working on.</span></span>

## <a name="features"></a><span data-ttu-id="73c35-113">機能</span><span class="sxs-lookup"><span data-stu-id="73c35-113">Features</span></span>

-   <span data-ttu-id="73c35-114">Dynamics 365 for Sales では、セールスの有効化の基盤を提供され、コンテキストに従ってセールス チームに必要なすべてのコンテンツが提供されます。</span><span class="sxs-lookup"><span data-stu-id="73c35-114">Dynamics 365 for Sales provides the foundation of sales enablement, which gives sales teams all the necessary content contextually.</span></span> <span data-ttu-id="73c35-115">正確なコンテンツは、営業担当者が購買プロセス全体を通じて購入者との関わりを深め、目的の成果を達成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="73c35-115">Having accurate content helps sales reps successfully engage the buyer throughout the buying process and achieve the desired outcome.</span></span>
    
-   <span data-ttu-id="73c35-116">営業マネージャーは、営業資料やドキュメント文書を参照し、プレイブック活動にそれを添付することができます。</span><span class="sxs-lookup"><span data-stu-id="73c35-116">Sales managers can refer and attach sales literature and documents to playbook activities.</span></span>

-   <span data-ttu-id="73c35-117">営業担当者は、必要な改善のために、コンテンツに関するフィードバックをマネージャーに提供できます。</span><span class="sxs-lookup"><span data-stu-id="73c35-117">Sales reps can provide feedback about content to their managers for any needed improvements.</span></span>


> [!NOTE]
> <span data-ttu-id="73c35-118">プレイブックによるコンテンツのレコメンデーションは、営業ハブでのみ利用でき、Sales Professional アプリケーションでは利用できません。</span><span class="sxs-lookup"><span data-stu-id="73c35-118">Content recommendation through playbooks is expected to be available only for Sales Hub, not for Sales Professional applications.</span></span>
