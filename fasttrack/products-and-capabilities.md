---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件をソース環境に提供します。
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016689"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="724ac-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="724ac-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="724ac-105">FastTrack でサポートされているサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="724ac-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="724ac-106">このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="724ac-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件をソース環境に提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="724ac-108">FastTrack では、最初にコア機能 (すべての Microsoft Online Services で共通) を使用し、次に対象となる各サービスのオンボーディングに役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="724ac-109">全般</span><span class="sxs-lookup"><span data-stu-id="724ac-109">General</span></span>](#general)
  - [<span data-ttu-id="724ac-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="724ac-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="724ac-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="724ac-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="724ac-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="724ac-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="724ac-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="724ac-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="724ac-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="724ac-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="724ac-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="724ac-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="724ac-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="724ac-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="724ac-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="724ac-118">全般</span><span class="sxs-lookup"><span data-stu-id="724ac-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-120"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="724ac-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="724ac-123">コア オンボーディングに関するリモート ガイダンスを提供します。コア オンボーディングには、サービスのプロビジョニング、テナント、および ID の統合が含まれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="724ac-124">また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="724ac-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="724ac-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="724ac-126"></li>
</ul>  

<strong> ID 統合 </strong></span><span class="sxs-lookup"><span data-stu-id="724ac-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="724ac-127">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="724ac-128">Azure AD Connect (単一または複数フォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="724ac-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="724ac-129">グループベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="724ac-130">クラウド移行、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (AD FS) を選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="724ac-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="724ac-131">単一AD Active Directory フォレストを持ち、AZURE AD Connect ツールと同期された ID を持つお客様に対して FS AD有効にします。</span><span class="sxs-lookup"><span data-stu-id="724ac-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="724ac-132">これには、R2 Active Directory Windows Server 2012 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="724ac-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="724ac-133">パスワード ハッシュ同期またはパススルー AD使用して、AD FS から Azure ADに認証を移行します。</span><span class="sxs-lookup"><span data-stu-id="724ac-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="724ac-134">シングル サインオン (SSO) のために、統合済みアプリ (Azure AD ギャラリーのサービスとしてのソフトウェア (SaaS) アプリなど) を AD FS から Azure AD に移行する。</span><span class="sxs-lookup"><span data-stu-id="724ac-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="724ac-135">Azure AD ギャラリーから SaaS アプリと SSO の統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="724ac-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="724ac-136">アプリ統合チュートリアルの一覧に示されている、統合済みの SaaS アプリの自動ユーザー プロビジョニングを有効にする <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">(Azure</a> AD ギャラリーの SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="724ac-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="724ac-137"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="724ac-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="724ac-138">FastTrack 特典の一環として、Microsoft 365 の最高レベルのパフォーマンスを保証するために、クラウド サービスに接続するためのベスト プラクティスについてお客様にアドバイスします。</span><span class="sxs-lookup"><span data-stu-id="724ac-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="724ac-139"><strong>Active Directory フォレスト</strong> これらの機能フォレスト レベルは、次のフォレスト構成で Windows Server 2003 以降に設定されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-140">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="724ac-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="724ac-141">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="724ac-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-142">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="724ac-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-143">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="724ac-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="724ac-144">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="724ac-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="724ac-145">テナントの構成と Azure Active Directory との統合に必要なタスク (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="724ac-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="724ac-146">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="724ac-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="724ac-147">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="724ac-148">複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange マルチハイブリッド構成に実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="724ac-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="724ac-149">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="724ac-150">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="724ac-151">複数フォレストのすべての構成では、Active Directory フェデレーション サービス (AD FS) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="724ac-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="724ac-152">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-153"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="724ac-154">次のリモート展開のガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-155">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="724ac-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="724ac-156">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="724ac-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="724ac-157">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="724ac-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="724ac-158">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="724ac-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="724ac-159">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="724ac-160">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="724ac-161">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="724ac-162">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="724ac-163">また、以前のバージョンの Office で動作するマクロやアドインを使用している場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加料金を使って互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="724ac-164">詳しくは <strong>、Windows</strong> <a href="#windows-10">10</a> の App Assure の部分をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="724ac-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="724ac-165">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="724ac-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-166"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="724ac-167">Microsoft では、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを示す、環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">提供します</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="724ac-168">これにより、移行の速度、ユーザー エクスペリエンス、サービスのパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="724ac-169">また、ネットワーク スコアの向上に役立つ、このデータによって強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="724ac-170">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="724ac-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="724ac-171">最新バージョンの Microsoft 365 アプリが必要です。</span><span class="sxs-lookup"><span data-stu-id="724ac-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="724ac-172"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている位置情報サービス。</span><span class="sxs-lookup"><span data-stu-id="724ac-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="724ac-173">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="724ac-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-174"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-175"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-176"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="724ac-177"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="724ac-178">次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="724ac-179">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="724ac-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="724ac-180">Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID の強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="724ac-181">Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="724ac-182">Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="724ac-183">Azure AD Password Protection による脆弱なパスワードの使用の検出とブロック。</span><span class="sxs-lookup"><span data-stu-id="724ac-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="724ac-184">Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。</span><span class="sxs-lookup"><span data-stu-id="724ac-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="724ac-185">Azure Identity Protection によるリスクベースの検出と修復の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="724ac-186">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="724ac-187">Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="724ac-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="724ac-188">役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="724ac-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="724ac-189">ハイブリッド Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="724ac-190">Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="724ac-191">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-192">Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-193">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-194">Azure ADの権利管理を使用して、Azure の ID とアクセス ライフサイクルAD管理します。</span><span class="sxs-lookup"><span data-stu-id="724ac-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="724ac-195">Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。</span><span class="sxs-lookup"><span data-stu-id="724ac-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-196">Azure AD利用規約の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-197">Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。</span><span class="sxs-lookup"><span data-stu-id="724ac-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-198">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-199">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="724ac-200">ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。</span><span class="sxs-lookup"><span data-stu-id="724ac-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-201">Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="724ac-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-202">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-203">コレクションを使用して、マイ アプリ ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="724ac-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-204">オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD と Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="724ac-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="724ac-206">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-207">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="724ac-208">ラベルおよびポリシーの作成と設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-209">ドキュメントへの情報保護の適用。</span><span class="sxs-lookup"><span data-stu-id="724ac-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="724ac-210">Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="724ac-211">Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="724ac-212">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="724ac-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="724ac-213">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="724ac-214">お客様の前提条件となる責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="724ac-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-215">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="724ac-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="724ac-216">承認された分類。</span><span class="sxs-lookup"><span data-stu-id="724ac-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="724ac-217">キー管理に関する規制上の制限または要件を理解する。</span><span class="sxs-lookup"><span data-stu-id="724ac-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-218">Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="724ac-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="724ac-219">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="724ac-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="724ac-220">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="724ac-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="724ac-221">詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="724ac-222">ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="724ac-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="724ac-223">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="724ac-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="724ac-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="724ac-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="724ac-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="724ac-226">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="724ac-227">展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="724ac-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="724ac-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="724ac-229">Microsoft 365 Defender は、高度な攻撃に対する統合された保護を提供するために、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整する統合された侵害前および侵害後のエンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="724ac-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="724ac-230">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="724ac-231">Microsoft 365 セキュリティ センターの概要について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="724ac-232">完全な攻撃範囲、影響を受けた資産、およびグループ化された自動修復アクションを確実にすることで、重要な問題に焦点を当てるなど、製品間のインシデントを確認します。</span><span class="sxs-lookup"><span data-stu-id="724ac-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="724ac-233">Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、メールボックスの調査を調整する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="724ac-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="724ac-234">複数のデータ セット間で電子メール、データ、デバイス、アカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="724ac-235">Microsoft セキュア スコアを使用して、顧客が全体的にセキュリティの状態を確認および改善する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="724ac-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="724ac-236"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="724ac-237">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="724ac-238">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="724ac-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="724ac-239">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="724ac-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="724ac-240">さまざまなアラートの種類と監視されるアクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="724ac-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="724ac-241">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="724ac-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="724ac-242">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="724ac-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="724ac-243">セキュリティ情報とイベント管理 (SIEM) または API の統合。</span><span class="sxs-lookup"><span data-stu-id="724ac-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="724ac-245">Microsoft Cloud App Security は、豊富な可視性、データ移動の制御、および高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) であり、すべての Microsoft およびサード パーティのクラウド サービスでサイバー脅威を特定して対処します。</span><span class="sxs-lookup"><span data-stu-id="724ac-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="724ac-246">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-247">以下を含むポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="724ac-248">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="724ac-249">管理者のアクセスと設定の管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="724ac-250">監視または監視から除外する特定のユーザー グループを選択するために展開をスコープ設定します。</span><span class="sxs-lookup"><span data-stu-id="724ac-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="724ac-251">IP 範囲とタグの設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="724ac-252">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスを個人用に設定します。</span><span class="sxs-lookup"><span data-stu-id="724ac-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="724ac-253">次を使用してシャドウ IT を提供するクラウド検出を設定します。</span><span class="sxs-lookup"><span data-stu-id="724ac-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="724ac-254">Microsoft Defender for Endpoints。</span><span class="sxs-lookup"><span data-stu-id="724ac-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="724ac-255">Zscaler</span><span class="sxs-lookup"><span data-stu-id="724ac-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="724ac-256">iboss。</span><span class="sxs-lookup"><span data-stu-id="724ac-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="724ac-257">アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使った</a> おすすめアプリの接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="724ac-258">条件付きアクセス ポータルと Cloud App Security ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</span><span class="sxs-lookup"><span data-stu-id="724ac-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="724ac-259">Cloud App Security および Cloud Discovery ダッシュボードの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="724ac-260">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="724ac-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="724ac-261">アプリ タグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="724ac-262">アプリの許可と削除。</span><span class="sxs-lookup"><span data-stu-id="724ac-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="724ac-263">アクティビティとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="724ac-264">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="724ac-265">Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="724ac-266">以下を除き、CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 個の使用事例 (最大 6 個のポリシーの作成または更新を含む) の構成支援を提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="724ac-267">サービスとしてのインターネット (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="724ac-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="724ac-268">ユーザーアクティビティを監視して、IaaS 環境内の脅威から保護する (#19)。</span><span class="sxs-lookup"><span data-stu-id="724ac-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="724ac-269"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="724ac-270">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="724ac-271">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="724ac-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="724ac-272">Docker またはログ コレクターを使用して、継続的レポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="724ac-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="724ac-273">詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、CASB の上位 20 の</a> 使用事例を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="724ac-274">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="724ac-275">ブロック スクリプトを使用したアプリの使用のブロック。</span><span class="sxs-lookup"><span data-stu-id="724ac-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="724ac-276">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="724ac-277">サードパーティの ID プロバイダー (ISP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="724ac-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="724ac-278">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="724ac-279">Microsoft Power Automate プレイブックを含む自動調査と修復。</span><span class="sxs-lookup"><span data-stu-id="724ac-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="724ac-280">セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="724ac-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="724ac-281">概念実証としての Cloud App Discovery の展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="724ac-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="724ac-283">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="724ac-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="724ac-284">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-285">エンドポイントをセキュリティで保護するテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="724ac-286">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="724ac-287">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサード パーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="724ac-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="724ac-288">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="724ac-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="724ac-289">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="724ac-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="724ac-290">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="724ac-291">展開のガイダンス、構成の支援、および次の教育について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-292">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-293">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="724ac-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-294">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="724ac-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-295">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="724ac-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-296">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="724ac-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-297">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="724ac-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-298">シミュレーションとチュートリアル (プラクティス シナリオ、偽のマルウェア、自動調査など) の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="724ac-299">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="724ac-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="724ac-300">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="724ac-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="724ac-301">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="724ac-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="724ac-302">次のオペレーティング システム:</span><span class="sxs-lookup"><span data-stu-id="724ac-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-303">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="724ac-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-304">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="724ac-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-305">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="724ac-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-306">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="724ac-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-307">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="724ac-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-308">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="724ac-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="724ac-309">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="724ac-310"></li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-311">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="724ac-312">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="724ac-313">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="724ac-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="724ac-314">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="724ac-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-315">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="724ac-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-316">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="724ac-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-317">Linux。</span><span class="sxs-lookup"><span data-stu-id="724ac-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-318">モバイル デバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="724ac-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-319">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-320">オフライン通信用のプロキシ サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-321">Configuration Manager のダウンレベルのインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-322">Azure セキュリティ センターへのサーバーのオンボーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-323">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="724ac-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-324">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-325">Intune による手動による展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-326">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="724ac-327">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-328">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-329">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-330">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="724ac-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-331">アプリの制御。</span><span class="sxs-lookup"><span data-stu-id="724ac-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-332">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="724ac-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-333">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="724ac-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-334">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="724ac-335">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="724ac-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="724ac-336">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="724ac-337">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="724ac-338">Kusto クエリの使用または作成に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="724ac-339">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="724ac-340"><strong>Id 用 Microsoft Defender </strong></span><span class="sxs-lookup"><span data-stu-id="724ac-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="724ac-341">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="724ac-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="724ac-342">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="724ac-343">Id 用の Defender のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="724ac-344">Id 用 Defender を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="724ac-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="724ac-345">ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。次が含されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="724ac-346">リソース容量計画用のサイズ変更ツールの実行。</span><span class="sxs-lookup"><span data-stu-id="724ac-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="724ac-347">監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。</span><span class="sxs-lookup"><span data-stu-id="724ac-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="724ac-348">ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャして解析するセンサーの展開。次の機能が含されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="724ac-349">センサー パッケージのダウンロード。</span><span class="sxs-lookup"><span data-stu-id="724ac-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="724ac-350">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="724ac-351">ドメイン コントローラーにサイレント モードでセンサーをインストールします。</span><span class="sxs-lookup"><span data-stu-id="724ac-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="724ac-352">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="724ac-353">Id 用 Defender を Microsoft Cloud App Security と統合する (Cloud App Security のライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="724ac-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="724ac-354">展開ガイダンス、構成支援、および以下の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="724ac-355">"ノイズ" を低減するために環境を調整します。</span><span class="sxs-lookup"><span data-stu-id="724ac-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="724ac-356">ID セキュリティの状況評価レポートについて。</span><span class="sxs-lookup"><span data-stu-id="724ac-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="724ac-357">ユーザーの調査の優先度スコアとユーザーの調査ランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="724ac-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="724ac-358">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="724ac-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="724ac-359">侵害されたアカウントでの修復オプションの提供。</span><span class="sxs-lookup"><span data-stu-id="724ac-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="724ac-360">Advanced Threat Analytics (ATA) から Id 用 Defender への移行を容易にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="724ac-361"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="724ac-362">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="724ac-363">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="724ac-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="724ac-364">Id センサー用の Defender の展開。次の機能が含されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="724ac-365">手動による容量計画。</span><span class="sxs-lookup"><span data-stu-id="724ac-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="724ac-366">スタンドアロンの容量でのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="724ac-367">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用したセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="724ac-368">サード パーティ製のツールを使用したセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="724ac-369">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続する。</span><span class="sxs-lookup"><span data-stu-id="724ac-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="724ac-370">honeytoken の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="724ac-371">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="724ac-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="724ac-372">さまざまなアラートの種類と監視対象アクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="724ac-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="724ac-373">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="724ac-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="724ac-374">脅威または高度な検索。</span><span class="sxs-lookup"><span data-stu-id="724ac-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="724ac-375">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="724ac-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="724ac-376">Id 用 Defender のセキュリティ警告ラボチュートリアルを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="724ac-377">指定されたセンサーを介してセキュリティ警告をサーバーに送信することで、Defender for Identity が疑わしいアクティビティを検出した場合の通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="724ac-378">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行し、特定のコンピューター上のローカル管理者を識別するための ID 用 Defender の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="724ac-379">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="724ac-380">セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="724ac-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="724ac-381">概念実証としての ID センサー用の Defender の展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="724ac-382">展開された Active Directory。</span><span class="sxs-lookup"><span data-stu-id="724ac-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="724ac-383">Id センサー用 Defender をインストールする予定のドメイン コントローラーは、Defender for Identity クラウド サービスへのインターネット接続を持っています。</span><span class="sxs-lookup"><span data-stu-id="724ac-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="724ac-384">ファイアウォールとプロキシは、Defender for Identity クラウド サービスと通信するために開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="724ac-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="724ac-385">次のいずれかのドメイン コントローラーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="724ac-386">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="724ac-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="724ac-387">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="724ac-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="724ac-388">Windows Server 2012 R2。</span><span class="sxs-lookup"><span data-stu-id="724ac-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="724ac-389">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="724ac-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="724ac-390">WINDOWS Server 2019 と KB4487044 (OS ビルド 17763.316)。</span><span class="sxs-lookup"><span data-stu-id="724ac-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="724ac-391"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="724ac-392">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-393">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-394">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-395">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-396">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="724ac-397">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-398">Advanced eDiscovery。</span><span class="sxs-lookup"><span data-stu-id="724ac-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="724ac-399">

  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="724ac-400">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="724ac-401">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="724ac-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="724ac-402">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="724ac-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="724ac-403">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="724ac-404">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="724ac-405">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="724ac-406">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-407"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="724ac-408">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-409">データの分類。</span><span class="sxs-lookup"><span data-stu-id="724ac-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="724ac-410">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="724ac-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="724ac-411">秘密度ラベルの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-412">感度ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="724ac-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-413">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="724ac-414">トレーニング可能な分類子。</span><span class="sxs-lookup"><span data-stu-id="724ac-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="724ac-415">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。</span><span class="sxs-lookup"><span data-stu-id="724ac-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="724ac-416">ポリシーを使用したラベルの発行 (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="724ac-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="724ac-417">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-418">Windows 10 デバイス用のエンドポイント DLP ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="724ac-419">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="724ac-420">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="724ac-420">Customer key.</span></span></li>
<li><span data-ttu-id="724ac-421">機密情報の種類用のカスタム正規表現 (RegEx) 開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="724ac-422">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="724ac-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="724ac-423">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="724ac-424">
<strong>注:</strong> 詳細については、「Enterprise <strong> Mobility </strong> + Security の Azure Information <a href="#enterprise-mobility--security">Protection」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="724ac-425">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="724ac-427">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="724ac-428">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="724ac-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="724ac-429">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="724ac-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-430">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="724ac-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="724ac-431">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="724ac-432">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-433">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-434">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="724ac-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-435">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="724ac-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-436">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-437">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-438">Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="724ac-439">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-440">組織に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、VPN プロファイルの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="724ac-441">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="724ac-442">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="724ac-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-443">リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="724ac-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="724ac-444">Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="724ac-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="724ac-445">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="724ac-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="724ac-446">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="724ac-446">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="724ac-447">次に関するアプリ保護ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-447">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-448">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-448">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="724ac-449">管理対象アプリの条件付きアクセス ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-449">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="724ac-450">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。</span><span class="sxs-lookup"><span data-stu-id="724ac-450">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-451">管理対象アプリの利用状況レポートの使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-451">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-452">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-452">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="724ac-453">
 
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-453">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="724ac-454">Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-454">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="724ac-455">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="724ac-455">The exact steps depend on your source environment.</span></span> <span data-ttu-id="724ac-456">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ac-456">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="724ac-457">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="724ac-457">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="724ac-458">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-458">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="724ac-459">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-459">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-460">ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。</span><span class="sxs-lookup"><span data-stu-id="724ac-460">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="724ac-461">MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-461">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-462">リモート インターネット ベースのデバイス管理の共同管理ソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-462">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-463">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-463">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="724ac-464">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="724ac-464">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="724ac-465"><strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-465"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="724ac-466">Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="724ac-466">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="724ac-467">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ac-467">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-468">Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。</span><span class="sxs-lookup"><span data-stu-id="724ac-468">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="724ac-469">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-469">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-470">iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-470">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="724ac-471">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-471">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-472">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-472">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-473">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-473">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="724ac-474">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを実稼働環境で既に動作している必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-474">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="724ac-475"><strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。</span><span class="sxs-lookup"><span data-stu-id="724ac-475"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="724ac-476"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="724ac-476"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="724ac-477">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="724ac-478"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-478"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="724ac-479"><strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-479"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="724ac-480">購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。</span><span class="sxs-lookup"><span data-stu-id="724ac-480">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="724ac-481">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="724ac-482"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-482"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="724ac-483">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-483">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="724ac-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="724ac-485">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-485">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-486">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-486">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="724ac-487">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-487">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="724ac-488">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-488">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="724ac-489">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="724ac-489">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-490">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-490">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="724ac-491">Office 365</span><span class="sxs-lookup"><span data-stu-id="724ac-491">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-492"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-492"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-493"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-493"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-494"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-494"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="724ac-495"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-495"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="724ac-496">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="724ac-496">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="724ac-497">正確な手順は、ソース環境とメール移行プランによって異なります。</span><span class="sxs-lookup"><span data-stu-id="724ac-497">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="724ac-498">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-498">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-499">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-499">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-500">メール交換 (MX) レコードの参照を 365 Officeする。</span><span class="sxs-lookup"><span data-stu-id="724ac-500">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-501">サブスクリプション サービスOffice 365 ATP 機能のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-501">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="724ac-502">詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-502">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="724ac-p126">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="724ac-p127">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="724ac-507">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、Information Rights Managed (IRM) 電子メールをオンプレミスのメールボックスから対応する Exchange Online メールボックスに移行します。</span><span class="sxs-lookup"><span data-stu-id="724ac-507">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="724ac-508">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="724ac-508">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="724ac-509">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-509">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="724ac-510">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys Identified Mail (DKIM)、ドメイン ベースのメッセージ認証、レポートと適合 (DMARC) および MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-510">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="724ac-511">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="724ac-511">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="724ac-512">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="724ac-512">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-513">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-513">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="724ac-514">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="724ac-514">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="724ac-515">Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-515">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="724ac-516">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="724ac-516">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-517">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="724ac-517">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="724ac-518">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="724ac-518">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-519">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="724ac-519">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="724ac-520">複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域</a>機能」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-520">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="724ac-521">Project for Office 365、Outlook for Windows、iOS および Android 用の Outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 Office</a>のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-521">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-522"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-522"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="724ac-523">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-523">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-524">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-524">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-525">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-525">Records management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-526">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-526">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-527">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-527">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="724ac-528">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-528">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-529">Advanced eDiscovery。</span><span class="sxs-lookup"><span data-stu-id="724ac-529">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="724ac-530">

  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-530">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="724ac-531">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-531">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="724ac-532">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="724ac-532">Data connectors.</span></span></li>
<li> <span data-ttu-id="724ac-533">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="724ac-533">Information barriers.</span></span></li>
<li> <span data-ttu-id="724ac-534">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-534">Privileged access management.</span></span></li>
<li> <span data-ttu-id="724ac-535">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-535">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="724ac-536">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-536">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="724ac-537">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-537">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-538"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-538"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="724ac-539">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-539">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-540">データの分類。</span><span class="sxs-lookup"><span data-stu-id="724ac-540">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="724ac-541">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="724ac-541">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="724ac-542">秘密度ラベルの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-542">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-543">感度ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="724ac-543">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-544">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-544">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="724ac-545">トレーニング可能な分類子。</span><span class="sxs-lookup"><span data-stu-id="724ac-545">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="724ac-546">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。</span><span class="sxs-lookup"><span data-stu-id="724ac-546">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="724ac-547">ポリシーを使用したラベルの発行 (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="724ac-547">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="724ac-548">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-548">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="724ac-549">Windows 10 デバイス用のエンドポイント DLP ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-549">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="724ac-550">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-550">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="724ac-551">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="724ac-551">Customer key.</span></span></li>
<li><span data-ttu-id="724ac-552">機密情報の種類用のカスタム正規表現 (RegEx) 開発。</span><span class="sxs-lookup"><span data-stu-id="724ac-552">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="724ac-553">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="724ac-553">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="724ac-554">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-554">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="724ac-555">
<strong>注:</strong> 詳細については、「Enterprise <strong> Mobility </strong> + Security の Azure Information <a href="#enterprise-mobility--security">Protection」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-555">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="724ac-556">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-556">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-557"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-557"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="724ac-558">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-558">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-559">Teams をサポートするために Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD要件を確認します。</span><span class="sxs-lookup"><span data-stu-id="724ac-559">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="724ac-560">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-560">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="724ac-561">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-561">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="724ac-562">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-562">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="724ac-563">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-563">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="724ac-564">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="724ac-564">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-565">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-565">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="724ac-566">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-566">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="724ac-567">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="724ac-567">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="724ac-568">Teams アプリ ポリシー (Teams Web アプリ、Teams デスクトップ アプリ、および iOS および Android 用 Teams アプリ) の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-568">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="724ac-569">該当する場合は、以下のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-569">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-570">Microsoft Teams Room Devices:</span><span class="sxs-lookup"><span data-stu-id="724ac-570">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="724ac-571"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-571">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="724ac-572">認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-572">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="724ac-573">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="724ac-573">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="724ac-574">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-574">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="724ac-575">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="724ac-575">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="724ac-576">電話システム:</span><span class="sxs-lookup"><span data-stu-id="724ac-576">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-577">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-577">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="724ac-578">通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="724ac-578">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="724ac-579">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="724ac-579">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="724ac-580">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-580">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="724ac-581">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-581">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-582">ダイレクト ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="724ac-582">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-583">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-583">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="724ac-584">セッション ボーダー コントローラー (SBC) 構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="724ac-584">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="724ac-585">ダイヤル プラン構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-585">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="724ac-586">ボイス ルート構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-586">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="724ac-587">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="724ac-587">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="724ac-588">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-588">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="724ac-589">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="724ac-589">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="724ac-590">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-590">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="724ac-591">Azure AD 365 で有効Office ID。</span><span class="sxs-lookup"><span data-stu-id="724ac-591">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-592">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="724ac-592">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="724ac-593">Exchange メールボックスが存在する (Exchange ハイブリッド構成ではオンラインとオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="724ac-593">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="724ac-594">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="724ac-594">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="724ac-595">
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスに割り当てられていない場合、ユーザーは OneDrive for Business ストレージを 365 Officeしません。</span><span class="sxs-lookup"><span data-stu-id="724ac-595">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="724ac-596">ファイル共有はチャネルで引き続き機能しますが、ユーザーは OneDrive for Business ストレージを使用せずにチャット内のファイルを Office 365 で共有できます。</span><span class="sxs-lookup"><span data-stu-id="724ac-596">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="724ac-597">Teams はオンプレミスの SharePoint をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="724ac-597">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="724ac-598">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する状態です。</span><span class="sxs-lookup"><span data-stu-id="724ac-598">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="724ac-599">オンプレミスにホームのメールボックスを持つユーザーの ID は、Azure Office Connect を介して Office 365 ディレクトリに同期ADがあります。</span><span class="sxs-lookup"><span data-stu-id="724ac-599">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="724ac-600">これらの Exchange ハイブリッドのお客様の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="724ac-600">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="724ac-601">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="724ac-601">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="724ac-603">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-603">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-604">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-604">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="724ac-605">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-605">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="724ac-606">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-606">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="724ac-607">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="724ac-607">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-608">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-608">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-609"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-609"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="724ac-610">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-610">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-611">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="724ac-611">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="724ac-612">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="724ac-612">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="724ac-613">Outlook モバイルのセキュリティ保護 ( <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">詳細については、「Exchange Online</a> での iOS および Android 用の Outlook のセキュリティ保護」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="724ac-613">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="724ac-614">Azure AD 365 で有効Office ID。</span><span class="sxs-lookup"><span data-stu-id="724ac-614">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-615">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="724ac-615">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-616"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-616"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="724ac-617">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-617">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-618">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="724ac-618">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="724ac-619">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-619">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-620">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-620">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-621"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-621"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="724ac-622">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-622">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-623">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-623">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="724ac-624">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="724ac-624">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="724ac-625">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-625">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="724ac-626">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-626">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-627">Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-627">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-628"><strong>Project Online Professional および Premium</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-628"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="724ac-629">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-629">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-630">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="724ac-630">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="724ac-631">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="724ac-631">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="724ac-632">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="724ac-632">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="724ac-633">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-633">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="724ac-634">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="724ac-634">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="724ac-635">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-635">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-636">Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-636">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-637"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-637"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="724ac-638">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-638">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-639">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-639">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="724ac-640">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-640">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="724ac-641">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="724ac-641">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="724ac-642">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-642">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="724ac-643">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="724ac-643">Planning site collections.</span></span></li>
<li><span data-ttu-id="724ac-644">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-644">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="724ac-645">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-645">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="724ac-646">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-646">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="724ac-647">移行方法。</span><span class="sxs-lookup"><span data-stu-id="724ac-647">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="724ac-648">OneDrive for Business の追加のガイダンスは、SharePoint のバージョンに応じて提供されます。次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="724ac-648">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-649">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="724ac-649">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="724ac-650">SharePoint Online 2013 SP1 (該当する場合) のインストール、同期と ID の要件の計画と実装、OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="724ac-650">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="724ac-651">すべてのユーザーに対する単一のロールアウト (または段階的なロールアウト) の計画と実装。</span><span class="sxs-lookup"><span data-stu-id="724ac-651">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="724ac-652">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に適用) を行い、対象ユーザーを設定して OneDrive へのアクセスを制御します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="724ac-652">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="724ac-653">OneDrive への既知のフォルダーのリダイレクトまたは移動。</span><span class="sxs-lookup"><span data-stu-id="724ac-653">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="724ac-654">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-654">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="724ac-655">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="724ac-655">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="724ac-656">Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-656">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="724ac-657"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-657"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-658">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ac-658">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="724ac-659">
  <strong>注:</strong> セルフサービス サイト作成は、SharePoint 2013 を実行するオンプレミス サーバーのスコープではありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-659">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="724ac-660">SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="724ac-660">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="724ac-661">
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードの対象ではありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-661">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="724ac-662">Microsoft パートナー <a href="https://go.microsoft.com/fwlink/?linkid=2080150">にお問い合</a> わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-662">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="724ac-663">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベル」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="724ac-663">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="724ac-664">
  <strong>注:</strong>複数地域機能の詳細については、「OneDrive の複数地域機能」および「Office <a href="https://go.microsoft.com/fwlink/?linkid=831056">365 の SharePoint Online」</a>を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="724ac-664">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-665"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-665"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="724ac-666">エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-666">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="724ac-667">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="724ac-667">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="724ac-668">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="724ac-668">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-669"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-669"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-670"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-670"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-671"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-671"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="724ac-672"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-672"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="724ac-673">次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-673">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="724ac-674">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="724ac-674">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="724ac-675">Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID の強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-675">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="724ac-676">Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-676">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="724ac-677">Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-677">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="724ac-678">Azure AD Password Protection による脆弱なパスワードの使用の検出とブロック。</span><span class="sxs-lookup"><span data-stu-id="724ac-678">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="724ac-679">Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。</span><span class="sxs-lookup"><span data-stu-id="724ac-679">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="724ac-680">Azure Identity Protection によるリスクベースの検出と修復の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-680">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="724ac-681">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-681">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="724ac-682">Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="724ac-682">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="724ac-683">役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="724ac-683">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="724ac-684">ハイブリッド Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-684">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="724ac-685">Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-685">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="724ac-686">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-686">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-687">Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-687">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-688">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-688">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-689">Azure ADの権利管理を使用して、Azure の ID とアクセス ライフサイクルAD管理します。</span><span class="sxs-lookup"><span data-stu-id="724ac-689">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="724ac-690">Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。</span><span class="sxs-lookup"><span data-stu-id="724ac-690">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-691">Azure AD利用規約の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-691">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-692">Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。</span><span class="sxs-lookup"><span data-stu-id="724ac-692">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-693">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-693">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-694">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-694">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="724ac-695">ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。</span><span class="sxs-lookup"><span data-stu-id="724ac-695">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-696">Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="724ac-696">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-697">動的グループAD Azure を有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-697">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-698">コレクションを使用して、マイ アプリ ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="724ac-698">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="724ac-699">オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD と Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-699">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="724ac-700"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="724ac-700"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="724ac-701">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-701">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-702">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-702">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="724ac-703">ラベルおよびポリシーの作成と設定。</span><span class="sxs-lookup"><span data-stu-id="724ac-703">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-704">ドキュメントへの情報保護の適用。</span><span class="sxs-lookup"><span data-stu-id="724ac-704">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="724ac-705">Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-705">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="724ac-706">Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="724ac-706">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="724ac-707">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="724ac-707">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="724ac-708">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-708">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="724ac-709">お客様の前提条件となる責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="724ac-709">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-710">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="724ac-710">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="724ac-711">承認された分類。</span><span class="sxs-lookup"><span data-stu-id="724ac-711">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="724ac-712">キー管理に関する規制上の制限または要件を理解する。</span><span class="sxs-lookup"><span data-stu-id="724ac-712">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-713">Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="724ac-713">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="724ac-714">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="724ac-714">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="724ac-715">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="724ac-715">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="724ac-716">詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-716">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="724ac-717">ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="724ac-717">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="724ac-718">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-718">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="724ac-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="724ac-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="724ac-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="724ac-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="724ac-721">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-721">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="724ac-722">展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="724ac-722">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="724ac-723"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-723"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="724ac-724">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-724">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="724ac-725">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="724ac-725">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="724ac-726">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="724ac-726">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-727">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="724ac-727">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="724ac-728">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-728">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="724ac-729">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-729">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-730">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-730">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-731">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="724ac-731">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-732">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="724ac-732">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-733">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-733">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-734">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-734">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-735">Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-735">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="724ac-736">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-736">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-737">組織に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、VPN プロファイルの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-737">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="724ac-738">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-738">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="724ac-739">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="724ac-739">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-740">リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="724ac-740">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="724ac-741">Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="724ac-741">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="724ac-742">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="724ac-742">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-743">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="724ac-743">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="724ac-744">次に関するアプリ保護ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-744">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-745">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-745">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="724ac-746">管理対象アプリの条件付きアクセス ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-746">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="724ac-747">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。</span><span class="sxs-lookup"><span data-stu-id="724ac-747">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-748">管理対象アプリの利用状況レポートの使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-748">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-749">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-749">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="724ac-750">
  
</li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-750">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="724ac-751">Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-751">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="724ac-752">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="724ac-752">The exact steps depend on your source environment.</span></span> <span data-ttu-id="724ac-753">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ac-753">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="724ac-754">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="724ac-754">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="724ac-755">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-755">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="724ac-756">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-756">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="724ac-757">ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。</span><span class="sxs-lookup"><span data-stu-id="724ac-757">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="724ac-758">MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-758">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-759">リモート インターネット ベースのデバイス管理の共同管理ソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-759">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="724ac-760">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-760">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="724ac-761">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="724ac-761">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="724ac-762"><strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-762"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="724ac-763">Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="724ac-763">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="724ac-764">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ac-764">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-765">Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。</span><span class="sxs-lookup"><span data-stu-id="724ac-765">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="724ac-766">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-766">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-767">iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-767">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="724ac-768">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-768">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-769">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-769">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="724ac-770">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="724ac-770">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="724ac-771">IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを実稼働環境で既に動作している必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-771">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="724ac-772"><strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。</span><span class="sxs-lookup"><span data-stu-id="724ac-772"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="724ac-773"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="724ac-773"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="724ac-774">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-774">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="724ac-775"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-775"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="724ac-776"><strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-776"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="724ac-777">購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。</span><span class="sxs-lookup"><span data-stu-id="724ac-777">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="724ac-778">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="724ac-779"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-779"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="724ac-780">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-780">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="724ac-781">Windows 10</span><span class="sxs-lookup"><span data-stu-id="724ac-781">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-782"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-782"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-783"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-783"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-784"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-784"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="724ac-785"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-785"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="724ac-786">Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-786">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="724ac-787">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-787">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-788">Windows 10 の目的を理解する。</span><span class="sxs-lookup"><span data-stu-id="724ac-788">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="724ac-789">ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="724ac-789">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="724ac-790">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-790">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="724ac-791">Windows 10 アプリを評価するための推奨オプション。</span><span class="sxs-lookup"><span data-stu-id="724ac-791">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="724ac-792">Desktop Analytics 展開計画の作成による Desktop Analytics とガイダンスの使用の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-792">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="724ac-793">Configuration Manager の Office 365 準備ダッシュボード、またはスタンドアロンの Toolkit for Office を活用した Microsoft 365 アプリの互換性評価と、Microsoft 365 アプリの展開のサポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-793">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="724ac-794">展開を成功するためにソース環境を最小要件に満たするために行う必要がある操作に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="724ac-794">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-795">必要なデバイス ハードウェア要件を満たす場合は、既存のデバイスの Windows 10 Enterprise へのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-795">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="724ac-796">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-796">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="724ac-797">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="724ac-797">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="724ac-798">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="724ac-798">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="724ac-799">Windows 10 の展開の一部として Configuration Manager を使用した Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-799">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="724ac-800">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-800">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="724ac-801">
  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-801">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-802">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="724ac-802">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="724ac-803">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-803">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-804">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-804">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="724ac-805">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="724ac-805">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="724ac-806">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="724ac-806">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="724ac-807">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-807">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="724ac-808">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-808">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="724ac-809">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="724ac-809">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="724ac-810">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-810">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="724ac-811">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-811">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-812">ソース OS: Windows 7 Enterprise Professional、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="724ac-812">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="724ac-813">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="724ac-813">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="724ac-814">ターゲット OS: Window 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="724ac-814">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="724ac-815">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-815">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-816">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="724ac-816">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="724ac-817">Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-817">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="724ac-818">詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-818">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="724ac-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="724ac-820">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="724ac-820">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="724ac-821">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-821">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-822">エンドポイントをセキュリティで保護するテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-822">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="724ac-823">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-823">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="724ac-824">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサード パーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="724ac-824">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="724ac-825">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="724ac-825">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="724ac-826">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="724ac-826">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="724ac-827">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-827">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="724ac-828">展開のガイダンス、構成の支援、および次の教育について説明します。</span><span class="sxs-lookup"><span data-stu-id="724ac-828">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-829">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-829">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-830">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="724ac-830">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-831">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="724ac-831">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-832">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="724ac-832">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-833">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="724ac-833">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="724ac-834">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="724ac-834">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="724ac-835">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="724ac-835">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-836">シミュレーションとチュートリアル (プラクティス シナリオ、偽のマルウェア、自動調査など) の確認。</span><span class="sxs-lookup"><span data-stu-id="724ac-836">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="724ac-837">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="724ac-837">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="724ac-838">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="724ac-838">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="724ac-839">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="724ac-839">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="724ac-840">次のオペレーティング システム:</span><span class="sxs-lookup"><span data-stu-id="724ac-840">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-841">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="724ac-841">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-842">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="724ac-842">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-843">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="724ac-843">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-844">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="724ac-844">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-845">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="724ac-845">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-846">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="724ac-846">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="724ac-847">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-847">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="724ac-848"></li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-848"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-849">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-849">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="724ac-850">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-850">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="724ac-851">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="724ac-851">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="724ac-852">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="724ac-852">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-853">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="724ac-853">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-854">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="724ac-854">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-855">Linux。</span><span class="sxs-lookup"><span data-stu-id="724ac-855">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-856">モバイル デバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="724ac-856">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-857">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-857">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-858">オフライン通信用のプロキシ サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-858">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-859">Configuration Manager のダウンレベルのインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-859">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-860">Azure セキュリティ センターへのサーバーのオンボーディング。</span><span class="sxs-lookup"><span data-stu-id="724ac-860">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-861">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="724ac-861">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-862">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-862">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-863">Intune による手動による展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-863">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-864">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-864">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="724ac-865">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-865">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-866">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-866">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-867">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-867">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-868">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="724ac-868">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-869">アプリの制御。</span><span class="sxs-lookup"><span data-stu-id="724ac-869">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-870">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="724ac-870">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-871">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="724ac-871">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="724ac-872">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-872">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="724ac-873">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="724ac-873">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="724ac-874">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-874">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="724ac-875">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-875">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="724ac-876">Kusto クエリの使用または作成に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="724ac-876">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="724ac-877">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="724ac-878">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="724ac-878">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-879"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-879"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-880"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-880"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-881"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-881"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="724ac-882"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-882"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="724ac-883">Windows Virtual Desktop (デスクトップとアプリの仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-883">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="724ac-884">Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="724ac-884">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="724ac-885">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-885">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="724ac-886">以下を使用して、Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows Virtual Desktop 環境を展開します。</span><span class="sxs-lookup"><span data-stu-id="724ac-886">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="724ac-887">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="724ac-887">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="724ac-888">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="724ac-888">Shared image.</span></span></li>
<li><span data-ttu-id="724ac-889">Office展開Toolkit (ODT)。</span><span class="sxs-lookup"><span data-stu-id="724ac-889">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="724ac-890">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="724ac-890">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="724ac-891">プロファイル コンテナーを使用した FSLogix エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-891">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="724ac-892">新しいコンテナーを使用した FSLogix エージェントOffice展開します。</span><span class="sxs-lookup"><span data-stu-id="724ac-892">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="724ac-893">コンテンツの除外を使用した FSLogix フォルダーの構成。</span><span class="sxs-lookup"><span data-stu-id="724ac-893">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="724ac-894">Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-894">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="724ac-895">Microsoft Teams の展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-895">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="724ac-896">Windows Virtual Desktop クライアントを使用した接続。</span><span class="sxs-lookup"><span data-stu-id="724ac-896">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="724ac-897">

<strong>次に示すのはスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="724ac-897">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="724ac-898">お客様の Windows Virtual Desktop 展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-898">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="724ac-899">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="724ac-899">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="724ac-900">カスタム画像。</span><span class="sxs-lookup"><span data-stu-id="724ac-900">Custom images.</span></span></li>
<li><span data-ttu-id="724ac-901">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="724ac-901">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="724ac-902">Linux シナリオ。</span><span class="sxs-lookup"><span data-stu-id="724ac-902">Linux scenarios.</span></span></li>
<li><span data-ttu-id="724ac-903">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="724ac-903">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="724ac-904">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-904">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="724ac-905">次の情報が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-905">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="724ac-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="724ac-907">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="724ac-907">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="724ac-908">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="724ac-908">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="724ac-909">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="724ac-909">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="724ac-910">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="724ac-910">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="724ac-911">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="724ac-911">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="724ac-912">Windows Virtual Desktop への接続を許可するファイアウォール規則。</span><span class="sxs-lookup"><span data-stu-id="724ac-912">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="724ac-913">詳細については、「サポートされるリモート デスクトップ <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-913">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="724ac-914">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="724ac-914">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="724ac-915">ID 戦略 <i>(次の 3 つのオプションのいずれかを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="724ac-915">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="724ac-916">Azure を使用した Active Directory AD Azure の Connect。</span><span class="sxs-lookup"><span data-stu-id="724ac-916">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="724ac-917">Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</span><span class="sxs-lookup"><span data-stu-id="724ac-917">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="724ac-918">Active Directory ドメイン サービス (AD DS)。</span><span class="sxs-lookup"><span data-stu-id="724ac-918">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="724ac-919">App Assure</span><span class="sxs-lookup"><span data-stu-id="724ac-919">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-920"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-920"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-921"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-921"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-922"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-922"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="724ac-923"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-923"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="724ac-924">App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="724ac-924">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="724ac-925">App Assure サービスをリクエストすると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加料金を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="724ac-925">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="724ac-926">また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様にガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力を行います。</span><span class="sxs-lookup"><span data-stu-id="724ac-926">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="724ac-927">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-927">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="724ac-928"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="724ac-928"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="724ac-929"><strong>Microsoft 365 アプリ</strong>  </span><span class="sxs-lookup"><span data-stu-id="724ac-929"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="724ac-930"><strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-930"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="724ac-931"><strong>Windows Virtual Desktop</strong> - 詳しくは <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは</a> 」と Windows 10 Enterprise マルチセッションの FAQ <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">をご覧ください</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-931"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="724ac-932">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-932">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-933">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="724ac-933">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="724ac-934">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-934">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="724ac-935">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-935">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="724ac-936">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="724ac-936">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="724ac-937">詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-937">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="724ac-938">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="724ac-938">App packaging-only services.</span></span> <span data-ttu-id="724ac-939">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="724ac-939">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="724ac-940">

<strong>お客様の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-940">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="724ac-941">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="724ac-941">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="724ac-942">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="724ac-942">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="724ac-943">
<strong>注:</strong>  Microsoft はソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="724ac-943">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="724ac-944">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="724ac-944">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="724ac-945">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="724ac-945">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="724ac-946"><strong>Windows 10 と Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="724ac-946"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-947">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="724ac-947">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-948">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="724ac-948">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="724ac-949">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイス上の Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="724ac-949">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="724ac-950">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="724ac-950">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="724ac-951">x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様がプレビュー <a href="https://insider.windows.com/">で利用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="724ac-951">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="724ac-952">Windows 10 バージョン 2004 (以降) の Windows Insider 以外のお客様は <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">、OpenCL</a>および OpenGL 互換機能パックを使って ARM64 Photoshop がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="724ac-952">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="724ac-953">Windows Insider Program のユーザーは、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換機能パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="724ac-953">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="724ac-954">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="724ac-954">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-955">Web アプリまたはサイトが Internet Explorer 11、Google Chrome のサポートされているバージョン、または Microsoft Edge の任意のバージョンで動作する場合は、Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="724ac-955">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-956">Web は常に進化し続けるので <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">、Microsoft Edge</a>のサイト互換性に影響を与える既知の変更の公開リストを必ず確認してください。</span><span class="sxs-lookup"><span data-stu-id="724ac-956">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-957">
  <strong>Windows Virtual Desktop </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-957">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="724ac-958">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-958">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-959">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されるアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise と Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-959">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-960">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="724ac-960">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="724ac-961">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限事項は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="724ac-961">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="724ac-962">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="724ac-962">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-963">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="724ac-963">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="724ac-964">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="724ac-964">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="724ac-965">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="724ac-965">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="724ac-966"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-966"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="724ac-967"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-967"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="724ac-968"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="724ac-968"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="724ac-969"><strong>Microsoft Edge</strong> (Windows 10 Enterprise のお客様向け)</span><span class="sxs-lookup"><span data-stu-id="724ac-969"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="724ac-970">Microsoft エンドポイント マネージャー (Microsoft Endpoint Configuration Manager または Intune) を使用して Windows 10 Enterprise に Microsoft Edge を展開する場合のリモート展開ガイダンスと互換性のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-970">We provide remote deployment guidance and compatibility assistance for: Deploying Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="724ac-971">Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリの構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="724ac-971">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="724ac-972">このモードで使用する必要がある可能性があるサイトの一Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="724ac-972">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="724ac-973">既存のInternet Explorerリストを使用してユーザー 設定モードを有効にする。</span><span class="sxs-lookup"><span data-stu-id="724ac-973">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="724ac-974">また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用している場合に互換性の問題が発生した場合は、追加費用を必要としない方法で問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="724ac-974">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="724ac-975">詳しくは <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">、「App Assure」</a> をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="724ac-975">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="724ac-976">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="724ac-976">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="724ac-977">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="724ac-977">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="724ac-978">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="724ac-978">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
