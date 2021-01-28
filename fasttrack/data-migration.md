---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016473"
---
# <a name="data-migration"></a><span data-ttu-id="3f296-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="3f296-104">Data Migration</span></span>

<span data-ttu-id="3f296-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="3f296-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="3f296-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="3f296-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="3f296-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="3f296-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="3f296-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="3f296-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="3f296-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="3f296-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="3f296-111">You create and schedule your migration events.</span></span> <span data-ttu-id="3f296-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="3f296-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="3f296-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="3f296-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="3f296-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="3f296-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="3f296-115">Considerations</span></span>

  - <span data-ttu-id="3f296-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="3f296-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="3f296-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="3f296-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="3f296-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="3f296-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="3f296-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="3f296-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="3f296-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="3f296-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="3f296-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="3f296-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="3f296-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="3f296-124">Migration service availability</span></span>

  - <span data-ttu-id="3f296-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="3f296-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="3f296-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="3f296-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="3f296-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="3f296-127">Migration to Exchange Online</span></span>

<span data-ttu-id="3f296-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3f296-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="3f296-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="3f296-130">You create and schedule your migration events.</span></span> <span data-ttu-id="3f296-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3f296-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="3f296-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3f296-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="3f296-133">Considerations</span></span>

  - <span data-ttu-id="3f296-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="3f296-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3f296-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="3f296-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="3f296-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="3f296-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3f296-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="3f296-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="3f296-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="3f296-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="3f296-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="3f296-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="3f296-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="3f296-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="3f296-143">Source environments</span></span>

<span data-ttu-id="3f296-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="3f296-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="3f296-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="3f296-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="3f296-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="3f296-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="3f296-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="3f296-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="3f296-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3f296-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3f296-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3f296-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="3f296-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3f296-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="3f296-154">
<strong>注:</strong> オンプレミスの Exchange の依存関係については、「ハイブリッド展開の前提条件 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</span><span class="sxs-lookup"><span data-stu-id="3f296-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="3f296-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="3f296-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="3f296-156">メール</span><span class="sxs-lookup"><span data-stu-id="3f296-156">Emails</span></span></li>
<li><span data-ttu-id="3f296-157">サーバー側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="3f296-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="3f296-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="3f296-158">Delegates</span></span></li>
<li><span data-ttu-id="3f296-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="3f296-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3f296-160">予定表</span><span class="sxs-lookup"><span data-stu-id="3f296-160">Calendar</span></span> </li>
<li> <span data-ttu-id="3f296-161">タスク</span><span class="sxs-lookup"><span data-stu-id="3f296-161">Tasks</span></span> </li>
<li> <span data-ttu-id="3f296-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="3f296-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="3f296-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="3f296-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="3f296-164">署名</span><span class="sxs-lookup"><span data-stu-id="3f296-164">Signatures</span></span> </li>
<li> <span data-ttu-id="3f296-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="3f296-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="3f296-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="3f296-167">Public folders</span></span> </li>
<li> <span data-ttu-id="3f296-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="3f296-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3f296-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="3f296-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="3f296-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="3f296-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="3f296-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3f296-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="3f296-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3f296-174">クライアント側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="3f296-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3f296-175"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="3f296-176">
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="3f296-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="3f296-177">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="3f296-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-178">メール</span><span class="sxs-lookup"><span data-stu-id="3f296-178">Emails</span></span> </li>
<li> <span data-ttu-id="3f296-179">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="3f296-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="3f296-180">カレンダー</span><span class="sxs-lookup"><span data-stu-id="3f296-180">Calendar</span></span> </li>
<li> <span data-ttu-id="3f296-181">ラベル</span><span class="sxs-lookup"><span data-stu-id="3f296-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-182">ルール</span><span class="sxs-lookup"><span data-stu-id="3f296-182">Rules</span></span> </li>
<li> <span data-ttu-id="3f296-183">デリゲート</span><span class="sxs-lookup"><span data-stu-id="3f296-183">Delegates</span></span> </li>
<li> <span data-ttu-id="3f296-184">署名</span><span class="sxs-lookup"><span data-stu-id="3f296-184">Signatures</span></span> </li>
<li> <span data-ttu-id="3f296-185">タスク</span><span class="sxs-lookup"><span data-stu-id="3f296-185">Tasks</span></span> </li>
<li> <span data-ttu-id="3f296-186">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3f296-187">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-188">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="3f296-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="3f296-189">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="3f296-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="3f296-190">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3f296-191">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="3f296-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="3f296-192">Google グループ</span><span class="sxs-lookup"><span data-stu-id="3f296-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="3f296-193">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="3f296-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="3f296-194">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="3f296-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3f296-195">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="3f296-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="3f296-196">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="3f296-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="3f296-197">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3f296-198"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="3f296-199">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="3f296-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="3f296-200">メール</span><span class="sxs-lookup"><span data-stu-id="3f296-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="3f296-201">ルール</span><span class="sxs-lookup"><span data-stu-id="3f296-201">Rules</span></span> </li>
<li> <span data-ttu-id="3f296-202">デリゲート</span><span class="sxs-lookup"><span data-stu-id="3f296-202">Delegates</span></span> </li>
<li> <span data-ttu-id="3f296-203">配布リスト</span><span class="sxs-lookup"><span data-stu-id="3f296-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="3f296-204">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="3f296-204">External contacts</span></span> </li>
<li> <span data-ttu-id="3f296-205">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="3f296-206">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-207">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="3f296-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3f296-208">予定表</span><span class="sxs-lookup"><span data-stu-id="3f296-208">Calendar</span></span> </li>
<li> <span data-ttu-id="3f296-209">署名</span><span class="sxs-lookup"><span data-stu-id="3f296-209">Signatures</span></span> </li>
<li> <span data-ttu-id="3f296-210">タスク</span><span class="sxs-lookup"><span data-stu-id="3f296-210">Tasks</span></span> </li>
<li> <span data-ttu-id="3f296-211">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="3f296-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3f296-212">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="3f296-212">Archive data</span></span> </li>
<li> <span data-ttu-id="3f296-213">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="3f296-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="3f296-214">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3f296-215">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="3f296-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3f296-216">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="3f296-216">FastTrack responsibilities</span></span>

<span data-ttu-id="3f296-217">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="3f296-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-218">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3f296-219">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="3f296-220">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3f296-221">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="3f296-221">Your responsibilities</span></span>

<span data-ttu-id="3f296-222">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-223">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3f296-224">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="3f296-225">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="3f296-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="3f296-226">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3f296-227">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="3f296-228">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="3f296-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="3f296-229">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="3f296-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="3f296-230">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="3f296-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3f296-231">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="3f296-232">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="3f296-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="3f296-233">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="3f296-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="3f296-234">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="3f296-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="3f296-235">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f296-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="3f296-236">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="3f296-237">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="3f296-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="3f296-238">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="3f296-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="3f296-239">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="3f296-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="3f296-240">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3f296-241">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3f296-242">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="3f296-242">You create and schedule your migration events.</span></span> <span data-ttu-id="3f296-243">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3f296-244">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="3f296-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="3f296-245">考慮事項</span><span class="sxs-lookup"><span data-stu-id="3f296-245">Considerations</span></span>

  - <span data-ttu-id="3f296-246">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3f296-247">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3f296-248">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3f296-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3f296-249">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="3f296-249">Source environment details</span></span>

<span data-ttu-id="3f296-250">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3f296-251">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="3f296-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3f296-252">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="3f296-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3f296-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="3f296-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3f296-254">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="3f296-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3f296-255">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="3f296-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3f296-256"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3f296-257"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3f296-258"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3f296-259"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3f296-260"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3f296-261">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-262">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-262">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-263">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-264">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="3f296-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3f296-265">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="3f296-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3f296-266">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-267">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-268">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-268">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-269">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-269">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-270">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-270">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-271">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="3f296-272">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="3f296-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3f296-273">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3f296-274">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="3f296-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3f296-275">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-276">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="3f296-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3f296-277">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-278">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="3f296-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="3f296-279">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="3f296-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3f296-280">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="3f296-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3f296-281">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="3f296-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3f296-282">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="3f296-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3f296-283">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3f296-284">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-285">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="3f296-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3f296-286">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="3f296-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3f296-287">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3f296-288"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3f296-289">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-290">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="3f296-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="3f296-291">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-292">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-293">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-294">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-295">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-296">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-296">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-297">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-297">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-298">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-298">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-299">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-300">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="3f296-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3f296-301">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-302">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-303">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="3f296-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3f296-304">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-305">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-306">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-307">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-308">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-309">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-310">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-311">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-312">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="3f296-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3f296-313">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="3f296-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3f296-314">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3f296-315">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="3f296-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3f296-316">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-317">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-318">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="3f296-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3f296-319">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="3f296-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-320">制限付きまたはコピー不可としてマークされたファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="3f296-321">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3f296-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3f296-323">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-324">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-324">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-325">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-326">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-327">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-328">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-329">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-330">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-330">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-331">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-331">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-332">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-332">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-333">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-334">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3f296-335">Box Notes (Word 文書形式に変換)</span><span class="sxs-lookup"><span data-stu-id="3f296-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-336">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-337">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="3f296-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3f296-338">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-339">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-340">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-341">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-342">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-343">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-344">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-345">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-346">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="3f296-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3f296-347">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3f296-348">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-349">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-350">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3f296-351"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3f296-352">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-353">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-353">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-354">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-355">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-356">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-357">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-358">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-359">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-359">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-360">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-360">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-361">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-361">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-362">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-363">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3f296-364">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-365">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-366">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="3f296-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3f296-367">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-368">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-369">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-370">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-371">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-372">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-373">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-374">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="3f296-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3f296-375">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3f296-376">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="3f296-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3f296-377">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="3f296-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3f296-378">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3f296-379">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-380">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="3f296-381">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3f296-382">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="3f296-382">FastTrack responsibilities</span></span>

<span data-ttu-id="3f296-383">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="3f296-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-384">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="3f296-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3f296-385">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="3f296-385">Your responsibilities</span></span>

<span data-ttu-id="3f296-386">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-387">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="3f296-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="3f296-388">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="3f296-389">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="3f296-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="3f296-390">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="3f296-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="3f296-391">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3f296-392">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3f296-393">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="3f296-393">You create and schedule your migration events.</span></span> <span data-ttu-id="3f296-394">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="3f296-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3f296-395">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="3f296-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="3f296-396">考慮事項</span><span class="sxs-lookup"><span data-stu-id="3f296-396">Considerations</span></span>

  - <span data-ttu-id="3f296-397">すべての移行には OneDrive for Business のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="3f296-398">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3f296-399">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3f296-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="3f296-400">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3f296-401">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="3f296-401">Source environment details</span></span>

<span data-ttu-id="3f296-402">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3f296-403">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="3f296-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3f296-404">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="3f296-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3f296-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="3f296-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3f296-406">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="3f296-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3f296-407">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="3f296-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3f296-408"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3f296-409"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3f296-410"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3f296-411"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3f296-412"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3f296-413">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-414">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-414">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-415">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-416">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="3f296-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3f296-417">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="3f296-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3f296-418">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-419">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-420">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-420">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-421">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-421">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-422">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-422">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-423">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3f296-424">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="3f296-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3f296-425">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3f296-426">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="3f296-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3f296-427">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="3f296-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3f296-428">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="3f296-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3f296-429">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-430">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="3f296-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="3f296-431">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="3f296-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3f296-432">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="3f296-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3f296-433">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="3f296-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3f296-434">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="3f296-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3f296-435">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3f296-436">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-437">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="3f296-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3f296-438">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="3f296-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3f296-439">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3f296-440"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3f296-441">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-442">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="3f296-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3f296-443">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-444">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-445">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-446">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-447">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-448">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-448">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-449">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-449">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-450">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-450">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-451">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-452">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="3f296-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3f296-453">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-454">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-455">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="3f296-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3f296-456">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-457">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-458">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-459">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-460">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-461">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-462">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-463">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-464">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="3f296-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3f296-465">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="3f296-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3f296-466">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3f296-467">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="3f296-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3f296-468">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-469">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-470">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="3f296-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3f296-471">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="3f296-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-472">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3f296-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3f296-474">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-475">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-475">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-476">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-477">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-478">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-479">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-480">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-481">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-481">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-482">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-482">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-483">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-483">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-484">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-485">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-486">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-487">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="3f296-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3f296-488">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-489">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-490">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-491">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-492">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-493">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-494">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-495">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3f296-496">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="3f296-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3f296-497">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3f296-498">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-499">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-500">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3f296-501"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="3f296-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3f296-502">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="3f296-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3f296-503">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-503">Documents</span></span> </li>
<li> <span data-ttu-id="3f296-504">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="3f296-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3f296-505">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-506">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3f296-507">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="3f296-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3f296-508">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="3f296-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3f296-509">作成日</span><span class="sxs-lookup"><span data-stu-id="3f296-509">Created date</span></span> </li>
<li> <span data-ttu-id="3f296-510">更新日</span><span class="sxs-lookup"><span data-stu-id="3f296-510">Modified date</span></span> </li>
<li> <span data-ttu-id="3f296-511">作成者</span><span class="sxs-lookup"><span data-stu-id="3f296-511">Created by</span></span> </li>
<li> <span data-ttu-id="3f296-512">最終更新者</span><span class="sxs-lookup"><span data-stu-id="3f296-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3f296-513">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3f296-514">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3f296-515">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="3f296-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3f296-516">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="3f296-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3f296-517">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-518">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="3f296-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3f296-519">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="3f296-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3f296-520">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="3f296-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3f296-521">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="3f296-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3f296-522">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="3f296-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="3f296-523">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="3f296-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3f296-524">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="3f296-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3f296-525">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="3f296-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3f296-526">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="3f296-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3f296-527">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="3f296-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3f296-528">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="3f296-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3f296-529">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="3f296-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3f296-530">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="3f296-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3f296-531">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="3f296-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3f296-532">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="3f296-532">FastTrack responsibilities</span></span>

<span data-ttu-id="3f296-533">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="3f296-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-534">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3f296-535">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="3f296-535">Your responsibilities</span></span>

<span data-ttu-id="3f296-536">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3f296-537">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f296-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3f296-538">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="3f296-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="3f296-539">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="3f296-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
