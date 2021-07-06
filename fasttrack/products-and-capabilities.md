---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: 43c8edc915d45c1af84155d82d995860cd966950
ms.sourcegitcommit: c4f9375811fd23d01edd308108340ace15ec4db7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2021
ms.locfileid: "53255506"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="08af6-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="08af6-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="08af6-105">FastTrack でサポートされるサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="08af6-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="08af6-106">このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。</span><span class="sxs-lookup"><span data-stu-id="08af6-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="08af6-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="08af6-108">FastTrack では、最初にコア機能 (すべてのサービスで共通) を使用し、次Microsoft Online Services対象となる各サービスをオンボーディングする場合に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="08af6-109">全般</span><span class="sxs-lookup"><span data-stu-id="08af6-109">General</span></span>](#general)
  - [<span data-ttu-id="08af6-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="08af6-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="08af6-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="08af6-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="08af6-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="08af6-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="08af6-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="08af6-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="08af6-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="08af6-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="08af6-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="08af6-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="08af6-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="08af6-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="08af6-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="08af6-118">全般</span><span class="sxs-lookup"><span data-stu-id="08af6-118">General</span></span>

<table>
<table style="width: 100%">
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-119">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-119">Service</span></span></th>
<th><span data-ttu-id="08af6-120">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-120">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-121">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-121">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="08af6-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="08af6-123">サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="08af6-124">Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も含まれています。セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションも含<a href="/office365/enterprise/office-365-network-connectivity-principles">まれます</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="08af6-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="08af6-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="08af6-126"></li>
</ul>  

<strong> Identity Integration </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="08af6-127">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="08af6-128">Azure AD Connect (単一フォレストまたは複数フォレスト) のインストールと構成、およびライセンス (グループ ベースのライセンスを含む) を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="08af6-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="08af6-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="08af6-130">クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</span><span class="sxs-lookup"><span data-stu-id="08af6-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="08af6-131">パスワードレス認証 (Fast Identity Online (FIDO)2 または Microsoft Authenticator App) を使用して、ユーザーの認証エクスペリエンスを選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="08af6-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="08af6-132">Azure ADと同期された単一の Active Directory フォレストと ID を持つ顧客に対して FS AD Connectします。</span><span class="sxs-lookup"><span data-stu-id="08af6-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="08af6-133">これには、R2 Windows Server 2012フェデレーション サービス 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="08af6-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="08af6-134">パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</span><span class="sxs-lookup"><span data-stu-id="08af6-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="08af6-135">シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</span><span class="sxs-lookup"><span data-stu-id="08af6-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="08af6-136">Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="08af6-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="08af6-137">アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを <a href="/azure/active-directory/saas-apps/tutorial-list">有効にする </a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="08af6-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="08af6-138"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="08af6-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="08af6-139">FastTrack の利点の一部として、クラウド サービスに接続してパフォーマンスの最高レベルを確保するためのベスト プラクティスについてMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="08af6-140"><strong>Active Directory フォレスト</strong>これらは、次のフォレスト構成を使用して、Windows Server 2003 以降の機能フォレスト レベルに設定されています。</span><span class="sxs-lookup"><span data-stu-id="08af6-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-141">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="08af6-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="08af6-142">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="08af6-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-143">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="08af6-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-144">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="08af6-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="08af6-145">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="08af6-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="08af6-146">必要に応じて、テナントの構成とAzure Active Directoryタスク。</span><span class="sxs-lookup"><span data-stu-id="08af6-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="08af6-147">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="08af6-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="08af6-148">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="08af6-149">Exchange マルチハイブリッド構成で複数の Exchange 組織で複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="08af6-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="08af6-150">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="08af6-151">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="08af6-152">複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="08af6-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="08af6-153">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-154"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="08af6-155">次のリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-156">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="08af6-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="08af6-157">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="08af6-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="08af6-158">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="08af6-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="08af6-159">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="08af6-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="08af6-160">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="08af6-161">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="08af6-162">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="08af6-163">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="08af6-164">さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストを使用して互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="08af6-165">詳細については<strong>、「アプリの保証</strong>」<a href="#windows-10">のWindows 10</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="08af6-166">オンライン クライアント ソフトウェアは、[システム要件] および [システム要件] で定義されている最小レベル<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-167"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="08af6-168">お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを <a href="/office365/enterprise/office-365-network-connectivity-principles">示します</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="08af6-169">これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="08af6-170">また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="08af6-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="08af6-171">Microsoft 365 管理センター アクセス。</span><span class="sxs-lookup"><span data-stu-id="08af6-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="08af6-172">最新のバージョンのアプリMicrosoft 365必要です。</span><span class="sxs-lookup"><span data-stu-id="08af6-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="08af6-173">場所サービスは、ネットワーク パフォーマンスに関する推奨事項に従って、Microsoft 365 管理<a href="/Office365/Enterprise/office-365-network-mac-perf-overview">センター (プレビュー) で有効になっています</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="08af6-174">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="08af6-174">Security and Compliance</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-175">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-175">Service</span></span></th>
<th><span data-ttu-id="08af6-176">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-176">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-177">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-177">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="08af6-178"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="08af6-179">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="08af6-180">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="08af6-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="08af6-181">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="08af6-182">FIDO2 またはアプリをMicrosoft Authenticatorします。</span><span class="sxs-lookup"><span data-stu-id="08af6-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="08af6-183">ユーザー以外のユーザー Azure AD Premium、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="08af6-184">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="08af6-185">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="08af6-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="08af6-186">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="08af6-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="08af6-187">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="08af6-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="08af6-188">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="08af6-189">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="08af6-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="08af6-190">役割ベースのアクセス制御 (RBAC) Office 365組み込みの管理役割を使用して管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="08af6-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="08af6-191">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="08af6-192">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="08af6-193">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-194">Azure AD正常性を使用AD FS、Azure AD Connect、およびドメイン コントローラーのリモート監視をAD Connectします。</span><span class="sxs-lookup"><span data-stu-id="08af6-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="08af6-195">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-196">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="08af6-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="08af6-197">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="08af6-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-198">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="08af6-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-199">Azure アカウントを使用して特権管理者アカウントへのアクセスを管理AD Privileged Identity Management。</span><span class="sxs-lookup"><span data-stu-id="08af6-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="08af6-200">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-201">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="08af6-202">ユーザーが独自のクラウド セキュリティまたはセルフサービス グループ管理を使用Office 365グループを作成および管理ADグループを作成および管理できます。</span><span class="sxs-lookup"><span data-stu-id="08af6-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="08af6-203">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="08af6-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="08af6-204">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="08af6-205">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="08af6-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="08af6-206">オンプレミスの Active Directory とその環境は、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復など、Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="08af6-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-207"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="08af6-208">Azure Information Protection の詳細については、この表<strong>Microsoft Information Protection</strong>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="08af6-209"><strong>応答&を検出する</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="08af6-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="08af6-211">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="08af6-212">新しいケースの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="08af6-213">保管担当者を保留に設定する。</span><span class="sxs-lookup"><span data-stu-id="08af6-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="08af6-214">検索の実行。</span><span class="sxs-lookup"><span data-stu-id="08af6-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="08af6-215">検索結果をレビュー セットに追加する。</span><span class="sxs-lookup"><span data-stu-id="08af6-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="08af6-216">レビュー セットで分析を実行する。</span><span class="sxs-lookup"><span data-stu-id="08af6-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="08af6-217">ドキュメントの確認とタグ付け。</span><span class="sxs-lookup"><span data-stu-id="08af6-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="08af6-218">レビュー セットからデータをエクスポートする。</span><span class="sxs-lookup"><span data-stu-id="08af6-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="08af6-219">非データのインポートOffice 365します。</span><span class="sxs-lookup"><span data-stu-id="08af6-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="08af6-220"><strong>高度な監査</strong> (E5 でのみサポート)</span><span class="sxs-lookup"><span data-stu-id="08af6-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="08af6-221">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="08af6-222">高度な監査を有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="08af6-223">検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</span><span class="sxs-lookup"><span data-stu-id="08af6-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="08af6-224">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="08af6-225">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="08af6-226">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="08af6-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="08af6-227">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="08af6-228">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="08af6-229">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="08af6-230">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="08af6-231">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="08af6-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="08af6-232">カスタム スクリプトまたはコーディング。</span><span class="sxs-lookup"><span data-stu-id="08af6-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="08af6-233">電子情報開示 API。</span><span class="sxs-lookup"><span data-stu-id="08af6-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="08af6-234">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="08af6-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="08af6-235">コンプライアンスの境界とセキュリティ フィルター。</span><span class="sxs-lookup"><span data-stu-id="08af6-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="08af6-236">データ調査。</span><span class="sxs-lookup"><span data-stu-id="08af6-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="08af6-237">データ主体の要求。</span><span class="sxs-lookup"><span data-stu-id="08af6-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="08af6-238">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="08af6-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="08af6-239">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="08af6-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="08af6-240">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="08af6-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="08af6-241">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="08af6-242"><strong>インサイダー リスクの管理</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="08af6-243">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="08af6-244">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="08af6-245">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="08af6-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="08af6-246">ケースの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="08af6-247">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="08af6-248">人事 (HR) コネクタの作成に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="08af6-249">

<strong> コミュニケーションコンプライアンス </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="08af6-250">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="08af6-251">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="08af6-252">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="08af6-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="08af6-253">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="08af6-254">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="08af6-255">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="08af6-256">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="08af6-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="08af6-257">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="08af6-258">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="08af6-259">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="08af6-260">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="08af6-261">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="08af6-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="08af6-262">フローの作成Power Automate管理します。</span><span class="sxs-lookup"><span data-stu-id="08af6-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="08af6-263">データ コネクタ (HR コネクタを超えて)。</span><span class="sxs-lookup"><span data-stu-id="08af6-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="08af6-264">カスタム正規表現 (RegEx) 構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="08af6-265">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="08af6-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="08af6-266">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="08af6-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="08af6-267">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="08af6-268">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="08af6-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="08af6-269">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="08af6-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="08af6-270">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="08af6-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="08af6-272">Microsoft 365 Defenderは、エンドポイント、ID、電子メール、アプリ全体の検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="08af6-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="08af6-273">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="08af6-274">セキュリティ センターの概要Microsoft 365提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="08af6-275">製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。</span><span class="sxs-lookup"><span data-stu-id="08af6-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="08af6-276">自動Microsoft 365 Defenderによって侵害された可能性があるアセット、ユーザー、デバイス、およびメールボックスの調査を、ユーザーがどのように調整できるのかについて説明します。</span><span class="sxs-lookup"><span data-stu-id="08af6-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="08af6-277">複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="08af6-278">Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</span><span class="sxs-lookup"><span data-stu-id="08af6-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="08af6-279"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="08af6-280">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="08af6-281">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="08af6-282">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="08af6-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="08af6-283">さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="08af6-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="08af6-284">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="08af6-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="08af6-285">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="08af6-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="08af6-286">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="08af6-287">セキュリティ情報とイベント管理 (SIEM) または API 統合。</span><span class="sxs-lookup"><span data-stu-id="08af6-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="08af6-289">Microsoft Cloud App Securityは、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。</span><span class="sxs-lookup"><span data-stu-id="08af6-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="08af6-290">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-291">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="08af6-292">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="08af6-293">管理者のアクセスと設定を管理する。</span><span class="sxs-lookup"><span data-stu-id="08af6-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="08af6-294">監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</span><span class="sxs-lookup"><span data-stu-id="08af6-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="08af6-295">IP 範囲とタグを設定する方法。</span><span class="sxs-lookup"><span data-stu-id="08af6-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="08af6-296">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="08af6-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-297">次を含むファースト パーティ サービスの統合</span><span class="sxs-lookup"><span data-stu-id="08af6-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="08af6-298">Microsoft Defender for Endpoint。</span><span class="sxs-lookup"><span data-stu-id="08af6-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="08af6-299">Microsoft Defender for Identity。</span><span class="sxs-lookup"><span data-stu-id="08af6-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="08af6-300">Azure AD Identity Protection。</span><span class="sxs-lookup"><span data-stu-id="08af6-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="08af6-301">Azure 情報保護。</span><span class="sxs-lookup"><span data-stu-id="08af6-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-302">次の方法を使用してクラウド検出を設定します。</span><span class="sxs-lookup"><span data-stu-id="08af6-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="08af6-303">Microsoft Defender for Endpoints.</span><span class="sxs-lookup"><span data-stu-id="08af6-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="08af6-304">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="08af6-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="08af6-305">iboss。</span><span class="sxs-lookup"><span data-stu-id="08af6-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-306">アプリのタグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="08af6-307">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="08af6-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="08af6-308">アプリの制裁と認可解除。</span><span class="sxs-lookup"><span data-stu-id="08af6-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="08af6-309">[クラウド検出] Cloud App Securityダッシュボードを確認します。</span><span class="sxs-lookup"><span data-stu-id="08af6-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="08af6-310">アプリ コネクタ <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> を使用して注目</a> のアプリを接続する。</span><span class="sxs-lookup"><span data-stu-id="08af6-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="08af6-311">Azure の条件付きアクセスおよびポータル内の条件付きアクセスでアプリAD保護Cloud App Securityします。</span><span class="sxs-lookup"><span data-stu-id="08af6-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="08af6-312">おすすめアプリの条件付きアクセス アプリコントロールを展開する。</span><span class="sxs-lookup"><span data-stu-id="08af6-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="08af6-313">アクティビティログとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="08af6-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="08af6-314">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="08af6-315">ポリシー テンプレートの確認と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="08af6-316">CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。</span><span class="sxs-lookup"><span data-stu-id="08af6-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="08af6-317">サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="08af6-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="08af6-318">IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</span><span class="sxs-lookup"><span data-stu-id="08af6-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-319">ポータルでのインシデントの相関関係Microsoft 365 Defenderします。</span><span class="sxs-lookup"><span data-stu-id="08af6-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="08af6-320"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="08af6-321">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="08af6-322">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="08af6-323">他の CASB Cloud App Securityとの比較について説明します。</span><span class="sxs-lookup"><span data-stu-id="08af6-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="08af6-324">特定のCloud App Security要件を満たしていることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="08af6-325">テスト以外の実稼働環境へのサービスの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="08af6-326">概念実証としてクラウド アプリの検出を展開する。</span><span class="sxs-lookup"><span data-stu-id="08af6-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="08af6-327">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="08af6-328">Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="08af6-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="08af6-329">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="08af6-330">ブロック スクリプトを使用してアプリの使用状況をブロックする。</span><span class="sxs-lookup"><span data-stu-id="08af6-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="08af6-331">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="08af6-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="08af6-332">非機能アプリの条件付きアクセス アプリ制御のオンボーディングと展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="08af6-333">サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="08af6-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="08af6-334">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="08af6-335">Microsoft およびプレイブックを含むPower Automate修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="08af6-336">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="08af6-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="08af6-337"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="08af6-338">Microsoft Defender for Endpoint は、エンタープライズ ネットワークによる高度な脅威の防止、検出、調査、および応答を支援するために設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="08af6-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="08af6-339">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-340">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="08af6-341">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="08af6-342">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="08af6-343">AV サービスまたは他のエンドポイント Windowsソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="08af6-344">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="08af6-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="08af6-345">オンボード エンドポイントを使用して Defender for Endpoint エージェント プロファイルを展開する方法を説明して、Microsoft Defender for Endpoint サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="08af6-346">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="08af6-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-347">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-348">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="08af6-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-349">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="08af6-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-350">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="08af6-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-351">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="08af6-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-352">デバイスのセキュリティで保護されたスコア。</span><span class="sxs-lookup"><span data-stu-id="08af6-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="08af6-353">Microsoft Defender SmartScreenを使用した構成Microsoft エンドポイント マネージャー。</span><span class="sxs-lookup"><span data-stu-id="08af6-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="08af6-354">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="08af6-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="08af6-355">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="08af6-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="08af6-356">Microsoft Defender for Office 365 Microsoft Defender for Endpoint との統合。</span><span class="sxs-lookup"><span data-stu-id="08af6-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="08af6-357">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="08af6-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="08af6-358">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="08af6-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-359">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="08af6-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-360">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="08af6-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-361">Windowsサーバー 2019。</span><span class="sxs-lookup"><span data-stu-id="08af6-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-362">WindowsServer 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="08af6-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-363">Windowsサーバー Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="08af6-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-364">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="08af6-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="08af6-365">
<strong>注:</strong>Windows Server のすべてのバージョンは、最新バージョンの System Center Configuration Manager 2012 (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) で管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="08af6-366"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="08af6-367">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="08af6-368">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="08af6-369">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="08af6-370">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="08af6-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="08af6-371">次の Microsoft Defender for Endpoint エージェントのオンボーディングまたは構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-372">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="08af6-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-373">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="08af6-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-374">Linux。</span><span class="sxs-lookup"><span data-stu-id="08af6-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-375">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="08af6-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="08af6-376">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="08af6-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-377">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="08af6-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-378">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-379">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-380">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="08af6-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-381">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="08af6-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-382">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="08af6-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-383">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-384">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="08af6-385">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-386">手動展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-387">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="08af6-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-388">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="08af6-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-389">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="08af6-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="08af6-390">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="08af6-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="08af6-391">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="08af6-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-392">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="08af6-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="08af6-393">次のようなアカウント保護機能の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="08af6-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="08af6-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="08af6-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="08af6-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-396">BitLocker の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="08af6-397">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="08af6-398">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="08af6-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="08af6-399">ユーザーの登録または構成Microsoft 365 Defender。</span><span class="sxs-lookup"><span data-stu-id="08af6-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="08af6-400">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="08af6-401">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="08af6-402">グループ ポリシー オブジェクト (GPO)、グループ ポリシー オブジェクト、またはグループ ポリシー オブジェクトを使用した Defender SmartScreen 構成をWindows セキュリティまたはガイダンスMicrosoft Edge。</span><span class="sxs-lookup"><span data-stu-id="08af6-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="08af6-403">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="08af6-404"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="08af6-405">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="08af6-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="08af6-406">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-407">リソース容量計画のサイジング ツールを実行する。</span><span class="sxs-lookup"><span data-stu-id="08af6-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="08af6-408">Defender for Identity のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="08af6-409">Defender for Identity を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="08af6-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="08af6-410">センサーを展開して、ネットワーク トラフィックをキャプチャして解析し、Windowsイベントをドメイン コントローラーから直接取得します。次の内容を含む。</span><span class="sxs-lookup"><span data-stu-id="08af6-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="08af6-411">センサー パッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="08af6-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="08af6-412">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="08af6-413">センサーをドメイン コントローラーにサイレント モードでインストールします。</span><span class="sxs-lookup"><span data-stu-id="08af6-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="08af6-414">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="08af6-415">イベント コレクター Windows構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="08af6-416">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="08af6-417">Defender for Identity と Microsoft Cloud App Security統合 (Cloud App Securityライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="08af6-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="08af6-418">エンティティ タグの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="08af6-419">機密性の高いアカウントのタグ付け。</span><span class="sxs-lookup"><span data-stu-id="08af6-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="08af6-420">正常性の問題とセキュリティアラートに関する電子メール通知の受信。</span><span class="sxs-lookup"><span data-stu-id="08af6-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="08af6-421">アラートの除外を構成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="08af6-422">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="08af6-423">Identity Security Posture Assessment レポートについて。</span><span class="sxs-lookup"><span data-stu-id="08af6-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="08af6-424">ユーザー調査の優先度スコアとユーザー調査のランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="08af6-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="08af6-425">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="08af6-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="08af6-426">侵害されたアカウントの修復オプションの説明。</span><span class="sxs-lookup"><span data-stu-id="08af6-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="08af6-427">Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。</span><span class="sxs-lookup"><span data-stu-id="08af6-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="08af6-428"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="08af6-429">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="08af6-430">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="08af6-431">Defender for Identity を概念実証として展開する。</span><span class="sxs-lookup"><span data-stu-id="08af6-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="08af6-432">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="08af6-433">次の Defender for Identity センサー アクティビティを展開または実行します。</span><span class="sxs-lookup"><span data-stu-id="08af6-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="08af6-434">手動の容量計画。</span><span class="sxs-lookup"><span data-stu-id="08af6-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="08af6-435">監査ツールの実行。</span><span class="sxs-lookup"><span data-stu-id="08af6-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="08af6-436">スタンドアロン センサーの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="08af6-437">Active Directory フェデレーション サービス (FS) AD展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="08af6-438">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="08af6-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="08af6-439">サード パーティ製のツールを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="08af6-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="08af6-440">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="08af6-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="08af6-441">Active Directory での Microsoft アカウント (MSA) の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="08af6-442">honeytokens の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="08af6-443">ネットワーク名解決 (NNR) を有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="08af6-444">削除済みオブジェクト コンテナーの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="08af6-445">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="08af6-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="08af6-446">さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="08af6-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="08af6-447">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="08af6-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="08af6-448">脅威または高度な狩猟。</span><span class="sxs-lookup"><span data-stu-id="08af6-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="08af6-449">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="08af6-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="08af6-450">Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。</span><span class="sxs-lookup"><span data-stu-id="08af6-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="08af6-451">Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="08af6-452">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="08af6-453">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="08af6-454">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="08af6-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="08af6-455">Id の <a href="/defender-for-identity/prerequisites"> 前提条件を Microsoft Defender に合わせて調整します</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="08af6-456">Active Directory が展開されました。</span><span class="sxs-lookup"><span data-stu-id="08af6-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="08af6-457">Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="08af6-458">Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="08af6-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-459">次のいずれかの方法で実行されているドメイン コントローラー。</span><span class="sxs-lookup"><span data-stu-id="08af6-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="08af6-460">Windowsサーバー 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="08af6-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="08af6-461">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="08af6-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="08af6-462">Windows Server 2012R2。</span><span class="sxs-lookup"><span data-stu-id="08af6-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="08af6-463">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="08af6-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="08af6-464">WindowsKB4487044 を含むサーバー 2019 (OS ビルド 17763.316 以降)。</span><span class="sxs-lookup"><span data-stu-id="08af6-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="08af6-465">Microsoft .NET Framework 4.7 以降をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="08af6-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="08af6-466">最低 5 GB のディスク領域が必要で、10 GB を推奨します。</span><span class="sxs-lookup"><span data-stu-id="08af6-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="08af6-467">ドメイン コントローラーにインストールされている 2 つの (2) コアと 6 つの (6) GB の RAM。</span><span class="sxs-lookup"><span data-stu-id="08af6-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="08af6-468"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="08af6-p114">Microsoft Defender for Office 365 は、メール メッセージ、リンク (URL)、コラボレーション ツールによってもたらされる悪意のある脅威から組織を保護します。Defender for Office 365 には次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="08af6-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="08af6-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> 脅威保護ポリシー</a>: 脅威保護ポリシーを定義して、組織に適切なレベルの保護を設定します。</span><span class="sxs-lookup"><span data-stu-id="08af6-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="08af6-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">レポート</a>: リアルタイム レポートを表示して、組織内のパフォーマンスOffice 365 Defender を監視します。</span><span class="sxs-lookup"><span data-stu-id="08af6-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="08af6-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">脅威の調査および反応機能</a>: 最先端のツールを使用して、脅威を調査、把握、シミュレーション、および回避を行います。</span><span class="sxs-lookup"><span data-stu-id="08af6-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="08af6-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">自動調査および対応機能</a>: 脅威の調査と軽減にかかる時間と労力を節約します。</span><span class="sxs-lookup"><span data-stu-id="08af6-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="08af6-475">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-476">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="08af6-477">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="08af6-478">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="08af6-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="08af6-479">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="08af6-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="08af6-480">ポータルでのインシデントの相関関係Microsoft 365 Defenderします。</span><span class="sxs-lookup"><span data-stu-id="08af6-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="08af6-481"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="08af6-482">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="08af6-483">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="08af6-484">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="08af6-485">Defender for Office 365他のセキュリティ 製品とを比較するディスカッション。</span><span class="sxs-lookup"><span data-stu-id="08af6-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="08af6-486">Defender for Office 365概念実証として展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="08af6-487">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="08af6-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="08af6-488">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="08af6-489">Microsoft およびプレイブックを含むPower Automate修復。</span><span class="sxs-lookup"><span data-stu-id="08af6-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="08af6-490">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="08af6-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="08af6-491">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="08af6-492"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="08af6-493">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-494">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="08af6-495">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="08af6-496">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="08af6-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="08af6-497">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="08af6-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="08af6-498">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="08af6-499">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="08af6-500">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="08af6-501">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="08af6-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="08af6-502">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="08af6-503">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="08af6-504">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="08af6-505">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="08af6-506">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="08af6-507">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="08af6-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="08af6-508">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="08af6-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="08af6-509">情報アーキテクチャのSharePoint。</span><span class="sxs-lookup"><span data-stu-id="08af6-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="08af6-510">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="08af6-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="08af6-511">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="08af6-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="08af6-512">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="08af6-513">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="08af6-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="08af6-514">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="08af6-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="08af6-515">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-516"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="08af6-517">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-518">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-519">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-520">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-521">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-522">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-523">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-524">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-525">E5 でサポートされているデバイスのエンドポイント データ損失防止 (DLP) Windows 10ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="08af6-526">チャットとチャネルに対Microsoft Teams DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="08af6-527">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="08af6-528">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="08af6-529">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="08af6-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="08af6-530">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="08af6-531">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="08af6-532">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="08af6-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="08af6-533">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="08af6-534">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="08af6-535">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-536">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="08af6-537">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="08af6-538">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="08af6-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="08af6-539">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="08af6-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="08af6-540">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="08af6-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="08af6-541">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="08af6-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="08af6-542">また、Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="08af6-543"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="08af6-544">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="08af6-544">Customer key.</span></span></li>
<li><span data-ttu-id="08af6-545">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="08af6-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="08af6-546">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="08af6-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="08af6-547">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="08af6-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="08af6-548">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="08af6-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="08af6-549">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="08af6-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="08af6-550">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="08af6-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="08af6-551">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="08af6-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="08af6-552">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="08af6-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="08af6-553"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="08af6-554">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="08af6-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-555">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="08af6-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="08af6-556">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="08af6-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="08af6-557">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="08af6-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="08af6-558">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="08af6-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="08af6-559">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="08af6-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="08af6-560">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="08af6-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="08af6-561">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="08af6-562">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="08af6-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="08af6-563">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="08af6-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="08af6-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="08af6-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="08af6-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="08af6-566">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="08af6-567">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="08af6-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="08af6-569">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="08af6-570">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="08af6-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="08af6-571">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="08af6-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-572">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="08af6-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="08af6-573">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="08af6-574">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="08af6-575">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-576">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="08af6-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-577">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="08af6-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-578">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-579">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="08af6-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-580">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="08af6-581">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="08af6-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-582">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="08af6-583">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="08af6-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="08af6-584">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="08af6-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-585">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="08af6-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="08af6-586">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="08af6-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="08af6-587">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="08af6-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="08af6-588">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="08af6-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="08af6-589">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="08af6-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-590">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="08af6-591">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="08af6-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="08af6-592">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="08af6-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-593">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="08af6-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-594">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="08af6-595">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="08af6-596">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="08af6-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="08af6-597">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="08af6-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="08af6-598">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="08af6-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-599">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="08af6-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="08af6-600">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="08af6-601">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="08af6-602">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="08af6-603">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="08af6-604">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="08af6-605">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="08af6-606">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="08af6-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="08af6-607"><strong>iOS Outlook Android 用モバイルを安全に展開する</strong>ユーザーが必要なすべてのアプリをインストールOutlook iOS と Android 用モバイルを安全に組織に展開するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="08af6-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="08af6-608">Intune を使用して iOS および Android Outlookを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="08af6-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="08af6-609">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="08af6-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-610">Apple App Store Outlook Google Play ストアを通じて、iOS と Android、Microsoft Authenticator、Intune ポータル サイトアプリ用のアプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="08af6-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="08af6-611">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-612">iOS Outlook Android、Intune でのアプリMicrosoft Authenticator、Intune ポータル サイトの展開に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="08af6-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="08af6-613">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="08af6-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-614">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="08af6-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="08af6-615">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="08af6-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="08af6-616">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="08af6-617"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="08af6-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="08af6-618"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="08af6-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="08af6-619">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="08af6-620"><strong>エンドポイント用 Microsoft Defender と統合された Intune</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="08af6-621"><strong>注</strong>: Intune と Microsoft Defender for Endpoint を統合し、そのリスク レベル評価に基づいてデバイス コンプライアンス ポリシー Windows 10提供しています。</span><span class="sxs-lookup"><span data-stu-id="08af6-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="08af6-622">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="08af6-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="08af6-623">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="08af6-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="08af6-625">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="08af6-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="08af6-626">Office 365</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-627">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-627">Service</span></span></th>
<th><span data-ttu-id="08af6-628">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-628">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-629">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-629">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="08af6-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="08af6-631">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="08af6-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="08af6-632">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="08af6-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="08af6-633">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-634">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="08af6-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-635">メール交換 (MX) レコードをユーザーにOffice 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-636">サブスクリプション サービスの一部Office 365場合は、Microsoft Defender for Office 365機能をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="08af6-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="08af6-637">詳細については、この表の一<strong>部Office 365</strong> Microsoft Defender を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="08af6-p126">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="08af6-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="08af6-642">
  <strong>注:</strong>メールボックス レプリケーション サービス (MRS) は、Information Rights Managed (IRM) メールをオンプレミスメールボックスから対応するメールボックスに移行Exchange Onlineします。</span><span class="sxs-lookup"><span data-stu-id="08af6-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="08af6-643">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="08af6-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-644">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="08af6-645">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="08af6-646">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="08af6-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="08af6-647">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="08af6-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-648">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="08af6-649">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="08af6-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="08af6-650">FastTrack 特典を使用してデータを移行する方法については、「Office 365」<a href="/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="08af6-651">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="08af6-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-652">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="08af6-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="08af6-653">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="08af6-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="08af6-654">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="08af6-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="08af6-655">複数地域の機能の詳細については、「複数地域の機能」を参照<a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="08af6-656">Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは、Microsoft 365 Office の System requirements で定義されている最小レベルである<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="08af6-657"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="08af6-658">詳細については<strong>、「Microsoft Defender for Office 365」</strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="08af6-659"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="08af6-660">詳細については <strong> 、「Microsoft Information Governance in Security</strong> and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-661"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="08af6-662">詳細については、「セキュリティとコンプライアンス<a href="/fasttrack/products-and-capabilities#security-and-compliance">Microsoft Information Protection」を参照してください</a>。 <strong></strong></span><span class="sxs-lookup"><span data-stu-id="08af6-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="08af6-664">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-665">オンライン、Exchange Online、SharePoint グループ、および Azure Office 365の最小要件を確認して、ADをサポートTeams。</span><span class="sxs-lookup"><span data-stu-id="08af6-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="08af6-666">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="08af6-667">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="08af6-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="08af6-668">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="08af6-669">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="08af6-670">ネットワーク評価のTeams:</span><span class="sxs-lookup"><span data-stu-id="08af6-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-671">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="08af6-672">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="08af6-673">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="08af6-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="08af6-674">アプリ ポリシー Teams構成する (Teams Web アプリ、Teamsデスクトップ アプリ、iOS Teams Android アプリの場合)。</span><span class="sxs-lookup"><span data-stu-id="08af6-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="08af6-675">該当する場合は、次のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-676">Microsoft Teamsルーム デバイス:</span><span class="sxs-lookup"><span data-stu-id="08af6-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="08af6-677"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="08af6-678">認定デバイスのサービス側構成をリモートMicrosoft Teams ミーティングします。</span><span class="sxs-lookup"><span data-stu-id="08af6-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="08af6-679">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="08af6-679">Enabling Audio Conferencing:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="08af6-680">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="08af6-681">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="08af6-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="08af6-682">電話システム:</span><span class="sxs-lookup"><span data-stu-id="08af6-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-683">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="08af6-684">通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="08af6-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="08af6-685">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="08af6-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="08af6-686">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="08af6-687">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="08af6-688">直接ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="08af6-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-689">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="08af6-690">セッション ボーダー コントローラー (SBC) の構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="08af6-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="08af6-691">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="08af6-692">音声ルートの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="08af6-693">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="08af6-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="08af6-694">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="08af6-695">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="08af6-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="08af6-696">移行をSkype for BusinessするTeamsガイダンス。</span><span class="sxs-lookup"><span data-stu-id="08af6-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="08af6-697">Azure ADでOffice 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-698">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="08af6-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="08af6-699">Exchangeメールボックスが存在する (オンラインとオンプレミスのハイブリッド構成Exchange)。</span><span class="sxs-lookup"><span data-stu-id="08af6-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="08af6-700">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="08af6-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="08af6-701">
  <strong>注:</strong>ユーザーがオンライン ライセンスで割り当ておよび有効SharePoint場合、ユーザーはオンライン ライセンスにOneDrive for BusinessストレージOffice 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="08af6-702">ファイル共有はチャネルで引き続き機能しますが、ユーザーはチャット内のファイルを共有OneDrive for Business共有Office 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="08af6-703">TeamsオンプレミスでのSharePointサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="08af6-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="08af6-704">
  <strong>注:</strong>理想的な状態は、すべてのユーザーが自分のメールボックスをユーザーにExchange Online。</span><span class="sxs-lookup"><span data-stu-id="08af6-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="08af6-705">オンプレミスに存在するメールボックスを持つユーザーは、自分の ID を Azure サーバー経由で Office 365 ディレクトリに同期AD Connect。</span><span class="sxs-lookup"><span data-stu-id="08af6-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="08af6-706">これらのユーザー Exchange、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="08af6-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="08af6-707">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="08af6-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="08af6-708"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="08af6-709">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-710">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="08af6-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="08af6-711">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="08af6-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="08af6-712">モバイルOutlookセキュリティ保護 (詳細については、「Outlook <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">iOS</a>および Android のセキュリティ保護Exchange Onlineを参照してください)。</span><span class="sxs-lookup"><span data-stu-id="08af6-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="08af6-713">Azure ADでOffice 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-714">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="08af6-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="08af6-716">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-717">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="08af6-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="08af6-718">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="08af6-719">オンライン クライアント ソフトウェア (Power BI Desktop) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="08af6-721">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-722">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="08af6-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="08af6-723">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="08af6-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="08af6-724">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="08af6-725">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="08af6-726">オンライン クライアント ソフトウェア (Project for Office 365) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-727"><strong>Project Online Professionalとプレミアム</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="08af6-728">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-729">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="08af6-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="08af6-730">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="08af6-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="08af6-731">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="08af6-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="08af6-732">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="08af6-733">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="08af6-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="08af6-734">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="08af6-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="08af6-735">オンライン クライアント ソフトウェア (Project for Office 365) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-736"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="08af6-737">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-738">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="08af6-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="08af6-739">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="08af6-740">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="08af6-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="08af6-741">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="08af6-742">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="08af6-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="08af6-743">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="08af6-744">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="08af6-745">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="08af6-746">移行方法。</span><span class="sxs-lookup"><span data-stu-id="08af6-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="08af6-747">追加のガイダンスは、OneDrive for Businessバージョンに応じてSharePoint提供されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-748">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="08af6-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="08af6-749">オンライン 2013 SP1 のSharePoint (該当する場合) のインストール、同期と ID の要件の計画と実装、および同期クライアントOneDrive for Business識別します。</span><span class="sxs-lookup"><span data-stu-id="08af6-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="08af6-750">すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。</span><span class="sxs-lookup"><span data-stu-id="08af6-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="08af6-751">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に適用)、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="08af6-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="08af6-752">既知のフォルダーを別のフォルダーにリダイレクトOneDrive。</span><span class="sxs-lookup"><span data-stu-id="08af6-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="08af6-753">クライアント同期OneDrive for Business展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="08af6-754">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="08af6-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="08af6-755">FastTrack 特典を使用してデータを移行する方法については、「Office 365」<a href="/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="08af6-756"><strong>ハイブリッドSharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="08af6-757">SharePointハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびセルフ サービス サイトの作成を構成し、オンプレミスから単一のターゲット SharePoint Online 環境に接続します。</span><span class="sxs-lookup"><span data-stu-id="08af6-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="08af6-758">
  <strong>注:</strong>セルフサービス サイトの作成は、2013 年に実行されているオンプレミス サーバー SharePointではありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="08af6-759">ハイブリッドSharePoint有効にするには、2013、2016、または 2019 のいずれかのオンプレミス SharePoint サーバー環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="08af6-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="08af6-760">
  <strong>注:</strong>サーバーがスコープ内SharePointにSharePointオンプレミスの環境のアップグレード。</span><span class="sxs-lookup"><span data-stu-id="08af6-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="08af6-761">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="08af6-762">詳細については、「ハイブリッド機能の<a href="https://go.microsoft.com/fwlink/?linkid=853548">最小公開更新レベルSharePoint参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="08af6-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="08af6-763">
  <strong>注:</strong>複数地域機能の詳細については、「OneDrive および SharePoint の複数地域<a href="https://go.microsoft.com/fwlink/?linkid=831056">機能」を参照</a><em>Office 365。</em>  </span><span class="sxs-lookup"><span data-stu-id="08af6-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="08af6-765">このサービスを有効にするためのリモート ガイダンスをYammer Enterpriseします。</span><span class="sxs-lookup"><span data-stu-id="08af6-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="08af6-766">オンライン クライアント ソフトウェアは、[システム要件] および [システム要件] で定義されている最小レベル<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="08af6-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="08af6-767">Enterprise Mobility + Security</span></span> 

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-768">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-768">Service</span></span></th>
<th><span data-ttu-id="08af6-769">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-769">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-770">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-770">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="08af6-771"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="08af6-772">詳細については、「セキュリティとコンプライアンス<strong>」Azure Active Directory (Azure AD)</strong> Azure AD Premium<a href="/fasttrack/products-and-capabilities#security-and-compliance">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="08af6-773"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="08af6-773"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="08af6-774">Azure Information Protection の詳細については、「セキュリティ<strong>とコンプライアンスMicrosoft Information Protection」</strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-774">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="08af6-775"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-775"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="08af6-776">詳細については、「セキュリティとコンプライアンス<a href="/fasttrack/products-and-capabilities#security-and-compliance">Microsoft Intune」を参照してください</a>。 <strong></strong></span><span class="sxs-lookup"><span data-stu-id="08af6-776">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="08af6-777">Windows 10</span><span class="sxs-lookup"><span data-stu-id="08af6-777">Windows 10</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-778">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-778">Service</span></span></th>
<th><span data-ttu-id="08af6-779">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-779">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-780">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-780">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="08af6-781"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-781"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="08af6-782">7 から 7 へのアップグレードWindows、ProfessionalからWindows 8.1 ProfessionalへのWindows 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="08af6-782">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="08af6-783">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-783">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-784">ユーザーの意図Windows 10理解します。</span><span class="sxs-lookup"><span data-stu-id="08af6-784">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="08af6-785">ソース環境と要件を評価します (Microsoft Endpoint Configuration Manager展開をサポートするために必要なレベルWindows 10してください)。</span><span class="sxs-lookup"><span data-stu-id="08af6-785">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="08af6-786">アプリケーションまたはWindows 10 EnterpriseをMicrosoft 365 AppsしてMicrosoft Endpoint Configuration Manager展開Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-786">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="08af6-787">アプリを評価するためのオプションWindows 10します。</span><span class="sxs-lookup"><span data-stu-id="08af6-787">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="08af6-788">デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="08af6-788">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="08af6-789">Microsoft 365 Apps構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と、Microsoft 365 Apps の展開を支援することで、互換性評価をMicrosoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="08af6-789">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="08af6-790">展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-790">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="08af6-791">既存のデバイスが必要なデバイス ハードウェア要件を満Windows 10 Enterpriseアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-791">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="08af6-792">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-792">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="08af6-793">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="08af6-793">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="08af6-794">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="08af6-794">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="08af6-795">Configuration Manager Microsoft 365 Apps展開の一部として構成マネージャーを使用Windows 10展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-795">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="08af6-796">組織が既存の Configuration Manager 環境またはサーバーを使用Windows 10 EnterpriseおよびMicrosoft 365 Appsを最新の情報にMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-796">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li> 
</ul><span data-ttu-id="08af6-797">
  
<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-797">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="08af6-798">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="08af6-798">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="08af6-799">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-799">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="08af6-800">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-800">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="08af6-801">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="08af6-801">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="08af6-802">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="08af6-802">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="08af6-803">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="08af6-803">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="08af6-804">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-804">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="08af6-805">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="08af6-805">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="08af6-806">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-806">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="08af6-807">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-807">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-808">ソース OS: Windows 7 Enterprise、Professional、Windows 8.1 Enterprise、Professional。</span><span class="sxs-lookup"><span data-stu-id="08af6-808">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="08af6-809">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="08af6-809">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="08af6-810">ターゲット OS: ウィンドウ 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="08af6-810">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="08af6-811">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-811">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-812">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="08af6-812">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="08af6-813">Configuration Manager のバージョンは、ターゲット バージョンでサポートWindows 10必要があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-813">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="08af6-814">詳細については、「<a href="/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-814">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="08af6-815"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-815"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="08af6-816">詳細については <strong> 、「Microsoft Defender for Endpoint in Security and</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-816">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="08af6-817">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="08af6-817">Windows Virtual Desktop</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-818">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-818">Service</span></span></th>
<th><span data-ttu-id="08af6-819">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-819">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-820">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-820">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="08af6-821"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-821"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="08af6-822">仮想デスクトップ (デスクトップおよびアプリの仮想化サービス) Windowsオンボーディングの展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-822">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="08af6-823">Windows仮想デスクトップは、Windows 10セッション エクスペリエンスを活用し、Microsoft 365 AppsとEnterpriseの統合されたセキュリティと管理をMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="08af6-823">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="08af6-824">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-824">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="08af6-825">次のWindows 10 Enterprise使用して、複数Microsoft 365 AppsセッションEnterpriseを展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-825">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="08af6-826">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="08af6-826">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="08af6-827">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="08af6-827">Shared image.</span></span></li>
<li><span data-ttu-id="08af6-828">Office展開Toolkit (ODT)。</span><span class="sxs-lookup"><span data-stu-id="08af6-828">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="08af6-829">ネイティブ Microsoft 365 Apps仮想デスクトップでの FSLogix のWindows構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-829">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="08af6-830">FSLogix の場合:</span><span class="sxs-lookup"><span data-stu-id="08af6-830">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="08af6-831">エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-831">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="08af6-832">プロファイルコンテナーとカスタム コンテナー Office構成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-832">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="08af6-833">コンテンツの除外とフォルダーのリダイレクトを構成するMicrosoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="08af6-833">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="08af6-834">展開Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="08af6-834">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="08af6-835">最適化Microsoft Teamsを展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-835">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="08af6-836">

<strong>以下はスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="08af6-836">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="08af6-837">Project仮想デスクトップ インフラストラクチャ展開のWindows管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-837">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="08af6-838">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="08af6-838">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="08af6-839">仮想デスクトップのカスタム イメージWindows作成します。</span><span class="sxs-lookup"><span data-stu-id="08af6-839">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="08af6-840">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="08af6-840">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="08af6-841">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="08af6-841">Linux scenarios.</span></span></li>
<li><span data-ttu-id="08af6-842">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="08af6-842">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="08af6-843">Microsoft Endpoint Configuration Manager仮想Microsoft エンドポイント マネージャーのWindows構成 (パッチ適用と管理を含む)。</span><span class="sxs-lookup"><span data-stu-id="08af6-843">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="08af6-844">Microsoft 365 DefenderセッションWindows 10を使用します。</span><span class="sxs-lookup"><span data-stu-id="08af6-844">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="08af6-845">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-845">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="08af6-846">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="08af6-846">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="08af6-847"><a href="/azure/virtual-desktop/overview#requirements">Windows仮想デスクトップ のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-847"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="08af6-848">仮想<a href="/azure/virtual-desktop/overview">Deskstop をサポートするためにWindowsインフラストラクチャ</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-848">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="08af6-849"><a href="/azure/virtual-desktop/store-fslogix-profile">Storage Deskstop の FSLogix プロファイル コンテナー Windowsを参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-849"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="08af6-850">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="08af6-850">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="08af6-851">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="08af6-851">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="08af6-852">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="08af6-852">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="08af6-853">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="08af6-853">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="08af6-854">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="08af6-854">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="08af6-855">仮想デスクトップへの接続を許可するWindowsルール。</span><span class="sxs-lookup"><span data-stu-id="08af6-855">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="08af6-856">詳細については、「サポートされる <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">リモート デスクトップ クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-856">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="08af6-857">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="08af6-857">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="08af6-858">ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="08af6-858">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="08af6-859">Azure の Active Directory AD Connectを使用します。</span><span class="sxs-lookup"><span data-stu-id="08af6-859">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="08af6-860">Azure を使用した Active Directory AD Connect VPN または ExpressRoute を使用してオンプレミスで実行できます。</span><span class="sxs-lookup"><span data-stu-id="08af6-860">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="08af6-861">Active Directory ドメイン サービス (DS AD)。</span><span class="sxs-lookup"><span data-stu-id="08af6-861">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="08af6-862">App Assure</span><span class="sxs-lookup"><span data-stu-id="08af6-862">App Assure</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-863">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-863">Service</span></span></th>
<th><span data-ttu-id="08af6-864">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-864">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-865">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-865">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="08af6-866"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="08af6-866"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="08af6-867">App Assure は、アプリの互換性と互換性に関する問題Windows 10解決Microsoft 365 Appsサービスです。</span><span class="sxs-lookup"><span data-stu-id="08af6-867">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="08af6-868">App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="08af6-868">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="08af6-869">また、仮想 Windowsデスクトップと Microsoft Edge を展開する際に互換性の問題に直面しているお客様にもガイダンスを提供し、互換性の問題を解決するためにあらゆる合理的な努力を行います。</span><span class="sxs-lookup"><span data-stu-id="08af6-869">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="08af6-870">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="08af6-870">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="08af6-871"><strong>Windows 10</strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="08af6-871"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="08af6-872"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="08af6-872"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="08af6-873"><strong>Microsoft Edge -</strong>展開のガイダンスについては、「<a href="/DeployEdge/microsoft-edge-channels">チャネルの概要」をMicrosoft Edgeしてください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-873"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="08af6-874"><strong>Windows仮想デスクトップ</strong> -詳細については、「仮想デスクトップとは<a href="/azure/virtual-desktop/overview">Windows」</a>および「Windows 10 Enterprise <a href="/azure/virtual-desktop/windows-10-multisession-faq">FAQ」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-874"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="08af6-875">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-875">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="08af6-876">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="08af6-876">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="08af6-877">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-877">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="08af6-878">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-878">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="08af6-879">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="08af6-879">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="08af6-880">詳細については、「<a href="/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="08af6-880">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="08af6-881">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="08af6-881">App packaging-only services.</span></span> <span data-ttu-id="08af6-882">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="08af6-882">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="08af6-883">

<strong>顧客の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-883">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="08af6-884">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="08af6-884">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="08af6-885">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="08af6-885">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="08af6-886">
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="08af6-886">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="08af6-887">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="08af6-887">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="08af6-888">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="08af6-888">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="08af6-889"><strong>Windows 10とMicrosoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="08af6-889"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-890">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="08af6-890">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="08af6-891">
<strong>Windows 10のARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="08af6-891">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="08af6-892">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Appsでも動作します。</span><span class="sxs-lookup"><span data-stu-id="08af6-892">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="08af6-893">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="08af6-893">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="08af6-894">x64 (64 ビット) エミュレーションは、インサイダー プログラムに参加しているお客様<a href="https://insider.windows.com/">Windowsプレビューで使用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-894">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="08af6-895">Windows 10 バージョン 2004 以降Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用して<a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">サポートされます</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-895">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="08af6-896">Insider Program Windowsのお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="08af6-896">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="08af6-897">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="08af6-897">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-898">Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="08af6-898">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-899">Web は常に進化していますので、サイトの互換性に影響を与える既知の変更の公開リストを確認<a href="/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge。</a></span><span class="sxs-lookup"><span data-stu-id="08af6-899">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="08af6-900">
  <strong>Windows仮想デスクトップ</strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-900">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="08af6-901">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-901">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-902">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 7 Enterprise および Windows 10 Enterprise で Windows 仮想デスクトップの一部として実行されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-902">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-903">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-903">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="08af6-904">
  <strong>注:</strong> Windows 10 Enterpriseの互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="08af6-904">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="08af6-905">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="08af6-905">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-906">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="08af6-906">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="08af6-907">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="08af6-907">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="08af6-908">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="08af6-908">Microsoft Edge</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="08af6-909">サービス</span><span class="sxs-lookup"><span data-stu-id="08af6-909">Service</span></span></th>
<th><span data-ttu-id="08af6-910">FastTrack ガイダンスの詳細</span><span class="sxs-lookup"><span data-stu-id="08af6-910">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="08af6-911">ソース環境要件</span><span class="sxs-lookup"><span data-stu-id="08af6-911">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="08af6-912"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="08af6-912"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="08af6-913">リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。</span><span class="sxs-lookup"><span data-stu-id="08af6-913">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="08af6-914">(Microsoft Edge Intune Windows 10) Microsoft エンドポイント マネージャーにMicrosoft Endpoint Configuration Manager展開します。</span><span class="sxs-lookup"><span data-stu-id="08af6-914">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="08af6-915">構成Microsoft Edge (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="08af6-915">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="08af6-916">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="08af6-916">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="08af6-917">既存のInternet Explorerリストを使用してEnterpriseモードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="08af6-917">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="08af6-918">(詳細については、「Engaging <a href="/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="08af6-918">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="08af6-919">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="08af6-919">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="08af6-920">App Assure の互換性サポートを要求するには <a href="https://fasttrack.microsoft.com/portal#/signin">、FastTrack</a> ポータルにサインインしてエンゲージメントを開始します。</span><span class="sxs-lookup"><span data-stu-id="08af6-920">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="08af6-921">ブックマークのエッジ導入と構成のガイダンスを計画Microsoft Searchします。</span><span class="sxs-lookup"><span data-stu-id="08af6-921">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="08af6-922">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="08af6-922">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="08af6-923">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="08af6-923">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="08af6-924">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="08af6-924">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
