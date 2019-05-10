---
title: オンプレミス展開でのエンティティ格納のサポート
description: Dynamics 365 for Finance and Operations オンプレミスで利用可能なエンティティ格納
author: MilindaV2
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: MilindaV2
ms.openlocfilehash: 958aff6631f41ce990b21cc2a12ab0643e0e2421
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225146"
---
#  <a name="entity-store-support-for-on-premises-deployments"></a><span data-ttu-id="67bcf-103">オンプレミス展開でのエンティティ格納のサポート</span><span class="sxs-lookup"><span data-stu-id="67bcf-103">Entity store support for on-premises deployments</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="67bcf-104">[エンティティ格納](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/power-bi-integration-entity-store)は、管理者またはパワー ユーザーのステージで、レポート作成および分析のために測定値を専用のデータ ストアに集約できる運用データ ストアです。</span><span class="sxs-lookup"><span data-stu-id="67bcf-104">[Entity store](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/power-bi-integration-entity-store) is an operational data store that lets an administrator or power user stage aggregate measurements in a dedicated data store for reporting and analytics.</span></span> <span data-ttu-id="67bcf-105">お客様は、Microsoft Power BI DirectQuery のモデルをエンティティ格納と共に使用して、大量のデータに対する大容量でほぼリアルタイムの分析レポートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="67bcf-105">Customers can use Microsoft Power BI DirectQuery models together with entity store to enable high-volume, near-real-time analytical reporting over large volumes of data.</span></span> <span data-ttu-id="67bcf-106">トランザクション ストアからのデータはリアルタイムで同期され、エンティティ格納で利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="67bcf-106">Data from the transactional store is synced in real time and made available in the entity store.</span></span>

<span data-ttu-id="67bcf-107">エンティティ格納は、バージョン 10.0 以降のすべてのお客様が、オンプレミス用に定義されてほぼリアルタイムで同期されるすべての既定の集計で利用できます。</span><span class="sxs-lookup"><span data-stu-id="67bcf-107">Entity store will be made available to all customers on version 10.0 and later with all default aggregates defined and synced in near real time for on-premises.</span></span> <span data-ttu-id="67bcf-108">オンプレミスのお客様は、エンティティ格納に対して作成された既成のレポートを使用し、自分の Power BI サブスクリプションに展開することができます。</span><span class="sxs-lookup"><span data-stu-id="67bcf-108">On-premises customers will get the ability to use the ready-made reports authored against entity store and deploy to their own Power BI subscription.</span></span> <span data-ttu-id="67bcf-109">ただし、オンプレミス展開には分析ワークスペースは含まれません。</span><span class="sxs-lookup"><span data-stu-id="67bcf-109">However, on-premises deployments will not contain Analytical workspaces.</span></span> 
