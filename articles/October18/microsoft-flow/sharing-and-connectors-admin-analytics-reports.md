---
title: 共有およびコネクタ管理分析レポート
description: 共有レポートとコネクタ レポートはどちらも Microsoft Flow 管理分析で使用できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/19/2019
ms.assetid: a3632f34-4ad9-e811-a987-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 8ec40257e6676cf2138043c9b55c6b70f5698e64
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880566"
---
# <a name="sharing-and-connectors-admin-analytics-reports-public-preview"></a>共有およびコネクタ管理分析レポート (パブリック プレビュー)




9 月後半に、Power Platform 管理分析の[パブリック プレビュー リリースを発表](https://flow.microsoft.com/blog/admin-analytics/)しました  その投稿では、共有とコネクタを含む今後のいくつかのレポートについて説明しました。 共有レポートとコネクタ レポートはどちらも Microsoft Flow 管理分析で使用できるようになりました。 

> [!NOTE]
> これらのレポートにアクセスするための前提条件は変更されていませんが、現在その作業に取り組んでいます。 以前の投稿で要件をご確認ください。

どちらのレポートでも、テナント内でのユーザーによる Microsoft Flow の使用状況の分析情報が提供されます。 共有の観点からは、だれが最高意思決定者であるかを理解し、さらに自動化されたソリューションを組織に提供するための権限をそれらの人物に与える方法を判断することができます。 コネクタ レポートでは、組織内で使用されている Microsoft、サードパーティ、カスタムのコネクタが示されます。 

[Power Platform 管理センター](https://admin.powerplatform.microsoft.com/)に移動すると、Common Data Service for Apps、Microsoft Flow、PowerApps の分析を参照するために選択できる [分析] メニューが見つかります。 共有およびコネクタ レポートの場合は、Microsoft Flow を選択します。 

![実行の使用方法](media/sharing-connectors-analytics-1.png "実行の使用方法")

Microsoft Flow 分析機能から、**共有**を選択して共有レポートにアクセスできます。 このレポートには、キャプチャする 3 つの異なるビジュアル化が表示されます。

- 共有されるフローの種類 (システム イベント、スケジュール済み、またはボタンのクリック)。
- 共有されたフローの名前。
- 発生した共有の数。
- これらの共有イベントのトレンドライン レポート。

![共有レポート](media/sharing-connectors-analytics-2.png "共有レポート")

共有レポートに加えて、コネクタの使用状況を強調するレポートもリリースしました。 コネクタ レポートには、次の項目があります。

- コネクタの使用状況を表示する 2 つのビジュアル化:
  - フロー実行。
  - コネクタ接続 (コネクタの呼び出し)。

- 次のものを一覧表示する表のビジュアル化。
  - コネクタの名前。
  - 接続の数。 
  - 関係するフローの数。
  - そのコネクタを使用して実行されているフローの数。

![コネクタ レポート](media/sharing-connectors-analytics-3.png "コネクタ レポート")