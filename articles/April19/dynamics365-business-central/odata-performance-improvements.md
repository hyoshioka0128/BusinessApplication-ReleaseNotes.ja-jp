---
title: OData のパフォーマンスの向上
description: OData のパフォーマンスの向上
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 5e27b1884dc9a3f57043e01a239c05b38c5a995d
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224918"
---
# <a name="odata-performance-improvements"></a><span data-ttu-id="3901d-103">OData のパフォーマンスの向上</span><span class="sxs-lookup"><span data-stu-id="3901d-103">OData performance improvements</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="3901d-104">テレメトリにより、Business Central Server の OData スタックが最適に機能していないことがわかりました。</span><span class="sxs-lookup"><span data-stu-id="3901d-104">Looking at telemetry, we realized that our OData stack in Business Central server was not performing optimally.</span></span> <span data-ttu-id="3901d-105">まず第一に、OData の $top クエリ オプションが SQL Server クエリの TOP 句に渡されていなかったため、データベースには $top クエリ オプションのメリットがありませんでした。</span><span class="sxs-lookup"><span data-stu-id="3901d-105">First of all, OData's $top query option was not passed on to the TOP clause in SQL Server queries, which meant that the database did not benefit from the $top query option.</span></span> <span data-ttu-id="3901d-106">第二に、合計の多くの OData クエリでは、Business Central Server の OData スタックで定義されている既定の 1,000 行よりはるかに多くの行が返されることがわかりました。</span><span class="sxs-lookup"><span data-stu-id="3901d-106">Second, we noticed that many OData queries in total returned many more rows than the default 1,000 rows defined in the Business Central server OData stack.</span></span> <span data-ttu-id="3901d-107">そのため、既定の行数を 20,000 に変更しました。</span><span class="sxs-lookup"><span data-stu-id="3901d-107">Therefore, we have changed the default number of rows to 20,000.</span></span>

## <a name="odata-resource-constraints"></a><span data-ttu-id="3901d-108">OData リソースの制約</span><span class="sxs-lookup"><span data-stu-id="3901d-108">OData resource constraints</span></span>

<span data-ttu-id="3901d-109">また、テレメトリから、少数のテナントが Business Central クラスター上で適正な量を超えるリソースを使用していることもわかりました。</span><span class="sxs-lookup"><span data-stu-id="3901d-109">From telemetry, we also noticed that a few tenants used more than a fair amount of resources on the Business Central clusters.</span></span> <span data-ttu-id="3901d-110">そのため、サーバーでの OData の同時呼び出し数を制限し、使用されるリソースのテナントごとのガバナンスも制御する設定が、Business Central Server の OData スタックに実装されました。</span><span class="sxs-lookup"><span data-stu-id="3901d-110">Therefore, we have implemented settings in the Business Central server OData stack to limit the amount of concurrent calls to OData on a server and also control per-tenant governance of resources used.</span></span>

<span data-ttu-id="3901d-111">以下の新しいサーバー設定が追加されています。</span><span class="sxs-lookup"><span data-stu-id="3901d-111">The following new server settings have been added:</span></span>

|  |  |
|--|--|
|<span data-ttu-id="3901d-112">ODataServicesOperationTimeout</span><span class="sxs-lookup"><span data-stu-id="3901d-112">ODataServicesOperationTimeout</span></span>|<span data-ttu-id="3901d-113">サーバー インスタンスが単一の OData 要求に割り当てることができる最大時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="3901d-113">Specifies the maximum amount of time that the server instance can allocate to a single OData request.</span></span> |
|<span data-ttu-id="3901d-114">ODataMaxConnections</span><span class="sxs-lookup"><span data-stu-id="3901d-114">ODataMaxConnections</span></span>|<span data-ttu-id="3901d-115">サーバー インスタンスでの同時 OData 要求の最大数を指定します (すべてのテナントに対して)。</span><span class="sxs-lookup"><span data-stu-id="3901d-115">Specifies the maximum number of simultaneous OData requests on the server instance (for all tenants).</span></span>|
|<span data-ttu-id="3901d-116">ODataMaxConnectionsPerTenant</span><span class="sxs-lookup"><span data-stu-id="3901d-116">ODataMaxConnectionsPerTenant</span></span>|<span data-ttu-id="3901d-117">テナントごとの同時 OData 要求の最大数を指定します。</span><span class="sxs-lookup"><span data-stu-id="3901d-117">Specifies the maximum number of simultaneous OData requests per tenant.</span></span>|

## <a name="tell-us-what-you-think"></a><span data-ttu-id="3901d-118">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3901d-118">Tell us what you think</span></span>
<span data-ttu-id="3901d-119">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3901d-119">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3901d-120">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3901d-120">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
