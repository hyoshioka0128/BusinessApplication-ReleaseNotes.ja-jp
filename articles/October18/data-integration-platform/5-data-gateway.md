---
title: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
description: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: a1561a448e7906d9509fc41293ac499a4722f458
ms.openlocfilehash: 29480860b839d38f18ef16541c9f2c3a45c0dff3
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a><span data-ttu-id="88f8b-103">オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続</span><span class="sxs-lookup"><span data-stu-id="88f8b-103">Enterprise-grade hybrid connectivity using the on-premises data gateway</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="88f8b-104">このリリースには、オンプレミス データ ゲートウェイを向上するための複数の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-104">This release includes multiple updates around improving the on-premises data gateway.</span></span>

## <a name="certified-custom-connectors-in-power-bi-desktop"></a><span data-ttu-id="88f8b-105">Power BI Desktop における認定カスタム コネクタ</span><span class="sxs-lookup"><span data-stu-id="88f8b-105">Certified custom connectors in Power BI Desktop</span></span>

<span data-ttu-id="88f8b-106">今年の始め、Microsoft は Power BI Desktop のカスタム コネクタに関するサポートを発表しました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-106">Earlier this year, we announced support for custom connectors in Power BI Desktop, leveraging the powerful capabilities of the M language allowing partners to write their own connectors and distribute them to every Power BI user.</span></span>

<span data-ttu-id="88f8b-107">ゲートウェイにおけるカスタム コネクタのサポートにより、ユーザーはオンプレミス データ ゲートウェイでデータを更新することで、カスタム コネクタで作成したレポートを Power BI サービスで最新の状態に保てます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-107">Custom connectors support in the gateway allows users to have their reports that they built with custom connectors stay up to date on the Power BI service by refreshing the data through the on-premises data gateway.</span></span>

<span data-ttu-id="88f8b-108">![オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート](media/custom-connectors-support-premises-data-gateway-1.jpg "オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート")</span><span class="sxs-lookup"><span data-stu-id="88f8b-108">![Custom connectors support in the on-premises data gateway](media/custom-connectors-support-premises-data-gateway-1.jpg "Custom connectors support in the on-premises data gateway")</span></span>

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a><span data-ttu-id="88f8b-109">Power BI Premium のゲートウェイ マルチ地域サポート</span><span class="sxs-lookup"><span data-stu-id="88f8b-109">Gateway multi-geo support for Power BI Premium</span></span>
<span data-ttu-id="88f8b-110">優先順位が変化するため、この機能のタイムフレームは決められていません。</span><span class="sxs-lookup"><span data-stu-id="88f8b-110">Due to changing priorities the timeframe for this feature has not been determined.</span></span> <span data-ttu-id="88f8b-111">調査が続けられている間、https://ideas.powerbi.com で提案に投票して優先順位付けにご協力ください。</span><span class="sxs-lookup"><span data-stu-id="88f8b-111">While investigation continues, please vote on the suggestion at https://ideas.powerbi.com to help prioritize.</span></span>

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a><span data-ttu-id="88f8b-112">クラスタリングを介したゲートウェイの高い利用可能性の保証</span><span class="sxs-lookup"><span data-stu-id="88f8b-112">Guarantee high availability of gateways via clustering</span></span>
<span data-ttu-id="88f8b-113">2017 年 11 月にリリースされたオンプレミス データ ゲートウェイにおける高い利用可能性の機能は、パブリック プレビューから一般提供に移行されます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-113">The high availability capabilities in the on-premises data gateway that we released in November 2017 are transitioning from public preview to general availability.</span></span> <span data-ttu-id="88f8b-114">この取り組みには、より良いエラー報告とユーザー エクスペリエンスの向上をはじめとするむ、複数のエクスペリエンスの向上が含まれます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-114">Part of this effort includes multiple experience improvements, especially around better error reporting and improved user experience.</span></span>

## <a name="improved-kerberos-single-sign-on-support"></a><span data-ttu-id="88f8b-115">Kerberos シングル サインオン サポートの向上</span><span class="sxs-lookup"><span data-stu-id="88f8b-115">Improved Kerberos single sign-on support</span></span>
<span data-ttu-id="88f8b-116">SSO の実装で複数のドメインがサポートされる予定で、SSO の接続テストと問題の診断をより簡単に行えるようにもします。</span><span class="sxs-lookup"><span data-stu-id="88f8b-116">We plan to support multiple domains in our SSO implementation as well as make it easier to test the SSO connection and diagnose issues.</span></span>

<span data-ttu-id="88f8b-117">![Kerberos シングル サインオン サポートの向上](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Kerberos シングル サインオン サポートの向上")</span><span class="sxs-lookup"><span data-stu-id="88f8b-117">![Improved Kerberos single sign-on support](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Improved Kerberos single sign-on support")</span></span>

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a><span data-ttu-id="88f8b-118">サポートされているデータ ソースの SAML ベースのシングル サインオン</span><span class="sxs-lookup"><span data-stu-id="88f8b-118">SAML-based single sign-on for supported data sources</span></span>

<span data-ttu-id="88f8b-119">昨年、SQL Server、SAP HANA、Teradata を含む複数のソースで、ゲートウェイに Kerberos シングル サインオン サポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="88f8b-119">Last year we added Kerberos single sign-on support to the gateway for multiple sources, including SQL Server, SAP HANA, and Teradata.</span></span>

<span data-ttu-id="88f8b-120">そして今後も、サポートされているデータ ソースで SAML ベースのシングル サインオン シナリオへのサポートを追加することにより、シングル サインオンへの投資を続ける予定です。</span><span class="sxs-lookup"><span data-stu-id="88f8b-120">This period we plan to continue investments in single sign-on support by adding support to SAML-based single sign-on scenarios for supported data sources.</span></span>

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a><span data-ttu-id="88f8b-121">Power BI Desktop とのパリティを保つための追加のクラウド データ更新機能</span><span class="sxs-lookup"><span data-stu-id="88f8b-121">Additional cloud data refresh capabilities for parity with Power BI Desktop</span></span>

<span data-ttu-id="88f8b-122">Power BI Desktop では問題なく Power BI データセットが更新されるものの、Power BI サービスでは更新に失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="88f8b-122">There are some cases where a Power BI dataset can refresh without issues in Power BI Desktop but fails to refresh in the Power BI service.</span></span> <span data-ttu-id="88f8b-123">これは多くの場合、このデータセットで使用された個別のデータ ソースのプライバシー設定が原因で生じます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-123">This commonly happens because of the privacy settings of the individual data sources used in this dataset.</span></span>

<span data-ttu-id="88f8b-124">Power BI Desktop では、ユーザーがそれぞれのデータ ソースのプライバシー設定を変更することが可能で、データセットは正常に更新されます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-124">In Power BI Desktop, users can change the privacy settings for each data source, allowing the dataset to refresh successfully.</span></span> <span data-ttu-id="88f8b-125">Power BI サービスでも、ユーザーにそれらのデータセットを正常に更新する機能が与えられる予定です。</span><span class="sxs-lookup"><span data-stu-id="88f8b-125">We intend to give users the ability to successfully refresh those datasets in the Power BI service.</span></span>

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a><span data-ttu-id="88f8b-126">データ ソース設定のエクスペリエンスの向上</span><span class="sxs-lookup"><span data-stu-id="88f8b-126">Improved data source settings experience</span></span>

<span data-ttu-id="88f8b-127">Power BI サービスの「ゲートウェイの管理」ページで、要望の多かった一部の機能を追加することで、データ ソースの作成エクスペリエンスを向上させる予定です。これには、テスト接続の手順をスキップする機能、データ ソースの名前を変更する機能、異なる認証情報で複数のデータ ソースを作成する機能などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-127">We plan to improve the data sources creation experience on the "Manage Gateways" page in the Power BI service by adding some of the highly requested capabilities, such as the ability to skip the test connection step, to rename data sources, and to create multiple data sources with different credentials.</span></span>

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a><span data-ttu-id="88f8b-128">オンプレミス データ ゲートウェイにおけるテナント レベルの管理</span><span class="sxs-lookup"><span data-stu-id="88f8b-128">Tenant level administration of on-premises data gateway</span></span>
<span data-ttu-id="88f8b-129">テナントの管理者が API およびユーザー インターフェイスの両方を通じて、テナント内のすべてのオンプレミス データ ゲートウェイを管理する機能を追加する予定です。</span><span class="sxs-lookup"><span data-stu-id="88f8b-129">We intend to add the ability for tenant administrators to manage all the on-premises data gateways in their tenant through both an API and the user interface.</span></span>

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a><span data-ttu-id="88f8b-130">オンプレミス データ ゲートウェイにおける基本的なトラフィック負荷分散</span><span class="sxs-lookup"><span data-stu-id="88f8b-130">Basic traffic load balancing in the on-premises data gateway</span></span>
<span data-ttu-id="88f8b-131">クラスターのゲートウェイ全体で、特定のゲートウェイ クラスターについてリクエストされたトラフィックを分割する機能を導入する予定です。</span><span class="sxs-lookup"><span data-stu-id="88f8b-131">We plan to introduce the ability to split the requests traffic for a given gateway cluster across all gateways in that cluster.</span></span>
<span data-ttu-id="88f8b-132">ゲートウェイの管理者は、組織のニーズに応じて、この機能のオンとオフを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="88f8b-132">The gateway administrator will be able to turn this capability on and off according to their organization's needs.</span></span>

