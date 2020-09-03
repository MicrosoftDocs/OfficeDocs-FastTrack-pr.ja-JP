---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。
ms.openlocfilehash: e4cebb463833c71cc9129155e86821c69f180a27
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338127"
---
# <a name="windows-10"></a><span data-ttu-id="30cf8-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="30cf8-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="30cf8-104">このコンテンツは最新ではなくなったため、削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="30cf8-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="30cf8-105">最新のコンテンツについては、左側のナビゲーションにある目次を使用してください。</span><span class="sxs-lookup"><span data-stu-id="30cf8-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="30cf8-106">FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。</span><span class="sxs-lookup"><span data-stu-id="30cf8-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="30cf8-107">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="30cf8-108">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise の展開。</span><span class="sxs-lookup"><span data-stu-id="30cf8-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="30cf8-109">Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="30cf8-110">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Microsoft 365 アプリを更新します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="30cf8-111">Microsoft Intune を使用して Configuration Manager をクラウドで接続するか、単独のクラウド管理ソリューションとして Intune を展開します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="30cf8-112">FastTrack では、お客様に推奨されるアプローチ、ガイダンス、および迅速に予測可能な結果を導き出すためのベスト プラクティスを提供します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="30cf8-113">このガイダンス以外の方法での展開を考えている場合、エクスペリエンスに影響が生じる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="30cf8-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="30cf8-114">ガイダンスは、口頭および書面のサポートの組み合わせとして定義されています。</span><span class="sxs-lookup"><span data-stu-id="30cf8-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="30cf8-115">FastTrack スペシャリストがガイダンスを提供する場合、お客様に代わって FastTrack の担当者が操作することはできません。</span><span class="sxs-lookup"><span data-stu-id="30cf8-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="30cf8-116">サブスクリプションが最新の状態に保たれている限り、FastTrack サービスを対象プランに使用できます。</span><span class="sxs-lookup"><span data-stu-id="30cf8-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="30cf8-117">次の表は、プロセスでの役割と責任を一覧にしたものです。</span><span class="sxs-lookup"><span data-stu-id="30cf8-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="30cf8-118">**役割**</span><span class="sxs-lookup"><span data-stu-id="30cf8-118">**Role**</span></span> <br/> |<span data-ttu-id="30cf8-119">**責任**</span><span class="sxs-lookup"><span data-stu-id="30cf8-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="30cf8-120">**FastTrack スペシャリスト**</span><span class="sxs-lookup"><span data-stu-id="30cf8-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="30cf8-121">すべての展開とサービスの更新をリモートで提供します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="30cf8-122">ツールと発行されているドキュメントを組み合わせて活用し、お客様をリモートでサポートします。</span><span class="sxs-lookup"><span data-stu-id="30cf8-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="30cf8-123">お客様またはお客様の担当者との作業を直接行います。</span><span class="sxs-lookup"><span data-stu-id="30cf8-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="30cf8-124">**FastTrack センター**</span><span class="sxs-lookup"><span data-stu-id="30cf8-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="30cf8-125">Windows 10 Enterprise の計画と展開を行うためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="30cf8-126">指定された地域の通常業務時間内に利用できるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="30cf8-127">繁体字中国語、簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、韓国語、ポルトガル語 (ブラジル)、スペイン語、タイ語、ベトナム語によるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="30cf8-128">[Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)または [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)を通してヘルプを受けられます。</span><span class="sxs-lookup"><span data-stu-id="30cf8-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="30cf8-129">サインインするには、アクティブなテナントでの職場または学校のアクティブなアカウント (組織 ID または Azure Active Directory ID) が必要です。</span><span class="sxs-lookup"><span data-stu-id="30cf8-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="30cf8-130">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="30cf8-131">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="30cf8-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="30cf8-132">ランディング ページの上部にある **[クイック アクション]** から **[Microsoft 365 サポート要求]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="30cf8-133">**Microsoft 365 サポート要求**フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="30cf8-p105">パートナーも顧客の代理として、[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得することができます。次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-p105">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="30cf8-136">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="30cf8-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="30cf8-137">ランディング ページの上部にある **[クイック アクション]** から **[Microsoft 365 サポート要求]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="30cf8-138">顧客名、ドメイン、または TPID を入力して顧客を検索します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="30cf8-139">検索結果から顧客を選択します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="30cf8-140">**Microsoft 365 サポート要求**フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="30cf8-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
