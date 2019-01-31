---
title: オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続
description: オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: tpalmer
audience: Admin
ms.openlocfilehash: 6c35a192a2448abc017e61d28ae2937c040f477c
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200169"
---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a><span data-ttu-id="95701-103">オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続</span><span class="sxs-lookup"><span data-stu-id="95701-103">Enterprise-grade hybrid connectivity using the on-premises data gateway</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="95701-104">このリリースには、オンプレミス データ ゲートウェイを向上するための複数の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="95701-104">This release includes multiple updates around improving the on-premises data gateway.</span></span>

## <a name="on-premises-data-gateway-supports-custom-connectors"></a><span data-ttu-id="95701-105">オンプレミス データ ゲートウェイでのカスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="95701-105">On-premises data gateway supports custom connectors</span></span>

<span data-ttu-id="95701-106">今年の初め、Microsoft は Power BI Desktop のカスタム コネクタに関するサポートを発表しました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。</span><span class="sxs-lookup"><span data-stu-id="95701-106">Earlier this year, we announced support for custom connectors in Power BI Desktop, leveraging the powerful capabilities of the M language allowing partners to write their own connectors and distribute them to every Power BI user.</span></span>

<span data-ttu-id="95701-107">ゲートウェイにおけるカスタム コネクタのサポートにより、ユーザーはオンプレミス データ ゲートウェイでデータを更新することで、カスタム コネクタで作成したレポートを Power BI サービスで最新の状態に保てます。</span><span class="sxs-lookup"><span data-stu-id="95701-107">Custom connectors support in the gateway allows users to have their reports that they built with custom connectors stay up to date on the Power BI service by refreshing the data through the on-premises data gateway.</span></span>

<span data-ttu-id="95701-108">![オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート](media/custom-connectors-support-premises-data-gateway-1.jpg "オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート")</span><span class="sxs-lookup"><span data-stu-id="95701-108">![Custom connectors support in the on-premises data gateway](media/custom-connectors-support-premises-data-gateway-1.jpg "Custom connectors support in the on-premises data gateway")</span></span>

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a><span data-ttu-id="95701-109">クラスタリングを介したゲートウェイの高い利用可能性の保証</span><span class="sxs-lookup"><span data-stu-id="95701-109">Guarantee high availability of gateways via clustering</span></span>
<span data-ttu-id="95701-110">2017 年 11 月にリリースされたオンプレミス データ ゲートウェイにおける高い利用可能性の機能は、パブリック プレビューから一般提供に移行されます。</span><span class="sxs-lookup"><span data-stu-id="95701-110">The high availability capabilities in the on-premises data gateway that we released in November 2017 are transitioning from public preview to general availability.</span></span> <span data-ttu-id="95701-111">この取り組みには、より詳細なエラー報告をはじめとする複数のエクスペリエンスの向上が含まれます。</span><span class="sxs-lookup"><span data-stu-id="95701-111">Part of this effort includes multiple experience improvements, especially around better error reporting.</span></span>

## <a name="improved-kerberos-single-sign-on-support"></a><span data-ttu-id="95701-112">Kerberos シングル サインオン サポートの向上</span><span class="sxs-lookup"><span data-stu-id="95701-112">Improved Kerberos single sign-on support</span></span>
<span data-ttu-id="95701-113">SSO の実装では、複数のドメインがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="95701-113">We will support multiple domains in our SSO implementation.</span></span>

<span data-ttu-id="95701-114">![Kerberos シングル サインオン サポートの向上](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Kerberos シングル サインオン サポートの向上")</span><span class="sxs-lookup"><span data-stu-id="95701-114">![Improved Kerberos single sign-on support](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Improved Kerberos single sign-on support")</span></span>

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a><span data-ttu-id="95701-115">サポートされているデータ ソースの SAML ベースのシングル サインオン</span><span class="sxs-lookup"><span data-stu-id="95701-115">SAML-based single sign-on for supported data sources</span></span>

<span data-ttu-id="95701-116">昨年、SQL Server、SAP HANA、Teradata を含む複数のソースで、ゲートウェイに Kerberos シングル サインオン サポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="95701-116">Last year we added Kerberos single sign-on support to the gateway for multiple sources, including SQL Server, SAP HANA, and Teradata.</span></span>

<span data-ttu-id="95701-117">そして今後も、サポートされているデータ ソースで SAML ベースのシングル サインオン シナリオへのサポートを追加することにより、シングル サインオンへの投資を続ける予定です。</span><span class="sxs-lookup"><span data-stu-id="95701-117">This period we plan to continue investments in single sign-on support by adding support to SAML-based single sign-on scenarios for supported data sources.</span></span>

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a><span data-ttu-id="95701-118">データ ソース設定のエクスペリエンスの向上</span><span class="sxs-lookup"><span data-stu-id="95701-118">Improved data source settings experience</span></span>

<span data-ttu-id="95701-119">Power BI サービスの「ゲートウェイの管理」ページで、要望の多かった一部の機能を追加することで、データ ソースの作成エクスペリエンスを向上させる予定です。これには、データ ソースの名前を変更する機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="95701-119">We plan to improve the data sources creation experience on the "Manage Gateways" page in the Power BI service by adding some of the highly requested capabilities, such as the ability to rename data sources.</span></span> <span data-ttu-id="95701-120">その他の機能は、https://ideas.powerbi.com でリクエストおよび投票することができます。</span><span class="sxs-lookup"><span data-stu-id="95701-120">Additional features can be requested and voted on at https://ideas.powerbi.com.</span></span>

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a><span data-ttu-id="95701-121">オンプレミス データ ゲートウェイにおけるテナント レベルの管理</span><span class="sxs-lookup"><span data-stu-id="95701-121">Tenant level administration of on-premises data gateway</span></span>
<span data-ttu-id="95701-122">テナントの管理者が API およびユーザー インターフェイスの両方を通じて、テナント内のすべてのオンプレミス データ ゲートウェイを管理する機能を追加する予定です。</span><span class="sxs-lookup"><span data-stu-id="95701-122">We intend to add the ability for tenant administrators to manage all the on-premises data gateways in their tenant through both an API and the user interface.</span></span>

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a><span data-ttu-id="95701-123">オンプレミス データ ゲートウェイにおける基本的なトラフィック負荷分散</span><span class="sxs-lookup"><span data-stu-id="95701-123">Basic traffic load balancing in the on-premises data gateway</span></span>
<span data-ttu-id="95701-124">クラスターのゲートウェイ全体で、特定のゲートウェイ クラスターについてリクエストされたトラフィックを分割する機能を導入する予定です。</span><span class="sxs-lookup"><span data-stu-id="95701-124">We plan to introduce the ability to split the requests traffic for a given gateway cluster across all gateways in that cluster.</span></span>
<span data-ttu-id="95701-125">ゲートウェイの管理者は、組織のニーズに応じて、この機能のオンとオフを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="95701-125">The gateway administrator will be able to turn this capability on and off according to their organization's needs.</span></span>
