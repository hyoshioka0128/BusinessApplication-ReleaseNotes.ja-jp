---
title: 二重書き込み (Common Data Service へのリンク)
description: 二重書き込み (Common Data Service へのリンク)
author: sabinn-msft
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: a654613e68e1e89b42d6c992d4721e45fd8b9f93
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225076"
---
# <a name="dual-write"></a>二重書き込み

[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]

顧客は、Microsoft の複数のビジネス アプリケーションを導入し、それらが同じ言語を使用してシームレスに連携できることを期待しているはずです。 二重書き込みにより、顧客は、これらのアプリを別々に書き込む異なるシステムと考えなくて済みます。基になるインフラストラクチャにより、これらのアプリへの同時書き込みがシームレスに行われます。  

## <a name="frictionless-experience-that-enables-dynamics-365-for-finance-and-operations-customers-to-natively-get-their-data-in-common-data-service"></a>Dynamics 365 for Finance and Operations ユーザーが Common Data Service のデータをネイティブに取得できるスムーズなエクスペリエンス

顧客は数回クリックするだけで、Dynamics 365 for Finance and Operations から Common Data Service にシームレスにリンクできます。 わずかな構成で、Dynamics 365 for Finance and Operations から Common Data Service に、そしてその逆に、変更が反映されます。 最初はエンティティのサブセットがサポートされているだけですが、徐々に増えていきます。

必要に応じて、Dynamics 365 for Finance and Operations の管理者は高度な設定を使用して、エンティティやフィールドのマッピングをカスタマイズしたり、ソース データのフィルタリングや変換を実行したりできます。

## <a name="ability-to-write-initial-data-prior-to-turning-on-dual-write"></a>二重書き込みを有効にする前に初期データを書き込む機能

この機能を使用して、二重書き込みを有効にする前に存在していたデータを書き込み、このデータを最新の状態に保ちます。

## <a name="making-dual-write-resilient-to-planned-or-unplanned-maintenance"></a>計画済みまたは計画外のメンテナンスに対する二重書き込みの回復性の確保

データの書き込みが失敗した場合、管理者は通知を受けてすぐにアクションを実行できる必要があります。 この機能は、組織のニーズに合ったエクスペリエンスを定義するための追加機能を管理者に提供します。

管理者は、電子メール通知を送信したり特定のエラーの種類やしきい値に対して管理者の代わりにアクションを実行したりするルールを定義できます。 また、予期しないエラーが発生した場合に非同期モードに切り替える機能も提供されます。

## <a name="support-for-multiple-legal-entities-in-dual-write"></a>二重書き込みにおける複数の法人のサポート

Dynamics 365 for Finance and Operations では、法人 (LE) による特定のデータのストライピングが可能です。 それぞれの法人に独自のユーザーが存在します。 製品は会社ごとにリリースできますが、価格は顧客の法人ごとに定義できます。

Dynamics 365 for Finance and Operations からのデータを統合する際には、適切な製品と価格が、適切なユーザーへの可視性を確保しながら Common Data Service に送信されるようにする必要があります。

同様に、Common Data Service の営業案件は、Dynamics 365 for Finance and Operations の適切な法人内に作成される必要があります。  

回避策はありますが、複数の法人に対する標準のサポートを提供する必要があります。 この機能を使用すると、複数の法人で同じプロジェクトを使用できるようになります。
