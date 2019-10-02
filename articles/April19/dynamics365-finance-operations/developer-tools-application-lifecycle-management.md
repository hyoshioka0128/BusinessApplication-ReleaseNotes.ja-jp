---
title: 開発者ツールとアプリケーション ライフサイクルの管理
description: Finance and Operations と Retail の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの VM の利用可能性を通して簡単かつ確実に行うことができます。
author: robadawy
ms.date: 06/24/2019
ms.topic: article
ms.service: business-applications
ms.author: robadawy
ms.openlocfilehash: f1ee76e2c55cf8753cfaad3724ea99bf67dfb163
ms.sourcegitcommit: a98cc941eeb7ff33997ba441bfba4a49e4429140
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/06/2019
ms.locfileid: "1992872"
---
#  <a name="developer-tools-and-application-lifecycle-management"></a><span data-ttu-id="4e58b-103">開発者ツールとアプリケーション ライフサイクルの管理</span><span class="sxs-lookup"><span data-stu-id="4e58b-103">Developer tools and application lifecycle management</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





<span data-ttu-id="4e58b-104">Unified Operations (Finance and Operations、Retail) の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの仮想マシン (VM) の利用可能性を通して簡単かつ確実に行うことができます。</span><span class="sxs-lookup"><span data-stu-id="4e58b-104">Setting up a Unified Operations (Finance and Operations, Retail) development environment is simple and reliable through the availability of ready-to-use cloud and on-premises virtual machines (VMs).</span></span> <span data-ttu-id="4e58b-105">この機能は優れていますが、顧客やパートナーにとっては、開発チームが拡大したときに、または複数のアプリケーションや同じアプリケーションの複数のバージョンを開発するときに、多くの開発環境を管理する必要があるため、コストがかかることがわかっています。</span><span class="sxs-lookup"><span data-stu-id="4e58b-105">This great feature has, however, proven costly to customers and partners because they need to manage many development environments as their development team grows or when they are developing multiple applications or multiple versions of the same application.</span></span> <span data-ttu-id="4e58b-106">さらに、当社の自動ビルド フレームワークも (Azure DevOps に加えて) 同様の VM に依存しており、Lifecycle Services (LCS) やサンドボックス環境へのビルドの自動展開は提供されていません。</span><span class="sxs-lookup"><span data-stu-id="4e58b-106">In addition, our automated build framework also relies on similar VMs (in addition to Azure DevOps) and does not provide automatic deployment of builds to Lifecycle Services (LCS) and sandbox environments.</span></span>

<span data-ttu-id="4e58b-107">Unified Operations 開発ツール、アプリケーション メタデータ、およびプラットフォームは、同じ環境で複数のアプリケーションを開発できるように、標準モジュールにコンポーネント化されています。</span><span class="sxs-lookup"><span data-stu-id="4e58b-107">The Unified Operations development tools, application metadata, and platform will be componentized into standard modules to enable the development of more than one application on the same environment.</span></span> <span data-ttu-id="4e58b-108">これにより、ステージは事前構成された VM において開発ツールの依存関係を削除するように設定され、ローカル コンピュータでの開発エクスペリエンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="4e58b-108">This will set the stage to remove the dev tools' dependency on preconfigured VMs and will improve the development experience on local computers.</span></span>

<span data-ttu-id="4e58b-109">さらに、ビルド自動化フレームワークは VM を必要とせず、Azure DevOps のビルド機能のみに依存します。</span><span class="sxs-lookup"><span data-stu-id="4e58b-109">In addition, the build automation framework will not require a VM and will solely rely on Azure DevOps build capabilities.</span></span> <span data-ttu-id="4e58b-110">リリース候補であるビルドを、LCS およびサンドボックス クラウド環境に自動的に展開できます。</span><span class="sxs-lookup"><span data-stu-id="4e58b-110">Builds that are release candidates can be automatically deployed to LCS and sandbox cloud environments.</span></span> <span data-ttu-id="4e58b-111">この機能は、2019 年 11 月にパブリック プレビュー向けにリリースされます。</span><span class="sxs-lookup"><span data-stu-id="4e58b-111">This functionality will be released for Public Preview in November 2019.</span></span>

<span data-ttu-id="4e58b-112">更新: 2019 年 4 月 1 日のリリースに間に合うように、Visual Studio Marketplace には Finance and Operations カスタム ビルド (AOT 展開可能パッケージ) をアップロードおよび展開するための Azure DevOps タスクが含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4e58b-112">Update: In time for the April 1, 2019, release, the Visual Studio Marketplace now includes Azure DevOps Tasks to upload and deploy Finance and Operations custom builds (AOT deployable packages).</span></span> <span data-ttu-id="4e58b-113">詳細および関連するお知らせについては、[Dynamics 365 for Finance and Operations での開発とカスタマイズに関するインサイダーのヒント](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax)のブログを参照してください。</span><span class="sxs-lookup"><span data-stu-id="4e58b-113">Follow the [Insiders tips on development and customization in Dynamics 365 for Finance and Operations](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax) blog for details and related announcements.</span></span>
