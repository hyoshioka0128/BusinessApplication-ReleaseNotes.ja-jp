---
title: "データ統合の新機能"
description: "Microsoft ビジネス アプリケーションの 2018 年 10 月のリリースで提供されるデータ統合の新機能の概要をご覧ください。"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 7326561e-192f-4897-ad72-af64d29849da
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4453c91b5ad512310b32458ebe292456976c1268
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="summary-of-whats-new-in-data-integration"></a>データ統合の新機能の概要

[!include[banner](../../includes/banner.md)]

このプラットフォーム機能に対する改善によって、Microsoft やサード パーティのさまざまなアプリケーションとサービスへの接続が拡充されます。 次の領域で重要なイノベーションが行われています。
-   [Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合](1-power-query.md)
-   [Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化](2-cdm.md)
-   [強化され、より統合されたコネクターと開発者エコシステム](3-connector-ecosystem.md)
-   [データ統合の強化された管理者機能](4-data-integration-admin.md)
-   [オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続](5-data-gateway.md)


|**製品** | **機能**| **リリースの種類** | **目標リリース月**|
|---------|-----------------------------------|---------|---------|
| Power BI | [機能強化された新しいコネクタ](1-power-query.md#enterprise-grade-connectors)<ul><li>OData v4 プロトコルのフル サポート</li><li>HDInsight Spark Connector の一般提供</li><li>Google BigQuery Connector の一般提供</li><li>SAP HANA</li><ul><li>Power BI サービス (ゲートウェイ経由) における SSL 認定検証のサポート</li><li>SAML ベースのシングル サインオン (Power BI Desktop およびゲートウェイを含む)</li></ul><li>SAP BW</li><ul><li>パフォーマンスの機能強化</li><li>追加の DirectQuery メタデータ (プロパティ、通貨、測定単位)</li><li>認証</li></ul><li>Power BI Desktop + サービス (ゲートウェイ経由) での Spark (非 HDInsight) コネクタのシングル サインオン</li><li>新しい PDF コネクタ</li><li>HTML コネクタの機能強化 (サンプル別データ抽出)</li><li>Spark (非 HDInsight) コネクタの一般提供</li></ul>| 一般提供 | 2018 年 10 月 |
| Power BI | [Get Data エクスペリエンスにおける認定カスタム コネクタのサポート](1-power-query.md#certified-custom-connectors-in-power-bi-desktop) | 一般提供 | 2018 年 10 月 |
| Power BI | ODBC 開発者向けのコンテンツを含むカスタム コネクタ開発文書の向上 | 一般提供 | 2018 年 10 月 |
| Power BI | [「あいまい統合」および「あいまい置換」の変換](1-power-query.md#new-power-query-data-preparation-capabilities) | 一般提供 | 2018 年 10 月 |
| Power BI | [機能強化された新しいコネクタ](1-power-query.md#enterprise-grade-connectors)<ul><li>AtScale コネクタ</li><li>Essbase コネクタ</li></ul> | パブリック プレビュー | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [個人およびエンタープライズ ゲートウェイのカスタム コネクタのサポート](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [異なる容量の地域で Power BI Premium によるゲートウェイのサポート](5-data-gateway.md#gateway-multi-geo-support-for-power-bi-premium) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [クラスタリングを介したゲートウェイの高い利用可能性の保証](5-data-gateway.md#guarantee-high-availability-of-gateways-via-clustering) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [Kerberos シングル サインオン サポートの向上](5-data-gateway.md#improved-kerberos-single-sign-on-support) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [サポートされているデータ ソースの SAML ベースのシングル サインオン](5-data-gateway.md#saml-based-single-sign-on-for-supported-data-sources) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [Power BI Desktop に存在する追加のデータ ソース機能](5-data-gateway.md#additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [データ ソース設定のエクスペリエンスの向上](5-data-gateway.md#improved-data-sources-settings-experience) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [D365 管理ポータルですべてのテナントのゲートウェイを管理する機能](5-data-gateway.md#tenant-level-administration-of-on-premises-data-gateway) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [オンプレミス データ ゲートウェイにおけるトラフィック負荷分散](5-data-gateway.md#basic-traffic-load-balancing-in-the-on-premises-data-gateway) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | ファイル コネクタ エクスペリエンスの一環としてのファイル アップロードのサポート | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | クラウド ベースのファイル ストレージ (OneDrive Business、OneDrive Personal、SharePoint Team Sites) を参照する機能 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | カスタム コネクタのサポート (ゲートウェイ経由) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 上位のエンタープライズ リレーショナル コネクタのサポート | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | インレイク データ変換のサポート | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | GDPR (ユーザー データをエクスポートする機能、ユーザーがすべての CRUD 業務を監査する機能、DPIA 文書) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 管理者向けデータ統合の機能強化<ul><li>ビジネス プラットフォーム管理センターでの新しいエクスペリエンス</li><li>グレード C アクセシビリティの準拠</li><li>管理ポータル内からサポート チケットを作成する機能</li><li>履歴レコードのレビュー機能の向上 (実行履歴の改ページ)</li></ul> | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 新規および機能強化されたテンプレート<ul><li>新しい Salesforce テンプレートによってアプリ用 CDS および Power BI データフローにデータをインポート</li><li>追加の新しいデータ統合のテンプレート</li><li>テンプレートをカスタマイズする機能の強化 (既存のテンプレートを選択せずに空のプロジェクトを作成)</li><li>バージョン管理のサポート</li><li>デスティネーションとソースのソリューションの検証</li><li>公開されたテンプレートからマーケットプレースで DI プロジェクトを作成する機能 (DI またはマーケットプレースから始める)</li><li>テナント間およびテナント内でのテンプレートの共有</li></ul> | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | DI の一元化されたセットアップ エクスペリエンス (開発者/管理者ポータルの切り替えを防ぐ) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | データおよびバッチ並列処理などのパフォーマンスの向上 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 実行中の処理を停止する機能 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 一般的なパターン ガイド (一般的な問題の回避策) やスケーラビリティ ガイドラインを始めとするドキュメントの向上 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | テナント内でプロジェクトを共有する機能 |
| アプリ用 CDS と Power BI データフロー | 統合データから得られる重要な分析情報を表示する豊富なダッシュボードおよび他の統合関連の統計情報 | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 上位のコネクタ用にトリガーでサンプル データを使用 | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 機能強化されたコネクタ<ul><li>Oracle Database (一般提供)</li><li>MQ (一般提供)</li><li>Excel Online<ul><li>更新操作のサポート</li></ul></li><li>Cognitive Services API、Microsoft Translator、Bing Search、および Bing Maps の組み込みキーのサポート</li></ul> | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 新しい地域のサポート:<ul><li>米国政府 (GCC)</li><li>ブラジル</li></ul> | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 新しい機能強化されたコネクタ<ul><li>Oracle Database<ul><li>保存された手順のサポート</li><li>具体化されたビューのサポート</li></ul></li><li>Azure SQL Data Warehouse<ul><li>書き込み操作のサポート</li></ul></li></ul> | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | カスタム コネクタでのポリシー テンプレートのサポート | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | [Microsoft Flow でデータを再形成するための Power Query のサポート(SQL Server コネクタによる)](1-power-query.md#flow-support-for-data-filtering--mashup) | パブリック プレビュー | 2018 年 10 月 |
| Power Query | [コミュニティ Web サイトの開始](1-power-query.md#power-query-community-website) | 一般提供 | 2018 年 10 月 |
| Power Query | [データ準備ワークロードの一部としてエラーや異常値を簡単に識別するためのデータ プロファイル機能](1-power-query.md#new-power-query-data-preparation-capabilities) | 一般提供 | 2018 年 10 月 |
| Power Query | [M 言語の IntelliSense サポート](1-power-query.md#intellisense-support-for-the-m-formula-language) | 一般提供 | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [プラットフォーム内のすべての製品用コネクタを認証およびリリースするためのパートナー向け統合コネクタ認定プログラム (Power BI、Microsoft Flow、PowerApps、および CDS)](3-connector-ecosystem.md#unified-connector-certification-program)| 一般提供 | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [署名、バージョン管理、依存関係を有効にするための Power Query SDK を使用したカスタム コネクタのサポート](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | 一般提供 | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [M、OpenAPI、OData ベースのコネクタのための開発および検証ツールの向上](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | パブリック プレビュー | 2018 年 10 月 |
| Common Data Model | [価値の提案の説明および拡張機能の構築に関する詳細なガイドラインを含む CDM ドキュメントの向上](2-cdm.md#docs)  | 一般提供 | 2018 年 10 月 |
| Common Data Model | [インタラクティブでグラフィカルな Common Data Model エンティティ エクスプローラーおよび CDM GitHub の機能強化](2-cdm.md#explorer) | 一般提供 | 2018 年 10 月 |
| Common Data Model | [医療、財務サービス、小売などの産業ソリューション向けの初期 CDM エンティティ パック](2-cdm.md#industry) | パブリック プレビュー | 2018 年 10 月 |
| Common Data Model | [Finance、Operations、Marketing など人気のある Dynamics サービスにおける主要なシナリオを対象とした他の CDM エンティティの定義](2-cdm.md#dynamics) | パブリック プレビュー | 2018 年 10 月 |

