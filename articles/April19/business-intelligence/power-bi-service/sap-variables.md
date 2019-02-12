---
title: SAP 変数
description: DirectQuery を介した SAP BW 変数と SAP HANA 変数へのインポートまたは接続のサポートを追加します。
author: AdamDWilson
ms.date: 01/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: adamw
ms.openlocfilehash: ba4f44f6b3336518770f0a65fac9ab5fa27d2bf9
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210992"
---
# <a name="support-for-sap-variables"></a>SAP 変数のサポート

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

Power BI は、SAP Business Warehouse (BW) と SAP HANA の両方への接続をサポートします。
通常、使用されている SAP BW オブジェクトや SAP HANA オブジェクトには変数やパラメーターが定義されています。 たとえば、SAP BW Infocube や SAP HANA の分析ビューで国や年に対して変数が定義されていると、利用できるデータが選択した国や年に限定されます。 このような変数は、SAP BW や SAP HANA のソースで必須またはオプションのいずれかに定義されている可能性があります。 パラメーターの例として、計算に使用される税率を決定する TaxRate というパラメーターが挙げられます。

Power BI Desktop は、データをインポートするときと DirectQuery を使用して接続するときに、このような SAP BW と SAP HANA の両方の変数とパラメーターに対するサポートを追加します。 これにより、レポート作成者が国や年などの値を設定することで、レポートに表示されるデータを選択した国や年に限定できます。 レポート作成者は最初の接続時に値を設定し、必要に応じて後で選択内容を変更できます。

レポートが Power BI サービスに発行された後は、そのレポートで選択した内容は Power BI サービスでは変更できません。
その結果、レポートを開いたすべてのユーザーに、レポート作成者が選択した内容が反映された同じデータが表示されます。

DirectQuery を使用するレポートについては、そのレポートを開いたユーザー自身が変数やパラメーターを選択できる機能を追加することで改善します。 たとえば、あるレポートを 1 人のユーザーは 2018 年のフランスのデータを表示できる一方で、もう一方のユーザーは同じレポートの 2017 年の米国のデータを表示できます。 選択は最新のスライサーのように行うことが可能で、各ユーザーが選択した内容は記憶され、次にそのレポートを開いたときに再利用されます。
