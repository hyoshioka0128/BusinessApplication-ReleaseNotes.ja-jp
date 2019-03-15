---
title: 電子申告 - 法人別のパラメーターの設定
description: 現時点では、電子申告の構成でデータをフィルター処理するために、法人固有の値を設定する機能はありません。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: af21632089dc16587e2e5dd9840673dc45fc13ac
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "286770"
---
#  <a name="electronic-reporting---setting-up-parameters-by-legal-entity"></a><span data-ttu-id="01169-103">電子申告 - 法人別のパラメーターの設定</span><span class="sxs-lookup"><span data-stu-id="01169-103">Electronic reporting - Setting up parameters by legal entity</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="01169-104">電子申告の構成では、多くの場合、各法人に固有の値セットに基づいてデータをフィルター処理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="01169-104">In many electronic reporting configurations, some data must be filtered based on a set of values that are specific for each legal entity.</span></span> <span data-ttu-id="01169-105">現在のところ、パワー ユーザーは、構成済みの電子申告 (ER) モデル マッピングか、ER 形式の一部としてのみ、このようなデータセットを指定できます。</span><span class="sxs-lookup"><span data-stu-id="01169-105">Currently, a power user can specify such data sets only as part of configured Electronic reporting (ER) model mappings or ER formats.</span></span> <span data-ttu-id="01169-106">そのため、この種の ER 構成は、特定の Microsoft Dynamics 365 for Finance and Operations インスタンスの設定に依存するものとなっています。その結果、この種の ER 構成やその抽出コピーを配布したり、それらをさらにメンテナンスするには、複雑な作業が伴います。</span><span class="sxs-lookup"><span data-stu-id="01169-106">This makes such ER configurations dependent on settings of the particular Microsoft Dynamics 365 for Finance and Operations instance and complicates distribution as well as further maintenance of such ER configurations and their derived copies.</span></span>

<span data-ttu-id="01169-107">この構成固有のパラメーター機能を使用すると、パワーユーザーは ER 形式内で抽象データ ソースを構成し、そのデータ ソースがビジネス ユーザーによってどのように入力されるかを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="01169-107">This configuration-specific parameters feature will allow a power user to configure in an ER format an abstract data source specifying how this data source will be filled in by a business user:</span></span>

-   <span data-ttu-id="01169-108">このデータ ソースを入力したビジネス ユーザーの要求に対して、どのようなデータが提供されるのか。</span><span class="sxs-lookup"><span data-stu-id="01169-108">What data will be offered upon request of a business user filling in this data source.</span></span>
-   <span data-ttu-id="01169-109">このデータ ソースによって、実行時にどのような種類の値が ER 形式に返されるのか。</span><span class="sxs-lookup"><span data-stu-id="01169-109">What type of values will be returned back to an ER format at run time by this data source.</span></span>

<span data-ttu-id="01169-110">![形式デザイナー: 課税 XML 要素](media/ER-setup-parameters-designer.png "形式デザイナー: 課税 XML 要素")</span><span class="sxs-lookup"><span data-stu-id="01169-110">![Format designer: Taxation XML Element](media/ER-setup-parameters-designer.png "Format designer: Taxation XML Element")</span></span>

<span data-ttu-id="01169-111">このデータ ソースを使用することで、パワー ユーザーはデータ ソースに関連する実際の法人を参照することなく、法人非依存のルールとして、ER 形式内にデータ フィルター処理を構成することができます。</span><span class="sxs-lookup"><span data-stu-id="01169-111">By using this data source, a power user may configure data filtering in an ER format as a legal entity independent rule having no references to actual legal entity related data sources.</span></span>

<span data-ttu-id="01169-112">![形式デザイナーのマッピングのスクリーンショット](media/ER-setup-parameters-datasource.png "形式デザイナーのマッピングのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="01169-112">![Format designer mapping screenshot](media/ER-setup-parameters-datasource.png "[Format designer mapping screenshot")</span></span>

<span data-ttu-id="01169-113">この機能を使用すると、ビジネス ユーザーは Finance and Operations のユーザー インターフェイスで、ER 形式固有の会社マスター データを設定することができます。</span><span class="sxs-lookup"><span data-stu-id="01169-113">This feature will allow a business user to set up an ER format-specific company master data in the Finance and Operations user interface.</span></span>

<span data-ttu-id="01169-114">![アプリケーション固有のパラメーター: 条件画面 1](media/ER-setup-parameters-UI.png "アプリケーション固有のパラメーター: 条件画面 1")</span><span class="sxs-lookup"><span data-stu-id="01169-114">![Application-specific parameters: Conditions screen 1](media/ER-setup-parameters-UI.png "Application-specific parameters: Conditions screen 1")</span></span>

<span data-ttu-id="01169-115">これは、対応する ER 形式の実行を制御する可能性がある、任意の法人に対して行うことができます。</span><span class="sxs-lookup"><span data-stu-id="01169-115">This can be done for any legal entity that might control execution of the corresponding ER format.</span></span>

<span data-ttu-id="01169-116">![アプリケーション固有のパラメーター: 条件画面 2](media/ER-setup-parameters-UI-screen-2.png "アプリケーション固有のパラメーター: 条件画面 2")</span><span class="sxs-lookup"><span data-stu-id="01169-116">![Application-specific parameters: Conditions screen 2](media/ER-setup-parameters-UI-screen-2.png "Application-specific parameters: Conditions screen 2")</span></span>

<span data-ttu-id="01169-117">ER 形式の実行中は、その実行を制御している法人に応じて、ER 形式の対応するデータ ソースにより、法人固有のマスター データのセットが使用されます。</span><span class="sxs-lookup"><span data-stu-id="01169-117">While an ER format is run, a legal entity specific set of master data will be used by a corresponding data source of an ER format depending on a legal entity controlling this execution.</span></span>

<span data-ttu-id="01169-118">この機能では、ビジネス ユーザーが 1 つの Finance and Operations インスタンスから ER 形式固有の会社マスター データをエクスポートし、それを別のインスタンスにインポートすることもできます。</span><span class="sxs-lookup"><span data-stu-id="01169-118">This feature also enables a business user to export an ER format-specific company master data from one Finance and Operations instance and import it to another one.</span></span>

