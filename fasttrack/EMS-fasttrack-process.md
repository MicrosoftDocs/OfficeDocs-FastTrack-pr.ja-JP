---
title: FastTrack プロセス
description: FastTrack センターの特典のオンボードプロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513776"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="98dcb-103">Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス</span><span class="sxs-lookup"><span data-stu-id="98dcb-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="98dcb-104">EMS の FastTrack センター特典の対象となる組織の場合は、FastTrack スペシャリストとリモートで作業して、Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection を入手することができます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="98dcb-105">また、「Azure Information Protection」、「Microsoft Cloud App Security」、および「Microsoft Advanced Threat Analytics」の[Fasttrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からサポートを依頼することもできます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics.</span></span> <span data-ttu-id="98dcb-106">組織が対象となるかどうかについては、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="98dcb-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="98dcb-107">次に、オンボードプロセスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="98dcb-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="98dcb-108">オンボードプロセスの概要</span><span class="sxs-lookup"><span data-stu-id="98dcb-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="98dcb-109">ソース環境に対する期待</span><span class="sxs-lookup"><span data-stu-id="98dcb-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="98dcb-110">オンボードプロセスのフェーズ</span><span class="sxs-lookup"><span data-stu-id="98dcb-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="98dcb-111">各フェーズの[Fasttrack の責任](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="98dcb-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="98dcb-112">各フェーズの[お客様の責任](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="98dcb-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="98dcb-113">オンボードが完了すると、次のようなことが予想されます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="98dcb-114">選択したサービスの EMS テナントが作成されます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="98dcb-115">ライセンスを付与されたユーザーは、次のいずれかの id オプションを使用して EMS サービスにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="98dcb-116">クラウド Id (一意の EMS アカウント)。</span><span class="sxs-lookup"><span data-stu-id="98dcb-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="98dcb-117">同期 Id: Azure Active Directory Connect ツール (パスワードハッシュ同期またはパススルー認証) を使用して、オンプレミスの Active Directory から同期された EMS アカウント。</span><span class="sxs-lookup"><span data-stu-id="98dcb-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="98dcb-118">このオプションは、1つのフォレストまたは複数の Active Directory フォレストを持つお客様を対象としています。</span><span class="sxs-lookup"><span data-stu-id="98dcb-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="98dcb-119">フェデレーション Id: 次のような Microsoft EMS アカウントを使用します。</span><span class="sxs-lookup"><span data-stu-id="98dcb-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="98dcb-120">Azure AD Connect ツールを使用して Active Directory から同期されます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="98dcb-121">このオプションは、1つの Active Directory フォレスト構成を持つお客様を対象としています。</span><span class="sxs-lookup"><span data-stu-id="98dcb-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="98dcb-122">オンプレミスの Active Directory から Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 またはそれ以降のバージョンとのフェデレーション。</span><span class="sxs-lookup"><span data-stu-id="98dcb-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="98dcb-123">Azure Information Protection を使用して、情報の自動分類と保護を両方とも行うことができます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="98dcb-124">Azure Information Protection スキャナーを使用して、オンプレミスのファイル共有と SharePoint サーバー内の情報を検出できます。</span><span class="sxs-lookup"><span data-stu-id="98dcb-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="98dcb-125">Azure Key Vault 内で Azure Information Protection のテナントキーを管理する機能。</span><span class="sxs-lookup"><span data-stu-id="98dcb-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 
