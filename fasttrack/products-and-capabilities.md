---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416566"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="39783-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="39783-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="39783-105">FastTrack でサポートされるサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="39783-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="39783-106">このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="39783-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="39783-108">FastTrack では、最初にコア機能 (すべてのサービスで共通) を使用し、次Microsoft Online Services対象となる各サービスをオンボーディングする場合に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="39783-109">全般</span><span class="sxs-lookup"><span data-stu-id="39783-109">General</span></span>](#general)
  - [<span data-ttu-id="39783-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="39783-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="39783-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="39783-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="39783-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="39783-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="39783-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="39783-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="39783-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="39783-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="39783-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="39783-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="39783-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="39783-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="39783-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="39783-118">全般</span><span class="sxs-lookup"><span data-stu-id="39783-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-120"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="39783-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="39783-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="39783-123">サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="39783-124">また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="39783-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="39783-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="39783-126"></li>
</ul>  

<strong> Identity Integration </strong></span><span class="sxs-lookup"><span data-stu-id="39783-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="39783-127">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="39783-128">Azure AD Connect (単一フォレストまたは複数フォレスト) とライセンス (グループ ベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="39783-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="39783-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="39783-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="39783-130">クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</span><span class="sxs-lookup"><span data-stu-id="39783-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="39783-131">Azure AD接続ツールと同期された単一の Active Directory フォレストと ID を持つユーザーの FS AD有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="39783-132">これには、R2 active Directory フェデレーション Windows Server 2012 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="39783-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="39783-133">パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</span><span class="sxs-lookup"><span data-stu-id="39783-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="39783-134">シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</span><span class="sxs-lookup"><span data-stu-id="39783-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="39783-135">Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="39783-136">アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">有効にする</a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="39783-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="39783-137"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="39783-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="39783-138">FastTrack のメリットの一環として、Microsoft 365 の最高レベルのパフォーマンスを確保するためにクラウド サービスに接続するためのベスト プラクティスについてアドバイスします。</span><span class="sxs-lookup"><span data-stu-id="39783-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="39783-139"><strong>Active Directory フォレスト</strong> これらは、次のフォレスト構成を使用して、Windows Server 2003 以降に機能フォレスト レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="39783-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="39783-140">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="39783-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="39783-141">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="39783-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="39783-142">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="39783-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="39783-143">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="39783-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="39783-144">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="39783-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="39783-145">必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。</span><span class="sxs-lookup"><span data-stu-id="39783-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="39783-146">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="39783-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="39783-147">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="39783-148">Exchange マルチハイブリッド構成で複数の Exchange 組織に複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="39783-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="39783-149">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="39783-150">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="39783-151">複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="39783-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="39783-152">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-153"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="39783-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="39783-154">次のリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-155">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="39783-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="39783-156">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="39783-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="39783-157">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="39783-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="39783-158">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="39783-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="39783-159">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="39783-160">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="39783-161">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="39783-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="39783-162">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="39783-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="39783-163">さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合、互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストで互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="39783-164">詳細については <strong>、「Windows</strong> <a href="#windows-10">10</a> の App Assure 部分」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="39783-165">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="39783-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-166"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="39783-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="39783-167">お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">示します</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="39783-168">これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="39783-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="39783-169">また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="39783-170">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="39783-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="39783-171">Microsoft 365 アプリの最新バージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="39783-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="39783-172"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている場所サービス。</span><span class="sxs-lookup"><span data-stu-id="39783-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="39783-173">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="39783-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-174"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-175"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-176"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="39783-177"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="39783-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="39783-178">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="39783-179">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="39783-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="39783-180">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="39783-181">Azure 以外のプレミアム ユーザー AD、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="39783-182">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="39783-183">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="39783-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="39783-184">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="39783-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="39783-185">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="39783-186">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="39783-187">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="39783-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="39783-188">役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して、Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="39783-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="39783-189">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="39783-190">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="39783-191">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-192">Azure AD 接続正常性を使用AD FS、Azure AD AD 接続、およびドメイン コントローラーのリモート監視を有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="39783-193">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-194">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="39783-195">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-196">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-197">Azure の特権 ID 管理を使用して、特権管理者アカウントへのアクセスAD制御します。</span><span class="sxs-lookup"><span data-stu-id="39783-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="39783-198">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-199">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="39783-200">ユーザーが独自のクラウド セキュリティまたは 365 グループを作成および管理Office、Azure ADグループ管理を使用できます。</span><span class="sxs-lookup"><span data-stu-id="39783-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="39783-201">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="39783-202">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-203">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="39783-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-204">オンプレミスの Active Directory とその環境は、Azure AD Premium 用に準備されています。Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復も含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-205"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="39783-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="39783-206">Azure Information Protection の詳細については、この表の <strong>「Microsoft Information Protection」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="39783-207"><strong>検出&応答</strong></span><span class="sxs-lookup"><span data-stu-id="39783-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="39783-208"><strong>高度な電子情報開示</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="39783-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="39783-209">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="39783-210">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="39783-211">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="39783-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="39783-212">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="39783-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="39783-213"><strong>高度な監査</strong> (E5 でのみサポート)</span><span class="sxs-lookup"><span data-stu-id="39783-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="39783-214">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="39783-215">高度な監査を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="39783-216">検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</span><span class="sxs-lookup"><span data-stu-id="39783-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="39783-217">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-218">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-219">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-220">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-221">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-222">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-223">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-224">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="39783-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="39783-225">カスタム スクリプトまたはコーディング。</span><span class="sxs-lookup"><span data-stu-id="39783-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="39783-226">電子情報開示 API。</span><span class="sxs-lookup"><span data-stu-id="39783-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="39783-227">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="39783-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="39783-228">コンプライアンスの境界とセキュリティ フィルター。</span><span class="sxs-lookup"><span data-stu-id="39783-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="39783-229">データ調査。</span><span class="sxs-lookup"><span data-stu-id="39783-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="39783-230">データ主体の要求。</span><span class="sxs-lookup"><span data-stu-id="39783-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="39783-231">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-232">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-233">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="39783-234">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="39783-235"><strong>Insider Threat Management</strong></span><span class="sxs-lookup"><span data-stu-id="39783-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="39783-236">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="39783-237">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="39783-238">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="39783-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="39783-239">ケースの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="39783-240">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="39783-241">人事 (HR) コネクタの作成に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="39783-242">

<strong> コミュニケーションコンプライアンス </strong></span><span class="sxs-lookup"><span data-stu-id="39783-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="39783-243">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="39783-244">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="39783-245">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="39783-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="39783-246">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="39783-247">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-248">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-249">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-250">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-251">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-252">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-253">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-254">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="39783-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="39783-255">Power Automate フローの作成と管理。</span><span class="sxs-lookup"><span data-stu-id="39783-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="39783-256">データ コネクタ (HR コネクタを超えて)。</span><span class="sxs-lookup"><span data-stu-id="39783-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="39783-257">カスタム正規表現 (RegEx) 構成。</span><span class="sxs-lookup"><span data-stu-id="39783-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="39783-258">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-259">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="39783-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="39783-260">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="39783-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="39783-261">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-262">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="39783-263">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="39783-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="39783-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="39783-265">Microsoft 365 Defender は、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="39783-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="39783-266">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="39783-267">Microsoft 365 セキュリティ センターの概要を説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="39783-268">製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。</span><span class="sxs-lookup"><span data-stu-id="39783-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="39783-269">Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、およびメールボックスの調査を調整する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="39783-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="39783-270">複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="39783-271">Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</span><span class="sxs-lookup"><span data-stu-id="39783-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="39783-272"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="39783-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="39783-273">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="39783-274">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="39783-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="39783-275">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="39783-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="39783-276">さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="39783-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="39783-277">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="39783-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="39783-278">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="39783-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="39783-279">セキュリティ情報とイベント管理 (SIEM) または API 統合。</span><span class="sxs-lookup"><span data-stu-id="39783-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="39783-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="39783-281">Microsoft Cloud App Security は、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。</span><span class="sxs-lookup"><span data-stu-id="39783-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="39783-282">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-283">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="39783-284">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="39783-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="39783-285">管理者のアクセスと設定を管理する。</span><span class="sxs-lookup"><span data-stu-id="39783-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="39783-286">監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</span><span class="sxs-lookup"><span data-stu-id="39783-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="39783-287">IP 範囲とタグの設定。</span><span class="sxs-lookup"><span data-stu-id="39783-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="39783-288">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="39783-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="39783-289">クラウド検出を設定して、次の方法でシャドウ IT を提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="39783-290">Microsoft Defender for Endpoints.</span><span class="sxs-lookup"><span data-stu-id="39783-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="39783-291">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="39783-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="39783-292">iboss。</span><span class="sxs-lookup"><span data-stu-id="39783-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="39783-293">アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使用して注目</a> のアプリを接続する。</span><span class="sxs-lookup"><span data-stu-id="39783-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="39783-294">条件付きアクセス ポータルとクラウド アプリ セキュリティ ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</span><span class="sxs-lookup"><span data-stu-id="39783-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="39783-295">クラウド アプリセキュリティダッシュボードとクラウド探索ダッシュボードの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="39783-296">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="39783-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="39783-297">アプリのタグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="39783-298">アプリの制裁と認可解除。</span><span class="sxs-lookup"><span data-stu-id="39783-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="39783-299">アクティビティログとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="39783-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="39783-300">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="39783-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="39783-301">Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="39783-302">CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。</span><span class="sxs-lookup"><span data-stu-id="39783-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="39783-303">サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="39783-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="39783-304">IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</span><span class="sxs-lookup"><span data-stu-id="39783-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="39783-305"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="39783-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="39783-306">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="39783-307">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="39783-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="39783-308">Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="39783-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="39783-309">詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、「CASB の上位 20 の</a> 使用例」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="39783-310">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="39783-311">ブロック スクリプトを使用してアプリの使用状況をブロックする。</span><span class="sxs-lookup"><span data-stu-id="39783-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="39783-312">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="39783-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="39783-313">サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="39783-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="39783-314">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="39783-315">Microsoft Power Automat プレイブックを含む自動調査と修復。</span><span class="sxs-lookup"><span data-stu-id="39783-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="39783-316">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="39783-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="39783-317">概念実証としてクラウド アプリの検出を展開する。</span><span class="sxs-lookup"><span data-stu-id="39783-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="39783-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="39783-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="39783-319">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="39783-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="39783-320">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-321">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="39783-322">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="39783-323">OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="39783-324">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="39783-325">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="39783-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="39783-326">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="39783-327">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="39783-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-328">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="39783-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-329">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="39783-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-330">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="39783-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-331">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="39783-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-332">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="39783-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-333">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="39783-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-334">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="39783-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="39783-335">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="39783-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="39783-336">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="39783-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="39783-337">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="39783-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="39783-338">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="39783-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-339">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="39783-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-340">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="39783-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-341">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="39783-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-342">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="39783-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-343">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="39783-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-344">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="39783-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="39783-345">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="39783-346"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-347">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="39783-348">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="39783-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="39783-349">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="39783-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="39783-350">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="39783-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-351">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="39783-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-352">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="39783-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-353">Linux。</span><span class="sxs-lookup"><span data-stu-id="39783-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-354">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="39783-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="39783-355">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="39783-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-356">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="39783-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-357">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-358">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-359">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="39783-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-360">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="39783-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-361">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="39783-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-362">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="39783-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-363">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="39783-364">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-365">手動展開。</span><span class="sxs-lookup"><span data-stu-id="39783-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-366">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="39783-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-367">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="39783-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-368">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="39783-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="39783-369">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="39783-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="39783-370">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="39783-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-371">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="39783-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="39783-372">次のようなアカウント保護機能の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="39783-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="39783-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="39783-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="39783-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="39783-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="39783-375">BitLocker の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="39783-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="39783-376">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="39783-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="39783-377">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="39783-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="39783-378">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="39783-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="39783-379">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="39783-380">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="39783-381">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="39783-382"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="39783-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="39783-383">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="39783-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="39783-384">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="39783-385">Defender for Identity のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="39783-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="39783-386">Defender for Identity を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="39783-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="39783-387">ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="39783-388">リソース容量計画のサイジング ツールを実行する。</span><span class="sxs-lookup"><span data-stu-id="39783-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="39783-389">監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="39783-390">センサーを展開して、ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャおよび解析します。次の内容を含む。</span><span class="sxs-lookup"><span data-stu-id="39783-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="39783-391">センサー パッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="39783-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="39783-392">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="39783-393">センサーをドメイン コントローラーにサイレント モードでインストールします。</span><span class="sxs-lookup"><span data-stu-id="39783-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="39783-394">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="39783-395">Defender for Identity と Microsoft Cloud App Security の統合 (Cloud App Security のライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="39783-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="39783-396">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="39783-397">"ノイズ" を低減するために環境を調整します。</span><span class="sxs-lookup"><span data-stu-id="39783-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="39783-398">ID セキュリティポスチャ評価レポートについて。</span><span class="sxs-lookup"><span data-stu-id="39783-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="39783-399">ユーザーの調査の優先度スコアとユーザー調査のランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="39783-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="39783-400">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="39783-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="39783-401">侵害されたアカウントに修復オプションを提供する。</span><span class="sxs-lookup"><span data-stu-id="39783-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="39783-402">Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。</span><span class="sxs-lookup"><span data-stu-id="39783-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="39783-403"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="39783-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="39783-404">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="39783-405">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="39783-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="39783-406">以下を含む、Defender for Identity センサーの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="39783-407">手動の容量計画。</span><span class="sxs-lookup"><span data-stu-id="39783-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="39783-408">スタンドアロン容量でのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="39783-409">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="39783-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="39783-410">サード パーティ製のツールを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="39783-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="39783-411">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="39783-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="39783-412">honeytokens の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="39783-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="39783-413">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="39783-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="39783-414">さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="39783-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="39783-415">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="39783-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="39783-416">脅威または高度な狩猟。</span><span class="sxs-lookup"><span data-stu-id="39783-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="39783-417">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="39783-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="39783-418">Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。</span><span class="sxs-lookup"><span data-stu-id="39783-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="39783-419">Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="39783-420">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="39783-421">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="39783-422">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="39783-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="39783-423">Defender for Identity センサーを概念実証として展開する。</span><span class="sxs-lookup"><span data-stu-id="39783-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="39783-424">Active Directory が展開されました。</span><span class="sxs-lookup"><span data-stu-id="39783-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="39783-425">Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。</span><span class="sxs-lookup"><span data-stu-id="39783-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="39783-426">Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="39783-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="39783-427">次のいずれかの方法で実行されているドメイン コントローラー。</span><span class="sxs-lookup"><span data-stu-id="39783-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="39783-428">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="39783-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="39783-429">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="39783-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="39783-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="39783-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="39783-431">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="39783-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="39783-432">WINDOWS Server 2019 および KB4487044 (OS ビルド 17763.316)。</span><span class="sxs-lookup"><span data-stu-id="39783-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="39783-433"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="39783-434">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-435">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="39783-436">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="39783-437">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="39783-438">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="39783-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="39783-439">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="39783-440">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-441">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-442">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-443">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-444">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-445">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-446">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-447">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="39783-448">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="39783-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="39783-449">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="39783-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="39783-450">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="39783-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="39783-451">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="39783-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="39783-452">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-453">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="39783-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="39783-454">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-455">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="39783-456">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-457"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="39783-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="39783-458">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-459">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-460">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-461">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-462">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-463">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-464">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-465">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-466">Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-467">Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="39783-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="39783-468">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-469">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-470">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-471">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-472">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-473">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-474">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-475">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="39783-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="39783-476">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-477">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="39783-478">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-479">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-480">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="39783-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-481">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="39783-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-482">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="39783-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="39783-483">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="39783-484"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="39783-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="39783-485">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="39783-485">Customer key.</span></span></li>
<li><span data-ttu-id="39783-486">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="39783-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="39783-487">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="39783-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="39783-488">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="39783-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="39783-489">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="39783-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="39783-490">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-491">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-492">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="39783-493">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="39783-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="39783-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="39783-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="39783-495">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="39783-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-496">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="39783-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="39783-497">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="39783-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="39783-498">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="39783-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="39783-499">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="39783-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="39783-500">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="39783-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="39783-501">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="39783-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="39783-502">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="39783-503">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="39783-504">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="39783-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="39783-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="39783-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="39783-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="39783-507">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="39783-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="39783-508">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="39783-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="39783-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="39783-510">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="39783-511">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="39783-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="39783-512">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="39783-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="39783-513">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="39783-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="39783-514">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="39783-515">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-516">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="39783-517">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="39783-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-518">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="39783-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-519">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-520">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="39783-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="39783-521">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="39783-522">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-523">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="39783-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="39783-524">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="39783-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="39783-525">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="39783-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="39783-526">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="39783-527">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="39783-528">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="39783-529">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="39783-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="39783-530">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="39783-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="39783-531">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="39783-532">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="39783-533">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="39783-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-534">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="39783-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-535">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="39783-536">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="39783-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="39783-537">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="39783-538">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="39783-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="39783-539">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-540">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="39783-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="39783-541">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="39783-542">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-543">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="39783-544">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="39783-545">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="39783-546">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="39783-547">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="39783-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="39783-548"><strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="39783-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="39783-549">Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="39783-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="39783-550">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="39783-551">Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="39783-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="39783-552">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="39783-553">Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="39783-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="39783-554">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-555">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-556">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="39783-557">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="39783-558"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="39783-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="39783-559"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="39783-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="39783-560">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="39783-561"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="39783-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="39783-562"><strong>注</strong>: Intune と Microsoft Defender ATP の統合と、Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供しています。</span><span class="sxs-lookup"><span data-stu-id="39783-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="39783-563">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="39783-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="39783-564">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="39783-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="39783-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="39783-566">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="39783-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="39783-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="39783-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="39783-568">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-569">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="39783-570">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="39783-571">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="39783-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="39783-572">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="39783-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-573">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="39783-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="39783-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-575"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-576"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-577"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="39783-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="39783-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="39783-579">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="39783-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="39783-580">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="39783-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="39783-581">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-582">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="39783-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-583">メール交換 (MX) レコードを 365 Officeします。</span><span class="sxs-lookup"><span data-stu-id="39783-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-584">サブスクリプション サービスのOffice 365 ATP 機能をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="39783-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="39783-585">詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> の部分を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="39783-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="39783-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="39783-p128">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="39783-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="39783-590">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、情報権利管理 (IRM) メールをオンプレミスメールボックスから対応する Exchange Online メールボックスに移行します。</span><span class="sxs-lookup"><span data-stu-id="39783-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="39783-591">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="39783-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="39783-592">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="39783-593">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="39783-594">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="39783-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="39783-595">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="39783-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-596">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="39783-597">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="39783-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="39783-598">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="39783-599">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="39783-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="39783-600">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="39783-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="39783-601">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="39783-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="39783-602">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="39783-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="39783-603">複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域機能」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="39783-604">Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-605"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="39783-606">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-607">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="39783-608">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="39783-609">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="39783-610">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="39783-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="39783-611">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="39783-612">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-613">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-614">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-615">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-616">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-617">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-618">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-619">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="39783-620">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="39783-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="39783-621">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="39783-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="39783-622">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="39783-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="39783-623">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="39783-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="39783-624">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-625">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="39783-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="39783-626">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-627">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="39783-628">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-629"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="39783-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="39783-630">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-631">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-632">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-633">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-634">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-635">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-636">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-637">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-638">Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="39783-639">Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="39783-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="39783-640">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="39783-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="39783-641">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="39783-642">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="39783-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="39783-643">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="39783-644">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="39783-645">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="39783-646">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="39783-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="39783-647">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="39783-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="39783-648">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-649">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="39783-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="39783-650">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-651">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="39783-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-652">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="39783-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-653">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="39783-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="39783-654">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="39783-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="39783-655">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="39783-656"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="39783-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="39783-657">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="39783-657">Customer key.</span></span></li>
<li><span data-ttu-id="39783-658">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="39783-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="39783-659">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="39783-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="39783-660">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="39783-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="39783-661">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="39783-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="39783-662">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="39783-663">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="39783-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="39783-664">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="39783-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="39783-665">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="39783-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="39783-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="39783-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="39783-667">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="39783-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-668">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="39783-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="39783-669">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="39783-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="39783-670">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="39783-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="39783-671">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="39783-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="39783-672">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="39783-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="39783-673">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="39783-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="39783-674">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="39783-675">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="39783-676">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="39783-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="39783-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="39783-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="39783-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="39783-679">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="39783-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="39783-680">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="39783-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="39783-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="39783-682">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-683">Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADで Teams をサポートしていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="39783-684">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="39783-685">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="39783-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="39783-686">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="39783-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="39783-687">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="39783-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="39783-688">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="39783-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="39783-689">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="39783-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="39783-690">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="39783-691">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="39783-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="39783-692">Teams アプリ ポリシーの構成 (Teams Web アプリ、Teams デスクトップ アプリ、および Teams for iOS および Android アプリ)。</span><span class="sxs-lookup"><span data-stu-id="39783-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="39783-693">該当する場合は、次のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-694">Microsoft Teams ルーム デバイス:</span><span class="sxs-lookup"><span data-stu-id="39783-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="39783-695"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="39783-696">認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="39783-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="39783-697">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="39783-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="39783-698">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="39783-699">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="39783-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="39783-700">電話システム:</span><span class="sxs-lookup"><span data-stu-id="39783-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="39783-701">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="39783-702">通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="39783-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="39783-703">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="39783-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="39783-704">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="39783-705">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="39783-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-706">直接ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="39783-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="39783-707">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="39783-708">セッション ボーダー コントローラー (SBC) の構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="39783-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="39783-709">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="39783-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="39783-710">音声ルートの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="39783-711">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="39783-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="39783-712">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="39783-713">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="39783-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="39783-714">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="39783-715">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="39783-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-716">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="39783-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="39783-717">Exchange メールボックスが存在します (Exchange ハイブリッド構成ではオンラインとオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="39783-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="39783-718">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="39783-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="39783-719">
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスで割り当ておよび有効になっていない場合、OneDrive for Business ストレージは 365 Officeされません。</span><span class="sxs-lookup"><span data-stu-id="39783-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="39783-720">ファイル共有はチャネルで引き続き機能しますが、ユーザーは 365 で OneDrive for Business ストレージを使用せずにチャットでファイルをOfficeできます。</span><span class="sxs-lookup"><span data-stu-id="39783-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="39783-721">Teams は SharePoint オンプレミスをサポートしない。</span><span class="sxs-lookup"><span data-stu-id="39783-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="39783-722">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する場合です。</span><span class="sxs-lookup"><span data-stu-id="39783-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="39783-723">オンプレミスに存在するメールボックスを持つユーザーは、Azure Office Connect を介して id を Office 365 ディレクトリAD必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="39783-724">これらの Exchange ハイブリッド顧客の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="39783-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="39783-725">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="39783-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="39783-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="39783-727">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-728">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="39783-729">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="39783-730">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="39783-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="39783-731">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="39783-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-732">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-733"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="39783-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="39783-734">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-735">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="39783-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="39783-736">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="39783-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="39783-737">Outlook モバイルのセキュリティ保護 (詳細 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">については、「Exchange Online</a> での Outlook for iOS と Android のセキュリティ保護」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="39783-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="39783-738">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="39783-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-739">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="39783-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="39783-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="39783-741">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-742">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="39783-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="39783-743">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-744">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="39783-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="39783-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="39783-746">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-747">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="39783-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="39783-748">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="39783-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="39783-749">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="39783-750">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-751">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="39783-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-752"><strong>Project Online Professional and Premium</strong></span><span class="sxs-lookup"><span data-stu-id="39783-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="39783-753">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-754">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="39783-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="39783-755">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="39783-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="39783-756">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="39783-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="39783-757">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="39783-758">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="39783-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="39783-759">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="39783-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-760">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="39783-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-761"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="39783-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="39783-762">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-763">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="39783-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="39783-764">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="39783-765">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="39783-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="39783-766">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="39783-767">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="39783-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="39783-768">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="39783-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="39783-769">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="39783-770">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="39783-771">移行方法。</span><span class="sxs-lookup"><span data-stu-id="39783-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="39783-772">SharePoint のバージョンに応じて、OneDrive for Business に関する追加のガイダンスが提供されます。次のようにします。</span><span class="sxs-lookup"><span data-stu-id="39783-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="39783-773">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="39783-774">SharePoint Online 2013 SP1 のインストール (該当する場合)、同期要件と ID 要件の計画と実装、OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="39783-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="39783-775">すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。</span><span class="sxs-lookup"><span data-stu-id="39783-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="39783-776">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリのリダイレクトを Office 365 (SharePoint Online 2013 に適用) し、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="39783-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="39783-777">既知のフォルダーを OneDrive にリダイレクトまたは移動する。</span><span class="sxs-lookup"><span data-stu-id="39783-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="39783-778">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="39783-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="39783-779">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="39783-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="39783-780">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="39783-781"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-782">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="39783-783">
  <strong>注:</strong> セルフサービス サイトの作成は、SharePoint 2013 を実行しているオンプレミス サーバーでは有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="39783-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="39783-784">SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="39783-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="39783-785">
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードはスコープ内ではありません。</span><span class="sxs-lookup"><span data-stu-id="39783-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="39783-786">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="39783-787">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能の最小パブリック更新レベル」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="39783-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="39783-788">
  <strong>注:</strong> 複数地域機能の詳細については、「OneDrive の複数地域機能」および <a href="https://go.microsoft.com/fwlink/?linkid=831056">「SharePoint Online in oneDrive」および「SharePoint Online in Office 365」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="39783-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="39783-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="39783-790">エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="39783-791">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="39783-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="39783-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="39783-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-793"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-794"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-795"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="39783-796"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="39783-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="39783-797">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="39783-798">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="39783-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="39783-799">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="39783-800">Azure 以外のプレミアム ユーザー AD、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="39783-801">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="39783-802">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="39783-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="39783-803">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="39783-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="39783-804">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="39783-805">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="39783-806">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="39783-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="39783-807">役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して、Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="39783-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="39783-808">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="39783-809">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="39783-810">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-811">Azure AD 接続正常性を使用AD FS、Azure AD AD 接続、およびドメイン コントローラーのリモート監視を有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="39783-812">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-813">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="39783-814">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-815">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="39783-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-816">Azure の特権 ID 管理を使用して、特権管理者アカウントへのアクセスAD制御します。</span><span class="sxs-lookup"><span data-stu-id="39783-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="39783-817">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-818">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="39783-819">ユーザーが独自のクラウド セキュリティまたは 365 グループを作成および管理Office、Azure ADグループ管理を使用できます。</span><span class="sxs-lookup"><span data-stu-id="39783-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="39783-820">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="39783-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="39783-821">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-822">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="39783-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="39783-823">オンプレミスの Active Directory とその環境は、Azure AD Premium 用に準備されています。Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復も含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="39783-824"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="39783-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="39783-825">Azure Information Protection の詳細については <strong>、「Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Compliance」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="39783-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="39783-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="39783-827">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="39783-828">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="39783-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="39783-829">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="39783-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="39783-830">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="39783-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="39783-831">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="39783-832">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-833">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="39783-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="39783-834">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="39783-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-835">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="39783-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-836">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-837">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="39783-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="39783-838">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="39783-839">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-840">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="39783-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="39783-841">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="39783-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="39783-842">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="39783-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="39783-843">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="39783-844">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="39783-845">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-846">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="39783-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="39783-847">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="39783-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="39783-848">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="39783-849">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="39783-850">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="39783-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-851">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="39783-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-852">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="39783-853">
  
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="39783-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="39783-854">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="39783-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="39783-855">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="39783-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="39783-856">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="39783-857">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="39783-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="39783-858">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="39783-859">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="39783-860">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="39783-861">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="39783-862">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="39783-863">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="39783-864">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="39783-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="39783-865"><strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="39783-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="39783-866">Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="39783-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="39783-867">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="39783-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="39783-868">Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="39783-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="39783-869">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="39783-870">Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="39783-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="39783-871">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-872">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="39783-873">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="39783-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="39783-874">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="39783-875"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="39783-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="39783-876"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="39783-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="39783-877">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="39783-878"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="39783-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="39783-879"><strong>注</strong>: Intune と Microsoft Defender ATP の統合と、Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供しています。</span><span class="sxs-lookup"><span data-stu-id="39783-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="39783-880">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="39783-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="39783-881">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="39783-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="39783-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="39783-883">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="39783-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="39783-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="39783-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-885"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-886"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-887"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="39783-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="39783-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="39783-889">Windows 10 Enterprise への Windows 7 Professionalおよび Windows 8.1 Professional へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="39783-890">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-891">Windows 10 の意図を理解する。</span><span class="sxs-lookup"><span data-stu-id="39783-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="39783-892">ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="39783-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="39783-893">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="39783-894">Windows 10 アプリを評価するためのオプションをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="39783-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="39783-895">デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="39783-896">構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と Microsoft 365 Apps の展開を支援することで、Microsoft 365 Apps の互換性評価を行います。</span><span class="sxs-lookup"><span data-stu-id="39783-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="39783-897">展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="39783-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="39783-898">必要なデバイス ハードウェア要件を満たす場合に、既存のデバイスのアップグレード ガイダンスを Windows 10 Enterprise に提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="39783-899">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="39783-900">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="39783-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="39783-901">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="39783-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="39783-902">Windows 10 展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="39783-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="39783-903">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="39783-904">
  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-905">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="39783-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="39783-906">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="39783-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="39783-907">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="39783-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="39783-908">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="39783-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="39783-909">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="39783-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="39783-910">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="39783-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="39783-911">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="39783-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="39783-912">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="39783-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="39783-913">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="39783-914">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="39783-915">ソース OS: Windows 7 Enterpriseまたはプロフェッショナル、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="39783-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="39783-916">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="39783-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="39783-917">ターゲット OS: ウィンドウ 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="39783-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="39783-918">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="39783-919">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="39783-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="39783-920">Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="39783-921">詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="39783-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="39783-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="39783-923">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="39783-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="39783-924">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="39783-925">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="39783-926">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="39783-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="39783-927">OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="39783-928">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="39783-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="39783-929">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="39783-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="39783-930">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="39783-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="39783-931">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="39783-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-932">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="39783-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-933">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="39783-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-934">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="39783-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-935">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="39783-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-936">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="39783-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="39783-937">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="39783-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="39783-938">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="39783-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-939">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="39783-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="39783-940">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="39783-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="39783-941">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="39783-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="39783-942">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="39783-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="39783-943">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="39783-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-944">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="39783-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-945">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="39783-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-946">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="39783-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-947">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="39783-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-948">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="39783-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-949">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="39783-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="39783-950">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39783-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="39783-951"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-952">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="39783-953">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="39783-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="39783-954">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="39783-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="39783-955">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="39783-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-956">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="39783-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-957">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="39783-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-958">Linux。</span><span class="sxs-lookup"><span data-stu-id="39783-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-959">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="39783-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="39783-960">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="39783-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="39783-961">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="39783-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-962">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-963">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-964">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="39783-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-965">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="39783-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-966">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="39783-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-967">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="39783-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-968">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="39783-969">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-970">手動展開。</span><span class="sxs-lookup"><span data-stu-id="39783-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="39783-971">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="39783-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-972">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="39783-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-973">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="39783-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="39783-974">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="39783-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="39783-975">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="39783-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-976">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="39783-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="39783-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="39783-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="39783-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="39783-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="39783-979">BitLocker の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="39783-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="39783-980">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="39783-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="39783-981">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="39783-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="39783-982">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="39783-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="39783-983">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="39783-984">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="39783-985">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="39783-986">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="39783-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-987"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-988"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-989"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="39783-990"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="39783-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="39783-991">Windows Virtual Desktop (デスクトップおよびアプリ仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="39783-992">Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="39783-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="39783-993">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="39783-994">Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows 仮想デスクトップ環境を展開するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="39783-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="39783-995">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="39783-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="39783-996">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="39783-996">Shared image.</span></span></li>
<li><span data-ttu-id="39783-997">Office展開Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="39783-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="39783-998">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="39783-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="39783-999">プロファイル コンテナーを使用した FSLogix エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="39783-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="39783-1000">FSLogix エージェントをコンテナーでOfficeします。</span><span class="sxs-lookup"><span data-stu-id="39783-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="39783-1001">コンテンツの除外を使用して FSLogix フォルダーを構成する。</span><span class="sxs-lookup"><span data-stu-id="39783-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="39783-1002">Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="39783-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="39783-1003">Microsoft Teams の展開。</span><span class="sxs-lookup"><span data-stu-id="39783-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="39783-1004">Windows 仮想デスクトップ クライアントを使用した接続。</span><span class="sxs-lookup"><span data-stu-id="39783-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="39783-1005">

<strong>以下はスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="39783-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="39783-1006">お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="39783-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="39783-1007">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="39783-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="39783-1008">カスタム イメージ。</span><span class="sxs-lookup"><span data-stu-id="39783-1008">Custom images.</span></span></li>
<li><span data-ttu-id="39783-1009">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="39783-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="39783-1010">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="39783-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="39783-1011">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="39783-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="39783-1012">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="39783-1013">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="39783-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="39783-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="39783-1015">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="39783-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="39783-1016">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="39783-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="39783-1017">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="39783-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="39783-1018">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="39783-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="39783-1019">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="39783-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="39783-1020">Windows 仮想デスクトップへの接続を許可するファイアウォール ルール。</span><span class="sxs-lookup"><span data-stu-id="39783-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="39783-1021">詳細については、「サポートされる <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> リモート デスクトップ クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="39783-1022">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="39783-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="39783-1023">ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="39783-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="39783-1024">Azure を使用した Active Directory AD Azure で接続します。</span><span class="sxs-lookup"><span data-stu-id="39783-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="39783-1025">Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</span><span class="sxs-lookup"><span data-stu-id="39783-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="39783-1026">Active Directory ドメイン サービス (DS AD)。</span><span class="sxs-lookup"><span data-stu-id="39783-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="39783-1027">App Assure</span><span class="sxs-lookup"><span data-stu-id="39783-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-1028"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-1029"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-1030"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="39783-1031"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="39783-1032">App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="39783-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="39783-1033">App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="39783-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="39783-1034">また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様に対してガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力をします。</span><span class="sxs-lookup"><span data-stu-id="39783-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="39783-1035">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="39783-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="39783-1036"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="39783-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="39783-1037"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="39783-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="39783-1038"><strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="39783-1039"><strong>Windows 仮想デスクトップ</strong> - 詳細については <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは」</a> および <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">「Windows 10 Enterprise マルチセッション FAQ」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="39783-1040">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-1041">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="39783-1041">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="39783-1042">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-1042">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="39783-1043">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="39783-1043">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="39783-1044">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="39783-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="39783-1045">詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="39783-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="39783-1046">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="39783-1046">App packaging-only services.</span></span> <span data-ttu-id="39783-1047">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="39783-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="39783-1048">

<strong>顧客の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="39783-1049">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="39783-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="39783-1050">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="39783-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="39783-1051">
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="39783-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="39783-1052">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="39783-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="39783-1053">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="39783-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="39783-1054"><strong>Windows 10 および Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="39783-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="39783-1055">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="39783-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="39783-1056">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="39783-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="39783-1057">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Apps でも動作します。</span><span class="sxs-lookup"><span data-stu-id="39783-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="39783-1058">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="39783-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="39783-1059">x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様に <a href="https://insider.windows.com/">プレビューで使用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="39783-1060">Windows 10 バージョン 2004 以降の Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">してサポートされています</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="39783-1061">Windows Insider Program のお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="39783-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="39783-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="39783-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="39783-1063">Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="39783-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-1064">Web は常に進化していますので、Microsoft Edge の既知のサイト互換性に影響を与える変更の公開リストを <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">必ず確認してください</a>。</span><span class="sxs-lookup"><span data-stu-id="39783-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="39783-1065">
  <strong>Windows 仮想デスクトップ </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="39783-1066">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="39783-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-1067">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 仮想デスクトップの一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="39783-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-1068">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="39783-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="39783-1069">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="39783-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="39783-1070">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="39783-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-1071">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="39783-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="39783-1072">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="39783-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="39783-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="39783-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="39783-1074"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="39783-1075"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="39783-1076"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="39783-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="39783-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="39783-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="39783-1078">リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。</span><span class="sxs-lookup"><span data-stu-id="39783-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="39783-1079">Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager または Intune) を使用した Windows 10 での Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="39783-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="39783-1080">Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="39783-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="39783-1081">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="39783-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="39783-1082">既存のエンタープライズ Internet Explorerリストを使用して、このモードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="39783-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="39783-1083">(詳細については、「Engaging <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack」を参照してください</a>)。</span><span class="sxs-lookup"><span data-stu-id="39783-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="39783-1084">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="39783-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="39783-1085">App Assure の互換性サポートを要求するには <a href="https://fasttrack.microsoft.com/portal#/signin">、FastTrack</a> ポータルにサインインしてエンゲージメントを開始します。</span><span class="sxs-lookup"><span data-stu-id="39783-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="39783-1086">Microsoft Search ブックマークのエッジ導入と構成ガイダンスの計画ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="39783-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="39783-1087">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="39783-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="39783-1088">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="39783-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="39783-1089">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="39783-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
