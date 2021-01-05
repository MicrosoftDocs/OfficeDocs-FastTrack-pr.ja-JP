---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750044"
---
# <a name="data-migration"></a><span data-ttu-id="f3b84-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-104">Data Migration</span></span>

<span data-ttu-id="f3b84-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="f3b84-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="f3b84-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="f3b84-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="f3b84-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="f3b84-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="f3b84-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-111">You create and schedule your migration events.</span></span> <span data-ttu-id="f3b84-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="f3b84-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="f3b84-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="f3b84-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="f3b84-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f3b84-115">Considerations</span></span>

  - <span data-ttu-id="f3b84-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="f3b84-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="f3b84-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="f3b84-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="f3b84-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="f3b84-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="f3b84-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="f3b84-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="f3b84-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="f3b84-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="f3b84-124">Migration service availability</span></span>

  - <span data-ttu-id="f3b84-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="f3b84-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="f3b84-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="f3b84-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="f3b84-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-127">Migration to Exchange Online</span></span>

<span data-ttu-id="f3b84-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3b84-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="f3b84-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-130">You create and schedule your migration events.</span></span> <span data-ttu-id="f3b84-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3b84-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="f3b84-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f3b84-133">Considerations</span></span>

  - <span data-ttu-id="f3b84-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="f3b84-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f3b84-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="f3b84-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="f3b84-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="f3b84-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f3b84-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="f3b84-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="f3b84-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="f3b84-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="f3b84-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="f3b84-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="f3b84-143">Source environments</span></span>

<span data-ttu-id="f3b84-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="f3b84-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="f3b84-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="f3b84-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="f3b84-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="f3b84-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f3b84-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f3b84-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f3b84-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f3b84-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="f3b84-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3b84-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="f3b84-154">
<strong>注:</strong> オンプレミスの Exchange の依存関係については、「ハイブリッド展開の前提条件 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</span><span class="sxs-lookup"><span data-stu-id="f3b84-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="f3b84-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="f3b84-156">メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-156">Emails</span></span></li>
<li><span data-ttu-id="f3b84-157">メールボックスのルール</span><span class="sxs-lookup"><span data-stu-id="f3b84-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="f3b84-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f3b84-158">Delegates</span></span></li>
<li><span data-ttu-id="f3b84-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="f3b84-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f3b84-160">予定表</span><span class="sxs-lookup"><span data-stu-id="f3b84-160">Calendar</span></span> </li>
<li> <span data-ttu-id="f3b84-161">タスク</span><span class="sxs-lookup"><span data-stu-id="f3b84-161">Tasks</span></span> </li>
<li> <span data-ttu-id="f3b84-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="f3b84-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="f3b84-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="f3b84-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="f3b84-164">署名</span><span class="sxs-lookup"><span data-stu-id="f3b84-164">Signatures</span></span> </li>
<li> <span data-ttu-id="f3b84-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="f3b84-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="f3b84-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="f3b84-167">Public folders</span></span> </li>
<li> <span data-ttu-id="f3b84-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3b84-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="f3b84-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="f3b84-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f3b84-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="f3b84-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3b84-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f3b84-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3b84-174"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="f3b84-175">
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="f3b84-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="f3b84-176">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="f3b84-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-177">メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-177">Emails</span></span> </li>
<li> <span data-ttu-id="f3b84-178">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="f3b84-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="f3b84-179">カレンダー</span><span class="sxs-lookup"><span data-stu-id="f3b84-179">Calendar</span></span> </li>
<li> <span data-ttu-id="f3b84-180">ラベル</span><span class="sxs-lookup"><span data-stu-id="f3b84-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-181">ルール</span><span class="sxs-lookup"><span data-stu-id="f3b84-181">Rules</span></span> </li>
<li> <span data-ttu-id="f3b84-182">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f3b84-182">Delegates</span></span> </li>
<li> <span data-ttu-id="f3b84-183">署名</span><span class="sxs-lookup"><span data-stu-id="f3b84-183">Signatures</span></span> </li>
<li> <span data-ttu-id="f3b84-184">タスク</span><span class="sxs-lookup"><span data-stu-id="f3b84-184">Tasks</span></span> </li>
<li> <span data-ttu-id="f3b84-185">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3b84-186">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-187">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f3b84-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="f3b84-188">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="f3b84-189">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3b84-190">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="f3b84-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="f3b84-191">Google グループ</span><span class="sxs-lookup"><span data-stu-id="f3b84-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="f3b84-192">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="f3b84-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="f3b84-193">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f3b84-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="f3b84-194">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="f3b84-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="f3b84-195">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="f3b84-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="f3b84-196">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3b84-197"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="f3b84-198">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="f3b84-199">メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="f3b84-200">ルール</span><span class="sxs-lookup"><span data-stu-id="f3b84-200">Rules</span></span> </li>
<li> <span data-ttu-id="f3b84-201">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f3b84-201">Delegates</span></span> </li>
<li> <span data-ttu-id="f3b84-202">配布リスト</span><span class="sxs-lookup"><span data-stu-id="f3b84-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="f3b84-203">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="f3b84-203">External contacts</span></span> </li>
<li> <span data-ttu-id="f3b84-204">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="f3b84-205">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-206">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="f3b84-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f3b84-207">予定表</span><span class="sxs-lookup"><span data-stu-id="f3b84-207">Calendar</span></span> </li>
<li> <span data-ttu-id="f3b84-208">署名</span><span class="sxs-lookup"><span data-stu-id="f3b84-208">Signatures</span></span> </li>
<li> <span data-ttu-id="f3b84-209">タスク</span><span class="sxs-lookup"><span data-stu-id="f3b84-209">Tasks</span></span> </li>
<li> <span data-ttu-id="f3b84-210">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3b84-211">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f3b84-211">Archive data</span></span> </li>
<li> <span data-ttu-id="f3b84-212">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="f3b84-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="f3b84-213">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3b84-214">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f3b84-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3b84-215">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="f3b84-215">FastTrack responsibilities</span></span>

<span data-ttu-id="f3b84-216">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f3b84-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-217">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3b84-218">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="f3b84-219">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3b84-220">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f3b84-220">Your responsibilities</span></span>

<span data-ttu-id="f3b84-221">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-222">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3b84-223">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="f3b84-224">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="f3b84-225">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f3b84-226">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="f3b84-227">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="f3b84-228">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="f3b84-229">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f3b84-230">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="f3b84-231">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="f3b84-232">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="f3b84-233">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="f3b84-234">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="f3b84-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="f3b84-235">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="f3b84-236">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="f3b84-237">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="f3b84-238">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="f3b84-239">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3b84-240">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f3b84-241">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-241">You create and schedule your migration events.</span></span> <span data-ttu-id="f3b84-242">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3b84-243">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="f3b84-244">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f3b84-244">Considerations</span></span>

  - <span data-ttu-id="f3b84-245">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f3b84-246">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="f3b84-247">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="f3b84-248">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="f3b84-248">Source environment details</span></span>

<span data-ttu-id="f3b84-249">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f3b84-250">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f3b84-251">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f3b84-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f3b84-253">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f3b84-254">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f3b84-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f3b84-255"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f3b84-256"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f3b84-257"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f3b84-258"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3b84-259"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f3b84-260">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-261">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-261">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-262">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-263">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f3b84-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3b84-264">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f3b84-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3b84-265">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-266">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-267">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-267">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-268">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-268">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-269">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-269">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-270">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="f3b84-271">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="f3b84-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f3b84-272">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f3b84-273">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f3b84-274">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-275">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f3b84-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f3b84-276">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-277">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f3b84-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="f3b84-278">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="f3b84-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f3b84-279">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="f3b84-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f3b84-280">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="f3b84-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f3b84-281">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="f3b84-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f3b84-282">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f3b84-283">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-284">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="f3b84-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f3b84-285">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="f3b84-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f3b84-286">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3b84-287"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f3b84-288">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-289">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="f3b84-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="f3b84-290">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-291">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-292">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-293">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-294">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-295">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-295">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-296">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-296">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-297">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-297">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-298">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-299">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="f3b84-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f3b84-300">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-301">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-302">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="f3b84-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f3b84-303">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-304">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-305">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-306">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-307">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-308">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-309">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-310">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-311">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="f3b84-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f3b84-312">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="f3b84-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f3b84-313">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f3b84-314">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f3b84-315">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-316">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-317">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f3b84-318">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-319">制限付きまたはコピー不可としてマークされたファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="f3b84-320">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3b84-321"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f3b84-322">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-323">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-323">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-324">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-325">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-326">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-327">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-328">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-329">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-329">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-330">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-330">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-331">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-331">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-332">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-333">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="f3b84-334">Box Notes (Word 文書形式に変換)</span><span class="sxs-lookup"><span data-stu-id="f3b84-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-335">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-336">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f3b84-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3b84-337">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-338">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-339">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-340">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-341">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-342">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-343">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-344">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-345">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="f3b84-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f3b84-346">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f3b84-347">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-348">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-349">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3b84-350"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f3b84-351">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-352">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-352">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-353">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-354">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-355">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-356">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-357">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-358">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-358">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-359">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-359">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-360">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-360">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-361">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-362">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f3b84-363">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-364">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-365">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f3b84-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3b84-366">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-367">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-368">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-369">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-370">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-371">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-372">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-373">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="f3b84-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f3b84-374">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f3b84-375">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="f3b84-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f3b84-376">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="f3b84-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f3b84-377">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f3b84-378">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-379">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="f3b84-380">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3b84-381">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="f3b84-381">FastTrack responsibilities</span></span>

<span data-ttu-id="f3b84-382">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f3b84-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-383">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="f3b84-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3b84-384">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f3b84-384">Your responsibilities</span></span>

<span data-ttu-id="f3b84-385">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-386">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="f3b84-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="f3b84-387">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="f3b84-388">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="f3b84-389">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="f3b84-390">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3b84-391">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f3b84-392">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-392">You create and schedule your migration events.</span></span> <span data-ttu-id="f3b84-393">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3b84-394">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="f3b84-395">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f3b84-395">Considerations</span></span>

  - <span data-ttu-id="f3b84-396">すべての移行には OneDrive for Business のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="f3b84-397">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="f3b84-398">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="f3b84-399">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="f3b84-400">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="f3b84-400">Source environment details</span></span>

<span data-ttu-id="f3b84-401">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f3b84-402">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f3b84-403">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f3b84-404">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f3b84-405">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="f3b84-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f3b84-406">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f3b84-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="f3b84-407"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="f3b84-408"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="f3b84-409"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f3b84-410"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3b84-411"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f3b84-412">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-413">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-413">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-414">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-415">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f3b84-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3b84-416">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f3b84-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3b84-417">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-418">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-419">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-419">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-420">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-420">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-421">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-421">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-422">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="f3b84-423">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="f3b84-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f3b84-424">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f3b84-425">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="f3b84-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f3b84-426">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f3b84-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="f3b84-427">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f3b84-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f3b84-428">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-429">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f3b84-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="f3b84-430">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="f3b84-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f3b84-431">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="f3b84-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f3b84-432">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="f3b84-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f3b84-433">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="f3b84-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f3b84-434">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f3b84-435">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-436">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="f3b84-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f3b84-437">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="f3b84-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f3b84-438">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3b84-439"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f3b84-440">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-441">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="f3b84-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="f3b84-442">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-443">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-444">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-445">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-446">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-447">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-447">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-448">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-448">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-449">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-449">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-450">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-451">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="f3b84-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f3b84-452">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-453">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-454">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="f3b84-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f3b84-455">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-456">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-457">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-458">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-459">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-460">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-461">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-462">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-463">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="f3b84-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f3b84-464">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="f3b84-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f3b84-465">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f3b84-466">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="f3b84-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f3b84-467">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-468">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-469">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f3b84-470">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-471">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3b84-472"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f3b84-473">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-474">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-474">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-475">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-476">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-477">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-478">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-479">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-480">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-480">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-481">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-481">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-482">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-482">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-483">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-484">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-485">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-486">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f3b84-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3b84-487">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-488">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-489">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-490">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-491">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-492">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-493">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-494">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3b84-495">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="f3b84-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f3b84-496">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f3b84-497">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-498">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-499">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3b84-500"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="f3b84-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f3b84-501">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f3b84-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3b84-502">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-502">Documents</span></span> </li>
<li> <span data-ttu-id="f3b84-503">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f3b84-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3b84-504">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-505">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-506">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f3b84-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3b84-507">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f3b84-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3b84-508">作成日</span><span class="sxs-lookup"><span data-stu-id="f3b84-508">Created date</span></span> </li>
<li> <span data-ttu-id="f3b84-509">更新日</span><span class="sxs-lookup"><span data-stu-id="f3b84-509">Modified date</span></span> </li>
<li> <span data-ttu-id="f3b84-510">作成者</span><span class="sxs-lookup"><span data-stu-id="f3b84-510">Created by</span></span> </li>
<li> <span data-ttu-id="f3b84-511">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f3b84-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3b84-512">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f3b84-513">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3b84-514">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3b84-515">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f3b84-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3b84-516">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-517">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f3b84-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3b84-518">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f3b84-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3b84-519">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f3b84-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3b84-520">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f3b84-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3b84-521">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f3b84-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3b84-522">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f3b84-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3b84-523">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="f3b84-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f3b84-524">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="f3b84-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f3b84-525">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="f3b84-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f3b84-526">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="f3b84-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f3b84-527">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f3b84-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f3b84-528">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f3b84-529">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f3b84-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3b84-530">現在の <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online の制限と制限を超えるファイルまたはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3b84-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3b84-531">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="f3b84-531">FastTrack responsibilities</span></span>

<span data-ttu-id="f3b84-532">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f3b84-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-533">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3b84-534">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f3b84-534">Your responsibilities</span></span>

<span data-ttu-id="f3b84-535">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3b84-536">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f3b84-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3b84-537">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f3b84-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="f3b84-538">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="f3b84-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
