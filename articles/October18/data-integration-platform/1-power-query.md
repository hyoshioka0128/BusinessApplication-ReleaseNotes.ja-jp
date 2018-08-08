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
ms.sourcegitcommit: e4d721713b70d0a9cfeb06d0f795f23d3f0223a5
ms.openlocfilehash: 2fdc6a7522631e62f608087ec6badd6805b32068
ms.contentlocale: ja-jp
ms.lasthandoff: 07/27/2018

---
#  <a name="simpler-smarter-transformation-and-integration-of-enterprise-data-with-power-query-and-data-integration-platform"></a><span data-ttu-id="d7516-103">Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合</span><span class="sxs-lookup"><span data-stu-id="d7516-103">Simpler, smarter transformation and integration of enterprise data with Power Query and Data Integration Platform</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="d7516-104">Microsoft では、次の革新により、エンタープライズにおける一般的なデータ統合の課題をよりシンプルにしました。</span><span class="sxs-lookup"><span data-stu-id="d7516-104">We have simplified common data integration problems in enterprises by innovating in:</span></span>

- <span data-ttu-id="d7516-105">新しい Power Query データ準備機能。</span><span class="sxs-lookup"><span data-stu-id="d7516-105">New Power Query data preparation capabilities.</span></span>
- <span data-ttu-id="d7516-106">エンタープライズ レベルのコネクタ。</span><span class="sxs-lookup"><span data-stu-id="d7516-106">Enterprise-grade connectors.</span></span>
- <span data-ttu-id="d7516-107">Common Data Service のデータ統合の向上。</span><span class="sxs-lookup"><span data-stu-id="d7516-107">Improvements for Common Data Service data integration.</span></span>

## <a name="new-power-query-data-preparation-capabilities"></a><span data-ttu-id="d7516-108">新しい Power Query データ準備機能</span><span class="sxs-lookup"><span data-stu-id="d7516-108">New Power Query data preparation capabilities</span></span>

<span data-ttu-id="d7516-109">Power Query は、市場をリードする *Smart Data Preparation* エクスペリエンスによって機能が大幅に向上しています。このエクスペリエンスには次が含まれます。</span><span class="sxs-lookup"><span data-stu-id="d7516-109">Power Query is being dramatically enhanced with market-leading *Smart Data Preparation* experiences, including:</span></span>

-   <span data-ttu-id="d7516-110">PDF ファイルなど部分的に構造化されたソースからのデータの抽出。</span><span class="sxs-lookup"><span data-stu-id="d7516-110">Data extraction from semi-structured sources like PDF files.</span></span>
-   <span data-ttu-id="d7516-111">HTML ページ。</span><span class="sxs-lookup"><span data-stu-id="d7516-111">HTML pages.</span></span>
-   <span data-ttu-id="d7516-112">類似パターンに基づいてデータを合理化および正規化する部分一致アルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="d7516-112">Fuzzy-matching algorithms to rationalize and normalize data based on similarity patterns.</span></span>
-   <span data-ttu-id="d7516-113">データ プロファイル機能。</span><span class="sxs-lookup"><span data-stu-id="d7516-113">Data profiling capabilities.</span></span>

<span data-ttu-id="d7516-114">これらの機能により、Power Query Editor のデータ準備ワークロードの一部としてエラーや異常値を簡単に識別することができます。</span><span class="sxs-lookup"><span data-stu-id="d7516-114">These abilities help to easily identify errors and outliers as part of the data preparation workload in the Power Query Editor.</span></span>

<span data-ttu-id="d7516-115">![](media/power-query-becomes-more-powerful-smarter-1.jpg "Power Query がよりスマートかつパワフルに")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="d7516-115">![](media/power-query-becomes-more-powerful-smarter-1.jpg "Power Query becomes smarter and more powerful")
<!-- picture --></span></span>


<span data-ttu-id="d7516-116">Microsoft は、Microsoft Research 内のいくつかのプロジェクトへの長年の投資に基づいた人工知能分野のリーダーシップを発揮して、Power Query で Smart Data Preparation 機能を利用可能にすることにより、幾百万ものビジネス ユーザーがさまざまな Microsoft 製品やサービス (Excel、Power BI、アプリ用 Common Data Service、Microsoft Flow など) で簡単にアクセスできるようにしています。</span><span class="sxs-lookup"><span data-stu-id="d7516-116">Microsoft is leveraging its leadership in the artificial intelligence field based on years of investment in several projects within Microsoft Research, and surfacing these Smart Data Preparation capabilities in Power Query, making them easily accessible to millions of business users across different Microsoft products and services (Excel, Power BI, Common Data Service for Apps, and Microsoft Flow).</span></span>

### <a name="intelligent-transforms-and-ai-support-in-power-query"></a><span data-ttu-id="d7516-117">Power Query におけるインテリジェントな変換と人工知能サポート</span><span class="sxs-lookup"><span data-stu-id="d7516-117">Intelligent transforms and AI support in Power Query</span></span> 

<span data-ttu-id="d7516-118">ビジネス アナリストは、シングル クリックで人工知能ベースの変換にアクセスして、人工知能駆動型の分析情報を簡単に組み込むことができます。</span><span class="sxs-lookup"><span data-stu-id="d7516-118">Business analysts can easily incorporate AI-driven insights with a single-click access to AI-based transforms.</span></span> <span data-ttu-id="d7516-119">この分野における初期段階の機能には、センチメント分析や自然言語テキストからのキーワードの抽出が含まれます。</span><span class="sxs-lookup"><span data-stu-id="d7516-119">Initial capabilities in this area will include sentiment analysis and keyword extraction from natural language text.</span></span> <span data-ttu-id="d7516-120">OCR や画像分析などの他の機能は追って追加される予定です。</span><span class="sxs-lookup"><span data-stu-id="d7516-120">Additional capabilities such as OCR and image analysis could be added over time.</span></span>

<span data-ttu-id="d7516-121">アナリストや BI 専門家は、人工知能変換のための新しい標準機能や API にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="d7516-121">Analysts and BI Pros will gain access to new out-of-the-box functions and APIs for AI transformations.</span></span> <span data-ttu-id="d7516-122">これにより、センチメント分析やキーワード抽出のための列変換が簡単になり、ボタンの 1回のクリックまたは「ApplySentimentIndex([textResponse])」のような 1 行のスクリプトで行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="d7516-122">This facilitates column transformations for sentiment analysis and keyword extraction with a click of a button, or with a single line of script, such as “ApplySentimentIndex([textResponse])”.</span></span>

<span data-ttu-id="d7516-123">Power Query API は、Power BI アプリケーションのインストール時と構成時にも使用できるようサポートされるようになり、データフローを活用できます。</span><span class="sxs-lookup"><span data-stu-id="d7516-123">The Power Query APIs will also be supported for use during installation and configuration of Power BI applications making use of dataflows.</span></span> <span data-ttu-id="d7516-124">この場合、列変換のバッチ処理は、顧客の Power BI Premium 容量の一環として実行される Cognitive Services コンテナーにシームレスに誘導されます。</span><span class="sxs-lookup"><span data-stu-id="d7516-124">In this instance, batch-processing of the transforms for the column will be directed seamlessly to a Cognitive Services container running as part of a customer’s Power BI Premium capacity.</span></span>

### <a name="analytic-and-ml-extensibility-with-scripting"></a><span data-ttu-id="d7516-125">スクリプトでの分析と ML 拡張性</span><span class="sxs-lookup"><span data-stu-id="d7516-125">Analytic and ML extensibility with scripting</span></span>

<span data-ttu-id="d7516-126">現在、Power BI でのカスタムのモデル化とビジュアル化で、R スクリプトの使用がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="d7516-126">We currently support the use of R scripts for custom modeling and visualization in Power BI.</span></span> <span data-ttu-id="d7516-127">これらの R スクリプトは、Power BI サービスのデータ更新の一部として実行することもでき、その場合はカスタム R ライブラリをプラグインするオプション付きのオンプレミス データ ゲートウェイ (個人用モード) を活用します。</span><span class="sxs-lookup"><span data-stu-id="d7516-127">These R scripts can also be executed as part of data refresh in the Power BI Service leveraging the on-premises Data Gateway (personal mode) with the option to plug in custom R libraries.</span></span>

<span data-ttu-id="d7516-128">Python は、開発者やデータ科学者の間で広範に使用されています。</span><span class="sxs-lookup"><span data-stu-id="d7516-128">Python has gained widespread adoption among developers and data scientists.</span></span>
<span data-ttu-id="d7516-129">便利なライブラリを数多くサポートしているため、データ分析や人工知能関連の作業でデファクト スタンダードとなっています。</span><span class="sxs-lookup"><span data-stu-id="d7516-129">It is the de-facto standard for data analysis and AI-related work due to its large support for useful libraries.</span></span> <span data-ttu-id="d7516-130">次のステップとして、Power BI Desktop は Python スクリプトのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="d7516-130">As the next step, Power BI Desktop is adding support for Python scripting.</span></span>

### <a name="intellisense-support-for-the-m-formula-language"></a><span data-ttu-id="d7516-131">M 式言語の IntelliSense サポート</span><span class="sxs-lookup"><span data-stu-id="d7516-131">Intellisense support for the M formula language</span></span>

<span data-ttu-id="d7516-132">M 言語編集エクスペリエンス (Advanced Query Editor、Add Custom Column、Formula Bar) への IntelliSense サポートが Power Query Editor に追加されます。これにより、ユーザーは M コードの直接的な編集、エラーの容易な検出、M ライブラリ機能の発見、および必要なパラメーターの理解をより効果的に行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="d7516-132">Intellisense support for the M language editing experiences (Advanced Query Editor, Add Custom Column, and Formula Bar) is being added to the Power Query Editor, making users more successful in editing their M code directly, being able to easily find errors, discover M library functions, and understand what parameters are needed.</span></span> <span data-ttu-id="d7516-133">M Intellisense のサポートは、ここ数年間に Power Query の中級および上級ユーザーからの要望が最も高かった機能であり、Power BI および Excel の機能推奨フォーラムにおいて、現在もなお Power Query に対して最も要望の高い機能となっています。</span><span class="sxs-lookup"><span data-stu-id="d7516-133">M Intellisense support is among the most requested features from intermediate-to-advanced Power Query users in the last couple of years and remains at the top of the feature asks for Power Query in the Power BI and Excel feature suggestions forums.</span></span>

![](media/power-query-becomes-more-powerful-smarter-4.png "")
<!-- picture -->


<span data-ttu-id="d7516-134">Power Query 内の新しいコア機能に加えて、Microsoft は Power Query を活用する製品とサービスの範囲を拡張しています。</span><span class="sxs-lookup"><span data-stu-id="d7516-134">In addition to new core capabilities within Power Query, Microsoft is also extending the range of products and services that leverage Power Query.</span></span> <span data-ttu-id="d7516-135">過去 6 か月間で、Power Query Online は Microsoft Flow と統合されました。</span><span class="sxs-lookup"><span data-stu-id="d7516-135">Over the past six months, Power Query Online has been integrated with Microsoft Flow.</span></span>

<a name="flow-support-for-data-filtering--mashup"></a>  
### <a name="flow-support-for-data-filtering-and-mashup"></a><span data-ttu-id="d7516-136">データ フィルター処理とマッシュアップの Flow サポート</span><span class="sxs-lookup"><span data-stu-id="d7516-136">Flow support for data filtering and mashup</span></span>

<span data-ttu-id="d7516-137">Microsoft Flow が Power Query Online と統合されたことにより、ユーザーは「Power Query を使用して行を取得する」ことが可能になります。これにより、SQL Server などの特定のコネクタで「行を取得する」一環としてデータ フィルター処理とマッシュアップを行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="d7516-137">Microsoft Flow now integrates with Power Query Online, allowing users to “Get Rows using Power Query,” which enables data filtering and mashup as part of the “Get Rows” action on specific connectors, such as SQL Server.</span></span>

### <a name="power-query-community-website"></a><span data-ttu-id="d7516-138">Power Query コミュニティ Web サイト</span><span class="sxs-lookup"><span data-stu-id="d7516-138">Power Query community website</span></span>

<span data-ttu-id="d7516-139">新しい Power Query コミュニティ Web サイトが立ち上げられました。</span><span class="sxs-lookup"><span data-stu-id="d7516-139">A new Power Query community website has been launched.</span></span> <span data-ttu-id="d7516-140">これには、Power Query テクノロジの概要、詳細記事、フォーラム、UserVoice、コミュニティ主導のコンテンツ (ブログ投稿、ウェビナー) などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d7516-140">It includes Power Query technology overview and deep dive articles as well as forums, UserVoice, and community-driven content (blog posts, webinars).</span></span> <span data-ttu-id="d7516-141">この新しいコミュニティは、パートナーがプラットフォーム上に新しいコネクタやデータ変換を構築するのを可能にする Power Query のコア機能に焦点を合わせており、以前から存在する製品ベースのリソース (Excel、Power BI、PowerApps など) を補完し、エンドユーザーの観点から特定の Power Query の統合に対応しています。</span><span class="sxs-lookup"><span data-stu-id="d7516-141">This new community focuses on the core Power Query technology aspects that enable partners to build new connectors and data transformations on top of the platform, and complements the previously existing product-based resources (Excel, Power BI, PowerApps, and more), which cover specific Power Query integrations from an end-user perspective.</span></span>

##  <a name="enterprise-grade-connectors"></a><span data-ttu-id="d7516-142">エンタープライズ レベルのコネクタ</span><span class="sxs-lookup"><span data-stu-id="d7516-142">Enterprise-grade connectors</span></span>

<span data-ttu-id="d7516-143">データ統合チームは引き続き、Power BI、アプリ用 Common Data Service、PowerApps、Microsoft Flow、および Logic Apps でエンタープライズ レベルのコネクタに貢献します。</span><span class="sxs-lookup"><span data-stu-id="d7516-143">The Data Integration team continues to contribute to enterprise-grade connectors across Power BI, Common Data Service for Apps, PowerApps, Microsoft Flow, and Logic Apps.</span></span>

<span data-ttu-id="d7516-144">Power BI に関して、Microsoft は SAP ビジネス ウェアハウス コネクタ (アプリケーション サーバーとメッセージ サーバー) 向けに大幅な機能向上をリリースする予定で、これにより Microsoft Power BI は、SAP ビジネス ウェアハウス (BW) への接続性において、他のサード パーティ BI ベンダーと同等またはそれ以上の優れた機能を持つ製品となります。</span><span class="sxs-lookup"><span data-stu-id="d7516-144">For Power BI, Microsoft is releasing significant enhancements to their SAP Business Warehouse connectors (Application Server and Message Server), which put Microsoft Power BI at parity or, in some cases, ahead of any other third-party BI vendors in terms of connectivity to SAP Business Warehouse (BW).</span></span>

<span data-ttu-id="d7516-145">SAP は、**SAP HANA と SAP BW で Microsoft のコネクタを認定しています。**</span><span class="sxs-lookup"><span data-stu-id="d7516-145">SAP has **certified Microsoft’s connectors for SAP HANA and SAP BW.**</span></span> <span data-ttu-id="d7516-146">また、SAP HANA コネクタが強化され、Security Assertion Markup Language (SAML) ベースのシングル サインオンおよび SSL 認定検証など、大規模なエンタープライズ機能が可能になりました。</span><span class="sxs-lookup"><span data-stu-id="d7516-146">In addition, the SAP HANA connector has been improved to enable large enterprise capabilities, such as Security Assertion Markup Language (SAML) based single sign-on and SSL certificate validation.</span></span> <span data-ttu-id="d7516-147">SAP BW コネクタも大幅に向上し、より良いパフォーマンスを提供する新しい実装や他の機能が追加されています。</span><span class="sxs-lookup"><span data-stu-id="d7516-147">The SAP BW connector is being significantly enhanced with a new implementation that provides orders of magnitude better performance as well as additional capabilities.</span></span>

<span data-ttu-id="d7516-148">コネクタの他の機能強化としては、Spark オンプレミスでの Kerberos 経由のシングル サインオンのサポート、また **HDInsight Spark、Google BigQuery、Spark (HDInsight 以外)** など、既存のコネクタの一般提供開始などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d7516-148">Other connector improvements will include single sign-on support via Kerberos for Spark on-premises and releasing existing connectors as generally available, including **HDInsight Spark, Google BigQuery, Spark (non-HDInsight)**, and more.</span></span>

<span data-ttu-id="d7516-149">さらに、PowerApps、Microsoft Flow、Logic Apps 内のコネクタの機能強化 (Azure SQL Data Warehouse の書き込み機能のリリースなど)、Visual Studio Team Services の各種更新 (カスタム フィールドのトリガーやサポートの向上など)、および Oracle コネクタの追加機能などもあります。</span><span class="sxs-lookup"><span data-stu-id="d7516-149">There have also been improvements to the connectors within PowerApps, Microsoft Flow, and Logic Apps such as releasing write capabilities for Azure SQL Data Warehouse, numerous Visual Studio Team Services updates including better triggers and support for custom fields, and additional capabilities in the Oracle connector and many more.</span></span>

<span data-ttu-id="d7516-150">プラットフォームは引き続き進化しており、アプリ用 Common Data Service、Power BI、PowerApps、Microsoft Flow、Logic Apps で一貫して機能する新しいコネクタが追加され、製品スイート全体で顧客エクスペリエンスの整合性がさらに向上しています。</span><span class="sxs-lookup"><span data-stu-id="d7516-150">The platform continues to evolve and has added new connectors that work consistently across Common Data Service for Apps, Power BI, PowerApps, Microsoft Flow, and Logic Apps, part of an effort to better align customer experiences across the full suite of products.</span></span>

##  <a name="improved-connectors-and-import-experiences-for-cds-data-integration"></a><span data-ttu-id="d7516-151">CDS データ統合のためのコネクタとインポート エクスペリエンスの向上</span><span class="sxs-lookup"><span data-stu-id="d7516-151">Improved connectors and import experiences for CDS data integration</span></span> 

<span data-ttu-id="d7516-152">2018 年 4 月に、Microsoft はアプリ用 Common Data Service のパブリック プレビューを発表しました。</span><span class="sxs-lookup"><span data-stu-id="d7516-152">In April 2018, Microsoft unveiled a public preview of Common Data Service for Apps.</span></span> <span data-ttu-id="d7516-153">このプレビューの一環として、ビジネス ユーザーがクラウドおよびオンプレミスで Microsoft とサードパーティの幅広いデータ ソースからデータをインポートする機能が組み込まれました。この機能には、ユーザーが Excel や Power BI Desktop で使い慣れている、コーディングなし (またはわずかなコーディング) の Web ベースの Power Query エクスペリエンスが活用されています。</span><span class="sxs-lookup"><span data-stu-id="d7516-153">As part of this preview, there were built-in capabilities for business users to import data from a wide range of data sources from Microsoft and third parties in the cloud and on-premises, leveraging a web-based, no-code/low-code Power Query experience that users are already familiar with from Excel and Power BI Desktop.</span></span>

<span data-ttu-id="d7516-154">今後 6 か月の間、Microsoft はこの Web ベースの Power Query エクスペリエンスにおけるデータ コネクタとデータ変換のサポートを拡張してゆく予定です。これには、Oracle、Amazon Redshift、Google BigQuery、Impala などのビジネス クリティカルなデータ ソース (オンプレミスおよびクラウド) のサポートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d7516-154">In the next six months, Microsoft will continue expanding support for data connectors and data transformations in this web-based Power Query experience, including support for business-critical data sources (on-premises and cloud), such as Oracle, Amazon Redshift, Google BigQuery, Impala, and others.</span></span>

<span data-ttu-id="d7516-155">また、Power Query Online におけるカスタム コネクタ (Data Connector SDK に基づく) のサポートも追加されます。これにより、パートナーが作成した既存のカスタム コネクタを活用してアプリ用 Common Data Service と Power BI データフローのデータ統合を実現することもできます。</span><span class="sxs-lookup"><span data-stu-id="d7516-155">Microsoft is also adding support for custom connectors (based on the Data Connector SDK) in Power Query Online, so existing custom connectors built by partners can also be leveraged for data integration with Common Data Services for Apps and Power BI dataflows.</span></span>

<span data-ttu-id="d7516-156">さらに、ユーザーがローカル ファイルのアップロードを行えるようになり (一般的な要望)、Power Query Online でファイルからデータをインポートするときのユーザー エクスペリエンスが向上されています。</span><span class="sxs-lookup"><span data-stu-id="d7516-156">The user experience for importing data from files in Power Query Online is also being improved by allowing users to upload local files, which is a common request.</span></span>

![](media/4-1.png "")
<!-- Get Data 5.png -->

<span data-ttu-id="d7516-157">同様に、OneDrive Business/Personal および SharePoint Team Sites など、人気のあるクラウド ベースのファイル ストレージ サービスのファイルを Power Query で参照できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d7516-157">Likewise, Microsoft will enable browsing in Power Query for files in popular cloud-based file storage services, such as OneDrive Business/Personal and SharePoint Team Sites.</span></span> 

##  <a name="certified-custom-connectors-in-power-bi-desktop"></a><span data-ttu-id="d7516-158">Power BI Desktop における認定カスタム コネクタ</span><span class="sxs-lookup"><span data-stu-id="d7516-158">Certified custom connectors in Power BI Desktop</span></span>

<span data-ttu-id="d7516-159">2018 年 4 月に、Microsoft は Power BI の最初のカスタム コネクタをリリースしました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。</span><span class="sxs-lookup"><span data-stu-id="d7516-159">In April 2018, Microsoft released the first custom connectors in Power BI, leveraging the powerful capabilities of the M language to allow partners to write their own connectors and distribute them to every Power BI user.</span></span> <span data-ttu-id="d7516-160">ユーザーはすべてのデータ ソースからコネクタに簡単にアクセスできるようになり、ベンダーも顧客の要望に応じて新しいコネクタを簡単に記述でき、Power BI がベンダーとエンドユーザーの双方にとって最適な BI プラットフォームとなるよう役割が強化されています。</span><span class="sxs-lookup"><span data-stu-id="d7516-160">Now any user can easily access connectors from all their data sources, and vendors can easily write new connectors as their own customers demand, improving Power BI’s role as the best BI platform for both vendors and end users.</span></span>

<span data-ttu-id="d7516-161">2018 年 5 月、既存の Get Data エクスペリエンスとの整合性が図られ、既存の標準コネクタとのシームレスなエクスペリエンスを実現して、シングル クリックで利用できるコネクタの数が大幅に増えました。</span><span class="sxs-lookup"><span data-stu-id="d7516-161">In May 2018, this was brought in line with the existing Get Data experience, making the experience seamless with existing, out-of-the-box connectors, and enabling the number of connectors available with a single click to increase dramatically.</span></span>



