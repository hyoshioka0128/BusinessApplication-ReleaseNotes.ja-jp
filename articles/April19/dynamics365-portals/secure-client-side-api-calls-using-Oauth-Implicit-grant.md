---
title: ポータルでの外部データの表示
description: ポータルでの外部データの表示
author: dileepsinghmicrosoft
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dileeps
ms.reviewer: shjais
ms.openlocfilehash: 7e5266e9c93a46336b29788e788797b05f5d077c
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225308"
---
#  <a name="displaying-external-data-in-portals"></a><span data-ttu-id="2a76d-103">ポータルでの外部データの表示</span><span class="sxs-lookup"><span data-stu-id="2a76d-103">Displaying external data in portals</span></span>
[!include[dynamics365-portals banner](../includes/dynamics365-portals.md)]


## <a name="business-value"></a><span data-ttu-id="2a76d-104">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2a76d-104">Business value</span></span>

<span data-ttu-id="2a76d-105">外部アプリケーションからデータを取得し、それらを安全な方法でポータルに表示できるようにする機能は、ポータルのお客様から多く寄せられていたニーズの 1 つです。</span><span class="sxs-lookup"><span data-stu-id="2a76d-105">One of the recurring themes for portal customers is to be able to get data from external applications and display it in portals in a secure manner.</span></span> <span data-ttu-id="2a76d-106">この機能を使用すると、お客様はクライアント側から外部 API を呼び出し、OAuth Implicit Grant Type フローを使用して、それらを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="2a76d-106">This feature will allow customers to make client-side calls to external APIs and secure them by using OAuth Implicit Grant Type flow.</span></span>

## <a name="personas"></a><span data-ttu-id="2a76d-107">ペルソナ</span><span class="sxs-lookup"><span data-stu-id="2a76d-107">Personas</span></span>

- <span data-ttu-id="2a76d-108">ポータル管理者</span><span class="sxs-lookup"><span data-stu-id="2a76d-108">Portal administrators</span></span>
- <span data-ttu-id="2a76d-109">ポータルのカスタマイズ担当者</span><span class="sxs-lookup"><span data-stu-id="2a76d-109">Portal customizers</span></span>

## <a name="features"></a><span data-ttu-id="2a76d-110">機能</span><span class="sxs-lookup"><span data-stu-id="2a76d-110">Features</span></span>

<span data-ttu-id="2a76d-111">この機能では、安全なアクセストークンを取得するためのエンドポイントが提供されます。これらのアクセス トークンに格納されるユーザー ID 情報は、外部 API によって、OAuth Implicit Grant Type フローに従った認証に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2a76d-111">This feature will provide an endpoint to obtain secure access tokens that will contain user identity information that external APIs can use for authorization following OAuth Implicit Grant Type flow.</span></span>
