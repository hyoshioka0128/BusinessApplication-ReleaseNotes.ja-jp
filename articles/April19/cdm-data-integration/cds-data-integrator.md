---
title: CDS データ インテグレーター
description: CDS データ インテグレーター
author: sabinn-msft
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: 94adbd951ef056c507ac78357440f69436d32a15
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210571"
---
# <a name="cds-data-integrator"></a><span data-ttu-id="86477-103">CDS データ インテグレーター</span><span class="sxs-lookup"><span data-stu-id="86477-103">CDS Data Integrator</span></span>
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]



<span data-ttu-id="86477-104">CDS データ インテグレーター (管理者用) は、データを Common Data Service (CDS) for Apps に統合するために使用されるポイント ツー ポイント統合サービスです。</span><span class="sxs-lookup"><span data-stu-id="86477-104">The CDS Data Integrator (for Admins) is a point-to-point integration service used to integrate data into Common Data Service (CDS) for Apps.</span></span> <span data-ttu-id="86477-105">複数のソースから Common Data Service for Apps へのデータの統合がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="86477-105">It supports integrating data from multiple sources into Common Data Service for Apps.</span></span> <span data-ttu-id="86477-106">Dynamics 365 for Finance and Operations と Dynamics 365 for Sales の間の直接同期を提供する見込顧客を現金化のようなプロセス ベースの統合シナリオをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="86477-106">It supports process-based integration scenarios like Prospect to Cash that provide direct synchronization between Dynamics 365 for Finance and Operations and Dynamics 365 for Sales.</span></span> <span data-ttu-id="86477-107">データ統合で使用できる見込顧客を現金化テンプレートを使用すると、Finance and Operations と Sales の間で、取引先企業、取引先担当者、製品、販売見積、販売注文、および売上請求書のデータをフローできます。</span><span class="sxs-lookup"><span data-stu-id="86477-107">The Prospect to Cash templates that are available with the data integration enable the flow of data for accounts, contacts, products, sales quotations, sales orders, and sales invoices between Finance and Operations and Sales.</span></span> <span data-ttu-id="86477-108">2019 年 4 月リリースでは以下の投資を行うことにより、顧客の使用とフィードバックに基づいてこのサービスの強化を続けます。</span><span class="sxs-lookup"><span data-stu-id="86477-108">We continue to enhance this service based on customer use and feedback by making the following investments for April '19.</span></span>

## <a name="sdk-for-data-integrator"></a><span data-ttu-id="86477-109">データ インテグレーター用の SDK</span><span class="sxs-lookup"><span data-stu-id="86477-109">SDK for Data Integrator</span></span>

<span data-ttu-id="86477-110">開発者がデータ統合プロジェクトをユーザーの操作なしにプログラムで作成、更新、およびスケジュールできるように、CDS データ インテグレーター SDK を提供しています。</span><span class="sxs-lookup"><span data-stu-id="86477-110">We are providing a CDS Data Integrator SDK to help developers create, update, and schedule data integration projects programmatically, without user interaction.</span></span>

## <a name="enhancements-in-project-management-error-handling-and-troubleshooting"></a><span data-ttu-id="86477-111">プロジェクト管理、エラー処理、トラブルシューティングの機能強化</span><span class="sxs-lookup"><span data-stu-id="86477-111">Enhancements in Project management, Error handling and troubleshooting</span></span>

<span data-ttu-id="86477-112">これらの機能により、顧客は統合元と統合先のエラー ログへのポインターを使用して、統合の問題をより的確に把握できます。</span><span class="sxs-lookup"><span data-stu-id="86477-112">With these features, customers have better visibility into integration issues with pointers to source and destination error logs.</span></span> <span data-ttu-id="86477-113">また、フィールド マッピングのカスタマイズ中に必須フィールドが確実にマップされるよう、早期警告も提供します。</span><span class="sxs-lookup"><span data-stu-id="86477-113">We also provide early warnings to ensure that mandatory fields are mapped while customizing field mappings.</span></span> <span data-ttu-id="86477-114">また、プロジェクト間のアクティブなエラーのリストを表示し、失敗したレコードを再試行できるようにします。</span><span class="sxs-lookup"><span data-stu-id="86477-114">We also show active lists of errors across projects and provide the ability to retry failed records.</span></span>

<span data-ttu-id="86477-115">さらに、データ統合プロジェクトでは、1 つのプロジェクト内で複数の法人または企業をサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="86477-115">Additionally, data integration projects now have support for multiple legal entities or companies within a single project.</span></span> <span data-ttu-id="86477-116">これは、多数の法人を抱えるエンタープライズの顧客にとって特に有益です。</span><span class="sxs-lookup"><span data-stu-id="86477-116">This is especially beneficial for enterprise customers with large number of legal entities.</span></span>
<span data-ttu-id="86477-117">以前は、テンプレートを更新するときに、古いテンプレートを使用しているプロジェクトを手動で更新する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="86477-117">In the past, when you updated a template, you had to manually update the projects that used the old template.</span></span> <span data-ttu-id="86477-118">この機能を使用すると、ソース テンプレートを更新した場合に、更新をプロジェクトにプッシュできます。</span><span class="sxs-lookup"><span data-stu-id="86477-118">With this feature, you can push updates to projects if the source template is updated.</span></span>

## <a name="guidance-for-performance-tuning-and-integration-write-patterns"></a><span data-ttu-id="86477-119">パフォーマンス チューニングと統合書き込みパターンに関するガイダンス</span><span class="sxs-lookup"><span data-stu-id="86477-119">Guidance for performance tuning and integration write patterns</span></span>

<span data-ttu-id="86477-120">当社の経験と顧客とのやり取りに基づいて、大容量統合のためにパフォーマンスの最適化方法に関するガイダンスのドキュメントを提供しています。</span><span class="sxs-lookup"><span data-stu-id="86477-120">Based on our experience and interaction with customers, we are providing documented guidance on how to optimize performance for high-volume integration.</span></span> <span data-ttu-id="86477-121">さらに、多対一および一対多のパターンでのエンティティ データの移動に関する一般的な要求をカバーした、統合のための書き込みパターンに関するガイダンスを公開しています。</span><span class="sxs-lookup"><span data-stu-id="86477-121">Additionally, we are publishing guidance around write patterns for integrations that covers common requests around moving entity data for many-to-one and one-to-many patterns.</span></span>

## <a name="compliance-for-government-cloud"></a><span data-ttu-id="86477-122">政府機関クラウドへのコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="86477-122">Compliance for government cloud</span></span>

<span data-ttu-id="86477-123">また、政府機関の顧客がサービスの恩恵を受けて利用できるように、データ インテグレーターを GCC に準拠させるようにしています。</span><span class="sxs-lookup"><span data-stu-id="86477-123">We are also making the Data Integrator compliant to GCC so that our government customers can adopt and use the benefits of our service.</span></span>
