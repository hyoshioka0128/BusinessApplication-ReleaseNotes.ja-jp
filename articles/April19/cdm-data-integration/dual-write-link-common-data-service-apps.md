---
title: 二重書き込み (Common Data Service へのリンク)
description: 二重書き込み (Common Data Service へのリンク)
author: sabinn-msft
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: a654613e68e1e89b42d6c992d4721e45fd8b9f93
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225076"
---
# <a name="dual-write"></a><span data-ttu-id="cb8bb-103">二重書き込み</span><span class="sxs-lookup"><span data-stu-id="cb8bb-103">Dual Write</span></span>

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

<span data-ttu-id="cb8bb-104">顧客は、Microsoft の複数のビジネス アプリケーションを導入し、それらが同じ言語を使用してシームレスに連携できることを期待しているはずです。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-104">Customers should be able to adopt business applications from Microsoft and expect they speak the same language and seamlessly work together.</span></span> <span data-ttu-id="cb8bb-105">二重書き込みにより、顧客は、これらのアプリを別々に書き込む異なるシステムと考えなくて済みます。基になるインフラストラクチャにより、これらのアプリへの同時書き込みがシームレスに行われます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-105">Dual Write allows our customers to not think about these apps as different systems to write to independently; rather, the underlying infrastructure makes it seamless for these apps to write simultaneously.</span></span>  

## <a name="frictionless-experience-that-enables-dynamics-365-for-finance-and-operations-customers-to-natively-get-their-data-in-common-data-service"></a><span data-ttu-id="cb8bb-106">Dynamics 365 for Finance and Operations ユーザーが Common Data Service のデータをネイティブに取得できるスムーズなエクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="cb8bb-106">Frictionless experience that enables Dynamics 365 for Finance and Operations customers to natively get their data in Common Data Service</span></span>

<span data-ttu-id="cb8bb-107">顧客は数回クリックするだけで、Dynamics 365 for Finance and Operations から Common Data Service にシームレスにリンクできます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-107">With a few clicks, customers will be able to seamlessly link to Common Data Service from Dynamics 365 for Finance and Operations.</span></span> <span data-ttu-id="cb8bb-108">わずかな構成で、Dynamics 365 for Finance and Operations から Common Data Service に、そしてその逆に、変更が反映されます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-108">Changes in Dynamics 365 for Finance and Operations will propagate to Common Data Service and vice versa without much configuration.</span></span> <span data-ttu-id="cb8bb-109">最初はエンティティのサブセットがサポートされているだけですが、徐々に増えていきます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-109">We will support a subset of entities at first and will grow this over time.</span></span>

<span data-ttu-id="cb8bb-110">必要に応じて、Dynamics 365 for Finance and Operations の管理者は高度な設定を使用して、エンティティやフィールドのマッピングをカスタマイズしたり、ソース データのフィルタリングや変換を実行したりできます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-110">Optionally, Dynamics 365 for Finance and Operations admins will be able to use an advanced version of the setup in which they can customize entities and field mappings and also do source data filtering and transformation.</span></span>

## <a name="ability-to-write-initial-data-prior-to-turning-on-dual-write"></a><span data-ttu-id="cb8bb-111">二重書き込みを有効にする前に初期データを書き込む機能</span><span class="sxs-lookup"><span data-stu-id="cb8bb-111">Ability to write initial data prior to turning on Dual Write</span></span>

<span data-ttu-id="cb8bb-112">この機能を使用して、二重書き込みを有効にする前に存在していたデータを書き込み、このデータを最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-112">With this feature, we will write data that exists prior to turning on Dual Write, and keep this data updated.</span></span>

## <a name="making-dual-write-resilient-to-planned-or-unplanned-maintenance"></a><span data-ttu-id="cb8bb-113">計画済みまたは計画外のメンテナンスに対する二重書き込みの回復性の確保</span><span class="sxs-lookup"><span data-stu-id="cb8bb-113">Making Dual Write resilient to planned or unplanned maintenance</span></span>

<span data-ttu-id="cb8bb-114">データの書き込みが失敗した場合、管理者は通知を受けてすぐにアクションを実行できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-114">If data writes fail, administrators want to be notified and empowered to take action immediately.</span></span> <span data-ttu-id="cb8bb-115">この機能は、組織のニーズに合ったエクスペリエンスを定義するための追加機能を管理者に提供します。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-115">This feature provides administrators with additional capabilities to define the experiences that suit their organization's needs.</span></span>

<span data-ttu-id="cb8bb-116">管理者は、電子メール通知を送信したり特定のエラーの種類やしきい値に対して管理者の代わりにアクションを実行したりするルールを定義できます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-116">Administrators will be able to define rules that provide email notifications and/or take actions on their behalf for specific error types and thresholds.</span></span> <span data-ttu-id="cb8bb-117">また、予期しないエラーが発生した場合に非同期モードに切り替える機能も提供されます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-117">This also provides the functionality to switch to async mode in case of unexpected failures.</span></span>

## <a name="support-for-multiple-legal-entities-in-dual-write"></a><span data-ttu-id="cb8bb-118">二重書き込みにおける複数の法人のサポート</span><span class="sxs-lookup"><span data-stu-id="cb8bb-118">Support for multiple legal entities in Dual Write</span></span>

<span data-ttu-id="cb8bb-119">Dynamics 365 for Finance and Operations では、法人 (LE) による特定のデータのストライピングが可能です。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-119">Dynamics 365 for Finance and Operations allows certain data to be striped by Legal Entity (LE).</span></span> <span data-ttu-id="cb8bb-120">それぞれの法人に独自のユーザーが存在します。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-120">Each legal entity has its own customers.</span></span> <span data-ttu-id="cb8bb-121">製品は会社ごとにリリースできますが、価格は顧客の法人ごとに定義できます。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-121">Products may be released per company while prices may be defined per legal entity for a customer.</span></span>

<span data-ttu-id="cb8bb-122">Dynamics 365 for Finance and Operations からのデータを統合する際には、適切な製品と価格が、適切なユーザーへの可視性を確保しながら Common Data Service に送信されるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-122">While integrating data from Dynamics 365 for Finance and Operations, the appropriate products and prices must be sent to Common Data Service while ensuring visibility to the right users.</span></span>

<span data-ttu-id="cb8bb-123">同様に、Common Data Service の営業案件は、Dynamics 365 for Finance and Operations の適切な法人内に作成される必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-123">Similarly, opportunities in Common Data Service need to be created in the appropriate legal entity in Dynamics 365 for Finance and Operations.</span></span>  

<span data-ttu-id="cb8bb-124">回避策はありますが、複数の法人に対する標準のサポートを提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-124">While workarounds exist, there is a need to provide out-of-box support for multiple legal entities.</span></span> <span data-ttu-id="cb8bb-125">この機能を使用すると、複数の法人で同じプロジェクトを使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="cb8bb-125">With this feature, you will be able to use the same project across multiple legal entities.</span></span>
