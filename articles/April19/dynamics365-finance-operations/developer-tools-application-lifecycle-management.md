---
title: 開発者ツールとアプリケーション ライフサイクルの管理
description: Finance and Operations と Retail の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの VM の利用可能性を通して簡単かつ確実に行うことができます。
author: robadawy
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: robadawy
ms.openlocfilehash: cfdca7166381ea517ec88f0a1ebb2a15662a4802
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210340"
---
#  <a name="developer-tools-and-application-lifecycle-management"></a><span data-ttu-id="5123b-103">開発者ツールとアプリケーション ライフサイクルの管理</span><span class="sxs-lookup"><span data-stu-id="5123b-103">Developer tools and application lifecycle management</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





<span data-ttu-id="5123b-104">Unified Operations (Finance and Operations、Retail) の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの仮想マシン (VM) の利用可能性を通して簡単かつ確実に行うことができます。</span><span class="sxs-lookup"><span data-stu-id="5123b-104">Setting up a Unified Operations (Finance and Operations, Retail) development environment is simple and reliable through the availability of ready-to-use cloud and on-premises virtual machines (VMs).</span></span> <span data-ttu-id="5123b-105">この機能は優れていますが、顧客やパートナーにとっては、開発チームが拡大したときに、または複数のアプリケーションや同じアプリケーションの複数のバージョンを開発するときに、多くの開発環境を管理する必要があるため、コストがかかることがわかっています。</span><span class="sxs-lookup"><span data-stu-id="5123b-105">This great feature has, however, proven costly to customers and partners because they need to manage many development environments as their development team grows or when they are developing multiple applications or multiple versions of the same application.</span></span> <span data-ttu-id="5123b-106">さらに、当社の自動ビルド フレームワークも (Azure DevOps に加えて) 同様の VM に依存しており、Lifecycle Services (LCS) やサンドボックス環境へのビルドの自動展開は提供されていません。</span><span class="sxs-lookup"><span data-stu-id="5123b-106">In addition, our automated build framework also relies on similar VMs (in addition to Azure DevOps) and does not provide automatic deployment of builds to Lifecycle Services (LCS) and sandbox environments.</span></span>

<span data-ttu-id="5123b-107">Unified Operations 開発ツール、アプリケーション メタデータ、およびプラットフォームは、同じ環境で複数のアプリケーションを開発できるように、標準モジュールにコンポーネント化されています。</span><span class="sxs-lookup"><span data-stu-id="5123b-107">The Unified Operations development tools, application metadata, and platform will be componentized into standard modules to enable the development of more than one application on the same environment.</span></span> <span data-ttu-id="5123b-108">これにより、ステージは事前構成された VM において開発ツールの依存関係を削除するように設定され、ローカル コンピュータでの開発エクスペリエンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="5123b-108">This will set the stage to remove the dev tools' dependency on preconfigured VMs and will improve the development experience on local computers.</span></span>

<span data-ttu-id="5123b-109">さらに、ビルド自動化フレームワークは VM を必要とせず、Azure DevOps のビルド機能のみに依存します。</span><span class="sxs-lookup"><span data-stu-id="5123b-109">In addition, the build automation framework will not require a VM and will solely rely on Azure DevOps build capabilities.</span></span> <span data-ttu-id="5123b-110">リリース候補であるビルドを、LCS およびサンドボックス クラウド環境に自動的に展開できます。</span><span class="sxs-lookup"><span data-stu-id="5123b-110">Builds that are release candidates can be automatically deployed to LCS and sandbox cloud environments.</span></span>

<span data-ttu-id="5123b-111">新しいお客様の場合、LCS の事前構成済み開発環境 (VM) はお客様の Azure サブスクリプションでホストされ、Microsoft によって管理されることはありません。</span><span class="sxs-lookup"><span data-stu-id="5123b-111">For new customers, preconfigured development environments (VMs) in LCS will be hosted in the customer’s Azure subscription and will not be managed by Microsoft.</span></span> <span data-ttu-id="5123b-112">これらの環境を実行するコストを削減するため、新しい LCS 機能が導入されます。</span><span class="sxs-lookup"><span data-stu-id="5123b-112">New LCS features will be introduced to reduce the cost of running these environments.</span></span> <span data-ttu-id="5123b-113">Microsoft によって管理される Tier-1 環境 (現在は開発/テスト環境) は、テストおよび構成環境のみとなり (RDP アクセスは不可)、他の種類のクラウド環境と同じアーキテクチャになります。</span><span class="sxs-lookup"><span data-stu-id="5123b-113">Tier-1 environments managed by Microsoft (which are currently dev/test environments) will become test and configuration environments only (no RDP access) and will align in architecture with other types of cloud environments.</span></span>
