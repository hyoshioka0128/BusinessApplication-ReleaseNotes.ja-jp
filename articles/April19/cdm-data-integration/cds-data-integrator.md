---
title: CDS データ インテグレーター
description: CDS データ インテグレーター
author: sabinn-msft
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: c9b023592a6da6d8a45575e5cfb2671dc3601472
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225196"
---
# <a name="cds-data-integrator"></a><span data-ttu-id="7f5e3-103">CDS データ インテグレーター</span><span class="sxs-lookup"><span data-stu-id="7f5e3-103">CDS Data Integrator</span></span>

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

<span data-ttu-id="7f5e3-104">CDS データ インテグレーター (管理者用) は、データを Common Data Service に統合するために使用されるポイント ツー ポイント統合サービスです。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-104">The CDS Data Integrator (for Admins) is a point-to-point integration service used to integrate data into Common Data Service.</span></span> <span data-ttu-id="7f5e3-105">複数のソースから Common Data Service へのデータの統合がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-105">It supports integrating data from multiple sources into Common Data Service.</span></span> <span data-ttu-id="7f5e3-106">Dynamics 365 for Finance and Operations と Dynamics 365 for Sales の間の直接同期を提供する見込顧客を現金化のようなプロセス ベースの統合シナリオをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-106">It supports process-based integration scenarios like Prospect to Cash that provide direct synchronization between Dynamics 365 for Finance and Operations and Dynamics 365 for Sales.</span></span> <span data-ttu-id="7f5e3-107">データ統合で使用できる見込顧客を現金化テンプレートを使用すると、Finance and Operations と Sales の間で、取引先企業、取引先担当者、製品、販売見積、販売注文、および売上請求書のデータをフローできます。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-107">The Prospect to Cash templates that are available with the data integration enable the flow of data for accounts, contacts, products, sales quotations, sales orders, and sales invoices between Finance and Operations and Sales.</span></span> <span data-ttu-id="7f5e3-108">2019 年 4 月リリースでは以下の投資を行うことにより、顧客の使用とフィードバックに基づいてこのサービスの強化を続けます。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-108">We continue to enhance this service based on customer use and feedback by making the following investments for April '19.</span></span>

## <a name="enhancements-in-error-handling-and-troubleshooting"></a><span data-ttu-id="7f5e3-109">エラー処理とトラブルシューティングの機能強化</span><span class="sxs-lookup"><span data-stu-id="7f5e3-109">Enhancements in error handling and troubleshooting</span></span>

<span data-ttu-id="7f5e3-110">これらの機能により、プロジェクト全体のアクティブなエラーのリストを表示し、失敗したレコードを再試行できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-110">With these features, we show active lists of errors across projects and provide the ability to retry failed records.</span></span>

## <a name="ability-to-propagate-template-updates-to-projects"></a><span data-ttu-id="7f5e3-111">テンプレートの更新をプロジェクトに反映する機能</span><span class="sxs-lookup"><span data-stu-id="7f5e3-111">Ability to propagate template updates to projects</span></span>

<span data-ttu-id="7f5e3-112">以前は、テンプレートを更新するときに、古いテンプレートを使用しているプロジェクトを手動で更新する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-112">In the past, when you updated a template, you had to manually update the projects that used the old template.</span></span> <span data-ttu-id="7f5e3-113">この機能を使用すると、ソース テンプレートを更新した場合に、更新をプロジェクトにプッシュできます。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-113">With this feature, you can push updates to projects if the source template is updated.</span></span>

## <a name="richer-dashboard-with-meaningful-insights-and-views"></a><span data-ttu-id="7f5e3-114">有意義な分析情報とビューを提供するさらに豊富なダッシュボード</span><span class="sxs-lookup"><span data-stu-id="7f5e3-114">Richer dashboard with meaningful insights and views</span></span>

<span data-ttu-id="7f5e3-115">顧客からのフィードバックに基づいて、すべての実行とそのステータスを 1 つの場所でリアルタイムに表示する管理ダッシュボードが提供されています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-115">Based on customer feedback, we provided an admin dashboard that served as a one-stop, real-time view of all executions and their status.</span></span> <span data-ttu-id="7f5e3-116">このビューでは、実行の詳細を見ることができました。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-116">This view allowed you to view details of executions.</span></span>

<span data-ttu-id="7f5e3-117">今回のリリースでは、このダッシュボードがさらに強化され、実行別の上位 5 つのデータ統合プロジェクト、実行状態別のプロジェクト数など、さらに豊富なビューを利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-117">With this release, we further enhance the dashboard with richer views, such as the top five data integration projects by execution, and the number of projects by execution state.</span></span>

## <a name="guidance-for-performance-tuning-and-integration-write-patterns"></a><span data-ttu-id="7f5e3-118">パフォーマンス チューニングと統合書き込みパターンに関するガイダンス</span><span class="sxs-lookup"><span data-stu-id="7f5e3-118">Guidance for performance tuning and integration write patterns</span></span>

<span data-ttu-id="7f5e3-119">当社の経験と顧客とのやり取りに基づいて、大容量統合のためにパフォーマンスの最適化方法に関するガイダンスのドキュメントを提供しています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-119">Based on our experience and interaction with customers, we are providing documented guidance on how to optimize performance for high-volume integration.</span></span> <span data-ttu-id="7f5e3-120">さらに、多対一および一対多のパターンでのエンティティ データの移動に関する一般的な要求をカバーした、統合のための書き込みパターンに関するガイダンスを公開しています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-120">Additionally, we are publishing guidance around write patterns for integrations that covers common requests around moving entity data for many-to-one and one-to-many patterns.</span></span>

## <a name="compliance-for-government-cloud"></a><span data-ttu-id="7f5e3-121">政府機関クラウドへのコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="7f5e3-121">Compliance for government cloud</span></span>

<span data-ttu-id="7f5e3-122">また、政府機関の顧客がサービスの恩恵を受けて利用できるように、データ インテグレーターを GCC に準拠させるようにしています。</span><span class="sxs-lookup"><span data-stu-id="7f5e3-122">We are also making the Data Integrator compliant to GCC so that our government customers can adopt and use the benefits of our service.</span></span>
