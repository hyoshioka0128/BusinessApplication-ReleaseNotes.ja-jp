---
title: "Visual Studio Code AL エクスペリエンスの向上"
description: "Visual Studio Code AL エクスペリエンスの改善"
author: pborring
manager: edupont04
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: pborring
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 161da5108c31c88f8e0f254abcf0f4b0fa6e950c
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="improved-visual-studio-code-al-experience"></a><span data-ttu-id="3e32c-103">Visual Studio Code AL エクスペリエンスの向上</span><span class="sxs-lookup"><span data-stu-id="3e32c-103">Improved Visual Studio Code AL experience</span></span>

[!include[banner](../../includes/banner.md)]

<span data-ttu-id="3e32c-104">拡張機能を作成することは、Business Central をカスタマイズするための手段です。</span><span class="sxs-lookup"><span data-stu-id="3e32c-104">Creating extensions is the way to customize Business Central.</span></span> <span data-ttu-id="3e32c-105">2018 年 10 月リリースでは、開発エクスペリエンスの生産性が強化されたほか、追加の拡張シナリオもサポートされました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-105">The October '18 release adds productivity enhancements to the development experience as well as support for additional extension scenarios.</span></span>

<span data-ttu-id="3e32c-106">強化されたツールや拡張機能を使用することで、開発者はソリューションの開発やトラブルシューティングを行う際の生産性を高めると共に、拡張機能を通じて顧客のカスタマイズ要件に柔軟に対応できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-106">With the enhancements to the tooling and extension capabilities, developers can be more productive when developing and troubleshooting solutions, and will have more options to meet customers' customization requirements using extensions.</span></span>

## <a name="sandbox-with-production-data"></a><span data-ttu-id="3e32c-107">運用データを使用したサンドボックス</span><span class="sxs-lookup"><span data-stu-id="3e32c-107">Sandbox with production data</span></span>
<span data-ttu-id="3e32c-108">サンドボックスを使用する際 (特にテストやトラブルシューティングを行う際) には、運用データを使用できたほうが望ましい場合がよくあります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-108">A common scenario when working with sandboxes, especially when testing or troubleshooting, is the wish to have production data available.</span></span> <span data-ttu-id="3e32c-109">今回のリリースでは、クラウドにバックアップされた運用データの最新のコピーに基づいてサンドボックスを作成できる機能が追加されます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-109">With this release, we add the ability to create a sandbox based on a copy of the latest cloud backup of the production data.</span></span> <span data-ttu-id="3e32c-110">運用データで設定されている統合とのクロストークを最小限に抑えるため、これらの統合はサンドボックスの作成時に無効化されます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-110">To minimize cross-talk with integrations set up in the production data, these integrations will be disabled when the sandbox is created.</span></span> <span data-ttu-id="3e32c-111">管理者ユーザーは、必要な注意を払ったうえで、これらの統合を必要に応じて有効化したり、再構成したりして、サンドボックスの使用目的に対応することができます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-111">Using caution, admin users can enable or reconfigure these integrations as required to support the intended sandbox use.</span></span>

## <a name="new-object-extensions"></a><span data-ttu-id="3e32c-112">新しいオブジェクト拡張</span><span class="sxs-lookup"><span data-stu-id="3e32c-112">New object extensions</span></span>
<span data-ttu-id="3e32c-113">次のオブジェクトを拡張できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-113">You can now extend the following:</span></span>

- <span data-ttu-id="3e32c-114">ベース アプリケーションからの列挙 (オプション)。拡張可能な列挙型を拡張機能内で新たに作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-114">Enums (options) from the base application as well as create new, extensible enums in your extensions.</span></span>
- <span data-ttu-id="3e32c-115">拡張機能内のレポート データ セット。</span><span class="sxs-lookup"><span data-stu-id="3e32c-115">Report data sets in extensions.</span></span> <span data-ttu-id="3e32c-116">レポート データのレイアウトは、引き続き置換での対応となります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-116">Report data layouts are still a replacement story.</span></span>
- <span data-ttu-id="3e32c-117">フィールド グループ。</span><span class="sxs-lookup"><span data-stu-id="3e32c-117">Field groups.</span></span>

## <a name="event-discoverability"></a><span data-ttu-id="3e32c-118">イベントの見つけやすさ</span><span class="sxs-lookup"><span data-stu-id="3e32c-118">Event discoverability</span></span>
<span data-ttu-id="3e32c-119">拡張機能を作成するうえで、イベントのサブスクライブは重要な操作となります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-119">A core aspect of creating extensions is to subscribe to events.</span></span> <span data-ttu-id="3e32c-120">しかし、特定のユーザー フローでどのイベントが使用できるかを把握することは、多くの開発者にとって共通の課題です。</span><span class="sxs-lookup"><span data-stu-id="3e32c-120">However, a common challenge is understanding which events are available in a given user flow.</span></span> <span data-ttu-id="3e32c-121">デバッグは有効な手段ですが、既にサブスクライブされているイベントしか確認できません。</span><span class="sxs-lookup"><span data-stu-id="3e32c-121">Debugging can help, but will only show events already being subscribed to.</span></span> <span data-ttu-id="3e32c-122">そこで、イベントや拡張ポイントを見つけやすくするために、クライアントに新しいイベント トレーサーが追加されました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-122">To aid in the discoverability of events and extension points, there is a new event tracer in the client.</span></span> <span data-ttu-id="3e32c-123">これを使用すると、ユーザー フローを記録して、発生したイベントをリストすることができます。これにより開発者は、イベントのサブスクライバー コードを生成して、AL コードに簡単にコピーできるようになります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-123">With this, a user flow can be recorded to list events that are raised, and the developer can have subscriber code for the event generated for easy copy into AL code.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-124">![イベント トレーサー](media/Event-tracer.png "イベント トレーサー")</span><span class="sxs-lookup"><span data-stu-id="3e32c-124">![Event tracer](media/Event-tracer.png "Event tracer")</span></span>

<span data-ttu-id="3e32c-125">また、新しいイベントも多数追加され、より多くの場所での拡張が可能になりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-125">Furthermore, a large number of new events has been added, making it possible to extend in more places.</span></span>

## <a name="visual-studio-code-al-extension-enhancements"></a><span data-ttu-id="3e32c-126">Visual Studio Code AL Extension の機能強化</span><span class="sxs-lookup"><span data-stu-id="3e32c-126">Visual Studio Code AL Extension enhancements</span></span>
<span data-ttu-id="3e32c-127">バージョニング チェックと下位互換性が提供されたことで、お客様は Visual Studio Code マーケットプレースから AL 言語の拡張機能をインストールし、それを使用してさまざまなプラットフォーム用のソリューションを開発できるようになりました (クラウド サンドボックス、Business Central 2018 年 4 月リリース、Business Central 2018 年 10 月リリース、および今後のバージョンを含む) 。</span><span class="sxs-lookup"><span data-stu-id="3e32c-127">With versioning check and backward compatibility, you can now install the AL Language extension from the Visual Studio Code marketplace and use it to develop solutions for many different platforms, including cloud sandboxes, Business Central April 2018 release, Business Central October 2018 release, and future versions.</span></span> <span data-ttu-id="3e32c-128">コンパイラは、接続されたテナントに互換性があることを確認し、新しい app.json プロパティで設定されたターゲット プラットフォームに対してコンパイルを実行します。</span><span class="sxs-lookup"><span data-stu-id="3e32c-128">The compiler will check that the connected tenant is compatible, and compile against the target platform as set in the new app.json property.</span></span>

<span data-ttu-id="3e32c-129">また、多数のオブジェクト拡張やファイルを含んだ大規模なプロジェクトを使用する際の、AL 拡張機能の高速性と応答性も改善されました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-129">Also, the AL extension is now faster and more responsive when working with larger projects containing many object extensions/files.</span></span>

## <a name="debugger-enhancements"></a><span data-ttu-id="3e32c-130">デバッガーの機能拡張</span><span class="sxs-lookup"><span data-stu-id="3e32c-130">Debugger enhancements</span></span>
<span data-ttu-id="3e32c-131">レガシーの Dynamics NAV デバッガーのように、一般的な Break on Error と Break on Write を使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-131">Just like in the legacy Dynamics NAV debugger, you can now use the common Break on Error, as well as Break on Write.</span></span> <span data-ttu-id="3e32c-132">ベース アプリケーション コード内の定義に移動して、ブレークポイントを設定することもできます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-132">You can also go to definition in the base application code and set breakpoints there.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-133">![ベース アプリケーション コードの定義に移動する (F12)](media/Go-to-definition-F12.gif "ベース アプリケーション コードの定義に移動する (F12)")</span><span class="sxs-lookup"><span data-stu-id="3e32c-133">![F12 Go to Definition for base application code](media/Go-to-definition-F12.gif "F12 Go to Definition for base application code")</span></span>

## <a name="intellisense-enhancements"></a><span data-ttu-id="3e32c-134">IntelliSense の機能拡張</span><span class="sxs-lookup"><span data-stu-id="3e32c-134">IntelliSense enhancements</span></span>
<span data-ttu-id="3e32c-135">AL 内のすべてのプロパティ (ホバーと IntelliSense の両方) で、関連するオンライン ドキュメントにリダイレクトするためのヘルプ リンクが提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-135">All properties in AL, both on hover and in IntelliSense, now have Help links that redirect you to the related online documentation.</span></span> <span data-ttu-id="3e32c-136">また、AL 言語の構成要素に関するドキュメントが自動生成されるようになり、それらをオンライン リファレンス ドキュメントと IntelliSense の両方に使用できるようになったことで、ドキュメントの最新性と統一性を維持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-136">Furthermore, the documentation for AL language constructs is autogenerated and used for both online reference documentation and IntelliSense, ensuring up-to-date and aligned documentation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-137">![IntelliSense からのヘルプ リンク](media/Help-link-from-IntelliSense.gif "IntelliSense からのヘルプ リンク")</span><span class="sxs-lookup"><span data-stu-id="3e32c-137">![Help link from IntelliSense](media/Help-link-from-IntelliSense.gif "Help link from IntelliSense")</span></span>

<span data-ttu-id="3e32c-138">拡張機能での画像プロパティの提示機能では、現在のコンテキストで使用できるものだけが提示されるようになりました。現在のコンテキストで使用できない画像については警告が表示されます。ユーザーは、IntelliSense とホバーを使用して画像をプレビューできます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-138">Suggestions for Image properties in an extension now only propose the ones that can be used in the current context, displaying a warning for images that cannot be used in the current context, and you can preview images when using IntelliSense and on-hover.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-139">![IntelliSense での画像の選択とプレビュー](media/IntelliSense-Preview-Images.gif "IntelliSense での画像の選択とプレビュー")</span><span class="sxs-lookup"><span data-stu-id="3e32c-139">![Select and preview images with IntelliSense](media/IntelliSense-Preview-Images.gif "Select and preview images with IntelliSense")</span></span>

## <a name="working-with-permissions"></a><span data-ttu-id="3e32c-140">アクセス許可の操作</span><span class="sxs-lookup"><span data-stu-id="3e32c-140">Working with permissions</span></span>
<span data-ttu-id="3e32c-141">アクセス許可を操作しやすくするため、クライアントを使用して、アクセス許可セットをアプリケーションからエクスポートし、それらを Visual Studio Code AL Extension にインポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-141">To make working with permissions easier, it is now possible to export permission sets from the application, using the client, and import these into the Visual Studio Code AL Extension.</span></span> <span data-ttu-id="3e32c-142">拡張機能内のオブジェクト用に使用する新しいアクセス許可ファイルは、Visual Studio Code AL プロジェクト内から生成することもできます。</span><span class="sxs-lookup"><span data-stu-id="3e32c-142">New permission files for the objects in an extension can also be generated from within the Visual Studio Code AL project.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-143">![拡張機能オブジェクト用のアクセス許可ファイルを生成するための Visual Studio Code AL コマンド](media/Permissions-AL-command.png "拡張機能オブジェクト用のアクセス許可ファイルを生成するための Visual Studio Code AL コマンド")</span><span class="sxs-lookup"><span data-stu-id="3e32c-143">![Visual Studio Code AL command for generating permissions file for extension objects](media/Permissions-AL-command.png "Visual Studio Code AL command for generating permissions file for extension objects")</span></span>

## <a name="net-interop"></a><span data-ttu-id="3e32c-144">.NET 相互運用機能</span><span class="sxs-lookup"><span data-stu-id="3e32c-144">.NET Interop</span></span>
<span data-ttu-id="3e32c-145">オンプレミス展開を対象とした Business Central ソリューションを取り扱う場合に、.NET相互運用機能を AL コード内に追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-145">When working with Business Central solutions that target on-premises deployments, you can now add .NET Interop in AL code.</span></span> <span data-ttu-id="3e32c-146">ただしその場合、後からソリューションをクラウドへ移行するには、.NET 相互運用機能を置き換えなければならなくなります。</span><span class="sxs-lookup"><span data-stu-id="3e32c-146">Note that this implies that the solution cannot be moved to the cloud later without replacing the .NET Interop.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-147">![オンプレミス AL 内の .NET 相互運用機能](media/DotNet-interop.png "オンプレミス AL 内の .NET 相互運用機能")</span><span class="sxs-lookup"><span data-stu-id="3e32c-147">![.NET Interop in on-premises AL](media/DotNet-interop.png ".NET Interop in on-premises AL")</span></span>

## <a name="translation-enhancements"></a><span data-ttu-id="3e32c-148">翻訳の機能強化</span><span class="sxs-lookup"><span data-stu-id="3e32c-148">Translation enhancements</span></span>
<span data-ttu-id="3e32c-149">特定の文字列が適用されるオブジェクトや要素を記述した新しいコンテキスト情報が、生成後の XLIFF 翻訳ファイルに追加されました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-149">New contextual information that describes which object and element a given string applies to has been added to the generated XLIFF translation files.</span></span> <span data-ttu-id="3e32c-150">これにより、文字列が UI のどこに表示されるのかを翻訳者が把握しやすくなり、翻訳の品質が向上します。</span><span class="sxs-lookup"><span data-stu-id="3e32c-150">This helps translators get a better overview of where a string is displayed in the UI, thereby increasing the quality of the translation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="3e32c-151">![XLIFF 翻訳ファイルの note タグ](media/xliff-note.png "XLIFF 翻訳ファイルの note タグ")</span><span class="sxs-lookup"><span data-stu-id="3e32c-151">![XLIFF translation file note tag](media/xliff-note.png "XLIFF translation file note tag")</span></span>

## <a name="odata-bound-actions-in-al"></a><span data-ttu-id="3e32c-152">AL 内での OData バインド アクション</span><span class="sxs-lookup"><span data-stu-id="3e32c-152">OData-bound actions in AL</span></span>
<span data-ttu-id="3e32c-153">AL 内で、OData にバインドされたアクションを宣言できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-153">It is now possible to declare OData bound actions in AL.</span></span> <span data-ttu-id="3e32c-154">これを実現するために、新しい属性と新しい AL 型が導入されました。</span><span class="sxs-lookup"><span data-stu-id="3e32c-154">A new attribute and a new AL type have been introduced to achieve this.</span></span>

```
[ServiceEnabled]
procedure CreateCustomerCopy(var actionContext : WebServiceActionContext)
var
createdCustomerGuid : Guid;
customer : Record Customer;
begin
actionContext.SetObjectType(ObjectType::Page);
actionContext.SetObjectId(Pages::Customer);
actionContext.AddEntityKey(customer.fieldNo(Id), createdCustomerGuid);
actionContext.SetResultCode(WebServiceActionResultCode::Created);
end;
```
<!--
### Who uses this feature
These features are intended for ISV and VAR developers.
## Status
### Availability
Cloud, On-premises
### Regional availability
Globally
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="3e32c-155">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3e32c-155">Tell us what you think</span></span>
<span data-ttu-id="3e32c-156">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="3e32c-156">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3e32c-157">Business Central フォーラム ([https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3e32c-157">Use the Business Central forum at [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).</span></span>
