---
title: "共有データセットと認定データセット"
description: "単一バージョンの事実を維持するために、ユーザー間でデータセットを共有します。"
author: Annbe
manager: AnnBe
ms.date: 11/05/2018
ms.assetid: 1508b82e-6be4-47f9-a827-3659f79aa7a1
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Analyst
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 712e7ffecb22a0731f198ab17bf93a70a0cd427a
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---
# <a name="shared-and-certified-datasets"></a><span data-ttu-id="d0265-103">共有データセットと認定データセット</span><span class="sxs-lookup"><span data-stu-id="d0265-103">Shared and certified datasets</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="d0265-104">データ カルチャを取り入れている組織では、多くの個人がしばしば同じソース データを使用してレポートを作成します。</span><span class="sxs-lookup"><span data-stu-id="d0265-104">Organizations embracing a data culture will have many individuals authoring reports, often using the same source data.</span></span> <span data-ttu-id="d0265-105">この俊敏性はデータの使用が普及するのを助けますが、ガバナンスの課題ももたらします。</span><span class="sxs-lookup"><span data-stu-id="d0265-105">This agility helps ensure the use of data is pervasive, but it also introduces governance challenges.</span></span>  <span data-ttu-id="d0265-106">多くのユーザーが同じソース データを参照すると、Power BI 内でソース データのすべてのインスタンスを最新の状態に保つための作業が重複して作成されるため、データと重要なビジネス メトリックが一貫して使用されるように事実の単一ソースを維持することが難しくなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d0265-106">With many users referencing the same source data, it creates duplicate work to keep all instances of the source data up to date within Power BI and it can be hard to maintain a single source of truth for data and important business metrics to be used consistently.</span></span> 

<span data-ttu-id="d0265-107">Power BI レポートの背後にあるデータ モデルまたは Analysis Services モデルは、企業規模のセマンティック モデルを構築するための優れたツールであり、これらの重要なメトリックを取得して再利用を促進し、事実の単一ソースを維持します。</span><span class="sxs-lookup"><span data-stu-id="d0265-107">The data model behind a Power BI report or an Analysis Services model is excellent tools to build enterprise-wide semantic models that capture these important metrics, fostering reuse and maintaining the single source of truth.</span></span> <span data-ttu-id="d0265-108">現在、Power BI 内の共有データセットと認定データセットにより、ユーザーはこれらの権限あるモデルをはるかに簡単に検出できます。</span><span class="sxs-lookup"><span data-stu-id="d0265-108">Now, with shared and certified datasets in Power BI, allowing users to discover those authoritative models is much easier.</span></span>

<span data-ttu-id="d0265-109">*共有データセット*は、ワークスペースをまたがって使用できます。つまり、ワークスペース A のレポートからワークスペース B のデータセットを参照できます。このようにして、組織は特定のワークスペース内に多数の信頼できるデータセットを設定でき、組織全体のアナリストたちが自分のワークスペースでこのデータを処理して、新しいレポートとダッシュボードを作成できます。</span><span class="sxs-lookup"><span data-stu-id="d0265-109">*Shared datasets* can be used across workspaces—that is, a report in workspace A can refer to a dataset in workspace B. This way, an organization can set up a number of trusted and reliable datasets in a specific workspace and can enable analysts across the org to work with this data in their own workspaces to create new reports and dashboards.</span></span> <span data-ttu-id="d0265-110">新しいアクセス許可モデルは、適切なユーザーだけがそれらのデータセットにアクセスできるようにします。新しいデータセット検出エクスペリエンス (下記参照) は、自分がアクセスできるすべてのデータセットを簡単に見つけるための単一の画面をユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="d0265-110">A new permission model ensures that only the right users get access to those datasets; a new dataset discovery experience (shown below) provides users with a single pane of glass to easily find all datasets they have access to.</span></span> <span data-ttu-id="d0265-111">この検出エクスペリエンスは、サービスとデスクトップの両方で一貫しています。</span><span class="sxs-lookup"><span data-stu-id="d0265-111">This discovery experience will be consistent in both the service and the desktop.</span></span>

<span data-ttu-id="d0265-112">*認定データセット*により、組織がユーザーを信頼できる正式なデータセットに誘導することが容易になります。</span><span class="sxs-lookup"><span data-stu-id="d0265-112">*Certified datasets* make it easier for organizations to steer users toward trusted and authoritative datasets.</span></span> <span data-ttu-id="d0265-113">データセットのこの "承認のスタンプ" は、新しいテナント設定で定義された特定の Power BI ユーザーグループだけが適用できます。</span><span class="sxs-lookup"><span data-stu-id="d0265-113">This "stamp of approval" for a dataset can only be applied by a specific group of Power BI users as defined in a new tenant setting.</span></span> <span data-ttu-id="d0265-114">データセットが認定されると、新しいデータセット検出エクスペリエンスに目立つように表示され、レポート作成者がこれらの高品質なデータ ソースを簡単に見つけて活用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d0265-114">Once a dataset is certified, it shows up prominently in the new dataset discovery experience, making sure report authors can effortlessly find and leverage these high-quality sources of data.</span></span> 

<span data-ttu-id="d0265-115">![コメントの例](media/certified-datasets.png "認定データセット")</span><span class="sxs-lookup"><span data-stu-id="d0265-115">![Commenting example](media/certified-datasets.png "Certified datasets")</span></span>

