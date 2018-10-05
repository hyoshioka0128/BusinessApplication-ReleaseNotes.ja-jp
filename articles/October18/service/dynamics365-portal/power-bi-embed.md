---
title: "Dynamics 365 Portal への Power BI ビジュアル化の埋め込み"
description: "ポータルのページに Power BI のビジュアル化を埋め込みます。"
author: neerajnandwana-ms
manager: ramalingamkrishnan
ms.date: 09/06/2018
ms.assetid: e2a02c53-de53-4890-9a21-73cf97965494
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b2cbc7080525e92e2e62f653eaaccb0e6c24b33d
ms.openlocfilehash: 68dd102a69ff83d447c451084a755c4c7fe7447e
ms.contentlocale: ja-jp
ms.lasthandoff: 09/11/2018

---
# <a name="embed-power-bi-visualizations"></a>Power BI のビジュアル化の埋め込み

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

[Power BI](https://powerbi.microsoft.com) は、シンプルな対話型のビジュアル化によって分析情報を提供する最も優れたツールの 1 つです。 ポータル ユーザーに対して有効にする Power BI の機能とユース ケースの検討において、この機能は現在も最も投票数の多いアイデアの 1 つです。

現在、ポータルへの安全な Power BI レポートの埋め込みは複雑な作業です。 これには、セキュリティ トークンを処理および管理するためのカスタム ロジックの作成が含まれます。 この機能により、Dynamics 365 Portal と Power BI の統合が合理化されます。 

## <a name="enable-power-bi"></a>Power BI の有効化

管理者は、ポータルに対して Power BI を構成し、有効にすることができます。 これには、適切な Power BI ライセンスが必要です。

>[!div class="mx-imgBorder"]
>![ポータル管理センターから Power BI 統合を有効にする](media/PBI_Admin_Center_EnablePBI.png "ポータル管理センターから Power BI 統合を有効にする")

## <a name="add-power-bi-visualization"></a>Power BI ビジュアル化の追加

カスタマイズ担当者は、Liquid コードを使用して Power BI ダッシュボードとレポートをページ内に埋め込むことができます。 Power BI コンテンツを埋め込むときに、カスタマイズ担当者は[フィルター パラメーター](https://docs.microsoft.com/power-bi/service-url-filters)を使用してパーソナライズされたビューを作成できます。 Liquid の powerbi タグにより、Power BI ダッシュボードとレポートをページ内に埋め込みます。

```
{% powerbi path:"https://app.powerbi.com/view?r=eyJrIjoiNjMzZTY1ZTItMDE2My00NGY5LWIwYmItNjUwMGY5NzEY3IiwidCI6IjU3NGMzZTU2LTQ5MjQtNDAwNC1hZDFhLWQ4NDI3ZTdkYjI0MSiOjZ9" %}
```

### <a name="parameters"></a>パラメーター

powerbi タグは、次のパラメーターを受け取ります。

**path**

Power BI レポートまたはダッシュボードのパス。 Power BI レポートまたはダッシュボードが安全である場合は、認証の種類を指定する必要があります。

**認証の種類**

Power BI レポートまたはダッシュボードに必要な認証の種類。 このパラメーターの有効な値は **Anonymous** または **AAD** です。 既定値は **Anonymous** です。

セキュリティ保護された Power BI レポートまたはダッシュボードを追加する場合は、Dynamics 365 Portal Azure Active Directory の認証済みユーザーと共有されていることを確認します。 

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/reports/00000000-0000-0000-0000-000000000001/ReportSectionc01" %}
```

**tileid**

ダッシュボードの指定されたタイルを表示します。 タイルの ID を指定する必要があります。

```
{% powerbi authentication_type:"AAD" path:"https://app.powerbi.com/groups/00000000-0000-0000-0000-000000000000/dashboards/00000000-0000-0000-0000-000000000001" tileid:"0000005" %}
```




<!--
### Who uses this feature
This feature is intended for end users and customizers. A customizer must configure Power BI in a portal to use this feature.
### License required
For Power BI configuration and content authoring, customers or administrators will need an appropriate Power BI license.
### Setup required
This feature must be configured and enabled in a portal by an administrator. 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

## <a name="wed-like-to-thank"></a>謝辞

優先順位付けに役立つ投票とコメントを[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=76fe3c62-62ea-e611-80c1-00155d460d59)にお送りいただき、ありがとうございました。

