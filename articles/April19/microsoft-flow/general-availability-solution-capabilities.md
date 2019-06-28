---
title: Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上
description: ソリューション機能の一般提供
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 05/09/2019
ms.assetid: ab87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: f3951a1a19e3639e997c825617a13991ab6b5658
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621745"
---
# <a name="improved-application-lifecycle-management-for-flows-using-common-data-service"></a>Common Data Service を使用したフローのアプリケーション ライフサイクル管理の向上

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

11 月に、マイクロソフトは Common Data Service ソリューションでの自動化およびスケジュールされたインスタント フローのサポートを[リリース](https://flow.microsoft.com/blog/solutions-in-microsoft-flow/)しました。 **ソリューション**により、フローや Common Data Service エンティティなどのコンポーネントのグループを作成、パッケージ化、メンテナンスできます。 ソリューションを配布することで、自分または他のユーザーが、環境全体でソリューションによって定義されているビジネス機能のインストールやアンインストールをできるようになります。

ソリューションの機能を向上させるために、現在新しい機能をリリースしています。 具体的には、Common Data Service を使用する特定のフローを、新しい環境へのソリューションのインポート時に自動的にアクティブ化できるようになりました。

自動的にオンにすることができるフローを構築するには、最初に左のナビゲーションで **ソリューション** に移動し、ソリューションを選択してからフローを追加することで、フローを構築する必要があります。 フローを構築する際には、新しい **Common Data Service (現在の環境)** コネクタを使用します。

![コネクタの検索](media/cds-native-1.png)

このコネクタは、フローが展開されている環境を常に使用し、フローの所有者のユーザー コンテキストを自動的に取得できるという点で特殊です。 つまり、接続先の環境を選択する必要はありません。

![完全トリガー](media/cds-native-2.png)

この例では、取引先企業の親会社が変更されたときにすべての関連取引先企業に自動的にメモを追加するフローを作成できます。

![完全フロー](media/cds-native-3.png)

フローを保存したら、それを管理ソリューションまたは非管理ソリューションとしてエクスポートできます。 フローによって完全にサポートされるようになった管理ソリューションは、フローを運用環境に移行する際に役立ちます。これらのソリューションの種類の違いについては、[こちらで詳細を読む](https://docs.microsoft.com/dynamics365/customer-engagement/developer/introduction-solutions#unmanaged-and-managed-solutions)ことができます。

![ソリューションのエクスポート](media/cds-native-4.png)

ソリューションをエクスポートした後、移行先の環境に移動してソリューションをインポートできます。

![ソリューションのインポート](media/cds-native-5.png)

このソリューションのフローは、更新されている取引先企業のリスニングとメモの作成をすぐに開始します。 追加の構成やアクティブ化は必要ありません。

![フローの結果](media/cds-native-6.png)

この機能は  **Common Data Service (現在の環境)** 以外のサービスへの接続がないフローに対してのみ機能します。 これは、インポート後に接続所有者によって他のサービスが明示的に許可される必要があるためです。 ただし、データを操作したり HTTP コネクタを使用したりする組み込みアクションは、インポート後すぐに機能します。

## <a name="known-issues"></a>既知の問題

新しい **Common Data Service (現在の環境)** 機能は、現在プレビュー版が利用可能で、来週には世界的に展開されます。 ソリューション内に構築されているフローにはいくつかの既知の問題があります。

*   Flow モバイル アプリでソリューション フローにアクセスする方法はありません。
*   ソリューション内のボタンが Flow モバイル アプリの [ボタン] タブに表示されず、ボタンの特定のフィールドを使用できません。
*   現在、カスタム コネクタをソリューションに含めることができません。
*   レコード上で列またはフィールドのセットが変更されると、フローが失敗する可能性があります。
*   実行履歴には現在、各アクションの単純なプロパティではなく、アクションに対する未加工の JSON 入力および出力が表示されます。
*   PowerApps からトリガーされるフローは現在サポートされていません。

現在、これらのフローに残っている問題の解決に取り組んでいます。
