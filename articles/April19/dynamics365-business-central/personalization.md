---
title: 個人用設定の改善
description: 自分のワークスペースをよりパーソナライズできます。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: end user
ms.openlocfilehash: ba7e40999e56a2bf03029f77660502ba82858ca2
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210801"
---
# <a name="personalization-enhancements"></a>個人用設定の改善
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

ユーザーが自分のワークスペースをさらにパーソナライズする手段を提供します。 ビジネス ユーザーはすべてのページのアクション バーをパーソナライズし、一般的なタスクの多くを効率的に実行するためにアクションの非表示や順番の変更を行うことができるようになりました。 さらに、ユーザーは任意のリストのピン留めなど、ロール センター上のナビゲーション バーをパーソナライズできます。

ユーザーは簡単入力およびドキュメントやカードなどのタスク ページ上のフィールドの重要度を微調整できるほか、リスト内の列のパーソナライズがより発見しやすく、アクセスしやすくなるように効率化されました。

Business Central 内のすべての個人用設定は、作業するデバイスやブラウザーに関係なく、継続的にそのユーザーに紐付けされます。

## <a name="optimize-for-data-input-with-quick-entry"></a>簡単入力によるデータ入力の最適化
簡単入力はデスクトップ ユーザーにとって生産性の高い機能であり、レコードの繰り返し入力に要する時間を短縮します。 フィールドで Enter キーを押すと、フォーカスが次の編集可能な簡単入力フィールドに移動します。自動入力されているフィールドはスキップされ、指定されているフィールドもスキップされることがあります。 ユーザーはすべてのページでフィールドの動作をパーソナライズし、そのユーザーや部署がレコードを入力するときの通常の動作を最適化できます。 個人用設定メニューを使用して、簡単入力のフィールドを追加または除外するだけです。

## <a name="optimize-readability-by-adjusting-field-importance"></a>フィールドの重要度を調整して読みやすくする
たまにしか必要とされないフィールドもあれば、ビジネス ユーザーが毎回参照する必要がある重要なフィールドもあります。 カード ページやドキュメント ページ上のフィールドを、**表示数を増やす**を選択するまで非表示にするか、クイック タブが折りたたまれたときにクイック タブの集計に表示するかどうかをパーソナライズできるようになりました。 フィールドを移動、表示、非表示にする機能と組み合わせることで、各ページの読みやすさを柔軟に最適化できます。 クイック タブの集計内のフィールドをクリックすると、クイック タブが展開されてそのフィールドにフォーカスされます。



<!--This screenshot shows the name Mike Nash. Is it from an approved list of fictitious names? It's recognizable as a former Msft exec.-->



> [!div class="mx-imgBorder"]
> ![そのグループが折りたたまれているときにフィールドが表示されるようにカスタマイズする個人用設定を適用中の販売見積のスクリーンショット](media/importance-personalization.PNG "フィールドの重要度をパーソナライズする")

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
