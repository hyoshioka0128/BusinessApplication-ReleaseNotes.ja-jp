---
title: 最適化された「次の値のいずれか」フィルタリング結果
description: 「次の値のいずれか」フィルター演算子が改善されました。 新しいエクスペリエンスでは、単一の入力フィールドからフィルター値を入力するときに、複数のフィルター値を入力するのに必要なキー ストロークが少なくなりました。
author: jasongre
manager: AnnBe
ms.date: 01/08/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: admin, end user, customizer, business analyst, IT pro
ms.openlocfilehash: ac2796ef69e07e682cd8c16d6121b036c85f8458
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288038"
---
# <a name="optimized-is-one-of-filtering-experience"></a>最適化された「次の値のいずれか」フィルタリング結果

フィルター ウィンドウおよびグリッド ヘッダーのドロップダウンリストを使用するとき、ほとんどのフィールドで「次の値のいずれか」フィルター演算子を使用できます。 この演算子を使用すると、複数の異なる値に基づいてフィールドをフィルター処理できます。 「次の値のいずれか」演算子の使いやすくなった新しいエクスペリエンスは、Platform Update 22 で利用できます。 改善点をよりよく理解するには、次の画像をご覧ください。

この画像では、Platform Update 22 より前の「次の値のいずれか」フィルタリング結果が示されています。

![Platform Update 22 より前の「次の値のいずれか」フィルタリング結果](media/isOneOfBefore.png "Platform Update 22 より前の「次の値のいずれか」フィルタリング結果")

*Platform Update 22 より前の「次の値のいずれか」フィルタリング結果*

次の画像では、Platform Update 22 での「次の値のいずれか」フィルタリング結果が示されています。

![Platform Update 22 での「次の値のいずれか」フィルタリング 結果](media/isOneOfAfter.png  "Platform Update 22 での「次の値のいずれか」フィルタリング結果")

*Platform Update 22 で最適化された「次の値のいずれか」フィルタリング結果*

最適化された「次の値のいずれか」フィルタリング結果には、以下の拡張機能が含まれます。

1.  **いっそう容易になった複数のフィルター値の入力**

    新しいエクスペリエンスでは、複数のフィルター値を入力するために必要なキー ストロークが少なくなっています。 1 つの入力フィールドからフィルター値を入力します。 値を設定すると (**Enter** キーを押すか、フィールドを離れるか、またはルックアップから値を選択することにより)、そのフィルター値は読み取り専用コントロールに移動されて、入力ボックスは次の値を入力できるようにクリアされます。 この方法では、入力する必要があるフィルター値ごとに**追加**ボタンをクリックして新しいフィールドに Tab で移動するより、はるかに速く操作できます。  

    さらに、複数の値をカンマで区切って入力フィールドに直接入力したり、[Excel からコピーしたリストを貼り付ける](paste-filter-lists-from-excel.md)こともできます。 

2.  **いっそうコンパクトで直感的になったフィルター値の表示**

    「次の値のいずれか」演算子のフィルター値の新しい視覚的表現は、いっそうコンパクトになり、角が丸くなっています。 これにより、フィルター ウィンドウで他のフィルターが表示される領域が広くなります。 

3.  **いっそう簡単になった個別または全部のフィルター値を削除するメカニズム**

    最適化された「次の値のいずれか」フィルタリング結果では、ワンクリックでフィルター値をクリアするメカニズムも提供されています。 各コントロールに含まれる**x**ボタンを使用すると、リストから単一のフィルター値を削除することができます。 また、**すべてクリア** ボタンを使用すると、そのフィールドのフィルター値のリストがクリアされます。  

## <a name="enabling-the-optimized-is-one-of-filtering-experience"></a>最適化された「次の値のいずれか」フィルタリング結果を有効にする 

Platform Update 22 では、最適化された「次の値のいずれか」フィルタリング結果は既定でオフになっていますが、システム管理者は環境でこの機能をオンにすることができます。 この機能を有効にするには、**システム管理**の**クライアント パフォーマンス オプション** ページにある、**最適化された「次の値のいずれか」フィルタリング結果**スイッチを使用します。   



