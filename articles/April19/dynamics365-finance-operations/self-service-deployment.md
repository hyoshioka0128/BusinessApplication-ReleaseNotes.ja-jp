---
title: セルフサービス展開
description: Tier 2 以上および本番環境へのセルフサービス展開
author: sarvanisathish
manager: AnnBe
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: sarvanis
audience: admin, end user, IT pro
ms.openlocfilehash: 51f10ce499d8fc5e4681740f18330c09bba9a318
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210304"
---
# <a name="self-service-deployment"></a>セルフサービス展開
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

新規導入プロジェクト向けのセルフサービス展開オプションが、2018 年 12 月に制限付きで提供開始されました。 今回は、本番環境向けのサポートが追加されました。 これにより本番環境は、セルフサービス展開用に構成されたすべての Lifecycle Services (LCS) プロジェクトに展開できるようになりました。

現時点では、セルフサービス展開オプションの対象となる新規プロジェクトはごく一部に限られています。 Microsoft では、新規プロジェクトの割合を今後徐々に増やしていく予定です。 既存のプロジェクトや環境への影響はありません。 Microsoft では、お客様の環境に新しいエクスペリエンスをもたらすべく、セルフサービス展開を使用していないお客様と連携して取り組んでいく予定です。

Tier 2 以上のサンドボックス環境に適用可能な機能についてはすべて、本番環境との整合性が確保されます。

## <a name="production-environments"></a>本番環境
1. 本番環境は、セルフサービス アクションとして展開できるようになります。 Microsoft のサービス要求を発行する必要はなくなります。
2. 展開は 3 時間以内に完了します (つまり、現在の方法で展開する場合の 3 分の 1 の時間)。
3. 更新を適用するため、結合された展開可能パッケージが Tier 2 サンドボックス環境に適用されます。 パッケージが適用されて検証されると、パッケージが本番環境に昇格されます。 

## <a name="tier-1-through-tier-5-sandbox-environments"></a>Tier 1 から Tier 5 のサンドボックス環境

### <a name="configure-tier-1-build-environment"></a>Tier 1 ビルド環境の構成
Tier 2 以上および本番環境に更新を適用できるようにするには、Tier 1 ビルド環境を構成する必要があります。 その Tier 1 ビルド環境を使用して、ISV ソリューションとカスタマイズを組み合わせた、単一の展開可能な更新パッケージを作成する必要があります。 パッケージ内に含まれているものはすべて環境に適用され、環境内にすでに存在しているものは上書きされます。

### <a name="remote-desktop-access"></a>リモート デスクトップ アクセス
現在、本番環境へのリモート デスクトップ アクセスはありません。 今後は、Tier 2 から Tier 5 のサンドボックス環境に対するリモート デスクトップ アクセスはできなくなります。 ただし、Tier 2、Tier 3、Tier 4、および Tier 5 のサンドボックス環境に関連付けられている Azure SQL データベースには、引き続きアクセスできます。 このアクセスは永続的ではありません。必要に応じて付与されます。 

Azure SQL データベースにアクセスするには:

1.  Lifecycle Services (LCS) から、SQL Server Management Studio を使用して、Azure SQL データベースへの接続に使用するコンピューターの IP アドレスを追加します。

2.  LCS を使用して、データベースの資格情報を参照するためのアクセス権を要求します。 その際、アクセス権を要求する理由を明示する必要があります。

要求を送信すると、要求がすぐに自動で承認されます。 1〜2 分以内に、LCS の **環境の詳細** ページにデータベース アクセスの資格情報が表示されます。 この資格情報を使用して、SQL データベースに接続できます。

> [!NOTE]
> 資格情報の有効期限は 8 時間で、その後は期限切れとなります。 資格情報が期限切れになると、アクセス権をもう一度要求しなければならなくなります。

コンピューターへのリモート アクセスを必要とするその他のアクション (環境間でのデータベース移動、CPU やメモリの消費量などといった正常性指標の確認、障害ログへのアクセス権の取得、リグレッション ツールの実行など) はすべて、LCS か、コンピューターへのリモート アクセスを必要としない方法を通じて利用できるようになります。
