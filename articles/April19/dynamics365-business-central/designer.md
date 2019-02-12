---
title: デザイナーの機能強化
description: Visual Studio Code が付属するデザイナーで、ページ上のコンテンツをさらに調整します。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, customizer
ms.openlocfilehash: cf3322d0e48265804ee77fe1aa90dcc3027894c6
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210966"
---
# <a name="designer-enhancements-for-developers"></a>開発者向けデザイナーの機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

デザイナーは Visual Studio Code が付属しており、開発者がページ オブジェクトのビジュアル コンテンツをテストしてすばやく調整するための便利な方法です。 次のような最も要求の多い機能のいくつかを使用してデザイナーを強化しました。

- デザイナーでは、テスト環境に展開されたすべての拡張機能に対する依存関係が自動的に追加されなくなりました。 デザイナーを終了するとき、依存関係が取得されなかった拡張機能は暗黙のうちに除外されます。
- フィールドの重要度と簡単入力を微調整します。
- アクション バーのアクションとナビゲーション バーのリストの並べ替え、非表示化、再グループ化を行って調整します。
- 特定のフィルターと並べ替え順序を含む名前付きビューを作成することにより、リストのバリエーションを定義します。

## <a name="designing-quick-entry"></a>簡単入力の設計
簡単入力はデスクトップ ユーザーにとって生産性の高い機能であり、レコードの繰り返し入力に要する時間を短縮します。 フィールドで Enter キーを押すと、フォーカスは次の編集可能な簡単入力フィールドまたはセルに移動します。常に必要ではないフィールドまたは自動入力されるフィールドはスキップされます。 任意のフィールドのメニューを使用して、デザイナーの簡単入力パスのフィールドを含めたり除外したりすることができ、ページ全体で変更の結果をすぐにテストできます。 これは、Visual Studio Code で簡単入力を微調整するよりはるかに効率的です。

## <a name="designing-field-importance"></a>フィールドの重要度の設計
たまにしか必要とされないフィールドもあれば、ビジネス ユーザーが毎回参照する必要がある重要なフィールドもあります。 フィールドを移動、非表示化、追加する機能に加えて、デザイナーでは、開発者は視覚的でインタラクティブな方法でフィールドの重要度プロパティを微調整することもできるようになります。


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
