---
title: 調査の設計
description: 調査デザイナーは、Microsoft Forms を基に作成されており、エンタープライズ クラスの機能を提供します。 ユーザーが調査の質問を入力し始めると、タイトルと既存の質問に基づいて、新しい質問の種類が自動的に提案されます。
author: prateeksmicrosoft
ms.date: 02/21/2019
ms.reviewer: shjais
ms.topic: article
ms.service: business-applications
ms.author: prateeks
ms.openlocfilehash: a74758720e888e54b0cad381d5ef678673ba6428
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "406252"
---
#  <a name="design-a-survey"></a><span data-ttu-id="7788d-104">調査の設計</span><span class="sxs-lookup"><span data-stu-id="7788d-104">Design a survey</span></span>
[!include[forms-pro banner](../includes/forms-pro.md)]


<span data-ttu-id="7788d-105">Forms Pro Designer は Forms の上に構築されており、以下のようにシンプルさを保ちながらエンタープライズ レベルの機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="7788d-105">Forms Pro designer is built on top of Forms to provide enterprise-grade capabilities while retaining its simplicity as follows:</span></span>

- <span data-ttu-id="7788d-106">質問の種類 (NPS、スマイリー レーティング、リッカート、ファイルのアップロードなど) を使用して効果的な調査を作成し、回答とビジネス インサイトを最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="7788d-106">Question types (such as NPS, smiley ratings, Likert, file upload) can be used to create effective surveys to maximize response and business insights.</span></span>

- <span data-ttu-id="7788d-107">調査デザイナーには、以前の質問に対する回答に基づいて、表示または非表示にする質問を制御できる、分岐機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="7788d-107">Survey designers will be provided with branching capabilities that can control what questions to show or hide based on the responses to previous questions.</span></span>

- <span data-ttu-id="7788d-108">ユーザーが調査の質問を入力し始めるとすぐに、タイトルと既存の質問に基づいて、新しい質問の種類が自動的に提案されます。</span><span class="sxs-lookup"><span data-stu-id="7788d-108">New questions will be suggested automatically based on the title and existing questions as soon as a user starts typing a survey question.</span></span>

- <span data-ttu-id="7788d-109">複数の地域で調査を作成および配布するために、多言語をサポートする調査が提供されます (たとえば、同じ調査の複数の言語バージョン)。</span><span class="sxs-lookup"><span data-stu-id="7788d-109">A multi-lingual supported survey is provided to create and distribute surveys in multiple regions (for example, multiple language versions of the same survey).</span></span>


## <a name="business-value"></a><span data-ttu-id="7788d-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7788d-110">Business value</span></span>

<span data-ttu-id="7788d-111">ビジネス オーナーは調査を利用して、正確で測定可能なフィードバックを利害関係者から直接得ます。</span><span class="sxs-lookup"><span data-stu-id="7788d-111">Business owners use surveys to get accurate, measurable feedback directly from stakeholders.</span></span> <span data-ttu-id="7788d-112">回答率が低いということは、そのデータには偏りがあり、そこから導き出された結論は誤っているかもしれないことを、意味する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7788d-112">Low response rates would mean that this data may be biased, and conclusions drawn from it may be erroneous.</span></span> <span data-ttu-id="7788d-113">Forms Pro では、調査設計者が回答率の高い効果的な調査を作成するのに役立つ、分岐機能を備えたインテリジェントな設計時の提案が提供されます。</span><span class="sxs-lookup"><span data-stu-id="7788d-113">Forms Pro provides intelligent design-time suggestions with branching capabilities to help survey designers create effective surveys that will have higher response rates.</span></span>

## <a name="persona"></a><span data-ttu-id="7788d-114">ペルソナ</span><span class="sxs-lookup"><span data-stu-id="7788d-114">Persona</span></span>

<span data-ttu-id="7788d-115">ビジネス ユーザー</span><span class="sxs-lookup"><span data-stu-id="7788d-115">Business users</span></span>

## <a name="features"></a><span data-ttu-id="7788d-116">機能</span><span class="sxs-lookup"><span data-stu-id="7788d-116">Features</span></span>

- <span data-ttu-id="7788d-117">**高度な質問の種類**: スマイリー評価、リッカート、ファイルのアップロードなどの質問の種類のサポートが追加され、調査の設計者は回答者から必要なフィードバックを得ることができます。</span><span class="sxs-lookup"><span data-stu-id="7788d-117">**Advanced question types**: Support for question types such as smiley rating, Likert, and file upload has been added to enable survey designers to get the needed feedback from the responders.</span></span>

- <span data-ttu-id="7788d-118">**分岐ロジック**: ユーザーは、以前の質問に対する回答に基づいて、質問者に対して表示または非表示にする質問を制御できる調査を設計できます。</span><span class="sxs-lookup"><span data-stu-id="7788d-118">**Branching logic**: Users can design surveys where they can control what questions are shown or hidden from the respondents based on their responses to previous questions.</span></span>

- <span data-ttu-id="7788d-119">**調査の設計の提案**: Forms Pro では、使用する質問の種類に関するインテリジェントな入力が提供され、調査設計者が最大限の回答を得られる調査を作成するのに役立つ提案を自動入力できます。</span><span class="sxs-lookup"><span data-stu-id="7788d-119">**Survey design suggestions**: Forms Pro provides intelligent inputs about the type of questions to use and can auto-fill suggestions to help survey designers create a survey that will attract maximum responses.</span></span>

- <span data-ttu-id="7788d-120">**調査の翻訳**: ユーザーは調査を複数の言語で翻訳して、企業が多言語市場に対応できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7788d-120">**Survey translation**: Users can translate a survey in multiple languages to enable enterprises to cater to multi-lingual markets.</span></span>

    > [!NOTE]
    > <span data-ttu-id="7788d-121">調査を翻訳する機能は、2019 年 3 月にパブリック プレビューとしてリリースされる予定です。</span><span class="sxs-lookup"><span data-stu-id="7788d-121">The capability to translate a survey will be released in March 2019 as public preview.</span></span>

- <span data-ttu-id="7788d-122">**データのパイプ処理**: 調査の質問の一部として、設計者は、注文情報、顧客のサポート案件のタイトル、関連する製品情報の取得など、ビジネス アプリからコンテキスト対応のデータを表示できます。</span><span class="sxs-lookup"><span data-stu-id="7788d-122">**Piping data**: As part of the survey questions, designers can display contextual data from business apps, such as fetching order information, customer case title, or related product information.</span></span>

    <span data-ttu-id="7788d-123">![調査デザイナー](media/survey-designer.png "調査デザイナー")</span><span class="sxs-lookup"><span data-stu-id="7788d-123">![Survey designer](media/survey-designer.png "Survey designer")</span></span>
