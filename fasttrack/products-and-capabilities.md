---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。 現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。
ms.openlocfilehash: 7071187e2bc2b52930a03b4bf9dabd4f717b88df
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827107"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="59d85-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="59d85-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="59d85-105">FastTrack でサポートされているサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="59d85-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="59d85-106">このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。</span><span class="sxs-lookup"><span data-stu-id="59d85-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="59d85-107">現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="59d85-108">FastTrack は、最初にコア機能 (すべての Microsoft Online サービスに共通) を提供し、次に各対象サービスをオンボードにするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="59d85-109">全般</span><span class="sxs-lookup"><span data-stu-id="59d85-109">General</span></span>](#general)
  - [<span data-ttu-id="59d85-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="59d85-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="59d85-111">エンタープライズモビリティ & のセキュリティ</span><span class="sxs-lookup"><span data-stu-id="59d85-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="59d85-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="59d85-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="59d85-113">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="59d85-113">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="59d85-114">App Assure</span><span class="sxs-lookup"><span data-stu-id="59d85-114">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="59d85-115">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="59d85-115">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="59d85-116">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-116">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="59d85-117">全般</span><span class="sxs-lookup"><span data-stu-id="59d85-117">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-118"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-118"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-119"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-119"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-120"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-120"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="59d85-121"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-121"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="59d85-122">コアオンボードに関するリモートガイダンスを提供します。これには、サービスのプロビジョニング、テナント、およびアイデンティティ統合が含まれます。</span><span class="sxs-lookup"><span data-stu-id="59d85-122">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="59d85-123">また、Exchange Online、SharePoint Online、Microsoft Teams などのオンボードサービスの基礎を提供するための手順についても説明します。これには、 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">セキュリティ、ネットワーク接続、コンプライアンスに関する説明</a>が含まれます。</span><span class="sxs-lookup"><span data-stu-id="59d85-123">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="59d85-124">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="59d85-124">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="59d85-125"></li>
</ul>  

<strong> Id 統合 </strong></span><span class="sxs-lookup"><span data-stu-id="59d85-125"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="59d85-126">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-126">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="59d85-127">Azure AD Connect (単一または複数のフォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、azure Active Directory (Azure AD) への同期用にオンプレミスの Active Directory Id を準備します。</span><span class="sxs-lookup"><span data-stu-id="59d85-127">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="59d85-128">グループベースのライセンスを使用することを含め、一括インポートおよびライセンスを含むクラウド id を作成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-128">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="59d85-129">クラウドへの移行、パスワードハッシュ同期、パススルー認証、または Active Directory フェデレーションサービス (AD FS) に対して適切な認証方法を選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-129">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="59d85-130">単一の Active Directory フォレストを持つお客様に対して AD FS を有効にし、id を Azure AD Connect ツールと同期させます。</span><span class="sxs-lookup"><span data-stu-id="59d85-130">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="59d85-131">これには、Windows Server 2012 R2 Active Directory フェデレーションサービス2.0 またはそれ以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="59d85-131">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="59d85-132">パスワードハッシュ同期またはパススルー認証を使用して、AD FS から Azure AD に認証を移行します。</span><span class="sxs-lookup"><span data-stu-id="59d85-132">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="59d85-133">シングルサインオン (SSO) に対して、事前に統合されたアプリ (Azure AD gallery software-a service (SaaS) アプリなど) を AD FS から Azure AD に移行します。</span><span class="sxs-lookup"><span data-stu-id="59d85-133">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="59d85-134">Azure AD gallery から SSO を使用した SaaS アプリの統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-134">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="59d85-135"><a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">アプリ統合チュートリアルリスト</a>に記載されているように、事前に統合された SaaS アプリの自動ユーザープロビジョニングを有効にします (Azure AD gallery SaaS アプリと送信プロビジョニングのみに限定)。</span><span class="sxs-lookup"><span data-stu-id="59d85-135">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="59d85-136"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="59d85-136"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="59d85-137">FastTrack の特典の一環として、クラウドサービスに接続して Microsoft 365 の最高レベルのパフォーマンスを確保するためのベストプラクティスについてお勧めします。</span><span class="sxs-lookup"><span data-stu-id="59d85-137">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="59d85-138"><strong>Active Directory フォレスト</strong> これらのフォレストの機能は、機能フォレストレベルが Windows Server 2003 以降に設定されており、フォレスト構成は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="59d85-138"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-139">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="59d85-139">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="59d85-140">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="59d85-140">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-141">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="59d85-141">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-142">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="59d85-142">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="59d85-143">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="59d85-143">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="59d85-144">必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。</span><span class="sxs-lookup"><span data-stu-id="59d85-144">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="59d85-145">
  <strong>大事な：</strong>  </span><span class="sxs-lookup"><span data-stu-id="59d85-145">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="59d85-146">複数フォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-146">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="59d85-147">複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange 多重ハイブリッド構成で実装する場合、ソースフォレスト間で共有されるユーザープリンシパル名 (UPN) の名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="59d85-147">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="59d85-148">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-148">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="59d85-149">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-149">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="59d85-150">すべての複数フォレスト構成では、Active Directory フェデレーションサービス (AD FS) の展開がスコープ外になります。</span><span class="sxs-lookup"><span data-stu-id="59d85-150">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="59d85-151">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-151">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-152"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-152"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="59d85-153">次のためのリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-153">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-154">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="59d85-154">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="59d85-155">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="59d85-155">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="59d85-156">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="59d85-156">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="59d85-157">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="59d85-157">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="59d85-158">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-158">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="59d85-159">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="59d85-159">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="59d85-160">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-160">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="59d85-161">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-161">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="59d85-162">また、以前のバージョンの Office で作業したマクロまたはアドインがあり、互換性の問題が発生した場合は、アプリの保証プログラムを通じて追加費用なしで互換性の問題を修復するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-162">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="59d85-163">詳細については、「 <strong>アプリ</strong> で <a href="#windows-10">Windows 10</a> の一部を確認する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-163">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="59d85-164">オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-164">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-165"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-165"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="59d85-166">組織のサイトが Microsoft の <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ネットワーク接続の原則</a>とどのように連携しているかを示す、環境からの主要なネットワーク接続データの取得と解釈に関するリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-166">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="59d85-167">これにより、移行速度、ユーザー環境、サービスのパフォーマンス、および信頼性に直接影響するネットワークスコアが強調されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-167">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="59d85-168">また、このデータで強調表示されている修復手順についても説明し、ネットワークのスコアを向上します。</span><span class="sxs-lookup"><span data-stu-id="59d85-168">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="59d85-169">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="59d85-169">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="59d85-170">Microsoft 365 アプリの最新バージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="59d85-170">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="59d85-171"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 管理センター (プレビュー) でのネットワークパフォーマンスに関する推奨事項</a>として有効になる場所サービス。</span><span class="sxs-lookup"><span data-stu-id="59d85-171">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="59d85-172">Office 365</span><span class="sxs-lookup"><span data-stu-id="59d85-172">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-173"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-173"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-174"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-174"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-175"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-175"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="59d85-176"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-176"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="59d85-177">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="59d85-177">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="59d85-178">正確な手順は、ソース環境と電子メール移行プランによって異なります。</span><span class="sxs-lookup"><span data-stu-id="59d85-178">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="59d85-179">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-179">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-180">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="59d85-180">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-181">メール交換 (MX) レコードを Office 365 に接続します。</span><span class="sxs-lookup"><span data-stu-id="59d85-181">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-182">サブスクリプションサービスの一部である場合は、Office 365 ATP 機能をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="59d85-182">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="59d85-183">詳細については、この表の「 <strong>Office 365 Advanced Threat Protection</strong> 」の部分を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-183">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="59d85-p113">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="59d85-p114">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="59d85-188">
  <strong>注:</strong> メールボックスレプリケーションサービス (MR) は、社内メールボックスから対応する Exchange Online メールボックスに Information Rights Managed (IRM) メールを移行しようとします。</span><span class="sxs-lookup"><span data-stu-id="59d85-188">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="59d85-189">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="59d85-189">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="59d85-190">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-190">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="59d85-191">DNS のセットアップ。必須の自動検出、sender policy framework (SPF)、DomainKeys 識別メール (DKIM)、ドメインベースのメッセージ認証、レポートと準拠 (DMARC)、および MX レコード (必要な場合) を含みます。</span><span class="sxs-lookup"><span data-stu-id="59d85-191">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="59d85-192">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="59d85-192">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="59d85-193">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="59d85-193">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-194">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-194">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="59d85-195">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="59d85-195">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="59d85-196">Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-196">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="59d85-197">ソース環境には、次の最低レベルのいずれかが必要です。</span><span class="sxs-lookup"><span data-stu-id="59d85-197">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-198">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="59d85-198">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="59d85-199">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="59d85-199">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="59d85-200">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="59d85-200">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="59d85-201">複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online の複数地域機能</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-201">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="59d85-202">Project for Office 365、Outlook for Windows、Outlook for iOS および Android 用の outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for business などのオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office のシステム要件</a>」で定義されている最低レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-202">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-203"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-203"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="59d85-204">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-204">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-205">情報ガバナンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-205">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="59d85-206">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-206">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-207">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-207">Records management.</span></span>  </li>
<li>  <span data-ttu-id="59d85-208">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-208">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-209">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-209">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="59d85-210">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-210">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="59d85-211">Advanced eDiscovery。</span><span class="sxs-lookup"><span data-stu-id="59d85-211">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-212"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-212">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-213"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-213"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="59d85-214">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-214">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-215">データの分類。</span><span class="sxs-lookup"><span data-stu-id="59d85-215">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="59d85-216">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="59d85-216">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="59d85-217">秘密度ラベルの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-217">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="59d85-218">秘密度ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="59d85-218">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="59d85-219">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="59d85-219">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="59d85-220">トレーニング可能な分類子。</span><span class="sxs-lookup"><span data-stu-id="59d85-220">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="59d85-221">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。</span><span class="sxs-lookup"><span data-stu-id="59d85-221">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="59d85-222">ポリシーを使用したラベルの発行 (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="59d85-222">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="59d85-223">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-223">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="59d85-224">Microsoft エンドポイントマネージャーで管理されるデバイスの DLP ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-224">Creating DLP policies for devices managed by Microsoft Endpoint Manager.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-225"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-225">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-226"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-226"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="59d85-227">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-227">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-228">Teams をサポートするために、Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD の最小要件を確認します。</span><span class="sxs-lookup"><span data-stu-id="59d85-228">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="59d85-229">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-229">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="59d85-230">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="59d85-230">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="59d85-231">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="59d85-231">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="59d85-232">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-232">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="59d85-233">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="59d85-233">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-234">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="59d85-234">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="59d85-235">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="59d85-235">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="59d85-236">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="59d85-236">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="59d85-237">Teams app policy (Teams web app、Teams デスクトップアプリ、および iOS および Android アプリの Teams) を構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-237">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="59d85-238">該当する場合は、次のようなガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-238">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-239">Microsoft Teams のルームデバイス:</span><span class="sxs-lookup"><span data-stu-id="59d85-239">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="59d85-240"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-240">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="59d85-241">認定された Microsoft Teams ルームデバイスのサービス側の構成を使用したリモートアシスタンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-241">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="59d85-242">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="59d85-242">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="59d85-243">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="59d85-243">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="59d85-244">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="59d85-244">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="59d85-245">電話システム:</span><span class="sxs-lookup"><span data-stu-id="59d85-245">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-246">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="59d85-246">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="59d85-247">通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能なマーケット</a>):</span><span class="sxs-lookup"><span data-stu-id="59d85-247">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="59d85-248">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="59d85-248">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="59d85-249">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-249">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="59d85-250">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="59d85-250">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-251">ダイレクトルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="59d85-251">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-252">パートナーによってホストされるシナリオの直接ルーティング設計のための組織のセットアップガイダンス、または最大10サイトの顧客展開シナリオ。</span><span class="sxs-lookup"><span data-stu-id="59d85-252">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="59d85-253">セッションボーダーコントローラー (SBC) 構成のレビュー。</span><span class="sxs-lookup"><span data-stu-id="59d85-253">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="59d85-254">ダイヤルプラン構成を使用したリモートアシスタンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-254">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="59d85-255">音声ルート構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-255">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="59d85-256">メディアバイパスとローカルメディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="59d85-256">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="59d85-257">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-257">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="59d85-258">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="59d85-258">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="59d85-259">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-259">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="59d85-260">Office 365 の Azure AD で有効になっている id。</span><span class="sxs-lookup"><span data-stu-id="59d85-260">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-261">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="59d85-261">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="59d85-262">Exchange メールボックスが存在する (Exchange ハイブリッド構成でオンラインおよびオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="59d85-262">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="59d85-263">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="59d85-263">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="59d85-264">
  <strong>注:</strong> ユーザーが SharePoint Online のライセンスで割り当てられて有効になっていない場合は、Office 365 の OneDrive for Business ストレージはありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-264">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="59d85-265">ファイル共有はチャネル内でも引き続き機能しますが、Office 365 の OneDrive for business ストレージを使用せずに、ユーザーはチャットでファイルを共有できません。</span><span class="sxs-lookup"><span data-stu-id="59d85-265">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="59d85-266">Teams は、オンプレミスの SharePoint をサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-266">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="59d85-267">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが Exchange Online 上にメールボックスを配置することです。</span><span class="sxs-lookup"><span data-stu-id="59d85-267">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="59d85-268">オンプレミスのメールボックスを持つユーザーは、Azure AD Connect を使用して、Office 365 ディレクトリにその id を同期する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-268">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="59d85-269">これらの Exchange ハイブリッドユーザーの場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成することはできません。</span><span class="sxs-lookup"><span data-stu-id="59d85-269">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="59d85-270">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="59d85-270">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-271"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-271"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="59d85-272">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-272">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-273">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-273">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="59d85-274">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-274">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="59d85-275">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="59d85-275">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="59d85-276">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="59d85-276">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-277"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-277">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-278"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-278"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="59d85-279">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-279">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-280">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="59d85-280">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="59d85-281">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="59d85-281">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="59d85-282">Outlook mobile をセキュリティで保護する (詳細については <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">、「Exchange Online で outlook For iOS と outlook For Android を保護</a> する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="59d85-282">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="59d85-283">Office 365 の Azure AD で有効になっている id。</span><span class="sxs-lookup"><span data-stu-id="59d85-283">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-284">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="59d85-284">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-285"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-285"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="59d85-286">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-286">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-287">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="59d85-287">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="59d85-288">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-288">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-289">Power BI Desktop のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-289">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-290"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-290"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="59d85-291">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-291">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-292">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="59d85-292">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="59d85-293">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="59d85-293">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="59d85-294">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="59d85-294">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="59d85-295">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-295">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-296">「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-296">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-297"><strong>Project Online Professional および Premium</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-297"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="59d85-298">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-298">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-299">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="59d85-299">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="59d85-300">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="59d85-300">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="59d85-301">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="59d85-301">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="59d85-302">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-302">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="59d85-303">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="59d85-303">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="59d85-304">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="59d85-304">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-305">「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-305">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-306"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-306"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="59d85-307">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-307">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-308">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="59d85-308">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="59d85-309">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-309">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="59d85-310">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="59d85-310">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="59d85-311">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-311">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="59d85-312">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="59d85-312">Planning site collections.</span></span></li>
<li><span data-ttu-id="59d85-313">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-313">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="59d85-314">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-314">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="59d85-315">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-315">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="59d85-316">移行方法。</span><span class="sxs-lookup"><span data-stu-id="59d85-316">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="59d85-317">SharePoint のバージョンによっては、次のように、OneDrive for Business に関する追加のガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-317">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-318">統合オプションを識別し、オンプレミスおよびオンラインのネットワークインフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="59d85-318">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="59d85-319">SharePoint Online 2013 SP1 (該当する場合) のインストール、同期および id の要件の計画と実装、および OneDrive for Business 同期クライアントの識別を行います。</span><span class="sxs-lookup"><span data-stu-id="59d85-319">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="59d85-320">すべてのユーザー (または段階的なロールアウト) に対して単一のロールアウトを計画し、実装します。</span><span class="sxs-lookup"><span data-stu-id="59d85-320">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="59d85-321">ライセンスの割り当て、個人用サイトおよび個人用ドキュメントライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に該当)、対象ユーザーを設定して OneDrive へのアクセスを制御する (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="59d85-321">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="59d85-322">既知のフォルダーを OneDrive にリダイレクトまたは移動します。</span><span class="sxs-lookup"><span data-stu-id="59d85-322">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="59d85-323">OneDrive for Business クライアントの同期を展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-323">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="59d85-324">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="59d85-324">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="59d85-325">Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-325">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="59d85-326"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-326"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="59d85-327">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツタイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネットサイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービスサイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="59d85-327">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="59d85-328">
  <strong>注:</strong> セルフサービスサイト作成は、SharePoint 2013 を実行しているオンプレミスサーバーの範囲内にありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-328">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="59d85-329">SharePoint ハイブリッドを有効にするには、次のオンプレミスの SharePoint Server 環境のうちの1つが必要です。2013、2016、または2019。</span><span class="sxs-lookup"><span data-stu-id="59d85-329">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="59d85-330">
  <strong>注:</strong> オンプレミスの SharePoint 環境の SharePoint Server へのアップグレードは、スコープ内にありません。</span><span class="sxs-lookup"><span data-stu-id="59d85-330">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="59d85-331">詳細については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-331">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="59d85-332">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint ハイブリッド機能の最小パブリック更新プログラムレベル</a>」を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="59d85-332">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="59d85-333">
  <strong>注:</strong>複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 の「OneDrive および SharePoint Online の複数地域機能</a>」を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="59d85-333">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-334"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-334"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="59d85-335">Yammer Enterprise service を有効にするためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-335">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="59d85-336">オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-336">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="59d85-337">エンタープライズモビリティ & のセキュリティ</span><span class="sxs-lookup"><span data-stu-id="59d85-337">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-338"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-338"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="59d85-339">次のシナリオでは、クラウド id を保護するためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-339">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="59d85-340">

<strong>セキュリティ保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="59d85-340">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="59d85-341">Azure 多要素認証 (MFA) (クラウドのみ)、Microsoft Authenticator アプリ、および Azure MFA とセルフサービスのパスワードのリセット (SSPR) の組み合わせを含む、強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-341">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="59d85-342">非 Azure AD Premium のお客様の場合は、セキュリティの既定値を使用して id をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-342">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="59d85-343">Azure AD premium のお客様の場合、条件付きアクセスを使用して id をセキュリティで保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="59d85-343">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="59d85-344">Azure AD パスワード保護を使用して、脆弱なパスワードの使用を検出およびブロックします。</span><span class="sxs-lookup"><span data-stu-id="59d85-344">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="59d85-345">Azure AD アプリケーションプロキシを使用したオンプレミスの web アプリケーションへのリモートアクセスをセキュリティで保護する。</span><span class="sxs-lookup"><span data-stu-id="59d85-345">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="59d85-346">Azure Id 保護を使用したリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-346">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="59d85-347">ロゴ、テキスト、イメージを含むカスタマイズされたサインイン画面を有効にして、カスタムブランド化します。</span><span class="sxs-lookup"><span data-stu-id="59d85-347">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="59d85-348">Azure AD B2B を使用して、アプリやサービスをゲストユーザーと安全に共有できます。</span><span class="sxs-lookup"><span data-stu-id="59d85-348">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="59d85-349">役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権のある管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="59d85-349">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="59d85-350">ハイブリッド Azure AD join を構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-350">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="59d85-351">Azure AD join を構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-351">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="59d85-352">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-352">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-353">Azure AD Connect Health を使用して AD FS、Azure AD Connect、およびドメインコントローラーのリモート監視を有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-353">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="59d85-354">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-354">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-355">Azure ad 受給管理を使用して、Azure AD id とアクセスのライフサイクルをスケールで管理します。</span><span class="sxs-lookup"><span data-stu-id="59d85-355">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="59d85-356">Azure ad グループメンバーシップ、エンタープライズアプリアクセス、および Azure AD アクセスレビューを使用したロール割り当てを管理します。</span><span class="sxs-lookup"><span data-stu-id="59d85-356">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-357">Azure AD の使用条件を確認します。</span><span class="sxs-lookup"><span data-stu-id="59d85-357">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-358">Azure AD 特権 Id 管理を使用して、特権のある管理者アカウントへのアクセスを管理および制御します。</span><span class="sxs-lookup"><span data-stu-id="59d85-358">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="59d85-359">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-359">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-360">Azure AD SSPR を有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-360">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="59d85-361">ユーザーが Azure AD セルフサービスグループ管理を使用して、独自のクラウドセキュリティまたは Office 365 グループを作成および管理できるようにします。</span><span class="sxs-lookup"><span data-stu-id="59d85-361">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="59d85-362">Azure AD 委任されたグループ管理を使用して、エンタープライズアプリへの委任されたアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="59d85-362">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="59d85-363">Azure AD の動的グループを有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-363">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="59d85-364">コレクションを使用して、個人用アプリポータルでアプリを整理します。</span><span class="sxs-lookup"><span data-stu-id="59d85-364">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="59d85-365">オンプレミスの Active Directory とその環境は Azure ad Premium 用に準備されています。これには、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復が含まれています。</span><span class="sxs-lookup"><span data-stu-id="59d85-365">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="59d85-366"><strong>Azure Information Protection (P2 または EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-366"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="59d85-367">次の方法についてのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-367">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-368">テナントのアクティブ化と構成を行います。</span><span class="sxs-lookup"><span data-stu-id="59d85-368">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="59d85-369">ラベルおよびポリシーの作成および設定。</span><span class="sxs-lookup"><span data-stu-id="59d85-369">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-370">情報保護のドキュメントへの適用。</span><span class="sxs-lookup"><span data-stu-id="59d85-370">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="59d85-371">Windows で実行され、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) での自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="59d85-371">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="59d85-372">Azure Information Protection スキャナーを使用した、保管中ファイルの使用。</span><span class="sxs-lookup"><span data-stu-id="59d85-372">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="59d85-373">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="59d85-373">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="59d85-374">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用する場合も、ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-374">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="59d85-375">既に次のことを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-375">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-376">Azure AD を使用します。</span><span class="sxs-lookup"><span data-stu-id="59d85-376">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="59d85-377">Windows または iOS のどちらか (他のオペレーティングシステムがスコープ外) を使用します。</span><span class="sxs-lookup"><span data-stu-id="59d85-377">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="59d85-378">
<strong>注</strong>: コンピューターとモバイルデバイスは、Azure Information Protection をサポートする <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">オペレーティングシステム</a> で実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-378">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="59d85-379">メインファイル共有場所を用意します。</span><span class="sxs-lookup"><span data-stu-id="59d85-379">Have your main file share locations.</span></span>  </li><span data-ttu-id="59d85-380">
<strong>注</strong>: ハイブリッドサポートには、AD RMS コネクタが必要です。</span><span class="sxs-lookup"><span data-stu-id="59d85-380">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="59d85-381">分類の分類が承認されている。</span><span class="sxs-lookup"><span data-stu-id="59d85-381">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="59d85-382">保護されたキーの管理に関する規制の制限について説明します。</span><span class="sxs-lookup"><span data-stu-id="59d85-382">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="59d85-383">
</ul>
  
<strong>Azure Information Protection スキャナー</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-383">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="59d85-384">既に次のことを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-384">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="59d85-385">Windows Server 2012 R2 または Windows Server 2016 を使用します。</span><span class="sxs-lookup"><span data-stu-id="59d85-385">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="59d85-386">インターネットに接続されている。</span><span class="sxs-lookup"><span data-stu-id="59d85-386">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="59d85-387">ローカルまたはリモートのインスタンスで Microsoft SQL Server 2012 以降が必要です。</span><span class="sxs-lookup"><span data-stu-id="59d85-387">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="59d85-388">オンプレミスの Active Directory に対してサービスアカウントを作成し、Azure AD と同期させます。</span><span class="sxs-lookup"><span data-stu-id="59d85-388">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="59d85-389">AzInfoProtection.exe をダウンロードしました。</span><span class="sxs-lookup"><span data-stu-id="59d85-389">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="59d85-390">自動分類/保護に対してラベルを構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-390">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-391"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-391"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="59d85-392">アプリとデバイスのための、クラウドベースのモバイルデバイス管理 (MDM) およびモバイルアプリ管理 (MAM) プロバイダーとして Intune を使用するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-392">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="59d85-393">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="59d85-393">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="59d85-394">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="59d85-394">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-395">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="59d85-395">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="59d85-396">オンプレミスの Active Directory またはクラウド id (Azure AD) を活用して、Intune で使用される id を構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-396">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="59d85-397">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-397">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="59d85-398">次のような管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-398">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-399">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="59d85-399">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-400">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="59d85-400">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-401">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-401">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-402">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="59d85-402">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-403">Web リンクまたはディープリンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-403">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="59d85-404">条件付きアクセスポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-404">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-405">組織内に既存の証明機関、ワイヤレスネットワーク、または VPN インフラストラクチャがある場合に、電子メール、ワイヤレスネットワーク、および VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-405">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="59d85-406">Intune データウェアハウスに接続します。</span><span class="sxs-lookup"><span data-stu-id="59d85-406">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="59d85-407">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="59d85-407">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-408">リモートアシスタンスのチームビューアー (チームビューアーサブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="59d85-408">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="59d85-409">モバイル脅威防御 (MTD) パートナーソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="59d85-409">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="59d85-410">電気通信経費管理ソリューション (電気通信経費管理ソリューションサブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="59d85-410">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="59d85-411">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="59d85-411">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-412">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="59d85-412">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="59d85-413">アプリ保護ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="59d85-413">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-414">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-414">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="59d85-415">管理対象アプリの条件付きアクセスポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="59d85-415">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="59d85-416">前述の MAM ポリシーを使用して、適切なユーザーグループを対象にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-416">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-417">管理対象アプリの使用状況レポートを使用します。</span><span class="sxs-lookup"><span data-stu-id="59d85-417">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-418">レガシ PC 管理から Intune MDM への移行ガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="59d85-418">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="59d85-419">
  <strong>注</strong>: レガシ PC 管理は、2020年10月15日以降ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-419">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="59d85-420"></li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-420"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="59d85-421">ここでは、Intune を使用した既存の Configuration Manager 環境のクラウド接続の準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="59d85-421">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="59d85-422">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="59d85-422">The exact steps depend on your source environment.</span></span> <span data-ttu-id="59d85-423">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="59d85-423">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="59d85-424">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="59d85-424">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="59d85-425">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-425">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="59d85-426">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-426">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="59d85-427">ハイブリッド Azure AD join を設定するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-427">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="59d85-428">MDM 自動登録用に Azure AD をセットアップするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-428">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="59d85-429">クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="59d85-429">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="59d85-430">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-430">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="59d85-431">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="59d85-431">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="59d85-432"><strong>IOS および Android 用の Outlook mobile を安全に展開する</strong> ユーザーが必要なすべてのアプリをインストールしていることを確認するために、iOS および Android 用の Outlook mobile を組織に安全に展開するためのガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="59d85-432"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="59d85-433">Intune を使用して iOS および Android 用の Outlook mobile を安全に展開するための手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="59d85-433">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="59d85-434">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="59d85-434">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-435">Apple App Store または Google Play ストアを介して、iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="59d85-435">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="59d85-436">セットアップのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-436">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-437">IOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリの展開 (Intune)。</span><span class="sxs-lookup"><span data-stu-id="59d85-437">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="59d85-438">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-438">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-439">条件付きアクセスポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="59d85-440">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="59d85-440">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="59d85-441"><strong>注</strong>: fasttrack は、Exchange モバイルデバイスメールボックスポリシーを使用して IOS および Android 用の Outlook のセキュリティ保護をサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-441"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="59d85-442">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-442">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="59d85-443">IT 管理者は、Intune を使用してワイヤレスネットワークおよび VPN プロファイルを展開する計画を立てるときに、既存の証明機関、ワイヤレスネットワーク、および VPN インフラストラクチャを運用環境で既に稼働している必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-443">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="59d85-444"><strong>注</strong>: fasttrack サービス特典には、Intune の証明機関、ワイヤレスネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書をセットアップまたは構成するための支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-444"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="59d85-445"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-445"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="59d85-446">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-446">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="59d85-447"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-447"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="59d85-448"><strong>注</strong>: MICROSOFT Defender ATP との Intune の統合、および Windows 10 のリスクレベルの評価に基づくデバイスコンプライアンスポリシーの作成に関する支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="59d85-448"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="59d85-449">購入、ライセンス、またはライセンス認証についてのサポートは提供していません。</span><span class="sxs-lookup"><span data-stu-id="59d85-449">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="59d85-450">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-450">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="59d85-451"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-451"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="59d85-452">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-452">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="59d85-453"><strong>IOS および Android 用の Outlook を、Intune を使用して安全に展開する </strong></span><span class="sxs-lookup"><span data-stu-id="59d85-453"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="59d85-454">Office 365 の Azure AD で有効になっているユーザー id。</span><span class="sxs-lookup"><span data-stu-id="59d85-454">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-455">ユーザーライセンスが割り当てられている exchange Online またはハイブリッド Exchange。</span><span class="sxs-lookup"><span data-stu-id="59d85-455">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="59d85-456">Windows 10</span><span class="sxs-lookup"><span data-stu-id="59d85-456">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-457"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-457"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-458"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-458"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-459"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-459"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="59d85-460"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-460"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="59d85-461">Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-461">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="59d85-462">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-462">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-463">Windows 10 の目的を理解します。</span><span class="sxs-lookup"><span data-stu-id="59d85-463">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="59d85-464">ソース環境と要件を評価します (Windows 10 展開をサポートするために、Microsoft エンドポイント構成マネージャーが必要なレベルにアップグレードされていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="59d85-464">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="59d85-465">Microsoft エンドポイント構成マネージャーまたは Microsoft 365 を使用して、Windows 10 Enterprise と Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-465">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="59d85-466">Windows 10 アプリを評価するためのオプションを推奨します。</span><span class="sxs-lookup"><span data-stu-id="59d85-466">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="59d85-467">デスクトップ分析展開計画の作成による、デスクトップ分析およびガイダンスの使用を有効にする。</span><span class="sxs-lookup"><span data-stu-id="59d85-467">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="59d85-468">Microsoft 365 アプリの互換性評価は、構成マネージャーで Office 365 レディネスダッシュボードを活用するか、またはスタンドアロンの準備ツールキットを使用して Office plus Microsoft 365 アプリを展開することによって評価されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-468">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="59d85-469">展開を成功させるために、ソース環境を最小要件にするために必要な作業について、修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-469">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="59d85-470">必要なデバイスハードウェア要件を満たしている場合は、既存のデバイスのアップグレードガイダンスを Windows 10 Enterprise に提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-470">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="59d85-471">既存の展開の動きをサポートするためのアップグレードガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-471">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="59d85-472">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="59d85-472">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="59d85-473">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="59d85-473">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="59d85-474">Windows 10 展開の一環として構成マネージャーを使用して、Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-474">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="59d85-475">既存の構成マネージャー環境または Microsoft 365 を使用して、Windows 10 Enterprise および Microsoft 365 アプリを使用して、組織が最新の状態を維持するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-475">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="59d85-476">
  <strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-476">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="59d85-477">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="59d85-477">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="59d85-478">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-478">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="59d85-479">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="59d85-479">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="59d85-480">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="59d85-480">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="59d85-481">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="59d85-481">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="59d85-482">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-482">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="59d85-483">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-483">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="59d85-484">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="59d85-484">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="59d85-485">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="59d85-486">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-486">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-487">ソース OS: Windows 7 Enterprise または Professional、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="59d85-487">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="59d85-488">デバイス: デスクトップ、ノートブック、またはタブレットフォームファクター。</span><span class="sxs-lookup"><span data-stu-id="59d85-488">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="59d85-489">ターゲット OS: Window 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="59d85-489">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="59d85-490">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-490">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-491">Microsoft エンドポイント構成マネージャー。</span><span class="sxs-lookup"><span data-stu-id="59d85-491">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="59d85-492">構成マネージャーのバージョンは、Windows 10 のターゲットのバージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-492">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="59d85-493">詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-493">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="59d85-494"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-494"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="59d85-495">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="59d85-495">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="59d85-496">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-496">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-497">エンドポイントをセキュリティで保護するためのテクノロジを展開する。</span><span class="sxs-lookup"><span data-stu-id="59d85-497">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="59d85-498">エンドポイント保護とデバイス制限プロファイルを構成する。</span><span class="sxs-lookup"><span data-stu-id="59d85-498">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="59d85-499">Windows Defender AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態、および Intune、Microsoft エンドポイント構成マネージャー、グループポリシーオブジェクト (Gpo)、サードパーティの構成を含む、OS バージョンとデバイスの管理を評価します。</span><span class="sxs-lookup"><span data-stu-id="59d85-499">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="59d85-500">Windows AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="59d85-500">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="59d85-501">ネットワークトラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="59d85-501">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="59d85-502">オンボードエンドポイントを使用して ATP エージェントプロファイルを展開する方法について説明することにより、Microsoft Defender ATP サービスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="59d85-502">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="59d85-503">展開のガイダンス、構成の支援、および教育:</span><span class="sxs-lookup"><span data-stu-id="59d85-503">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-504">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-504">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-505">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="59d85-505">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-506">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="59d85-506">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-507">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="59d85-507">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-508">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="59d85-508">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-509">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="59d85-509">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-510">シミュレーションとチュートリアル (プラクティスシナリオ、偽のマルウェア、自動調査など) をレビューします。</span><span class="sxs-lookup"><span data-stu-id="59d85-510">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="59d85-511">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="59d85-511">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="59d85-512">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="59d85-512">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="59d85-513">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="59d85-513">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="59d85-514">次のオペレーティングシステム。</span><span class="sxs-lookup"><span data-stu-id="59d85-514">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-515">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="59d85-515">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-516">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="59d85-516">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-517">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="59d85-517">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-518">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="59d85-518">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-519">Windows Server Semi-Annual Channel (SAC) バージョン1803。</span><span class="sxs-lookup"><span data-stu-id="59d85-519">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-520">macOS バージョン10.13、10.14、および10.15。</span><span class="sxs-lookup"><span data-stu-id="59d85-520">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="59d85-521">
<strong>注:</strong> Windows Server のすべてのバージョンは、System Center Configuration Manager 2012 (バージョン 1012 R2、1511、または 1602) または Microsoft エンドポイント構成マネージャー (バージョン2002以上) の最新バージョンで管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-521">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="59d85-522"></li>
</ul>

<strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-522"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="59d85-523">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-523">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="59d85-524">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="59d85-524">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="59d85-525">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="59d85-525">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="59d85-526">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="59d85-526">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-527">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="59d85-527">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-528">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="59d85-528">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-529">マシン.</span><span class="sxs-lookup"><span data-stu-id="59d85-529">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-530">モバイルデバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="59d85-530">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-531">サーバーのオンボードと構成:</span><span class="sxs-lookup"><span data-stu-id="59d85-531">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-532">オフライン通信用のプロキシサーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="59d85-532">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-533">下位レベルの構成マネージャーのインスタンスとバージョンで構成マネージャーの展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="59d85-533">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-534">Azure セキュリティセンターへのオンボードサーバー。</span><span class="sxs-lookup"><span data-stu-id="59d85-534">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-535">構成マネージャーで管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="59d85-535">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-536">macOS のオンボードと構成:</span><span class="sxs-lookup"><span data-stu-id="59d85-536">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-537">手動による Intune ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-537">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-538">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-538">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="59d85-539">その他のモバイルデバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-539">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-540">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-540">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-541">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="59d85-541">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-542">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="59d85-542">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-543">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="59d85-543">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-544">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="59d85-544">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-545">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="59d85-545">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="59d85-546">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-546">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="59d85-547">構成またはトレーニング API またはセキュリティ情報およびイベント管理 (SIEM) 接続を確認します。</span><span class="sxs-lookup"><span data-stu-id="59d85-547">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="59d85-548">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="59d85-548">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="59d85-549">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-549">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="59d85-550">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="59d85-550">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="59d85-551">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-551">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="59d85-552">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="59d85-552">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-553"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-553"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-554"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-554"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-555"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-555"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="59d85-556"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-556"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="59d85-557">Windows 仮想デスクトップ (デスクトップおよびアプリ仮想化サービス) のオンボードに関する展開のガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="59d85-557">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="59d85-558">Windows 仮想デスクトップは、Windows 10 の複数セッション環境を活用しており、microsoft 365 Apps for Enterprise for Microsoft 365 の統合セキュリティと管理に最適化されています。</span><span class="sxs-lookup"><span data-stu-id="59d85-558">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="59d85-559">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-559">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="59d85-560">次の方法を使用して、windows 10 Enterprise マルチセッションおよびエンタープライズ向け Microsoft 365 アプリを使用して、Windows 仮想デスクトップ環境を展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-560">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="59d85-561">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="59d85-561">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="59d85-562">共有画像。</span><span class="sxs-lookup"><span data-stu-id="59d85-562">Shared image.</span></span></li>
<li><span data-ttu-id="59d85-563">Office 展開ツールキット (ODT)。</span><span class="sxs-lookup"><span data-stu-id="59d85-563">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="59d85-564">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="59d85-564">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="59d85-565">プロファイルコンテナーを使用して FSLogix エージェントを展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-565">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="59d85-566">Office コンテナーと共に FSLogix エージェントを展開します。</span><span class="sxs-lookup"><span data-stu-id="59d85-566">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="59d85-567">コンテンツ除外を使用して FSLogix フォルダーを構成します。</span><span class="sxs-lookup"><span data-stu-id="59d85-567">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="59d85-568">Microsoft Edge を展開する。</span><span class="sxs-lookup"><span data-stu-id="59d85-568">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="59d85-569">Microsoft Teams を展開する。</span><span class="sxs-lookup"><span data-stu-id="59d85-569">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="59d85-570">Windows 仮想デスクトップクライアントを使用して接続します。</span><span class="sxs-lookup"><span data-stu-id="59d85-570">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="59d85-571">

<strong>次の範囲外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="59d85-571">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="59d85-572">お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-572">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="59d85-573">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="59d85-573">On-site support.</span></span></li>
<li><span data-ttu-id="59d85-574">サードパーティ製のアプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="59d85-574">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="59d85-575">カスタムイメージ。</span><span class="sxs-lookup"><span data-stu-id="59d85-575">Custom images.</span></span></li>
<li><span data-ttu-id="59d85-576">VMware および Citrix に関連する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="59d85-576">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="59d85-577">Linux シナリオ。</span><span class="sxs-lookup"><span data-stu-id="59d85-577">Linux scenarios.</span></span></li>
<li><span data-ttu-id="59d85-578">ユーザープロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="59d85-578">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="59d85-579">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-579">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="59d85-580">既に次のものがあるはずです。</span><span class="sxs-lookup"><span data-stu-id="59d85-580">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="59d85-581"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 仮想デスクトップのライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="59d85-581"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="59d85-582">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="59d85-582">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="59d85-583">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="59d85-583">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="59d85-584">ファイアウォールとネットワークセキュリティグループ。</span><span class="sxs-lookup"><span data-stu-id="59d85-584">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="59d85-585">VPN および ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="59d85-585">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="59d85-586">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="59d85-586">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="59d85-587">Windows 仮想デスクトップへの接続を許可するファイアウォールルール。</span><span class="sxs-lookup"><span data-stu-id="59d85-587">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="59d85-588">詳細については、「 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> サポートされているリモートデスクトップクライアント</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-588">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="59d85-589">Azure AD 全般のセットアップ:</span><span class="sxs-lookup"><span data-stu-id="59d85-589">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="59d85-590">Id 戦略 <i>(次の3つのオプションのうち1つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="59d85-590">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="59d85-591">Azure AD Connect がある Active Directory。</span><span class="sxs-lookup"><span data-stu-id="59d85-591">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="59d85-592">VPN または ExpressRoute 経由の Azure AD Connect オンプレミスの Active Directory。</span><span class="sxs-lookup"><span data-stu-id="59d85-592">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="59d85-593">Active Directory ドメインサービス (AD DS)。</span><span class="sxs-lookup"><span data-stu-id="59d85-593">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="59d85-594">App Assure</span><span class="sxs-lookup"><span data-stu-id="59d85-594">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-595"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-595"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-596"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-596"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-597"><strong>サポートされる製品</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-597"><strong>Supported products</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-598"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-598"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="59d85-599">アプリの保証は、Windows 10 および Microsoft 365 アプリの互換性に関する問題に対処するように設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="59d85-599">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="59d85-600">アプリにサービスを提供することを要求した場合は、お客様と協力して、有効なアプリの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="59d85-600">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="59d85-601">また、Windows 仮想デスクトップと新しい Microsoft Edge を展開し、互換性の問題を解決するための適切な取り組みを行う際に、互換性の問題に直面しているお客様にガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-601">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="59d85-602">次の Microsoft 製品に展開されているアプリの修復サポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-602">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="59d85-603"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="59d85-603"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="59d85-604"><strong>Microsoft 365 アプリ</strong>  </span><span class="sxs-lookup"><span data-stu-id="59d85-604"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="59d85-605"><strong>新しい Microsoft Edge-</strong> 展開のガイダンスについては、「 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge チャネルの概要</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-605"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="59d85-606"><strong>Windows 仮想デスクトップ</strong> - 詳細については、「 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows 仮想デスクトップ</a> と <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">windows 10 ENTERPRISE マルチセッション FAQ</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-606"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="59d85-607">

<strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-607">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="59d85-608">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="59d85-608">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="59d85-609">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-609">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="59d85-610">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-610">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="59d85-611">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="59d85-611">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="59d85-612">詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-612">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="59d85-613">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="59d85-613">App packaging-only services.</span></span> <span data-ttu-id="59d85-614">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="59d85-614">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="59d85-615">

<strong>お客様の責任を含む</strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-615">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="59d85-616">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="59d85-616">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="59d85-617">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="59d85-617">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="59d85-618">
<strong>注:</strong>  Microsoft は、ソースコードに変更を加えることはできません。</span><span class="sxs-lookup"><span data-stu-id="59d85-618">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="59d85-619">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="59d85-619">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="59d85-620">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="59d85-620">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="59d85-621"><strong>Windows 10 および Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="59d85-621"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-622">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="59d85-622">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="59d85-623">
<strong>ARM 版 Windows 10</strong>
</span><span class="sxs-lookup"><span data-stu-id="59d85-623">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="59d85-624">Windows 7、Office 2010、またはそれ以降のバージョンで動作していたアプリは、ARM64 デバイス上の Windows 10 および Microsoft 365 アプリで動作します。</span><span class="sxs-lookup"><span data-stu-id="59d85-624">Apps that worked on Windows 7, Office 2010, or later versions work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="59d85-625">
  <strong>注:</strong> ARM の除外と制限については、次の Windows 10 をご用意しています。</span><span class="sxs-lookup"><span data-stu-id="59d85-625">
  <strong>Note:</strong> Windows 10 on ARM exclusions and limitations include:</span></span>
<ul>
<li>  
 <span data-ttu-id="59d85-626">ARM に対応していないソフトウェアドライバーに依存しているアプリ。</span><span class="sxs-lookup"><span data-stu-id="59d85-626">Apps that rely on software drivers that aren’t compatible in ARM.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-627">OpenGL または OpenCL を使用するアプリ。</span><span class="sxs-lookup"><span data-stu-id="59d85-627">Apps that use OpenGL or OpenCL.</span></span>   
  </li>
<li>  
  <span data-ttu-id="59d85-628">アプリは64ビット (x64) でのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="59d85-628">Apps only available in 64-bit (x64).</span></span>  
  </li>
</ul><span data-ttu-id="59d85-629">
<strong>新しい Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="59d85-629">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-630">Web アプリまたはサイトが Internet Explorer 11、サポート対象バージョンの Google Chrome、または Microsoft Edge のいずれかのバージョンで動作する場合、それらは新しい Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="59d85-630">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-631">Web は常に進化していますが、 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge のサイト互換性に影響</a>する既知の既知の変更の一覧を必ず確認してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-631">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="59d85-632">
  <strong>Windows 仮想デスクトップ </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-632">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="59d85-633">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-633">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-634">Windows 7 または Windows 10 の仮想デスクトップインフラストラクチャ (VDI) 環境で実行されているアプリは、windows 7 Enterprise および windows 10 Enterprise で Windows 仮想デスクトップの一部としても実行されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-634">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-635">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="59d85-635">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="59d85-636">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="59d85-636">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="59d85-637">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="59d85-637">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-638">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="59d85-638">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="59d85-639">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="59d85-639">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="59d85-640">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="59d85-640">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="59d85-641"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-641"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="59d85-642"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-642"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="59d85-643"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="59d85-643"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="59d85-644"><strong>Microsoft Edge</strong> (Windows 10 Enterprise お客様向け)</span><span class="sxs-lookup"><span data-stu-id="59d85-644"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="59d85-645">Microsoft は、Microsoft エンドポイントマネージャー (Microsoft エンドポイント構成マネージャーまたは Intune) を使用して、Windows 10 Enterprise に新しい Microsoft Edge を展開するためのリモート展開のガイダンスと互換性支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="59d85-645">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="59d85-646">Microsoft Edge の構成 (グループポリシーまたは Intune アプリの構成とアプリポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="59d85-646">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="59d85-647">[インベントリ] Internet Explorer モードでの使用が必要なサイトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="59d85-647">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="59d85-648">既存のエンタープライズサイトリストを使用して Internet Explorer モードを有効にする。</span><span class="sxs-lookup"><span data-stu-id="59d85-648">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="59d85-649">また、Internet Explorer または Google Chrome と連携する web アプリまたはサイトがあり、互換性の問題が発生した場合は、追加料金なしで問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="59d85-649">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="59d85-650">詳細については、「 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">アプリの保証</a> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="59d85-650">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="59d85-651">

<strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="59d85-651">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="59d85-652">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="59d85-652">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="59d85-653">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="59d85-653">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
