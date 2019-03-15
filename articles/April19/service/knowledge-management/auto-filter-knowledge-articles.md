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
ms.openlocfilehash: e297efd83f39c19c4d34e8c0bfa58429b9e39532
ms.sourcegitcommit: 5a7459fc91c2cfa410b32eb645c89aff41ed8e8f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "391630"
---
# <a name="automatic-filtering-of-knowledge-articles"></a><span data-ttu-id="fb52f-103">ナレッジ記事の自動フィルタリング</span><span class="sxs-lookup"><span data-stu-id="fb52f-103">Automatic filtering of knowledge articles</span></span>

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="fb52f-104">管理者は、エージェントからの手動入力なしで、サポート案件データに基づいてナレッジ記事を自動的にフィルタリングするように、サポート情報の検索制御を構成できます。</span><span class="sxs-lookup"><span data-stu-id="fb52f-104">As an administrator, you can configure Knowledge Base search control to automatically filter knowledge articles based on case data, without any manual input from the agents.</span></span>

<span data-ttu-id="fb52f-105">たとえば、サポート案件の情報カテゴリでナレッジ記事の自動フィルタリングを設定した場合、サポート案件と同じ情報カテゴリの記事がフィルターで抽出されて、エージェントに表示されます。</span><span class="sxs-lookup"><span data-stu-id="fb52f-105">For example, if you set up automatic filtering of knowledge articles on case subject, articles with the same subject as case will be filtered in and shown to the agents.</span></span> <span data-ttu-id="fb52f-106">他の記事は自動的に除外されます。</span><span class="sxs-lookup"><span data-stu-id="fb52f-106">Other articles will be filtered out automatically.</span></span> 

<span data-ttu-id="fb52f-107">この機能を拡張して、サポート案件とナレッジ記事エンティティの両方に存在するルックアップ フィールドで、ナレッジ記事を自動的にフィルター処理することができます。</span><span class="sxs-lookup"><span data-stu-id="fb52f-107">This feature can be extended to automatically filter knowledge articles on any lookup field that is present on both Case and Knowledge Article entity.</span></span> <span data-ttu-id="fb52f-108">管理者とエージェントは、自動フィルタリングをオフにして、サポート情報全体が検索されるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="fb52f-108">Administrators and agents will also have an option to turn off automatic filtering and be able to search the entire Knowledge Base.</span></span> 



