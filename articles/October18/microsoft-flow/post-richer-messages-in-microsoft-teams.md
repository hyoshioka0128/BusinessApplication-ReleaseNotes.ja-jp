---
title: Microsoft Teams のアダプティブ カード
description: Flow ボットでチャネルにメッセージを投稿できるようになり、これらのメッセージにアダプティブ カードを含められるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 03/15/2019
ms.assetid: 3d8ad1f3-d30e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ea053c76eb4bc96440b97e2e9482f4b44897ff50
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880538"
---
# <a name="adaptive-cards-for-microsoft-teams"></a>Microsoft Teams のアダプティブ カード

独自の_アダプティブ カード_を Flow ボットとしてチャネルに投稿できるようになりました。 アダプティブ カードは、充実した書式設定を利用したコンテンツを Microsoft Teams (Teams) の会話に直接表示するための手段です。 アダプティブ カードには、画像、グラフ、充実した書式設定を利用したテキストなどのコンポーネントを含めることができます。 開始するには、Teams コネクタで新しいアクションを選択します。

![Teams アクションの一覧](media/adaptive-cards-teams-1.png)

アダプティブ カードでは、さまざまなチャネルで使用できる共通の JSON 形式を使用します。 ただし、この JSON を手作業で作成する必要はありません。[アダプティブ カード Web サイトの機能豊富なドラッグ アンド ドロップ デザイナー](https://adaptivecards.io/designer/)を使用してカードを作成できます。

![アダプティブ カード デザイナー](media/adaptive-cards-teams-2.png)

カードに必要なすべての要素を追加したら、下部の JSON ウィンドウを開き、そこに含まれるすべてのコンテンツをコピーします。 次に、Microsoft Flow デザイナーで、アクションの**メッセージ** フィールドにそのコンテンツを貼り付けます。 アクションが実行されると、選択した Teams チャネルに、見栄えよく書式設定されたアダプティブ カードが表示されます。

![Teams チャネルに表示されたカード](media/adaptive-cards-teams-3.png)

アダプティブ カードを投稿するだけでなく、単純なメッセージをボットとして Teams チャネルに投稿することもできます。 これらのメッセージを、自分のユーザー アカウントではなく Flow ボットから送信できます。 また、メッセージに他のユーザーの **@mentions** を含めて、メッセージを投稿したときに対象ユーザーに通知が送られるようにすることができます。  **@mention** を作成するには、そのユーザーの電子メール アドレスまたはユーザー ID を `<at>` タグで囲む必要があります。 たとえば、次のようにします。

```
Hello <at>stephen@example.com</at> - your request has been completed!
```