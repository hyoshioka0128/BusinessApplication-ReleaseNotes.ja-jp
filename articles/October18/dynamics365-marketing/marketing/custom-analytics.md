---
title: "Marketing Insights アプリ"
description: "Marketing Insights は、マーケティング イニシアチブ全体で作成される多様なデータと通信を収集、管理、分析し、マーケティング担当者がキャンペーンの対象にしてより効率的に実行できるように関連するアクションを識別します。"
keywords: 
ms.date: 7/22/2018
ms.service:
- business-applications
ms.topic: article
ms.assetid: ed50382f-1d58-4c0c-b3fe-3b54b215f3a5
author: Annbe
ms.author: Annbe
manager: AnnBe
ms.translationtype: HT
ms.sourcegitcommit: 769d782f006d6c6a78719870a82e0904bc426d61
ms.openlocfilehash: c197abf5df4cb7e1d4eacaef0e003b2f05dc2a66
ms.contentlocale: ja-jp
ms.lasthandoff: 09/11/2018

---

# <a name="custom-analytics"></a>カスタム分析

[!include[marketing banner](../../includes/marketing.md)]

Dynamics 365 for Marketing は、取引先担当者がマーケティング イニシアチブとやり取りする方法についての広範で詳細な情報を収集します。 カスタム分析を使用して、Marketing アプリ内でこのデータを編成および提示します。

カスタム分析は、Marketing および他のビジネス アプリケーションからのデータに基づいて、アクション可能な分析情報を提供するのに役立ちます。 ビジネス プロセスに合わせて調整されたレポートを表示し、それを使用してさらに効果的かつ効率的にキャンペーンを実行する方法を明らかにします。 将来的には、機械学習に基づく分析情報も提供し、ビジネス データ、取得されたデータ、Microsoft 固有のデータ セットから、より多くのことを得られるようにします。

Dynamics 365 for Marketing を使用して、組織固有のビジネス プロセスをサポートし、適切な意志決定を促進し、結果を提供するカスタム分析を作成します。 マーケティング担当者が最も必要とするアプリに埋め込むことができるチャート、グラフ、KPI を設計します。

## <a name="setup-required"></a>必要なセットアップ

- この機能を使用するには、自分の Azure Blob Storage を持ち込む必要があります。 Marketing アプリは、このリソースに接続して、そこにマーケティング データを保存できる必要があります。
- Power BI データフロー コネクタを使用して、このデータ ストア上に Power BI レポートを構築できます。 この機能はまだプレビュー段階です。 詳細: [データフローでのセルフサービス データの準備 (パブリック プレビュー)](https://docs.microsoft.com/en-us/business-applications-release-notes/october18/intelligence-platform/power-bi-service/self-service-data-prep-with-dataflows)
- または、Azure Blob Storage に格納されているマーケティング データに対するカスタム マッピングを利用して、Power BI レポートを作成することもできます。

## <a name="status"></a>状態

パブリック プレビュー

