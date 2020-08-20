---
title: データ移行
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817714"
---
# <a name="data-migration"></a><span data-ttu-id="8913b-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="8913b-104">Data Migration</span></span>

<span data-ttu-id="8913b-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8913b-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8913b-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="8913b-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8913b-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8913b-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="8913b-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8913b-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8913b-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8913b-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="8913b-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8913b-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8913b-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="8913b-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8913b-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="8913b-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8913b-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="8913b-115">Considerations</span></span>

  - <span data-ttu-id="8913b-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8913b-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8913b-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="8913b-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8913b-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="8913b-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8913b-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="8913b-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8913b-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="8913b-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8913b-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8913b-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8913b-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="8913b-124">Migration service availability</span></span>

  - <span data-ttu-id="8913b-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="8913b-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8913b-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="8913b-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8913b-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="8913b-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8913b-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8913b-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8913b-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="8913b-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8913b-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8913b-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="8913b-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8913b-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="8913b-133">Considerations</span></span>

  - <span data-ttu-id="8913b-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8913b-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8913b-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8913b-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="8913b-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8913b-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8913b-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8913b-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="8913b-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8913b-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="8913b-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8913b-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="8913b-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8913b-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="8913b-143">Source environments</span></span>

<span data-ttu-id="8913b-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8913b-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="8913b-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8913b-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="8913b-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8913b-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="8913b-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8913b-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="8913b-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8913b-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8913b-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8913b-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8913b-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8913b-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8913b-154">
<strong>メモ:</strong>  オンプレミスの Exchange の依存関係については、「 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ハイブリッド展開の前提条件</span></a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8913b-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="8913b-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8913b-156">メール</span><span class="sxs-lookup"><span data-stu-id="8913b-156">Emails</span></span></li>
<li><span data-ttu-id="8913b-157">メールボックスのルール</span><span class="sxs-lookup"><span data-stu-id="8913b-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="8913b-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="8913b-158">Delegates</span></span></li>
<li><span data-ttu-id="8913b-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="8913b-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8913b-160">予定表</span><span class="sxs-lookup"><span data-stu-id="8913b-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8913b-161">タスク</span><span class="sxs-lookup"><span data-stu-id="8913b-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8913b-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="8913b-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8913b-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="8913b-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8913b-164">署名</span><span class="sxs-lookup"><span data-stu-id="8913b-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8913b-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="8913b-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8913b-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8913b-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="8913b-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8913b-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="8913b-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8913b-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="8913b-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8913b-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8913b-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="8913b-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8913b-174"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8913b-175">
<strong>注:</strong>  G Suite 環境は、「<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">G Suite の移行を実行する</a>」で説明されている前提条件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8913b-176">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="8913b-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-177">メール</span><span class="sxs-lookup"><span data-stu-id="8913b-177">Emails</span></span> </li>
<li> <span data-ttu-id="8913b-178">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="8913b-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8913b-179">カレンダー</span><span class="sxs-lookup"><span data-stu-id="8913b-179">Calendar</span></span> </li>
<li> <span data-ttu-id="8913b-180">ラベル</span><span class="sxs-lookup"><span data-stu-id="8913b-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-181">ルール</span><span class="sxs-lookup"><span data-stu-id="8913b-181">Rules</span></span> </li>
<li> <span data-ttu-id="8913b-182">デリゲート</span><span class="sxs-lookup"><span data-stu-id="8913b-182">Delegates</span></span> </li>
<li> <span data-ttu-id="8913b-183">署名</span><span class="sxs-lookup"><span data-stu-id="8913b-183">Signatures</span></span> </li>
<li> <span data-ttu-id="8913b-184">タスク</span><span class="sxs-lookup"><span data-stu-id="8913b-184">Tasks</span></span> </li>
<li> <span data-ttu-id="8913b-185">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8913b-186">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-187">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="8913b-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8913b-188">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="8913b-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8913b-189">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8913b-190">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="8913b-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8913b-191">Google グループ</span><span class="sxs-lookup"><span data-stu-id="8913b-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="8913b-192">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="8913b-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8913b-193">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="8913b-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8913b-194">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="8913b-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8913b-195">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="8913b-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8913b-196">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8913b-197"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8913b-198">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="8913b-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8913b-199">メール</span><span class="sxs-lookup"><span data-stu-id="8913b-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8913b-200">ルール</span><span class="sxs-lookup"><span data-stu-id="8913b-200">Rules</span></span> </li>
<li> <span data-ttu-id="8913b-201">デリゲート</span><span class="sxs-lookup"><span data-stu-id="8913b-201">Delegates</span></span> </li>
<li> <span data-ttu-id="8913b-202">配布リスト</span><span class="sxs-lookup"><span data-stu-id="8913b-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8913b-203">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="8913b-203">External contacts</span></span> </li>
<li> <span data-ttu-id="8913b-204">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8913b-205">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-206">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="8913b-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8913b-207">予定表</span><span class="sxs-lookup"><span data-stu-id="8913b-207">Calendar</span></span> </li>
<li> <span data-ttu-id="8913b-208">署名</span><span class="sxs-lookup"><span data-stu-id="8913b-208">Signatures</span></span> </li>
<li> <span data-ttu-id="8913b-209">タスク</span><span class="sxs-lookup"><span data-stu-id="8913b-209">Tasks</span></span> </li>
<li> <span data-ttu-id="8913b-210">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="8913b-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8913b-211">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="8913b-211">Archive data</span></span> </li>
<li> <span data-ttu-id="8913b-212">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="8913b-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8913b-213">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8913b-214">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="8913b-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8913b-215">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="8913b-215">FastTrack responsibilities</span></span>

<span data-ttu-id="8913b-216">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="8913b-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-217">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8913b-218">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8913b-219">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8913b-220">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="8913b-220">Your responsibilities</span></span>

<span data-ttu-id="8913b-221">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-222">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8913b-223">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8913b-224">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="8913b-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8913b-225">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8913b-226">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8913b-227">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="8913b-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8913b-228">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8913b-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8913b-229">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="8913b-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8913b-230">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8913b-231">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="8913b-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8913b-232">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="8913b-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8913b-233">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="8913b-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8913b-234">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="8913b-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8913b-235">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="8913b-236">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="8913b-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8913b-237">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="8913b-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8913b-238">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="8913b-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="8913b-239">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8913b-240">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8913b-241">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="8913b-241">You create and schedule your migration events.</span></span> <span data-ttu-id="8913b-242">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8913b-243">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="8913b-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8913b-244">考慮事項</span><span class="sxs-lookup"><span data-stu-id="8913b-244">Considerations</span></span>

  - <span data-ttu-id="8913b-245">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8913b-246">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8913b-247">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="8913b-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8913b-248">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="8913b-248">Source environment details</span></span>

<span data-ttu-id="8913b-249">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8913b-250">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="8913b-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8913b-251">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="8913b-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8913b-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8913b-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8913b-253">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="8913b-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8913b-254">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="8913b-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8913b-255"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8913b-256"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8913b-257"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8913b-258"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8913b-259"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8913b-260">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-261">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-261">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-262">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-263">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="8913b-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8913b-264">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="8913b-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8913b-265">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-266">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-267">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-267">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-268">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-268">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-269">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-269">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-270">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8913b-271">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="8913b-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8913b-272">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8913b-273">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="8913b-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8913b-274">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-275">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="8913b-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8913b-276">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-277">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="8913b-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="8913b-278">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="8913b-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8913b-279">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="8913b-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8913b-280">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="8913b-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8913b-281">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="8913b-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8913b-282">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8913b-283">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-284">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="8913b-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8913b-285">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="8913b-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8913b-286">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8913b-287"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8913b-288">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-289">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="8913b-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8913b-290">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-291">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-292">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-293">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-294">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-295">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-295">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-296">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-296">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-297">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-297">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-298">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-299">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="8913b-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8913b-300">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-301">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-302">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="8913b-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8913b-303">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-304">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-305">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-306">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-307">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-308">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-309">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-310">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-311">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="8913b-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8913b-312">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="8913b-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8913b-313">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8913b-314">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="8913b-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8913b-315">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-316">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-317">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="8913b-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8913b-318">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="8913b-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-319">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8913b-320"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8913b-321">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-322">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-322">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-323">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-324">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-325">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-326">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-327">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-328">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-328">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-329">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-329">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-330">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-330">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-331">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-332">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-333">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-334">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="8913b-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8913b-335">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-336">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-337">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-338">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-339">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-340">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-341">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-342">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-343">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="8913b-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8913b-344">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8913b-345">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-346">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-347">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8913b-348"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8913b-349">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-350">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-350">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-351">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-352">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-353">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-354">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-355">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-356">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-356">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-357">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-357">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-358">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-358">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-359">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-360">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8913b-361">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-362">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-363">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="8913b-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8913b-364">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-365">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-366">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-367">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-368">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-369">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-370">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-371">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8913b-372">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8913b-373">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="8913b-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8913b-374">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="8913b-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8913b-375">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8913b-376">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-377">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8913b-378">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8913b-379">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="8913b-379">FastTrack responsibilities</span></span>

<span data-ttu-id="8913b-380">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="8913b-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-381">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="8913b-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8913b-382">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="8913b-382">Your responsibilities</span></span>

<span data-ttu-id="8913b-383">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-384">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="8913b-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8913b-385">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8913b-386">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="8913b-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8913b-387">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="8913b-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8913b-388">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8913b-389">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8913b-390">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="8913b-390">You create and schedule your migration events.</span></span> <span data-ttu-id="8913b-391">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="8913b-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8913b-392">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="8913b-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8913b-393">考慮事項</span><span class="sxs-lookup"><span data-stu-id="8913b-393">Considerations</span></span>

  - <span data-ttu-id="8913b-394">すべての移行には OneDrive for Business のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="8913b-395">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8913b-396">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="8913b-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8913b-397">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8913b-398">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="8913b-398">Source environment details</span></span>

<span data-ttu-id="8913b-399">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8913b-400">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="8913b-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8913b-401">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="8913b-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8913b-402">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8913b-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8913b-403">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="8913b-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8913b-404">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="8913b-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8913b-405"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8913b-406"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8913b-407"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8913b-408"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8913b-409"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8913b-410">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-411">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-411">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-412">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-413">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="8913b-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8913b-414">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="8913b-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8913b-415">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-416">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-417">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-417">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-418">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-418">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-419">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-419">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-420">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8913b-421">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="8913b-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8913b-422">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8913b-423">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="8913b-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8913b-424">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="8913b-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8913b-425">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="8913b-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8913b-426">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-427">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="8913b-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="8913b-428">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="8913b-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8913b-429">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="8913b-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8913b-430">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="8913b-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8913b-431">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="8913b-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8913b-432">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8913b-433">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-434">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="8913b-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8913b-435">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="8913b-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8913b-436">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8913b-437"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8913b-438">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-439">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="8913b-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8913b-440">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-441">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-442">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-443">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-444">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-445">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-445">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-446">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-446">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-447">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-447">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-448">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-449">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="8913b-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8913b-450">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-451">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-452">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="8913b-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8913b-453">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-454">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-455">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-456">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-457">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-458">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-459">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-460">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-461">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="8913b-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8913b-462">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="8913b-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8913b-463">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8913b-464">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="8913b-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8913b-465">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-466">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-467">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="8913b-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8913b-468">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="8913b-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-469">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8913b-470"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8913b-471">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-472">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-472">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-473">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-474">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-475">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-476">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-477">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-478">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-478">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-479">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-479">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-480">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-480">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-481">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-482">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-483">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-484">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="8913b-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8913b-485">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-486">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-487">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-488">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-489">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-490">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-491">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-492">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8913b-493">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="8913b-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8913b-494">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8913b-495">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-496">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-497">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8913b-498"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="8913b-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8913b-499">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="8913b-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8913b-500">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-500">Documents</span></span> </li>
<li> <span data-ttu-id="8913b-501">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="8913b-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8913b-502">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-503">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8913b-504">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="8913b-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8913b-505">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="8913b-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8913b-506">作成日</span><span class="sxs-lookup"><span data-stu-id="8913b-506">Created date</span></span> </li>
<li> <span data-ttu-id="8913b-507">更新日</span><span class="sxs-lookup"><span data-stu-id="8913b-507">Modified date</span></span> </li>
<li> <span data-ttu-id="8913b-508">作成者</span><span class="sxs-lookup"><span data-stu-id="8913b-508">Created by</span></span> </li>
<li> <span data-ttu-id="8913b-509">最終更新者</span><span class="sxs-lookup"><span data-stu-id="8913b-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8913b-510">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8913b-511">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8913b-512">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="8913b-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8913b-513">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="8913b-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8913b-514">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-515">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="8913b-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8913b-516">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="8913b-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8913b-517">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="8913b-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8913b-518">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="8913b-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8913b-519">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="8913b-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="8913b-520">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="8913b-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8913b-521">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8913b-522">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="8913b-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8913b-523">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="8913b-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8913b-524">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="8913b-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8913b-525">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="8913b-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8913b-526">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="8913b-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8913b-527">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="8913b-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8913b-528">現在の  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限事項と制約事項</span></a> から逸脱するファイルまたはフォルダー</span><span class="sxs-lookup"><span data-stu-id="8913b-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8913b-529">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="8913b-529">FastTrack responsibilities</span></span>

<span data-ttu-id="8913b-530">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="8913b-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-531">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8913b-532">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="8913b-532">Your responsibilities</span></span>

<span data-ttu-id="8913b-533">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8913b-534">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8913b-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8913b-535">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="8913b-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8913b-536">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="8913b-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
