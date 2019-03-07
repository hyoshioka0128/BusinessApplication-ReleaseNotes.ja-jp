---
title: Word 文書の生成
description: Word Online (Business) コネクタを使用すると、Microsoft Graph でサポートされているドキュメント ライブラリ内の Word ファイルを操作して、テンプレートからファイルを生成したりファイルの PDF バージョンを作成したりできます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/04/2019
ms.assetid: a49f123a-d50e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 95c8e8e3342eb5401507561299de9cfa59890312
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391075"
---
# <a name="word-document-generation-public-preview"></a><span data-ttu-id="7cb30-103">Word 文書の生成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="7cb30-103">Word document generation (Public Preview)</span></span>




<span data-ttu-id="7cb30-104">新しい [Word Online (Business)](https://flow.microsoft.com/services/) コネクタを使用すると、Microsoft Graph (OneDrive for Business、SharePoint サイト、および Office 365 グループ) でサポートされているドキュメント ライブラリ内の Word ファイルを操作できます。</span><span class="sxs-lookup"><span data-stu-id="7cb30-104">The new [Word Online (Business)](https://flow.microsoft.com/services/) connector lets you work with Word files in document libraries supported by Microsoft Graph: OneDrive for Business, SharePoint Sites, and Office 365 Groups.</span></span> <span data-ttu-id="7cb30-105">現時点では 2 つのアクションがあります。</span><span class="sxs-lookup"><span data-stu-id="7cb30-105">Today there are two actions:</span></span>

- <span data-ttu-id="7cb30-106">**Word 文書を PDF に変換する**: 選択したファイルの PDF バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="7cb30-106">**Convert Word Document to PDF**: Gets a PDF version of the selected file.</span></span>
- <span data-ttu-id="7cb30-107">**Microsoft Word テンプレートを設定する**: Microsoft Word テンプレートを読み取り、選択した動的な値をテンプレートのフィールドに入力して Word 文書を生成します。</span><span class="sxs-lookup"><span data-stu-id="7cb30-107">**Populate a Microsoft Word template**: Reads a Microsoft Word template to then fill the template fields with selected dynamic values to generate a Word document.</span></span>

<span data-ttu-id="7cb30-108">Word テンプレートは、Windows または Mac 上で[**開発者**タブを有効にする](https://support.office.com/article/show-the-developer-tab-e1192344-5e56-4d45-931b-e5fd9bea2d45)ことによって作成できます。このタブを有効にしたら、**コントロール** セクションの下で[任意の数のテキスト コンテンツ コントロール](https://support.office.com/article/create-forms-that-users-complete-or-print-in-word-040c5cc1-e309-445b-94ac-542f732c8c8b)を文書に追加できます。</span><span class="sxs-lookup"><span data-stu-id="7cb30-108">You can build Word templates on either Windows or your Mac by [enabling the **Developer** tab](https://support.office.com/article/show-the-developer-tab-e1192344-5e56-4d45-931b-e5fd9bea2d45). Once you have enabled that tab, under the **Controls** section you can add [any number of text content controls](https://support.office.com/article/create-forms-that-users-complete-or-print-in-word-040c5cc1-e309-445b-94ac-542f732c8c8b) into your document.</span></span> <span data-ttu-id="7cb30-109">コントロールにフロー内で使用する表示名を付けるには、コントロールの**プロパティ**を使用します。</span><span class="sxs-lookup"><span data-stu-id="7cb30-109">Use the control **Properties** to give the control a friendly name that you will use in the flow.</span></span> <span data-ttu-id="7cb30-110">Word 文書の作成が完了したら、上記のいずれかのドキュメント ライブラリの場所に保存します。</span><span class="sxs-lookup"><span data-stu-id="7cb30-110">Once you are done creating your Word document, save it to one of the above document library locations.</span></span>

<span data-ttu-id="7cb30-111">これで、フローの構築を開始できます。</span><span class="sxs-lookup"><span data-stu-id="7cb30-111">Now, you can start building the flow.</span></span> <span data-ttu-id="7cb30-112">**Microsoft Word テンプレートを設定する**アクションをフローに追加します。そのファイルを選択すると、追加したすべてのコントロールの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7cb30-112">Add the **Populate a Microsoft Word template** action to your flow, and when you select that file you should see a list of all the controls that you added.</span></span> <span data-ttu-id="7cb30-113">これらのフィールドに、新しい Word 文書に含める (おそらく *動的コンテンツ*からの) 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7cb30-113">Populate these fields with the values (probably from *Dynamic content*) you’ll want to be in the new Word document.</span></span> <span data-ttu-id="7cb30-114">最後に、アクションの出力を使用して電子メールを送信したり、文書を別の場所に保存したり、その他の任意の数のアクションを実行したりできます。</span><span class="sxs-lookup"><span data-stu-id="7cb30-114">Finally, you can then use the outputs of the action and send an email, save the document to another location, or any number of other actions.</span></span> 

<span data-ttu-id="7cb30-115">現時点では、表で使用されるような繰り返しコンテンツ コントロールはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="7cb30-115">Note that at this time, repeating content controls such as those used in tables are not supported.</span></span>