---
title: SQL Database のデッドロックの監視 - ファイルベースの xe ターゲット
description: SQL Database のデッドロックの監視 - ファイルベースの xe ターゲット
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 710ffca59f8179558d8a623166b51f20e77b3055
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878520"
---
# <a name="monitoring-sql-database-deadlocks-using-file-based-xe-targets"></a>ファイルベースの xe ターゲットを使用した SQL Database のデッドロックの監視

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

既定では、SQL Server は ring_buffer ターゲットと呼ばれるメモリ内データ構造を使用してデッドロック イベントを格納します。 Business Central Server はデッドロックに関する通知を受け取ると、対象の ring_buffer ターゲットからデータを読み取ります。 これに加えて、イベントを SQL Server 上の event_file ターゲットと呼ばれるファイルに格納し、ring_buffer ターゲットの代わりにこのファイルからデータを読み取るように Business Central サーバーを構成できるようになりました。 ring_buffer ターゲットと event_file ターゲットの重要な違いは、ring_buffer ターゲットには 5 MB というストレージ サイズ制限があるのに対し、event_file ターゲットでははるかに大きいストレージ容量が提供されるという点です。 event_file ターゲットを使用すると、大量のデータを処理する状況で発生する可能性のある過負荷を解消できます。 そのため、設定で大量のデータベース トラフィックがあるときは、event_file ターゲットにデッドロックを書き込むように SQL Server を変更することが必要な場合があります。 既定の ring_buffer ターゲットを使用する場合は、それ以上のアクションは不要です。

詳細については、「[SQL Database のデッドロックの監視](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-deadlocks#configure-where-to-store-deadlock-events)」を参照してください。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
