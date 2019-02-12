---
title: Dynamics 365 Portal でステータスに対して投票を有効にする
description: ポータルで、さまざまなステータスに対して投票を有効にします。
author: neerajnandwana-ms
manager: rycu
ms.date: 11/20/2018
ms.assetid: D81BD65F-E1D6-42CF-BF48-667DFA8A2852
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: nenandw
ms.reviewer: shjais
audience: Admin
ms.openlocfilehash: cb6ed3c1e66696517736f20b11c10a4c620cb24a
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199551"
---
# <a name="enable-voting-for-status-reasons"></a>ステータスに対して投票を有効にする

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

現在、アイデアに対して投票できるのは**ステータス**が**新規**に設定されている場合のみです。 この機能により、さまざまなステータスに対するアイデアの投票を有効にすることができます。 さまざまなステータスに対して投票を有効にするには、**Ideas/EnableVotingForStatusReasons** サイト設定を作成して、値を必要なステータス値に設定する必要があります。
 
たとえば、**新規**、**承諾済み**および**拒否済み**のステータスについて投票を有効にするとします。 サイト設定を作成し、値を次のように設定する必要があります。

- **名前**: Ideas/EnableVotingForStatusReasons

- **値**: 1;100000000;100000002

## <a name="resources"></a>リソース

[ステータスに対して投票を有効にする](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)

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
