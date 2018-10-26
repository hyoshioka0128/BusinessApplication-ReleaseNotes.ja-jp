---
title: "AppSource で既存の Power BI アプリを更新する"
description: "AppSource で既存の Power BI アプリを更新する"
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: avive
audience: Admin, end user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 471d412ae40cbef021decc560fbc329cfd3fe5d8
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource-public-preview"></a><span data-ttu-id="29ee3-103">AppSource で既存の Power BI アプリを更新する (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="29ee3-103">Update an existing Power BI app in AppSource (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="29ee3-104">アプリケーション ライフサイクル管理 (ALM) については、次の機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="29ee3-104">The application lifecycle management (ALM) story includes the following capabilities:</span></span>

- <span data-ttu-id="29ee3-105">アプリは Power BI ワークスペースをベースとし、追加の設定 (パラメーター) を使用して提供されます。</span><span class="sxs-lookup"><span data-stu-id="29ee3-105">An app is based on a Power BI workspace with additional settings (parameters).</span></span>
- <span data-ttu-id="29ee3-106">アプリには 3 つのリリース レベルがあります: ワークスペース (WIP) --> パッケージ (リリース候補) --> 公開済みアプリ (AppSource を通じてインストールできる、公開済みのコンテンツ) 。</span><span class="sxs-lookup"><span data-stu-id="29ee3-106">There are three release levels for an app: workspace (WIP) --> package (release candidate) --> published app (content that is publicly available to install through AppSource).</span></span>
- <span data-ttu-id="29ee3-107">リリース レベルごとに、1 つのバージョンが保持されます: WIP のワークスペースが 1 つ、パッケージが 1 つ、公開済みアプリが 1 つ。</span><span class="sxs-lookup"><span data-stu-id="29ee3-107">On each release level we keep a single version: one workspace in WIP, one package, one published app.</span></span> <span data-ttu-id="29ee3-108">公開済みアプリを更新するには、パッケージを展開します。</span><span class="sxs-lookup"><span data-stu-id="29ee3-108">To make an update to a published app, you deploy a package.</span></span> <span data-ttu-id="29ee3-109">パッケージを展開すると、AppSource の公開済みアプリが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="29ee3-109">Deploying a package will overwrite the published app in AppSource.</span></span>
- <span data-ttu-id="29ee3-110">アプリの作成は、WIP ワークスペースでいつでも続行できます。</span><span class="sxs-lookup"><span data-stu-id="29ee3-110">Building the app can continue at all times on the WIP workspace.</span></span>
- <span data-ttu-id="29ee3-111">リリース候補を作成する準備ができたら、パッケージを保存します。</span><span class="sxs-lookup"><span data-stu-id="29ee3-111">Whenever you are ready to create a release candidate, save the package.</span></span>

