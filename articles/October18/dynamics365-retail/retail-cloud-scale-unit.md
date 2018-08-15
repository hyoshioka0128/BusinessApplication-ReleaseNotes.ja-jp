---
title: "Retail クラウド スケール ユニット"
description: "Retail クラウド スケール ユニット"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 18b230e4-931f-4843-b1d6-81ffa7aefecb
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 8b26ea0484233cec30d1fcf3e2a8507d54cc7b99
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
#  <a name="retail-cloud-scale-unit"></a><span data-ttu-id="dd531-103">Retail クラウド スケール ユニット</span><span class="sxs-lookup"><span data-stu-id="dd531-103">Retail Cloud Scale Unit</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]




<span data-ttu-id="dd531-104">Retail 展開トポロジには、Retail サーバー、クラウド POS サーバー、Commerce Runtime (CRT)、チャネル データベース コンポーネントをコア バック オフィスから分離する Retail クラウド スケール ユニット (RCSU) が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="dd531-104">Retail deployment topologies now include the Retail Cloud Scale Unit (RCSU), which separates the Retail Server, Cloud POS server, Commerce run-time (CRT), and channel database components from the core back office.</span></span> <span data-ttu-id="dd531-105">これにより、チャネル固有のワークロードを別のスケール ユニットに分散することでシステムのあらゆる側面のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="dd531-105">This improves performance across all aspects of the system by distributing the channel-specific workloads into a separate scale unit.</span></span> <span data-ttu-id="dd531-106">また、チャネル コンポーネントを個別に処理できるようになるので、ダウンタイムが短縮され、バック オフィスまたはチャネル要件に基づく調整が可能になります。</span><span class="sxs-lookup"><span data-stu-id="dd531-106">In addition, the channel components can now be serviced independently, reducing downtime and allowing for coordination based on back-office or channel requirements.</span></span>

