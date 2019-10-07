---
title: ビジネス プロセス フローのインスタント フロー ステップ
description: このプレビューでは、ユーザーはインスタント フローを実行して、反復的なタスクの自動化、ドキュメントの生成、承認の追跡などをビジネス プロセス フローのステップからオンデマンドで実行できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: beaaf2bd-1597-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 44f12f6f984855582d252a70896b5011a1992e22
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757226"
---
# <a name="instant-flows-in-business-process-flows-public-preview"></a>ビジネス プロセス フロー内のインスタント フロー (パブリック プレビュー)

ビジネス プロセス フローでは、ステージとステップの形式で作業を行う手順がガイドされます。 ステージはプロセス内での位置を示すのに対し、ステップは目的の結果に至るアクション項目です。 以前は、ステップは Common Data Service での情報の入力やアクションの実行にのみ使用できました。

このプレビューでは、**インスタント フロー**を実行して、反復的なタスクの自動化、ドキュメントの生成、承認の追跡などをビジネス プロセスのステージ内から実行できるようになりました。

![ランタイム](media/flow-step-in-a-business-process-2.jpg)

## <a name="add-an-instant-flow-as-a-step-in-a-business-process"></a>インスタント フローをビジネス プロセスのステップとして追加する

たとえば、プリンターを企業に販売していて、商談の成立を支援するためにリードから営業案件への営業プロセスを使用するとします。

![デザイナー](media/lead-to-opportunity-sales-process-1.jpg)

このプロセスの一環として、ビジネス プロセス フローの**提案**ステージで販売チームがまとめた提案を顧客と共有する前に、チーム リーダーがそれをレビューし、承認するようにします。

これを行うには、以下の手順に従います。

1.  チームから提案のレビューと承認を要求するソリューション対応のインスタント フローを構築します。
2.  このフローをリードから営業案件への営業プロセスのステップとして追加します。

## <a name="build-the-instant-flow"></a>インスタント フローを構築する

ビジネス プロセスのステップとして追加できるのは、[ソリューション対応のフロー](https://docs.microsoft.com/flow/overview-solution-flows)だけです。 例では、**既定のソリューション**にインスタント フローを作成します。 これを行うには、ナビゲーション メニューの**ソリューション**を選択し、ソリューションの一覧で**既定のソリューション**を選択して開き、**+ 新規**メニューからこのソリューション内にフローを作成します。

![ソリューション フロー](media/creating-a-solution-aware-flow.jpg)

このバージョンのプレビューでは、最初に Common Data Service コネクタから**レコードが選択されたとき**トリガーを追加します。 **環境**フィールドを**既定**に設定し、**エンティティ名**を**リードから営業案件への営業プロセス**に設定します。 最後に、テキスト入力フィールドを追加して、提案へのリンクをキャプチャします。

![トリガー](media/when-a-record-is-selected-trigger.jpg)

次に、ビジネス プロセス フロー インスタンスから情報を取得して、レビューのコンテキストを提供できます。 このバージョンのプレビューでは、**JSON の解析**アクションを追加することでこれを行います。 トリガーの動的な値の一覧から選択することで**コンテンツ** フィールドを**エンティティ**に設定し、次の内容を**スキーマ** フィールドに貼り付けます。

```json
{
  "type": "object",
    "properties": {
        "entity": {
            "type": "object",
            "properties": {
                "FlowsWorkflowLogId": {
                    "type": "string"
                },
                "BPFInstanceId": {
                    "type": "string"
                },
                "BPFInstanceEntityName": {
                    "type": "string"
                },
                "BPFDefinitionId": {
                    "type": "string"
                },
                "BPFDefinitionEntityName": {
                    "type": "string"
                },
                "StepId": {
                    "type": "string"
                },
                "BPFDefinitionName": {
                    "type": "string"
                },
                "BPFInstanceName": {
                    "type": "string"
                },
                "BPFFlowStageLocalizedName": {
                    "type": "string"
                },
                "BPFFlowStageEntityName": {
                    "type": "string"
                },
                "BPFFlowStageEntityCollectionName": {
                    "type": "string"
                },
                "BPFFlowStageEntityRecordId": {
                    "type": "string"
                },
                "BPFActiveStageId": {
                    "type": "string"
                },
                "BPFActiveStageEntityName": {
                    "type": "string"
                },
                "BPFActiveStageLocalizedName": {
                    "type": "string"
                }
            }
        }
    }
}
```

![エンティティを使用する](media/parse-json-to-get-bpf-details.jpg)

ビジネス プロセスの提案ステージは営業案件エンティティで定義されているため、関連する営業案件レコードから情報を取得して、承認要求に追加のコンテキストを提供しましょう。 これを行うには、Common Data Service コネクタの**レコードの取得**アクションを追加します。 **環境**を **(現在)** に、**エンティティ名**を**営業案件**に、**品目の識別子**を動的な値の一覧から選択した **BPFFlowStageEntityRecordID** に設定します。

![JSON の使用](media/get-opportunity-information-related-to-the-bpf.jpg)

データが得られたので、**承認の開始と待機 (V2)** アクション追加して承認プロセスを定義しましょう。 動的コンテンツ ピッカーを使用して、**レコードの取得**アクションからフィールドを追加して、営業案件に関する関連情報を追加します。 ビジネス プロセスが属するアクティブなステージのコンテキストをさらに提供するには、動的な値の一覧から **BPFActiveStageLocalizedName** フィールドを選択します。

![ローカライズされた情報](media/send-an-approval-containing-bpf-and-opportunity-information.jpg)

次に、承認の結果に基づいて要求者にメールを送信しましょう。 これを行うには、承認の**結果**フィールドに基づいて条件を追加し (動的な値の一覧から選択)、**電子メールの送信**アクションを**はいの場合**と**いいえの場合**の両方のパスに追加します。

![分岐](media/branch-on-approval-outcome.jpg)

最後に、フローを保存してオンにします。 まとめると、ビジネス プロセスおよび関連する営業案件レコードからの情報を使用して承認を要求し、その結果に基づいて動作するフローは以下のとおりです。

![概要](media/entire-flow.jpg)

## <a name="add-an-instant-flow-as-a-step-in-a-business-process"></a>インスタント フローをビジネス プロセスのステップとして追加する

まず、BPF デザイナーでリードから営業案件への営業プロセスを開きます。 BPF の提案ステージのステップとしてフローを追加するには、単純に**フロー ステップ (プレビュー)** コンポーネントを提案ステージにドラッグ アンド ドロップします。

![ステップをドラッグする](media/add-a-flow-step-to-a-bpf.jpg)

次に、**フローの選択**フィールドの検索アイコンを選択して、BPF に追加できるすべてのフローを一覧表示し、一覧から 1 つを選択します。 変更を保存するには、プロパティ ウィンドウの下部にある**適用**ボタンを選択します。

![ピック](media/pick-a-flow-to-run-from-the-flow-step.jpg)

最後に、**更新**ボタンを選択して、このビジネス プロセス フローとその新しいフロー ステップをユーザーが使用できるようにします。

これで完了です。 **フローの実行**ボタンを選択して、リードから営業案件への営業プロセスの**提案**ステージからフローを実行できるようになりました。

![最終](media/flow-step-in-a-business-process-2.jpg)
