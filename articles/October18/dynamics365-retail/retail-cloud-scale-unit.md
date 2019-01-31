---
title: Retail Cloud Scale Unit
description: Retail Cloud Scale Unit
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 18b230e4-931f-4843-b1d6-81ffa7aefecb
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 4cffa93ae68545e36672323f5525e85c1c0b0358
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199571"
---
#  <a name="retail-cloud-scale-unit"></a><span data-ttu-id="00022-103">Retail Cloud Scale Unit</span><span class="sxs-lookup"><span data-stu-id="00022-103">Retail Cloud Scale Unit</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]




<span data-ttu-id="00022-104">Retail 展開トポロジには、Retail サーバー、クラウド POS サーバー、Commerce Runtime (CRT)、チャネル データベース コンポーネントをコア バック オフィスから分離する Retail Cloud Scale Unit (RCSU) が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="00022-104">Retail deployment topologies now include the Retail Cloud Scale Unit (RCSU), which separates the Retail Server, Cloud POS server, Commerce run-time (CRT), and channel database components from the core back office.</span></span> <span data-ttu-id="00022-105">これにより、チャネル固有のワークロードを別のスケール ユニットに分散することでシステムのあらゆる側面のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="00022-105">This improves performance across all aspects of the system by distributing the channel-specific workloads into a separate scale unit.</span></span> <span data-ttu-id="00022-106">また、チャネル コンポーネントを個別に処理できるようになるので、ダウンタイムが短縮され、バック オフィスまたはチャネル要件に基づく調整が可能になります。</span><span class="sxs-lookup"><span data-stu-id="00022-106">In addition, the channel components can now be serviced independently, reducing downtime and allowing for coordination based on back-office or channel requirements.</span></span>
