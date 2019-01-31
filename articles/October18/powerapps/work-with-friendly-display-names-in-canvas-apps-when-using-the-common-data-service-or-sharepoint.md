---
title: アプリ用 Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する
description: 暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。
author: gregli-msft
ms.reviewer: anneta
ms.date: 12/10/2018
ms.assetid: 491c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: e7e431afb2c9ecf31e50111fe52fe163539c34f1
ms.sourcegitcommit: 4516c399d430cc569513d46822c70670809fe5c6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/12/2019
ms.locfileid: "202453"
---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-for-apps-or-sharepoint"></a>アプリ用 Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する


[!include[banner](../../includes/banner.md)]

Common Data Service と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。  1 つは、開発者向けの「名前」です。これはシステム的な名前で、スペースを使用せず、大文字/小文字の使用も不規則です。アンダースコアを使用して、一意の名前にする必要があります。 もう 1 つは、エンドユーザーに表示されるユーザーにわかりやすい「表示名」です。スペースを使用でき、大文字/小文字も標準の方法で使用されます。この名前はアプリの UI に表示されます。  

これまで、PowerApps では開発者名のみサポートされていました。 今回導入された機能により、表示名を開発者名の代わりに使用できるようになったので、式の読み書きがしやすくなり、わかりやすくなりました。

