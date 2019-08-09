---
title: Common Data Model とデータ統合の新機能と予定されている機能 (2019 年 4 月)
description: Common Data Model とデータ統合の新機能の概要
author: theresapalmer
ms.date: 03/07/2019
ms.assetid: 5f0ee2c1-29a8-4aa1-abd9-a0f4ab7018ad
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: deonhe
ms.openlocfilehash: e2cd3850bba5ea596dc8b40f18911ce92a3b37c2
ms.sourcegitcommit: 611196f6d269078b130fa2f6e4734db9fc3eb8de
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/05/2019
ms.locfileid: "1729689"
---
# <a name="whats-new-and-planned-for-common-data-model-and-data-integration"></a>Common Data Model とデータ統合の新機能と予定されている機能

このトピックでは、2019 年 4 月から 2019 年 9 月の間にリリースが計画されている機能の一覧を示します。 一部の機能のプレビューは 2019 年 2 月に開始されます。  

リリース ノートで説明されている機能は、まだリリースされていない場合があります。 提供タイムラインおよび予定されている機能は、変更される可能性、または出荷されない可能性があります ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。

**日付**列で月が使用されている場合、機能はその月に配信されます。 配布日は、その月の最初の日だけでなく、その月の任意の日にすることができます。

Dynamics 365 ビジネス アプリケーションを利用できる国または地域の一覧については、[ご利用いただける国と地域に関するガイド](https://aka.ms/dynamics_365_international_availability_deck)を参照してください。

2019 年 4 月リリースには、Power Query、コネクタ プラットフォーム、拡張性、Common Data Model (CDM)、二重書き込み (Common Data Service for Apps へのリンク)、CDS データ インテグレーター、データ エクスポート サービス、データ統合テンプレート、ゲートウェイの分野において、4 つのテーマがあります。

## <a name="power-query-desktop"></a>Power Query デスクトップ

| 分野                                           | 機能                                                               | リリースの種類         | 日付 |
|------------------------------------------------|-----------------------------------------------------------------------|----------------------|----------------------|
| [改善された新しいコネクタ](./power-query.md#high-enterprise-value-connectors-become-generally-available-for-power-bi-customers)                    | Microsoft では PDF、Essbase、IBM DB2 DirectQuery 用のコネクタに取り組んでいます。 <br/>| 一般提供 <br/> | <br/>2019 年 4 月           |
| [改善された新しいコネクタ](./power-query.md#high-enterprise-value-connectors-become-generally-available-for-power-bi-customers)                    | AtScale 用のコネクタを追加しています。 <br/>| パブリック プレビュー <br/> | <br/> 2019 年 4 月 |
| [改善された新しいデータ準備機能](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities) | お客様からのフィードバックに基づいて、Power Query デスクトップの "Smart Data Prep" 機能を改善し、6 か月のうちに一般提供を開始します。 <br/>| 一般提供 <br/>| <br>2019 年 4 月           |
| [接続プラットフォーム](./power-query.md#increased-support-for-developers-on-the-power-query-platform)                          | 開発者署名のカスタム コネクタへのサポートを追加します。                        | パブリック プレビュー       | 2019 年 4 月           |


## <a name="power-query-online"></a>Power Query オンライン

|分野          | 機能                   | リリースの種類         | 日付 |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [改善された新しいデータ取得機能](power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                             | Power Query オンラインにデータを入力またはコピーして貼り付けてテーブルを作成し、Power Query オンラインのファイル ソースに接続するときに OneDrive for Business を参照できるようにします。                                                                     | 一般提供 | 2019 年 4 月           |
| [SAP データ接続](./power-query.md#high-enterprise-value-connectors-become-generally-available-for-power-bi-customers) | 発行済みのレポートについて、PowerBI.com での SAP HANA や BW の変数の修正をサポートします。                                                                         | パブリック プレビュー       | 2019 年 6 月           |
| [新しいデータ コネクタ](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                                | Microsoft では、Amazon Redshift、Impala、Apache Spark、HDInsight Spark、HDInsight Hive Interactive Query、Vertica、Google BigQuery、Teradata、Informix、Sybase、MySQL、PostgreSQL 用の新しいデータ コネクタの作成に取り組んでいます。 | パブリック プレビュー       | 2019 年 4 月           |
| [基礎とコンプライアンス](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                          | 新しい地域や GCC での Power Query オンラインのサポート。                                                                                                           | パブリック プレビュー       | 2019 年 4 月           |
| [CDM スキーマへのエンティティのマッピング](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                     | Power Query オンライン データ統合を介して新しいエンティティを作成するときの CDS for Apps のデータ型のマッピングのサポートや、CDM スキーマにエンティティをマッピングするときのエンティティの参照エクスペリエンスの改善が含まれています。 | パブリック プレビュー       | 2019 年 4 月           |
| [Common Data Service for Apps](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                       | Power Query オンライン データ統合を介して新しいエンティティを作成するときのナチュラル キーを使用したルックアップのインポートのサポートが含まれています。                                             | パブリック プレビュー       | 2019 年 4 月           |

## <a name="common-data-model"></a>Common Data Model

| 機能                                                                                                                                                    | リリースの種類         | 日付 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [Common Data Model を使用して開発するための最新の資料とクイックスタート ガイド](common-data-model-cdm.md#updated-developer-and-consumer-documentation)                                          | 一般提供 | 2019 年 4 月           |
| [バージョン管理などの CDM スキーマ文書の拡張](common-data-model-cdm.md#cdm-schema-documents)                                                           | パブリック プレビュー       | 2019 年 4 月           |
| [CDM スキーマ文書、CDM フォルダー、model.json ファイル用の複数言語の SDK とツール](common-data-model-cdm.md#sdk-and-tooling)                                                                | パブリック プレビュー       | 2019 年 4 月           |
| [Finance、Operations、Marketing など人気のある Dynamics オファリングにおける主要なシナリオを対象とした新しい CDM エンティティの定義](common-data-model-cdm.md#new-entity-definitions) | パブリック プレビュー       | 2019 年 4 月           |
| [教育、非営利、小売などの産業ソリューション向けの初期 CDM エンティティ パック](common-data-model-cdm.md#new-entity-definitions)                                               | パブリック プレビュー       | 2019 年 4 月           |


## <a name="dual-write"></a>二重書き込み 

| 機能                                                                                                | リリースの種類   | 日付 |
|--------------------------------------------------------------------------------------------------------|----------------|----------------------|
| [Dynamics 365 for Finance and Operations ユーザーが Common Data Service のデータをネイティブに取得できるスムーズなエクスペリエンス](dual-write-link-common-data-service-apps.md) | パブリック プレビュー | 2019 年 5 月           |
| [二重書き込みを有効にする前に初期データを書き込む機能](dual-write-link-common-data-service-apps.md) | パブリック プレビュー | 2019 年 5 月           |
| [計画済みまたは計画外のメンテナンスに対する二重書き込みの回復性の確保](dual-write-link-common-data-service-apps.md) | パブリック プレビュー | 2019 年 5 月           |
| [二重書き込みにおける複数の法人のサポート](dual-write-link-common-data-service-apps.md) | パブリック プレビュー | 2019 年 7 月           |

## <a name="cds-data-integrator"></a>CDS データ インテグレーター

| 機能                                                                            | リリースの種類   | 日付 |
|------------------------------------------------------------------------------------|----------------|----------------------|
| [エラー処理とトラブルシューティングの機能強化](cds-data-integrator.md#enhancements-in-error-handling-and-troubleshooting)                             | パブリック プレビュー | 2019 年 4 月           |
| [テンプレートの更新をプロジェクトに反映する機能](cds-data-integrator.md#ability-to-propagate-template-updates-to-projects)   | パブリック プレビュー | 2019 年 6 月           |
| [有意義な分析情報とビューを提供するさらに豊富なダッシュボード](cds-data-integrator.md#richer-dashboard-with-meaningful-insights-and-views)                                  | パブリック プレビュー | 2019 年 4 月           |
| [パフォーマンス チューニングと統合書き込みパターンに関するガイダンス](cds-data-integrator.md#guidance-for-performance-tuning-and-integration-write-patterns)                    | パブリック プレビュー | 2019 年 4 月           |
| [政府機関クラウドへのコンプライアンス](cds-data-integrator.md#compliance-for-government-cloud) | パブリック プレビュー | 2019 年 6 月           |

## <a name="enable-common-data-service-entities-for-analytics"></a>分析用 Common Data Service エンティティの有効化

| 機能                                                                            | リリースの種類   | 日付 |
|------------------------------------------------------------------------------------|----------------|----------------------|
| [ファースト パーティの分析アプリを介して CDS データからインテリジェンスを抽出する](enable-common-data-service-entities-analytics.md#extract-intelligence-from-your-common-data-service-data-through-first-party-analytics-apps)                             | パブリック プレビュー | 2019 年 7 月           |
| [Azure Data Lake Storage を接続してデータを補給するためのスムーズなエクスペリエンス](enable-common-data-service-entities-analytics.md#frictionless-experience-to-connect-and-hydrate-your-azure-data-lake-storage)   | パブリック プレビュー | 2019 年 7 月           |
| [初期書き込みと増分書き込みのサポート](enable-common-data-service-entities-analytics.md#support-for-initial-and-incremental-writes)                                  | パブリック プレビュー | 2019 年 7 月           |
| [Azure Data Lake でのデータとメタデータの変更のサポート](enable-common-data-service-entities-analytics.md#support-for-data-and-metadata-changes-in-the-azure-data-lake)                    | パブリック プレビュー | 2019 年 7 月           |


## <a name="data-export-service"></a>データ エクスポート サービス

| 機能                                                                        | リリースの種類         | 日付 |
|--------------------------------------------------------------------------------|----------------------|----------------------|
| [Dynamics 365 for Sales (CRM) や Azure SQL からのレコードの数を表示する](data-export-service.md#show-count-and-trend-of-records-to-validate-and-notify-on-convergence-status)          | 一般提供 | 2019 年 8 月           |
| [Dynamics 365 for Sales (CRM) や Azure SQL からのレコードの傾向を表示する](data-export-service.md#show-count-and-trend-of-records-to-validate-and-notify-on-convergence-status) | 一般提供 | 2019 年 8 月           |
| [書き込み失敗に関する通知](data-export-service.md#reduce-latency-and-improve-performance)                          | 一般提供 | 2019 年 8 月           |
| [データの前のメタデータを優先することで書き込みの失敗を最小限に抑える](data-export-service.md#reduce-latency-and-improve-performance)                          | 一般提供 | 2019 年 8 月           |
| [削除処理の待ち時間を減らしてパフォーマンスを向上させる](data-export-service.md#reduce-latency-and-improve-performance)                          | 一般提供 | 2019 年 4 月           |
| [変更追跡でサポートされていないエンティティを表示する](data-export-service.md#reduce-latency-and-improve-performance)                          | 一般提供 | 2019 年 4 月           |


## <a name="data-integration-templates"></a>データ統合テンプレート

| 機能                                                                                                                                                                                          | リリースの種類         | 日付 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [新しいテンプレートと既存のテンプレートの更新 (Dynamics 365 for Finance and Operations、Field Service、Project Service、Dynamics 365 for Talent、Salesforce)](cds-data-integrator.md) | 一般提供 | 2019 年 4 月 |


## <a name="connector-platform-and-extensibility"></a>コネクタ プラットフォームと拡張性

| 機能                                                                                                    | リリースの種類         | 日付 |
|------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [PowerApps と Microsoft Flow 用の新しいコネクタと改善されたコネクタ](connector-platform-extensibility.md#new-and-enhanced-connectors-for-powerapps-and-microsoft-flow)                                   | パブリック プレビュー       | 2019 年 4 月           |
| [コネクタ開発用の豊富なドキュメントとガイド](connector-platform-extensibility.md#rich-documentation-and-guides-for-developing-connectors)                        | 一般提供 | 2019 年 4 月           |
| [PowerApps および Microsoft Flow 用のカスタム コネクタ CLI](connector-platform-extensibility.md#custom-connector-cli-for-powerapps-and-microsoft-flow)                   | パブリック プレビュー       | 2019 年 4 月           |
| [PowerApps および Microsoft Flow 用カスタム コネクタでのポリシー テンプレートのサポート](connector-platform-extensibility.md#support-for-policy-templates-in-custom-connectors-for-powerapps-and-microsoft-flow) | パブリック プレビュー       | 2019 年 4 月           |
| [PowerApps および Microsoft Flow 用のオープン ソース コネクタの開発](connector-platform-extensibility.md#open-source-connector-development-on-github-for-powerapps-and-microsoft-flow)    | 一般提供 | 2019 年 4 月           |
| [改善されたコネクタ認定プロセス](connector-platform-extensibility.md#improved-certification-process)                               | 一般提供 | 2019 年 4 月           |

## <a name="gateway"></a>ゲートウェイ

| 機能                                                                                                                      | リリースの種類         | 日付 |
|------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [OOTB 認定カスタム データ コネクタのサポート (拡張性サポート)](gateway.md#on-premises-data-gateway-supports-out-of-box-certified-data-connectors)                                 | パブリック プレビュー | 2019 年 4 月           |
| [オンプレミスのデータ ソース用の複数の資格情報](gateway.md#on-premises-data-gateway-supports-out-of-box-certified-data-connectors)                                                   | 一般提供 | 2019 年 6 月           |
| [テナント間のゲートウェイ管理](gateway.md#gateway-administration-across-a-tenant)                                                    | パブリック プレビュー | 2019 年 4 月           |
| [ゲートウェイ管理の改善](gateway.md#management-enhancements)                                                        | パブリック プレビュー | 2019 年 5 月           |
| [改善された信頼性、サポート性、診断](gateway.md#improved-reliability-supportability-and-diagnostics)                                | 一般提供 | 2019 年 4 月           |
| [SAP BW アプリケーションおよびメッセージ サーバー用 Power BI サービスでの (オンプレミス データ ゲートウェイ経由) SAP BW シングル サインオン (Kerberos)](gateway.md#sap-bw-single-sign-on-kerberos-in-power-bi-service-via-on-premises-data-gateway-for-sap-bw-application-and-message-server)  | パブリック プレビュー | 2019 年 4 月           |
| [Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)](gateway.md#sap-hana-single-sign-on-saml-in-power-bi-service-via-on-premises-data-gateway)                                            | パブリック プレビュー | 2019 年 4 月           |
