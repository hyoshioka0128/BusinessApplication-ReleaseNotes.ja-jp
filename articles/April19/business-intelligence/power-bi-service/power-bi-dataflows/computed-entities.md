---
title: 計算されたエンティティ
description: 計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます
author: adiregev
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: antonfrMSFT
ms.reviewer: mihart
ms.openlocfilehash: 180194f56086c3d1eab00f406686a99348b8fd8a
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210713"
---
# <a name="computed-entities"></a>計算されたエンティティ
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]


データフロー エンティティは、Azure Data Lake Storage Gen2 内の Common Data Model に準拠したフォルダー (CDM フォルダー) に格納されます。 エンティティが CDM フォルダーに読み込まれた後、エンティティを変換、変更、補強し、大規模なデータを集約することで、新しい分析情報を生成できます。 これらの新しく作成されたエンティティは、CDM フォルダーにも格納されます。 Power Query の M 式のスタティック分析により、エンティティ間の依存関係が自動的に識別され、常に最適な順序でエンティティが更新されるので、手動オーケストレーションの必要はありません。 

計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。 たとえば、Dynamics 365 for Sales の顧客アカウント エンティティを、Dynamics 365 for Service のオープン サービス チケットからの情報、および Office 365 の関連する顧客会議情報で補強できます 。

計算されたエンティティを最新の情報に更新するには、Power BI Premium が必要です。 
