---
title: 標準 Web API
description: Business Central では、統合を容易にするために Web API を公開しています
author: henrikwh
ms.reviewer: edupont
ms.date: 01/21/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.author: henrikwh
audience: developer, customizer
ms.openlocfilehash: 2fe3f86669a26b270b980bc556dfeb63506bf64f
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225199"
---
# <a name="standard-web-api"></a>標準 Web API 
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]
標準 Web API は、ベータ版から移行される予定です。 これまで、この API はベータ版として提供され、パートナー コミュニティからのフィードバックに基づいて進化を続けてきました。 今リリースでは、API の最終的な機能改善といくつかの新しいエンティティが、バージョン 1.0 として統合されます。  

## <a name="developer-improvements"></a>開発者にとっての改善点

- カスタム名前空間を使用した AL での API 開発
- オープン API 仕様 3.x

## <a name="changes-from-beta-to-v10-apis"></a>ベータから v1.0 API に向けての変更点

- 深いエンティティ入れ子
- 単純キー
- 従業員タイムシート登録 API  

## <a name="business-value"></a>ビジネス バリュー
標準 Web API では 48 を超えるエンティティを公開しているため、Business Central への疎結合統合が可能です。 この Web API を使用すれば、Business Central 内で開発や展開を行う必要はありません。 設計の主な目的は、Business Central に関する深い知識がなくても使用できる API を提供することと、Business Central の複数のローカライズや展開を標準化された方法で統合するための、固定バージョンのコントラクトを提供することです。  

標準 API は、Business Central オンラインで既定で有効になりますが、オンプレミス展開でも有効にできます。

### <a name="developing-apis-in-al"></a>AL での API 開発
拡張機能では API を公開することができます。これにより、API プラットフォームを Business Central 内で利用することができます。 つまり、カスタム API で標準 API と同じ機能を利用できるということです。 これには、WebHooks、OAS 3.0、OData v4、およびバージョン管理のサポートが含まれます。  

API の開発では、*カスタム名前空間*が活用されます。これは、API をグループに分割するための手段です。 これを使用するには、APIPublisher、APIGroup、および APIVersion の各プロパティを API で指定する必要があります。 

```
page 50100 ApiPageExpenses
{
    PageType = API;
    Caption = 'apiPageName';
    APIPublisher = 'contoso';
    APIGroup = 'expenses';
    APIVersion = 'v2.0';
    EntityName = 'Receipt';
    EntitySetName = 'Receipts';
    SourceTable = ContosoReceipt;
    InsertAllowed = true;
    DeleteAllowed = true;
    layout
    {
        area(Content)
```

上記の例の場合、展開時にルーティング テーブルが更新され、それにより、指定された名前空間内のエンドポイントが公開されます。

```
GET https://api.businesscentral.dynamics.com/v1.0/api/contoso/expenses/v2.0/companies(7d0b2f2d-150e-4596-b064-e66f3491811c)/Receipts
```

### <a name="open-api-specification-3x"></a>オープン API 仕様 3.x 
Business Central では、OAS 3.0 の生成がサポートされる予定です。 OAS は、ほとんどのプログラミング言語用に SDK を生成できる、共通のメタデータ フォーマットを提供するものです。

2019 年 4 月以降は、Business Central API ドキュメントも OAS を介して生成されるようになります。   

### <a name="deeper-entity-nesting"></a>より深いエンティティ入れ子
パーツ ページの制限により、2 レベルより深いエンティティ構造を指定することはできません。 例:  

```
/journal({id})/journalLine(id)
```

この例では、当該の制限により、**journalLines** への**添付ファイル**が使いづらくなっています。リソースを直接アドレス指定する方法がないためです。

```
/journal({id})/journalLine(id)/attachment(id)
```

現在のベータ版実装では、**添付ファイル**はルートに配置されます。  

### <a name="simple-keys"></a>単純キー
マルチパート/複合キーを使用すると、API が使いにくくなります。リクエストを構成するのに、複数のパラメーターが必要になる場合があるためです。 2019 年 4 月リリースでは、API で単純キーが使用されるようになります。


### <a name="employee-timesheet-registration-api"></a>従業員タイムシート登録 API
従業員タイムシートが、標準 API を通じて有効化される予定です。 現在、Business Central 内のタイムシートでは、従業員の時間登録はリソースに対してサポートされています。 現在の実装では、リソースは複数のマシンと人を表すことができます。 2019 年 4 月リリースでは、従業員タイムシート登録を使用する場合、時間を登録するリソースが 1 人の従業員を指すようにしなければならなくなります。 

## <a name="personas"></a>ペルソナ
エンド ユーザー、管理者、カスタマイザー、一般開発者、開発者

## <a name="status"></a>状態
現在、すべての API はベータ版です。 2019 年 4 月リリースでは、v1.0 API が公開される予定です (上記の機能改善を含む)。 

## <a name="availability"></a>利用可能性

SaaS、オンプレミス

## <a name="tell-us-what-you-think"></a>フィードバック

Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。

