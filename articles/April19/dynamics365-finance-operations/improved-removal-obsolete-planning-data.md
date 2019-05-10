---
title: 古い計画データの削除の改善
description: マスター プランが正常に実行された後は、不要になった計画データを削除するためのクリーンアップ ジョブをスケジュールします。
author: Mirzaab
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
ms.openlocfilehash: 07f30fc98a6247923d57e7e1efbba1fea03b7dcb
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224891"
---
#  <a name="improved-removal-of-obsolete-planning-data"></a>古い計画データの削除の改善
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



マスター プランが正常に実行された後は、不要になった計画データを削除するためのクリーンアップ ジョブをスケジュールします。 ただし、マスター プランの実行が失敗したときなど、場合によっては、データがクリーンアップされず、それによって不要なデータが集計される危険性があります。 

クリーンアップ ジョブは、以前に失敗したマスター プランの実行からデータを削除するように強化されました。また、設計は他のスレッドをブロックしないように最適化されて、すべてのヘルパーをマスター プランの実行に使用できるようになりました。 これらの改善は、会社間のマスター プランにも適用されます。
