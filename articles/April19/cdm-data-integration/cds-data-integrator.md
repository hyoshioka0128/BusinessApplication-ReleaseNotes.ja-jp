---
title: CDS データ インテグレーター
description: CDS データ インテグレーター
author: sabinn-msft
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: 94adbd951ef056c507ac78357440f69436d32a15
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210571"
---
# <a name="cds-data-integrator"></a>CDS データ インテグレーター
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]



CDS データ インテグレーター (管理者用) は、データを Common Data Service (CDS) for Apps に統合するために使用されるポイント ツー ポイント統合サービスです。 複数のソースから Common Data Service for Apps へのデータの統合がサポートされています。 Dynamics 365 for Finance and Operations と Dynamics 365 for Sales の間の直接同期を提供する見込顧客を現金化のようなプロセス ベースの統合シナリオをサポートしています。 データ統合で使用できる見込顧客を現金化テンプレートを使用すると、Finance and Operations と Sales の間で、取引先企業、取引先担当者、製品、販売見積、販売注文、および売上請求書のデータをフローできます。 2019 年 4 月リリースでは以下の投資を行うことにより、顧客の使用とフィードバックに基づいてこのサービスの強化を続けます。

## <a name="sdk-for-data-integrator"></a>データ インテグレーター用の SDK

開発者がデータ統合プロジェクトをユーザーの操作なしにプログラムで作成、更新、およびスケジュールできるように、CDS データ インテグレーター SDK を提供しています。

## <a name="enhancements-in-project-management-error-handling-and-troubleshooting"></a>プロジェクト管理、エラー処理、トラブルシューティングの機能強化

これらの機能により、顧客は統合元と統合先のエラー ログへのポインターを使用して、統合の問題をより的確に把握できます。 また、フィールド マッピングのカスタマイズ中に必須フィールドが確実にマップされるよう、早期警告も提供します。 また、プロジェクト間のアクティブなエラーのリストを表示し、失敗したレコードを再試行できるようにします。

さらに、データ統合プロジェクトでは、1 つのプロジェクト内で複数の法人または企業をサポートするようになりました。 これは、多数の法人を抱えるエンタープライズの顧客にとって特に有益です。
以前は、テンプレートを更新するときに、古いテンプレートを使用しているプロジェクトを手動で更新する必要がありました。 この機能を使用すると、ソース テンプレートを更新した場合に、更新をプロジェクトにプッシュできます。

## <a name="guidance-for-performance-tuning-and-integration-write-patterns"></a>パフォーマンス チューニングと統合書き込みパターンに関するガイダンス

当社の経験と顧客とのやり取りに基づいて、大容量統合のためにパフォーマンスの最適化方法に関するガイダンスのドキュメントを提供しています。 さらに、多対一および一対多のパターンでのエンティティ データの移動に関する一般的な要求をカバーした、統合のための書き込みパターンに関するガイダンスを公開しています。

## <a name="compliance-for-government-cloud"></a>政府機関クラウドへのコンプライアンス

また、政府機関の顧客がサービスの恩恵を受けて利用できるように、データ インテグレーターを GCC に準拠させるようにしています。
