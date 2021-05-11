---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: 0e33e8a79ebc577188644dbc69cd78707a575838
ms.sourcegitcommit: 69a30fee5e7e199bd6830fb0837af1ae4904ef3b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/11/2021
ms.locfileid: "52312445"
---
# <a name="data-migration"></a><span data-ttu-id="f47e6-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-104">Data Migration</span></span>

<span data-ttu-id="f47e6-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="f47e6-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="f47e6-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="f47e6-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="f47e6-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="f47e6-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="f47e6-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-111">You create and schedule your migration events.</span></span> <span data-ttu-id="f47e6-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="f47e6-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="f47e6-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="f47e6-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="f47e6-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f47e6-115">Considerations</span></span>

  - <span data-ttu-id="f47e6-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="f47e6-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="f47e6-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="f47e6-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="f47e6-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="f47e6-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="f47e6-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="f47e6-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="f47e6-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="f47e6-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="f47e6-124">Migration service availability</span></span>

  - <span data-ttu-id="f47e6-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="f47e6-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="f47e6-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-127">Migration to Exchange Online</span></span>

<span data-ttu-id="f47e6-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f47e6-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="f47e6-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-130">You create and schedule your migration events.</span></span> <span data-ttu-id="f47e6-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f47e6-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="f47e6-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f47e6-133">Considerations</span></span>

  - <span data-ttu-id="f47e6-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="f47e6-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f47e6-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="f47e6-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="f47e6-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="f47e6-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f47e6-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="f47e6-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="f47e6-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="f47e6-141">オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="f47e6-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="f47e6-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="f47e6-143">Source environments</span></span>

<span data-ttu-id="f47e6-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="f47e6-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="f47e6-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="f47e6-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="f47e6-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="f47e6-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f47e6-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f47e6-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f47e6-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="f47e6-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f47e6-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="f47e6-154">
<strong>注:</strong>オンプレミスの依存関係については、「ハイブリッドExchange前提条件<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</span><span class="sxs-lookup"><span data-stu-id="f47e6-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="f47e6-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="f47e6-156">メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-156">Emails</span></span></li>
<li><span data-ttu-id="f47e6-157">サーバー側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="f47e6-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="f47e6-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f47e6-158">Delegates</span></span></li>
<li><span data-ttu-id="f47e6-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="f47e6-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f47e6-160">予定表</span><span class="sxs-lookup"><span data-stu-id="f47e6-160">Calendar</span></span> </li>
<li> <span data-ttu-id="f47e6-161">タスク</span><span class="sxs-lookup"><span data-stu-id="f47e6-161">Tasks</span></span> </li>
<li> <span data-ttu-id="f47e6-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="f47e6-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="f47e6-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="f47e6-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="f47e6-164">署名</span><span class="sxs-lookup"><span data-stu-id="f47e6-164">Signatures</span></span> </li>
<li> <span data-ttu-id="f47e6-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="f47e6-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="f47e6-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="f47e6-167">Public folders</span></span> </li>
<li> <span data-ttu-id="f47e6-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f47e6-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="f47e6-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="f47e6-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f47e6-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="f47e6-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f47e6-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f47e6-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="f47e6-174">クライアント側のメールボックス ルール</span><span class="sxs-lookup"><span data-stu-id="f47e6-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-175"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="f47e6-176">
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</span><span class="sxs-lookup"><span data-stu-id="f47e6-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="f47e6-177">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="f47e6-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-178">メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-178">Emails</span></span> </li>
<li> <span data-ttu-id="f47e6-179">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="f47e6-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="f47e6-180">カレンダー</span><span class="sxs-lookup"><span data-stu-id="f47e6-180">Calendar</span></span> </li>
<li> <span data-ttu-id="f47e6-181">ラベル</span><span class="sxs-lookup"><span data-stu-id="f47e6-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-182">ルール</span><span class="sxs-lookup"><span data-stu-id="f47e6-182">Rules</span></span> </li>
<li> <span data-ttu-id="f47e6-183">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f47e6-183">Delegates</span></span> </li>
<li> <span data-ttu-id="f47e6-184">署名</span><span class="sxs-lookup"><span data-stu-id="f47e6-184">Signatures</span></span> </li>
<li> <span data-ttu-id="f47e6-185">タスク</span><span class="sxs-lookup"><span data-stu-id="f47e6-185">Tasks</span></span> </li>
<li> <span data-ttu-id="f47e6-186">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f47e6-187">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-188">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f47e6-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="f47e6-189">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="f47e6-190">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f47e6-191">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="f47e6-192">Google グループ</span><span class="sxs-lookup"><span data-stu-id="f47e6-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="f47e6-193">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="f47e6-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="f47e6-194">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f47e6-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="f47e6-195">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="f47e6-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="f47e6-196">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="f47e6-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="f47e6-197">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f47e6-198"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="f47e6-199">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="f47e6-200">メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="f47e6-201">ルール</span><span class="sxs-lookup"><span data-stu-id="f47e6-201">Rules</span></span> </li>
<li> <span data-ttu-id="f47e6-202">デリゲート</span><span class="sxs-lookup"><span data-stu-id="f47e6-202">Delegates</span></span> </li>
<li> <span data-ttu-id="f47e6-203">配布リスト</span><span class="sxs-lookup"><span data-stu-id="f47e6-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="f47e6-204">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="f47e6-204">External contacts</span></span> </li>
<li> <span data-ttu-id="f47e6-205">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="f47e6-206">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-207">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="f47e6-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f47e6-208">予定表</span><span class="sxs-lookup"><span data-stu-id="f47e6-208">Calendar</span></span> </li>
<li> <span data-ttu-id="f47e6-209">署名</span><span class="sxs-lookup"><span data-stu-id="f47e6-209">Signatures</span></span> </li>
<li> <span data-ttu-id="f47e6-210">タスク</span><span class="sxs-lookup"><span data-stu-id="f47e6-210">Tasks</span></span> </li>
<li> <span data-ttu-id="f47e6-211">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f47e6-212">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="f47e6-212">Archive data</span></span> </li>
<li> <span data-ttu-id="f47e6-213">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="f47e6-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="f47e6-214">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f47e6-215">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="f47e6-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="f47e6-216">移行に関する FastTrack Exchange Online責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="f47e6-217">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f47e6-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-218">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f47e6-219">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="f47e6-220">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="f47e6-221">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-221">Your responsibilities</span></span>

<span data-ttu-id="f47e6-222">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-223">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f47e6-224">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="f47e6-225">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="f47e6-226">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f47e6-227">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="f47e6-228">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="f47e6-229">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="f47e6-230">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f47e6-231">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="f47e6-232">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="f47e6-233">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="f47e6-234">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="f47e6-235">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="f47e6-236">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="f47e6-237">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="f47e6-238">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="f47e6-239">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="f47e6-240">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f47e6-241">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f47e6-242">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-242">You create and schedule your migration events.</span></span> <span data-ttu-id="f47e6-243">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f47e6-244">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="f47e6-245">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f47e6-245">Considerations</span></span>

 - <span data-ttu-id="f47e6-246">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f47e6-247">詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="f47e6-248">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="f47e6-249">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="f47e6-249">Source environment details</span></span>

<span data-ttu-id="f47e6-250">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f47e6-251">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f47e6-252">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f47e6-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f47e6-254">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f47e6-255">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f47e6-256"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f47e6-257"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f47e6-258"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f47e6-259"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f47e6-260"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f47e6-261">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-262">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-262">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-263">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-264">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-265">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-266">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-267">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-268">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-268">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-269">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-269">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-270">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-270">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-271">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="f47e6-272">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="f47e6-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f47e6-273">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f47e6-274">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f47e6-275">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-276">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-277">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-278">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-279">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f47e6-280">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="f47e6-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f47e6-281">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="f47e6-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f47e6-282">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="f47e6-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f47e6-283">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f47e6-284">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-285">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="f47e6-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f47e6-286">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f47e6-287">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-288"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f47e6-289">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-290">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="f47e6-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="f47e6-291">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-292">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-293">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-294">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-295">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-296">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-296">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-297">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-297">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-298">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-298">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-299">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-300">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="f47e6-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f47e6-301">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-302">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-303">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="f47e6-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f47e6-304">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-305">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-306">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-307">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-308">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-309">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-310">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-311">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-312">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="f47e6-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f47e6-313">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="f47e6-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f47e6-314">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f47e6-315">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f47e6-316">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-317">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-318">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f47e6-319">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-320">制限付きまたはコピー不可としてマークされたファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="f47e6-321">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f47e6-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f47e6-323">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-324">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-324">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-325">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-326">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-327">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-328">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-329">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-330">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-330">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-331">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-331">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-332">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-332">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-333">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-334">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="f47e6-335">Box Notes (Word ドキュメント形式に変換)</span><span class="sxs-lookup"><span data-stu-id="f47e6-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-336">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-337">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-338">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-339">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-340">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-341">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-342">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-343">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-344">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-345">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-346">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="f47e6-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f47e6-347">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f47e6-348">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-349">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-350">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-351"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f47e6-352">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-353">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-353">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-354">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-355">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-356">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-357">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-358">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-359">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-359">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-360">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-360">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-361">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-361">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-362">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-363">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f47e6-364">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-365">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-366">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-367">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-368">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-369">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-370">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-371">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-372">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-373">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-374">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="f47e6-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f47e6-375">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f47e6-376">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="f47e6-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f47e6-377">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="f47e6-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f47e6-378">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f47e6-379">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-380">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="f47e6-381">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="f47e6-382">FastTrack のオンライン移行SharePoint責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="f47e6-383">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f47e6-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-384">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="f47e6-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="f47e6-385">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-385">Your responsibilities</span></span>

<span data-ttu-id="f47e6-386">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-387">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="f47e6-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="f47e6-388">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="f47e6-389">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="f47e6-390">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="f47e6-391">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f47e6-392">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f47e6-393">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-393">You create and schedule your migration events.</span></span> <span data-ttu-id="f47e6-394">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f47e6-395">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="f47e6-396">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f47e6-396">Considerations</span></span>

  - <span data-ttu-id="f47e6-397">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f47e6-398">詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="f47e6-399">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="f47e6-400">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="f47e6-401">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="f47e6-401">Source environment details</span></span>

<span data-ttu-id="f47e6-402">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f47e6-403">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f47e6-404">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f47e6-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f47e6-406">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f47e6-407">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="f47e6-408"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="f47e6-409"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="f47e6-410"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f47e6-411"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f47e6-412"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f47e6-413">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-414">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-414">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-415">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-416">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-417">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-418">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-419">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-420">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-420">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-421">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-421">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-422">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-422">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-423">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="f47e6-424">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="f47e6-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f47e6-425">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f47e6-426">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f47e6-427">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="f47e6-428">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-429">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-430">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-431">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f47e6-432">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="f47e6-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f47e6-433">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="f47e6-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f47e6-434">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="f47e6-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f47e6-435">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f47e6-436">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-437">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="f47e6-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f47e6-438">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f47e6-439">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-440"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f47e6-441">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-442">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="f47e6-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="f47e6-443">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-444">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-445">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-446">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-447">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-448">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-448">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-449">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-449">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-450">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-450">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-451">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-452">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="f47e6-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f47e6-453">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-454">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-455">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="f47e6-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f47e6-456">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-457">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-458">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-459">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-460">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-461">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-462">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-463">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-464">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="f47e6-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f47e6-465">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="f47e6-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f47e6-466">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f47e6-467">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f47e6-468">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-469">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-470">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f47e6-471">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-472">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f47e6-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f47e6-474">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-475">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-475">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-476">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-477">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-478">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-479">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-480">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-481">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-481">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-482">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-482">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-483">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-483">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-484">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-485">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-486">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-487">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-488">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-489">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-490">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-491">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-492">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-493">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-494">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-495">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-496">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="f47e6-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f47e6-497">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f47e6-498">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-499">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-500">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-501"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f47e6-502">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-503">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-503">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-504">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-505">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-506">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-507">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-508">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-509">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-509">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-510">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-510">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-511">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-511">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-512">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-513">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f47e6-514">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f47e6-515">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-516">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-517">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-518">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-519">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-520">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-521">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-522">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-523">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-524">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="f47e6-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f47e6-525">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f47e6-526">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="f47e6-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f47e6-527">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="f47e6-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f47e6-528">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f47e6-529">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-530">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-531">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="f47e6-532">FastTrack の移行に対するOneDrive for Business責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="f47e6-533">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f47e6-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-534">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="f47e6-535">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-535">Your responsibilities</span></span>

<span data-ttu-id="f47e6-536">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-537">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f47e6-538">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="f47e6-539">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="f47e6-540">グループとMicrosoft TeamsグループMicrosoft 365移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="f47e6-541">FastTrack を使用してファイルを Microsoft Teams グループMicrosoft 365移行する場合は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f47e6-542">移行を計画し、ソース環境と Teams グループと Microsoft 365 グループを構成し、データ移行サービスを活用してファイルを移行するのに役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f47e6-543">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-543">You create and schedule your migration events.</span></span> <span data-ttu-id="f47e6-544">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f47e6-545">移行イベントが完了すると、ソース環境の適切にスケジュールされた適格なソースからのファイルが Teams および Microsoft 365 グループに移行されたと予想できます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="f47e6-546">Teamsおよび Microsoft 365グループは、これらの移行先の種類にデータを移行する前に、お客様が事前に準備する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="f47e6-547">TeamsグループMicrosoft 365グループは、ファイルの保存先の場所に対するアクセス許可に影響します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="f47e6-548">TeamsグループMicrosoft 365グループは、コラボレーションを可能にするために構築されています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="f47e6-549">このTeamsまたはMicrosoft 365グループは、それらの宛先に移行するときに、それらのファイルにアクセスできるユーザーを決定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="f47e6-550">FastTrack は、移行中にエンド ユーザーまたはグループをTeamsグループMicrosoft 365アクセス許可に追加しない。</span><span class="sxs-lookup"><span data-stu-id="f47e6-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="f47e6-551">考慮事項</span><span class="sxs-lookup"><span data-stu-id="f47e6-551">Considerations</span></span>

- <span data-ttu-id="f47e6-552">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f47e6-553">詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="f47e6-554">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="f47e6-555">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="f47e6-555">Source environment details</span></span>

<span data-ttu-id="f47e6-556">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="f47e6-557">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="f47e6-558">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="f47e6-559">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="f47e6-560">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="f47e6-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="f47e6-561">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="f47e6-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="f47e6-562"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="f47e6-563"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="f47e6-564"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f47e6-565"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f47e6-566"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f47e6-567">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-568">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-568">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-569">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-570">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-571">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-572">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-573">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-574">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-574">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-575">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-575">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-576">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-576">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-577">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="f47e6-578">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="f47e6-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f47e6-579">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f47e6-580">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="f47e6-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f47e6-581">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="f47e6-582">アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f47e6-583">移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f47e6-584">グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-585">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-586">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-587">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="f47e6-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="f47e6-588">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f47e6-589">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="f47e6-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f47e6-590">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="f47e6-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f47e6-591">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="f47e6-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f47e6-592">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f47e6-593">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-594">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="f47e6-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f47e6-595">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="f47e6-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f47e6-596">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-597"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f47e6-598">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-599">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="f47e6-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="f47e6-600">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-601">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-602">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-603">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-604">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-605">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-605">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-606">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-606">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-607">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-607">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-608">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-609">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="f47e6-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f47e6-610">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="f47e6-611">\*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f47e6-612">移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f47e6-613">グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="f47e6-614">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-615">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="f47e6-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f47e6-616">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-617">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-618">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-619">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-620">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-621">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-622">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-623">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-624">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="f47e6-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f47e6-625">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="f47e6-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f47e6-626">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f47e6-627">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="f47e6-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f47e6-628">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-629">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-630">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f47e6-631">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-632">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f47e6-633"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f47e6-634">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-635">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-635">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-636">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-637">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-638">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-639">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-640">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-641">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-641">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-642">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-642">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-643">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-643">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-644">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-645">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="f47e6-646">Box Notes (Word ドキュメント形式に変換)</span><span class="sxs-lookup"><span data-stu-id="f47e6-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="f47e6-647">\*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f47e6-648">移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f47e6-649">グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="f47e6-650">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-651">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-652">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-653">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-654">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-655">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-656">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-657">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-658">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-659">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f47e6-660">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="f47e6-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f47e6-661">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f47e6-662">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-663">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-664">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f47e6-665"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="f47e6-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f47e6-666">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="f47e6-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f47e6-667">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-667">Documents</span></span> </li>
<li> <span data-ttu-id="f47e6-668">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="f47e6-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f47e6-669">ユーザー レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-670">グループ レベルのフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="f47e6-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f47e6-671">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="f47e6-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f47e6-672">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="f47e6-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f47e6-673">作成日</span><span class="sxs-lookup"><span data-stu-id="f47e6-673">Created date</span></span> </li>
<li> <span data-ttu-id="f47e6-674">更新日</span><span class="sxs-lookup"><span data-stu-id="f47e6-674">Modified date</span></span> </li>
<li> <span data-ttu-id="f47e6-675">作成者</span><span class="sxs-lookup"><span data-stu-id="f47e6-675">Created by</span></span> </li>
<li> <span data-ttu-id="f47e6-676">最終更新者</span><span class="sxs-lookup"><span data-stu-id="f47e6-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f47e6-677">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f47e6-678">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="f47e6-679">\*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f47e6-680">移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="f47e6-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f47e6-681">グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="f47e6-682">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f47e6-683">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="f47e6-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f47e6-684">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-685">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f47e6-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f47e6-686">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="f47e6-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f47e6-687">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="f47e6-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f47e6-688">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="f47e6-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f47e6-689">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="f47e6-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="f47e6-690">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="f47e6-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f47e6-691">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="f47e6-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f47e6-692">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="f47e6-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f47e6-693">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="f47e6-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f47e6-694">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="f47e6-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f47e6-695">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="f47e6-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f47e6-696">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f47e6-697">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="f47e6-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f47e6-698">オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </span><span class="sxs-lookup"><span data-stu-id="f47e6-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="f47e6-699">FastTrack のグループの移行Microsoft TeamsおよびMicrosoft 365の責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="f47e6-700">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="f47e6-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-701">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="f47e6-702">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="f47e6-702">Your responsibilities</span></span> 

<span data-ttu-id="f47e6-703">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f47e6-704">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f47e6-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="f47e6-705">また、グループの移行に固有のMicrosoft TeamsアクティビティMicrosoft 365実行します。</span><span class="sxs-lookup"><span data-stu-id="f47e6-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="f47e6-706">移行イベントMicrosoft Teams対象Microsoft 365、すべてのチャネルとグループをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="f47e6-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="f47e6-707">FastTrack は、チャネルまたはグループのMicrosoft Teams準備Microsoft 365行わない。</span><span class="sxs-lookup"><span data-stu-id="f47e6-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="f47e6-708">FastTrack は、エンド ユーザーまたはグループをチャネルまたはグループMicrosoft Teams追加Microsoft 365行わない。</span><span class="sxs-lookup"><span data-stu-id="f47e6-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="f47e6-709">これらの移行先にデータを移行する前に、エンド ユーザーまたはグループをすべての Microsoft Teams チャネルと Microsoft 365 グループに追加して、それらのエンド ユーザーが新しく移行されたドキュメントにアクセスできる必要があります。</span><span class="sxs-lookup"><span data-stu-id="f47e6-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>