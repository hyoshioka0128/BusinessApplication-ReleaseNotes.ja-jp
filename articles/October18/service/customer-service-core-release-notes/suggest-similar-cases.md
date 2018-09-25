---
title: "Dynamics 365 for Customer Service で類似サポート案件の提示機能がどのように役立つか"
description: "類似するサポート案件についてのインテリジェントな分析情報を活用して、顧客サービス組織のエージェントに知識や専門スキルを伝達する方法について説明します。"
author: vippand
manager: mahesh
ms.date: 7/22/2018
ms.assetid: 0ce32dcb-9752-4e81-be03-7406bba91057
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 47e3e08ea8c4f6474d6b87a933b8bfc69404d70f
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---

#  <a name="suggest-similar-cases"></a><span data-ttu-id="3b043-103">類似サポート案件の提示</span><span class="sxs-lookup"><span data-stu-id="3b043-103">Suggest similar cases</span></span>  

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]



<span data-ttu-id="3b043-104">初回のコンタクト時に最小限の時間で顧客サービス問題を解決することは、顧客満足度 (CSAT) の向上や運営コストの削減につながります。</span><span class="sxs-lookup"><span data-stu-id="3b043-104">Resolving a customer service issue during the first contact and within minimal time helps organizations with increased customer satisfaction (CSAT) and reduced operations cost.</span></span>  <span data-ttu-id="3b043-105">通常、顧客サービス組織では、経験豊富な顧客サービス エージェントや内容領域専門家 (SME) が、類似する問題への対応を通じて培った知識や経験に基づいて、問題を迅速に解決します。</span><span class="sxs-lookup"><span data-stu-id="3b043-105">Typically, in a customer service organization, experienced customer service agents or subject matter experts (SMEs) resolve issues faster based on knowledge or experience gained over a period of resolving similar issues.</span></span> <span data-ttu-id="3b043-106">エージェントが専門外のサポート案件に遭遇した際に、専門のエージェントにサポート案件を転送したり、SME に相談したりしていると、顧客努力や通話処理時間が増加することになり、CSAT の低下につながります。</span><span class="sxs-lookup"><span data-stu-id="3b043-106">If agents get a case outside their areas of expertise, transferring the case to an expert agent or consulting an SME leads to increased customer effort and call handling time, resulting in reduced CSAT.</span></span>  

<span data-ttu-id="3b043-107">類似のサポート案件に関するインテリジェントな分析情報を活用すると、本来なら経験豊富なエージェントからしか提供できない知識や専門スキルを担当のエージェントに伝達し、対応力を強化することができます。</span><span class="sxs-lookup"><span data-stu-id="3b043-107">Intelligent insights on similar cases help customer service organizations empower agents with knowledge and expertise that was otherwise available only with experienced agents.</span></span>  <span data-ttu-id="3b043-108">類似サポート案件の提示機能を使用すれば、解決手順を組織全体で活用できるようになり、経験の浅いエージェントでも、経験豊富なエージェントと同等の対応ができるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b043-108">Suggestions on similar cases help in leveraging resolution steps across the organization, thus making an inexperienced agent as productive as an experienced one.</span></span>  

<span data-ttu-id="3b043-109">この機能は、[Microsoft Text Analytics API](https://azure.microsoft.com/en-in/services/cognitive-services/text-analytics/) と複数のエンティティ レコードのサポート案件情報を使用して、類似するサポート案件を提示するものです。</span><span class="sxs-lookup"><span data-stu-id="3b043-109">This feature leverages [Microsoft Text Analytics APIs](https://azure.microsoft.com/en-in/services/cognitive-services/text-analytics/) and case information across different entity records to suggest similar cases.</span></span> <span data-ttu-id="3b043-110">これにより、サポート案件をよりすばやく効果的に解決できるようになるため、平均処理時間 (AHT) の短縮や顧客エクスペリエンスの向上が促進されます。</span><span class="sxs-lookup"><span data-stu-id="3b043-110">This enables faster and better case resolution, resulting in reduced average handling time (AHT) and improved customer experience.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3b043-111">![](media/similar-cases.png "類似サポート案件の例")</span><span class="sxs-lookup"><span data-stu-id="3b043-111">![](media/similar-cases.png "Example of similar cases")</span></span>

