---
title: "高度なフィルター"
description: "強力なフィルター機能によりデスクトップでの生産性が向上します。"
author: mikebcMSFT
manager: edupont04
ms.date: 09/23/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
<<<<<<< HEAD
ms.sourcegitcommit: 8b8612bb36ad0e7abd0c55439652b9015c944035
ms.openlocfilehash: 8c2bc84d8e3e8291d5cc07b49e7ae853a5cb5df3
ms.contentlocale: ja-jp
ms.lasthandoff: 09/24/2018
=======
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 8c2bc84d8e3e8291d5cc07b49e7ae853a5cb5df3
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018
>>>>>>> 87e028547d07f7115112632b834c7e86c5555bb3

---
# <a name="advanced-filtering"></a>高度なフィルター

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]



計算を制御し、複数のフィールドにフィルターを適用することにより、Dynamics 365 Business Central のリストでの作業を効率化できます。

バックオフィスのインフォメーション ワーカーは、データの入力や変更、傾向や異常の分析、特定のレコードの単純な検索など、リストに関する作業に多くの時間を費やします。 簡易検索ではすべての列で最も近い一致を検索することによりリストを縮小できますが、ビジネス データベースのサイズが大きくなるとユーザーはさらに高度な制御を必要とすることがよくあります。 Business Central の強力なフィルター機能は、最新の直感的なエクスペリエンスによりフィルター処理の完全な制御を提供することで、リスト関連のタスクにかかる時間を短縮します。

## <a name="filtering-lists"></a>リストのフィルター処理
リストの横に固定された新しいフィルター ウィンドウは、わかりやすく、効率よく作業できる使い慣れたデザインになっています。 リストのあらかじめ定義されたフィルター ビューを切り替え、独自のフィルターを追加してビューを調整し、何もない状態からでも簡単に始めることができます。

> [!div class="mx-imgBorder"]
> ![alt text](media/list-page-with-advanced-filter.png "リストの横に表示されているフィルター ウィンドウ。")

フィルター ウィンドウでは次のことができます。

-   自分、フィルター ビュー、またはアプリケーション自体のいずれによって設定されたかに関わらず、現在適用されているフィルターの概要を取得します。
-   入力してソース テーブルの任意のフィールドからすばやく選択することにより、フィルター処理された列を好きなだけ追加します。
-   ルックアップまたはフィールドのデータ型を使用してフィルター値指定のサポートを利用します。
-   演算子、範囲、数式、%MyCustomers などの新しいフィルター トークンを使用して、複雑なフィルターを作成します。
-   フィルターの変更を、リストのフィルターされていないビューまたは事前定義されたビューに戻します。

Business Central は、ユーザーがページ間をあちこち移動しても、セッションを通してユーザーが適用したフィルターを憶えています。 変更をフィルター ビューとして永続的に保存する機能は後日提供されます。

フィルター ウィンドウは、リストがワークシートなどの主要コンテンツを表すすべてのページで使用できます。 リスト パーツとして埋め込まれたリストは、引き続き簡単なフィルタリングを使用しており、フィルター ウィンドウは後日採用されます。

## <a name="filtering-totals"></a>合計のフィルター処理
Dynamics NAV の最も好評な機能の 1 つが、Business Central に組み込まれるようになります。 リストでは、合計金額など、集計値や計算値が FlowField で表示されることがよくあります。 このリリースの Business Central で提供されているまったく新しいレベルの制御機能を利用すると、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。 これをフィルター、並べ替え、検索と組み合わせて使用し、データを探索および分析します。

## <a name="keyboard-shortcuts"></a>キーボード ショートカット
フィルター ウィンドウはワン クリックで利用できますが、多彩で強力なキーボード ショートカットを使用して、マウスを使わずに作業することもできます。たとえば、Alt + F3 ショートカットは現在の値でフィルターを適用します。 リストを離れることなくオンザフライで複合フィルターを作成でき、ショートカットを使用してセル間を移動し、現在フォーカスがある値にフィルターを適用したり、現在の列のフィルターをクリアしたりできます。 すべてのキーボード ショートカットの一覧については、https://aka.ms/bckeys を参照してください。

<!--
### Who uses these features
These features are available to all desktop users without additional setup, in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available in all Dynamics 365 Business Central supported markets.
-->

## <a name="try-it-now"></a>試してみましょう
https://businesscentral.dynamics.com/?page=31 でオンライン環境にサインインし、**Shift + F3** キーを押してフィルター ウィンドウを表示して、品目リストで新しいフィルター ウィンドウをお試しください。

## <a name="resources"></a>リソース
[リストの並べ替え、検索、およびフィルター処理](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-enter-criteria-filters)

[カレンダーの日付と時刻の操作](https://docs.microsoft.com/en-US/dynamics365/business-central/ui-enter-date-ranges)

[技術文書: フィルター トークンの追加](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-adding-filter-tokens)

[検索とフィルター処理に関するよくある質問](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-search-filter-faq)

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。

