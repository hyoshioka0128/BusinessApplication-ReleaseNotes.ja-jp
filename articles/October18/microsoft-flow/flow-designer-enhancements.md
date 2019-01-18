---
title: "新しい Microsoft Flow ポータルとデザイナー エクスペリエンス"
description: "デザイナーの内部でのナビゲーションおよび検索アクション用の新しい Microsoft Flow エクスペリエンス。"
author: sunayv
ms.reviewer: deonhe
ms.date: 01/02/2019
ms.assetid: 4f7e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sunayv
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: 3b237595c6354b2e614a344523f8d4ab7dd8a54a
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---
# <a name="new-microsoft-flow-portal-and-designer-experience"></a>新しい Microsoft Flow ポータルとデザイナー エクスペリエンス




10 月のリリースの一環として、Microsoft Flow ポータルとデザイナーのエクスペリエンスのいくつかの重要な側面をオーバーホールしています。

## <a name="navigating-in-the-flow-portal"></a>Flow ポータル内のナビゲーション

Microsoft Flow ポータルには、さまざまな重要ページを見つけるまったく新しい方法があります。 以前は、ポータルの*上部*にいくつかのリンクがありました。 一部のページ (**接続**や**カスタム コネクタ**など) は右上の設定ギアに追いやられ、多くの人にとってこれらのページを見つけることは困難でした。

10 月のリリースでは、*左側*のナビゲーションに移動しています。 この新しいナビゲーションには、**データ** セクションがあります。このセクションには**接続**面へのアクセスだけでなく、Common Data Service の**エンティティ**へのアクセスも含まれます。

> [!div class="mx-imgBorder"]
> ![新しい左側のナビゲーション](media/flow-ui-enhancements-1.png "新しい左側のナビゲーション")

この変更が重要である理由として、近日中に提供されるソリューション管理機能など、将来的にナビゲーションに項目を追加できるようになることもあります。 これにより、フローを論理コンポーネント (アイデア フォーラムの[上位のアイデア]( https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796)の 1 つ) にグループ化することができます。

最後に、左側のナビゲーションをナビゲーションの上部にあるボタンから展開および折りたたむことができます。

## <a name="the-my-flows-list"></a>マイ フロー リスト

マイ フロー リストのエクスペリエンスを簡略化し、他の Microsoft ユーザー インターフェイスと一貫させています。 

> [!div class="mx-imgBorder"]
> ![簡略化されたマイ フロー リスト](media/flow-ui-enhancements-2.png "簡略化されたマイ フロー リスト")

この新しいエクスペリエンスでは、フロー リストから [実行] を選択することによって、*インスタント フロー* (モバイルの [フロー] ボタンによってトリガーされるフローなど) を実行できます。 また、オフになっているフローのアイコンを薄暗くすることで、どのフローがオンになっているのかを簡単に識別できるようにしました。 

## <a name="adding-triggers-and-actions-in-the-flow-designer"></a>フロー デザイナーでのトリガーとアクションの追加

第 3 に、フロー デザイナーでトリガーとアクションを追加するための新しいエクスペリエンスがあります。 **トリガー**を追加すると、次のようなエクスペリエンスが表示されます。

> [!div class="mx-imgBorder"]
> ![トリガーの追加](media/flow-ui-enhancements-3.png "トリガーの追加")

この新しいエクスペリエンスにより、コネクタをカテゴリ別に参照することができます。 たとえば、環境内のどのコネクタが**プレミアム**または**カスタム** コネクタかを確認できます。

次に、**新しいステップ**を選択したときに、アクションや条件などの追加の間に選択するセカンダリ ポップアップは表示されなくなります。 すぐに**アクションの選択**ダイアログが表示されるので、常に余分な選択を行う必要がなくなります。

> [!div class="mx-imgBorder"]
> ![アクションの選択](media/flow-ui-enhancements-4.png "アクションの選択")


すべての**コントロール** アクションをこのダイアログにまとめたので、依然として**条件**をすぐに選択できます。 **コントロール** コネクタを検索または選択して、Apply to Each やスコープのような他の制御フローの概念にアクセスできます。

> [!div class="mx-imgBorder"]
> ![コントロール コネクタ](media/flow-ui-enhancements-5.png "コントロール コネクタ")
