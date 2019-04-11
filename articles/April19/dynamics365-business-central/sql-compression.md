---
title: SQL Server データ圧縮のサポート
description: SQL Server データ圧縮のサポート
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: f47ada053b21d0e4464676b80a2879a4e494e9ac
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878733"
---
# <a name="support-for-sql-server-data-compression"></a>SQL Server データ圧縮のサポート

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Business Central では 2019 年 4 月現在、SQL Server データ圧縮の使用はサポートされている構成です。

データ圧縮を使用し、データベース内のテーブルを選択してサイズを減らすことができます。 スペースの節約に加えて、データ圧縮は、データがより少ないページに格納され、クエリでディスクから読み取る必要があるページが少なくなるので、 I/O 集約型ワークロードのパフォーマンスの向上に役立ちます。 これは、ストレージ システムが SSD ではなくディスクに基づいている場合に特に便利です。

AL の CompressionType プロパティを使用することにより、テーブルのメタデータで圧縮を構成し、Business Central のテーブル同期プロセスに SQL Server テーブルの変更を処理させることも、SQL Server で直接データ圧縮を制御することもできます。

SQL Server ではパーティション レベルでデータ圧縮がサポートされるため、SQL Server のデータ圧縮とテーブルのパーティション分割を組み合わせることにより、テーブルのアクティブな部分に CPU のオーバーヘッドをかけることなく、大きなテーブルの履歴部分に対する柔軟なデータ アーカイブを実現できます。

> [!NOTE]
> SQL Server 2016 SP1 より前は、SQL Server のすべてのエディションで圧縮を利用できませんでした。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
