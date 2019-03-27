---
title: Power Query
description: Power Query
author: msftman
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: deonhe
ms.openlocfilehash: 16e399f3df7bb8bf3ebeb9ffcf4f9eacfd9ff75a
ms.sourcegitcommit: ca9feb07bc4f4050b7621ba462eb0d3ad5cd8359
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/13/2019
ms.locfileid: "390067"
---
<!--Are the names in the screenshot from an approved fictitious names list?-->


# <a name="power-query-becomes-smarter-and-more-powerful"></a>Power Query がよりスマートかつパワフルに
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]


セルフサービスのデータ準備分野における主な傾向の 1 つは、*スマート データ準備*です。 データ アナリストは AI の力を活用して、自動 (組み込みのレコメンデーションなど) であっても、ユーザーの操作 (AI/ML 関数への呼び出しなど) によるものであっても、AI アルゴリズムへのアクセスを一般化し、データを補完して強化します。

過去 6 か月から 12 か月の間に、Power Query のコア エクスペリエンスに次のようなスマート データ準備機能が多数追加されました。

- **例によるデータ抽出機能**: ユーザーが既存のテーブル列や HTML ページからデータを抽出できるようにします。 これは、ユーザーに一連のサンプルの出力値を指定させ、Power Query にユーザーの意図を推測させた後に AI アルゴリズムを適用することで残りの値を抽出することをベースとしています。  
- **あいまい統合**: 完全一致ではなく、あいまい一致アルゴリズムを使用して複数のテーブルからデータを簡単に結合できるようにします。 
- **データ プロファイリング**: ユーザーが Power Query Editor のデータ プレビュー内でエラー値、空の値、異常値を簡単に特定できるようサポートします。 
- **Power Query Online の組み込みのブラウジングおよび呼び出しエクスペリエンス**: Azure Machine Learning モデルと Azure Cognitive Services の機能を Power BI データフローの通常のデータ準備ステップとして使用します。 これにより Azure クラウド プラットフォームに Cognitive Services のすぐに使える機能を組み込み、組織のデータ サイエンティストが作成した Azure Machine Learning モデルをデータ アナリストと共有して使用できます。  

   ![データ プロファイリングのイメージ](media/data-profiling.png "データ プロファイリングのイメージ")

今後数か月において、Microsoft ではこれをベースに Power Query のスマート データ準備機能を強化し、データ アナリストが少ない労力でより多くの分析情報をデータから得られるようにします。

## <a name="high-enterprise-value-connectors-become-generally-available-for-power-bi-customers"></a>Power BI ユーザーへのエンタープライズ グレードの高レベルなコネクタの一般提供を開始

2019 年の 4 月までに、パブリック プレビューとして最近公開された Power BI のエンタープライズ グレードのコネクタの多くの機能の一般提供が開始されます。その中には次の機能が含まれます。

- Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP BW シングル サインオン (Kerberos)
- Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)
- PDF コネクタ
- Essbase コネクタ
- IBM DB2 DirectQuery

さらに、次のコネクタがパブリック プレビューに入ります。

- AtScale コネクタ

さらに、Power BI ではエンタープライズ ユーザーのフィードバックに基づいて、SAP HANA と SAP BW コネクタの上に、レポートのユーザーが SAP HANA/BW の変数値を PowerBI.com のレポート消費エクスペリエンス内で修正できる新機能をパブリック プレビューとして公開します。

## <a name="power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities"></a>Power Query Online にデータ接続とデータ準備に関わるいくつかの新機能を追加

Power Query は Windows/デスクトップに埋め込み可能なコンポーネント (現在 Power BI Desktop、デスクトップ版 Excel、SQL Server Data Tools と統合) としてのほか、Azure にホストされた Web ベースのサービス (現在 Power BI データフロー、Common Data Service for Apps、Microsoft Flow と統合) として利用できます。

今後 6 か月間で、次のデータ コネクタを Power Query Online に追加します。  

- Amazon Redshift
- Impala
- Apache Spark
- HDInsight Spark
- HDInsight Hive 対話型クエリ
- Vertica
- Google BigQuery
- Teradata
- Informix
- Sybase
- MySQL
- PostgreSQL

## <a name="increased-support-for-developers-on-the-power-query-platform"></a>開発者に対する Power Query プラットフォームに関わるサポートを改善

認定コネクタの一般提供開始と Power BI のカスタム コネクタ開発により、コネクタの開発に使用する同じツールを Power Query プラットフォームで世界中の開発者が利用できるようにしました。

Microsoft では今後 6 か月の間にこのオファーを継続的に開発者に展開し、だれでもデータを Power Query プラットフォームに接続できるようにします。 

開発者は Microsoft のプロセスに従うのではなく、自身の証明書で署名されたコネクタを提供する方法をサポートするよう Microsoft に依頼してきました。 Microsoft では開発者やユーザーがサード パーティによって署名されたコネクタを使用できるようにする方法を導入します。