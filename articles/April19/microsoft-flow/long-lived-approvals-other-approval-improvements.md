---
title: 長期にわたる承認のサポートとその他の改善点
description: Microsoft Flow の承認には、30 日を超える承認のサポート、送信された承認を取り消す機能、受信トレイ内の承認要求の自動クリーンアップ、承認メールを制御する機能など、多くの改善点があります。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: 76e85cbf-1397-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 482b368a762f0fb1b288c96fae1963e4d52aef1b
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757245"
---
# <a name="long-running-approvals-and-other-improvements"></a>長期にわたる承認とその他の改善点



Microsoft Flow では、承認を要求し、それらの応答に基づいて動作するワークフローを簡単に自動化できます。 現在、[フローの実行は 30 日後にタイムアウトになり](https://docs.microsoft.com/flow/limits-and-config#run-duration-and-retention)、保留中のステップ (承認など) もタイムアウトになります。 これはほとんどの承認にとって問題ではありませんが、承認への応答に 30 日より長くかかる場合もあります。

承認が Common Data Service に保存されている場合、元のフロー実行がタイムアウトになった後でも、承認要求に対する応答に基づいて動作するフローを作成できるようになりました。これを行うには、2 つのフローを使用します。1 つは承認要求を送信するためのもので、もう 1 つは新しい**承認の作成 (v2)** に基づいて承認要求への応答に対してビジネス ロジックを実行するためのものです。

[無期限に実行される承認プロセスを作成する方法に関するステップバイステップの説明を入手してください](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Build-long-running-Approval-Flows/ba-p/279890)。

## <a name="cancel-sent-approvals"></a>送信済みの承認を取り消す

自分が送信した承認要求を取り消したい場合があります。 要求に間違いがあったか、要求が不要になった可能性があります。 どちらの場合でも、要求を送信した人は今すぐそれを**キャンセル**できます。

![[キャンセル] ボタン](media/cancelbuttoninpanel.png)

そのためには、承認を選択してから、サイド ペインで**承認を取り消し**を選択します。 いつでも**履歴**タブを選択して、取り消した承認要求を表示できます。

![履歴内でのキャンセル](media/cancelapprovals.png)

> [!NOTE]
> キャンセル機能は、**承認の作成 (v2)** アクションでのみ動作します。

## <a name="automatic-cleanup-of-approval-requests-in-your-inbox"></a>受信トレイ内の承認要求の自動クリーンアップ

Microsoft Flow の承認要求は受信トレイに直接送信できるため、迅速に応答できます。 ただし、メールは自分 (および他の承認者) の受信トレイに保存されるため、既に処理された承認に関するメールが残る可能性があります。

![更新された承認](media/approvalupdatedinemail.png)

現在、最新の電子メール クライアントでは、承認が完了したことを示すために電子メールが自動的に更新されます。 つまり、特定の承認が既に承認または拒否されているかどうかを気にする必要はありません。

## <a name="control-the-approval-email"></a>承認メールの管理

最後に、送信された承認メールを構成するフロー作成者がサポートされるようになりました。 **承認の作成 (v2)** アクションでは、**詳細オプションの表示**を選択した場合に、新しい**通知の有効化**オプションがあります。 組み込みのメール テンプレートが組織の要件を満たしていない場合は、これを**いいえ**に設定し、組み込みの通知メールを抑制できます。

組み込みのメールを無効にしたら、承認の詳細を使用し、組み込みの汎用アカウントや共有メールボックスの使用など、Microsoft Flow のメール送信方法のいずれかを使用して、承認に関する完全にカスタマイズされたメールを送信できます。


