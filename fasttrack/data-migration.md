---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827659"
---
# <a name="data-migration"></a><span data-ttu-id="0e3a1-104">データ移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-104">Data Migration</span></span>

<span data-ttu-id="0e3a1-105">FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="0e3a1-106">提供するサポートの種類は、Office 365 ライセンスの数によって異なります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="0e3a1-107">**ライセンスの数が 150 - 499 個の Office 365 テナントの場合** : FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="0e3a1-108">セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="0e3a1-109">**ライセンスの数が 500 個以上の Office 365 テナントの場合** : FastTrack は、移行ガイダンスとデータ移行サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="0e3a1-110">移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="0e3a1-111">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-111">You create and schedule your migration events.</span></span> <span data-ttu-id="0e3a1-112">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="0e3a1-113">2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="0e3a1-114">教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="0e3a1-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="0e3a1-115">Considerations</span></span>

  - <span data-ttu-id="0e3a1-116">データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="0e3a1-117">Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="0e3a1-118">データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="0e3a1-119">当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="0e3a1-120">データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="0e3a1-121">Microsoft は、メールやファイルの移行速度を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="0e3a1-122">予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="0e3a1-123">当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="0e3a1-124">移行サービスの可用性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-124">Migration service availability</span></span>

  - <span data-ttu-id="0e3a1-125">**商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="0e3a1-126">**米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="0e3a1-127">Exchange Online への移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-127">Migration to Exchange Online</span></span>

<span data-ttu-id="0e3a1-128">FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0e3a1-129">移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="0e3a1-130">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-130">You create and schedule your migration events.</span></span> <span data-ttu-id="0e3a1-131">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0e3a1-132">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="0e3a1-133">考慮事項</span><span class="sxs-lookup"><span data-stu-id="0e3a1-133">Considerations</span></span>

  - <span data-ttu-id="0e3a1-134">移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="0e3a1-135">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0e3a1-136">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="0e3a1-137">FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="0e3a1-138">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0e3a1-139">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="0e3a1-140">各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="0e3a1-141">オンプレミスの Active Directory に存在する配布リスト ( *MailEnabledGroup* オブジェクト) と外部の連絡先 ( *MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="0e3a1-142">ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="0e3a1-143">ソース環境</span><span class="sxs-lookup"><span data-stu-id="0e3a1-143">Source environments</span></span>

<span data-ttu-id="0e3a1-144">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="0e3a1-145">単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="0e3a1-146">1 つの IMAP 対応のメール環境。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="0e3a1-147">G Suite 環境 (Gmail、連絡先、カレンダーのみ)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="0e3a1-148">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0e3a1-149"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0e3a1-150"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0e3a1-151"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="0e3a1-152"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0e3a1-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="0e3a1-154">
<strong>注:</strong> オンプレミスの Exchange の依存関係については、「 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ハイブリッド展開の前提条件</span></a>」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="0e3a1-155">ハイブリッド展開での移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="0e3a1-156">メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-156">Emails</span></span></li>
<li><span data-ttu-id="0e3a1-157">メールボックスのルール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="0e3a1-158">デリゲート</span><span class="sxs-lookup"><span data-stu-id="0e3a1-158">Delegates</span></span></li>
<li><span data-ttu-id="0e3a1-159">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="0e3a1-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0e3a1-160">予定表</span><span class="sxs-lookup"><span data-stu-id="0e3a1-160">Calendar</span></span> </li>
<li> <span data-ttu-id="0e3a1-161">タスク</span><span class="sxs-lookup"><span data-stu-id="0e3a1-161">Tasks</span></span> </li>
<li> <span data-ttu-id="0e3a1-162">権限が管理されたメール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="0e3a1-163">暗号化されたメール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="0e3a1-164">署名</span><span class="sxs-lookup"><span data-stu-id="0e3a1-164">Signatures</span></span> </li>
<li> <span data-ttu-id="0e3a1-165">ユーザーのメールボックスと一緒に移行された個人用アーカイブ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="0e3a1-166">回復可能なアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-167">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-167">Public folders</span></span> </li>
<li> <span data-ttu-id="0e3a1-168">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0e3a1-169">ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション</span><span class="sxs-lookup"><span data-stu-id="0e3a1-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="0e3a1-170">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-171">パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="0e3a1-172">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0e3a1-173">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0e3a1-174"><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="0e3a1-175">
<strong>注:</strong> G Suite 環境は、「 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">g suite 移行を実行</a>する」で説明されている前提条件を満たしている必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="0e3a1-176">カット オーバーまたは段階的</span><span class="sxs-lookup"><span data-stu-id="0e3a1-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-177">メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-177">Emails</span></span> </li>
<li> <span data-ttu-id="0e3a1-178">メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="0e3a1-179">カレンダー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-179">Calendar</span></span> </li>
<li> <span data-ttu-id="0e3a1-180">ラベル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-181">ルール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-181">Rules</span></span> </li>
<li> <span data-ttu-id="0e3a1-182">デリゲート</span><span class="sxs-lookup"><span data-stu-id="0e3a1-182">Delegates</span></span> </li>
<li> <span data-ttu-id="0e3a1-183">署名</span><span class="sxs-lookup"><span data-stu-id="0e3a1-183">Signatures</span></span> </li>
<li> <span data-ttu-id="0e3a1-184">タスク</span><span class="sxs-lookup"><span data-stu-id="0e3a1-184">Tasks</span></span> </li>
<li> <span data-ttu-id="0e3a1-185">メッセージのサイズ制限を超えている電子メールまたは添付ファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0e3a1-186">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-187">PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="0e3a1-188">権限が管理された、または暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="0e3a1-189">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0e3a1-190">Google ハングアウト\*\*</span><span class="sxs-lookup"><span data-stu-id="0e3a1-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="0e3a1-191">Google グループ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="0e3a1-192">リソース メールボックス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="0e3a1-193">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="0e3a1-194">休暇の設定および自動応答の設定</span><span class="sxs-lookup"><span data-stu-id="0e3a1-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="0e3a1-195">共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色</span><span class="sxs-lookup"><span data-stu-id="0e3a1-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="0e3a1-196">\*\*ラベルとして保存されたハングアウトの会話が移行されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0e3a1-197"><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-198">ネイティブの IMAP4 ツールを使用した移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="0e3a1-199">メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-200">ルール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-200">Rules</span></span> </li>
<li> <span data-ttu-id="0e3a1-201">デリゲート</span><span class="sxs-lookup"><span data-stu-id="0e3a1-201">Delegates</span></span> </li>
<li> <span data-ttu-id="0e3a1-202">配布リスト</span><span class="sxs-lookup"><span data-stu-id="0e3a1-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="0e3a1-203">外部の連絡先</span><span class="sxs-lookup"><span data-stu-id="0e3a1-203">External contacts</span></span> </li>
<li> <span data-ttu-id="0e3a1-204">メールが有効なユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="0e3a1-205">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-206">メールボックスの連絡先</span><span class="sxs-lookup"><span data-stu-id="0e3a1-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0e3a1-207">予定表</span><span class="sxs-lookup"><span data-stu-id="0e3a1-207">Calendar</span></span> </li>
<li> <span data-ttu-id="0e3a1-208">署名</span><span class="sxs-lookup"><span data-stu-id="0e3a1-208">Signatures</span></span> </li>
<li> <span data-ttu-id="0e3a1-209">タスク</span><span class="sxs-lookup"><span data-stu-id="0e3a1-209">Tasks</span></span> </li>
<li> <span data-ttu-id="0e3a1-210">メッセージのサイズ制限を超えている電子メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0e3a1-211">アーカイブ データ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-211">Archive data</span></span> </li>
<li> <span data-ttu-id="0e3a1-212">暗号化された電子メール</span><span class="sxs-lookup"><span data-stu-id="0e3a1-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="0e3a1-213">破損アイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0e3a1-214">非アクティブなメールボックス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0e3a1-215">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="0e3a1-215">FastTrack responsibilities</span></span>

<span data-ttu-id="0e3a1-216">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-217">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0e3a1-218">FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="0e3a1-219">該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0e3a1-220">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="0e3a1-220">Your responsibilities</span></span>

<span data-ttu-id="0e3a1-221">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-222">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0e3a1-223">また、Exchange の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="0e3a1-224">Exchange Online の FastTrack コア オンボーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="0e3a1-225">オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0e3a1-226">詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="0e3a1-227">Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="0e3a1-228">詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="0e3a1-229">オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0e3a1-230">詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="0e3a1-231">該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="0e3a1-232">該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="0e3a1-233">ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="0e3a1-234">ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="0e3a1-235">必要に応じて、クライアント側のデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="0e3a1-236">これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="0e3a1-237">クライアント側の移行の問題を修正してエンド ユーザーを支援します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="0e3a1-238">SharePoint Online への移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="0e3a1-239">FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0e3a1-240">移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0e3a1-241">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-241">You create and schedule your migration events.</span></span> <span data-ttu-id="0e3a1-242">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0e3a1-243">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="0e3a1-244">考慮事項</span><span class="sxs-lookup"><span data-stu-id="0e3a1-244">Considerations</span></span>

  - <span data-ttu-id="0e3a1-245">すべての移行には SharePoint Online のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="0e3a1-246">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0e3a1-247">移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0e3a1-248">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="0e3a1-248">Source environment details</span></span>

<span data-ttu-id="0e3a1-249">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0e3a1-250">ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0e3a1-251">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0e3a1-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0e3a1-253">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0e3a1-254">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0e3a1-255"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0e3a1-256"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0e3a1-257"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0e3a1-258"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0e3a1-259"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0e3a1-260">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-261">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-261">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-262">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-263">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="0e3a1-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0e3a1-264">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="0e3a1-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0e3a1-265">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-266">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-267">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-267">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-268">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-268">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-269">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-269">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-270">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="0e3a1-271">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0e3a1-272">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0e3a1-273">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0e3a1-274">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-275">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="0e3a1-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0e3a1-276">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-277">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="0e3a1-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="0e3a1-278">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0e3a1-279">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="0e3a1-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0e3a1-280">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0e3a1-281">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="0e3a1-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0e3a1-282">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0e3a1-283">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-284">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="0e3a1-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0e3a1-285">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0e3a1-286">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0e3a1-287"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-288">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-289">10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="0e3a1-290">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-291">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-292">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-293">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-294">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-295">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-295">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-296">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-296">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-297">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-297">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-298">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-299">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0e3a1-300">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-301">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-302">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="0e3a1-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0e3a1-303">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-304">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-305">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-306">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-307">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-308">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-309">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-310">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-311">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0e3a1-312">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="0e3a1-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0e3a1-313">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0e3a1-314">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0e3a1-315">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-316">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-317">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0e3a1-318">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-319">制限付きとしてマークされている、またはコピーできないファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="0e3a1-320">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0e3a1-321"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-322">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-323">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-323">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-324">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-325">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-326">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-327">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-328">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-329">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-329">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-330">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-330">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-331">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-331">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-332">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-333">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-334">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-335">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="0e3a1-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0e3a1-336">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-337">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-338">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-339">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-340">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-341">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-342">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-343">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-344">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0e3a1-345">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0e3a1-346">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-347">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-348">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0e3a1-349"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-350">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-351">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-351">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-352">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-353">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-354">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-355">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-356">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-357">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-357">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-358">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-358">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-359">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-359">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-360">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-361">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0e3a1-362">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-363">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-364">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="0e3a1-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0e3a1-365">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-366">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-367">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-368">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-369">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-370">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-371">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-372">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0e3a1-373">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0e3a1-374">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="0e3a1-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0e3a1-375">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0e3a1-376">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0e3a1-377">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-378">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="0e3a1-379">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0e3a1-380">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="0e3a1-380">FastTrack responsibilities</span></span>

<span data-ttu-id="0e3a1-381">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-382">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="0e3a1-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0e3a1-383">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="0e3a1-383">Your responsibilities</span></span>

<span data-ttu-id="0e3a1-384">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-385">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください</span><span class="sxs-lookup"><span data-stu-id="0e3a1-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="0e3a1-386">また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="0e3a1-387">移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="0e3a1-388">OneDrive for Business への移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="0e3a1-389">FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0e3a1-390">移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0e3a1-391">移行イベントを作成してスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-391">You create and schedule your migration events.</span></span> <span data-ttu-id="0e3a1-392">お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0e3a1-393">移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="0e3a1-394">考慮事項</span><span class="sxs-lookup"><span data-stu-id="0e3a1-394">Considerations</span></span>

  - <span data-ttu-id="0e3a1-395">すべての移行には OneDrive for Business のクォータが適用されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="0e3a1-396">詳細については、「[<span class="underline">SharePoint Online および OneDrive for Business ソフトウェアの境界と制限</span>](https://go.microsoft.com/fwlink/?LinkId=698855)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0e3a1-397">移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="0e3a1-398">FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0e3a1-399">ソース環境の詳細</span><span class="sxs-lookup"><span data-stu-id="0e3a1-399">Source environment details</span></span>

<span data-ttu-id="0e3a1-400">データ移行サービスは、次のソース環境からデータを移行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0e3a1-401">ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0e3a1-402">単一の G Suite 環境 (Google ドライブのみ)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0e3a1-403">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0e3a1-404">Dropbox for Teams (スタンダードと アドバンスド用)。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0e3a1-405">次の表は、各ソース環境に固有の移行の詳細を示しています。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="0e3a1-406"><strong>ソース環境</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="0e3a1-407"><strong>移行の種類</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="0e3a1-408"><strong>移行されるコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0e3a1-409"><strong>移行されないコンテンツ</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0e3a1-410"><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0e3a1-411">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-412">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-412">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-413">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-414">ユーザー レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="0e3a1-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0e3a1-415">グループ レベルのファイルとフォルダーのアクセス許可\*</span><span class="sxs-lookup"><span data-stu-id="0e3a1-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0e3a1-416">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-417">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-418">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-418">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-419">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-419">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-420">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-420">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-421">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="0e3a1-422">\*ディレクトリ同期の構成が必要。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0e3a1-423">エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0e3a1-424">ファイル共有デバイスで直接管理されているアクセス許可は移行されません。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0e3a1-425">SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="0e3a1-426">所有権の履歴と以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="0e3a1-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0e3a1-427">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-428">以前のバージョン</span><span class="sxs-lookup"><span data-stu-id="0e3a1-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="0e3a1-429">Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0e3a1-430">Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定</span><span class="sxs-lookup"><span data-stu-id="0e3a1-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0e3a1-431">明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0e3a1-432">NTFS 監査の構成</span><span class="sxs-lookup"><span data-stu-id="0e3a1-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0e3a1-433">ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0e3a1-434">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-435">非表示の共有</span><span class="sxs-lookup"><span data-stu-id="0e3a1-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0e3a1-436">共有 (共有のレベルに与えられるアクセス許可など)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0e3a1-437">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0e3a1-438"><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-439">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-440">Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="0e3a1-441">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-442">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-443">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-444">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-445">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-446">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-446">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-447">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-447">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-448">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-448">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-449">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-450">共有ドライブ (フォルダーとファイル)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0e3a1-451">移行中の Google ドライブ アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-452">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-453">ファイルとフォルダーの説明、フォルダーの色</span><span class="sxs-lookup"><span data-stu-id="0e3a1-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0e3a1-454">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-455">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-456">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-457">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-458">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-459">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-460">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-461">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-462">Google フォト、フォーム、マップとその他の接続されたアプリ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0e3a1-463">Google 図形描画</span><span class="sxs-lookup"><span data-stu-id="0e3a1-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0e3a1-464">組織外との共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0e3a1-465">Google Drive アカウントが所有していないコンテンツの移行</span><span class="sxs-lookup"><span data-stu-id="0e3a1-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0e3a1-466">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-467">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-468">共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0e3a1-469">移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-470">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0e3a1-471"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-472">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-473">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-473">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-474">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-475">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-476">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-477">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-478">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-479">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-479">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-480">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-480">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-481">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-481">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-482">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-483">移行される Box アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-484">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-485">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="0e3a1-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0e3a1-486">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-487">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-488">Box のタグと高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-489">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-490">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-491">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-492">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-493">ブロックされたユーザーまたは非アクティブなユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0e3a1-494">Box のアプリ、ブックマーク、お気に入り、およびワークフロー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0e3a1-495">移行された Box アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0e3a1-496">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-497">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-498">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0e3a1-499"><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></span><span class="sxs-lookup"><span data-stu-id="0e3a1-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0e3a1-500">単一または複数のパス</span><span class="sxs-lookup"><span data-stu-id="0e3a1-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-501">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-501">Documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-502">ファイルとフォルダーの構造</span><span class="sxs-lookup"><span data-stu-id="0e3a1-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0e3a1-503">ユーザー レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-504">グループ レベルのフォルダーのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-505">15 GB 未満のファイル</span><span class="sxs-lookup"><span data-stu-id="0e3a1-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0e3a1-506">基本的なドキュメントとフォルダーのメタデータ:</span><span class="sxs-lookup"><span data-stu-id="0e3a1-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0e3a1-507">作成日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-507">Created date</span></span> </li>
<li> <span data-ttu-id="0e3a1-508">更新日</span><span class="sxs-lookup"><span data-stu-id="0e3a1-508">Modified date</span></span> </li>
<li> <span data-ttu-id="0e3a1-509">作成者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-509">Created by</span></span> </li>
<li> <span data-ttu-id="0e3a1-510">最終更新者</span><span class="sxs-lookup"><span data-stu-id="0e3a1-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0e3a1-511">共有チームのフォルダーとコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0e3a1-512">移行される Dropbox アカウントが所有する共有コンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0e3a1-513">所有権の履歴、以前のバージョン、コメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0e3a1-514">ファイルとフォルダーの説明</span><span class="sxs-lookup"><span data-stu-id="0e3a1-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0e3a1-515">ユーザー レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-516">グループ レベルのファイルのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="0e3a1-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0e3a1-517">高度なメタデータ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0e3a1-518">ファイル ロックの属性</span><span class="sxs-lookup"><span data-stu-id="0e3a1-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0e3a1-519">コンテンツ内に埋め込まれた URL の変換</span><span class="sxs-lookup"><span data-stu-id="0e3a1-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0e3a1-520">ごみ箱に入れられたアイテム</span><span class="sxs-lookup"><span data-stu-id="0e3a1-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="0e3a1-521">アクセスできない、または破損しているドキュメント</span><span class="sxs-lookup"><span data-stu-id="0e3a1-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0e3a1-522">マウントが解除された Dropbox フォルダー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0e3a1-523">削除または切断されたユーザー</span><span class="sxs-lookup"><span data-stu-id="0e3a1-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0e3a1-524">Dropbox の用紙、ショーケース、スペース</span><span class="sxs-lookup"><span data-stu-id="0e3a1-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0e3a1-525">Dropbox アプリとお気に入り (Pin/スター)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0e3a1-526">移行された Dropbox アカウントが所有していないコンテンツ</span><span class="sxs-lookup"><span data-stu-id="0e3a1-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0e3a1-527">外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0e3a1-528">移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。)</span><span class="sxs-lookup"><span data-stu-id="0e3a1-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0e3a1-529">現在の<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online の制限と制限を</span>超えるファイルまたはフォルダー</a> </span><span class="sxs-lookup"><span data-stu-id="0e3a1-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0e3a1-530">FastTrack の責任範囲</span><span class="sxs-lookup"><span data-stu-id="0e3a1-530">FastTrack responsibilities</span></span>

<span data-ttu-id="0e3a1-531">FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-532">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0e3a1-533">お客様の責任</span><span class="sxs-lookup"><span data-stu-id="0e3a1-533">Your responsibilities</span></span>

<span data-ttu-id="0e3a1-534">移行プロジェクト中に標準のアクティビティを実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0e3a1-535">詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0e3a1-536">また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="0e3a1-537">移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="0e3a1-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
