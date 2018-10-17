---
title: "データ統合の新機能"
description: "Microsoft ビジネス アプリケーションの 2018 年 10 月のリリースで提供されるデータ統合の新機能の概要をご覧ください。"
author: shellyhaverkamp
manager: AnnBe
ms.date: 9/7/2018
ms.assetid: 7326561e-192f-4897-ad72-af64d29849da
ms.topic: summary
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 571d4025b4fe454cc95c9c2b2e7bbaf91cd5f656
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---
#  <a name="summary-of-whats-new-in-data-integration"></a>データ統合の新機能の概要

このプラットフォーム機能に対する改善によって、Microsoft やサード パーティのアプリケーションとサービスへの接続が拡充されます。

(リリース ノートで説明されている機能は、まだリリースされていない場合があります。) 提供タイムラインおよび予定されている機能は、変更される可能性、または出荷されない可能性があります ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。
    
Dynamics 365 ビジネス アプリケーションを利用できる地域の一覧については、[ご利用いただける国と地域に関するガイド](https://aka.ms/dynamics_365_international_availability_deck)を参照してください。 

|**製品** | **機能**| **リリースの種類** | **日付**|
|---------|-----------------------------------|---------|---------|
| Power BI | [機能強化された新しいコネクタ](1-power-query.md#enterprise-grade-connectors)<br> * OData v4 プロトコルのフル サポート <br> * HDInsight Spark Connector <br> * Google BigQuery Connector <br><br> *  SAP HANA   <br>   - Power BI サービス (ゲートウェイ経由) における SSL 認定検証のサポート   <br>   - [SAML ベースのシングル サインオン](5-data-gateway.md#saml-based-single-sign-on-for-supported-data-sources) (Power BI Desktop およびゲートウェイを含む) <br><br> * SAP BW   <br>   - パフォーマンスの機能強化   <br>   - 追加の DirectQuery メタデータ (プロパティ、通貨、測定単位)   <br>   - 認証   <br>   - Power BI Desktop + サービス (ゲートウェイ経由) でのシングル サインオン <br><br> * Spark (非 HDInsight) コネクタ <br> * Power BI Desktop + サービス (ゲートウェイ経由) でのシングル サインオン <br> * HTML コネクタの機能強化 (サンプル別データ抽出)  | 一般提供 | 2018 年 10 月 |
| Power BI | [Get Data エクスペリエンスにおける認定カスタム コネクタのサポート](1-power-query.md#certified-custom-connectors-in-power-bi-desktop) | 一般提供 | 2018 年 10 月 |
| Power BI | ODBC 開発者向けのコンテンツを含むカスタム コネクタ開発文書の向上 | 一般提供 | 2018 年 10 月 |
| Power BI | [新しい PDF コネクタ](1-power-query.md#enterprise-grade-connectors)| 一般提供 | 2018 年 12 月 |
| Power BI | [「あいまい統合」の変換](1-power-query.md#new-power-query-data-preparation-capabilities) | パブリック プレビュー | 2018 年 10 月 |
| Power BI | [機能強化された新しいコネクタ](1-power-query.md#enterprise-grade-connectors) <br> * AtScale コネクタ <br> * Essbase コネクタ <br> * IBM DB2 DirectQuery <br> * PBI サービスの Vertica (ゲートウェイ経由) <br> * PBI サービスの HDInsight 対話型クエリ (ゲートウェイ経由) | パブリック プレビュー | 2018 年 10 月 |
| Power BI | AtScale コネクタ (招待によるプライベート プレビュー - 2018 年 10 月)* | パブリック プレビュー* | 2019 年 1 月* |
| Power BI | Essbase コネクタ (招待によるプライベート プレビュー - 2018 年 12 月)* | パブリック プレビュー* | 2019 年 3 月* |
| オンプレミス データ ゲートウェイ | [個人およびエンタープライズ ゲートウェイのカスタム コネクタのサポート](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [クラスタリングを介したゲートウェイの高い利用可能性の保証](5-data-gateway.md#guarantee-high-availability-of-gateways-via-clustering) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [Kerberos シングル サインオン サポートの向上](5-data-gateway.md#improved-kerberos-single-sign-on-support) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [Power BI Desktop に存在する追加のデータ ソース機能](5-data-gateway.md#additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [データ ソース設定のエクスペリエンスの向上](5-data-gateway.md#improved-data-sources-settings-experience) | 一般提供 | 2018 年 10 月 |
| オンプレミス データ ゲートウェイ | [D365 管理ポータルですべてのテナントのゲートウェイを管理する機能*](5-data-gateway.md#tenant-level-administration-of-on-premises-data-gateway) | 一般提供* | 2018 年 12 月* |
| オンプレミス データ ゲートウェイ | [オンプレミス データ ゲートウェイにおけるトラフィック負荷分散](5-data-gateway.md#basic-traffic-load-balancing-in-the-on-premises-data-gateway) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | PowerApps メーカー ポータルでのデータ統合プロジェクトに対するスケジュールされた更新のサポート | 一般提供 | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | GDPR (ユーザー データをエクスポートする機能、ユーザーがすべての CRUD 業務を監査する機能、DPIA 文書) | 一般提供 | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 管理者向けデータ統合の機能強化 <br> * ビジネス プラットフォーム管理センターでの新しいエクスペリエンス <br> * 管理ポータル内からサポート チケットを作成する機能 <br> * 履歴レコードのレビュー機能の向上 (実行履歴の改ページ) | 一般提供 | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | ファイル コネクタ エクスペリエンスの一環としてのファイル アップロードのサポート | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | クラウド ベースのファイル ストレージ (OneDrive Business、OneDrive Personal、SharePoint Team Sites) を参照する機能 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 上位のエンタープライズ リレーショナル コネクタのサポート (Oracle Database 、IBM DB2 データベース、PostgreSQL など)| パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | インレイク データ変換のサポート | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 新規および機能強化されたテンプレート <br> * 新しい Salesforce テンプレートによってアプリ用 CDS および Power BI データフローにデータをインポート <br> * 追加の新しいデータ統合のテンプレート <br> * テンプレートをカスタマイズする機能の強化 (既存のテンプレートを選択せずに空のプロジェクトを作成) <br> * バージョン管理のサポート <br> * デスティネーションとソースのソリューションの検証<br> * 公開されたテンプレートからマーケットプレースで DI プロジェクトを作成する機能 (DI またはマーケットプレースから始める) <br> * テナント間およびテナント内でのテンプレートの共有 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | DI の一元化されたセットアップ エクスペリエンス (開発者/管理者ポータルの切り替えを防ぐ) | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | データおよびバッチ並列処理などのパフォーマンスの向上 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 実行中の処理をキャンセルする機能 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 一般的なパターン ガイド (一般的な問題の回避策) やスケーラビリティ ガイドラインを始めとするドキュメントの向上 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | テナント内でプロジェクトを共有する機能 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | 統合データから得られる重要な分析情報を表示する豊富なダッシュボードおよび他の統合関連の統計情報 | パブリック プレビュー | 2018 年 10 月 |
| アプリ用 CDS と Power BI データフロー | ソース エンティティが関連しているときのデータ統合によるエンティティ間の関連付けの自動作成 | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 上位のコネクタ用にトリガーでサンプル データを使用 | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 機能強化されたコネクタ <br> * Oracle Database (一般提供) <br> * MQ (一般提供) <br> * Microsoft Translator、Bing Search、および Bing マップの組み込みキーのサポート | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 新しい地域のサポート: <br> * ブラジル | 一般提供 | 2018 年 10 月 |
| Microsoft Flow および PowerApps | 新しい地域のサポート: <br> * 米国政府 (GCC) | パブリック プレビュー* | 2018 年 11 月* |
| Microsoft Flow および PowerApps | 新しい機能強化されたコネクタ <br> * Oracle Database <br> * 保存された手順のサポート <br> * 具体化されたビューのサポート <br> * Azure SQL Data Warehouse <br> * 書き込み操作のサポート <br> * Excel Online <br> * 更新操作のサポート | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | カスタム コネクタでのポリシー テンプレートのサポート | パブリック プレビュー | 2018 年 10 月 |
| Microsoft Flow および PowerApps | [Microsoft Flow でデータを再形成するための Power Query のサポート(SQL Server コネクタによる)](1-power-query.md#flow-support-for-data-filtering--mashup) | パブリック プレビュー | 2018 年 10 月 |
| Power Query | [コミュニティ Web サイトの開始](1-power-query.md#power-query-community-website) | 一般提供 | 2018 年 10 月 |
| Power Query | [データ準備ワークロードの一部としてエラーや異常値を簡単に識別するためのデータ プロファイル機能](1-power-query.md#new-power-query-data-preparation-capabilities) | パブリック プレビュー | 2018 年 10 月 |
| Power Query | [M 言語の IntelliSense サポート](1-power-query.md#intellisense-support-for-the-m-formula-language) | パブリック プレビュー | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [プラットフォーム内のすべての製品用コネクタを認証およびリリースするためのパートナー向け統合コネクタ認定プログラム (Power BI、Microsoft Flow、PowerApps、および CDS)](3-connector-ecosystem.md#unified-connector-certification-program)| 一般提供 | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [Power Query SDK を使用するカスタム コネクタのサポート](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | 一般提供 | 2018 年 10 月 |
| コネクタ プラットフォームの拡張性 | [M、OpenAPI、OData ベースのコネクタのための開発および検証ツールの向上](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | パブリック プレビュー | 2018 年 10 月 |
| Common Data Model | [エンティティの定義がオープン ソース化されていて、追加のドキュメントとツールが含まれる、CDM GitHub リポジトリ](2-cdm.md)  | 一般提供 | 2018 年 10 月 |
| Common Data Model | [価値の提案の説明および拡張機能の構築に関する詳細なガイドラインを含む CDM ドキュメントの向上](2-cdm.md#docs)  | 一般提供 | 2018 年 10 月 |
| Common Data Model | [インタラクティブでグラフィカルな Common Data Model エンティティ エクスプローラーおよび CDM GitHub の機能強化](2-cdm.md#explorer) | 一般提供 | 2018 年 10 月 |
| Common Data Model | [医療、財務サービス、小売などの産業ソリューション向けの初期 CDM エンティティ パック](2-cdm.md#industry) | パブリック プレビュー | 2018 年 10 月 |
| Common Data Model | [Finance、Operations、Marketing など人気のある Dynamics オファリングにおける主要なシナリオを対象とした他の CDM エンティティの定義](2-cdm.md#dynamics) | パブリック プレビュー | 2018 年 10 月 |

凡例:  
* これらの日付は、以前のリリース ノートが公開されてから更新されています。  
** これらの項目のリリースの種類 (パブリック プレビューまたは一般提供) は誤ってマークされていたため、更新されました。  
*** これらの項目は、10 月の新機能です。  

この一覧から削除された項目:  

|機能 | 理由 |
|-----|--------------------------|
| アプリ用 CDS および Power BI データフローでのカスタム コネクタ (ゲートウェイ経由) のサポート <br> (2018 年 10 月にパブリック プレビューでした) | この機能のサポートの調査はまだ行われています。ただし、そのサポートに対する明確なタイムラインはありません。 [PowerApps のアイデア](https://powerusers.microsoft.com/t5/PowerApps-Ideas/idb-p/PowerAppsIdeas)および [Power BI のアイデア](https://ideas.powerbi.com)で提案に投票して優先順位付けにご協力ください。 |
| 異なる容量の地域での Power BI Premium によるゲートウェイのサポート <br> (2018 年 10 月に一般提供でした)| 優先順位が変化するため、この機能のタイムフレームは決められていません。 調査が続けられている間、https://ideas.powerbi.com で提案に投票して優先順位付けにご協力ください。| 

