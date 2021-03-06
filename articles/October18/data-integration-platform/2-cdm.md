---
title: Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化
description: Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 60626a9d-c022-4a1f-8d3a-0533deba9b45
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: tpalmer
audience: Admin
ms.openlocfilehash: b76ea831b9512b3246633cec14555d51fb84eb85
ms.sourcegitcommit: c258b490eed49dcd0739f795d263189497aeb86c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/07/2019
ms.locfileid: "778594"
---
# <a name="easier-sharing-unification-and-enrichment-of-data-with-common-data-model-entities"></a>Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化




標準エンティティのオープンソース **Common Data Model** の定義が強化されました。セールス、サービス、マーケティング、運営、財務、人材、およびコマースの各業務機能、また顧客のコア エンティティ プロファイル全体で、**ビジネス プロセス、アプリケーション、プロファイル エンリッチメントを統合**でき、観測的なデータ エンリッチメントと分析がサポートされます。

Common Data Model (CDM) は、アプリケーションや展開全体で構造およびセマンティック面での一貫性を保ちながら、よく知られた形式でデータ統合を可能にします。 データを Common Data Model 形式で保存することで、 **多数の幅広いソリューションが効率的に機能する**ようになっています。 このようなデータと分析情報の共有により、新しい業務プロセスや分析ソリューションをすばやく導入し、複雑さを排除しながら事業運営を全方位から視野に入れることができます。

2018 年 3 月の初期リリース以来、公開されている Common Data Model [GitHub リポジトリ](https://github.com/Microsoft/CDM)は、数百もの適切に定義された、モジュラー型で拡張可能なビジネス エンティティへと[大幅に増加](#a-more-expressive-richer-common-data-model)しており、これには戦略的パートナーとの密接なコラボレーションのもとで他の業種をサポートするための大幅な拡張も含まれます。 改善された[ドキュメンテーションとプレゼンテーションのコンテンツ](#common-data-model-community-content)により、顧客とパートナーは Common Data Model についてよりよく理解し、使いこなすことができます。 Power Query によるコーディングなし (またはわずかなコーディング) のデータ統合、変換、およびエンリッチメント エクスペリエンスにより、CDM の[サポートと実装](#built-in-automatic-support-for-the-common-data-model)が引き続き可能です。

##  <a name="a-more-expressive-richer-common-data-model"></a>より表現豊かで豊富な Common Data Model

![プラットフォームと CDM の概要](media/a-more-expressive-richer-common-data-model-1.png "プラットフォームと CDM の概要")
<!-- picture -->

Microsoft は **ISV のエコシステムと協力**して、Common Data Model のリーチと柔軟性を向上させるための業界の拡張機能を作成して、組織の業務プロセスをデジタルに変革するよう支援しています。 これらの拡張機能は、エコシステムの専門知識をベースにして業界の一部を対象としていますが、時間とともに拡大する予定です。 

次にいくつかの例を挙げます。

<a name="industry"></a>
### <a name="industry-extensions-for-strategic-verticals"></a>戦略的な業種向けの業界拡張機能

特定の業種を専門とするパートナーとの協力を通して、Common Data Model は、ヘルスケア、小売、財務分析、教育といった分野で、業界エンティティ パックにより拡張されています。 これらのエンティティ パックは、ビジネス アプリケーション プラットフォーム全体に渡る、より大規模な業界ソリューション オファリングの一部としてリリースされています。

そのようなパートナーに **CUNA Mutual Group** があります。その AdvantEdge Analytics ソリューションは、信用組合がメンバーへのサービスを向上するのに役立っています。 Common Data Model と標準データ コネクタの拡張機能により、信用組合が使用する基幹業務向けアプリのデータを統合することができます。 

<a name="dynamics"></a>
### <a name="key-scenarios-from-popular-dynamics-offerings"></a>人気のある Dynamics オファリングにおける主要なシナリオ
人気のある Dynamics オファリングにおける主要なシナリオを対象として、他の CDM エンティティの定義が追加されています。これには、Finance、Operations、Marketing のシナリオも含まれます。 更新された Dynamics アプリケーションとともに、顧客は独自のシナリオでこれらの標準エンティティを活用できます。 

##  <a name="common-data-model-community-content"></a>Common Data Model のコミュニティ コンテンツ

Common Data Model とデータ統合のコンテンツは CDM GitHub のリポジトリを補完し、ガイダンス、詳細記事、ベスト プラクティスを提供します。

<a name="explorer"></a>
### <a name="common-data-model-entity-explorer"></a>Common Data Model のエンティティ エクスプローラー

このインタラクティブかつグラフィカルなエンティティ エクスプローラーは、顧客とパートナーが、ビジネス アプリケーションとアナリティカル ソリューションの開発において既存の Common Data Model エンティティをより良く理解して活用するのに役立ちます。 詳細なエンティティと属性メタデータの説明により、このモデルの豊富なセマンティックに対する分析情報をもたらします。

<a name="docs"></a>
### <a name="improved-documentation-and-presentation-content"></a>ドキュメンテーションとプレゼンテーションのコンテンツの向上
顧客およびパートナー向けのドキュメンテーションとプレゼンテーションのコンテンツが充実したことにより、Common Data Model に何が含まれるのか、プラットフォーム内でどのように有効活用できるのか、また CDM ベスト プラクティスに従ってどのようにカスタマイズできるのかをより良く理解できるようになります。

また、アプリケーション、データ モデル、データ統合、およびテンプレートの開発者コミュニティをサポートするために、ディスカッション フォーラムも立ち上げられています。

加えて、パートナーは、CDM における潜在的な[業種向けの機能拡張](#industry-extensions-for-strategic-verticals)において**戦略的パートナーになるための方法**について明確なガイダンスを見つけることができ、CDS プラットフォームにより多くのアプリケーションをもたらして、ISV およびアプリ開発者のエコシステムをさらに強化することができます。 

-   これらのソリューションや具体的なユースケースにより、どのように顧客とパートナーが共同でより簡単にソリューションの使用と構築を (CDM と CDS プラットフォームの上で) 成功させることができるのか、またそれによって、追加のアプリや統合による充実したエコシステムがどのように形成されるかに関する説明。

-   これらの CDM 拡張機能を活用する AppSource のパッケージ化されたターンキー ソリューションの詳細と入手方法。

-   これら戦略パートナーの共同声明および共同顧客の生の経験。

レコードと SaaS サービスのシステムを CDS に接続する**データ統合テンプレートとソリューションの構築**に興味があるコンサルタントは、標準コネクタ、Data Connector SDK、およびデータを Common Data Model エンティティに変換するためのガイダンスとベスト プラクティスによるサポートが得られます。


##  <a name="built-in-automatic-support-for-the-common-data-model"></a>Common Data Model の組み込み型自動サポート 

Power Query のデータ統合エクスペリエンス、データ統合テンプレート、アプリ用 CDS、および Power BI データフローは、Common Data Model を実装しています。 Common Data Model およびそれがサポートする製品スイートとエクスペリエンスの重要な特徴は拡張性です。 

**データ統合テンプレート**は、一般的な基幹業務アプリケーションや SaaS サービスから、有名な Common Data Model エンティティの形式にデータを統合するのを加速します。 たとえば、Salesforce テンプレートは、顧客がデータを CDS および Power BI データフローに統合して、それによってセールスの機会やパイプラインに関する分析情報を取得するのに役立ちます。 また、テンプレートの[追加の機能](4-data-integration-admin.md#templates)では、エンド カスタマーのためにこの機能が拡張される予定です。
