---
title: "倉庫管理での CW 製品処理"
description: "倉庫管理での CW 製品処理"
author: ShylaThompson
manager: AnnBe
ms.date: 09/24/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 4000f44f5648de2dcb2fa2f24e3409d6e031be1d
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="catch-weight-product-processing-with-warehouse-management"></a>倉庫管理での CW 製品処理

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

この機能は、CW 製品を倉庫管理プロセスの一部として使用するためのサポートを提供します。 CW 製品は、食品業界など、製品によって重量やサイズのいずれか、または両方が微妙に異なる業界でよく使用されます。 CW 製品では、在庫単位 (Kg) と CW 単位 (箱) の 2 つの単位が使用されます。 在庫単位は、製品の計量と請求に使用される測定単位です。 CW 単位は、入庫、輸送、出荷などでの製品の処理単位です。 

倉庫管理プロセスでは、CW 製品をパレットや箱などの異なる単位で処理することができ、ビジネス プロセスを細かく定義して、たとえばパレット レベルごとに入庫計量を実行したり、CW 数量 (箱) あたりのピッキングまたは梱包時に出荷営業プロセスを取り込んだりできます。 

別のオプションとして、CW 単位で重量を取得する CW タグを使用することもできます。 このアプローチの目的は、製品を受領時に 1 回のみ計量することです。 これは、冷凍エビなど、時間がたっても重量が変化せず、出荷可能な測定単位 (エビの箱など) がある製品に有効です。 このアプローチでは、ユーザーは CW タグをスキャンして、製品の構成に基づいてピッキングまたは梱包時に重量を識別し、取り込んだ CW タグに関連付けられている重量に基づいて請求できます。

