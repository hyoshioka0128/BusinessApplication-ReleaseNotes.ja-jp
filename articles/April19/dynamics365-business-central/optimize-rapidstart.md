---
title: ラピッドスタートの最適化
description: ラピッドスタートの最適化
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 96dad2dcdfe69876834687182e49686c2d49093a
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878731"
---
# <a name="rapidstart-optimization"></a>ラピッドスタートの最適化

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

ラピッドスタートとも呼ばれる構成パッケージのパフォーマンスが向上しました。 各テーブル ノードを順番に処理する代わりに、多数の行を含むノードをバックグラウンド セッションに並列に送信し、システムが過負荷にならないように同時バックグラウンド セッションの数を調整します。 この最適化の影響として、ラピッドスタート パッケージのインポートが約 2 倍速くなり、パッケージの削除が 3 倍以上速くなっています。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
