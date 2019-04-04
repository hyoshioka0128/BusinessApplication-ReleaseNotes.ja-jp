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
# <a name="improved-integration-with-dynamics-365-for-field-service"></a><span data-ttu-id="30e16-103">Dynamics 365 for Field Service との統合の改善</span><span class="sxs-lookup"><span data-stu-id="30e16-103">Improved integration with Dynamics 365 for Field Service</span></span>

<span data-ttu-id="30e16-104">リモート アシストに対する最新の更新プログラムにより、リモート アシストを Dynamics 365 for Field Service と共に使用するフィールド サービス技術者は次のことができるようになります。</span><span class="sxs-lookup"><span data-stu-id="30e16-104">With the latest updates to Remote Assist, field service technicians using Remote Assist with Dynamics 365 for Field Service can:</span></span>

- <span data-ttu-id="30e16-105">予約状態を表示および更新する</span><span class="sxs-lookup"><span data-stu-id="30e16-105">View and update booking status</span></span> 

- <span data-ttu-id="30e16-106">リモート アシストの通話情報を自動的にログ記録する</span><span class="sxs-lookup"><span data-stu-id="30e16-106">Automatically log Remote Assist call information</span></span> 

- <span data-ttu-id="30e16-107">Mixed Reality 画像を予約にキャプチャする</span><span class="sxs-lookup"><span data-stu-id="30e16-107">Capture mixed-reality images in a booking</span></span>

## <a name="view-and-update-booking-status"></a><span data-ttu-id="30e16-108">予約状態を表示および更新する</span><span class="sxs-lookup"><span data-stu-id="30e16-108">View and update booking status</span></span> 

<span data-ttu-id="30e16-109">リモート アシストのユーザーは、現在の日付に予定されている複数の予約を表示して選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="30e16-109">Remote Assist users can now view and select from multiple bookings scheduled for the current day.</span></span> <span data-ttu-id="30e16-110">予約は、アクティブな予約、今後の予約、完了した予約に分類されます。</span><span class="sxs-lookup"><span data-stu-id="30e16-110">The bookings are categorized by active, upcoming, and completed bookings.</span></span>

<span data-ttu-id="30e16-111">![アクティブな予約、今後の予約、完了した予約](media/bookings-for-today.PNG "アクティブな予約、今後の予約、完了した予約")</span><span class="sxs-lookup"><span data-stu-id="30e16-111">![Active, upcoming, and completed bookings](media/bookings-for-today.PNG "Active, upcoming, and completed bookings")</span></span>

<span data-ttu-id="30e16-112">予約の状態を変更するには、予約を開き、現在の状態の横にあるドロップダウンリストで新しい状態を選択して、**保存**を選択します。</span><span class="sxs-lookup"><span data-stu-id="30e16-112">To change the status of a booking, open the booking, select the drop-down list next to the current status, select a new status, and then select **Save**.</span></span> <span data-ttu-id="30e16-113">状態の選択項目には、Dynamics 365 for Field Service で使用できるすべての状態値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="30e16-113">Status selections include any of the status values available in Dynamics 365 for Field Service.</span></span> <span data-ttu-id="30e16-114">管理者が状態値の追加や名前変更を行うこともできます。</span><span class="sxs-lookup"><span data-stu-id="30e16-114">Administrators can also add or rename status values.</span></span>

<span data-ttu-id="30e16-115">![状態の選択項目](media/status-drop-down.PNG "状態の選択項目")</span><span class="sxs-lookup"><span data-stu-id="30e16-115">![Status selections](media/status-drop-down.PNG "Status selections")</span></span>

## <a name="automatically-log-remote-assist-call-information"></a><span data-ttu-id="30e16-116">リモート アシストの通話情報を自動的にログ記録する</span><span class="sxs-lookup"><span data-stu-id="30e16-116">Automatically log Remote Assist call information</span></span> 

<span data-ttu-id="30e16-117">リモート アシストの通話情報が予約と共に自動的にログ記録されるため、サービス技術者の貴重な時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="30e16-117">Remote Assist call information is automatically logged with the booking, which saves valuable time for service technicians:</span></span>

<span data-ttu-id="30e16-118">![記録された通話情報](media/recorded-call-info.PNG "記録された通話情報")</span><span class="sxs-lookup"><span data-stu-id="30e16-118">![Recorded call information](media/recorded-call-info.PNG "Recorded call information")</span></span>

<span data-ttu-id="30e16-119">次の情報が自動的にキャプチャされます。</span><span class="sxs-lookup"><span data-stu-id="30e16-119">The following information is automatically captured:</span></span>

- <span data-ttu-id="30e16-120">通話の参加者</span><span class="sxs-lookup"><span data-stu-id="30e16-120">The participant(s) on the call</span></span>

- <span data-ttu-id="30e16-121">通話が開始された日時</span><span class="sxs-lookup"><span data-stu-id="30e16-121">The day and time the call was started</span></span>

- <span data-ttu-id="30e16-122">通話の種類 (着信または発信)</span><span class="sxs-lookup"><span data-stu-id="30e16-122">The type of call – incoming or outgoing</span></span>

- <span data-ttu-id="30e16-123">通話時間</span><span class="sxs-lookup"><span data-stu-id="30e16-123">Call duration</span></span>

- <span data-ttu-id="30e16-124">通話に関連する資産 (写真)</span><span class="sxs-lookup"><span data-stu-id="30e16-124">Assets related to the call (photo)</span></span>

## <a name="capture-mixed-reality-images-in-a-booking"></a><span data-ttu-id="30e16-125">Mixed Reality 画像を予約にキャプチャする</span><span class="sxs-lookup"><span data-stu-id="30e16-125">Capture mixed-reality images in a booking</span></span>

<span data-ttu-id="30e16-126">リモート アシストのユーザーは、通話内の Mixed Reality 画像を**カメラ** ![カメラ ボタン](media/camera-button.PNG "カメラ ボタン") ボタンを選択してキャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="30e16-126">Remote Assist users can capture mixed-reality images in the call by selecting the **Camera** ![Camera button](media/camera-button.PNG "Camera button") button.</span></span> <span data-ttu-id="30e16-127">画像は OneDrive または予約に保存できます。</span><span class="sxs-lookup"><span data-stu-id="30e16-127">Save images to OneDrive or to the booking.</span></span>

<span data-ttu-id="30e16-128">![保存の選択項目](media/save-image.PNG "保存の選択項目")</span><span class="sxs-lookup"><span data-stu-id="30e16-128">![Save choices](media/save-image.PNG "Save choices")</span></span>

<span data-ttu-id="30e16-129">予約ウィンドウの右下隅にある**資産**の下に、保存した画像のサムネイルが表示されます。</span><span class="sxs-lookup"><span data-stu-id="30e16-129">The saved image thumbnails appear under **Assets** in the lower-right corner of the booking pane.</span></span>

<span data-ttu-id="30e16-130">![画像のサムネイル](media/saved-image.PNG "画像のサムネイル")</span><span class="sxs-lookup"><span data-stu-id="30e16-130">![Image thumbnails](media/saved-image.PNG "Image thumbnails")</span></span>

<span data-ttu-id="30e16-131">リモート アシストを Dynamics 365 for Field Service と共に使用する方法の詳細については、次のトピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="30e16-131">For more information on using Remote Assist with Dynamics 365 for Field Service, see the following topics:</span></span>

- [<span data-ttu-id="30e16-132">リモート アシスト ユーザー ガイド</span><span class="sxs-lookup"><span data-stu-id="30e16-132">Remote Assist User Guide</span></span>](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/user-guide)

- [<span data-ttu-id="30e16-133">Field Service 統合のトラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="30e16-133">Troubleshoot Field Service integration</span></span>](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/troubleshoot-field-service)
