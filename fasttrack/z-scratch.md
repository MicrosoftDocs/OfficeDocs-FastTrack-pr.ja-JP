## <a name="security-and-compliance"></a>セキュリティとコンプライアンス

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender は、高度な攻撃に対する統合された保護を提供するために、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整する、侵害前および侵害後の統合エンタープライズ防御スイートです。 以下に関するリモート ガイダンスを提供します。 </p> 
<ul>
<li>  Microsoft 365 セキュリティ センターの概要について説明します。  </li>
<li>  完全な攻撃範囲、影響を受けた資産、およびグループ化された自動修復アクションを確実にすることで、重要な問題に焦点を当てるなど、製品間のインシデントを確認します。  </li>
<li>  Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、メールボックスの調査を調整する方法を示します。 </li>
<li>  複数のデータ セットにわたる電子メール、データ、デバイス、アカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探す方法の例を説明し、提供します。   </li>
<li> Microsoft セキュア スコアを使用して、顧客が全体的にセキュリティの状態を確認および改善する方法を示します。</li>
</ul>
<p><strong>次に示すのはスコープ外です</strong></p>
<ul>
<li> お客様の修復アクティビティのプロジェクト管理。 </li>
<li> 継続的な管理、脅威への対応、修復。 </li>
<li> 展開に関するガイダンスまたは教育:
<ul>
<li> さまざまなアラートの種類と監視されるアクティビティを修復または解釈する方法。 </li>
<li> ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。 </li>
<li> カスタム脅威の検出。  </li>
</ul>
</li>
<li> セキュリティ情報とイベント管理 (SIEM) または API の統合。</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security は、豊富な可視性、データ移動の制御、および高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) であり、すべての Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処します。 以下に関するリモート ガイダンスを提供します。
<ul>
<li>  以下を含むポータルの構成。  </li>
<ul>
<li> ユーザー グループのインポート。</li>
<li> 管理者のアクセスと設定の管理。  </li>
<li> 監視または監視から除外する特定のユーザー グループを選択するために展開をスコープ設定します。</li>
<li> IP 範囲とタグの設定。</li>
<li> ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスを個人用に設定します。</li>
</ul>
<li> 次を使用してシャドウ IT を提供するクラウド検出を設定します。</li>
<ul>
<li> Microsoft Defender for Endpoints。</li>
<li> Zscaler</li>
<li> iboss。</li>
</ul>
<li> アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">を使った</a> おすすめアプリの接続。</li>
<li> 条件付きアクセス ポータルと Cloud App Security ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</li>
<li> Cloud App Security および Cloud Discovery ダッシュボードの展開。</li>
<li> 組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</li>
<li> アプリ タグとカテゴリの作成。</li>
<li> アプリの許可と削除。</li>
<li> アクティビティとファイル ログの使用。</li>
<li> OAuth アプリの管理。</li>
<li> Microsoft 365 Defender ポータルでのインシデントの相関関係について。</li>
<li> 以下を除き、CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 個の使用事例 (最大 6 個のポリシーの作成または更新を含む) の構成支援を提供します。 </li>
<ul>
<li> サービスとしてのインターネット (IaaS) 環境 (#18)。</li>
<li> ユーザーアクティビティを監視して、IaaS 環境 (#19) の脅威から保護します。</li>
</ul>
</ul>
<p><strong>次に示すのはスコープ外です</strong></p>
<ul>
<li> お客様の修復アクティビティのプロジェクト管理。</li>
<li> 継続的な管理、脅威への対応、修復。 </li>
<li> Docker またはログ コレクターを使用して、継続的レポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。 詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、CASB の上位 20 の</a> 使用事例を参照してください。</li>
<li> クラウド探索スナップショット レポートの作成。</li>
<li> ブロック スクリプトを使用したアプリの使用のブロック。</li>
<li> カスタム アプリの接続。</li>
<li> サードパーティの ID プロバイダー (ISP) およびデータ損失防止 (DLP) プロバイダーとの統合。</li>
<li> 高度な検出に関するトレーニングまたはガイダンス。</li>
<li> Microsoft Power Automate プレイブックを含む自動調査と修復。</li>
<li> セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。</li>
<li> 概念実証としての Cloud App Security の展開。</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティ保護するテクノロジの展開。  </li>
<li>  エンドポイント保護とデバイス制限プロファイルの構成。  </li>
<li>  OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。  </li>
<li>  展開ガイダンス、構成支援、および次の教育について説明します。
<ul>
<li>  
  脅威と脆弱性の管理。  
  </li>
<li>  
  攻撃面の縮小。  
  </li>
<li>  
  次世代の保護。  
  </li>
<li>  
  エンドポイントの検出および応答。  
  </li>
<li>  
  調査と修復の自動化。  
  </li>
<li>  
  セキュア スコア。  
  </li>
</ul></li>
<li>  シミュレーションとチュートリアル (プラクティス シナリオ、偽のマルウェア、自動調査など) の確認。  </li>
<li>  レポート機能と脅威分析機能の概要。  </li>
<li>  Office 365 の ATP と Microsoft Defender ATP の統合。  </li>
<li>  Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。  </li>
<li>  次のオペレーティング システム:
<ul>
<li>  
  Windows 10。  
  </li>
<li>  
  Windows Server 2016。  
  </li>
<li>  
  Windows Server 2019。  
  </li>
<li>  
  Windows Server 2019 Core Edition。  
  </li>
<li>  
  Windows Server Semi-Annual チャネル (SAC) バージョン 1803。  
  </li>
<li>  
  macOS バージョン 10.13、10.14、および 10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理されている必要があります。 

</li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
<ul>
<li>  お客様の修復アクティビティのプロジェクト管理。  </li>
<li>  オンサイト サポート。  </li>
<li>  継続的な管理と脅威の対処。  </li>
<li>  次の Microsoft Defender ATP エージェントのオンボーディングまたは設定:
<ul>
<li>  
  Windows Server 2008。  
  </li>
<li>  
  Windows Server 2012。  
  </li>
<li>  
  Linux。  
  </li>
<li>  
  モバイル デバイス (Android および iOS)。  
  </li>
</ul></li>
<li>  サーバーのオンボーディングと構成:
<ul>
<li>  
  オフライン通信用のプロキシ サーバーの構成。  
  </li>
<li>  
  ダウンレベルの Configuration Manager のインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。  
  </li>
<li>  
  Azure Security Center へのサーバーのオンボーディング。  
  </li>
<li>  
  Configuration Manager によって管理されていないサーバー。  
  </li>
</ul></li>
<li>  macOS のオンボーディングと構成:
<ul>
<li>  
  Intune による手動による展開。  
  </li>
<li>  
  JAMF ベースの展開。
  </li>
<li>  
  その他のモバイル デバイス管理 (MDM) 製品ベースの展開。  
  </li>
<li>  
  手動による展開。  
  </li>
</ul></li>
<li>  次の攻撃面の縮小機能の構成:
<ul>
<li>  
  ハードウェア ベースの分離。  
  </li>
<li>  
  アプリの制御。  
  </li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  ネットワーク ファイアウォール。  
  </li>
</ul></li>
<li>  Microsoft 脅威エキスパートの登録または構成。  </li>
<li>  API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認する構成またはトレーニング。  </li>
<li>  Microsoft 脅威保護 (MTP) の登録または構成。  </li>
<li>  高度な検出に関するトレーニングまたはガイダンス。  </li>
<li>  Kusto クエリの使用または作成に関するトレーニングまたはガイダンス。</li>
</li>
</ul>
これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Id 用 Microsoft Defender </strong></td>
<td>  Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。 以下に関するリモート ガイダンスを提供します。
<ul>
<li>   Id 用の Defender のインスタンスを作成します。 </li>
<li>   Id 用 Defender を Active Directory に接続する。 </li>
<li>   ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。次の機能があります。</li>   
<ul> 
<li>  リソース容量計画用のサイズ変更ツールの実行。 </li>
<li>  監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。 </li>
</ul>
<li>  ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャおよび解析するセンサーの展開。次の機能が含されます。 </li>
<ul> 
<li>  センサー パッケージのダウンロード。 </li>
<li>  センサーの構成。 </li>
<li>  ドメイン コントローラーにサイレント モードでセンサーをインストールします。 </li>
<li>  複数フォレスト環境へのセンサーの展開。 </li>
</ul>
<li>  Id 用 Defender を Microsoft Cloud App Security と統合する (Cloud App Security のライセンスは必要ありません)。 </li>
<li>  展開ガイダンス、構成支援、および次の教育を提供します。 </li>
<ul>
<li> "ノイズ" を低減するために環境を調整します。  </li>
<li>  ID セキュリティの状況評価レポートについて。 </li>
<li>  ユーザーの調査優先度スコアとユーザーの調査ランク付けレポートについて。 </li>
<li> 非アクティブなユーザー レポートについて。  </li>
<li> 侵害されたアカウントでの修復オプションの提供。  </li>
</ul>
<li>  Advanced Threat Analytics (ATA) から Defender for Identity への移行を容易にする。 </li>
</ul>
<p><strong>次に示すのはスコープ外です</strong></p>
<ul>

<li> お客様の修復アクティビティのプロジェクト管理。 </li>
<li> 継続的な管理、脅威への対応、修復。  </li>
<li> Id センサー用の Defender の展開。次の機能が含されます。 </li>
<ul>
<li> 手動による容量計画。 </li>
<li> スタンドアロンの容量でのセンサーの展開。 </li>
<li> ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用したセンサーの展開。 </li>
<li> サード パーティ製のツールを使用したセンサーの展開。 </li>
<li> Web プロキシ接続を介して Defender for Identity クラウド サービスに接続する。 </li>
</ul>
<li> honeytoken の作成と管理。 </li>
<li> 展開に関するガイダンスまたは教育: </li>
<ul>
<li> さまざまなアラートの種類と監視対象アクティビティを修復または解釈します。  </li>
<li> ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。 </li>
<li> 脅威または高度な検索。 </li>
<li> インシデント対応。 </li>
</ul>
<li> Defender for Identity 用のセキュリティ警告ラボ チュートリアルを提供します。 </li>
<li> 指定されたセンサーを介してセキュリティ警告をサーバーに送信することで、Defender for Identity が疑わしいアクティビティを検出した場合に通知を提供します。  </li>
<li> セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行し、特定のコンピューター上のローカル管理者を識別するための Id 用 Defender の構成。 </li>
<li> VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。  </li>
<li> セキュリティ情報とイベント管理 (SIEM) または API の統合 (Azure Sentinel を含む)。 </li>
<li> 概念実証としての ID センサー用の Defender の展開。</li>
</ul></td>
<td><ul>
<li>  展開された Active Directory。  </li>
<li>  Id センサー用 Defender をインストールする予定のドメイン コントローラーは、Defender for Identity クラウド サービスへのインターネット接続を持っています。  </li>
<ul>
<li> ファイアウォールとプロキシは、Defender for Identity クラウド サービスと通信するために開いている必要があります (*.atp.azure.com ポート 443 が開いている必要があります)。</li>
</ul>
<li> 次のいずれかのドメイン コントローラーで実行されます。</li>
<ul>
<li> Windows Server 2008 R2 SP1。</li>
<li> Windows Server 2012。</li>
<li> Windows Server 2012 R2。</li>
<li> Windows Server 2016。</li>
<li> WINDOWS Server 2019 と KB4487044 (OS ビルド 17763.316)。</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft 情報ガバナンス</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  保持ラベルとポリシー。  </li>
<li>  レコード管理。  </li>
<li>  削除ポリシー。  </li>
<li>  通信コンプライアンス。  </li>
<li>  インサイダー リスクの管理。  </li>
<li>  Advanced eDiscovery。  </li>
</ul>

  <strong>次に示すのはスコープ外です </strong>  
<ul>
<li> レコード管理ファイル計画の開発。</li>
<li> データ コネクタ。</li>
<li> 情報バリア。</li>
<li> 特権アクセス管理。</li>
<li> SharePoint での情報アーキテクチャの開発。</li>
<li> カスタム スクリプトとコーディング。</li>
</td>
<td>一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  データの分類。  </li>
<li>  機密情報の種類。  </li>
<li>  秘密度ラベルの作成。  </li>
<li>  感度ラベルの適用。  </li>
<li>  統合されたラベル付け。  </li>
<li>  トレーニング可能な分類子。  </li>
<li>  コンテンツ エクスプローラーとアクティビティ エクスプローラーを使用してデータを把握する。  </li>
<li>  ポリシーを使用したラベルの発行 (手動および自動)。  </li>
<li>  Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。  </li>
<li>  Windows 10 デバイス用のエンドポイント DLP ポリシーの作成。  </li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
<ul>
<li>顧客キー。</li>
<li>機密情報の種類用のカスタム正規表現 (RegEx) 開発。</li>
<li>キーワード ディクショナリの作成または変更。</li>
<li>カスタム スクリプトとコーディング。</li>
</ul>
<strong>注:</strong> 詳細については、「Enterprise <strong> Mobility </strong> + Security の Azure Information <a href="#enterprise-mobility--security">Protection」を参照してください</a>。
<ul>

</td>
<td>一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。  </li>
<li>  自動化、調査、応答の構成。  </li>
<li>  攻撃シミュレータの使用。  </li>
<li>  レポート作成と脅威分析。  </li>
</ul></td>
<td>一般の <strong>コア オンボーディング</strong> 部分以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>

</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>サービス</strong></TD>
<TD width 50%><strong>FastTrack ガイダンスの詳細</strong></TD>
<TD width 25%><strong>ソース環境の期待</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>