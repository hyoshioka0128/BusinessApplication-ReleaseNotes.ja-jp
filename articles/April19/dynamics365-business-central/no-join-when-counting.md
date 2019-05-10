---
title: 不要な付属テーブルの結合の削除
description: 不要な付属テーブルの結合の削除
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 3892212f9ce5a11cc8cf5f61b4d44e92e04b6fe6
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225061"
---
# <a name="removed-unnecessary-companion-table-joins"></a>不要な付属テーブルの結合の削除

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

拡張によって拡張されたテーブルに対して AL メソッド COUNT または ISEMPTY を実行するとき、テーブルを拡張するフィールドにフィルターが設定されていない場合、Business Central Server では追加フィールドが格納されている付属テーブルが結合されません。 これにより、パフォーマンスが 2 倍に向上します。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
