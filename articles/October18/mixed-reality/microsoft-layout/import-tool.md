---
title: インポート ツールの改善
description: 2019 年 1 月の更新プログラムでの Dynamics 365 インポート ツール (プレビュー) の改善。
author: ornellaalt
ms.date: 01/16/2019
ms.topic: article
ms.service: business-applications
ms.author: ornella
ms.reviewer: v-brycho
ms.openlocfilehash: b31cdcfd5674f88fb9bafcef260f7a545fb7b0e6
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288232"
---
# <a name="import-tool-improvements"></a>インポート ツールの改善

インポート ツールに対する 2019 年 1 月の更新プログラムでは、3D モデルのインポートを容易にするいくつかの改善が行われています。

## <a name="improved-control-with-microsoft-cloud-service"></a>Microsoft クラウド サービスによる制御の改善

Microsoft クラウド サービスを使用するときに、資産最適化プロセスをより細かく制御できるようになりました。 通常は 1 つのシーンに配置されるいくつかのモデルと共に、モデルのターゲット デバイスを指定できます。 インポート ツールでは、目的の使用シナリオに適したモデルが生成されます。

![クラウド サービス オプション](media/cloud-service-option.PNG "クラウド サービス オプション")

## <a name="iterative-optimization-with-microsoft-cloud-service"></a>Microsoft クラウド サービスによる反復的な最適化

既定では、インポート ツールは指定された使用シナリオとの互換性が非常に高いモデルを生成します。 ただし、Microsoft クラウド サービス オプションを使用する場合は、パフォーマンスまたは品質の観点からモデルを繰り返し再最適化することを選択できます。 パフォーマンスを最適化すると、HoloLens または Windows Mixed Reality ヘッドセットでのモデルのパフォーマンスが向上します。 品質を最適化すると、視覚的な品質は向上しますが、HoloLens または Windows Mixed Reality ヘッドセットではうまくレンダリングされない可能性のあるモデルが生成されます。

![3D モデルの再最適化](media/reoptimize-slider.PNG "3D モデルの再最適化")

## <a name="make-your-models-compatible-without-optimizing-them"></a>モデルを最適化せずに互換性を持たせる

現在は、モデルを最適化しなくても、Microsoft クラウド サービスを使用してモデルを HoloLens または Windows Mixed Reality ヘッドセットと互換にすることができます。 これを行うには、[最適化なしで変換] オプションを選択します。 

![最適化なしで変換オプション](media/convert-without-optimizing.PNG "最適化なしで変換オプション")

最適化なしでの変換がサポートされているソース ファイルの種類には、FBX、OBJ、SKP、JT、STP、STEP、GLTF があります。

## <a name="change-the-background-of-a-model-to-make-it-easier-to-view"></a>見やすくするためにモデルの背景を変更する

インポートしたモデルを表示するときに、明るい背景と暗い背景を切り替えられるようになりました。

![暗い背景](media/dark-background.PNG "暗い背景")
![明るい背景](media/light-background.PNG "明るい背景")

## <a name="provide-feedback-for-each-imported-model"></a>インポートされた各モデルにフィードバックを提供する

**プロパティ** ウィンドウの**良好**または**不良**ボタンを選択して、インポートされたモデルの品質に関するフィードバックを提供できます。

![フィードバック](media/feedback.PNG "フィードバック")

モデルの品質を 3 以下と評価した場合は、追加コストなしで手動処理するためにモデルを Microsoft に送信するように求められます (オプション)。 Microsoft によるモデル最適化の後、それをインポート ツールでダウンロードし、レイアウト アプリケーションで使用できます。

インポート ツールを使用した資産のインポートについて詳しくは、「[Dynamics 365 Layout ユーザー ガイド](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/layout/user-guide)」をご覧ください。 



