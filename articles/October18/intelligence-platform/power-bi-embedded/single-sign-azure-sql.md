---
title: "Azure SQL Database に対するシングル サインオン"
description: "Azure SQL Database に対するシングル サインオン"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4e774f63cd021959f0fe95f44598a2d937ada967
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a><span data-ttu-id="e4045-103">Azure SQL Database に対する Power BI Embedded のシングル サインオン</span><span class="sxs-lookup"><span data-stu-id="e4045-103">Power BI Embedded single sign-on for Azure SQL Database</span></span>


[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="e4045-104">この機能は、Power BI Embedded において、データ ソース レベルで構成されたセキュリティ設定を考慮できるようにするものです。</span><span class="sxs-lookup"><span data-stu-id="e4045-104">This enables Power BI Embedded to respect security settings that are configured at the data source level.</span></span> <span data-ttu-id="e4045-105">Power BI Embedded では、アプリケーションのユーザーは認識されません。</span><span class="sxs-lookup"><span data-stu-id="e4045-105">Power BI Embedded has no awareness of the application’s user.</span></span> <span data-ttu-id="e4045-106">Azure SQL Database で行レベルのセキュリティを設定する必要があるアプリケーションでは、アプリケーションのユーザー情報を SQL Database に渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="e4045-106">For applications that want to set row-level security in Azure SQL Database, there is a need to pass the application’s user information to SQL Database.</span></span> <span data-ttu-id="e4045-107">シングル サインオン オプションを有効にした場合、Power BI Embedded は Azure SQL Database へのクエリ内でレポートにアクセスするユーザーについて、認証済みの Azure Active Directory 資格情報を送信します。</span><span class="sxs-lookup"><span data-stu-id="e4045-107">By enabling the single sign-on option, Power BI Embedded sends authenticated Azure Active Directory credentials for users accessing reports in the queries to the Azure SQL Database.</span></span> 

