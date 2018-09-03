---
title: "業務プロセス フロー内のカスタム コントロール"
description: "業務プロセス フローは、カスタム コントロールや業務ルールを含むあらゆるフォーム機能をサポートします。"
author: KaranSr
manager: KVivek
ms.date: 8/10/2018
ms.assetid: 357e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: karansr
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 8a89a9ef9d7a84980eeebc44f72692acacc7e744
ms.openlocfilehash: 79228ed622d245d15b9b2b715c8d6509062b8ca9
ms.contentlocale: ja-jp
ms.lasthandoff: 08/20/2018

---
# <a name="custom-controls-in-business-process-flows"></a>業務プロセス フロー内のカスタム コントロール


[!include[banner](../../includes/banner.md)]

業務プロセス フローでは、ステージとステップの形式で作業を行う手順がガイドされます。 ステージはプロセス内での位置を示すのに対し、ステップは目的の結果に至るアクション項目です。 ステップは、アプリ用 Common Data Service (CDS) エンティティのフィールドに対してバインドされており、今のところ、フィールドの種類 (テキスト ボックス、ドロップダウン、数値など) に対して許可されている唯一の既定のビジュアル化です。 このリリースの業務プロセス フローのステップは、スライダー、放射状ノブ、LinkedIn コントロールなどの形式で、リッチなビジュアル化のためのカスタム コントロールをサポートします。 この機能は、統一インターフェイスと Web クライアントの両方で使用できます。

> [!div class="mx-imgBorder"]
> ![カスタム コントロールの例](media/custom-controls_01.png "カスタム コントロールの例")

この機能は、わかりやすくてイマーシブなプロセス ランタイム エクスペリエンスの可能性を高めます。

