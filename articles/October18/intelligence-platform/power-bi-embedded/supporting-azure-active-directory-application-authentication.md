---
title: Azure Active Directory アプリケーション認証のサポート
description: Azure Active Directory アプリケーション認証のサポート
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 4346342cb55725fb42d473f1f89085c5d48658bc
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199714"
---
# <a name="azure-active-directory-application-authentication-public-preview"></a>Azure Active Directory アプリケーション認証 (パブリック プレビュー) 

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




Power BI Embedded にアプリケーション認証が追加されます。 これにより、Power BI Embedded アプリケーションの展開、セキュリティ、およびアプリケーション ライフサイクル管理が強化されます。 現在、Power BI Embedded アプリケーションを作成するには、マスター ユーザー アカウントを作成し、そのアカウントの資格情報を保存した後、それらをアプリケーション コード内で使用して、Power BI への非対話型サインインを実行できるようにする必要があります。 Azure Active Directory では、ユーザー コンテキストを使用せず、アプリケーション自身の ID を使用するアプリケーション認証が特別にサポートされています。 アプリケーションのみの認証に対応して設計されたこのサポートは、制御性とセキュリティに優れ、制限事項も少ないため、推奨のアプローチとなっています。 
