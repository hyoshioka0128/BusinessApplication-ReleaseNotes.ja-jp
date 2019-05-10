---
title: 独自の Data Lake 内のエンティティ格納
description: エンティティ格納内のトランザクション データとマスター データは、独自の ADLS Gen2 Data Lake で利用できます。
author: MilindaV2
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: MilindaV2
ms.openlocfilehash: c11d0d0f0d4a8be91bc3a300864c0eeb70816e84
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225183"
---
<!--from editor: What does BYOD stand for? Also, COGS? Does ADL mean Azure Data Lake?-->


#  <a name="entity-store-in-your-own-business-data-lake"></a>独自の Business Data Lake 内のエンティティ格納
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



Dynamics 365 for Finance and Operations に組み込まれている分析ワークスペースは、以下のような理由で、お客様から高く評価されています。

- **Finance and Operations のコンテキストでの埋め込み**: セキュリティ フィルターとデータ フィルターはユーザーのコンテキストに基づいています。 ユーザーはドリルスルーしてアクションを実行できます。

- **予測可能な価格**: Finance and Operations のライセンスを入手すると、お客様はエクスペリエンスを利用できます。

ただし、一般に、KPI や計算を追加することによって埋め込みレポートを拡張したり、独自のデータとマージすることが、頻繁に必要になります。 埋め込みレポートを変更するとコストは高くなります (つまり、開発者の関与が必要です)。 そのため、お客様は BYOD も使用して、レポート用に独自のデータベースにデータをエクスポートし、多くの場合、レポートを複製して変更します。 データ管理では引き続き SQL データベース (BYOD など) へのデータのエクスポートがサポートされますが、データのエクスポートと例外の管理に関連する管理上のオーバーヘッドを削減したいと考えています。

苦労を減らして、エクスペリエンスを単純化するため、Business Data Lake (ADL Gen2) インフラストラクチャを Power BI データフローと共に利用しています。 この機能は次のとおりです。

お客様は、独自の Data Lake (Azure Data Lake Storage Gen2) を持ち込み、Finance and Operations 内で構成することができます。 Data Lake は、SQL データベースより費用対効果の高いオプションです。

エンティティ格納内のトランザクション データとマスター データは、お客様の Data Lake に公開されます。 リアルタイム ベースで最新のデータが保持されます。 最初の重点は Data Lake 内で集計の測定と集計の分析コードを有効にすることですが、機能の改善として Data Lake で通常のデータ エンティティをステージングできるようにする予定です。

お客様は、自分自身の PowerBI.com サブスクリプションを持ち込み、Finance and Operations 内で構成することもできます。 この機能は、システムで既に使用できます。 お客様がこの情報を提供すると、分析ワークスペースに含まれる Power BI レポートも、お客様独自の PowerBI.com サブスクリプションに公開されます。 PowerBI.com のパワー ユーザーや消費者は、レポートやダッシュボードを使用するだけでなく拡張することもできます。 また、Power Q&A やモバイル ダッシュボードの使用など、PowerBI.com で利用可能なすべての機能も使用できます。

この機能により、運用レポートの作成に伴う現在の苦労が解消されるだけでなく、戦略的な利点ももたらされます。

- エンティティ格納で使用できるトランザクション データとマスター データに、Data Lake 経由でアクセスできるようになります。 同じトランザクション データを BYOD にエクスポートする必要はありません。 データ フローを介した PowerBI.com との既製の統合により、簡単なデータ マッシュアップが可能になります。

- お客様は、データをオンプレミスのデータ ウェアハウスにダウンロードしなくても、自分のデータ Data Lake に取り込んで、マッシュアップ シナリオを簡単に実現できます。 データを Data Lake に格納するコストは、SQL データベースに格納するよりはるかに低くなります。

- Dynamics ドメイン内の複数のアプリケーションを対象とする分析アプリを構築できます。 たとえば、お客様は Customer Engagement アプリケーションと Finance and Operations の間でデータを組み合わせることができます。

- お客様の COGS の削減 (BYOD の使用の削減)。
