---
title: Microsoft Flow を使用したバックエンド システムからのアクションまたはデータへのアクセスの有効化
description: Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。
author: shellyhaverkamp
ms.date: 02/21/2019
ms.topic: article
ms.service: business-applications
ms.author: ''
ms.reviewer: v-stsau
ms.openlocfilehash: a429d3bf3afd5003202b951a59150d1b232cdce1
ms.sourcegitcommit: 3b77d2603bb0c2166c61729c589e1c2e2296fc9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/15/2019
ms.locfileid: "843526"
---
<!--from editor: Please provide caption info for screenshot.-->


# <a name="enable-actions-or-access-data-from-back-end-systems-using-microsoft-flow"></a><span data-ttu-id="3f5b3-103">Microsoft Flow を使用したバックエンド システムからのアクションまたはデータへのアクセスの有効化</span><span class="sxs-lookup"><span data-stu-id="3f5b3-103">Enable actions or access data from back-end systems using Microsoft Flow</span></span>
[!include[customer-service banner](../../../includes/dynamics365-ai-customer-service.md)]


<span data-ttu-id="3f5b3-104">ソリューションでは、仮想エージェントがユーザーに代わってバックエンドのワークフローまたはビジネス プロセスを起動する必要がある場合があります。たとえば、ギフト カードの残高に関するクエリなどです。</span><span class="sxs-lookup"><span data-stu-id="3f5b3-104">Solutions sometimes require the virtual agent to trigger a back-end workflow or business process on behalf of the user; for example, a query about a gift card balance.</span></span>

<span data-ttu-id="3f5b3-105">Dynamics 365 Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。</span><span class="sxs-lookup"><span data-stu-id="3f5b3-105">Dynamics 365 Virtual Agent for Customer Service integrates with Microsoft Flow, empowering customer service managers to trigger existing flows or create new ones that call back-end systems without writing code.</span></span>

<span data-ttu-id="3f5b3-106">Microsoft Flow には、利用可能な一般的なサービスへの何百ものコネクタがあり、それらを使用して既存の内部ワークフローを自動化することができます。</span><span class="sxs-lookup"><span data-stu-id="3f5b3-106">Microsoft Flow has hundreds of connectors to common services available, which can be used to automate existing internal workflows.</span></span> <span data-ttu-id="3f5b3-107">その後、これらを Virtual Agent for Customer Service で作成されたダイアログから直接呼び出して、仮想エージェントに機能を追加できます。</span><span class="sxs-lookup"><span data-stu-id="3f5b3-107">These can then be called directly from dialogs authored in Virtual Agent for Customer Service, adding functionality to the virtual agent.</span></span> <span data-ttu-id="3f5b3-108">カスタム コネクタを介してカスタム コードおよびレガシ システムへの接続もサポートでき、仮想エージェントの機能向上に伴い拡張性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="3f5b3-108">Even custom code and connections to legacy systems can be supported through custom connectors, providing extensibility as the virtual agent’s capabilities grow.</span></span>

![フローを使用した会話パス](../media/customer-service-virtual-agent-7.png)
