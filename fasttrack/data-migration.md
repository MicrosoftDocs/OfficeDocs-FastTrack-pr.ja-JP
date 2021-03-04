---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: b02c7c863cdc689fab4a6545ac1acc84f6b03fc2
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416614"
---
# <a name="data-migration"></a><span data-ttu-id="ccf68-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-104">Data Migration</span></span>

<span data-ttu-id="ccf68-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="ccf68-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="ccf68-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="ccf68-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="ccf68-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="ccf68-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="ccf68-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-111">You create and schedule your migration events.</span></span> <span data-ttu-id="ccf68-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="ccf68-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="ccf68-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="ccf68-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="ccf68-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="ccf68-115">Considerations</span></span>

  - <span data-ttu-id="ccf68-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="ccf68-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="ccf68-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="ccf68-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="ccf68-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="ccf68-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="ccf68-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="ccf68-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="ccf68-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="ccf68-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="ccf68-124">Migration service availability</span></span>

  - <span data-ttu-id="ccf68-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="ccf68-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="ccf68-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="ccf68-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="ccf68-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-127">Migration to Exchange Online</span></span>

<span data-ttu-id="ccf68-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="ccf68-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="ccf68-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-130">You create and schedule your migration events.</span></span> <span data-ttu-id="ccf68-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="ccf68-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="ccf68-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="ccf68-133">Considerations</span></span>

  - <span data-ttu-id="ccf68-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="ccf68-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="ccf68-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="ccf68-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="ccf68-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="ccf68-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="ccf68-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="ccf68-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="ccf68-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="ccf68-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="ccf68-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="ccf68-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="ccf68-143">Source environments</span></span>

<span data-ttu-id="ccf68-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="ccf68-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="ccf68-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="ccf68-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="ccf68-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="ccf68-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="ccf68-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="ccf68-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="ccf68-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="ccf68-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="ccf68-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="ccf68-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="ccf68-154">
<strong>注:</strong> オンプレミスの Exchange 依存関係については、「ハイブリッド展開の前提条件 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</span><span class="sxs-lookup"><span data-stu-id="ccf68-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="ccf68-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="ccf68-156">メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-156">Emails</span></span></li>
<li><span data-ttu-id="ccf68-157">サーバー側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="ccf68-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="ccf68-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="ccf68-158">Delegates</span></span></li>
<li><span data-ttu-id="ccf68-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="ccf68-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="ccf68-160">予定表</span><span class="sxs-lookup"><span data-stu-id="ccf68-160">Calendar</span></span> </li>
<li> <span data-ttu-id="ccf68-161">タスク</span><span class="sxs-lookup"><span data-stu-id="ccf68-161">Tasks</span></span> </li>
<li> <span data-ttu-id="ccf68-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="ccf68-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="ccf68-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="ccf68-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="ccf68-164">署名</span><span class="sxs-lookup"><span data-stu-id="ccf68-164">Signatures</span></span> </li>
<li> <span data-ttu-id="ccf68-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="ccf68-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="ccf68-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="ccf68-167">Public folders</span></span> </li>
<li> <span data-ttu-id="ccf68-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="ccf68-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="ccf68-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="ccf68-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="ccf68-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="ccf68-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="ccf68-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="ccf68-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="ccf68-174">クライアント側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="ccf68-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="ccf68-175"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="ccf68-176">
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="ccf68-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="ccf68-177">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="ccf68-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-178">メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-178">Emails</span></span> </li>
<li> <span data-ttu-id="ccf68-179">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="ccf68-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="ccf68-180">カレンダー</span><span class="sxs-lookup"><span data-stu-id="ccf68-180">Calendar</span></span> </li>
<li> <span data-ttu-id="ccf68-181">ラベル</span><span class="sxs-lookup"><span data-stu-id="ccf68-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-182">ルール</span><span class="sxs-lookup"><span data-stu-id="ccf68-182">Rules</span></span> </li>
<li> <span data-ttu-id="ccf68-183">デリゲート</span><span class="sxs-lookup"><span data-stu-id="ccf68-183">Delegates</span></span> </li>
<li> <span data-ttu-id="ccf68-184">署名</span><span class="sxs-lookup"><span data-stu-id="ccf68-184">Signatures</span></span> </li>
<li> <span data-ttu-id="ccf68-185">タスク</span><span class="sxs-lookup"><span data-stu-id="ccf68-185">Tasks</span></span> </li>
<li> <span data-ttu-id="ccf68-186">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="ccf68-187">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-188">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="ccf68-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="ccf68-189">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="ccf68-190">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="ccf68-191">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="ccf68-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="ccf68-192">Google グループ</span><span class="sxs-lookup"><span data-stu-id="ccf68-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="ccf68-193">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="ccf68-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="ccf68-194">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="ccf68-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="ccf68-195">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="ccf68-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="ccf68-196">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="ccf68-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="ccf68-197">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="ccf68-198"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="ccf68-199">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="ccf68-200">メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="ccf68-201">ルール</span><span class="sxs-lookup"><span data-stu-id="ccf68-201">Rules</span></span> </li>
<li> <span data-ttu-id="ccf68-202">デリゲート</span><span class="sxs-lookup"><span data-stu-id="ccf68-202">Delegates</span></span> </li>
<li> <span data-ttu-id="ccf68-203">配布リスト</span><span class="sxs-lookup"><span data-stu-id="ccf68-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="ccf68-204">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="ccf68-204">External contacts</span></span> </li>
<li> <span data-ttu-id="ccf68-205">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="ccf68-206">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-207">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="ccf68-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="ccf68-208">予定表</span><span class="sxs-lookup"><span data-stu-id="ccf68-208">Calendar</span></span> </li>
<li> <span data-ttu-id="ccf68-209">署名</span><span class="sxs-lookup"><span data-stu-id="ccf68-209">Signatures</span></span> </li>
<li> <span data-ttu-id="ccf68-210">タスク</span><span class="sxs-lookup"><span data-stu-id="ccf68-210">Tasks</span></span> </li>
<li> <span data-ttu-id="ccf68-211">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="ccf68-212">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="ccf68-212">Archive data</span></span> </li>
<li> <span data-ttu-id="ccf68-213">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="ccf68-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="ccf68-214">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="ccf68-215">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="ccf68-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="ccf68-216">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="ccf68-216">FastTrack responsibilities</span></span>

<span data-ttu-id="ccf68-217">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="ccf68-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-218">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="ccf68-219">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="ccf68-220">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="ccf68-221">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="ccf68-221">Your responsibilities</span></span>

<span data-ttu-id="ccf68-222">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-223">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="ccf68-224">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="ccf68-225">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="ccf68-226">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="ccf68-227">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="ccf68-228">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="ccf68-229">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="ccf68-230">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="ccf68-231">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="ccf68-232">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="ccf68-233">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="ccf68-234">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="ccf68-235">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="ccf68-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="ccf68-236">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="ccf68-237">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="ccf68-238">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="ccf68-239">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="ccf68-240">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="ccf68-241">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="ccf68-242">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-242">You create and schedule your migration events.</span></span> <span data-ttu-id="ccf68-243">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="ccf68-244">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="ccf68-245">考慮事項</span><span class="sxs-lookup"><span data-stu-id="ccf68-245">Considerations</span></span>

  - <span data-ttu-id="ccf68-246">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="ccf68-247">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="ccf68-248">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="ccf68-249">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="ccf68-249">Source environment details</span></span>

<span data-ttu-id="ccf68-250">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="ccf68-251">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="ccf68-252">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="ccf68-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="ccf68-254">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="ccf68-255">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="ccf68-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="ccf68-256"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="ccf68-257"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="ccf68-258"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="ccf68-259"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="ccf68-260"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="ccf68-261">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-262">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-262">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-263">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-264">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="ccf68-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="ccf68-265">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="ccf68-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="ccf68-266">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-267">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-268">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-268">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-269">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-269">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-270">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-270">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-271">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="ccf68-272">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="ccf68-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="ccf68-273">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="ccf68-274">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="ccf68-275">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-276">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="ccf68-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="ccf68-277">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-278">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="ccf68-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="ccf68-279">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="ccf68-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="ccf68-280">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="ccf68-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="ccf68-281">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="ccf68-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="ccf68-282">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="ccf68-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="ccf68-283">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="ccf68-284">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-285">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="ccf68-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="ccf68-286">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="ccf68-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="ccf68-287">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="ccf68-288"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="ccf68-289">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-290">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="ccf68-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="ccf68-291">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-292">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-293">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-294">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-295">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-296">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-296">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-297">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-297">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-298">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-298">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-299">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-300">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="ccf68-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="ccf68-301">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-302">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-303">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="ccf68-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="ccf68-304">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-305">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-306">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-307">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-308">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-309">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-310">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-311">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-312">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="ccf68-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="ccf68-313">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="ccf68-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="ccf68-314">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="ccf68-315">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="ccf68-316">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-317">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-318">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="ccf68-319">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-320">制限付きまたはコピー不可としてマークされたファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="ccf68-321">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="ccf68-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="ccf68-323">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-324">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-324">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-325">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-326">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-327">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-328">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-329">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-330">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-330">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-331">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-331">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-332">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-332">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-333">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-334">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="ccf68-335">Box Notes (Word ドキュメント形式に変換)</span><span class="sxs-lookup"><span data-stu-id="ccf68-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-336">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-337">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="ccf68-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="ccf68-338">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-339">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-340">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-341">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-342">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-343">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-344">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-345">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-346">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="ccf68-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="ccf68-347">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="ccf68-348">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-349">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-350">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="ccf68-351"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="ccf68-352">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-353">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-353">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-354">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-355">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-356">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-357">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-358">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-359">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-359">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-360">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-360">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-361">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-361">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-362">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-363">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="ccf68-364">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-365">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-366">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="ccf68-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="ccf68-367">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-368">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-369">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-370">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-371">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-372">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-373">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-374">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="ccf68-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="ccf68-375">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="ccf68-376">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="ccf68-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="ccf68-377">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="ccf68-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="ccf68-378">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="ccf68-379">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-380">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="ccf68-381">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="ccf68-382">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="ccf68-382">FastTrack responsibilities</span></span>

<span data-ttu-id="ccf68-383">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="ccf68-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-384">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="ccf68-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="ccf68-385">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="ccf68-385">Your responsibilities</span></span>

<span data-ttu-id="ccf68-386">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-387">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="ccf68-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="ccf68-388">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="ccf68-389">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="ccf68-390">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="ccf68-391">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="ccf68-392">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="ccf68-393">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-393">You create and schedule your migration events.</span></span> <span data-ttu-id="ccf68-394">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="ccf68-395">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="ccf68-396">考慮事項</span><span class="sxs-lookup"><span data-stu-id="ccf68-396">Considerations</span></span>

  - <span data-ttu-id="ccf68-397">すべての移行には OneDrive for Business のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="ccf68-398">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="ccf68-399">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="ccf68-400">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="ccf68-401">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="ccf68-401">Source environment details</span></span>

<span data-ttu-id="ccf68-402">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="ccf68-403">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="ccf68-404">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="ccf68-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="ccf68-406">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="ccf68-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="ccf68-407">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="ccf68-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="ccf68-408"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="ccf68-409"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="ccf68-410"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="ccf68-411"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="ccf68-412"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="ccf68-413">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-414">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-414">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-415">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-416">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="ccf68-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="ccf68-417">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="ccf68-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="ccf68-418">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-419">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-420">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-420">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-421">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-421">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-422">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-422">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-423">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="ccf68-424">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="ccf68-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="ccf68-425">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="ccf68-426">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="ccf68-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="ccf68-427">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="ccf68-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="ccf68-428">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="ccf68-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="ccf68-429">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-430">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="ccf68-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="ccf68-431">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="ccf68-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="ccf68-432">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="ccf68-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="ccf68-433">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="ccf68-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="ccf68-434">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="ccf68-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="ccf68-435">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="ccf68-436">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-437">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="ccf68-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="ccf68-438">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="ccf68-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="ccf68-439">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="ccf68-440"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="ccf68-441">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-442">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="ccf68-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="ccf68-443">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-444">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-445">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-446">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-447">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-448">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-448">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-449">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-449">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-450">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-450">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-451">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-452">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="ccf68-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="ccf68-453">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-454">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-455">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="ccf68-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="ccf68-456">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-457">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-458">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-459">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-460">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-461">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-462">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-463">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-464">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="ccf68-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="ccf68-465">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="ccf68-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="ccf68-466">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="ccf68-467">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="ccf68-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="ccf68-468">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-469">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-470">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="ccf68-471">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-472">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="ccf68-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="ccf68-474">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-475">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-475">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-476">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-477">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-478">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-479">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-480">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-481">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-481">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-482">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-482">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-483">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-483">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-484">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-485">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-486">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-487">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="ccf68-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="ccf68-488">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-489">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-490">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-491">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-492">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-493">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-494">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-495">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="ccf68-496">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="ccf68-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="ccf68-497">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="ccf68-498">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-499">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-500">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="ccf68-501"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="ccf68-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="ccf68-502">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="ccf68-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="ccf68-503">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-503">Documents</span></span> </li>
<li> <span data-ttu-id="ccf68-504">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="ccf68-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="ccf68-505">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-506">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-507">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="ccf68-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="ccf68-508">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="ccf68-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="ccf68-509">作成日</span><span class="sxs-lookup"><span data-stu-id="ccf68-509">Created date</span></span> </li>
<li> <span data-ttu-id="ccf68-510">更新日</span><span class="sxs-lookup"><span data-stu-id="ccf68-510">Modified date</span></span> </li>
<li> <span data-ttu-id="ccf68-511">作成者</span><span class="sxs-lookup"><span data-stu-id="ccf68-511">Created by</span></span> </li>
<li> <span data-ttu-id="ccf68-512">最終更新者</span><span class="sxs-lookup"><span data-stu-id="ccf68-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="ccf68-513">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="ccf68-514">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="ccf68-515">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="ccf68-516">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="ccf68-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="ccf68-517">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-518">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="ccf68-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="ccf68-519">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="ccf68-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="ccf68-520">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="ccf68-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="ccf68-521">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="ccf68-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="ccf68-522">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="ccf68-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="ccf68-523">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="ccf68-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="ccf68-524">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="ccf68-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="ccf68-525">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="ccf68-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="ccf68-526">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="ccf68-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="ccf68-527">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="ccf68-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="ccf68-528">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="ccf68-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="ccf68-529">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="ccf68-530">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="ccf68-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="ccf68-531">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="ccf68-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="ccf68-532">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="ccf68-532">FastTrack responsibilities</span></span>

<span data-ttu-id="ccf68-533">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="ccf68-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-534">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="ccf68-535">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="ccf68-535">Your responsibilities</span></span>

<span data-ttu-id="ccf68-536">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="ccf68-537">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ccf68-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="ccf68-538">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="ccf68-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="ccf68-539">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="ccf68-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
