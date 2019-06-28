---
title: Azure Monitor にオンボードする
description: 顧客が Finance and Operations の環境を予防的に診断および監視できるよう、未加工のテレメトリ データにアクセスできるようにします。
author: ManaliDongre
ms.date: 05/10/2019
ms.assetid: ''
ms.topic: article
ms.service: business-applications
ms.author: manado
ms.openlocfilehash: 74c15c661b4151c032b5ec1145f3281f576f1220
ms.sourcegitcommit: 55dac8945162ba049d9ba8c77127fa88f62d2880
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/10/2019
ms.locfileid: "1540068"
---
# <a name="onboard-to-azure-monitor"></a><span data-ttu-id="ec6c6-103">Azure Monitor にオンボードする</span><span class="sxs-lookup"><span data-stu-id="ec6c6-103">Onboard to Azure Monitor</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="ec6c6-104">顧客は、この機能を使用して、未加工データ、テレメトリ データ、および診断データにアクセスし、アラートを設定したり、ダッシュボードを作成したりして、Finance and Operations 環境を予防的に監視できるようになります。</span><span class="sxs-lookup"><span data-stu-id="ec6c6-104">With this feature, customers will have the option to access raw, telemetry, and diagnostics data so that they can set up alerts and/or create dashboards to proactively monitor their Finance and Operations environment.</span></span> 

<span data-ttu-id="ec6c6-105">未加工のログを取得するには、顧客は独自の Azure サブスクリプションを設定し、Finance and Operations 環境から生成されるログの保存先を選択する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ec6c6-105">To get raw logs, customers will need to set up their own Azure subscription and select a destination location for the logs emitted from their Finance and Operations environment.</span></span><span data-ttu-id="ec6c6-106">ストレージ アカウントへのアーカイブ、ログ分析への送信、またはイベント ハブへのストリーミングを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ec6c6-106"> They can choose to archive to a storage account, send to log analytics, or stream to an event hub.</span></span> <span data-ttu-id="ec6c6-107">この構成が済むと、ほとんどのテレメトリ ログは構成された宛先にルーティングされます。</span><span class="sxs-lookup"><span data-stu-id="ec6c6-107">Once this is configured, most of the telemetry logs will be routed to the configured destination.</span></span> <span data-ttu-id="ec6c6-108">その時点で、顧客はトラブルシューティングにログ分析を使用するか、または高度な分析のためにログを外部のサード パーティ サービスにルーティングするかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ec6c6-108">At that point, customers have the option to use log analytics for troubleshooting or route the logs to an external third-party service for advanced analysis.</span></span> 
