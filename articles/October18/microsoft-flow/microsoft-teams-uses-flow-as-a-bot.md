---
title: Teams の Microsoft Flow タブ
description: チーム チャネルのユーザーは、チャネルにコマンドを入力してやり取りするだけで、新しいタブやテキストを使用して対話できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/21/2019
ms.assetid: 450627f1-ce73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 473444550d8df2c9f3f6bc3b328e121bd120ce3f
ms.sourcegitcommit: 1de869f4ccb74ccc9b9cd26817e3d5c30734c3c3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2019
ms.locfileid: "288955"
---
# <a name="microsoft-flow-tab-in-teams"></a>Teams の Microsoft Flow タブ




当社は最近、_ユーザー_がフローを作成および管理し、フロー ボットからフローを起動できる[個人用 Teams アプリ](https://flow.microsoft.com/blog/microsoft-flow-in-microsoft-teams/)をリリースしました。これらの操作はすべて Teams 内で行います。 これらの機能を [フロー] タブで_チーム全員_に拡張しました。コントソの戦略・計画チームのメンバーになったつもりで考えてみてください。 "仕様" という単語を含むドキュメントが SharePoint にアップロードされるたびに、チームに通知する必要があります。 Teams での Microsoft Flow の統合により、それを正確に行うフローをすばやく作成し、すぐにチームと共有して、必要に応じて他のユーザーが編集できるようにすることができます。 

## <a name="flow-tab-in-teams"></a>Teams の [フロー] タブ

まず、Teams で戦略・計画チームに移動し、[フロー] タブを [全般] チャネルに追加します。 そのためには、タブの追加 (＋) ボタンを選択します。

![タブの追加](media/flow-tab-teams-1.png "タブの追加")

次に、**すべてのタブ** カテゴリから**フロー**を選択します。 **インストール**に続いて**保存**を選択して、インストールを終了します。 プロンプトが表示されたら、サインインします。

![すべてのタブから選択](media/flow-tab-teams-2.png "すべてのタブから選択")

## <a name="create-a-flow"></a>フローの作成

Microsoft Flow にサインインしたら、空白からフローを作成するかテンプレートから選ぶかを選択します。 Microsoft Flow では、チームを SharePoint、Microsoft Forms、Twitter、UserVoice などのさまざまなサービスに接続できます。 **テンプレートからの作成**を選択します。  

![テンプレートからの作成](media/flow-tab-teams-3.png "テンプレートからの作成")

**特定のドキュメントがアップロードされたらチームに通知**というラベルの付いたテンプレートを選択します。

![テンプレートの選択](media/flow-tab-teams-4.png "テンプレートの選択")

プロンプトが表示されたら、接続を確認し、**続行**を選択します。

![続行を選択](media/flow-tab-teams-5.png "続行を選択")

Microsoft Flow デザイナーで、Teams アクションである [チームに通知] に現在のチームとチャネルに事前に入力されています。

![「はい」の分岐アクション設定の設定](media/flow-tab-teams-6.png "「はい」の分岐アクション設定の設定")

"ファイルが作成されたとき (プロパティのみ)" のトリガーの [サイト アドレス] と [ライブラリ名] を選択します。 この例では、戦略・計画サイトとドキュメント ライブラリを選択します。 条件では、ファイル名に "仕様" が含まれている場合にチームに通知します。

![フロー条件](media/flow-tab-teams-6_a.png "フロー条件")

最後に、[チームに通知] アクションで、メッセージを次のようにカスタマイズします。

![メッセージの内容](media/flow-tab-teams-7.png "メッセージの内容")

**保存**を選択してフローを保存してから閉じます。 フローが保存されると、自動的にチームと共有され、チームのメンバーはだれでもフローを編集できます。

![フローの一覧](media/flow-tab-teams-7_a.png "フローの一覧")

![チームの所有権](media/flow-tab-teams-8.png "チームの所有権")

"仕様" という単語を含む新しいドキュメントがアップロードされると、ファイルへのリンクおよびフローに設定したテキストと共に、新しいメッセージがチャネルに投稿されます。   

![投稿されたメッセージ](media/flow-tab-teams-9.png "投稿されたメッセージ")

## <a name="use-the-bot-to-launch-flows"></a>ボットを使用してフローを起動する

個人用アプリと同じように、[フロー] タブには手動フローやスケジュールに基づいてトリガーされるフローを実行できるボットが含まれています。 毎週実行され、チームにメッセージを投稿して今後の技術デモを全員に知らせるフローがあるとしましょう。 [このブログ投稿](https://flow.microsoft.com/blog/email-digest-date-manipulations/)で、そのようなフローの作成方法を確認できます。 フロー ボットを使用すると、このフローをすぐに実行できます。

[会話] タブで、「\@Flow」に続けてコマンド `List flows` を入力します。 フローの一覧に戻ったら、コマンド `Run flow` に続けて実行するフローのインデックスを入力します。 たとえば、`Run flow 1` などとします。

![ボット メッセージ](media/flow-tab-teams-10.png "ボット メッセージ")
