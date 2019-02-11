---
title: Common Data Model (CDM)
description: Common Data Model (CDM)
author: theresapalmer
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: deonhe
ms.openlocfilehash: 7484d9f7a4742b7d979d9a0642ab84949a014fe7
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210747"
---
# <a name="common-data-model-cdm"></a>Common Data Model (CDM)
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]


現在の Common Data Model (CDM) では、モジュール式で拡張可能なビジネス エンティティ (取引先企業、リード、営業案件など) と、観察データの概念 (リンクのクリックや電子メールのオープンなど) が提供されています。 それにより、よく知られたスキーマ内のデータと、データ サイロ、アプリケーション、展開をまたがって一貫性を持つセマンティックが統合されます。

> [!div class="mx-imgBorder"]
> ![CDM によりプロデューサーとコンシューマーがデータ レイク内で相互作用できる](media/common-data-model-cdm-1.png "CDM によりプロデューサーとコンシューマーがデータ レイク内で相互作用できる")

CDM の形式でデータを実装、生成、消費する製品、プラットフォーム、サービスの範囲は、Microsoft の内外で拡大し続けています。

## <a name="additional-capabilities-and-features-as-part-of-the-open-data-initiative"></a>Open Data Initiative の一環としての追加機能

Open Data Initiative の一環として、創設パートナー間の "1 つのデータ モデル" により、基盤となるデータとメタデータに直接アクセスすることで、インテリジェンスと知識の作成シナリオのための顧客所有の共有データ レイクがサポートされます。 創設パートナー (および追加パートナー) は、データと明確に定義されたセマンティック メタデータをそのデータ レイクに格納し、そこから取得します。 これは Azure Data Lake Storage (ADLS) Gen2 の最初のバージョンの "CDM フォルダー" に似ていますが、複数の Azure データ サービスとパートナー (Informatica など) がそれに向けて構築することで、大きな進化が必要です。

既存のトランザクション プラットフォーム (CDS など) 上には膨大な量の既存の顧客データとアプリケーションが存在しており、それらを同じ "1 つのデータ モデル" に収束させることは簡単な問題ではありません。 データがレイクにシームレスかつ自動的に格納されることを保証する必要があります。 同様に、共有データ レイクから分析情報を取得し、それらの分析情報をプラットフォームに戻すことも、簡単でなければなりません。 これにより、Adobe および SAP のデータ資産を当社の AI およびインテリジェンス オファリングに含めるための取り組みも拡張されます。

## <a name="updated-developer-and-consumer-documentation"></a>開発者および消費者向けドキュメントの更新

Common Data Model は範囲と機能が進化し続けているため、消費者と開発者の両方に対する公開ドキュメントの重要性が増しています。 公開ドキュメント セットに対する追加のクイック スタートやベスト プラクティスなどのリリースにより、CDM に関心のある人ならだれでもその力を最大限に活用する方法を学ぶことができる場所が提供されます。

## <a name="cdm-schema-documents"></a>CDM スキーマ ドキュメント

CDM スキーマの定義は、エコシステムからのニーズに基づいて改善され続けています。 たとえば、名前空間処理のサポートの追加により、パートナーは自分のソリューションに固有の概念として識別およびバージョン管理できるスキーマを CDM 形式で開発およびリリースできます。 また、CDM スキーマ ドキュメントの正式なバージョン管理体系もリリースされました。 この体系により、プロデューサーとコンシューマーは、サポートしているバージョンを確実に報告および識別できます。

## <a name="sdk-and-tooling"></a>SDK とツール

CDM 形式のデータを作成および利用できるよう、CDM 形式のコンテンツを探索、読み取り、変更、作成するための SDK とツールがリリースされました。 これらのツールにより、開発者はさまざまなプラットフォームやサービスでイニシアチブにアクセスしやすくなります。 これらのツールにより、増え続けている CDM 形式対応のサービスやエクスペリエンスの集合にデータが提供されます。

## <a name="new-entity-definitions"></a>新しいエンティティの定義

CDM は、コア Dynamics 365 ソリューションからリリースされる新しい業界アクセラレーターと概念によって拡大を続けています。 たとえば、教育業界や非営利産業からのアクセラレーターのリリース、および医療アクセラレーターの更新により、CDM モデルに 100 を超える新しいエンティティがもたらされました。 さらに、Dynamics 365 for Finance and Operations、Marketing、Talent などからのエンティティ定義により、CDM とあらゆる規模の顧客やパートナーとの関連が強化され続けています。
