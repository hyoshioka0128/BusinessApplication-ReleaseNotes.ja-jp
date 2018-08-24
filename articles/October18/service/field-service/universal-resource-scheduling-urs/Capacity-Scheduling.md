---
title: "キャパシティのスケジューリング"
description: "キャパシティのスケジューリング"
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 877d8d044a57d95cf8be26d3d9c883aca2dee3f5
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---




#  <a name="capacity-scheduling"></a>キャパシティのスケジューリング

[!include[field-service banner](../../../includes/field-service.md)]



リソース要件では、要件でリソースに要求される作業量を指定できるようになります。 スケジュールのとき、スケジュール アシスタントはリソースに定義されている作業時間キャパシティを調べて、必要な作業量を確保できるかどうかを確認します。 リソースのキャパシティは 1 日のうちでも変換することがあります。

キャパシティ スケジューリングは、設備を予約するときに特に役立ちます。 たとえば、バンでは標準的な自動車の 2 倍のスペースが必要になる場合があります。 特定のキャパシティの設備を作成できますが、バンで作業時間を予約するときは、2 台の自動車または 6 台のオートバイを登録する場合と同じ設備キャパシティが消費されます。

スケジュール ボードでは、特定の時間にリソースが予約されていてもリソースに追加キャパシティがあるときのビジュアル インジケーターも提供されます。

* サンプル使用事例
    * リソースが指定されていないときのスタッフの増強。
    * 効率的なリソース。
        * 標準的なユーザーが 1 台のバイクを手配できるときに、ユーザーは 2 台のバイクを手配できます。
    * 物理的な空間。
        * 1 つのワークスペースが 2 台の自動車または 1 台のバンを手配できます。
        * リソースとして「クラス」を作成し、最大 10 人の顧客をクラスに予約できます。
> オンサイト作業を実行するリソースは、複数のキャパシティを持つことはできません。

> [!div class="mx-imgBorder"]
> ![](media/Additional-Capacity.png "追加キャパシティ")
<!-- picture -->

*追加容量行が展開されたリソースを示すスケジュール ボード*

