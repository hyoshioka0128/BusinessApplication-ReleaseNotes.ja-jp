---
title: Azure の統合
description: Power BI と Azure Data Lake Storage Gen2 との間でデータ アクセスを統合することによる、ロール間でのコラボレーション
author: adiregev
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: antonfrMSFT
ms.reviewer: mihart
ms.openlocfilehash: cfa0faab0618205dc67a15abde2b2febd900e98a
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "211017"
---
# <a name="azure-integration"></a><span data-ttu-id="13866-103">Azure の統合</span><span class="sxs-lookup"><span data-stu-id="13866-103">Azure integration</span></span>
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]

<span data-ttu-id="13866-104">Power BI を構成して、組織の Azure Data Lake Storage Gen2 アカウントの Common Data Model 準拠のフォルダーにデータを格納できます。このアカウントでは、データ開発者やデータ サイエンティストは Azure サービスを介してそのデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="13866-104">Power BI can be configured to store data in Common Data Model-compliant folders in your organization’s Azure Data Lake Storage Gen2 account where data developers and data scientists can access that data via Azure services.</span></span> <span data-ttu-id="13866-105">Common Data Model 準拠のフォルダーの読み取りと書き込みのサポートが組み込まれた Azure サービス (Azure Machine Learning、Azure Databricks、Azure Data Factory など) は徐々に増えていきます。</span><span class="sxs-lookup"><span data-stu-id="13866-105">Over time, more and more Azure services (such as Azure Machine Learning, Azure Databricks, and Azure Data Factory) will introduce built-in support to read and write Common Data Model-compliant folders.</span></span>

<span data-ttu-id="13866-106">Power BI は組織の Azure Data Lake Storage アカウントの Azure サービスによって作成された Common Data Model 準拠のフォルダーに接続することもでき、アナリストは Power BI でこのデータを使ってシームレスに作業できます。</span><span class="sxs-lookup"><span data-stu-id="13866-106">Power BI can also connect to Common Data Model-compliant folders created by Azure services in your organization’s Azure Data Lake Storage account, enabling analysts to work seamlessly with this data in Power BI.</span></span>
