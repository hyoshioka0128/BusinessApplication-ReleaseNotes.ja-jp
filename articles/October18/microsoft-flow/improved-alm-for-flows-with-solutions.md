---
title: ソリューションを使用したフローの ALM の向上
description: ソリューションには、キャンバス アプリ、およびモデル駆動型アプリ、フロー、他のコンポーネントを含めることができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: 66861f2b-56e1-e811-a976-000d3a137a43
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 71635b2f4f0ae7f56975a911f7fecdf76d11b968
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391047"
---
# <a name="improved-alm-for-flows-with-solutions"></a>ソリューションを使用したフローの ALM の向上




Microsoft は最近、PowerApps と Microsoft Flow の新しいアプリケーション ライフサイクル管理 (ALM) 機能についてのニュースを[発表](https://powerapps.microsoft.com/blog/apps-and-flows-lifecycle-management-just-got-easier/)しました。 この新しい機能は Common Data Service (CDS) for Apps ソリューションが基になっており、関連するフロー (およびアプリ) を単一の展開可能ユニットにバンドルすることができます。

以前は、単一のフローをある環境からエクスポートして別の環境にインポートする機能が提供されていました。 この機能は環境間で個別のフローをプロモートするのには役立ちましたが、複数のフローを移動するには多くの労力が必要でした。

また、お客様から、フローを構築したり管理したりするときに[*関連するフローを論理的にグループ化する*](https://powerusers.microsoft.com/t5/Flow-Ideas/Provide-a-method-of-organising-Flows/idi-p/87796)ための機能に関するフィードバックをいただきました。 たとえば、作業中のプロジェクトの一部である複数のフローがあるとします。 これらのフローを作業または管理する際、フローにアクセスしたいときにスクロールして検索することが必要なのは好ましくありません。

ソリューションは、一連のフロー (およびアプリ) をエクスポートおよびインポートできるようにすることで、展開のニーズに対応します。 さらに、これらのフローを単一の「コンテナー」内に整理することができ、フローのナビゲートと管理が簡単になります。

## <a name="accessing-solutions"></a>ソリューションへのアクセス

新しい**ソリューション** リンクが、Microsoft Flow ポータルの左側のナビゲーション内に表示されます。 このエクスペリエンスは、Common Data Service データベース バージョン 9.1.0.267 以降の環境で使用できます。 **ソリューション**が表示されず、環境の管理者である場合は、**[Microsoft Flow 管理センター](https://admin.flow.microsoft.com/)** > **環境** > ***環境の選択*** > **詳細**タブに移動します。**自分のデータベースを作成**ボタンが表示されたら、そのボタンを選択して、ソリューションを格納するための Common Data Service データベースを作成する必要があります。 データベースがある場合は、**インスタンスのバージョン**を確認できます。

![ソリューションへのアクセス](media/improve-alm-solutions/solutions-1-accessingsolutions.png "ソリューションへのアクセス")

**ソリューション**を選択すると、環境内のすべてのソリューションのリストが表示されます。 このエクスペリエンスの一部として、ソリューションが作成された**日付**、**バージョン**、およびソリューションに関するその他の詳細を確認できます。

![ソリューションの参照](media/improve-alm-solutions/solutions-2-solutionsexplorer.png "ソリューションの参照")

## <a name="creating-a-new-solution"></a>新しいソリューションの作成

フローをグループ化する新しいソリューションを作成するには、ソリューション エクスペリエンスから、**新しいソリューション** ボタンを選択します。

![新しいソリューション](media/improve-alm-solutions/solutions-3-newsolution.png "新しいソリューション")

新しいタブが開き、ソリューションの**表示名**、**発行元**、および**バージョン**を入力できます。 これらの詳細を入力したら、**保存**を選択し、**閉じる**を選択します。

![ソリューションの保存](media/improve-alm-solutions/solutions-4-savesolution.png "ソリューションの保存")

## <a name="adding-flows-to-a-solution"></a>ソリューションへのフローの追加

ソリューション エクスペリエンスから、新しく作成したソリューションを選択して、既定のビューに移動できます。 状況に応じたメニューが表示され、**新規**および**既存**の資産をソリューションに追加できます。 ソリューションに新しいフローを追加するには、**新規 – フロー**を選択します。

![新しいフロー](media/improve-alm-solutions/solutions-5-newflow.png "新しいフロー")

新しいタブが開いてフロー デザイナーが表示され、フローを構築して、関連するトリガーとアクションを追加することができます。 フローの編集が完了したら、**保存**を選択してフローを保存します。

![フローの保存](media/improve-alm-solutions/solutions-6-saveflow.png "フローの保存")

フローを保存すると、このフローはソリューションの一部になります。

![ソリューション内のフロー](media/improve-alm-solutions/solutions-7-newflow.png "ソリューション内のフロー")

以上の手順を繰り返して、後続のフローをソリューションに追加することができます。

![複数のフロー](media/improve-alm-solutions/solutions-8-multipleflows.png "複数のフロー")

## <a name="exporting-your-solution"></a>ソリューションのエクスポート

ALM の重要な特徴は、最初にサンドボックスまたはテスト環境でフローが動作することを検証した後、単一のアクションで、フローを実稼働環境に移動できることです。 ソリューションをエクスポートするには、**ソリューション** エクスペリエンスでソリューションを探し、**…** を選択し、**エクスポート**を選択した後、**アンマネージドとして**を選択します。

![エクスポート](media/improve-alm-solutions/solutions-9-export.png "エクスポート")

**アンマネージドとして**を選択すると、ローカルにダウンロードして保存できる zip ファイルが用意されます。

## <a name="importing-your-solution"></a>ソリューションのインポート

ソリューションをエクスポートすると、実稼働環境などの別の環境にソリューションをインポートできるようになります。 環境ピッカーで実稼働環境を選択すると、**インポート**を選択することでパッケージのインポートを選択できます。

![インポート](media/improve-alm-solutions/solutions-10-import.png "インポート")

ソリューション パッケージを**参照**して選択し、ウィザードを完了してソリューションを読み込む必要があります。

![パッケージの選択](media/improve-alm-solutions/solutions-11-selectpackage.png "パッケージの選択")

インポート プロセスが完了すると、新しい環境内に展開されたソリューションが表示されます。

![インポートされた新しいソリューション](media/improve-alm-solutions/solutions-12-newsolution.png "インポートされた新しいソリューション")

## <a name="configuring-and-enabling-your-solution"></a>ソリューションの構成と有効化

ソリューションをインポートした後は、実行する必要があるアクティビティがいくつかあります。

- インポートした各フローについて、トリガーとアクションに対する接続を設定する必要があります。

  ![接続](media/improve-alm-solutions/solutions-13-connections.png "接続")

- 既定では、インポートされたフローはまだ接続を確立する必要があるため、無効な状態になっています。 接続を確立してフローを保存すると、フローがアクティブになります。

  > [!NOTE]
  > アクティブになっているフローに変更を保存することはできません。 先に、ソリューション エクスペリエンスまたはフロー作成ポータルでフローをオフにして、フローを非アクティブにする必要があります。