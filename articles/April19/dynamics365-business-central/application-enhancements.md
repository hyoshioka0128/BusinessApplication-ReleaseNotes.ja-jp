---
title: アプリケーションの機能強化
description: アプリケーションの機能強化
author: bnielse
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: bnielse
audience: developer, end user, customizer
ms.openlocfilehash: 550755306fa9a20d9f2937a6b8ff50f1a3e15419
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210923"
---
# <a name="application-enhancements"></a>アプリケーションの機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

最もよく使用される部分のパフォーマンスに重点を置いて、引き続きアプリケーションを強化していきます。 熟練したユーザーは、フォーカス モードで最適化することによりデータの入力が速くなります。 同時に、ホーム ページの読み込み速度の最適化など、アプリケーション コードの最適化の結果として応答が速くなり、日常的に使用する主要なアプリケーション シナリオでのパフォーマンスが向上します。

既定の分析コードの拡張性、単体テスト実行中のメッセージ処理の改善、簡単に拡張できるような運用および計画エンジンのリファクタリングなど、ISV がアプリケーションの拡張を簡単に構築できるようにするための、アプリケーションの改良が続けられています。 [Business Central のアイデア サイト](https://aka.ms/bcideas)が引き続きアプリケーションの機能強化に関する情報源です。 このリリースには、以下の機能強化が含まれています。

## <a name="write-longer-names-and-descriptions"></a>入力できる名前と説明の文字数の増加
Business Central 全体のすべての**説明**および**名前**フィールドに、最大で 100 文字まで入力できるようになりました (以前は 50 文字)。 この変更は以下に適用されます。

- 顧客、仕入先、品目、取引先担当者、リソース カードなどのマスター データ カードの**名前**および **説明** フィールド。
- 販売注文書、発注書、請求書、見積もりなどの文書の**名前**および **説明** フィールド。
- 一般仕訳帳や品目仕訳帳などの仕訳帳の **説明** フィールド。
- 顧客、仕入先、品目などの元帳エントリの **説明** フィールド。

さらに、**測定単位の説明**フィールドに入力できる文字が最大 50 文字に増えました (以前は 10 文字)。

## <a name="use-physical-inventory-orders-to-better-structure-your-physical-inventory-counting"></a>現物在庫注文を使用して現物在庫棚卸をより適切に構成する
現物在庫棚卸は、すべての流通会社において 1 年に 1 回または 1 年に複数回発生する、中核的な在庫プロセスの 1 つです。 このプロセスの既存の機能は仕訳帳に基づいているため、大規模な在庫棚卸でプロセスを追跡して作業を分散させることは困難です。 **現物在庫注文**ページと**現物在庫記録**ページを使用すると生産性が向上し、既存の機能のギャップに対応できます。 新しい機能はドイツの一般的なローカル機能に基づいており、これは大規模な在庫棚卸が必要なほとんどすべての実装で広く使用されています。

## <a name="select-multiple-items-to-add-to-a-sales-or-purchase-document"></a>複数の品目を選択して販売ドキュメントまたは購買ドキュメントに追加する
品目リストで複数の品目を一度に選択して、販売ドキュメントまたは購買ドキュメントに追加できるようになりました。 いずれかの販売ドキュメントまたは購買ドキュメントで、**アイテムの選択**明細行アクションを選択します。  

ヒント: **販売および売掛金設定**ページの**既定の品目数量**チェック ボックスをオンにすると、販売ドキュメントに追加されるように選択されているすべての品目の販売明細行の**数量**フィールドが事前入力されます。

## <a name="use-a-sales-quote-validity-policy-to-control-when-sales-quotes-expire"></a>販売見積の有効性ポリシーを使用して売上見積の有効期限を制御する
**販売および売掛金設定**ページの**見積有効期限計算**フィールドで、販売見積の**見積有効期限**フィールドの計算に使用される日付式を設定できるようになりました。

ヒント: 有効期限が切れた販売見積を確実に削除するには、**期限切れの見積もりの削除**バッチ ジョブを実行します。 販売見積のアーカイブを有効にすると (**販売および売掛金設定**ページ)、削除された販売見積もアーカイブされるため、顧客から再び問い合わせがあったらアーカイブから復元できます。

## <a name="control-item-and-customer-creation-from-lookups-on-sales-documents"></a>販売ドキュメントのルックアップから品目と顧客の作成を制御する
販売明細に存在しない品目を入力すると、新しい品目カードを作成するか既存の品目を選択するように求められます。 多くの新しい品目をインポートするときなど、場合によっては、この確認によってプロセスがブロックされます。 したがって、確認をスキップできるようになりました。 **在庫設定**ページで、**品目作成の確認をスキップする**チェック ボックスをオンにします。

![新しい品目作成の確認をスキップする設定が表示されている在庫設定ページ](media/skip-prompt-create-item.png " 新しい品目作成の確認をスキップする設定が表示されている在庫設定ページ")

## <a name="copy-customer-dimensions-to-jobs-created-for-the-customer"></a>顧客に対して作成されたジョブに顧客の分析コードをコピーする
ジョブが作成されて、顧客がそのジョブに割り当てられると、顧客の既定の分析コード値がジョブにコピーされます。 つまり、ユーザーは必要な場合はジョブの分析コード値を変更するだけでよく、顧客の既存の分析コードがジョブに割り当てられるためレポートの一貫性が維持されます。

## <a name="copy-templates-used-to-create-customers-vendors-and-items"></a>顧客、仕入先、品目の作成に使用されるテンプレートをコピーする
新しいデータ テンプレートを作成するときに、既存のデータ テンプレートをコピーできるようになりました。 データ テンプレート (構成テンプレート) を使用すると、顧客、仕入先、品目、または取引先担当者のカードをすばやく作成できます。 既存のデータ テンプレートをコピーするには、**構成テンプレート ヘッダー** ページの**構成テンプレートのコピー** アクションを選択します。

![構成テンプレート ヘッダー ページの構成テンプレートのコピー アクション](media/copy-master-template.png "構成テンプレート ヘッダー ページの構成テンプレートのコピー アクションの図")

## <a name="merge-duplicate-customers-or-vendors"></a>重複する顧客または仕入先を統合する
顧客または仕入先の重複するレコードが誤って作成されたときは、そのような重複レコードを単一のレコードに統合できるようになりました。

## <a name="dynamically-set-shortcut-dimension-columns-in-lists-documents-and-journal-lines"></a>リスト、ドキュメント、仕訳帳明細行にショートカット分析コード列を動的に設定する
**総勘定元帳の設定**ページで設定した 2 つのグローバル分析コードのフィールドは、仕訳帳とドキュメントの明細行で常に使用できます。 その設定ページで設定したショートカット分析コードも、常に使用できるようになりました。 つまり、ショートカット分析コードの値も、**分析コード** ページを開かずに、仕訳帳とドキュメントの明細行に直接追加できます。

## <a name="bulk-import-item-pictures"></a>品目の画像を一括インポートする
一度に複数の品目の画像をインポートできるようになりました。 品目の番号に対応する名前で画像ファイルに名前を付け、それらを zip ファイルに圧縮してから、**品目の画像のインポート** ページを使用するだけです。 または、**品目の画像を設定する**アシスト セットアップ ガイドを使用することもできます。 まだ画像が設定されていない品目カードだけが更新されます。

![品目の画像のインポート ページの画像のインポート アクション](media/bulk-import-item-pictures.png "品目画像の一括インポートの図")

## <a name="view-payment-information-on-customer-and-vendor-statistics-factboxes"></a>顧客および仕入先の統計情報ボックスで支払情報を表示する
顧客および仕入先の統計情報ボックスで、支払と最終支払日に関する情報を表示できるようになりました。

![領収済支払と最終支払日に関する情報が含まれる情報ボックスが表示されている顧客リスト ページ](media/cash-receipt-last-payment.png "顧客統計情報ボックス内の領収済支払と最終支払日の図")

## <a name="look-up-swift-codes"></a>SWIFT コードを検索する
取り引きのある銀行の SWIFT コードのリストを保持し、銀行口座を使用するページでそれを使用することができます。 これにより、支払の正確な準備が可能になり、ユーザーは SWIFT コードを自由書式として入力するのではなく、定義済みの SWIFT コードのリストから選択することができます。

![SWIFT コード フィールドのルックアップが示されている銀行口座ページ](media/lookup-swift-codes.png " SWIFT コード ルックアップ テーブルの図")

## <a name="ensure-that-approval-users-are-set-up-to-run-approval-workflows"></a>承認ユーザーが承認ワークフローを実行するように設定されていることを確認する
ユーザーが承認ワークフローを開始する前に、ユーザーが**承認ユーザー** ページで設定されていることを確認するチェックが追加されています。

## <a name="configure-reports-for-warehouse-documents"></a>倉庫ドキュメント用のレポートを構成する
**集荷**、**プット アウェイ**、**出荷**などの倉庫ドキュメントについて、他の分野のドキュメントと同様に、どのレポートを印刷するかをレポート選択機能を使用して構成できるようになりました。

![倉庫管理で選択可能なレポートを示すレポート選択ページ](media/report-select-whse.png "レポート選択使用フィールドの図")

## <a name="view-vendor-invoice-number-on-purchase-invoice-and-credit-memo-lists"></a>仕入請求書およびクレジット メモのリストに仕入先請求書番号を表示する
**仕入先請求書番号**列が**仕入請求書**ページと**購買クレジット メモ** ページに表示されるようになりました。

## <a name="view-time-information-on-registers"></a>登録の時刻情報を表示する
**G/L登録**、**品目登録**、**ジョブ登録**などのさまざまな登録ページで、時刻情報を見ることができるようになりました。 これにより、日付だけでなく、トランザクションが作成された時刻も使用して、登録のトランザクションをより早く見つけることができます。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。

<!--
Describe the new feature, and then give an elevator pitch of the business value for it. Include high-value capabilities that light up something exciting for our customers. The feature should be something that a customer needs to plan for...definitely larger than a hotfix or bug fix.
If the feature has been designated as a key feature, complete the entire template. Otherwise, only complete the **Business value**, **Describe the feature**, and **Status** sections.
## Business value (Required)
Describe the top capabilities of the feature and and the business problems it solves.  
**Example**
End-of-day processing is a crucial element of retail operational workflow. This involves aggregation of raw transactions into meaningful business data to ensure that business and accounting rules are conformed to, before posting transactions as official business records. Improving the reliability and performance of this batch process and increasing the visibility of the processing for the administrator improves the user experience. Users can easily monitor the progress of the processing and see exactly what caused a validation failure. As a result, they can quickly resolve the issue and reliably retry the process without contacting Microsoft Support.
## Describe the feature (Required)
Describe how the feature works and the scenarios the feature enables. Include concrete examples and screenshots.
**Example**
New capabilities include improved statement posting performance by removing table deadlocks and optimizing batch processing. The introduction of a state model in the posting process aids in rollback and recovery, which eliminates data corruption and the need for manual intervention. Enhanced in-app diagnostics with detailed status, errors, and logs (including details of transactions included in the scope of the statement, transactions resulting in errors, and possible steps to correct issues) allow for easy troubleshooting.
<<screenshot goes here>>
### Who uses this feature (Required)
Indicate each persona impacted:  end user, admin, customizer, citizen developer, developer, business analyst, IT Pro
**Example**
This feature is intended for retail administrators. It works without any additional setup.
### License required
List the license(s) a customer must have to use the feature.
### Setup required (if any beyond standard product setup)
**Example**
This feature must be enabled in System parameters by an administrator.
### Quick steps (provide if feature is done enough)
**Example**
To get started with model‑driven apps, use designers to:
- Define your site map. Model your app's navigation, pulling in only the subset of information your users need. Take advantage of multiple levels of hierarchy and the ability to reference external resources.
- Add dashboards. Include model‑driven dashboards or embedded Power BI content within your app.
- Include entities and components. Add specific forms, views, dashboards, and charts for targeted entities to craft your user experience.
> [!div class="mx-imgBorder"]
> ![Photograph of a man using a Hololens to view augmented reality in Connected Field Service](/articles/Spring18/media/507e34a661a1b831d21ea3dadda9c6cf.jpg "Field Service IoT")
## Compliance, privacy and security considerations
List any compliance, privacy and security considerations that customers should plan for, including any steps or tools provided to help customers comply with GDPR.
## Status (Required)
### Development status
Pick one: Generally available, Public preview, In development
Notes: In development features are features that some teams may have previously included on the roadmap site. Anything in Private preview is considered to be In development.
#### Target timeframe
Enter the release, month, or month or later if dubious. (Release if committed to a release, Month if committed to a month, Month or later if dubious)
### Availability (current availability)
Cloud, On-premises, Government cloud
### Regional availability
List whether this feature is available globally or restricted to specific regions.
## Tell us what you think
Include an alias or link for feedback for the feature.
## We'd like to thank
Link to item from Ideas or User voice.
-->
