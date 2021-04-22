---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: 70e279268f33591884c6bebb8625688ca724480d
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927035"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="4335b-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="4335b-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="4335b-105">FastTrack でサポートされるサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="4335b-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="4335b-106">このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。</span><span class="sxs-lookup"><span data-stu-id="4335b-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="4335b-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="4335b-108">FastTrack では、最初にコア機能 (すべてのサービスで共通) を使用し、次Microsoft Online Services対象となる各サービスをオンボーディングする場合に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="4335b-109">全般</span><span class="sxs-lookup"><span data-stu-id="4335b-109">General</span></span>](#general)
  - [<span data-ttu-id="4335b-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="4335b-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="4335b-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="4335b-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="4335b-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="4335b-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="4335b-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="4335b-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="4335b-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="4335b-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="4335b-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="4335b-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="4335b-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="4335b-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="4335b-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="4335b-118">全般</span><span class="sxs-lookup"><span data-stu-id="4335b-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-120"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4335b-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="4335b-123">サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="4335b-124">また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="4335b-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="4335b-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="4335b-126"></li>
</ul>  

<strong> Identity Integration </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="4335b-127">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="4335b-128">Azure AD Connect (単一フォレストまたは複数フォレスト) とライセンス (グループ ベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="4335b-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="4335b-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="4335b-130">クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</span><span class="sxs-lookup"><span data-stu-id="4335b-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="4335b-131">パスワードレス認証 (Fast Identity Online (FIDO)2 または Microsoft Authenticator App) を使用して、ユーザーの認証エクスペリエンスを選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="4335b-132">Azure AD接続ツールと同期された単一の Active Directory フォレストと ID を持つユーザーの FS AD有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="4335b-133">これには、R2 active Directory フェデレーション Windows Server 2012 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="4335b-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="4335b-134">パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</span><span class="sxs-lookup"><span data-stu-id="4335b-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="4335b-135">シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</span><span class="sxs-lookup"><span data-stu-id="4335b-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="4335b-136">Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="4335b-137">アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">有効にする</a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="4335b-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="4335b-138"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="4335b-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="4335b-139">FastTrack のメリットの一環として、Microsoft 365 の最高レベルのパフォーマンスを確保するためにクラウド サービスに接続するためのベスト プラクティスについてアドバイスします。</span><span class="sxs-lookup"><span data-stu-id="4335b-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="4335b-140"><strong>Active Directory フォレスト</strong> これらは、次のフォレスト構成を使用して、Windows Server 2003 以降に機能フォレスト レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="4335b-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-141">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="4335b-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="4335b-142">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="4335b-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-143">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="4335b-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-144">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="4335b-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="4335b-145">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="4335b-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="4335b-146">必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。</span><span class="sxs-lookup"><span data-stu-id="4335b-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="4335b-147">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="4335b-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="4335b-148">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="4335b-149">Exchange マルチハイブリッド構成で複数の Exchange 組織に複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="4335b-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="4335b-150">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="4335b-151">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="4335b-152">複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="4335b-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="4335b-153">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-154"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="4335b-155">次のリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-156">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="4335b-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="4335b-157">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="4335b-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="4335b-158">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="4335b-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="4335b-159">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="4335b-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="4335b-160">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4335b-161">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="4335b-162">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="4335b-163">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="4335b-164">さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合、互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストで互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="4335b-165">詳細については <strong>、「Windows</strong> <a href="#windows-10">10</a> の App Assure 部分」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4335b-166">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="4335b-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-167"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="4335b-168">お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">示します</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="4335b-169">これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="4335b-170">また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="4335b-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="4335b-171">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="4335b-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="4335b-172">Microsoft 365 アプリの最新バージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="4335b-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="4335b-173"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている場所サービス。</span><span class="sxs-lookup"><span data-stu-id="4335b-173">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="4335b-174">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="4335b-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-175"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-176"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-177"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="4335b-178"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="4335b-179">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="4335b-180">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="4335b-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="4335b-181">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="4335b-182">FIDO2 または Microsoft Authenticator アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="4335b-183">Azure 以外のプレミアム ユーザー AD、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="4335b-184">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="4335b-185">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="4335b-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="4335b-186">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="4335b-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="4335b-187">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="4335b-188">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="4335b-189">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="4335b-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="4335b-190">役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して、Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="4335b-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="4335b-191">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4335b-192">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="4335b-193">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-194">Azure AD 接続正常性を使用AD FS、Azure AD AD 接続、およびドメイン コントローラーのリモート監視を有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="4335b-195">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-196">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="4335b-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="4335b-197">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="4335b-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-198">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="4335b-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-199">Azure の特権 ID 管理を使用して、特権管理者アカウントへのアクセスAD制御します。</span><span class="sxs-lookup"><span data-stu-id="4335b-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="4335b-200">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-201">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="4335b-202">ユーザーが独自のクラウド セキュリティまたは 365 グループを作成および管理Office、Azure ADグループ管理を使用できます。</span><span class="sxs-lookup"><span data-stu-id="4335b-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="4335b-203">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="4335b-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="4335b-204">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="4335b-205">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="4335b-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4335b-206">オンプレミスの Active Directory とその環境は、Azure AD Premium 用に準備されています。Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復も含まれます。</span><span class="sxs-lookup"><span data-stu-id="4335b-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-207"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="4335b-208">Azure Information Protection の詳細については、この表の <strong>「Microsoft Information Protection」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="4335b-209"><strong>応答&を検出する</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="4335b-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="4335b-211">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="4335b-212">新しいケースの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="4335b-213">保管担当者を保留に設定する。</span><span class="sxs-lookup"><span data-stu-id="4335b-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="4335b-214">検索の実行。</span><span class="sxs-lookup"><span data-stu-id="4335b-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="4335b-215">検索結果をレビュー セットに追加する。</span><span class="sxs-lookup"><span data-stu-id="4335b-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="4335b-216">レビュー セットで分析を実行する。</span><span class="sxs-lookup"><span data-stu-id="4335b-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="4335b-217">ドキュメントの確認とタグ付け。</span><span class="sxs-lookup"><span data-stu-id="4335b-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="4335b-218">レビュー セットからデータをエクスポートする。</span><span class="sxs-lookup"><span data-stu-id="4335b-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="4335b-219">365 以外のデータOfficeインポートします。</span><span class="sxs-lookup"><span data-stu-id="4335b-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="4335b-220"><strong>高度な監査</strong> (E5 でのみサポート)</span><span class="sxs-lookup"><span data-stu-id="4335b-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="4335b-221">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="4335b-222">高度な監査を有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="4335b-223">検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</span><span class="sxs-lookup"><span data-stu-id="4335b-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="4335b-224">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="4335b-225">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="4335b-226">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="4335b-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="4335b-227">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="4335b-228">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="4335b-229">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="4335b-230">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="4335b-231">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="4335b-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="4335b-232">カスタム スクリプトまたはコーディング。</span><span class="sxs-lookup"><span data-stu-id="4335b-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="4335b-233">電子情報開示 API。</span><span class="sxs-lookup"><span data-stu-id="4335b-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="4335b-234">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="4335b-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="4335b-235">コンプライアンスの境界とセキュリティ フィルター。</span><span class="sxs-lookup"><span data-stu-id="4335b-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="4335b-236">データ調査。</span><span class="sxs-lookup"><span data-stu-id="4335b-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="4335b-237">データ主体の要求。</span><span class="sxs-lookup"><span data-stu-id="4335b-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="4335b-238">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="4335b-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="4335b-239">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="4335b-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="4335b-240">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="4335b-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="4335b-241">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="4335b-242"><strong>Insider リスク管理</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="4335b-243">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="4335b-244">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="4335b-245">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="4335b-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="4335b-246">ケースの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="4335b-247">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="4335b-248">人事 (HR) コネクタの作成に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="4335b-249">

<strong> コミュニケーションコンプライアンス </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="4335b-250">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="4335b-251">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="4335b-252">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="4335b-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="4335b-253">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="4335b-254">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="4335b-255">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="4335b-256">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="4335b-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="4335b-257">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="4335b-258">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="4335b-259">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="4335b-260">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="4335b-261">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="4335b-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="4335b-262">Power Automate フローの作成と管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="4335b-263">データ コネクタ (HR コネクタを超えて)。</span><span class="sxs-lookup"><span data-stu-id="4335b-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="4335b-264">カスタム正規表現 (RegEx) 構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="4335b-265">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="4335b-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="4335b-266">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="4335b-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="4335b-267">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="4335b-268">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="4335b-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="4335b-269">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="4335b-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="4335b-270">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="4335b-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="4335b-272">Microsoft 365 Defender は、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="4335b-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="4335b-273">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="4335b-274">Microsoft 365 セキュリティ センターの概要を説明します。</span><span class="sxs-lookup"><span data-stu-id="4335b-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="4335b-275">製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。</span><span class="sxs-lookup"><span data-stu-id="4335b-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="4335b-276">Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、およびメールボックスの調査を調整する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="4335b-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="4335b-277">複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="4335b-278">Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</span><span class="sxs-lookup"><span data-stu-id="4335b-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="4335b-279"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="4335b-280">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="4335b-281">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="4335b-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="4335b-282">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="4335b-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="4335b-283">さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="4335b-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="4335b-284">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="4335b-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="4335b-285">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="4335b-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="4335b-286">セキュリティ情報とイベント管理 (SIEM) または API 統合。</span><span class="sxs-lookup"><span data-stu-id="4335b-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="4335b-288">Microsoft Cloud App Security は、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。</span><span class="sxs-lookup"><span data-stu-id="4335b-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="4335b-289">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-290">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="4335b-291">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="4335b-292">管理者のアクセスと設定を管理する。</span><span class="sxs-lookup"><span data-stu-id="4335b-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="4335b-293">監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</span><span class="sxs-lookup"><span data-stu-id="4335b-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="4335b-294">IP 範囲とタグの設定。</span><span class="sxs-lookup"><span data-stu-id="4335b-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="4335b-295">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="4335b-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="4335b-296">クラウド検出を設定して、次の方法でシャドウ IT を提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="4335b-297">Microsoft Defender for Endpoints.</span><span class="sxs-lookup"><span data-stu-id="4335b-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="4335b-298">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="4335b-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="4335b-299">iboss。</span><span class="sxs-lookup"><span data-stu-id="4335b-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="4335b-300">アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使用して注目</a> のアプリを接続する。</span><span class="sxs-lookup"><span data-stu-id="4335b-300">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="4335b-301">条件付きアクセス ポータルとクラウド アプリ セキュリティ ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</span><span class="sxs-lookup"><span data-stu-id="4335b-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="4335b-302">クラウド アプリセキュリティダッシュボードとクラウド探索ダッシュボードの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="4335b-303">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="4335b-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="4335b-304">アプリのタグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="4335b-305">アプリの制裁と認可解除。</span><span class="sxs-lookup"><span data-stu-id="4335b-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="4335b-306">アクティビティログとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="4335b-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="4335b-307">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="4335b-308">Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</span><span class="sxs-lookup"><span data-stu-id="4335b-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="4335b-309">CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。</span><span class="sxs-lookup"><span data-stu-id="4335b-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="4335b-310">サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="4335b-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="4335b-311">IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</span><span class="sxs-lookup"><span data-stu-id="4335b-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="4335b-312"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="4335b-313">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="4335b-314">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="4335b-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="4335b-315">Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="4335b-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="4335b-316">詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、「CASB の上位 20 の</a> 使用例」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="4335b-317">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="4335b-318">ブロック スクリプトを使用してアプリの使用状況をブロックする。</span><span class="sxs-lookup"><span data-stu-id="4335b-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="4335b-319">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="4335b-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="4335b-320">サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="4335b-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="4335b-321">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="4335b-322">Microsoft Power Automat プレイブックを含む自動調査と修復。</span><span class="sxs-lookup"><span data-stu-id="4335b-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="4335b-323">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="4335b-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="4335b-324">概念実証としてクラウド アプリの検出を展開する。</span><span class="sxs-lookup"><span data-stu-id="4335b-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="4335b-325"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="4335b-326">Microsoft Defender for Endpoint は、エンタープライズ ネットワークによる高度な脅威の防止、検出、調査、および応答を支援するために設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="4335b-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="4335b-327">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-328">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="4335b-329">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="4335b-330">OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4335b-331">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4335b-332">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="4335b-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="4335b-333">オンボード エンドポイントを使用して Defender for Endpoint エージェント プロファイルを展開する方法を説明して、Microsoft Defender for Endpoint サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="4335b-334">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="4335b-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-335">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-336">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="4335b-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-337">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="4335b-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-338">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="4335b-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-339">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="4335b-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-340">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="4335b-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-341">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="4335b-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="4335b-342">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="4335b-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="4335b-343">Microsoft Defender for Office 365 と Microsoft Defender for Endpoint の統合。</span><span class="sxs-lookup"><span data-stu-id="4335b-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="4335b-344">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="4335b-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="4335b-345">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="4335b-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-346">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="4335b-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-347">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="4335b-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-348">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="4335b-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-349">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="4335b-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-350">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="4335b-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-351">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="4335b-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="4335b-352">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="4335b-353"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4335b-354">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="4335b-355">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="4335b-356">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="4335b-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="4335b-357">次の Microsoft Defender for Endpoint エージェントのオンボーディングまたは構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-358">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="4335b-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-359">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="4335b-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-360">Linux。</span><span class="sxs-lookup"><span data-stu-id="4335b-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-361">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="4335b-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="4335b-362">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="4335b-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-363">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="4335b-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-364">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-365">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-366">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="4335b-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-367">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="4335b-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-368">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="4335b-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-369">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-370">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="4335b-371">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-372">手動展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-373">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="4335b-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-374">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="4335b-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-375">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="4335b-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="4335b-376">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="4335b-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="4335b-377">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="4335b-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-378">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="4335b-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="4335b-379">次のようなアカウント保護機能の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="4335b-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="4335b-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="4335b-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="4335b-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="4335b-382">BitLocker の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="4335b-383">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="4335b-384">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="4335b-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="4335b-385">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="4335b-386">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="4335b-387">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="4335b-388">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="4335b-389"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="4335b-390">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="4335b-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="4335b-391">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="4335b-392">Defender for Identity のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="4335b-393">Defender for Identity を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="4335b-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="4335b-394">ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="4335b-395">リソース容量計画のサイジング ツールを実行する。</span><span class="sxs-lookup"><span data-stu-id="4335b-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="4335b-396">監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="4335b-397">センサーを展開して、ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャおよび解析します。次の内容を含む。</span><span class="sxs-lookup"><span data-stu-id="4335b-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="4335b-398">センサー パッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="4335b-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="4335b-399">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="4335b-400">センサーをドメイン コントローラーにサイレント モードでインストールします。</span><span class="sxs-lookup"><span data-stu-id="4335b-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="4335b-401">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="4335b-402">Defender for Identity と Microsoft Cloud App Security の統合 (Cloud App Security のライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="4335b-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="4335b-403">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="4335b-404">"ノイズ" を低減するために環境を調整します。</span><span class="sxs-lookup"><span data-stu-id="4335b-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="4335b-405">ID セキュリティポスチャ評価レポートについて。</span><span class="sxs-lookup"><span data-stu-id="4335b-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="4335b-406">ユーザーの調査の優先度スコアとユーザー調査のランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="4335b-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="4335b-407">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="4335b-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="4335b-408">侵害されたアカウントに修復オプションを提供する。</span><span class="sxs-lookup"><span data-stu-id="4335b-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="4335b-409">Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。</span><span class="sxs-lookup"><span data-stu-id="4335b-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="4335b-410"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="4335b-411">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="4335b-412">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="4335b-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="4335b-413">以下を含む、Defender for Identity センサーの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="4335b-414">手動の容量計画。</span><span class="sxs-lookup"><span data-stu-id="4335b-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="4335b-415">スタンドアロン容量でのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="4335b-416">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="4335b-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="4335b-417">サード パーティ製のツールを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="4335b-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="4335b-418">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="4335b-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="4335b-419">honeytokens の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="4335b-420">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="4335b-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="4335b-421">さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="4335b-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="4335b-422">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="4335b-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="4335b-423">脅威または高度な狩猟。</span><span class="sxs-lookup"><span data-stu-id="4335b-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="4335b-424">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="4335b-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="4335b-425">Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。</span><span class="sxs-lookup"><span data-stu-id="4335b-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="4335b-426">Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="4335b-427">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="4335b-428">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="4335b-429">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="4335b-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="4335b-430">Defender for Identity センサーを概念実証として展開する。</span><span class="sxs-lookup"><span data-stu-id="4335b-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4335b-431">Active Directory が展開されました。</span><span class="sxs-lookup"><span data-stu-id="4335b-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="4335b-432">Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="4335b-433">Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="4335b-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="4335b-434">次のいずれかの方法で実行されているドメイン コントローラー。</span><span class="sxs-lookup"><span data-stu-id="4335b-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="4335b-435">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="4335b-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="4335b-436">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="4335b-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="4335b-437">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="4335b-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="4335b-438">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="4335b-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="4335b-439">WINDOWS Server 2019 および KB4487044 (OS ビルド 17763.316)。</span><span class="sxs-lookup"><span data-stu-id="4335b-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="4335b-440"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="4335b-441">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-442">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="4335b-443">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="4335b-444">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="4335b-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="4335b-445">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="4335b-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4335b-446">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="4335b-447"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="4335b-448">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-449">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="4335b-450">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="4335b-451">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="4335b-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="4335b-452">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="4335b-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="4335b-453">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="4335b-454">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="4335b-455">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="4335b-456">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="4335b-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="4335b-457">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="4335b-458">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="4335b-459">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="4335b-460">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="4335b-461">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="4335b-462">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="4335b-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="4335b-463">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="4335b-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="4335b-464">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="4335b-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="4335b-465">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="4335b-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="4335b-466">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="4335b-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="4335b-467">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="4335b-468">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="4335b-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="4335b-469">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="4335b-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="4335b-470">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-471"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="4335b-472">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-473">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-474">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-475">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-476">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-477">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-478">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-479">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-480">Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="4335b-481">Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="4335b-482">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="4335b-483">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="4335b-484">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="4335b-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="4335b-485">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="4335b-486">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="4335b-487">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="4335b-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="4335b-488">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="4335b-489">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="4335b-490">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="4335b-491">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="4335b-492">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="4335b-493">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="4335b-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="4335b-494">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="4335b-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="4335b-495">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="4335b-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="4335b-496">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="4335b-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="4335b-497">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="4335b-498"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="4335b-499">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="4335b-499">Customer key.</span></span></li>
<li><span data-ttu-id="4335b-500">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="4335b-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="4335b-501">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="4335b-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="4335b-502">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="4335b-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="4335b-503">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="4335b-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="4335b-504">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="4335b-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="4335b-505">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="4335b-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="4335b-506">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="4335b-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="4335b-507">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="4335b-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="4335b-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="4335b-509">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4335b-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="4335b-510">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="4335b-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="4335b-511">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="4335b-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="4335b-512">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="4335b-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="4335b-513">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="4335b-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="4335b-514">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="4335b-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="4335b-515">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="4335b-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="4335b-516">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-516">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="4335b-517">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="4335b-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="4335b-518">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="4335b-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="4335b-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="4335b-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="4335b-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="4335b-521">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="4335b-522">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="4335b-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="4335b-524">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="4335b-525">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="4335b-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="4335b-526">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="4335b-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-527">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="4335b-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4335b-528">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="4335b-529">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4335b-530">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-531">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="4335b-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-532">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="4335b-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-533">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-534">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="4335b-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-535">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="4335b-536">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="4335b-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-537">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="4335b-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="4335b-538">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="4335b-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="4335b-539">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="4335b-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-540">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="4335b-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4335b-541">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="4335b-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4335b-542">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="4335b-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="4335b-543">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="4335b-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="4335b-544">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="4335b-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-545">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="4335b-546">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="4335b-547">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="4335b-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-548">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="4335b-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-549">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="4335b-550">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="4335b-551">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="4335b-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="4335b-552">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="4335b-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="4335b-553">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4335b-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="4335b-554">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="4335b-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4335b-555">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="4335b-556">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4335b-557">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4335b-558">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="4335b-559">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="4335b-560">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="4335b-561">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="4335b-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="4335b-562"><strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="4335b-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="4335b-563">Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="4335b-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="4335b-564">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="4335b-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-565">Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="4335b-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="4335b-566">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-567">Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="4335b-568">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="4335b-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-569">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="4335b-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4335b-570">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="4335b-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="4335b-571">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="4335b-572"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="4335b-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="4335b-573"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="4335b-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="4335b-574">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="4335b-575"><strong>エンドポイント用 Microsoft Defender と統合された Intune</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="4335b-576"><strong>注</strong>: Intune と Microsoft Defender for Endpoint を統合し、Windows 10 のリスク レベル評価に基づいてデバイス コンプライアンス ポリシーを作成する際のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="4335b-577">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="4335b-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="4335b-578">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="4335b-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="4335b-580">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="4335b-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="4335b-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-582"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-583"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-584"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4335b-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="4335b-586">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="4335b-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="4335b-587">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="4335b-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="4335b-588">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-589">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="4335b-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-590">メール交換 (MX) レコードを 365 Officeします。</span><span class="sxs-lookup"><span data-stu-id="4335b-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-591">サブスクリプション サービスの一部である場合Office 365 機能用に Microsoft Defender をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="4335b-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="4335b-592">詳細については、この表の <strong>「Microsoft Defender for Office 365」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="4335b-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="4335b-p128">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="4335b-597">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、情報権利管理 (IRM) メールをオンプレミスメールボックスから対応する Exchange Online メールボックスに移行します。</span><span class="sxs-lookup"><span data-stu-id="4335b-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="4335b-598">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="4335b-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="4335b-599">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4335b-600">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="4335b-601">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="4335b-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="4335b-602">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="4335b-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-603">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="4335b-604">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="4335b-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="4335b-605">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="4335b-606">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="4335b-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-607">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="4335b-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="4335b-608">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="4335b-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="4335b-609">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="4335b-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="4335b-610">複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域機能」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="4335b-611">Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="4335b-612"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="4335b-613">詳細については<strong>、「Microsoft Defender for Office 365」</strong><a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="4335b-614"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="4335b-615">詳細については <strong> 、「Microsoft Information Governance in Security</strong> and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-616"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="4335b-617">詳細については <strong>、「Microsoft Information Protection in Security </strong> and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="4335b-619">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-620">Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADで Teams をサポートしていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="4335b-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="4335b-621">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4335b-622">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="4335b-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="4335b-623">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="4335b-624">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="4335b-625">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="4335b-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-626">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="4335b-627">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="4335b-628">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="4335b-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="4335b-629">Teams アプリ ポリシーの構成 (Teams Web アプリ、Teams デスクトップ アプリ、および Teams for iOS および Android アプリ)。</span><span class="sxs-lookup"><span data-stu-id="4335b-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="4335b-630">該当する場合は、次のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-631">Microsoft Teams ルーム デバイス:</span><span class="sxs-lookup"><span data-stu-id="4335b-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="4335b-632"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="4335b-633">認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="4335b-634">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="4335b-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="4335b-635">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="4335b-636">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="4335b-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="4335b-637">電話システム:</span><span class="sxs-lookup"><span data-stu-id="4335b-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-638">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="4335b-639">通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="4335b-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="4335b-640">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="4335b-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="4335b-641">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="4335b-642">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4335b-643">直接ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="4335b-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-644">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="4335b-645">セッション ボーダー コントローラー (SBC) の構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="4335b-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="4335b-646">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="4335b-647">音声ルートの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="4335b-648">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="4335b-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="4335b-649">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="4335b-650">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="4335b-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="4335b-651">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4335b-652">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="4335b-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-653">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="4335b-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="4335b-654">Exchange メールボックスが存在します (Exchange ハイブリッド構成ではオンラインとオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="4335b-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="4335b-655">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="4335b-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="4335b-656">
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスで割り当ておよび有効になっていない場合、OneDrive for Business ストレージは 365 Officeされません。</span><span class="sxs-lookup"><span data-stu-id="4335b-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="4335b-657">ファイル共有はチャネルで引き続き機能しますが、ユーザーは 365 で OneDrive for Business ストレージを使用せずにチャットでファイルをOfficeできます。</span><span class="sxs-lookup"><span data-stu-id="4335b-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="4335b-658">Teams は SharePoint オンプレミスをサポートしない。</span><span class="sxs-lookup"><span data-stu-id="4335b-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="4335b-659">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する場合です。</span><span class="sxs-lookup"><span data-stu-id="4335b-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="4335b-660">オンプレミスに存在するメールボックスを持つユーザーは、Azure Office Connect を介して id を Office 365 ディレクトリAD必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="4335b-661">これらの Exchange ハイブリッド顧客の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="4335b-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="4335b-662">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="4335b-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="4335b-663"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="4335b-664">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-665">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="4335b-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="4335b-666">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="4335b-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="4335b-667">Outlook モバイルのセキュリティ保護 (詳細 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">については、「Exchange Online</a> での Outlook for iOS と Android のセキュリティ保護」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4335b-667">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4335b-668">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="4335b-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-669">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="4335b-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="4335b-671">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-672">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="4335b-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="4335b-673">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4335b-674">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="4335b-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="4335b-676">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-677">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="4335b-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="4335b-678">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="4335b-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="4335b-679">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="4335b-680">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4335b-681">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="4335b-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-682"><strong>Project Online Professional and Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="4335b-683">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-684">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="4335b-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="4335b-685">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="4335b-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="4335b-686">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="4335b-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="4335b-687">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4335b-688">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="4335b-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4335b-689">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="4335b-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4335b-690">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="4335b-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-691"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="4335b-692">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-693">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="4335b-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="4335b-694">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4335b-695">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="4335b-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="4335b-696">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="4335b-697">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="4335b-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="4335b-698">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="4335b-699">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="4335b-700">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="4335b-701">移行方法。</span><span class="sxs-lookup"><span data-stu-id="4335b-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="4335b-702">SharePoint のバージョンに応じて、OneDrive for Business に関する追加のガイダンスが提供されます。次のようにします。</span><span class="sxs-lookup"><span data-stu-id="4335b-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-703">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="4335b-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="4335b-704">SharePoint Online 2013 SP1 のインストール (該当する場合)、同期要件と ID 要件の計画と実装、OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="4335b-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="4335b-705">すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。</span><span class="sxs-lookup"><span data-stu-id="4335b-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="4335b-706">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリのリダイレクトを Office 365 (SharePoint Online 2013 に適用) し、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="4335b-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="4335b-707">既知のフォルダーを OneDrive にリダイレクトまたは移動する。</span><span class="sxs-lookup"><span data-stu-id="4335b-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="4335b-708">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="4335b-709">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="4335b-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="4335b-710">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="4335b-711"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="4335b-712">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4335b-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="4335b-713">
  <strong>注:</strong> セルフサービス サイトの作成は、SharePoint 2013 を実行しているオンプレミス サーバーでは有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="4335b-714">SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="4335b-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="4335b-715">
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードはスコープ内ではありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="4335b-716">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="4335b-717">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能の最小パブリック更新レベル」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="4335b-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="4335b-718">
  <strong>注:</strong> 複数地域機能の詳細については、「OneDrive の複数地域機能」および <a href="https://go.microsoft.com/fwlink/?linkid=831056">「SharePoint Online in oneDrive」および「SharePoint Online in Office 365」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="4335b-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="4335b-720">エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="4335b-721">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="4335b-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="4335b-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="4335b-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-723"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-724"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-725"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4335b-726"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="4335b-727">詳細については <strong> 、「Azure Active Directory (Azure AD)</strong> と Azure AD Premium in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4335b-728"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="4335b-728"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="4335b-729">Azure Information Protection の詳細については <strong>、「Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Compliance」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-729">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="4335b-730"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-730"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="4335b-731">詳細については <strong> 、「Microsoft Intune in Security</strong> and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-731">For more information, see <strong> Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="4335b-732">Windows 10</span><span class="sxs-lookup"><span data-stu-id="4335b-732">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-733"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-733"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-734"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-734"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-735"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-735"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4335b-736"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-736"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="4335b-737">Windows 10 Enterprise への Windows 7 Professionalおよび Windows 8.1 Professional へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-737">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="4335b-738">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-738">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-739">Windows 10 の意図を理解する。</span><span class="sxs-lookup"><span data-stu-id="4335b-739">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="4335b-740">ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="4335b-740">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="4335b-741">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-741">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="4335b-742">Windows 10 アプリを評価するためのオプションをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4335b-742">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="4335b-743">デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="4335b-743">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="4335b-744">構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と Microsoft 365 Apps の展開を支援することで、Microsoft 365 Apps の互換性評価を行います。</span><span class="sxs-lookup"><span data-stu-id="4335b-744">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="4335b-745">展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="4335b-745">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="4335b-746">必要なデバイス ハードウェア要件を満たす場合に、既存のデバイスのアップグレード ガイダンスを Windows 10 Enterprise に提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-746">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="4335b-747">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-747">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="4335b-748">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="4335b-748">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="4335b-749">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="4335b-749">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="4335b-750">Windows 10 展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="4335b-750">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="4335b-751">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-751">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="4335b-752">
  
<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-752">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4335b-753">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="4335b-753">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="4335b-754">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-754">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="4335b-755">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-755">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="4335b-756">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="4335b-756">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="4335b-757">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="4335b-757">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="4335b-758">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="4335b-758">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="4335b-759">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-759">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="4335b-760">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="4335b-760">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="4335b-761">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="4335b-762">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-762">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-763">ソース OS: Windows 7 Enterpriseまたはプロフェッショナル、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="4335b-763">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="4335b-764">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="4335b-764">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="4335b-765">ターゲット OS: ウィンドウ 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="4335b-765">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="4335b-766">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-766">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-767">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="4335b-767">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="4335b-768">Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-768">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="4335b-769">詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-769">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="4335b-770"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-770"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="4335b-771">詳細については <strong> 、「Microsoft Defender for Endpoint in Security and</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-771">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="4335b-772">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="4335b-772">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-773"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-773"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-774"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-774"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-775"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-775"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4335b-776"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-776"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="4335b-777">Windows Virtual Desktop (デスクトップおよびアプリ仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-777">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="4335b-778">Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="4335b-778">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="4335b-779">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-779">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="4335b-780">Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows 仮想デスクトップ環境を展開するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="4335b-780">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="4335b-781">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="4335b-781">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="4335b-782">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="4335b-782">Shared image.</span></span></li>
<li><span data-ttu-id="4335b-783">Office展開Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="4335b-783">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="4335b-784">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="4335b-784">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="4335b-785">プロファイル コンテナーを使用した FSLogix エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-785">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="4335b-786">FSLogix エージェントをコンテナーでOfficeします。</span><span class="sxs-lookup"><span data-stu-id="4335b-786">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="4335b-787">コンテンツの除外を使用して FSLogix フォルダーを構成する。</span><span class="sxs-lookup"><span data-stu-id="4335b-787">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="4335b-788">Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-788">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="4335b-789">Microsoft Teams の展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-789">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="4335b-790">Windows 仮想デスクトップ クライアントを使用した接続。</span><span class="sxs-lookup"><span data-stu-id="4335b-790">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="4335b-791">

<strong>以下はスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="4335b-791">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="4335b-792">お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-792">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="4335b-793">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-793">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="4335b-794">カスタム イメージ。</span><span class="sxs-lookup"><span data-stu-id="4335b-794">Custom images.</span></span></li>
<li><span data-ttu-id="4335b-795">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="4335b-795">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="4335b-796">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="4335b-796">Linux scenarios.</span></span></li>
<li><span data-ttu-id="4335b-797">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="4335b-797">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="4335b-798">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-798">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="4335b-799">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="4335b-799">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="4335b-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="4335b-801">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="4335b-801">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="4335b-802">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="4335b-802">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="4335b-803">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="4335b-803">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="4335b-804">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="4335b-804">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="4335b-805">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="4335b-805">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="4335b-806">Windows 仮想デスクトップへの接続を許可するファイアウォール ルール。</span><span class="sxs-lookup"><span data-stu-id="4335b-806">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="4335b-807">詳細については、「サポートされる <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> リモート デスクトップ クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-807">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="4335b-808">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="4335b-808">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="4335b-809">ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="4335b-809">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="4335b-810">Azure を使用した Active Directory AD Azure で接続します。</span><span class="sxs-lookup"><span data-stu-id="4335b-810">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="4335b-811">Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</span><span class="sxs-lookup"><span data-stu-id="4335b-811">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="4335b-812">Active Directory ドメイン サービス (DS AD)。</span><span class="sxs-lookup"><span data-stu-id="4335b-812">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="4335b-813">App Assure</span><span class="sxs-lookup"><span data-stu-id="4335b-813">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-814"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-814"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-815"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-815"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-816"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-816"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4335b-817"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-817"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="4335b-818">App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="4335b-818">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="4335b-819">App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="4335b-819">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="4335b-820">また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様に対してガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力をします。</span><span class="sxs-lookup"><span data-stu-id="4335b-820">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="4335b-821">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="4335b-821">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="4335b-822"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="4335b-822"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="4335b-823"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="4335b-823"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="4335b-824"><strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-824"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="4335b-825"><strong>Windows 仮想デスクトップ</strong> - 詳細については <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは」</a> および <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">「Windows 10 Enterprise マルチセッション FAQ」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-825"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="4335b-826">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-826">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4335b-827">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="4335b-827">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="4335b-828">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-828">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="4335b-829">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-829">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="4335b-830">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="4335b-830">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="4335b-831">詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4335b-831">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="4335b-832">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="4335b-832">App packaging-only services.</span></span> <span data-ttu-id="4335b-833">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="4335b-833">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="4335b-834">

<strong>顧客の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-834">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="4335b-835">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="4335b-835">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="4335b-836">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="4335b-836">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="4335b-837">
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="4335b-837">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="4335b-838">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="4335b-838">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="4335b-839">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="4335b-839">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="4335b-840"><strong>Windows 10 および Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="4335b-840"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-841">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="4335b-841">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="4335b-842">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="4335b-842">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="4335b-843">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Apps でも動作します。</span><span class="sxs-lookup"><span data-stu-id="4335b-843">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="4335b-844">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="4335b-844">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="4335b-845">x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様に <a href="https://insider.windows.com/">プレビューで使用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-845">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="4335b-846">Windows 10 バージョン 2004 以降の Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">してサポートされています</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-846">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="4335b-847">Windows Insider Program のお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="4335b-847">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="4335b-848">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="4335b-848">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-849">Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="4335b-849">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-850">Web は常に進化していますので、Microsoft Edge の既知のサイト互換性に影響を与える変更の公開リストを <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">必ず確認してください</a>。</span><span class="sxs-lookup"><span data-stu-id="4335b-850">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="4335b-851">
  <strong>Windows 仮想デスクトップ </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-851">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4335b-852">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-852">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-853">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 仮想デスクトップの一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-853">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-854">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-854">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="4335b-855">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4335b-855">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="4335b-856">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="4335b-856">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-857">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4335b-857">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4335b-858">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="4335b-858">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="4335b-859">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="4335b-859">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4335b-860"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-860"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4335b-861"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-861"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4335b-862"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="4335b-862"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4335b-863"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="4335b-863"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="4335b-864">リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。</span><span class="sxs-lookup"><span data-stu-id="4335b-864">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="4335b-865">Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager または Intune) を使用した Windows 10 での Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="4335b-865">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="4335b-866">Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="4335b-866">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="4335b-867">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="4335b-867">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="4335b-868">既存のエンタープライズ Internet Explorerリストを使用して、このモードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="4335b-868">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="4335b-869">(詳細については、「Engaging <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack」を参照してください</a>)。</span><span class="sxs-lookup"><span data-stu-id="4335b-869">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="4335b-870">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4335b-870">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="4335b-871">App Assure の互換性サポートを要求するには <a href="https://fasttrack.microsoft.com/portal#/signin">、FastTrack</a> ポータルにサインインしてエンゲージメントを開始します。</span><span class="sxs-lookup"><span data-stu-id="4335b-871">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="4335b-872">Microsoft Search ブックマークのエッジ導入と構成ガイダンスの計画ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="4335b-872">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="4335b-873">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4335b-873">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="4335b-874">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="4335b-874">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="4335b-875">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="4335b-875">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
