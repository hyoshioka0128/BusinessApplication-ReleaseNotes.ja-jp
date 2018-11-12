---
title: "Microsoft Dynamics 365 for Finance and Operations - 規制サービス、構成サービス"
description: "このトピックでは、Microsoft Dynamics 365 for Finance and Operations - 規制サービスの一部としてリリースされる構成サービスについて説明します。"
author: JaneA07
manager: sshvedov
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: janeaug
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 1603957267bec07c2323edf292da204bc2f31aea
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="microsoft-dynamics-365-for-finance-and-operations---regulatory-services-configuration-service"></a><span data-ttu-id="c2ac3-103">Microsoft Dynamics 365 for Finance and Operations - 規制サービス、構成サービス</span><span class="sxs-lookup"><span data-stu-id="c2ac3-103">Microsoft Dynamics 365 for Finance and Operations - Regulatory Services, Configuration service</span></span> 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]




<span data-ttu-id="c2ac3-104">Microsoft Dynamics 365 for Finance and Operations - 規制サービス、構成サービスは、規制構成ツール (電子申告とも呼ぶ) が進化したものです。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-104">The Microsoft Dynamics 365 for Finance and Operations - Regulatory Services, Configuration service is the evolution of the regulatory configuration tool (also known as Electronic Reporting).</span></span> <span data-ttu-id="c2ac3-105">構成サービスでは、複数のバージョンの Microsoft Dynamics 365 for Finance and Operations や、以前の Microsoft Dynamics AX バージョン (AX 2012 や AX 2009 (インドのみ) など) を使用しているパートナーやお客様が、共通サービスを使用して規制機能を 1 回だけ構成することができます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-105">The Configuration service allows partners and customers using multiple versions of Microsoft Dynamics 365 for Finance and Operations and earlier Microsoft Dynamics AX versions (such as AX 2012 and AX 2009 for India only) to configure regulatory features only once using a common service.</span></span> <span data-ttu-id="c2ac3-106">構成サービスは、コード記述のないプログラミング アプローチを採用しています。これによりパワー ユーザーは、複数のアプリケーションでコードを記述しなくても、規制報告、電子請求書、支払い形式、および税規則についての法的要件を構成し、要件の頻繁な変更に効果的に対応できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-106">The Configuration service targets a no-code programming approach, allowing power users to configure frequently changed legal requirements for regulatory reports, e-invoices, payment formats and tax rules, rather than writing code in multiple applications.</span></span> 

<span data-ttu-id="c2ac3-107">構成サービスは、最初にリリースされる規制サービスのコンポーネントです。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-107">The Configuration service is the first component of Regulatory Services to be released.</span></span> <span data-ttu-id="c2ac3-108">規制サービスでは、任意のビジネス アプリケーションと統合可能な機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-108">Regulatory Services will provide functionality that can be integrated with any business application.</span></span> <span data-ttu-id="c2ac3-109">このサービスを使用することで、アプリケーション開発者は、世界各国で増え続ける法的要件への準拠にわずらわされることなく、各自の本来の中核業務に専念することができます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-109">This service allows developers building applications to focus on their core functionality rather than worrying about meeting the increasing number of legal requirements around the globe.</span></span> 

<span data-ttu-id="c2ac3-110">構成サービスは、次の機能を提供します:</span><span class="sxs-lookup"><span data-stu-id="c2ac3-110">The Configuration service provides the following capabilities:</span></span>

-   <span data-ttu-id="c2ac3-111">ビジュアル デザイナーにアクセスして、規制報告、電子請求書、支払い形式、税規則、その他の規制機能を構成できます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-111">Access to visual designers to configure regulatory reports, e-invoices, payment formats, tax rules, and other regulatory features.</span></span> 
-   <span data-ttu-id="c2ac3-112">データ テーブル、列挙、クラス、などのターゲット アプリケーションのアーティファクトの説明をインポートする機能、またはメタデータへのアクセスに接続済みアプリケーションを使用する機能を提供するメタデータ。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-112">Metadata that provides the ability to either import a description of the target application’s artifacts, such as data tables, enumeration, and classes, or use connected applications for accessing metadata.</span></span> <span data-ttu-id="c2ac3-113">メタデータは、データ モデル マッピング バージョンのデータ ソースを定義するために設計時に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-113">Metadata is used at design time to define data sources of a data model mapping version.</span></span> 
-   <span data-ttu-id="c2ac3-114">データが保持される地域をユーザーが選択できるようにする地域展開のサポート。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-114">Support for regional deployments to enable users to select what region their data is held in.</span></span> <span data-ttu-id="c2ac3-115">最初の GA (一般提供) リリースでは利用できる国が限られますが、その後のリリースで追加されます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-115">There will be a limited set of countries available with the initial GA release, but these will be added to over later releases.</span></span>    

## <a name="regional-availability"></a><span data-ttu-id="c2ac3-116">利用可能なリージョン</span><span class="sxs-lookup"><span data-stu-id="c2ac3-116">Regional availability</span></span>
<span data-ttu-id="c2ac3-117">構成サービスが一般提供されると、Finance and Operations を利用可能なすべての地域で使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-117">When the Configuration service is generally available, it will be available in all regions in which Finance and Operations is available.</span></span> <span data-ttu-id="c2ac3-118">ただし、データは最初は米国のデータセンターにのみホストされます。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-118">However, data will be initially hosted only in a US datacenter.</span></span>

<span data-ttu-id="c2ac3-119">地域の一覧については、「[Dynamics 365 各国での利用可能性ガイド](https://aka.ms/dynamics_365_international_availability_deck)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c2ac3-119">For a complete list of regions, see the [Dynamics 365 International Availability Guide](https://aka.ms/dynamics_365_international_availability_deck).</span></span>

