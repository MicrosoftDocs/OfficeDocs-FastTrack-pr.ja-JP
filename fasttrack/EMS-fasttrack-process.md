---
title: FastTrack プロセス
description: FastTrack Center の特典オンボーディング プロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 06/04/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0b24a3d1b339836fb07137a7ad2138f85ed7709b
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673248"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="e1643-103">Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス</span><span class="sxs-lookup"><span data-stu-id="e1643-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="e1643-104">お客様の組織が EMS 向け FastTrack Center の特典を受ける対象である場合は、FastTrack スペシャリストとリモートで作業して Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection を使用できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="e1643-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="e1643-105">また、Azure Information Protection、Microsoft Cloud App Security、および Microsoft Advanced Threat Analytics の [FastTrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からもヘルプを要求できます。</span><span class="sxs-lookup"><span data-stu-id="e1643-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics.</span></span> <span data-ttu-id="e1643-106">組織が特典を受ける対象であるかどうかを判断するには、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="e1643-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="e1643-107">ここでは、オンボーディング プロセスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e1643-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="e1643-108">オンボーディング プロセスの概要</span><span class="sxs-lookup"><span data-stu-id="e1643-108">Overview of the update process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="e1643-109">ソース環境の要件</span><span class="sxs-lookup"><span data-stu-id="e1643-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="e1643-110">オンボーディング プロセスのフェーズ</span><span class="sxs-lookup"><span data-stu-id="e1643-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="e1643-111">各フェーズの [FastTrack の責任範囲](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="e1643-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="e1643-112">各フェーズの [お客様の責任範囲](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="e1643-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="e1643-113">オンボーディングを終えると、次のような状態になっているはずです。</span><span class="sxs-lookup"><span data-stu-id="e1643-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="e1643-114">選択したサービスの EMS テナントが作成されます。</span><span class="sxs-lookup"><span data-stu-id="e1643-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="e1643-115">ライセンスを持つユーザーが、以下のいずれかの ID オプションを使用して EMS サービスにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="e1643-115">Licensed users can access O365_W14_2nd by using one of the following identity options:</span></span>

    -   <span data-ttu-id="e1643-116">クラウド ID (固有の EMS アカウント)。</span><span class="sxs-lookup"><span data-stu-id="e1643-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="e1643-117">同期 ID: Azure Active Directory Connect ツール (パスワード ハッシュ同期またはパススルー認証) を使用して、オンプレミスの Active Directory から EMS アカウントを同期しています。</span><span class="sxs-lookup"><span data-stu-id="e1643-117">Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="e1643-118">このオプションは、単一フォレストまたは複数の Active Directory フォレストを持つお客様向けです。</span><span class="sxs-lookup"><span data-stu-id="e1643-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="e1643-119">次の Microsoft EMS アカウントを持つフェデレーション ID:</span><span class="sxs-lookup"><span data-stu-id="e1643-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="e1643-120">Active Directory から Azure AD Connect ツールと同期します。</span><span class="sxs-lookup"><span data-stu-id="e1643-120">Synchronized from Active Directory with the Azure Active Directory Connect tool for customers with:</span></span> <span data-ttu-id="e1643-121">このオプションは、単一の Active Directory フォレスト構成を持つお客様向けです。</span><span class="sxs-lookup"><span data-stu-id="e1643-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="e1643-122">オンプレミスの Active Directory から Windows Server 2012 R2 の Active Directory フェデレーション サービス (AD FS) 2.0 以降とフェデレーションされています。</span><span class="sxs-lookup"><span data-stu-id="e1643-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="e1643-123">Azure Information Protection を使用して、保存中および転送中の両方で情報を自動分類および保護する機能。</span><span class="sxs-lookup"><span data-stu-id="e1643-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="e1643-124">Azure Information Protection スキャナーを使用して、オンプレミスのファイル共有と SharePoint サーバーの情報を見つける機能。</span><span class="sxs-lookup"><span data-stu-id="e1643-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="e1643-125">Azure Key Vault 内の Azure Information Protection テナント キーを管理する機能。</span><span class="sxs-lookup"><span data-stu-id="e1643-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 
