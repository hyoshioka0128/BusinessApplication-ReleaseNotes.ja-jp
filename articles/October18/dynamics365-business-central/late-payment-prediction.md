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
# <a name="late-payment-prediction-extension"></a>支払遅延予測の拡張機能

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

売掛金の効果的な管理は、ビジネスの全体的な財務健全性にとって重要です。 支払遅延予測拡張機能は、売上請求書が適時に支払われるかどうかを予測することによって未処理の売掛金を削減するのに役立ちます。

この拡張機能では、人工知能の標準的なメリットを提供する機械学習分類モデルを使用します。データ サイエンティストである必要はありません。 しかしそうであるなら、このモデルをわずかなステップで自分のモデルと交換できます。 

この拡張機能では、顧客の支払習慣に関する予測をより鮮明にするデータを蓄積しながら、モデルを訓練し続けることもできます。 Business Central を使用するほど、モデルにフィードするデータが増え、予測がより正確になります。

いつ、どのようにして予測を生成するかは、ユーザー次第です。

-   すべての売上請求書を**顧客元帳エントリ** ウィンドウで分析することができます。このウィンドウでは、転記された請求書をさらに詳しく調べることができます。 [支払遅延] フィールドには、予測の結果が表示されます。

-   支払遅延を前もって予測することができます。 **販売見積**、**販売注文**、および**売上請求書**ウィンドウで、**支払の予測**アクションを使用して、表示している営業書類の予測を生成できます。

> [!div class="mx-imgBorder"]
> ![遅延が予測される請求書の概要](media/LPP_List.png "遅延が予測される請求書の概要")

*遅延が予測される請求書の概要*

> [!div class="mx-imgBorder"]
> ![販売見積の予測の生成](media/LPP_Quote.png "販売見積の予測の生成")

*販売見積の予測の生成*

これらの分析情報をプロアクティブなアクションに変換できます。 たとえば、支払の遅延が予測される場合、顧客の支払条件または支払方法を調整することができます。

## <a name="resources"></a>リソース
[支払遅延の予測](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-extensions-late-payment-prediction)

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
