---
title: ユーザー セッションを最後の状態に回復する機能
description: このトピックでは、サービスが一時的に利用できなくなった場合に、(Web クライアントを介して) ユーザー セッションを最後の状態に回復する機能を紹介します。
author: hasaid
manager: AnnBe
ms.date: 01/25/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: hasaid
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.openlocfilehash: 99d64fd92b934d61f079619865f5622ef493d5b7
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225234"
---
#  <a name="ability-to-recover-a-user-session-to-its-last-state"></a><span data-ttu-id="fb4ce-103">ユーザー セッションを最後の状態に回復する機能</span><span class="sxs-lookup"><span data-stu-id="fb4ce-103">Ability to recover a user session to its last state</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="fb4ce-104">ビジネスをサポートする Web アプリケーションのユーザー エクスペリエンスに対する顧客の期待はますます高まっています。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-104">Customers have ever-increasing expectations of their user experience in the web applications that support their business.</span></span> <span data-ttu-id="fb4ce-105">そのため、Dynamics 365 for Finance and Operations ではエンドユーザー エクスペリエンスの向上に継続的に投資しています。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-105">To this end, Dynamics 365 for Finance and Operations is committed to continued investment in improvements to the end-user experience.</span></span> 

<span data-ttu-id="fb4ce-106">サービスが一時的に利用できなくなった場合に、(Web クライアントを介して) ユーザー セッションを最後の状態に回復する機能を導入しています。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-106">We are introducing the ability for a user session (through the web client) to recover to its last state, in the event that the service becomes temporarily unavailable.</span></span> <span data-ttu-id="fb4ce-107">現在、ユーザーが同じセッション内でシステムと対話しようとすると、エラーがポップアップ表示されます。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-107">Currently, if a user tries to interact with the system within the same session, an error will pop up.</span></span> <span data-ttu-id="fb4ce-108">ユーザーによって閉じられると、ページが最新の情報に更新されます。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-108">Once closed by the user, the page will be refreshed.</span></span>

<span data-ttu-id="fb4ce-109">新機能を使用すると、ユーザー セッションはサービスの一時的な利用不可からスムーズに回復し、この回復はユーザーにとってシームレスになります。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-109">With the new feature, the user session will smoothly recover from temporary unavailability of the service, and this recovery will be seamless to the user.</span></span>

> [!Note]
> <span data-ttu-id="fb4ce-110">この機能は、一般提供される前に、まず特定の顧客グループにロール アウトされます。</span><span class="sxs-lookup"><span data-stu-id="fb4ce-110">This feature will be rolled out first to a select group of customers before it becomes generally available.</span></span>


