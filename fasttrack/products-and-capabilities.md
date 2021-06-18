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
description: このトピックでは、作業を開始する前に、FastTrackによってサポートされるワークロード シナリオと、ソース環境の期待に関する詳細について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994870"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="25951-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="25951-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="25951-105">サービスとシナリオは、ユーザーがサポートFastTrack</span><span class="sxs-lookup"><span data-stu-id="25951-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="25951-106">このトピックでは、作業を開始する前に、FastTrackによってサポートされるワークロード シナリオと、ソース環境の期待に関する詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="25951-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="25951-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="25951-108">FastTrackは、最初にコア機能 (すべてのサービスで共通) を使用し、次にMicrosoft Online Services対象のサービスをオンボーディングする場合に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="25951-109">全般</span><span class="sxs-lookup"><span data-stu-id="25951-109">General</span></span>](#general)
  - [<span data-ttu-id="25951-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="25951-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="25951-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="25951-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="25951-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="25951-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="25951-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="25951-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="25951-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="25951-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="25951-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="25951-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="25951-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="25951-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="25951-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="25951-118">全般</span><span class="sxs-lookup"><span data-stu-id="25951-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-120"><strong>FastTrackガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="25951-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="25951-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="25951-123">サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="25951-124">Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も含まれています。セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションも含<a href="/office365/enterprise/office-365-network-connectivity-principles">まれます</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="25951-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="25951-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="25951-126"></li>
</ul>  

<strong> Identity Integration </strong></span><span class="sxs-lookup"><span data-stu-id="25951-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="25951-127">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="25951-128">Azure AD Connect (単一フォレストまたは複数フォレスト) のインストールと構成、およびライセンス (グループ ベースのライセンスを含む) を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="25951-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="25951-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="25951-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="25951-130">クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</span><span class="sxs-lookup"><span data-stu-id="25951-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="25951-131">パスワードレス認証 (Fast Identity Online (FIDO)2 または Microsoft Authenticator App) を使用して、ユーザーの認証エクスペリエンスを選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="25951-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="25951-132">Azure ADと同期された単一の Active Directory フォレストと ID を持つ顧客に対して FS AD Connectします。</span><span class="sxs-lookup"><span data-stu-id="25951-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="25951-133">これには、R2 Windows Server 2012フェデレーション サービス 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="25951-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="25951-134">パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</span><span class="sxs-lookup"><span data-stu-id="25951-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="25951-135">シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</span><span class="sxs-lookup"><span data-stu-id="25951-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="25951-136">Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="25951-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="25951-137">アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを <a href="/azure/active-directory/saas-apps/tutorial-list">有効にする </a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="25951-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="25951-138"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="25951-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="25951-139">この利点の一FastTrack、クラウド サービスに接続するためのベスト プラクティスを提供し、クラウド サービスの最高レベルのパフォーマンスを確保Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="25951-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="25951-140"><strong>Active Directory フォレスト</strong>これらは、次のフォレスト構成を使用して、Windows Server 2003 以降の機能フォレスト レベルに設定されています。</span><span class="sxs-lookup"><span data-stu-id="25951-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="25951-141">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="25951-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="25951-142">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="25951-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="25951-143">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="25951-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="25951-144">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="25951-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="25951-145">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="25951-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="25951-146">必要に応じて、テナントの構成とAzure Active Directoryタスク。</span><span class="sxs-lookup"><span data-stu-id="25951-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="25951-147">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="25951-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="25951-148">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="25951-149">Exchange マルチハイブリッド構成で複数の Exchange 組織で複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="25951-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="25951-150">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="25951-151">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="25951-152">複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="25951-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="25951-153">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-154"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="25951-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="25951-155">次のリモート展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-156">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="25951-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="25951-157">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="25951-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="25951-158">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="25951-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="25951-159">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="25951-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="25951-160">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="25951-161">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="25951-162">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="25951-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="25951-163">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="25951-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="25951-164">さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストを使用して互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="25951-165">詳細については<strong>、「アプリの保証</strong>」<a href="#windows-10">のWindows 10</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="25951-166">オンライン クライアント ソフトウェアは、[システム要件] および [システム要件] で定義されている最小レベル<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365必要Office。</a></span><span class="sxs-lookup"><span data-stu-id="25951-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-167"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="25951-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="25951-168">お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを <a href="/office365/enterprise/office-365-network-connectivity-principles">示します</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="25951-169">これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="25951-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="25951-170">また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="25951-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="25951-171">Microsoft 365 管理センター アクセス。</span><span class="sxs-lookup"><span data-stu-id="25951-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="25951-172">最新のバージョンのアプリMicrosoft 365必要です。</span><span class="sxs-lookup"><span data-stu-id="25951-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="25951-173">場所サービスは、ネットワーク パフォーマンスに関する推奨事項に従って、Microsoft 365 管理<a href="/Office365/Enterprise/office-365-network-mac-perf-overview">センター (プレビュー) で有効になっています</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="25951-174">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="25951-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-175"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-176"><strong>FastTrackガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-177"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="25951-178"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="25951-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="25951-179">クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。</span><span class="sxs-lookup"><span data-stu-id="25951-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="25951-180">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="25951-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="25951-181">Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="25951-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="25951-182">FIDO2 またはアプリをMicrosoft Authenticatorします。</span><span class="sxs-lookup"><span data-stu-id="25951-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="25951-183">ユーザー以外のユーザー Azure AD Premium、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="25951-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="25951-184">Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="25951-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="25951-185">Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。</span><span class="sxs-lookup"><span data-stu-id="25951-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="25951-186">Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。</span><span class="sxs-lookup"><span data-stu-id="25951-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="25951-187">Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。</span><span class="sxs-lookup"><span data-stu-id="25951-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="25951-188">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="25951-189">Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="25951-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="25951-190">役割ベースのアクセス制御 (RBAC) Office 365組み込みの管理役割を使用して管理者のアクセスを管理し、特権管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="25951-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="25951-191">ハイブリッド Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="25951-192">Azure AD構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="25951-193">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="25951-194">Azure AD正常性を使用AD FS、Azure AD Connect、およびドメイン コントローラーのリモート監視をAD Connectします。</span><span class="sxs-lookup"><span data-stu-id="25951-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="25951-195">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="25951-196">Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。</span><span class="sxs-lookup"><span data-stu-id="25951-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="25951-197">Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。</span><span class="sxs-lookup"><span data-stu-id="25951-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-198">Azure AD利用規約を確認します。</span><span class="sxs-lookup"><span data-stu-id="25951-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-199">Azure アカウントを使用して特権管理者アカウントへのアクセスを管理AD Privileged Identity Management。</span><span class="sxs-lookup"><span data-stu-id="25951-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="25951-200">
  
<strong>オートメーションと効率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="25951-201">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="25951-202">ユーザーが独自のクラウド セキュリティまたはセルフサービス グループ管理を使用Office 365グループを作成および管理ADグループを作成および管理できます。</span><span class="sxs-lookup"><span data-stu-id="25951-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="25951-203">Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="25951-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="25951-204">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="25951-205">コレクションを使用して My Apps ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="25951-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="25951-206">オンプレミスの Active Directory とその環境は、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復など、Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="25951-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-207"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="25951-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="25951-208">Azure Information Protection の詳細については、この表<strong>Microsoft Information Protection</strong>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="25951-209"><strong>応答&を検出する</strong></span><span class="sxs-lookup"><span data-stu-id="25951-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="25951-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="25951-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="25951-211">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="25951-212">新しいケースの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="25951-213">保管担当者を保留に設定する。</span><span class="sxs-lookup"><span data-stu-id="25951-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="25951-214">検索の実行。</span><span class="sxs-lookup"><span data-stu-id="25951-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="25951-215">検索結果をレビュー セットに追加する。</span><span class="sxs-lookup"><span data-stu-id="25951-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="25951-216">レビュー セットで分析を実行する。</span><span class="sxs-lookup"><span data-stu-id="25951-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="25951-217">ドキュメントの確認とタグ付け。</span><span class="sxs-lookup"><span data-stu-id="25951-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="25951-218">レビュー セットからデータをエクスポートする。</span><span class="sxs-lookup"><span data-stu-id="25951-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="25951-219">非データのインポートOffice 365します。</span><span class="sxs-lookup"><span data-stu-id="25951-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="25951-220"><strong>高度な監査</strong> (E5 でのみサポート)</span><span class="sxs-lookup"><span data-stu-id="25951-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="25951-221">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="25951-222">高度な監査を有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="25951-223">検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</span><span class="sxs-lookup"><span data-stu-id="25951-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="25951-224">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="25951-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="25951-225">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="25951-226">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="25951-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="25951-227">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="25951-228">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="25951-229">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="25951-230">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="25951-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="25951-231">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="25951-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="25951-232">カスタム スクリプトまたはコーディング。</span><span class="sxs-lookup"><span data-stu-id="25951-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="25951-233">電子情報開示 API。</span><span class="sxs-lookup"><span data-stu-id="25951-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="25951-234">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="25951-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="25951-235">コンプライアンスの境界とセキュリティ フィルター。</span><span class="sxs-lookup"><span data-stu-id="25951-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="25951-236">データ調査。</span><span class="sxs-lookup"><span data-stu-id="25951-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="25951-237">データ主体の要求。</span><span class="sxs-lookup"><span data-stu-id="25951-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="25951-238">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="25951-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="25951-239">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="25951-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="25951-240">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="25951-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="25951-241">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="25951-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="25951-242"><strong>Insider リスク管理</strong></span><span class="sxs-lookup"><span data-stu-id="25951-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="25951-243">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="25951-244">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="25951-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="25951-245">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="25951-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="25951-246">ケースの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="25951-247">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="25951-248">人事 (HR) コネクタの作成に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="25951-249">

<strong> コミュニケーションコンプライアンス </strong></span><span class="sxs-lookup"><span data-stu-id="25951-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="25951-250">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="25951-251">ポリシーの作成と設定の確認。</span><span class="sxs-lookup"><span data-stu-id="25951-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="25951-252">レポートとアラートへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="25951-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="25951-253">通知テンプレートの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="25951-254">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="25951-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="25951-255">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="25951-256">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="25951-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="25951-257">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="25951-258">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="25951-259">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="25951-260">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="25951-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="25951-261">

<strong>以下はスコープ外です </strong> 
</span><span class="sxs-lookup"><span data-stu-id="25951-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="25951-262">フローの作成Power Automate管理します。</span><span class="sxs-lookup"><span data-stu-id="25951-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="25951-263">データ コネクタ (HR コネクタを超えて)。</span><span class="sxs-lookup"><span data-stu-id="25951-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="25951-264">カスタム正規表現 (RegEx) 構成。</span><span class="sxs-lookup"><span data-stu-id="25951-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="25951-265">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="25951-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="25951-266">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="25951-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="25951-267">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="25951-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="25951-268">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="25951-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="25951-269">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="25951-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="25951-270">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="25951-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="25951-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="25951-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="25951-272">Microsoft 365 Defenderは、エンドポイント、ID、電子メール、アプリ全体の検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="25951-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="25951-273">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="25951-274">セキュリティ センターの概要Microsoft 365提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="25951-275">製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。</span><span class="sxs-lookup"><span data-stu-id="25951-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="25951-276">自動Microsoft 365 Defenderによって侵害された可能性があるアセット、ユーザー、デバイス、およびメールボックスの調査を、ユーザーがどのように調整できるのかについて説明します。</span><span class="sxs-lookup"><span data-stu-id="25951-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="25951-277">複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="25951-278">Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</span><span class="sxs-lookup"><span data-stu-id="25951-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="25951-279"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="25951-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="25951-280">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="25951-281">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="25951-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="25951-282">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="25951-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="25951-283">さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="25951-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="25951-284">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="25951-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="25951-285">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="25951-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="25951-286">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="25951-287">セキュリティ情報とイベント管理 (SIEM) または API 統合。</span><span class="sxs-lookup"><span data-stu-id="25951-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="25951-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="25951-289">Microsoft Cloud App Securityは、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。</span><span class="sxs-lookup"><span data-stu-id="25951-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="25951-290">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-291">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="25951-292">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="25951-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="25951-293">管理者のアクセスと設定を管理する。</span><span class="sxs-lookup"><span data-stu-id="25951-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="25951-294">監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</span><span class="sxs-lookup"><span data-stu-id="25951-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="25951-295">IP 範囲とタグを設定する方法。</span><span class="sxs-lookup"><span data-stu-id="25951-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="25951-296">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="25951-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="25951-297">次を含むファースト パーティ サービスの統合</span><span class="sxs-lookup"><span data-stu-id="25951-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="25951-298">Microsoft Defender for Endpoint。</span><span class="sxs-lookup"><span data-stu-id="25951-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="25951-299">Microsoft Defender for Identity。</span><span class="sxs-lookup"><span data-stu-id="25951-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="25951-300">Azure AD Identity Protection。</span><span class="sxs-lookup"><span data-stu-id="25951-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="25951-301">Azure 情報保護。</span><span class="sxs-lookup"><span data-stu-id="25951-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="25951-302">次の方法を使用してクラウド検出を設定します。</span><span class="sxs-lookup"><span data-stu-id="25951-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="25951-303">Microsoft Defender for Endpoints.</span><span class="sxs-lookup"><span data-stu-id="25951-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="25951-304">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="25951-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="25951-305">iboss。</span><span class="sxs-lookup"><span data-stu-id="25951-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="25951-306">アプリのタグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="25951-307">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="25951-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="25951-308">アプリの制裁と認可解除。</span><span class="sxs-lookup"><span data-stu-id="25951-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="25951-309">Cloud App Security ダッシュボードと Cloud Discovery ダッシュボードを確認します。</span><span class="sxs-lookup"><span data-stu-id="25951-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="25951-310">アプリ コネクタ <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> を使用して注目</a> のアプリを接続する。</span><span class="sxs-lookup"><span data-stu-id="25951-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="25951-311">Azure AD および Cloud App Security ポータル内の条件付きアクセスアプリ制御を使用してアプリを保護します。</span><span class="sxs-lookup"><span data-stu-id="25951-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="25951-312">おすすめアプリの条件付きアクセス アプリコントロールを展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="25951-313">アクティビティログとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="25951-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="25951-314">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="25951-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="25951-315">ポリシー テンプレートの確認と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="25951-316">CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。</span><span class="sxs-lookup"><span data-stu-id="25951-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="25951-317">サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="25951-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="25951-318">IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</span><span class="sxs-lookup"><span data-stu-id="25951-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="25951-319">Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</span><span class="sxs-lookup"><span data-stu-id="25951-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="25951-320"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="25951-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="25951-321">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="25951-322">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="25951-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="25951-323">Cloud App Security と他の CASB 製品を比較するディスカッション。</span><span class="sxs-lookup"><span data-stu-id="25951-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="25951-324">特定のコンプライアンス要件または規制要件を満たしたクラウド アプリ セキュリティの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="25951-325">テスト以外の実稼働環境へのサービスの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="25951-326">概念実証としてクラウド アプリの検出を展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="25951-327">サポート <a href=" /fasttrack/us-gov-appendix-overview"> GCC-HighまたはGCC-DoD (Office 365 US Government)</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="25951-328">Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="25951-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="25951-329">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="25951-330">ブロック スクリプトを使用してアプリの使用状況をブロックする。</span><span class="sxs-lookup"><span data-stu-id="25951-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="25951-331">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="25951-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="25951-332">非機能アプリの条件付きアクセス アプリ制御のオンボーディングと展開。</span><span class="sxs-lookup"><span data-stu-id="25951-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="25951-333">サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="25951-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="25951-334">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="25951-335">Microsoft Power Automat プレイブックを含む自動調査と修復。</span><span class="sxs-lookup"><span data-stu-id="25951-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="25951-336">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="25951-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="25951-337"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="25951-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="25951-338">Microsoft Defender for Endpoint は、エンタープライズ ネットワークによる高度な脅威の防止、検出、調査、および応答を支援するために設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="25951-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="25951-339">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-340">エンドポイントをセキュリティで保護するためのテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="25951-341">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="25951-342">OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="25951-343">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="25951-344">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="25951-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="25951-345">オンボード エンドポイントを使用して Defender for Endpoint エージェント プロファイルを展開する方法を説明して、Microsoft Defender for Endpoint サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="25951-346">展開のガイダンス、構成の支援、および次の教育を行います。</span><span class="sxs-lookup"><span data-stu-id="25951-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-347">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="25951-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-348">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="25951-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-349">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="25951-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-350">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="25951-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-351">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="25951-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-352">デバイスのセキュリティで保護されたスコア。</span><span class="sxs-lookup"><span data-stu-id="25951-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="25951-353">Microsoft エンドポイント マネージャーを使用した Microsoft Defender SmartScreen 構成。</span><span class="sxs-lookup"><span data-stu-id="25951-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="25951-354">シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。</span><span class="sxs-lookup"><span data-stu-id="25951-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="25951-355">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="25951-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="25951-356">Microsoft Defender for Office 365 と Microsoft Defender for Endpoint の統合。</span><span class="sxs-lookup"><span data-stu-id="25951-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="25951-357">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="25951-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="25951-358">次のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="25951-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-359">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="25951-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-360">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="25951-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-361">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="25951-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-362">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="25951-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-363">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="25951-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-364">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="25951-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="25951-365">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="25951-366"></li>
</ul>

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="25951-367">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="25951-368">サポート <a href=" /fasttrack/us-gov-appendix-overview"> GCC-HighまたはGCC-DoD (Office 365 US Government)</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="25951-369">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="25951-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="25951-370">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="25951-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="25951-371">次の Microsoft Defender for Endpoint エージェントのオンボーディングまたは構成。</span><span class="sxs-lookup"><span data-stu-id="25951-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-372">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="25951-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-373">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="25951-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-374">Linux。</span><span class="sxs-lookup"><span data-stu-id="25951-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-375">モバイル デバイス (Android と iOS)。</span><span class="sxs-lookup"><span data-stu-id="25951-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="25951-376">仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。</span><span class="sxs-lookup"><span data-stu-id="25951-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="25951-377">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="25951-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-378">オフライン通信用にプロキシ サーバーを構成する。</span><span class="sxs-lookup"><span data-stu-id="25951-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-379">ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。</span><span class="sxs-lookup"><span data-stu-id="25951-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-380">サーバーを Azure セキュリティ センターにオンボーディングする。</span><span class="sxs-lookup"><span data-stu-id="25951-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-381">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="25951-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="25951-382">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="25951-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-383">Intune ベースの手動展開。</span><span class="sxs-lookup"><span data-stu-id="25951-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-384">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="25951-385">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-386">手動展開。</span><span class="sxs-lookup"><span data-stu-id="25951-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="25951-387">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="25951-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-388">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="25951-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-389">アプリコントロール。</span><span class="sxs-lookup"><span data-stu-id="25951-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="25951-390">デバイス制御。</span><span class="sxs-lookup"><span data-stu-id="25951-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="25951-391">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="25951-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-392">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="25951-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="25951-393">次のようなアカウント保護機能の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="25951-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="25951-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="25951-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="25951-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="25951-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="25951-396">BitLocker の構成または管理。</span><span class="sxs-lookup"><span data-stu-id="25951-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="25951-397">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="25951-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="25951-398">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="25951-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="25951-399">Microsoft 365 Defender の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="25951-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="25951-400">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="25951-401">Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="25951-402">グループ ポリシー オブジェクト (GPO)、グループ ポリシー オブジェクト、またはグループ ポリシー オブジェクトを使用した Defender SmartScreen 構成をWindows セキュリティまたはガイダンスMicrosoft Edge。</span><span class="sxs-lookup"><span data-stu-id="25951-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="25951-403">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="25951-404"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="25951-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="25951-405">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="25951-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="25951-406">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-407">リソース容量計画のサイジング ツールを実行する。</span><span class="sxs-lookup"><span data-stu-id="25951-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="25951-408">Defender for Identity のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="25951-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="25951-409">Defender for Identity を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="25951-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="25951-410">センサーを展開して、ネットワーク トラフィックをキャプチャして解析し、Windowsイベントをドメイン コントローラーから直接取得します。次の内容を含む。</span><span class="sxs-lookup"><span data-stu-id="25951-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="25951-411">センサー パッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="25951-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="25951-412">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="25951-413">センサーをドメイン コントローラーにサイレント モードでインストールします。</span><span class="sxs-lookup"><span data-stu-id="25951-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="25951-414">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="25951-415">イベント コレクター Windows構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="25951-416">以下を含む、ポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="25951-417">Defender for Identity と Microsoft Cloud App Security統合 (Cloud App Securityライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="25951-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="25951-418">エンティティ タグの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="25951-419">機密性の高いアカウントのタグ付け。</span><span class="sxs-lookup"><span data-stu-id="25951-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="25951-420">正常性の問題とセキュリティアラートに関する電子メール通知の受信。</span><span class="sxs-lookup"><span data-stu-id="25951-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="25951-421">アラートの除外を構成する。</span><span class="sxs-lookup"><span data-stu-id="25951-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="25951-422">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="25951-423">Identity Security Posture Assessment レポートについて。</span><span class="sxs-lookup"><span data-stu-id="25951-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="25951-424">ユーザー調査の優先度スコアとユーザー調査のランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="25951-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="25951-425">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="25951-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="25951-426">侵害されたアカウントの修復オプションの説明。</span><span class="sxs-lookup"><span data-stu-id="25951-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="25951-427">Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。</span><span class="sxs-lookup"><span data-stu-id="25951-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="25951-428"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="25951-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="25951-429">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="25951-430">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="25951-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="25951-431">Defender for Identity を概念実証として展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="25951-432">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="25951-433">次の Defender for Identity センサー アクティビティを展開または実行します。</span><span class="sxs-lookup"><span data-stu-id="25951-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="25951-434">手動の容量計画。</span><span class="sxs-lookup"><span data-stu-id="25951-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="25951-435">監査ツールの実行。</span><span class="sxs-lookup"><span data-stu-id="25951-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="25951-436">スタンドアロン センサーの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="25951-437">Active Directory フェデレーション サービス (FS) AD展開します。</span><span class="sxs-lookup"><span data-stu-id="25951-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="25951-438">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="25951-439">サード パーティ製のツールを使用してセンサーを展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="25951-440">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="25951-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="25951-441">Active Directory での Microsoft アカウント (MSA) の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="25951-442">honeytokens の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="25951-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="25951-443">ネットワーク名解決 (NNR) を有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="25951-444">削除済みオブジェクト コンテナーの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="25951-445">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="25951-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="25951-446">さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="25951-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="25951-447">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="25951-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="25951-448">脅威または高度な狩猟。</span><span class="sxs-lookup"><span data-stu-id="25951-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="25951-449">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="25951-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="25951-450">Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。</span><span class="sxs-lookup"><span data-stu-id="25951-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="25951-451">Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="25951-452">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="25951-453">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="25951-454">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="25951-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="25951-455">Id の <a href="/defender-for-identity/prerequisites"> 前提条件を Microsoft Defender に合わせて調整します</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="25951-456">Active Directory が展開されました。</span><span class="sxs-lookup"><span data-stu-id="25951-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="25951-457">Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。</span><span class="sxs-lookup"><span data-stu-id="25951-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="25951-458">Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="25951-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="25951-459">次のいずれかの方法で実行されているドメイン コントローラー。</span><span class="sxs-lookup"><span data-stu-id="25951-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="25951-460">Windowsサーバー 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="25951-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="25951-461">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="25951-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="25951-462">Windows Server 2012R2。</span><span class="sxs-lookup"><span data-stu-id="25951-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="25951-463">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="25951-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="25951-464">WindowsKB4487044 を含むサーバー 2019 (OS ビルド 17763.316 以降)。</span><span class="sxs-lookup"><span data-stu-id="25951-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="25951-465">Microsoft .NET Framework 4.7 以降をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="25951-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="25951-466">最低 5 GB のディスク領域が必要で、10 GB を推奨します。</span><span class="sxs-lookup"><span data-stu-id="25951-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="25951-467">ドメイン コントローラーにインストールされている 2 つの (2) コアと 6 つの (6) GB の RAM。</span><span class="sxs-lookup"><span data-stu-id="25951-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="25951-468"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="25951-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="25951-p114">Microsoft Defender for Office 365 は、メール メッセージ、リンク (URL)、コラボレーション ツールによってもたらされる悪意のある脅威から組織を保護します。Defender for Office 365 には次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="25951-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="25951-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> 脅威保護ポリシー</a>: 脅威保護ポリシーを定義して、組織に適切なレベルの保護を設定します。</span><span class="sxs-lookup"><span data-stu-id="25951-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="25951-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">レポート</a>: リアルタイム レポートを表示して、組織内のパフォーマンスOffice 365 Defender を監視します。</span><span class="sxs-lookup"><span data-stu-id="25951-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="25951-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">脅威の調査および反応機能</a>: 最先端のツールを使用して、脅威を調査、把握、シミュレーション、および回避を行います。</span><span class="sxs-lookup"><span data-stu-id="25951-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="25951-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">自動調査および対応機能</a>: 脅威の調査と軽減にかかる時間と労力を節約します。</span><span class="sxs-lookup"><span data-stu-id="25951-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="25951-475">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="25951-476">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="25951-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="25951-477">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="25951-478">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="25951-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="25951-479">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="25951-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="25951-480">ポータルでのインシデントの相関関係Microsoft 365 Defenderします。</span><span class="sxs-lookup"><span data-stu-id="25951-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="25951-481"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="25951-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="25951-482">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="25951-483">継続的な管理、脅威対応、修復。</span><span class="sxs-lookup"><span data-stu-id="25951-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="25951-484">サポート<a href=" /fasttrack/us-gov-appendix-overview">GCC-HighまたはGCC-DoD (Office 365)</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="25951-485">Defender for Office 365他のセキュリティ 製品とを比較するディスカッション。</span><span class="sxs-lookup"><span data-stu-id="25951-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="25951-486">Defender for Office 365概念実証として展開します。</span><span class="sxs-lookup"><span data-stu-id="25951-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="25951-487">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="25951-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="25951-488">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="25951-489">Microsoft およびプレイブックを含むPower Automate修復。</span><span class="sxs-lookup"><span data-stu-id="25951-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="25951-490">セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="25951-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="25951-491">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="25951-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="25951-492"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="25951-493">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-494">保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="25951-495">レコード管理 (E5 でのみサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="25951-496">ファイル 計画の作成を確認する。</span><span class="sxs-lookup"><span data-stu-id="25951-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="25951-497">レコードの作成と管理 (イベント ベースのレコードを含む)。</span><span class="sxs-lookup"><span data-stu-id="25951-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="25951-498">廃棄の確認。</span><span class="sxs-lookup"><span data-stu-id="25951-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="25951-499">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="25951-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="25951-500">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="25951-501">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="25951-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="25951-502">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="25951-503">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="25951-504">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="25951-505">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="25951-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="25951-506">

  <strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="25951-507">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="25951-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="25951-508">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="25951-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="25951-509">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="25951-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="25951-510">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="25951-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="25951-511">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="25951-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="25951-512">E3 のサポート。</span><span class="sxs-lookup"><span data-stu-id="25951-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="25951-513">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="25951-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="25951-514">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="25951-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="25951-515">General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="25951-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-516"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="25951-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="25951-517">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-518">データ分類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-519">機密情報の種類 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-520">感度ラベルの作成 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-521">感度ラベルの適用 (E3 および E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-522">トレーニング可能な分類子 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-523">コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-524">ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-525">Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="25951-526">Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。</span><span class="sxs-lookup"><span data-stu-id="25951-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="25951-527">

<strong> コンプライアンス マネージャー</strong></span><span class="sxs-lookup"><span data-stu-id="25951-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="25951-528">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="25951-529">役割の種類を確認する。</span><span class="sxs-lookup"><span data-stu-id="25951-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="25951-530">評価の追加と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="25951-531">改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="25951-532">組み込みのコントロール マッピングを確認し、コントロールを評価します。</span><span class="sxs-lookup"><span data-stu-id="25951-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="25951-533">評価内でレポートを生成する。</span><span class="sxs-lookup"><span data-stu-id="25951-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="25951-534">

<strong> Azure 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="25951-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="25951-535">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="25951-536">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="25951-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="25951-537">ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="25951-538">ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。</span><span class="sxs-lookup"><span data-stu-id="25951-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="25951-539">Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。</span><span class="sxs-lookup"><span data-stu-id="25951-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="25951-540">Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="25951-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="25951-541">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="25951-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="25951-542">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="25951-543"><strong>以下はスコープ外です </strong></span><span class="sxs-lookup"><span data-stu-id="25951-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="25951-544">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="25951-544">Customer key.</span></span></li>
<li><span data-ttu-id="25951-545">機密情報の種類のカスタム正規表現 (RegEx) の開発。</span><span class="sxs-lookup"><span data-stu-id="25951-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="25951-546">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="25951-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="25951-547">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="25951-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="25951-548">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="25951-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="25951-549">デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</span><span class="sxs-lookup"><span data-stu-id="25951-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="25951-550">業界および地域の規制および要件への準拠。</span><span class="sxs-lookup"><span data-stu-id="25951-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="25951-551">コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</span><span class="sxs-lookup"><span data-stu-id="25951-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="25951-552">General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a></span><span class="sxs-lookup"><span data-stu-id="25951-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="25951-553"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="25951-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="25951-554">お客様の前提条件の責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="25951-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="25951-555">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="25951-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="25951-556">承認済みの分類分類。</span><span class="sxs-lookup"><span data-stu-id="25951-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="25951-557">キー管理に関する規制上の制限または要件について理解する。</span><span class="sxs-lookup"><span data-stu-id="25951-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="25951-558">Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="25951-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="25951-559">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="25951-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="25951-560">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="25951-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="25951-561">詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="25951-562">ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="25951-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="25951-563">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="25951-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="25951-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="25951-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="25951-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="25951-566">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="25951-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="25951-567">展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="25951-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="25951-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="25951-569">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="25951-570">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="25951-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="25951-571">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="25951-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="25951-572">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="25951-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="25951-573">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="25951-574">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="25951-575">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="25951-576">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="25951-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="25951-577">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="25951-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-578">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="25951-579">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="25951-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="25951-580">Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="25951-581">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="25951-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="25951-582">組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。</span><span class="sxs-lookup"><span data-stu-id="25951-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="25951-583">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="25951-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="25951-584">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="25951-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="25951-585">リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="25951-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="25951-586">モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="25951-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="25951-587">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="25951-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="25951-588">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="25951-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="25951-589">アプリ保護に関するガイダンスを提供する:</span><span class="sxs-lookup"><span data-stu-id="25951-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="25951-590">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="25951-591">管理アプリの条件付きアクセス ポリシーを構成する。</span><span class="sxs-lookup"><span data-stu-id="25951-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="25951-592">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。</span><span class="sxs-lookup"><span data-stu-id="25951-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="25951-593">管理アプリの使用状況レポートを使用する。</span><span class="sxs-lookup"><span data-stu-id="25951-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="25951-594">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="25951-595">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="25951-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="25951-596">Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="25951-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="25951-597">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="25951-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="25951-598">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="25951-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="25951-599">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="25951-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="25951-600">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="25951-601">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="25951-602">ハイブリッド Azure グループへの参加をセットアップするAD提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="25951-603">MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="25951-604">リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="25951-605">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="25951-606">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="25951-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="25951-607"><strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="25951-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="25951-608">Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="25951-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="25951-609">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="25951-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="25951-610">Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="25951-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="25951-611">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="25951-612">Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="25951-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="25951-613">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="25951-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="25951-614">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="25951-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="25951-615">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="25951-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="25951-616">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="25951-617"><strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。</span><span class="sxs-lookup"><span data-stu-id="25951-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="25951-618"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="25951-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="25951-619">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="25951-620"><strong>エンドポイント用 Microsoft Defender と統合された Intune</strong></span><span class="sxs-lookup"><span data-stu-id="25951-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="25951-621"><strong>注</strong>: Intune と Microsoft Defender for Endpoint を統合し、Windows 10 のリスク レベル評価に基づいてデバイス コンプライアンス ポリシーを作成する際のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="25951-622">購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。</span><span class="sxs-lookup"><span data-stu-id="25951-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="25951-623">このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="25951-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="25951-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="25951-625">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="25951-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="25951-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="25951-626">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-627"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-627"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-628"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-628"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-629"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-629"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="25951-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="25951-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="25951-631">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="25951-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="25951-632">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="25951-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="25951-633">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-634">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="25951-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-635">メール交換 (MX) レコードを 365 Officeします。</span><span class="sxs-lookup"><span data-stu-id="25951-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-636">サブスクリプション サービスの一部である場合Office 365 機能用に Microsoft Defender をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="25951-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="25951-637">詳細については、この表の <strong>「Microsoft Defender for Office 365」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="25951-p126">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="25951-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="25951-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="25951-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="25951-642">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、情報権利管理 (IRM) メールをオンプレミスメールボックスから対応する Exchange Online メールボックスに移行します。</span><span class="sxs-lookup"><span data-stu-id="25951-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="25951-643">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="25951-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="25951-644">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="25951-645">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="25951-646">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="25951-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="25951-647">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="25951-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-648">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="25951-649">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="25951-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="25951-650">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="25951-651">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="25951-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="25951-652">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="25951-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="25951-653">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="25951-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="25951-654">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="25951-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="25951-655">複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域機能」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="25951-656">Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="25951-657"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="25951-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="25951-658">詳細については<strong>、「Microsoft Defender for Office 365」</strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="25951-659"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="25951-660">詳細については <strong> 、「Microsoft Information Governance in Security</strong> and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-661"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="25951-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="25951-662">詳細については <strong>、「Microsoft Information Protection in Security </strong> and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="25951-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="25951-664">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-665">Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADで Teams をサポートしていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="25951-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="25951-666">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="25951-667">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="25951-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="25951-668">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="25951-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="25951-669">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="25951-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="25951-670">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="25951-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="25951-671">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="25951-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="25951-672">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="25951-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="25951-673">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="25951-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="25951-674">Teams アプリ ポリシーの構成 (Teams Web アプリ、Teams デスクトップ アプリ、および Teams for iOS および Android アプリ)。</span><span class="sxs-lookup"><span data-stu-id="25951-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="25951-675">該当する場合は、次のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-676">Microsoft Teams ルーム デバイス:</span><span class="sxs-lookup"><span data-stu-id="25951-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="25951-677"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="25951-678">認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="25951-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="25951-679">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="25951-679">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="25951-680">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="25951-681">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="25951-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="25951-682">電話システム:</span><span class="sxs-lookup"><span data-stu-id="25951-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="25951-683">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="25951-684">通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="25951-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="25951-685">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="25951-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="25951-686">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="25951-687">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="25951-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="25951-688">直接ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="25951-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="25951-689">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="25951-690">セッション ボーダー コントローラー (SBC) の構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="25951-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="25951-691">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="25951-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="25951-692">音声ルートの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="25951-693">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="25951-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="25951-694">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="25951-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="25951-695">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="25951-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="25951-696">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="25951-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="25951-697">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="25951-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-698">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="25951-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="25951-699">Exchange メールボックスが存在します (Exchange ハイブリッド構成ではオンラインとオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="25951-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="25951-700">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="25951-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="25951-701">
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスで割り当ておよび有効になっていない場合、OneDrive for Business ストレージは 365 Officeされません。</span><span class="sxs-lookup"><span data-stu-id="25951-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="25951-702">ファイル共有はチャネルで引き続き機能しますが、ユーザーは 365 で OneDrive for Business ストレージを使用せずにチャットでファイルをOfficeできます。</span><span class="sxs-lookup"><span data-stu-id="25951-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="25951-703">Teams は SharePoint オンプレミスをサポートしない。</span><span class="sxs-lookup"><span data-stu-id="25951-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="25951-704">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する場合です。</span><span class="sxs-lookup"><span data-stu-id="25951-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="25951-705">オンプレミスに存在するメールボックスを持つユーザーは、Azure Office Connect を介して id を Office 365 ディレクトリAD必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="25951-706">これらの Exchange ハイブリッド顧客の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="25951-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="25951-707">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="25951-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="25951-708"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="25951-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="25951-709">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-710">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="25951-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="25951-711">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="25951-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="25951-712">Outlook モバイルのセキュリティ保護 (詳細 <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">については、「Exchange Online</a> での Outlook for iOS と Android のセキュリティ保護」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="25951-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="25951-713">Azure AD 365 でOffice ID。</span><span class="sxs-lookup"><span data-stu-id="25951-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-714">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="25951-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="25951-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="25951-716">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-717">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="25951-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="25951-718">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="25951-719">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="25951-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="25951-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="25951-721">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-722">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="25951-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="25951-723">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="25951-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="25951-724">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="25951-725">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="25951-726">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="25951-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="25951-727"><strong>Project Online Professional and Premium</strong></span><span class="sxs-lookup"><span data-stu-id="25951-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="25951-728">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-729">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="25951-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="25951-730">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="25951-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="25951-731">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="25951-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="25951-732">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="25951-733">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="25951-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="25951-734">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="25951-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="25951-735">Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="25951-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-736"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="25951-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="25951-737">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-738">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="25951-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="25951-739">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="25951-740">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="25951-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="25951-741">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="25951-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="25951-742">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="25951-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="25951-743">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="25951-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="25951-744">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="25951-745">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="25951-746">移行方法。</span><span class="sxs-lookup"><span data-stu-id="25951-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="25951-747">SharePoint のバージョンに応じて、OneDrive for Business に関する追加のガイダンスが提供されます。次のようにします。</span><span class="sxs-lookup"><span data-stu-id="25951-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="25951-748">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="25951-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="25951-749">SharePoint Online 2013 SP1 のインストール (該当する場合)、同期要件と ID 要件の計画と実装、OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="25951-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="25951-750">すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。</span><span class="sxs-lookup"><span data-stu-id="25951-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="25951-751">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリのリダイレクトを Office 365 (SharePoint Online 2013 に適用) し、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="25951-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="25951-752">既知のフォルダーを OneDrive にリダイレクトまたは移動する。</span><span class="sxs-lookup"><span data-stu-id="25951-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="25951-753">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="25951-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="25951-754">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="25951-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="25951-755">FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="25951-756"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="25951-757">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="25951-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="25951-758">
  <strong>注:</strong> セルフサービス サイトの作成は、SharePoint 2013 を実行しているオンプレミス サーバーでは有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="25951-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="25951-759">SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="25951-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="25951-760">
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードはスコープ内ではありません。</span><span class="sxs-lookup"><span data-stu-id="25951-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="25951-761">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="25951-762">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能の最小パブリック更新レベル」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="25951-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="25951-763">
  <strong>注:</strong> 複数地域機能の詳細については、「OneDrive の複数地域機能」および <a href="https://go.microsoft.com/fwlink/?linkid=831056">「SharePoint Online in oneDrive」および「SharePoint Online in Office 365」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="25951-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="25951-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="25951-765">エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="25951-766">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="25951-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="25951-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="25951-767">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-768"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-768"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-769"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-769"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-770"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-770"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="25951-771"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="25951-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="25951-772">詳細については <strong> 、「Azure Active Directory (Azure AD)</strong> と Azure AD Premium in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="25951-773">#セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="25951-773">#security-and-compliance</span></span>
<td><span data-ttu-id="25951-774"><strong>Azure 情報保護 </strong></span><span class="sxs-lookup"><span data-stu-id="25951-774"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="25951-775">Azure Information Protection の詳細については <strong>、「Microsoft Information</strong> Protection in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-775">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="25951-776"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="25951-776"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="25951-777">詳細については <strong> 、「Microsoft Intune in Security</strong> and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-777">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="25951-778">Windows 10</span><span class="sxs-lookup"><span data-stu-id="25951-778">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-779"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-779"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-780"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-780"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-781"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-781"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="25951-782"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="25951-782"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="25951-783">Windows 10 Enterprise への Windows 7 Professionalおよび Windows 8.1 Professional へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-783">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="25951-784">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-784">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="25951-785">Windows 10 の意図を理解する。</span><span class="sxs-lookup"><span data-stu-id="25951-785">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="25951-786">ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="25951-786">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="25951-787">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-787">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="25951-788">Windows 10 アプリを評価するためのオプションをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="25951-788">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="25951-789">デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="25951-789">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="25951-790">構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と Microsoft 365 Apps の展開を支援することで、Microsoft 365 Apps の互換性評価を行います。</span><span class="sxs-lookup"><span data-stu-id="25951-790">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="25951-791">展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="25951-791">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="25951-792">必要なデバイス ハードウェア要件を満たす場合に、既存のデバイスのアップグレード ガイダンスを Windows 10 Enterprise に提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-792">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="25951-793">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-793">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="25951-794">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="25951-794">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="25951-795">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="25951-795">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="25951-796">Windows 10 展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。</span><span class="sxs-lookup"><span data-stu-id="25951-796">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="25951-797">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-797">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="25951-798">
  
<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-798">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="25951-799">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="25951-799">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="25951-800">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="25951-800">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="25951-801">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="25951-801">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="25951-802">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="25951-802">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="25951-803">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="25951-803">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="25951-804">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-804">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="25951-805">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="25951-805">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="25951-806">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="25951-806">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="25951-807">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-807">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="25951-808">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-808">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="25951-809">ソース OS: Windows 7 Enterpriseまたはプロフェッショナル、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="25951-809">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="25951-810">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="25951-810">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="25951-811">ターゲット OS: ウィンドウ 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="25951-811">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="25951-812">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-812">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="25951-813">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="25951-813">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="25951-814">Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="25951-814">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="25951-815">詳細については、「<a href="/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-815">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="25951-816"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="25951-816"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="25951-817">詳細については <strong> 、「Microsoft Defender for Endpoint in Security and</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-817">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="25951-818">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="25951-818">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-819"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-819"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-820"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-820"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-821"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-821"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="25951-822"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="25951-822"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="25951-823">Windows Virtual Desktop (デスクトップおよびアプリ仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-823">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="25951-824">Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="25951-824">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="25951-825">次のリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-825">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="25951-826">以下を使用して Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を展開します。</span><span class="sxs-lookup"><span data-stu-id="25951-826">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="25951-827">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="25951-827">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="25951-828">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="25951-828">Shared image.</span></span></li>
<li><span data-ttu-id="25951-829">Office展開Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="25951-829">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="25951-830">ネイティブ Windows 仮想デスクトップでの MICROSOFT 365 Apps for FSLogix の構成。</span><span class="sxs-lookup"><span data-stu-id="25951-830">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="25951-831">FSLogix の場合:</span><span class="sxs-lookup"><span data-stu-id="25951-831">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="25951-832">エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="25951-832">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="25951-833">プロファイルコンテナーとカスタム コンテナー Office構成します。</span><span class="sxs-lookup"><span data-stu-id="25951-833">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="25951-834">Microsoft 365 Apps のコンテンツ除外とフォルダー リダイレクトの構成。</span><span class="sxs-lookup"><span data-stu-id="25951-834">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="25951-835">Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="25951-835">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="25951-836">最適化を使用した Microsoft Teams の展開。</span><span class="sxs-lookup"><span data-stu-id="25951-836">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="25951-837">

<strong>以下はスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="25951-837">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="25951-838">お客様の Windows Virtual Desktop インフラストラクチャ展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="25951-838">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="25951-839">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="25951-839">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="25951-840">Windows Virtual Desktop 用のカスタム イメージの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-840">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="25951-841">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="25951-841">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="25951-842">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="25951-842">Linux scenarios.</span></span></li>
<li><span data-ttu-id="25951-843">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="25951-843">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="25951-844">Windows 仮想デスクトップ用の Microsoft Endpoint Configuration Manager および Microsoft Endpoint Manager 構成 (パッチ適用と管理を含む)。</span><span class="sxs-lookup"><span data-stu-id="25951-844">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="25951-845">Microsoft 365 Defender with Windows 10 multi-session.</span><span class="sxs-lookup"><span data-stu-id="25951-845">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="25951-846">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-846">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="25951-847">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="25951-847">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="25951-848"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-848"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="25951-849"><a href="/azure/virtual-desktop/overview">Windows Virtual Deskstop をサポートするために必要なインフラストラクチャ</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-849">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="25951-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Windows Virtual Deskstop の FSLogix プロファイル コンテナーの記憶域</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="25951-851">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="25951-851">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="25951-852">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="25951-852">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="25951-853">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="25951-853">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="25951-854">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="25951-854">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="25951-855">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="25951-855">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="25951-856">Windows 仮想デスクトップへの接続を許可するファイアウォール ルール。</span><span class="sxs-lookup"><span data-stu-id="25951-856">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="25951-857">詳細については、「サポートされる <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">リモート デスクトップ クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-857">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="25951-858">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="25951-858">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="25951-859">ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="25951-859">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="25951-860">Azure を使用した Active Directory AD Azure で接続します。</span><span class="sxs-lookup"><span data-stu-id="25951-860">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="25951-861">Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</span><span class="sxs-lookup"><span data-stu-id="25951-861">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="25951-862">Active Directory ドメイン サービス (DS AD)。</span><span class="sxs-lookup"><span data-stu-id="25951-862">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="25951-863">App Assure</span><span class="sxs-lookup"><span data-stu-id="25951-863">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-864"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-864"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-865"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-865"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-866"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-866"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="25951-867"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="25951-867"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="25951-868">App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="25951-868">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="25951-869">App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="25951-869">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="25951-870">また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様に対してガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力をします。</span><span class="sxs-lookup"><span data-stu-id="25951-870">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="25951-871">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。</span><span class="sxs-lookup"><span data-stu-id="25951-871">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="25951-872"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="25951-872"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="25951-873"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="25951-873"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="25951-874"><strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-874"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="25951-875"><strong>Windows 仮想デスクトップ</strong> - 詳細については <a href="/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは」</a> および <a href="/azure/virtual-desktop/windows-10-multisession-faq">「Windows 10 Enterprise マルチセッション FAQ」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-875"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="25951-876">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-876">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="25951-877">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="25951-877">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="25951-878">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-878">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="25951-879">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="25951-879">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="25951-880">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="25951-880">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="25951-881">詳細については、「<a href="/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25951-881">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="25951-882">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="25951-882">App packaging-only services.</span></span> <span data-ttu-id="25951-883">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="25951-883">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="25951-884">

<strong>顧客の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-884">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="25951-885">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="25951-885">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="25951-886">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="25951-886">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="25951-887">
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="25951-887">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="25951-888">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="25951-888">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="25951-889">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="25951-889">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="25951-890"><strong>Windows 10 および Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="25951-890"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="25951-891">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="25951-891">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="25951-892">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="25951-892">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="25951-893">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Apps でも動作します。</span><span class="sxs-lookup"><span data-stu-id="25951-893">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="25951-894">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="25951-894">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="25951-895">x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様に <a href="https://insider.windows.com/">プレビューで使用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-895">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="25951-896">Windows 10 バージョン 2004 以降の Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">してサポートされています</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-896">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="25951-897">Windows Insider Program のお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="25951-897">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="25951-898">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="25951-898">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="25951-899">Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="25951-899">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-900">Web は常に進化していますので、Microsoft Edge の既知のサイト互換性に影響を与える変更の公開リストを <a href="/microsoft-edge/web-platform/site-impacting-changes">必ず確認してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-900">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="25951-901">
  <strong>Windows 仮想デスクトップ </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-901">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="25951-902">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="25951-902">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-903">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 仮想デスクトップの一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="25951-903">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-904">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="25951-904">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="25951-905">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="25951-905">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="25951-906">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="25951-906">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-907">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="25951-907">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="25951-908">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="25951-908">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="25951-909">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="25951-909">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="25951-910"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="25951-910"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="25951-911"><strong>FastTrackガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="25951-911"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="25951-912"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="25951-912"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="25951-913"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="25951-913"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="25951-914">リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。</span><span class="sxs-lookup"><span data-stu-id="25951-914">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="25951-915">(Microsoft Edge Intune Windows 10) Microsoft エンドポイント マネージャーにMicrosoft Endpoint Configuration Manager展開します。</span><span class="sxs-lookup"><span data-stu-id="25951-915">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="25951-916">構成Microsoft Edge (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="25951-916">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="25951-917">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="25951-917">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="25951-918">既存のInternet Explorerリストを使用してEnterpriseモードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="25951-918">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="25951-919">(詳細については、「Engaging FastTrack」<a href="/fasttrack/process-and-expectations#engaging-fasttrack">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="25951-919">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="25951-920">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="25951-920">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="25951-921">App Assure の互換性のサポートを要求するには、FastTrack<a href="https://fasttrack.microsoft.com/portal#/signin">ポータル</a>にサインインしてエンゲージメントを開始します。</span><span class="sxs-lookup"><span data-stu-id="25951-921">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="25951-922">ブックマークのエッジ導入と構成のガイダンスを計画Microsoft Searchします。</span><span class="sxs-lookup"><span data-stu-id="25951-922">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="25951-923">

<strong>以下はスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="25951-923">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="25951-924">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="25951-924">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="25951-925">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="25951-925">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
