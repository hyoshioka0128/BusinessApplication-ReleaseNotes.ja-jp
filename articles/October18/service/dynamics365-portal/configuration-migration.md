---
title: 構成の移行
description: 環境の間で Dynamics 365 Portal の構成を移行します
author: sandhangitmsft
manager: rycu
ms.date: 11/20/2018
ms.assetid: f454a2d3-c047-4a57-8a9f-7ddf38781971
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: sandhan
ms.reviewer: shjais
audience: Admin
ms.openlocfilehash: 6d8652bcf7c057524a81f89745a9afe7564b3e0f
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199511"
---
# <a name="configuration-migration"></a><span data-ttu-id="8158c-103">構成の移行</span><span class="sxs-lookup"><span data-stu-id="8158c-103">Configuration migration</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="8158c-104">ポータルの開発には、ポータルのエンド ユーザーに望ましいエクスペリエンスを実現するための複数の構成とカスタマイズが含まれます。</span><span class="sxs-lookup"><span data-stu-id="8158c-104">Portal development involves several configurations and customizations to achieve a desired experience for portal end users.</span></span> <span data-ttu-id="8158c-105">複数の環境でポータルの構成を管理するために必要な時間と作業を軽減するため、[構成移行 SDK ツール](https://technet.microsoft.com/library/dn647421.aspx)で動作する構成移行用のスキーマが公開されています。</span><span class="sxs-lookup"><span data-stu-id="8158c-105">To reduce the time and effort required to manage portal configuration across environments, we are publishing schema for configuration migration that works with the [Configuration Migration SDK tool](https://technet.microsoft.com/library/dn647421.aspx).</span></span>

<span data-ttu-id="8158c-106">ポータル カスタマイズ担当者はさまざまな方法を使用し、その 1 つとして、構成移行 SDK ツールがさまざまな環境 (一般的には開発、テスト、運用) に構成を移動するためのスキーマ ファイルを一から作成することが含まれます。</span><span class="sxs-lookup"><span data-stu-id="8158c-106">Portal customizers use various ways, including creation of schema files from scratch, for the Configuration Migration SDK tool to move configurations to different environments, typically development, test, and production.</span></span> <span data-ttu-id="8158c-107">スキーマを一から作成すると時間がかかり、そのために一部のデータしか移行できないことがあり、エラーも発生しやすくなります。</span><span class="sxs-lookup"><span data-stu-id="8158c-107">Creating schema from scratch can be time-consuming, sometimes causing partial data migration, and can be error-prone.</span></span>

<span data-ttu-id="8158c-108">構成移行 SDK ツールのすべての機能をこのスキーマで使用して、ポータルの構成を管理できます。</span><span class="sxs-lookup"><span data-stu-id="8158c-108">All Configuration Migration SDK tool capabilities can be used with this schema to manage portal configuration:</span></span>

 - <span data-ttu-id="8158c-109">**スキーマの作成**: ツールで用意されている標準的な方法を使用して、実装に合わせてスキーマを調整することができます。</span><span class="sxs-lookup"><span data-stu-id="8158c-109">**Create schema**: The schema can be tailored for the implementation using standard ways provided by the tool.</span></span> <span data-ttu-id="8158c-110">スキーマ ファイルをツールに読み込んで変更し、構成移行のニーズに適するようにエンティティや属性などを追加、削除、変更できます。</span><span class="sxs-lookup"><span data-stu-id="8158c-110">Schema files can be loaded in the tool and altered to add, remove, and modify entities, attributes, and so on to suit configuration migration needs.</span></span>
 - <span data-ttu-id="8158c-111">**データのエクスポート**: スキーマ ファイルを使用して環境から .zip ファイルにデータをエクスポートし、バックアップ、ソース管理、またはターゲット環境へのインポートに使用します。</span><span class="sxs-lookup"><span data-stu-id="8158c-111">**Export data**: Use the schema file to export data from an environment into a .zip file, and use it for backup, source control, or importing into a target environment.</span></span>
 - <span data-ttu-id="8158c-112">**データのインポート**: エクスポートされたデータを使用して、ターゲット環境にインポートします。</span><span class="sxs-lookup"><span data-stu-id="8158c-112">**Import data**: Use the exported data to import into a target environment.</span></span>


## <a name="wed-like-to-thank"></a><span data-ttu-id="8158c-113">謝辞</span><span class="sxs-lookup"><span data-stu-id="8158c-113">We'd like to thank</span></span>

<span data-ttu-id="8158c-114">優先順位付けに役立つ投票とコメントを[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c)にお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="8158c-114">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) with votes and comments that helped us prioritize it.</span></span>

## <a name="resources"></a><span data-ttu-id="8158c-115">リソース</span><span class="sxs-lookup"><span data-stu-id="8158c-115">Resources</span></span>

[<span data-ttu-id="8158c-116">Dynamics 365 Portal 構成の移行</span><span class="sxs-lookup"><span data-stu-id="8158c-116">Migrate Dynamics 365 Portal configuration</span></span>](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/migrate-portal-configuration)
