---
title: e コマース統合での支払い方法の一覧表示
description: この機能を使用すると、e コマースの支払に関する顧客のコンテキストを送信し、以前の支払い方法を一覧表示することができます。
author: rubendel
manager: AnnBe
ms.date: 04/11/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rubendel
audience: ''
ms.openlocfilehash: 151186d246ed809bd69a4429f2b867dcfa3651e7
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225297"
---
# <a name="list-payment-instruments-in-e-commerce-integration"></a>e コマース統合での支払い方法の一覧表示

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

## <a name="business-value"></a>ビジネス バリュー

e コマースのシナリオでは、顧客が今後の取引のために支払い方法を保存して、後で注文を作成するときにその支払い方法を使用できるようにするのが一般的です。 この機能を使用すると、店舗は承認要求に顧客のコンテキストを含めることができ、それを使用して、顧客を同じ支払プロセッサで以前に使用された支払い方法にマッピングすることができます。 

## <a name="feature-description"></a>機能の説明

Dynamics 365 for Retail または Finance and Operations の e コマースのシナリオでは、"支払受け入れページ" (外部の支払フローの URL) または "支払受け入れコンテンツ" (外部の支払フローの HTML コンテンツ) によって支払エクスペリエンスが進められます。 この URL または HTML コンテンツは、新しい支払セッションと支払いコネクタに送信される一連のパラメーターに基づいて、支払ゲートウェイ/プロセッサによってオンザフライで生成されます。

この機能を小売共有パラメーターで有効にすると、e コマース店舗で認証された顧客が注文を作成するときに、次回の訪問のためにカードを保存するオプションが提示されます。 チェックアウト プロセスで顧客がカードを保存することを選択すると、次に顧客がその Web ネットショップを訪問したときに、そのカードが支払オプションの 1 つとして表示されます。 顧客はカードの保存をオプトインする必要があります。 ゲスト チェックアウトを使用している顧客はカードを保存できません。 

この機能を有効にすると、カード支払ページの要求と共に、顧客のコンテキストが支払ゲートウェイに渡されます。 プロセッサが保存されている顧客のカードを返すことができ、顧客を以前に保存された支払にマッピングできる場合、チェックアウト時にそれらの支払を選択できるようになります。 
