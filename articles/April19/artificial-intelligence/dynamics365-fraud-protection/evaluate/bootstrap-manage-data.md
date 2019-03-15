---
title: データのブートストラップと管理
description: データは良い決断の礎です。
author: jackwi111
manager: josaw
ms.date: 02/21/2019
ms.assetid: 4408f694-9951-46ec-b363-2dd80087b248
ms.topic: article
ms.custom:
- dyn365-fieldservice
ms.service: dynamics-365-customerservice
ms.author: v-jowigh
ms.openlocfilehash: ba6d5d500536d6748d56ad101d77a8151ede3a9b
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "406261"
---
#  <a name="bootstrap-and-manage-your-data"></a>データのブートストラップと管理
[!include[dynamics365-fraud-protection banner](../../../includes/dynamics365-fraud-protection.md)]






データは良い決断の礎です。 履歴データを Dynamics 365 Fraud Protection にブートストラップして、リスク決定の正確さを高めることができます。 ブートストラップには、不正検出の改善に役立つ、購入、チャージバック、および業者や銀行の決定などの重要なシグナルといったデータが含まれます。
この履歴データを使用することで、機械学習モデルを準備するプロセスを短縮できます。

Microsoft Azure リポジトリからのデータ ストリームを Dynamics 365 Fraud Protection に取り込み、それを基本/拡張オントロジーにマップし、1 回限りまたは反復的な一括データ取り込みジョブを設定してナレッジ グラフを生成することができます。 Dynamics 365 Fraud Protection では、これらの反復的な一括取り込みジョブの信頼性を監視し、欠落データや不正なデータを検出して、障害に関する警告を受け取ることができます。
