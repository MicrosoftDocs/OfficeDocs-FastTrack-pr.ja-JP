---
title: 製品と機能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、開始前に FastTrack によってサポートされるワークロード シナリオの詳細と、必要なソース環境要件について説明します。 現在のセットアップ環境に基づいて、お客様と連同してソース環境をオンボーディングを正常に行うための最小要件を満たす修復計画を作成します。
ms.openlocfilehash: d25c1df8e628f14487952cacc86ccf8fb9dad8c1
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817702"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="c7e68-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="c7e68-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="c7e68-105">FastTrack によってサポートされるサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="c7e68-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="c7e68-106">このトピックでは、開始前に FastTrack によってサポートされるワークロード シナリオの詳細と、必要なソース環境要件について説明します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="c7e68-107">現在のセットアップ環境に基づいて、お客様と連同してソース環境をオンボーディングを正常に行うための最小要件を満たす修復計画を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="c7e68-108">FastTrack は、最初にコア機能 (すべての Microsoft Online Services に共通) を作成し、次に対象となる各サービスのオンボーディングをサポートするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="c7e68-109">全般</span><span class="sxs-lookup"><span data-stu-id="c7e68-109">General</span></span>](#general)
  - [<span data-ttu-id="c7e68-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="c7e68-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="c7e68-111">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="c7e68-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="c7e68-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="c7e68-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="c7e68-113">App Assure</span><span class="sxs-lookup"><span data-stu-id="c7e68-113">App Assure</span></span>](Win-10-app-assure.md)
  - [<span data-ttu-id="c7e68-114">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="c7e68-114">The new Microsoft Edge</span></span>](Win-10-microsoft-edge.md)

> [!NOTE]
> <span data-ttu-id="c7e68-115">Office 365 US Government のソース環境要件については、「 [展開元環境要件:Office 365 US Government」を参照してください](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-115">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="c7e68-116">全般</span><span class="sxs-lookup"><span data-stu-id="c7e68-116">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c7e68-117"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-117"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c7e68-118"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-118"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c7e68-119"><strong>ソース環境要件</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-119"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c7e68-120"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-120"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-121">コア オンボーディングに関するガイダンスを提供します。それには、サービスのプロビジョニング、テナント、ID の統合が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-121">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="c7e68-122">また、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供する手順も含まれています。これには、セキュリティ、ネットワーク接続、およびコンプライアンスについてのディスカッ <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ションも含まれます</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-122">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="c7e68-123">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-123">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="c7e68-124"></li>
</ul>  

<strong> ID 統合 </strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-124"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="c7e68-125">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-125">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="c7e68-126">Azure Active Directory (シングル フォレストまたは複数フォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含め、Azure AD Active Directory (Azure AD) と同期するためのオンプレミスの Active Directory ID の準備を含む。</span><span class="sxs-lookup"><span data-stu-id="c7e68-126">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="c7e68-127">グループベースのライセンスの使用を含む一括インポートやライセンスなど、クラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-127">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="c7e68-128">クラウドへの移行、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (AD FS) の正しい認証方法を選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-128">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="c7e68-129">1 つの AD アカウントと Azure 共有 Active Directory 接続ツールと同期された ID を持つお客様に対ADします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-129">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="c7e68-130">これには、R2 Windows Server 2012 サービス 2.0 以上の証明書が必要です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-130">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="c7e68-131">パスワード ハッシュ同期またはパスAD使用して、FS から Azure AD に認証を移行します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-131">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="c7e68-132">シングル サインオン (SSO) 用に、事前統合されたアプリ (Azure AD ギャラリー ソフトウェア (SaaS) アプリなど) の AD FS から Azure AD への移行。</span><span class="sxs-lookup"><span data-stu-id="c7e68-132">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="c7e68-133">Azure の仮想システム ギャラリーから SaaS アプリと SSO の統合AD有効にします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-133">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="c7e68-134">[アプリ統合チュートリアル] リストに記載されている、事前統合された SaaS アプリに対するユーザーの自動プロビジョニング <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">の有効化</a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみに限定されます)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-134">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="c7e68-135"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="c7e68-135"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="c7e68-136">FastTrack 特典の一部として、Microsoft 365 の最高レベルのパフォーマンスを確実にするために、クラウド サービスに接続するためのベスト プラクティスへのリンクを提供してください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-136">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="c7e68-137"><strong>Active Directory フォレスト</strong> フォレスト構成は、機能フォレスト レベルを Windows Server 2003 以降に設定します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-137"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-138">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="c7e68-138">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-139">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="c7e68-139">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-140">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="c7e68-140">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-141">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-141">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-142">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="c7e68-142">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-143">テナント構成と Azure Active Directory との統合 (必要な場合) に必要なタスク。   </span><span class="sxs-lookup"><span data-stu-id="c7e68-143">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="c7e68-144">
  <strong>大事な：</strong>  </span><span class="sxs-lookup"><span data-stu-id="c7e68-144">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="c7e68-145">複数のフォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開される場合は、Exchange と同じ Active Directory フォレスト内に展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-145">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-146">複数の Exchange 組織を含む複数の Active Directory フォレストを Exchange マルチ ハイブリッド構成で実装する場合、ソース フォレスト間で共有されているユーザー プリンシパル名 (UPN) の名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-146">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="c7e68-147">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-147">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="c7e68-148">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-148">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-149">フォレストが複数あるすべての構成で、Active Directory フェデレーション サービス (AD FS) の展開は対象外です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-149">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="c7e68-150">この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-150">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-151"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-151"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-152">以下に関するリモート展開のガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-152">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-153">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="c7e68-153">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-154">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-154">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-155">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-155">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-156">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-156">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-157">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-157">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-158">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-158">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-159">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-159">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-160">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-160">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="c7e68-161">さらに、以前のバージョンの Office で作業していたマクロまたはアドインで互換性の問題が発生した場合、Microsoft は App Assure プログラムによる追加料金なしで互換性の問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-161">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="c7e68-162">詳しくは<a href="#windows-10">、Windows 10</a>の App <strong>Assure</strong>の部分をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-162">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c7e68-163">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および組織のシステム要件で定義されている最小レベルを満たOffice。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-163">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-164"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-164"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-165">Microsoft は、ネットワーク接続のマイクロソフトの原則に組織のサイトを整合する方法を示す、ご利用の環境からお客様の環境から主要なネットワーク接続データを取得して解釈するためのリモート <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ガイダンスを提供します</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-165">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="c7e68-166">これにより、移行の実行のウィンドウローク性、ユーザー エクスペリエンス、サービスのパフォーマンス、信頼性に直接影響するネットワークのスコアが強調されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-166">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="c7e68-167">また、このデータによって強調表示される、ネットワーク スコアの改善に役立つ修復手順についても説明します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-167">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="c7e68-168">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-168">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-169">Microsoft 365 アプリの最新バージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-169">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-170">Microsoft 365 管理センター <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">(プレビュー) でネットワーク パフォーマンスに関する推奨事項に従って有効になっている場所サービス。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-170">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="c7e68-171">Office 365</span><span class="sxs-lookup"><span data-stu-id="c7e68-171">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c7e68-172"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-172"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c7e68-173"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-173"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c7e68-174"><strong>ソース環境要件</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-174"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c7e68-175"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-175"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-176">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-176">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="c7e68-177">正確な手順は、お使いのソース環境とメールの移行プランによって異なります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-177">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="c7e68-178">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-178">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-179">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="c7e68-179">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-180">メール交換 (MX) レコードのポイントを 365 Officeします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-180">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-181">Office 365 ATP 機能がサブスクリプション サービスに含まれています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-181">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="c7e68-182">詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> の部分を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-182">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-p113">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="c7e68-p114">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="c7e68-187">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、オンプレミスのメールボックスから対応する Exchange Online メールボックスへの Information Rights Managed (IRM) で管理されたメールの移行を試行します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-187">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="c7e68-188">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-188">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="c7e68-189">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-189">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-190">必要な自動検出、Sender Policy Framework (SPF)、DomainKeys Identified Mail (DKIM)、Domain-based Message Authentication、Reporting and Conformance (DMARC)、および MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-190">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-191">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-191">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-192">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="c7e68-192">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-193">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-193">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="c7e68-194">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="c7e68-194">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="c7e68-195">Office 365 へのデータ移行に関する FastTrack 特典の使用に関する詳細については、「データ移行 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-195">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="c7e68-196">ソース環境には、次に示す最低レベルのいずれかが必要です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-196">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-197">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="c7e68-197">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-198">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="c7e68-198">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-199">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-199">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-200">複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、Exchange Online の複数地域機能を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-200">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-201">Project for Office 365、Office 365 用 Outlook、iOS および Android 用の Outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは、Microsoft 365 Office のシステム要件で定義されている最小 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">レベルを満たしていなけらなけらなけずに、必要です</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-201">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-202"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-202"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-203">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-203">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-204">情報ガバナンス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-204">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-205">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-206">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="c7e68-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-207">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-208">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-209">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="c7e68-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-210">Advanced eDiscovery</span><span class="sxs-lookup"><span data-stu-id="c7e68-210">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-211">全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-211">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-212"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-212"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-213">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-213">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-214">データの分類。</span><span class="sxs-lookup"><span data-stu-id="c7e68-214">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-215">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="c7e68-215">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-216">機密ラベルを作成する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-216">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-217">機密ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-217">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-218">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="c7e68-218">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-219">トレーニング可能な分類です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-219">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-220">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使ってデータの確認</span><span class="sxs-lookup"><span data-stu-id="c7e68-220">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-221">ポリシーを使用してラベルを発行する (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-221">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-222">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-222">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-223">全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-223">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-224"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-224"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-225">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-225">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-226">Teams をサポートするための Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADの最小要件を確認する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-226">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-227">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-227">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-228">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="c7e68-228">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-229">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-229">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-230">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-230">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-231">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="c7e68-231">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-232">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-232">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-233">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-233">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-234">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="c7e68-234">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c7e68-235">Teams アプリ ポリシー (Teams Web アプリ、Teams デスクトップ アプリ、iOS および Android 用 Teams アプリ) の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-235">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-236">該当する場合は、次の操作のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-236">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-237">Microsoft Teams ミーティング デバイス:</span><span class="sxs-lookup"><span data-stu-id="c7e68-237">Microsoft Teams Room Devices:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c7e68-238">Teams デバイス カタログに一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン <a href="https://go.microsoft.com/fwlink/?linkid=2066478">アカウントの作成</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-238">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c7e68-239">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="c7e68-239">Enabling Audio Conferencing:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c7e68-240">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-240">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-241">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-241">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c7e68-242">電話システム:</span><span class="sxs-lookup"><span data-stu-id="c7e68-242">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-243">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-243">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-244">通話プランのガイダンス (利用可能<a href="https://go.microsoft.com/fwlink/?linkid=2066478">な市場の提供):</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-244">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-245">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-245">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-246">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-246">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-247">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="c7e68-247">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-248">ダイレクト ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="c7e68-248">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-249">パートナー ホスティング シナリオまたは単一サイトでの顧客展開シナリオの直接ルーティング デサインのための組織のセットアップ ガイド。</span><span class="sxs-lookup"><span data-stu-id="c7e68-249">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for a single site.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="c7e68-250">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-250">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-251">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="c7e68-251">Organization setup and integration into Microsoft Stream.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c7e68-252">365 用 Azure AD で Office有効になっている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-252">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-253">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-253">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-254">Exchange メールボックスがある (Exchange ハイブリッド構成でオンラインおよびオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-254">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-255">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-255">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="c7e68-256">
  <strong>注:</strong>  SharePoint Online ライセンスがユーザーに割り当てられておらない場合は、SharePoint 365 の OneDrive for Business 記憶域Officeできません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-256">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="c7e68-257">ファイル共有はチャネル内で引き続き動作しますが、Office 365 に OneDrive for Business ストレージがないと、ユーザーはチャットでファイルを共有できません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-257">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="c7e68-258">Teams はオンプレミスの SharePoint をサポートしていいない。</span><span class="sxs-lookup"><span data-stu-id="c7e68-258">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="c7e68-259">
  <strong>注:</strong>  すべてのユーザーがメールボックスを Exchange Online のホームに設定するのが理的な状態です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-259">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="c7e68-260">メールボックスがオンプレミスでホームに設定されているユーザーは、Azure Connect を介して Office 365 ディレクトリと ID をADする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-260">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="c7e68-261">これら Exchange ハイブリッドのお客様について、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加したり構成したりできません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-261">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="c7e68-262">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、ダウンロードできます  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 。</span><span class="sxs-lookup"><span data-stu-id="c7e68-262">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-264">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-264">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-265">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-265">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-266">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-266">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-267">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-267">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-268">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="c7e68-268">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-269">全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-269">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-270"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-270"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-271">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-272">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="c7e68-272">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-273">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-273">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-274">Outlook モバイルの保護 (詳細については、Exchange Online で <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Outlook for iOS および Outlook for Android のセキュリティ保護を</a> 参照してください)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-274">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c7e68-275">365 用 Azure AD で Office有効になっている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-275">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-276">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-276">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-277"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-277"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-278">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-279">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-279">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-280">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-280">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-281">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および Microsoft のシステム要件で定義されている最小レベルを満たOffice。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-281">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-282"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-282"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-283">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-283">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-284">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-284">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-285">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-285">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-286">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-286">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-287">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-287">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-288">Project for Office 365 などのオンライン クライアント ソフトウェアは、Microsoft 365 および <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 のシステム要件で定義されている最小レベルである必要がありますOffice。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-288">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-289"><strong>Project Online Professional と Premium</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-289"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-290">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-291">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="c7e68-291">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-292">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-292">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-293">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-293">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-294">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-294">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-295">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-295">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-296">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="c7e68-296">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-297">Project for Office 365 などのオンライン クライアント ソフトウェアは、Microsoft 365 および <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 のシステム要件で定義されている最小レベルである必要がありますOffice。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-297">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-298"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-298"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-299">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-299">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-300">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="c7e68-300">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-301">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-301">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-302">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="c7e68-302">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="c7e68-303">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-303">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="c7e68-304">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="c7e68-304">Planning site collections.</span></span></li>
<li><span data-ttu-id="c7e68-305">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="c7e68-305">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="c7e68-306">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-306">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="c7e68-307">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-307">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-308">移行方法。</span><span class="sxs-lookup"><span data-stu-id="c7e68-308">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-309">SharePoint バージョンに応じて、その他のガイダンスも OneDrive for Business 向けに提供されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-309">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-310">統合オプションの特定、社内およびオンラインのネットワーク インフラストラクチャおよび帯域幅の確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-310">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-311">SharePoint Online 2013 SP1 (該当する場合)、同期および ID 要件の計画と実装、および OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="c7e68-311">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-312">すべてのユーザー (または段階的にロールアウト) を対象に 1 つのロールアウトを計画し、実装します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-312">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-313">Office OneDrive へのアクセス制御を行うための対象ユーザーの設定 (SharePoint Online 2013 に適用可能) へのライセンスの割り当ておよび個人用ドキュメント ライブラリの割り当て、個人用ドキュメント ライブラリのリダイレクトを行います (SharePoint Online 2013 に適用されます)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-313">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="c7e68-314">既知のフォルダーを OneDrive にリダイレクトまたは移動する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-314">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="c7e68-315">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-315">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="c7e68-316">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="c7e68-316">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="c7e68-317">Office 365 へのデータ移行に関する FastTrack 特典の使用に関する詳細については、「データ移行 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-317">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="c7e68-318"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-318"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="c7e68-319">SharePoint ハイブリッド構成には、オンプレミスから単一のターゲット SharePoint Online 環境に接続するハイブリッドの検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、セルフサービス サイト作成の構成が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-319">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="c7e68-320">
  <strong>注:</strong> セルフサービス サイト作成は、SharePoint 2013を実行する社内サーバーの対象範囲には含みません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-320">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="c7e68-321">SharePoint ハイブリッドを有効にするには、2013、2016、2019 のいずれかのオンプレミスの SharePoint Server 環境を持つ必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-321">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="c7e68-322">
  <strong>注:</strong> オンプレミスの SharePoint 環境の SharePoint Server へのアップグレードは対象範囲外です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-322">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="c7e68-323">Microsoft パートナーに <a href="https://go.microsoft.com/fwlink/?linkid=2080150">お問い</a> 合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-323">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="c7e68-324">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベルを参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="c7e68-324">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="c7e68-325">
  <strong>注:</strong> 複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=831056">、「OneDrive の複数地域機能」および「Office 365 の SharePoint Online の複数地域機能」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="c7e68-325">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-326"><strong>Skype for Business Online</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-326"><strong>Skype for Business Online</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-327">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-328">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-328">Configuring firewall ports.</span></span>  </li>

<li>  <span data-ttu-id="c7e68-329">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="c7e68-329">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-330">ネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="c7e68-330">Network assessment:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-331">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-331">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-332">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-332">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-333">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="c7e68-333">Bandwidth estimates.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-334">ルーム システム デバイスのアカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-334">Creating accounts for any room system devices.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-335">サポートされる Skype for Business Online クライアントの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-335">Deploying a supported Skype for Business Online client.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-336">オンプレミスの Lync 2010、Lync 2013、Skype for Business 2015 サーバー環境と、Skype for Business Online テナント (該当する場合)、通話プラン、Skype 会議ブロードキャスト、電話システムおよび通話プラン (利用可能なマーケットのみ) との間で、分割ドメイン サーバー構成を確立する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-336">Establishing split domain server configuration between your on-premises Lync 2010, Lync 2013, or Skype for Business 2015 server environment and Skype for Business Online tenant (if applicable), Calling Plans, Skype Meeting Broadcast, and Phone System and Calling Plans (in available markets).</span></span>  
  <span data-ttu-id="c7e68-337">該当する場合は、FastTrack に次の手順も示されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-337">If applicable, FastTrack also guides you through:</span></span>  </li>
<li>  <span data-ttu-id="c7e68-338">ルーム システム デバイスの構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-338">Configuring room system device:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-339">Skype for Business ソリューション カタログの [Meeting Room Systems (会議室システム)] タブに一覧表示されている、サポート対象会議室 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">デバイスに必要なオンライン アカウントの作成</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-339">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business solutions catalog</a>.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-340">ハイブリッド サーバーと分割ドメイン サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-340">Configuring hybrid and split domain servers.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-341">電話会議の構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-341">Configuring Audio Conferencing:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-342">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-342">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-343">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-343">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-344">電話システムの既定の設定の構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-344">Configuring Phone System default settings:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-345">通話プラン:</span><span class="sxs-lookup"><span data-stu-id="c7e68-345">Calling Plans:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-346">ライセンス ユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="c7e68-346">Assignment of numbers to licenses users.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-347">ユーザー インターフェイスを通じて 99 までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-347">Local number porting guidance through user interface up to 99</span></span>  </li>
<li>  <span data-ttu-id="c7e68-348">999 以上の電話番号の移植サービス要求のサポート</span><span class="sxs-lookup"><span data-stu-id="c7e68-348">Local number porting service request support over 999</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="c7e68-349">Skype for Business 会議ブロードキャストを構成します:</span><span class="sxs-lookup"><span data-stu-id="c7e68-349">Configure Skype for Business Meeting Broadcast:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-350">会議メディア サービスとのフェデレーションのための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-350">Organization setup for federation with Meeting Broadcast service.</span></span>  </li>
</ul></li>
</ul></td>
<td>  <span data-ttu-id="c7e68-351"><strong>Lync ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-351"><strong>For Lync hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="c7e68-352">1 つのオンプレミスの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="c7e68-352">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-353">Lync 2010 Server 環境と、Lync 2013 2013 管理ツールまたは Skype for Business 2015 管理ツール、および Lync 2010 エッジ サーバーの役割。</span><span class="sxs-lookup"><span data-stu-id="c7e68-353">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-354">Lync 2013 Server 環境と Lync 2013 エッジ サーバーの役割。</span><span class="sxs-lookup"><span data-stu-id="c7e68-354">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  </li>
</ul><span data-ttu-id="c7e68-355">
  <strong>Skype for Business ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-355">
  <strong>For Skype for Business hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="c7e68-356">1 つのオンプレミスの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="c7e68-356">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-357">1 つの Active Directory アカウント フォレスト以降とリソース フォレスト (Exchange と Skype for Business の一方または両方) のトポロジ。</span><span class="sxs-lookup"><span data-stu-id="c7e68-357">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-358">複数の Active Directory アカウント フォレスト、および一元化された Active Directory アカウント フォレストで、その中に Exchange と Skype for Business の一方または両方がある 1 つのフォレスト。</span><span class="sxs-lookup"><span data-stu-id="c7e68-358">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-359">Skype for Business エッジ サーバーの役割を含む Skype for Business Server 2015 環境。</span><span class="sxs-lookup"><span data-stu-id="c7e68-359">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  </li>
</ul><span data-ttu-id="c7e68-360">
  <strong>注:</strong> この追加のサービスは分割ドメイン (ハイブリッド) タスクの構成と検証用で、オンプレミスのコンポーネント (たとえば、Lync 2013 管理ツールや Lync 2013/Skype for Business Online サーバー、Lync 2010、Lync 2013、または Skype for Business エッジ サーバー) の導入は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-360">
  <strong>Note:</strong> This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-361"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-361"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="c7e68-362">Microsoft は、エンタープライズ サービスを有効にするためのリモート Yammer提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-362">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="c7e68-363">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および組織のシステム要件で定義されている最小レベルを満たOffice。</a></span><span class="sxs-lookup"><span data-stu-id="c7e68-363">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="c7e68-364">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="c7e68-364">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-365"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-365"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-366">次のシナリオで、クラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-366">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="c7e68-367">

<strong>セキュアな基礎インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="c7e68-367">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="c7e68-368">ID に対する強力な認証の構成と有効化。Azure 多要素認証 (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-368">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-369">Azure 以外のお客様には、セキュリティADを使用して ID をセキュリティ保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-369">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-370">Azure プレミアムADお客様には、条件付きアクセスで ID を保護するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-370">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-371">Azure AD Password Protection での弱いパスワードの使用を検出、ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-371">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-372">Azure エンドポイント アプリケーション プロキシを使用して、オンプレミス Web アプリへのリモート ADをセキュリティ保護します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-372">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-373">リスク ベースの検出と Azure Identity Protection による修復の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-373">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-374">カスタム ブランドを使用して、ロゴ、テキスト、画像など、カスタマイズしたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="c7e68-374">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-375">Azure アカウントと B2B を使用して、ゲスト ユーザーとアプリやサービスを安全AD共有します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-375">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-376">役割ベースのアクセス制御 (RBAC) 組み込みの管理者ロールを使用して Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-376">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-377">ハイブリッド Azure への参加AD方法。</span><span class="sxs-lookup"><span data-stu-id="c7e68-377">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-378">Azure への参加ADする。</span><span class="sxs-lookup"><span data-stu-id="c7e68-378">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="c7e68-379">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-379">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c7e68-380">Azure Connect Health を使用した AD FS、Azure AD Connect、およびドメイン コントローラーのリモート監視AD有効にします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-380">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="c7e68-381">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-381">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c7e68-382">Azure デバイスのエンADメント管理を使用して、大規模な Azure ID とアクセス ライフADを管理します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-382">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="c7e68-383">Azure グループ メンバーシップADエンタープライズ アプリへのアクセス、役割の割り当ての管理と、Azure ADでのアクセス レビュー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-383">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-384">Azure の使用条件ADの確認。</span><span class="sxs-lookup"><span data-stu-id="c7e68-384">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-385">Azure を使用した特権 ID 管理による特権管理者アカウントAD管理と制御。</span><span class="sxs-lookup"><span data-stu-id="c7e68-385">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="c7e68-386">
  
<strong>自動化と効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-386">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c7e68-387">AD Azure SSPR の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-387">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="c7e68-388">セルフサービスによるグループ管理を使用して、ユーザーが独自のクラウド セキュリティや Office office 365 ADを作成および管理できるようにする。</span><span class="sxs-lookup"><span data-stu-id="c7e68-388">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-389">Azure でグループ管理を委任されたアプリを使用ADアクセスを管理する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-389">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-390">動的なグループADの有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-390">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-391">コレクションを使って [マイ アプリ] ポータルでアプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-391">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c7e68-392">オンプレミスの Active Directory とその環境は Azure AD Premium 用に準備されています。このコンソールには、Azure AD および Azure AD Premium 機能との統合を防止する特定された問題の修復などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-392">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c7e68-393"><strong>Azure Information Protection (P2 または EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-393"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-394">次の方法に関するガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-394">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-395">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-395">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-396">ラベルおよびポリシーの作成および設定。</span><span class="sxs-lookup"><span data-stu-id="c7e68-396">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-397">情報保護のドキュメントへの適用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-397">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-398">Windows で実行され、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) での自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="c7e68-398">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-399">Azure Information Protection スキャナーを使用した、保管中ファイルの使用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-399">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-400">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="c7e68-400">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-401">また、Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用する場合は、ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-401">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="c7e68-402">以下の作業が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-402">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-403">Azure サブスクリプションをAD。</span><span class="sxs-lookup"><span data-stu-id="c7e68-403">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-404">Windows または iOS のいずれかを使用します (その他のオペレーティング システムは対象外)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-404">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="c7e68-405">
<strong>注</strong>: コンピューターとモバイル デバイスは、Azure Information Protection を <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">サポートしているオペレーティング システム</a> 上で実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-405">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="c7e68-406">メインのファイル共有場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-406">Have your main file share locations.</span></span>  </li><span data-ttu-id="c7e68-407">
<strong>注</strong>: ハイブリッド サポートには、RMS コネクタAD必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-407">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="c7e68-408">承認済みの分類の分類がある場合。</span><span class="sxs-lookup"><span data-stu-id="c7e68-408">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-409">保護されたキー管理に対するすべての規制制限を理解します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-409">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="c7e68-410">
</ul>
  
<strong>Azure Information Protection スキャナー</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-410">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="c7e68-411">以下の作業が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="c7e68-411">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="c7e68-412">新Windows Server 2012 R2 または Windows Server 2016 を使用します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-412">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-413">インターネット接続。</span><span class="sxs-lookup"><span data-stu-id="c7e68-413">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-414">ローカルまたはMicrosoft SQL Serverリモートのインスタンスに 2012 以降のバージョンがある。</span><span class="sxs-lookup"><span data-stu-id="c7e68-414">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-415">オンプレミスの Active Directory 用のサービス アカウントが作成し、Azure アカウントとAD。</span><span class="sxs-lookup"><span data-stu-id="c7e68-415">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-416">ダウンロードしてAzInfoProtection.exe。</span><span class="sxs-lookup"><span data-stu-id="c7e68-416">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-417">ラベルを自動分類/保護用に構成している。</span><span class="sxs-lookup"><span data-stu-id="c7e68-417">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c7e68-418"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-418"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-419">Intune を、アプリおよびデバイス用のクラウドベースのモバイル デバイス管理 (MDM) およびモバイル アプリ管理 (MAM) プロバイダーとして使用する準備についてのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-419">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="c7e68-420">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-420">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="c7e68-421">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="c7e68-421">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-422">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="c7e68-422">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-423">オンプレミスの Active Directory またはクラウド ID (Azure AD) を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-423">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-424">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-424">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-425">管理ニーズに基づき、以下の MDM 機関を構成する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-425">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-426">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-426">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-427">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="c7e68-427">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-428">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-428">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-429">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-429">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-430">Web リンクまたは詳細リンクを介した、サポートされている各プラットフォームでのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-430">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-431">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-431">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-432">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合の、電子メール、ワイヤレス ネットワーク、VPN のプロファイルの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-432">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-433">Microsoft Intune Exchange Connector のセットアップ (該当する場合)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-433">Setting up the Microsoft Intune Exchange Connector (when applicable).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-434">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="c7e68-434">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-435">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="c7e68-435">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-436">リモート アシスタンス用の Team Viewer (チーム ビューアーのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-436">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-437">Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-437">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-438">通信経費の管理ソリューション (通信経費の管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-438">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-439">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-439">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-440">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="c7e68-440">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="c7e68-441">以下のアプリ保護ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="c7e68-441">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-442">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-442">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-443">管理対象アプリの条件付きアクセス ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-443">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-444">前述の MAM ポリシーを使って、適切なユーザー グループを対象にできます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-444">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-445">管理対象アプリ使用状況レポートの使用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-445">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-446">従来の PC 管理から Intune MDM への移行ガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="c7e68-446">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="c7e68-447">
  <strong>注</strong>: 2020 年 10 月 15 日以降、レガシ PC 管理はサポートされなくなりました。</span><span class="sxs-lookup"><span data-stu-id="c7e68-447">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="c7e68-448"></li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-448"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="c7e68-449">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備を説明しています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-449">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="c7e68-450">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-450">The exact steps depend on your source environment.</span></span> <span data-ttu-id="c7e68-451">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-451">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="c7e68-452">Intune を使用してクラウドに接続することの利点についての説明。</span><span class="sxs-lookup"><span data-stu-id="c7e68-452">Explaining the benefits of cloud-attaching Configuration Manager with Intune.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-453">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="c7e68-453">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-454">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-454">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-455">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-455">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-456">Configuration Manager コンソールでのクラウド接続の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-456">Enabling cloud-attach in the Configuration Manager console.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-457">参加へのハイブリッド Azure の移行のガイダンスADします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-457">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-458">MDM 自動登録に必要な Azure ADガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="c7e68-458">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-459">クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="c7e68-459">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-460">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-460">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-461">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-461">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="c7e68-462"><strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織で安全に展開し、必要なアプリがすべてユーザーにインストールされていることが保たれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-462"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="c7e68-463">Intune を使用して、iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-463">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="c7e68-464">これには以下を含むことができます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-464">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-465">Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、および Intune ポータル サイト アプリをダウンロードする。</span><span class="sxs-lookup"><span data-stu-id="c7e68-465">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-466">セットアップのガイダンスを提供:</span><span class="sxs-lookup"><span data-stu-id="c7e68-466">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-467">Android 用の Outlook、Microsoft Authenticator、および Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-467">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-468">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-468">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-469">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-469">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-470">アプリの構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-470">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="c7e68-471"><strong>注</strong>: FastTrack では、Exchange モバイル デバイス メールボックス ポリシーを使用した Outlook for iOS と Outlook for Android のセキュリティ保護はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-471"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="c7e68-472">この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-472">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="c7e68-473">Intune でワイヤレス ネットワークと VPN プロファイルの展開を計画する際には、IT 管理者は既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを運用環境であらかじめ運用している必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-473">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="c7e68-474"><strong>注</strong>: FastTrack サービス特典には、Intune 用の認証機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書のセットアップおよび構成に関するサポートは含まれていません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-474"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  

<span data-ttu-id="c7e68-475"><strong>Intune を使用して Configuration Manager をクラウドで接続する</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-475"><strong>Cloud-attach Configuration Manager with Intune</strong></span></span>  

 <span data-ttu-id="c7e68-476">クラウド接続を使用する場合、IT 管理者がオンプレミス環境の準備を行います。</span><span class="sxs-lookup"><span data-stu-id="c7e68-476">With cloud-attach, IT admins are responsible for preparing the on-premises environment.</span></span> <span data-ttu-id="c7e68-477">この中には、Intune を使用した Configuration Manager 環境のクラウド接続を回避する問題の修復が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-477">This can include remediation of issues that prevent you from cloud-attaching your Configuration Manager environments with Intune.</span></span>  
  <span data-ttu-id="c7e68-478"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-478"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="c7e68-479">この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-479">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="c7e68-480"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-480"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="c7e68-481"><strong>注</strong>: Intune を Microsoft Defender ATP と統合し、Windows 10 のリスク レベル評価に基づいてデバイス コンプライアンス ポリシーを作成するための支援を提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-481"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="c7e68-482">購入、ライセンス、ライセンス認証に関するサポートは提供していません。</span><span class="sxs-lookup"><span data-stu-id="c7e68-482">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="c7e68-483">この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-483">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="c7e68-484"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-484"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="c7e68-485">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-485">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="c7e68-486"><strong>Intune を使用して Outlook for iOS および Outlook for Android を安全に展開する </strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-486"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="c7e68-487">ユーザー ID は、Azure 365 向けAD Azure Office有効になっています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-487">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-488">Exchange Online またはハイブリッド Exchange が構成され、ユーザー ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="c7e68-488">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="c7e68-489">Windows 10</span><span class="sxs-lookup"><span data-stu-id="c7e68-489">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c7e68-490"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-490"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c7e68-491"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-491"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c7e68-492"><strong>ソース環境要件</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-492"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c7e68-493"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-493"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-494">Microsoft では、アップグレードとアップグレードをサポートWindows 7 ProfessionalWindows 7 Professional.1 Professional から Windows 8 windows 10 Enterprise へのアップグレードをサポートするガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-494">We provide guidance to help you upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="c7e68-495">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-496">Windows 10 の目的を理解する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-496">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-497">ソース環境と要件を評価する (Windows 10 の展開をサポートするために必要なレベルに Microsoft Endpoint Configuration Manager をアップグレードする必要があります)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-497">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-498">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Microsoft 365 アプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-498">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-499">Windows 10 アプリを評価するためのオプションの推奨。</span><span class="sxs-lookup"><span data-stu-id="c7e68-499">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-500">Desktop Analytics 展開計画作成を使用する場合の Desktop Analytics とガイダンスの使用を有効にする。</span><span class="sxs-lookup"><span data-stu-id="c7e68-500">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-501">Microsoft 365 アプリ互換性評価:「Configuration Manager の Office 365 の準備状態」ダッシュボードやスタンドアロンの準備 Toolkit (Office に加えて Microsoft 365 アプリの展開を支援します)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-501">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-502">Microsoft Intune を使用して Configuration Manager をクラウドで接続する場合や、単一のクラウド管理ソリューションとして Intune を展開するなど、最新の管理戦略の評価。</span><span class="sxs-lookup"><span data-stu-id="c7e68-502">Assessing your modern management strategies, including cloud-attaching Configuration Manager with Microsoft Intune or deploying Intune as the sole cloud management solution.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-503">ソース環境を展開を成功にするための最小要件を満たすための必要な修復チェックリストの作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-503">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-504">既存のデバイスが必要なデバイスのハードウェア要件を満たしている場合は、Windows 10 Enterprise へのアップグレードガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-504">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-505">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-505">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="c7e68-506">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="c7e68-506">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="c7e68-507">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7e68-507">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-508">Windows 10 の展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-508">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="c7e68-509">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 アプリを最大に最新のものにするために役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-509">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-510">Configuration Manager を Intune にクラウドで接続するか、Intune スタンドアロンを展開 (必要な場合) ことによって最新の管理を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-510">Providing guidance to enable modern management by cloud-attaching Configuration Manager to Intune or by deploying Intune standalone (where required).</span></span>  </li>
</ul><span data-ttu-id="c7e68-511">
  <strong>次の範囲外である </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-511">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="c7e68-512">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="c7e68-512">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-513">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-513">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-514">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="c7e68-514">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-515">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="c7e68-515">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-516">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-516">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-517">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-517">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-518">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-518">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-519">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="c7e68-519">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-520">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-520">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="c7e68-521">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-521">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-522">ソース OS: Windows 7 Enterpriseまたは Professional、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="c7e68-522">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-523">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="c7e68-523">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-524">ターゲット OS: Window 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="c7e68-524">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="c7e68-525">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-525">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-526">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="c7e68-526">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-527">Configuration Manager バージョンは、Windows 10 のターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-527">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="c7e68-528">詳細については、Configuration Manager の Windows <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">10 サポートに関する Configuration Manager のサポート テーブルを参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="c7e68-528">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="c7e68-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="c7e68-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="c7e68-530">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="c7e68-530">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="c7e68-531">次の機能に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-531">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c7e68-532">エンドポイントをセキュリティで保護するためのテクノロジを展開する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-532">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-533">Endpoint Protection とデバイスの制限プロファイルを構成する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-533">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-534">OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サード パーティの構成を含む) の評価と、Windows Defender AV サービスやその他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-534">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-535">Windows AV サービスまたはその他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-535">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-536">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="c7e68-536">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-537">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="c7e68-537">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-538">展開のガイダンス、構成サポート、教育機関:</span><span class="sxs-lookup"><span data-stu-id="c7e68-538">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-539">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="c7e68-539">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-540">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="c7e68-540">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-541">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="c7e68-541">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-542">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="c7e68-542">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-543">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="c7e68-543">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-544">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="c7e68-544">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-545">シミュレーションとチュートリアル (プラクティスのシナリオ、偽のマルウェア、自動調査など) を確認する。</span><span class="sxs-lookup"><span data-stu-id="c7e68-545">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-546">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="c7e68-546">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-547">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="c7e68-547">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-548">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-548">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-549">次のオペレーティング システム:</span><span class="sxs-lookup"><span data-stu-id="c7e68-549">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-550">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="c7e68-550">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-551">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="c7e68-551">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-552">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="c7e68-552">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-553">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="c7e68-553">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-554">Windows Server 半期チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="c7e68-554">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-555">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="c7e68-555">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="c7e68-556">
<strong>注:</strong> Windows Server のすべてのバージョンは、System Center Configuration Manager 2012 (バージョン 1012 R2、1511、1602 のバージョン) または Microsoft Endpoint Configuration Manager (バージョン 2002 以降) の最新バージョンで管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7e68-556">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="c7e68-557"></li>
</ul>

<strong>次の範囲外である </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c7e68-557"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="c7e68-558">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="c7e68-558">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-559">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="c7e68-559">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-560">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="c7e68-560">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-561">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="c7e68-561">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-562">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="c7e68-562">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-563">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="c7e68-563">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-564">Linux。</span><span class="sxs-lookup"><span data-stu-id="c7e68-564">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-565">モバイル デバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="c7e68-565">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-566">サーバー オンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-566">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-567">オフライン通信のプロキシ サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-567">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-568">Configuration Manager の下位レベルのインスタンスおよびバージョンでの Configuration Manager の展開パッケージの構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-568">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-569">Azure Security Center へのサーバーのオンボーディング。</span><span class="sxs-lookup"><span data-stu-id="c7e68-569">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-570">Configuration Manager で管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="c7e68-570">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-571">macOS オンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-571">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-572">Intune ベースの手動による展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-572">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-573">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-573">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="c7e68-574">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-574">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-575">手動展開。</span><span class="sxs-lookup"><span data-stu-id="c7e68-575">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-576">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="c7e68-576">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="c7e68-577">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="c7e68-577">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-578">アプリ コントロール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-578">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-579">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="c7e68-579">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c7e68-580">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="c7e68-580">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c7e68-581">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-581">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-582">構成またはトレーニング中に API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認します。</span><span class="sxs-lookup"><span data-stu-id="c7e68-582">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-583">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="c7e68-583">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="c7e68-584">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="c7e68-584">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="c7e68-585">Kusto クエリの使用または作成について説明するトレーニングまたはガイダンスです。</span><span class="sxs-lookup"><span data-stu-id="c7e68-585">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="c7e68-586">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="c7e68-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>
