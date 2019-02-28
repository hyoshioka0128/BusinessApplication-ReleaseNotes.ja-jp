---
title: 自動フローによる CDS for Apps でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 1f7458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 0018849723c6214f53a49660357b06a4b137fe49
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210479"
---
# <a name="automated-flows-support-batch-operations-in-cds-for-apps"></a>自動フローによる CDS for Apps でのバッチ操作のサポート


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

Common Data Service (CDS) for Apps で一度に多くのアクションを実行したい場合 (100 個の異なるレコードを一度に挿入するなど)、通常であれば Microsoft Flow によって CDS for Apps に対する多くの異なる呼び出しが行われます。 これでもうまくいきますが、そのようなフローを実行すると長い時間がかかることがよくあります。

このリリースでは、フローに**バッチ** スコープを追加して、すべての異なる操作を CDS for Apps の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。 これを使用するには、**Common Data Service** コネクタで**バッチ**を探します。 このスコープを Microsoft Flow デザイナーに追加した後は、任意の CDS for Apps アクションをその中に追加できます。 バッチ スコープに他のサービスのアクションを含めることはできません。 そのような場合は、バッチの前後で他のアクションを実行する必要があります。

> [!div class="mx-imgBorder"]
> ![フローのバッチ スコープ](media/BatchOperations-1.png "フローのバッチ スコープ")

バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。 取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。
