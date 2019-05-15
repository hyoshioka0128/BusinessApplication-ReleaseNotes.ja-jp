---
title: クエリヒントの構成
description: Business Central で SQL Server のパフォーマンスを最適化するためのクエリ ヒントの構成
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: b0f99f5cad117407472dfc3915119de3e6471706
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225161"
---
# <a name="configuring-query-hints-for-optimizing-sql-server-performance"></a>SQL Server のパフォーマンスを最適化するためのクエリ ヒントの構成

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

SQL Server クエリ オプティマイザーは、それ自体で、クエリに最適な実行プランを選択しようとします。 ほとんどの場合、クエリ オプティマイザーは正しい選択をします。 クエリ ヒントは、クエリ オプティマイザーによってクエリに対して選択される可能性のある実行プランをオーバーライドするために、SQL Server クエリ プロセッサによって適用される戦略です。 Business Central Server インスタンスに含まれる以下の構成設定を使用すると、データベース内のクエリに対してヒントの使用を有効または無効にできます。

|ヒント|説明|既定で使用|
|----|-----------|---------------|
|順序を強制 |クエリ構文によって示されている結合順序を維持するようクエリ オプティマイザーに指示します。|いいえ|
|ループ結合|クエリ全体のすべての結合操作に LOOP JOIN を使用するようクエリ オプティマイザーに指示します。|いいえ|
|不明に対する最適化|クエリがコンパイルおよび最適化されるときに、強制パラメーター化で作成されるパラメーターを含め、すべてのローカル変数に対して初期値ではなく統計データを使用するようクエリ オプティマイザーに指示します。|はい|

Business Central クエリ オブジェクトの実行計画で、SQL Server のクエリ ヒントを使用するようにしました。

また、これらの機能は Dynamics NAV の 2017 と 2018 で利用できるようにされました。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
