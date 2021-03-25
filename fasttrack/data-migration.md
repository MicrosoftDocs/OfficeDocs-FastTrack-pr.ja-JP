---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: f518e8dbda9200318022bad2cc12d1ba68263df8
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188026"
---
# <a name="data-migration"></a><span data-ttu-id="4b558-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="4b558-104">Data Migration</span></span>

<span data-ttu-id="4b558-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4b558-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="4b558-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="4b558-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="4b558-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="4b558-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="4b558-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="4b558-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="4b558-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="4b558-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-111">You create and schedule your migration events.</span></span> <span data-ttu-id="4b558-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="4b558-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="4b558-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="4b558-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="4b558-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="4b558-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="4b558-115">Considerations</span></span>

  - <span data-ttu-id="4b558-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="4b558-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="4b558-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="4b558-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="4b558-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="4b558-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="4b558-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="4b558-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="4b558-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="4b558-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="4b558-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="4b558-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="4b558-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="4b558-124">Migration service availability</span></span>

  - <span data-ttu-id="4b558-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="4b558-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="4b558-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="4b558-127">Migration to Exchange Online</span></span>

<span data-ttu-id="4b558-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="4b558-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="4b558-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-130">You create and schedule your migration events.</span></span> <span data-ttu-id="4b558-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="4b558-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="4b558-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="4b558-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="4b558-133">Considerations</span></span>

  - <span data-ttu-id="4b558-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="4b558-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="4b558-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="4b558-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="4b558-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="4b558-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="4b558-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="4b558-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="4b558-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="4b558-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="4b558-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="4b558-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="4b558-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="4b558-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="4b558-143">Source environments</span></span>

<span data-ttu-id="4b558-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="4b558-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="4b558-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="4b558-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="4b558-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="4b558-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="4b558-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="4b558-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4b558-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="4b558-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="4b558-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="4b558-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4b558-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="4b558-154">
<strong>注:</strong> オンプレミスの Exchange 依存関係については、「ハイブリッド展開の前提条件 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</span><span class="sxs-lookup"><span data-stu-id="4b558-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="4b558-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="4b558-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="4b558-156">メール</span><span class="sxs-lookup"><span data-stu-id="4b558-156">Emails</span></span></li>
<li><span data-ttu-id="4b558-157">サーバー側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="4b558-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="4b558-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="4b558-158">Delegates</span></span></li>
<li><span data-ttu-id="4b558-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="4b558-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="4b558-160">予定表</span><span class="sxs-lookup"><span data-stu-id="4b558-160">Calendar</span></span> </li>
<li> <span data-ttu-id="4b558-161">タスク</span><span class="sxs-lookup"><span data-stu-id="4b558-161">Tasks</span></span> </li>
<li> <span data-ttu-id="4b558-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="4b558-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="4b558-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="4b558-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="4b558-164">署名</span><span class="sxs-lookup"><span data-stu-id="4b558-164">Signatures</span></span> </li>
<li> <span data-ttu-id="4b558-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="4b558-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="4b558-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="4b558-167">Public folders</span></span> </li>
<li> <span data-ttu-id="4b558-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="4b558-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="4b558-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="4b558-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="4b558-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="4b558-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="4b558-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="4b558-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="4b558-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="4b558-174">クライアント側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="4b558-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-175"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="4b558-176">
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="4b558-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="4b558-177">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="4b558-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-178">メール</span><span class="sxs-lookup"><span data-stu-id="4b558-178">Emails</span></span> </li>
<li> <span data-ttu-id="4b558-179">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="4b558-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="4b558-180">カレンダー</span><span class="sxs-lookup"><span data-stu-id="4b558-180">Calendar</span></span> </li>
<li> <span data-ttu-id="4b558-181">ラベル</span><span class="sxs-lookup"><span data-stu-id="4b558-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-182">ルール</span><span class="sxs-lookup"><span data-stu-id="4b558-182">Rules</span></span> </li>
<li> <span data-ttu-id="4b558-183">デリゲート</span><span class="sxs-lookup"><span data-stu-id="4b558-183">Delegates</span></span> </li>
<li> <span data-ttu-id="4b558-184">署名</span><span class="sxs-lookup"><span data-stu-id="4b558-184">Signatures</span></span> </li>
<li> <span data-ttu-id="4b558-185">タスク</span><span class="sxs-lookup"><span data-stu-id="4b558-185">Tasks</span></span> </li>
<li> <span data-ttu-id="4b558-186">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="4b558-187">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-188">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="4b558-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="4b558-189">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="4b558-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="4b558-190">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="4b558-191">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="4b558-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="4b558-192">Google グループ</span><span class="sxs-lookup"><span data-stu-id="4b558-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="4b558-193">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="4b558-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="4b558-194">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="4b558-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="4b558-195">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="4b558-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="4b558-196">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="4b558-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="4b558-197">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4b558-198"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="4b558-199">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="4b558-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="4b558-200">メール</span><span class="sxs-lookup"><span data-stu-id="4b558-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="4b558-201">ルール</span><span class="sxs-lookup"><span data-stu-id="4b558-201">Rules</span></span> </li>
<li> <span data-ttu-id="4b558-202">デリゲート</span><span class="sxs-lookup"><span data-stu-id="4b558-202">Delegates</span></span> </li>
<li> <span data-ttu-id="4b558-203">配布リスト</span><span class="sxs-lookup"><span data-stu-id="4b558-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="4b558-204">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="4b558-204">External contacts</span></span> </li>
<li> <span data-ttu-id="4b558-205">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="4b558-206">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-207">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="4b558-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="4b558-208">予定表</span><span class="sxs-lookup"><span data-stu-id="4b558-208">Calendar</span></span> </li>
<li> <span data-ttu-id="4b558-209">署名</span><span class="sxs-lookup"><span data-stu-id="4b558-209">Signatures</span></span> </li>
<li> <span data-ttu-id="4b558-210">タスク</span><span class="sxs-lookup"><span data-stu-id="4b558-210">Tasks</span></span> </li>
<li> <span data-ttu-id="4b558-211">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="4b558-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="4b558-212">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="4b558-212">Archive data</span></span> </li>
<li> <span data-ttu-id="4b558-213">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="4b558-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="4b558-214">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="4b558-215">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="4b558-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="4b558-216">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="4b558-216">FastTrack responsibilities</span></span>

<span data-ttu-id="4b558-217">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="4b558-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-218">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="4b558-219">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="4b558-220">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="4b558-221">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="4b558-221">Your responsibilities</span></span>

<span data-ttu-id="4b558-222">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-223">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="4b558-224">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="4b558-225">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="4b558-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="4b558-226">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="4b558-227">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="4b558-228">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="4b558-229">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4b558-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="4b558-230">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="4b558-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="4b558-231">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="4b558-232">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="4b558-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="4b558-233">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="4b558-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="4b558-234">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="4b558-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="4b558-235">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="4b558-236">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="4b558-237">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="4b558-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="4b558-238">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="4b558-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="4b558-239">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="4b558-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="4b558-240">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="4b558-241">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="4b558-242">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-242">You create and schedule your migration events.</span></span> <span data-ttu-id="4b558-243">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="4b558-244">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="4b558-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="4b558-245">考慮事項</span><span class="sxs-lookup"><span data-stu-id="4b558-245">Considerations</span></span>

 - <span data-ttu-id="4b558-246">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="4b558-247">詳細については <a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint の制限」</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="4b558-248">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4b558-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="4b558-249">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="4b558-249">Source environment details</span></span>

<span data-ttu-id="4b558-250">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="4b558-251">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="4b558-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="4b558-252">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="4b558-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="4b558-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="4b558-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="4b558-254">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="4b558-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="4b558-255">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4b558-256"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="4b558-257"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="4b558-258"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="4b558-259"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4b558-260"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="4b558-261">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-262">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-262">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-263">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-264">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-265">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-266">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-267">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-268">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-268">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-269">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-269">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-270">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-270">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-271">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="4b558-272">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="4b558-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="4b558-273">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="4b558-274">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="4b558-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="4b558-275">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-276">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-277">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-278">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-279">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="4b558-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="4b558-280">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="4b558-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="4b558-281">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="4b558-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="4b558-282">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="4b558-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="4b558-283">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="4b558-284">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-285">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="4b558-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="4b558-286">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="4b558-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="4b558-287">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-288"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="4b558-289">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-290">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="4b558-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="4b558-291">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-292">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-293">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-294">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-295">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-296">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-296">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-297">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-297">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-298">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-298">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-299">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-300">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="4b558-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="4b558-301">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-302">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-303">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="4b558-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="4b558-304">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-305">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-306">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-307">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-308">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-309">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-310">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-311">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-312">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="4b558-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="4b558-313">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="4b558-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="4b558-314">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="4b558-315">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="4b558-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="4b558-316">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-317">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-318">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="4b558-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="4b558-319">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="4b558-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-320">制限付きまたはコピー不可としてマークされたファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="4b558-321">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4b558-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="4b558-323">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-324">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-324">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-325">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-326">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-327">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-328">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-329">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-330">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-330">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-331">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-331">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-332">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-332">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-333">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-334">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="4b558-335">Box Notes (Word ドキュメント形式に変換)</span><span class="sxs-lookup"><span data-stu-id="4b558-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-336">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-337">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-338">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-339">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-340">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-341">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-342">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-343">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-344">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-345">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-346">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="4b558-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="4b558-347">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="4b558-348">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-349">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-350">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-351"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="4b558-352">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-353">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-353">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-354">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-355">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-356">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-357">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-358">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-359">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-359">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-360">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-360">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-361">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-361">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-362">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-363">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="4b558-364">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-365">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-366">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-367">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-368">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-369">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-370">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-371">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-372">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-373">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-374">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="4b558-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="4b558-375">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="4b558-376">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="4b558-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="4b558-377">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="4b558-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="4b558-378">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="4b558-379">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-380">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="4b558-381">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="4b558-382">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="4b558-382">FastTrack responsibilities</span></span>

<span data-ttu-id="4b558-383">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="4b558-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-384">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="4b558-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="4b558-385">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="4b558-385">Your responsibilities</span></span>

<span data-ttu-id="4b558-386">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-387">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="4b558-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="4b558-388">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="4b558-389">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="4b558-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="4b558-390">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="4b558-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="4b558-391">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="4b558-392">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="4b558-393">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-393">You create and schedule your migration events.</span></span> <span data-ttu-id="4b558-394">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="4b558-395">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="4b558-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="4b558-396">考慮事項</span><span class="sxs-lookup"><span data-stu-id="4b558-396">Considerations</span></span>

  - <span data-ttu-id="4b558-397">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="4b558-398">詳細については <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> 、「SharePoint の制限」</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="4b558-399">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4b558-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="4b558-400">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="4b558-401">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="4b558-401">Source environment details</span></span>

<span data-ttu-id="4b558-402">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="4b558-403">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="4b558-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="4b558-404">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="4b558-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="4b558-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="4b558-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="4b558-406">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="4b558-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="4b558-407">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="4b558-408"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="4b558-409"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="4b558-410"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="4b558-411"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4b558-412"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="4b558-413">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-414">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-414">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-415">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-416">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-417">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-418">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-419">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-420">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-420">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-421">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-421">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-422">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-422">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-423">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="4b558-424">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="4b558-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="4b558-425">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="4b558-426">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="4b558-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="4b558-427">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="4b558-428">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-429">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-430">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-431">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="4b558-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="4b558-432">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="4b558-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="4b558-433">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="4b558-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="4b558-434">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="4b558-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="4b558-435">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="4b558-436">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-437">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="4b558-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="4b558-438">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="4b558-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="4b558-439">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-440"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="4b558-441">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-442">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="4b558-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="4b558-443">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-444">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-445">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-446">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-447">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-448">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-448">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-449">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-449">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-450">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-450">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-451">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-452">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="4b558-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="4b558-453">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-454">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-455">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="4b558-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="4b558-456">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-457">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-458">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-459">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-460">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-461">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-462">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-463">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-464">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="4b558-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="4b558-465">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="4b558-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="4b558-466">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="4b558-467">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="4b558-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="4b558-468">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-469">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-470">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="4b558-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="4b558-471">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="4b558-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-472">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4b558-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="4b558-474">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-475">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-475">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-476">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-477">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-478">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-479">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-480">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-481">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-481">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-482">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-482">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-483">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-483">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-484">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-485">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-486">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-487">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-488">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-489">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-490">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-491">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-492">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-493">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-494">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-495">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-496">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="4b558-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="4b558-497">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="4b558-498">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-499">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-500">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-501"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="4b558-502">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-503">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-503">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-504">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-505">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-506">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="4b558-507">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-508">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-509">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-509">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-510">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-510">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-511">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-511">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-512">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-513">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="4b558-514">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="4b558-515">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-516">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-517">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-518">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-519">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-520">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-521">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-522">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-523">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-524">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="4b558-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="4b558-525">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="4b558-526">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="4b558-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="4b558-527">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="4b558-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="4b558-528">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="4b558-529">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-530">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-531">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="4b558-532">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="4b558-532">FastTrack responsibilities</span></span>

<span data-ttu-id="4b558-533">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="4b558-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-534">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="4b558-535">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="4b558-535">Your responsibilities</span></span>

<span data-ttu-id="4b558-536">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-537">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="4b558-538">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="4b558-539">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="4b558-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="4b558-540">Microsoft Teams および Microsoft 365 グループへの移行</span><span class="sxs-lookup"><span data-stu-id="4b558-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="4b558-541">FastTrack を使用してファイルを Microsoft Teams および Microsoft 365 グループに移行する場合は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="4b558-542">移行を計画し、ソース環境と Teams と Microsoft 365 グループを構成し、データ移行サービスを活用してファイルを移行するのに役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="4b558-543">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="4b558-543">You create and schedule your migration events.</span></span> <span data-ttu-id="4b558-544">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="4b558-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="4b558-545">移行イベントが完了すると、ソース環境の適切にスケジュールされ、対象となるソースからのファイルが Teams および Microsoft 365 グループに移行される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="4b558-546">Teams チャネルと Microsoft 365 グループは、これらの移行先の種類にデータを移行する前に、お客様が事前に準備する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="4b558-547">Teams と Microsoft 365 グループは、ファイルの送信先の場所に対するアクセス許可に影響します。</span><span class="sxs-lookup"><span data-stu-id="4b558-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="4b558-548">Teams と Microsoft 365 グループは、コラボレーションを可能にするために構築されています。</span><span class="sxs-lookup"><span data-stu-id="4b558-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="4b558-549">Teams チャネルまたは Microsoft 365 グループは、それらの宛先に移行するときに、それらのファイルにアクセスできるユーザーを決定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="4b558-550">FastTrack は、移行中に Teams チャネルまたは Microsoft 365 グループのアクセス許可にエンド ユーザーまたはグループを追加しない。</span><span class="sxs-lookup"><span data-stu-id="4b558-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="4b558-551">考慮事項</span><span class="sxs-lookup"><span data-stu-id="4b558-551">Considerations</span></span>

- <span data-ttu-id="4b558-552">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="4b558-553">詳細については <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> 、「SharePoint の制限」</a> を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="4b558-554">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4b558-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="4b558-555">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="4b558-555">Source environment details</span></span>

<span data-ttu-id="4b558-556">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="4b558-557">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="4b558-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="4b558-558">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="4b558-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="4b558-559">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="4b558-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="4b558-560">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="4b558-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="4b558-561">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="4b558-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="4b558-562"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="4b558-563"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="4b558-564"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="4b558-565"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4b558-566"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="4b558-567">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-568">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-568">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-569">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-570">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-571">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-572">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-573">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-574">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-574">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-575">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-575">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-576">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-576">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-577">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="4b558-578">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="4b558-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="4b558-579">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="4b558-580">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="4b558-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="4b558-581">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="4b558-582">アクセス許可は、Microsoft 365 グループまたは Microsoft Teams チャネルの影響を受えます。</span><span class="sxs-lookup"><span data-stu-id="4b558-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="4b558-583">移行先が Microsoft 365 グループまたは Microsoft Teams チャネルの場合、移行されたファイルに対する最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="4b558-584">Microsoft 365 グループまたは Microsoft Teams チャネルに移行するファイルに対するアクセス許可を移行することはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="4b558-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-585">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-586">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-587">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="4b558-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="4b558-588">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="4b558-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="4b558-589">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="4b558-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="4b558-590">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="4b558-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="4b558-591">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="4b558-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="4b558-592">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="4b558-593">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-594">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="4b558-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="4b558-595">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="4b558-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="4b558-596">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-597"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="4b558-598">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-599">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="4b558-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="4b558-600">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-601">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-602">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-603">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-604">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-605">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-605">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-606">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-606">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-607">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-607">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-608">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-609">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="4b558-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="4b558-610">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="4b558-611">\*アクセス許可は、Microsoft 365 グループまたは Microsoft Teams チャネルの影響を受します。</span><span class="sxs-lookup"><span data-stu-id="4b558-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="4b558-612">移行先が Microsoft 365 グループまたは Microsoft Teams チャネルの場合、移行されたファイルに対する最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="4b558-613">Microsoft 365 グループまたは Microsoft Teams チャネルに移行するファイルに対するアクセス許可を移行することはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="4b558-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="4b558-614">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-615">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="4b558-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="4b558-616">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-617">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-618">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-619">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-620">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-621">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-622">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-623">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-624">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="4b558-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="4b558-625">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="4b558-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="4b558-626">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="4b558-627">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="4b558-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="4b558-628">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-629">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-630">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="4b558-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="4b558-631">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="4b558-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-632">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4b558-633"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="4b558-634">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-635">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-635">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-636">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-637">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-638">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-639">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-640">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-641">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-641">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-642">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-642">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-643">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-643">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-644">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-645">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="4b558-646">Box Notes (Word ドキュメント形式に変換)</span><span class="sxs-lookup"><span data-stu-id="4b558-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="4b558-647">\*アクセス許可は、Microsoft 365 グループまたは Microsoft Teams チャネルの影響を受します。</span><span class="sxs-lookup"><span data-stu-id="4b558-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="4b558-648">移行先が Microsoft 365 グループまたは Microsoft Teams チャネルの場合、移行されたファイルに対する最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="4b558-649">Microsoft 365 グループまたは Microsoft Teams チャネルに移行するファイルに対するアクセス許可を移行することはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="4b558-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="4b558-650">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-651">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-652">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-653">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-654">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-655">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-656">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-657">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-658">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-659">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="4b558-660">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="4b558-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="4b558-661">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="4b558-662">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-663">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-664">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4b558-665"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="4b558-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="4b558-666">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="4b558-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="4b558-667">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-667">Documents</span></span> </li>
<li> <span data-ttu-id="4b558-668">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="4b558-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="4b558-669">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-670">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="4b558-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="4b558-671">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="4b558-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="4b558-672">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="4b558-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="4b558-673">作成日</span><span class="sxs-lookup"><span data-stu-id="4b558-673">Created date</span></span> </li>
<li> <span data-ttu-id="4b558-674">更新日</span><span class="sxs-lookup"><span data-stu-id="4b558-674">Modified date</span></span> </li>
<li> <span data-ttu-id="4b558-675">作成者</span><span class="sxs-lookup"><span data-stu-id="4b558-675">Created by</span></span> </li>
<li> <span data-ttu-id="4b558-676">最終更新者</span><span class="sxs-lookup"><span data-stu-id="4b558-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="4b558-677">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="4b558-678">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="4b558-679">\*アクセス許可は、Microsoft 365 グループまたは Microsoft Teams チャネルの影響を受します。</span><span class="sxs-lookup"><span data-stu-id="4b558-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="4b558-680">移行先が Microsoft 365 グループまたは Microsoft Teams チャネルの場合、移行されたファイルに対する最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="4b558-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="4b558-681">Microsoft 365 グループまたは Microsoft Teams チャネルに移行するファイルに対するアクセス許可を移行することはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="4b558-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="4b558-682">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="4b558-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="4b558-683">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="4b558-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="4b558-684">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-685">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4b558-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="4b558-686">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="4b558-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="4b558-687">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="4b558-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="4b558-688">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="4b558-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="4b558-689">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="4b558-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="4b558-690">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="4b558-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="4b558-691">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="4b558-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="4b558-692">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="4b558-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="4b558-693">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="4b558-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="4b558-694">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="4b558-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="4b558-695">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="4b558-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="4b558-696">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="4b558-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="4b558-697">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="4b558-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="4b558-698">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="4b558-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="4b558-699">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="4b558-699">FastTrack responsibilities</span></span>

<span data-ttu-id="4b558-700">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="4b558-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-701">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="4b558-702">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="4b558-702">Your responsibilities</span></span> 

<span data-ttu-id="4b558-703">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="4b558-704">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4b558-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="4b558-705">また、Microsoft Teams および Microsoft 365 グループの移行に固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="4b558-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="4b558-706">移行イベントの対象として、すべての Microsoft Teams チャネルと Microsoft 365 グループをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="4b558-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="4b558-707">FastTrack は、Microsoft Teams チャネルまたは Microsoft 365 グループを事前準備しない。</span><span class="sxs-lookup"><span data-stu-id="4b558-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="4b558-708">FastTrack は、Microsoft Teams チャネルまたは Microsoft 365 グループにエンド ユーザーまたはグループを追加しない。</span><span class="sxs-lookup"><span data-stu-id="4b558-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="4b558-709">これらの移行先にデータを移行する前に、すべての Microsoft Teams チャネルと Microsoft 365 グループにエンド ユーザーまたはグループを追加して、それらのエンド ユーザーが新しく移行されたドキュメントにアクセスできる必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b558-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>