---
title: テーブル フィールドの最大可変長の増加
description: テーブル フィールドの最大可変長の増加
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: de56a4cc9a35e514970854d4deb6a0d64d1c5dc1
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878724"
---
# <a name="increased-maximum-length-of-text-and-code-fields-variables-and-text-constants"></a>テキストおよびコード フィールド、変数、およびテキスト定数の最大長の増加

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

テキストおよびコード タイプのテーブル フィールド、変数、テキスト定数に使用できる最大文字数が増えました。 新しい制限は次のとおりです。

|  |  |
|--|--|
|テーブル フィールド|コードの指定最大長: 2048<br />テキストの指定最大長: 2048|
|変数|コードの指定最大長: 2048<br />テキストの指定最大長: 2048|
|テキスト定数|テキスト定数の最大長: 2048|

> [!NOTE]
> 長さが指定されていない場合、テキスト変数の長さはこれまでと同様に無制限です。 これは、実際には Int32.MaxValue によって制御されます。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
