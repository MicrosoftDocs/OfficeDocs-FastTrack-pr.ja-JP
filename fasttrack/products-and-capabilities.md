---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するためにソース環境を最小要件に満たします。
ms.openlocfilehash: 5e65d160822ed50840ecc65f484433bf0d485913
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750104"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="97bbe-104">製品と機能</span><span class="sxs-lookup"><span data-stu-id="97bbe-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="97bbe-105">FastTrack でサポートされているサービスとシナリオ</span><span class="sxs-lookup"><span data-stu-id="97bbe-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="97bbe-106">このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="97bbe-107">現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するためにソース環境を最小要件に満たします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="97bbe-108">FastTrack では、最初にコア機能 (すべての Microsoft Online Services で共通) を使用し、次に対象となる各サービスのオンボーディングに役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="97bbe-109">全般</span><span class="sxs-lookup"><span data-stu-id="97bbe-109">General</span></span>](#general)
  - [<span data-ttu-id="97bbe-110">セキュリティと法令遵守</span><span class="sxs-lookup"><span data-stu-id="97bbe-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="97bbe-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="97bbe-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="97bbe-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="97bbe-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="97bbe-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="97bbe-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="97bbe-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="97bbe-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="97bbe-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="97bbe-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="97bbe-116">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="97bbe-116">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="97bbe-117">Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="97bbe-118">全般</span><span class="sxs-lookup"><span data-stu-id="97bbe-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-119"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-120"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-121"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="97bbe-122"><strong>コア オンボーディング</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-123">コア オンボーディングに関するリモート ガイダンスを提供します。コア オンボーディングには、サービスのプロビジョニング、テナント、および ID の統合が含まれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="97bbe-124">また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="97bbe-125">1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="97bbe-126"></li>
</ul>  

<strong> ID 統合 </strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="97bbe-127">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="97bbe-128">Azure AD Connect (単一または複数フォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期用のオンプレミスの Active Directory ID の準備。</span><span class="sxs-lookup"><span data-stu-id="97bbe-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="97bbe-129">グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="97bbe-130">クラウドへの移行、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (AD FS) を選択して有効にします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="97bbe-131">Azure AD Connect ツールと同期された単一の Active Directory フォレストと ID を持つお客様に対して AD FS を有効にします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="97bbe-132">これには R2 Active Directory Windows Server 2012 2.0 以上が必要です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="97bbe-133">パスワード ハッシュ同期またはパススルー AD使用して、AD FS から Azure ADに認証を移行します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="97bbe-134">シングル サインオン (SSO) のために、統合済みアプリ (Azure AD ギャラリーのサービスとしてのソフトウェア (SaaS) アプリなど) を AD FS から Azure AD に移行する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="97bbe-135">Azure AD ギャラリーから SaaS アプリと SSO の統合を有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="97bbe-136">アプリ統合チュートリアルの一覧に示されている、統合済みの SaaS アプリの自動ユーザー プロビジョニングを有効にする <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">(Azure</a> AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="97bbe-137"><strong>ネットワークの有効化 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="97bbe-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="97bbe-138">FastTrack 特典の一部として、Microsoft 365 の最高レベルのパフォーマンスを確保するためにクラウド サービスに接続するためのベスト プラクティスについてお客様にアドバイスします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="97bbe-139"><strong>Active Directory フォレスト</strong> これらの機能フォレスト レベルは、次のフォレスト構成で Windows Server 2003 以降に設定されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-140">1 つの Active Directory フォレスト。</span><span class="sxs-lookup"><span data-stu-id="97bbe-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-141">単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="97bbe-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-142">複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。  </span><span class="sxs-lookup"><span data-stu-id="97bbe-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-143">複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-144">複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。</span><span class="sxs-lookup"><span data-stu-id="97bbe-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-145">必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。</span><span class="sxs-lookup"><span data-stu-id="97bbe-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="97bbe-146">
  <strong>大事な</strong>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="97bbe-147">複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-148">複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange マルチハイブリッド構成に実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="97bbe-149">Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="97bbe-150">詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-151">複数フォレストのすべての構成では、Active Directory フェデレーション サービス (AD FS) の展開はスコープ外です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="97bbe-152">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-153"><strong>Microsoft 365 アプリ</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-154">次のリモート展開のガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-155">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="97bbe-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-156">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="97bbe-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-157">クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-158">iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-159">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-160">ローカルまたはクラウドのインストールの選択とセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-161">Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-162">Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="97bbe-163">また、以前のバージョンの Office で動作するマクロやアドインを使用している場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加料金を使って互換性の問題を修復するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="97bbe-164">詳しくは <strong>、Windows</strong> <a href="#windows-10">10</a> の App Assure の部分をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="97bbe-165">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="97bbe-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-166"><strong>ネットワークの正常性</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-167">Microsoft では、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを示す、環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">提供します</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="97bbe-168">これにより、移行速度、ユーザー エクスペリエンス、サービスのパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="97bbe-169">また、ネットワーク スコアの向上に役立つ、このデータによって強調表示されている修復手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="97bbe-170">Microsoft 365 管理センターへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-171">最新バージョンの Microsoft 365 アプリが必要です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-172"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている位置情報サービス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="97bbe-173">セキュリティとコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="97bbe-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-174"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-175"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-176"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="97bbe-177"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-178">次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="97bbe-179">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="97bbe-180">Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス によるパスワードリセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-181">Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-182">Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-183">Azure AD Password Protection で脆弱なパスワードの使用を検出し、ブロックします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-184">Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-185">Azure Identity Protection によるリスクベースの検出と修復の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-186">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-187">Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-188">役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-189">ハイブリッド Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-190">Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="97bbe-191">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-192">Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-193">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-194">Azure の権利管理ADを使用して、Azure の ID とアクセス ライフサイクルAD管理します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="97bbe-195">Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-196">Azure AD利用規約の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-197">Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-198">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-199">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="97bbe-200">ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-201">Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-202">Azure ADグループを有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-203">コレクションを使用して、マイ アプリ ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-204">オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD および Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="97bbe-206">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-207">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-208">ラベルおよびポリシーの作成と設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-209">ドキュメントへの情報保護の適用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-210">Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-211">Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-212">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="97bbe-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-213">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="97bbe-214">お客様の前提条件となる責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-215">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="97bbe-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-216">承認された分類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="97bbe-217">キー管理に関する規制上の制限または要件を理解する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-218">Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="97bbe-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="97bbe-219">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="97bbe-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="97bbe-220">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="97bbe-221">詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="97bbe-222">ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="97bbe-223">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="97bbe-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="97bbe-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="97bbe-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="97bbe-226">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="97bbe-227">展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="97bbe-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="97bbe-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="97bbe-229">Microsoft 365 Defender は、高度な攻撃に対する統合された保護を提供するために、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整する、侵害前および侵害後の統合エンタープライズ防御スイートです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="97bbe-230">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="97bbe-231">Microsoft 365 セキュリティ センターの概要について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-232">完全な攻撃範囲、影響を受けた資産、およびグループ化された自動修復アクションを確実にすることで、重要な問題に焦点を当てるなど、製品間のインシデントを確認します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-233">Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、メールボックスの調査を調整する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="97bbe-234">複数のデータ セットにわたる電子メール、データ、デバイス、アカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探す方法の例を説明し、提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="97bbe-235">Microsoft セキュア スコアを使用して、顧客が全体的にセキュリティの状態を確認および改善する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="97bbe-236"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="97bbe-237">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="97bbe-238">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="97bbe-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="97bbe-239">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="97bbe-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="97bbe-240">さまざまなアラートの種類と監視されるアクティビティを修復または解釈する方法。</span><span class="sxs-lookup"><span data-stu-id="97bbe-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="97bbe-241">ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。</span><span class="sxs-lookup"><span data-stu-id="97bbe-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="97bbe-242">カスタム脅威の検出。</span><span class="sxs-lookup"><span data-stu-id="97bbe-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="97bbe-243">セキュリティ情報とイベント管理 (SIEM) または API の統合。</span><span class="sxs-lookup"><span data-stu-id="97bbe-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-245">Microsoft Cloud App Security は、豊富な可視性、データ移動の制御、および高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) であり、すべての Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="97bbe-246">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-247">以下を含むポータルの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="97bbe-248">ユーザー グループのインポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="97bbe-249">管理者のアクセスと設定の管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="97bbe-250">監視または監視から除外する特定のユーザー グループを選択するために展開をスコープ設定します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="97bbe-251">IP 範囲とタグの設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="97bbe-252">ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスを個人用に設定します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="97bbe-253">次を使用してシャドウ IT を提供するクラウド検出を設定します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="97bbe-254">Microsoft Defender for Endpoints。</span><span class="sxs-lookup"><span data-stu-id="97bbe-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="97bbe-255">Zscaler</span><span class="sxs-lookup"><span data-stu-id="97bbe-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="97bbe-256">iboss。</span><span class="sxs-lookup"><span data-stu-id="97bbe-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="97bbe-257">アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使った</a> おすすめアプリの接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="97bbe-258">条件付きアクセス ポータルと Cloud App Security ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="97bbe-259">Cloud App Security および Cloud Discovery ダッシュボードの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="97bbe-260">組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="97bbe-261">アプリ タグとカテゴリの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="97bbe-262">アプリの許可と削除。</span><span class="sxs-lookup"><span data-stu-id="97bbe-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="97bbe-263">アクティビティとファイル ログの使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="97bbe-264">OAuth アプリの管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="97bbe-265">Microsoft 365 Defender ポータルでのインシデントの相関関係について。</span><span class="sxs-lookup"><span data-stu-id="97bbe-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="97bbe-266">以下を除き、CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 個の使用事例 (最大 6 個のポリシーの作成または更新を含む) の構成支援を提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="97bbe-267">サービスとしてのインターネット (IaaS) 環境 (#18)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="97bbe-268">ユーザーアクティビティを監視して、IaaS 環境 (#19) の脅威から保護します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="97bbe-269"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="97bbe-270">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="97bbe-271">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="97bbe-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="97bbe-272">Docker またはログ コレクターを使用して、継続的レポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="97bbe-273">詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、CASB の上位 20 の</a> 使用事例を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="97bbe-274">クラウド探索スナップショット レポートの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="97bbe-275">ブロック スクリプトを使用したアプリの使用のブロック。</span><span class="sxs-lookup"><span data-stu-id="97bbe-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="97bbe-276">カスタム アプリの接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="97bbe-277">サードパーティの ID プロバイダー (ISP) およびデータ損失防止 (DLP) プロバイダーとの統合。</span><span class="sxs-lookup"><span data-stu-id="97bbe-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="97bbe-278">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="97bbe-279">Microsoft Power Automate プレイブックを含む自動調査と修復。</span><span class="sxs-lookup"><span data-stu-id="97bbe-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="97bbe-280">セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="97bbe-281">概念実証としての Cloud App Discovery の展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="97bbe-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-283">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="97bbe-284">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-285">エンドポイントをセキュリティ保護するテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-286">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-287">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-288">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-289">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="97bbe-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-290">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-291">展開ガイダンス、構成支援、および次の教育について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-292">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-293">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="97bbe-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-294">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="97bbe-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-295">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="97bbe-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-296">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-297">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="97bbe-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-298">シミュレーションとチュートリアル (プラクティス シナリオ、偽のマルウェア、自動調査など) の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-299">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="97bbe-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-300">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="97bbe-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-301">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-302">次のオペレーティング システム:</span><span class="sxs-lookup"><span data-stu-id="97bbe-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-303">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="97bbe-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-304">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="97bbe-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-305">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="97bbe-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-306">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="97bbe-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-307">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="97bbe-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-308">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="97bbe-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="97bbe-309">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="97bbe-310"></li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-311">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-312">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-313">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="97bbe-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-314">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="97bbe-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-315">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="97bbe-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-316">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="97bbe-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-317">Linux。</span><span class="sxs-lookup"><span data-stu-id="97bbe-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-318">モバイル デバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-319">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-320">オフライン通信用のプロキシ サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-321">ダウンレベルの Configuration Manager のインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-322">Azure Security Center へのサーバーのオンボーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-323">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-324">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-325">Intune による手動による展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-326">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="97bbe-327">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-328">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-329">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-330">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="97bbe-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-331">アプリの制御。</span><span class="sxs-lookup"><span data-stu-id="97bbe-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-332">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="97bbe-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-333">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-334">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-335">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-336">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-337">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-338">Kusto クエリの使用または作成に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="97bbe-339">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="97bbe-340"><strong>Id 用 Microsoft Defender </strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="97bbe-341">Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="97bbe-342">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="97bbe-343">Id 用の Defender のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="97bbe-344">Id 用 Defender を Active Directory に接続する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="97bbe-345">ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。次の機能があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="97bbe-346">リソース容量計画用のサイズ変更ツールの実行。</span><span class="sxs-lookup"><span data-stu-id="97bbe-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="97bbe-347">監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="97bbe-348">ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャおよび解析するセンサーの展開。次の機能が含されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="97bbe-349">センサー パッケージのダウンロード。</span><span class="sxs-lookup"><span data-stu-id="97bbe-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="97bbe-350">センサーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="97bbe-351">ドメイン コントローラーにサイレント モードでセンサーをインストールします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="97bbe-352">複数フォレスト環境へのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="97bbe-353">Id 用 Defender を Microsoft Cloud App Security と統合する (Cloud App Security のライセンスは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="97bbe-354">展開ガイダンス、構成支援、および次の教育を提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="97bbe-355">"ノイズ" を低減するために環境を調整します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="97bbe-356">ID セキュリティの状況評価レポートについて。</span><span class="sxs-lookup"><span data-stu-id="97bbe-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="97bbe-357">ユーザーの調査優先度スコアとユーザーの調査ランク付けレポートについて。</span><span class="sxs-lookup"><span data-stu-id="97bbe-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="97bbe-358">非アクティブなユーザー レポートについて。</span><span class="sxs-lookup"><span data-stu-id="97bbe-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="97bbe-359">侵害されたアカウントでの修復オプションの提供。</span><span class="sxs-lookup"><span data-stu-id="97bbe-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="97bbe-360">Advanced Threat Analytics (ATA) から Defender for Identity への移行を容易にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="97bbe-361"><strong>次に示すのはスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="97bbe-362">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="97bbe-363">継続的な管理、脅威への対応、修復。</span><span class="sxs-lookup"><span data-stu-id="97bbe-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="97bbe-364">Id センサー用の Defender の展開。次の機能が含されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="97bbe-365">手動による容量計画。</span><span class="sxs-lookup"><span data-stu-id="97bbe-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="97bbe-366">スタンドアロンの容量でのセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="97bbe-367">ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用したセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="97bbe-368">サード パーティ製のツールを使用したセンサーの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="97bbe-369">Web プロキシ接続を介して Defender for Identity クラウド サービスに接続する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="97bbe-370">honeytoken の作成と管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="97bbe-371">展開に関するガイダンスまたは教育:</span><span class="sxs-lookup"><span data-stu-id="97bbe-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="97bbe-372">さまざまなアラートの種類と監視対象アクティビティを修復または解釈します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="97bbe-373">ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。</span><span class="sxs-lookup"><span data-stu-id="97bbe-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="97bbe-374">脅威または高度な検索。</span><span class="sxs-lookup"><span data-stu-id="97bbe-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="97bbe-375">インシデント対応。</span><span class="sxs-lookup"><span data-stu-id="97bbe-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="97bbe-376">Defender for Identity 用のセキュリティ警告ラボ チュートリアルを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="97bbe-377">指定されたセンサーを介してセキュリティ警告をサーバーに送信することで、Defender for Identity が疑わしいアクティビティを検出した場合に通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="97bbe-378">セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行し、特定のコンピューター上のローカル管理者を識別するための Id 用 Defender の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="97bbe-379">VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="97bbe-380">セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="97bbe-381">概念実証としての ID センサー用の Defender の展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="97bbe-382">展開された Active Directory。</span><span class="sxs-lookup"><span data-stu-id="97bbe-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-383">Id センサー用 Defender をインストールする予定のドメイン コントローラーは、Defender for Identity クラウド サービスへのインターネット接続を持っています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="97bbe-384">ファイアウォールとプロキシは、Defender for Identity クラウド サービスと通信するために開いている必要があります (\*.atp.azure.com ポート 443 が開いている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="97bbe-385">次のいずれかのドメイン コントローラーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="97bbe-386">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="97bbe-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="97bbe-387">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="97bbe-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="97bbe-388">Windows Server 2012 R2。</span><span class="sxs-lookup"><span data-stu-id="97bbe-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="97bbe-389">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="97bbe-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="97bbe-390">WINDOWS Server 2019 と KB4487044 (OS ビルド 17763.316)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="97bbe-391"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-392">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-393">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-394">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-395">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-396">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-397">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-398">Advanced eDiscovery。</span><span class="sxs-lookup"><span data-stu-id="97bbe-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="97bbe-399">

  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="97bbe-400">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="97bbe-401">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="97bbe-402">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="97bbe-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="97bbe-403">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="97bbe-404">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="97bbe-405">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="97bbe-406">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-407"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-408">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-409">データの分類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-410">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-411">秘密度ラベルの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-412">感度ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-413">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-414">トレーニング可能な分類子。</span><span class="sxs-lookup"><span data-stu-id="97bbe-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-415">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-416">ポリシーを使用したラベルの発行 (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-417">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-418">Windows 10 デバイス用のエンドポイント DLP ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="97bbe-419">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="97bbe-420">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-420">Customer key.</span></span></li>
<li><span data-ttu-id="97bbe-421">機密情報の種類用のカスタム正規表現 (RegEx) 開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="97bbe-422">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="97bbe-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="97bbe-423">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="97bbe-424">
<strong>注:</strong> 詳細については、「Enterprise <strong> Mobility </strong> + Security の Azure Information <a href="#enterprise-mobility--security">Protection」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="97bbe-425">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-427">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="97bbe-428">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="97bbe-429">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="97bbe-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-430">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="97bbe-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-431">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-432">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-433">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-434">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-435">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="97bbe-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-436">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-437">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-438">Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-439">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-440">組織内に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、および VPN プロファイルの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-441">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-442">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="97bbe-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-443">リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-444">Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-445">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-446">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-446">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-447">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="97bbe-447">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="97bbe-448">次に関するアプリ保護ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-448">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-449">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-449">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-450">管理対象アプリの条件付きアクセス ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-450">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-451">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-451">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-452">管理対象アプリの利用状況レポートの使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-452">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-453">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-453">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="97bbe-454">
  <strong>注</strong>: 従来の PC 管理は、2020 年 10 月 15 日以降サポートされなくなりました。</span><span class="sxs-lookup"><span data-stu-id="97bbe-454">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="97bbe-455"></li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-455"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="97bbe-456">Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-456">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="97bbe-457">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-457">The exact steps depend on your source environment.</span></span> <span data-ttu-id="97bbe-458">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-458">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="97bbe-459">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="97bbe-459">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-460">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-460">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-461">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-461">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-462">ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-462">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-463">MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-463">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-464">クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="97bbe-464">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-465">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-465">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-466">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-466">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="97bbe-467"><strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-467"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="97bbe-468">Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-468">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="97bbe-469">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-469">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-470">Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-470">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-471">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-471">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-472">iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-472">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-473">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-473">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-474">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-474">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-475">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-475">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="97bbe-476"><strong>注</strong>: FastTrack では、Exchange モバイル デバイス メールボックス ポリシーを使用した iOS および Android 用の Outlook のセキュリティ保護はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-476"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="97bbe-477">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="97bbe-478">IT 管理者は、Intune を使用したワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャが実稼働環境で既に動作している必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-478">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="97bbe-479"><strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-479"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="97bbe-480"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-480"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="97bbe-481">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="97bbe-482"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-482"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="97bbe-483"><strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-483"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="97bbe-484">購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。</span><span class="sxs-lookup"><span data-stu-id="97bbe-484">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="97bbe-485">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="97bbe-486"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-486"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="97bbe-487">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-487">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="97bbe-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-489">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-489">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-490">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-490">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-491">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-491">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-492">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-492">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-493">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="97bbe-493">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-494">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-494">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="97bbe-495">Office 365</span><span class="sxs-lookup"><span data-stu-id="97bbe-495">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-496"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-496"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-497"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-497"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-498"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-498"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="97bbe-499"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-499"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-500">Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-500">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="97bbe-501">正確な手順は、ソース環境とメール移行計画によって異なります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-501">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="97bbe-502">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-502">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-503">Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-503">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-504">メール交換 (MX) レコードの参照を 365 Officeする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-504">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-505">サブスクリプション サービスOffice 365 ATP 機能のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-505">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="97bbe-506">詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-506">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-p128">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-p128">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="97bbe-p129">サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-p129">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="97bbe-511">
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、Information Rights Managed (IRM) 電子メールをオンプレミスのメールボックスから対応する Exchange Online メールボックスに移行します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-511">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="97bbe-512">移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-512">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="97bbe-513">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-513">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-514">必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys Identified Mail (DKIM)、ドメイン ベースのメッセージ認証、レポートと適合 (DMARC) および MX レコード (必要に応じて) を含む DNS のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-514">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-515">ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-515">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-516">ソースのメッセージング環境から Office 365 にメール移行を実行。</span><span class="sxs-lookup"><span data-stu-id="97bbe-516">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-517">メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-517">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="97bbe-518">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-518">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="97bbe-519">Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-519">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="97bbe-520">ソース環境には、次のいずれかの最小レベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-520">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-521">Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="97bbe-521">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-522">1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="97bbe-522">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-523">単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-523">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-524">複数地域機能の詳細については、「Exchange Online の複数地域機能」 <a href="https://go.microsoft.com/fwlink/?linkid=872776">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-524">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-525">Project for Office 365、Outlook for Windows、iOS および Android 用の Outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 Office</a>のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-525">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-526"><strong>Microsoft 情報ガバナンス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-526"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-527">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-527">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-528">保持ラベルとポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-528">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-529">レコード管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-529">Records management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-530">削除ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-530">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-531">通信コンプライアンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-531">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-532">インサイダー リスクの管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-532">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-533">Advanced eDiscovery。</span><span class="sxs-lookup"><span data-stu-id="97bbe-533">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="97bbe-534">

  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-534">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="97bbe-535">レコード管理ファイル計画の開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-535">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="97bbe-536">データ コネクタ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-536">Data connectors.</span></span></li>
<li> <span data-ttu-id="97bbe-537">情報バリア。</span><span class="sxs-lookup"><span data-stu-id="97bbe-537">Information barriers.</span></span></li>
<li> <span data-ttu-id="97bbe-538">特権アクセス管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-538">Privileged access management.</span></span></li>
<li> <span data-ttu-id="97bbe-539">SharePoint での情報アーキテクチャの開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-539">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="97bbe-540">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-540">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="97bbe-541">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-541">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-542"><strong>Microsoft 情報保護</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-542"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-543">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-543">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-544">データの分類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-544">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-545">機密情報の種類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-545">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-546">秘密度ラベルの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-546">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-547">感度ラベルの適用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-547">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-548">統合されたラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-548">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-549">トレーニング可能な分類子。</span><span class="sxs-lookup"><span data-stu-id="97bbe-549">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-550">コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-550">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-551">ポリシーを使用したラベルの発行 (手動および自動)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-551">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-552">Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-552">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-553">Windows 10 デバイス用のエンドポイント DLP ポリシーの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-553">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="97bbe-554">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-554">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="97bbe-555">顧客キー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-555">Customer key.</span></span></li>
<li><span data-ttu-id="97bbe-556">機密情報の種類用のカスタム正規表現 (RegEx) 開発。</span><span class="sxs-lookup"><span data-stu-id="97bbe-556">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="97bbe-557">キーワード ディクショナリの作成または変更。</span><span class="sxs-lookup"><span data-stu-id="97bbe-557">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="97bbe-558">カスタム スクリプトとコーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-558">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="97bbe-559">
<strong>注:</strong> 詳細については、「Enterprise <strong> Mobility </strong> + Security の Azure Information <a href="#enterprise-mobility--security">Protection」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-559">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="97bbe-560">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-560">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-561"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-561"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-562">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-562">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-563">Teams をサポートするために Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD要件を確認します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-563">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-564">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-564">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-565">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-565">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-566">Teams が Office 365 テナントで有効であることの確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-566">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-567">ユーザーのライセンスの有効化と無効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-567">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-568">Teams のネットワーク評価:</span><span class="sxs-lookup"><span data-stu-id="97bbe-568">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-569">ポートとエンドポイントの確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-569">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-570">接続品質の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-570">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-571">帯域幅の推定値。</span><span class="sxs-lookup"><span data-stu-id="97bbe-571">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="97bbe-572">Teams アプリ ポリシー (Teams Web アプリ、Teams デスクトップ アプリ、および iOS および Android 用 Teams アプリ) の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-572">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-573">該当する場合は、以下のガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-573">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-574">Microsoft Teams Room Devices:</span><span class="sxs-lookup"><span data-stu-id="97bbe-574">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="97bbe-575"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-575">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-576">認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-576">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-577">電話会議を有効にする:</span><span class="sxs-lookup"><span data-stu-id="97bbe-577">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="97bbe-578">会議ブリッジの既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-578">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-579">ライセンスを持つユーザーへの会議ブリッジの割り当て。</span><span class="sxs-lookup"><span data-stu-id="97bbe-579">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="97bbe-580">電話システム:</span><span class="sxs-lookup"><span data-stu-id="97bbe-580">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-581">Cloud Voice の既定の設定のための組織のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-581">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-582">通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):</span><span class="sxs-lookup"><span data-stu-id="97bbe-582">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-583">ライセンスを持つユーザーへの番号の割り当て。</span><span class="sxs-lookup"><span data-stu-id="97bbe-583">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-584">ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-584">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-585">999 件を超える電話番号の移植サービス リクエスト (SR) サポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-585">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-586">ダイレクト ルーティングのガイダンス:</span><span class="sxs-lookup"><span data-stu-id="97bbe-586">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-587">パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-587">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="97bbe-588">セッション ボーダー コントローラー (SBC) 構成レビュー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-588">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="97bbe-589">ダイヤル プランの構成に関するリモート アシスタンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-589">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="97bbe-590">ボイス ルート構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-590">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="97bbe-591">メディア バイパスとローカル メディアの最適化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-591">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="97bbe-592">Teams ライブ イベントの有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-592">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-593">組織のセットアップと Microsoft Stream への統合。</span><span class="sxs-lookup"><span data-stu-id="97bbe-593">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-594">Skype for Business から Teams への移行に関するガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-594">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="97bbe-595">Azure AD 365 で有効Office ID。</span><span class="sxs-lookup"><span data-stu-id="97bbe-595">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-596">SharePoint Online に対してユーザーが有効になっている。</span><span class="sxs-lookup"><span data-stu-id="97bbe-596">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-597">Exchange メールボックスが存在する (Exchange ハイブリッド構成ではオンラインとオンプレミス)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-597">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-598">Office 365 グループに対して有効になっている。</span><span class="sxs-lookup"><span data-stu-id="97bbe-598">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="97bbe-599">
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスで割り当てられていない場合、ユーザーは OneDrive for Business ストレージを 365 Officeしません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-599">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="97bbe-600">ファイル共有はチャネルで引き続き機能しますが、ユーザーは OneDrive for Business ストレージを使用せずにチャット内のファイルを Office 365 で共有できます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-600">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="97bbe-601">Teams はオンプレミスの SharePoint をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-601">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="97bbe-602">
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する状態です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-602">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="97bbe-603">オンプレミスにホームのメールボックスを持つユーザーの ID は、Azure Office Connect を介して Office 365 ディレクトリに同期ADがあります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-603">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="97bbe-604">これらの Exchange ハイブリッドのお客様の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-604">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="97bbe-605">Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-605">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-607">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-607">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-608">安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-608">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-609">自動化、調査、応答の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-609">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-610">攻撃シミュレータの使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-610">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-611">レポート作成と脅威分析。</span><span class="sxs-lookup"><span data-stu-id="97bbe-611">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-612">一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-612">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-613"><strong>iOS 版および Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-613"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-614">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-614">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-615">Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。</span><span class="sxs-lookup"><span data-stu-id="97bbe-615">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-616">アカウントの構成、および Exchange Online メールボックスへのアクセス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-616">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-617">Outlook モバイルのセキュリティ保護 (詳細については <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">、「Exchange Online</a> での iOS および Android 用の Outlook のセキュリティ保護」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-617">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="97bbe-618">Azure AD 365 で有効Office ID。</span><span class="sxs-lookup"><span data-stu-id="97bbe-618">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-619">Exchange Online が構成され、ライセンスが割り当てられている。</span><span class="sxs-lookup"><span data-stu-id="97bbe-619">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-620"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-620"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-621">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-621">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-622">Power BI ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="97bbe-622">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-623">Power BI Desktop アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-623">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-624">Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-624">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-625"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-625"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-626">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-626">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-627">Project Online が依存している基本的な SharePoint の機能の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-627">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-628">テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-628">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-629">エンタープライズ リソース共有元 (ERP) のセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-629">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-630">最初のプロジェクトの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-630">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-631">Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-631">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-632"><strong>Project Online Professional および Premium</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-632"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-633">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-634">展開の問題への対応。</span><span class="sxs-lookup"><span data-stu-id="97bbe-634">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-635">Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。</span><span class="sxs-lookup"><span data-stu-id="97bbe-635">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-636">クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-636">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-637">Office 365 展開ツールを使用した更新設定の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-637">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-638">Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-638">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-639">Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-639">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-640">Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-640">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-641"><strong>Sharepoint Online と OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-641"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-642">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-642">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-643">DNS の設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-643">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-644">ファイアウォール ポートの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-645">ユーザーとライセンスのプロビジョニング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-645">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="97bbe-646">SharePoint Online 管理者のサイト作成の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-646">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="97bbe-647">サイト コレクションのプランニング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-647">Planning site collections.</span></span></li>
<li><span data-ttu-id="97bbe-648">コンテンツのセキュリティ保護および権限の管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-648">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="97bbe-649">SharePoint Online 機能の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-649">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="97bbe-650">ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-650">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-651">移行方法。</span><span class="sxs-lookup"><span data-stu-id="97bbe-651">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-652">OneDrive for Business の追加のガイダンスは、SharePoint のバージョンに応じて提供されます。次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-652">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-653">統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-653">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-654">SharePoint Online 2013 SP1 のインストール (該当する場合)、同期と ID の要件の計画と実装、OneDrive for Business 同期クライアントの識別。</span><span class="sxs-lookup"><span data-stu-id="97bbe-654">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-655">すべてのユーザーに対する単一のロールアウト (または段階的なロールアウト) の計画と実装。</span><span class="sxs-lookup"><span data-stu-id="97bbe-655">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-656">ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に適用) を行い、対象ユーザーを設定して OneDrive へのアクセスを制御します (SharePoint Online 2013 に適用)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-656">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="97bbe-657">OneDrive への既知のフォルダーのリダイレクトまたは移動。</span><span class="sxs-lookup"><span data-stu-id="97bbe-657">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="97bbe-658">OneDrive for Business クライアント同期の展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-658">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="97bbe-659">
  <strong>データ移行</strong>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-659">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="97bbe-660">Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-660">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="97bbe-661"><strong>SharePoint ハイブリッドの場合:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-661"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-662">SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-662">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="97bbe-663">
  <strong>注:</strong> セルフサービス サイト作成は、SharePoint 2013 を実行するオンプレミス サーバーのスコープではありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-663">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="97bbe-664">SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。</span><span class="sxs-lookup"><span data-stu-id="97bbe-664">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="97bbe-665">
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードの対象ではありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-665">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="97bbe-666">Microsoft パートナー <a href="https://go.microsoft.com/fwlink/?linkid=2080150">にお問い合</a> わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-666">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="97bbe-667">詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベル」を参照してください</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-667">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="97bbe-668">
  <strong>注:</strong>複数地域機能の詳細については、「OneDrive の複数地域機能」および「SharePoint Online in <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365」</a>を参照してください<em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-668">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-669"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-669"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="97bbe-670">エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-670">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="97bbe-671">オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</span><span class="sxs-lookup"><span data-stu-id="97bbe-671">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="97bbe-672">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="97bbe-672">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-673"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-673"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-674"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-674"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-675"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-675"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="97bbe-676"><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-676"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-677">次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-677">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="97bbe-678">

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-678">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="97bbe-679">Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス によるパスワードリセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-679">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-680">Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-680">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-681">Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-681">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-682">Azure AD Password Protection で脆弱なパスワードの使用を検出し、ブロックします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-682">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-683">Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-683">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-684">Azure Identity Protection によるリスクベースの検出と修復の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-684">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-685">カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-685">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-686">Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-686">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-687">役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-687">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-688">ハイブリッド Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-688">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-689">Azure ADの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-689">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="97bbe-690">
  
<strong>監視とレポート</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-690">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-691">Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-691">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-692">
  
<strong>ガバナンス</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-692">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-693">Azure の権利管理ADを使用して、Azure の ID とアクセス ライフサイクルAD管理します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-693">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="97bbe-694">Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-694">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-695">Azure AD利用規約の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-695">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-696">Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-696">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-697">
  
<strong>自動化と効率性 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-697">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-698">Azure AD SSPR を有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-698">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="97bbe-699">ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-699">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-700">Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-700">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-701">Azure ADグループを有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-701">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-702">コレクションを使用して、マイ アプリ ポータルでアプリを整理する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-702">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="97bbe-703">オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD および Azure AD Premium 用に準備されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-703">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="97bbe-704"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-704"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="97bbe-705">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-705">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-706">テナントのアクティブ化と構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-706">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-707">ラベルおよびポリシーの作成と設定。</span><span class="sxs-lookup"><span data-stu-id="97bbe-707">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-708">ドキュメントへの情報保護の適用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-708">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-709">Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-709">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-710">Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。</span><span class="sxs-lookup"><span data-stu-id="97bbe-710">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-711">Exchange Online のメール フロー ルールを使用した、転送中メールの監視。</span><span class="sxs-lookup"><span data-stu-id="97bbe-711">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-712">Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-712">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="97bbe-713">お客様の前提条件となる責任は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-713">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-714">スキャンするファイル共有の場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="97bbe-714">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-715">承認された分類。</span><span class="sxs-lookup"><span data-stu-id="97bbe-715">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="97bbe-716">キー管理に関する規制上の制限または要件を理解する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-716">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-717">Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。</span><span class="sxs-lookup"><span data-stu-id="97bbe-717">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="97bbe-718">分類と保護用に構成されたラベル。</span><span class="sxs-lookup"><span data-stu-id="97bbe-718">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="97bbe-719">Azure Information Protection スキャナーのすべての前提条件が満たされています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-719">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="97bbe-720">詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-720">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="97bbe-721">ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-721">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="97bbe-722">詳細については、以下を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-722">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="97bbe-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </span><span class="sxs-lookup"><span data-stu-id="97bbe-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="97bbe-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="97bbe-725">ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-725">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="97bbe-726">展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。</span><span class="sxs-lookup"><span data-stu-id="97bbe-726">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="97bbe-727"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-727"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-728">アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-728">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="97bbe-729">具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-729">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="97bbe-730">以下の手順が含まれる可能性があります:</span><span class="sxs-lookup"><span data-stu-id="97bbe-730">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-731">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="97bbe-731">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-732">オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-732">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-733">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-733">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-734">次の管理ニーズに基づいて MDM 機関を構成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-734">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-735">Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-735">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-736">以下の MDM ガイダンスの提供:</span><span class="sxs-lookup"><span data-stu-id="97bbe-736">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-737">MDM 管理ポリシーの検証に使用するテストグループの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-737">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-738">以下のような、MDM 管理ポリシーとサービスの構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-738">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-739">Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-739">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-740">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-740">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-741">組織内に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、および VPN プロファイルの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-741">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-742">Intune データ ウェアハウスへの接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-742">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-743">以下との Intune の統合:</span><span class="sxs-lookup"><span data-stu-id="97bbe-743">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-744">リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-744">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-745">Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-745">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-746">通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-746">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-747">Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-747">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-748">サポートされている各プラットフォームのデバイスの Intune への登録。</span><span class="sxs-lookup"><span data-stu-id="97bbe-748">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="97bbe-749">次に関するアプリ保護ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-749">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-750">サポートされている各プラットフォームでのアプリ保護ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-750">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-751">管理対象アプリの条件付きアクセス ポリシーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-751">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-752">前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-752">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-753">管理対象アプリの利用状況レポートの使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-753">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-754">従来の PC 管理から Intune MDM への移行ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-754">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="97bbe-755">
  <strong>注</strong>: 従来の PC 管理は、2020 年 10 月 15 日以降サポートされなくなりました。</span><span class="sxs-lookup"><span data-stu-id="97bbe-755">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="97bbe-756"></li>
</ul>
  
<strong>クラウド接続</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-756"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="97bbe-757">Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-757">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="97bbe-758">具体的な手順はソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-758">The exact steps depend on your source environment.</span></span> <span data-ttu-id="97bbe-759">手順には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-759">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="97bbe-760">エンド ユーザーのライセンス認証。</span><span class="sxs-lookup"><span data-stu-id="97bbe-760">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-761">オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-761">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-762">Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-762">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-763">ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-763">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-764">MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-764">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-765">クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。</span><span class="sxs-lookup"><span data-stu-id="97bbe-765">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-766">Intune に切り替えることを希望する、サポートされているワークロードの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-766">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-767">Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-767">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="97bbe-768"><strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-768"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="97bbe-769">Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-769">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="97bbe-770">次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-770">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-771">Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-771">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-772">セットアップに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-772">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-773">iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-773">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-774">アプリ保護ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-774">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-775">条件付きアクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-775">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-776">アプリ構成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-776">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="97bbe-777"><strong>注</strong>: FastTrack では、Exchange モバイル デバイス メールボックス ポリシーを使用した iOS および Android 用の Outlook のセキュリティ保護はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-777"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="97bbe-778">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="97bbe-779">IT 管理者は、Intune を使用したワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャが実稼働環境で既に動作している必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-779">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="97bbe-780"><strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-780"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="97bbe-781"><strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-781"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="97bbe-782">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-782">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="97bbe-783"><strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-783"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="97bbe-784"><strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-784"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="97bbe-785">購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。</span><span class="sxs-lookup"><span data-stu-id="97bbe-785">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="97bbe-786">サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="97bbe-787"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-787"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="97bbe-788">IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-788">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="97bbe-789">Windows 10</span><span class="sxs-lookup"><span data-stu-id="97bbe-789">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-790"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-790"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-791"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-791"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-792"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-792"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="97bbe-793"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-793"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-794">Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに関するガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-794">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="97bbe-795">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-795">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-796">Windows 10 の目的を理解する。</span><span class="sxs-lookup"><span data-stu-id="97bbe-796">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-797">ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-797">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-798">Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-798">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-799">Windows 10 アプリを評価するための推奨オプション。</span><span class="sxs-lookup"><span data-stu-id="97bbe-799">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-800">Desktop Analytics 展開計画の作成による Desktop Analytics とガイダンスの使用の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-800">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-801">Configuration Manager の Office 365 準備ダッシュボード、またはスタンドアロンの Toolkit for Office を活用した Microsoft 365 アプリの互換性評価と、Microsoft 365 アプリの展開のサポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-801">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-802">展開を成功するためにソース環境を最小要件に満たするために必要な操作に関する修復チェックリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-802">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-803">必要なデバイス ハードウェア要件を満たす場合は、既存のデバイスの Windows 10 Enterprise へのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-803">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-804">既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-804">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="97bbe-805">FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-805">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="97bbe-806">また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-806">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-807">Windows 10 の展開の一部として Configuration Manager を使用した Microsoft 365 アプリの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-807">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="97bbe-808">既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するのに役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-808">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="97bbe-809">
  <strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-809">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-810">Configuration Manager の Current Branch へのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="97bbe-810">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-811">Windows 10 展開用のカスタム画像の作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-811">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-812">Windows 10 の展開用の展開スクリプトの作成とサポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-812">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-813">Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。</span><span class="sxs-lookup"><span data-stu-id="97bbe-813">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-814">Windows 10 のセキュリティ機能の有効化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-814">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-815">Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-815">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-816">Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-816">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-817">ユーザー状態移行ツール (USMT) の使用。</span><span class="sxs-lookup"><span data-stu-id="97bbe-817">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-818">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-818">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="97bbe-819">PC のアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-819">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-820">ソース OS: Windows 7 Enterprise Professional、Windows 8.1 Enterprise または Professional。</span><span class="sxs-lookup"><span data-stu-id="97bbe-820">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-821">デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。</span><span class="sxs-lookup"><span data-stu-id="97bbe-821">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-822">ターゲット OS: Window 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="97bbe-822">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="97bbe-823">インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-823">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-824">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="97bbe-824">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-825">Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-825">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="97bbe-826">詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-826">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="97bbe-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-828">Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-828">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="97bbe-829">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-829">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-830">エンドポイントをセキュリティ保護するテクノロジの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-830">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-831">エンドポイント保護とデバイス制限プロファイルの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-831">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-832">OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-832">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-833">Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-833">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-834">ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。</span><span class="sxs-lookup"><span data-stu-id="97bbe-834">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-835">オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-835">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-836">展開ガイダンス、構成支援、および次の教育について説明します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-836">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-837">脅威と脆弱性の管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-837">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-838">攻撃面の縮小。</span><span class="sxs-lookup"><span data-stu-id="97bbe-838">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-839">次世代の保護。</span><span class="sxs-lookup"><span data-stu-id="97bbe-839">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-840">エンドポイントの検出および応答。</span><span class="sxs-lookup"><span data-stu-id="97bbe-840">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-841">調査と修復の自動化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-841">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-842">セキュア スコア。</span><span class="sxs-lookup"><span data-stu-id="97bbe-842">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-843">シミュレーションとチュートリアル (プラクティス シナリオ、偽のマルウェア、自動調査など) の確認。</span><span class="sxs-lookup"><span data-stu-id="97bbe-843">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-844">レポート機能と脅威分析機能の概要。</span><span class="sxs-lookup"><span data-stu-id="97bbe-844">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-845">Office 365 の ATP と Microsoft Defender ATP の統合。</span><span class="sxs-lookup"><span data-stu-id="97bbe-845">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-846">Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-846">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-847">次のオペレーティング システム:</span><span class="sxs-lookup"><span data-stu-id="97bbe-847">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-848">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="97bbe-848">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-849">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="97bbe-849">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-850">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="97bbe-850">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-851">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="97bbe-851">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-852">Windows Server Semi-Annual チャネル (SAC) バージョン 1803。</span><span class="sxs-lookup"><span data-stu-id="97bbe-852">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-853">macOS バージョン 10.13、10.14、および 10.15。</span><span class="sxs-lookup"><span data-stu-id="97bbe-853">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="97bbe-854">
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-854">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="97bbe-855"></li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-855"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-856">お客様の修復アクティビティのプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-856">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-857">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-857">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-858">継続的な管理と脅威の対処。</span><span class="sxs-lookup"><span data-stu-id="97bbe-858">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-859">次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:</span><span class="sxs-lookup"><span data-stu-id="97bbe-859">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-860">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="97bbe-860">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-861">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="97bbe-861">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-862">Linux。</span><span class="sxs-lookup"><span data-stu-id="97bbe-862">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-863">モバイル デバイス (Android および iOS)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-863">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-864">サーバーのオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-864">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-865">オフライン通信用のプロキシ サーバーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-865">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-866">ダウンレベルの Configuration Manager のインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-866">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-867">Azure Security Center へのサーバーのオンボーディング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-867">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-868">Configuration Manager によって管理されていないサーバー。</span><span class="sxs-lookup"><span data-stu-id="97bbe-868">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-869">macOS のオンボーディングと構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-869">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-870">Intune による手動による展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-870">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-871">JAMF ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-871">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="97bbe-872">その他のモバイル デバイス管理 (MDM) 製品ベースの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-872">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-873">手動による展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-873">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-874">次の攻撃面の縮小機能の構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-874">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-875">ハードウェア ベースの分離。</span><span class="sxs-lookup"><span data-stu-id="97bbe-875">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-876">アプリの制御。</span><span class="sxs-lookup"><span data-stu-id="97bbe-876">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-877">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="97bbe-877">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-878">ネットワーク ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="97bbe-878">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="97bbe-879">Microsoft 脅威エキスパートの登録または構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-879">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-880">API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-880">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-881">Microsoft 脅威保護 (MTP) の登録または構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-881">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-882">高度な検出に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-882">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-883">Kusto クエリの使用または作成に関するトレーニングまたはガイダンス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-883">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="97bbe-884">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-884">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="97bbe-885">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="97bbe-885">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-886"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-886"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-887"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-887"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-888"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-888"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="97bbe-889"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-889"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="97bbe-890">Windows Virtual Desktop (デスクトップとアプリの仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-890">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="97bbe-891">Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-891">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="97bbe-892">以下に関するリモート ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-892">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="97bbe-893">以下を使用して、Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows Virtual Desktop 環境を展開します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-893">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="97bbe-894">Azure Marketplace イメージ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-894">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="97bbe-895">共有イメージ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-895">Shared image.</span></span></li>
<li><span data-ttu-id="97bbe-896">Office展開Toolkit (ODT)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-896">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="97bbe-897">FSLogix の構成:</span><span class="sxs-lookup"><span data-stu-id="97bbe-897">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="97bbe-898">プロファイル コンテナーを使用した FSLogix エージェントの展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-898">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="97bbe-899">新しいコンテナーを使用した FSLogix エージェントOffice展開します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-899">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="97bbe-900">コンテンツの除外を使用した FSLogix フォルダーの構成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-900">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="97bbe-901">Microsoft Edge の展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-901">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="97bbe-902">Microsoft Teams の展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-902">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="97bbe-903">Windows Virtual Desktop クライアントを使用した接続。</span><span class="sxs-lookup"><span data-stu-id="97bbe-903">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="97bbe-904">

<strong>次に示すのはスコープ外です</strong>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-904">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="97bbe-905">お客様の Windows Virtual Desktop 展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-905">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="97bbe-906">サード パーティ製アプリの仮想化と展開。</span><span class="sxs-lookup"><span data-stu-id="97bbe-906">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="97bbe-907">カスタム画像。</span><span class="sxs-lookup"><span data-stu-id="97bbe-907">Custom images.</span></span></li>
<li><span data-ttu-id="97bbe-908">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-908">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="97bbe-909">Linux シナリオ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-909">Linux scenarios.</span></span></li>
<li><span data-ttu-id="97bbe-910">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="97bbe-910">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="97bbe-911">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-911">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="97bbe-912">次の情報が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-912">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="97bbe-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="97bbe-914">Azure ネットワーク:</span><span class="sxs-lookup"><span data-stu-id="97bbe-914">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="97bbe-915">仮想ネットワーク (VNET) の作成とサブネット化。</span><span class="sxs-lookup"><span data-stu-id="97bbe-915">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="97bbe-916">ファイアウォールとネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="97bbe-916">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="97bbe-917">VPN と ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="97bbe-917">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="97bbe-918">オンプレミスから Azure へのルーティング。</span><span class="sxs-lookup"><span data-stu-id="97bbe-918">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="97bbe-919">Windows Virtual Desktop への接続を許可するファイアウォール規則。</span><span class="sxs-lookup"><span data-stu-id="97bbe-919">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="97bbe-920">詳細については、「サポートされるリモート デスクトップ <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> クライアント」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-920">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="97bbe-921">Azure AD一般的なセットアップ:</span><span class="sxs-lookup"><span data-stu-id="97bbe-921">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="97bbe-922">ID 戦略 <i>(次の 3 つのオプションのいずれかを使用できます)。</i>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-922">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="97bbe-923">Azure の Active Directory と Azure AD Connect。</span><span class="sxs-lookup"><span data-stu-id="97bbe-923">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="97bbe-924">Azure を使用する Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-924">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="97bbe-925">Active Directory ドメイン サービス (AD DS)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-925">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="97bbe-926">App Assure</span><span class="sxs-lookup"><span data-stu-id="97bbe-926">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-927"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-927"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-928"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-928"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-929"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-929"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="97bbe-930"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-930"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="97bbe-931">App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-931">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="97bbe-932">App Assure サービスをリクエストすると、有効なアプリの問題に対して、対象のサブスクリプションを使用して追加料金を支払う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-932">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="97bbe-933">また、Windows Virtual Desktop と新しい Microsoft Edge を展開するときに互換性の問題に直面しているお客様にガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力を行います。</span><span class="sxs-lookup"><span data-stu-id="97bbe-933">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="97bbe-934">Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-934">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="97bbe-935"><strong>Windows 10 </strong> (ARM64 デバイスを含む)</span><span class="sxs-lookup"><span data-stu-id="97bbe-935"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="97bbe-936"><strong>Microsoft 365 アプリ</strong>  </span><span class="sxs-lookup"><span data-stu-id="97bbe-936"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="97bbe-937"><strong>新しい Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-937"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-938"><strong>Windows Virtual Desktop</strong> - 詳しくは <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop</a> とは」と Windows 10 Enterprise マルチセッションの FAQ <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">をご覧ください</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-938"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="97bbe-939">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-939">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-940">アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。</span><span class="sxs-lookup"><span data-stu-id="97bbe-940">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="97bbe-941">このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-941">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="97bbe-942">詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-942">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="97bbe-943">サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。</span><span class="sxs-lookup"><span data-stu-id="97bbe-943">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="97bbe-944">詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-944">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="97bbe-945">アプリのパッケージ化専用サービス。</span><span class="sxs-lookup"><span data-stu-id="97bbe-945">App packaging-only services.</span></span> <span data-ttu-id="97bbe-946">ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-946">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="97bbe-947">

<strong>お客様の責任は次のとおりです。</strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-947">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="97bbe-948">アプリ インベントリの作成。</span><span class="sxs-lookup"><span data-stu-id="97bbe-948">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="97bbe-949">Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</span><span class="sxs-lookup"><span data-stu-id="97bbe-949">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="97bbe-950">
<strong>注:</strong>  Microsoft はソース コードを変更できない。</span><span class="sxs-lookup"><span data-stu-id="97bbe-950">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="97bbe-951">ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-951">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="97bbe-952">これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-952">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="97bbe-953"><strong>Windows 10 と Microsoft 365 アプリ</strong>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-953"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-954">Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-954">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-955">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-955">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="97bbe-956">Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 アプリでも動作します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-956">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="97bbe-957">
  <strong>注:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="97bbe-957">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="97bbe-958">x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様がプレビュー <a href="https://insider.windows.com/">で利用できます</a>。</span><span class="sxs-lookup"><span data-stu-id="97bbe-958">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="97bbe-959">Windows 10 バージョン 2004 (以降) の Windows Insider 以外のお客様は <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">、OpenCL</a>および OpenGL 互換機能パックを使って ARM64 Photoshop がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="97bbe-959">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="97bbe-960">Windows Insider Program のユーザーは、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換機能パックをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-960">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="97bbe-961">
<strong>新しい Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="97bbe-961">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-962">Web アプリまたはサイトが Internet Explorer 11、サポート対象バージョンの Google Chrome、または Microsoft Edge のいずれかのバージョンで動作する場合、それらは新しい Microsoft Edge でも動作します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-962">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-963">Web は常に進化し続けるので <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">、Microsoft Edge</a>のサイト互換性に影響を与える既知の変更の公開リストを必ず確認してください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-963">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-964">
  <strong>Windows Virtual Desktop </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-964">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="97bbe-965">Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-965">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-966">Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されるアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise と Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-966">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-967">Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。</span><span class="sxs-lookup"><span data-stu-id="97bbe-967">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="97bbe-968">
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限事項は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="97bbe-968">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="97bbe-969">ハードウェアのリダイレクトの制限。</span><span class="sxs-lookup"><span data-stu-id="97bbe-969">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-970">音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="97bbe-970">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="97bbe-971">64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="97bbe-971">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="97bbe-972">新しい Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="97bbe-972">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="97bbe-973"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-973"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="97bbe-974"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-974"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="97bbe-975"><strong>ソース環境の期待</strong></span><span class="sxs-lookup"><span data-stu-id="97bbe-975"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="97bbe-976"><strong>Microsoft Edge</strong> (Windows 10 Enterprise のお客様向け)</span><span class="sxs-lookup"><span data-stu-id="97bbe-976"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="97bbe-977">Microsoft エンドポイント マネージャー (Microsoft Endpoint Configuration Manager または Intune) を使用して Windows 10 Enterprise に新しい Microsoft Edge を展開する場合のリモート展開ガイダンスと互換性のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-977">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-978">Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリの構成とアプリ ポリシーを使用)。</span><span class="sxs-lookup"><span data-stu-id="97bbe-978">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="97bbe-979">このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。</span><span class="sxs-lookup"><span data-stu-id="97bbe-979">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="97bbe-980">既存のInternet Explorerリストを使用してユーザー 設定モードを有効にする。</span><span class="sxs-lookup"><span data-stu-id="97bbe-980">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="97bbe-981">また、Internet Explorer または Google Chrome と一緒に動作する Web アプリまたはサイトを使用している場合に互換性の問題が発生した場合は、追加コストで問題を解決するためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="97bbe-981">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="97bbe-982">詳しくは <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">、「App Assure」</a> をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="97bbe-982">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="97bbe-983">

<strong>次に示すのはスコープ外です </strong>  
</span><span class="sxs-lookup"><span data-stu-id="97bbe-983">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="97bbe-984">顧客の Microsoft Edge 配置のプロジェクトの管理。</span><span class="sxs-lookup"><span data-stu-id="97bbe-984">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="97bbe-985">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="97bbe-985">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
