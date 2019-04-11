---
title: Power BI データフローの一般提供
description: Power BI データフローの一般提供
author: antonfrMSFT
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.reviewer: mihart
ms.openlocfilehash: 837c7f1bee2a74ba2e40ecc99b8a0a71ddf66609
ms.sourcegitcommit: e9ae36f4f7ff145fcdc3d3ebfb2080fc33083f69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2019
ms.locfileid: "849659"
---
# <a name="general-availability-of-power-bi-dataflows"></a>Power BI データフローの一般提供
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]


Power BI では、異なるソースのデータを統合し、それらをモデリング用に準備する作業を支援するために、データフローが導入されました。 アナリストは、使い慣れたセルフサービス ツールを使用してデータフローを簡単に作成できます。 データフローは、データ ソース接続、ETL (抽出、変換、読み込み) ロジック、更新スケジュールなどを定義して、ビッグデータの取り込み、変換、統合、エンリッチを行うために使用されます。 データは、Azure Data Lake Storage Gen2 で、Common Data Model に準拠したフォルダー内のエンティティとして保存されます。 データフローは、Power BI サービスを使用して、アプリ ワークスペース内で作成および管理されます。   

ユーザーはデータフローを使用して、サポートされているオンプレミスやクラウドベースのさまざまなデータ ソース (Dynamics 365、Salesforce、Azure SQL Database、Excel、SharePoint など) からデータを取り込むことができます。

またその後、データを既知の Common Data Model エンティティにマップし、既存のエンティティを変更および拡張して、ユーザー定義エンティティを作成することができます。 上級ユーザーは、コーディングを一切 (またはほとんど) 必要としないセルフサービスの組み込み Power Query 作成エクスペリエンスを通じて、完全にカスタマイズされたデータフローを作成することができます。これは、数百万人の Power BI Desktop ユーザーや Excel ユーザーが既に知っている Power Query と同様のエクスペリエンスです。  

データフローを作成したら、Power BI Desktop と Power BI サービスを使用して、Common Data Model のパワーを活用したデータセット、レポート、ダッシュボード、およびアプリを作成し、ビジネス活動に関する、より詳細な分析情報を取得することができます。 

データフローの更新スケジュールは、データセットと同様、データフローが作成されたワークスペースから直接管理されます。 

Power BI のデータフローには、一般的なデータ ソースへのコネクタが 40 以上含まれています (Excel、SQL Server、Oracle、Azure SQL Data Warehouse、Dynamics 365、Salesforce など)。 

[!include[feedback](../../includes/service-feedback.md)]