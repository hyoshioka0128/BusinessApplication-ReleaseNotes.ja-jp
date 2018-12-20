---
title: "Dynamics 365 ポータルでステータスに対して投票を有効にする"
description: "ポータルにおいて、さまざまなテータスに対する投票を有効にします。"
author: neerajnandwana-ms
manager: rycu
ms.date: 11/20/2018
ms.assetid: D81BD65F-E1D6-42CF-BF48-667DFA8A2852
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
ms.reviewer: shjais
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: e35bcf943f7257d057015b8535340025f4e76c30
ms.openlocfilehash: cb6ed3c1e66696517736f20b11c10a4c620cb24a
ms.contentlocale: ja-jp
ms.lasthandoff: 11/21/2018

---
# <a name="enable-voting-for-status-reasons"></a><span data-ttu-id="b1766-103">ステータスに対して投票を有効にする</span><span class="sxs-lookup"><span data-stu-id="b1766-103">Enable voting for status reasons</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

<span data-ttu-id="b1766-104">現在、アイデアに対して投票できるのは**ステータス**が**新規**に設定されている場合のみです。</span><span class="sxs-lookup"><span data-stu-id="b1766-104">Currently, an idea is enabled for voting only when the **Status Reason** is set to **New**.</span></span> <span data-ttu-id="b1766-105">この機能により、さまざまなステータスに対するアイデアの投票を有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="b1766-105">This feature allows you to enable the voting on an idea for different status reasons.</span></span> <span data-ttu-id="b1766-106">さまざまなステータスに対して投票を有効にするには、**Ideas/EnableVotingForStatusReasons** サイト設定を作成して、値を必要なステータス値に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b1766-106">To enable voting for different status reasons, you must create the **Ideas/EnableVotingForStatusReasons** site setting and set its value to the required status reason values.</span></span>
 
<span data-ttu-id="b1766-107">たとえば、**新規**、**承諾済み**および**拒否済み**のステータスについて投票を有効にするとします。</span><span class="sxs-lookup"><span data-stu-id="b1766-107">For example, if you want to enable voting for **New**, **Accepted**, and **Rejected** status reasons.</span></span> <span data-ttu-id="b1766-108">サイト設定を作成し、値を次のように設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b1766-108">You must create the site setting and set its value as:</span></span>

- <span data-ttu-id="b1766-109">**名前**: Ideas/EnableVotingForStatusReasons</span><span class="sxs-lookup"><span data-stu-id="b1766-109">**Name**: Ideas/EnableVotingForStatusReasons</span></span>

- <span data-ttu-id="b1766-110">**値**: 1;100000000;100000002</span><span class="sxs-lookup"><span data-stu-id="b1766-110">**Value**: 1;100000000;100000002</span></span>

## <a name="resources"></a><span data-ttu-id="b1766-111">リソース</span><span class="sxs-lookup"><span data-stu-id="b1766-111">Resources</span></span>

[<span data-ttu-id="b1766-112">ステータスに対して投票を有効にする</span><span class="sxs-lookup"><span data-stu-id="b1766-112">Enable voting for status reasons</span></span>](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)

<!--
### Who uses this feature
This feature is intended for customizers. A customizer can configure and decide the status reasons, where user can vote.
### License required
NA
### Setup required
No 
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
This feature will be available globally. 
-->

