---
title: Marketing Insights アプリ
description: Marketing Insights は、マーケティング イニシアチブ全体で作成される多様なデータと通信を収集、管理、分析し、マーケティング担当者がキャンペーンの対象にしてより効率的に実行できるように関連するアクションを識別します。
ms.date: 11/01/2018
ms.service: business-applications
ms.topic: article
ms.assetid: ed50382f-1d58-4c0c-b3fe-3b54b215f3a5
author: Annbe
ms.author: Annbe
manager: AnnBe
ms.openlocfilehash: a589016c85c28cac2d54f6053761a036ee3c5e12
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199085"
---
# <a name="custom-analytics"></a><span data-ttu-id="efaa8-103">カスタム分析</span><span class="sxs-lookup"><span data-stu-id="efaa8-103">Custom analytics</span></span>

<span data-ttu-id="efaa8-104">Dynamics 365 for Marketing は、取引先担当者がマーケティング イニシアチブとやり取りする方法についての広範で詳細な情報を収集します。</span><span class="sxs-lookup"><span data-stu-id="efaa8-104">Dynamics 365 for Marketing collects wide-ranging and detailed information about how contacts interact with your marketing initiatives.</span></span> <span data-ttu-id="efaa8-105">カスタム分析を使用して、Marketing アプリ内でこのデータを編成および提示します。</span><span class="sxs-lookup"><span data-stu-id="efaa8-105">Use custom analytics to organize and present this data within the Marketing app.</span></span>

<span data-ttu-id="efaa8-106">カスタム分析は、Marketing および他のビジネス アプリケーションからのデータに基づいて、アクション可能な分析情報を提供するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="efaa8-106">Custom analytics can help deliver actionable insights based on data from Marketing and other business applications.</span></span> <span data-ttu-id="efaa8-107">ビジネス プロセスに合わせて調整されたレポートを表示し、それを使用してさらに効果的かつ効率的にキャンペーンを実行する方法を明らかにします。</span><span class="sxs-lookup"><span data-stu-id="efaa8-107">View reports that are fine-tuned to your business processes and use them to identify ways to run more efficient and effective campaigns.</span></span> <span data-ttu-id="efaa8-108">将来的には、機械学習に基づく分析情報も提供し、ビジネス データ、取得されたデータ、Microsoft 固有のデータ セットから、より多くのことを得られるようにします。</span><span class="sxs-lookup"><span data-stu-id="efaa8-108">In the future, we'll also deliver insights based on machine learning to help you get even more out of your business data, acquired data, and unique Microsoft data sets.</span></span>

<span data-ttu-id="efaa8-109">Dynamics 365 for Marketing を使用して、組織固有のビジネス プロセスをサポートし、適切な意志決定を促進し、結果を提供するカスタム分析を作成します。</span><span class="sxs-lookup"><span data-stu-id="efaa8-109">Use Dynamics 365 for Marketing to build custom analytics that support your organization's specific business processes, drive good decision making, and deliver results.</span></span> <span data-ttu-id="efaa8-110">マーケティング担当者が最も必要とするアプリに埋め込むことができるチャート、グラフ、KPI を設計します。</span><span class="sxs-lookup"><span data-stu-id="efaa8-110">Design charts, graphs, and KPIs that you can embed right into the app, where marketers need them most.</span></span>

## <a name="setup-required"></a><span data-ttu-id="efaa8-111">必要なセットアップ</span><span class="sxs-lookup"><span data-stu-id="efaa8-111">Setup required</span></span>

- <span data-ttu-id="efaa8-112">この機能を使用するには、自分の Azure Blob Storage を持ち込む必要があります。</span><span class="sxs-lookup"><span data-stu-id="efaa8-112">You must bring you own Azure Blob Storage to use this feature.</span></span> <span data-ttu-id="efaa8-113">Marketing アプリは、このリソースに接続して、そこにマーケティング データを保存できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="efaa8-113">The Marketing app must be able to connect to this resource and store marketing data there.</span></span>
- <span data-ttu-id="efaa8-114">Power BI データフロー コネクタを使用して、このデータ ストア上に Power BI レポートを構築できます。</span><span class="sxs-lookup"><span data-stu-id="efaa8-114">You can choose to build Power BI reporting on top of this data store by using the Power BI dataflows connector.</span></span> <span data-ttu-id="efaa8-115">この機能はまだプレビュー段階です。</span><span class="sxs-lookup"><span data-stu-id="efaa8-115">This feature is still in preview.</span></span> <span data-ttu-id="efaa8-116">詳細: [データフローでのセルフサービス データの準備 (パブリック プレビュー)](https://docs.microsoft.com/en-us/business-applications-release-notes/october18/intelligence-platform/power-bi-service/self-service-data-prep-with-dataflows)</span><span class="sxs-lookup"><span data-stu-id="efaa8-116">More information: [Self-service data prep with dataflows (Public Preview)](https://docs.microsoft.com/en-us/business-applications-release-notes/october18/intelligence-platform/power-bi-service/self-service-data-prep-with-dataflows)</span></span>
- <span data-ttu-id="efaa8-117">または、Azure Blob Storage に格納されているマーケティング データに対するカスタム マッピングを利用して、Power BI レポートを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="efaa8-117">Alternatively, you can build Power BI reporting leveraging custom mapping for the marketing data stored on Azure Blob Storage.</span></span>

## <a name="status"></a><span data-ttu-id="efaa8-118">状態</span><span class="sxs-lookup"><span data-stu-id="efaa8-118">Status</span></span>
<span data-ttu-id="efaa8-119">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="efaa8-119">Public preview</span></span>

## <a name="resources"></a><span data-ttu-id="efaa8-120">リソース</span><span class="sxs-lookup"><span data-stu-id="efaa8-120">Resources</span></span>

[<span data-ttu-id="efaa8-121">Power BI でのカスタム分析の作成</span><span class="sxs-lookup"><span data-stu-id="efaa8-121">Create custom analytics with Power BI</span></span>](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/custom-analytics)
