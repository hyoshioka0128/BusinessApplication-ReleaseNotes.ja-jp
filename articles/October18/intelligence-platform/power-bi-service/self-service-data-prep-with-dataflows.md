---
title: データフローでのセルフサービス データの準備
description: データフローを使用すると、複数のビジネス アプリケーションやデータ ソースにまたがったデータからビジネス分析を開発する際の時間、複雑さ、およびコストを削減できます。
author: adiregev
manager: PaBenja
ms.date: 11/09/2018
ms.assetid: ''
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: adiregev
audience: ''
ms.openlocfilehash: acea8e2112f4d29bfdfb279e6e61893488a84865
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "284977"
---
# <a name="self-service-data-prep-with-dataflows-public-preview"></a>データフローでのセルフサービス データの準備 (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Power BI では、異なるソースのデータを統合し、それらをモデリング用に準備する作業を支援するために、データフローが導入されました。 アナリストは、使い慣れたセルフサービス ツールを使用して、データフローを簡単に作成できます。 データフローは、データ ソース接続、ETL ロジック、更新スケジュールなどを定義して、ビッグデータの取り込み、変換、統合、エンリッチを行うために使用されます。 データは、Azure Data Lake Storage Gen2 で、Common Data Model に準拠したフォルダー内のエンティティとして保存されます。 データフローは、Power BI サービスを使用して、アプリ ワークスペース内で作成および管理されます。   

ユーザーはデータフローを使用して、サポートされているオンプレミスやクラウドベースのさまざまなデータ ソース (Dynamics 365、Salesforce、Azure SQL Database、Excel、SharePoint など) からデータを取り込むことができます。

またその後、データを既知の Common Data Model エンティティにマップし、既存のエンティティを変更および拡張して、ユーザー定義エンティティを作成することができます。 上級ユーザーは、コーディングを一切 (またはほとんど) 必要としないセルフサービスの組み込み Power Query 作成エクスペリエンスを通じて、完全にカスタマイズされたデータフローを作成することができます。これは、数百万人の Power BI Desktop ユーザーや Excel ユーザーが既に知っている Power Query と同様のエクスペリエンスです。  

データフローを作成したら、Power BI Desktop と Power BI サービスを使用して、Common Data Model のパワーを活用したデータセット、レポート、ダッシュボード、およびアプリを作成し、ビジネス活動に関する、より詳細な分析情報を取得することができます。 

データフローの更新スケジュールは、データセットと同様、データフローが作成されたワークスペースから直接管理されます。 

プレビューには、一般的なデータ ソースへのコネクタが 20 以上含まれています (Excel、SQL Server、Oracle、Azure SQL Data Warehouse、Dynamics 365、Salesforce など)。 

## <a name="resources"></a>リソース
[データフローでの Power BI データの準備](https://docs.microsoft.com/en-us/power-bi/service-dataflows-overview)
