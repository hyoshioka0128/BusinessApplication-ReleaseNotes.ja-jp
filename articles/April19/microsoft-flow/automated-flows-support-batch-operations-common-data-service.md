---
title: 自動フローによる Common Data Service でのバッチ操作のサポート
description: フローにバッチ スコープを追加して、これらすべての異なる操作を Common Data Service の 1 回の呼び出しにまとめることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/30/2019
ms.assetid: ff86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 1dc8637555002cc65bb75829a629971f9d6071d5
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445790"
---
# <a name="automated-flows-support-batch-operations-in-common-data-service"></a>自動フローによる Common Data Service でのバッチ操作のサポート

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

Common Data Service で一括操作 (100 個の異なるレコードを挿入するなど) を実行する場合、通常であれば、Microsoft Flow によって Common Data Service に対する複数の呼び出しが行われます。 これでも問題なく機能しますが、フローの実行に長い時間がかかることがあります。

今回、フローに **バッチ** スコープを追加できるようになりました。 このスコープにより、すべての操作を Common Data Service の 1 回の呼び出しにまとめることができ、パフォーマンスが劇的に向上します。 このスコープを使用するには、**Common Data Service** コネクタで**バッチ**を探します。 このスコープを Microsoft Flow デザイナーに追加したら、任意の Common Data Service アクションをその中に追加できます。 **バッチ** スコープに他のサービスのアクションを含めることはできません。 そのような場合は、**バッチ**の前後で他のアクションを実行する必要があります。

![Flow のバッチ スコープ](media/BatchOperations-1.png "Microsoft Flow のバッチ スコープ")

バッチ要求を使用するのが最善なのは、相互に関連付けられていないエンティティに対して操作を実行する場合であることに注意してください。 取引先企業の主要な取引先担当者の取得など、関連付けられているレコードに対する操作の中には、バッチ処理を使用せずに単一の操作で実行できるものがあります。
