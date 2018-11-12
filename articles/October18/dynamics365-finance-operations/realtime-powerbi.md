---
title: "リアルタイム Power BI レポート"
description: "リアルタイム Power BI レポート"
author: milindav
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: milindav
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: cd00f281b554bae6ce553082c3afb0d8ce799aa9
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="real-time-power-bi-reports"></a><span data-ttu-id="54052-103">リアルタイム Power BI レポート</span><span class="sxs-lookup"><span data-stu-id="54052-103">Real-time Power BI reports</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="54052-104">現在 Microsoft Dynamics 365 for Finance and Operations バージョン 7.3 または 8.0 以降を実行しているお客様は、プラットフォームの更新時に製品内のほとんどの分析ワークスペースと埋め込み Power BI レポートがリアルタイムで更新されます。</span><span class="sxs-lookup"><span data-stu-id="54052-104">If you are a customer who is currently running Microsoft Dynamics 365 for Finance and Operations version 7.3 or 8.0 or later, most analytical workspaces and embedded Power BI reports in the product are updated in real-time when you update your platform.</span></span> <span data-ttu-id="54052-105">エンティティ ストアは "ハンズ フリー" で最新の情報に更新されるので、管理者はエンティティ ストアの更新スケジュールを管理する必要がありません。</span><span class="sxs-lookup"><span data-stu-id="54052-105">The entity store is refreshed “hands free,” so your administrator does not need to manage the entity store refresh schedule.</span></span> <span data-ttu-id="54052-106">Microsoft がお客様の更新を管理します。</span><span class="sxs-lookup"><span data-stu-id="54052-106">Microsoft will manage the refresh for you.</span></span> 
 
<span data-ttu-id="54052-107">システムは、リアルタイムでモデル (またはモデルの一部) の更新作業を行います。</span><span class="sxs-lookup"><span data-stu-id="54052-107">The system makes an effort to refresh models (or parts of models) in real time.</span></span> <span data-ttu-id="54052-108">管理者は、モデルからの警告を含む、(リアルタイムではなく) 夜間に更新されるエンティティ ストア データの更新状態を確認できます。</span><span class="sxs-lookup"><span data-stu-id="54052-108">Administrators can see the refresh status of entity store data including warnings from models that are refreshed on a nightly basis (as opposed to real time).</span></span> <span data-ttu-id="54052-109">既定で夜間に更新されるモデルは、オンデマンドで更新することもできます。</span><span class="sxs-lookup"><span data-stu-id="54052-109">Models that are refreshed overnight by default can also be refreshed on demand.</span></span>
 
<span data-ttu-id="54052-110">開発者は、ベスト プラクティス警告をオンにして、夜間に更新される集計の測定 (分析モデルなど) のエンティティとテーブルの一覧がコンパイラに表示されるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="54052-110">If you are a developer, you can turn on best practice warnings to make the compiler show a list of entities and tables in aggregate measurements (such as analytical models) that will be refreshed on a nightly basis.</span></span> <span data-ttu-id="54052-111">リアルタイム更新をサポートするようにエンティティとテーブルをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="54052-111">You can customize entities and tables to support real-time updates.</span></span>


