---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: 56fe941acf3f5739802ac9065c843dbbc2f2525b
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592450"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="dea43-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="dea43-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="dea43-105">FastTrack でサポートされるサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="dea43-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="dea43-106">このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。</span><span class="sxs-lookup"><span data-stu-id="dea43-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="dea43-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="dea43-108">FastTrack では、最初にコア機能 (すべてのサービスで共通) を使用し、次Microsoft Online Services対象となる各サービスをオンボーディングする場合に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="dea43-109">全般</span><span class="sxs-lookup"><span data-stu-id="dea43-109">General</span></span>](#general)
  - [<span data-ttu-id="dea43-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="dea43-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="dea43-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="dea43-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="dea43-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="dea43-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="dea43-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="dea43-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="dea43-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="dea43-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="dea43-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="dea43-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="dea43-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="dea43-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="dea43-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="dea43-118">全般</span><span class="sxs-lookup"><span data-stu-id="dea43-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-120"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dea43-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="dea43-123">サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="dea43-124">Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も含まれています。セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションも含[まれます](/office365/enterprise/office-365-network-connectivity-principles)。</span><span class="sxs-lookup"><span data-stu-id="dea43-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a [discussion on security, network connectivity, and compliance](/office365/enterprise/office-365-network-connectivity-principles).</span></span>  
  <span data-ttu-id="dea43-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="dea43-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="dea43-126"></li>
</ul>  

<strong> Identity Integration </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="dea43-127">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="dea43-128">Azure AD Connect (単一フォレストまたは複数フォレスト) のインストールと構成、およびライセンス (グループ ベースのライセンスを含む) を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="dea43-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="dea43-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="dea43-130">クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</span><span class="sxs-lookup"><span data-stu-id="dea43-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="dea43-131">パスワードレス認証 (Fast Identity Online (FIDO)2 または Microsoft Authenticator App) を使用して、ユーザーの認証エクスペリエンスを選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="dea43-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="dea43-132">Azure ADと同期された単一の Active Directory フォレストと ID を持つ顧客に対して FS AD Connectします。</span><span class="sxs-lookup"><span data-stu-id="dea43-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="dea43-133">これには、R2 Windows Server 2012フェデレーション サービス 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="dea43-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="dea43-134">パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</span><span class="sxs-lookup"><span data-stu-id="dea43-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="dea43-135">シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</span><span class="sxs-lookup"><span data-stu-id="dea43-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="dea43-136">Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="dea43-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="dea43-137">アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを [有効にする](/azure/active-directory/saas-apps/tutorial-list) (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="dea43-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the [App integration tutorial list](/azure/active-directory/saas-apps/tutorial-list) (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="dea43-138"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="dea43-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="dea43-139">FastTrack の利点の一部として、クラウド サービスに接続してパフォーマンスの最高レベルを確保するためのベスト プラクティスについてMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="dea43-140"><strong>Active Directory フォレスト</strong>これらは、次のフォレスト構成を使用して、Windows Server 2003 以降の機能フォレスト レベルに設定されています。</span><span class="sxs-lookup"><span data-stu-id="dea43-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-141">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="dea43-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="dea43-142">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="dea43-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-143">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="dea43-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-144">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="dea43-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="dea43-145">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="dea43-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="dea43-146">必要に応じて、テナントの構成とAzure Active Directoryタスク。</span><span class="sxs-lookup"><span data-stu-id="dea43-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="dea43-147">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="dea43-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="dea43-148">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="dea43-149">Exchange マルチハイブリッド構成で複数の Exchange 組織で複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="dea43-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="dea43-150">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="dea43-151">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="dea43-152">複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="dea43-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="dea43-153">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-154"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="dea43-155">次のリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-156">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="dea43-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="dea43-157">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="dea43-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="dea43-158">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="dea43-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="dea43-159">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="dea43-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="dea43-160">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="dea43-161">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="dea43-162">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="dea43-163">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="dea43-164">さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストを使用して互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="dea43-165">詳細については<strong>、「アプリの保証</strong>」<a href="#windows-10">のWindows 10</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="dea43-166">オンライン クライアント ソフトウェアは、[システム要件] および [システム要件] で定義されている最小レベル<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-167"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="dea43-168">お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを [示します](/office365/enterprise/office-365-network-connectivity-principles)。</span><span class="sxs-lookup"><span data-stu-id="dea43-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s [principles of network connectivity](/office365/enterprise/office-365-network-connectivity-principles).</span></span> <span data-ttu-id="dea43-169">これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="dea43-170">また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="dea43-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="dea43-171">Microsoft 365管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="dea43-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="dea43-172">最新のバージョンのアプリMicrosoft 365必要です。</span><span class="sxs-lookup"><span data-stu-id="dea43-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="dea43-173">ネットワーク パフォーマンスに関する推奨事項に従って、Microsoft 365管理センター [(プレビュー) で有効になっている場所サービス](/Office365/Enterprise/office-365-network-mac-perf-overview)。</span><span class="sxs-lookup"><span data-stu-id="dea43-173">Location services enabled as per [Network performance recommendations in the Microsoft 365 Admin Center (preview)](/Office365/Enterprise/office-365-network-mac-perf-overview).</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="dea43-174">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="dea43-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-175"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-176"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-177"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="dea43-178"><strong>Azure Active Directory (Azure AD) と Azure AD プレミアム</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="dea43-179">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="dea43-180">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="dea43-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="dea43-181">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="dea43-182">FIDO2 またはアプリをMicrosoft Authenticatorします。</span><span class="sxs-lookup"><span data-stu-id="dea43-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="dea43-183">Azure 以外のユーザー AD プレミアム、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="dea43-184">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="dea43-185">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="dea43-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="dea43-186">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="dea43-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="dea43-187">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="dea43-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="dea43-188">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="dea43-189">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="dea43-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="dea43-190">役割ベースのアクセス制御 (RBAC) Office 365組み込みの管理役割を使用して管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="dea43-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="dea43-191">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="dea43-192">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="dea43-193">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-194">Azure AD正常性を使用AD FS、Azure AD Connect、およびドメイン コントローラーのリモート監視をAD Connectします。</span><span class="sxs-lookup"><span data-stu-id="dea43-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="dea43-195">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-196">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="dea43-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="dea43-197">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="dea43-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-198">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="dea43-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-199">Azure アカウントを使用して特権管理者アカウントへのアクセスを管理AD Privileged Identity Management。</span><span class="sxs-lookup"><span data-stu-id="dea43-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="dea43-200">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-201">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="dea43-202">ユーザーが独自のクラウド セキュリティまたはセルフサービス グループ管理を使用Office 365グループを作成および管理ADグループを作成および管理できます。</span><span class="sxs-lookup"><span data-stu-id="dea43-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="dea43-203">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="dea43-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="dea43-204">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="dea43-205">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="dea43-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="dea43-206">オンプレミスの Active Directory とその環境は、Azure AD プレミアム 用に準備されています。Azure AD および Azure AD プレミアム 機能との統合を妨げる特定の問題の修復も含まれます。</span><span class="sxs-lookup"><span data-stu-id="dea43-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-207"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="dea43-208">Azure Information Protection の詳細については、この表の <strong>「Microsoft Information Protection」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="dea43-209"><strong>応答&を検出する</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="dea43-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="dea43-211">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="dea43-212">新しいケースの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="dea43-213">保管担当者を保留に設定する。</span><span class="sxs-lookup"><span data-stu-id="dea43-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="dea43-214">検索の実行。</span><span class="sxs-lookup"><span data-stu-id="dea43-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="dea43-215">検索結果をレビュー セットに追加する。</span><span class="sxs-lookup"><span data-stu-id="dea43-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="dea43-216">レビュー セットで分析を実行する。</span><span class="sxs-lookup"><span data-stu-id="dea43-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="dea43-217">ドキュメントの確認とタグ付け。</span><span class="sxs-lookup"><span data-stu-id="dea43-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="dea43-218">レビュー セットからデータをエクスポートする。</span><span class="sxs-lookup"><span data-stu-id="dea43-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="dea43-219">非データのインポートOffice 365します。</span><span class="sxs-lookup"><span data-stu-id="dea43-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="dea43-220"><strong>高度な監査</strong> (E5 でのみサポート)</span><span class="sxs-lookup"><span data-stu-id="dea43-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="dea43-221">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="dea43-222">高度な監査を有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="dea43-223">検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</span><span class="sxs-lookup"><span data-stu-id="dea43-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="dea43-224">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="dea43-225">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="dea43-226">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="dea43-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="dea43-227">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="dea43-228">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="dea43-229">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="dea43-230">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="dea43-231">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="dea43-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="dea43-232">カスタム スクリプトまたはコーディング。</span><span class="sxs-lookup"><span data-stu-id="dea43-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="dea43-233">電子情報開示 API。</span><span class="sxs-lookup"><span data-stu-id="dea43-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="dea43-234">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="dea43-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="dea43-235">コンプライアンスの境界とセキュリティ フィルター。</span><span class="sxs-lookup"><span data-stu-id="dea43-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="dea43-236">データ調査。</span><span class="sxs-lookup"><span data-stu-id="dea43-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="dea43-237">データ主体の要求。</span><span class="sxs-lookup"><span data-stu-id="dea43-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="dea43-238">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="dea43-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="dea43-239">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="dea43-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="dea43-240">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="dea43-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="dea43-241">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="dea43-242"><strong>Insider リスク管理</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="dea43-243">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="dea43-244">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="dea43-245">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="dea43-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="dea43-246">ケースの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="dea43-247">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="dea43-248">人事 (HR) コネクタの作成に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="dea43-249">

<strong> コミュニケーションコンプライアンス </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="dea43-250">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="dea43-251">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="dea43-252">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="dea43-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="dea43-253">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="dea43-254">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="dea43-255">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="dea43-256">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="dea43-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="dea43-257">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="dea43-258">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="dea43-259">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="dea43-260">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="dea43-261">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="dea43-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="dea43-262">フローの作成Power Automate管理します。</span><span class="sxs-lookup"><span data-stu-id="dea43-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="dea43-263">データ コネクタ (HR コネクタを超えて)。</span><span class="sxs-lookup"><span data-stu-id="dea43-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="dea43-264">カスタム正規表現 (RegEx) 構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="dea43-265">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="dea43-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="dea43-266">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="dea43-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="dea43-267">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="dea43-268">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="dea43-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="dea43-269">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="dea43-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="dea43-270">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="dea43-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="dea43-272">Microsoft 365Defender は、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="dea43-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="dea43-273">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="dea43-274">セキュリティ センターの概要Microsoft 365提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="dea43-275">製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。</span><span class="sxs-lookup"><span data-stu-id="dea43-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="dea43-276">Defender がMicrosoft 365自己修復によって侵害された可能性がある資産、ユーザー、デバイス、メールボックスの調査を調整する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="dea43-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="dea43-277">複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="dea43-278">Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</span><span class="sxs-lookup"><span data-stu-id="dea43-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="dea43-279"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="dea43-280">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="dea43-281">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="dea43-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="dea43-282">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="dea43-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="dea43-283">さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="dea43-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="dea43-284">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="dea43-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="dea43-285">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="dea43-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="dea43-286">セキュリティ情報とイベント管理 (SIEM) または API 統合。</span><span class="sxs-lookup"><span data-stu-id="dea43-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="dea43-288">Microsoft Cloud App Securityは、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。</span><span class="sxs-lookup"><span data-stu-id="dea43-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="dea43-289">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-290">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="dea43-291">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="dea43-292">管理者のアクセスと設定を管理する。</span><span class="sxs-lookup"><span data-stu-id="dea43-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="dea43-293">監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</span><span class="sxs-lookup"><span data-stu-id="dea43-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="dea43-294">IP 範囲とタグの設定。</span><span class="sxs-lookup"><span data-stu-id="dea43-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="dea43-295">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="dea43-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="dea43-296">クラウド検出を設定して、次の方法でシャドウ IT を提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="dea43-297">Microsoft Defender for Endpoints.</span><span class="sxs-lookup"><span data-stu-id="dea43-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="dea43-298">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="dea43-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="dea43-299">iboss。</span><span class="sxs-lookup"><span data-stu-id="dea43-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="dea43-300">アプリ コネクタ [を使用して注目](/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps) のアプリを接続する。</span><span class="sxs-lookup"><span data-stu-id="dea43-300">Connecting [featured apps](/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps) using app connectors.</span></span></li>
<li> <span data-ttu-id="dea43-301">条件付きアクセスとリアルタイム セッション コントロールを適用するCloud App Securityポータルで条件付きアクセス アプリ制御を設定します。</span><span class="sxs-lookup"><span data-stu-id="dea43-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="dea43-302">クラウド 検出ダッシュボードCloud App Security展開する。</span><span class="sxs-lookup"><span data-stu-id="dea43-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="dea43-303">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="dea43-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="dea43-304">アプリのタグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="dea43-305">アプリの制裁と認可解除。</span><span class="sxs-lookup"><span data-stu-id="dea43-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="dea43-306">アクティビティログとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="dea43-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="dea43-307">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="dea43-308">Defender ポータルでのインシデントのMicrosoft 365について。</span><span class="sxs-lookup"><span data-stu-id="dea43-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="dea43-309">CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。</span><span class="sxs-lookup"><span data-stu-id="dea43-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="dea43-310">サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="dea43-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="dea43-311">IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</span><span class="sxs-lookup"><span data-stu-id="dea43-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="dea43-312"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="dea43-313">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="dea43-314">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="dea43-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="dea43-315">Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="dea43-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="dea43-316">詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、「CASB の上位 20 の</a> 使用例」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="dea43-317">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="dea43-318">ブロック スクリプトを使用してアプリの使用状況をブロックする。</span><span class="sxs-lookup"><span data-stu-id="dea43-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="dea43-319">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="dea43-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="dea43-320">サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="dea43-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="dea43-321">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="dea43-322">Microsoft およびプレイブックを含むPower Automate修復。</span><span class="sxs-lookup"><span data-stu-id="dea43-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="dea43-323">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="dea43-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="dea43-324">概念実証としてクラウド アプリの検出を展開する。</span><span class="sxs-lookup"><span data-stu-id="dea43-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="dea43-325"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="dea43-326">Microsoft Defender for Endpoint は、エンタープライズ ネットワークによる高度な脅威の防止、検出、調査、および応答を支援するために設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="dea43-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="dea43-327">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-328">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="dea43-329">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="dea43-330">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="dea43-331">AV サービスまたは他のエンドポイント Windowsソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="dea43-332">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="dea43-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="dea43-333">オンボード エンドポイントを使用して Defender for Endpoint エージェント プロファイルを展開する方法を説明して、Microsoft Defender for Endpoint サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="dea43-334">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="dea43-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-335">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-336">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="dea43-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-337">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="dea43-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-338">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="dea43-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-339">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="dea43-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-340">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="dea43-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-341">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="dea43-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="dea43-342">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="dea43-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="dea43-343">Microsoft Defender for Office 365 Microsoft Defender for Endpoint との統合。</span><span class="sxs-lookup"><span data-stu-id="dea43-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="dea43-344">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="dea43-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="dea43-345">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="dea43-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-346">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="dea43-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-347">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="dea43-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-348">Windowsサーバー 2019。</span><span class="sxs-lookup"><span data-stu-id="dea43-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-349">WindowsServer 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="dea43-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-350">Windowsサーバー Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="dea43-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-351">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="dea43-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="dea43-352">
<strong>注:</strong>Windows Server のすべてのバージョンは、最新バージョンの System Center Configuration Manager 2012 (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) で管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="dea43-353"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="dea43-354">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="dea43-355">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="dea43-356">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="dea43-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="dea43-357">次の Microsoft Defender for Endpoint エージェントのオンボーディングまたは構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-358">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="dea43-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-359">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="dea43-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-360">Linux。</span><span class="sxs-lookup"><span data-stu-id="dea43-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-361">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="dea43-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="dea43-362">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="dea43-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-363">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="dea43-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-364">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-365">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-366">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="dea43-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-367">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="dea43-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-368">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="dea43-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-369">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-370">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="dea43-371">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-372">手動展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-373">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="dea43-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-374">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="dea43-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-375">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="dea43-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="dea43-376">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="dea43-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="dea43-377">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="dea43-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-378">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="dea43-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="dea43-379">次のようなアカウント保護機能の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="dea43-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="dea43-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="dea43-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="dea43-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="dea43-382">サーバーの構成またはBitLocker。</span><span class="sxs-lookup"><span data-stu-id="dea43-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="dea43-383">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="dea43-384">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="dea43-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="dea43-385">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="dea43-386">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="dea43-387">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="dea43-388">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="dea43-389"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="dea43-390">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="dea43-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="dea43-391">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="dea43-392">Defender for Identity のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="dea43-393">Defender for Identity を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="dea43-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="dea43-394">ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="dea43-395">リソース容量計画のサイジング ツールを実行する。</span><span class="sxs-lookup"><span data-stu-id="dea43-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="dea43-396">監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="dea43-397">センサーを展開して、ネットワーク トラフィックをキャプチャして解析し、Windowsイベントをドメイン コントローラーから直接取得します。次の内容を含む。</span><span class="sxs-lookup"><span data-stu-id="dea43-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="dea43-398">センサー パッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="dea43-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="dea43-399">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="dea43-400">センサーをドメイン コントローラーにサイレント モードでインストールします。</span><span class="sxs-lookup"><span data-stu-id="dea43-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="dea43-401">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="dea43-402">Defender for Identity と Microsoft Cloud App Security統合 (Cloud App Securityライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="dea43-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="dea43-403">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="dea43-404">"ノイズ" を低減するために環境を調整します。</span><span class="sxs-lookup"><span data-stu-id="dea43-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="dea43-405">ID セキュリティポスチャ評価レポートについて。</span><span class="sxs-lookup"><span data-stu-id="dea43-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="dea43-406">ユーザーの調査の優先度スコアとユーザー調査のランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="dea43-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="dea43-407">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="dea43-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="dea43-408">侵害されたアカウントに修復オプションを提供する。</span><span class="sxs-lookup"><span data-stu-id="dea43-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="dea43-409">Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。</span><span class="sxs-lookup"><span data-stu-id="dea43-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="dea43-410"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="dea43-411">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="dea43-412">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="dea43-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="dea43-413">以下を含む、Defender for Identity センサーの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="dea43-414">手動の容量計画。</span><span class="sxs-lookup"><span data-stu-id="dea43-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="dea43-415">スタンドアロン容量でのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="dea43-416">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="dea43-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="dea43-417">サード パーティ製のツールを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="dea43-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="dea43-418">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="dea43-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="dea43-419">honeytokens の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="dea43-420">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="dea43-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="dea43-421">さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="dea43-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="dea43-422">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="dea43-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="dea43-423">脅威または高度な狩猟。</span><span class="sxs-lookup"><span data-stu-id="dea43-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="dea43-424">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="dea43-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="dea43-425">Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。</span><span class="sxs-lookup"><span data-stu-id="dea43-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="dea43-426">Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="dea43-427">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="dea43-428">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="dea43-429">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="dea43-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="dea43-430">Defender for Identity センサーを概念実証として展開する。</span><span class="sxs-lookup"><span data-stu-id="dea43-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="dea43-431">Active Directory が展開されました。</span><span class="sxs-lookup"><span data-stu-id="dea43-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="dea43-432">Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="dea43-433">Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="dea43-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="dea43-434">次のいずれかの方法で実行されているドメイン コントローラー。</span><span class="sxs-lookup"><span data-stu-id="dea43-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="dea43-435">Windowsサーバー 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="dea43-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="dea43-436">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="dea43-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="dea43-437">Windows Server 2012R2。</span><span class="sxs-lookup"><span data-stu-id="dea43-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="dea43-438">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="dea43-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="dea43-439">WindowsKB4487044 のサーバー 2019 (OS ビルド 17763.316)。</span><span class="sxs-lookup"><span data-stu-id="dea43-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="dea43-440"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="dea43-441">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-442">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="dea43-443">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="dea43-444">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="dea43-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="dea43-445">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="dea43-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="dea43-446">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="dea43-447"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="dea43-448">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-449">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="dea43-450">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="dea43-451">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="dea43-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="dea43-452">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="dea43-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="dea43-453">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="dea43-454">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="dea43-455">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="dea43-456">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="dea43-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="dea43-457">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="dea43-458">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="dea43-459">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="dea43-460">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="dea43-461">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="dea43-462">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="dea43-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="dea43-463">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="dea43-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="dea43-464">情報アーキテクチャのSharePoint。</span><span class="sxs-lookup"><span data-stu-id="dea43-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="dea43-465">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="dea43-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="dea43-466">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="dea43-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="dea43-467">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="dea43-468">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="dea43-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="dea43-469">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="dea43-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="dea43-470">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-471"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="dea43-472">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-473">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-474">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-475">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-476">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-477">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-478">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-479">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-480">E5 でサポートされているデバイスのエンドポイント データ損失防止 (DLP) Windows 10ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="dea43-481">チャットとチャネルに対Microsoft Teams DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="dea43-482">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="dea43-483">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="dea43-484">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="dea43-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="dea43-485">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="dea43-486">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="dea43-487">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="dea43-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="dea43-488">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="dea43-489">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="dea43-490">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="dea43-491">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="dea43-492">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="dea43-493">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="dea43-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="dea43-494">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="dea43-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="dea43-495">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="dea43-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="dea43-496">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="dea43-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="dea43-497">また、Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="dea43-498"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="dea43-499">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="dea43-499">Customer key.</span></span></li>
<li><span data-ttu-id="dea43-500">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="dea43-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="dea43-501">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="dea43-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="dea43-502">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="dea43-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="dea43-503">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="dea43-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="dea43-504">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="dea43-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="dea43-505">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="dea43-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="dea43-506">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="dea43-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="dea43-507">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="dea43-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="dea43-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="dea43-509">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="dea43-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="dea43-510">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="dea43-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="dea43-511">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="dea43-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="dea43-512">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="dea43-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="dea43-513">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="dea43-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="dea43-514">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="dea43-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="dea43-515">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="dea43-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="dea43-516">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 [を参照してください](/azure/information-protection/deploy-aip-scanner-prereqs)。</span><span class="sxs-lookup"><span data-stu-id="dea43-516">For more information, see [Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner](/azure/information-protection/deploy-aip-scanner-prereqs).</span></span> </li>
<li>  <span data-ttu-id="dea43-517">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="dea43-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="dea43-518">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="dea43-519">[管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする](/azure/information-protection/rms-client/clientv2-admin-guide-install)   </span><span class="sxs-lookup"><span data-stu-id="dea43-519">[Admin Guide: Install the Azure Information Protection unified labeling client for users](/azure/information-protection/rms-client/clientv2-admin-guide-install)   </span></span></li>
<li>  <span data-ttu-id="dea43-520">[iOS または Android 用の Azure Information Protection アプリとは](/azure/information-protection/rms-client/mobile-app-faq)  </span><span class="sxs-lookup"><span data-stu-id="dea43-520">[What is the Azure Information Protection app for iOS or Android?](/azure/information-protection/rms-client/mobile-app-faq)  </span></span></li>
</ul>
<li> <span data-ttu-id="dea43-521">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="dea43-522">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="dea43-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="dea43-524">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="dea43-525">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="dea43-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="dea43-526">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="dea43-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-527">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="dea43-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="dea43-528">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="dea43-529">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="dea43-530">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-531">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="dea43-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-532">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="dea43-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-533">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-534">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="dea43-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-535">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="dea43-536">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="dea43-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-537">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="dea43-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="dea43-538">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="dea43-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="dea43-539">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="dea43-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-540">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="dea43-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="dea43-541">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="dea43-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="dea43-542">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="dea43-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="dea43-543">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="dea43-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="dea43-544">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="dea43-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-545">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="dea43-546">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="dea43-547">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="dea43-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-548">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="dea43-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-549">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="dea43-550">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="dea43-551">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="dea43-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="dea43-552">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="dea43-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="dea43-553">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="dea43-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="dea43-554">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="dea43-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="dea43-555">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="dea43-556">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="dea43-557">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="dea43-558">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="dea43-559">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="dea43-560">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="dea43-561">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="dea43-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="dea43-562"><strong>iOS Outlook Android 用モバイルを安全に展開する</strong>ユーザーが必要なすべてのアプリをインストールOutlook iOS と Android 用モバイルを安全に組織に展開するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="dea43-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="dea43-563">Intune を使用して iOS および Android Outlookを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="dea43-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="dea43-564">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="dea43-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-565">Apple App Store Outlook Google Play ストアを通じて、iOS と Android、Microsoft Authenticator、Intune ポータル サイトアプリ用のアプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="dea43-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="dea43-566">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-567">iOS Outlook Android、Intune でのアプリMicrosoft Authenticator、Intune ポータル サイトの展開に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="dea43-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="dea43-568">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="dea43-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-569">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="dea43-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="dea43-570">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="dea43-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="dea43-571">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="dea43-572"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="dea43-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="dea43-573"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="dea43-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="dea43-574">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="dea43-575"><strong>エンドポイント用 Microsoft Defender と統合された Intune</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="dea43-576"><strong>注</strong>: Intune と Microsoft Defender for Endpoint を統合し、そのリスク レベル評価に基づいてデバイス コンプライアンス ポリシー Windows 10提供しています。</span><span class="sxs-lookup"><span data-stu-id="dea43-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="dea43-577">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="dea43-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="dea43-578">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="dea43-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="dea43-580">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="dea43-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="dea43-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-582"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-583"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-584"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dea43-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="dea43-586">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="dea43-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="dea43-587">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="dea43-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="dea43-588">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-589">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="dea43-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-590">メール交換 (MX) レコードをユーザーにOffice 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-591">サブスクリプション サービスの一部Office 365場合は、Microsoft Defender for Office 365機能をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="dea43-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="dea43-592">詳細については、この表の一<strong>部Office 365</strong> Microsoft Defender を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="dea43-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="dea43-p128">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="dea43-597">
  <strong>注:</strong>メールボックス レプリケーション サービス (MRS) は、Information Rights Managed (IRM) メールをオンプレミスメールボックスから対応するメールボックスに移行Exchange Onlineします。</span><span class="sxs-lookup"><span data-stu-id="dea43-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="dea43-598">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="dea43-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="dea43-599">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="dea43-600">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="dea43-601">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="dea43-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="dea43-602">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="dea43-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-603">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="dea43-604">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="dea43-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="dea43-605">FastTrack 特典を使用してデータを移行する方法については、「Office 365」[を参照してください](data-migration.md)。</span><span class="sxs-lookup"><span data-stu-id="dea43-605">For information on using the FastTrack benefit for data migration to Office 365, see [Data Migration](data-migration.md).</span></span>   
<td>  <span data-ttu-id="dea43-606">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="dea43-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-607">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="dea43-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="dea43-608">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="dea43-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="dea43-609">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="dea43-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="dea43-610">複数地域の機能の詳細については、「複数地域の機能」を参照<a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="dea43-611">Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは、Microsoft 365 Office の System requirements で定義されている最小レベルである<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="dea43-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="dea43-612"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="dea43-613">詳細については<strong>、「Microsoft Defender for Office 365」</strong>[を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="dea43-614"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="dea43-615">詳細については <strong> 、「Microsoft Information Governance in Security</strong> and [Compliance」を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-615">For more information, see <strong> Microsoft Information Governance</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-616"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="dea43-617">詳細については <strong>、「Microsoft Information Protection in Security </strong> and [Compliance」を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-617">For more information, see <strong>Microsoft Information Protection </strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="dea43-619">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-620">オンライン、Exchange Online、SharePoint グループ、および Azure Office 365の最小要件を確認して、ADをサポートTeams。</span><span class="sxs-lookup"><span data-stu-id="dea43-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="dea43-621">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="dea43-622">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="dea43-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="dea43-623">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="dea43-624">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="dea43-625">ネットワーク評価のTeams:</span><span class="sxs-lookup"><span data-stu-id="dea43-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-626">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="dea43-627">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="dea43-628">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="dea43-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="dea43-629">アプリ ポリシー Teams構成する (Teams Web アプリ、Teamsデスクトップ アプリ、iOS Teams Android アプリの場合)。</span><span class="sxs-lookup"><span data-stu-id="dea43-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="dea43-630">該当する場合は、次のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-631">Microsoft Teamsルーム デバイス:</span><span class="sxs-lookup"><span data-stu-id="dea43-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="dea43-632"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="dea43-633">認定デバイスのサービス側構成をリモートMicrosoft Teams ミーティングします。</span><span class="sxs-lookup"><span data-stu-id="dea43-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="dea43-634">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="dea43-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="dea43-635">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="dea43-636">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="dea43-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="dea43-637">電話システム:</span><span class="sxs-lookup"><span data-stu-id="dea43-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-638">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="dea43-639">通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="dea43-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="dea43-640">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="dea43-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="dea43-641">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="dea43-642">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="dea43-643">直接ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="dea43-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-644">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="dea43-645">セッション ボーダー コントローラー (SBC) の構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="dea43-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="dea43-646">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="dea43-647">音声ルートの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="dea43-648">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="dea43-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="dea43-649">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="dea43-650">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="dea43-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="dea43-651">移行をSkype for BusinessするTeamsガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="dea43-652">Azure ADでOffice 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-653">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="dea43-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="dea43-654">Exchangeメールボックスが存在する (オンラインとオンプレミスのハイブリッド構成Exchange)。</span><span class="sxs-lookup"><span data-stu-id="dea43-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="dea43-655">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="dea43-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="dea43-656">
  <strong>注:</strong>ユーザーがオンライン ライセンスで割り当ておよび有効SharePoint場合、ユーザーはオンライン ライセンスにOneDrive for BusinessストレージOffice 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="dea43-657">ファイル共有はチャネルで引き続き機能しますが、ユーザーはチャット内のファイルを共有OneDrive for Business共有Office 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="dea43-658">TeamsオンプレミスでのSharePointサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="dea43-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="dea43-659">
  <strong>注:</strong>理想的な状態は、すべてのユーザーが自分のメールボックスをユーザーにExchange Online。</span><span class="sxs-lookup"><span data-stu-id="dea43-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="dea43-660">オンプレミスに存在するメールボックスを持つユーザーは、自分の ID を Azure サーバー経由で Office 365 ディレクトリに同期AD Connect。</span><span class="sxs-lookup"><span data-stu-id="dea43-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="dea43-661">これらのユーザー Exchange、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="dea43-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="dea43-662">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="dea43-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="dea43-663"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="dea43-664">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-665">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="dea43-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="dea43-666">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="dea43-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="dea43-667">モバイルOutlookセキュリティ保護 (詳細については、「Outlook [iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android)および Android のセキュリティ保護Exchange Onlineを参照してください)。</span><span class="sxs-lookup"><span data-stu-id="dea43-667">Securing Outlook mobile (see [Securing Outlook for iOS and Android in Exchange Online](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android) for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="dea43-668">Azure ADでOffice 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-669">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="dea43-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="dea43-671">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-672">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="dea43-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="dea43-673">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="dea43-674">オンライン クライアント ソフトウェア (Power BI Desktop) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="dea43-676">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-677">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="dea43-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="dea43-678">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="dea43-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="dea43-679">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="dea43-680">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="dea43-681">オンライン クライアント ソフトウェア (Project for Office 365) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dea43-682"><strong>Project Online Professionalとプレミアム</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="dea43-683">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-684">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="dea43-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="dea43-685">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="dea43-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="dea43-686">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="dea43-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="dea43-687">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="dea43-688">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="dea43-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="dea43-689">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="dea43-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="dea43-690">オンライン クライアント ソフトウェア (Project for Office 365) は、「システム要件」および「システム要件」で定義されている最小レベルMicrosoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-691"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="dea43-692">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-693">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="dea43-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="dea43-694">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="dea43-695">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="dea43-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="dea43-696">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="dea43-697">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="dea43-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="dea43-698">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="dea43-699">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="dea43-700">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="dea43-701">移行方法。</span><span class="sxs-lookup"><span data-stu-id="dea43-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="dea43-702">追加のガイダンスは、OneDrive for Businessバージョンに応じてSharePoint提供されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-703">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="dea43-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="dea43-704">オンライン 2013 SP1 のSharePoint (該当する場合) のインストール、同期と ID の要件の計画と実装、および同期クライアントOneDrive for Business識別します。</span><span class="sxs-lookup"><span data-stu-id="dea43-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="dea43-705">すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。</span><span class="sxs-lookup"><span data-stu-id="dea43-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="dea43-706">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に適用)、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="dea43-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="dea43-707">既知のフォルダーを別のフォルダーにリダイレクトOneDrive。</span><span class="sxs-lookup"><span data-stu-id="dea43-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="dea43-708">クライアント同期OneDrive for Business展開します。</span><span class="sxs-lookup"><span data-stu-id="dea43-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="dea43-709">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="dea43-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="dea43-710">FastTrack 特典を使用してデータを移行する方法については、「Office 365」[を参照してください](data-migration.md)。</span><span class="sxs-lookup"><span data-stu-id="dea43-710">For information on using the FastTrack benefit for data migration to Office 365, see [Data Migration](data-migration.md).</span></span>
</ul></td>
<td><br><span data-ttu-id="dea43-711"><strong>ハイブリッドSharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="dea43-712">SharePointハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびセルフ サービス サイトの作成を構成し、オンプレミスから単一のターゲット SharePoint Online 環境に接続します。</span><span class="sxs-lookup"><span data-stu-id="dea43-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="dea43-713">
  <strong>注:</strong>セルフサービス サイトの作成は、2013 年に実行されているオンプレミス サーバー SharePointではありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="dea43-714">ハイブリッドSharePoint有効にするには、2013、2016、または 2019 のいずれかのオンプレミス SharePoint サーバー環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="dea43-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="dea43-715">
  <strong>注:</strong>サーバーがスコープ内SharePointにSharePointオンプレミスの環境のアップグレード。</span><span class="sxs-lookup"><span data-stu-id="dea43-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="dea43-716">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="dea43-717">詳細については、「ハイブリッド機能の<a href="https://go.microsoft.com/fwlink/?linkid=853548">最小公開更新レベルSharePoint参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="dea43-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="dea43-718">
  <strong>注:</strong>複数地域機能の詳細については、「OneDrive および SharePoint の複数地域<a href="https://go.microsoft.com/fwlink/?linkid=831056">機能」を参照</a><em>Office 365。</em>  </span><span class="sxs-lookup"><span data-stu-id="dea43-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="dea43-720">このサービスを有効にするためのリモート ガイダンスをYammer Enterpriseします。</span><span class="sxs-lookup"><span data-stu-id="dea43-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="dea43-721">オンライン クライアント ソフトウェアは、[システム要件] および [システム要件] で定義されている最小レベル<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="dea43-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="dea43-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="dea43-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-723"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-724"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-725"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="dea43-726"><strong>Azure Active Directory (Azure AD) と Azure AD プレミアム</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="dea43-727">詳細については、「セキュリティとコンプライアンス<strong>Azure Active Directory (Azure AD)</strong>と Azure AD プレミアム」[を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="dea43-728">#セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="dea43-728">#security-and-compliance</span></span>
<td><span data-ttu-id="dea43-729"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="dea43-729"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="dea43-730">Azure Information Protection の詳細については <strong>、「Microsoft Information</strong> Protection in Security and [Compliance」を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-730">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="dea43-731"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-731"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="dea43-732">詳細については、「セキュリティとコンプライアンス[Microsoft Intune」を参照してください](products-and-capabilities.md#security-and-compliance)。 <strong></strong></span><span class="sxs-lookup"><span data-stu-id="dea43-732">For more information, see <strong> Microsoft Intune</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="dea43-733">Windows 10</span><span class="sxs-lookup"><span data-stu-id="dea43-733">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-734"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-734"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-735"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-735"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-736"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-736"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dea43-737"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-737"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="dea43-738">7 から 7 へのアップグレードWindows、ProfessionalからWindows 8.1 ProfessionalへのWindows 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="dea43-738">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="dea43-739">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-739">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-740">ユーザーの意図Windows 10理解します。</span><span class="sxs-lookup"><span data-stu-id="dea43-740">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="dea43-741">ソース環境と要件を評価します (Microsoft Endpoint Configuration Manager展開をサポートするために必要なレベルWindows 10してください)。</span><span class="sxs-lookup"><span data-stu-id="dea43-741">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="dea43-742">アプリケーションまたはWindows 10 EnterpriseをMicrosoft 365 AppsしてMicrosoft Endpoint Configuration Manager展開Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-742">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="dea43-743">アプリを評価するためのオプションWindows 10します。</span><span class="sxs-lookup"><span data-stu-id="dea43-743">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="dea43-744">デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="dea43-744">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="dea43-745">Microsoft 365 Apps構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と、Microsoft 365 Apps の展開を支援することで、互換性評価をMicrosoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="dea43-745">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="dea43-746">展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="dea43-746">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="dea43-747">既存のデバイスが必要なデバイス ハードウェア要件を満Windows 10 Enterpriseアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-747">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="dea43-748">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-748">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="dea43-749">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="dea43-749">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="dea43-750">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="dea43-750">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="dea43-751">Configuration Manager Microsoft 365 Apps展開の一部として構成マネージャーを使用Windows 10展開します。</span><span class="sxs-lookup"><span data-stu-id="dea43-751">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="dea43-752">組織が既存の Configuration Manager 環境またはサーバーを使用Windows 10 EnterpriseおよびMicrosoft 365 Appsを最新の情報にMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-752">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="dea43-753">
  
<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-753">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="dea43-754">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="dea43-754">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="dea43-755">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-755">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="dea43-756">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-756">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="dea43-757">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="dea43-757">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="dea43-758">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="dea43-758">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="dea43-759">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="dea43-759">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="dea43-760">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-760">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="dea43-761">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="dea43-761">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="dea43-762">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-762">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="dea43-763">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-763">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-764">ソース OS: Windows 7 Enterprise、Professional、Windows 8.1 Enterprise、Professional。</span><span class="sxs-lookup"><span data-stu-id="dea43-764">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="dea43-765">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="dea43-765">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="dea43-766">ターゲット OS: ウィンドウ 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="dea43-766">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="dea43-767">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-767">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-768">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="dea43-768">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="dea43-769">Configuration Manager のバージョンは、ターゲット バージョンでサポートWindows 10必要があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-769">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="dea43-770">詳細については、「[Configuration Manager での Windows 10 のサポート](/sccm/core/plan-design/configs/support-for-windows-10)」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-770">For more information, see the Configuration Manager support table at [Support for Windows 10 in Configuration Manager](/sccm/core/plan-design/configs/support-for-windows-10).</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="dea43-771"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-771"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="dea43-772">詳細については <strong> 、「Microsoft Defender for Endpoint in Security and</strong> [Compliance」を参照してください](products-and-capabilities.md#security-and-compliance)。</span><span class="sxs-lookup"><span data-stu-id="dea43-772">For more information, see <strong> Microsoft Defender for Endpoint</strong> in [Security and Compliance](products-and-capabilities.md#security-and-compliance).</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="dea43-773">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="dea43-773">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-774"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-774"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-775"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-775"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-776"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-776"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dea43-777"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-777"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="dea43-778">仮想デスクトップ (デスクトップおよびアプリの仮想化サービス) Windowsオンボーディングの展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-778">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="dea43-779">Windows仮想デスクトップは、Windows 10セッション エクスペリエンスを活用し、Microsoft 365 AppsとEnterpriseの統合されたセキュリティと管理をMicrosoft 365。</span><span class="sxs-lookup"><span data-stu-id="dea43-779">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="dea43-780">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-780">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="dea43-781">複数セッションWindows仮想デスクトップ環境Windows 10 Enterprise展開し、Microsoft 365 AppsをEnterprise使用します。</span><span class="sxs-lookup"><span data-stu-id="dea43-781">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="dea43-782">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="dea43-782">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="dea43-783">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="dea43-783">Shared image.</span></span></li>
<li><span data-ttu-id="dea43-784">Office展開Toolkit (ODT)。</span><span class="sxs-lookup"><span data-stu-id="dea43-784">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="dea43-785">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="dea43-785">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="dea43-786">プロファイル コンテナーを使用した FSLogix エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-786">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="dea43-787">FSLogix エージェントをコンテナーでOfficeします。</span><span class="sxs-lookup"><span data-stu-id="dea43-787">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="dea43-788">コンテンツの除外を使用して FSLogix フォルダーを構成する。</span><span class="sxs-lookup"><span data-stu-id="dea43-788">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="dea43-789">展開Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="dea43-789">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="dea43-790">展開Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="dea43-790">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="dea43-791">仮想デスクトップ クライアントWindows接続します。</span><span class="sxs-lookup"><span data-stu-id="dea43-791">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="dea43-792">

<strong>以下はスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="dea43-792">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="dea43-793">Project仮想デスクトップ展開のWindows管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-793">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="dea43-794">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="dea43-794">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="dea43-795">カスタム イメージ。</span><span class="sxs-lookup"><span data-stu-id="dea43-795">Custom images.</span></span></li>
<li><span data-ttu-id="dea43-796">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="dea43-796">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="dea43-797">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="dea43-797">Linux scenarios.</span></span></li>
<li><span data-ttu-id="dea43-798">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="dea43-798">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="dea43-799">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-799">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="dea43-800">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="dea43-800">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="dea43-801">[Windows仮想デスクトップ のライセンス要件](/azure/virtual-desktop/overview#requirements)。</span><span class="sxs-lookup"><span data-stu-id="dea43-801">[Windows Virtual Desktop licensing requirements](/azure/virtual-desktop/overview#requirements).</span></span></li>
<li><span data-ttu-id="dea43-802">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="dea43-802">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="dea43-803">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="dea43-803">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="dea43-804">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="dea43-804">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="dea43-805">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="dea43-805">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="dea43-806">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="dea43-806">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="dea43-807">仮想デスクトップへの接続を許可するWindowsルール。</span><span class="sxs-lookup"><span data-stu-id="dea43-807">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="dea43-808">詳細については、「サポートされる [リモート デスクトップ クライアント」を参照してください](/azure/virtual-desktop/overview#supported-remote-desktop-clients)。</span><span class="sxs-lookup"><span data-stu-id="dea43-808">For more information, see [Supported Remote Desktop clients](/azure/virtual-desktop/overview#supported-remote-desktop-clients).</span></span>
</ul>
<ul><li><span data-ttu-id="dea43-809">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="dea43-809">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="dea43-810">ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="dea43-810">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="dea43-811">Azure の Active Directory AD Connectを使用します。</span><span class="sxs-lookup"><span data-stu-id="dea43-811">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="dea43-812">Azure を使用した Active Directory AD Connect VPN または ExpressRoute を使用してオンプレミスで実行できます。</span><span class="sxs-lookup"><span data-stu-id="dea43-812">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="dea43-813">Active Directory ドメイン サービス (DS AD)。</span><span class="sxs-lookup"><span data-stu-id="dea43-813">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="dea43-814">App Assure</span><span class="sxs-lookup"><span data-stu-id="dea43-814">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-815"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-815"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-816"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-816"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-817"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-817"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="dea43-818"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-818"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="dea43-819">App Assure は、アプリの互換性と互換性に関する問題Windows 10解決Microsoft 365 Appsサービスです。</span><span class="sxs-lookup"><span data-stu-id="dea43-819">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="dea43-820">App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="dea43-820">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="dea43-821">また、仮想 Windowsデスクトップと Microsoft Edge を展開する際に互換性の問題に直面しているお客様にもガイダンスを提供し、互換性の問題を解決するためにあらゆる合理的な努力を行います。</span><span class="sxs-lookup"><span data-stu-id="dea43-821">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="dea43-822">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="dea43-822">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="dea43-823"><strong>Windows 10</strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="dea43-823"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="dea43-824"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="dea43-824"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="dea43-825"><strong>Microsoft Edge -</strong>展開のガイダンスについては、「[チャネルの概要」をMicrosoft Edgeしてください](/DeployEdge/microsoft-edge-channels)。</span><span class="sxs-lookup"><span data-stu-id="dea43-825"><strong>Microsoft Edge -</strong> For deployment guidance, see [Overview of the Microsoft Edge channels](/DeployEdge/microsoft-edge-channels).</span></span>  </li>
<li>  <span data-ttu-id="dea43-826"><strong>Windows仮想デスクトップ</strong> -詳細については、「仮想デスクトップとは[Windows」](/azure/virtual-desktop/overview)および「Windows 10 Enterprise [FAQ」を参照してください](/azure/virtual-desktop/windows-10-multisession-faq)。</span><span class="sxs-lookup"><span data-stu-id="dea43-826"><strong>Windows Virtual Desktop</strong> - For more information, see [What is Windows Virtual Desktop?](/azure/virtual-desktop/overview) and [Windows 10 Enterprise multi-session FAQ](/azure/virtual-desktop/windows-10-multisession-faq).</span></span>  </li>
</ul><span data-ttu-id="dea43-827">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-827">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="dea43-828">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="dea43-828">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="dea43-829">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-829">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="dea43-830">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-830">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="dea43-831">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="dea43-831">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="dea43-832">詳細については、「[Desktop Analytics とは](/sccm/desktop-analytics/overview)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="dea43-832">For more information, see [Desktop Analytics](/sccm/desktop-analytics/overview).</span></span></li>
<li><span data-ttu-id="dea43-833">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="dea43-833">App packaging-only services.</span></span> <span data-ttu-id="dea43-834">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="dea43-834">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="dea43-835">

<strong>顧客の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-835">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="dea43-836">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="dea43-836">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="dea43-837">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="dea43-837">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="dea43-838">
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="dea43-838">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="dea43-839">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="dea43-839">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="dea43-840">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="dea43-840">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="dea43-841"><strong>Windows 10とMicrosoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="dea43-841"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-842">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="dea43-842">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="dea43-843">
<strong>Windows 10のARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="dea43-843">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="dea43-844">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Appsでも動作します。</span><span class="sxs-lookup"><span data-stu-id="dea43-844">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="dea43-845">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="dea43-845">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="dea43-846">x64 (64 ビット) エミュレーションは、インサイダー プログラムに参加しているお客様<a href="https://insider.windows.com/">Windowsプレビューで使用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="dea43-846">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="dea43-847">Windows 10 バージョン 2004 以降Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用して<a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">サポートされます</a>。</span><span class="sxs-lookup"><span data-stu-id="dea43-847">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="dea43-848">Insider Program Windowsのお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="dea43-848">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="dea43-849">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="dea43-849">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-850">Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="dea43-850">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-851">Web は常に進化していますので、サイトの互換性に影響を与える既知の変更の公開リストを確認[Microsoft Edge。](/microsoft-edge/web-platform/site-impacting-changes)</span><span class="sxs-lookup"><span data-stu-id="dea43-851">As the web is constantly evolving, be sure to review this published list of known [site compatibility-impacting changes for Microsoft Edge](/microsoft-edge/web-platform/site-impacting-changes).</span></span>  
  </li>
</ul><span data-ttu-id="dea43-852">
  <strong>Windows仮想デスクトップ</strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-852">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="dea43-853">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-853">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-854">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 7 Enterprise および Windows 10 Enterprise で Windows 仮想デスクトップの一部として実行されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-854">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-855">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-855">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="dea43-856">
  <strong>注:</strong> Windows 10 Enterpriseの互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="dea43-856">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="dea43-857">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="dea43-857">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-858">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="dea43-858">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="dea43-859">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="dea43-859">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="dea43-860">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="dea43-860">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dea43-861"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-861"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="dea43-862"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-862"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="dea43-863"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="dea43-863"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="dea43-864"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="dea43-864"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="dea43-865">リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。</span><span class="sxs-lookup"><span data-stu-id="dea43-865">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="dea43-866">(Microsoft Edge Intune Windows 10) Microsoft エンドポイント マネージャーにMicrosoft Endpoint Configuration Manager展開します。</span><span class="sxs-lookup"><span data-stu-id="dea43-866">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="dea43-867">構成Microsoft Edge (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="dea43-867">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="dea43-868">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="dea43-868">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="dea43-869">既存のInternet Explorerリストを使用してEnterpriseモードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="dea43-869">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="dea43-870">(詳細については、「Engaging [FastTrack」を参照してください](process-and-expectations.md#engaging-fasttrack))。</span><span class="sxs-lookup"><span data-stu-id="dea43-870">(For more information, see [Engaging FastTrack](process-and-expectations.md#engaging-fasttrack)).</span></span> <span data-ttu-id="dea43-871">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="dea43-871">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="dea43-872">App Assure の互換性サポートを要求するには <a href="https://fasttrack.microsoft.com/portal#/signin">、FastTrack</a> ポータルにサインインしてエンゲージメントを開始します。</span><span class="sxs-lookup"><span data-stu-id="dea43-872">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="dea43-873">Microsoft Search ブックマークのエッジ導入と構成ガイダンスの計画ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="dea43-873">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="dea43-874">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="dea43-874">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="dea43-875">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="dea43-875">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="dea43-876">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="dea43-876">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
