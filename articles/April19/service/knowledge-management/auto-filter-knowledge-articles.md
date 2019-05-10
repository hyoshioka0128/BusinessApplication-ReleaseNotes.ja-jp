---
title: Dynamics 365 for Customer Service でのナレッジ記事の自動フィルタリングを理解する
description: Dynamics 365 for Customer Service でナレッジ記事の自動フィルタリングがどのように動作するのかを説明します
ms.date: 02/14/2019
ms.assetid: 516afbde-61a3-4718-8ce1-a4007ada5960
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
author: Karthik55217
ms.author: Karthig
ms.reviewer: anjgupta
audience: Admin
ms.openlocfilehash: e3047b3fc4dfdc0185886fcaed7a5e4182ab188f
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225439"
---
# <a name="automatic-filtering-of-knowledge-articles"></a><span data-ttu-id="1efd8-103">ナレッジ記事の自動フィルタリング</span><span class="sxs-lookup"><span data-stu-id="1efd8-103">Automatic filtering of knowledge articles</span></span>



<span data-ttu-id="1efd8-104">管理者は、エージェントからの手動入力なしで、サポート案件データに基づいてナレッジ記事を自動的にフィルタリングするように、サポート情報の検索制御を構成できます。</span><span class="sxs-lookup"><span data-stu-id="1efd8-104">As an administrator, you can configure Knowledge Base search control to automatically filter knowledge articles based on case data, without any manual input from the agents.</span></span>

<span data-ttu-id="1efd8-105">たとえば、サポート案件の情報カテゴリでナレッジ記事の自動フィルタリングを設定した場合、サポート案件と同じ情報カテゴリの記事がフィルターで抽出されて、エージェントに表示されます。</span><span class="sxs-lookup"><span data-stu-id="1efd8-105">For example, if you set up automatic filtering of knowledge articles on case subject, articles with the same subject as case will be filtered in and shown to the agents.</span></span> <span data-ttu-id="1efd8-106">他の記事は自動的に除外されます。</span><span class="sxs-lookup"><span data-stu-id="1efd8-106">Other articles will be filtered out automatically.</span></span> 

<span data-ttu-id="1efd8-107">この機能を拡張して、サポート案件とナレッジ記事エンティティの両方に存在するルックアップ フィールドで、ナレッジ記事を自動的にフィルター処理することができます。</span><span class="sxs-lookup"><span data-stu-id="1efd8-107">This feature can be extended to automatically filter knowledge articles on any lookup field that is present on both Case and Knowledge Article entity.</span></span> <span data-ttu-id="1efd8-108">管理者とエージェントは、自動フィルタリングをオフにして、サポート情報全体が検索されるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="1efd8-108">Administrators and agents will also have an option to turn off automatic filtering and be able to search the entire Knowledge Base.</span></span> 



