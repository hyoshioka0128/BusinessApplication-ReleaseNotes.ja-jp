---
title: 自動フローによる CDS for Apps での変更セットのサポート
description: 変更セットのスコープについてのネイティブな理解が Microsoft Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 1b7458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 8e5f6cd71712c621b5ddaa1ededa7c50ef25b772
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287505"
---
# <a name="automated-flows-support-change-sets-in-cds-for-apps"></a>自動フローによる CDS for Apps での変更セットのサポート


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

すべての操作はアトミックと見なされ、これはいずれかの操作が失敗した場合は完了したすべての操作がロールバックされることを意味するので、変更セットは Common Data Service (CDS) for Apps の処理における重要な部分です。 これは、*トランザクション*と呼ばれることがよくあります。

変更セットのスコープについてのネイティブな理解が Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。

![Flow での変更セット](media/ChangeSets-1.png "Flow での変更セット")

変更セットは**バッチ** スコープの内部に追加することができます。 これを使用するには、**Common Data Service** コネクタで**変更セット**を探します。 このスコープを Microsoft Flow デザイナーに追加した後は、CDS の作成、更新、または削除アクションをその中に追加できます (読み取り操作を変更セットに含めることはできません)。

> [!NOTE]
> 変更セット スコープに他のサービスのアクションを含めることはできません。 そのような場合は、バッチの前後で他のアクションを実行する必要があります。