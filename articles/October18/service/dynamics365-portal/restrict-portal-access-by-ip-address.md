---
title: "IP アドレスからポータルへのアクセスの制限"
description: "許可される IP 範囲を定義することで、ポータルのアクセスを一部のユーザーのみに制限します"
author: dileeps
manager: prvenka
ms.date: 07/22/2018
ms.assetid: 143d1e32-f70e-478c-b8c1-d25b37782653
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: dileeps
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 6e8406073dd7c7d202d8152877222da082d27bd6
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="restrict-portal-access-by-ip-address"></a><span data-ttu-id="0f9a0-103">IP アドレスからポータルへのアクセスの制限</span><span class="sxs-lookup"><span data-stu-id="0f9a0-103">Restrict portal access by IP address</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="0f9a0-104">セキュリティは、アプリケーションの重要な考慮事項であり、Dynamics 365 Portal などの外部に接続するアプリケーションにとってはより重要になります。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-104">Security is a key concern for applications and it becomes more paramount for an external-facing application like Dynamics 365 Portal.</span></span> <span data-ttu-id="0f9a0-105">このリリースの一部として、お客様がポータルへのアクセスを特定の IP アドレスからのアクセスに制限できる機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-105">As part of this release, we will add capabilities for customers to be able to restrict access to their portals from certain IP addresses.</span></span> <span data-ttu-id="0f9a0-106">これは、自社ポータルへのアクセスを社内ネットワークなどの固定の場所からのアクセスに制限しようとしている組織に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-106">This will help organizations that are looking to restrict their portals from fixed locations like internal company networks.</span></span> <span data-ttu-id="0f9a0-107">また、不正な構成が原因でデータがリークされることがないようにしたい、現在開発段階のお客様にも役立ちます。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-107">Also, this will help customers who are in a development phase and want to make sure their data doesn't get leaked because of a bad configuration.</span></span>

<span data-ttu-id="0f9a0-108">この機能は、ポータルへのアクセスを許可される IP アドレスの一覧を管理者が定義できるようにします。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-108">This feature would allow administrators to define a list of IP addresses that are allowed to access your portal.</span></span> <span data-ttu-id="0f9a0-109">許可リストには、個々の IP アドレスまたはサブネット マスクによって定義された IP アドレスの範囲を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-109">The allow list can include individual IP addresses or a range of IP addresses defined by a subnet mask.</span></span> <span data-ttu-id="0f9a0-110">ポータルに対する要求が任意のユーザーから生成されると、そのユーザーの IP アドレスが許可リストに照らして評価されます。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-110">When a request to the portal is generated from any user, their IP address is evaluated against the allow list.</span></span> <span data-ttu-id="0f9a0-111">IP アドレスがリストにない場合、ポータルは HTTP 403 状態コードで応答します。</span><span class="sxs-lookup"><span data-stu-id="0f9a0-111">If the IP address is not in the list, the portal replies with an HTTP 403 status code.</span></span>

<!--
### Who uses this feature
This feature is intended for administrators who are managing portals.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability 
Cloud
### Regional availability
Global
-->

