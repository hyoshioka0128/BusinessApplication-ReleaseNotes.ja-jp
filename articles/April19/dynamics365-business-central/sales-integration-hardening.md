---
title: Business Central と Dynamics 365 for Sales の統合の強化
description: Business Central と Dynamics 365 for Sales の統合の改善
author: ikoletic
ms.reviewer: edupont
ms.date: 02/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.author: ivkoleti
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: 5b8723bfd2767769cd6d0221543f71822cd52ade
ms.sourcegitcommit: a75d70c06338341eb5e9e15a3679c07dfcd7fc45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/22/2019
ms.locfileid: "721928"
---
# <a name="hardening-the-integration-between-business-central-and-dynamics-365-for-sales"></a>Business Central と Dynamics 365 for Sales の統合の強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Dynamics 365 for Sales を使用する Business Central ユーザーの増加に伴い、Business Central と Dynamics 365 for Sales の統合には、信頼性の高い同期、販売注文の統合の改善、Dynamics 365 for Sales との AI 分析情報の共有が求められるようになりました。  

## <a name="business-value"></a>ビジネス バリュー
データの重複入力を避けるために、データは Business Central と Sales の間で同期されます。 Business Central と Sales の両方で同期データが変更されると、同期の競合が発生する可能性があります。 営業担当者は、このような競合を認識し、IT 部門やパートナーを介さずに簡単に解決できる必要があります。  

外出先での作業を可能にするために、営業担当者は、Business Central と Sales の両方について、応答性の高いユーザー エクスペリエンスを備えた最新のモバイル アプリケーションで作業できる必要があります。  

販売注文の処理中、注文処理の担当者は価格を更新する、営業担当者が入力したメモを読む、代替品目を入力する、出荷予定日を変更することなどを実行できる必要があります。 Sales で作業している営業担当者がこのような変更を確認し、すぐに顧客に通知できるようにすることが重要です。  

Business Central と Sales のデータから生成された AI ベースの分析情報を共有することで、営業担当者は成立する可能性が最も高い商談に集中することが可能になり、支払いが遅れると予想される顧客のリスクを軽減できます。  

## <a name="self-service-in-resolving-synchronization-conflicts"></a>セルフサービスでの同期競合の解決
Sales や Relationship Manager のロール センターなどの営業関連のロール センターで対応可能な同期の問題を表面化することで、営業担当者はそのようなデータの所有者として (たとえば一括で) それらを解決する方法を決めることができます。  

![同期が競合しているタイル](media/synch-resolution.png "ロール センターのデータ エラー タイル")

## <a name="open-coupled-sales-records-from-business-central-in-unified-interface"></a>統一インターフェイスで Business Central から Sales の連結レコードを開く
新しい統一インターフェイスで、Business Central から Sales の連結エンティティを開くことができるようになりました。 Dynamics 365 営業ハブ アプリがインストールされている場合は、**Microsoft Dynamics 365 接続の設定**ページの **Dynamics 365 営業ハブで連結エンティティを開く**チェック ボックスをオンにします。 これにより、**取引先企業**、**取引先担当者**、**製品**などのアクションを選択すると、統一インターフェイスに Dynamics 365 for Sales の連結エンティティが開きます。

![Dynamics 365 営業ハブで連結エンティティを開く](media/open-coupled-in-uci.png "[接続の設定] ページの [Dynamics 365 営業ハブで連結エンティティを開く] チェック ボックスの図")

Sales への接続が確立されると、統一インターフェイス Sales アプリ (営業ハブ) がインストールされているかどうかが Business Central によって確認されてから、**Microsoft Dynamics 365 接続設定**ページの **Dynamics 365 営業ハブで連結エンティティを開く**チェック ボックスが自動的にオンになります。

## <a name="sales-order-synchronization"></a>販売注文の同期
Sales で送信された販売注文が Business Central で作成された後に、さまざまな変更が発生する場合があります。 そのような変更は再度 Sales に同期させることができます。 Sales で営業担当者が作成したメモを Business Central と同期できるようになりました。

![Business Central が Dynamics 365 for Sales で送信された販売注文を更新](media/sales-order-posts-from-bc.png "販売注文送信済みフォームの Dynamics 365 for Sales タイムラインに対して Business Central が行った投稿の図")

## <a name="sales-quote-synchronization"></a>販売見積の同期
一度 Sales で有効になった販売見積を、Business Central でピックアップして作成できるようになりました。 Sales では見積の改訂が発生する可能性があるので、Business Central で以前に同期された見積をアーカイブおよび更新することによって、そのような改訂が Business Central に再び同期されます。

![Dynamics 365 for Sales からのアクティブ化された見積の処理](media/process-quote-from-sales.png "Business Central で処理される予定の、Dynamics 365 for Sales から取得された販売見積の図")

## <a name="shared-ai-between-business-central-and-sales-post-april-2019"></a>Business Central と Sales の間の共有 AI (2019 年 4 月投稿)
Business Central で作業をしている営業担当者は AI for Sales で生成されたインテリジェンスを消費し、Sales で作業している営業担当者は Business Central で生成されたインテリジェンスを消費できます。  

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。

<!--
### Who uses this feature
These features are intended for end users working in sales. They may require additional setup.
## Status
### Development status
In development
-->
