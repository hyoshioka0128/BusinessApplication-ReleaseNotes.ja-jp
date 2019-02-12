---
title: パフォーマンスの向上
description: Dynamics 365 Layout の 2018 年 12 月のアップデートでのパフォーマンスの向上には、新しい Performance 設定と、シーンが複雑な場合にそれを示すバーが含まれています
author: ornellaalt
ms.author: ornella
ms.date: 12/05/2018
ms.topic: article
ms.service: business-applications
ms.reviewer: v-brycho
ms.openlocfilehash: 9a8e7f2126be879e8f39328eaf45cf9aa64602f3
ms.sourcegitcommit: 163b0e8ec8da8ef8bbe43f302c561bbaed43d0be
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2019
ms.locfileid: "290548"
---
# <a name="performance-improvements"></a>パフォーマンスの向上
2018 年 12 月 5 日に次のようなパフォーマンス向上を行いました。

## <a name="performance-setting"></a>パフォーマンス設定

多くのお客様から、特定のシナリオでは 3D アセットのビジュアル化にテクスチャや複数色は重要でないとお聞きしました。 それ以外の場合は、色やテクスチャを妥協できず、元の形式でアセットを表示できる必要があります。 テクスチャと複数色が重要でない場合にパフォーマンスを向上させるために、新しいパフォーマンス設定を追加しました。 設定をオンにすると、テクスチャが削除され、アセットが単一色で表示されます。 状況に応じて、設定をオンまたはオフに切り替えます。 

パフォーマンス モードをオンまたはオフにするには、**設定**に移動し、**パフォーマンス**を選択してから、**1 つの色だけを使用してオブジェクトを単純化する**オプションをオンまたはオフにします。 

![パフォーマンスモードの設定](media/performance-mode-setting.PNG "パフォーマンスモードの設定") 


## <a name="view-complexity-bar"></a>複雑度の表示バー
一部のお客様は、多くのアセットを 1 つのシーンに配置します。 より複雑なアセットがシーンに追加されると、各アセットが荷重を追加するためパフォーマンスが低下します。 現在のシーンの複雑度を判断するために、**複雑度の表示**バーを追加しました。

![複雑度のバー](media/complexity-bar.PNG "複雑度のバー") 

バーを使用して、複雑度が高すぎる場合はそれを把握し、トレードオフの判断をします。

 


