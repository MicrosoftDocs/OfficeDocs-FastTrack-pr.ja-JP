---
title: 製品と機能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。 現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800969"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="9beb0-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="9beb0-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="9beb0-105">FastTrack でサポートされているサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="9beb0-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="9beb0-106">このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="9beb0-107">現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="9beb0-108">FastTrack は、最初にコア機能 (すべての Microsoft Online サービスに共通) を提供し、次に各対象サービスをオンボードにするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="9beb0-109">全般</span><span class="sxs-lookup"><span data-stu-id="9beb0-109">General</span></span>](#general)
  - [<span data-ttu-id="9beb0-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="9beb0-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="9beb0-111">エンタープライズモビリティ & のセキュリティ</span><span class="sxs-lookup"><span data-stu-id="9beb0-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="9beb0-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="9beb0-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="9beb0-113">App Assure</span><span class="sxs-lookup"><span data-stu-id="9beb0-113">App Assure</span></span>](Win-10-app-assure.md)
  - [<span data-ttu-id="9beb0-114">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="9beb0-114">The new Microsoft Edge</span></span>](Win-10-microsoft-edge.md)

> [!NOTE]
> <span data-ttu-id="9beb0-115">Office 365 US Government のソース環境の要件の詳細については、「 [office 365 Us government のソース環境の要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-115">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="9beb0-116">全般</span><span class="sxs-lookup"><span data-stu-id="9beb0-116">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9beb0-117"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-117"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9beb0-118"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-118"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9beb0-119"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-119"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9beb0-120"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-120"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-121">コアオンボードに関するリモートガイダンスを提供します。これには、サービスのプロビジョニング、テナント、およびアイデンティティ統合が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-121">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="9beb0-122">また、Exchange Online、SharePoint Online、Microsoft Teams などのオンボードサービスの基礎を提供するための手順についても説明します。これには、 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">セキュリティ、ネットワーク接続、コンプライアンスに関する説明</a>が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-122">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="9beb0-123">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-123">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="9beb0-124"></li>
</ul>  

<strong> Id 統合 </strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-124"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="9beb0-125">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-125">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="9beb0-126">Azure AD Connect (単一または複数のフォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、azure Active Directory (Azure AD) への同期用にオンプレミスの Active Directory Id を準備します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-126">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="9beb0-127">グループベースのライセンスを使用することを含め、一括インポートおよびライセンスを含むクラウド id を作成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-127">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="9beb0-128">クラウドへの移行、パスワードハッシュ同期、パススルー認証、または Active Directory フェデレーションサービス (AD FS) に対して適切な認証方法を選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-128">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="9beb0-129">単一の Active Directory フォレストを持つお客様に対して AD FS を有効にし、id を Azure AD Connect ツールと同期させます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-129">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="9beb0-130">これには、Windows Server 2012 R2 Active Directory フェデレーションサービス2.0 またはそれ以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="9beb0-130">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="9beb0-131">パスワードハッシュ同期またはパススルー認証を使用して、AD FS から Azure AD に認証を移行します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-131">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="9beb0-132">シングルサインオン (SSO) に対して、事前に統合されたアプリ (Azure AD gallery software-a service (SaaS) アプリなど) を AD FS から Azure AD に移行します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-132">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="9beb0-133">Azure AD gallery から SSO を使用した SaaS アプリの統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-133">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="9beb0-134"><a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">アプリ統合チュートリアルリスト</a>に記載されているように、事前に統合された SaaS アプリの自動ユーザープロビジョニングを有効にします (Azure AD gallery SaaS アプリと送信プロビジョニングのみに限定)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-134">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="9beb0-135"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="9beb0-135"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="9beb0-136">FastTrack の特典の一環として、クラウドサービスに接続して Microsoft 365 の最高レベルのパフォーマンスを確保するためのベストプラクティスについてお勧めします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-136">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="9beb0-137"><strong>Active Directory フォレスト</strong> これらのフォレストの機能は、機能フォレストレベルが Windows Server 2003 以降に設定されており、フォレスト構成は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="9beb0-137"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-138">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="9beb0-138">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-139">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="9beb0-139">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-140">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="9beb0-140">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-141">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-141">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-142">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="9beb0-142">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-143">必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。   </span><span class="sxs-lookup"><span data-stu-id="9beb0-143">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="9beb0-144">
  <strong>大事な：</strong>  </span><span class="sxs-lookup"><span data-stu-id="9beb0-144">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="9beb0-145">複数フォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-145">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-146">複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange 多重ハイブリッド構成で実装する場合、ソースフォレスト間で共有されるユーザープリンシパル名 (UPN) の名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-146">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="9beb0-147">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-147">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="9beb0-148">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-148">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-149">すべての複数フォレスト構成では、Active Directory フェデレーションサービス (AD FS) の展開がスコープ外になります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-149">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="9beb0-150">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-150">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-151"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-151"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-152">次のためのリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-152">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-153">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="9beb0-153">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-154">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-154">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-155">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-155">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-156">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-156">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-157">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-157">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-158">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-158">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-159">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-159">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-160">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-160">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="9beb0-161">また、以前のバージョンの Office で作業したマクロまたはアドインがあり、互換性の問題が発生した場合は、アプリの保証プログラムを通じて追加費用なしで互換性の問題を修復するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-161">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="9beb0-162">詳細については、「 <strong>アプリ</strong> で <a href="#windows-10">Windows 10</a> の一部を確認する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-162">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9beb0-163">オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-163">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-164"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-164"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-165">組織のサイトが Microsoft の <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ネットワーク接続の原則</a>とどのように連携しているかを示す、環境からの主要なネットワーク接続データの取得と解釈に関するリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-165">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="9beb0-166">これにより、移行速度、ユーザー環境、サービスのパフォーマンス、および信頼性に直接影響するネットワークスコアが強調されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-166">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="9beb0-167">また、このデータで強調表示されている修復手順についても説明し、ネットワークのスコアを向上します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-167">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="9beb0-168">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-168">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-169">Microsoft 365 アプリの最新バージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="9beb0-169">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-170"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 管理センター (プレビュー) でのネットワークパフォーマンスに関する推奨事項</a>として有効になる場所サービス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-170">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="9beb0-171">Office 365</span><span class="sxs-lookup"><span data-stu-id="9beb0-171">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9beb0-172"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-172"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9beb0-173"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-173"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9beb0-174"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-174"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9beb0-175"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-175"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-176">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-176">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="9beb0-177">正確な手順は、ソース環境と電子メール移行プランによって異なります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-177">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="9beb0-178">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-178">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-179">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="9beb0-179">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-180">メール交換 (MX) レコードを Office 365 に接続します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-180">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-181">サブスクリプションサービスの一部である場合は、Office 365 ATP 機能をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-181">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="9beb0-182">詳細については、この表の「 <strong>Office 365 Advanced Threat Protection</strong> 」の部分を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-182">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-p113">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="9beb0-p114">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="9beb0-187">
  <strong>注:</strong> メールボックスレプリケーションサービス (MR) は、社内メールボックスから対応する Exchange Online メールボックスに Information Rights Managed (IRM) メールを移行しようとします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-187">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="9beb0-188">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-188">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="9beb0-189">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-189">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-190">DNS のセットアップ。必須の自動検出、sender policy framework (SPF)、DomainKeys 識別メール (DKIM)、ドメインベースのメッセージ認証、レポートと準拠 (DMARC)、および MX レコード (必要な場合) を含みます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-190">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-191">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-191">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-192">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="9beb0-192">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-193">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-193">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="9beb0-194">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="9beb0-194">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="9beb0-195">Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-195">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="9beb0-196">ソース環境には、次の最低レベルのいずれかが必要です。</span><span class="sxs-lookup"><span data-stu-id="9beb0-196">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-197">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="9beb0-197">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-198">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="9beb0-198">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-199">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-199">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-200">複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online の複数地域機能</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-200">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-201">Project for Office 365、Outlook for Windows、Outlook for iOS および Android 用の outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for business などのオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office のシステム要件</a>」で定義されている最低レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-201">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-202"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-202"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-203">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-203">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-204">情報ガバナンス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-204">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-205">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-206">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="9beb0-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-207">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-208">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-209">Insider リスク管理。</span><span class="sxs-lookup"><span data-stu-id="9beb0-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-210">Advanced eDiscovery</span><span class="sxs-lookup"><span data-stu-id="9beb0-210">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-211"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-211">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-212"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-212"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-213">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-213">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-214">データの分類。</span><span class="sxs-lookup"><span data-stu-id="9beb0-214">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-215">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="9beb0-215">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-216">機密ラベルを作成する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-216">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-217">機密ラベルを適用する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-217">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-218">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="9beb0-218">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-219">Trainable 分類子。</span><span class="sxs-lookup"><span data-stu-id="9beb0-219">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-220">コンテンツエクスプローラーとアクティビティエクスプローラーを使用してデータを把握します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-220">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-221">ポリシーを使用してラベルを発行する (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-221">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-222">Microsoft Teams のチャットおよびチャネルのデータ損失防止 (DLP) ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-222">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-223"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-223">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-224"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-224"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-225">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-225">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-226">Teams をサポートするために、Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD の最小要件を確認します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-226">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-227">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-227">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-228">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="9beb0-228">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-229">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-229">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-230">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-230">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-231">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="9beb0-231">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-232">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-232">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-233">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-233">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-234">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="9beb0-234">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9beb0-235">Teams app policy (Teams web app、Teams デスクトップアプリ、および iOS および Android アプリの Teams) を構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-235">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-236">該当する場合は、次のようなガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-236">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-237">Microsoft Teams のルームデバイス:</span><span class="sxs-lookup"><span data-stu-id="9beb0-237">Microsoft Teams Room Devices:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9beb0-238"> <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイスカタログ</a>にリストされている、サポートされているテレフォニーおよび会議室デバイスに必要なオンラインアカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-238">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9beb0-239">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="9beb0-239">Enabling Audio Conferencing:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9beb0-240">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-240">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-241">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-241">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9beb0-242">電話システム:</span><span class="sxs-lookup"><span data-stu-id="9beb0-242">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-243">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-243">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-244">通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能なマーケット</a>):</span><span class="sxs-lookup"><span data-stu-id="9beb0-244">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-245">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-245">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-246">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-246">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-247">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="9beb0-247">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-248">ダイレクトルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="9beb0-248">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-249">パートナー ホスティング シナリオまたは単一サイトでの顧客展開シナリオの直接ルーティング デサインのための組織のセットアップ ガイド。</span><span class="sxs-lookup"><span data-stu-id="9beb0-249">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for a single site.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="9beb0-250">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-250">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-251">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="9beb0-251">Organization setup and integration into Microsoft Stream.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9beb0-252">Office 365 の Azure AD で有効になっている id。</span><span class="sxs-lookup"><span data-stu-id="9beb0-252">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-253">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="9beb0-253">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-254">Exchange メールボックスが存在する (Exchange ハイブリッド構成でオンラインおよびオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-254">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-255">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="9beb0-255">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="9beb0-256">
  <strong>注:</strong>  ユーザーが SharePoint Online のライセンスで割り当てられて有効になっていない場合は、Office 365 の OneDrive for Business ストレージはありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-256">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="9beb0-257">ファイル共有はチャネル内でも引き続き機能しますが、Office 365 の OneDrive for business ストレージを使用せずに、ユーザーはチャットでファイルを共有できません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-257">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="9beb0-258">Teams は、オンプレミスの SharePoint をサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-258">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="9beb0-259">
  <strong>注:</strong>  理想的な状態は、すべてのユーザーが Exchange Online 上にメールボックスを配置することです。</span><span class="sxs-lookup"><span data-stu-id="9beb0-259">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="9beb0-260">オンプレミスのメールボックスを持つユーザーは、Azure AD Connect を使用して、Office 365 ディレクトリにその id を同期する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-260">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="9beb0-261">これらの Exchange ハイブリッドユーザーの場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成することはできません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-261">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="9beb0-262">Microsoft Teams Windows および Mac デスクトップクライアントのインストーラーは、からダウンロードでき  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> ます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-262">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-264">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-264">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-265">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-265">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-266">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-266">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-267">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="9beb0-267">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-268">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="9beb0-268">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-269"><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-269">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-270"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-270"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-271">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-272">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="9beb0-272">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-273">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-273">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-274">Outlook mobile をセキュリティで保護する (詳細については <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">、「Exchange Online で outlook For iOS と outlook For Android を保護</a> する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-274">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9beb0-275">Office 365 の Azure AD で有効になっている id。</span><span class="sxs-lookup"><span data-stu-id="9beb0-275">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-276">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="9beb0-276">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-277"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-277"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-278">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-279">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-279">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-280">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-280">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-281">Power BI Desktop のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-281">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-282"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-282"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-283">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-283">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-284">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-284">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-285">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-285">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-286">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-286">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-287">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-287">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-288">「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-288">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-289"><strong>Project Online Professional および Premium</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-289"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-290">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-291">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="9beb0-291">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-292">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-292">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-293">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-293">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-294">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-294">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-295">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-295">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-296">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="9beb0-296">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-297">「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-297">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-298"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-298"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-299">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-299">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-300">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="9beb0-300">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-301">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-301">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-302">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="9beb0-302">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="9beb0-303">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-303">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="9beb0-304">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="9beb0-304">Planning site collections.</span></span></li>
<li><span data-ttu-id="9beb0-305">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="9beb0-305">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="9beb0-306">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-306">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="9beb0-307">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-307">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-308">移行方法。</span><span class="sxs-lookup"><span data-stu-id="9beb0-308">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-309">SharePoint のバージョンによっては、次のように、OneDrive for Business に関する追加のガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-309">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-310">統合オプションを識別し、オンプレミスおよびオンラインのネットワークインフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-310">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-311">SharePoint Online 2013 SP1 (該当する場合) のインストール、同期および id の要件の計画と実装、および OneDrive for Business 同期クライアントの識別を行います。</span><span class="sxs-lookup"><span data-stu-id="9beb0-311">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-312">すべてのユーザー (または段階的なロールアウト) に対して単一のロールアウトを計画し、実装します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-312">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-313">ライセンスの割り当て、個人用サイトおよび個人用ドキュメントライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に該当)、対象ユーザーを設定して OneDrive へのアクセスを制御する (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-313">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="9beb0-314">既知のフォルダーを OneDrive にリダイレクトまたは移動します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-314">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="9beb0-315">OneDrive for Business クライアントの同期を展開します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-315">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="9beb0-316">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="9beb0-316">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="9beb0-317">Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-317">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="9beb0-318"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-318"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="9beb0-319">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツタイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネットサイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービスサイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-319">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="9beb0-320">
  <strong>注:</strong> セルフサービスサイト作成は、SharePoint 2013 を実行しているオンプレミスサーバーの範囲内にありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-320">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="9beb0-321">SharePoint ハイブリッドを有効にするには、次のオンプレミスの SharePoint Server 環境のうちの1つが必要です。2013、2016、または2019。</span><span class="sxs-lookup"><span data-stu-id="9beb0-321">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="9beb0-322">
  <strong>注:</strong> オンプレミスの SharePoint 環境の SharePoint Server へのアップグレードは、スコープ内にありません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-322">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="9beb0-323">詳細については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-323">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="9beb0-324">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint ハイブリッド機能の最小パブリック更新プログラムレベル</a>」を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="9beb0-324">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="9beb0-325">
  <strong>注:</strong>複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 の「OneDrive および SharePoint Online の複数地域機能</a>」を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="9beb0-325">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-326"><strong>Skype for Business Online</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-326"><strong>Skype for Business Online</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-327">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-328">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-328">Configuring firewall ports.</span></span>  </li>

<li>  <span data-ttu-id="9beb0-329">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="9beb0-329">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-330">ネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="9beb0-330">Network assessment:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-331">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-331">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-332">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="9beb0-332">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-333">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="9beb0-333">Bandwidth estimates.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-334">ルーム システム デバイスのアカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-334">Creating accounts for any room system devices.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-335">サポートされる Skype for Business Online クライアントの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-335">Deploying a supported Skype for Business Online client.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-336">オンプレミスの Lync 2010、Lync 2013、Skype for Business 2015 サーバー環境と、Skype for Business Online テナント (該当する場合)、通話プラン、Skype 会議ブロードキャスト、電話システムおよび通話プラン (利用可能なマーケットのみ) との間で、分割ドメイン サーバー構成を確立する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-336">Establishing split domain server configuration between your on-premises Lync 2010, Lync 2013, or Skype for Business 2015 server environment and Skype for Business Online tenant (if applicable), Calling Plans, Skype Meeting Broadcast, and Phone System and Calling Plans (in available markets).</span></span>  
  <span data-ttu-id="9beb0-337">必要に応じて、FastTrack で次の手順についても説明します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-337">If applicable, FastTrack also guides you through:</span></span>  </li>
<li>  <span data-ttu-id="9beb0-338">ルームシステムデバイスの構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-338">Configuring room system device:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-339"> <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype For business ソリューションカタログ</a>の [会議室システム] タブに一覧表示される、サポートされている会議室デバイスに必要なオンラインアカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-339">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business solutions catalog</a>.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-340">ハイブリッドおよび分割ドメインサーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-340">Configuring hybrid and split domain servers.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-341">電話会議の構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-341">Configuring Audio Conferencing:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-342">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-342">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-343">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-343">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-344">電話システムの既定の設定の構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-344">Configuring Phone System default settings:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-345">通話プラン:</span><span class="sxs-lookup"><span data-stu-id="9beb0-345">Calling Plans:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-346">ライセンスユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="9beb0-346">Assignment of numbers to licenses users.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-347">ユーザーインターフェイスを介して99までのローカル番号の移植ガイダンス</span><span class="sxs-lookup"><span data-stu-id="9beb0-347">Local number porting guidance through user interface up to 99</span></span>  </li>
<li>  <span data-ttu-id="9beb0-348">999を超える電話番号の移植サービス要求のサポート</span><span class="sxs-lookup"><span data-stu-id="9beb0-348">Local number porting service request support over 999</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="9beb0-349">Skype for Business 会議ブロードキャストを構成する:</span><span class="sxs-lookup"><span data-stu-id="9beb0-349">Configure Skype for Business Meeting Broadcast:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-350">会議メディア サービスとのフェデレーションのための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-350">Organization setup for federation with Meeting Broadcast service.</span></span>  </li>
</ul></li>
</ul></td>
<td>  <span data-ttu-id="9beb0-351"><strong>Lync ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-351"><strong>For Lync hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="9beb0-352">1 つのオンプレミスの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="9beb0-352">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-353">Lync 2010 Server 環境と、Lync 2013 2013 管理ツールまたは Skype for Business 2015 管理ツール、および Lync 2010 エッジ サーバーの役割。</span><span class="sxs-lookup"><span data-stu-id="9beb0-353">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-354">Lync 2013 Server 環境と Lync 2013 エッジ サーバーの役割。</span><span class="sxs-lookup"><span data-stu-id="9beb0-354">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  </li>
</ul><span data-ttu-id="9beb0-355">
  <strong>Skype for Business ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-355">
  <strong>For Skype for Business hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="9beb0-356">1 つのオンプレミスの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="9beb0-356">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-357">1 つの Active Directory アカウント フォレスト以降とリソース フォレスト (Exchange と Skype for Business の一方または両方) のトポロジ。</span><span class="sxs-lookup"><span data-stu-id="9beb0-357">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-358">複数の Active Directory アカウント フォレスト、および一元化された Active Directory アカウント フォレストで、その中に Exchange と Skype for Business の一方または両方がある 1 つのフォレスト。</span><span class="sxs-lookup"><span data-stu-id="9beb0-358">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-359">Skype for Business エッジ サーバーの役割を含む Skype for Business Server 2015 環境。</span><span class="sxs-lookup"><span data-stu-id="9beb0-359">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  </li>
</ul><span data-ttu-id="9beb0-360">
  <strong>注:</strong> この追加サービスは、分割ドメイン (ハイブリッド) タスクを構成および検証するためのものであり、オンプレミスコンポーネント (Lync 2013 管理ツール、Lync 2013/Skype for Business Online サーバー、Lync 2010、Lync 2013、Skype for Business edge server など) の導入も含みません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-360">
  <strong>Note:</strong> This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-361"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-361"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="9beb0-362">Yammer Enterprise service を有効にするためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-362">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="9beb0-363">オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-363">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="9beb0-364">エンタープライズモビリティ & のセキュリティ</span><span class="sxs-lookup"><span data-stu-id="9beb0-364">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-365"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-365"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-366">次のシナリオでは、クラウド id を保護するためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-366">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="9beb0-367">

<strong>セキュリティ保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="9beb0-367">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="9beb0-368">Azure 多要素認証 (MFA) (クラウドのみ)、Microsoft Authenticator アプリ、および Azure MFA とセルフサービスのパスワードのリセット (SSPR) の組み合わせを含む、強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-368">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-369">非 Azure AD Premium のお客様の場合は、セキュリティの既定値を使用して id をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-369">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-370">Azure AD premium のお客様の場合、条件付きアクセスを使用して id をセキュリティで保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-370">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-371">Azure AD パスワード保護を使用して、脆弱なパスワードの使用を検出およびブロックします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-371">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-372">Azure AD アプリケーションプロキシを使用したオンプレミスの web アプリケーションへのリモートアクセスをセキュリティで保護する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-372">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-373">Azure Id 保護を使用したリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-373">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-374">ロゴ、テキスト、イメージを含むカスタマイズされたサインイン画面を有効にして、カスタムブランド化します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-374">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-375">Azure AD B2B を使用して、アプリやサービスをゲストユーザーと安全に共有できます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-375">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-376">役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権のある管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-376">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-377">ハイブリッド Azure AD join を構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-377">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-378">Azure AD join を構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-378">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="9beb0-379">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-379">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9beb0-380">Azure AD Connect Health を使用して AD FS、Azure AD Connect、およびドメインコントローラーのリモート監視を有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-380">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="9beb0-381">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-381">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9beb0-382">Azure ad 受給管理を使用して、Azure AD id とアクセスのライフサイクルをスケールで管理します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-382">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="9beb0-383">Azure ad グループメンバーシップ、エンタープライズアプリアクセス、および Azure AD アクセスレビューを使用したロール割り当てを管理します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-383">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-384">Azure AD の使用条件を確認します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-384">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-385">Azure AD 特権 Id 管理を使用して、特権のある管理者アカウントへのアクセスを管理および管理します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-385">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="9beb0-386">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-386">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9beb0-387">Azure AD SSPR を有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-387">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="9beb0-388">ユーザーが Azure AD セルフサービスグループ管理を使用して、独自のクラウドセキュリティまたは Office 365 グループを作成および管理できるようにします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-388">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-389">Azure AD 委任されたグループ管理を使用して、エンタープライズアプリへの委任されたアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-389">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-390">Azure AD の動的グループを有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-390">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-391">コレクションを使用して、個人用アプリポータルでアプリを整理します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-391">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9beb0-392">オンプレミスの Active Directory とその環境は Azure ad Premium 用に準備されています。これには、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-392">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9beb0-393"><strong>Azure Information Protection (P2 または EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-393"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-394">次の方法についてのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-394">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-395">テナントのアクティブ化と構成を行います。</span><span class="sxs-lookup"><span data-stu-id="9beb0-395">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-396">ラベルおよびポリシーの作成および設定。</span><span class="sxs-lookup"><span data-stu-id="9beb0-396">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-397">情報保護のドキュメントへの適用。</span><span class="sxs-lookup"><span data-stu-id="9beb0-397">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-398">Windows で実行され、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) での自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="9beb0-398">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-399">Azure Information Protection スキャナーを使用した、保管中ファイルの使用。</span><span class="sxs-lookup"><span data-stu-id="9beb0-399">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-400">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="9beb0-400">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-401">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用する場合も、ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-401">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="9beb0-402">既に次のことを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-402">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-403">Azure AD を使用します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-403">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-404">Windows または iOS のどちらか (他のオペレーティングシステムがスコープ外) を使用します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-404">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="9beb0-405">
<strong>注</strong>: コンピューターとモバイルデバイスは、Azure Information Protection をサポートする <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">オペレーティングシステム</a> で実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-405">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="9beb0-406">メインファイル共有場所を用意します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-406">Have your main file share locations.</span></span>  </li><span data-ttu-id="9beb0-407">
<strong>注</strong>: ハイブリッドサポートには、AD RMS コネクタが必要です。</span><span class="sxs-lookup"><span data-stu-id="9beb0-407">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="9beb0-408">分類の分類が承認されている。</span><span class="sxs-lookup"><span data-stu-id="9beb0-408">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-409">保護されたキーの管理に関する規制の制限について説明します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-409">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="9beb0-410">
</ul>
  
<strong>Azure Information Protection スキャナー</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-410">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="9beb0-411">既に次のことを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-411">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="9beb0-412">Windows Server 2012 R2 または Windows Server 2016 を使用します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-412">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-413">インターネットに接続されている。</span><span class="sxs-lookup"><span data-stu-id="9beb0-413">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-414">ローカルまたはリモートのインスタンスで Microsoft SQL Server 2012 以降が必要です。</span><span class="sxs-lookup"><span data-stu-id="9beb0-414">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-415">オンプレミスの Active Directory に対してサービスアカウントを作成し、Azure AD と同期させます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-415">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-416">AzInfoProtection.exe をダウンロードしました。</span><span class="sxs-lookup"><span data-stu-id="9beb0-416">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-417">自動分類/保護に対してラベルを構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-417">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9beb0-418"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-418"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-419">アプリとデバイスのための、クラウドベースのモバイルデバイス管理 (MDM) およびモバイルアプリ管理 (MAM) プロバイダーとして Intune を使用するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-419">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="9beb0-420">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-420">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="9beb0-421">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="9beb0-421">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-422">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="9beb0-422">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-423">オンプレミスの Active Directory またはクラウド id (Azure AD) を活用して、Intune で使用される id を構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-423">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-424">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-424">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-425">次のような管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-425">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-426">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-426">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-427">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="9beb0-427">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-428">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-428">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-429">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-429">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-430">Web リンクまたはディープリンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-430">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-431">条件付きアクセスポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-431">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-432">組織内に既存の証明機関、ワイヤレスネットワーク、または VPN インフラストラクチャがある場合に、電子メール、ワイヤレスネットワーク、および VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-432">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-433">Microsoft Intune Exchange Connector のセットアップ (該当する場合)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-433">Setting up the Microsoft Intune Exchange Connector (when applicable).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-434">Intune データウェアハウスに接続します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-434">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-435">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="9beb0-435">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-436">リモートアシスタンスのチームビューアー (チームビューアーサブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-436">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-437">モバイル脅威防御 (MTD) パートナーソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-437">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-438">電気通信経費管理ソリューション (電気通信経費管理ソリューションサブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-438">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-439">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-439">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-440">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="9beb0-440">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="9beb0-441">アプリ保護ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="9beb0-441">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-442">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-442">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-443">管理対象アプリの条件付きアクセスポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-443">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-444">前述の MAM ポリシーを使用して、適切なユーザーグループを対象にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-444">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-445">管理対象アプリの使用状況レポートを使用します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-445">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-446">レガシ PC 管理から Intune MDM への移行ガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="9beb0-446">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="9beb0-447">
  <strong>注</strong>: レガシ PC 管理は、2020年10月15日以降ではサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-447">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="9beb0-448"></li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-448"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="9beb0-449">ここでは、Intune を使用した既存の Configuration Manager 環境のクラウド接続の準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-449">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="9beb0-450">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-450">The exact steps depend on your source environment.</span></span> <span data-ttu-id="9beb0-451">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-451">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="9beb0-452">Intune を使用してクラウドに接続することの利点についての説明。</span><span class="sxs-lookup"><span data-stu-id="9beb0-452">Explaining the benefits of cloud-attaching Configuration Manager with Intune.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-453">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="9beb0-453">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-454">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-454">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-455">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-455">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-456">Configuration Manager コンソールでのクラウド接続の有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-456">Enabling cloud-attach in the Configuration Manager console.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-457">ハイブリッド Azure AD join を設定するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-457">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-458">MDM 自動登録用に Azure AD をセットアップするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-458">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-459">クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="9beb0-459">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-460">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-460">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-461">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-461">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="9beb0-462"><strong>IOS および Android 用の Outlook mobile を安全に展開する</strong> ユーザーが必要なすべてのアプリをインストールしていることを確認するために、iOS および Android 用の Outlook mobile を組織に安全に展開するためのガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-462"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="9beb0-463">Intune を使用して iOS および Android 用の Outlook mobile を安全に展開するための手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-463">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="9beb0-464">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-464">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-465">Apple App Store または Google Play ストアを介して、iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-465">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-466">セットアップのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-466">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-467">IOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリの展開 (Intune)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-467">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-468">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-468">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-469">条件付きアクセスポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-469">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-470">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-470">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="9beb0-471"><strong>注</strong>: fasttrack は、Exchange モバイルデバイスメールボックスポリシーを使用して IOS および Android 用の Outlook のセキュリティ保護をサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-471"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="9beb0-472">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-472">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="9beb0-473">IT 管理者は、Intune を使用してワイヤレスネットワークおよび VPN プロファイルを展開する計画を立てるときに、既存の証明機関、ワイヤレスネットワーク、および VPN インフラストラクチャを運用環境で既に稼働している必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-473">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="9beb0-474"><strong>注</strong>: fasttrack サービス特典には、Intune の証明機関、ワイヤレスネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書をセットアップまたは構成するための支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-474"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  

<span data-ttu-id="9beb0-475"><strong>Intune を使用して Configuration Manager をクラウドで接続する</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-475"><strong>Cloud-attach Configuration Manager with Intune</strong></span></span>  

 <span data-ttu-id="9beb0-476">クラウド接続を使用すると、IT 管理者はオンプレミス環境の準備を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-476">With cloud-attach, IT admins are responsible for preparing the on-premises environment.</span></span> <span data-ttu-id="9beb0-477">これには、Intune による構成マネージャー環境のクラウド接続を妨げる問題の修復が含まれることがあります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-477">This can include remediation of issues that prevent you from cloud-attaching your Configuration Manager environments with Intune.</span></span>  
  <span data-ttu-id="9beb0-478"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-478"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="9beb0-479">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-479">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="9beb0-480"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-480"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="9beb0-481"><strong>注</strong>: MICROSOFT Defender ATP との Intune の統合、および Windows 10 のリスクレベルの評価に基づくデバイスコンプライアンスポリシーの作成に関する支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-481"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="9beb0-482">購入、ライセンス、またはライセンス認証についてのサポートは提供していません。</span><span class="sxs-lookup"><span data-stu-id="9beb0-482">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="9beb0-483">この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-483">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="9beb0-484"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-484"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="9beb0-485">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-485">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="9beb0-486"><strong>IOS および Android 用の Outlook を、Intune を使用して安全に展開する </strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-486"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="9beb0-487">Office 365 の Azure AD で有効になっているユーザー id。</span><span class="sxs-lookup"><span data-stu-id="9beb0-487">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-488">ユーザーライセンスが割り当てられている exchange Online またはハイブリッド Exchange。</span><span class="sxs-lookup"><span data-stu-id="9beb0-488">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="9beb0-489">Windows 10</span><span class="sxs-lookup"><span data-stu-id="9beb0-489">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9beb0-490"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-490"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9beb0-491"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-491"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9beb0-492"><strong>ソース環境の要件</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-492"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9beb0-493"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-493"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-494">Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに役立つガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-494">We provide guidance to help you upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="9beb0-495">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-496">Windows 10 の目的を理解します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-496">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-497">ソース環境と要件を評価します (Windows 10 展開をサポートするために、Microsoft エンドポイント構成マネージャーが必要なレベルにアップグレードされていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-497">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-498">Microsoft エンドポイント構成マネージャーまたは Microsoft 365 を使用して、Windows 10 Enterprise と Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-498">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-499">Windows 10 アプリを評価するためのオプションを推奨します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-499">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-500">デスクトップ分析展開計画の作成による、デスクトップ分析およびガイダンスの使用を有効にする。</span><span class="sxs-lookup"><span data-stu-id="9beb0-500">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-501">Microsoft 365 アプリの互換性評価は、構成マネージャーで Office 365 レディネスダッシュボードを活用するか、またはスタンドアロンの準備ツールキットを使用して Office plus Microsoft 365 アプリを展開することによって評価されます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-501">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-502">Microsoft Intune を使用したクラウド接続の構成マネージャーや、単独のクラウド管理ソリューションとしての Intune の展開など、最新の管理戦略を評価します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-502">Assessing your modern management strategies, including cloud-attaching Configuration Manager with Microsoft Intune or deploying Intune as the sole cloud management solution.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-503">展開を成功させるために、ソース環境を最小要件にするために必要な作業について、修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-503">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-504">必要なデバイスハードウェア要件を満たしている場合は、既存のデバイスのアップグレードガイダンスを Windows 10 Enterprise に提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-504">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-505">既存の展開の動きをサポートするためのアップグレードガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-505">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="9beb0-506">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="9beb0-506">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="9beb0-507">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="9beb0-507">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-508">Windows 10 展開の一環として構成マネージャーを使用して、Microsoft 365 アプリを展開します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-508">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="9beb0-509">既存の構成マネージャー環境または Microsoft 365 を使用して、Windows 10 Enterprise および Microsoft 365 アプリを使用して、組織が最新の状態を維持するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-509">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-510">クラウドを使用した最新の管理を有効にするためのガイダンスを提供するか、intune に構成マネージャーを展開する (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-510">Providing guidance to enable modern management by cloud-attaching Configuration Manager to Intune or by deploying Intune standalone (where required).</span></span>  </li>
</ul><span data-ttu-id="9beb0-511">
  <strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-511">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9beb0-512">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="9beb0-512">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-513">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-513">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-514">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="9beb0-514">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-515">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="9beb0-515">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-516">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-516">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-517">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-517">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-518">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-518">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-519">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="9beb0-519">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-520">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-520">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="9beb0-521">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-521">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-522">ソース OS: Windows 7 Enterprise または Professional、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="9beb0-522">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-523">デバイス: デスクトップ、ノートブック、またはタブレットフォームファクター。</span><span class="sxs-lookup"><span data-stu-id="9beb0-523">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-524">ターゲット OS: Window 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="9beb0-524">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="9beb0-525">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-525">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-526">Microsoft エンドポイント構成マネージャー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-526">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-527">構成マネージャーのバージョンは、Windows 10 のターゲットのバージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-527">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="9beb0-528">詳細については、「configuration <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">manager での Windows 10 のサポート</a>」の構成マネージャーサポートの表を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-528">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="9beb0-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9beb0-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9beb0-530">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="9beb0-530">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="9beb0-531">次のためのリモートガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-531">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9beb0-532">エンドポイントをセキュリティで保護するためのテクノロジを展開する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-532">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-533">エンドポイント保護とデバイス制限プロファイルを構成する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-533">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-534">Windows Defender AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態、および Intune、Microsoft エンドポイント構成マネージャー、グループポリシーオブジェクト (Gpo)、サードパーティの構成を含む、OS バージョンとデバイスの管理を評価します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-534">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-535">Windows AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-535">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-536">ネットワークトラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="9beb0-536">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-537">オンボードエンドポイントを使用して ATP エージェントプロファイルを展開する方法について説明することにより、Microsoft Defender ATP サービスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-537">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-538">展開のガイダンス、構成の支援、および教育:</span><span class="sxs-lookup"><span data-stu-id="9beb0-538">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-539">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="9beb0-539">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-540">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="9beb0-540">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-541">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="9beb0-541">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-542">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="9beb0-542">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-543">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="9beb0-543">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-544">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="9beb0-544">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-545">シミュレーションとチュートリアル (プラクティスシナリオ、偽のマルウェア、自動調査など) をレビューします。</span><span class="sxs-lookup"><span data-stu-id="9beb0-545">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-546">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="9beb0-546">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-547">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="9beb0-547">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-548">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-548">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-549">次のオペレーティングシステム。</span><span class="sxs-lookup"><span data-stu-id="9beb0-549">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-550">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="9beb0-550">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-551">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="9beb0-551">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-552">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="9beb0-552">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-553">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="9beb0-553">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-554">Windows Server 半期チャネル (SAC) バージョン1803。</span><span class="sxs-lookup"><span data-stu-id="9beb0-554">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-555">macOS バージョン10.13、10.14、および10.15。</span><span class="sxs-lookup"><span data-stu-id="9beb0-555">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="9beb0-556">
<strong>注:</strong> Windows Server のすべてのバージョンは、System Center Configuration Manager 2012 (バージョン 1012 R2、1511、または 1602) または Microsoft エンドポイント構成マネージャー (バージョン2002以上) の最新バージョンで管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="9beb0-556">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="9beb0-557"></li>
</ul>

<strong>次の範囲外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9beb0-557"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9beb0-558">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="9beb0-558">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-559">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="9beb0-559">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-560">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="9beb0-560">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-561">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="9beb0-561">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-562">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="9beb0-562">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-563">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="9beb0-563">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-564">マシン.</span><span class="sxs-lookup"><span data-stu-id="9beb0-564">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-565">モバイルデバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="9beb0-565">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-566">サーバーのオンボードと構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-566">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-567">オフライン通信用のプロキシサーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-567">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-568">下位レベルの構成マネージャーのインスタンスとバージョンで構成マネージャーの展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="9beb0-568">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-569">Azure セキュリティセンターへのオンボードサーバー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-569">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-570">構成マネージャーで管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="9beb0-570">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-571">macOS のオンボードと構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-571">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-572">手動による Intune ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-572">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-573">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-573">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="9beb0-574">その他のモバイルデバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-574">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-575">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="9beb0-575">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-576">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="9beb0-576">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="9beb0-577">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="9beb0-577">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-578">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-578">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-579">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="9beb0-579">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9beb0-580">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="9beb0-580">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9beb0-581">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-581">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-582">構成またはトレーニング API またはセキュリティ情報およびイベント管理 (SIEM) 接続を確認します。</span><span class="sxs-lookup"><span data-stu-id="9beb0-582">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-583">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="9beb0-583">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="9beb0-584">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-584">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="9beb0-585">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="9beb0-585">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="9beb0-586">これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="9beb0-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>
