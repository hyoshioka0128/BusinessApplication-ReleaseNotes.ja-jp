---
title: "Azure SQL Database に対するシングル サインオン"
description: "Azure SQL Database に対するシングル サインオン"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4e774f63cd021959f0fe95f44598a2d937ada967
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a>Azure SQL Database に対する Power BI Embedded のシングル サインオン

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




この機能は、Power BI Embedded において、データ ソース レベルで構成されたセキュリティ設定を考慮できるようにするものです。 Power BI Embedded では、アプリケーションのユーザーは認識されません。 Azure SQL Database で行レベルのセキュリティを設定する必要があるアプリケーションでは、アプリケーションのユーザー情報を SQL Database に渡す必要があります。 シングル サインオン オプションを有効にした場合、Power BI Embedded は Azure SQL Database へのクエリ内でレポートにアクセスするユーザーについて、認証済みの Azure Active Directory 資格情報を送信します。 

