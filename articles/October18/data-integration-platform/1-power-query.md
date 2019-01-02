---
title: "Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合"
description: "Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 4870e3a2-ac78-4f21-be77-0ddf0ce91282
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
<<<<<<< HEAD
ms.sourcegitcommit: 5eda86ab05b375f2f919fc04c5089565ba4d7c86
ms.openlocfilehash: 0f4fb80846d9a9ab2c5b4c5b34e97357faa6fcfb
ms.contentlocale: ja-jp
ms.lasthandoff: 09/13/2018
=======
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 0f4fb80846d9a9ab2c5b4c5b34e97357faa6fcfb
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018
>>>>>>> 87e028547d07f7115112632b834c7e86c5555bb3

---
#  <a name="simpler-smarter-transformation-and-integration-of-enterprise-data-with-power-query-and-data-integration-platform"></a>Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




Microsoft では、次の革新により、エンタープライズにおける一般的なデータ統合の課題をよりシンプルにしました。

- 新しい Power Query データ準備機能。
- エンタープライズ レベルのコネクタ。
- Common Data Service のデータ統合の向上。

## <a name="new-power-query-data-preparation-capabilities"></a>新しい Power Query データ準備機能

Power Query は、市場をリードする *Smart Data Preparation* エクスペリエンスによって機能が大幅に向上しています。このエクスペリエンスには次が含まれます。

-   PDF ファイルなど部分的に構造化されたソースからのデータの抽出。
-   HTML ページ。
-   類似パターンに基づいてデータを合理化および正規化する部分一致アルゴリズム。
-   データ プロファイル機能。

これらの機能により、Power Query Editor のデータ準備ワークロードの一部としてエラーや異常値を簡単に識別することができます。

![](media/power-query-becomes-more-powerful-smarter-1.jpg "Power Query がよりスマートかつパワフルに")
<!-- picture -->


Microsoft は、Microsoft Research 内のいくつかのプロジェクトへの長年の投資に基づいた人工知能分野のリーダーシップを発揮して、Power Query で Smart Data Preparation 機能を利用可能にすることにより、幾百万ものビジネス ユーザーがさまざまな Microsoft 製品やサービス (Excel、Power BI、アプリ用 Common Data Service、Microsoft Flow など) で簡単にアクセスできるようにしています。

### <a name="intelligent-transforms-and-ai-support-in-power-query"></a>Power Query におけるインテリジェントな変換と人工知能サポート 

ビジネス アナリストは、シングル クリックで人工知能ベースの変換にアクセスして、人工知能駆動型の分析情報を簡単に組み込むことができます。 この分野における初期段階の機能には、センチメント分析や自然言語テキストからのキーワードの抽出が含まれます。 OCR や画像分析などの他の機能は追って追加される予定です。

アナリストや BI 専門家は、人工知能変換のための新しい標準機能や API にアクセスできます。 これにより、センチメント分析やキーワード抽出のための列変換が簡単になり、ボタンの 1回のクリックまたは「ApplySentimentIndex([textResponse])」のような 1 行のスクリプトで行えるようになります。

Power Query API は、Power BI アプリケーションのインストール時と構成時にも使用できるようサポートされるようになり、データフローを活用できます。 この場合、列変換のバッチ処理は、顧客の Power BI Premium 容量の一環として実行される Cognitive Services コンテナーにシームレスに誘導されます。

### <a name="analytic-and-ml-extensibility-with-scripting"></a>スクリプトでの分析と ML 拡張性

現在、Power BI でのカスタムのモデル化とビジュアル化で、R スクリプトの使用がサポートされています。 これらの R スクリプトは、Power BI サービスのデータ更新の一部として実行することもでき、その場合はカスタム R ライブラリをプラグインするオプション付きのオンプレミス データ ゲートウェイ (個人用モード) を活用します。

Python は、開発者やデータ科学者の間で広範に使用されています。
便利なライブラリを数多くサポートしているため、データ分析や人工知能関連の作業でデファクト スタンダードとなっています。 次のステップとして、Power BI Desktop は Python スクリプトのサポートを追加します。

### <a name="intellisense-support-for-the-m-formula-language"></a>M 式言語の IntelliSense サポート

M 言語編集エクスペリエンス (Advanced Query Editor、Add Custom Column、Formula Bar) への IntelliSense サポートが Power Query Editor に追加されます。これにより、ユーザーは M コードの直接的な編集、エラーの容易な検出、M ライブラリ機能の発見、および必要なパラメーターの理解をより効果的に行えるようになります。 M Intellisense のサポートは、ここ数年間に Power Query の中級および上級ユーザーからの要望が最も高かった機能であり、Power BI および Excel の機能推奨フォーラムにおいて、現在もなお Power Query に対して最も要望の高い機能となっています。

![](media/power-query-becomes-more-powerful-smarter-4.png "")
<!-- picture -->


Power Query 内の新しいコア機能に加えて、Microsoft は Power Query を活用する製品とサービスの範囲を拡張しています。 過去 6 か月間で、Power Query Online は Microsoft Flow と統合されました。

<a name="flow-support-for-data-filtering--mashup"></a>  
### <a name="flow-support-for-data-filtering-and-mashup"></a>データ フィルター処理とマッシュアップの Flow サポート

Microsoft Flow が Power Query Online と統合されたことにより、ユーザーは "Power Query を使用して行を取得する" ことが可能になります。これにより、SQL Server などの特定のコネクタで "行を取得する" アクションの一部としてデータ フィルター処理とマッシュアップを行えるようになります。

### <a name="power-query-documentation"></a>Power Query ドキュメント

Microsoft Docs に Power Query のセクションが追加されました。 これらのドキュメントには、Power Query 用のカスタム コネクタを作成するためのサンプル、チュートリアル、ハウツー、開発者向けリファレンスが含まれます。 Power Query で使用されている言語である M での作業に関心のある開発者やエンド ユーザーは、ここで多くの質問への回答を得ることができます。

### <a name="power-query-community-website"></a>Power Query コミュニティ Web サイト

新しい Power Query コミュニティ Web サイトが立ち上げられました。 これには、Power Query テクノロジの概要、詳細記事、フォーラム、UserVoice、コミュニティ主導のコンテンツ (ブログ投稿、ウェビナー) などが含まれます。 この新しいコミュニティは、パートナーがプラットフォーム上に新しいコネクタやデータ変換を構築するのを可能にする Power Query テクノロジの機能に焦点を合わせており、既存の製品ベースのリソース (Excel、Power BI、PowerApps など) を補完し、エンド ユーザーのための特定の Power Query の統合に対応しています。

##  <a name="enterprise-grade-connectors"></a>エンタープライズ レベルのコネクタ

データ統合チームは引き続き、Power BI、アプリ用 Common Data Service、PowerApps、Microsoft Flow、および Logic Apps でエンタープライズ レベルのコネクタに貢献します。

Power BI に関して、Microsoft は SAP Business Warehouse コネクタ (アプリケーション サーバーとメッセージ サーバー) 向けに大幅な機能向上をリリースする予定で、これにより Microsoft Power BI は、SAP Business Warehouse (BW) への接続性において、他のサード パーティ BI ベンダーと同等またはそれ以上の優れた機能を持つ製品となります。

SAP は、**SAP HANA と SAP BW で Microsoft のコネクタを認定しています**。 また、SAP HANA コネクタが強化され、Security Assertion Markup Language (SAML) ベースのシングル サインオンおよび SSL 認定検証など、大規模なエンタープライズ機能が可能になりました。 SAP BW コネクタも大幅に向上し、より優れたパフォーマンスを提供する新しい実装や他の機能が追加されています。

コネクタの他の機能強化としては、Spark オンプレミスでの Kerberos 経由のシングル サインオンのサポート、また **HDInsight Spark、Google BigQuery、Spark (HDInsight 以外)** など、既存のコネクタの一般提供開始などが含まれます。

さらに、PowerApps、Microsoft Flow、Logic Apps 内のコネクタの機能強化 (Azure SQL Data Warehouse の書き込み機能のリリースなど)、Visual Studio Team Services の各種更新 (カスタム フィールドのトリガーやサポートの向上など)、および Oracle コネクタの追加機能などもあります。

プラットフォームは引き続き進化しており、アプリ用 Common Data Service、Power BI、PowerApps、Microsoft Flow、Logic Apps で一貫して機能する新しいコネクタが追加され、製品スイート全体で顧客エクスペリエンスの整合性がさらに向上しています。

##  <a name="improved-connectors-and-import-experiences-for-cds-data-integration"></a>CDS データ統合のためのコネクタとインポート エクスペリエンスの向上 

2018 年 4 月に、Microsoft はアプリ用 Common Data Service のパブリック プレビューを発表しました。 このプレビューの一環として、ビジネス ユーザーがクラウドおよびオンプレミスで Microsoft とサードパーティの幅広いデータ ソースからデータをインポートする機能が組み込まれました。この機能には、ユーザーが Excel や Power BI Desktop で使い慣れている、コーディングなし (またはわずかなコーディング) の Web ベースの Power Query エクスペリエンスが活用されています。

今後 6 か月の間、Microsoft はこの Web ベースの Power Query エクスペリエンスにおけるデータ コネクタとデータ変換のサポートを拡張してゆく予定です。これには、Oracle、Amazon Redshift、Google BigQuery、Impala などのビジネス クリティカルなデータ ソース (オンプレミスおよびクラウド) のサポートが含まれます。

また、Power Query Online におけるカスタム コネクタ (Data Connector SDK に基づく) のサポートも追加されます。これにより、パートナーが作成した既存のカスタム コネクタを活用してアプリ用 Common Data Service と Power BI データフローのデータ統合を実現することもできます。

さらに、ユーザーがローカル ファイルのアップロードを行えるようになり (一般的な要望)、Power Query Online でファイルからデータをインポートするときのユーザー エクスペリエンスが向上されています。

![](media/4-1.png "")
<!-- Get Data 5.png -->

同様に、OneDrive Business/Personal および SharePoint Team Sites など、人気のあるクラウド ベースのファイル ストレージ サービスのファイルを Power Query で参照できるようになります。 

##  <a name="certified-custom-connectors-in-power-bi-desktop"></a>Power BI Desktop における認定カスタム コネクタ

2018 年 4 月に、Microsoft は Power BI の最初のカスタム コネクタをリリースしました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。 ユーザーはすべてのデータ ソースからコネクタに簡単にアクセスできるようになり、ベンダーも顧客の要望に応じて新しいコネクタを簡単に記述でき、Power BI がベンダーとエンドユーザーの双方にとって最適な BI プラットフォームとなるよう役割が強化されています。

2018 年 5 月、この機能と既存の Get Data エクスペリエンスとの整合性が図られ、既存の標準コネクタとのシームレスなエクスペリエンスを実現して、シングル クリックで利用できるコネクタの数が大幅に増えました。

2018 年 10 月、この機能は一般に提供されるようになり、Power BI はエンド ユーザーに新しい認定されたカスタム コネクタを定期的に提供するようになります。 コネクタ認定プログラムの詳細については、[こちら](https://docs.microsoft.com/en-us/power-query/connectorcertification)の Power Query ドキュメントを参照してください。



