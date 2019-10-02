---
title: Power Query
description: Power Query
author: msftman
ms.date: 03/29/2019
ms.topic: article
ms.service: business-applications
ms.author: deonhe
ms.openlocfilehash: cc49e5643138351fa31b180fe2f2b5c7e9a21e36
ms.sourcegitcommit: 6dace9a8682f19cf4b3a514283a5acf3d16bcc89
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/06/2019
ms.locfileid: "1991417"
---
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

## <a name="high-enterprise-value-connectors-become-generally-available-for-power-bi-customers"></a>Power BI ユーザーへのエンタープライズ レベルの高レベルなコネクタの一般提供を開始

2019 年の 9 月までに、パブリック プレビューとして最近公開された Power BI のエンタープライズ レベルのコネクタの多くの機能の一般提供が開始されます。その中には次の機能が含まれます。

- Power BI サービスでの (オンプレミス データ ゲートウェイ経由) SAP BW シングル サインオン (Kerberos)
- Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)
- PDF コネクタ
- Essbase コネクタ
- IBM DB2 DirectQuery
- PostgreSQL のネイティブ クエリの折り重ね
- Power Platform データフロー

さらに、次のコネクタがパブリック プレビューに入ります。

- AtScale コネクタ

さらに、Power BI ではエンタープライズ ユーザーのフィードバックに基づいて、SAP HANA と SAP BW コネクタの上に、レポートのユーザーが SAP HANA/BW の変数値を PowerBI.com のレポート消費エクスペリエンス内で修正できる新機能をパブリック プレビューとして公開します。

## <a name="power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities"></a>Power Query Online にデータ接続とデータ準備に関わるいくつかの新機能を追加

Power Query は Windows/デスクトップに埋め込み可能なコンポーネント (現在 Power BI Desktop、デスクトップ版 Excel、SQL Server Data Tools と統合) としてのほか、Azure にホストされた Web ベースのサービス (現在 Power BI データフロー、Common Data Service for Apps、Microsoft Flow と統合) として利用できます。

今後 6 か月間で、次のデータ コネクタを Power Query Online に追加します。  

- Amazon Redshift
- Impala
- Vertica
- Teradata
- MySQL
- PostgreSQL

## <a name="increased-support-for-developers-on-the-power-query-platform"></a>開発者に対する Power Query プラットフォームにかかわるサポートを改善

認定コネクタの一般提供開始と Power BI のカスタム コネクタ開発により、コネクタの開発に使用する同じツールを Power Query プラットフォームで世界中の開発者が利用できるようにしました。

Microsoft では今後 6 か月の間にこのオファーを継続的に開発者に展開し、だれでもデータを Power Query プラットフォームに接続できるようにします。 

開発者は Microsoft のプロセスに従うのではなく、自身の証明書で署名されたコネクタを提供する方法をサポートするよう Microsoft に依頼してきました。 Microsoft では開発者やユーザーがサード パーティによって署名されたコネクタを使用できるようにする方法を導入します。
