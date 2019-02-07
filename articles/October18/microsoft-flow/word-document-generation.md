---
title: Word 文書の生成
description: Word Online (Business) コネクタを使用すると、Microsoft Graph でサポートされているドキュメント ライブラリ内の Word ファイルを操作して、テンプレートからファイルを生成したりファイルの PDF バージョンを作成したりできます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/20/2019
ms.assetid: a49f123a-d50e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 0c2351000543c46ab22e3c321dbc710ce073f1d8
ms.sourcegitcommit: 1de869f4ccb74ccc9b9cd26817e3d5c30734c3c3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2019
ms.locfileid: "288660"
---
# <a name="word-document-generation-public-preview"></a>Word 文書の生成 (パブリック プレビュー)


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

新しい [Word Online (Business)](https://flow.microsoft.com/services/) コネクタを使用すると、Microsoft Graph (OneDrive for Business、SharePoint サイト、および Office 365 グループ) でサポートされているドキュメント ライブラリ内の Word ファイルを操作できます。 現時点では 2 つのアクションがあります。

- **Word 文書を PDF に変換する**: 選択したファイルの PDF バージョンを取得します。
- **Microsoft Word テンプレートを設定する**: Microsoft Word テンプレートを読み取り、選択した動的な値をテンプレートのフィールドに入力して Word 文書を生成します。

Word テンプレートは、Windows または Mac 上で[**開発者**タブを有効にする](https://support.office.com/article/show-the-developer-tab-e1192344-5e56-4d45-931b-e5fd9bea2d45)ことによって作成できます。このタブを有効にしたら、**コントロール** セクションの下で[任意の数のテキスト コンテンツ コントロール](https://support.office.com/article/create-forms-that-users-complete-or-print-in-word-040c5cc1-e309-445b-94ac-542f732c8c8b)を文書に追加できます。 コントロールにフロー内で使用する表示名を付けるには、コントロールの**プロパティ**を使用します。 Word 文書の作成が完了したら、上記のいずれかのドキュメント ライブラリの場所に保存します。

これで、フローの構築を開始できます。 **Microsoft Word テンプレートを設定する**アクションをフローに追加します。そのファイルを選択すると、追加したすべてのコントロールの一覧が表示されます。 これらのフィールドに、新しい Word 文書に含める (おそらく *動的コンテンツ*からの) 値を設定します。 最後に、アクションの出力を使用して電子メールを送信したり、文書を別の場所に保存したり、その他の任意の数のアクションを実行したりできます。 

現時点では、表で使用されるような繰り返しコンテンツ コントロールはサポートされていません。