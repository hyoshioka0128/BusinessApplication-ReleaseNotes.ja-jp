---
title: Common Data Service for Apps または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する
description: 暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/04/2019
ms.assetid: 491c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: f11a7b9f2672fc76a1f1c3e5eee38d30436876e6
ms.sourcegitcommit: b0c22af04369d4d8d0d0a5d67c06d26b3474ceb6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/11/2019
ms.locfileid: "379414"
---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-for-apps-or-sharepoint"></a><span data-ttu-id="7bd94-104">Common Data Service for Apps または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する</span><span class="sxs-lookup"><span data-stu-id="7bd94-104">Work with friendly display names in canvas apps when using Common Data Service for Apps or SharePoint</span></span>


[!include[powerapps banner](../includes/powerapps.md)]

<span data-ttu-id="7bd94-105">Common Data Service for Apps と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。</span><span class="sxs-lookup"><span data-stu-id="7bd94-105">Both Common Data Service for Apps and SharePoint maintain two names for every table and field.</span></span>  <span data-ttu-id="7bd94-106">1 つは、開発者向けの名前です。これはシステム的な名前で、スペースを使用せず、大文字/小文字の使用も不規則です。アンダースコアを使用して、一意の名前にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7bd94-106">First, there's a developer-friendly name, which is somewhat cryptic, with no spaces, odd capitalization, underscores, and a requirement to be unique.</span></span> <span data-ttu-id="7bd94-107">もう 1 つは、エンドユーザーに表示されるユーザーにわかりやすい「表示名」です。スペースを使用でき、大文字/小文字も標準の方法で使用されます。この名前はアプリの UI に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7bd94-107">Then there's a user-friendly name, meant for end users to see, with spaces and standard capitalization, displayed in the app's UI.</span></span>  

<span data-ttu-id="7bd94-108">これまで、PowerApps では開発者名のみサポートされていました。</span><span class="sxs-lookup"><span data-stu-id="7bd94-108">To date, PowerApps has only supported the developer names.</span></span> <span data-ttu-id="7bd94-109">今回導入された機能により、表示名を開発者名の代わりに使用できるようになったので、式の読み書きがしやすくなり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="7bd94-109">With this feature, authors can now work with display names instead, making reading and writing of formulas easier and clearer.</span></span>