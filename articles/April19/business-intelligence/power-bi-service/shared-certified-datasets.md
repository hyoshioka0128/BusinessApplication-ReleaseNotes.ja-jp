---
title: 共有データセットと認定データセット
description: Power BI の共有データセットを使用すると、ワークスペースの垣根を超えて、1 つのデータセットを複数のレポートから使用できます。
author: AdamDWilson
ms.date: 05/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: adamw
ms.openlocfilehash: 41ffff900f2da5d7d5c9d76e5cc5dbc1f09b1549
ms.sourcegitcommit: 13b66e38a4b6704674dcab12102e5d5aa2ad368b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/21/2019
ms.locfileid: "1593835"
---
# <a name="shared-and-certified-datasets"></a><span data-ttu-id="8d4b3-103">共有データセットと認定データセット</span><span class="sxs-lookup"><span data-stu-id="8d4b3-103">Shared and certified datasets</span></span>

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

<span data-ttu-id="8d4b3-104">多くの場合、ビジネス上の質問に答えるためのデータは既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-104">In many cases, data already exists to answer your business question.</span></span> <span data-ttu-id="8d4b3-105">データ プロバイダーにとっての課題は、共通の情報源を確保し、その再利用を促進することです。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-105">The challenge for the data provider is to share it in a way that encourages reuse and preserves a single version of the truth.</span></span> <span data-ttu-id="8d4b3-106">レポート作成者にとっての課題は、信頼性の高い高品質のデータを、サービスと Power BI Desktop の両方で迅速かつ容易に見つけられるようにすることです。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-106">For the report author, the challenge is to find reliable and high-quality data quickly and easily in both the service and Power BI Desktop.</span></span>

<span data-ttu-id="8d4b3-107">Power BI の共有データセットを使用すれば、ワークスペースの垣根を超えて、1 つのデータセットを複数のレポートから使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-107">With shared datasets in Power BI, we are allowing a single dataset to be used by multiple reports, across workspaces.</span></span> <span data-ttu-id="8d4b3-108">異なるワークスペースのデータセットに基づいて新しいレポートを作成することも、既存のレポートをワークスペース間でコピーすることもできます。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-108">You can either build new reports based on datasets in different workspaces or you can copy existing reports across workspaces.</span></span>  <span data-ttu-id="8d4b3-109">この作業の一環として、データセットの所有者とテナント管理者が共有データの使用を制御するための新機能を導入しています。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-109">As part of this work, we are introducing new capabilities for dataset owners and tenant administrators to control the use of shared data.</span></span>  

- <span data-ttu-id="8d4b3-110">データセットの所有者の場合、マイクロソフトでは、Power BI のアクセス許可モデルを拡張して**ビルド**という新しいアクセス許可を追加し、データセットに基づく事前作成済みレポートを表示するアクセス許可と、**ビルド**によるアクセス許可を分離しました。これにより、Power BI サービス (レポート、Q&A)、Desktop、Excel オプションでの分析、サードパーティ BI ツールのいずれを使用するかにかかわらず、新しいコンテンツを作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-110">For dataset owners, we are expanding the Power BI permission model to add a new **build** permission, separating out the permission to view pre-created reports on a dataset from those with **build**, which will allow the creation of new content whether that is through the Power BI service (reports, Q&A), Desktop, Analyze in Excel option, or third-party BI tools.</span></span> <span data-ttu-id="8d4b3-111">共有データセットのロールアウト中に、既存のデータセットのアクセス許可セットが移行されるので、現在**読み取り**アクセス許可を割り当てられているユーザーは同じアクセス レベルを維持するために**ビルド** アクセス許可も取得します。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-111">During roll-out of shared datasets, the permission set of existing datasets will be migrated so that users currently assigned the **Read** permission will also get the **Build** permission to maintain the same level of access.</span></span> 

-   <span data-ttu-id="8d4b3-112">テナント管理者の場合、新しい管理者コントロールにより、共有データセットの上にレポートを作成できるユーザーのグループを制限できます。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-112">For tenant administrators, a new admin control will allow you to restrict the group of users who can create reports on top of shared datasets.</span></span> <span data-ttu-id="8d4b3-113">この管理者コントロールは、現在**データのエクスポート**管理者コントロールに制限を設定していない限り、既定で**組織全体に対して有効**になります。制限を設定している場合、既定は**組織全体に対して無効**になります。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-113">This admin control will default to **Enabled for whole org** unless you currently have restrictions set up for the **Export data** admin control, in which case the default will be **Disabled for whole org**.</span></span>

<span data-ttu-id="8d4b3-114">ユーザーが自分に関連する共有データセットを簡単に見つけられるようにするために、マイクロソフトでは、Power BI サービスと Desktop に新しいデータセット検索エクスペリエンスを導入しようとしています。これにより、コンテンツを簡単に参照し、検索できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-114">To help users discover shared datasets relevant to them, we are introducing a new dataset discovery experience in the Power BI service and Desktop that makes it easy to browse and search content.</span></span> 

<span data-ttu-id="8d4b3-115">![共有データセットと認定データセット](media/shared-certified-datasets-1.png "共有データセットと認定データセット")</span><span class="sxs-lookup"><span data-stu-id="8d4b3-115">![Shared and certified datasets](media/shared-certified-datasets-1.png "Shared and certified datasets")</span></span>

<span data-ttu-id="8d4b3-116">組織では、データセットを重要な情報の正式なソースとして認定できるようになります。これは検索エクスペリエンスのための重要な機能として導入される予定です。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-116">Organizations will be able to certify datasets that are the authoritative source for critical information, which will be prominently featured in the discovery experience.</span></span> <span data-ttu-id="8d4b3-117">データセットを認証する機能は、新しい管理者コントロールを介して内部的に厳格に管理し、文書化できます。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-117">The ability to certify datasets can be tightly controlled and documented internally via a new admin control.</span></span> <span data-ttu-id="8d4b3-118">したがって、組織はデータセットの認証を選択的なプロセスにして、組織全体で使用するために設計された信頼できる正式なデータセットを確立できます。</span><span class="sxs-lookup"><span data-stu-id="8d4b3-118">Thus, organizations can ensure that dataset certification is a selective process resulting in the establishment of truly reliable and authoritative datasets designed for use across the org.</span></span>


[!include[feedback](../includes/service-feedback.md)]
