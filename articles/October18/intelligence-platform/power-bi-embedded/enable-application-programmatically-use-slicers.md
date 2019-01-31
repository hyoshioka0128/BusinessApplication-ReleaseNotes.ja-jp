---
title: アプリケーションがスライサーをプログラムで使用可能
description: スライサー API を使用すると、アプリケーションはセッション全体でユーザーが操作するスライサーを制御できます。
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 21ca0fd2-7676-4c50-af47-f6b7cbc7fe8a
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: f1a07b0c712e65870086749c584cfe5c97d12dbc
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199815"
---
#  <a name="enable-an-application-to-programmatically-use-slicers"></a><span data-ttu-id="a4bea-103">アプリケーションがスライサーをプログラムで使用可能</span><span class="sxs-lookup"><span data-stu-id="a4bea-103">Enable an application to programmatically use slicers</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="a4bea-104">スライサー API を使用すると、アプリケーションはセッション全体でユーザーが操作するスライサーを制御できます。</span><span class="sxs-lookup"><span data-stu-id="a4bea-104">The slicers API will give the application control, throughout the session, of the slicers the user interacts with.</span></span> <span data-ttu-id="a4bea-105">開発者はフィルター API と同じようにこの API を簡単かつ直感的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="a4bea-105">The API will be like the filters API so that it will be easy and intuitive for the developer.</span></span> <span data-ttu-id="a4bea-106">次の機能がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="a4bea-106">The supported capabilities are:</span></span>

-   <span data-ttu-id="a4bea-107">スライサーの値を取得します</span><span class="sxs-lookup"><span data-stu-id="a4bea-107">Get slicers value</span></span>
-   <span data-ttu-id="a4bea-108">読み込み時にスライサーの値を設定します</span><span class="sxs-lookup"><span data-stu-id="a4bea-108">Set slicers value on load</span></span>
-   <span data-ttu-id="a4bea-109">セッションの間にスライサーの値を設定します</span><span class="sxs-lookup"><span data-stu-id="a4bea-109">Set slicers value during the session</span></span>
-   <span data-ttu-id="a4bea-110">ユーザーが適用したスライサーの値を取得します</span><span class="sxs-lookup"><span data-stu-id="a4bea-110">Get the value of the user’s applied slicer</span></span>
