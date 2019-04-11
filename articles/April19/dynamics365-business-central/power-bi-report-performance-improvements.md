---
title: Power BI レポートのパフォーマンスの向上
description: Power BI レポートの使用が、ページ読み込みのパフォーマンスが向上するように最適化されました。
author: KennieNP
ms.reviewer: edupont
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 2b75b496cdaf3d731161d587356167350a5f1422
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878734"
---
# <a name="power-bi-report-performance-improvements"></a><span data-ttu-id="d45f2-103">Power BI レポートのパフォーマンスの向上</span><span class="sxs-lookup"><span data-stu-id="d45f2-103">Power BI report performance improvements</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="d45f2-104">Power BI レポートの使用が、ページ読み込みのパフォーマンスが向上するように最適化されました。</span><span class="sxs-lookup"><span data-stu-id="d45f2-104">The use of Power BI reports has been optimized for better performance of page loads.</span></span> <span data-ttu-id="d45f2-105">2019 年 4 月のリリースでは、Power BI レポートは要求を分散するために遅延読み込みされます。</span><span class="sxs-lookup"><span data-stu-id="d45f2-105">In the April 2019 release, Power BI reports are lazy-loaded to disperse requests.</span></span> <span data-ttu-id="d45f2-106">レポートが展開された後、ユーザーが初めて既定のページにアクセスしたときにのみ最初の更新が行われます。</span><span class="sxs-lookup"><span data-stu-id="d45f2-106">Reports are deployed and the initial refresh happens only when users visit their default page for the first time.</span></span> <span data-ttu-id="d45f2-107">2018 年 10 月のリリースで導入されたリスト ページ レポートの自動展開は、大きいデータ セットの場合にレポートで要求されるリソースが多すぎたため、削除されました。</span><span class="sxs-lookup"><span data-stu-id="d45f2-107">Auto-deployment of list page reports that was introduced in the October 2018 release has been removed, because the reports were too demanding on resources for larger data sets.</span></span> <span data-ttu-id="d45f2-108">ロール センターのレポートが最適化され、財務データは Account Schedule KPI にキャッシュされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d45f2-108">Role Center reports have been optimized, and finance data is now cached in the  Account Schedule KPI.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="d45f2-109">フィードバック</span><span class="sxs-lookup"><span data-stu-id="d45f2-109">Tell us what you think</span></span>
<span data-ttu-id="d45f2-110">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="d45f2-110">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="d45f2-111">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="d45f2-111">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
