---
title: 分析用 Common Data Service エンティティの有効化
description: 分析用 Common Data Service エンティティの有効化
author: sabinn-msft
ms.date: 04/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: e8f3af8998d794319b92e11e46b9e7004fcdf80c
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225148"
---
# <a name="enable-common-data-service-entities-for-analytics"></a>分析用 Common Data Service エンティティの有効化
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]



Microsoft は、顧客が Common Data Service 内のデータに基づいて包括的な分析情報を取得し、ビジネス アクションを推進できるようにすることをビジョンとして掲げています。 これを達成するために、分析を実行してデータからインテリジェンスを抽出するには、データを Azure Data Lake にプッシュする必要があります。これにより、Azure Storage の基本的な可用性、セキュリティ、持続性の機能と共に、クラス最高の分析パフォーマンスを提供できます。 この取り組みによって、Common Data Service から Azure Data Lake にデータをプッシュしてファースト パーティの分析アプリで豊富な分析機能を実行できるようになります。 さらに、顧客が既存の Azure Data Lake を自分の Common Data Service 環境にリンクできる、自分のレイクの持ち込み/自分のストレージの持ち込み機能もサポートされます。 これにより顧客は、自分の Common Data Service データに対して豊富な分析機能を実行できます。

![Common Data Service から ADLS へ](media/enable-common-data-service-entities-analytics.jpg "Common Data Service から ADLS への図")

## <a name="extract-intelligence-from-your-common-data-service-data-through-first-party-analytics-apps"></a>ファースト パーティの分析アプリを介して Common Data Service データからインテリジェンスを抽出する

顧客との完全な対話履歴に関心のある営業担当者や、自分のチームに関する分析情報を必要としている営業マネージャー、ケースの傾向に関する分析情報を活用してニーズを予測しパフォーマンスを向上したいと考えている顧客サービス マネージャーは、Dynamics 365 Customer Insights、Sales Insights、Customer Service Insights などのファースト パーティの分析アプリを使用して目的を達成できます。  この機能は、Azure Data Lake に Common Data Service のデータを補給して、ファースト パーティの分析アプリを強化することによって豊富な分析情報を利用できるようにします。

## <a name="frictionless-experience-to-connect-and-hydrate-your-azure-data-lake-storage"></a>Azure Data Lake Storage を接続してデータを補給するためのスムーズなエクスペリエンス 

この機能では、簡単に自分の Azure Data Lake を持ち込み (または作成して)、自分の Common Data Service 環境にリンクして、レイクにデータを補給する Common Data Service エンティティを選択することができます。 これにより、Power BI やその他の強力な分析および機械学習サービスを使用して充実したレポートを作成できるようになります。  

## <a name="support-for-initial-and-incremental-writes"></a>初期書き込みと増分書き込みのサポート  

この機能を使用すると、既存および増分の Common Data Service データをレイクに書き込むことができます。 顧客は更新のたびにデータ全体をコピーしたくないと考えており、増分データ更新に関するこの重要な要請をサポートすることはきわめて重要です。  

## <a name="support-for-data-and-metadata-changes-in-the-azure-data-lake"></a>Azure Data Lake でのデータとメタデータの変更のサポート 

あらゆるビジネスにおいて、データは絶えず変化しています。そこで Microsoft では、CRUD (作成、読み取り、更新、削除) 操作のサポートと共に、データとメタデータの変更を Azure Data Lake に反映するための完全なサポートを提供します。 
