---
title: Common Data Service コネクタで環境を選択する
description: Common Data Service コネクタで環境を選択する
author: aorth
ms.reviewer: anneta
ms.date: 05/17/2019
ms.assetid: dbb2b284-2c65-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: a0e216b0e830165995b810217a393aa1c2b4802f
ms.sourcegitcommit: 6c1c9ed9328a3b6194ebc4741d0beeef0ef435f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/23/2019
ms.locfileid: "1605798"
---
# <a name="select-an-environment-with-the-common-data-service-connector"></a><span data-ttu-id="cc854-103">Common Data Service コネクタで環境を選択する</span><span class="sxs-lookup"><span data-stu-id="cc854-103">Select an environment with the Common Data Service connector</span></span>

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="cc854-104">キャンバス アプリの作成者は、Common Data Service で 1 つ以上のエンティティに接続するときに環境を選択できます。</span><span class="sxs-lookup"><span data-stu-id="cc854-104">Canvas-app makers can choose an environment when they connect to one or more entities in Common Data Service.</span></span> <span data-ttu-id="cc854-105">この変更の前は、作成者はキャンバス アプリが展開された環境内のエンティティにだけ接続できました。</span><span class="sxs-lookup"><span data-stu-id="cc854-105">Before this change, makers could connect to entities only in the environment where the canvas app was deployed.</span></span> <span data-ttu-id="cc854-106">現在の環境は、単一の環境で構築されて実行されるアプリ、または開発と運用のために環境を移行されるアプリに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cc854-106">The current environment is useful for apps that are built and run in a single environment or that migrate through environments for development and production.</span></span> <span data-ttu-id="cc854-107">この機能を使用すると、アプリ作成者は特定の環境を選択でき、これはアプリ内の別の既存環境を参照するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cc854-107">With this feature, app makers can choose a specific environment, which is useful for referencing a separate existing environment within an app.</span></span> <span data-ttu-id="cc854-108">この場合、アプリが別の環境に移行されても、データ ソースは変化しません。</span><span class="sxs-lookup"><span data-stu-id="cc854-108">In this case, the data source doesn't change when the app is migrated to another environment.</span></span>

<span data-ttu-id="cc854-109">![環境を変更する](media/cds-change-environment.png "環境を変更する")</span><span class="sxs-lookup"><span data-stu-id="cc854-109">![Change environment](media/cds-change-environment.png "Change environment")</span></span>

<span data-ttu-id="cc854-110">![環境を選択する](media/cds-select-environment.png "環境を選択する")</span><span class="sxs-lookup"><span data-stu-id="cc854-110">![Select environment](media/cds-select-environment.png "Select environment")</span></span>
