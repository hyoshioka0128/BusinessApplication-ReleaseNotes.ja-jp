---
title: 統合のためのビジネス イベント
description: 統合のためのビジネス イベント
author: Sunil-Garg
ms.date: 03/11/2019
ms.topic: article
ms.service: business-applications
ms.author: Sunil-Garg
ms.openlocfilehash: 3aa280e04b43332dc14002915a1ff0f067062467
ms.sourcegitcommit: 3b77d2603bb0c2166c61729c589e1c2e2296fc9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/15/2019
ms.locfileid: "844201"
---
#  <a name="business-events-for-integrations"></a><span data-ttu-id="4d1a4-103">統合のためのビジネス イベント</span><span class="sxs-lookup"><span data-stu-id="4d1a4-103">Business events for integrations</span></span>  
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





<span data-ttu-id="4d1a4-104">イベントは Finance and Operations 内に存在しますが、それらの使用は以前は Finance and Operations 内に限定されていました。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-104">Events exist in Finance and Operations, but their consumption was previously confined within Finance and Operations.</span></span> <span data-ttu-id="4d1a4-105">この新しい機能によって提供されるフレームワークでは、業務プロセスの実行時に Finance and Operations 内の業務プロセスでビジネス イベントをキャプチャし、そのイベントを外部のシステムまたはアプリケーションに送信できます。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-105">This new capability provides a framework that will allow business processes in Finance and Operations to capture business events as business processes are executed, and send the events to an external system or application.</span></span>

<span data-ttu-id="4d1a4-106">これにより、たとえば、発注書の承認によって仕入先組織でのフルフィルメントをすぐにトリガーしたり、損傷部品の受領で仕入先のクレーム プロセスをリアルタイムでトリガーしたりできるようになります。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-106">This will allow, for example, a purchase order approval to trigger a fulfillment in the vendor organization sooner than later; a receipt of a damaged part to trigger the vendor claim process in real time; and so on.</span></span> <span data-ttu-id="4d1a4-107">これらのイベントは業務プロセスのコンテキストで発生するため、これらのイベントは*ビジネス イベント*と呼ばれ、*業務プロセスの統合*を可能にします。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-107">Since these events happen in the context of business processes, they are called *business events* that enable *business process integration*.</span></span>

<span data-ttu-id="4d1a4-108">外部の業務プロセスは、Finance and Operations で特定のビジネス イベントをサブスクライブし、発生したときに通知を受けります。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-108">External business processes will subscribe to specific business events from Finance and Operations to get notified when they occur.</span></span> <span data-ttu-id="4d1a4-109">ビジネス イベントは、Finance and Operations コネクタで "トリガー" として使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-109">The business events can also be consumed as "triggers" in the Finance and Operations connector.</span></span>

<span data-ttu-id="4d1a4-110">この機能の詳細については、「[ビジネス イベント](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/business-events/home-page)」で機能のドキュメントを参照してください。</span><span class="sxs-lookup"><span data-stu-id="4d1a4-110">More details on this capability can be found in the feature documentation on [Business events](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/business-events/home-page).</span></span>

