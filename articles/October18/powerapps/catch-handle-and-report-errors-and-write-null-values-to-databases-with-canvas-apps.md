---
title: Catch, handle, and report errors, and write Null values to databases with canvas apps
description: App makers can take control of errors when they happen and, as a side benefit, write Null values.
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: c198c53f04636c4cbef3f6723cfa5246afc06cfa
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み (パブリック プレビュー)


[!include[banner](../../includes/banner.md)]

アプリを作成中にエラーが発生するのは仕方がないことです。  キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、希望するものとは異なる場合があります。  With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.

Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.  Null is a legitimate value in many database systems.  With errors properly separated out in canvas apps, you can write Null values to all databases.

