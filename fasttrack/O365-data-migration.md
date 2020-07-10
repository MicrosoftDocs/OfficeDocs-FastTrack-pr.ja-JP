---
title: データ移行
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011311"
---
# <a name="data-migration"></a>データ移行

Office 365 に移行するデータがソース環境に含まれていることがあります。

**150 - 499 ライセンスを使用した Office 365 テナントの場合:** ツールとドキュメントの組み合わせを使用してガイダンスを提供し、移行をスムーズかつ効率的に行います。 

**500以上のライセンスを使用している Office 365 テナントの場合\*:** Exchange Online、SharePoint Online、OneDrive for Business では、データ移行サービスを利用できます。 FastTrack 特典には、ソース環境の統合およびデータの移行に関するガイダンスの提供が含まれます。
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> (ソース環境での読み取り不可または破損した項目を含め、またそれに限らず) 予期しない問題のために、いくつかの項目は移行できない場合があります。 
  
> [!NOTE]
> 移行支援は繁体字中国語と簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、ポルトガル語 (ブラジル)、スペイン語で利用できます。 
  
> [!NOTE]
> 統合が必要な場合、お使いのソース環境が対象のアプリケーションに必要な最低要件を満たしている必要があります。 
  
> [!NOTE]
> お客様が COVID-19 発生への対応を図る中、Microsoft では 6 か月無料の [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) および [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) の試用版ライセンスを 2020 年 3 月より新たに提供し、リモートでの勤務や学習を支援します。 例外として、FastTrack では 2020 年 3 月から 2020 年 8 月 まで、これらの試用版の 500 以上のライセンスを持つテナント、および学生向けの [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) でデータ移行サービスを利用できるようにしています。 この支援サービスは、予告なしに中止、変更、または一時停止する場合がございます。

次の表に、既存のソース環境の移行に必要な要件を示します。
  

|**アクティビティ**|**ソース環境要件**|
|:-----|:-----|
|**Exchange Online への移行**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  1 つまたは複数の Exchange 組織を持つ 1 つまたは複数のActive Directory フォレスト (Exchange 2010 ベースのハイブリッド以降が各組織に実装されていて、Exchange メール システムが 2003 以降の場合)。  <br/>  1 つの IMAP 対応のメール環境。  <br/>  G Suite 環境 (Gmail、連絡先、カレンダーのみ)。 <br/> <br/> **メモ** *Exchange Online オンボーディングは、移行の前に行う必要があります。* <br/> <br/> **メモ** *FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。* <br/> <br/> **メモ** *オンプレミスの Exchange の依存関係については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。* <br/><br/> **メモ** *複数のソース メッセージング環境 (複数の Exchange 組織と複数の Domino ドメインなど) を移行する場合、こうした移行が順次行われます。*| 
|**SharePoint Online への移行**  <br/> | ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。 <br/> 単一の G Suite 環境 (Google ドライブのみ)。<br/>  Box (Starter、Business、Enterprise)。  <br/> Dropbox for Teams (スタンダードと アドバンスド用)。<br/> |
|**OneDrive for Business への移行**  <br/> | ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。  <br/>  単一の G Suite 環境 (Google ドライブのみ)。  <br/>  Box (Starter、Business、Enterprise)。 <br/> Dropbox for Teams (スタンダードと アドバンスド用)。<br/><br/> **メモ** *FastTrack は、アクティブな Office 365 ドライブへの移行のみ行います。*|
   
## <a name="migration-to-exchange-online"></a>Exchange Online への移行
''
### <a name="enable-to-migrate"></a>移行の有効化
  
Microsoft を使用してメールを移行する場合、移行のために Exchange Online とソース環境の両方を有効化するためのガイダンスが提供されます。 移行元の環境に応じて、さまざまな有効化手順を実行することがあります。 ツール、ドキュメントを組み合わせて使ったり、可能な場合には構成タスクを実行したりするなどしてガイダンスを提供します。 適用可能なパラメーターがある場合には、それに応じてメールボックスを移行し、ジョブを監視し、進捗レポートを提供します。
移行アクティビティを実行するには、メール システムに対するアクセスとアクセス許可が必要となる場合があります。
  
### <a name="migration-policy-and-steps"></a>移行ポリシーと手順
  
> [!NOTE]
> 移行時間帯は移行バッチとも呼ばれます。

#### <a name="commercial-and-uk-government"></a>商用および英国政府機関

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>米国政府機関/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>最終的な状態
  
移行バッチの後に予想される最終的な状態には、次が含まれます。
- ソース環境で適切にスケジュールされて対象となるソース メールボックスからのデータは、Office 365 に移行されます。 
- Microsoft が提供する移行バッチ対象に関する移行後のレポート。
    
すべての移行が完了した後に予想される最終的な状態には、次が含まれます。
- 次の表で定義されているように、対象となるソース メールボックスのデータは Office 365 に移行されます。
- 移行されるデータの種類は、次の表で説明するように、ソース環境に依存しています。
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**ソース環境**|**移行の種類**|**ソース メールボックスから移行される内容**|**移行対象ではない**|
|**Exchange 2003 以降**|一括| メール <br/> メールボックスのルール <br/> デリゲート <br/> メールボックスの連絡先 <br/> 予定表 <br/> タスク <br/> 権限が管理されたメール <br/> 暗号化されたメール| パブリック フォルダー <br/> 個人用連絡先 <br/> メールが有効なユーザー <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> 署名 <br/> メールボックス収集 <br/>  メッセージのサイズ制限を超えている電子メール <br/> アーカイブ データ <br/> 破損アイテム <br/>  非アクティブなメールボックス |
|**Exchange 2003 および Exchange 2007**|段階的| メール <br/> メールボックスのルール <br/> デリゲート <br/> メールボックスの連絡先 <br/> 予定表 <br/> タスク <br/> 権限が管理されたメール <br/> 暗号化されたメール| パブリック フォルダー <br/> 個人用連絡先 <br/> メールが有効なユーザー <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> 署名 <br/> メールボックス収集 <br/> メッセージのサイズ制限を超えている電子メール <br/> アーカイブ データ <br/> 破損アイテム <br/> 非アクティブなメールボックス |
|**Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019** <br/><br/> **メモ** *オンプレミスの Exchange の依存関係については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。*           |ハイブリッド展開での移行| メール <br/> メールボックスのルール <br/> デリゲート <br/> メールボックスの連絡先 <br/> 予定表 <br/> タスク <br/> 署名 <br/> ユーザーのメールボックスと一緒に移行された個人用アーカイブ <br/> 回復可能なアイテム <br/> 権限が管理されたメール <br/> 暗号化されたメール| パブリック フォルダー <br/> メッセージのサイズ制限を超えている電子メール <br/> ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ <br/> 破損アイテム <br/> 非アクティブなメールボックス |
|**G Suite 環境 (Gmail、連絡先、カレンダーのみ)** <br/> <br/> **メモ** *G Suite 環境では、機能拡張のために Google API と Google Admin SDK を有効にする必要があります。* <br/>          |カット オーバーまたは段階的| メール <br/> メールボックスの連絡先\*  <br/> 予定表 <br/> ラベル <br/> \*連絡先ごとに最大 3 つのメール アドレスが移行される| ルール <br/> デリゲート <br/> 署名 <br/> タスク <br/> メッセージのサイズ制限を超えている電子メールまたは添付ファイル <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ <br/> 権限が管理された、または暗号化された電子メール <br/> 破損アイテム <br/> Google ハングアウト\*\* <br/> Google グループ <br/> リソース メールボックス <br/> 非アクティブなメールボックス <br/> 休暇の設定および自動応答の設定 <br/> 共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色 <br/>\*\*ラベルとして保存されたハングアウトの会話が移行される |
|**IMAP4 ソース (Domino、GroupWise、Zimbra など)** |ネイティブの IMAP4 ツールを使用した移行| メール | ルール <br/> デリゲート <br/> 配布リスト <br/> 外部の連絡先 <br/> メールが有効なユーザー <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> メールボックスの連絡先 <br/> 予定表 <br/> 署名 <br/> タスク <br/> メッセージのサイズ制限を超えている電子メール <br/> アーカイブ データ <br/> 暗号化された電子メール <br/> 破損アイテム <br/> 非アクティブなメールボックス |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack スペシャリストは、移行中に以下のことを行います。
- メールボックスの移行スケジュールのために標準テンプレートを提供します。
- FastTrack スペシャリストに必要なアクセス許可についての情報を提供します。 
- あらかじめ定義された形式で事前に定義したメールボックスの移行スケジュールを収集します。
- 移行バッチで 1 つのメールボックスを最大 2 回移行しようとした後に、そのメールボックスの移行エラーが報告されます。
- Exchange と IMAP4 ベースの移行元の環境では、ユーザー メールボックス容量の上限の最大 85% までメールボックスのコンテンツが移行されます (たとえば、メールボックス容量の上限が 50 GB の場合、Microsoft によって 50 GB 容量の上限の最大 85% まで移行が行われます)。 
- カット オーバー移行を使用している場合を除き、ソース メッセージング環境と Office 365 Exchange Online の間で SMTP メール ルーティングの共存を有効にします。
- 移行後のレポートを提供します。
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - 移行中のデータ損失。
  - 移行中に使用不可になるソース環境。
  - ソース環境における問題の原因となる移行作業。
    
お客様は、移行中に以下のことを行います。
- FastTrack センター を使って Exchange Online オンボーディングを完了するか、必要なチェックに合格します。
- エンドユーザーとのすべての通信を処理します。  
- Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。 詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」を参照してください。 
- 該当する場合には、ソース メッセージング環境と Office 365 Exchange Online の間の SMTP メール ルーティングの共存を検証します。
- 定義された方法で設定したスケジュールと、移行する特定のメールボックスの一覧を各移行イベントごとに提供します。
- 移行バッチの 24 時間前までに、スケジュールからメールボックスを削除します。 
- 次の表に示すように、24 時間における対象のメールボックスの平均数をスケジュールします。
    
|||
|:-----|:-----|
|**移行の対象となるメールボックス数** <br/> |**24 時間におけるメールボックスの平均最小数** <br/> |
|150-1000  <br/> |合計の 25%  <br/> |
|1001-5000  <br/> |合計の 20%  <br/> |
|5001-10000  <br/> |合計の 15%  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- 移行バッチに少なくとも 35 のメールボックスをスケジュールします。 
- 移行前エラーを修正します (該当する場合)。  
- 移行アクティビティを実行するために、FastTrack スペシャリストに移行元の環境へのアクセスとアクセス許可を与えます。 
- 移行アクティビティを実行するために、Office 365 のライセンス済みの管理者アカウントを調達または提供、あるいはその両方を行います (必要に応じて)。 
- クライアント側の移行に関する問題を支援し、必要に応じて移行後の操作を実行します。 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- 対象の Office 365 メールボックス制限の 85% 未満になるようにメールボックスのサイズを小さくします (該当する場合)。   
- 移動されなかったメールボックスを含め、移行後レポートの操作を行います。  
- 移行後のエラーを修正し、メールボックスを再スケジュールします (該当する場合)。   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - 移行中のデータ損失。
  - 移行中に使用不可になるソース環境。
  - ソース環境における問題の原因となる移行作業。
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>SharePoint Online への移行

### <a name="enable-to-migrate"></a>移行の有効化
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
一部の作業を実行するために、適切なアクセスとアクセス許可を Microsoft に提供していただく必要があります。
  
### <a name="migration-policy-and-steps"></a>移行ポリシーと手順
  
> [!NOTE]
> 移行時間帯は移行バッチとも呼ばれます。

#### <a name="commercial-and-uk-government"></a>商用および英国政府機関

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>米国政府機関/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

- すべての移行は、「[SharePoint Online と OneDrive for Business ソフトウェアの境界と制限](https://go.microsoft.com/fwlink/?LinkID=616612)」に記載されている SharePoint Online クォータの対象になります。   
- 移行後のデータの全体量は、使用できる SharePoint Online ストレージ クォータの全体の 75% (個別に購入した追加のストレージを含む) にバインドされます。
    
 ### <a name="end-state"></a>最終的な状態
  
移行バッチの後に予想される最終的な状態には、次が含まれます。 
- ソース環境で適切にスケジュールされた対象となるソースからのデータは、SharePoint Online に移行されます。   
- Microsoft が提供する移行バッチ対象に関する移行後のレポート。
    
すべての移行が完了した後に予想される最終的な状態には、次が含まれます。 
- 次の表で定義されているように、対象となるソースのデータが Office 365 に移行されます。  
- 移行されるデータの種類は、次の表で説明するように、ソース環境に依存しています。
    
|||||
|:-----|:-----|:-----|:-----|
|**ソース環境** <br/> |**移行の種類** <br/> |**移行対象** <br/> |**移行対象ではない** <br/> |
|**SMB 2.0 以降をサポートするファイル共有デバイス**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのファイルとフォルダーのアクセス許可\*  <br/>  グループ レベルのファイルとフォルダーのアクセス許可\*  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/><br/> \**ディレクトリ同期の構成が必要。エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。ファイル共有デバイスで直接管理されているアクセス許可は移行されません。SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。* <br/> | 所有権の履歴と以前のバージョン  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  以前のバージョン  <br/>  Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)  <br/>  Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定  <br/>  明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)  <br/>  NTFS 監査の構成  <br/>  ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ  <br/>  アクセスできない、または破損しているドキュメント  <br/>  非表示の共有  <br/>  共有 (共有のレベルに与えられるアクセス許可など)  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> |
|**単一の G Suite 環境 (Google ドライブのみ)**  <br/> |単一または複数のパス  <br/> | <br/>  10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます) <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可 <br/>  15 GB 未満のファイル  <br/> 基本的なドキュメントとフォルダーのメタデータ: <br/> 作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/> 共有ドライブ (フォルダーとファイル) <br/>  移行される Google Drive アカウントが所有する共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\*  <br/><br/> \**外部アカウントの識別のために Google Drive 管理を使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント <br/>  ファイルとフォルダーの説明、フォルダーの色  <br/>  ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可  <br/>  高度なメタデータ  <br/>  ファイル ロックの属性  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  ごみ箱に入れられたアイテム  <br/>  アクセスできない、または破損しているドキュメント  <br/>  ブロックされたユーザーまたは非アクティブなユーザー  <br/>  Google フォト、フォーム、マップとその他の接続されたアプリ  <br/>  Google 図形描画  <br/>  組織外との共有コンテンツ  <br/> Google Drive アカウントが所有していないコンテンツの移行 <br/>外部ユーザーのアクセス許可と基本的なメタデータ  <br/> 共有ドライブのメンバーのアクセス許可\* <br/> 現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> <br/> \**外部アカウントの識別のために Google Drive 管理を使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/>|
|**Box (Starter、Business、Enterprise)**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/>  移行対象の Box アカウントによって所有されている共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\*  <br/><br/> \**外部アカウントの識別のために Box のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント <br/>  ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可  <br/>  ファイルとフォルダーの説明  <br/>  Box のタグと高度なメタデータ  <br/>  ファイル ロックの属性  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  ごみ箱に入れられたアイテム  <br/>  アクセスできない、または破損しているドキュメント  <br/>  ブロックされたユーザーまたは非アクティブなユーザー  <br/>  Box Note (変換されないため、移行後は機能しない)  <br/>  Box のアプリ、ブックマーク、お気に入り、およびワークフロー  <br/>  移行された Box アカウントによって所有されていないコンテンツ (共有フォルダー)  <br/>  外部ユーザーのアクセス許可と基本的なメタデータ\*  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> <br/>\**Google Drive 管理を使用して、共有ドライブのメンバーシップを特定します。移行の前に、ターゲットのメンバーシップ設定を構成するようエンドユーザーに指示します。* |
|**Teams Dropbox for Teams (スタンダードと アドバンスド用)。**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/> 共有チームのフォルダーとコンテンツ <br/>  移行対象の Dropbox アカウントによって所有されている共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\*  <br/> <br/> \**外部アカウントの識別のために Dropbox のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント <br/>  ファイルとフォルダーの説明 <br/>  ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可    <br/> 高度なメタデータ  <br/>  ファイル ロックの属性  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  ごみ箱に入れられたアイテム  <br/>  アクセスできない、または破損しているドキュメント  <br/>  マウントが解除された Dropbox フォルダー <br/>  削除または切断されたユーザー <br/>  Dropbox の用紙、ショーケース、スペース  <br/> Dropbox アプリとお気に入り (Pin/スター) <br/> 移行された Dropbox アカウントが所有していないコンテンツ  <br/>  外部ユーザーのアクセス許可と基本的なメタデータ\*  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> <br/> \**外部アカウントの識別のために Dropbox のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> |
   
FastTrack スペシャリストは、移行中に以下のことを行います。 
- 選択した移行シナリオのプロセスとアプローチを網羅するワークショップで、移行のチュートリアルを実施します。
- シナリオで該当する場合は、評価と移行のツールの前提条件を提供します。   
- 移行チームが評価と移行の目的で、ソースと対象環境にアクセスするための前提条件を提供します。 
- 対象ソース環境の評価を実行する評価ツールを提供します。または、ネイティブ ソース プラットフォームを使用して、評価レポートを作成する方法について説明します。   
- 評価ツールと移行ツールの展開と実行を支援します (該当する場合)。   
- コンテンツ移行の準備として、インフラストラクチャの移行を構成します (該当する場合)。    
- 移行インフラストラクチャと必要な前提条件を検証するために、限定的な試験移行を実施します。   
- 移行の一部として、そのまま使用できる対象 SharePoint Online サイトのプロビジョニングを行います。    
- 本格的な移行の前に、1 つのパイロット移行を実施します。   
- 選択したシナリオの移行のスケジュール設定のガイダンスを提供します。 
- お客様が提供し、FastTrack リソースで検証された移行スケジュールに基づいて、コンテンツの移行を速度を上げて実施します。   
- 各移行間隔の後に、移行の結果を提供します。   
- 移行の速度を上げるために、優先順位を決め、潜在的な修復オプションに関するガイダンスを提供します。   
- 本格的な移行間隔ごとに、最終的な移行レポートを提供します。   
- ユーザー受け入れテストの間、移行完了後最大 5 日間まで、移行後の支援を提供します。
    
お客様は、移行中に以下のことを行います。 
- Provide project resources recommended for assessment and migration activities. These include: 
  - プロジェクトの管理。 
  - ユーザー受け入れテスト (UAT)。  
  - 移行元と移行先のコンテンツ プラットフォームを担当する管理者。  
- 評価と移行アクティビティのためにインフラストラクチャの前提条件を提供します (必要な場合)。  
- 移行アクティビティを実行するために、FastTrack スペシャリストに移行元と移行先の環境へのアクセスとアクセス許可を与えます (必要な場合)。
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 評価と移行のサポートに必要な前提条件を提示してアクティビティを実行します。   
- FastTrack に用意されている評価ツールをインストールし、評価データの収集アクティビティを完了します (該当する場合)。   
- FastTrack に用意されているオンプレミスの移行ソフトウェアをインストールします (該当する場合)。   
- FastTrack に用意されている修復レポートに記載の修復アクティビティを完了します (該当する場合)。  
- FastTrack のテンプレートとガイダンスを使用して、移行スケジュールを提供します。   
- 移行品質保証とユーザー受け入れのテストを実施します。   
- 移行後の移行修復フェーズを実施します (必要な場合)。
- 変更の管理とエンド ユーザーとの通信を計画し、実装します (該当する場合)。   
- 評価と移行の作業を正常に完了するために必要な、ソース システムとデバイスに対する変更を管理および設定します。
- 各移行イベントの少なくとも 3 日前に、定義された方法で設定したスケジュールと、移行する特定のユーザー データの一覧を提供します。
- 移行バッチの 24 時間前までに、スケジュールからユーザー データを削除します。 これが最終の移行バッチとなります。
> [!NOTE]
> Microsoft は、ファイルの移行速度を保証することはできません。
    
## <a name="migration-to-onedrive-for-business"></a>OneDrive for Business への移行

 ### <a name="enable-to-migrate"></a>移行の有効化
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>移行ポリシーと手順
  
> [!NOTE]
> 移行時間帯は移行バッチとも呼ばれます。

#### <a name="commercial-and-uk-government"></a>商用および英国政府機関

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>米国政府機関/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
- すべての移行には、ソース環境に対する適切なアクセスとアクセス許可が必要です。   
- すべての移行は、「[SharePoint Online と OneDrive for Business のソフトウェアの境界と制限](https://go.microsoft.com/fwlink/?LinkId=698855)」に記載されている OneDrive for Business クォータの対象になります。
    
 ### <a name="end-state"></a>最終的な状態
  
移行バッチの後に予想される最終的な状態には、次が含まれます。  
- ソース環境内の適切にスケジュールされた対象ソースのデータが、OneDrive for Business に移行されます。  
- Microsoft が提供する移行バッチ対象に関する移行後のレポート。
    
すべての移行が完了した後に予想される最終的な状態には、次が含まれます。
- 次の表で定義されているように、対象となるソースのデータが Office 365 に移行されます。  
- 移行されるデータの種類は、次の表で説明するように、ソース環境に依存しています。
    
|||||
|:-----|:-----|:-----|:-----|
|**ソース環境**|**移行の種類**|**移行対象**|**移行対象ではない**|
|**SMB 2.0 以降をサポートするファイル共有デバイス**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのファイルとフォルダーのアクセス許可\*  <br/>  グループ レベルのファイルとフォルダーのアクセス許可\*  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/> <br/>\**ディレクトリ同期の構成が必要。エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。ファイル共有デバイスで直接管理されているアクセス許可は移行されません。SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。* <br/> | 所有権の履歴と以前のバージョン  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  以前のバージョン  <br/>  Windows のファイルやフォルダーの属性 (読み取り専用、非表示など)  <br/>  Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定  <br/>  明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ)  <br/>  NTFS 監査の構成  <br/>  FCI によって提供される追加のファイルのメタデータ  <br/>  アクセスできない、または破損しているドキュメント  <br/>  非表示の共有  <br/>  共有 (共有のレベルに与えられるアクセス許可など)  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> |
|**単一の G Suite 環境 (Google ドライブのみ)**  <br/> |単一または複数のパス  <br/> | Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます)  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/> 共有ドライブ (フォルダーとファイル) <br/> 移行される Google Drive アカウントが所有する共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\* <br/> <br/>\**外部アカウントの識別のために Google Drive 管理を使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント  <br/>  ファイルとフォルダーの説明、フォルダーの色  <br/>   ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可  <br/> 高度なメタデータ <br/>  ファイル ロックの属性 <br/> コンテンツ内に埋め込まれた URL の変換  <br/> ごみ箱に入れられたアイテム <br/> アクセスできない、または破損しているドキュメント <br/> ブロックされたユーザーまたは非アクティブなユーザー <br/> Google フォト <br/> フォームとその他の接続されたアプリ <br/> Google 図形描画 <br/> 組織外との共有コンテンツ <br/> Google Drive アカウントが所有していないコンテンツの移行 <br/> 外部ユーザーのアクセス許可と基本的なメタデータ<br/> 共有ドライブのメンバーのアクセス許可\*<br/> 現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/><br/> \**Google Drive 管理を使用して、共有ドライブのメンバーシップを特定します。移行の前に、ターゲットのメンバーシップ設定を構成するようエンドユーザーに指示します。* <br/> |
|**Box (Starter、Business、Enterprise)**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/>  移行対象の Box アカウントによって所有されている共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\*  <br/><br/> \**外部アカウントの識別のために Box のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント  <br/>  ファイルとフォルダーの説明  <br/>  ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可  <br/>  Box のタグと高度なメタデータ  <br/>  ファイル ロックの属性  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  ごみ箱に入れられたアイテム  <br/>  アクセスできない、または破損しているドキュメント  <br/>  ブロックされたユーザーまたは非アクティブなユーザー  <br/>  Box Note (変換されないため、移行後は機能しない)  <br/>  Box のアプリ、ブックマーク、お気に入り、およびワークフロー  <br/>  移行された Box アカウントによって所有されていないコンテンツ (共有フォルダー)  <br/>  外部ユーザーのアクセス許可と基本的なメタデータ\*  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> |
|**Teams Dropbox for Teams (スタンダードと アドバンスド用)。**  <br/> |単一または複数のパス  <br/> | ドキュメント  <br/>  ファイルとフォルダーの構造  <br/>  ユーザー レベルのフォルダーのアクセス許可  <br/>  グループ レベルのフォルダーのアクセス許可  <br/>  15 GB 未満のファイル  <br/>  基本的なドキュメントとフォルダーのメタデータ:  <br/>  作成日  <br/>  更新日  <br/>  作成者  <br/>  最終更新者  <br/> 共有チームのフォルダーとコンテンツ <br/> 移行対象の Dropbox アカウントによって所有されている共有コンテンツ (ユーザーまたはグループと明示的に共有する場合)\*  <br/> <br/> \**外部アカウントの識別のために Dropbox のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> | 所有権の履歴、以前のバージョン、コメント <br/>  ファイルとフォルダーの説明 <br/>  ユーザー レベルのファイルのアクセス許可  <br/>  グループ レベルのファイルのアクセス許可    <br/> 高度なメタデータ  <br/>  ファイル ロックの属性  <br/>  コンテンツ内に埋め込まれた URL の変換  <br/>  ごみ箱に入れられたアイテム  <br/>  アクセスできない、または破損しているドキュメント  <br/>  マウントが解除された Dropbox フォルダー <br/>  削除または切断されたユーザー <br/>  Dropbox の用紙、ショーケース、スペース  <br/> Dropbox アプリとお気に入り (Pin/スター) <br/> 移行された Dropbox アカウントが所有していないコンテンツ  <br/>  外部ユーザーのアクセス許可と基本的なメタデータ\*  <br/>  現在の [SharePoint Online の制限事項と制約事項](https://go.microsoft.com/fwlink/?linkid=846724)から逸脱するファイルまたはフォルダー <br/> <br/> \**外部アカウントの識別のために Dropbox のレポートを使用します。移行後にコンテンツを再共有するようエンド ユーザーに指示します。* <br/> |
   
FastTrack スペシャリストは、移行中に以下のことを行います。  
- 選択した移行シナリオのプロセスとアプローチを網羅するワークショップで、移行のチュートリアルを実施します。   
- シナリオで該当する場合は、評価と移行のツールの前提条件を提供します。  
- 移行チームが評価と移行の目的で、ソースと対象環境にアクセスするための前提条件を提供します。   
- 対象ソース環境の評価を実行する評価ツールを提供します。または、ネイティブ ソース プラットフォームを使用して、評価レポートを作成する方法について説明します。    
- 評価ツールと移行ツールの展開と実行を支援します (該当する場合)。   
- コンテンツ移行の準備として、インフラストラクチャの移行を構成します (該当する場合)。    
- 移行インフラストラクチャと必要な前提条件を検証するために、限定的な試験移行を実施します。    
- 移行の一部として、そのまま使用できる対象 OneDrive for Business サイトのプロビジョニングを行います。    
- 本格的な移行の前に、1 つのパイロット移行を実施します。
- 選択したシナリオの移行のスケジュール設定のガイダンスを提供します。   
- お客様が提供し、FastTrack リソースで検証された移行スケジュールに基づいて、コンテンツの移行を速度を上げて実施します。   
- 各移行間隔の後に、移行の結果を提供します。   
- 移行の速度を上げるために、優先順位を決め、潜在的な修復オプションに関するガイダンスを提供します。 
- 本格的な移行間隔ごとに、最終的な移行レポートを提供します。   
- ユーザー受け入れテストの間、移行完了後最大 5 日間まで、移行後の支援を提供します。
   
お客様は、移行中に以下のことを行います。
- Provide project resources recommended for assessment and migration activities. These include:
  - プロジェクトの管理。
  - UAT。
  - 移行元と移行先のコンテンツ プラットフォームを担当する管理者。
- 評価と移行アクティビティのためにインフラストラクチャの前提条件を提供します (必要な場合)。   
- 移行アクティビティを実行するために、FastTrack スペシャリストに移行元と移行先の環境へのアクセスとアクセス許可を与えます (必要な場合)。  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- FastTrack に用意されている評価ツールをインストールし、評価データの収集アクティビティを完了します (該当する場合)。
- FastTrack に用意されているオンプレミスの移行ソフトウェアをインストールします (該当する場合)。  
- FastTrack に用意されている修復レポートに記載の修復アクティビティを完了します (該当する場合)。   
- FastTrack のテンプレートとガイダンスを使用して、移行スケジュールを提供します。 
- 定義された方法で設定したスケジュールと、移行する特定のユーザー データの一覧を各移行イベントごとに提供します。
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- 移行品質保証とユーザー受け入れのテストを実施します。   
- 移行後の移行修復フェーズを実施します (必要な場合)。  
- 変更の管理とエンド ユーザーとの通信を計画し、実装します (該当する場合)。  
- 評価と移行の作業を正常に完了するために必要な、ソース システムとデバイスに対する変更を管理および設定します。
    
> [!NOTE]
> Microsoft は、ファイルの移行速度を保証することはできません。 


