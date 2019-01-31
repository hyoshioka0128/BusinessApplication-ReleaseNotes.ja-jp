---
title: Microsoft Flow Web API が利用可能に
description: Microsoft Flow の API (フローをプログラムで作成、共有、削除する機能など) が文書化されました。
author: KentWeareMSFT
ms.reviewer: deonhe
ms.date: 01/02/2019
ms.assetid: 417e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: c048022d691d492a9085a9ac20cdb5f8keweare
audience: Power user
ms.openlocfilehash: 76ae6004953d45d065042b3e08f7e2123607c6ba
ms.sourcegitcommit: 851bbbbeaac02e33829dfbf5f6f8e4055acf0822
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "203586"
---
# <a name="microsoft-flow-web-apis-available"></a><span data-ttu-id="8e7c6-103">Microsoft Flow Web API が利用可能に</span><span class="sxs-lookup"><span data-stu-id="8e7c6-103">Microsoft Flow Web APIs available</span></span>

<span data-ttu-id="8e7c6-104">アプリケーション ライフサイクル管理タスクの自動化や、テナント内のフローのアクセス許可とガバナンスの自動化を求めるメーカーや管理者からの要望が高まっています。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-104">We are seeing greater demand from makers and administrators who want to automate application lifecycle management tasks and the permissions and governance of flows within a tenant.</span></span> <span data-ttu-id="8e7c6-105">Microsoft は昨半期に、Microsoft Flow からのライフサイクル タスクを自動化できる[豊富な管理コネクタ](https://powerapps.microsoft.com/blog/new-connectors-for-powerapps-and-flow-resources/)を含む、Microsoft Flow のガバナンスについての[この詳細なガイダンス]( https://flow.microsoft.com/blog/security-governance-strategy/)をリリースしました。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-105">Last semester we released [this detailed guidance]( https://flow.microsoft.com/blog/security-governance-strategy/) about governance of Microsoft Flow, including [rich management connectors](https://powerapps.microsoft.com/blog/new-connectors-for-powerapps-and-flow-resources/) that allow you to automate lifecycle tasks from  Microsoft Flow.</span></span>

<span data-ttu-id="8e7c6-106">現在、組織がプロセス簡素化のための追加ツールを任意の言語で作成するために必要なすべての API の完全な文書化を進めています。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-106">Now, we're fully documenting all the APIs that organizations need to build additional tooling to streamline their processes—in whatever language they want.</span></span> <span data-ttu-id="8e7c6-107">この API は、[アプリ用 Common Data Service  Web API](https://docs.microsoft.com/dynamics365/customer-engagement/developer/webapi/perform-operations-web-api) に基づいています。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-107">The APIs are based the [Common Data Service for Apps Web API](https://docs.microsoft.com/dynamics365/customer-engagement/developer/webapi/perform-operations-web-api).</span></span> <span data-ttu-id="8e7c6-108">これには以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-108">They cover:</span></span>

- <span data-ttu-id="8e7c6-109">フローの一覧表示</span><span class="sxs-lookup"><span data-stu-id="8e7c6-109">List flows</span></span>
- <span data-ttu-id="8e7c6-110">フローの作成</span><span class="sxs-lookup"><span data-stu-id="8e7c6-110">Create a flow</span></span>
- <span data-ttu-id="8e7c6-111">フローの更新</span><span class="sxs-lookup"><span data-stu-id="8e7c6-111">Update a flow</span></span>
- <span data-ttu-id="8e7c6-112">フローを共有しているすべてのユーザーの取得</span><span class="sxs-lookup"><span data-stu-id="8e7c6-112">Get all users with whom a flow is shared</span></span>
- <span data-ttu-id="8e7c6-113">フローの共有または共有解除</span><span class="sxs-lookup"><span data-stu-id="8e7c6-113">Share or unshare a flow</span></span>
- <span data-ttu-id="8e7c6-114">フローのエクスポート</span><span class="sxs-lookup"><span data-stu-id="8e7c6-114">Export flows</span></span>
- <span data-ttu-id="8e7c6-115">フローのインポート</span><span class="sxs-lookup"><span data-stu-id="8e7c6-115">Import flows</span></span>

<span data-ttu-id="8e7c6-116">これらの API はメーカーと環境管理者の両方に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-116">These APIs work for both makers and environment administrators.</span></span> <span data-ttu-id="8e7c6-117">これらの API は、Microsoft Flow の**ソリューション** タブに含まれるフローの管理を対象としています。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-117">These APIs cover the management of flows included on the **Solutions** tab in Microsoft Flow.</span></span> <span data-ttu-id="8e7c6-118">現時点では、**マイ フロー**のフローはこれらの API でサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-118">Currently, flows under **My Flows** are not supported by these APIs.</span></span> <span data-ttu-id="8e7c6-119">まずは、Microsoft Flow Web API について詳しく説明している[ドキュメント サイト](https://docs.microsoft.com/flow/web-api)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8e7c6-119">Start on [our documentation site](https://docs.microsoft.com/flow/web-api) with the full Microsoft Flow Web API.</span></span>
