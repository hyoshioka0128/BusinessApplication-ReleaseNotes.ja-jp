---
title: 統合のためのビジネス イベント
description: 統合のためのビジネス イベント
author: Sunil-Garg
ms.date: 02/12/2019
ms.topic: article
ms.service: business-applications
ms.author: Sunil-Garg
ms.openlocfilehash: ea516d21c62d80a8bdaa54a69ae3c8c8235df63c
ms.sourcegitcommit: 12ea920fd9f3d36860a9d7330d0b0037ff2f7ea5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/12/2019
ms.locfileid: "380216"
---
#  <a name="business-events-for-integrations"></a><span data-ttu-id="b8304-103">統合のためのビジネス イベント</span><span class="sxs-lookup"><span data-stu-id="b8304-103">Business events for integrations</span></span>  
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





<span data-ttu-id="b8304-104">イベントは Finance and Operations 内に存在しますが、それらの使用は以前は Finance and Operations 内に限定されていました。</span><span class="sxs-lookup"><span data-stu-id="b8304-104">Events exist in Finance and Operations, but their consumption was previously confined within Finance and Operations.</span></span> <span data-ttu-id="b8304-105">この新しい機能によって提供されるフレームワークでは、業務プロセスの実行時に Finance and Operations 内の業務プロセスでビジネス イベントをキャプチャし、そのイベントを外部のシステムまたはアプリケーションに送信できます。</span><span class="sxs-lookup"><span data-stu-id="b8304-105">This new capability provides a framework that will allow business processes in Finance and Operations to capture business events as business processes are executed, and send the events to an external system or application.</span></span>

<span data-ttu-id="b8304-106">これにより、たとえば、発注書の承認によって仕入先組織でのフルフィルメントをすぐにトリガーしたり、損傷部品の受領で仕入先のクレーム プロセスをリアルタイムでトリガーしたりできるようになります。</span><span class="sxs-lookup"><span data-stu-id="b8304-106">This will allow, for example, a purchase order approval to trigger a fulfillment in the vendor organization sooner than later; a receipt of a damaged part to trigger the vendor claim process in real time; and so on.</span></span> <span data-ttu-id="b8304-107">これらのイベントは業務プロセスのコンテキストで発生するため、これらのイベントは*ビジネス イベント*と呼ばれ、*業務プロセスの統合*を可能にします。</span><span class="sxs-lookup"><span data-stu-id="b8304-107">Since these events happen in the context of business processes, they are called *business events* that enable *business process integration*.</span></span>

<span data-ttu-id="b8304-108">外部の業務プロセスは、Finance and Operations で特定のビジネス イベントをサブスクライブし、発生したときに通知を受けります。</span><span class="sxs-lookup"><span data-stu-id="b8304-108">External business processes will subscribe to specific business events from Finance and Operations to get notified when they occur.</span></span> <span data-ttu-id="b8304-109">ビジネス イベントは、Finance and Operations コネクタで "トリガ" として使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="b8304-109">The business events can also be consumed as "triggers" in the Finance and Operations connector.</span></span>

<span data-ttu-id="b8304-110">含まれる予定の機能は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="b8304-110">Some capabilities that will be included are:</span></span>

- <span data-ttu-id="b8304-111">ビジネス イベント管理者エクスペリエンス: 必要に応じてビジネス イベントを有効または無効にします</span><span class="sxs-lookup"><span data-stu-id="b8304-111">Business events administrator experience: enable and disable business events as needed</span></span>
- <span data-ttu-id="b8304-112">アプリケーション ビジネス イベント</span><span class="sxs-lookup"><span data-stu-id="b8304-112">Application business events</span></span>
- <span data-ttu-id="b8304-113">ワークフロー ビジネス イベント</span><span class="sxs-lookup"><span data-stu-id="b8304-113">Workflow business events</span></span>
- <span data-ttu-id="b8304-114">ビジネス イベント フレームワーク: パートナーおよびお客様が定義するイベント</span><span class="sxs-lookup"><span data-stu-id="b8304-114">Business events framework: for partner- and customer-defined events</span></span>
- <span data-ttu-id="b8304-115">イベント グリッドに対するエンドポイントのサポート: 統合シナリオ用</span><span class="sxs-lookup"><span data-stu-id="b8304-115">Endpoint support for Event Grid: for integration scenarios</span></span>
- <span data-ttu-id="b8304-116">"ビジネス イベント発生時" 用のコネクタ トリガー: Microsoft Flow および LogicApp で使用します。</span><span class="sxs-lookup"><span data-stu-id="b8304-116">Connector triggers for "when a business event occurs": for use in Microsoft Flow and LogicApps.</span></span> <span data-ttu-id="b8304-117">ユーザーは Finance and Operations で利用可能な特定のビジネス イベントをサブスクライブできるようになります。</span><span class="sxs-lookup"><span data-stu-id="b8304-117">The user will then be able to subscribe to specific business events available in Finance and Operations.</span></span>

