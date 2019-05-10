---
title: データ損失防止の強化
description: データ損失防止には、データ分類とデータ フローの方向を適用する機能が追加されました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/14/2019
ms.assetid: 4f87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 2dc044217588e834640044282627e6d0b3aa7e39
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445452"
---
# <a name="data-loss-prevention-enhancements"></a><span data-ttu-id="ec4e9-103">データ損失防止の強化</span><span class="sxs-lookup"><span data-stu-id="ec4e9-103">Data Loss Prevention enhancements</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="ec4e9-104">データ損失防止 (DLP) ポリシーを使用すると、組織はコネクタをビジネス データ グループと非ビジネス データ グループにグループ化できます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-104">Data Loss Prevention (DLP) policies provide organizations with the ability to group connectors into Business and Non-Business Data Groups.</span></span> <span data-ttu-id="ec4e9-105">これにより、組織は*ビジネス* データ ソースだけを含むフローを構築し、ビジネス データが非ビジネス データ ソースに漏れるのを防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-105">This allows organizations to build flows that contain only *Business* data sources and prevent business data from leaking to non-business data sources.</span></span> <span data-ttu-id="ec4e9-106">一般的な例は、*自分の SharePoint データが Twitter に送られて欲しくない*ような場合です。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-106">A common example is: *I don’t want my SharePoint data to end up on Twitter*.</span></span>

<span data-ttu-id="ec4e9-107">これらの機能に加えて、ユーザーからはデータの分類とデータ フローの方向を尊重する機能の要望がありました。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-107">In addition to these capabilities, users have wanted the ability to respect data classifications and the direction of data flow.</span></span> <span data-ttu-id="ec4e9-108">これをサポートすることで、ブロックするシナリオを細かく指定できるので、作成されるフローの数が増えます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-108">By supporting this, the number of flows that people build will increase because we can be more specific about what scenarios are blocked.</span></span>

<span data-ttu-id="ec4e9-109">たとえば、多くの環境では、Twitter は*非ビジネス*に分類され、SharePoint は*ビジネス*に分類されます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-109">For example, in many environments, Twitter is classified as *non-business* and SharePoint as *business*.</span></span> <span data-ttu-id="ec4e9-110">現在のモデルでは、これはユーザーがセンチメント分析データを収集してそれを SharePoint リスト (イベントおよびフィードバック収集に関して製品チームに非常に役立つもの) に格納できないことを意味します。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-110">Under the current model, this means that people can’t gather sentiment analysis data and put it in a SharePoint list—something highly useful for product teams around events and collecting feedback.</span></span>

<span data-ttu-id="ec4e9-111">DLP に対する新しい機能強化により、これが可能になります。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-111">With our new enhancements to DLP, this would now be enabled.</span></span> <span data-ttu-id="ec4e9-112">これについては、2 つの重要な側面があります。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-112">There are two important aspects to this:</span></span>

- <span data-ttu-id="ec4e9-113">1 つ目は、管理者はデータがコネクタ間を移動できる方向を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-113">First, administrators can now choose the direction that data can travel between connectors.</span></span> <span data-ttu-id="ec4e9-114">たとえば、組織によっては Twitter のデータがフローに入るのは問題なくても、そのデータがフローから Twitter に送られるのは望ましくない場合があります。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-114">For example, an organization might be comfortable with Twitter data to enter a flow, but they don’t want that data leaving the flow and onto Twitter.</span></span>
- <span data-ttu-id="ec4e9-115">2 つ目は、設計時と実行時の両方においてデータの分類が Microsoft Flow によって適用されます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-115">Second, Data Classification is enforced by Microsoft Flow at both design time and run time.</span></span> <span data-ttu-id="ec4e9-116">たとえば、機密性の高い SharePoint サイトからデータを取得して、パブリックの SharePoint サイトに送信することはできません。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-116">For example, you can't take data from a Highly Confidential SharePoint site and send it to a public SharePoint site.</span></span> <span data-ttu-id="ec4e9-117">一方、パブリック サイトからデータを取得して高機密性サイトに移動することはできます。</span><span class="sxs-lookup"><span data-stu-id="ec4e9-117">However, you can take data from the public site and move it to the Highly Confidential site.</span></span>
