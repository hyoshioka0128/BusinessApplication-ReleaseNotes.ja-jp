---
title: 買掛金勘定仕入先請求書の為替レート フィールドでの変更
description: 仕入先請求書承認仕訳帳での為替レートのロック
author: aprilolson
ms.date: 04/25/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: f064903bbb37e5674ca9da7d04e6ef4cc4526e2c
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225534"
---
# <a name="accounts-payable-vendor-invoice-change-with-exchange-rate-field"></a>買掛金勘定仕入先請求書の為替レート フィールドでの変更
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


仕入先請求書の承認プロセスで使用される為替レートが、請求書の登録に使用されたレートと同じになります。 これにより、請求書登録の見越計上エントリが承認仕訳帳の転記プロセスで正しく取り消されるようになります。 仕入先請求書承認仕訳帳の為替レート フィールドは、変更を防ぐためにロックされます。
