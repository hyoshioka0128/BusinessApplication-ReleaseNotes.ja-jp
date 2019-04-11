---
title: 共有データセットと認定データセット
description: Power BI の共有データセットを使用すると、ワークスペースの垣根を超えて、1 つのデータセットを複数のレポートから使用できます。
author: AdamDWilson
ms.date: 01/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: adamw
ms.openlocfilehash: c5795afae06342c25462a4f94359f1472353f361
ms.sourcegitcommit: e9ae36f4f7ff145fcdc3d3ebfb2080fc33083f69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2019
ms.locfileid: "849571"
---
# <a name="shared-and-certified-datasets"></a><span data-ttu-id="b5c06-103">共有データセットと認定データセット</span><span class="sxs-lookup"><span data-stu-id="b5c06-103">Shared and certified datasets</span></span>

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

<span data-ttu-id="b5c06-104">多くの場合、ビジネス上の質問に答えるためのデータは既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="b5c06-104">In many cases, data already exists to answer your business question.</span></span> <span data-ttu-id="b5c06-105">データ プロバイダーにとっての課題は、共通の情報源を確保し、その再利用を促進することです。</span><span class="sxs-lookup"><span data-stu-id="b5c06-105">The challenge for the data provider is to share it in a way that encourages reuse and preserves a single version of the truth.</span></span> <span data-ttu-id="b5c06-106">レポート作成者にとっての課題は、信頼性の高い高品質のデータを、サービスと Power BI Desktop の両方で迅速かつ容易に見つけられるようにすることです。</span><span class="sxs-lookup"><span data-stu-id="b5c06-106">For the report author, the challenge is to find reliable and high-quality data quickly and easily in both the service and Power BI Desktop.</span></span>

<span data-ttu-id="b5c06-107">Power BI の共有データセットを使用すれば、ワークスペースの垣根を超えて、1 つのデータセットを複数のレポートから使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="b5c06-107">With shared datasets in Power BI, we are allowing a single dataset to be used by multiple reports, across workspaces.</span></span> <span data-ttu-id="b5c06-108">これを実現するため、Microsoft では、Power BI のアクセス許可モデルを拡張して "explore" という新しいアクセス許可を追加し、データセットに基づく事前作成済みレポートを表示するアクセス許可と、"explore" によるアクセス許可を分離しました。これにより、Power BI サービス (レポート、Q&A)、Desktop、Excel での分析、サードパーティ BI ツールのいずれを使用するかにかかわらず、新しいコンテンツを作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="b5c06-108">As part of this work, we are expanding the Power BI permission model to add a new “explore” permission, separating out the permission to view pre-created reports on a dataset from those with “explore”, which will allow the creation of new content, whether that is through the Power BI service (reports, Q&A), Desktop, Analyze in Excel, or third-party BI tools.</span></span>

<span data-ttu-id="b5c06-109">ユーザーが自分に関連する共有データセットを簡単に見つけられるようにするために、Microsoft では、Power BI サービスと Desktop に新しいデータセット検索エクスペリエンスを導入しようとしています。これにより、コンテンツを簡単に参照し、検索できるようになります (次のスクリーンショットを参照)。</span><span class="sxs-lookup"><span data-stu-id="b5c06-109">To help users discover shared datasets relevant to them, we are introducing a new dataset discovery experience in the Power BI service and Desktop that makes it easy to browse and search to find content (see the following screenshot).</span></span>
<span data-ttu-id="b5c06-110">組織では、データセットを重要な情報の正式なソースとして認定できるようになります。これは検索エクスペリエンスのための重要な機能として導入される予定です。</span><span class="sxs-lookup"><span data-stu-id="b5c06-110">Organizations will be able to certify datasets that are the authoritative source for critical information, which will be prominently featured in the discovery experience.</span></span>

<span data-ttu-id="b5c06-111">![共有データセットと認定データセット](media/shared-certified-datasets-1.png "共有データセットと認定データセット")</span><span class="sxs-lookup"><span data-stu-id="b5c06-111">![Shared and certified datasets](media/shared-certified-datasets-1.png "Shared and certified datasets")</span></span>

[!include[feedback](../includes/service-feedback.md)]