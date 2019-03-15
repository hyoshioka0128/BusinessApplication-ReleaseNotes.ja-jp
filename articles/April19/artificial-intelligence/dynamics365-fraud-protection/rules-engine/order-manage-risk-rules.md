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
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "406364"
---
#  <a name="order-and-manage-risk-rules"></a><span data-ttu-id="e5707-103">リスク ルールの順序付けと管理</span><span class="sxs-lookup"><span data-stu-id="e5707-103">Order and manage risk rules</span></span>
[!include[dynamics365-fraud-protection banner](../../../includes/dynamics365-fraud-protection.md)]






<span data-ttu-id="e5707-104">Dynamics 365 Fraud Protection でのルールの順序付けと管理により、誤検知と検知漏れのバランスを細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="e5707-104">By ordering and managing rules in Dynamics 365 Fraud Protection, you can finely control the balance between false positives and false negatives.</span></span> <span data-ttu-id="e5707-105">標準のルール (詐欺防止ネットワークによって提供されるリスク スコアしきい値を適用する) に加えて、コーホート内の追加の知識を使用してカスタム ルール スタック (トランザクションを承認または却下する最終決定を行う) を構築できます。</span><span class="sxs-lookup"><span data-stu-id="e5707-105">In addition to a standard rule (which applies the risk score threshold provided by the fraud protection network), you can use the extra knowledge in cohorts to build a custom rules stack (which delivers a final decision to approve or reject a transaction).</span></span> <span data-ttu-id="e5707-106">ルールには、セーフ リスト、ブロック リスト、監視リスト、カスタム リストを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="e5707-106">The rules can include your safe, block, or watch lists, as well as custom lists.</span></span> <span data-ttu-id="e5707-107">標準ルールに適用されるリスク スコアしきい値、および決定に対してトリガーされる特定のリスク ルールでは、ナレッジ グラフに注釈が自動的に付けられます。</span><span class="sxs-lookup"><span data-stu-id="e5707-107">The risk score threshold applied in the standard rule, and the specific risk rule that gets triggered for a decision, are automatically annotated in the knowledge graph.</span></span> <span data-ttu-id="e5707-108">[グラフ エクスプローラー](../understand-business/graph-explorer.md)を使用してトランザクションを参照するときに、これらの機能が表示されます。</span><span class="sxs-lookup"><span data-stu-id="e5707-108">You can see these features when you use the [graph explorer](../understand-business/graph-explorer.md) to browse the transaction.</span></span> <span data-ttu-id="e5707-109">これは、顧客サポート チームがリスク関連の顧客エスカレーションを調査するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e5707-109">This helps your customer-support team investigate risk-related customer escalations.</span></span>
