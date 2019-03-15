---
title: リアルタイム イベント API の実装
description: リアルタイムのトランザクション データを取り込むため、Dynamics 365 Fraud Protection ではイベント API が提供されています。
author: jackwi111
manager: josaw
ms.date: 02/21/2019
ms.assetid: c3bd0443-0bf5-4f61-9180-e3b3ad023c90
ms.topic: article
ms.custom:
- dyn365-fieldservice
ms.service: dynamics-365-customerservice
ms.author: v-jowigh
ms.openlocfilehash: ff103032a106cec0b642a76047d8263b409b8fde
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "406292"
---
#  <a name="implement-real-time-event-apis"></a>リアルタイム イベント API の実装
[!include[dynamics365-fraud-protection banner](../../../includes/dynamics365-fraud-protection.md)]






リアルタイムのトランザクション データを取り込むため、Dynamics 365 Fraud Protection ではイベント API が提供されています。 迅速な立ち上げのために提供されているサンプル コードでは、リスク イベント API が呼び出され、デバイスのフィンガープリント タグが追加されて、ルール エンジンで決定ルールを設定できるようになります。 これらのルールでは、不正防止ネットワークのリスク モデルによって評価されたリスク スコアを使用できます。 最小限の作業で、Dynamics 365 Fraud Protection API を実装し、製品が正しく統合されるようにすることができます。
