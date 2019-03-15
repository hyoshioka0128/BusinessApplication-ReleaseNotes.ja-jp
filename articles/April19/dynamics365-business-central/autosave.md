---
title: 自動保存インジケーター
description: 変更は自動的に保存されます。
author: kotelko
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: blazkote
audience: end user
ms.openlocfilehash: 98c9eee8e7968f7414b700b325c5fb7d7e5f1865
ms.sourcegitcommit: 163b0e8ec8da8ef8bbe43f302c561bbaed43d0be
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2019
ms.locfileid: "290571"
---
# <a name="autosave-indicator"></a>自動保存インジケーター
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Business Central の現在のお客様および Dynamics NAV のお客様は、これらの製品に共通する自動保存の概念をよくご存じでしょう。 これは非常に好まれ歓迎されている機能ですが、他の ERP システムから移行してきた多くのお客様からは、保存機能を明示的に使用しなくても、データが Business Central に保存されてセキュリティで保護されていることを知らないという声をよく聞きます。 データが保存されていることを示すスマートな自動保存インジケーターを作成したのは、これらのお客様のためです。  

## <a name="business-value"></a>ビジネス バリュー
この新しい要素では、バックグラウンドで保存されているカードまたはドキュメントのデータの状態が直接示され、入力された情報がセキュリティで保護されていることが明確に示されます。 

## <a name="autosave-indicator-appearance"></a>自動保存インジケーターの外観   
インジケーターは画面上のカードの右側に表示され、コンピューターがサーバーと通信してデータを保存していると値が変化します。 インジケーターは、現在の状態に応じて**保存中**または**保存済**を表示できます。 データ検証エラーが発生した場合は、**未保存**も表示されます。 動作中のインジケーターの例を以下に示します。

![Business Central の新しい自動保存インジケーター](media/autosave.png "自動保存インジケーター") 


## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
