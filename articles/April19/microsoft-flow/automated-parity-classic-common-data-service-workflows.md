---
title: 従来の Common Data Service ワークフローと同等の自動フロー
description: このリリースでは、従来の非同期 Common Data Service ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/30/2019
ms.assetid: fb86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: e2c91d3a6cfd40f4f9735771fa08e3d59507beaf
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445823"
---
# <a name="automated-flow-parity-with-classic-common-data-service-workflows"></a><span data-ttu-id="f1195-103">従来の Common Data Service ワークフローと同等の自動フロー</span><span class="sxs-lookup"><span data-stu-id="f1195-103">Automated flow parity with classic Common Data Service workflows</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="f1195-104">今後、既存の従来の Common Data Service ワークフロー (以前は Dynamics 365 for Customer Engagement ワークフローと呼ばれていました) は、自動フローによって置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="f1195-104">Automated flows will, over time, replace the existing Classic Common Data Service workflows (formerly known as Dynamics 365 for Customer Engagement workflow).</span></span> <span data-ttu-id="f1195-105">このリリースでは、従来の非同期 Common Data Service ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f1195-105">With this release, it is now possible to accomplish all scenarios that asynchronous classic Common Data Service workflows supported with automated flows.</span></span> <span data-ttu-id="f1195-106">アクションのサポートやバッチ処理のサポートなど、いくつかの機能がリリース ノートの他の部分で説明されています。</span><span class="sxs-lookup"><span data-stu-id="f1195-106">Several capabilities, including action support and batching support, are covered elsewhere in the release notes.</span></span> <span data-ttu-id="f1195-107">自動フローの新機能の一覧を次に示します。</span><span class="sxs-lookup"><span data-stu-id="f1195-107">Here's a list of the new features in automated flows:</span></span>

- <span data-ttu-id="f1195-108">**トリガーにフィルターを提供する**: 自動フローをトリガーするレコードを正確に制御できます。</span><span class="sxs-lookup"><span data-stu-id="f1195-108">**Provide filters to triggers**: You can control exactly which records trigger your automated flows.</span></span> <span data-ttu-id="f1195-109">トリガーをフローの途中に含めることで、それらをフローの内部の**待機状態**として利用できます。</span><span class="sxs-lookup"><span data-stu-id="f1195-109">By including triggers in the middle of flows, you can leverage them as **Wait conditions** inside of a flow.</span></span>
- <span data-ttu-id="f1195-110">**として実行**機能: CDS for Apps によってトリガーされる自動フローは、フローの所有者によって定義されたアカウントで、またはトリガーの原因になった変更を実行したユーザーの ID によって、実行できます。</span><span class="sxs-lookup"><span data-stu-id="f1195-110">**Run As** capabilities: Automated flows that are triggered by CDS for Apps can run with either an account defined by the owner of the flow, or with the identity of the user who performed the change that caused the trigger.</span></span>
- <span data-ttu-id="f1195-111">**失敗したアクションからフローを再開する**: アクションでフローが失敗した場合、作成者はエラーを修復した後そのアクションからフローを再開できます。</span><span class="sxs-lookup"><span data-stu-id="f1195-111">**Resume flows from a failed action**: If a flow fails on an action, makers can resume the flow right from that action once they’ve repaired the error.</span></span>
- <span data-ttu-id="f1195-112">**複数のトリガー タイプのサポート**: フローを、自動 (システム内のイベントによってトリガーされる) と即時 (オンデマンドでトリガーされる) の両方に同時にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f1195-112">**Support for multiple trigger types**: Flows can now both be automated (triggered by events in the system), and instant (triggered on-demand) at the same time.</span></span>
- <span data-ttu-id="f1195-113">**他のフローを呼び出す**: フローでは、他のフローを呼び出してパラメーターを渡すことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f1195-113">**Call other flows**: Flows can now call other flows and pass parameters to them.</span></span>

<span data-ttu-id="f1195-114">最後に、お客様に対して移行ガイダンスも提供されていますが、現時点では自動移行はありません。</span><span class="sxs-lookup"><span data-stu-id="f1195-114">Finally, we are also providing migration guidance for our customers, although there is no automatic migration at this time.</span></span>
