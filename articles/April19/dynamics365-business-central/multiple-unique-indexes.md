---
title: 複数の固有キー
description: 複数の固有キー
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: b72dafd23f1f9f445d2348d2c44637fb4d0d8e9a
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225050"
---
# <a name="multiple-unique-keys"></a>複数の固有キー

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

AL のキー定義には Unique プロパティが含まれるようになり、それを使用して SQL Server のテーブルに一意制約を作成できます。 固有キーは、テーブル内のレコードが同じフィールド値を持たないようにします。 固有キーがあると、テーブルが検証されるときに、キー値の一意性がチェックされます。 テーブルに重複値を持つレコードが含まれていると、検証は失敗します。 固有インデックスのもう 1 つの利点は、より効率的な実行計画を作成するのに役立つ情報がクエリ オプティマイザーに提供されることです。

主キーと同様に、複数のフィールドで構成される固有の予備キーを作成できます。 この場合、一意でなければならないのは予備キーの値の組み合わせです。 たとえば、Customer テーブルがある場合、Name、Address、City フィールドに固有キーを作成して、これらのフィールドの値の同じ組み合わせを持つ顧客がいないようにできます。 主キーとは異なり、1 つのテーブルに複数の固有予備キーを定義することができます。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
