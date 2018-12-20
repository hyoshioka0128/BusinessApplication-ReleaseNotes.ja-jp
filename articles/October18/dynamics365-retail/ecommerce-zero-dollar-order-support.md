---
title: "e コマースでのサンプル注文のサポート"
description: "このトピックでは、総額が $0 の場合でもエラーなしに e コマースの注文を処理できる機能拡張について説明します。"
author: hhaines
manager: AnnBe
ms.date: 11/27/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: hhainesms
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 08fffd56773d83d916e88529f3d225b141e679cc
ms.openlocfilehash: 3b42b777c1af4a0b8bd3200f79ddd5ac85a9f06e
ms.contentlocale: ja-jp
ms.lasthandoff: 12/07/2018

---

# <a name="support-for-sample-orders-in-ecommerce"></a>e コマースでのサンプル注文のサポート

一部の小売業者は、顧客にオンライン サイトを通じてサンプルを購入する機会を提供しています。 サンプルにはコストがかからず、顧客はサンプル品目の代金を支払う必要はありません  (これは、カーペット/フローリング、ペイント、窓処理などの業界では一般的です)。場合によっては、小売業者はサンプルを一定の期間内に返却してもらう必要があります。 顧客が指定された期間内にサンプルを返さないと、クレジット カードに請求されます。 

Dynamics 365 for Retail の現在の e コマース チェックアウトでは、ユーザーが価格 $0 で注文を送信しようとするとエラーがスローされます。 新しい設計変更により、$0 での注文が許可されます。

この修正により、サンプルを提供する業界の小売業者や、オンライン ストアからの注文が可能な他の無料品目がサポートされます。 サンプル注文は、これらの小売業者の e コマース サイトから作成および処理することができます。


<!--
## License Required
No specific licensing requirements are required.
## Setup Required
No specific setup is required.
## Status
Development complete
## Target Timeframe
8.1.3 update
## Regional Availability
Global
-->

