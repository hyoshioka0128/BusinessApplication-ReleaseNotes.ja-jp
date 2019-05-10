---
title: コネクタ プラットフォームと拡張性
description: コネクタ プラットフォームと拡張性
author: schabungbam
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sameerch
ms.reviewer: deonhe
ms.openlocfilehash: 3c7267a83b9f5232563fec0a10756cf3482a7e9a
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225259"
---
# <a name="connector-platform-and-extensibility"></a>コネクタ プラットフォームと拡張性

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

データ統合とそれがサポートする製品スイート (PowerApps、Microsoft Flow、Power BI、Power Query) の重要な要素の 1 つに、外部データ ソースに対する接続性があります。 Microsoft では、エンタープライズ レベルのデータ ソースのセットに引き続き投資していますが、多くのユーザーがそのセット以外にも依存するようになっているデータベースやサービスが増えています。 必要なデータにユーザーが接続できるよう、プラットフォーム全体の拡張性ポイントに引き続き投資しています。 コネクタを開発しようとしている開発者や ISV は、コネクタを作成し、対象の製品に対してコネクタの[認定を受ける](https://aka.ms/connector-certification)ことができます。

## <a name="new-and-enhanced-connectors-for-powerapps-and-microsoft-flow"></a>PowerApps と Microsoft Flow 用の新しいコネクタと改善されたコネクタ

パートナーや ISV によって作成された PowerApps および Microsoft Flow 用のコネクタが継続的に追加されています。 エコシステムが成長するにつれて、より多くのパートナーがコネクタを作成し、認定を受けることを希望しています。 これらのコネクタについては、新しい機能がコネクタに追加されるのに併せて継続的な更新も行われています。

### <a name="connectors-released-in-october-2018"></a>2018 年 10 月にリリースされたコネクタ

* [Rencore](https://docs.microsoft.com/connectors/rencore/)
* [Parseur](https://docs.microsoft.com/connectors/parseur/)
* [Dynamics 365 Business Central (オンプレミス)](https://docs.microsoft.com/connectors/dynamicssmbonprem/)
* [Dynamics 365 Business Central](https://docs.microsoft.com/connectors/dynamicssmbsaas/)

### <a name="connectors-released-in-november-2018"></a>2018 年 11 月にリリースされたコネクタ

* [Stormboard](https://docs.microsoft.com/connectors/stormboard/)
* [Imprezian360-CRM](https://docs.microsoft.com/connectors/imprezian/)
* [Encodian](https://docs.microsoft.com/connectors/encodiandocumentmanager/)
* [Soft1](https://docs.microsoft.com/connectors/soft1/)
* [Zahara](https://docs.microsoft.com/connectors/zahara/)
* [Yeelight](https://docs.microsoft.com/connectors/yeelight/)
* [Windows Defender Advanced Threat Protection (ATP)](https://docs.microsoft.com/connectors/wdatp/)
* [Cloud App Security](https://docs.microsoft.com/connectors/cloudappsecurity/)
* [Webex Teams](https://docs.microsoft.com/connectors/webex/)

### <a name="connectors-released-in-december-2018"></a>2018 年 12 月にリリースされたコネクタ

* [OneBlink](https://docs.microsoft.com/connectors/oneblink/)
* [TDox](https://docs.microsoft.com/connectors/tdox/)
* [CandidateZip](https://docs.microsoft.com/connectors/candidatezip/)
* [Expiration Reminder](https://docs.microsoft.com/connectors/expirationreminder/)
* [Plumsail HelpDesk](https://docs.microsoft.com/connectors/plumsailhelpdesk/)
* [Acumatica](https://docs.microsoft.com/connectors/acumatica/)

### <a name="connectors-released-in-january-2019"></a>2019 年 1 月にリリースされたコネクタ

* [TxtSync](https://docs.microsoft.com/connectors/txtsync/)
* [Ally](https://docs.microsoft.com/connectors/aliru/)
* [Word Online (Business)](https://docs.microsoft.com/connectors/wordonlinebusiness/)
* [Microsoft Graph Security](https://docs.microsoft.com/connectors/microsoftgraphsecurity/)

### <a name="connectors-released-in-february-2019"></a>2019 年 2 月にリリースされたコネクタ

* [XooaDB](https://docs.microsoft.com/connectors/xooadb/)
* [Chainpoint](https://docs.microsoft.com/connectors/chainpointnode/)
* [Projectwise Share](https://docs.microsoft.com/connectors/projectwiseshare/)
* [Ahead](https://docs.microsoft.com/connectors/ahead/)
* [Document Merge](https://docs.microsoft.com/connectors/documentmerge/)

### <a name="connectors-released-in-march-2019"></a>2019 年 3 月にリリースされたコネクタ

* [SignNow](https://docs.microsoft.com/connectors/signnow/)
* [Dynamics 365 Customer Insights](https://docs.microsoft.com/connectors/customerinsights/)
* [Microsoft Forms Pro](https://docs.microsoft.com/connectors/microsoftformspro/)

## <a name="rich-documentation-and-guides-for-developing-connectors"></a>コネクタ開発用の豊富なドキュメントとガイド

今日、既にコネクタを作成しているパートナーがいますが、優れたエンド ユーザー エクスペリエンスを確保するための高度な機能の一部については多くの手間がかかります。 これにより、認定エンジニアの負荷が増大し、開発期間が長くなります。 パートナーや顧客から寄せられるフィードバックで多いのは、カスタム コネクタの作成についてのドキュメントの改善に関するものです。

このリリースでは、コネクタの開発に関する一連の参照資料が更新されています。 ドキュメントと一緒に、認定されるコネクタのガイドラインについて、コネクタを開発する ISV やパートナーに役立つ開発者ガイドも提供されています。 特定のトピックについては、複数のサンプルとガイド付き学習ドキュメントも開発者に役立ちます。 これにより、コネクタを作成するときの開発時間が短縮されます。

## <a name="custom-connector-cli-for-powerapps-and-microsoft-flow"></a>PowerApps および Microsoft Flow 用のカスタム コネクタ CLI

開発者は、[Power Query SDK](https://aka.ms/dataconnectors) を使用して Power BI および Power Query Online 向けの豊富なデータ コネクタを作成できます。また、このリリースには、開発者が PowerApps および Microsoft Flow 用のカスタム コネクタの展開に使用できるコマンド ライン インターフェイス (CLI) スクリプトも含まれています。

## <a name="support-for-policy-templates-in-custom-connectors-for-powerapps-and-microsoft-flow"></a>PowerApps および Microsoft Flow 用カスタム コネクタでのポリシー テンプレートのサポート

PowerApps および Microsoft Flow 用のコネクタを作成しているときに、基になる API の動作の変更が必要になることがよくあります。 現在、これらの動作の変更は、標準の組み込みコネクタに対する Azure APIM ポリシーを使用して実現できます。 現在、多くのコネクタはこれらのポリシーに依存しています。 ただし、APIM ポリシーの最大の欠点は、カスタム コネクタに使用できないことです。 つまり、カスタム コネクタに対する変更はすべて社内で行う必要があります。 コネクタを作成するパートナーは、コネクタの変更および試用やテストについてさえも、Microsoft に頼る必要があります。 これは、パートナーを苛立たせることが多いハイ タッチ開発モデルにつながります。

このリリースでは、PowerApps またはフロー用のカスタム コネクタにポリシーを適用できるようになりました。 ポリシーを使用して、コネクタの特定の動作を変更できます。 たとえば、ポリシーを使用すると、コネクタ内の 1 つ以上の操作での接続からの呼び出し数を制限できます。 他のポリシーでは、ヘッダーやクエリ パラメーターを修正したり、フィールドやパラメーターを変更することさえできます。 ポリシーを使用して、コネクタの全体的なユーザー エクスペリエンスを向上させることができます。

このリリースには、カスタム コネクタで使用するように修正されたポリシー テンプレートのセットが含まれています。 今後、より多くの機能を提供するポリシー テンプレートをさらに追加します。

![コネクタ作成エクスペリエンスでのポリシー テンプレートのモックアップ](media/policy-templates-flow.png "コネクタ作成エクスペリエンスでのポリシー テンプレートのモックアップ")

## <a name="open-source-connector-development-on-github-for-powerapps-and-microsoft-flow"></a>GitHub での PowerApps および Microsoft Flow 用のオープン ソース コネクタの開発

また、Microsoft は率先して、GitHub リポジトリの多くのコネクタにオープン ソースを使用しています。 これにより、開発者エコシステムでは実際のコネクタの例の背後にあるソース コードにアクセスでき、コネクタの改善につながる変更に寄与します。 

Microsoft は、パートナーがオープン ソース コネクタ開発モデルを採用し、コネクタの維持管理に開発者エコシステムを利用することを推奨します。

## <a name="improved-certification-process"></a>認定プロセスの改善

さまざまな開発者やパートナーとともに作業するので、SLA を予測でき、ステータスを確認でき、ヒューマン エラーが少なくなり、認証にかかる時間とプロセスが全体的に向上するように、認証プロセスを改善する必要があります。

GitHub での豊富なツールとオープン ソース開発モデルのサポートにより、コネクタの認定を望む ISV やパートナーは、より簡単な認証プロセスを使用できるようになりました。 このプロセスでは手作業で引き渡す必要がなくなり、代わりに共通のソース コード リポジトリによって行われます。 これにより、コネクタを展開するための認定と追加検証の時間が短縮されます。
