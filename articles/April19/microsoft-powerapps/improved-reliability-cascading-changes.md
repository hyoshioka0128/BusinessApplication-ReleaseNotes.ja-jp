---
title: カスケード変更の信頼性の向上
description: 多数のレコードに影響を与えるカスケード変更は、バックグラウンドで処理されます。 これにより、UI との対話がより迅速にユーザーに返され、データベース タイムアウトが減少し、大規模なカスケード実行の成功率が向上します。
author: ''
ms.reviewer: ''
ms.date: 09/06/2019
ms.assetid: bad86458-45a7-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: nhelgren
audience: Power user
ms.openlocfilehash: 84053e220105156b75d013aaaec90c774a07e068
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994292"
---
# <a name="improved-reliability-of-cascading-changes-public-preview"></a>カスケード変更の信頼性の向上 (パブリック プレビュー)



100 を超えるレコードに影響するカスケード変更 (割り当て、削除) は、バックグラウンドで非同期に処理されます。 これにより、ユーザーは UI との対話をより早く再開でき、カスケード変更を処理するときの UI とデータベースのタイムアウトが削減されます。 これらの変更をバックグラウンドで処理すると、多数のレコードが関係する場合に成功率が高くなり、システムで実行されている他のプロセスが変更によってブロックされるのを防ぐことができます。 

最初の変更が行われてからすべてのレコードが処理されるまでに遅延があります。 遅延期間は、処理されたレコードの数に基づきます。 バックグラウンド処理のステータスは、**ジョブ** リストを使用して組織の**設定**で表示できます。
