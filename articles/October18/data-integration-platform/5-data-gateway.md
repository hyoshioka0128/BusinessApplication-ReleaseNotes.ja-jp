---
title: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
description: "オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: a7d7af2618f94a26de1f78a89b253af4d0c4225a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




このリリースには、オンプレミス データ ゲートウェイを向上するための複数の更新が含まれます。

## <a name="certified-custom-connectors-in-power-bi-desktop"></a>Power BI Desktop における認定カスタム コネクタ

今年の始め、Microsoft は Power BI Desktop のカスタム コネクタに関するサポートを発表しました。これは M 言語の強力な機能を使用しており、パートナーは独自のコネクタを記述してすべての Power BI ユーザーに配布することができます。

ゲートウェイにおけるカスタム コネクタのサポートにより、ユーザーはオンプレミス データ ゲートウェイでデータを更新することで、カスタム コネクタで作成したレポートを Power BI サービスで最新の状態に保てます。

![オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート](media/custom-connectors-support-premises-data-gateway-1.jpg "オンプレミス データ ゲートウェイにおけるカスタム コネクタのサポート")

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a>Power BI Premium のゲートウェイ マルチ地域サポート

Power BI サービスでマルチ地域をサポートする作業の一環として、オンプレミス データ ゲートウェイは、構成手順の最中にユーザーがテナントのホーム リージョンとは異なるリージョンを選択するのを可能にします。 これにより、データ ソースの情報および資格情報は選択された地域にとどまり、組織固有の規制要件に準拠できます。

またエクスペリエンスを更新して、ユーザーがそれらのリージョンでオンプレミス データ ゲートウェイを使用できるようにする必要があります。 この取り組みには、データ ソースの情報 (たとえば、認証情報) がワークスペースの属するリージョンから離れないように見届けることが含まれます (データの主権に準拠するため)。

![オンプレミス データ ゲートウェイにおけるマルチ地域のサポート](media/gateway-multi-geo-support-pbi-premium-1.png "オンプレミス データ ゲートウェイにおけるマルチ地域のサポート")

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a>クラスタリングを介したゲートウェイの高い利用可能性の保証
2017 年 11 月にリリースされたオンプレミス データ ゲートウェイにおける高い利用可能性の機能は、パブリック プレビューから一般提供に移行されます。 この取り組みには、より良いエラー報告とユーザー エクスペリエンスの向上をはじめとするむ、複数のエクスペリエンスの向上が含まれます。

## <a name="improved-kerberos-single-sign-on-support"></a>Kerberos シングル サインオン サポートの向上
SSO の実装で複数のドメインがサポートされる予定で、SSO の接続テストと問題の診断をより簡単に行えるようにもします。

![Kerberos シングル サインオン サポートの向上](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Kerberos シングル サインオン サポートの向上")

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a>サポートされているデータ ソースの SAML ベースのシングル サインオン

昨年、SQL Server、SAP HANA、Teradata を含む複数のソースで、ゲートウェイに Kerberos シングル サインオン サポートを追加しました。

そして今後も、サポートされているデータ ソースで SAML ベースのシングル サインオン シナリオへのサポートを追加することにより、シングル サインオンへの投資を続ける予定です。

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a>Power BI Desktop とのパリティを保つための追加のクラウド データ更新機能

Power BI Desktop では問題なく Power BI データセットが更新されるものの、Power BI サービスでは更新に失敗することがあります。 これは多くの場合、このデータセットで使用された個別のデータ ソースのプライバシー設定が原因で生じます。

Power BI Desktop では、ユーザーがそれぞれのデータ ソースのプライバシー設定を変更することが可能で、データセットは正常に更新されます。 Power BI サービスでも、ユーザーにそれらのデータセットを正常に更新する機能が与えられる予定です。

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a>データ ソース設定のエクスペリエンスの向上

Power BI サービスの「ゲートウェイの管理」ページで、要望の多かった一部の機能を追加することで、データ ソースの作成エクスペリエンスを向上させる予定です。これには、テスト接続の手順をスキップする機能、データ ソースの名前を変更する機能、異なる認証情報で複数のデータ ソースを作成する機能などが含まれます。

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイにおけるテナント レベルの管理
テナントの管理者が API およびユーザー インターフェイスの両方を通じて、テナント内のすべてのオンプレミス データ ゲートウェイを管理する機能を追加する予定です。

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a>オンプレミス データ ゲートウェイにおける基本的なトラフィック負荷分散
クラスターのゲートウェイ全体で、特定のゲートウェイ クラスターについてリクエストされたトラフィックを分割する機能を導入する予定です。
ゲートウェイの管理者は、組織のニーズに応じて、この機能のオンとオフを切り替えることができます。

