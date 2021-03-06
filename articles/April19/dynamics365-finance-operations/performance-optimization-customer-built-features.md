---
title: 電子申告 - 顧客が構築した構成のパフォーマンスの最適化
description: 機能コンサルタントのペルソナは、頻繁に使用されるノードでキャッシュを設定することにより、電子申告の構成のパフォーマンスを最適化できます。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: c75b75f74dceb8eec20122c238f2de38ff605776
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225301"
---
#  <a name="electronic-reporting---performance-optimization-of-customer-built-configurations"></a>電子申告 - 顧客が構築した構成のパフォーマンスの最適化
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


機能コンサルタントのペルソナは、電子申告の構成の実行を追跡することができます。 このコンサルタントは、生成されたトレースを分析し、頻繁に使用されるノードでキャッシュを設定することにより、電子申告の構成のパフォーマンスを最適化することもできます。

![モデル マッピング デザイナー](media/ER-perf-model-mapping.png "モデル マッピング デザイナー")

現在、このキャッシュではレコードのフラット リストのみがサポートされているため、関連レコードはキャッシュされません。 この機能は入れ子になったレコードをキャッシュできます。 また、リスト全体ではなく、参照されているレコードのみがキャッシュされる場合、ユーザーは "遅延" キャッシュを有効にできます。

![モデル マッピング デザイナーのパフォーマンス統計](media/ER-perf-statistics.png "モデル マッピング デザイナーのパフォーマンス統計")
