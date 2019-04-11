---
title: 計算されたエンティティ
description: 計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます
author: adiregev
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: antonfrMSFT
ms.reviewer: mihart
ms.openlocfilehash: 01dd1fa2982791dac9620c5c8acf57a4d90b62cf
ms.sourcegitcommit: e9ae36f4f7ff145fcdc3d3ebfb2080fc33083f69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2019
ms.locfileid: "850319"
---
# <a name="computed-entities"></a>計算されたエンティティ
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]


データフロー エンティティは、Azure Data Lake Storage Gen2 内の Common Data Model に準拠したフォルダー (CDM フォルダー) に格納されます。 エンティティが CDM フォルダーに読み込まれた後、エンティティを変換、変更、補強し、大規模なデータを集約することで、新しい分析情報を生成できます。 これらの新しく作成されたエンティティは、CDM フォルダーにも格納されます。 Power Query の M 式のスタティック分析により、エンティティ間の依存関係が自動的に識別され、常に最適な順序でエンティティが更新されるので、手動オーケストレーションの必要はありません。 

計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。 たとえば、Dynamics 365 for Sales の顧客アカウント エンティティを、Dynamics 365 for Service のオープン サービス チケットからの情報、および Office 365 の関連する顧客会議情報で補強できます 。

計算されたエンティティを最新の情報に更新するには、Power BI Premium が必要です。 

[!include[feedback](../../includes/service-feedback.md)]