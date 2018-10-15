---
title: "アプリ用 Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する"
description: "暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。"
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 491c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: 6b558cfedafa239a3a641fcf40961e834ccc50c7
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-for-apps-or-sharepoint"></a>Work with friendly display names in canvas apps when using Common Data Service for Apps or SharePoint


[!include[banner](../../includes/banner.md)]

Common Data Service と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。  First, there's a developer-friendly name, which is somewhat cryptic, with no spaces, odd capitalization, underscores, and a requirement to be unique. Then there's a user-friendly name, meant for end users to see, with spaces and standard capitalization, displayed in the app's UI.  

To date, PowerApps has only supported the developer names. With this feature, authors can now work with display names instead, making reading and writing of formulas easier and clearer.


