---
title: "Excel への最大 100 万行のエクスポート"
description: "ユーザーは、これまでより大きいデータセットを Excel にエクスポートできます"
author: jasongre
manager: AnnBe
ms.date: 01/22/2019
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: admin, end user, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 041a3b63349c945c85216566b140ca6e75294b4b
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

# <a name="export-up-to-1-million-rows-to-excel"></a><span data-ttu-id="6eae5-103">Excel への最大 100 万行のエクスポート</span><span class="sxs-lookup"><span data-stu-id="6eae5-103">Export up to 1 million rows to Excel</span></span>

<span data-ttu-id="6eae5-104">Excel へのエクスポート機能では、Finance and Operations のグリッドから最大 100 万行をエクスポートできるように構成できるようになり、以前の 10,000 行の制限から大幅に増加しました。</span><span class="sxs-lookup"><span data-stu-id="6eae5-104">The Export to Excel feature can now be configured to allow users to export up to 1 million rows from a grid in Finance and Operations, a substantial increase from the previous 10,000-row limit.</span></span> <span data-ttu-id="6eae5-105">既定では、エクスポートの制限は 50,000 行に設定されていますが、**クライアント パフォーマンス オプション** ページで、システム管理者はエクスポートの上限を 100 万行まで調整できます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-105">By default, the export limit is set to 50,000 rows, but through the **Client performance options** page, system administrators can adjust the export limit as high as 1 million rows.</span></span>  

<span data-ttu-id="6eae5-106">Finance and Operations で Excel にエクスポートできるデータセットが大きくなったため、Excel へのエクスポート機能のユーザー エクスペリエンスに対して 2 つの調整が加えられました。</span><span class="sxs-lookup"><span data-stu-id="6eae5-106">Because Finance and Operations can now allow much larger datasets to be exported to Excel, two adjustments have been made to the user's experience with the Export to Excel feature.</span></span>

-    <span data-ttu-id="6eae5-107">エクスポートの間に表示される新しいダイアログでは、ユーザーにフィードバックと進行状況が提供されます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-107">A new dialog is shown during the export that provides the user with feedback and progress.</span></span> <span data-ttu-id="6eae5-108">また、このダイアログでは、ユーザーはいつでもエクスポートを停止し、それまでにエクスポートされたデータを含むファイルを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-108">The dialog also allows the user to stop the export at any point and get a file containing the data exported so far.</span></span> <span data-ttu-id="6eae5-109">エクスポートの速度はデータセットによって異なり、エクスポートされる行数、グリッドの列数、表示方法の有無 (計算列)、グリッド内のディメンション フィールドの有無に依存します。</span><span class="sxs-lookup"><span data-stu-id="6eae5-109">The speed of the export will vary by dataset and will be dependent on the number of rows exported, the number of columns in the grid, the presence of display methods (calculated columns), and the presence of dimension fields in the grid.</span></span> <span data-ttu-id="6eae5-110">この機能は、Platform update 22 で利用できます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-110">This feature is available in Platform update 22.</span></span>

      <span data-ttu-id="6eae5-111">![エクスポート進行状況のダイアログ](media/largeExport.png  "エクスポート進行状況のダイアログ")</span><span class="sxs-lookup"><span data-stu-id="6eae5-111">![Export progress dialog](media/largeExport.png  "Export progress dialog")</span></span>

-  <span data-ttu-id="6eae5-112">エクスポートの完了後、ユーザーは、エクスポート完了通知をアクション センターで受け取ります。</span><span class="sxs-lookup"><span data-stu-id="6eae5-112">After the export completes, users receive a notification in the Action center alerting them that the export has finished.</span></span> <span data-ttu-id="6eae5-113">この通知には、エクスポートされたデータを含む Excel ファイルをダウンロードするためのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-113">The notification includes a link to download the Excel file containing the exported data.</span></span> <span data-ttu-id="6eae5-114">リンクと通知には、エクスポートが完了してからおよそ 3 日間アクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-114">The link and notification are accessible for roughly three days after the export completes.</span></span> <span data-ttu-id="6eae5-115">この機能は、Platform update 23 で利用できます。</span><span class="sxs-lookup"><span data-stu-id="6eae5-115">This feature is available in Platform update 23.</span></span>     

<span data-ttu-id="6eae5-116">詳細については、「[Office 統合のトラブルシューティング](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/office-integration/office-integration-troubleshooting)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6eae5-116">For more information, see [Troubleshoot the Office integration](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/office-integration/office-integration-troubleshooting).</span></span>


