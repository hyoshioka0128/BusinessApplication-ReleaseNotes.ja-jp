---
title: "編集可能なアクセス許可セット"
description: "エンド ユーザーがアクセス許可セットを編集できるようになります"
author: bnielse
manager: edupont04
ms.date: 11/07/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: cdbe692282951665ec1a0d55010d4adbeddb1cba
ms.openlocfilehash: d402e30454de93e061c6923d9b8d22596d4e8bbd
ms.contentlocale: ja-jp
ms.lasthandoff: 11/07/2018

---

# <a name="permission-sets-are-editable"></a>アクセス許可セットを編集可能

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

顧客には Business Central でユーザーが実行できる必要があることについての独自の定義が存在することがよくあり、これらの定義が定義済みのアクセス許可セットと一致していないことがあります。 これに対処するため、アクセス許可セットを編集可能にして、追加、削除、変更できるようにしました。

アクセス許可セットのリストからは、新しいアクセス許可を追加したり、既存のアクセス許可セットをコピーしたりできます。 結果セットの種類はユーザー定義になります。 既存のアクセス許可セットをコピーする場合は、元のアクセス許可セットが変更されたら通知を受け取ることを選択できるので、必要に応じてカスタマイズ セットを更新できます。  

![](media/editablepermissionsets_list.png "必要なアクセス許可セットを追加する。")

さらに、アクセス許可セットの定義を含むファイル (パートナー提供のファイルや、別の会社からコピーされたファイルなど) をインポートしたり、RapidStart を使用してアクセス許可セットを追加したりすることもできます。

# <a name="overview-of-effective-permissions-for-a-user"></a>ユーザーに対する有効なアクセス許可の概要

セットアップとトラブルシューティングでは、ユーザーのアクセス許可がどこから付与され、ユーザーの資格 (ライセンス) によって何に対するアクセス権が与えられるのかについての情報が必要です。

各ユーザー カードからの [有効なアクセス許可] ウィンドウには、ユーザーが持っているアクセス許可と、付与に使用されるアクセス許可セット (権利、既定のセット (システム)、またはカスタマイズ セット (ユーザー定義) のいずれか) が表示されます。 ここでは、ユーザー定義の種類のアクセス許可セットを変更することもできます。  

> [!NOTE]
> アクセス許可セットを編集すると、アクセス許可セットが割り当てられている他のユーザーにも変更内容が適用されます。

![](media/effective_permission_sets.png "有効なアクセス許可の概要。")

## <a name="resources"></a>リソース
[ユーザーとアクセス許可の管理](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-how-users-permissions)

<!--
### Who uses this feature
End users, admins, customizers, developers, IT pros
## Status
### Availability
Cloud, On-premises, Hybrid
### Regional availability
No regional restrictions. All Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。

