---
title: データ移行
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。 提供するサポートの種類は、Office 365 ライセンスの数によって異なります。
ms.openlocfilehash: 7b9e48d802e0c33f72165f77b23680915c9c61eb
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994938"
---
# <a name="data-migration"></a>データ移行

FastTrack は、ソース環境のメールとファイル データを Office 365 (Exchange Online、SharePoint Online、および OneDrive for Business) に移行するのに役立ちます。

提供するサポートの種類は、Office 365 ライセンスの数によって異なります。

  - **ライセンスの数が 150 - 499 個の Office 365 テナントの場合**: FastTrack は移行ガイダンスのみを提供します。お客様はデータ移行を行う責任があります。 セルフ サービスの移行を実行するための無料ツールの計画と使用に役立つドキュメントをご案内します。
  - **ライセンスの数が 500 個以上の Office 365 テナントの場合**: FastTrack は、移行ガイダンスとデータ移行サービスを提供します。 移行の計画、ソース環境と Office 365 テナントの構成、およびデータ移行サービスを利用したデータの移行に役立つガイダンスを提供します。 移行イベントを作成してスケジュールします。 お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。

> [!NOTE]
> 2017 年 9 月 1 日より前に商用プランを購入または更新した場合、データ移行サービスの対象となるのに必要なライセンスの数は 150 個のみです。 教育機関向けプランの場合、有料の教職員のライセンスのみがデータ移行サービスの対象となります。

### <a name="considerations"></a>考慮事項

  - データを Office 365 に移行するには、ソース環境が特定の期待を満たす必要があります。 Exchange、SharePoint、および OneDrive for Business に対する期待されるソース環境の詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。
  - データ移行サービスを提供するには、ソース環境と Office 365 テナントへの適切なアクセスと権限が必要です。
  - 当社のデータ移行サービスは、特別な法的要件または規制要件の対象となるデータに対して設計または意図されたものではありません。 データを移行する際、設備を維持している任意の場所に転送、保存、および処理できます (FastTrack 移行プロジェクトで別途提供されている場合を除く)。
  - Microsoft は、メールやファイルの移行速度を保証することはできません。
  - 予期しない問題 (ソース環境の読み取り不能または破損したアイテムなど) により、一部のデータ アイテムを移行できない場合があります。
  - 当社の制御が及ばない外部要因 (サードパーティのアプリケーション プログラミング インターフェース (API) への変更など) により、データ移行サービスが変更、遅延、または停止される場合があります。

### <a name="migration-service-availability"></a>移行サービスの可用性

  - **商業および英国政府機関のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。
  - **米国政府/DOD のお客様の場合:** データ移行サービスを 24 時間年中無休で提供しています。

## <a name="migration-to-exchange-online"></a>Exchange Online への移行

FastTrack を使用してメールを Exchange Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。 移行の計画、ソース環境と Exchange Online の構成、およびデータ移行サービスを利用したメールボックスの移行に役立つガイダンスを提供します。 移行イベントを作成してスケジュールします。 お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。 移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソース メールボックスからのメールが Exchange Online に移行されることが期待できます。

### <a name="considerations"></a>考慮事項

  - 移行の前に、Exchange Online の FastTrack コア オンボーディングを完了する必要があります。
      - オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。 詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。
  - FastTrack は、アクティブな Office 365 メールボックスへの移行のみ行います。
  - オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たす必要があります。 詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。
  - 各ソース環境は、ソース環境でそれぞれの製品の最新のサービス パック (SP) とロールアップ (RU)/累積的な更新プログラム (CU) レベルにあることが必要です。
  - オンプレミスの Active Directory に存在する配布リスト (*MailEnabledGroup* オブジェクト) と外部の連絡先 (*MailEnabledContact* オブジェクト) は、メールボックス データの移行の一部ではありません。 ただし、Azure Active Directory (Azure AD) Connect を使用して同期できます。 

## <a name="source-environments"></a>ソース環境

データ移行サービスは、次のソース環境からデータを移行します。

  - 単一または複数の Exchange 組織を持つ単一または複数の Active Directory フォレスト (各 Exchange メール システムは Exchange 2010 以降である必要があります)。
  - 1 つの IMAP 対応のメール環境。
  - G Suite 環境 (Gmail、連絡先、カレンダーのみ)。

次の表は、各ソース環境に固有の移行の詳細を示しています。

<table>
<thead>
<tr class="header">
<th><strong>ソース環境</strong></th>
<th><strong>移行の種類</strong></th>
<th><strong>移行されるコンテンツ</strong></th>
<th><strong>移行されないコンテンツ</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong><br />
<br />
<strong>注:</strong>オンプレミスの依存関係については、「ハイブリッドExchange前提条件<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">」を参照してください</span></a>。</td>
<td>ハイブリッド展開での移行</td>
<td><ul>
<li>メール</li>
<li>サーバー側のメールボックス ルール</li>
<li>デリゲート</li>
<li>メールボックスの連絡先 </li>
<li> 予定表 </li>
<li> タスク </li>
<li> 権限が管理されたメール </li>
<li> 暗号化されたメール </li>
<li> 署名 </li>
<li> ユーザーのメールボックスと一緒に移行された個人用アーカイブ </li>
<li> 回復可能なアイテム </li>
</ul></td>
<td><ul>
<li> パブリック フォルダー </li>
<li> メッセージのサイズ制限を超えている電子メール </li>
<li> ジャーナリング アーカイブやサード パーティ製アーカイブ ソリューション </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> パーソナル ストレージ テーブル (PST) ファイルのアーカイブ データ </li>
<li> 破損アイテム </li>
<li> 非アクティブなメールボックス </li>
<li> クライアント側のメールボックス ルール</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>G Suite 環境 (Gmail、連絡先、カレンダーのみ)</strong><br />
<br />
<strong>注:</strong> G Suite 環境は、「G Suite 移行の実行」で説明されている <a href="/exchange/mailbox-migration/perform-g-suite-migration">前提条件を満たす必要があります</a>。</td>
<td>カット オーバーまたは段階的</td>
<td><ul>
<li> メール </li>
<li> メールボックス連絡先 (連絡先ごとに最大 3 つのメール アドレスが移行される) </li>
<li> カレンダー </li>
<li> ラベル </li>
</ul></td>
<td><ul>
<li> ルール </li>
<li> デリゲート </li>
<li> 署名 </li>
<li> タスク </li>
<li> メッセージのサイズ制限を超えている電子メールまたは添付ファイル </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> PST ファイルまたはサード パーティのアーカイブ ソリューション (たとえば、Google Vault) のアーカイブ データ </li>
<li> 権限が管理された、または暗号化された電子メール </li>
<li> 破損アイテム </li>
<li> Google ハングアウト** </li>
<li> Google グループ </li>
<li> リソース メールボックス </li>
<li> 非アクティブなメールボックス </li>
<li> 休暇の設定および自動応答の設定 </li>
<li> 共有の予定表、クラウド添付ファイル、Google ハングアウトのリンク、イベントの色 </li>
</ul>
**ラベルとして保存されたハングアウトの会話が移行されます。 </td>
</tr>
<tr class="odd">
<td><strong>IMAP4 ソース (Domino、GroupWise、または Zimbra など)</strong></td>
<td>ネイティブの IMAP4 ツールを使用した移行</td>
<td><li>メール </li></td>
<td><ul>
<li> ルール </li>
<li> デリゲート </li>
<li> 配布リスト </li>
<li> 外部の連絡先 </li>
<li> メールが有効なユーザー </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> メールボックスの連絡先 </li>
<li> 予定表 </li>
<li> 署名 </li>
<li> タスク </li>
<li> メッセージのサイズ制限を超えている電子メール </li>
<li> アーカイブ データ </li>
<li> 暗号化された電子メール </li>
<li> 破損アイテム </li>
<li> 非アクティブなメールボックス </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a>FastTrack移行のExchange Online責任

FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。

FastTrack スペシャリストは、Exchange の移行に対して固有の次のアクティビティも実行します。

  -  該当する場合、ソース環境と Exchange Online の間で SMTP メール ルーティングの共存を有効にするためのガイダンスを提供します。

### <a name="your-responsibilities"></a>お客様の責任

移行プロジェクト中に標準のアクティビティを実行します。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。

また、Exchange の移行に対して固有の次のアクティビティも実行します。

  - Exchange Online の FastTrack コア オンボーディングを完了します。 オンボーディングを自分で行った場合は、必要なチェックと前提条件に合格する必要があります。 詳細については、「[製品と機能](products-and-capabilities.md)」を参照してください。
  -  Office 365 のガイドラインに従って、適切なレベルのクライアント ソフトウェアをインストールします。 詳細については、「[モダン ワークプレイス](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)」をご覧ください。
  -  オンプレミスの Exchange 環境から移行する場合は、特定の要件を満たします。 詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/?LinkId=787528)」を参照してください。
  -  該当する場合、各ソース環境が最新の Service Pack (SP) およびロールアップ (RU)/累積的な更新プログラム (CU) レベルであることを確認します。
  -  該当する場合、ソース環境と Exchange Online の間の SMTP メール ルーティングの共存を構成および検証します。
  -  ソース メールボックスのサイズが対象のメールボックスのクォータを超えないようにします。 ソース プラットフォームによっては、ソース データを対象のメールボックス クォータの 85% に制限する必要がある場合があります。
  -  必要に応じて、クライアント側のデータを移行します。 これにはローカルのアドレス帳、ローカルの PST ファイル内のデータ、Outlook ルール、ローカルの Outlook 設定も含まれますが、それだけに限られるわけではありません。
  -  クライアント側の移行の問題を修正してエンド ユーザーを支援します。

## <a name="migration-to-sharepoint-online"></a>SharePoint Online への移行

FastTrack を使用してファイルを SharePoint Online に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。 移行の計画、ソース環境と SharePoint Online の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。 移行イベントを作成してスケジュールします。 お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。 移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが SharePoint Online に移行されることが期待できます。

### <a name="considerations"></a>考慮事項

 - すべての移行には SharePoint Online のクォータが適用されます。 詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。 
  - 移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。

### <a name="source-environment-details"></a>ソース環境の詳細

データ移行サービスは、次のソース環境からデータを移行します。

  - ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。
  - 単一の G Suite 環境 (Google ドライブのみ)。
  - Box (Starter、Business、Enterprise)。
  - Dropbox for Teams (スタンダードと アドバンスド用)。

次の表は、各ソース環境に固有の移行の詳細を示しています。

<table>
<thead>
<tr class="header">
<th><strong>ソース環境</strong></th>
<th><strong>移行の種類</strong></th>
<th><strong>移行されるコンテンツ</strong></th>
 <th><strong>移行されないコンテンツ</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのファイルとフォルダーのアクセス許可* </li>
<li> グループ レベルのファイルとフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
</ul>
*ディレクトリ同期の構成が必要。 エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。 ファイル共有デバイスで直接管理されているアクセス許可は移行されません。 SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。</td>
<td><ul>
<li> 所有権の履歴と以前のバージョン </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> 以前のバージョン </li>
<li> Windows のファイルやフォルダーの属性 (読み取り専用、非表示など) </li>
<li> Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定 </li>
<li> 明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ) </li>
<li> NTFS 監査の構成 </li>
<li> ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> 非表示の共有 </li>
<li> 共有 (共有のレベルに与えられるアクセス許可など) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> 10 MB を超えるものを含む Google ドキュメント、スプレッドシート、スライド (ファイルは対応する Office 形式に変換されます) </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有ドライブ (フォルダーとファイル) </li>
<li> 移行中の Google ドライブ アカウントが所有する共有コンテンツ </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明、フォルダーの色 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Google フォト、フォーム、マップとその他の接続されたアプリ </li>
<li> Google 図形描画 </li>
<li> 組織外との共有コンテンツ </li>
<li> Google Drive アカウントが所有していないコンテンツの移行 </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> 共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。 移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。) </li>
<li> 制限付きまたはコピー不可としてマークされたファイル </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 移行される Box アカウントが所有する共有コンテンツ </li>
<li> Box Notes (Word ドキュメント形式に変換) </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> Box のタグと高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Box のアプリ、ブックマーク、お気に入り、およびワークフロー </li>
<li> 移行された Box アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有チームのフォルダーとコンテンツ </li>
<li> 移行される Dropbox アカウントが所有する共有コンテンツ </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> マウントが解除された Dropbox フォルダー </li>
<li> 削除または切断されたユーザー </li>
<li> Dropbox の用紙、ショーケース、スペース </li>
<li> Dropbox アプリとお気に入り (Pin/スター) </li>
<li> 移行された Dropbox アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a>FastTrack移行のSharePoint責任

FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください

### <a name="your-responsibilities"></a>お客様の責任

移行プロジェクト中に標準のアクティビティを実行します。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください

また、SharePoint Online の移行に対して固有の次のアクティビティも実行します。

  - 移行イベントの対象となるすべての SharePoint チーム サイトをプロビジョニングします。

## <a name="migration-to-onedrive-for-business"></a>OneDrive for Business への移行

FastTrack を使用してファイルを OneDrive for Business に移行することを選択すると、移行ガイダンスとデータ移行サービスが提供されます。 移行の計画、ソース環境と OneDrive for Business の構成、およびデータ移行サービスを利用したファイルの移行に役立つガイダンスを提供します。 移行イベントを作成してスケジュールします。 お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。 移行イベントが完了すると、ソース環境の適切にスケジュールされた対象となるソースからのファイルが OneDrive for Business に移行されることが期待できます。

### <a name="considerations"></a>考慮事項

  - すべての移行には SharePoint Online のクォータが適用されます。 詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。 
  - 移行するデータの全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。
  - FastTrack は、アクティブな OneDrive for Business ドライブにのみ移行します。

### <a name="source-environment-details"></a>ソース環境の詳細

データ移行サービスは、次のソース環境からデータを移行します。

  - ファイル共有 (SMB 2.0 以降をサポートするデバイスでの SMB ファイルの共有)。
  - 単一の G Suite 環境 (Google ドライブのみ)。
  - Box (Starter、Business、Enterprise)。
  - Dropbox for Teams (スタンダードと アドバンスド用)。

次の表は、各ソース環境に固有の移行の詳細を示しています。

<table>
<thead>
<tr class="header">
 <th><strong>ソース環境</strong></th>
 <th><strong>移行の種類</strong></th>
 <th><strong>移行されるコンテンツ</strong></th>
 <th><strong>移行されないコンテンツ</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのファイルとフォルダーのアクセス許可* </li>
<li> グループ レベルのファイルとフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
</ul>
<br>
*ディレクトリ同期の構成が必要。 エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。 ファイル共有デバイスで直接管理されているアクセス許可は移行されません。 SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。 </td>
<td><ul>
<li> 所有権の履歴と以前のバージョン </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> 以前のバージョン </li>
<li> Windows のファイルやフォルダーの属性 (読み取り専用、非表示など) </li>
<li> Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定 </li>
<li> 明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ) </li>
<li> NTFS 監査の構成 </li>
<li> ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> 非表示の共有 </li>
<li> 共有 (共有のレベルに与えられるアクセス許可など) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます) </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有ドライブ (フォルダーとファイル) </li>
<li> 移行中の Google ドライブ アカウントが所有する共有コンテンツ </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明、フォルダーの色 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Google フォト、フォーム、マップとその他の接続されたアプリ </li>
<li> Google 図形描画 </li>
<li> 組織外との共有コンテンツ </li>
<li> Google Drive アカウントが所有していないコンテンツの移行 </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> 共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。 移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 移行される Box アカウントが所有する共有コンテンツ </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> Box のタグと高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Box のアプリ、ブックマーク、お気に入り、およびワークフロー </li>
<li> 移行された Box アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可 </li>
<li> グループ レベルのフォルダーのアクセス許可 </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有チームのフォルダーとコンテンツ </li>
<li> 移行される Dropbox アカウントが所有する共有コンテンツ </li>
</ul></td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> マウントが解除された Dropbox フォルダー </li>
<li> 削除または切断されたユーザー </li>
<li> Dropbox の用紙、ショーケース、スペース </li>
<li> Dropbox アプリとお気に入り (Pin/スター) </li>
<li> 移行された Dropbox アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a>FastTrack移行に関するOneDrive for Business責任

FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。

### <a name="your-responsibilities"></a>お客様の責任

移行プロジェクト中に標準のアクティビティを実行します。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。

また、OneDrive for Business の移行に対して固有の次のアクティビティも実行します。

  - 移行イベントの対象となるすべての OneDrive for Business サイトをプロビジョニングします。

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>グループとMicrosoft TeamsグループMicrosoft 365移行

ファイルを FastTrackグループMicrosoft Teamsおよび Microsoft 365に移行する場合は、移行ガイダンスとデータ移行サービスを提供します。 移行を計画し、ソース環境と Teams グループと Microsoft 365 グループを構成し、データ移行サービスを活用してファイルを移行するのに役立つガイダンスを提供します。 移行イベントを作成してスケジュールします。 お客様のスケジュールに従って移行イベントを開始し、その進捗状況を監視し、状態レポートを提供します。 移行イベントが完了すると、ソース環境の適切にスケジュールされた適格なソースからのファイルが Teams および Microsoft 365 グループに移行されたと予想できます。 Teamsおよび Microsoft 365グループは、これらの移行先の種類にデータを移行する前に、お客様が事前に準備する必要があります。 TeamsグループMicrosoft 365グループは、ファイルの保存先の場所に対するアクセス許可に影響します。 TeamsグループMicrosoft 365グループは、コラボレーションを可能にするために構築されています。 このTeamsまたはMicrosoft 365グループは、それらの宛先に移行するときに、それらのファイルにアクセスできるユーザーを決定します。 FastTrack、移行中にエンド ユーザーまたはグループを任意のチャネルTeamsグループMicrosoft 365追加しない。

### <a name="considerations"></a>考慮事項

- すべての移行には SharePoint Online のクォータが適用されます。 詳細については<a href="https://go.microsoft.com/fwlink/?LinkId=698855">、「SharePoint制限」</a>を参照してください。 
- 移行の全体量を、資格がある SharePoint Online のストレージ クォータ全体 (個別に購入した追加のストレージを含む) の 75% に制限することをお勧めします。 


### <a name="source-environment-details"></a>ソース環境の詳細

データ移行サービスは、次のソース環境からデータを移行します。 

- ファイル共有 (SMB 2.0 以降をサポートするデバイスでのサーバー メッセージ ブロック (SMB) ファイルの共有)。
-  単一の G Suite 環境 (Google ドライブのみ)。 
- Box (Starter、Business、Enterprise)。 
- Dropbox for Teams (スタンダードと アドバンスド用)。 

次の表は、各ソース環境に固有の移行の詳細を示しています。

<table>
<thead>
<tr class="header">
 <th><strong>ソース環境</strong></th>
 <th><strong>移行の種類</strong></th>
 <th><strong>移行されるコンテンツ</strong></th>
 <th><strong>移行されないコンテンツ</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>SMB 2.0 以降をサポートするファイル共有デバイス</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのファイルとフォルダーのアクセス許可* </li>
<li> グループ レベルのファイルとフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
</ul>
<br>
*ディレクトリ同期の構成が必要。 エクスプローラーに公開されている NTFS アクセス許可のみが移行されます。 ファイル共有デバイスで直接管理されているアクセス許可は移行されません。 SMB 2.0 デバイスにデータを保存する場合、SMB プロトコルによって公開されている NTFS と同等のアクセス許可が移行されます。 アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。 移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。 グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。</td>
<td><ul>
<li> 所有権の履歴と以前のバージョン </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> 以前のバージョン </li>
<li> Windows のファイルやフォルダーの属性 (読み取り専用、非表示など) </li>
<li> Windows 以外の New Technology File System (NTFS) と NTFS の高度なアクセス許可と特別な設定 </li>
<li> 明示的なアクセス許可の拒否 (移行後に削除、並列アクセス許可または親フォルダーのアクセス許可の対象となるコンテンツ) </li>
<li> NTFS 監査の構成 </li>
<li> ファイル分類インフラストラクチャ (FCI) で提供されている追加のファイルのメタデータ </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> 非表示の共有 </li>
<li> 共有 (共有のレベルに与えられるアクセス許可など) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>単一の G Suite 環境 (Google ドライブのみ)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> Google ドキュメント、スプレッドシート、スライド (10 MB を超えるものを含むファイルは、対応する Office 形式に変換されます) </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可* </li>
<li> グループ レベルのフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有ドライブ (フォルダーとファイル) </li>
<li> 移行中の Google ドライブ アカウントが所有する共有コンテンツ </li>
</ul>
<br>
*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。 移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。 グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。 
</td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明、フォルダーの色 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Google フォト、フォーム、マップとその他の接続されたアプリ </li>
<li> Google 図形描画 </li>
<li> 組織外との共有コンテンツ </li>
<li> Google Drive アカウントが所有していないコンテンツの移行 </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Google ドライブ管理レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> 共有ドライブのメンバー権限 (<strong>注</strong>: Google ドライブ管理レポートを使用して、共有ドライブのメンバーを識別します。 移行前に、対象に対してこれらのメンバーシップ設定を構成するようにエンド ユーザーに指示してください。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可* </li>
<li> グループ レベルのフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 移行される Box アカウントが所有する共有コンテンツ </li>
<li> Box Notes (Word ドキュメント形式に変換) </li>
</ul>
<br>
*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。 移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。 グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。 </td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> Box のタグと高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> ブロックされたユーザーまたは非アクティブなユーザー </li>
<li> Box のアプリ、ブックマーク、お気に入り、およびワークフロー </li>
<li> 移行された Box アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Box レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Teams Dropbox for Teams (スタンダードと アドバンスド用)。</strong></td>
<td>単一または複数のパス</td>
<td><ul>
<li> ドキュメント </li>
<li> ファイルとフォルダーの構造 </li>
<li> ユーザー レベルのフォルダーのアクセス許可* </li>
<li> グループ レベルのフォルダーのアクセス許可* </li>
<li> 15 GB 未満のファイル </li>
<li> 基本的なドキュメントとフォルダーのメタデータ:
<ul>
<li> 作成日 </li>
<li> 更新日 </li>
<li> 作成者 </li>
<li> 最終更新者 </li>
</ul></li>
<li> 共有チームのフォルダーとコンテンツ </li>
<li> 移行される Dropbox アカウントが所有する共有コンテンツ </li>
</ul>
<br>
*アクセス許可は、グループまたはMicrosoft 365チャネルによってMicrosoft Teamsされます。 移行先がグループまたはMicrosoft 365チャネルMicrosoft Teams、移行されたファイルの最終的なアクセス許可プロファイルがグループまたはチャネルによって決定されます。 グループまたはグループ チャネルに移行するファイルに対するアクセス許可Microsoft 365移行Microsoft Teams勧めします。
</td>
<td><ul>
<li> 所有権の履歴、以前のバージョン、コメント </li>
<li> ファイルとフォルダーの説明 </li>
<li> ユーザー レベルのファイルのアクセス許可 </li>
<li> グループ レベルのファイルのアクセス許可 </li>
<li> 高度なメタデータ </li>
<li> ファイル ロックの属性 </li>
<li> コンテンツ内に埋め込まれた URL の変換 </li>
<li> ごみ箱に入れられたアイテム </li>
<li> アクセスできない、または破損しているドキュメント </li>
<li> マウントが解除された Dropbox フォルダー </li>
<li> 削除または切断されたユーザー </li>
<li> Dropbox の用紙、ショーケース、スペース </li>
<li> Dropbox アプリとお気に入り (Pin/スター) </li>
<li> 移行された Dropbox アカウントが所有していないコンテンツ </li>
<li> 外部ユーザーの権限と基本メタデータ (<strong>注</strong>: Dropbox レポートを使用して、外部ユーザーと共有されているコンテンツを特定します。 移行後に外部ユーザーとコンテンツを再共有するようにエンド ユーザーに指示します。) </li>
<li> オンラインの制限と制限SharePointを超えるファイル<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">またはフォルダー</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a>FastTrackグループの移行Microsoft TeamsおよびMicrosoft 365の責任

FastTrack スペシャリストは、移行プロジェクト中に標準的な活動を行います。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。

### <a name="your-responsibilities"></a>お客様の責任 

移行プロジェクト中に標準のアクティビティを実行します。 詳細については、「[プロセスと期待](process-and-expectations.md)」のデータ移行責任に関する情報を参照してください。
また、グループの移行に固有のMicrosoft TeamsアクティビティMicrosoft 365実行します。 

- 移行イベントMicrosoft Teams対象Microsoft 365、すべてのチャネルとグループをプロビジョニングします。

> [!NOTE]
>FastTrackは、チャネルまたはグループMicrosoft TeamsプロビジョニングMicrosoft 365行わない。 FastTrackチャネルまたはグループにエンド ユーザーまたはグループMicrosoft Teams追加Microsoft 365します。 これらの移行先にデータを移行する前に、エンド ユーザーまたはグループをすべての Microsoft Teams チャネルと Microsoft 365 グループに追加して、それらのエンド ユーザーが新しく移行されたドキュメントにアクセスできる必要があります。