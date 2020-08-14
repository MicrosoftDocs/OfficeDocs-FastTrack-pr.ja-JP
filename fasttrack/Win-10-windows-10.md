---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。
ms.openlocfilehash: da069420434a8087c661f77400edd9239f56c366
ms.sourcegitcommit: 7da7b0966b08486a0ede148240af958408a271f7
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/11/2020
ms.locfileid: "46634171"
---
# <a name="windows-10"></a><span data-ttu-id="bb210-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="bb210-103">Windows 10</span></span>

<span data-ttu-id="bb210-104">FastTrack では、Windows 10 の展開のガイダンスを提供することで、ユーザーが Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise にアップグレードするお手伝いをします。</span><span class="sxs-lookup"><span data-stu-id="bb210-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="bb210-105">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="bb210-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="bb210-106">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise の展開。</span><span class="sxs-lookup"><span data-stu-id="bb210-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="bb210-107">Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="bb210-107">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="bb210-108">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Microsoft 365 アプリを更新します。</span><span class="sxs-lookup"><span data-stu-id="bb210-108">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="bb210-109">Microsoft Intune を使用して Configuration Manager をクラウドで接続するか、単独のクラウド管理ソリューションとして Intune を展開します。</span><span class="sxs-lookup"><span data-stu-id="bb210-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="bb210-110">FastTrack では、お客様に推奨されるアプローチ、ガイダンス、および迅速に予測可能な結果を導き出すためのベスト プラクティスを提供します。</span><span class="sxs-lookup"><span data-stu-id="bb210-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="bb210-111">このガイダンス以外の方法での展開を考えている場合、エクスペリエンスに影響が生じる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bb210-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="bb210-112">ガイダンスは、口頭および書面のサポートの組み合わせとして定義されています。</span><span class="sxs-lookup"><span data-stu-id="bb210-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="bb210-113">FastTrack スペシャリストがガイダンスを提供する場合、お客様に代わって FastTrack の担当者が操作することはできません。</span><span class="sxs-lookup"><span data-stu-id="bb210-113">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="bb210-114">サブスクリプションが最新の状態に保たれている限り、FastTrack サービスを対象プランに使用できます。</span><span class="sxs-lookup"><span data-stu-id="bb210-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="bb210-115">次の表は、プロセスでの役割と責任を一覧にしたものです。</span><span class="sxs-lookup"><span data-stu-id="bb210-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="bb210-116">**役割**</span><span class="sxs-lookup"><span data-stu-id="bb210-116">**Role**</span></span> <br/> |<span data-ttu-id="bb210-117">**責任**</span><span class="sxs-lookup"><span data-stu-id="bb210-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="bb210-118">**FastTrack スペシャリスト**</span><span class="sxs-lookup"><span data-stu-id="bb210-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="bb210-119">すべての展開とサービスの更新をリモートで提供します。</span><span class="sxs-lookup"><span data-stu-id="bb210-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="bb210-120">ツールと発行されているドキュメントを組み合わせて活用し、お客様をリモートでサポートします。</span><span class="sxs-lookup"><span data-stu-id="bb210-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="bb210-121">お客様またはお客様の担当者との作業を直接行います。</span><span class="sxs-lookup"><span data-stu-id="bb210-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="bb210-122">**FastTrack センター**</span><span class="sxs-lookup"><span data-stu-id="bb210-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="bb210-123">Windows 10 Enterprise の計画と展開を行うためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="bb210-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="bb210-124">指定された地域の通常業務時間内に利用できるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="bb210-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="bb210-125">繁体字中国語、簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、韓国語、ポルトガル語 (ブラジル)、スペイン語、タイ語、ベトナム語によるサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="bb210-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="bb210-126">[Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)または [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)を通してヘルプを受けられます。</span><span class="sxs-lookup"><span data-stu-id="bb210-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="bb210-127">サインインするには、アクティブなテナントでの職場または学校のアクティブなアカウント (組織 ID または Azure Active Directory ID) が必要です。</span><span class="sxs-lookup"><span data-stu-id="bb210-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="bb210-128">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="bb210-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="bb210-129">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="bb210-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="bb210-130">ランディング ページの上部にある **[クイック アクション]** から **[Microsoft 365 サポート要求]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="bb210-130">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="bb210-131">**Microsoft 365 サポート要求**フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="bb210-131">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="bb210-p104">パートナーも顧客の代理として、[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得することができます。次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="bb210-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="bb210-134">[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。</span><span class="sxs-lookup"><span data-stu-id="bb210-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="bb210-135">ランディング ページの上部にある **[クイック アクション]** から **[Microsoft 365 サポート要求]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="bb210-135">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="bb210-136">顧客名、ドメイン、または TPID を入力して顧客を検索します。</span><span class="sxs-lookup"><span data-stu-id="bb210-136">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="bb210-137">検索結果から顧客を選択します。</span><span class="sxs-lookup"><span data-stu-id="bb210-137">Select customer from the search results.</span></span>
5.    <span data-ttu-id="bb210-138">**Microsoft 365 サポート要求**フォームに必要事項を記入します。</span><span class="sxs-lookup"><span data-stu-id="bb210-138">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
