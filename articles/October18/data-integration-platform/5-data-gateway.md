---
title: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
description: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 6c35a192a2448abc017e61d28ae2937c040f477c
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続




このリリースには、オンプレミス データ ゲートウェイを向上するための複数の更新が含まれます。

## <a name="on-premises-data-gateway-supports-custom-connectors"></a>オンプレミス データ ゲートウェイでのカスタム コネクタのサポート

今年の初め、Microsoft は Power BI Desktop のカスタム コネクタに関するサポートを発表しました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。

ゲートウェイにおけるカスタム コネクタのサポートにより、ユーザーはオンプレミス データ ゲートウェイでデータを更新することで、カスタム コネクタで作成したレポートを Power BI サービスで最新の状態に保てます。

![オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート](media/custom-connectors-support-premises-data-gateway-1.jpg "オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート")

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a>クラスタリングを介したゲートウェイの高い利用可能性の保証
2017 年 11 月にリリースされたオンプレミス データ ゲートウェイにおける高い利用可能性の機能は、パブリック プレビューから一般提供に移行されます。 この取り組みには、より詳細なエラー報告をはじめとする複数のエクスペリエンスの向上が含まれます。

## <a name="improved-kerberos-single-sign-on-support"></a>Kerberos シングル サインオン サポートの向上
SSO の実装では、複数のドメインがサポートされます。

![Kerberos シングル サインオン サポートの向上](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Kerberos シングル サインオン サポートの向上")

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a>サポートされているデータ ソースの SAML ベースのシングル サインオン

昨年、SQL Server、SAP HANA、Teradata を含む複数のソースで、ゲートウェイに Kerberos シングル サインオン サポートを追加しました。

そして今後も、サポートされているデータ ソースで SAML ベースのシングル サインオン シナリオへのサポートを追加することにより、シングル サインオンへの投資を続ける予定です。

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a>データ ソース設定のエクスペリエンスの向上

Power BI サービスの「ゲートウェイの管理」ページで、要望の多かった一部の機能を追加することで、データ ソースの作成エクスペリエンスを向上させる予定です。これには、データ ソースの名前を変更する機能が含まれます。 その他の機能は、https://ideas.powerbi.com でリクエストおよび投票することができます。

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイにおけるテナント レベルの管理
テナントの管理者が API およびユーザー インターフェイスの両方を通じて、テナント内のすべてのオンプレミス データ ゲートウェイを管理する機能を追加する予定です。

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイにおける基本的なトラフィック負荷分散
クラスターのゲートウェイ全体で、特定のゲートウェイ クラスターについてリクエストされたトラフィックを分割する機能を導入する予定です。
ゲートウェイの管理者は、組織のニーズに応じて、この機能のオンとオフを切り替えることができます。

