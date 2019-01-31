---
title: 複数リソースのスケジューリング
description: 複数リソースのスケジューリングにより、単一の作業指示書に対して複数のリソースをスケジュールできます。
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 3cf4815b-ae74-4c42-89a4-cc2ab31ebfad
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 1735f94d0f92dd51be23d11b340e2eea26b0ed25
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200016"
---
#  <a name="multi-resource-scheduling"></a><span data-ttu-id="17615-103">複数リソースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="17615-103">Multi-resource scheduling</span></span>

[!include[field-service banner](../../includes/field-service.md)]




<span data-ttu-id="17615-104">複数リソースのスケジューリングにより、単一の作業指示書に対して複数のリソースをスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="17615-104">Multi-resource scheduling allows for multiple resources to be scheduled against a single work order.</span></span> <span data-ttu-id="17615-105">これは、作業の完了に複数のリソースが必要な複雑な作業指示書を持つお客様からよくいただく要求でした。</span><span class="sxs-lookup"><span data-stu-id="17615-105">This has been a common request from customers who have complex work orders requiring more than a single resource to complete the work.</span></span> <span data-ttu-id="17615-106">インシデントの種類を要件グループ テンプレートに関連付けることができるので、作業指示書を作成し、インシデントの種類を選択するときに、作業指示書に要件のグループを追加して、複数リソースのスケジューリングを開始できます。</span><span class="sxs-lookup"><span data-stu-id="17615-106">Incident types will be able to be related to requirement group templates so that when you create a work order and select an incident type, a group of requirements can be added to the work order, lighting up multi-resource scheduling.</span></span>  <span data-ttu-id="17615-107">複数リソースのスケジューリングのインフラストラクチャは、2018 年春の Universal Resource Scheduling (URS) にプレビューとして含まれ、2018 年 10 月に GA (一般提供) となります。2018 年 10 月リリースからは Field Service によって利用されます。</span><span class="sxs-lookup"><span data-stu-id="17615-107">The infrastructure for multi-resource scheduling was included in Universal Resource Scheduling (URS) in Spring '18 as a preview, October '18 GA, and is now being leveraged by Field Service starting with the October '18 release.</span></span>
