---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/13/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。
ms.openlocfilehash: 0d94d7cd231e6b9659f325b471c705239bdf03ce
ms.sourcegitcommit: d469f9b0dfa7f39fde051c38f255d6f5790f62f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/12/2019
ms.locfileid: "36294414"
---
# <a name="windows-10"></a><span data-ttu-id="ec442-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="ec442-103">Windows 10</span></span>

<span data-ttu-id="ec442-104">FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。</span><span class="sxs-lookup"><span data-stu-id="ec442-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="ec442-105">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="ec442-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="ec442-106">Microsoft System Center Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise の展開。</span><span class="sxs-lookup"><span data-stu-id="ec442-106">Deploy Windows 10 Enterprise using Microsoft System Center Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="ec442-107">Office 365 ProPlus の展開。</span><span class="sxs-lookup"><span data-stu-id="ec442-107">Deploy Office 365 ProPlus</span></span> 
- <span data-ttu-id="ec442-108">System Center Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Office 365 ProPlus の更新。</span><span class="sxs-lookup"><span data-stu-id="ec442-108">Update Windows 10 Enterprise and Office 365 ProPlus using System Center Configuration Manager or Microsoft 365.</span></span>
  
> [!NOTE]
> <span data-ttu-id="ec442-109">FastTrack では、お客様に推奨されるアプローチ、ガイダンス、および迅速に予測可能な結果を導き出すためのベスト プラクティスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ec442-109">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="ec442-110">このガイダンス以外の方法での展開を考えている場合、エクスペリエンスに影響が生じる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ec442-110">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="ec442-111">ガイダンスは、口頭および書面のサポートの組み合わせとして定義されています。</span><span class="sxs-lookup"><span data-stu-id="ec442-111">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="ec442-112">FastTrack スペシャリストがガイダンスを提供する場合、お客様に代わって FastTrack の担当者が操作することはできません。</span><span class="sxs-lookup"><span data-stu-id="ec442-112">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="ec442-113">サブスクリプションが最新の状態に保たれている限り、FastTrack サービスを対象プランに使用できます。</span><span class="sxs-lookup"><span data-stu-id="ec442-113">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span>  
    
<span data-ttu-id="ec442-114">次の表は、プロセスでの役割と責任を一覧にしたものです。</span><span class="sxs-lookup"><span data-stu-id="ec442-114">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec442-115">**役割**</span><span class="sxs-lookup"><span data-stu-id="ec442-115">**Role**</span></span> <br/> |<span data-ttu-id="ec442-116">**責任**</span><span class="sxs-lookup"><span data-stu-id="ec442-116">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="ec442-117">**FastTrack スペシャリスト**</span><span class="sxs-lookup"><span data-stu-id="ec442-117">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="ec442-118">すべての展開とサービスの更新をリモートで提供します。</span><span class="sxs-lookup"><span data-stu-id="ec442-118">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="ec442-119">ツールと発行されているドキュメントを組み合わせて活用し、お客様をリモートでサポートします。</span><span class="sxs-lookup"><span data-stu-id="ec442-119">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="ec442-120">お客様またはお客様の担当者との作業を直接行います。</span><span class="sxs-lookup"><span data-stu-id="ec442-120">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="ec442-121">**FastTrack センター**</span><span class="sxs-lookup"><span data-stu-id="ec442-121">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="ec442-122">Windows 10 Enterprise の計画と展開を行うためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ec442-122">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="ec442-123">指定された地域の通常業務時間内に利用できるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ec442-123">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="ec442-124">繁体字中国語、簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、韓国語、ポルトガル語 (ブラジル)、スペイン語、タイ語、ベトナム語によるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ec442-124">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="ec442-125">[Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)または [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)を通してヘルプを受けられます。</span><span class="sxs-lookup"><span data-stu-id="ec442-125">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="ec442-126">サインインするには、アクティブなテナントでの職場または学校のアクティブなアカウント (組織 ID または Azure Active Directory ID) が必要です。</span><span class="sxs-lookup"><span data-stu-id="ec442-126">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="ec442-127">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="ec442-127">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="ec442-128">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="ec442-128">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="ec442-129">**[サービス]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="ec442-129">Select **Services**.</span></span>
3.  <span data-ttu-id="ec442-130">**Microsoft 365 サポート要求**フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="ec442-130">Complete the **Request for Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="ec442-p104">パートナーも顧客の代理として、[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得することができます。次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="ec442-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.  <span data-ttu-id="ec442-133">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="ec442-133">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="ec442-134">**[顧客]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="ec442-134">Select **My Customers**.</span></span>
3.  <span data-ttu-id="ec442-135">顧客を検索するか、顧客リストから選択します。</span><span class="sxs-lookup"><span data-stu-id="ec442-135">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="ec442-136">**[サービス]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="ec442-136">Select **Services**.</span></span>
5.  <span data-ttu-id="ec442-137">**Microsoft 365 サポート要求フォーム**を選択します。</span><span class="sxs-lookup"><span data-stu-id="ec442-137">Complete the **Request for Assistance with Microsoft 365** form.</span></span>
6.  <span data-ttu-id="ec442-138">Windows 10 の製品オプションを選択し、フォームに記入します。</span><span class="sxs-lookup"><span data-stu-id="ec442-138">Select the Windows 10 product option and complete the form.</span></span>
 