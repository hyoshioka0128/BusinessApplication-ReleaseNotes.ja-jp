---
title: 電子申告 - 法人別のパラメーターの設定
description: 現時点では、電子申告の構成でデータをフィルター処理するために、法人固有の値を設定する機能はありません。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: af21632089dc16587e2e5dd9840673dc45fc13ac
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "286770"
---
#  <a name="electronic-reporting---setting-up-parameters-by-legal-entity"></a>電子申告 - 法人別のパラメーターの設定
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

電子申告の構成では、多くの場合、各法人に固有の値セットに基づいてデータをフィルター処理する必要があります。 現在のところ、パワー ユーザーは、構成済みの電子申告 (ER) モデル マッピングか、ER 形式の一部としてのみ、このようなデータセットを指定できます。 そのため、この種の ER 構成は、特定の Microsoft Dynamics 365 for Finance and Operations インスタンスの設定に依存するものとなっています。その結果、この種の ER 構成やその抽出コピーを配布したり、それらをさらにメンテナンスするには、複雑な作業が伴います。

この構成固有のパラメーター機能を使用すると、パワーユーザーは ER 形式内で抽象データ ソースを構成し、そのデータ ソースがビジネス ユーザーによってどのように入力されるかを指定することができます。

-   このデータ ソースを入力したビジネス ユーザーの要求に対して、どのようなデータが提供されるのか。
-   このデータ ソースによって、実行時にどのような種類の値が ER 形式に返されるのか。

![形式デザイナー: 課税 XML 要素](media/ER-setup-parameters-designer.png "形式デザイナー: 課税 XML 要素")

このデータ ソースを使用することで、パワー ユーザーはデータ ソースに関連する実際の法人を参照することなく、法人非依存のルールとして、ER 形式内にデータ フィルター処理を構成することができます。

![形式デザイナーのマッピングのスクリーンショット](media/ER-setup-parameters-datasource.png "形式デザイナーのマッピングのスクリーンショット")

この機能を使用すると、ビジネス ユーザーは Finance and Operations のユーザー インターフェイスで、ER 形式固有の会社マスター データを設定することができます。

![アプリケーション固有のパラメーター: 条件画面 1](media/ER-setup-parameters-UI.png "アプリケーション固有のパラメーター: 条件画面 1")

これは、対応する ER 形式の実行を制御する可能性がある、任意の法人に対して行うことができます。

![アプリケーション固有のパラメーター: 条件画面 2](media/ER-setup-parameters-UI-screen-2.png "アプリケーション固有のパラメーター: 条件画面 2")

ER 形式の実行中は、その実行を制御している法人に応じて、ER 形式の対応するデータ ソースにより、法人固有のマスター データのセットが使用されます。

この機能では、ビジネス ユーザーが 1 つの Finance and Operations インスタンスから ER 形式固有の会社マスター データをエクスポートし、それを別のインスタンスにインポートすることもできます。

