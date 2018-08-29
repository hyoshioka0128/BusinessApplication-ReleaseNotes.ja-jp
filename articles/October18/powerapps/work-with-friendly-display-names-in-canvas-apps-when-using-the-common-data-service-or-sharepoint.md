---
title: "アプリ用 Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する"
description: "暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。"
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 491c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: 6b558cfedafa239a3a641fcf40961e834ccc50c7
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-for-apps-or-sharepoint"></a>アプリ用 Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する


[!include[banner](../../includes/banner.md)]

Common Data Service と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。  1 つは、開発者向けの名前です。これはやや暗号的な名前で、スペースを使用せず、大文字/小文字の使用も不規則です。アンダースコアを使用して、一意の名前にする必要があります。 もう 1 つは、エンドユーザーに表示されるユーザー フレンドリ名です。スペースを使用でき、大文字/小文字も標準の方法で使用されます。この名前はアプリの UI に表示されます。  

これまで、PowerApps では開発者名しかサポートされていませんでした。 今回導入された機能により、表示名を開発者名の代わりに使用できるようになったので、式の読み書きがしやすくなり、わかりやすくなりました。


