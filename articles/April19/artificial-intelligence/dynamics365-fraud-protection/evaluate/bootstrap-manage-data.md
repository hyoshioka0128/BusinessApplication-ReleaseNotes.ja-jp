---
title: データのブートストラップと管理
description: データは良い決断の礎です。
author: jackwi111
manager: josaw
ms.date: 02/21/2019
ms.assetid: 4408f694-9951-46ec-b363-2dd80087b248
ms.topic: article
ms.custom:
- dyn365-fieldservice
ms.service: dynamics-365-customerservice
ms.author: v-jowigh
ms.openlocfilehash: ba6d5d500536d6748d56ad101d77a8151ede3a9b
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225123"
---
#  <a name="bootstrap-and-manage-your-data"></a><span data-ttu-id="b0f82-103">データのブートストラップと管理</span><span class="sxs-lookup"><span data-stu-id="b0f82-103">Bootstrap and manage your data</span></span>
[!include[dynamics365-fraud-protection banner](../../../includes/dynamics365-fraud-protection.md)]






<span data-ttu-id="b0f82-104">データは良い決断の礎です。</span><span class="sxs-lookup"><span data-stu-id="b0f82-104">Data is the cornerstone of good decisions.</span></span> <span data-ttu-id="b0f82-105">履歴データを Dynamics 365 Fraud Protection にブートストラップして、リスク決定の正確さを高めることができます。</span><span class="sxs-lookup"><span data-stu-id="b0f82-105">You can bootstrap your historical data into Dynamics 365 Fraud Protection to increase the accuracy of your risk decisions.</span></span> <span data-ttu-id="b0f82-106">ブートストラップには、不正検出の改善に役立つ、購入、チャージバック、および業者や銀行の決定などの重要なシグナルといったデータが含まれます。</span><span class="sxs-lookup"><span data-stu-id="b0f82-106">Bootstrapping includes data containing purchase, chargeback, and other key signals, like merchant and bank decisions, that help improve fraud detection.</span></span>
<span data-ttu-id="b0f82-107">この履歴データを使用することで、機械学習モデルを準備するプロセスを短縮できます。</span><span class="sxs-lookup"><span data-stu-id="b0f82-107">Using this historical data accelerates the process of priming our machine learning model.</span></span>

<span data-ttu-id="b0f82-108">Microsoft Azure リポジトリからのデータ ストリームを Dynamics 365 Fraud Protection に取り込み、それを基本/拡張オントロジーにマップし、1 回限りまたは反復的な一括データ取り込みジョブを設定してナレッジ グラフを生成することができます。</span><span class="sxs-lookup"><span data-stu-id="b0f82-108">You can choose to bring data streams from your Microsoft Azure repository into Dynamics 365 Fraud Protection, map them to the base/extended ontology, and set up a one-time or recurring bulk data ingestion jobs to populate the knowledge graph.</span></span> <span data-ttu-id="b0f82-109">Dynamics 365 Fraud Protection では、これらの反復的な一括取り込みジョブの信頼性を監視し、欠落データや不正なデータを検出して、障害に関する警告を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="b0f82-109">With Dynamics 365 Fraud Protection, you can monitor the reliability of these recurring bulk ingestion jobs, detect missing or malformed data, and get alerted about failures.</span></span>
