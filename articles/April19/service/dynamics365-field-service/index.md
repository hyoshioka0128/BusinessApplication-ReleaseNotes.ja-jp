---
title: Dynamics 365 for Field Service の 2019 年 4 月リリースの概要
description: Field Service は、組織が事後対応型から事前対応型または予測型のフィールド サービスを提供するよう移行することを可能にします。
author: kyley
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kyley
ms.reviewer: shellyha
ms.openlocfilehash: 4d2c03075ba92fb615de9567fd9c1974ead5ce2a
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210565"
---
#  <a name="overview-of-dynamics-365-for-field-service-april-19-release"></a><span data-ttu-id="c7619-103">Dynamics 365 for Field Service 2019 年 4 月リリースの概要</span><span class="sxs-lookup"><span data-stu-id="c7619-103">Overview of Dynamics 365 for Field Service April '19 release</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]


<span data-ttu-id="c7619-104">Dynamics 365 for Field Service は、組織が事後対応型から事前対応型または予測型のフィールド サービスを提供するよう移行することを可能にし、結果ベースのサービスや "サービスとしてのもの" などの新しいビジネス モデルを採用することを支援します。</span><span class="sxs-lookup"><span data-stu-id="c7619-104">Dynamics 365 for Field Service empowers organizations to move from being reactive to providing proactive or predictive field service, and to embrace new business models such as outcome-based service or “anything-as-a-service."</span></span>

<span data-ttu-id="c7619-105">2019 年 4 月リリースには、次の分野への投資が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c7619-105">The April '19 release includes investments in these areas:</span></span> 

<span data-ttu-id="c7619-106">**埋め込み IoT の機能強化**: 2018 年 10 月リリースには、IoT Central と Field Service の間で IoT 情報のフローを可能にする Azure IoT Central との統合が含まれていました。</span><span class="sxs-lookup"><span data-stu-id="c7619-106">**Embedded IoT enhancements**: The October '18 release included integration with Azure IoT Central to enable the flow of IoT information between IoT Central and Field Service.</span></span>
<span data-ttu-id="c7619-107">Azure IoT Central は、完全に管理されたグローバルな IoT のソフトウェアとしてのサービス (SaaS) ソリューションであり、大規模な IoT 資産の接続、監視、管理を簡単にします。</span><span class="sxs-lookup"><span data-stu-id="c7619-107">Azure IoT Central is a fully managed global IoT software as a service (SaaS) solution that makes it easy to connect, monitor, and manage your IoT assets at scale.</span></span> <span data-ttu-id="c7619-108">デバイスからの測定値は IoT Central に送られて、そこでデバイスを監視できます。</span><span class="sxs-lookup"><span data-stu-id="c7619-108">Measurements from devices flow into IoT Central where the devices can be monitored.</span></span> <span data-ttu-id="c7619-109">さらに、サービス アクションを必要とする条件またはイベントを識別するためのルールを作成できます。</span><span class="sxs-lookup"><span data-stu-id="c7619-109">In addition, rules can be created to identify conditions or events that require service action.</span></span> <span data-ttu-id="c7619-110">これらは "IoT アラート" として Field Service に送られます。</span><span class="sxs-lookup"><span data-stu-id="c7619-110">These come into Field Service as “IoT alerts.”</span></span>
<span data-ttu-id="c7619-111">Field Service では、IoT アラートを監視および追跡できます。</span><span class="sxs-lookup"><span data-stu-id="c7619-111">IoT alerts can be monitored and tracked in Field Service.</span></span>

<span data-ttu-id="c7619-112">2019 年 4 月リリースには、Field Service アプリケーションに完全に埋め込むための、IoT Central との次のレベルの統合が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7619-112">The April '19 release will include the next level of integration with IoT Central to be fully embedded within the Field Service application.</span></span> <span data-ttu-id="c7619-113">アラートのフローはサポート案件で管理でき、アラートの詳細に基づいて作業を定義できます。</span><span class="sxs-lookup"><span data-stu-id="c7619-113">The flow of alerts can be managed through cases and work can be defined based on the details of the alert.</span></span>

<span data-ttu-id="c7619-114">コンテキスト内で (たとえば、アラート、サポート案件、または資産内)、IoT Central からの現在および過去の情報の測定がビジュアル化を使用して表示されます。</span><span class="sxs-lookup"><span data-stu-id="c7619-114">Within context (for example, within alerts, cases, or assets), measurement of current and historical information from IoT Central will be shown using visualizations.</span></span> <span data-ttu-id="c7619-115">ビジュアル化では、デバイスのデータを操作してアラートを診断し、次のアクションを決定する機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c7619-115">The visualizations provide the capability to manipulate the device data to diagnose alerts and determine next actions.</span></span> <span data-ttu-id="c7619-116">診断に基づいて、Field Service アプリケーションからコマンドをトリガーし、IoT Central によってデバイス上で実行することができます。</span><span class="sxs-lookup"><span data-stu-id="c7619-116">Based on the diagnosis, commands can be triggered from the Field Service application and executed on the device through IoT Central.</span></span>

<span data-ttu-id="c7619-117">**スケジュール機能**: 過去 2 年間にわたり、リソース スケジュール最適化 (RSO) によるフィールド サービスのスケジュール機能の自動化と最適化に多大な投資を行ってきました。</span><span class="sxs-lookup"><span data-stu-id="c7619-117">**Scheduling capabilities**: Over the past two years we have made significant investments in automated and optimized scheduling capability for field service through resource scheduling optimization (RSO).</span></span> <span data-ttu-id="c7619-118">2018 年 11 月には、組織が選択したリソースのスケジュールを迅速に最適化できる単一リソース最適化がリリースされました。</span><span class="sxs-lookup"><span data-stu-id="c7619-118">In November 2018, we released single resource optimization, which enables organizations to quickly optimize the schedule for a selected resource.</span></span>

<span data-ttu-id="c7619-119">2019 年 4 月リリースには、スケジューリングに対する以下の機能拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7619-119">The April '19 release will include the following enhancements to scheduling:</span></span>

- <span data-ttu-id="c7619-120">変動リソースの場所により、リソースは異なる場所から働くことができ、リソースのそのシフトをスケジュールに反映できます。</span><span class="sxs-lookup"><span data-stu-id="c7619-120">Variable resource location will enable resources to work from different areas and have schedules reflect that shift in resources.</span></span>
- <span data-ttu-id="c7619-121">最適化の分析情報では、サービス マネージャーとディスパッチャーに対し、目的の最適化結果を実現するのに役立つ最適化の要約と統計が表示される洞察に富んだ Power BI 分析ダッシュボードが提供されます。</span><span class="sxs-lookup"><span data-stu-id="c7619-121">Optimization insights will provide service managers and dispatchers an insightful Power BI analytical dashboard to show optimization summarization and statistics to help ensure the desired optimization results.</span></span> 
- <span data-ttu-id="c7619-122">ポータルでのセルフサービス スケジューリングにより、時間と都合を顧客に合わせることができます。</span><span class="sxs-lookup"><span data-stu-id="c7619-122">Self-service scheduling via a portal will enable engaging customers on their time, and at their convenience.</span></span>  

<span data-ttu-id="c7619-123">**技術者の生産性向上**: Field Service モバイル アプリケーションの強化と改善を続けています。</span><span class="sxs-lookup"><span data-stu-id="c7619-123">**Technician productivity enhancements**: We continue to enhance and improve the Field Service mobile application.</span></span> <span data-ttu-id="c7619-124">2018 年 10 月リリースでは、プッシュ通知とリアルタイムのジオ トラッキングがリリースされました。</span><span class="sxs-lookup"><span data-stu-id="c7619-124">In the October '18 release, we released push notifications and real-time geo tracking.</span></span> <span data-ttu-id="c7619-125">2018 年 10 月リリースでは、HoloLens Remote Assist アプリ内での埋め込み Field Service のコンテキストも有効にしました。</span><span class="sxs-lookup"><span data-stu-id="c7619-125">In the October '18 release, we also enabled embedded Field Service context within the HoloLens Remote Assist app.</span></span>

<span data-ttu-id="c7619-126">2019 年 4 月リリースでは、埋め込み IoT データ、検査、および時間入力の機能を Field Service モバイル アプリに追加する予定です。</span><span class="sxs-lookup"><span data-stu-id="c7619-126">In the April '19 release, we will add embedded IoT data, inspections, and time entry capabilities to the Field Service mobile app.</span></span>

<span data-ttu-id="c7619-127">**サービス提供の改善**: 2019 年 4 月リリースには、プロセス、安全性、または規制の要件を満たすために、技術者が項目のチェックリストを迅速かつ簡単に考慮できるようにするための検査機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7619-127">**Service delivery improvements**: The April '19 release will include inspections capabilities to enable technicians to quickly and easily account for a checklist of items to meet process, safety, or regulatory requirements.</span></span> <span data-ttu-id="c7619-128">また、時間追跡機能により、技術者の時間をいっそう正確に考慮できるようになり、コストと収益の計算に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c7619-128">Also, time-tracking capabilities ensure a more accurate accounting for technician time, which helps with calculating cost and revenue.</span></span>
