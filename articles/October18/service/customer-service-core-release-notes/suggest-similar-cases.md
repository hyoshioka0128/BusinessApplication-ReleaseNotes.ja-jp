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
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 47e3e08ea8c4f6474d6b87a933b8bfc69404d70f
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---

#  <a name="suggest-similar-cases"></a>類似サポート案件の提示  

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]



初回のコンタクト時に最小限の時間で顧客サービス問題を解決することは、顧客満足度 (CSAT) の向上や運営コストの削減につながります。  通常、顧客サービス組織では、経験豊富な顧客サービス エージェントや内容領域専門家 (SME) が、類似する問題への対応を通じて培った知識や経験に基づいて、問題を迅速に解決します。 エージェントが専門外のサポート案件に遭遇した際に、専門のエージェントにサポート案件を転送したり、SME に相談したりしていると、顧客努力や通話処理時間が増加することになり、CSAT の低下につながります。  

類似のサポート案件に関するインテリジェントな分析情報を活用すると、本来なら経験豊富なエージェントからしか提供できない知識や専門スキルを担当のエージェントに伝達し、対応力を強化することができます。  類似サポート案件の提示機能を使用すれば、解決手順を組織全体で活用できるようになり、経験の浅いエージェントでも、経験豊富なエージェントと同等の対応ができるようになります。  

この機能は、[Microsoft Text Analytics API](https://azure.microsoft.com/en-in/services/cognitive-services/text-analytics/) と複数のエンティティ レコードのサポート案件情報を使用して、類似するサポート案件を提示するものです。 これにより、サポート案件をよりすばやく効果的に解決できるようになるため、平均処理時間 (AHT) の短縮や顧客エクスペリエンスの向上が促進されます。

> [!div class="mx-imgBorder"]
> ![](media/similar-cases.png "類似サポート案件の例")

