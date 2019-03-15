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
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "404755"
---
# <a name="visual-studio-code-and-al"></a>Visual Studio Code と AL
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]
2019 年 4 月リリースでは、ベース アプリケーションと国の変更を C/AL から AL に移行する準備、大規模プロジェクト (AL 上のベース アプリケーションなど) を操作するための最適化、および社内外の開発者からのフィードバックに対応した追加の生産性機能が重点的に強化されています。

## <a name="application-as-an-app"></a>アプリとしての申請
北米と EMEA での Directions 2018 カンファレンスで示されたように、Microsoft では、ベース アプリケーションとテストを C/AL から AL へ移行する取り組みを進めています。 これらは内部で並行して進められており、2019 年 4 月リリース以前か、同リリースの一部として、Docker イメージ上でのプレビュー モードで提供される予定です。 2019 年 4 月リリースは C/AL と C/SIDE をベースとしており、2018 年 10 月リリースから 12〜24 か月以内に、新リリースのサポート対象プラットフォームを AL および Visual Studio Code に切り替えるべく計画が進められています。 

![W1 アプリケーションを AL に変換](media/w1_app.png "W1 アプリケーションを AL に変換")

## <a name="supporting-larger-projects"></a>大規模プロジェクトのサポート
ベース アプリケーションを AL に変換するのと並行して、ベース アプリケーションなどの大規模プロジェクトを操作する際の開発者エクスペリエンスの最適化が重点的に進められています。 具体的には、以下のような点が改善されています。 

- コンパイラと IntelliSense によって使用される内部メタデータ リポジトリに対するパフォーマンス。
- 大規模プロジェクトでの読み込み時間、コンパイル時間、ビルド時間。
- 迅速なアプリケーション開発ラウンドトリップのための部分的なコンパイルおよび展開。

## <a name="force-sync-when-deploying-applications"></a>アプリケーション展開時の強制的な同期 
C/SIDE と同様に、新しい "強制" スキーマ同期を使用して、バージョンの更新やアップグレード コードの作成を行わずに、開発中に重大な変更を作成して展開できるようになりました。 このモードでは、加法的と破壊的両方のすべての変更が許可され、他のすべてのデータを破壊することなく、列の削除などの破壊的な変更が適用されます。

## <a name="outline-view"></a>アウトライン ビュー
Visual Studio Code の標準アウトライン ビューに対するサポートが追加されます。 これにより開発者は、現在アクティブなエディターのシンボル ツリーの概要を確認したり、コード エディター内の特定の場所に移動したりできるようになります。 さまざまな並べ替えモードがあるので、入力時にシンボルを検索したり、フィルター処理することができます。エラーや警告もアウトライン ビューに表示されるので、問題の場所をひとめで確認できます。 また、[ブレッドクラム] ビューを使用して、AL ファイル内の構造を簡単にナビゲートすることもできます。

![アウトライン ビュー](media/outline_view_search.png "顧客ページのシンボル ツリーが表示されたアウトライン ビューと、No の検索。")

## <a name="designer-no-longer-takes-dependencies-on-all-extensions"></a>デザイナーがすべての拡張機能に依存しなくなる
これまで、クライアント内デザイナーはインストールされているすべての拡張機能に依存していました。 この仕様が変更され、必要な拡張機能にのみ依存するようになります。これにより、コンサルタントや顧客がデザイナーで小規模な変更を加えた後に、それらを Visual Studio Code で編集する必要がなくなります。

## <a name="code-actions-support"></a>コード アクションのサポート
Visual Studio Code には、エラーをすばやく修正したり、リファクタリングを実行するための、コード アクションというフレームワークがあります。 Microsoft では、AL プロジェクトでのこのフレームワークのサポートを追加すると共に、一般的な問題に対するクイック修正もいくつかリリースする予定です。

![Code Actions](media/code_action.png "Code Actions でサポートされるエラーのクイック修正")

## <a name="multiple-objects-id-ranges-in-appjson"></a>app.json 内での複数のオブジェクト ID 範囲
今リリースでは、app.json ファイルに複数の ID 範囲を追加して、ID がそれらの範囲外である場合に、コンパイラから警告を発することが可能になります。
