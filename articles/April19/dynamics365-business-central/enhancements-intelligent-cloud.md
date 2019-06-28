---
title: インテリジェント クラウドの機能強化
description: インテリジェント クラウドの機能をさらに強化しています
author: jenolson
ms.reviewer: edupont
ms.topic: summary
ms.service: business-applications
ms.author: jenolson
audience: Admin
ms.date: 05/07/2019
ms.openlocfilehash: 16728f4faeba98551970b1a72e88db979b7a9821
ms.sourcegitcommit: 6e35a95a3ec33c1b4478fe5247fab577ed7a3a8d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/10/2019
ms.locfileid: "1539886"
---
# <a name="enhancements-to-the-intelligent-cloud-for-dynamics-smb-and-dynamics-365-business-central"></a>Dynamics SMB と Dynamics 365 Business Central 向けのインテリジェント クラウドの機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]
Business Central の 2019 年 4 月リリースでは、お客様向けのインテリジェント クラウドに多数の新しいビジネス バリューの機会が追加されました。 

## <a name="dynamics-sl-2018-and-the-intelligent-cloud"></a>Dynamics SL 2018 と Intelligent Cloud
Dynamics SL 2018 CU1 では、既存のお客様は Business Central Intelligent Cloud が提供する機能を利用できます。  

お客様は、既存の Dynamics SL 2018 オンプレミス ソリューションから Business Central クラウド テナントに、オープンなトランザクションおよびマスター レコードのデータを複製できます。 データの複製が完了すると、Dynamics SL のデータを PowerApps、Microsoft Flow、Power BI、Azure などのクラウド サービスで使用できます。  

## <a name="dynamics-gp-2018-r2-historical-data-available-in-the-intelligent-cloud"></a>Intelligent Cloud で使用できる Dynamics GP 2018 R2 の履歴データ
2019 年 4 月リリースでは、Dynamics GP 2018 R2 から Business Central Intelligent Cloud への追加データの複製のサポートが追加されます。  

2018 年 10 月リリースでは、Dynamics GP 2018 R2 のお客様は、オープンなトランザクション データとマスター レコード データを Business Central クラウド テナントに複製できるようになりました。 フィードバックに基づき、2019 年 4 月リリースからは、履歴データのデータ複製プロセスもサポートされます。  

## <a name="dynamics-nav-2018-and-the-intelligent-cloud"></a>Dynamics NAV 2018 と Intelligent Cloud
Intelligent Cloud でのすべての Dynamics SMB 製品に対するデータ複製のサポートを完全なものにするため、Dynamics NAV 2018 は Business Central の 2019 年 4 月リリースの一部として完全にサポートされる予定です。 

Dynamics NAV 2018 のお客様は、カスタマイズされたテーブルを除き、事実上すべてのオンプレミス テーブルを Business Central クラウド テナントに複製することができます。

## <a name="improved-data-replication-services"></a>データ複製サービスの向上
また、データ複製サービスを強化し、同じサービスのパフォーマンスとテレメトリを改善しています。 ウィザードのセットアップ プロセスに、これまでよりわかりやすいエラー メッセージを追加しました。

さらに、スキーマの比較を緩和しました。スキーマが完全に一致する場合、テーブルは失敗しません。 テーブルにカスタム列が追加されている場合、コア列が引き継がれ、失敗にはなりません。 拡張機能が Business Central オンラインにはインストールされていて、オンプレミス展開にはインストールされていない場合は、エラーではなく警告が表示されます。 オンプレミスより Business Central オンラインの方が列が長い場合は、データを引き継ぎます。

2019 年 4 月の更新プログラムでは、サービスの更新が発生したときの新しい通知も追加されます。 自動ではなく手動でサービスを更新するオプションがあります。 新しい [ステータスの更新] ボタンそ使用すると、ページから移動しなくても Intelligent Cloud 管理ページを更新できます。

4 月の更新プログラムの前は、手動で複製をトリガーできる回数には制限があり、24 時間に 1 回に制限されていました。 4 月の更新プログラムでは、その制限は取り除かれました。

## <a name="smartlists"></a>SmartLists
Business Central (オンライン) 内のビジネス インテリジェンスを簡略化するために SmartLists を追加し、後のリリースで SmartList Designer ツールを作成するための基盤を構築します。

2019 年 4 月の更新プログラムでは、Business Central のさまざまなページに 16 個の既定の SmartLists が追加されました。 これらの SmartLists は、Business Central のマスター エンティティにリンクされている情報の追加ビューです。

16 個の既定のリストは、複数のテーブルからデータを取得するビューに基づいています。 今回の更新プログラムでは、クエリに基づいてリスト ビューを作成する機能が追加されました。  

追加されたリストの例としては、顧客リスト、販売担当者リスト、場所別品目リストなどがあります。 これらの SmartLists には、リスト ページからアクセスすることができます。 たとえば、顧客リストに移動し、アクション バーの左側にある新しい [すべて] ドロップダウン アクションに注目してください。 そのアクションを選択すると、この更新プログラムに追加された新しい SmartLists を見ることができます。

16 個の SmartLists には、勘定科目表、顧客、仕入先、品目の一覧ページからアクセスできます。

|リスト| SmartLists のページ名|
|----|------------------------|
|勘定科目表| 勘定科目表 (取引先企業の説明)|
|顧客|    顧客出荷先住所|
|顧客|    顧客および営業担当者|
|顧客|    ブロックされた顧客|
|顧客|    与信限度額のある顧客|
|顧客|    顧客と取引先担当者|
|仕入先|        仕入先注文住所|
|仕入先|        仕入先と購入者|
|仕入先|        ブロックされた仕入先|
|仕入先|        仕入先残高|
|品目|       品目|
|品目  |      品目数量|
|品目  |      場所別品目|
|品目  |      マイナス数量品目|
|品目  |      カウント期限切れ品目|
|品目  |      品目カウント期限|

SmartLists 機能の追加と共に、クエリに基づいて SmartLists を作成できるようにするため、基盤となるプラットフォームに対する変更をいくつか行いました。 この機能により、拡張機能を通して独自のリストを作成できるようになります。 作成したリストは、QueryCategory プロパティを設定することで、エンティティに割り当てることができます。

クエリに基づいて新しいリスト ページを作成できることにより、すべてのデータがデータベース内の単一のテーブルにない場合でも、必要なデータを 1 つのリストにまとめることができます。


 
