---
title: データ エクスポートのレポートごとの制御
description: レポート作成者は、Power BI サービスにレポートが公開されたときにコンシューマーが利用できるデータ エクスポート オプションを柔軟に制御できるようになりました。
author: MI77
ms.date: 12/12/2018
ms.topic: article
ms.service: business-applications
ms.author: willthom
ms.openlocfilehash: c16c478827a3103d77fc6a03619262bbd0e243b8
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287706"
---
#  <a name="per-report-control-of-data-export"></a><span data-ttu-id="893a4-103">データ エクスポートのレポートごとの制御</span><span class="sxs-lookup"><span data-stu-id="893a4-103">Per-report control of data export</span></span> 

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="893a4-104">レポート作成者は、Power BI サービスにレポートが公開されたときにコンシューマーが利用できるデータ エクスポート オプションを柔軟に制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="893a4-104">Report authors now have the flexibility to control the data export options available to consumers when the report is published to the Power BI service.</span></span> <span data-ttu-id="893a4-105">作成者は次の設定を選択できます。</span><span class="sxs-lookup"><span data-stu-id="893a4-105">The author can choose to:</span></span>

-   <span data-ttu-id="893a4-106">エンド ユーザーが Power BI サービスから概要データをエクスポートできるようにする。</span><span class="sxs-lookup"><span data-stu-id="893a4-106">Allow end users to export summarized data from the Power BI service.</span></span>
-   <span data-ttu-id="893a4-107">エンド ユーザーが概要データと基になるデータの両方をエクスポートできるようにする。</span><span class="sxs-lookup"><span data-stu-id="893a4-107">Allow end users to export both summarized and underlying data.</span></span>
-   <span data-ttu-id="893a4-108">エンド ユーザーがサービスからデータをエクスポートできないようにする。</span><span class="sxs-lookup"><span data-stu-id="893a4-108">Block end users from exporting any data from the service.</span></span>

<span data-ttu-id="893a4-109">新しいレポートの既定値では、概要データのエクスポートのみが可能になります。</span><span class="sxs-lookup"><span data-stu-id="893a4-109">The default for new reports will be to only allow the export of summarized data.</span></span>
<span data-ttu-id="893a4-110">ユーザーはこの設定を Power BI Desktop の [レポート設定] にあるオプション ダイアログから更新できます。</span><span class="sxs-lookup"><span data-stu-id="893a4-110">Users can update this setting in the Power BI Desktop through the options dialog under Report Settings.</span></span>

<span data-ttu-id="893a4-111">既存のレポートに対するデータ エクスポート設定は変更されません。</span><span class="sxs-lookup"><span data-stu-id="893a4-111">The export data settings for existing reports will be unchanged.</span></span> <span data-ttu-id="893a4-112">概要データのエクスポートのみを可能にする場合、作成者はレポート オプションにアクセスして、既存のレポートに対するそれらの設定を変更する必要があります。</span><span class="sxs-lookup"><span data-stu-id="893a4-112">If authors would like to only allow the export of summarized data, they must go to the report options and change those settings for existing reports.</span></span>

<span data-ttu-id="893a4-113">![Power BI Desktop でデータをエクスポートするためのレポート設定](media/per-report-control-data-export-1.png "Power BI Desktop でデータをエクスポートするためのレポート設定")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="893a4-113">![Report settings for exporting data in Power BI Desktop](media/per-report-control-data-export-1.png "Report settings for exporting data in Power BI Desktop")
<!-- picture --></span></span>

<span data-ttu-id="893a4-114">ユーザーはこの設定を Power BI サービスのレポート設定ウィンドウから更新することもできます。</span><span class="sxs-lookup"><span data-stu-id="893a4-114">Users can also update this setting in the Power BI service through the report settings pane.</span></span>

<span data-ttu-id="893a4-115">![Power BI サービスでデータをエクスポートするためのレポート設定](media/per-report-control-data-export-2.png "Power BI サービスでデータをエクスポートするためのレポート設定")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="893a4-115">![Report settings for exporting data in Power BI service](media/per-report-control-data-export-2.png "Report settings for exporting data in Power BI service")
<!-- picture --></span></span>

## <a name="resources"></a><span data-ttu-id="893a4-116">リソース</span><span class="sxs-lookup"><span data-stu-id="893a4-116">Resources</span></span>
[<span data-ttu-id="893a4-117">ビジュアル化の作成に使用されたデータをエクスポートする</span><span class="sxs-lookup"><span data-stu-id="893a4-117">Export the data used to create the visualization</span></span>](https://docs.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-export-data)
