---
title: Dynamics 365 Remote Assistの 2019 年 3 月更新プログラムでは、Dynamics 365 for Field Service の統合が改善されています。
description: Dynamics 365 Remote Assistの 2019 年 3 月更新プログラムでは、Dynamics 365 for Field Service の統合が改善されています。
author: MatthewJonPaul
ms.date: 03/12/2019
ms.topic: article
ms.service: business-applications
ms.author: mapau
ms.reviewer: v-brycho
ms.openlocfilehash: 38cc62940c408a0b0696b549ae504a270a1b25db
ms.sourcegitcommit: b159c2b409bf6789dd7b87594f72a64f504668ae
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/12/2019
ms.locfileid: "835099"
---
# <a name="improved-integration-with-dynamics-365-for-field-service"></a>Dynamics 365 for Field Service との統合の改善

リモート アシストに対する最新の更新プログラムにより、リモート アシストを Dynamics 365 for Field Service と共に使用するフィールド サービス技術者は次のことができるようになります。

- 予約状態を表示および更新する 

- リモート アシストの通話情報を自動的にログ記録する 

- Mixed Reality 画像を予約にキャプチャする

## <a name="view-and-update-booking-status"></a>予約状態を表示および更新する 

リモート アシストのユーザーは、現在の日付に予定されている複数の予約を表示して選択できるようになりました。 予約は、アクティブな予約、今後の予約、完了した予約に分類されます。

![アクティブな予約、今後の予約、完了した予約](media/bookings-for-today.PNG "アクティブな予約、今後の予約、完了した予約")

予約の状態を変更するには、予約を開き、現在の状態の横にあるドロップダウンリストで新しい状態を選択して、**保存**を選択します。 状態の選択項目には、Dynamics 365 for Field Service で使用できるすべての状態値が含まれています。 管理者が状態値の追加や名前変更を行うこともできます。

![状態の選択項目](media/status-drop-down.PNG "状態の選択項目")

## <a name="automatically-log-remote-assist-call-information"></a>リモート アシストの通話情報を自動的にログ記録する 

リモート アシストの通話情報が予約と共に自動的にログ記録されるため、サービス技術者の貴重な時間を節約できます。

![記録された通話情報](media/recorded-call-info.PNG "記録された通話情報")

次の情報が自動的にキャプチャされます。

- 通話の参加者

- 通話が開始された日時

- 通話の種類 (着信または発信)

- 通話時間

- 通話に関連する資産 (写真)

## <a name="capture-mixed-reality-images-in-a-booking"></a>Mixed Reality 画像を予約にキャプチャする

リモート アシストのユーザーは、通話内の Mixed Reality 画像を**カメラ** ![カメラ ボタン](media/camera-button.PNG "カメラ ボタン") ボタンを選択してキャプチャできます。 画像は OneDrive または予約に保存できます。

![保存の選択項目](media/save-image.PNG "保存の選択項目")

予約ウィンドウの右下隅にある**資産**の下に、保存した画像のサムネイルが表示されます。

![画像のサムネイル](media/saved-image.PNG "画像のサムネイル")

リモート アシストを Dynamics 365 for Field Service と共に使用する方法の詳細については、次のトピックを参照してください。

- [リモート アシスト ユーザー ガイド](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/user-guide)

- [Field Service 統合のトラブルシューティング](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/troubleshoot-field-service)
