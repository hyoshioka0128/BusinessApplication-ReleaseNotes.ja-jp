---
title: "Dynamics 365 Portal でステータスに対して投票を有効にする"
description: "ポータルにおいて、さまざまなテータスに対する投票を有効にします。"
author: neerajnandwana-ms
manager: ramalingamkrishnan
ms.date: 09/20/2018
ms.assetid: D81BD65F-E1D6-42CF-BF48-667DFA8A2852
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: nenandw
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 4cc4cae09f6e22a6ec165d69a19c70777175b3ef
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---
# <a name="enable-voting-for-status-reasons"></a>ステータスに対して投票を有効にする

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

現在、アイデアに対して投票できるのは**ステータス**が**新規**に設定されている場合のみです。 この機能により、さまざまなステータスに対するアイデアの投票を有効にすることができます。 さまざまなステータスに対して投票を有効にするには、**Ideas/EnableVotingForStatusReasons** サイト設定を作成して、値を必要なステータス値に設定する必要があります。
 
たとえば、**新規**、**承諾済み**および**拒否済み**のステータスについて投票を有効にするとします。 サイト設定を作成し、値を次のように設定する必要があります。

- **名前**: Ideas/EnableVotingForStatusReasons

- **値**: 1;100000000;100000002

ステータス値の検証や取得手順については、「[ステータスに対して投票を有効にする](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/crowdsource-ideas#enable-voting-for-status-reasons)」で詳しい説明をご覧ください。

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

