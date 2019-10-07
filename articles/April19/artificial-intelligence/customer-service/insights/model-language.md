---
title: トピック生成での追加言語のサポート
description: Dynamics 365 Customer Service Insights では、英語以外の言語のテキスト入力からトピックを作成できるようになりました
author: tpalmer
ms.date: 08/05/2019
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: shellyha
ms.openlocfilehash: e9461b3c8b16f169a1ad7e281de3269b96c7c0c1
ms.sourcegitcommit: 9c7b08c332ea6bc83b5399d184935c47971dc5d0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/08/2019
ms.locfileid: "1866724"
---
# <a name="support-for-additional-languages-in-topic-generation"></a>トピック生成での追加言語のサポート

[!include[customer-service banner](../../../includes/dynamics365-ai-customer-service.md)]

Customer Service Insights では、自然言語の理解とその他の人工知能技術を使用して、類似サポート案件をトピックに自動的にグループ化することにより、実用的な分析情報を検出します。 類似サポート案件をより正確に検索するために、3 つのバイリンガル言語モデル (フランス語と英語、ドイツ語と英語、スペイン語と英語) およびすべての言語向けの一般モデルを含む追加言語モデルが利用可能になります。 

言語固有のモデルにより、これらの言語に対する言語理解機能が向上します。 Customer Service Insights が毎日の更新でサポート案件データを処理するときに、サポート案件で使用されている主要言語が自動的に検出されます。 サポート案件の 70% を超える言語が単一のモデル (英語またはいずれかのバイリンガル言語モデル) でサポートされている場合、そのモデルはすべてのサポート案件からトピックを検出するために使用されます。 それ以外の場合は、一般モデルが使用されます。 
