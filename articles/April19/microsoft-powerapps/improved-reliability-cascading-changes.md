---
title: カスケード変更の信頼性の向上
description: 多数のレコードに影響を与えるカスケード変更は、バックグラウンドで処理されます。 これにより、UI との対話がより迅速にユーザーに返され、データベース タイムアウトが減少し、大規模なカスケード実行の成功率が向上します。
author: ''
ms.reviewer: ''
ms.date: 09/06/2019
ms.assetid: bad86458-45a7-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: nhelgren
audience: Power user
ms.openlocfilehash: 84053e220105156b75d013aaaec90c774a07e068
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994292"
---
# <a name="improved-reliability-of-cascading-changes-public-preview"></a><span data-ttu-id="81cae-104">カスケード変更の信頼性の向上 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="81cae-104">Improved reliability of cascading changes (Public Preview)</span></span>



<span data-ttu-id="81cae-105">100 を超えるレコードに影響するカスケード変更 (割り当て、削除) は、バックグラウンドで非同期に処理されます。</span><span class="sxs-lookup"><span data-stu-id="81cae-105">Cascading changes (assign, delete) that affect more than 100 records will be processed in the background asynchronously.</span></span> <span data-ttu-id="81cae-106">これにより、ユーザーは UI との対話をより早く再開でき、カスケード変更を処理するときの UI とデータベースのタイムアウトが削減されます。</span><span class="sxs-lookup"><span data-stu-id="81cae-106">This allows users to resume interaction with the UI sooner and reduces UI and database timeouts when processing cascading changes.</span></span> <span data-ttu-id="81cae-107">これらの変更をバックグラウンドで処理すると、多数のレコードが関係する場合に成功率が高くなり、システムで実行されている他のプロセスが変更によってブロックされるのを防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="81cae-107">Processing these changes in the background allows for a higher rate of success when large numbers of records are involved and prevents the changes from blocking other processes that are being run on the system.</span></span> 

<span data-ttu-id="81cae-108">最初の変更が行われてからすべてのレコードが処理されるまでに遅延があります。</span><span class="sxs-lookup"><span data-stu-id="81cae-108">There will be a delay between when the initial change is made and when all records have been processed.</span></span> <span data-ttu-id="81cae-109">遅延期間は、処理されたレコードの数に基づきます。</span><span class="sxs-lookup"><span data-stu-id="81cae-109">The delay duration will be based on the number of records processed.</span></span> <span data-ttu-id="81cae-110">バックグラウンド処理のステータスは、**ジョブ** リストを使用して組織の**設定**で表示できます。</span><span class="sxs-lookup"><span data-stu-id="81cae-110">The status of the background processing can be viewed in the **Settings** for the organization using the **Jobs** list.</span></span>
