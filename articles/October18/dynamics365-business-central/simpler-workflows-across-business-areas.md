---
title: ビジネス エリア全体で簡素化されたワークフロー
description: さまざまな一般的なユーザー タスクがより簡単になりました。
author: bnielse
manager: edupont04
ms.date: 11/07/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.openlocfilehash: 40c21c5573c75922d7ce44b88a7c1cabac913560
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "285083"
---
# <a name="simpler-workflows-across-business-areas"></a>ビジネス エリア全体で簡素化されたワークフロー

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="simplified-payment-process"></a>簡略化された支払プロセス

お客様からのフィードバックに基づいて支払プロセスが改善され、顧客/仕入先/従業員帳エントリ ページへの検索可能なエイリアス (代替キーワード) の追加と、選択されたエントリを仕訳に転送する支払作成アクションの導入が行われました。 その結果、以下のことがより簡単になります。

* 未処理の仕入先請求書の表示。 支払うものの選択。 支払仕訳帳の自動記入。
* 未処理の顧客請求書の表示、支払受け取りの選択。 現金領収仕訳帳の自動記入。

### <a name="resources"></a>リソース
https://docs.microsoft.com/en-us/dynamics365/business-central/receivables-how-reconcile-customer-payments-list-unpaid-sales-documents#to-register-customer-payments-individually

## <a name="simplified-journals"></a>簡略化された仕訳帳

新しいユーザーからのフィードバックに基づいて、仕訳帳の 2 つの表示モードのサポートを追加することで、一般仕訳帳、仕入仕訳帳、売上仕訳帳のページのレイアウトを簡素化しました。

簡素化されたビュー:

* 列数の削減
* 一般仕訳帳: 借方/貸方記入フィールド
* 仕入仕訳帳: 購入に固有の勘定タイプのみを表示します
* 売上仕訳帳: 販売に固有の勘定タイプのみを表示します

簡略化されたビューにより、新しいユーザーでもデータ入力が容易になり、高度なシナリオを処理するために標準ビューに簡単に切り替えることができます。

## <a name="remind-user-to-release-purchasesales-order"></a>発注書/販売注文のリリースをユーザーに通知

発注書または販売注文のリリースをユーザーが忘れるのはよくあることであり、結果としてドキュメントを倉庫処理に使用できなくなります。 次の条件に基づいて、ドキュメントを閉じるときに、ユーザーに対する新しいリリースの警告が表示されます。

* 注文がまだリリースされていません。
* 数量フィールドが記入された行が存在します。
* 場所コード フィールドが行に入力されています。
* 場所には集荷/出荷または受入/プット アウェイが必要です。

## <a name="warning-about-unposted-document-is-enabled-for-invoices-only-by-default"></a>請求書に対してのみ有効な未転記ドキュメントに関する警告 (既定)

未転記ドキュメントに関する警告を調整しました。 未転記ドキュメントに関する警告のための高度なフィルタリングを追加し、既定のフィルターを "ドキュメントの種類" = 請求書に設定しました。つまり、既定では請求書のみが表示されます。 ユーザーはこれを変更して他のドキュメントの種類を含めることができます。

## <a name="improved-handling-of-situations-when-currency-exchange-rates-are-missing"></a>為替レートがない状況の処理の改善

利用統計情報に基づいて、ユーザーは新しい通貨を作成したときに為替レートの追加を忘れることが多く、ドキュメントで通貨を選択しようとするとエラーになることがわかりました。 ユーザーのエクスペリエンスを向上させるため、ユーザーを為替レート ページに誘導して為替レートの不足を修正できる確認ダイアログを追加しました。 また、新しい通貨コードを作成するときの為替レートの不足に関する注意を追加しました。

## <a name="copy-account-schedules"></a>会計スケジュールのコピー

ユーザーは、詳細な損益計算書や要約損益計算書など、同じ財務レポートのわずかに異なるバージョンを実行することがよくあります。 会計スケジュール ページにコピー アクションが追加され、ユーザーは会計スケジュールを最初から作成するのではなく、会計スケジュールをコピーして編集できるので、多くの時間を節約できます。 また、"システム" 会計スケジュールに関する警告がダイアログに変更されたため、ユーザーは "システム" 会計スケジュールを確認するかコピーを編集するかを決定することができます。

### <a name="resources"></a>リソース
https://docs.microsoft.com/en-us/dynamics365/business-central/bi-how-work-account-schedule

## <a name="check-avail-period-calc-setting-is-not-needed-for-basic-available-to-order-scenarios"></a>利用可能な期間の計算の確認の設定が基本的な注文可能シナリオには必要ない

ユーザーは、受注から在庫が少ないことを通知されたときに最短入荷日フィールドが更新されない理由を忘れることがよくあります。 会社情報ページで利用可能な期間の計算の確認をオプションにしたため、入庫予定があるときに最短入荷日フィールドが常に計算されます。

## <a name="eu-shipment-method-code-support-for-intrastat"></a>Intrastat に対する EU 出荷方法コードのサポート

EU Intrastat レポート定義には、EU ではオプションであるが、EU 内の一部の国では必須または条件付きで必須とされる多くのデータ要素が含まれています。 必須パラメータの強制は、ローカル バージョンでの一般的な変更でした。 したがって、これが必須または条件付き必須である国でローカライズする必要がないようにする新しい構成設定が追加されました。  

## <a name="address-format-consolidation"></a>住所形式の統一

住所の書式設定に関するさまざまな要件を分析して調整し、現在は次のようになっています。  

* 郡フィールドのキャプションを州/地域/郡などに動的に更新することができます ([国/地域] ページの新しい市区郡名のフィールド)
* 対応する国/地域コードの住所形式に応じて郡フィールドの表示を動的に変更できます
* あらかじめ定義された文字列に加えて、カスタム住所形式のオプションと、[国/地域] ページでオプションを作成するためのシンプルなビジュアル デザイナーが追加されました

## <a name="cancel-purchase-invoices-posted-from-order"></a>注文から転記された仕入請求書の取り消し

機能を販売部門と連携させ、ユーザーが間違った転記を修正できるよう、発注書に関連する転記済仕入請求書のキャンセル アクションが有効にされました。

## <a name="usca-users-can-update-tax-amount-on-general-journal-lines"></a>US/CA: ユーザーは一般仕訳帳明細行で税額を更新できる

機能を VAT に合わせて、ユーザーが税金差額を処理できるようにするため、US/CA ユーザーが一般仕訳帳明細行で税額を更新できるしました。

## <a name="items-purchased-for-specific-jobs-use-fixed-application"></a>特定の職務のために購入されたアイテムでの固定申請の使用

会計の観点から、在庫の変更を評価するには特定の申請を使用するのが好ましい方法です。 したがって、職務用にアイテムを直接購入したときは、原価計算方法が平均であっても、固定申請が使用されるようになりました。 また、その方が購買返品の処理がはるかに簡単です (それでも、マイナス調整に申請ワークシートをリンクする必要があります)

## <a name="drill-down-on-the-inventory-field-on-the-item-card"></a>アイテム カードの在庫フィールドでのドリルダウン

アイテム カードの "在庫 (手持ち)" フィールドに、在庫レベルの迅速な調整を行う AssistEdit と、取引履歴の簡単な調査のための DrillDown の両方が含まれるようになりました。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。
