---
title: 製品バリアントの測定単位換算
description: 以前は、製品バリアント レベルでの測定単位 (UoM) の換算は、特定の倉庫管理シナリオのセットでのみサポートされていました。 この機能が、アプリケーション全体の製品バリアント レベルでの UoM 変換をサポートするように拡張されました。
author: sorenva
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: sorenand
ms.openlocfilehash: 0cfb6b4f9b64afa2303e3da434ed3d695a752f78
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287950"
---
#  <a name="unit-of-measure-conversions-for-product-variants"></a>製品バリアントの測定単位換算
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



以前は、製品バリアント レベルでの測定単位 (UoM) の換算は、特定の倉庫管理シナリオのセットでのみサポートされていました。 この機能が、アプリケーション全体の製品バリアント レベルでの UoM 変換をサポートするように拡張されました。

製品バリアントを使用すると、個別のメンテナンスが必要な製品を複数作成する代わりに、製品のバリエーションを作成することができます。 たとえば、製品バリアントによって、特定のサイズや色の T シャツを作成することもできます。 これまで、単位換算は製品マスターに対してしか設定できなかったので、製品バリアントにはすべて同じ単位換算ルールが適用されていました。 たとえば、T シャツが箱で販売されている場合、箱に収まる T シャツの数が T シャツのサイズによって異なる場合は、この新しい機能を使用することで、Tシャツの各サイズと、包装に使われる箱との間の単位変換を設定することができます。

この機能の一般的な使用は、**製品情報管理パラメーター** ページで有効化します。 この機能は、すべての製品マスターに対して有効にすることもできますし、倉庫プロセス用に有効化されている製品マスターに対してのみ有効化することもできます。

![[製品情報管理パラメーター] ページで製品バリアントによる測定単位換算を有効にする](media/uom-setup-1.png "[製品情報管理パラメーター] ページで製品バリアントによる測定単位換算を有効にする")

特定の製品マスターの場合は、**製品詳細**ページの**測定単位換算の有効化**フィールドをオンにして機能を有効化します。

![[製品詳細] ページで特定の製品マスターの製品バリアントによる測定単位換算を有効にする](media/uom-setup-2.png "[製品詳細] ページで特定の製品マスターの製品バリアントによる測定単位換算を有効にする")

この例では、T シャツに 3 つの製品バリアントがリリースされています (Large、Medium、Small)。

![T シャツの 3 つのバリアント (Large、Medium、Small) が表示された [リリース済製品バリアント] ページ](media/uom-setup-3.png "T シャツの 3 つのバリアント (Large、Medium、Small) が表示された [リリース済製品バリアント] ページ")

製品マスターから、**単位換算**ページを開くことができます。 このページではまず、単位換算を製品に対して設定するのか、それとも製品バリアントに対して設定するのかを選択します。 

![[単位変換] ページで、単位変換を製品バリアントに対して設定するのか、それとも製品マスターに対して設定するのかを選択する](media/uom-setup-4.png "[単位変換] ページで、単位変換を製品バリアントに対して設定するのか、それとも製品マスターに対して設定するのかを選択する")

**製品バリアント**を選択した場合は、特定の製品バリアントに対して単位変換が設定されます。 この例では、単位 "Box" と単位 "Ea" の間の単位換算が、Small サイズのＴシャツに対して設定されます。 

**製品**を選択した場合は、製品マスターに対して単位換算が設定されます。この単位換算は、単位換算が定義されていないすべての製品バリアントのフォールバックとして機能します。

![単位変換ページで製品マスターのフォールバック測定単位変換を定義する](media/uom-setup-5.png "単位変換ページで製品マスターのフォールバック測定単位変換を定義する")