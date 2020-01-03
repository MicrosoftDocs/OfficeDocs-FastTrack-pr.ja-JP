---
title: 付録 A IBM Domino から Exchange Online への移行
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: IBM Domino から Exchange Online への移行には、次の段階中での処理内容を含む、いくつかの重要な側面があります。
ms.openlocfilehash: 17d7b6669dbd5f8647ee7dcf7218f898ddac59fc
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929271"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="78ab2-103">付録 A - IBM Domino から Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="78ab2-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="78ab2-104">IBM Domino から Exchange Online への移行には、次の段階中での処理内容を含む、いくつかの重要な側面があります。</span><span class="sxs-lookup"><span data-stu-id="78ab2-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="78ab2-105">開始フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="78ab2-106">評価フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="78ab2-107">修復フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="78ab2-108">有効化フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="78ab2-109">移行フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="78ab2-110">ID</span><span class="sxs-lookup"><span data-stu-id="78ab2-110">Identities</span></span>

<span data-ttu-id="78ab2-111">ID (クラウドのみ、同期済み、オンプレミスの Active Directory と統合済み) を作成して管理する責任があります。</span><span class="sxs-lookup"><span data-stu-id="78ab2-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="78ab2-112">オンボーディングの初期段階に、Domino とオンプレミスの Active Directory や Azure Active Directory の間で ID のマッピングを完了する必要があります (まだ存在しない場合)。</span><span class="sxs-lookup"><span data-stu-id="78ab2-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="78ab2-113">共存</span><span class="sxs-lookup"><span data-stu-id="78ab2-113">Coexistence</span></span>

<span data-ttu-id="78ab2-114">Office 365 用 FastTrack Center 特典はすべてのお客様に、オンプレミスの Domino 環境と Exchange Online 間の双方向メール フローを提供します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="78ab2-115">移行</span><span class="sxs-lookup"><span data-stu-id="78ab2-115">Migration</span></span>

<span data-ttu-id="78ab2-p102">Domino から Exchange Online への移行に関する FastTrack センター の標準プロセスには、Exchange Online メールボックスへの移行前に Domino データを Azure に事前設定することが含まれます。 FastTrack の移行では、FastTrack センター の担当者とお客様が、オンボーディングのさまざまな段階でアクティビティを実行する必要があります。これらのアクティビティについては、以下のセクションで説明します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="78ab2-p103">FastTrack サービスを経由して移行されるデータは、米国内または Microsoft が施設を保有する任意の場所に転送され、そこで保存され、処理される場合があります。FastTrack サービスは、特別な法律や規制要件の対象となるデータのために設計または意図されてはいません。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="78ab2-121">開始フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-121">Initiate phase</span></span>

 <span data-ttu-id="78ab2-122">**主な操作**</span><span class="sxs-lookup"><span data-stu-id="78ab2-122">**Key actions**</span></span>
  
- <span data-ttu-id="78ab2-123">Domino をソース メール プラットフォームとして識別します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="78ab2-124">FastTrack センター による移行を実行するかどうか決定します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="78ab2-125">**お客様の責任**</span><span class="sxs-lookup"><span data-stu-id="78ab2-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="78ab2-126">ソース メッセージング プラットフォームに関する基本情報を提供し、FastTrack センターによる移行を実行することを確認します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="78ab2-127">FastTrack センターの特典プロセスのチュートリアルに参加します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="78ab2-128">FastTrack サービス規約に署名します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="78ab2-129">評価フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-129">Assess phase</span></span>

 <span data-ttu-id="78ab2-130">**主な操作**</span><span class="sxs-lookup"><span data-stu-id="78ab2-130">**Key actions**</span></span>
  
- <span data-ttu-id="78ab2-131">FastTrack センター では、お客様との移行ワークショップを行っています。</span><span class="sxs-lookup"><span data-stu-id="78ab2-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="78ab2-132">移行に関するアンケートと管理ワークステーションのプロビジョニングなど、移行の前提条件を完了します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="78ab2-133">Domino の移行評価は、オンプレミスの環境で実行されます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="78ab2-134">**お客様の責任**</span><span class="sxs-lookup"><span data-stu-id="78ab2-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="78ab2-135">FastTrack センターが使う管理ワークステーションを準備し、オンボーディングと移行タスク (評価、レプリカ作成、監査、移行時の転送設定など) を管理します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="78ab2-p104">評価は、効果的な計画と迅速な移行を行う上で重要です。これは、Domino 環境への特定のアクセスが必要な移行の設計者によって実行されます。必要な管理ワークステーションのコンポーネントには、すべてのソース Domino メール サーバーと Azure Domino レプリカ ステージング サーバーにアクセスできるように構成された Notes クライアントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="78ab2-p105">管理ワークステーションとアカウントへのリモート アクセスや、評価と移行アクティビティを実行するためのアクセス許可を移行チームに提供します。これには、移行に必要な管理アクセス許可による、オンプレミスと Exchange Online での複数のアカウントのプロビジョニングが含まれます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="78ab2-p106">ファイアウォール ポートを開きます。ソース Domino メール サーバーと Azure ステージング サーバー間で送信ポートを開く必要があります。その他の通信用のポート (管理ワークステーション、ソース Domino サーバー、存在するならオンプレミスの Exchange サーバーなど) も開く必要があります。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="78ab2-p107">ソース Domino環境と Azure Domino ステージング サーバーとの間で相互証明を有効にして、レプリケーションを容易にします。相互証明タスクは、お客様の Domino 管理者と FastTrack センター の間で調整されます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="78ab2-146">Azure での移行環境の構成に必要な情報 (ツール、スクリプト、移行サーバーなど) をキャプチャする移行アンケートを完了します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="78ab2-147">Office 365 の対象メールボックスで Messaging Application Program Interface (MAPI) プロトコルが有効になっていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="78ab2-p108">一部の Office 365 プランは、MAPI プロトコルをサポートしていません。データを移行するためには、そのようなプランからのメールボックスを、移行イベントの前に MAPI をサポートするプランに変換する必要があります。それらのプランは、移行の後に元に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="78ab2-151">修復フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-151">Remediate phase</span></span>

 <span data-ttu-id="78ab2-152">**主な操作**</span><span class="sxs-lookup"><span data-stu-id="78ab2-152">**Key actions**</span></span>
  
- <span data-ttu-id="78ab2-153">FastTrack センター では、移行の評価レポートを確認し、アンケートに記載された詳細をテストします。</span><span class="sxs-lookup"><span data-stu-id="78ab2-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="78ab2-154">FastTrack センターが提案する修復項目を、自分で行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="78ab2-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="78ab2-155">**お客様の責任**</span><span class="sxs-lookup"><span data-stu-id="78ab2-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="78ab2-156">FastTrack センターが提供するガイドライン (たとえば、メール ファイルに存在しないと見なされる必要なアクセス許可を設定する) に基づいて Domino 環境を改善します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="78ab2-157">Domino メールボックスが、移行で許可されている最大サイズよりも小さいことを確認します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="78ab2-158">FastTrack は許可されている合計対象サイズの 85% までメールボックスを移行しますが、2 GB を超えるメールボックスを移行しようとすると、次のようなリスクが発生します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="78ab2-p109">移行の期間が長くなる。    </span><span class="sxs-lookup"><span data-stu-id="78ab2-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="78ab2-p110">他のメールボックスを移行するためのリソースが使われる。    </span><span class="sxs-lookup"><span data-stu-id="78ab2-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="78ab2-161">エラー率が大幅に増加する。</span><span class="sxs-lookup"><span data-stu-id="78ab2-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="78ab2-p111">移行用にメールイン データベースとアクセス制御リスト (ACL) を準備します。Exchange Online でメールイン データベースと共有メールボックスに対するアクセス許可を正常に移行するには、いくつかの修復手順を実行する必要があります。いくつかの手順は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="78ab2-165">Domino ディレクトリにある既存のメールイン データベースのエントリを削除し、新しい人物レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="78ab2-166">Office 365 Azure Active Directory に同期されており、Exchange Online の共有メールボックスでアクセス許可を設定するために使うオンプレミスの Active Directory に、メール対応ユニバーサル セキュリティ グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="78ab2-167">これにより、メールイン データベースで設定されているアクセス許可が Exchange Online の共有メールボックスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="78ab2-168">これで、新しいメッセージング システムとクライアントに関するエンド ユーザーの準備とトレーニングを開始できます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="78ab2-169">有効化フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-169">Enable phase</span></span>

 <span data-ttu-id="78ab2-170">**主な操作**</span><span class="sxs-lookup"><span data-stu-id="78ab2-170">**Key actions**</span></span>
  
- <span data-ttu-id="78ab2-171">FastTrack センター</span><span class="sxs-lookup"><span data-stu-id="78ab2-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="78ab2-172">Azure で移行環境をセットアップします。</span><span class="sxs-lookup"><span data-stu-id="78ab2-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="78ab2-173">オンプレミスの管理ワークステーションで移行ツールを構成します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="78ab2-174">自動インポート ツールを構成し、使用方法を説明します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="78ab2-175">すべての移行コンポーネントの検証を実施し、テスト移行を実行します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="78ab2-176">**お客様の責任**</span><span class="sxs-lookup"><span data-stu-id="78ab2-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="78ab2-p113">スケジューリング メールボックスの移行を担当するユーザーは、自動インポート ツールを使う方法について理解している必要があります。このツールは、FastTrack センター が移行前のアクティビティを実行するのに使うスケジューリング データベースに、移行スケジュールをインポートする場合に使います。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="78ab2-179">ユーザー スケジュールのインポート、監査レポートの分析、すべての問題の修復、問題のあるユーザー アカウントの再インポートといった、移行前のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="78ab2-p114">移行前のアクティビティは、お客様と FastTrack Center との間で調整されます。Azure への複製は、ユーザーの移行スケジュールをインポートした後に開始されます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="78ab2-p115">複製に要する時間は、データの量によって異なります。FastTrack センター は、監査を実行して移行の準備を確認します。監査結果が提供されますが、通常はそれ以降も修復が必要になります。これらの手順は、ユーザーがスケジュールした移行を行う前に開始する必要があるため、"T マイナス" アクティビティと呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="78ab2-186">移行フェーズ</span><span class="sxs-lookup"><span data-stu-id="78ab2-186">Migrate phase</span></span>

 <span data-ttu-id="78ab2-187">**主な操作**</span><span class="sxs-lookup"><span data-stu-id="78ab2-187">**Key actions**</span></span>
  
- <span data-ttu-id="78ab2-188">FastTrack センター</span><span class="sxs-lookup"><span data-stu-id="78ab2-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="78ab2-189">パイロット移行と迅速な移行を行います。</span><span class="sxs-lookup"><span data-stu-id="78ab2-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="78ab2-190">移行イベントと T マイナス アクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="78ab2-191">移行後のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="78ab2-192">**お客様の責任**</span><span class="sxs-lookup"><span data-stu-id="78ab2-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="78ab2-193">移行の 21 日前に移行スケジュールを識別しインポートします。</span><span class="sxs-lookup"><span data-stu-id="78ab2-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="78ab2-p116">移行前のアクティビティには、実際の移行日 (T-0) 前のさまざまな段階での修復やレプリカ作成の再試行が関係しているため、このタスクは重要です。一部のメールボックスを移行しているときでも、他のメールボックスでは T マイナス処理が実行されています。このため、適切な計画と調整が必要です。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="78ab2-197">T マイナス アクティビティ中に特定された問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="78ab2-198">移行アクティビティに影響を与える Domino サーバーに関する問題に対応し、修正します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="78ab2-199">今後の移行日についてエンドユーザーとコミュニケーションを取ります。</span><span class="sxs-lookup"><span data-stu-id="78ab2-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="78ab2-200">新しいメッセージング システムとクライアントについてエンド ユーザーの準備とトレーニングを実施します。</span><span class="sxs-lookup"><span data-stu-id="78ab2-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="78ab2-p117">移行後の問題を識別してレポートします。FastTrack センター は、移行 5 日後 (T+5) まで、移行後のサポートを提供します。それ以降はお客様の責任になります。メールボックスでのメール、予定表アイテム、連絡先の欠落や重複といった問題に対して、移行後のチケットをログ出力できます。</span><span class="sxs-lookup"><span data-stu-id="78ab2-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="78ab2-204">FastTrack センター では、展開、ライセンス料、ディレクトリの準備に関連したサポート (Domino と Active Directory ディレクトリの同期を含む)、Notes アプリケーションを相互運用するための共存ソフトウェアのアドオン、セルフサービスの移行、アーカイブの移行については扱いません。</span><span class="sxs-lookup"><span data-stu-id="78ab2-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

