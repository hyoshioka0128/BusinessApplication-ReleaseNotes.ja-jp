---
title: キャンバス アプリでの多対多リレーションシップのサポート強化
description: キャンバス アプリケーションで一対多および多対多の関係をたどり、レコード相互の関連付け/関連付け解除を行います
author: gregli-msft
ms.reviewer: anneta
ms.date: 01/08/2019
ms.assetid: ccc7655b-30e1-e811-a97a-000d3a137063
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: b460f24bdb3aa0cc4919e37a1ab03287c3b8c61a
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "286605"
---
# <a name="better-support-for-many-to-many-relationships-in-canvas-apps-public-preview"></a>キャンバス アプリでの多対多リレーションシップのサポート強化 (パブリック プレビュー)


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

ビジネス データはリレーショナルです。 顧客、従業員、供給業者、荷主、製品、在庫が、注文と発注を通じて相互に関連しています。 Common Data Service (CDS) for Apps では、これらのリレーションシップが一対多、多対一、または多対多のリレーションシップとしてモデル化されます。

作成者は、以前の多対一リレーションシップで行ったのと同じように、単純なオブジェクト ドット表記を使用して、CDS for Apps のこれらすべての種類のリレーションシップをたどることができます。 たとえば、注文.従業員.名前は、注文エンティティから多対一のリレーションシップをたどって従業員エンティティに至り、名前フィールドを取得します。 逆に、従業員.注文では、この従業員が割り当てた注文のテーブルが返され、多対多のリレーションシップも同じ方法で処理されます。 さらに、多対多のリレーションシップはどちらのエンティティのルックアップ フィールドにも基づいていないため、作成者は新しい関数を使用してレコードを関連付けたりレコードの関連付けを解除したりすることができます。

![簡単な式で製品エンティティから選択した製品のレビューまでたどる](media/OneToMany.png "簡単な式で製品エンティティから選択した製品のレビューまでたどる")
