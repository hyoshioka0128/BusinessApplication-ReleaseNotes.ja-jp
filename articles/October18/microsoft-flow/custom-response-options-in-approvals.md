---
title: 承認のカスタム応答オプションの使用
description: 開発者は、必要などのようなオプションをいくつでも含む承認フローを構築することができます。
author: KaranSr
ms.reviewer: deonhe
ms.date: 03/15/2019
ms.assetid: e37358cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: karansr
audience: Power user
ms.openlocfilehash: 724cb6084bc713e1398d0001eb04c9812c717225
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880545"
---
# <a name="custom-response-options-in-approvals"></a>承認のカスタム応答オプション

組織のニーズに合わせて特別に調整した応答を使用する承認フローを作成するには、カスタム応答オプションを使用します。 たとえば、カスタム応答を使用して、コンテンツのレビューなどで*承認*、*編集して承認*、*却下*のような詳細なフィードバックを提供できます。

## <a name="create-an-approval-with-custom-responses"></a>カスタム応答を使用する承認を作成する

だれかが SharePoint に提案をアップロードするたびに承認依頼を送信し、承認者が*承認*、*編集して承認*、*却下*の 3 つのオプションのいずれかを使用して応答できるようにするとします。

開始するには、次の手順を実行します。

1. 承認を開始するアクションを追加します。

     ![承認アクションの一覧](media/custom-response-options-in-approvals/customresponseoptions-1.png "承認アクションの一覧")

1. **承認タイプ**の一覧で、2 つのタイプのいずれかを選択します。

     ![承認タイプ](media/custom-response-options-in-approvals/customresponseoptions-2.png "承認タイプ")

1. **応答オプション項目**フィールドにカスタム応答を入力します。

    > [!TIP]
    > さらにカスタム応答を追加する場合は、**新しい項目の追加**を選択します。

     ![応答オプション](media/custom-response-options-in-approvals/customresponseoptions-3.png "応答オプション")

## <a name="use-approval-responses"></a>承認応答を使用する

承認者が依頼に対して意思決定を行った後に、異なる処理が必要になる場合があります。 たとえば、依頼への応答が**承認**または**却下**の場合には提案を SharePoint の承認済み提案または却下済み提案のフォルダーに移動し、 応答が**編集して承認**の場合には作成者に電子メールを送信して提案の変更を依頼するとします。

これを行うには、フローに条件または切り替えアクションを追加した後で、動的コンテンツピッカーから承認依頼の**結果**フィールドを選択します。 値が**承認**、**編集して承認**、**却下**のどれであるかを必ず確認してください。

![結果に基づく切り替え](media/custom-response-options-in-approvals/customresponseoptions-5.png "結果に基づく切り替え")

## <a name="respond-to-approval-requests-with-a-custom-response"></a>カスタム応答を使用して承認依頼に応答する

Microsoft Flow の承認センターに移動するか、アクション可能な電子メールにアクセスして、応答を選択します。

   ![依頼への応答](media/custom-response-options-in-approvals/customresponseoptions-5-2.png "依頼への応答")

