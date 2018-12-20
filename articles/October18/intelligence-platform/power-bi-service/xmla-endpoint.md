---
title: "サードパーティ クライアント接続と監視のための XMLA エンドポイント"
description: 
author: adamw
manager: PaBenj
ms.date: 12/05/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: HaydnR
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 6b6290afd87b7786a135a154041de9416f0dbc7f
ms.openlocfilehash: d2df7d981542e668d164b2e0ecc6ae93e4987b77
ms.contentlocale: ja-jp
ms.lasthandoff: 12/05/2018

---
# <a name="xmla-endpoint-for-third-party-client-connectivity-and-monitoring-public-preview"></a><span data-ttu-id="02fdf-102">サードパーティ クライアント接続と監視のための XMLA エンドポイント (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="02fdf-102">XMLA endpoint for third-party client connectivity and monitoring (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="02fdf-103">Power BI サービス内のデータセットに対して XMLA プロトコルがサポートされたことで、お客様はこれまで以上に柔軟な方法で、BI 展開を提供および管理できるようになります。</span><span class="sxs-lookup"><span data-stu-id="02fdf-103">With the support of the XMLA protocol for datasets in the Power BI service, customers will have more flexibility in how they deliver and manage their BI deployments.</span></span> <span data-ttu-id="02fdf-104">XMLA は SQL Server Analysis Services や Azure Analysis Services のモデル管理に使用されるのと同じプロトコルなので、さまざまな Microsoft ツールやサードパーティ ツールが有効になります。</span><span class="sxs-lookup"><span data-stu-id="02fdf-104">Since XMLA is the same protocol used for managing SQL Server Analysis Services and Azure Analysis Services models, a variety of Microsoft and third-party tools will be enabled.</span></span>

<span data-ttu-id="02fdf-105">XMLA エンドポイントにより、分析、デバッグ、監視のためにサードパーティ アプリケーションから Power BI データセットへの読み取り専用接続のみが許可されます。</span><span class="sxs-lookup"><span data-stu-id="02fdf-105">The XMLA endpoint will allow read-only connectivity to Power BI datasets from third-party applications for analysis, debugging, and monitoring.</span></span>

<span data-ttu-id="02fdf-106">将来のリリースでは書き込みアクセスが許可されるので、スクリプトやアプリケーションから、データセットの管理や更新をプログラムによって行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="02fdf-106">A future release will allow write access, enabling programmability to manage and update datasets from scripts or applications.</span></span> <span data-ttu-id="02fdf-107">これにより、Power BI データセットのモデル化、ライフサイクル管理、操作のシナリオが可能になります。</span><span class="sxs-lookup"><span data-stu-id="02fdf-107">This will enable scenarios for modeling, lifecycle management, and operations for Power BI datasets.</span></span> <span data-ttu-id="02fdf-108">Analysis Services の表形式モデリング機能がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="02fdf-108">Analysis Services tabular modeling features will be supported.</span></span>

