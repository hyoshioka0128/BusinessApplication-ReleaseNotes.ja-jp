---
title: テンプレート アプリ用のセルフサービス ビルダー エクスペリエンス
description: テンプレート アプリの作成者は、アプリをインストールしたユーザーがコンテンツを編集できないようにアプリを構成できます。
author: ezaviv
ms.date: 01/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: avive
ms.openlocfilehash: cc6f0b6227250b41c7ae9342ad0742f4a42b324f
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210249"
---
# <a name="self-service-builder-experience-for-template-apps"></a><span data-ttu-id="2625d-103">テンプレート アプリ用のセルフサービス ビルダー エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="2625d-103">Self-service builder experience for template apps</span></span>

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

<span data-ttu-id="2625d-104">Power BI では、ユーザーがテンプレート アプリ ビルダー モードでテンプレート アプリを作成し、既存のワークスペースを Power BI テンプレート アプリに切り替えることができます。これらのテンプレート アプリは、パッケージ化して他のテナントに展開することができます。</span><span class="sxs-lookup"><span data-stu-id="2625d-104">Power BI enables its users to go into a template app builder mode to create template apps and switch existing workspaces into Power BI template apps that can then be packaged and deployed to other tenants.</span></span> <span data-ttu-id="2625d-105">テンプレート アプリ パッケージは、タイプごとに 1 つのアーティファクト (1 つのダッシュボード、1 つのレポート、1 つのデータセット、1 つのデータフロー) で構成されます。</span><span class="sxs-lookup"><span data-stu-id="2625d-105">The template app package consists of one artifact per type (one dashboard, one report, one dataset, one dataflow).</span></span> <span data-ttu-id="2625d-106">テンプレート アプリの作成者は、アプリをインストールしたユーザーがコンテンツを編集できないようにアプリを構成できます。</span><span class="sxs-lookup"><span data-stu-id="2625d-106">As a template app creator, you can configure your app to block content from being available for editing by those who install the app.</span></span>

<span data-ttu-id="2625d-107">このような展開パッケージを使用できるシナリオは複数考えられます。</span><span class="sxs-lookup"><span data-stu-id="2625d-107">There are several scenarios where such a deployment package could be used.</span></span> <span data-ttu-id="2625d-108">企業内では、テスト環境、運用前環境、運用環境の間でコンテンツを仕上げていくことができます。</span><span class="sxs-lookup"><span data-stu-id="2625d-108">In the enterprise, you can promote content between your test, preproduction, and production environments.</span></span> <span data-ttu-id="2625d-109">システム インテグレーターの場合は、テンプレート アプリを作成して、データの取り込み中にデータフローの一部として実行される "M" コードをベースに、分析ソリューションを提供することができます。つまり、顧客に独自のインサイトを提供するためのデータセットを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="2625d-109">As a system integrator, you can create a template app to deliver an analytics solution based on ‘M’ code running during data ingest as part of a dataflow, or dataset that is used to deliver unique insights for your customers.</span></span>
