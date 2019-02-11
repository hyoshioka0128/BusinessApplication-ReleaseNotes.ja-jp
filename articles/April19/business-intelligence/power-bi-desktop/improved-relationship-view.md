---
title: リレーションシップ ビューの改善
description: レポート作成者は、何十ものテーブルと何百ものフィールドを含むレポートを作成できます。
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: 25bdc241018f46d95d2562092d71cac41a8e1c6e
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210834"
---
# <a name="improved-relationship-view"></a><span data-ttu-id="b0e06-103">リレーションシップ ビューの改善</span><span class="sxs-lookup"><span data-stu-id="b0e06-103">Improved relationship view</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="b0e06-104">レポート作成者は、何十ものテーブルと何百ものフィールドを含むレポートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-104">Report authors can create reports that contain dozens of tables and hundreds of fields.</span></span> <span data-ttu-id="b0e06-105">リレーションシップ ビューを改善し、大規模なモデルをもっと扱いやすくする予定です。</span><span class="sxs-lookup"><span data-stu-id="b0e06-105">We will be improving the relationship view to make it easier to deal with large-scale models.</span></span> <span data-ttu-id="b0e06-106">テーブルの数が増えるにつれて、1 つの図でリレーションシップのネットワークを理解し維持することはますます困難になります。</span><span class="sxs-lookup"><span data-stu-id="b0e06-106">As the number of tables grows, it becomes increasingly difficult to understand and maintain the network of relationships in a single diagram.</span></span> <span data-ttu-id="b0e06-107">改善されたリレーションシップ ビューでは、複数のレイアウトを作成でき、それぞれのレイアウトにテーブルのサブセットとそれらの間のリレーションシップを表示できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-107">The improved relationship view will allow multiple layouts to be created, each of which can show a subset of the tables, and the relationships between them.</span></span> <span data-ttu-id="b0e06-108">主題領域に関連する表だけを含む別々の図を作成することも可能です。</span><span class="sxs-lookup"><span data-stu-id="b0e06-108">It will be possible to have separate diagrams containing just the tables that are relevant to a subject area.</span></span>

<span data-ttu-id="b0e06-109">次の例では、メイン レイアウト "All tables" にモデル内の 16 個のテーブルがすべて含まれていますが、"Quota" レイアウトにはクォータに関連する 3 つのテーブルだけが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b0e06-109">In the following example, while the main layout “All tables” includes all 16 tables in the model, the “Quota” layout includes just the three tables relevant to Quota.</span></span> <span data-ttu-id="b0e06-110">フィールド リストからドラッグするか、すでにレイアウトに含まれているテーブルを選択してそれに関連するすべてのテーブルを含めることで、テーブルをレイアウトに追加できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-110">Tables can be added to a layout by dragging from the field list, or by including all tables that are related to a chosen table that is already included in the layout.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0e06-111">![改善されたリレーションシップ ビューで多数のテーブルがあるモデル](media/improved-relationship-view-1.png "改善されたリレーションシップ ビューで多数のテーブルがあるモデル")
<!-- picture -->
*改善されたリレーションシップ ビューで多数のテーブルがあるモデル*</span><span class="sxs-lookup"><span data-stu-id="b0e06-111">![A model with many tables in the improved relationship view](media/improved-relationship-view-1.png "A model with many tables in the improved relationship view")
<!-- picture -->
*A model with many tables in the improved relationship view*</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0e06-112">![モデル内のテーブルのサブセットが表示されている改善されたリレーションシップ ビュー](media/improved-relationship-view-2.png "モデル内のテーブルのサブセットが表示されている改善されたリレーションシップ ビュー")
<!-- picture -->
*モデル内のテーブルのサブセットが表示されている改善されたリレーションシップ ビュー*</span><span class="sxs-lookup"><span data-stu-id="b0e06-112">![Improved relationship view showing a subset of the tables in your model](media/improved-relationship-view-2.png "Improved relationship view showing a subset of the tables in your model")
<!-- picture -->
*Improved relationship view showing a subset of the tables in your model*</span></span>

<span data-ttu-id="b0e06-113">新しいリレーションシップ ビューでは、モデル サイズが大きくなっても、テーブルや列にプロパティを簡単に設定できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-113">The new relationship view will also make it easier to set properties on tables and columns as the model size grows.</span></span> <span data-ttu-id="b0e06-114">フィールド リストでオブジェクト (テーブル、列、メジャーなど) を選択すると、そのオブジェクトのすべてのプロパティ (表示設定、書式設定、既定の集計など) がプロパティ ウィンドウに表示され、値を変更できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-114">When an object (table, column, measure, and so on) is selected in the field list, then all the properties (visibility, formatting settings, default summarization etc.) of that object will be displayed in the property pane, where the values can be changed.</span></span> <span data-ttu-id="b0e06-115">さらに、フィールド リストで複数のオブジェクトを選択してから、選択した*すべての*オブジェクトのプロパティの値を 1 回の編集で変更することもできます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-115">In addition, it will be possible to select multiple objects in the field list, and then change the value of properties for *all* of the selected objects, in a single edit.</span></span>

<span data-ttu-id="b0e06-116">次の例では、千単位の区切り記号の使用および表示する小数点以下の桁数に関する書式設定オプションを、選択した 3 つのフィールド "SalesAmount"、"TaxAmt"、"TotalProductCost" について、1 回の編集で簡単に変更できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-116">In the following example, the formatting options for use of a thousand’s separator, and the number of decimal places to display, can easily be changed in one edit for the three selected fields “SalesAmount”, “TaxAmt”, and “TotalProductCost”.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0e06-117">![改善されたリレーションシップ ビューでは、プロパティの書式設定を一括編集で簡単に変更できる](media/improved-relationship-view-3.png "改善されたリレーションシップ ビューでは、プロパティの書式設定を一括編集で簡単に変更できる")
<!-- picture -->
*改善されたリレーションシップ ビューでは、プロパティの書式設定を一括編集で簡単に変更できる*</span><span class="sxs-lookup"><span data-stu-id="b0e06-117">![Formatting of properties can easily be modified with bulk edit in the improved relationship view](media/improved-relationship-view-3.png "Formatting of properties can easily be modified with bulk edit in the improved relationship view")
<!-- picture -->
*Formatting of properties can easily be modified with bulk edit in the improved relationship view*</span></span>

<span data-ttu-id="b0e06-118">レポート ビューのフィールド リストの場合と同様に、検索を使用してテーブルやフィールドを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-118">It will be possible to use search to find tables and fields, as is the case for the field list in the report view.</span></span>

<span data-ttu-id="b0e06-119">最後に、プロパティには新しい "フォルダーの表示" プロパティが含まれます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-119">Finally, properties will include a new “Display folder” property.</span></span> <span data-ttu-id="b0e06-120">これにより、モデル作成者はフィールドをフォルダーに整理して、多数のフィールドを単一のフラット リストとして表示するのを回避できます。</span><span class="sxs-lookup"><span data-stu-id="b0e06-120">This allows the model author to organize fields into folders to avoid dozens of fields being presented as a single flat list.</span></span> <span data-ttu-id="b0e06-121">次の例では、Customer テーブルの一部のフィールドが、"Contact Information" と "Demographics" というフォルダーにまとめられています。</span><span class="sxs-lookup"><span data-stu-id="b0e06-121">In the following example, some fields on the Customer table have been organized in folders for “Contact Information” and “Demographics”.</span></span> <span data-ttu-id="b0e06-122">その後、Power BI Desktop 内と、レポートを Power BI サービスに発行した後の両方で、フィールドを表示するときにこの編成を使用します。</span><span class="sxs-lookup"><span data-stu-id="b0e06-122">This organization will then be used when displaying the fields, both within the Power BI Desktop and after publishing the report to the Power BI service.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="b0e06-123">![Power BI Desktop で表示フォルダーを作成できる](media/improved-relationship-view-4.png "Power BI Desktop で表示フォルダーを作成できる")
<!-- picture -->
*Power BI Desktop で表示フォルダーを作成できる*</span><span class="sxs-lookup"><span data-stu-id="b0e06-123">![Display folders can be created in Power BI Desktop](media/improved-relationship-view-4.png "Display folders can be created in Power BI Desktop")
<!-- picture -->
*Display folders can be created in Power BI Desktop*</span></span>
