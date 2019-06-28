---
title: Dynamics 365 Product Visualize で SharePoint 統合を使用して 3D コンテンツをインポートする
description: Dynamics 365 Product Visualize で SharePoint 統合を使用して 3D コンテンツを Dynamics 365 for Sales の営業案件にインポートします。
author: Mamithan
ms.date: 05/15/2019
ms.topic: article
ms.service: business-applications
ms.author: mamithan
ms.reviewer: v-brycho
ms.openlocfilehash: 980e1d87b4507812935e9f22c2868c6b5675ba89
ms.sourcegitcommit: cf4dbc9865a44606bbf9346d74fe8c4a3fc9a3b5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/16/2019
ms.locfileid: "1578977"
---
# <a name="sharepoint-integration"></a><span data-ttu-id="d2dbd-103">SharePoint 統合</span><span class="sxs-lookup"><span data-stu-id="d2dbd-103">SharePoint integration</span></span>

<span data-ttu-id="d2dbd-104">一部のユーザーや組織は、3D コンテンツを SharePoint に格納することがあります。</span><span class="sxs-lookup"><span data-stu-id="d2dbd-104">Some users and organizations may store 3D content in SharePoint.</span></span> <span data-ttu-id="d2dbd-105">ユーザーは、Dynamics 365 for Sales へのアクセスに使用されるのと同じ Azure Active Directory 資格情報を使用して、自分に関連付けられている SharePoint サイトにアクセスして 3D コンテンツを Microsoft Dynamics 365 Product Visualize にインポートできます。</span><span class="sxs-lookup"><span data-stu-id="d2dbd-105">By using the same Azure Active Directory credentials used to access Dynamics 365 for Sales, users have the ability to access their associated SharePoint sites to import 3D content into Microsoft Dynamics 365 Product Visualize.</span></span>  

> [!NOTE]
> <span data-ttu-id="d2dbd-106">3D モデルとそのモデルでキャプチャされた関連メモは、モデルのインポート元の SharePoint サイトではなく関連付けられた Dynamics 365 for Sales 製品および営業案件に保存されます。</span><span class="sxs-lookup"><span data-stu-id="d2dbd-106">The 3D model and associated notes captured on that model will be saved to the associated Dynamics 365 for Sales product and opportunity, not the SharePoint site from which the model was imported.</span></span>  
