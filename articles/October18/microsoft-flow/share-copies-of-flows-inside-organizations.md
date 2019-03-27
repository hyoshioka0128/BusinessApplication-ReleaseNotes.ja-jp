---
title: 組織内でフローのコピーを共有
description: フローのコピーを共有することによってフロー テンプレートを配布します。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: 584a5018-e70e-e911-a98c-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ecc270b829a27b6e7c644beda9a045be65d9dbfa
ms.sourcegitcommit: 94bf29c750d9915eff328352bb0cbc819a09e203
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "403841"
---
# <a name="share-copies-of-flows-inside-organizations-public-preview"></a>組織内でフローのコピーを共有 (パブリック プレビュー)


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

自分のフローのコピーを組織内の他のユーザーが作成できるようにする場合は、新しい**コピーの送信**機能を使用できます。 フローのコピーを送信するには、まず、そのフローに個人情報が含まれていないことを確認する必要があります。 たとえば、自分の電子メール アドレス宛てに何かを送信するフローは、他のユーザーにコピーとして送信するのに適していない可能性があります。

フローのコピーを送信すると、受信者が元のフローのコピーを自分で作成できるようになります。 これらのコピーは受信者のつながりを使用し、受信者がフロー作成後に変更を加えることを希望する場合は、受信者によって所有されることになります。

フローのコピーを送信するための主なエントリ ポイントは 2 つあります。 1 つ目は、フローの一覧からです。

![フローの一覧の "コピーの送信" オプション](media/send_a_copy_from_flow_list.png)

2 つ目は、フローのプロパティ ページからです。

![フローのプロパティ ページの "コピーの送信" オプション](media/send_a_copy_from_flow_properties.png)

フローをコピーとして送信する前に、最後にフローを更新してから少なくとも 1 回はフローを正常に実行している必要があります。 これは、フローが送信先のあらゆるユーザーに対して機能することを確認するために役立ちます。 また、フローをコピーとして共有した後はコピーを取り消すことができないため、送信する前にフローから個人情報を削除することが重要です。

だれかがフローのコピーを使用するとき、コピー作成時にその構成を調整する方法はありません。コピーはそのまま作成されますが、その人物のつながりが使用されます。 そのため、受信者のつながりに基づいてすべてのデータを動的に取得するようにフローを設計することをお勧めします。 たとえば、自分や受信者の電子メール アドレスをフローにハード コーディングするのではなく、**[自分のプロファイルを取得](https://docs.microsoft.com/connectors/office365users/#get-my-profile--v2-)** のようなアクションを使用できます。

**コピーの送信**を選択すると、受信者だけでなくテンプレートのタイトルと説明をカスタマイズするように求められます。 組織内のユーザーとセキュリティ グループの任意の組み合わせを受信者にすることができます。 フロー送信先のユーザーだけが、フローにアクセスできます。

!["コピーの送信" パネルの入力](media/send_a_copy_panel.png)

受信者は、送信されたフローの自分用のコピーを作成するように促す電子メールを受信します。

!["コピーの送信" で受信されたメール](media/send_a_copy_email.png)

さらに、自分と共有されたテンプレートを**共有アイテム** タブで確認できます。

!["共有アイテム" テンプレート ギャラリー](media/send_a_copy_shared_with_me.png)