---
title: "強化され、より統合されたコネクターと開発者エコシステム"
description: "強化され、より統合されたコネクターと開発者エコシステム"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 64dd4753-dced-47af-8087-0a75f48a4a2d
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3b01ce72e354533570465a5953bf12d1412327f5
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="richer-and-more-unified-connector-and-developer-ecosystem"></a>強化され、より統合されたコネクターと開発者エコシステム

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




データ統合とそれがサポートする製品スイートの重要な要素の一つに、外部データ ソースに対する接続性があります。 Microsoft では、エンタープライズ レベルのデータ ソースのセットに引き続き投資していますが、多くのユーザーがそのセット以外にも依存するようになっているデータベースやサービスが増えています。 必要なデータにユーザーが接続できるよう、プラットフォーム全体の拡張性ポイントに引き続き投資しています。

## <a name="improved-development-for-connectors-across-the-platform"></a>プラットフォーム全体のコネクタに対する開発の向上

プラットフォーム用にコネクタを作成する開発者や ISV は、PowerApps、Microsoft Flow、および Logic Apps のアクションとトリガーでコネクタを作成するか、Power BI 用のリッチ データ コネクタを作成することができます。 また、開発者および ISV はデータ統合を介してアプリケーション向け Common Data Service および Power BI データフローのコネクタを作成できます。 フル プラットフォームのサポートに関心がある ISV は今それを行えます。

このリリースには、プラットフォーム全体でコネクタの作成、テスト、リリースを行えるよう、ISV および開発者向けに多くの機能強化が含まれています。  Power Query SDK の一般提供に伴い、開発者は、Power BI、アプリケーション向け Common Data Service、および Power BI データフローのリッチ コネクタを作成するために、成熟したプラットフォームにアクセスできるようになりました。  開発者にはガイドとなる豊富なドキュメントおよびサンプルが準備されており、SDK の新しい機能を使用してカスタム コネクタの署名、バージョン管理、検証を行うことができます。  [ここから Power Query SDK](https://aka.ms/dataconnectors) にアクセスできます。

プレビュー機能の一つとして、フル プラットフォームで機能するシングル コネクタがあります。最初から開発することも、既存の OpenAPI 定義から作成することもできます。  そのようなコネクタの作成に関心のある開発者は、Microsoft PowerApps、Microsoft Flow、または Logic Apps にあるカスタム コネクタ ポータルで開始するか、利用可能になった Power Query Data Connector SDK で開始することができます。 開発者は、フル プラットフォームで正しいコンポーネントを生成することができます。
Microsoft Flow と PowerApps での現在のインライン テスト エクスペリエンスに加えて、Power BI Desktop またはオンプレミス データ ゲートウェイで使用するためにコネクタをダウンロードして、それらの製品で完全なエンド ツー エンドのテストを行うこともできます。

![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "ナビゲーターの ListContacts")
<!-- picture -->

## <a name="improved-consumption-for-connectors"></a>コネクタの消費の向上
このリリースでは、Power BI Desktop のコネクタおよびオンプレミス データ ゲートウェイを介して消費エクスペリエンスを向上させるために、統合エクスペリエンスが提供されるようになっています。  パートナーや ISV が作成した認定コネクタを簡単に見つけて Power BI Desktop で使用できるようになりました。
この統合により、コネクタが多くの統合に追加されることになり、エコシステムの開発者と消費者にとってエクスペリエンスが改善されます。  オンプレミス データ ゲートウェイの個人およびエンタープライズ バージョンの両方で、認定コネクタおよびカスタム コネクタの検出とデータ更新がサポートされるようになっています。

-  [Power BI Desktop での認定コネクタのサポート](1-power-query.md#certified-custom-connectors-in-power-bi-desktop)
-  [個人およびエンタープライズ ゲートウェイのカスタム コネクタのサポート](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop)


## <a name="unified-connector-certification-program"></a>統一コネクタ認定プログラム
コネクタを作成する開発者や ISV は、認定用にコネクタを Microsoft に提出することができます。
認定されたコネクタは公開され、エンドユーザーに統合エクスペリエンスを提供します。
また、サービスのリーチ、見つけやすさ、使用率を向上することになります。

コネクタ認定プログラムでは、次の基本要件を満たすパートナー作成コネクタであればどれでも提出できます。

- 提出者は、コネクタが対象としているサービスの関係者である。
- コネクタは、対象プラットフォームのビジネス ユーザー シナリオをサポートしている。

詳細については、[コネクタ認定プログラム](https://aka.ms/connector-certification)をご覧ください。


