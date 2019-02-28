---
title: アプリケーション ライフサイクル管理の機能強化
description: 管理者が Business Central アプリケーションのライフサイクル管理に使用できるツールが増えました
author: jaredha
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jaredha
audience: admin
ms.openlocfilehash: 8c4e6ca1cf4213a7b8f2645bcebd6787ecfdcd95
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210894"
---
# <a name="enhancements-for-application-lifecycle-management"></a>アプリケーション ライフサイクル管理の機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

Business Central の 2019 年 4 月リリースでは、顧客の Business Central テナントを管理する方法が強化されています。  

## <a name="manage-upgrade-schedule"></a>アップグレードのスケジュールを管理する

2019 年 4 月リリースでは、Business Central 環境のアップグレードの表示と制御が改善されています。 Business Central テナントのアップグレードが所定の日にスケジュールされるようになり、ユーザーと管理者はより適切にアップグレードの計画を立てることができます。 また、管理者は、Business Central 管理センターでアップグレードを別の日に再スケジュールしたり、*今すぐアップグレード* アクションを選択することで環境をすぐにアップグレードしたりすることもできます。 管理者は、アップグレードが失敗する原因になる可能性があるテレメトリのエラーも見ることができます。

## <a name="monitoring-and-notifications"></a>監視と通知

Business Central の管理者は、環境で発生しているイベントについていっそう多くの通知を受け取ることができます。 管理者は、Business Central 管理センターを使用して、さまざまなイベントの種類ごとに通知を受け取る受信者を選択できます。 新しいイベント通知には、今後のアップグレード、アップグレードのスケジュール、アップグレードの結果、利用可能な拡張機能のアップグレードに関する詳細が含まれます。 管理者は、Business Central 管理センターの新しいページを使用して、すべての通知の一覧と詳細を表示することもできます。

## <a name="version-previews"></a>バージョン プレビュー

アプリケーションの新バージョンのリリース候補を、サンドボックス環境で利用できるようになります。 テナント管理者と ISV は、サンドボックス環境を新しいリリース候補バージョンにアップグレードしたり、新しいバージョンで新しいサンドボックス環境を作成したりできます。 これにより、管理者と ISV は、運用環境でアップグレードが行われる前に、サンドボックス環境でテストを行い、拡張機能の互換性を確認し、新しいアプリケーションの機能を確認できます。

## <a name="multiple-sandboxes"></a>複数のサンドボックス

サンドボックス環境は、Business Central 用の拡張機能を正常に作成、テスト、およびアップグレードするために不可欠です。 多くのシナリオでは、複数のサンドボックス環境を用意する必要があります。 2019 年 4 月リリースでは、管理者はテナント用に複数のサンドボックス環境を作成できるようになります。 各サンドボックスは異なる環境であり、運用環境に影響を与えることなく、個別に変更、アップグレード、および削除できます。  

## <a name="enhanced-sandbox-management"></a>強化されたサンドボックス管理

2019 年 4 月リリースでは、Business Central 管理センターのサンドボックス管理エクスペリエンスが強化されています。 環境の概要では、サンドボックス環境に関する追加情報が表示され、サンドボックス環境をアップグレードしてアプリケーションのバージョンをプレビューできます。 また、管理者は、運用環境の場合と同じように、テナントごとの拡張機能をサンドボックスにアップロードして展開することもできます。 サンドボックスに展開されたテナントごとの拡張機能と AppSource アプリは、運用環境でのアップグレードと同じ方法でアップグレードされるので、管理者はサンドボックス環境でアップグレードを完全にテストできます。

## <a name="enhanced-extension-management"></a>強化された拡張機能の管理

テナントごとの拡張機能と AppSource アプリを最新の状態に保ち、将来のバージョンでも確実に動作させることが不可欠です。 2019 年 4 月リリースには、管理者がこのタスクを行うのを助ける多くの機能が含まれています。 1 つ目は、ベース アプリケーションの将来のバージョンに対してテナントごとの拡張機能を検証し、非互換性が見つかった場合に管理者/開発者に通知する自動化サービスです。 インストール済み AppSource アプリの新しいバージョンが使用できるようになったときにも、通知が管理者に送信されます。 管理者はスケジュールに従って拡張機能管理ページからアプリをアップグレードできます。  

## <a name="lifecycle-services-preview"></a>Lifecycle Services (プレビュー)

Business Central の ISV は、Lifecycle Services (LCS) を通じて、アプリのライフサイクルに対するサポートを受けることができます。 Lifecycle Services は、ISV がソリューションの完全なライフサイクル管理を実行するためのポータルであり、展開、アップグレード、初期のテストと評価のためのプレビュー版の表示、VAR の承認、監視、ライブ サイトのトラブルシューティングなどが含まれます。  
