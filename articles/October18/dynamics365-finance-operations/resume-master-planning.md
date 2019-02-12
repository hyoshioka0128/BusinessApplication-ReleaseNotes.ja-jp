---
title: マスター プランの再開
description: マスター プランの再開
author: josaw1
manager: AnnBe
ms.date: 11/29/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: josaw
audience: end-user
ms.openlocfilehash: cef4f35c4f7718ef0329aca340f3a5c153c89709
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199830"
---
#  <a name="resume-master-planning"></a>マスター プランの再開

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

強化された計画エンジン機能により、メイン スレッドが予期せず停止した場合に、マスター プランのバッチ ジョブが自動的に再開されます。 この状況は、なんらかの理由により、マスター プランの実行中にバッチ サーバー接続が失われた場合に発生することがあります。 この機能が実装される前は、マスター プランの完全な再実行が必要でした。 現在は、マスター プランのバッチ ジョブが自動的に再開され、中断された場所から続行されます。 プランナーは、**マスター プラン履歴ログ**から、メイン スレッドが予期せず停止し、プロセスが再開されたことを確認できます。

再開は 1 回だけ行われるので、メイン スレッドが再開中に再び予期せず停止した場合は、失敗したものとしてログに記録され、再開は再試行されません。 また、再開は、少なくともマスター プラン計算のカバレッジ状態に達した再生成とジョブにのみ適用されます。 ヘルパー スレッドが予期せず停止した場合、プランは残りのヘルパーで続行されます。

