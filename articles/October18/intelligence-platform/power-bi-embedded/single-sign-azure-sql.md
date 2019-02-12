---
title: Azure SQL Database に対するシングル サインオン
description: Azure SQL Database に対するシングル サインオン
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 36e6a56293de8aa7e11ba18e1114ca55830368df
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199128"
---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a>Azure SQL Database に対する Power BI Embedded のシングル サインオン

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




この機能は、Power BI Embedded において、データ ソース レベルで構成されたセキュリティ設定を考慮できるようにするものです。 Power BI Embedded では、アプリケーションのユーザーは認識されません。 Azure SQL Database で行レベルのセキュリティを設定する必要があるアプリケーションでは、アプリケーションのユーザー情報を SQL Database に渡す必要があります。 シングル サインオン オプションを有効にした場合、Power BI Embedded は Azure SQL Database へのクエリ内でレポートにアクセスするユーザーについて、認証済みの Azure Active Directory 資格情報を送信します。 
