---
title: カスタム コネクタから Azure サービスへの接続
description: ユーザーは、より簡単に Azure サービスのデータにアクセスできるカスタム コネクタを作成できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: 2587bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 938f8a9b4c6afcd695ed392a0ced532cb720720d
ms.sourcegitcommit: 8edb4083244f1fd7bc34d165af28550093070daa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/12/2019
ms.locfileid: "1870854"
---
# <a name="connect-to-azure-services-from-custom-connectors"></a>カスタム コネクタから Azure サービスへの接続



Azure Functions または Azure Logic Apps でホストされている RESTful API がある場合は、それをインポートして、Microsoft Flow や PowerApps で使用できるカスタム コネクタを簡単に作成できるようになります。

ユーザーに求められるのは、サイド バーで**データ**の下にある**カスタム コネクタ** ページに移動することだけです。 **+ 新しいカスタム コネクタ**をクリックして、**Azure サービスから作成する (プレビュー)** を選択します。

![新しいカスタム API](media/azure-connectors-1.jpg)

次に、コネクタの名前を指定して、Azure サブスクリプションを選択し、Azure サービスを選択してから、アプリを選択します。

![Azure サービスを選択する](media/azure-connectors-2.jpg)

**続行**をクリックすると、API がカスタム コネクタ ポータルにインポートされるので、そこで他の詳細を追加し、コネクタを作成して、テストできます。

![構成する](media/azure-connectors-3.jpg)

作成された新しいコネクタは、[カスタム コネクタ] ページと、Flow Designer でフローに使用するときに表示されます。

![新しいコネクタを使用する](media/azure-connectors-4.jpg)

## <a name="azure-functions-setup"></a>Azure Functions のセットアップ

Azure Functions では、API を Microsoft Flow にインポートする前に特定の条件を満たす必要があります。 Microsoft Flow または PowerApps で使用する予定の場合は、次のことに留意してアプリを作成してください。

1.  [アプリ ランタイム バージョンを設定する](https://docs.microsoft.com/azure/azure-functions/functions-openapi-definition#set-the-functions-runtime-version)
1.  [OpenAPI 定義を生成する (Swagger)](https://docs.microsoft.com/azure/azure-functions/functions-openapi-definition#generate-the-openapi-definition)

    > [!NOTE]
    > Azure では、API をホストする URL を提供するか、Azure portal に提供されているテンプレートに基づいて定義を生成することができます。 Azure テンプレートを使用することを選択した場合は、HTTP によってトリガーされた関数からのメタデータを使用してスパース定義が作成されます。 ただし、使用する前にそれを変更し、API 操作とデータ構造に関する追加のメタデータを提供する必要があります。
1.  [クロス オリジン リソース共有 (CORS) の構成を有効にする](https://docs.microsoft.com/azure/azure-functions/functions-how-to-use-azure-function-app-settings#cors)

## <a name="still-to-come"></a>今後の予定

Azure のリソースを使用してカスタム コネクタを作成するプロセスを合理化するための他の方法を模索しています。 たとえば、Swagger のインポート後に API キー ベースの接続をテストする場合は、Azure portal から API キーをコピーして Microsoft Flow に貼り付ける必要なしに、Azure Functions アプリで定義されたキーに基づいて自動的にテスト接続を作成することを検討しています。

Oauth 認証を使用するカスタム コネクタのインポート エクスペリエンスも向上します。 最後に、近々サポートする Azure サービスを増やす予定なので、目を離さないでください。
