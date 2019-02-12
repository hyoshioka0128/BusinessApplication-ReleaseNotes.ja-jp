---
title: e コマースでのサンプル注文のサポート
description: このトピックでは、総額が $0 の場合でもエラーなしに e コマースの注文を処理できる機能拡張について説明します。
author: hhaines
manager: AnnBe
ms.date: 11/27/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: hhainesms
audience: Admin
ms.openlocfilehash: 1a28ad3a70a2c506575e6d2ca66b854aef3800ea
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199574"
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
