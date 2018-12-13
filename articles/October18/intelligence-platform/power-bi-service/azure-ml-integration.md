---
redirect_url: ../../change-history
title: "Azure Machine Learning の統合"
description: "Power Query を使用して Azure Machine Learning モデルにアクセスします。"
author: SantoshC
manager: RichTk
ms.date: 09/27/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: SantoshC
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: f872ddf2157fa0b1a033b8d289c3d464c6293768
ms.openlocfilehash: f1bed7384048ec88fccda25bdf680b3e14bc16d3
ms.contentlocale: ja-jp
ms.lasthandoff: 12/13/2018

---
#  <a name="access-azure-machine-learning-models-in-power-query-public-preview"></a><span data-ttu-id="177a5-103">Power Query で Azure Machine Learning モデルにアクセスする (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="177a5-103">Access Azure Machine Learning models in Power Query (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]


<span data-ttu-id="177a5-104">ユーザーは、Power BI の Power Query 関数として Azure Machine Learning モデルに動的にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="177a5-104">Users can dynamically access Azure Machine Learning models as Power Query functions in Power BI.</span></span>
<span data-ttu-id="177a5-105">ユーザーが Azure ポータルから Azure Machine Learning モデルへのアクセスを許可されると、</span><span class="sxs-lookup"><span data-stu-id="177a5-105">When a user is granted access to an Azure Machine Learning model through the Azure portal, the</span></span>  
<span data-ttu-id="177a5-106">モデルは自動的に Power Query 関数として利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="177a5-106">model is automatically available as a Power Query function.</span></span> <span data-ttu-id="177a5-107">テーブルの列名は、名前が一致したときに Power Query 関数の Azure Machine Learning モデルへの入力として自動的にマップされます。</span><span class="sxs-lookup"><span data-stu-id="177a5-107">Column names from the table are automatically mapped as inputs to the Azure Machine Learning model in the Power Query function when the names match.</span></span> <span data-ttu-id="177a5-108">これにより、ユーザーは、取り込みまたはリフレッシュ時に Azure Machine Learning モデルをデータに簡単に適用できます。</span><span class="sxs-lookup"><span data-stu-id="177a5-108">This enables users to easily apply the Azure Machine Learning model to their data upon ingestion or refresh.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="177a5-109">![](media/azure-ml-integration.png "Power Query を使用して Azure Machine Learning モデルにアクセスする")</span><span class="sxs-lookup"><span data-stu-id="177a5-109">![](media/azure-ml-integration.png "Access Azure Machine Learning models using Power Query")</span></span>

<span data-ttu-id="177a5-110">*Power Query を使用して Azure Machine Learning モデルにアクセスする*</span><span class="sxs-lookup"><span data-stu-id="177a5-110">*Access Azure Machine Learning models using Power Query*</span></span>

