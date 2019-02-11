---
title: ゲートウェイ
description: ゲートウェイ
author: msftman
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: deonhe
ms.openlocfilehash: 9da1016b709e23824e78cf6dbe18904bca049f51
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210725"
---
# <a name="gateway"></a><span data-ttu-id="00bf4-103">ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="00bf4-103">Gateway</span></span>
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]



## <a name="on-premises-data-gateway-supports-out-of-box-certified-data-connectors"></a><span data-ttu-id="00bf4-104">すぐに使用できる認定データ コネクタをサポートしているオンプレミス データ ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="00bf4-104">On-premises data gateway supports out-of-box certified data connectors</span></span>  

<span data-ttu-id="00bf4-105">認定カスタム コネクタはオンプレミス データ ゲートウェイですぐに使用できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-105">Certified custom connectors will be available out of the box on the on-premises data gateway.</span></span> <span data-ttu-id="00bf4-106">これにより、開発者およびゲートウェイ管理者は、構成をほとんど、またはまったく変更することなく、認定カスタム コネクタをデータ ソースとして選択できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-106">This will help developers and gateway admins select certified custom connectors as data sources with minimal or no configuration changes.</span></span> 

<span data-ttu-id="00bf4-107">ユーザーは、Microsoft 認定のカスタム コネクタを発見し、ゲートウェイ管理エクスペリエンスで新しいデータ ソースとして追加できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-107">The user can discover Microsoft-certified custom connectors and add them as new data sources in the manage gateway experience.</span></span> <span data-ttu-id="00bf4-108">これにより、ゲートウェイ クラスター内のすべてのゲートウェイでこれらの認定コネクタを管理する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="00bf4-108">This eliminates the need to manage these certified connectors across all gateways in a gateway cluster.</span></span>   
 
## <a name="ability-to-create-multiple-credentials-for-an-on-premises-data-source"></a><span data-ttu-id="00bf4-109">オンプレミス データ ソース用に複数の資格情報を作成する機能</span><span class="sxs-lookup"><span data-stu-id="00bf4-109">Ability to create multiple credentials for an on-premises data source</span></span>   
 
<span data-ttu-id="00bf4-110">同じオンプレミス ゲートウェイ データ ソースに対して異なるセキュリティ レベルを実装すると、ゲートウェイ管理者は、エンド ユーザーに許可されているアクセス レベルに基づいてエンド ユーザーにアクセスを許可することで、セキュリティを効率的に管理できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-110">Different security levels implemented for the same on-premises gateway data source will help gateway admins manage security efficiently by granting access to end users based on their allowed access level.</span></span> <span data-ttu-id="00bf4-111">現在のゲートウェイ管理では、各ゲートウェイのデータ ソースごとに 1 つの認証情報しかサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="00bf4-111">Gateway management today supports only one credential per data source in each gateway.</span></span> <span data-ttu-id="00bf4-112">この制限により、データ ソースの認証情報に高いアクセス権がある場合、ユーザーはデータ ソースの承認されていないデータに接続できます (逆も成り立ちます)。</span><span class="sxs-lookup"><span data-stu-id="00bf4-112">Due to this restriction, users can connect to unauthorized data from a data source if the data source credential has superior access and vice versa.</span></span> <span data-ttu-id="00bf4-113">この問題を解決するため、ゲートウェイ管理者は新しいゲートウェイを稼働させる必要がありました。</span><span class="sxs-lookup"><span data-stu-id="00bf4-113">To resolve this issue, gateway admins had to spin up a new gateway.</span></span> <span data-ttu-id="00bf4-114">この新機能により、管理者は同じソースに接続する (それぞれ異なる認証情報を持つ) 複数のデータ ソースを作成し、アクセス レベルに基づいてこれらの各データ ソースにユーザーを追加することができます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-114">With this new capability, they can now create multiple data sources connecting to the same source, each with a different credential, and add users to each of these data sources based on their access level.</span></span> 
 
## <a name="gateway-administration-across-a-tenant"></a><span data-ttu-id="00bf4-115">テナント間のゲートウェイ管理</span><span class="sxs-lookup"><span data-stu-id="00bf4-115">Gateway administration across a tenant</span></span>
  
-   <span data-ttu-id="00bf4-116">**テナント管理ポータル**: テナント管理者は、このポータルを介して、組織内にインストールされているすべてのオンプレミス ゲートウェイを確認および管理できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-116">**Tenant admin portal**: The tenant administrator can review and manage all on-premises gateways installed within their organization via this portal.</span></span>

    <span data-ttu-id="00bf4-117">現在は、組織内のすべてのユーザーが、インストールするすべてのゲートウェイに管理者としてテナント管理者を追加しない限り、他のユーザーがインストールして構成したすべてのゲートウェイをテナント管理者が一元管理できる場所はありません。</span><span class="sxs-lookup"><span data-stu-id="00bf4-117">There is currently no single place where tenant administrators can manage all gateways that other users have installed and configured unless all users in the organization add the tenant admin as an administrator to every gateway they install.</span></span> <span data-ttu-id="00bf4-118">この問題を軽減するため、テナント管理者はすべてのゲートウェイ クラスターと、各ゲートウェイ クラスターの下に表示されている個々のゲートウェイ コンピューターおよびゲートウェイ管理情報を、見ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="00bf4-118">To mitigate this issue, tenant admins can now see all gateway clusters and also individual gateway machines listed under each gateway cluster and gateway admin information.</span></span> 
  
-   <span data-ttu-id="00bf4-119">**ユーザーがオンプレミス ゲートウェイをインストールできないように制限するテナント管理**: これにより、テナント管理者は、社内の特定のユーザーが管理性向上のためにオンプレミス ゲートウェイをインストールすることを許可できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-119">**Tenant admin to restrict users from installing on-premises gateway**: This lets tenant administrators allow selective users in the company to install the on-premises gateway for better manageability.</span></span> 
 
## <a name="management-enhancements"></a><span data-ttu-id="00bf4-120">管理機能の強化</span><span class="sxs-lookup"><span data-stu-id="00bf4-120">Management enhancements</span></span> 
  
-   <span data-ttu-id="00bf4-121">**集中ゲートウェイ管理**: ゲートウェイ管理者には、Power BI、PowerApps、Microsoft Flow などの Power プラットフォーム全体で、ゲートウェイ クラスター、個々のゲートウェイ コンピューター、および関連するデータ ソースの構成を管理するための標準的なエクスペリエンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-121">**Centralized gateway management**: Gateway admins will have a standard experience for managing configuration for gateway clusters, individual gateway machines, and associated data sources across the Power platform including Power BI, PowerApps, and Microsoft Flow.</span></span> <span data-ttu-id="00bf4-122">これは、ゲートウェイ管理者が各クラスター内のゲートウェイを表示および管理するのにも役立ちます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-122">This will also help gateway admins view and manage gateways within each cluster.</span></span> 

-   <span data-ttu-id="00bf4-123">**旧バージョンのゲートウェイの廃止**: 古いバージョンのオンプレミス ゲートウェイを使用しているゲートウェイ管理者およびレポート ユーザーには、最新バージョンのゲートウェイへのアップグレードが通知されます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-123">**Deprecation of older versions of a gateway**: Gateway admins and report users using older versions of the on-premises gateway will be notified to upgrade to the latest version of the gateway.</span></span> <span data-ttu-id="00bf4-124">これにより、ゲートウェイ管理者は、最新バージョンへのアップグレードを計画し、サポート性を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-124">This will help gateway admins plan for upgrades to the latest version and improve supportability.</span></span> <span data-ttu-id="00bf4-125">また、レポート ユーザーとゲートウェイ管理者には、オンプレミス ゲートウェイの最新リリースに付属する更新プログラムおよび最新機能によるメリットもあります。</span><span class="sxs-lookup"><span data-stu-id="00bf4-125">Report users and gateway admins will also benefit from the updates and latest features shipped with the most recent releases of the on-premises gateway.</span></span>  
  
## <a name="improved-reliability-supportability-and-diagnostics"></a><span data-ttu-id="00bf4-126">改善された信頼性、サポート性、診断</span><span class="sxs-lookup"><span data-stu-id="00bf4-126">Improved reliability, supportability, and diagnostics</span></span>
 
<span data-ttu-id="00bf4-127">基本機能に関しては次のような改善が行われています。</span><span class="sxs-lookup"><span data-stu-id="00bf4-127">These are some improvements related to the fundamentals:</span></span>

-   <span data-ttu-id="00bf4-128">インストールやデータ更新など、複数の分野でのエラーに対するアクションにつながるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="00bf4-128">Actionable messaging for errors in multiple areas like installation and data refreshes.</span></span> 
-   <span data-ttu-id="00bf4-129">ゲートウェイ メタデータ サービスの迅速なリリースと信頼性の向上。</span><span class="sxs-lookup"><span data-stu-id="00bf4-129">Faster releases and improved reliability of the gateway metadata service.</span></span> 
-   <span data-ttu-id="00bf4-130">使用状況、更新、データ ソース、および接続性に関連する改善されたゲートウェイ ロギング。</span><span class="sxs-lookup"><span data-stu-id="00bf4-130">Improved gateway logging related to usage, refreshes, data sources, and connectivity.</span></span>
-   <span data-ttu-id="00bf4-131">パブリック REST API および PowerShell コマンドレット (データ ソースとクラスターの更新) に関するドキュメントを含む、ゲートウェイ ドキュメントの更新。</span><span class="sxs-lookup"><span data-stu-id="00bf4-131">Updated gateway documentation including documentation for public REST APIs and PowerShell cmdlets (update data sources and cluster).</span></span>

## <a name="sap-bw-single-sign-on-kerberos-in-power-bi-service-via-on-premises-data-gateway-for-sap-bw-application-and-message-server"></a><span data-ttu-id="00bf4-132">SAP BW アプリケーションおよびメッセージ サーバー用の、Power BI サービスでの (オンプレミス データ ゲートウェイ経由の) SAP BW シングル サインオン (Kerberos)</span><span class="sxs-lookup"><span data-stu-id="00bf4-132">SAP BW single sign-on (Kerberos) in Power BI service (via on-premises data gateway), for SAP BW Application and Message Server</span></span>
 
<span data-ttu-id="00bf4-133">この機能を使用すると、ユーザーは、SAP BW アプリケーションおよびメッセージ サーバーのデータに基づいて DirectQuery ベースのレポートを発行するときに、Kerberos で制限されたシングル サインオン委任を利用できます。</span><span class="sxs-lookup"><span data-stu-id="00bf4-133">This feature will enable users to leverage Kerberos-constrained single sign-on delegation when publishing DirectQuery-based reports on top of SAP BW Application and Message Server data.</span></span>

## <a name="sap-hana-single-sign-on-saml-in-power-bi-service-via-on-premises-data-gateway"></a><span data-ttu-id="00bf4-134">Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)</span><span class="sxs-lookup"><span data-stu-id="00bf4-134">SAP HANA single sign-on (SAML) in Power BI service (via on-premises data gateway)</span></span>
 
<span data-ttu-id="00bf4-135">これまで、Power BI から DirectQuery モードで SAP HANA に接続するときに、Kerberos を利用してシングル サインオンを使用できました。</span><span class="sxs-lookup"><span data-stu-id="00bf4-135">You've been able to use single sign-on leveraging Kerberos when connecting to SAP HANA in DirectQuery mode from Power BI.</span></span> <span data-ttu-id="00bf4-136">この機能では、SAML を利用するシングル サインオンを使用して SAP HANA に接続することもできるようになります。</span><span class="sxs-lookup"><span data-stu-id="00bf4-136">With this feature, you will now also be able to connect to SAP HANA using single sign-on leveraging SAML.</span></span>

## <a name="support-for-developer-signed-custom-connectors"></a><span data-ttu-id="00bf4-137">開発者署名のカスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="00bf4-137">Support for developer-signed custom connectors</span></span>
 
<span data-ttu-id="00bf4-138">開発者からは、Microsoft のプロセスに従うのではなく、自分の証明書で署名されたコネクタを提供する方法をサポートしてほしいという要望がありました。</span><span class="sxs-lookup"><span data-stu-id="00bf4-138">We’ve been asked by developers to support a way to deliver connectors that have been signed with their certificate, rather than going through Microsoft’s process.</span></span> <span data-ttu-id="00bf4-139">Microsoft では開発者やユーザーがサード パーティによって署名されたコネクタを使用できるようにする方法を導入します。</span><span class="sxs-lookup"><span data-stu-id="00bf4-139">We will be introducing a method to enable developers and users to use connectors signed by third parties.</span></span> <span data-ttu-id="00bf4-140">この機能は、Power BI Desktop に加えて、オンプレミス データ ゲートウェイでもサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="00bf4-140">This feature will be supported via the on-premises data gateway in addition to Power BI Desktop.</span></span>
