---
title: "Azure Active Directory アプリケーション認証のサポート"
description: "Azure Active Directory アプリケーション認証のサポート"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3c644df8af2bbc07c910cc7dd6581d55fc95686e
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="azure-active-directory-application-authentication-public-preview"></a>Azure Active Directory アプリケーション認証 (パブリック プレビュー) 

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




Power BI Embedded にアプリケーション認証が追加されます。 これにより、Power BI Embedded アプリケーションの展開、セキュリティ、およびアプリケーション ライフサイクル管理が強化されます。 現在、Power BI Embedded アプリケーションを作成するには、マスター ユーザー アカウントを作成し、そのアカウントの資格情報を保存した後、それらをアプリケーション コード内で使用して、Power BI への非対話型サインインを実行できるようにする必要があります。 Azure Active Directory では、ユーザー コンテキストを使用せず、アプリケーション自身の ID を使用するアプリケーション認証が特別にサポートされています。 アプリケーションのみの認証に対応して設計されたこのサポートは、制御性とセキュリティに優れ、制限事項も少ないため、推奨のアプローチとなっています。 

