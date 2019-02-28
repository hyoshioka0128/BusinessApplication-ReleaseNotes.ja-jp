---
title: 倉庫管理での CW 製品処理
description: CW 機能では、CW 製品を倉庫管理プロセスの一部として使用するためのサポートが提供されます。
author: sorenva
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: perlynne
ms.openlocfilehash: 4962e85b405b7aaf0c43741f2515e96e15b5b5e0
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210732"
---
#  <a name="catch-weight-product-processing-with-warehouse-management"></a>倉庫管理での CW 製品処理
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


この機能では、倉庫管理プロセス内で CW 製品を使用するためのサポートが提供されます。 CW 製品は、食品業界など、製品によって重量やサイズが異なる業界でよく使用されます。 CW 製品では、在庫単位 (Kg、lb、oz など) と CW 単位 (箱、1 つ、パレットなど) の 2 つの測定単位が使用されます。 在庫単位は、製品の計量と請求に使用される測定単位です。 CW 単位は、入庫、輸送、出荷などでの製品の処理単位です。 

> [!div class="mx-imgBorder"]
> ![現物手持在庫ページで在庫数量と一緒に表示されている CW 数量](media/catch-weight-1.png "現物手持在庫ページで在庫数量と一緒に表示されている CW 数量")

倉庫管理プロセスでは、CW 製品をパレットや箱などの異なる単位で処理することができ、ビジネス プロセスを細かく定義して、たとえばパレット レベルごとに入庫計量を実行したり、CW 数量 (箱) あたりのピッキングまたは梱包時に出荷営業プロセスを取り込んだりできます。

この機能では、割り当てられている CW 単位ごとにキャプチャされた重量を取得する CW タグを使用することもできます。 このアプローチの目的は、製品を受領時に 1 回のみ計量することです。 これは、時間がたっても重量が変化しない製品 (冷凍エビなど)、および出荷可能な材料取り扱い測定単位 (エビの箱など) がある製品に有効です。 

> [!div class="mx-imgBorder"]
> ![タグ重量のキャプチャ方法が示されているモバイル ウェアハウス アプリ](media/catch-weight-2.png "タグ重量のキャプチャ方法が示されているモバイル ウェアハウス アプリ")

このアプローチでは、ユーザーは CW タグをスキャンして、製品の構成に基づいてピッキングまたは梱包時に重量を識別し、取り込んだ CW タグに関連付けられている重量に基づいて請求できます。

> [!div class="mx-imgBorder"]
> ![CW 品目の取り扱いに関するポリシー ページで重量タグの追跡を有効にする](media/catch-weight-3.png "CW 品目の取り扱いに関するポリシー ページで重量タグの追跡を有効にする")

> [!div class="mx-imgBorder"]
> ![CW タグの登録ページに表示されている CW 登録](media/catch-weight-4.png "CW タグの登録ページに表示されている CW 登録")
