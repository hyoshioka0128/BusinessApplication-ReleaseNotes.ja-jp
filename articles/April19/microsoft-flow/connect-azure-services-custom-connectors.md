---
title: カスタム コネクタから Azure サービスへの接続
description: ユーザーは、より簡単に Azure サービスのデータにアクセスできるカスタム コネクタを作成できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/06/2019
ms.assetid: 2587bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: e4406d1f17d18f70b4664b2e195be42b5603fee6
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621635"
---
# <a name="connect-to-azure-services-from-custom-connectors"></a><span data-ttu-id="81bec-103">カスタム コネクタから Azure サービスへの接続</span><span class="sxs-lookup"><span data-stu-id="81bec-103">Connect to Azure services from custom connectors</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="81bec-104">Azure Functions または Azure Logic Apps でホストされている RESTful API がある場合は、それをインポートして、Microsoft Flow や PowerApps で使用できるカスタム コネクタを簡単に作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="81bec-104">If you have a RESTful API hosted in Azure Functions or Azure Logic Apps, there is now a simple way you can import it to create a custom connector that can be used in Microsoft Flow and PowerApps.</span></span>

<span data-ttu-id="81bec-105">ユーザーに求められるのは、サイド バーで**データ**の下にある**カスタム コネクタ** ページに移動することだけです。</span><span class="sxs-lookup"><span data-stu-id="81bec-105">All you need to do is navigate to the **Custom Connectors** page under **Data** on the sidebar.</span></span> <span data-ttu-id="81bec-106">**+ 新しいカスタム コネクタ**をクリックして、**Azure サービスから作成する (プレビュー)** を選択します。</span><span class="sxs-lookup"><span data-stu-id="81bec-106">Click **+ New custom connector** and select **Create from Azure Service (Preview)**.</span></span>

![新しいカスタム API](media/azure-connectors-1.jpg)

<span data-ttu-id="81bec-108">次に、コネクタの名前を指定して、Azure サブスクリプションを選択し、Azure サービスを選択してから、アプリを選択します。</span><span class="sxs-lookup"><span data-stu-id="81bec-108">Next, give your connector a name, select your Azure subscription, choose the Azure service, and then select your app.</span></span>

![Azure サービスを選択する](media/azure-connectors-2.jpg)

<span data-ttu-id="81bec-110">**続行**をクリックすると、API がカスタム コネクタ ポータルにインポートされるので、そこで他の詳細を追加し、コネクタを作成して、テストできます。</span><span class="sxs-lookup"><span data-stu-id="81bec-110">When you click **Continue**, it will import your API into the custom connector portal where you can add additional details, create the connector, and test it.</span></span>

![構成する](media/azure-connectors-3.jpg)

<span data-ttu-id="81bec-112">作成された新しいコネクタは、[カスタム コネクタ] ページと、Flow Designer でフローに使用するときに表示されます。</span><span class="sxs-lookup"><span data-stu-id="81bec-112">Once created, you’ll see your new connector on the Custom Connectors page as well as in the Flow designer when using it in a flow.</span></span>

![新しいコネクタそ使用する](media/azure-connectors-4.jpg)

## <a name="azure-functions-setup"></a><span data-ttu-id="81bec-114">Azure Functions のセットアップ</span><span class="sxs-lookup"><span data-stu-id="81bec-114">Azure Functions setup</span></span>

<span data-ttu-id="81bec-115">現在、Azure Functions では、特定の条件を満たしていない API は Microsoft Flow にインポートできません。</span><span class="sxs-lookup"><span data-stu-id="81bec-115">Azure Functions currently requires that your API meets certain conditions before it can be imported to Microsoft Flow.</span></span> <span data-ttu-id="81bec-116">Microsoft Flow または PowerApps で使用する予定の場合は、次のことに留意してアプリを作成してください。</span><span class="sxs-lookup"><span data-stu-id="81bec-116">Be sure you have built your app with these in mind if you plan to use it in Microsoft Flow or PowerApps:</span></span>

1.  [<span data-ttu-id="81bec-117">アプリ ランタイムのバージョンは 1 以下である必要があります</span><span class="sxs-lookup"><span data-stu-id="81bec-117">App runtime version must be ~1</span></span>](https://docs.microsoft.com/azure/azure-functions/functions-openapi-definition#set-the-functions-runtime-version)
2.  [<span data-ttu-id="81bec-118">OpenAPI 定義を生成します (Swagger)</span><span class="sxs-lookup"><span data-stu-id="81bec-118">Generate the OpenAPI definition (Swagger)</span></span>](https://docs.microsoft.com/azure/azure-functions/functions-openapi-definition#generate-the-openapi-definition)
    *   <span data-ttu-id="81bec-119">注: Azure では、API をホストする URL を提供するか、Azure portal で提供されているテンプレートに基づいて定義を生成することができます。</span><span class="sxs-lookup"><span data-stu-id="81bec-119">Note: In Azure, you can either provide the URL that hosts your API or generate the definition based on the template provided in the Azure portal.</span></span> <span data-ttu-id="81bec-120">Azure のテンプレートを使用することを選択した場合は、HTTP によってトリガーされた関数からのメタデータを使用してスパース定義が作成されます。</span><span class="sxs-lookup"><span data-stu-id="81bec-120">If you choose to use Azure’s template, it will create a sparse definition with the metadata from your HTTP-triggered functions.</span></span> <span data-ttu-id="81bec-121">ただし、使用する前にそれを変更し、API 操作とデータ構造に関する追加のメタデータを提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="81bec-121">However, you’ll want to modify it and provide additional metadata about the API operations and data structures before using it.</span></span>
3.  [<span data-ttu-id="81bec-122">クロス オリジン リソース共有 (CORS) の構成を有効にする</span><span class="sxs-lookup"><span data-stu-id="81bec-122">Enable Configure Cross-Origin Resource Sharing (CORS)</span></span>](https://docs.microsoft.com/azure/azure-functions/functions-how-to-use-azure-function-app-settings#cors)

## <a name="still-to-come"></a><span data-ttu-id="81bec-123">今後の予定</span><span class="sxs-lookup"><span data-stu-id="81bec-123">Still to come</span></span>

<span data-ttu-id="81bec-124">Azure のリソースを使用してカスタム コネクタを作成するプロセスを合理化するための他の方法を模索しています。</span><span class="sxs-lookup"><span data-stu-id="81bec-124">We’re exploring other ways we can streamline the process to create custom connectors using your Azure resources.</span></span> <span data-ttu-id="81bec-125">たとえば、Swagger のインポート後に API キー ベースの接続をテストする場合は、Azure portal から API キーをコピーしてする Flow ポータルに貼り付ける必要なしに、Azure Functions アプリで定義されたキーに基づいて自動的にテスト接続を作成することを検討しています。</span><span class="sxs-lookup"><span data-stu-id="81bec-125">For example, when testing an API Key-based connection after importing the Swagger, we’re looking into automatically creating a test connection for you based on a key defined in your Azure Functions app rather than requiring you to copy the API Key from the Azure portal and pasting it into the Flow portal.</span></span>

<span data-ttu-id="81bec-126">Oauth 認証を使用するカスタム コネクタのインポート エクスペリエンスも向上します。</span><span class="sxs-lookup"><span data-stu-id="81bec-126">There will also be improvements in the importing experience for custom connectors that use OAuth authentication.</span></span> <span data-ttu-id="81bec-127">最後に、近々サポートする Azure サービスを増やす予定なので、目を離さないでください。</span><span class="sxs-lookup"><span data-stu-id="81bec-127">Finally, we plan to support more Azure services in the near future so keep an eye out.</span></span>
