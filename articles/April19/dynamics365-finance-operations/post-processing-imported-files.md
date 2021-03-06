---
title: 電子申告 - インポートされたファイルの後処理
description: 電子申告のインポート機能は、フォルダーを使用して次に処理するファイル セットを取得します。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: ed68377e31862e792b5cdf3e4ee98b7bb3dcca4e
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225258"
---
#  <a name="electronic-reporting---post-processing-of-imported-files"></a>電子申告 - インポートされたファイルの後処理
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


電子申告 (ER) のインポート機能は、SharePoint のフォルダーを使用して次に処理するファイル セットを取得します。 現在のところ、処理されたファイルを自動的に管理する手順はありません。たとえば、正常に処理されたファイルは自動的に SharePoint のソース フォルダーから削除され、別の場所に移動することはできません。 これにより、手動での作業が追加で発生し、エラーを招く可能性があります。 この機能はこの手順を自動化し、後処理のアクションを構成できます。 ER の形式のソース設定を変更することで、ユーザーは次のアクションを構成できます。

- 正常に処理されたファイルの場合:
  - ファイルを SharePoint のソース フォルダーから削除する
  - ファイルを SharePoint の別のフォルダーに移動する
- 警告ありで処理されたファイルの場合:
  - ファイルを SharePoint のソース フォルダーに保持する
  - ファイルを SharePoint の別のフォルダーに移動する
- 失敗したファイルの場合:
  - ファイルを SharePoint のソース フォルダーに保持する
  - ファイルを SharePoint の別のフォルダーに移動する

![SharePoint のソース設定](media/ER-post-process.png "SharePoint のソース設定")  
