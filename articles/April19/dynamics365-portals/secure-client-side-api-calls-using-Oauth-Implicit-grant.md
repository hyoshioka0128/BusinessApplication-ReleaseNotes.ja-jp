---
title: ポータルでの外部データの表示
description: ポータルでの外部データの表示
author: dileepsinghmicrosoft
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dileeps
ms.reviewer: shjais
ms.openlocfilehash: 7e5266e9c93a46336b29788e788797b05f5d077c
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "211103"
---
#  <a name="displaying-external-data-in-portals"></a>ポータルでの外部データの表示
[!include[dynamics365-portals banner](../includes/dynamics365-portals.md)]


## <a name="business-value"></a>ビジネス バリュー

外部アプリケーションからデータを取得し、それらを安全な方法でポータルに表示できるようにする機能は、ポータルのお客様から多く寄せられていたニーズの 1 つです。 この機能を使用すると、お客様はクライアント側から外部 API を呼び出し、OAuth Implicit Grant Type フローを使用して、それらを保護することができます。

## <a name="personas"></a>ペルソナ

- ポータル管理者
- ポータルのカスタマイズ担当者

## <a name="features"></a>機能

この機能では、安全なアクセストークンを取得するためのエンドポイントが提供されます。これらのアクセス トークンに格納されるユーザー ID 情報は、外部 API によって、OAuth Implicit Grant Type フローに従った認証に使用できます。
