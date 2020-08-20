---
title: FastTrack プロセス
description: FastTrack Center の特典オンボーディング プロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Normal
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a0fc877fa22f6198e45e212c85ea1234ed19da70
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817258"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="61d90-103">Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス</span><span class="sxs-lookup"><span data-stu-id="61d90-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>

> [!CAUTION]
> <span data-ttu-id="61d90-104">このコンテンツは現在は使用されていないため、削除する予定です。</span><span class="sxs-lookup"><span data-stu-id="61d90-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="61d90-105">現在のコンテンツに対して左側のナビゲーション内の目次を使用します。</span><span class="sxs-lookup"><span data-stu-id="61d90-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="61d90-106">お客様の組織が EMS 向け FastTrack Center の特典を受ける対象である場合は、FastTrack スペシャリストとリモートで作業して Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection を使用できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="61d90-106">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="61d90-107">また、Azure Information Protection や Microsoft Cloud App Security の [FastTrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からもヘルプを要求できます。</span><span class="sxs-lookup"><span data-stu-id="61d90-107">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection and Microsoft Cloud App Security.</span></span> <span data-ttu-id="61d90-108">組織が特典を受ける対象であるかどうかを判断するには、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="61d90-108">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="61d90-109">ここでは、オンボーディング プロセスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="61d90-109">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="61d90-110">オンボーディング プロセスの概要</span><span class="sxs-lookup"><span data-stu-id="61d90-110">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="61d90-111">ソース環境の要件</span><span class="sxs-lookup"><span data-stu-id="61d90-111">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="61d90-112">オンボーディング プロセスのフェーズ</span><span class="sxs-lookup"><span data-stu-id="61d90-112">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="61d90-113">各フェーズの [FastTrack の責任範囲](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="61d90-113">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="61d90-114">各フェーズの [お客様の責任範囲](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="61d90-114">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="61d90-115">以下は、オンボード完了時に予測される内容です。</span><span class="sxs-lookup"><span data-stu-id="61d90-115">Here's what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="61d90-116">選択したサービスの EMS テナントが作成されます。</span><span class="sxs-lookup"><span data-stu-id="61d90-116">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="61d90-117">ライセンスを持つユーザーが、以下のいずれかの ID オプションを使用して EMS サービスにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="61d90-117">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="61d90-118">クラウド ID (固有の EMS アカウント)。</span><span class="sxs-lookup"><span data-stu-id="61d90-118">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="61d90-119">同期 ID: Azure Active Directory Connect ツール (パスワード ハッシュ同期またはパススルー認証) を使用して、オンプレミスの Active Directory から EMS アカウントを同期しています。</span><span class="sxs-lookup"><span data-stu-id="61d90-119">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="61d90-120">このオプションは、単一フォレストまたは複数の Active Directory フォレストを持つお客様向けです。</span><span class="sxs-lookup"><span data-stu-id="61d90-120">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="61d90-121">次の Microsoft EMS アカウントを持つフェデレーション ID:</span><span class="sxs-lookup"><span data-stu-id="61d90-121">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="61d90-122">Active Directory から Azure AD Connect ツールと同期します。</span><span class="sxs-lookup"><span data-stu-id="61d90-122">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="61d90-123">このオプションは、単一の Active Directory フォレスト構成を持つお客様向けです。</span><span class="sxs-lookup"><span data-stu-id="61d90-123">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="61d90-124">オンプレミスの Active Directory から Windows Server 2012 R2 の Active Directory フェデレーション サービス (AD FS) 2.0 以降とフェデレーションされています。</span><span class="sxs-lookup"><span data-stu-id="61d90-124">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="61d90-125">Azure Information Protection を使用して、保存中および転送中の両方で情報を自動分類および保護する機能。</span><span class="sxs-lookup"><span data-stu-id="61d90-125">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="61d90-126">Azure Information Protection スキャナーを使用して、オンプレミスのファイル共有と SharePoint サーバーの情報を見つける機能。</span><span class="sxs-lookup"><span data-stu-id="61d90-126">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="61d90-127">Azure Key Vault 内の Azure Information Protection テナント キーを管理する機能。</span><span class="sxs-lookup"><span data-stu-id="61d90-127">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 

