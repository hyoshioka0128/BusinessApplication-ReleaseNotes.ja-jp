---
title: 簡素化されたビュー - テンプレート
description: 簡素化されたビュー - テンプレート
author: ReneeW-CPub
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: f4c3996f77c28fadf08ce6eac55189297e607883
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287884"
---
#  <a name="simplified-view---templates"></a>簡素化されたビュー - テンプレート 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



2019 年 4 月リリースでは、独自のパーソナライズ ページ ビューを作成し、それらを管理、公開できるようになります。

この新機能をベースに、一連の事前構成済みビュー テンプレートが一部のドキュメントとエンティティで利用可能になります。 テンプレートの構成は、特定のユーザー ロールと、同じユーザー ロールによって実行される特定のタスクの両方に関連する情報によって決まります。 ビュー テンプレートが利用可能になるドキュメントとエンティティの種類は次のとおりです。

**ドキュメント**

- 販売注文
- 発注書
- 購買要求
- 仕訳帳 (の選択)

**エンティティ**

- 顧客
- ベンダー
- 製品

具体的には、顧客サービス担当者と売掛金担当者向けに、販売注文詳細ページの 2 つのビューが個別に用意され、ロールに関連する注文詳細にそれぞれの異なるニーズが反映されます。 顧客サービス担当者には、注文の処理と履行の段階に応じて異なる注文情報を参照できるよう、2 つの追加ページ ビューが提供されます。

**注文入力**ビューは、注文入力と注文準備に不可欠な注文明細行詳細 (製品名と属性、数量、価格とマージン関連の値、合計金額など) の表示に特化しています。

![簡素化されたビュー テンプレートの例 1](media/simplified-view-templates-1.png "簡素化されたビュー テンプレートの例 1")

注文が履行された後、顧客サービス担当者が顧客の問合せに回答する必要があるときには、フルフィルメントの状態に関する詳細に特化した**注文フォローアップ** ビューが役に立ちます。

![簡素化されたビュー テンプレートの例 2](media/simplified-view-templates-2.png "簡素化されたビュー テンプレートの例 2")

