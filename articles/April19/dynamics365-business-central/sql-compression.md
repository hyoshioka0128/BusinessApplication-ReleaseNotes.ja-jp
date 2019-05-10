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
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224901"
---
# <a name="support-for-sql-server-data-compression"></a><span data-ttu-id="23154-103">SQL Server データ圧縮のサポート</span><span class="sxs-lookup"><span data-stu-id="23154-103">Support for SQL Server data compression</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="23154-104">Business Central では 2019 年 4 月現在、SQL Server データ圧縮の使用はサポートされている構成です。</span><span class="sxs-lookup"><span data-stu-id="23154-104">As of Business Central April 2019, the use of SQL Server data compression is a supported configuration.</span></span>

<span data-ttu-id="23154-105">データ圧縮を使用し、データベース内のテーブルを選択してサイズを減らすことができます。</span><span class="sxs-lookup"><span data-stu-id="23154-105">You can use data compression to help reduce the size of selected tables in the database.</span></span> <span data-ttu-id="23154-106">スペースの節約に加えて、データ圧縮は、データがより少ないページに格納され、クエリでディスクから読み取る必要があるページが少なくなるので、I/O 集約型ワークロードのパフォーマンスの向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="23154-106">In addition to saving space, data compression can help improve performance of I/O intensive workloads because the data is stored in fewer pages and queries have to read fewer pages from disk.</span></span> <span data-ttu-id="23154-107">これは、ストレージ システムが SSD ではなくディスクに基づいている場合に特に便利です。</span><span class="sxs-lookup"><span data-stu-id="23154-107">This is especially useful if your storage system is based on disks and not SSD.</span></span>

<span data-ttu-id="23154-108">AL の CompressionType プロパティを使用することにより、テーブルのメタデータで圧縮を構成し、Business Central のテーブル同期プロセスに SQL Server テーブルの変更を処理させることも、SQL Server で直接データ圧縮を制御することもできます。</span><span class="sxs-lookup"><span data-stu-id="23154-108">By using the CompressionType property in AL, you can either configure compression in metadata for a table, and let the Business Central table synchronization process handle the changes to SQL Server tables, or you can choose to control data compression directly on SQL Server.</span></span>

<span data-ttu-id="23154-109">SQL Server ではパーティション レベルでデータ圧縮がサポートされるため、SQL Server のデータ圧縮とテーブルのパーティション分割を組み合わせることにより、テーブルのアクティブな部分に CPU のオーバーヘッドをかけることなく、大きなテーブルの履歴部分に対する柔軟なデータ アーカイブを実現できます。</span><span class="sxs-lookup"><span data-stu-id="23154-109">Because SQL Server supports data compression on the partition level, you can combine SQL Server data compression with table partitioning to achieve flexible data archiving on historical parts of a large table without having the CPU overhead on the active part of the table.</span></span>

> [!NOTE]
> <span data-ttu-id="23154-110">SQL Server 2016 SP1 より前は、SQL Server のすべてのエディションで圧縮を利用できませんでした。</span><span class="sxs-lookup"><span data-stu-id="23154-110">Prior to SQL Server 2016 SP1, compression was not available in every edition of SQL Server.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="23154-111">フィードバック</span><span class="sxs-lookup"><span data-stu-id="23154-111">Tell us what you think</span></span>
<span data-ttu-id="23154-112">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="23154-112">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="23154-113">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="23154-113">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
