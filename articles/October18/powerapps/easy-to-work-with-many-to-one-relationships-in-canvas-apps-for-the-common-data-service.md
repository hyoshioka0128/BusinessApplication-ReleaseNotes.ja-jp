---
title: "アプリ用 Common Data Service のキャンバス アプリで多対一リレーションシップを簡単に操作"
description: "手動で参加または検索する必要がありません。 PowerApps は多対一リレーションシップを自動で拡張するため、必要な情報はすぐそこにあります。"
author: gregli-msft
manager: KVivek
ms.date: 11/26/2018
ms.assetid: 421c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: bed7137531560ede4b30b6f50cc45f8df572e874
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a><span data-ttu-id="11a6a-104">アプリ用 Common Data Service のキャンバス アプリで多対一リレーションシップを簡単に操作</span><span class="sxs-lookup"><span data-stu-id="11a6a-104">Easy to work with many-to-one relationships in canvas apps for Common Data Service for Apps</span></span>




<span data-ttu-id="11a6a-105">リレーショナル データの活用はほとんどのビジネス アプリケーションで鍵となります。</span><span class="sxs-lookup"><span data-stu-id="11a6a-105">Working with relational data is key to most business applications.</span></span> <span data-ttu-id="11a6a-106">とはいえ、必要な情報を取り込み、外部キーを組み込み、プロジェクションを制御するクエリを記述するのは面倒な場合があります。</span><span class="sxs-lookup"><span data-stu-id="11a6a-106">Yet it can be tedious to write queries that pull in the necessary information, join on foreign keys, and control the projection.</span></span>

<span data-ttu-id="11a6a-107">この機能により、キャンバス アプリ開発者はアプリ用 Common Data Service を使うと簡単に行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="11a6a-107">With this feature, it all becomes a lot easier for canvas app makers when they use Common Data Service for Apps.</span></span> <span data-ttu-id="11a6a-108">たとえば、アプリ用 CDS の標準モデルには、取引先担当者エンティティを示す PrimaryContact を参照する取引先企業エンティティがあります。</span><span class="sxs-lookup"><span data-stu-id="11a6a-108">For example, in the CDS for Apps standard model, there is an Account entity with a lookup for PrimaryContact that points to the Contacts entity.</span></span> <span data-ttu-id="11a6a-109">仮に、ギャラリー コントロール内で主要な取引先担当者の姓を表示する必要があるとします。</span><span class="sxs-lookup"><span data-stu-id="11a6a-109">Let's say you need to display the last name of the primary contact in a gallery control.</span></span> <span data-ttu-id="11a6a-110">この場合に記述する必要があるのは **ThisItem.PrimaryContact.LastName** だけです。</span><span class="sxs-lookup"><span data-stu-id="11a6a-110">All you need to write is **ThisItem.PrimaryContact.LastName**.</span></span> <span data-ttu-id="11a6a-111">取引先担当者データ ソースを読み込む必要はありません。</span><span class="sxs-lookup"><span data-stu-id="11a6a-111">The Contacts data source doesn't even need to be loaded.</span></span> <span data-ttu-id="11a6a-112">PowerApps はアプリを分析して、どの検索が望ましいかを識別し、プロジェクションに必要なフィールドのみを取り込みます。</span><span class="sxs-lookup"><span data-stu-id="11a6a-112">PowerApps analyzes the app to determine which lookups are desired and to bring in only the fields that are required for the projection.</span></span>

