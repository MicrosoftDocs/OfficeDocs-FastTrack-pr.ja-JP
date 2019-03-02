---
title: fasttrack プロセス
description: fasttrack センターの特典のオンボードプロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0516035e55bc791645b32ad1819839b6c73f1772
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359841"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="5d98c-103">Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス</span><span class="sxs-lookup"><span data-stu-id="5d98c-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="5d98c-p101">EMS の fasttrack センターの特典の対象となる組織の場合は、fasttrack スペシャリストとリモートで作業して、microsoft Azure Active Directory Premium と microsoft Intune を利用することができます。また、「Azure Information Protection」、「microsoft Cloud App Security」、および「microsoft Advanced Threat Analytics」の[fasttrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からサポートを依頼することもできます。組織が対象となるかどうかについては、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5d98c-p101">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use. You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics. To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="5d98c-107">次に、オンボードプロセスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="5d98c-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="5d98c-108">オンボードプロセスの概要</span><span class="sxs-lookup"><span data-stu-id="5d98c-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="5d98c-109">ソース環境の要件</span><span class="sxs-lookup"><span data-stu-id="5d98c-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="5d98c-110">オンボードプロセスのフェーズ</span><span class="sxs-lookup"><span data-stu-id="5d98c-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="5d98c-111">各フェーズの[fasttrack の責任](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="5d98c-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="5d98c-112">各フェーズの[お客様の責任](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="5d98c-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="5d98c-113">オンボーディングを終えると、次のような状態になっているはずです。</span><span class="sxs-lookup"><span data-stu-id="5d98c-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="5d98c-114">選択したサービスの EMS テナントが作成されます。</span><span class="sxs-lookup"><span data-stu-id="5d98c-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="5d98c-115">ライセンスを付与されたユーザーは、次のいずれかの id オプションを使用して EMS サービスにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="5d98c-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="5d98c-116">クラウド id (一意の EMS アカウント)。</span><span class="sxs-lookup"><span data-stu-id="5d98c-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="5d98c-p102">同期 id: Azure active directory Connect ツール (パスワードハッシュ同期またはパススルー認証) を使用して、オンプレミスの active directory から同期された EMS アカウント。このオプションは、1つのフォレストまたは複数の Active Directory フォレストを持つお客様を対象としています。</span><span class="sxs-lookup"><span data-stu-id="5d98c-p102">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication). This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="5d98c-119">フェデレーション id: 次のような Microsoft EMS アカウントを使用します。</span><span class="sxs-lookup"><span data-stu-id="5d98c-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="5d98c-p103">Azure AD Connect ツールを使用して Active Directory から同期されます。このオプションは、1つの Active Directory フォレスト構成を持つお客様を対象としています。</span><span class="sxs-lookup"><span data-stu-id="5d98c-p103">Synchronized from Active Directory with the Azure AD Connect tool. This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="5d98c-122">オンプレミスの active directory から Windows Server 2012 R2 active directory Federation Services (AD FS) 2.0 またはそれ以降のバージョンとのフェデレーション。</span><span class="sxs-lookup"><span data-stu-id="5d98c-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>
