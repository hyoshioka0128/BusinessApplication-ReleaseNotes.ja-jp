---
title: C/AL および AL デバッガーでのデータベース分析情報
description: C/AL および AL デバッガーでのデータベース分析情報
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 4f37c61df9f1d9fed98d06365c2e71deed40dafe
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878729"
---
# <a name="database-insights-in-cal-and-al-debuggers"></a>C/AL および AL デバッガーでのデータベース分析情報

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

## <a name="debugging-sql-behavior"></a>SQL の動作のデバッグ

従来、AL のデバッグは、言語ランタイムの動作を調べる (たとえば、ブレークポイントでのローカル変数の内容を調べる) ことを目的としていました。 Business Central の 2019 年 4 月リリースから、C/AL および AL デバッガーで、AL コードが Business Central データベースに与える影響を調べる機能も提供されるようになります。 デバッガーの**変数**ボックスで **\<データベースの統計情報\>** ノードを展開すると、Business Central Server と Business Central データベースの間の待機時間、実行された SQL ステートメントの合計数、読み取られた行の合計数などの分析情報と、サーバーによって実行された最近の SQL ステートメントに関する分析情報を取得できます。
 
データベースの統計情報には、次の分析情報が含まれます。


|    |    |
| -- | -- |
|現在の SQL 待機時間 (ミリ秒) | デバッガーがブレークポイントにヒットすると、サーバーは短い SQL ステートメントをデータベースに送信し、それにかかる時間を測定します。 この値はミリ秒単位で表示されます。|
|SQL の実行数 | デバッガーの起動以降にデバッグ セッションで実行された SQL ステートメントの合計数を示します。|
|読み取られた SQL 行の数 | デバッガーの起動以降にデバッグ セッションで Business Central データベースから読み取られた行の合計数を示します。|

データベース分析情報では、サーバーによって実行された最新の SQL ステートメントと最近の実行時間の長い SQL ステートメントを調べることもできます。 これらのリストをデバッガーで表示するには、**\<最後に実行された SQL ステートメント\>** または**\<最近の実行時間の長い SQL ステートメント\>** ノードを展開します。  
 
SQL ステートメントの統計情報には、次の分析情報が含まれます。

|||
|-|-|
|ステートメント | AL サーバーが Business Central データベースに送信した SQL ステートメント。 これを SQL Server Management Studio などの他のデータベース ツールにコピーして、さらに分析できます。|
|実行時間 (UTC) | SQL ステートメントが実行されたときのタイムスタンプ (UTC)。 これを使用して、SQL ステートメントが現在のブレークポイントと最後のブレークポイント (設定されている場合) の間の AL コードに含まれていたかどうかを推測できます。|
|期間 (ミリ秒) | Business Central Server 内で測定された SQL ステートメントの合計実行時間の期間 (ミリ秒)。<br /><br />これを使用して、インデックス (Business Central キー) が欠落しているかどうかを調べたり、データベースのパーティション分割や圧縮のパフォーマンスを実験したりできます。|
|読み取られた行の概数 | SQL ステートメントによって Business Central データベースから読み取られた行の概数を示します。<br /><br />これを使用して、フィルターが不足しているかどうかを分析できます。|

デバッガーによって追跡される SQL ステートメントの数は、Business Central Server で構成できます。 既定値は 10 です。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
