---
title: 自動フローによる Common Data Service でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/06/2019
ms.assetid: ff86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 3f1a1bf012b4d064cfca0038fa074a4fbad50f38
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621657"
---
# <a name="automated-flows-support-batch-operations-in-common-data-service"></a>自動フローによる Common Data Service でのバッチ操作のサポート

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

Common Data Service で一度に多くのアクションを実行したい場合 (100 個の異なるレコードを一度に挿入するなど)、通常であれば Microsoft Flow によって Common Data Service に対する多くの異なる呼び出しが行われます。 これでもうまくいきますが、そのようなフローを実行すると長い時間がかかることがよくあります。

このリリースでは、フローに**バッチ** スコープを追加して、すべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。 これを使用するには、**Common Data Service** コネクタで**バッチ**を探します。 このスコープを Microsoft Flow デザイナーに追加したら、任意の Common Data Service アクションをその中に追加できます。 バッチ スコープに他のサービスのアクションを含めることはできません。 そのような場合は、バッチの前後で他のアクションを実行する必要があります。

![フローのバッチ スコープ](media/BatchOperations-1.png "フローのバッチ スコープ")

バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。 取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。
