---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。
ms.openlocfilehash: e49ada61aee869785f061bbebbee4ae14aaee045
ms.sourcegitcommit: 895a8b9df9a7cd26e27e95e5fd3145e7306c78e8
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464209"
---
# <a name="products-and-capabilities"></a>製品と機能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack でサポートされるサービスとシナリオ 

このトピックでは、FastTrack でサポートされるワークロード シナリオの詳細と、開始する前に必要なソース環境の期待について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件までソース環境を提供します。

FastTrack では、最初にコア機能 (すべてのサービスで共通) を使用し、次Microsoft Online Services対象となる各サービスをオンボーディングする場合に役立つガイダンスを提供します。

  - [全般](#general)
  - [セキュリティと法令遵守](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。 
 
## <a name="general"></a>全般

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>コア オンボーディング</strong></td>
<td>  サービスのプロビジョニング、テナント、ID 統合を含むコア オンボーディングに関するリモート ガイダンスを提供します。 また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。  
  1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。
</li>
</ul>  

<strong> Identity Integration </strong>

次のリモート ガイダンスを提供します。
<ul>
<li>Azure AD Connect (単一フォレストまたは複数フォレスト) とライセンス (グループ ベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</li>
<li>グループ ベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</li>
<li>クラウドジャーニー、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (FS) の正しい認証方法を選択して有効ADします。</li>
<li>Azure AD接続ツールと同期された単一の Active Directory フォレストと ID を持つユーザーの FS AD有効にします。 これには、R2 active Directory フェデレーション Windows Server 2012 2.0 以上が必要です。</li>
<li>パスワード ハッシュ同期またはパススルー ADを使用AD FS から Azure への認証の移行。</li>
<li>シングル サインオン (SSO) 用に、AD FS から Azure AD に事前統合されたアプリ (Azure AD ギャラリー のサービスとしてのソフトウェア (SaaS) アプリなど) を移行します。</li>
<li>Azure AD ギャラリーから SaaS アプリの SSO との統合を有効にします。</li>
<li>アプリ統合チュートリアル リストに記載されている統合済み SaaS アプリの自動ユーザー プロビジョニングを <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">有効にする</a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみ)。  </li>
</td>

<td>  <strong>ネットワークの有効化 </strong>  
  <br>FastTrack のメリットの一環として、Microsoft 365 の最高レベルのパフォーマンスを確保するためにクラウド サービスに接続するためのベスト プラクティスについてアドバイスします。  
  
<strong>Active Directory フォレスト</strong> これらは、次のフォレスト構成を使用して、Windows Server 2003 以降に機能フォレスト レベルを設定します。
<ul>
<li>  1 つの Active Directory フォレスト。  </li>
<li>  単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。  </li>
<li>  複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。  </li>
<li>  必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。   </li>
</ul>
  <strong>大事な</strong>  <ul>
<li>  複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。  </li>
<li>  Exchange マルチハイブリッド構成で複数の Exchange 組織に複数の Active Directory フォレストを実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。 Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。 詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。  </li>
<li>  複数のフォレスト構成の場合、Active Directory フェデレーション サービス (FS AD) の展開はスコープ外です。 このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 アプリ</strong></td>
<td>  次のリモート展開ガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。  </li>
<li>  iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  ローカルまたはクラウドのインストールの選択とセットアップ。  </li>
<li>  Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。  </li>
<li>  Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。  
  さらに、以前のバージョンの Office で動作したマクロまたはアドインがある場合、互換性の問題が発生した場合は、App Assure プログラムを通じて追加コストで互換性の問題を修復するガイダンスを提供します。 詳細については <strong>、「Windows</strong> <a href="#windows-10">10</a> の App Assure 部分」を参照してください。 </li>
</ul></td>
<td><ul>
<li>  オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>ネットワークの正常性</strong></td>
<td>  お客様の環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを提供し、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">示します</a>。 これにより、移行速度、ユーザー エクスペリエンス、サービスパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調表示されます。  
  また、ネットワーク スコアの向上に役立つ、このデータで強調表示されている修復手順について説明します。  </td>
<td><ul>
<li>  Microsoft 365 管理センターへのアクセス。  </li>
<li>  Microsoft 365 アプリの最新バージョンが必要です。  </li>
<li>  <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている場所サービス。  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>セキュリティとコンプライアンス

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></td>
<td>  クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。  

 <br/>

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
<ul>
<li>  Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。  </li>
<li>  Azure 以外のプレミアム ユーザー AD、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。  </li>
<li>  Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。  </li>
<li>  Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。  </li>
<li>  Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。  </li>
<li>  Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。  </li>
<li>  カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。  </li>
<li>  Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。  </li>
<li>  役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して、Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure AD構成します。  </li>
<li>  Azure AD構成します。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure AD 接続正常性を使用AD FS、Azure AD AD 接続、およびドメイン コントローラーのリモート監視を有効にします。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。
  </li>
<li>  
  Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。  
  </li>
<li>  
  Azure AD利用規約を確認します。  
  </li>
<li>  
  Azure の特権 ID 管理を使用して、特権管理者アカウントへのアクセスAD制御します。  
  </li>
</ul>
  
<strong>オートメーションと効率 </strong>  
<ul>
<li>  
  Azure AD SSPR を有効にする。  
  </li>
<li>  ユーザーが独自のクラウド セキュリティまたは 365 グループを作成および管理Office、Azure ADグループ管理を使用できます。  </li>
<li>  Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。  </li>
<li>  動的グループAD Azure を有効にする。  </li>
<li>  コレクションを使用して My Apps ポータルでアプリを整理する。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は、Azure AD Premium 用に準備されています。Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復も含まれます。</td>
</tr>
<tr class="odd">
<td><strong>Azure 情報保護 </strong></td>
<td>  Azure Information Protection の詳細については、この表の <strong>「Microsoft Information Protection」</strong> を参照してください。

  </td>
<td>  
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
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
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
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender は、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整し、高度な攻撃に対する統合保護を提供する統合された侵害前および侵害後のエンタープライズ防御スイートです。 次のリモート ガイダンスを提供します。 </p> 
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
<tr class="odd">
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
<li> アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使用して注目</a> のアプリを接続する。</li>
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
<li> 概念実証としてクラウド アプリの検出を展開する。</li>
</ul></td>
</tr>



<tr class="even">
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
<li> 仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。  </li>
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
<li> デバイス制御。</li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  ネットワーク ファイアウォール。  
  </li>



</ul></li>
<li> 次のようなアカウント保護機能の構成または管理。 </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> BitLocker の構成または管理。</li>
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
<li>  保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。  
</li>
<li>  レコード管理 (E5 でのみサポート)。  </li>
<ul><li>  ファイル 計画の作成を確認する。 </li>
<li>  レコードの作成と管理 (イベント ベースのレコードを含む)。  </li>
<li>  廃棄の確認。 </ul> </li>
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
<li> レコード管理ファイル計画の開発。</li>
<li> データ コネクタ。</li>
<li> SharePoint での情報アーキテクチャの開発。</li>
<li> カスタム スクリプトとコーディング。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> E3 のサポート。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul>

</td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  データ分類 (E3 および E5 でサポート)。  </li>
<li>  機密情報の種類 (E3 および E5 でサポート)。  </li>
<li>  感度ラベルの作成 (E3 および E5 でサポート)。  </li>
<li>  感度ラベルの適用 (E3 および E5 でサポート)。  </li>
<li>  トレーニング可能な分類子 (E5 でサポート)。  </li>
<li>  コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。  </li>
<li>  ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。  </li>
<li>  Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。  </li>
<li>  Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。  </li>
</ul>

<strong> コンプライアンス マネージャー</strong>

次のリモート ガイダンスを提供します。  

<ul> <li>役割の種類を確認する。  </li>
<li> 評価の追加と構成。</li>
<li> 改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</li>
<li> 組み込みのコントロール マッピングを確認し、コントロールを評価します。</li>
<li> 評価内でレポートを生成する。</li>
</ul>

<strong> Azure 情報保護</strong>

次のリモート ガイダンスを提供します。  
<ul>
<li>  テナントのアクティブ化と構成。  </li>
<li>  ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。  </li>
<li>  ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。  </li>
<li>  Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。  </li>
<li>  Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>

  Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。

<strong>以下はスコープ外です </strong>  
<ul>
<li>顧客キー。</li>
<li>機密情報の種類のカスタム正規表現 (RegEx) の開発。</li>
<li>キーワード ディクショナリの作成または変更。</li>
<li>カスタム スクリプトとコーディング。</li>
<li> Azure Purview。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul>

<ul>

</td>
<td>General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a>

<strong>Azure Information Protection</strong>

お客様の前提条件の責任は次のとおりです。  
<ul>
<li>  スキャンするファイル共有の場所の一覧。  </li>
<li>  承認済みの分類分類。 </li>
<li> キー管理に関する規制上の制限または要件について理解する。  </li>
<li>  Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。 </li>
<li>  分類と保護用に構成されたラベル。 </li>
<li> Azure Information Protection スキャナーのすべての前提条件が満たされています。 詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。 </li>
<li>  ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。 詳細については、以下を参照してください。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </li>
</ul>
<li> ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。  </li>
<li> 展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。 具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。 以下の手順が含まれる可能性があります:
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  次の管理ニーズに基づいて MDM 機関を構成します。
<ul>
<li>  Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。  </li>
</ul></li>
<li>  以下の MDM ガイダンスの提供:
<ul>
<li>  MDM 管理ポリシーの検証に使用するテストグループの構成。  </li>
<li>  以下のような、MDM 管理ポリシーとサービスの構成:
<ul>
<li>  Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。  </li>
<li>  Intune データ ウェアハウスへの接続。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。  </li>
<li>  モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。  </li>
<li>  通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。  </li>

</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  アプリ保護に関するガイダンスを提供する:
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理アプリの条件付きアクセス ポリシーを構成する。  </li>
<li>  前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。  </li>
<li>  管理アプリの使用状況レポートを使用する。  </li>
</ul></li>
<li>  従来の PC 管理から Intune MDM への移行ガイダンスを提供します。  </li>
</ul>
 
</li>
</ul>
  
<strong>クラウド接続</strong>  

  Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  ハイブリッド Azure グループへの参加をセットアップするAD提供します。  </li>
<li>  MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。  </li>
<li>  リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。  
  Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。 次のものが含まれます。
<ul>
<li>  Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。  </li>
<li>  セットアップに関するガイダンスを提供します。
<ul>
<li>  Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  アプリ構成ポリシー。  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。  
  <strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。  
 
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: Intune と Microsoft Defender ATP の統合と、Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供しています。 購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。 このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。  
  
</td>
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
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。 正確な手順は、ソース環境とメール移行計画によって異なります。  
  次のリモート ガイダンスを提供します。
<ul>
<li>  Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。  </li>
<li>  メール交換 (MX) レコードを 365 Officeします。  </li>
<li>  サブスクリプション サービスのOffice 365 ATP 機能をセットアップします。 詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> の部分を参照してください。  </li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
</ul>
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、情報権利管理 (IRM) メールをオンプレミスメールボックスから対応する Exchange Online メールボックスに移行します。 移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。  
<ul>
<li>  ファイアウォール ポートの構成。  </li>
<li>  必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys 識別メール (DKIM)、ドメイン ベースのメッセージ認証、レポートと準拠 (DMARC)、MX レコード (必要に応じて) を含む DNS のセットアップ。  </li>
<li>  ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。  </li>
<li>  ソースのメッセージング環境から Office 365 にメール移行を実行。  </li>
<li>  メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。  </li>
</ul>
  <strong>データ移行</strong>  <br>
FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。   
<td>  ソース環境には、次のいずれかの最小レベルが必要です。
<ul>
<li>  Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。  </li>
<li>  1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。  </li>
<li>  単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。  </li>
<li>  複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域機能」を参照してください</a>。  </li>
</ul>
Project for Office 365、Outlook for Windows、Outlook for iOS、Android、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>Office のシステム要件で定義されている最小レベルである必要があります。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 情報ガバナンス</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  保持ラベルとポリシーの作成と発行 (E5 でのみサポート)。  
</li>
<li>  レコード管理 (E5 でのみサポート)。  </li>
<ul><li>  ファイル 計画の作成を確認する。 </li>
<li>  レコードの作成と管理 (イベント ベースのレコードを含む)。  </li>
<li>  廃棄の確認。 </ul> </li>
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
<li> レコード管理ファイル計画の開発。</li>
<li> データ コネクタ。</li>
<li> SharePoint での情報アーキテクチャの開発。</li>
<li> カスタム スクリプトとコーディング。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> E3 のサポート。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul>


</td>
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  データ分類 (E3 および E5 でサポート)。  </li>
<li>  機密情報の種類 (E3 および E5 でサポート)。  </li>
<li>  感度ラベルの作成 (E3 および E5 でサポート)。  </li>
<li>  感度ラベルの適用 (E3 および E5 でサポート)。  </li>
<li>  トレーニング可能な分類子 (E5 でサポート)。  </li>
<li>  コンテンツ エクスプローラーとアクティビティ エクスプローラーでデータを知る (E5 でサポート)。  </li>
<li>  ポリシー (手動および自動) を使用してラベルを発行する (E5 でサポート)。  </li>
<li>  Windows 10 デバイス用のエンドポイント データ損失防止 (DLP) ポリシーの作成 (E5 でサポート)。  </li>
<li>  Microsoft Teams のチャットとチャネルの DLP ポリシーを作成する。  </li>
</ul>

<strong> コンプライアンス マネージャー</strong>

次のリモート ガイダンスを提供します。  

<ul> <li>役割の種類を確認する。  </li>
<li> 評価の追加と構成。</li>
<li> 改善アクションを実装し、コンプライアンス スコアに与える影響を判断して、コンプライアンスを評価します。</li>
<li> 組み込みのコントロール マッピングを確認し、コントロールを評価します。</li>
<li> 評価内でレポートを生成する。</li>
</ul>

<strong> Azure 情報保護</strong>

次のリモート ガイダンスを提供します。  
<ul>
<li>  テナントのアクティブ化と構成。  </li>
<li>  ラベルとポリシーの作成と設定 (P1 と P2 でサポート)。  </li>
<li>  ドキュメントへの情報保護の適用 (P1 および P2 でサポート)。  </li>
<li>  Windows で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) で情報を自動的に分類およびラベル付けし、Azure Information Protection クライアント (P2 でサポート) を使用します。  </li>
<li>  Azure Information Protection スキャナー (P1 および P2 でサポート) を使用して、保存中のファイルの検出とラベル付け。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>
  
Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合のガイダンスも提供します。

<strong>以下はスコープ外です </strong>  
<ul>
<li>顧客キー。</li>
<li>機密情報の種類のカスタム正規表現 (RegEx) の開発。</li>
<li>キーワード ディクショナリの作成または変更。</li>
<li>カスタム スクリプトとコーディング。</li>
<li> Azure Purview。</li>
<li> デザイン、アーキテクト、サードパーティ製のドキュメント レビュー。</li>
<li> 業界および地域の規制および要件への準拠。</li>
<li> コンプライアンス マネージャーでの評価に対する推奨される改善アクションの実践的な実装。</li>
</ul>

</td>
<td>General の<strong>コア オンボーディング部分</strong>以外に、Azure Information Protection を除く最小システム要件はありません。 <a href="#general"></a>

<strong>Azure Information Protection</strong>

お客様の前提条件の責任は次のとおりです。  
<ul>
<li>  スキャンするファイル共有の場所の一覧。  </li>
<li>  承認済みの分類分類。 </li>
<li> キー管理に関する規制上の制限または要件について理解する。  </li>
<li>  Azure サーバーと同期されたオンプレミスの Active Directory 用に作成されたサービス AD。 </li>
<li>  分類と保護用に構成されたラベル。 </li>
<li> Azure Information Protection スキャナーのすべての前提条件が満たされています。 詳細については、「Azure Information Protection 統合ラベル スキャナーをインストールして展開するための前提条件」 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">を参照してください</a>。 </li>
<li>  ユーザー デバイスがサポートされているオペレーティング システムを実行し、必要な前提条件がインストールされていることを確認します。 詳細については、以下を参照してください。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理者ガイド: ユーザー向け Azure Information Protection 統合ラベル 付けクライアントをインストールする</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </li>
</ul>
<li> ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。  </li>
<li> 展開に次のいずれかのオプションが必要な場合は、Bring Your Own Key (BYOK)、ダブル キー暗号化 (DKE) (統合ラベル 付けクライアントのみ)、または Hold Your Own Key (HYOK) (クラシック クライアントのみ) のセットアップと構成を行います。  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADで Teams をサポートしていることを確認します。  </li>
<li>  ファイアウォール ポートの構成。  </li>
<li>  DNS の設定。  </li>
<li>  Teams が Office 365 テナントで有効であることの確認。  </li>
<li>  ユーザーのライセンスの有効化と無効化。  </li>
<li>  Teams のネットワーク評価:
<ul>
<li>  ポートとエンドポイントの確認。  </li>
<li>  接続品質の確認。  </li>
<li>  帯域幅の推定値。  </li>
</ul>
<ul>
<li>  Teams アプリ ポリシーの構成 (Teams Web アプリ、Teams デスクトップ アプリ、および Teams for iOS および Android アプリ)。  </li>
</ul>
該当する場合は、次のガイダンスも提供します。
<ul>
<li>  Microsoft Teams ルーム デバイス:  </li>
<ul>
<li>  <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイス カタログ</a>に一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン アカウントの作成。  </li>
<li>  認定された Microsoft Teams Rooms デバイスのサービス側構成に関するリモート アシスタンス。  </li>
<li>  電話会議を有効にする:  </li>
<li>  会議ブリッジの既定の設定のための組織のセットアップ。  </li>
<li>  ライセンスを持つユーザーへの会議ブリッジの割り当て。  </li>
</ul>
<li>  電話システム:
<ul>
<li>  Cloud Voice の既定の設定のための組織のセットアップ。  </li>
<li>  通話プランのガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):
<ul>
<li>  ライセンスを持つユーザーへの番号の割り当て。  </li>
<li>  ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。  </li>
<li>  999 件を超える電話番号の移植サービス リクエスト (SR) サポート。  </li>
</ul></li>
<li>  直接ルーティングのガイダンス:
<ul>
<li>  パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。  </li>
<li> セッション ボーダー コントローラー (SBC) の構成レビュー。 </li>

<li> ダイヤル プランの構成に関するリモート アシスタンス。 </li>

<li> 音声ルートの構成。</li>

<li> メディア バイパスとローカル メディアの最適化。 </li>

</ul></li>
</ul></li>
<li>  Teams ライブ イベントの有効化。  </li>
<li>  組織のセットアップと Microsoft Stream への統合。  </li>
<li>  Skype for Business から Teams への移行に関するガイダンス。  </li>
</ul></td>
<td><ul>
<li>  Azure AD 365 でOffice ID。  </li>
<li>  SharePoint Online に対してユーザーが有効になっている。  </li>
<li>  Exchange メールボックスが存在します (Exchange ハイブリッド構成ではオンラインとオンプレミス)。  </li>
<li>  Office 365 グループに対して有効になっている。  </li>
</ul>
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスで割り当ておよび有効になっていない場合、OneDrive for Business ストレージは 365 Officeされません。 ファイル共有はチャネルで引き続き機能しますが、ユーザーは 365 で OneDrive for Business ストレージを使用せずにチャットでファイルをOfficeできます。 Teams は SharePoint オンプレミスをサポートしない。  <br>
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する場合です。 オンプレミスに存在するメールボックスを持つユーザーは、Azure Office Connect を介して id を Office 365 ディレクトリAD必要があります。 これらの Exchange ハイブリッド顧客の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。  
  Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。  </td>
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
<td>General の <strong>コア オンボーディング部分</strong> 以外 <a href="#general">に、最小</a>システム要件はありません。</td>
</tr>
<tr class="even">
<td><strong>iOS 版および Android 版 Outlook</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。  </li>
<li>  アカウントの構成、および Exchange Online メールボックスへのアクセス。  </li>
<li>  Outlook モバイルのセキュリティ保護 (詳細 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">については、「Exchange Online</a> での Outlook for iOS と Android のセキュリティ保護」を参照してください)。  </li>
</ul></td>
<td><ul>
<li>  Azure AD 365 でOffice ID。  </li>
<li>  Exchange Online が構成され、ライセンスが割り当てられている。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  Power BI ライセンスの割り当て。  </li>
<li>  Power BI Desktop アプリの展開。  </li>
</ul></td>
<td>Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  Project Online が依存している基本的な SharePoint の機能の確認。  </li>
<li>  テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。  </li>
<li>  エンタープライズ リソース共有元 (ERP) のセットアップ。  </li>
<li>  最初のプロジェクトの作成。  </li>
</ul></td>
<td>Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional and Premium</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。  </li>
<li>  Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。  </li>
</ul></td>
<td>Project for Office 365 のようなオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</td>
</tr>
<tr class="even">
<td><strong>Sharepoint Online と OneDrive for Business</strong></td>
<td>  次のリモート ガイダンスを提供します。
<ul>
<li>  DNS の設定。  </li>
<li>  ファイアウォール ポートの構成。  </li>
<li>  ユーザーとライセンスのプロビジョニング。  </li>
<li>SharePoint Online 管理者のサイト作成の有効化。</li>
<li>サイト コレクションのプランニング。</li>
<li>コンテンツのセキュリティ保護および権限の管理。</li>
<li>SharePoint Online 機能の構成。</li>
<li>  ハイブリッド検索、ハイブリッド サイト、ハイブリッド分類、コンテンツ タイプ、ハイブリッド セルフサービス サイト作成 (SharePoint Server 2013 のみ)、拡張アプリ起動ツール、ハイブリッド OneDrive for Business、エクストラネット サイトなどの SharePoint ハイブリッド機能の構成。  </li>
<li>  移行方法。  </li>
</ul>
SharePoint のバージョンに応じて、OneDrive for Business に関する追加のガイダンスが提供されます。次のようにします。
<ul>
<li>  統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。  </li>
<li>  SharePoint Online 2013 SP1 のインストール (該当する場合)、同期要件と ID 要件の計画と実装、OneDrive for Business 同期クライアントの識別。  </li>
<li>  すべてのユーザー (または段階的なロールアウト) に対する 1 つのロールアウトの計画と実装。  </li>
<li>  ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリのリダイレクトを Office 365 (SharePoint Online 2013 に適用) し、OneDrive へのアクセスを制御する対象ユーザーを設定します (SharePoint Online 2013 に適用)。  </li>
<li>既知のフォルダーを OneDrive にリダイレクトまたは移動する。</li>
<li>  OneDrive for Business クライアント同期の展開。  </li>
</ul>
  <strong>データ移行</strong>  <br>
FastTrack 特典を使用してデータを 365 に移行する方法については、「Office移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。
</ul></td>
<td><br><strong>SharePoint ハイブリッドの場合:</strong>  
<ul>
<li>  SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ 起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。  </li>
</ul>
  <strong>注:</strong> セルフサービス サイトの作成は、SharePoint 2013 を実行しているオンプレミス サーバーでは有効ではありません。  
<ul>
<li>  SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。  </li>
</ul>
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードはスコープ内ではありません。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナーにお</a> 問い合わせください。 詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能の最小パブリック更新レベル」を参照してください</a><em>。</em>  <br>
  <strong>注:</strong> 複数地域機能の詳細については、「OneDrive の複数地域機能」および <a href="https://go.microsoft.com/fwlink/?linkid=831056">「SharePoint Online in oneDrive」および「SharePoint Online in Office 365」を参照してください</a><em>。</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
エンタープライズ サービスを有効にするためのリモート ガイダンスYammer提供します。  
</ul></td>
<td>オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></td>
<td>  クラウド ID をセキュリティで保護するためのリモート ガイダンスは、次のシナリオで提供されます。  

 <br/>

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
<ul>
<li>  Azure 多要素認証 (MFA) (クラウドのみ) による保護、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID に対する強力な認証の構成と有効化。  </li>
<li>  Azure 以外のプレミアム ユーザー AD、セキュリティの既定値を使用して ID をセキュリティで保護するためのガイダンスが提供されます。  </li>
<li>  Azure のプレミアム AD、条件付きアクセスを使用して ID をセキュリティで保護するためのガイダンスが提供されます。  </li>
<li>  Azure パスワード保護を使用して脆弱なパスワードの使用を検出ADブロックします。  </li>
<li>  Azure アプリケーション プロキシを使用してオンプレミス Web アプリへのリモート アクセスAD保護します。  </li>
<li>  Azure Identity Protection を使用してリスクベースの検出と修復を有効にします。  </li>
<li>  カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。  </li>
<li>  Azure AD B2B を使用して、アプリとサービスをゲスト ユーザーと安全に共有します。  </li>
<li>  役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して、Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure AD構成します。  </li>
<li>  Azure AD構成します。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure AD 接続正常性を使用AD FS、Azure AD AD 接続、およびドメイン コントローラーのリモート監視を有効にします。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure の資格管理ADを使用して、Azure の ID とアクセス のライフサイクルをAD管理します。
  </li>
<li>  
  Azure グループ のAD、エンタープライズ アプリ アクセス、およびロールの割り当てを Azure アクセス レビュー AD管理します。  
  </li>
<li>  
  Azure AD利用規約を確認します。  
  </li>
<li>  
  Azure の特権 ID 管理を使用して、特権管理者アカウントへのアクセスAD制御します。  
  </li>
</ul>
  
<strong>オートメーションと効率 </strong>  
<ul>
<li>  
  Azure AD SSPR を有効にする。  
  </li>
<li>  ユーザーが独自のクラウド セキュリティまたは 365 グループを作成および管理Office、Azure ADグループ管理を使用できます。  </li>
<li>  Azure または委任されたグループ管理を使用して、エンタープライズ アプリADアクセスを管理します。  </li>
<li>  動的グループAD Azure を有効にする。  </li>
<li>  コレクションを使用して My Apps ポータルでアプリを整理する。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は、Azure AD Premium 用に準備されています。Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復も含まれます。</td>
</tr>
<tr class="odd">
<td><strong>Azure 情報保護 </strong></td>
<td>  Azure Information Protection の詳細については <strong>、「Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Compliance」を参照してください。  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  アプリとデバイスのクラウドベースのモバイル デバイス管理 (MDM) プロバイダーおよびモバイル アプリ管理 (MAM) プロバイダーとして Intune を使用する準備に関するリモート ガイダンスを提供します。 具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。 以下の手順が含まれる可能性があります:
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID (Azure AD) を活用して、Intune で使用される ID を構成します。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  次の管理ニーズに基づいて MDM 機関を構成します。
<ul>
<li>  Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。  </li>
</ul></li>
<li>  以下の MDM ガイダンスの提供:
<ul>
<li>  MDM 管理ポリシーの検証に使用するテストグループの構成。  </li>
<li>  以下のような、MDM 管理ポリシーとサービスの構成:
<ul>
<li>  Web リンクまたはディープ リンクを介したサポートされている各プラットフォームのアプリの展開。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合は、電子メール、ワイヤレス ネットワーク、VPN プロファイルを展開します。  </li>
<li>  Intune データ ウェアハウスへの接続。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモート アシスタンス用のチーム ビューアー (チーム ビューアーサブスクリプションが必要です)。  </li>
<li>  モバイル脅威防御 (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。  </li>
<li>  通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。  </li>
</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  アプリ保護に関するガイダンスを提供する:
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理アプリの条件付きアクセス ポリシーを構成する。  </li>
<li>  前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定します。  </li>
<li>  管理アプリの使用状況レポートを使用する。  </li>
</ul></li>
<li>  従来の PC 管理から Intune MDM への移行ガイダンスを提供します。  </li>
</ul>
  
</li>
</ul>
  
<strong>クラウド接続</strong>  

  Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備について説明します。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  ハイブリッド Azure グループへの参加をセットアップするAD提供します。  </li>
<li>  MDM 自動登録用の Azure AD設定に関するガイダンスを提供します。  </li>
<li>  リモート インターネット ベースのデバイス管理の共同管理のためのソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>iOS および Android 用 Outlook モバイルを安全に展開する</strong> Outlook mobile for iOS および Android を組織に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供できます。  
  Intune を使用して Outlook mobile for iOS および Android を安全に展開する手順は、ソース環境によって異なります。 次のものが含まれます。
<ul>
<li>  Apple App Store または Google Play ストアを使用して、Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードします。  </li>
<li>  セットアップに関するガイダンスを提供します。
<ul>
<li>  Outlook for iOS および Android、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  アプリ構成ポリシー。  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャを実稼働環境で既に機能している必要があります。  
  <strong>注</strong>: FastTrack サービスの利点には、Intune の認証局、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含されません。  
 
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: Intune と Microsoft Defender ATP の統合と、Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供しています。 購入、ライセンス認証、またはライセンス認証に関するサポートは提供しない。 このサポート <a href="https://go.microsoft.com/fwlink/?linkid=2080150">については、Microsoft パートナー</a> にお問い合わせください。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Windows 10 Enterprise への Windows 7 Professionalおよび Windows 8.1 Professional へのアップグレードに関するガイダンスを提供します。  
  次のリモート ガイダンスを提供します。
<ul>
<li>  Windows 10 の意図を理解する。  </li>
<li>  ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。  </li>
<li>  Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。  </li>
<li>  Windows 10 アプリを評価するためのオプションをお勧めします。  </li>
<li>  デスクトップ分析の使用と、デスクトップ分析の展開計画の作成によるガイダンスを有効にする。  </li>
<li>  構成マネージャーの Office 365 準備ダッシュボードを活用するか、Office 用のスタンドアロンの準備 Toolkit と Microsoft 365 Apps の展開を支援することで、Microsoft 365 Apps の互換性評価を行います。  </li>
<li>  展開を成功するために、ソース環境を最小要件まで引き上げするために必要な処理に関する修復チェックリストを作成します。  </li>
<li>  必要なデバイス ハードウェア要件を満たす場合に、既存のデバイスのアップグレード ガイダンスを Windows 10 Enterprise に提供します。  </li>
<li>  既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。  </li>
<li>  Windows 10 展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。   </li>
<li>  既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。  </li>
</ul>
  <strong>以下はスコープ外です </strong>  
<ul>
<li>  Configuration Manager の Current Branch へのアップグレード。  </li>
<li>  Windows 10 展開用のカスタム画像の作成。  </li>
<li>  Windows 10 の展開用の展開スクリプトの作成とサポート。  </li>
<li>  Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。  </li>
<li>  Windows 10 のセキュリティ機能の有効化。  </li>
<li>  Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。  </li>
<li>  Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。  </li>
<li>  ユーザー状態移行ツール (USMT) の使用。  </li>
</ul>
これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。  </td>
<td>  PC のアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  ソース OS: Windows 7 Enterpriseまたはプロフェッショナル、Windows 8.1 Enterprise または Professional。  </li>
<li>  デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。  </li>
<li>  ターゲット OS: ウィンドウ 10 Enterprise。  </li>
</ul>
インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  Microsoft Endpoint Configuration Manager。  </li>
<li>  Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。 詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。  </li>
</ul>

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
<li> Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。  </li>
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
<li> 仮想デスクトップ インフラストラクチャ (VDI) (永続的または非永続的)。  </li>
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
<li> デバイス制御。</li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  ネットワーク ファイアウォール。  
  </li>

<ul>
<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>

</ul></li>
<li> BitLocker の構成または管理。</li>
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

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Windows Virtual Desktop (デスクトップおよびアプリ仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。 Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</p>
<p>次のリモート ガイダンスを提供します。</p>
<ul>
<li>Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows 仮想デスクトップ環境を展開するには、次の手順を実行します。
<ul>
<li>Azure Marketplace イメージ。</li>
<li>共有イメージ。</li>
<li>Office展開Toolkit (ODT)</li>
</ul></li>
<li>FSLogix の構成:
<ul>
<li>プロファイル コンテナーを使用した FSLogix エージェントの展開。</li>
<li>FSLogix エージェントをコンテナーでOfficeします。</li>
<li>コンテンツの除外を使用して FSLogix フォルダーを構成する。</li>
</ul></li>
<li>Microsoft Edge の展開。</li>
<li>Microsoft Teams の展開。</li>
<li>Windows 仮想デスクトップ クライアントを使用した接続。</li>
</ul>

<strong>以下はスコープ外です</strong>
<ul>
<li>お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</li>
<li>サード パーティ製アプリの仮想化と展開。</li>
<li>カスタム イメージ。</li>
<li>VMware と Citrix が関係する移行とシナリオ。</li>
<li>Linux のシナリオ。</li>
<li>ユーザー プロファイルの変換または移行。</li>
</ul>
これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</td>
<td>次の情報が既に必要です。
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</li>
<li>Azure ネットワーク:
<ul>
<li>仮想ネットワーク (VNET) の作成とサブネット化。</li>
<li>ファイアウォールとネットワーク セキュリティ グループ。</li>
<li>VPN と ExpressRoute。</li>
<li>オンプレミスから Azure へのルーティング。</li>
<li>Windows 仮想デスクトップへの接続を許可するファイアウォール ルール。
</ul>
詳細については、「サポートされる <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> リモート デスクトップ クライアント」を参照してください</a>。
</ul>
<ul><li>Azure AD一般的なセットアップ:
<ul>
<li>ID 戦略 <i>(次の 3 つのオプションの 1 つのみを使用できます)。</i>
<ul>
<li>Azure を使用した Active Directory AD Azure で接続します。</li>
<li>Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</li>
<li>Active Directory ドメイン サービス (DS AD)。</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>App Assure


<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>App Assure</strong></td>
<td>  App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。 App Assure サービスを要求すると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加費用を支払う必要はありません。 また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様に対してガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力をします。 Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供しています。
<ul>
<li>  <strong>Windows 10 </strong> (ARM64 デバイスを含む)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。  </li>
<li>  <strong>Windows 仮想デスクトップ</strong> - 詳細については <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは」</a> および <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">「Windows 10 Enterprise マルチセッション FAQ」を参照してください</a>。  </li>
</ul>

<strong>以下はスコープ外です </strong>  
<ul>
<li>  アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。 このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。 詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</li>
<li>  サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。 詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</li>
<li>アプリのパッケージ化専用サービス。 ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</li>
</ul>

<strong>顧客の責任は次のとおりです。</strong>  
<ul>
<li>  アプリ インベントリの作成。</li>
<li>  Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</li>
</ul>
<strong>注:</strong>  Microsoft では、ソース コードを変更できない。 ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。 


  これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。  </td>

</td>
<td><strong>Windows 10 および Microsoft 365 アプリ</strong>
<ul>
<li>  
  Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。  
  </li>
</ul>
<strong>Windows 10 on ARM</strong>
<ul>
<li>  
Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイスの Windows 10 および Microsoft 365 Apps でも動作します。 
  </li>
</ul>
  <strong>注:</strong> 
<ul>
<li> x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様に <a href="https://insider.windows.com/">プレビューで使用できます</a>。  </li>
<li>  
 Windows 10 バージョン 2004 以降の Windows Insider 以外のお客様の場合、ARM64 Photoshop は OpenCL および OpenGL 互換パックを使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">してサポートされています</a>。 
  </li>
<li>  
  Windows Insider Program のお客様は、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換パックをダウンロードできます。    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Web アプリまたはサイトが Internet Explorer 11、サポートされているバージョンの Google Chrome、または任意のバージョンの Microsoft Edge で動作する場合は、Microsoft Edge でも動作します。  
  </li>
<li>  
  Web は常に進化していますので、Microsoft Edge の既知のサイト互換性に影響を与える変更の公開リストを <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">必ず確認してください</a>。  
  </li>
</ul>
  <strong>Windows 仮想デスクトップ </strong>  
<ul>
<li>  
  Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。  
  </li>
<li>  
  Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されているアプリは、Windows 仮想デスクトップの一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。  
  </li>
<li>  
  Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。  
  </li>
</ul>
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限は次のとおりです。
<ul>
<li>  
  ハードウェアのリダイレクトの制限。  
  </li>
<li>  
  音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。  
  </li>
<li>  
  64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の期待</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
リモート展開と導入に関するガイダンスと互換性に関するサポートは、次の場合に提供されます。 <ul> <li>Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager または Intune) を使用した Windows 10 での Microsoft Edge の展開。  </li>
<li>  Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリ構成とアプリ ポリシーを使用)。  </li>
<li>  このモードで使用する必要がある可能性があるサイトの一覧Internet Explorerします。  </li>
<li>  既存のエンタープライズ Internet Explorerリストを使用して、このモードを有効にします。 (詳細については、「Engaging <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack」を参照してください</a>)。 また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用し、互換性の問題が発生した場合は、追加費用を必要としない問題を解決するためのガイダンスを提供します。 App Assure の互換性サポートを要求するには <a href="https://fasttrack.microsoft.com/portal#/signin">、FastTrack</a> ポータルにサインインしてエンゲージメントを開始します。  </li>
<li> Microsoft Search ブックマークのエッジ導入と構成ガイダンスの計画ガイダンス。</li>
</ul>

<strong>以下はスコープ外です </strong>  
<ul>
<li>顧客の Microsoft Edge 配置のプロジェクトの管理。</li>
<li>  オンサイト サポート。</li>

</td>
<td></td>
</tr>
</tbody>
</table>
