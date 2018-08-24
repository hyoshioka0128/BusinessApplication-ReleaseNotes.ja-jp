---
title: "計算されたエンティティ"
description: "計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。"
author: adiregev
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: adiregev
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 43b015ad18453b1bd9a9f9f60c79f23c3afa5bce
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="computed-entities-public-preview"></a>計算されたエンティティ (パブリック プレビュー)  

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



データフロー エンティティは、Azure Data Lake Storage Gen2 内の Common Data Model に準拠したフォルダー (CDM フォルダー) に格納されます。 エンティティが CDM フォルダーに読み込まれた後、エンティティを変換、変更、補強し、大規模なデータを集約することで、新しい分析情報を生成できます。 これらの新しく作成されたエンティティは、CDM フォルダーにも格納されます。 Power Query の M 式のスタティック分析により、エンティティ間の依存関係が自動的に識別され、常に最適な順序でエンティティが更新されるので、手動オーケストレーションの必要はありません。 

計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。 たとえば、Dynamics 365 for Sales の顧客アカウント エンティティを、サービスに対する Dynamics 365 のオープン サービス チケットからの情報、および Office 365 の関連する顧客会議情報で補強できます 。
計算されたエンティティを最新の情報に更新するには、Power BI Premium が必要です。 

