---
title: Microsoft Flow ボタン入力の機能拡張
description: 作成者がボタンの入力をより細かく制御できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/19/2019
ms.assetid: 537e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: f2e712c69038d6b44a46279376d4a002ca1f12d9
ms.sourcegitcommit: d0ae525dc6a82af6449204a4bdb8dc57a04d2b74
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "880720"
---
# <a name="microsoft-flow-button-input-enhancements"></a>Microsoft Flow ボタン入力の機能拡張




ボタンを 1 回タップするだけで実行できることをだれもが望む多くの反復的なタスクがあります。 たとえば、毎日のチーム同期に参加するよう通知するためにチームに迅速に電子メールを送信する必要がある場合や、その日はそれ以上チェックインが予定されていないことが通知された後に新しい Visual Studio Online ビルドを開始することが必要な場合があります。 ボタン フローを使用すると、モバイル デバイスのボタンをタップするだけでこれらのタスクやその他のタスクを実行できます。

ボタンの初期リリースでは、ボタンはテキストのような基本的な入力を受け取ることができました。 しかし、[このアイデア](https://powerusers.microsoft.com/t5/Flow-Ideas/Create-multiple-input-types-for-buttons/idi-p/33695)でカバーされているように、充実したデータをボタン フローに渡すことが求められてきました。 これに対応して、ボタン フローに以下のすべての種類のデータを要求できるようになりました。

- テキスト
- ドロップダウン (ラジオ ボタンなど)
- 電子メール アドレス
- ファイル (携帯電話上の写真など)
- [はい] または [いいえ] のチェック ボックス
- 数値
- 日付 (カレンダー ピッカー付き)

![入力の追加](media/flow-button-enhancements-1.png "入力の追加")

さらに、一部の入力を必須として指定し、他の入力を省略可能として指定することができます。 これは各入力フィールドのアクション メニュー (右側にある **...** ボタン) から行うことができます。 ボタンあたり 5 入力の制限も引き上げました。

![入力を省略可能にする](media/flow-button-enhancements-2.png "入力を省略可能にする")