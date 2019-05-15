---
title: サンドボックスでのレポート作成のパフォーマンス
description: サンドボックスでのレポート作成のパフォーマンス
author: KennieNP
ms.reviewer: edupont
ms.date: 02/27/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: dfb48bcb8c853eab576dd5a8962e825da5d8c464
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224902"
---
# <a name="rdlc-reporting-performance-on-sandboxes"></a>(RDLC) サンドボックスでのレポート作成のパフォーマンス

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Dynamics NAV 2013 R2 の出荷前に、RDLC レポートのランタイムで大きなパフォーマンスのリグレッションが発見されました。 これは、.NET バージョン 4.0 にアップグレードしたためであり、RDLC レポートをパフォーマンスを低下させることなく機能させるために、レガシ コードのアクセス セキュリティ ポリシーを使用するよう .NET ランタイムを設定する必要がありました。 5 年後に、Business Central サンドボックスでのデバッグを有効にしました。 これには、サンドボックス クラスターでのコード アクセス セキュリティを無効にする必要がありました。 残念ながら、これにより RDLC レポートのパフォーマンスに関する古いリグレッションが再現しました。 Business Central の 2019 年 4 月リリースでは、RDLC レポートを別の .NET AppDomain で完全に実行することで、パフォーマンスの問題を解消しました。

## <a name="solved-memory-leak-in-rdlc-reporting"></a>RDLC レポートでの解決されたメモリ リーク

Business Central Server での RDLC の古い実装では、レポート実行時にわずかなメモリ リークが発生していました。 Business Central の 2019 年 4 月リリースでは、レポートに使用される .NET AppDomain を定期的にリサイクルするため、このメモリ リークは発生しなくなりました。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
