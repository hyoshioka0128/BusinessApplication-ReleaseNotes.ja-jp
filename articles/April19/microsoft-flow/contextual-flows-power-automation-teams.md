---
title: Microsoft Teams でのコンテキスト フローによる高度な自動化
description: Microsoft Flow は、すべてのユーザーが Microsoft Teams で高度な自動動作を使用できる手段になっています。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: f37358cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 8cad688b6ef1b775133d63b6bcad615121d591a9
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "404667"
---
# <a name="contextual-flows-power-automation-in-microsoft-teams"></a>Microsoft Teams でのコンテキスト フローによる高度な自動化
[!include[microsoft-flow banner](../includes/microsoft-flow.md)]




Microsoft Flow は、すべてのユーザーが Microsoft Teams で高度な自動動作を使用できる手段になっています。 構想されているのは、Outlook の仕訳ルールのようなワールド クラスのエクスペリエンスを Microsoft Teams に提供することです。 つまり、ユーザーが次のことをできるようにします。

- チームでの重要な更新に関する通知を外部のサービスから受け取り、それらに基づいて行動します。
- Teams のエクスペリエンスに直接組み込まれたコマンドとアクションを通じてサービスと対話します。
- Teams のイベントに基づいてワークフローを設定することで、チームワークを自動化します。

これらの新機能は、Teams *アプリ* (専用の [フロー] タブなど) からだけでなく、メッセージやファイルなどのエンティティからメニュー項目を介してコンテキストに応じて有効にすることもできます。

![Microsoft Teams の統合ポイント](./media/TeamsIntegrationPoints-1.png "Microsoft Teams の統合ポイント")

セットアップが簡単になっただけでなく、Microsoft Flow では、適応型カードによるチャネル通知、個人通知、さらには Team イベントやチャネル イベントのワークフローを作成する機能もサポートされるようになりました。 シナリオの例をいくつか示します。

- プロジェクト リーダーは、チームのプロジェクトについてだれかが話したときに通知を受けることができます。
- チーム管理者は、新しいユーザーがチームに参加したときに、オンボーディング リソースへのリンクが含まれるウェルカム メッセージを送信することができます。