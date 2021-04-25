---
title: セキュリティとコンプライアンス
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: Microsoft サービスの FastTrack ガイダンスの詳細。
ms.openlocfilehash: 000a81c51729deba8d3f5c4d88a0baa918dcd048
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996245"
---
# <a name="security-and-compliance"></a>セキュリティとコンプライアンス

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

<td> <p> Microsoft 365 Defender は、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する、侵害前および侵害後の統合エンタープライズ防御スイートです。 次のリモート ガイダンスを提供します。 </p> 
<ul>
<li>  Microsoft 365 セキュリティ センターの概要を説明します。  </li>
<li>  製品間インシデントの確認(攻撃範囲全体、影響を受けたアセット、グループ化された自動修復アクションを確実に行い、重要な状況に集中するなど)。  </li>
<li>  Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、およびメールボックスの調査を調整する方法を示します。 </li>
<li>  複数のデータ セットにわたる電子メール、データ、デバイス、およびアカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探し出す方法の例を説明し、提供します。   </li>
<li> Microsoft Secure Score を使用して、セキュリティ態勢を全体的に確認して改善する方法を顧客に示します。</li>
</ul>
<p><strong>以下はスコープ外です</strong></p>
<ul>
<li> お客様の修復アクティビティのプロジェクト管理。 </li>
<li> 継続的な管理、脅威対応、修復。 </li>
<li> 展開に関するガイダンスまたは教育:
<ul>
<li> さまざまなアラートの種類と監視対象アクティビティを修復または解釈する方法。 </li>
<li> ユーザー、コンピューター、横方向の移動パス、またはエンティティを調査する方法。 </li>
<li> カスタム脅威の検出。  </li>
</ul>
</li>
<li> セキュリティ情報とイベント管理 (SIEM) または API 統合。</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security は、Microsoft およびサード パーティのクラウド サービス全体でサイバー脅威を特定して対処するための、豊富な可視性、データ移動の制御、高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) です。 次のリモート ガイダンスを提供します。
<ul>
<li>  以下を含む、ポータルの構成。  </li>
<ul>
<li> ユーザー グループのインポート。</li>
<li> 管理者のアクセスと設定を管理する。  </li>
<li> 監視または監視から除外する特定のユーザー グループを選択する展開のスコープ。</li>
<li> IP 範囲とタグの設定。</li>
<li> ロゴとカスタム メッセージングを使用してエンド ユーザー エクスペリエンスをカスタマイズする。</li>
</ul>
<li> クラウド検出を設定して、次の方法でシャドウ IT を提供します。</li>
<ul>
<li> Microsoft Defender for Endpoints.</li>
<li> Zscaler。</li>
<li> iboss。</li>
</ul>
<li> アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">を使用して注目</a> のアプリを接続する。</li>
<li> 条件付きアクセス ポータルとクラウド アプリ セキュリティ ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</li>
<li> クラウド アプリセキュリティダッシュボードとクラウド探索ダッシュボードの展開。</li>
<li> 組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</li>
<li> アプリのタグとカテゴリの作成。</li>
<li> アプリの制裁と認可解除。</li>
<li> アクティビティログとファイル ログの使用。</li>
<li> OAuth アプリの管理。</li>
<li> Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</li>
<li> CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> の使用例 (最大 6 つのポリシーの作成または更新を含む) に対する構成支援を提供します。以下を除く。 </li>
<ul>
<li> サービスとしてのインターネットの構成の監査 (IaaS) 環境 (#18)。</li>
<li> IaaS 環境の脅威から保護するためのユーザー アクティビティの監視 (#19)。</li>
</ul>
</ul>
<p><strong>以下はスコープ外です</strong></p>
<ul>
<li> お客様の修復アクティビティのプロジェクト管理。</li>
<li> 継続的な管理、脅威対応、修復。 </li>
<li> Docker またはログ コレクターを使用した継続的なレポートの自動ログ アップロードのインフラストラクチャ、インストール、または展開をセットアップします。 詳細 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">については、「CASB の上位 20 の</a> 使用例」を参照してください。</li>
<li> クラウド探索スナップショット レポートの作成。</li>
<li> ブロック スクリプトを使用してアプリの使用状況をブロックする。</li>
<li> カスタム アプリの接続。</li>
<li> サードパーティ ID プロバイダー (IsP) およびデータ損失防止 (DLP) プロバイダーとの統合。</li>
<li> 高度な検出に関するトレーニングまたはガイダンス。</li>
<li> Microsoft Power Automat プレイブックを含む自動調査と修復。</li>
<li> セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。</li>
<li> 概念実証としてクラウド アプリ セキュリティを展開する。</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  次のリモート ガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティで保護するためのテクノロジの展開。  </li>
<li>  エンドポイント保護とデバイス制限プロファイルの構成。  </li>
<li>  OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サードパーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。  </li>
<li>  展開のガイダンス、構成の支援、および次の教育を行います。
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
<li>  シミュレーションとチュートリアルを確認する (プラクティス シナリオ、偽のマルウェア、自動調査など)。  </li>
<li>  レポート機能と脅威分析機能の概要。  </li>
<li>  Office 365 の ATP と Microsoft Defender ATP の統合。  </li>
<li>  Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。  </li>
<li>  次のオペレーティング システム。
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
<strong>注:</strong> すべての Windows Server バージョンは、System Center Configuration Manager 2012 の最新バージョン (バージョン 1012 R2、1511、または 1602) または Microsoft Endpoint Configuration Manager (バージョン 2002 以上) によって管理する必要があります。 

</li>
</ul>

<strong>以下はスコープ外です </strong>  
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
  モバイル デバイス (Android と iOS)。  
  </li>
</ul></li>
<li>  サーバーのオンボーディングと構成:
<ul>
<li>  
  オフライン通信用にプロキシ サーバーを構成する。  
  </li>
<li>  
  ダウンレベルの Configuration Manager インスタンスとバージョンで Configuration Manager 展開パッケージを構成する。  
  </li>
<li>  
  サーバーを Azure セキュリティ センターにオンボーディングする。  
  </li>
<li>  
  Configuration Manager によって管理されていないサーバー。  
  </li>
</ul></li>
<li>  macOS のオンボーディングと構成:
<ul>
<li>  
  Intune ベースの手動展開。  
  </li>
<li>  
  JAMF ベースの展開。
  </li>
<li>  
  その他のモバイル デバイス管理 (MDM) 製品ベースの展開。  
  </li>
<li>  
  手動展開。  
  </li>
</ul></li>
<li>  次の攻撃面の縮小機能の構成:
<ul>
<li>  
  ハードウェア ベースの分離。  
  </li>
<li>  
  アプリコントロール。  
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
<li>  Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</li>
</li>
</ul>
これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity はクラウドベースのセキュリティ ソリューションであり、オンプレミスの Active Directory のシグナルを活用して、組織に対する高度な脅威、ID の漏えい、内部関係者の不正な行動を特定、検出、調査します。 次のリモート ガイダンスを提供します。
<ul>
<li>   Defender for Identity のインスタンスを作成します。 </li>
<li>   Defender for Identity を Active Directory に接続する。 </li>
<li>   ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。</li>   
<ul> 
<li>  リソース容量計画のサイジング ツールを実行する。 </li>
<li>  監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。 </li>
</ul>
<li>  センサーを展開して、ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャおよび解析します。次の内容を含む。 </li>
<ul> 
<li>  センサー パッケージをダウンロードします。 </li>
<li>  センサーの構成。 </li>
<li>  センサーをドメイン コントローラーにサイレント モードでインストールします。 </li>
<li>  複数フォレスト環境へのセンサーの展開。 </li>
</ul>
<li>  Defender for Identity と Microsoft Cloud App Security の統合 (Cloud App Security のライセンスは必要ありません)。 </li>
<li>  展開ガイダンス、構成支援、および次の教育を提供します。 </li>
<ul>
<li> "ノイズ" を低減するために環境を調整します。  </li>
<li>  ID セキュリティポスチャ評価レポートについて。 </li>
<li>  ユーザーの調査の優先度スコアとユーザー調査のランク付けレポートについて。 </li>
<li> 非アクティブなユーザー レポートについて。  </li>
<li> 侵害されたアカウントに修復オプションを提供する。  </li>
</ul>
<li>  Advanced Threat Analytics (ATA) から Defender for Identity への移行を促進します。 </li>
</ul>
<p><strong>以下はスコープ外です</strong></p>
<ul>

<li> お客様の修復アクティビティのプロジェクト管理。 </li>
<li> 継続的な管理、脅威対応、修復。  </li>
<li> 以下を含む、Defender for Identity センサーの展開。 </li>
<ul>
<li> 手動の容量計画。 </li>
<li> スタンドアロン容量でのセンサーの展開。 </li>
<li> ネットワーク インターフェイス カード (NIC) チーリング アダプターを使用してセンサーを展開する。 </li>
<li> サード パーティ製のツールを使用してセンサーを展開する。 </li>
<li> Web プロキシ接続を介して Defender for Identity クラウド サービスに接続します。 </li>
</ul>
<li> honeytokens の作成と管理。 </li>
<li> 展開に関するガイダンスまたは教育: </li>
<ul>
<li> さまざまなアラートの種類と監視対象のアクティビティを修復または解釈します。  </li>
<li> ユーザー、コンピューター、横方向の移動パス、またはエンティティの調査。 </li>
<li> 脅威または高度な狩猟。 </li>
<li> インシデント対応。 </li>
</ul>
<li> Defender for Identity のセキュリティ アラート ラボ チュートリアルを提供する。 </li>
<li> Defender for Identity が不審なアクティビティを検出した場合に、指名されたセンサーを介して syslog サーバーにセキュリティアラートを送信することで通知を提供します。  </li>
<li> セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行して、特定のコンピューター上のローカル管理者を識別するための Defender for Identity の構成。 </li>
<li> VPN 接続からユーザーのプロファイル ページに情報を追加するための VPN ソリューションの構成。  </li>
<li> セキュリティ情報とイベント管理 (SIEM) または API 統合 (Azure Sentinel を含む)。 </li>
<li> Defender for Identity センサーを概念実証として展開する。</li>
</ul></td>
<td><ul>
<li>  Active Directory が展開されました。  </li>
<li>  Defender for Identity センサーをインストールするドメイン コントローラーには、Defender for Identity クラウド サービスへのインターネット接続があります。  </li>
<ul>
<li> Defender for Identity クラウド サービスと通信するには、ファイアウォールとプロキシを開いている必要があります (*.atp.azure.com ポート 443 が開いている必要があります)。</li>
</ul>
<li> 次のいずれかの方法で実行されているドメイン コントローラー。</li>
<ul>
<li> Windows Server 2008 R2 SP1。</li>
<li> Windows Server 2012。</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016。</li>
<li> WINDOWS Server 2019 および KB4487044 (OS ビルド 17763.316)。</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft 情報ガバナンス</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  保持ラベルとポリシー。  </li>
<li>  レコード管理。  </li>
<li>  削除ポリシー。  </li>
<li>  通信コンプライアンス。  </li>
<li>  インサイダー リスクの管理。  </li>
<li>  Advanced eDiscovery。  </li>
</ul>

  <strong>以下はスコープ外です </strong>  
<ul>
<li> レコード管理ファイル計画の開発。</li>
<li> データ コネクタ。</li>
<li> 情報バリア。</li>
<li> 特権アクセス管理。</li>
<li> SharePoint での情報アーキテクチャの開発。</li>
<li> カスタム スクリプトとコーディング。</li>
</td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="products-and-capabilities.md#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  次のリモート ガイダンスを提供します。
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

<strong>以下はスコープ外です </strong>  
<ul>
<li>顧客キー。</li>
<li>機密情報の種類のカスタム正規表現 (RegEx) の開発。</li>
<li>キーワード ディクショナリの作成または変更。</li>
<li>カスタム スクリプトとコーディング。</li>
</ul>
<strong>注:</strong> 詳細については <strong>、「Azure Information Protection</strong> in Enterprise <a href="products-and-capabilities.md#enterprise-mobility--security">Mobility + Security」を参照してください</a>。
<ul>

</td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="products-and-capabilities.md#general">に、最小</a>システム要件はありません。</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。  </li>
<li>  自動化、調査、応答の構成。  </li>
<li>  攻撃シミュレータの使用。  </li>
<li>  レポート作成と脅威分析。  </li>
</ul></td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="products-and-capabilities.md#general">に、最小</a>システム要件はありません。</td>
</tr>


<tr class="odd">
<td><strong>検出&応答</strong></td>
<td>  

<strong>高度な電子情報開示</strong>
  
<ul>
<li>  安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。  </li>
<li>  自動化、調査、応答の構成。  </li>
<li>  攻撃シミュレータの使用。  </li>
<li>  レポート作成と脅威分析。  </li>
</ul>

<strong>高度な監査</strong> (E5 でのみサポート)

次のリモート ガイダンスを提供します。 
<ul>
<li> 高度な監査を有効にする。</li>
<li> 検索監査ログ UI と基本的な監査 PowerShell コマンドの実行。</li>
</ul>

<strong> コンプライアンス マネージャー</strong>

次のリモート ガイダンスを提供します。  

<ul> <li>役割の種類を確認する。  </li>
<li> 評価の追加と構成。</li>
<li> 改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</li>
<li> 組み込みのコントロール マッピングを確認し、コントロールを評価します。</li>
<li> 評価内でレポートを生成する。</li>
</ul>

<strong>以下はスコープ外です </strong> 
<ul>
<li> カスタム スクリプトまたはコーディング。</li>
<li> 電子情報開示 API。 </li>
<li> データ コネクタ。 </li>
<li> コンプライアンスの境界とセキュリティ フィルター。</li>
<li> データ調査。</li>
<li> データ主体の要求。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul>
</td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="products-and-capabilities.md#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Insider Threat Management</strong></td>

<td>  次のリモート ガイダンスを提供します。
<ul>
<li> ポリシーの作成と設定の確認。</li>
<li> レポートとアラートへのアクセス。</li>
<li> ケースの作成。</li>
<li> 通知テンプレートの作成。</li>
<li> 人事 (HR) コネクタの作成に関するガイダンス。</li>
</ul>

<strong> コミュニケーションコンプライアンス </strong> 

次のリモート ガイダンスを提供します。 
<ul>
<li> ポリシーの作成と設定の確認。</li>
<li> レポートとアラートへのアクセス。</li>
<li> 通知テンプレートの作成。</li>
</ul>

<strong> コンプライアンス マネージャー</strong>

次のリモート ガイダンスを提供します。  

<ul> <li>役割の種類を確認する。  </li>
<li> 評価の追加と構成。</li>
<li> 改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</li>
<li> 組み込みのコントロール マッピングを確認し、コントロールを評価します。</li>
<li> 評価内でレポートを生成する。</li>
</ul>

<strong>以下はスコープ外です </strong> 
<ul>
<li> Power Automate フローの作成と管理。</li>
<li> データ コネクタ (HR コネクタを超えて)。 </li>
<li> カスタム正規表現 (RegEx) 構成。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> 情報バリア。</li>
<li> 特権アクセス管理。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul></td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="products-and-capabilities.md#general">に、最小</a>システム要件はありません。</td>
</tr>


</tbody>
</table>












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