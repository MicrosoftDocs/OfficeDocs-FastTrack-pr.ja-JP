---
title: 製品と機能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件をソース環境に提供します。
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016689"
---
# <a name="products-and-capabilities"></a>製品と機能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack でサポートされているサービスとシナリオ

このトピックでは、FastTrack でサポートされているワークロード シナリオと、開始する前に必要なソース環境の期待に関する詳細について説明します。 現在のセットアップに基づいて、お客様と一緒に修復計画を作成し、オンボーディングを成功するための最小要件をソース環境に提供します。

FastTrack では、最初にコア機能 (すべての Microsoft Online Services で共通) を使用し、次に対象となる各サービスのオンボーディングに役立つガイダンスを提供します。

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
<td>  コア オンボーディングに関するリモート ガイダンスを提供します。コア オンボーディングには、サービスのプロビジョニング、テナント、および ID の統合が含まれる必要があります。 また、セキュリティ、ネットワーク接続、コンプライアンスに関するディスカッションなど、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供するための手順も <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">含まれています</a>。  
  1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。
</li>
</ul>  

<strong> ID 統合 </strong>

以下に関するリモート ガイダンスを提供します。
<ul>
<li>Azure AD Connect (単一または複数フォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、Azure Active Directory (Azure AD) への同期のためのオンプレミスの Active Directory ID の準備。</li>
<li>グループベースのライセンスの使用を含む、一括インポートとライセンスを含むクラウド ID の作成。</li>
<li>クラウド移行、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (AD FS) を選択して有効にします。</li>
<li>単一AD Active Directory フォレストを持ち、AZURE AD Connect ツールと同期された ID を持つお客様に対して FS AD有効にします。 これには、R2 Active Directory Windows Server 2012 2.0 以上が必要です。</li>
<li>パスワード ハッシュ同期またはパススルー AD使用して、AD FS から Azure ADに認証を移行します。</li>
<li>シングル サインオン (SSO) のために、統合済みアプリ (Azure AD ギャラリーのサービスとしてのソフトウェア (SaaS) アプリなど) を AD FS から Azure AD に移行する。</li>
<li>Azure AD ギャラリーから SaaS アプリと SSO の統合を有効にします。</li>
<li>アプリ統合チュートリアルの一覧に示されている、統合済みの SaaS アプリの自動ユーザー プロビジョニングを有効にする <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">(Azure</a> AD ギャラリーの SaaS アプリと送信プロビジョニングのみ)。  </li>
</td>

<td>  <strong>ネットワークの有効化 </strong>  
  <br>FastTrack 特典の一環として、Microsoft 365 の最高レベルのパフォーマンスを保証するために、クラウド サービスに接続するためのベスト プラクティスについてお客様にアドバイスします。  
  
<strong>Active Directory フォレスト</strong> これらの機能フォレスト レベルは、次のフォレスト構成で Windows Server 2003 以降に設定されています。
<ul>
<li>  1 つの Active Directory フォレスト。  </li>
<li>  単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。  </li>
<li>  複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。  </li>
<li>  テナントの構成と Azure Active Directory との統合に必要なタスク (必要な場合)。   </li>
</ul>
  <strong>大事な</strong>  <ul>
<li>  複数フォレストの Active Directory シナリオでは、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。  </li>
<li>  複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange マルチハイブリッド構成に実装する場合、ソース フォレスト間の共有ユーザー プリンシパル名 (UPN) 名前空間はサポートされません。 Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。 詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。  </li>
<li>  複数フォレストのすべての構成では、Active Directory フェデレーション サービス (AD FS) の展開はスコープ外です。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 アプリ</strong></td>
<td>  次のリモート展開のガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。  </li>
<li>  iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  ローカルまたはクラウドのインストールの選択とセットアップ。  </li>
<li>  Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。  </li>
<li>  Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。  
  また、以前のバージョンの Office で動作するマクロやアドインを使用している場合に互換性の問題が発生した場合は、App Assure プログラムを通じて追加料金を使って互換性の問題を修復するガイダンスを提供します。 詳しくは <strong>、Windows</strong> <a href="#windows-10">10</a> の App Assure の部分をご覧ください。 </li>
</ul></td>
<td><ul>
<li>  オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Microsoft 365 のシステム要件で定義されている最小レベルOffice。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>ネットワークの正常性</strong></td>
<td>  Microsoft では、組織のサイトが Microsoft のネットワーク接続の原則とどのように一致するかを示す、環境から主要なネットワーク接続データを取得および解釈するリモート ガイダンスを <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">提供します</a>。 これにより、移行の速度、ユーザー エクスペリエンス、サービスのパフォーマンス、および信頼性に直接影響するネットワーク スコアが強調されます。  
  また、ネットワーク スコアの向上に役立つ、このデータによって強調表示されている修復手順について説明します。  </td>
<td><ul>
<li>  Microsoft 365 管理センターへのアクセス。  </li>
<li>  最新バージョンの Microsoft 365 アプリが必要です。  </li>
<li>  <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>管理センター (プレビュー) のネットワーク パフォーマンスに関する推奨事項に従って有効になっている位置情報サービス。  </li>
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
<td>  次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。  

 <br/>

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
<ul>
<li>  Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID の強力な認証の構成と有効化。  </li>
<li>  Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。  </li>
<li>  Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。  </li>
<li>  Azure AD Password Protection による脆弱なパスワードの使用の検出とブロック。  </li>
<li>  Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。  </li>
<li>  Azure Identity Protection によるリスクベースの検出と修復の有効化。  </li>
<li>  カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。  </li>
<li>  Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。  </li>
<li>  役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure ADの構成。  </li>
<li>  Azure ADの構成。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure ADの権利管理を使用して、Azure の ID とアクセス ライフサイクルAD管理します。
  </li>
<li>  
  Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。  
  </li>
<li>  
  Azure AD利用規約の確認。  
  </li>
<li>  
  Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。  
  </li>
</ul>
  
<strong>自動化と効率性 </strong>  
<ul>
<li>  
  Azure AD SSPR を有効にする。  
  </li>
<li>  ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。  </li>
<li>  Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。  </li>
<li>  動的グループAD Azure を有効にする。  </li>
<li>  コレクションを使用して、マイ アプリ ポータルでアプリを整理する。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD と Azure AD Premium 用に準備されています。</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  テナントのアクティブ化と構成。  </li>
<li>  ラベルおよびポリシーの作成と設定。  </li>
<li>  ドキュメントへの情報保護の適用。  </li>
<li>  Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。  </li>
<li>  Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>
Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。  </td>
<td>  お客様の前提条件となる責任は次のとおりです。
<ul>
<li>  スキャンするファイル共有の場所の一覧。  </li>
<li>  承認された分類。 </li>
<li> キー管理に関する規制上の制限または要件を理解する。  </li>
<li>  Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。 </li>
<li>  分類と保護用に構成されたラベル。 </li>
<li> Azure Information Protection スキャナーのすべての前提条件が満たされています。 詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。 </li>
<li>  ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。 詳細については、以下を参照してください。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </li>
</ul>
<li> ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。  </li>
<li> 展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender は、高度な攻撃に対する統合された保護を提供するために、エンドポイント、ID、電子メール、アプリ間で検出、防止、調査、応答をネイティブに調整する統合された侵害前および侵害後のエンタープライズ防御スイートです。 以下に関するリモート ガイダンスを提供します。 </p> 
<ul>
<li>  Microsoft 365 セキュリティ センターの概要について説明します。  </li>
<li>  完全な攻撃範囲、影響を受けた資産、およびグループ化された自動修復アクションを確実にすることで、重要な問題に焦点を当てるなど、製品間のインシデントを確認します。  </li>
<li>  Microsoft 365 Defender が、自動自己修復によって侵害された可能性がある資産、ユーザー、デバイス、メールボックスの調査を調整する方法を示します。 </li>
<li>  複数のデータ セット間で電子メール、データ、デバイス、アカウントに影響を与える侵入の試みと侵害アクティビティを顧客が積極的に探す方法の例を説明し、提供します。   </li>
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
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security は、豊富な可視性、データ移動の制御、および高度な分析を提供するクラウド アクセス セキュリティ ブローカー (CASB) であり、すべての Microsoft およびサード パーティのクラウド サービスでサイバー脅威を特定して対処します。 以下に関するリモート ガイダンスを提供します。
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
<li> アプリ コネクタ <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">を使った</a> おすすめアプリの接続。</li>
<li> 条件付きアクセス ポータルと Cloud App Security ポータルで条件付きアクセス アプリ制御を設定して、リアルタイム セッション コントロールを適用します。</li>
<li> Cloud App Security および Cloud Discovery ダッシュボードの展開。</li>
<li> 組織の優先順位に基づいてアプリのリスク スコアをカスタマイズする。</li>
<li> アプリ タグとカテゴリの作成。</li>
<li> アプリの許可と削除。</li>
<li> アクティビティとファイル ログの使用。</li>
<li> OAuth アプリの管理。</li>
<li> Microsoft 365 Defender ポータルでのインシデントの相関関係について説明します。</li>
<li> 以下を除き、CASB の上位 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 個の使用事例 (最大 6 個のポリシーの作成または更新を含む) の構成支援を提供します。 </li>
<ul>
<li> サービスとしてのインターネット (IaaS) 環境 (#18)。</li>
<li> ユーザーアクティビティを監視して、IaaS 環境内の脅威から保護する (#19)。</li>
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
<li> 概念実証としての Cloud App Discovery の展開。</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティで保護するテクノロジの展開。  </li>
<li>  エンドポイント保護とデバイス制限プロファイルの構成。  </li>
<li>  OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサード パーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。  </li>
<li>  展開のガイダンス、構成の支援、および次の教育について説明します。
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
  Configuration Manager のダウンレベルのインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。  
  </li>
<li>  
  Azure セキュリティ センターへのサーバーのオンボーディング。  
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
<li>   ドメイン コントローラーに Defender for Identity センサーを展開するための環境の準備状況を評価します。次が含されます。</li>   
<ul> 
<li>  リソース容量計画用のサイズ変更ツールの実行。 </li>
<li>  監査ツールを実行して、ドメイン コントローラーとセンサーとの互換性を評価します。 </li>
</ul>
<li>  ネットワーク トラフィックと Windows イベントをドメイン コントローラーから直接キャプチャして解析するセンサーの展開。次の機能が含されます。 </li>
<ul> 
<li>  センサー パッケージのダウンロード。 </li>
<li>  センサーの構成。 </li>
<li>  ドメイン コントローラーにサイレント モードでセンサーをインストールします。 </li>
<li>  複数フォレスト環境へのセンサーの展開。 </li>
</ul>
<li>  Id 用 Defender を Microsoft Cloud App Security と統合する (Cloud App Security のライセンスは必要ありません)。 </li>
<li>  展開ガイダンス、構成支援、および以下の教育を提供します。 </li>
<ul>
<li> "ノイズ" を低減するために環境を調整します。  </li>
<li>  ID セキュリティの状況評価レポートについて。 </li>
<li>  ユーザーの調査の優先度スコアとユーザーの調査ランク付けレポートについて。 </li>
<li> 非アクティブなユーザー レポートについて。  </li>
<li> 侵害されたアカウントでの修復オプションの提供。  </li>
</ul>
<li>  Advanced Threat Analytics (ATA) から Id 用 Defender への移行を容易にする。 </li>
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
<li> Id 用 Defender のセキュリティ警告ラボチュートリアルを提供します。 </li>
<li> 指定されたセンサーを介してセキュリティ警告をサーバーに送信することで、Defender for Identity が疑わしいアクティビティを検出した場合の通知を提供します。  </li>
<li> セキュリティ アカウント マネージャー リモート (SAMR) プロトコルを使用してクエリを実行し、特定のコンピューター上のローカル管理者を識別するための ID 用 Defender の構成。 </li>
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
<li>  Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  組織に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、VPN プロファイルの展開。  </li>
<li>  Intune データ ウェアハウスへの接続。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。  </li>
<li>  Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。  </li>
<li>  通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。  </li>

</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  次に関するアプリ保護ガイダンスを提供します。
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理対象アプリの条件付きアクセス ポリシーの構成。  </li>
<li>  前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。  </li>
<li>  管理対象アプリの利用状況レポートの使用。  </li>
</ul></li>
<li>  従来の PC 管理から Intune MDM への移行ガイダンスを提供します。  </li>
</ul>
 
</li>
</ul>
  
<strong>クラウド接続</strong>  

  Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。  </li>
<li>  MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。  </li>
<li>  リモート インターネット ベースのデバイス管理の共同管理ソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。  
  Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。 次のものが含まれます。
<ul>
<li>  Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。  </li>
<li>  セットアップに関するガイダンスを提供します。
<ul>
<li>  iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  アプリ構成ポリシー。  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを実稼働環境で既に動作している必要があります。  
  <strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。  
 
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。 購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。  
  
</td>
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

## <a name="office-365"></a>Office 365

<<table>
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
<td>  Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。 正確な手順は、ソース環境とメール移行プランによって異なります。  
  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。  </li>
<li>  メール交換 (MX) レコードの参照を 365 Officeする。  </li>
<li>  サブスクリプション サービスOffice 365 ATP 機能のセットアップ。 詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> を参照してください。  </li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
</ul>
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、Information Rights Managed (IRM) 電子メールをオンプレミスのメールボックスから対応する Exchange Online メールボックスに移行します。 移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。  
<ul>
<li>  ファイアウォール ポートの構成。  </li>
<li>  必要な自動検出、送信者ポリシー フレームワーク (SPF)、DomainKeys Identified Mail (DKIM)、ドメイン ベースのメッセージ認証、レポートと適合 (DMARC) および MX レコード (必要に応じて) を含む DNS のセットアップ。  </li>
<li>  ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。  </li>
<li>  ソースのメッセージング環境から Office 365 にメール移行を実行。  </li>
<li>  メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。   
<td>  ソース環境には、次のいずれかの最小レベルが必要です。
<ul>
<li>  Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。  </li>
<li>  1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。  </li>
<li>  単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。  </li>
<li>  複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、「Exchange Online の複数地域</a>機能」を参照してください。  </li>
</ul>
Project for Office 365、Outlook for Windows、iOS および Android 用の Outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 Office</a>のシステム要件で定義されている最小レベルである必要があります。  </td>
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
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Teams をサポートするために Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD要件を確認します。  </li>
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
<li>  Teams アプリ ポリシー (Teams Web アプリ、Teams デスクトップ アプリ、および iOS および Android 用 Teams アプリ) の構成。  </li>
</ul>
該当する場合は、以下のガイダンスも提供します。
<ul>
<li>  Microsoft Teams Room Devices:  </li>
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
<li>  通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能な市場</a>):
<ul>
<li>  ライセンスを持つユーザーへの番号の割り当て。  </li>
<li>  ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。  </li>
<li>  999 件を超える電話番号の移植サービス リクエスト (SR) サポート。  </li>
</ul></li>
<li>  ダイレクト ルーティングのガイダンス:
<ul>
<li>  パートナーホスト型シナリオのダイレクト ルーティング設計、または最大 10 サイトの顧客展開シナリオに関する組織のセットアップ ガイダンス。  </li>
<li> セッション ボーダー コントローラー (SBC) 構成レビュー。 </li>

<li> ダイヤル プラン構成に関するリモート アシスタンス。 </li>

<li> ボイス ルート構成。</li>

<li> メディア バイパスとローカル メディアの最適化。 </li>

</ul></li>
</ul></li>
<li>  Teams ライブ イベントの有効化。  </li>
<li>  組織のセットアップと Microsoft Stream への統合。  </li>
<li>  Skype for Business から Teams への移行に関するガイダンス。  </li>
</ul></td>
<td><ul>
<li>  Azure AD 365 で有効Office ID。  </li>
<li>  SharePoint Online に対してユーザーが有効になっている。  </li>
<li>  Exchange メールボックスが存在する (Exchange ハイブリッド構成ではオンラインとオンプレミス)。  </li>
<li>  Office 365 グループに対して有効になっている。  </li>
</ul>
  <strong>注:</strong> ユーザーが SharePoint Online ライセンスに割り当てられていない場合、ユーザーは OneDrive for Business ストレージを 365 Officeしません。 ファイル共有はチャネルで引き続き機能しますが、ユーザーは OneDrive for Business ストレージを使用せずにチャット内のファイルを Office 365 で共有できます。 Teams はオンプレミスの SharePoint をサポートしています。  <br>
  <strong>注:</strong> 理想的な状態は、すべてのユーザーが自分のメールボックスを Exchange Online にホームに設定する状態です。 オンプレミスにホームのメールボックスを持つユーザーの ID は、Azure Office Connect を介して Office 365 ディレクトリに同期ADがあります。 これらの Exchange ハイブリッドのお客様の場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成できません。  
  Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> からダウンロードできます。  </td>
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
<tr class="even">
<td><strong>iOS 版および Android 版 Outlook</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。  </li>
<li>  アカウントの構成、および Exchange Online メールボックスへのアクセス。  </li>
<li>  Outlook モバイルのセキュリティ保護 ( <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">詳細については、「Exchange Online</a> での iOS および Android 用の Outlook のセキュリティ保護」を参照してください)。  </li>
</ul></td>
<td><ul>
<li>  Azure AD 365 で有効Office ID。  </li>
<li>  Exchange Online が構成され、ライセンスが割り当てられている。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Power BI ライセンスの割り当て。  </li>
<li>  Power BI Desktop アプリの展開。  </li>
</ul></td>
<td>Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Project Online が依存している基本的な SharePoint の機能の確認。  </li>
<li>  テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。  </li>
<li>  エンタープライズ リソース共有元 (ERP) のセットアップ。  </li>
<li>  最初のプロジェクトの作成。  </li>
</ul></td>
<td>Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional および Premium</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。  </li>
<li>  Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。  </li>
</ul></td>
<td>Project for Office 365 などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365</a>および Office のシステム要件で定義されている最小レベルである必要があります。</td>
</tr>
<tr class="even">
<td><strong>Sharepoint Online と OneDrive for Business</strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
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
OneDrive for Business の追加のガイダンスは、SharePoint のバージョンに応じて提供されます。次に例を示します。
<ul>
<li>  統合オプションを特定し、オンプレミスとオンラインのネットワーク インフラストラクチャと帯域幅を確認します。  </li>
<li>  SharePoint Online 2013 SP1 (該当する場合) のインストール、同期と ID の要件の計画と実装、OneDrive for Business 同期クライアントの識別。  </li>
<li>  すべてのユーザーに対する単一のロールアウト (または段階的なロールアウト) の計画と実装。  </li>
<li>  ライセンスの割り当て、個人用サイトと個人用ドキュメント ライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に適用) を行い、対象ユーザーを設定して OneDrive へのアクセスを制御します (SharePoint Online 2013 に適用)。  </li>
<li>OneDrive への既知のフォルダーのリダイレクトまたは移動。</li>
<li>  OneDrive for Business クライアント同期の展開。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に FastTrack 特典を使用する方法については、「データ移行」 <a href="https://docs.microsoft.com/fasttrack/data-migration">を参照してください</a>。
</ul></td>
<td><br><strong>SharePoint ハイブリッドの場合:</strong>  
<ul>
<li>  SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービス サイト作成の構成が含まれます。  </li>
</ul>
  <strong>注:</strong> セルフサービス サイト作成は、SharePoint 2013 を実行するオンプレミス サーバーのスコープではありません。  
<ul>
<li>  SharePoint ハイブリッドを有効にするには、2013、2016、または 2019 のいずれかのオンプレミスの SharePoint Server 環境が必要です。  </li>
</ul>
  <strong>注:</strong> オンプレミスの SharePoint 環境から SharePoint Server へのアップグレードの対象ではありません。 Microsoft パートナー <a href="https://go.microsoft.com/fwlink/?linkid=2080150">にお問い合</a> わせください。 詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、「SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベル」を参照してください</a><em>。</em>  <br>
  <strong>注:</strong>複数地域機能の詳細については、「OneDrive の複数地域機能」および「Office <a href="https://go.microsoft.com/fwlink/?linkid=831056">365 の SharePoint Online」</a>を参照してください<em>。</em>  </td>
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
<td>  次のシナリオでクラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。  

 <br/>

<strong>セキュリティで保護された基盤インフラストラクチャ</strong>  </ul>
<ul>
<li>  Azure Multi-Factor Authentication (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録など、ID の強力な認証の構成と有効化。  </li>
<li>  Azure 以外の AD Premium のお客様には、セキュリティの既定値を使用して ID を保護するためのガイダンスが提供されます。  </li>
<li>  Azure およびADのお客様向けには、条件付きアクセスを使用して ID を保護するためのガイダンスが提供されています。  </li>
<li>  Azure AD Password Protection による脆弱なパスワードの使用の検出とブロック。  </li>
<li>  Azure AD アプリケーション プロキシを使用して、オンプレミスの Web アプリへのリモート アクセスをセキュリティで保護します。  </li>
<li>  Azure Identity Protection によるリスクベースの検出と修復の有効化。  </li>
<li>  カスタム ブランド化を使用して、ロゴ、テキスト、画像などのカスタマイズされたサインイン画面を有効にする。  </li>
<li>  Azure AD B2B を使用して、ゲスト ユーザーとアプリとサービスを安全に共有します。  </li>
<li>  役割ベースのアクセス制御 (RBAC) に組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権を持つ管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure ADの構成。  </li>
<li>  Azure ADの構成。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure AD Connect Health を使用AD FS、Azure AD Connect、ドメイン コントローラーのリモート監視AD有効にする。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure ADの権利管理を使用して、Azure の ID とアクセス ライフサイクルAD管理します。
  </li>
<li>  
  Azure ADメンバーシップ、エンタープライズ アプリ アクセス、ロールの割り当てを Azure で管理し、アクセス AD確認できます。  
  </li>
<li>  
  Azure AD利用規約の確認。  
  </li>
<li>  
  Azure AD Privileged Identity Management を使用して、特権管理者アカウントへのアクセスを管理および制御します。  
  </li>
</ul>
  
<strong>自動化と効率性 </strong>  
<ul>
<li>  
  Azure AD SSPR を有効にする。  
  </li>
<li>  ユーザーが独自のクラウド セキュリティを作成して管理したり、Azure Office 365 グループを使用して 365 ADグループを作成および管理したりすることを許可します。  </li>
<li>  Azure および委任されたグループ管理を使用して、エンタープライズ ADアクセスを管理します。  </li>
<li>  動的グループAD Azure を有効にする。  </li>
<li>  コレクションを使用して、マイ アプリ ポータルでアプリを整理する。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は、Azure AD Premium の機能との統合を妨げる特定の問題の修復を含め、Azure AD と Azure AD Premium 用に準備されています。</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  テナントのアクティブ化と構成。  </li>
<li>  ラベルおよびポリシーの作成と設定。  </li>
<li>  ドキュメントへの情報保護の適用。  </li>
<li>  Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。  </li>
<li>  Azure Information Protection スキャナーを使用して、保存中のファイルの検出とラベル付け。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>
Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用する場合もガイダンスを提供します。  </td>
<td>  お客様の前提条件となる責任は次のとおりです。
<ul>
<li>  スキャンするファイル共有の場所の一覧。  </li>
<li>  承認された分類。 </li>
<li> キー管理に関する規制上の制限または要件を理解する。  </li>
<li>  Azure Active Directory と同期されたオンプレミスの Active Directory 用に作成されたサービス AD。 </li>
<li>  分類と保護用に構成されたラベル。 </li>
<li> Azure Information Protection スキャナーのすべての前提条件が満たされています。 詳細については、「Azure Information Protection 統合ラベル付けスキャナーをインストールおよび展開するための前提条件 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">」を参照してください</a>。 </li>
<li>  ユーザー デバイスでサポートされているオペレーティング システムが実行され、必要な前提条件がインストールされていることを確認します。 詳細については、以下を参照してください。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理ガイド: ユーザー向け Azure Information Protection 統合ラベル付けクライアントをインストールする</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS または Android 用の Azure Information Protection アプリとは</a>  </li>
</ul>
<li> ハイブリッド サポート用の Active Directory RMS (AD RMS) コネクタを含む Azure RMS コネクタとサーバーのインストールと構成。  </li>
<li> 展開でこれらのオプションのいずれかを必要とする場合は、Bring Your Own Key (BYOK)、Double Key Encryption (DKE) (統合ラベル付けクライアントのみ)、または Hold Your Own Key (HYOK) (従来のクライアントのみ) のセットアップと構成を行います。  </li>
  </ul>
</ul>
  
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
<li>  Web リンクまたはディープ リンクを介した、サポートされている各プラットフォームのアプリの展開。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  組織に既存の証明機関、ワイヤレス ネットワーク、または VPN インフラストラクチャがある場合の電子メール、ワイヤレス ネットワーク、VPN プロファイルの展開。  </li>
<li>  Intune データ ウェアハウスへの接続。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモート アシスタンス用のチーム ビューアー (チーム ビューアーのサブスクリプションが必要です)。  </li>
<li>  Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要)。  </li>
<li>  通信経費管理ソリューション (通信経費管理ソリューションのサブスクリプションが必要です)。  </li>
</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  次に関するアプリ保護ガイダンスを提供します。
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理対象アプリの条件付きアクセス ポリシーの構成。  </li>
<li>  前述の MAM ポリシーを使用して適切なユーザー グループをターゲットに設定する。  </li>
<li>  管理対象アプリの利用状況レポートの使用。  </li>
</ul></li>
<li>  従来の PC 管理から Intune MDM への移行ガイダンスを提供します。  </li>
</ul>
  
</li>
</ul>
  
<strong>クラウド接続</strong>  

  Intune を使用して既存の Configuration Manager 環境をクラウドで接続する準備について説明します。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  ハイブリッド Azure アプリケーションのセットアップに関するガイダンスADします。  </li>
<li>  MDM 自動登録用の Azure ADセットアップに関するガイダンスを提供します。  </li>
<li>  リモート インターネット ベースのデバイス管理の共同管理ソリューションとして使用する場合のクラウド管理ゲートウェイのセットアップ方法に関するガイダンスを提供します。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織内に安全に展開し、ユーザーに必要なすべてのアプリがインストールされていることを確認するためのガイダンスを提供します。  
  Intune を使用して iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。 次のものが含まれます。
<ul>
<li>  Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリをダウンロードする。  </li>
<li>  セットアップに関するガイダンスを提供します。
<ul>
<li>  iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータル サイト アプリの Intune での展開。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  アプリ構成ポリシー。  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 管理者は、Intune でのワイヤレス ネットワークと VPN プロファイルの展開を計画する際に、既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを実稼働環境で既に動作している必要があります。  
  <strong>注</strong>: FastTrack サービス特典には、Intune の証明書機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書の設定または構成のサポートは含されません。  
 
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: Intune と Microsoft Defender ATP の統合、および Windows 10 のリスク レベル評価に基づくデバイス コンプライアンス ポリシーの作成に関するサポートを提供します。 購入、ライセンス、またはライセンス認証に関するサポートは提供一部行われかねない。 サポートについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  
  
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
<td>  Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに関するガイダンスを提供します。  
  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  Windows 10 の目的を理解する。  </li>
<li>  ソース環境と要件を評価します (Windows 10 の展開をサポートするために、Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードしていることを確認してください)。  </li>
<li>  Microsoft Endpoint Configuration Manager または Microsoft 365 を使用した Windows 10 Enterprise および Microsoft 365 アプリの展開。  </li>
<li>  Windows 10 アプリを評価するための推奨オプション。  </li>
<li>  Desktop Analytics 展開計画の作成による Desktop Analytics とガイダンスの使用の有効化。  </li>
<li>  Configuration Manager の Office 365 準備ダッシュボード、またはスタンドアロンの Toolkit for Office を活用した Microsoft 365 アプリの互換性評価と、Microsoft 365 アプリの展開のサポート。  </li>
<li>  展開を成功するためにソース環境を最小要件に満たするために行う必要がある操作に関する修復チェックリストを作成します。  </li>
<li>  必要なデバイス ハードウェア要件を満たす場合は、既存のデバイスの Windows 10 Enterprise へのアップグレード ガイダンスを提供します。  </li>
<li>  既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。  </li>
<li>  Windows 10 の展開の一部として Configuration Manager を使用した Microsoft 365 アプリの展開。   </li>
<li>  既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 Apps を最新の情報に更新するためのガイダンスを提供します。  </li>
</ul>
  <strong>次に示すのはスコープ外です </strong>  
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
これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  </td>
<td>  PC のアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  ソース OS: Windows 7 Enterprise Professional、Windows 8.1 Enterprise または Professional。  </li>
<li>  デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。  </li>
<li>  ターゲット OS: Window 10 Enterprise。  </li>
</ul>
インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  Microsoft Endpoint Configuration Manager。  </li>
<li>  Configuration Manager のバージョンは、Windows 10 ターゲット バージョンでサポートされている必要があります。 詳細については、「<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager での Windows 10 のサポート</a>」で Configuration Manager のサポート テーブルを参照してください。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  以下に関するリモート ガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティで保護するテクノロジの展開。  </li>
<li>  エンドポイント保護とデバイス制限プロファイルの構成。  </li>
<li>  OS のバージョンとデバイスの管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、およびサード パーティの構成を含む) と、Windows Defender AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  Windows AV サービスまたは他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にする。  </li>
<li>  展開のガイダンス、構成の支援、および次の教育について説明します。
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
  Configuration Manager のダウンレベルのインスタンスとバージョンでの Configuration Manager 展開パッケージの構成。  
  </li>
<li>  
  Azure セキュリティ センターへのサーバーのオンボーディング。  
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
<td><p>Windows Virtual Desktop (デスクトップとアプリの仮想化サービス) へのオンボーディングに関する展開ガイダンスを提供します。 Windows Virtual Desktop は、Windows 10 マルチセッション エクスペリエンスを利用し、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化されています。</p>
<p>以下に関するリモート ガイダンスを提供します。</p>
<ul>
<li>以下を使用して、Windows 10 Enterprise マルチセッションと Microsoft 365 Apps for Enterprise を使用して Windows Virtual Desktop 環境を展開します。
<ul>
<li>Azure Marketplace イメージ。</li>
<li>共有イメージ。</li>
<li>Office展開Toolkit (ODT)。</li>
</ul></li>
<li>FSLogix の構成:
<ul>
<li>プロファイル コンテナーを使用した FSLogix エージェントの展開。</li>
<li>新しいコンテナーを使用した FSLogix エージェントOffice展開します。</li>
<li>コンテンツの除外を使用した FSLogix フォルダーの構成。</li>
</ul></li>
<li>Microsoft Edge の展開。</li>
<li>Microsoft Teams の展開。</li>
<li>Windows Virtual Desktop クライアントを使用した接続。</li>
</ul>

<strong>次に示すのはスコープ外です</strong>
<ul>
<li>お客様の Windows Virtual Desktop 展開のプロジェクト管理。</li>
<li>サード パーティ製アプリの仮想化と展開。</li>
<li>カスタム画像。</li>
<li>VMware と Citrix が関係する移行とシナリオ。</li>
<li>Linux シナリオ。</li>
<li>ユーザー プロファイルの変換または移行。</li>
</ul>
これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。</td>
<td>次の情報が既に存在する必要があります。
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop のライセンス要件</a>。</li>
<li>Azure ネットワーク:
<ul>
<li>仮想ネットワーク (VNET) の作成とサブネット化。</li>
<li>ファイアウォールとネットワーク セキュリティ グループ。</li>
<li>VPN と ExpressRoute。</li>
<li>オンプレミスから Azure へのルーティング。</li>
<li>Windows Virtual Desktop への接続を許可するファイアウォール規則。
</ul>
詳細については、「サポートされるリモート デスクトップ <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> クライアント」を参照してください</a>。
</ul>
<ul><li>Azure AD一般的なセットアップ:
<ul>
<li>ID 戦略 <i>(次の 3 つのオプションのいずれかを使用できます)。</i>
<ul>
<li>Azure を使用した Active Directory AD Azure の Connect。</li>
<li>Azure を使用した Active Directory AD VPN または ExpressRoute を使用してオンプレミスに接続します。</li>
<li>Active Directory ドメイン サービス (AD DS)。</li>
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
<td>  App Assure は、Windows 10 と Microsoft 365 Apps アプリの互換性に関する問題に対処するために設計されたサービスです。 App Assure サービスをリクエストすると、有効なアプリの問題に対して、対象となるサブスクリプションを使用して追加料金を支払う必要はありません。 また、Windows Virtual Desktop と Microsoft Edge を展開する際に互換性の問題に直面しているお客様にガイダンスを提供し、互換性の問題を解決するためにあらゆる妥当な努力を行います。 Microsoft では、次の Microsoft 製品に展開されているアプリの修復支援を提供します。
<ul>
<li>  <strong>Windows 10 </strong> (ARM64 デバイスを含む)</li>
<li> <strong>Microsoft 365 アプリ</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> 展開のガイダンスについては <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">、「Microsoft Edge チャネルの概要」を参照してください</a>。  </li>
<li>  <strong>Windows Virtual Desktop</strong> - 詳しくは <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">、「Windows Virtual Desktop とは</a> 」と Windows 10 Enterprise マルチセッションの FAQ <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">をご覧ください</a>。  </li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
<ul>
<li>  アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。 このプロセスのガイダンスについては、<a href="https://go.microsoft.com/fwlink/?linkid=2080140">デスクトップ展開センター</a> を参照してください。 詳細なアップグレードの準備状況の評価に興味がある場合、<a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> のフォームを完了してください。</li>
<li>  サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。 詳細については、「<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics とは</a>」を参照してください。</li>
<li>アプリのパッケージ化専用サービス。 ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。</li>
</ul>

<strong>お客様の責任は次のとおりです。</strong>  
<ul>
<li>  アプリ インベントリの作成。</li>
<li>  Windows 10 および Microsoft 365 アプリでの当該アプリの検証。</li>
</ul>
<strong>注:</strong>  Microsoft はソース コードを変更できない。 ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。 


  これらのサービスについては <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  </td>

</td>
<td><strong>Windows 10 と Microsoft 365 アプリ</strong>
<ul>
<li>  
  Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。  
  </li>
</ul>
<strong>Windows 10 on ARM</strong>
<ul>
<li>  
Windows 7、Office 2010 以降のバージョンで動作したアプリは、ARM64 デバイス上の Windows 10 および Microsoft 365 アプリでも動作します。 
  </li>
</ul>
  <strong>注:</strong> 
<ul>
<li> x64 (64 ビット) エミュレーションは、Windows Insider Program に参加しているお客様がプレビュー <a href="https://insider.windows.com/">で利用できます</a>。  </li>
<li>  
 Windows 10 バージョン 2004 (以降) の Windows Insider 以外のお客様は <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">、OpenCL</a>および OpenGL 互換機能パックを使って ARM64 Photoshop がサポートされています。 
  </li>
<li>  
  Windows Insider Program のユーザーは、追加のアプリで使用するために、Insider バージョンの OpenCL および OpenGL 互換機能パックをダウンロードできます。    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Web アプリまたはサイトが Internet Explorer 11、Google Chrome のサポートされているバージョン、または Microsoft Edge の任意のバージョンで動作する場合は、Microsoft Edge でも動作します。  
  </li>
<li>  
  Web は常に進化し続けるので <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">、Microsoft Edge</a>のサイト互換性に影響を与える既知の変更の公開リストを必ず確認してください。  
  </li>
</ul>
  <strong>Windows Virtual Desktop </strong>  
<ul>
<li>  
  Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。  
  </li>
<li>  
  Windows 7 または Windows 10 仮想デスクトップ インフラストラクチャ (VDI) 環境で実行されるアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise と Windows 10 Enterprise でも実行されます。  
  </li>
<li>  
  Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。  
  </li>
</ul>
  <strong>注:</strong> Windows 10 Enterprise のマルチセッション互換性の除外と制限事項は次のとおりです。
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
<td><strong>Microsoft Edge</strong> (Windows 10 Enterprise のお客様向け)</td>
<td><ul>
<li>  Microsoft エンドポイント マネージャー (Microsoft Endpoint Configuration Manager または Intune) を使用して Windows 10 Enterprise に Microsoft Edge を展開する場合のリモート展開ガイダンスと互換性のサポートを提供します。  </li>
<li>  Microsoft Edge の構成 (グループ ポリシーまたは Intune アプリの構成とアプリ ポリシーを使用)。  </li>
<li>  このモードで使用する必要がある可能性があるサイトの一Internet Explorerします。  </li>
<li>  既存のInternet Explorerリストを使用してユーザー 設定モードを有効にする。  
  また、Internet Explorer または Google Chrome で動作する Web アプリまたはサイトを使用している場合に互換性の問題が発生した場合は、追加費用を必要としない方法で問題を解決するためのガイダンスを提供します。 詳しくは <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">、「App Assure」</a> をご覧ください。  </li>
</ul>

<strong>次に示すのはスコープ外です </strong>  
<ul>
<li>顧客の Microsoft Edge 配置のプロジェクトの管理。</li>
<li>  オンサイト サポート。</li>

</td>
<td></td>
</tr>
</tbody>
</table>
