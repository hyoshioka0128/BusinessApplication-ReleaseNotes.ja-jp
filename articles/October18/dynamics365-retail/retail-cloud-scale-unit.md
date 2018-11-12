---
title: "Retail クラウド スケール ユニット"
description: "Retail クラウド スケール ユニット"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 18b230e4-931f-4843-b1d6-81ffa7aefecb
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 4cffa93ae68545e36672323f5525e85c1c0b0358
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="retail-cloud-scale-unit"></a><span data-ttu-id="5e23d-103">Retail クラウド スケール ユニット</span><span class="sxs-lookup"><span data-stu-id="5e23d-103">Retail Cloud Scale Unit</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]




<span data-ttu-id="5e23d-104">Retail 展開トポロジには、Retail サーバー、クラウド POS サーバー、Commerce Runtime (CRT)、チャネル データベース コンポーネントをコア バック オフィスから分離する Retail クラウド スケール ユニット (RCSU) が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5e23d-104">Retail deployment topologies now include the Retail Cloud Scale Unit (RCSU), which separates the Retail Server, Cloud POS server, Commerce run-time (CRT), and channel database components from the core back office.</span></span> <span data-ttu-id="5e23d-105">これにより、チャネル固有のワークロードを別のスケール ユニットに分散することでシステムのあらゆる側面のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="5e23d-105">This improves performance across all aspects of the system by distributing the channel-specific workloads into a separate scale unit.</span></span> <span data-ttu-id="5e23d-106">また、チャネル コンポーネントを個別に処理できるようになるので、ダウンタイムが短縮され、バック オフィスまたはチャネル要件に基づく調整が可能になります。</span><span class="sxs-lookup"><span data-stu-id="5e23d-106">In addition, the channel components can now be serviced independently, reducing downtime and allowing for coordination based on back-office or channel requirements.</span></span>

