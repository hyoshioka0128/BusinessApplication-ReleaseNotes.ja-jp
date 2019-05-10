---
title: 依存関係を持つアクションを変更する
description: 出力が他のステップで使用されるトリガーとアクションの名前を変更すること、および削除することができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/14/2019
ms.assetid: 1d87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 72d772a9b77a5ce8f56c67f6982d2e5c28c6fbcb
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445496"
---
# <a name="change-actions-that-have-dependencies"></a>依存関係を持つアクションを変更する

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

自動化されたフローの強力な特徴の 1 つは、任意のアクションにおいて、フロー内で上流にあるトリガーまたはアクションによって出力されたデータを使用できることです。 ただし、変更したいステップがフローの先頭にあり、他のアクションがそのステップに依存している場合、これは容易ではありません。 以前は、フロー設計者が、ユーザーがそのような変更を行うことをブロックしていました。そのような変更を行うと、フロー内の他のアクションが中断されるためです。

新しい**フロー チェッカー**では、フロー内で修復が必要なアクションが強調表示されます。 これで、他のステップが依存しているアクションを削除または名前変更することができます。 **フロー チェッカー**を使用して、発生する問題を解決します。
