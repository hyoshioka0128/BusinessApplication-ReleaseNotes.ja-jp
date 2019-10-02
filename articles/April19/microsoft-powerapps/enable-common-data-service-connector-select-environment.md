---
title: Common Data Service コネクタで環境を選択できるようにする
description: Common Data Service コネクタで環境を選択できるようにする
author: aorth
ms.reviewer: tapanm
ms.date: 07/16/2019
ms.assetid: dbb2b284-2c65-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: 19cb5be20639b6be90d24f43e78b1e9bde4b79c2
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1993978"
---
# <a name="enable-common-data-service-connector-to-select-an-environment"></a><span data-ttu-id="42826-103">Common Data Service コネクタで環境を選択できるようにする</span><span class="sxs-lookup"><span data-stu-id="42826-103">Enable Common Data Service connector to select an environment</span></span>



<span data-ttu-id="42826-104">キャンバス アプリ作成者は、最新の Common Data Service コネクタを使用するときに環境を選択できるようになります。</span><span class="sxs-lookup"><span data-stu-id="42826-104">Canvas apps makers will be able to choose the environment when using the latest Common Data Service connector.</span></span>  <span data-ttu-id="42826-105">このコネクタは現在、キャンバス アプリが展開されている最新の環境のみを使用しています。</span><span class="sxs-lookup"><span data-stu-id="42826-105">The connector currently uses only the current environment where the canvas app is deployed.</span></span>  <span data-ttu-id="42826-106">現在の環境は、単一の環境で構築されて実行されるアプリ、または開発と運用のために複数の環境に移行されるアプリに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="42826-106">The current environment is useful for apps that are built and run in a single environment or apps that migrate through environments for development and production.</span></span>  <span data-ttu-id="42826-107">この機能により、作成者が必要に応じて特定の環境を選択することができるようになります。これは、アプリケーション内で既存の別の環境を参照するときに便利です。</span><span class="sxs-lookup"><span data-stu-id="42826-107">This feature will enable a maker to optionally choose a specific environment, which is useful for referencing a separate existing environment within an application.</span></span>  <span data-ttu-id="42826-108">この場合、アプリが新しい環境に移行されても、データ ソースは変わりません。</span><span class="sxs-lookup"><span data-stu-id="42826-108">In this case the data source does not change when the app is migrated to a new environment.</span></span>


<span data-ttu-id="42826-109">![環境を変更する](media/cds-connector-connector-change-environment.png "環境を変更する")</span><span class="sxs-lookup"><span data-stu-id="42826-109">![Change environment](media/cds-connector-connector-change-environment.png "Change environment")</span></span>

<span data-ttu-id="42826-110">![環境を選択する](media/cds-connector-select-environment.png "環境を選択する")</span><span class="sxs-lookup"><span data-stu-id="42826-110">![Select environment](media/cds-connector-select-environment.png "Select environment")</span></span>
