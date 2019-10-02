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
# <a name="support-for-additional-languages-in-topic-generation"></a><span data-ttu-id="52058-103">トピック生成での追加言語のサポート</span><span class="sxs-lookup"><span data-stu-id="52058-103">Support for additional languages in topic generation</span></span>

[!include[customer-service banner](../../../includes/dynamics365-ai-customer-service.md)]

<span data-ttu-id="52058-104">Customer Service Insights では、自然言語の理解とその他の人工知能技術を使用して、類似サポート案件をトピックに自動的にグループ化することにより、実用的な分析情報を検出します。</span><span class="sxs-lookup"><span data-stu-id="52058-104">Customer Service Insights uses natural language understanding and other artificial intelligence technology to discover actionable insights by automatically grouping similar support cases into topics.</span></span> <span data-ttu-id="52058-105">類似サポート案件をより正確に検索するために、3 つのバイリンガル言語モデル (フランス語と英語、ドイツ語と英語、スペイン語と英語) およびすべての言語向けの一般モデルを含む追加言語モデルが利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="52058-105">In order to find similar cases more accurately, additional language models will be available, including three bilingual language models (French and English, German and English, and Spanish and English), and a general model for all languages.</span></span> 

<span data-ttu-id="52058-106">言語固有のモデルにより、これらの言語に対する言語理解機能が向上します。</span><span class="sxs-lookup"><span data-stu-id="52058-106">The language-specific models enable better language understanding capability for those languages.</span></span> <span data-ttu-id="52058-107">Customer Service Insights が毎日の更新でサポート案件データを処理するときに、サポート案件で使用されている主要言語が自動的に検出されます。</span><span class="sxs-lookup"><span data-stu-id="52058-107">When Customer Service Insights processes the case data on daily refresh, it will automatically detect the primary languages used in the cases.</span></span> <span data-ttu-id="52058-108">サポート案件の 70% を超える言語が単一のモデル (英語またはいずれかのバイリンガル言語モデル) でサポートされている場合、そのモデルはすべてのサポート案件からトピックを検出するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="52058-108">If more than 70 percent of the cases are in the languages supported by a single model (either English or one of the bilingual language models), that model will be used to discover topics from all of the cases.</span></span> <span data-ttu-id="52058-109">それ以外の場合は、一般モデルが使用されます。</span><span class="sxs-lookup"><span data-stu-id="52058-109">Otherwise, the general model will be used.</span></span> 
