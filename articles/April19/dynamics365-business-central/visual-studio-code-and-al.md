---
title: Visual Studio Code と AL
description: Visual Studio Code 開発者環境と AL の強化
author: pborring
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.author: pborring
audience: developer, admin, citizen developer, customizer
ms.openlocfilehash: f9d612c6593ad5e239859320a2ad66302f02c02f
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225325"
---
# <a name="visual-studio-code-and-al"></a><span data-ttu-id="5f414-103">Visual Studio Code と AL</span><span class="sxs-lookup"><span data-stu-id="5f414-103">Visual Studio Code and AL</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]
<span data-ttu-id="5f414-104">2019 年 4 月リリースでは、ベース アプリケーションと国の変更を C/AL から AL に移行する準備、大規模プロジェクト (AL 上のベース アプリケーションなど) を操作するための最適化、および社内外の開発者からのフィードバックに対応した追加の生産性機能が重点的に強化されています。</span><span class="sxs-lookup"><span data-stu-id="5f414-104">The April '19 release focuses on preparing to move the base application and country modifications from C/AL to AL, on optimizations for working with large projects (such as the base app on AL), as well as on additional productivity features addressing feedback from internal and external developers.</span></span>

## <a name="application-as-an-app"></a><span data-ttu-id="5f414-105">アプリとしての申請</span><span class="sxs-lookup"><span data-stu-id="5f414-105">Application as an app</span></span>
<span data-ttu-id="5f414-106">北米と EMEA での Directions 2018 カンファレンスで示されたように、Microsoft では、ベース アプリケーションとテストを C/AL から AL へ移行する取り組みを進めています。</span><span class="sxs-lookup"><span data-stu-id="5f414-106">As shown at the Directions 2018 conferences in North America and EMEA, we are working on moving the base application and tests from C/AL to AL.</span></span> <span data-ttu-id="5f414-107">これらは内部で並行して進められており、2019 年 4 月リリース以前か、同リリースの一部として、Docker イメージ上でのプレビュー モードで提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="5f414-107">We will be running these in parallel internally and are planning to ship these in preview mode on Docker images before or as part of the April '19 release.</span></span> <span data-ttu-id="5f414-108">2019 年 4 月リリースは C/AL と C/SIDE をベースとしており、2018 年 10 月リリースから 12〜24 か月以内に、新リリースのサポート対象プラットフォームを AL および Visual Studio Code に切り替えるべく計画が進められています。</span><span class="sxs-lookup"><span data-stu-id="5f414-108">The April '19 release is based on C/AL and C/SIDE, and plans are on track to switch to AL and Visual Studio Code as the supported platform for new releases within 12-24 months from our October '18 release.</span></span> 

<span data-ttu-id="5f414-109">![W1 アプリケーションを AL に変換](media/w1_app.png "W1 アプリケーションを AL に変換")</span><span class="sxs-lookup"><span data-stu-id="5f414-109">![W1 application converted to AL](media/w1_app.png "W1 application converted to AL")</span></span>

## <a name="supporting-larger-projects"></a><span data-ttu-id="5f414-110">大規模プロジェクトのサポート</span><span class="sxs-lookup"><span data-stu-id="5f414-110">Supporting larger projects</span></span>
<span data-ttu-id="5f414-111">ベース アプリケーションを AL に変換するのと並行して、ベース アプリケーションなどの大規模プロジェクトを操作する際の開発者エクスペリエンスの最適化が重点的に進められています。</span><span class="sxs-lookup"><span data-stu-id="5f414-111">In parallel to converting the base application to AL, we are focusing on optimizing the developer experience when working with large projects such as the base application.</span></span> <span data-ttu-id="5f414-112">具体的には、以下のような点が改善されています。</span><span class="sxs-lookup"><span data-stu-id="5f414-112">Some of the investments involve improving:</span></span> 

- <span data-ttu-id="5f414-113">コンパイラと IntelliSense によって使用される内部メタデータ リポジトリに対するパフォーマンス。</span><span class="sxs-lookup"><span data-stu-id="5f414-113">Performance on the internal metadata repository used by compiler and IntelliSense.</span></span>
- <span data-ttu-id="5f414-114">大規模プロジェクトでの読み込み時間、コンパイル時間、ビルド時間。</span><span class="sxs-lookup"><span data-stu-id="5f414-114">Load, compile, and build times for large projects.</span></span>
- <span data-ttu-id="5f414-115">迅速なアプリケーション開発ラウンドトリップのための部分的なコンパイルおよび展開。</span><span class="sxs-lookup"><span data-stu-id="5f414-115">Partial compile and deploy for rapid application development roundtrips.</span></span>

## <a name="force-sync-when-deploying-applications"></a><span data-ttu-id="5f414-116">アプリケーション展開時の強制的な同期</span><span class="sxs-lookup"><span data-stu-id="5f414-116">Force sync when deploying applications</span></span> 
<span data-ttu-id="5f414-117">C/SIDE と同様に、新しい "強制" スキーマ同期を使用して、バージョンの更新やアップグレード コードの作成を行わずに、開発中に重大な変更を作成して展開できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5f414-117">You can now create and deploy breaking changes during development without version update or creating upgrade code, by using the new "force" schema synchronization, similar to C/SIDE.</span></span> <span data-ttu-id="5f414-118">このモードでは、加法的と破壊的両方のすべての変更が許可され、他のすべてのデータを破壊することなく、列の削除などの破壊的な変更が適用されます。</span><span class="sxs-lookup"><span data-stu-id="5f414-118">This mode permits all changes, both additive and destructive, and applies destructive changes, such as dropping a column, without destroying all other data.</span></span>

## <a name="outline-view"></a><span data-ttu-id="5f414-119">アウトライン ビュー</span><span class="sxs-lookup"><span data-stu-id="5f414-119">Outline View</span></span>
<span data-ttu-id="5f414-120">Visual Studio Code の標準アウトライン ビューに対するサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="5f414-120">We are adding support for the standard Outline View in Visual Studio Code.</span></span> <span data-ttu-id="5f414-121">これにより開発者は、現在アクティブなエディターのシンボル ツリーの概要を確認したり、コード エディター内の特定の場所に移動したりできるようになります。</span><span class="sxs-lookup"><span data-stu-id="5f414-121">This allows developers to get an overview of the symbol tree of the currently active editor and navigate to locations in code editor.</span></span> <span data-ttu-id="5f414-122">さまざまな並べ替えモードがあるので、入力時にシンボルを検索したり、フィルター処理することができます。エラーや警告もアウトライン ビューに表示されるので、問題の場所をひとめで確認できます。</span><span class="sxs-lookup"><span data-stu-id="5f414-122">There are different sort-by modes—you can find or filter on symbols as you type, and errors and warnings are also shown in Outline View, letting you see a problem's location at a glance.</span></span> <span data-ttu-id="5f414-123">また、[ブレッドクラム] ビューを使用して、AL ファイル内の構造を簡単にナビゲートすることもできます。</span><span class="sxs-lookup"><span data-stu-id="5f414-123">You can also use the Breadcrumbs view to easily navigate the structure in an AL file.</span></span>

<span data-ttu-id="5f414-124">![アウトライン ビュー](media/outline_view_search.png "顧客ページのシンボル ツリーが表示されたアウトライン ビューと、No の検索。")</span><span class="sxs-lookup"><span data-stu-id="5f414-124">![Outline View](media/outline_view_search.png "Outline View with symbol tree for customer page, and search for No.")</span></span>

## <a name="designer-no-longer-takes-dependencies-on-all-extensions"></a><span data-ttu-id="5f414-125">デザイナーがすべての拡張機能に依存しなくなる</span><span class="sxs-lookup"><span data-stu-id="5f414-125">Designer no longer takes dependencies on all extensions</span></span>
<span data-ttu-id="5f414-126">これまで、クライアント内デザイナーはインストールされているすべての拡張機能に依存していました。</span><span class="sxs-lookup"><span data-stu-id="5f414-126">The In-Client Designer used to take dependencies on all the extensions installed.</span></span> <span data-ttu-id="5f414-127">この仕様が変更され、必要な拡張機能にのみ依存するようになります。これにより、コンサルタントや顧客がデザイナーで小規模な変更を加えた後に、それらを Visual Studio Code で編集する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="5f414-127">This is no longer the case—it only takes dependency on the extensions that are necessary, removing the need to edit these in Visual Studio Code after consultants or customers have used the Designer for small changes.</span></span>

## <a name="code-actions-support"></a><span data-ttu-id="5f414-128">コード アクションのサポート</span><span class="sxs-lookup"><span data-stu-id="5f414-128">Code Actions support</span></span>
<span data-ttu-id="5f414-129">Visual Studio Code には、エラーをすばやく修正したり、リファクタリングを実行するための、コード アクションというフレームワークがあります。</span><span class="sxs-lookup"><span data-stu-id="5f414-129">Visual Studio Code has a framework, Code Actions, for quickly fixing errors or performing refactoring.</span></span> <span data-ttu-id="5f414-130">Microsoft では、AL プロジェクトでのこのフレームワークのサポートを追加すると共に、一般的な問題に対するクイック修正もいくつかリリースする予定です。</span><span class="sxs-lookup"><span data-stu-id="5f414-130">We are adding support for this framework in AL projects, and will also be releasing some quick fixes for common problems.</span></span>

<span data-ttu-id="5f414-131">![Code Actions](media/code_action.png "Code Actions でサポートされるエラーのクイック修正")</span><span class="sxs-lookup"><span data-stu-id="5f414-131">![Code Actions](media/code_action.png "Code Actions supports quick fixes for errors")</span></span>

## <a name="multiple-objects-id-ranges-in-appjson"></a><span data-ttu-id="5f414-132">app.json 内での複数のオブジェクト ID 範囲</span><span class="sxs-lookup"><span data-stu-id="5f414-132">Multiple objects ID ranges in app.json</span></span>
<span data-ttu-id="5f414-133">今リリースでは、app.json ファイルに複数の ID 範囲を追加して、ID がそれらの範囲外である場合に、コンパイラから警告を発することが可能になります。</span><span class="sxs-lookup"><span data-stu-id="5f414-133">With this release, you can now add multiple ID ranges in the app.json file to have the compiler issue warnings if IDs are outside of those ranges.</span></span>
