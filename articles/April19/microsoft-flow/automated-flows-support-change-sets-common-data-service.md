---
title: 自動フローによる Common Data Service での変更セットのサポート
description: 変更セットのスコープについてのネイティブな理解が Microsoft Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: 0187bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ad6380295e5727024c07f255177d04cf0d01f168
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757027"
---
# <a name="automated-flows-support-change-sets-in-common-data-service"></a>自動フローによる Common Data Service での変更セットのサポート

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

変更セットは Common Data Service に関する作業の重要な部分です。その理由は、すべての操作がアトミックと見なされることです。つまり、いずれかの操作が失敗した場合は、完了したすべての操作がロールバックされます。 これは、*トランザクション*と呼ばれることがよくあります。

変更セットのスコープについてのネイティブな理解が Flow デザイナーに追加され、ユーザーはこれまでアトミックなトランザクションを必要とした従来の Common Data Service ワークフローを置き換えることができるようになりました。

![Flow での変更セット](media/ChangeSets-1.png "Flow での変更セット")

変更セットは**バッチ** スコープの内部に追加することができます。 これを使用するには、**Common Data Service** コネクタで**変更セット**を探します。 このスコープを Microsoft Flow デザイナーに追加した後は、Common Data Service の作成、更新、または削除アクションをスコープの内部に追加できます (読み取り操作を変更セットに含めることはできません)。

> [!NOTE]
> 変更セット スコープに他のサービスのアクションを含めることはできません。 そのような場合は、バッチの前後で他のアクションを実行する必要があります。
