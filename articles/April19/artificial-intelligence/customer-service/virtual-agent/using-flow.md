---
title: Microsoft Flow を使用したバックエンド システムからのアクションまたはデータへのアクセスの有効化
description: Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。
author: shellyhaverkamp
ms.date: 02/21/2019
ms.topic: article
ms.service: business-applications
ms.author: ''
ms.reviewer: v-stsau
ms.openlocfilehash: f5a5295036850286a53b04a0b4391beaa4fb1a41
ms.sourcegitcommit: cb60b8678619bdabcbea7c0bc29027c5af897b17
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/28/2019
ms.locfileid: "770544"
---
<!--from editor: Please provide caption info for screenshot.-->


# <a name="enable-actions-or-access-data-from-back-end-systems-using-microsoft-flow"></a>Microsoft Flow を使用したバックエンド システムからのアクションまたはデータへのアクセスの有効化
[!include[customer-service banner](../../../includes/customer-service.md)]


ソリューションでは、仮想エージェントがユーザーに代わってバックエンドのワークフローまたはビジネス プロセスを起動する必要がある場合があります。たとえば、ギフト カードの残高に関するクエリなどです。

Dynamics 365 Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。

Microsoft Flow には、利用可能な一般的なサービスへの何百ものコネクタがあり、それらを使用して既存の内部ワークフローを自動化することができます。 その後、これらを Virtual Agent for Customer Service で作成されたダイアログから直接呼び出して、仮想エージェントに機能を追加できます。 カスタム コネクタを介してカスタム コードおよびレガシ システムへの接続もサポートでき、仮想エージェントの機能向上に伴い拡張性が提供されます。

![フローを使用した会話パス](../media/customer-service-virtual-agent-7.png)
