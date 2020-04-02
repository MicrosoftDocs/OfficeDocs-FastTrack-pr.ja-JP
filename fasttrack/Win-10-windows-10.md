---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。
ms.openlocfilehash: d9f2ea820828f91e6eb0ddc22e37c7f98dd8f71d
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098363"
---
# <a name="windows-10"></a><span data-ttu-id="18a19-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="18a19-103">Windows 10</span></span>

<span data-ttu-id="18a19-104">FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。</span><span class="sxs-lookup"><span data-stu-id="18a19-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="18a19-105">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="18a19-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="18a19-106">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise の展開。</span><span class="sxs-lookup"><span data-stu-id="18a19-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="18a19-107">Office 365 ProPlus の展開。</span><span class="sxs-lookup"><span data-stu-id="18a19-107">Deploy Office 365 ProPlus.</span></span> 
- <span data-ttu-id="18a19-108">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Office 365 ProPlus の更新。</span><span class="sxs-lookup"><span data-stu-id="18a19-108">Update Windows 10 Enterprise and Office 365 ProPlus using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="18a19-109">Microsoft Intune を使用して Configuration Manager をクラウドで接続するか、単独のクラウド管理ソリューションとして Intune を展開します。</span><span class="sxs-lookup"><span data-stu-id="18a19-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="18a19-110">FastTrack では、お客様に推奨されるアプローチ、ガイダンス、および迅速に予測可能な結果を導き出すためのベスト プラクティスを提供します。</span><span class="sxs-lookup"><span data-stu-id="18a19-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="18a19-111">このガイダンス以外の方法での展開を考えている場合、エクスペリエンスに影響が生じる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="18a19-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="18a19-112">ガイダンスは、口頭および書面のサポートの組み合わせとして定義されています。</span><span class="sxs-lookup"><span data-stu-id="18a19-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="18a19-113">FastTrack スペシャリストがガイダンスを提供する場合、お客様に代わって FastTrack の担当者が操作することはできません。</span><span class="sxs-lookup"><span data-stu-id="18a19-113">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="18a19-114">サブスクリプションが最新の状態に保たれている限り、FastTrack サービスを対象プランに使用できます。</span><span class="sxs-lookup"><span data-stu-id="18a19-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="18a19-115">次の表は、プロセスでの役割と責任を一覧にしたものです。</span><span class="sxs-lookup"><span data-stu-id="18a19-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="18a19-116">**役割**</span><span class="sxs-lookup"><span data-stu-id="18a19-116">**Role**</span></span> <br/> |<span data-ttu-id="18a19-117">**責任**</span><span class="sxs-lookup"><span data-stu-id="18a19-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="18a19-118">**FastTrack スペシャリスト**</span><span class="sxs-lookup"><span data-stu-id="18a19-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="18a19-119">すべての展開とサービスの更新をリモートで提供します。</span><span class="sxs-lookup"><span data-stu-id="18a19-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="18a19-120">ツールと発行されているドキュメントを組み合わせて活用し、お客様をリモートでサポートします。</span><span class="sxs-lookup"><span data-stu-id="18a19-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="18a19-121">お客様またはお客様の担当者との作業を直接行います。</span><span class="sxs-lookup"><span data-stu-id="18a19-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="18a19-122">**FastTrack センター**</span><span class="sxs-lookup"><span data-stu-id="18a19-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="18a19-123">Windows 10 Enterprise の計画と展開を行うためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="18a19-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="18a19-124">指定された地域の通常業務時間内に利用できるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="18a19-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="18a19-125">繁体字中国語、簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、韓国語、ポルトガル語 (ブラジル)、スペイン語、タイ語、ベトナム語によるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="18a19-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="18a19-126">[Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)または [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)を通してヘルプを受けられます。</span><span class="sxs-lookup"><span data-stu-id="18a19-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="18a19-127">サインインするには、アクティブなテナントでの職場または学校のアクティブなアカウント (組織 ID または Azure Active Directory ID) が必要です。</span><span class="sxs-lookup"><span data-stu-id="18a19-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="18a19-128">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="18a19-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="18a19-129">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="18a19-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="18a19-130">ランディング ページの上部にある**クイック操作**から [**Microsoft 365 のサポートを依頼する**] を選択するか、展開カードの [**Microsoft 365 のサポートを依頼する**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="18a19-130">Select **Request assistance for Microsoft 365** from the **quick actions** on the top of your landing page or by selecting **Request assistance for Microsoft 365** on the deploy card.</span></span>
3.    <span data-ttu-id="18a19-131">[**Microsoft 365 のサポートを依頼する**] フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="18a19-131">Complete the **Request Assistance for Microsoft 365** form.</span></span>
  
<span data-ttu-id="18a19-p104">パートナーも顧客の代理として、[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得することができます。次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="18a19-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="18a19-134">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="18a19-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="18a19-135">**[顧客]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="18a19-135">Select **My Customers**.</span></span>
3.    <span data-ttu-id="18a19-136">顧客を検索するか、顧客リストから選択します。</span><span class="sxs-lookup"><span data-stu-id="18a19-136">Search for your customer or select them from your customer list.</span></span>
4.    <span data-ttu-id="18a19-137">**[サービス]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="18a19-137">Select **Services**.</span></span>
5.    <span data-ttu-id="18a19-138">[**Microsoft 365 のサポートを依頼する**] フォームを選択します。</span><span class="sxs-lookup"><span data-stu-id="18a19-138">Select the **Request Assistance for Microsoft 365** form.</span></span>
6.    <span data-ttu-id="18a19-139">Windows 10 の製品オプションを選択し、フォームに記入します。</span><span class="sxs-lookup"><span data-stu-id="18a19-139">Select the Windows 10 product option and complete the form.</span></span>
 
