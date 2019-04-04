---
title: Dynamics 365 for Customer Service での顧客サービス管理設定の理解
description: Dynamics 365 for Customer Service の管理設定の新機能を説明します
ms.date: 03/15/2019
ms.assetid: 516afbde-61a3-4718-8ce1-a4007ada5960
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: DeepapMS
ms.reviewer: anjgupta
audience: Admin
ms.openlocfilehash: 5221cc48b19567d2f9d2ef4088e4b3536f8eab6c
ms.sourcegitcommit: 3631212f9fba5a8128793f0a92114ae04b614708
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/15/2019
ms.locfileid: "845248"
---
#  <a name="customer-service-admin-settings"></a>Customer Service 管理設定 

[!include[customer-service-core-release-notes banner](../../includes/customer-service-core-release-notes.md)]

Dynamics 365 の顧客の主要な目標の 1 つは、業務プロセスをすばやく展開することです。 Service Management モジュールは、顧客サービス マネージャーが、さまざまな顧客サービス プロセスを自動化し、エージェントのターンアラウンド時間を短縮し、顧客満足を最善にするのに役立ちます。 Service Management は、パブリック キューまたはプライベート キューの構成、親子サポート案件設定のセットアップ、ルーティング規則の構成、自動レコード作成と更新ルールの構成、サービス レベル アグリーメント (SLA) のセットアップなど、顧客サービス タスクを構成して管理する機能を管理者に提供します。

最新リリースの Service Management は顧客サービス ハブの下に移動しており、顧客サービス マネージャーはアプリケーション内から構成にアクセスできます。 統一インターフェイスに基づく新しい Service Management では、サービス タスクを簡単に構成でき、生産性を高めることができます。 

Service Management には、顧客サービス ハブのサイトマップからアクセスできます。 

![サイトマップからの Service Management へのアクセス](media/csh-sitemap-service-management.png "サイトマップからの Service Management へのアクセス")

> [!NOTE]
> 2018 年 10 月のリリースでは、顧客サービス ハブのサイトマップから、**ルーティング規則セット**、**自動レコード作成**、**サービス レベル アグリーメント**を除くすべての管理設定にアクセスして管理できます。 これら 3 つの管理者設定にアクセスして管理するには、Web アプリケーションで**設定** > **サービスの管理**に移動します。 </br>
> これらの 3 つの管理設定 (ルーティング規則セット、自動レコード作成、サービス レベル アグリーメント) は、2019 年 4 月リリース以降の顧客サービス ハブのサイトマップで利用できるようになります。

Service Management 内では、さまざまな機能をカスタマイズできます。 次のような機能です。  

- **キュー**: Service Management のキューには再設計されたエクスペリエンスが付属し、割り当てられた作業の進捗の適切な優先順位付けと監視に役立ちます。

  ![Service Management でのキューの使用](media/service-management-queues.png "Service Management でのキューの使用")

- **情報カテゴリ**: 情報カテゴリは、サポート案件、サポート情報の記事、製品、営業資料を分類する強力な機能であり、それによってエージェントの能力を高め、顧客への迅速な応答を促進します。  

  ![Service Management での情報カテゴリの使用](media/service-management-subjects.png "Service Management での情報カテゴリの使用")

- **サポート案件の設定**: 親子サポート案件の設定を使用すると、サポート案件をリンクでき、一般的な問題に対する応答と追跡が向上します。  

- **ルーティング規則**: ルーティング規則は、手動介入なしで、適切なキュー、ユーザー、またはをチームへのサポート案件のルーティングを自動化します。 

- **自動レコード作成と更新ルール**: このルールでは、電子メール、ソーシャル アクティビティ、または他のカテゴリのアクティビティなどの入力アクティビティに基づいて、サポート案件や関連するレコードの作成または更新を自動化できます。 

- **権利**: 権利は、顧客に資格があるサポートの定義と定量化に役立ちます。 時間数またはサポート案件数に基づいて、サポート条件を指定できます。 

  ![権利の使用](media/service-management-entitlements.png "権利の使用")

- **権利テンプレート**: 権利セットアップ用の再利用可能なテンプレートを使用して、エクスペリエンスをすばやく構成できます。  

- **祝日スケジュール**: SLA が影響を受けないように、祝日の休業に対応できます。 

  ![祝日のスケジューリング](media/service-management-holiday-schedule.png "祝日のスケジューリング")

- **顧客サービス スケジュール**: チームの営業時間を定義するために使用できます。  

  ![顧客サービス スケジュールの設定](media/service-management-customer-service-schedule.png "顧客サービス スケジュールの設定")

- **サービス レベル アグリーメント**: サービス タスクのマイルストーンの合意に使用されます。 サービス レベル アグリーメントは、祝日スケジュールと顧客サービス スケジュールで定義されている構成に従います。  

- **ナレッジ マネージメントの設定**: ナレッジ マネージメントとテキスト分析に対してエンティティを有効にするために使用されます。 

## <a name="resources"></a>リソース

[サービス マネージャー ガイド (顧客サービス ハブおよび Customer Service アプリ)](https://docs.microsoft.com/dynamics365/customer-engagement/customer-service/service-manager-guide)


