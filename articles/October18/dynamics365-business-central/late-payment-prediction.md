---
title: 支払遅延予測の拡張機能
description: 販売に対する支払が期限どおりであるかどうかの予測
author: AndreiPanko
manager: edupont04
ms.date: 10/17/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: andreipa
audience: developer, admin, end user
ms.openlocfilehash: e108c381c19b78983c5da5453274999f61676960
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199149"
---
# <a name="late-payment-prediction-extension"></a><span data-ttu-id="d5bd6-103">支払遅延予測の拡張機能</span><span class="sxs-lookup"><span data-stu-id="d5bd6-103">Late Payment Prediction extension</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="d5bd6-104">売掛金の効果的な管理は、ビジネスの全体的な財務健全性にとって重要です。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-104">Effectively managing receivables is important to the overall financial health of a business.</span></span> <span data-ttu-id="d5bd6-105">支払遅延予測拡張機能は、売上請求書が適時に支払われるかどうかを予測することによって未処理の売掛金を削減するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-105">The Late Payment Prediction extension can help you reduce outstanding receivables by predicting whether sales invoices will be paid on time.</span></span>

<span data-ttu-id="d5bd6-106">この拡張機能では、人工知能の標準的なメリットを提供する機械学習分類モデルを使用します。データ サイエンティストである必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-106">The extension uses a machine learning classification model that gives you out-of-the-box benefits from artificial intelligence, without having to be a data scientist.</span></span> <span data-ttu-id="d5bd6-107">しかしそうであるなら、このモデルをわずかなステップで自分のモデルと交換できます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-107">If you are, though, you can swap out our model for yours in just a few steps.</span></span> 

<span data-ttu-id="d5bd6-108">この拡張機能では、顧客の支払習慣に関する予測をより鮮明にするデータを蓄積しながら、モデルを訓練し続けることもできます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-108">The extension also lets you continue to train your model as you accumulate data that will sharpen predictions about the payment habits of your customers.</span></span> <span data-ttu-id="d5bd6-109">Business Central を使用するほど、モデルにフィードするデータが増え、予測がより正確になります。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-109">The more you use Business Central and the more data you feed the model, the more accurate predictions become.</span></span>

<span data-ttu-id="d5bd6-110">いつ、どのようにして予測を生成するかは、ユーザー次第です。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-110">How, and when, you generate predictions is up to you:</span></span>

-   <span data-ttu-id="d5bd6-111">すべての売上請求書を**顧客元帳エントリ** ウィンドウで分析することができます。このウィンドウでは、転記された請求書をさらに詳しく調べることができます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-111">You can analyze all sales invoices in the **Customer Ledger Entries** window, where you can also dig deeper into each posted invoice.</span></span> <span data-ttu-id="d5bd6-112">[支払遅延] フィールドには、予測の結果が表示されます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-112">The Late Payment field shows the outcome of the prediction.</span></span>

-   <span data-ttu-id="d5bd6-113">支払遅延を前もって予測することができます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-113">You can predict late payments upfront.</span></span> <span data-ttu-id="d5bd6-114">**販売見積**、**販売注文**、および**売上請求書**ウィンドウで、**支払の予測**アクションを使用して、表示している営業書類の予測を生成できます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-114">In the **Sales Quotes**, **Sales Orders**, and **Sales Invoices** windows, you can use the **Predict Payment** action to generate a prediction for the sales document you're viewing.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="d5bd6-115">![遅延が予測される請求書の概要](media/LPP_List.png "遅延が予測される請求書の概要")</span><span class="sxs-lookup"><span data-stu-id="d5bd6-115">![Overview of invoices predicted to be late](media/LPP_List.png "Overview of invoices predicted to be late")</span></span>

<span data-ttu-id="d5bd6-116">*遅延が予測される請求書の概要*</span><span class="sxs-lookup"><span data-stu-id="d5bd6-116">*Overview of invoices predicted to be late*</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="d5bd6-117">![販売見積の予測の生成](media/LPP_Quote.png "販売見積の予測の生成")</span><span class="sxs-lookup"><span data-stu-id="d5bd6-117">![Generate prediction for the sales quote](media/LPP_Quote.png "Generate prediction for the sales quote")</span></span>

<span data-ttu-id="d5bd6-118">*販売見積の予測の生成*</span><span class="sxs-lookup"><span data-stu-id="d5bd6-118">*Generate prediction for the sales quote*</span></span>

<span data-ttu-id="d5bd6-119">これらの分析情報をプロアクティブなアクションに変換できます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-119">You can turn these insights into proactive action.</span></span> <span data-ttu-id="d5bd6-120">たとえば、支払の遅延が予測される場合、顧客の支払条件または支払方法を調整することができます。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-120">For example, if a payment is predicted to be late, you might decide to adjust the terms of payment or the payment method for the customer.</span></span>

## <a name="resources"></a><span data-ttu-id="d5bd6-121">リソース</span><span class="sxs-lookup"><span data-stu-id="d5bd6-121">Resources</span></span>
[<span data-ttu-id="d5bd6-122">支払遅延の予測</span><span class="sxs-lookup"><span data-stu-id="d5bd6-122">Predicting Late Payments</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-extensions-late-payment-prediction)

## <a name="tell-us-what-you-think"></a><span data-ttu-id="d5bd6-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="d5bd6-123">Tell us what you think</span></span>
<span data-ttu-id="d5bd6-124">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="d5bd6-125">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="d5bd6-125">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
