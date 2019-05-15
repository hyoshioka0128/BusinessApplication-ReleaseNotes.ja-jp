---
title: リスク ルールの順序付けと管理
description: Dynamics 365 Fraud Protection でのルールの順序付けと管理により、誤検知と検知漏れのバランスを細かく制御できます。
author: jackwi111
manager: josaw
ms.date: 02/21/2019
ms.assetid: 9e120d3a-ee15-4184-845e-4fc8bc426570
ms.topic: article
ms.custom:
- dyn365-fieldservice
ms.service: dynamics-365-customerservice
ms.author: v-jowigh
ms.openlocfilehash: d43f6b841dcbaddfb322b1484825e9b2a915fe21
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225095"
---
#  <a name="order-and-manage-risk-rules"></a>リスク ルールの順序付けと管理
[!include[dynamics365-fraud-protection banner](../../../includes/dynamics365-fraud-protection.md)]






Dynamics 365 Fraud Protection でのルールの順序付けと管理により、誤検知と検知漏れのバランスを細かく制御できます。 標準のルール (詐欺防止ネットワークによって提供されるリスク スコアしきい値を適用する) に加えて、コーホート内の追加の知識を使用してカスタム ルール スタック (トランザクションを承認または却下する最終決定を行う) を構築できます。 ルールには、セーフ リスト、ブロック リスト、監視リスト、カスタム リストを含めることができます。 標準ルールに適用されるリスク スコアしきい値、および決定に対してトリガーされる特定のリスク ルールでは、ナレッジ グラフに注釈が自動的に付けられます。 [グラフ エクスプローラー](../understand-business/graph-explorer.md)を使用してトランザクションを参照するときに、これらの機能が表示されます。 これは、顧客サポート チームがリスク関連の顧客エスカレーションを調査するのに役立ちます。
