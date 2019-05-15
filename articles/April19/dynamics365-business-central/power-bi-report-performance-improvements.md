---
title: Power BI レポートのパフォーマンスの向上
description: Power BI レポートの使用が、ページ読み込みのパフォーマンスが向上するように最適化されました。
author: KennieNP
ms.reviewer: edupont
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 2b75b496cdaf3d731161d587356167350a5f1422
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225044"
---
# <a name="power-bi-report-performance-improvements"></a>Power BI レポートのパフォーマンスの向上

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Power BI レポートの使用が、ページ読み込みのパフォーマンスが向上するように最適化されました。 2019 年 4 月のリリースでは、Power BI レポートは要求を分散するために遅延読み込みされます。 レポートが展開された後、ユーザーが初めて既定のページにアクセスしたときにのみ最初の更新が行われます。 2018 年 10 月のリリースで導入されたリスト ページ レポートの自動展開は、大きいデータ セットの場合にレポートで要求されるリソースが多すぎたため、削除されました。 ロール センターのレポートが最適化され、財務データは Account Schedule KPI にキャッシュされるようになりました。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
