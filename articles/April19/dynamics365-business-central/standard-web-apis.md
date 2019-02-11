---
title: 標準 Web API
description: Business Central では、統合を容易にするために Web API を公開しています
author: henrikwh
ms.reviewer: edupont
ms.date: 01/21/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.author: henrikwh
audience: developer, customizer
ms.openlocfilehash: 2fe3f86669a26b270b980bc556dfeb63506bf64f
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210814"
---
# <a name="standard-web-api"></a><span data-ttu-id="423b8-103">標準 Web API</span><span class="sxs-lookup"><span data-stu-id="423b8-103">Standard web API</span></span> 
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]
<span data-ttu-id="423b8-104">標準 Web API は、ベータ版から移行される予定です。</span><span class="sxs-lookup"><span data-stu-id="423b8-104">The standard web API is moving out of beta.</span></span> <span data-ttu-id="423b8-105">これまで、この API はベータ版として提供され、パートナー コミュニティからのフィードバックに基づいて進化を続けてきました。</span><span class="sxs-lookup"><span data-stu-id="423b8-105">The API has been in beta while evolving based on feedback from the partner community.</span></span> <span data-ttu-id="423b8-106">今リリースでは、API の最終的な機能改善といくつかの新しいエンティティが、バージョン 1.0 として統合されます。</span><span class="sxs-lookup"><span data-stu-id="423b8-106">This release integrates final improvements and several new entities in the API as version 1.0.</span></span>  

## <a name="developer-improvements"></a><span data-ttu-id="423b8-107">開発者にとっての改善点</span><span class="sxs-lookup"><span data-stu-id="423b8-107">Developer improvements</span></span>

- <span data-ttu-id="423b8-108">カスタム名前空間を使用した AL での API 開発</span><span class="sxs-lookup"><span data-stu-id="423b8-108">Developing APIs in AL using custom namespaces</span></span>
- <span data-ttu-id="423b8-109">オープン API 仕様 3.x</span><span class="sxs-lookup"><span data-stu-id="423b8-109">Open API Specification 3.x</span></span>

## <a name="changes-from-beta-to-v10-apis"></a><span data-ttu-id="423b8-110">ベータから v1.0 API に向けての変更点</span><span class="sxs-lookup"><span data-stu-id="423b8-110">Changes from beta to v1.0 APIs</span></span>

- <span data-ttu-id="423b8-111">深いエンティティ入れ子</span><span class="sxs-lookup"><span data-stu-id="423b8-111">Deep entity nesting</span></span>
- <span data-ttu-id="423b8-112">単純キー</span><span class="sxs-lookup"><span data-stu-id="423b8-112">Simple keys</span></span>
- <span data-ttu-id="423b8-113">従業員タイムシート登録 API</span><span class="sxs-lookup"><span data-stu-id="423b8-113">Employee timesheet registration API</span></span>  

## <a name="business-value"></a><span data-ttu-id="423b8-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="423b8-114">Business value</span></span>
<span data-ttu-id="423b8-115">標準 Web API では 48 を超えるエンティティを公開しているため、Business Central への疎結合統合が可能です。</span><span class="sxs-lookup"><span data-stu-id="423b8-115">The standard web API exposes more than 48 entities, enabling loosely coupled integrations to Business Central.</span></span> <span data-ttu-id="423b8-116">この Web API を使用すれば、Business Central 内で開発や展開を行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="423b8-116">If you use the web API, you don't need development or deployment within Business Central.</span></span> <span data-ttu-id="423b8-117">設計の主な目的は、Business Central に関する深い知識がなくても使用できる API を提供することと、Business Central の複数のローカライズや展開を標準化された方法で統合するための、固定バージョンのコントラクトを提供することです。</span><span class="sxs-lookup"><span data-stu-id="423b8-117">Key design objectives have been to provide APIs that do not require deep knowledge of Business Central and to provide a fixed versioned contract, which enables a standardized way to integrate across localizations and deployments of Business Central.</span></span>  

<span data-ttu-id="423b8-118">標準 API は、Business Central オンラインで既定で有効になりますが、オンプレミス展開でも有効にできます。</span><span class="sxs-lookup"><span data-stu-id="423b8-118">The standard API is enabled by default in Business Central online and can be enabled for on-premises deployments as well.</span></span>

### <a name="developing-apis-in-al"></a><span data-ttu-id="423b8-119">AL での API 開発</span><span class="sxs-lookup"><span data-stu-id="423b8-119">Developing APIs in AL</span></span>
<span data-ttu-id="423b8-120">拡張機能では API を公開することができます。これにより、API プラットフォームを Business Central 内で利用することができます。</span><span class="sxs-lookup"><span data-stu-id="423b8-120">Extensions can expose APIs, which takes advantage of the API platform in Business Central.</span></span> <span data-ttu-id="423b8-121">つまり、カスタム API で標準 API と同じ機能を利用できるということです。</span><span class="sxs-lookup"><span data-stu-id="423b8-121">This means that custom APIs have the same capabilities as the standard APIs.</span></span> <span data-ttu-id="423b8-122">これには、WebHooks、OAS 3.0、OData v4、およびバージョン管理のサポートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="423b8-122">This includes support for webhooks, OAS 3.0, OData v4, and versioning.</span></span>  

<span data-ttu-id="423b8-123">API の開発では、*カスタム名前空間*が活用されます。これは、API をグループに分割するための手段です。</span><span class="sxs-lookup"><span data-stu-id="423b8-123">Developing APIs leverages *custom namespaces*—a way to segment APIs into groups.</span></span> <span data-ttu-id="423b8-124">これを使用するには、APIPublisher、APIGroup、および APIVersion の各プロパティを API で指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="423b8-124">This requires the API to specify APIPublisher, APIGroup, and APIVersion properties.</span></span> 

```
page 50100 ApiPageExpenses
{
    PageType = API;
    Caption = 'apiPageName';
    APIPublisher = 'contoso';
    APIGroup = 'expenses';
    APIVersion = 'v2.0';
    EntityName = 'Receipt';
    EntitySetName = 'Receipts';
    SourceTable = ContosoReceipt;
    InsertAllowed = true;
    DeleteAllowed = true;
    layout
    {
        area(Content)
```

<span data-ttu-id="423b8-125">上記の例の場合、展開時にルーティング テーブルが更新され、それにより、指定された名前空間内のエンドポイントが公開されます。</span><span class="sxs-lookup"><span data-stu-id="423b8-125">At deployment time, the example shown above causes routing tables to be updated, and with that exposes the endpoint in the specified namespace.</span></span>

```
GET https://api.businesscentral.dynamics.com/v1.0/api/contoso/expenses/v2.0/companies(7d0b2f2d-150e-4596-b064-e66f3491811c)/Receipts
```

### <a name="open-api-specification-3x"></a><span data-ttu-id="423b8-126">オープン API 仕様 3.x</span><span class="sxs-lookup"><span data-stu-id="423b8-126">Open API Specification 3.x</span></span> 
<span data-ttu-id="423b8-127">Business Central では、OAS 3.0 の生成がサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="423b8-127">Business Central will provide support for generating OAS 3.0.</span></span> <span data-ttu-id="423b8-128">OAS は、ほとんどのプログラミング言語用に SDK を生成できる、共通のメタデータ フォーマットを提供するものです。</span><span class="sxs-lookup"><span data-stu-id="423b8-128">OAS provides a common metadata format from which SDKs can be generated for most programming languages.</span></span>

<span data-ttu-id="423b8-129">2019 年 4 月以降は、Business Central API ドキュメントも OAS を介して生成されるようになります。</span><span class="sxs-lookup"><span data-stu-id="423b8-129">After April 2019, Business Central API documentation will also generate via OAS.</span></span>   

### <a name="deeper-entity-nesting"></a><span data-ttu-id="423b8-130">より深いエンティティ入れ子</span><span class="sxs-lookup"><span data-stu-id="423b8-130">Deeper entity nesting</span></span>
<span data-ttu-id="423b8-131">パーツ ページの制限により、2 レベルより深いエンティティ構造を指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="423b8-131">Due to limitations in Part Pages, it isn't possible to have an entity structure deeper than two levels.</span></span> <span data-ttu-id="423b8-132">例:</span><span class="sxs-lookup"><span data-stu-id="423b8-132">An example is:</span></span>  

```
/journal({id})/journalLine(id)
```

<span data-ttu-id="423b8-133">この例では、当該の制限により、 **journalLines** への**添付ファイル**が使いづらくなっています。リソースを直接アドレス指定する方法がないためです。</span><span class="sxs-lookup"><span data-stu-id="423b8-133">Having that limitation, for this specific example, makes **attachments** to **journalLines** cumbersome to use, as there is no way to address the resource directly:</span></span>

```
/journal({id})/journalLine(id)/attachment(id)
```

<span data-ttu-id="423b8-134">現在のベータ版実装では、**添付ファイル**はルートに配置されます。</span><span class="sxs-lookup"><span data-stu-id="423b8-134">Current beta implementations have **attachments** in the root.</span></span>  

### <a name="simple-keys"></a><span data-ttu-id="423b8-135">単純キー</span><span class="sxs-lookup"><span data-stu-id="423b8-135">Simple keys</span></span>
<span data-ttu-id="423b8-136">マルチパート/複合キーを使用すると、API が使いにくくなります。リクエストを構成するのに、複数のパラメーターが必要になる場合があるためです。</span><span class="sxs-lookup"><span data-stu-id="423b8-136">Multipart/complex keys are making the APIs harder to use, as constructing requests can require several parameters.</span></span> <span data-ttu-id="423b8-137">2019 年 4 月リリースでは、API で単純キーが使用されるようになります。</span><span class="sxs-lookup"><span data-stu-id="423b8-137">By April 2019, APIs will use simple keys.</span></span>


### <a name="employee-timesheet-registration-api"></a><span data-ttu-id="423b8-138">従業員タイムシート登録 API</span><span class="sxs-lookup"><span data-stu-id="423b8-138">Employee timesheet registration API</span></span>
<span data-ttu-id="423b8-139">従業員タイムシートが、標準 API を通じて有効化される予定です。</span><span class="sxs-lookup"><span data-stu-id="423b8-139">Employee timesheets will be enabled through the standard API.</span></span> <span data-ttu-id="423b8-140">現在、Business Central 内のタイムシートでは、従業員の時間登録はリソースに対してサポートされています。</span><span class="sxs-lookup"><span data-stu-id="423b8-140">Timesheets within Business Central currently support employee time registration on resources.</span></span> <span data-ttu-id="423b8-141">現在の実装では、リソースは複数のマシンと人を表すことができます。</span><span class="sxs-lookup"><span data-stu-id="423b8-141">With current implementation, a resource can represent several machines and persons.</span></span> <span data-ttu-id="423b8-142">2019 年 4 月リリースでは、従業員タイムシート登録を使用する場合、時間を登録するリソースが 1 人の従業員を指すようにしなければならなくなります。</span><span class="sxs-lookup"><span data-stu-id="423b8-142">By April 2019, using employee timesheet registration will require the resource to which time is registered to point to one employee.</span></span> 

## <a name="personas"></a><span data-ttu-id="423b8-143">ペルソナ</span><span class="sxs-lookup"><span data-stu-id="423b8-143">Personas</span></span>
<span data-ttu-id="423b8-144">エンド ユーザー、管理者、カスタマイザー、一般開発者、開発者</span><span class="sxs-lookup"><span data-stu-id="423b8-144">End users, admins, customizers, citizen developers, developers</span></span>

## <a name="status"></a><span data-ttu-id="423b8-145">状態</span><span class="sxs-lookup"><span data-stu-id="423b8-145">Status</span></span>
<span data-ttu-id="423b8-146">現在、すべての API はベータ版です。</span><span class="sxs-lookup"><span data-stu-id="423b8-146">Currently all APIs are in beta.</span></span> <span data-ttu-id="423b8-147">2019 年 4 月リリースでは、v1.0 API が公開される予定です (上記の機能改善を含む)。</span><span class="sxs-lookup"><span data-stu-id="423b8-147">By April 2019, v1.0 APIs will be published, containing improvements described above.</span></span> 

## <a name="availability"></a><span data-ttu-id="423b8-148">利用可能性</span><span class="sxs-lookup"><span data-stu-id="423b8-148">Availability</span></span>

<span data-ttu-id="423b8-149">SaaS、オンプレミス</span><span class="sxs-lookup"><span data-stu-id="423b8-149">SaaS, on-premises</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="423b8-150">フィードバック</span><span class="sxs-lookup"><span data-stu-id="423b8-150">Tell us what you think</span></span>

<span data-ttu-id="423b8-151">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="423b8-151">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="423b8-152">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="423b8-152">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>

