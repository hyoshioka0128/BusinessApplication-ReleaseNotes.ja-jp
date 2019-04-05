---
title: Common Data Service for Apps または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する
description: 暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/19/2019
ms.assetid: 491c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: 38f2be4b751f7d2bfb4e87f501cc58bee287d15a
ms.sourcegitcommit: 1a61095607f38831541a95f4ceb2a54bb756a41b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "879662"
---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-for-apps-or-sharepoint"></a>Common Data Service for Apps または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する


[!include[powerapps banner](../includes/powerapps.md)]

Common Data Service for Apps と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。  1 つは、開発者向けの名前です。これはシステム的な名前で、スペースを使用せず、大文字/小文字の使用も不規則です。アンダースコアを使用して、一意の名前にする必要があります。 もう 1 つは、エンドユーザーに表示されるユーザーにわかりやすい「表示名」です。スペースを使用でき、大文字/小文字も標準の方法で使用されます。この名前はアプリの UI に表示されます。  

これまで、PowerApps では開発者名のみサポートされていました。 今回導入された機能により、表示名を開発者名の代わりに使用できるようになったので、式の読み書きがしやすくなり、わかりやすくなりました。