---
title: 製品と機能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。 現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800969"
---
# <a name="products-and-capabilities"></a>製品と機能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack でサポートされているサービスとシナリオ

このトピックには、FastTrack でサポートされているワークロードシナリオの詳細と、開始する前に必要なソース環境の要件が記載されています。 現在の設定に基づいて、お客様と協力して、ソース環境を正常にオンボードにするための最小要件を実現する修復計画を作成します。

FastTrack は、最初にコア機能 (すべての Microsoft Online サービスに共通) を提供し、次に各対象サービスをオンボードにするためのガイダンスを提供します。

  - [全般](#general)
  - [Office 365](#office-365)
  - [エンタープライズモビリティ & のセキュリティ](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [App Assure](Win-10-app-assure.md)
  - [新しい Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> Office 365 US Government のソース環境の要件の詳細については、「 [office 365 Us government のソース環境の要件](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)」を参照してください。
 
## <a name="general"></a>全般

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>コア オンボーディング</strong></td>
<td>  コアオンボードに関するリモートガイダンスを提供します。これには、サービスのプロビジョニング、テナント、およびアイデンティティ統合が含まれます。 また、Exchange Online、SharePoint Online、Microsoft Teams などのオンボードサービスの基礎を提供するための手順についても説明します。これには、 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">セキュリティ、ネットワーク接続、コンプライアンスに関する説明</a>が含まれます。  
  1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。
</li>
</ul>  

<strong> Id 統合 </strong>

次のためのリモートガイダンスを提供します。
<ul>
<li>Azure AD Connect (単一または複数のフォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含む、azure Active Directory (Azure AD) への同期用にオンプレミスの Active Directory Id を準備します。</li>
<li>グループベースのライセンスを使用することを含め、一括インポートおよびライセンスを含むクラウド id を作成します。</li>
<li>クラウドへの移行、パスワードハッシュ同期、パススルー認証、または Active Directory フェデレーションサービス (AD FS) に対して適切な認証方法を選択して有効にします。</li>
<li>単一の Active Directory フォレストを持つお客様に対して AD FS を有効にし、id を Azure AD Connect ツールと同期させます。 これには、Windows Server 2012 R2 Active Directory フェデレーションサービス2.0 またはそれ以上が必要です。</li>
<li>パスワードハッシュ同期またはパススルー認証を使用して、AD FS から Azure AD に認証を移行します。</li>
<li>シングルサインオン (SSO) に対して、事前に統合されたアプリ (Azure AD gallery software-a service (SaaS) アプリなど) を AD FS から Azure AD に移行します。</li>
<li>Azure AD gallery から SSO を使用した SaaS アプリの統合を有効にします。</li>
<li><a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">アプリ統合チュートリアルリスト</a>に記載されているように、事前に統合された SaaS アプリの自動ユーザープロビジョニングを有効にします (Azure AD gallery SaaS アプリと送信プロビジョニングのみに限定)。  </li>
</td>

<td>  <strong>ネットワークの有効化 </strong>  
  <br>FastTrack の特典の一環として、クラウドサービスに接続して Microsoft 365 の最高レベルのパフォーマンスを確保するためのベストプラクティスについてお勧めします。  
  
<strong>Active Directory フォレスト</strong> これらのフォレストの機能は、機能フォレストレベルが Windows Server 2003 以降に設定されており、フォレスト構成は次のとおりです。
<ul>
<li>  1 つの Active Directory フォレスト。  </li>
<li>  単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。  </li>
<li>  複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。  </li>
<li>  必要に応じて、テナントの構成と Azure Active Directory との統合に必要なタスク。   </li>
</ul>
  <strong>大事な：</strong>  <ul>
<li>  複数フォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開されている場合は、Exchange と同じ Active Directory フォレストに展開する必要があります。  </li>
<li>  複数の Exchange 組織を持つ複数の Active Directory フォレストを Exchange 多重ハイブリッド構成で実装する場合、ソースフォレスト間で共有されるユーザープリンシパル名 (UPN) の名前空間はサポートされません。 Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。 詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。  </li>
<li>  すべての複数フォレスト構成では、Active Directory フェデレーションサービス (AD FS) の展開がスコープ外になります。 この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 アプリ</strong></td>
<td>  次のためのリモート展開ガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。  </li>
<li>  iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  ローカルまたはクラウドのインストールの選択とセットアップ。  </li>
<li>  Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。  </li>
<li>  Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。  
  また、以前のバージョンの Office で作業したマクロまたはアドインがあり、互換性の問題が発生した場合は、アプリの保証プログラムを通じて追加費用なしで互換性の問題を修復するためのガイダンスを提供します。 詳細については、「 <strong>アプリ</strong> で <a href="#windows-10">Windows 10</a> の一部を確認する」を参照してください。 </li>
</ul></td>
<td><ul>
<li>  オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>ネットワークの正常性</strong></td>
<td>  組織のサイトが Microsoft の <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ネットワーク接続の原則</a>とどのように連携しているかを示す、環境からの主要なネットワーク接続データの取得と解釈に関するリモートガイダンスを提供します。 これにより、移行速度、ユーザー環境、サービスのパフォーマンス、および信頼性に直接影響するネットワークスコアが強調されます。  
  また、このデータで強調表示されている修復手順についても説明し、ネットワークのスコアを向上します。  </td>
<td><ul>
<li>  Microsoft 365 管理センターへのアクセス。  </li>
<li>  Microsoft 365 アプリの最新バージョンが必要です。  </li>
<li>  <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 管理センター (プレビュー) でのネットワークパフォーマンスに関する推奨事項</a>として有効になる場所サービス。  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。 正確な手順は、ソース環境と電子メール移行プランによって異なります。  
  次のためのリモートガイダンスを提供します。
<ul>
<li>  Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。  </li>
<li>  メール交換 (MX) レコードを Office 365 に接続します。  </li>
<li>  サブスクリプションサービスの一部である場合は、Office 365 ATP 機能をセットアップします。 詳細については、この表の「 <strong>Office 365 Advanced Threat Protection</strong> 」の部分を参照してください。  </li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
</ul>
  <strong>注:</strong> メールボックスレプリケーションサービス (MR) は、社内メールボックスから対応する Exchange Online メールボックスに Information Rights Managed (IRM) メールを移行しようとします。 移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。  
<ul>
<li>  ファイアウォール ポートの構成。  </li>
<li>  DNS のセットアップ。必須の自動検出、sender policy framework (SPF)、DomainKeys 識別メール (DKIM)、ドメインベースのメッセージ認証、レポートと準拠 (DMARC)、および MX レコード (必要な場合) を含みます。  </li>
<li>  ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。  </li>
<li>  ソースのメッセージング環境から Office 365 にメール移行を実行。  </li>
<li>  メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。   
<td>  ソース環境には、次の最低レベルのいずれかが必要です。
<ul>
<li>  Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。  </li>
<li>  1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。  </li>
<li>  単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。  </li>
<li>  複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online の複数地域機能</a>」を参照してください。  </li>
</ul>
Project for Office 365、Outlook for Windows、Outlook for iOS および Android 用の outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for business などのオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office のシステム要件</a>」で定義されている最低レベルである必要があります。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 情報ガバナンス</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  情報ガバナンス。  </li>
<li>  保持ラベルとポリシー。  </li>
<li>  レコード管理。  </li>
<li>  削除ポリシー。  </li>
<li>  通信コンプライアンス。  </li>
<li>  Insider リスク管理。  </li>
<li>  Advanced eDiscovery  </li>
</ul></td>
<td><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  データの分類。  </li>
<li>  機密情報の種類。  </li>
<li>  機密ラベルを作成する。  </li>
<li>  機密ラベルを適用する。  </li>
<li>  統合されたラベル付け。  </li>
<li>  Trainable 分類子。  </li>
<li>  コンテンツエクスプローラーとアクティビティエクスプローラーを使用してデータを把握します。  </li>
<li>  ポリシーを使用してラベルを発行する (手動および自動)。  </li>
<li>  Microsoft Teams のチャットおよびチャネルのデータ損失防止 (DLP) ポリシーを作成します。  </li>
</ul></td>
<td><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  Teams をサポートするために、Exchange Online、SharePoint Online、Office 365 グループ、および Azure AD の最小要件を確認します。  </li>
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
<li>  Teams app policy (Teams web app、Teams デスクトップアプリ、および iOS および Android アプリの Teams) を構成します。  </li>
</ul>
該当する場合は、次のようなガイダンスも提供します。
<ul>
<li>  Microsoft Teams のルームデバイス:  </li>
</ul>
<ul>
<li>   <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams デバイスカタログ</a>にリストされている、サポートされているテレフォニーおよび会議室デバイスに必要なオンラインアカウントの作成。  </li>
</ul>
<ul>
<li>  電話会議を有効にする:  </li>
</ul>
<ul>
<li>  会議ブリッジの既定の設定のための組織のセットアップ。  </li>
<li>  ライセンスを持つユーザーへの会議ブリッジの割り当て。  </li>
</ul>
<ul>
<li>  電話システム:
<ul>
<li>  Cloud Voice の既定の設定のための組織のセットアップ。  </li>
<li>  通話プランガイダンス (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">利用可能なマーケット</a>):
<ul>
<li>  ライセンスを持つユーザーへの番号の割り当て。  </li>
<li>  ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。  </li>
<li>  999 件を超える電話番号の移植サービス リクエスト (SR) サポート。  </li>
</ul></li>
<li>  ダイレクトルーティングのガイダンス:
<ul>
<li>  パートナー ホスティング シナリオまたは単一サイトでの顧客展開シナリオの直接ルーティング デサインのための組織のセットアップ ガイド。  </li>
</ul></li>
</ul></li>
<li>  Teams ライブ イベントの有効化。  </li>
<li>  組織のセットアップと Microsoft Stream への統合。  </li>
</ul></td>
<td><ul>
<li>  Office 365 の Azure AD で有効になっている id。  </li>
<li>  SharePoint Online に対してユーザーが有効になっている。  </li>
<li>  Exchange メールボックスが存在する (Exchange ハイブリッド構成でオンラインおよびオンプレミス)。  </li>
<li>  Office 365 グループに対して有効になっている。  </li>
</ul>
  <strong>注:</strong>  ユーザーが SharePoint Online のライセンスで割り当てられて有効になっていない場合は、Office 365 の OneDrive for Business ストレージはありません。 ファイル共有はチャネル内でも引き続き機能しますが、Office 365 の OneDrive for business ストレージを使用せずに、ユーザーはチャットでファイルを共有できません。 Teams は、オンプレミスの SharePoint をサポートしていません。  <br>
  <strong>注:</strong>  理想的な状態は、すべてのユーザーが Exchange Online 上にメールボックスを配置することです。 オンプレミスのメールボックスを持つユーザーは、Azure AD Connect を使用して、Office 365 ディレクトリにその id を同期する必要があります。 これらの Exchange ハイブリッドユーザーの場合、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加または構成することはできません。  
  Microsoft Teams Windows および Mac デスクトップクライアントのインストーラーは、からダウンロードでき  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> ます。  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。  </li>
<li>  自動化、調査、応答の構成。  </li>
<li>  攻撃シミュレータの使用。  </li>
<li>  レポート作成と脅威分析。  </li>
</ul></td>
<td><a href="#general">一般</a>の<strong>コアのオンボード</strong>部分とは別に、最小限のシステム要件はありません。</td>
</tr>
<tr class="even">
<td><strong>iOS 版および Android 版 Outlook</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。  </li>
<li>  アカウントの構成、および Exchange Online メールボックスへのアクセス。  </li>
<li>  Outlook mobile をセキュリティで保護する (詳細については <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">、「Exchange Online で outlook For iOS と outlook For Android を保護</a> する」を参照してください)。  </li>
</ul></td>
<td><ul>
<li>  Office 365 の Azure AD で有効になっている id。  </li>
<li>  Exchange Online が構成され、ライセンスが割り当てられている。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  Power BI ライセンスの割り当て。  </li>
<li>  Power BI Desktop アプリの展開。  </li>
</ul></td>
<td>Power BI Desktop のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低レベルである必要があります。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  Project Online が依存している基本的な SharePoint の機能の確認。  </li>
<li>  テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。  </li>
<li>  エンタープライズ リソース共有元 (ERP) のセットアップ。  </li>
<li>  最初のプロジェクトの作成。  </li>
</ul></td>
<td>「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional および Premium</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。  </li>
<li>  Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。  </li>
</ul></td>
<td>「Project for Office 365」のようなオンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</td>
</tr>
<tr class="even">
<td><strong>Sharepoint Online と OneDrive for Business</strong></td>
<td>  次のためのリモートガイダンスを提供します。
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
SharePoint のバージョンによっては、次のように、OneDrive for Business に関する追加のガイダンスが提供されます。
<ul>
<li>  統合オプションを識別し、オンプレミスおよびオンラインのネットワークインフラストラクチャと帯域幅を確認します。  </li>
<li>  SharePoint Online 2013 SP1 (該当する場合) のインストール、同期および id の要件の計画と実装、および OneDrive for Business 同期クライアントの識別を行います。  </li>
<li>  すべてのユーザー (または段階的なロールアウト) に対して単一のロールアウトを計画し、実装します。  </li>
<li>  ライセンスの割り当て、個人用サイトおよび個人用ドキュメントライブラリの Office 365 へのリダイレクト (SharePoint Online 2013 に該当)、対象ユーザーを設定して OneDrive へのアクセスを制御する (SharePoint Online 2013 に適用)。  </li>
<li>既知のフォルダーを OneDrive にリダイレクトまたは移動します。</li>
<li>  OneDrive for Business クライアントの同期を展開します。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に FastTrack の利点を使用する方法については、「 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">データ移行</a>」を参照してください。
</ul></td>
<td><br><strong>SharePoint ハイブリッドの場合:</strong>  
<ul>
<li>  SharePoint ハイブリッド構成には、ハイブリッド検索、サイト、分類、コンテンツタイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネットサイト、およびオンプレミスから単一のターゲット SharePoint Online 環境に接続されたセルフサービスサイト作成の構成が含まれます。  </li>
</ul>
  <strong>注:</strong> セルフサービスサイト作成は、SharePoint 2013 を実行しているオンプレミスサーバーの範囲内にありません。  
<ul>
<li>  SharePoint ハイブリッドを有効にするには、次のオンプレミスの SharePoint Server 環境のうちの1つが必要です。2013、2016、または2019。  </li>
</ul>
  <strong>注:</strong> オンプレミスの SharePoint 環境の SharePoint Server へのアップグレードは、スコープ内にありません。 詳細については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。 詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint ハイブリッド機能の最小パブリック更新プログラムレベル</a>」を参照してください<em>。</em>  <br>
  <strong>注:</strong>複数地域機能の詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 の「OneDrive および SharePoint Online の複数地域機能</a>」を参照してください<em>。</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  次のためのリモートガイダンスを提供します。
<ul>
<li>  ファイアウォール ポートの構成。  </li>

<li>  DNS の設定。  </li>
<li>  ネットワーク評価:
<ul>
<li>  ポートとエンドポイントの確認。  </li>
<li>  接続品質の確認。  </li>
<li>  帯域幅の推定値。  </li>
</ul></li>
<li>  ルーム システム デバイスのアカウントの作成。  </li>
<li>  サポートされる Skype for Business Online クライアントの展開。  </li>
<li>  オンプレミスの Lync 2010、Lync 2013、Skype for Business 2015 サーバー環境と、Skype for Business Online テナント (該当する場合)、通話プラン、Skype 会議ブロードキャスト、電話システムおよび通話プラン (利用可能なマーケットのみ) との間で、分割ドメイン サーバー構成を確立する。  
  必要に応じて、FastTrack で次の手順についても説明します。  </li>
<li>  ルームシステムデバイスの構成:
<ul>
<li>   <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype For business ソリューションカタログ</a>の [会議室システム] タブに一覧表示される、サポートされている会議室デバイスに必要なオンラインアカウントの作成。  </li>
</ul></li>
<li>  ハイブリッドおよび分割ドメインサーバーの構成。  </li>
<li>  電話会議の構成:
<ul>
<li>  会議ブリッジの既定の設定のための組織のセットアップ。  </li>
<li>  ライセンスを持つユーザーへの会議ブリッジの割り当て。  </li>
</ul></li>
<li>  電話システムの既定の設定の構成:
<ul>
<li>  通話プラン:
<ul>
<li>  ライセンスユーザーへの番号の割り当て。  </li>
<li>  ユーザーインターフェイスを介して99までのローカル番号の移植ガイダンス  </li>
<li>  999を超える電話番号の移植サービス要求のサポート  </li>
</ul></li>
</ul></li>
<li>  Skype for Business 会議ブロードキャストを構成する:
<ul>
<li>  会議メディア サービスとのフェデレーションのための組織のセットアップ。  </li>
</ul></li>
</ul></td>
<td>  <strong>Lync ハイブリッドの場合:</strong>  
<ul>
<li>  1 つのオンプレミスの Active Directory フォレスト。  </li>
<li>  Lync 2010 Server 環境と、Lync 2013 2013 管理ツールまたは Skype for Business 2015 管理ツール、および Lync 2010 エッジ サーバーの役割。  </li>
<li>  Lync 2013 Server 環境と Lync 2013 エッジ サーバーの役割。  </li>
</ul>
  <strong>Skype for Business ハイブリッドの場合:</strong>  
<ul>
<li>  1 つのオンプレミスの Active Directory フォレスト。  </li>
<li>  1 つの Active Directory アカウント フォレスト以降とリソース フォレスト (Exchange と Skype for Business の一方または両方) のトポロジ。  </li>
<li>  複数の Active Directory アカウント フォレスト、および一元化された Active Directory アカウント フォレストで、その中に Exchange と Skype for Business の一方または両方がある 1 つのフォレスト。  </li>
<li>  Skype for Business エッジ サーバーの役割を含む Skype for Business Server 2015 環境。  </li>
</ul>
  <strong>注:</strong> この追加サービスは、分割ドメイン (ハイブリッド) タスクを構成および検証するためのものであり、オンプレミスコンポーネント (Lync 2013 管理ツール、Lync 2013/Skype for Business Online サーバー、Lync 2010、Lync 2013、Skype for Business edge server など) の導入も含みません。  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Yammer Enterprise service を有効にするためのリモートガイダンスを提供します。  
</ul></td>
<td>オンラインクライアントソフトウェアは、「 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 および Office のシステム要件</a>」で定義されている最低限のレベルである必要があります。</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>エンタープライズモビリティ & のセキュリティ

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></td>
<td>  次のシナリオでは、クラウド id を保護するためのリモートガイダンスを提供します。  

 <br/>

<strong>セキュリティ保護された基盤インフラストラクチャ</strong>  </ul>
<ul>
<li>  Azure 多要素認証 (MFA) (クラウドのみ)、Microsoft Authenticator アプリ、および Azure MFA とセルフサービスのパスワードのリセット (SSPR) の組み合わせを含む、強力な認証の構成と有効化。  </li>
<li>  非 Azure AD Premium のお客様の場合は、セキュリティの既定値を使用して id をセキュリティで保護するためのガイダンスが提供されます。  </li>
<li>  Azure AD premium のお客様の場合、条件付きアクセスを使用して id をセキュリティで保護するためのガイダンスが提供されています。  </li>
<li>  Azure AD パスワード保護を使用して、脆弱なパスワードの使用を検出およびブロックします。  </li>
<li>  Azure AD アプリケーションプロキシを使用したオンプレミスの web アプリケーションへのリモートアクセスをセキュリティで保護する。  </li>
<li>  Azure Id 保護を使用したリスクベースの検出と修復を有効にします。  </li>
<li>  ロゴ、テキスト、イメージを含むカスタマイズされたサインイン画面を有効にして、カスタムブランド化します。  </li>
<li>  Azure AD B2B を使用して、アプリやサービスをゲストユーザーと安全に共有できます。  </li>
<li>  役割ベースのアクセス制御 (RBAC) 組み込みの管理役割を使用して Office 365 管理者のアクセスを管理し、特権のある管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure AD join を構成します。  </li>
<li>  Azure AD join を構成します。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure AD Connect Health を使用して AD FS、Azure AD Connect、およびドメインコントローラーのリモート監視を有効にします。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure ad 受給管理を使用して、Azure AD id とアクセスのライフサイクルをスケールで管理します。
  </li>
<li>  
  Azure ad グループメンバーシップ、エンタープライズアプリアクセス、および Azure AD アクセスレビューを使用したロール割り当てを管理します。  
  </li>
<li>  
  Azure AD の使用条件を確認します。  
  </li>
<li>  
  Azure AD 特権 Id 管理を使用して、特権のある管理者アカウントへのアクセスを管理および管理します。  
  </li>
</ul>
  
<strong>自動化と効率性 </strong>  
<ul>
<li>  
  Azure AD SSPR を有効にします。  
  </li>
<li>  ユーザーが Azure AD セルフサービスグループ管理を使用して、独自のクラウドセキュリティまたは Office 365 グループを作成および管理できるようにします。  </li>
<li>  Azure AD 委任されたグループ管理を使用して、エンタープライズアプリへの委任されたアクセスを管理します。  </li>
<li>  Azure AD の動的グループを有効にします。  </li>
<li>  コレクションを使用して、個人用アプリポータルでアプリを整理します。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は Azure ad Premium 用に準備されています。これには、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復が含まれています。</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection (P2 または EMS E5)</strong></td>
<td>  次の方法についてのガイダンスを提供します。
<ul>
<li>  テナントのアクティブ化と構成を行います。  </li>
<li>  ラベルおよびポリシーの作成および設定。  </li>
<li>  情報保護のドキュメントへの適用。  </li>
<li>  Windows で実行され、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) での自動分類およびラベル付け。  </li>
<li>  Azure Information Protection スキャナーを使用した、保管中ファイルの使用。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>
Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用する場合も、ガイダンスを提供します。  </td>
<td>  既に次のことを行う必要があります。
<ul>
<li>  Azure AD を使用します。  </li>
<li>  Windows または iOS のどちらか (他のオペレーティングシステムがスコープ外) を使用します。  
  </ul>
<strong>注</strong>: コンピューターとモバイルデバイスは、Azure Information Protection をサポートする <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">オペレーティングシステム</a> で実行する必要があります。  
<li>  メインファイル共有場所を用意します。  </li>
<strong>注</strong>: ハイブリッドサポートには、AD RMS コネクタが必要です。 
<li>  分類の分類が承認されている。  </li>
<li>  保護されたキーの管理に関する規制の制限について説明します。  </li>
</ul>
  
<strong>Azure Information Protection スキャナー</strong>  
  
既に次のことを行う必要があります。  
<ul>
<li>  Windows Server 2012 R2 または Windows Server 2016 を使用します。  </li>
<li>  インターネットに接続されている。  </li>
<li>  ローカルまたはリモートのインスタンスで Microsoft SQL Server 2012 以降が必要です。  </li>
<li>  オンプレミスの Active Directory に対してサービスアカウントを作成し、Azure AD と同期させます。  </li>
<li>  AzInfoProtection.exe をダウンロードしました。  </li>
<li>  自動分類/保護に対してラベルを構成します。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  アプリとデバイスのための、クラウドベースのモバイルデバイス管理 (MDM) およびモバイルアプリ管理 (MAM) プロバイダーとして Intune を使用するためのガイダンスを提供します。 具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。 以下の手順が含まれる可能性があります:
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド id (Azure AD) を活用して、Intune で使用される id を構成します。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  次のような管理ニーズに基づいて MDM 機関を構成します。
<ul>
<li>  Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。  </li>
</ul></li>
<li>  以下の MDM ガイダンスの提供:
<ul>
<li>  MDM 管理ポリシーの検証に使用するテストグループの構成。  </li>
<li>  以下のような、MDM 管理ポリシーとサービスの構成:
<ul>
<li>  Web リンクまたはディープリンクを介した、サポートされている各プラットフォームのアプリの展開。  </li>
<li>  条件付きアクセスポリシー。  </li>
<li>  組織内に既存の証明機関、ワイヤレスネットワーク、または VPN インフラストラクチャがある場合に、電子メール、ワイヤレスネットワーク、および VPN プロファイルを展開します。  </li>
<li>  Microsoft Intune Exchange Connector のセットアップ (該当する場合)。  </li>
<li>  Intune データウェアハウスに接続します。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモートアシスタンスのチームビューアー (チームビューアーサブスクリプションが必要)。  </li>
<li>  モバイル脅威防御 (MTD) パートナーソリューション (MTD サブスクリプションが必要です)。  </li>
<li>  電気通信経費管理ソリューション (電気通信経費管理ソリューションサブスクリプションが必要)。  </li>
<li>  Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。  </li>
</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  アプリ保護ガイダンスの提供:
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理対象アプリの条件付きアクセスポリシーを構成する。  </li>
<li>  前述の MAM ポリシーを使用して、適切なユーザーグループを対象にします。  </li>
<li>  管理対象アプリの使用状況レポートを使用します。  </li>
</ul></li>
<li>  レガシ PC 管理から Intune MDM への移行ガイダンスの提供。  </li>
</ul>
  <strong>注</strong>: レガシ PC 管理は、2020年10月15日以降ではサポートされていません。  
</li>
</ul>
  
<strong>クラウド接続</strong>  

  ここでは、Intune を使用した既存の Configuration Manager 環境のクラウド接続の準備について説明します。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  Intune を使用してクラウドに接続することの利点についての説明。  </li>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  Configuration Manager コンソールでのクラウド接続の有効化。  </li>
<li>  ハイブリッド Azure AD join を設定するためのガイダンスを提供します。  </li>
<li>  MDM 自動登録用に Azure AD をセットアップするためのガイダンスを提供します。  </li>
<li>  クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>IOS および Android 用の Outlook mobile を安全に展開する</strong> ユーザーが必要なすべてのアプリをインストールしていることを確認するために、iOS および Android 用の Outlook mobile を組織に安全に展開するためのガイダンスを提供することができます。  
  Intune を使用して iOS および Android 用の Outlook mobile を安全に展開するための手順は、ソース環境によって異なります。 次のものが含まれます。
<ul>
<li>  Apple App Store または Google Play ストアを介して、iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリをダウンロードします。  </li>
<li>  セットアップのガイダンスを提供します。
<ul>
<li>  IOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリの展開 (Intune)。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセスポリシー。  </li>
<li>  アプリ構成ポリシー。  </li>
</ul></li>
</ul>
  
  <strong>注</strong>: fasttrack は、Exchange モバイルデバイスメールボックスポリシーを使用して IOS および Android 用の Outlook のセキュリティ保護をサポートしていません。 この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。  
  </td>
<td>  IT 管理者は、Intune を使用してワイヤレスネットワークおよび VPN プロファイルを展開する計画を立てるときに、既存の証明機関、ワイヤレスネットワーク、および VPN インフラストラクチャを運用環境で既に稼働している必要があります。  
  <strong>注</strong>: fasttrack サービス特典には、Intune の証明機関、ワイヤレスネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書をセットアップまたは構成するための支援は含まれていません。  

<strong>Intune を使用して Configuration Manager をクラウドで接続する</strong>  

 クラウド接続を使用すると、IT 管理者はオンプレミス環境の準備を行うことができます。 これには、Intune による構成マネージャー環境のクラウド接続を妨げる問題の修復が含まれることがあります。  
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: MICROSOFT Defender ATP との Intune の統合、および Windows 10 のリスクレベルの評価に基づくデバイスコンプライアンスポリシーの作成に関する支援を提供しています。 購入、ライセンス、またはライセンス認証についてのサポートは提供していません。 この点については、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。  
  
<strong>IOS および Android 用の Outlook を、Intune を使用して安全に展開する </strong>  
<ul>
<li>  Office 365 の Azure AD で有効になっているユーザー id。  </li>
<li>  ユーザーライセンスが割り当てられている exchange Online またはハイブリッド Exchange。  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境の要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Windows 7 Professional および Windows 8.1 Professional から Windows 10 Enterprise へのアップグレードに役立つガイダンスが提供されています。  
  次のためのリモートガイダンスを提供します。
<ul>
<li>  Windows 10 の目的を理解します。  </li>
<li>  ソース環境と要件を評価します (Windows 10 展開をサポートするために、Microsoft エンドポイント構成マネージャーが必要なレベルにアップグレードされていることを確認してください)。  </li>
<li>  Microsoft エンドポイント構成マネージャーまたは Microsoft 365 を使用して、Windows 10 Enterprise と Microsoft 365 アプリを展開します。  </li>
<li>  Windows 10 アプリを評価するためのオプションを推奨します。  </li>
<li>  デスクトップ分析展開計画の作成による、デスクトップ分析およびガイダンスの使用を有効にする。  </li>
<li>  Microsoft 365 アプリの互換性評価は、構成マネージャーで Office 365 レディネスダッシュボードを活用するか、またはスタンドアロンの準備ツールキットを使用して Office plus Microsoft 365 アプリを展開することによって評価されます。  </li>
<li>  Microsoft Intune を使用したクラウド接続の構成マネージャーや、単独のクラウド管理ソリューションとしての Intune の展開など、最新の管理戦略を評価します。  </li>
<li>  展開を成功させるために、ソース環境を最小要件にするために必要な作業について、修復チェックリストを作成します。  </li>
<li>  必要なデバイスハードウェア要件を満たしている場合は、既存のデバイスのアップグレードガイダンスを Windows 10 Enterprise に提供します。  </li>
<li>  既存の展開の動きをサポートするためのアップグレードガイダンスを提供します。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。  </li>
<li>  Windows 10 展開の一環として構成マネージャーを使用して、Microsoft 365 アプリを展開します。   </li>
<li>  既存の構成マネージャー環境または Microsoft 365 を使用して、Windows 10 Enterprise および Microsoft 365 アプリを使用して、組織が最新の状態を維持するためのガイダンスを提供します。  </li>
<li>  クラウドを使用した最新の管理を有効にするためのガイダンスを提供するか、intune に構成マネージャーを展開する (必要な場合)。  </li>
</ul>
  <strong>次の範囲外です </strong>  
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
これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。  </td>
<td>  PC のアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  ソース OS: Windows 7 Enterprise または Professional、Windows 8.1 Enterprise または Professional。  </li>
<li>  デバイス: デスクトップ、ノートブック、またはタブレットフォームファクター。  </li>
<li>  ターゲット OS: Window 10 Enterprise。  </li>
</ul>
インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  Microsoft エンドポイント構成マネージャー。  </li>
<li>  構成マネージャーのバージョンは、Windows 10 のターゲットのバージョンでサポートされている必要があります。 詳細については、「configuration <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">manager での Windows 10 のサポート</a>」の構成マネージャーサポートの表を参照してください。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  次のためのリモートガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティで保護するためのテクノロジを展開する。  </li>
<li>  エンドポイント保護とデバイス制限プロファイルを構成する。  </li>
<li>  Windows Defender AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態、および Intune、Microsoft エンドポイント構成マネージャー、グループポリシーオブジェクト (Gpo)、サードパーティの構成を含む、OS バージョンとデバイスの管理を評価します。  </li>
<li>  Windows AV サービスまたはその他のエンドポイントセキュリティソフトウェアの状態を評価します。  </li>
<li>  ネットワークトラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボードエンドポイントを使用して ATP エージェントプロファイルを展開する方法について説明することにより、Microsoft Defender ATP サービスを有効にします。  </li>
<li>  展開のガイダンス、構成の支援、および教育:
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
<li>  シミュレーションとチュートリアル (プラクティスシナリオ、偽のマルウェア、自動調査など) をレビューします。  </li>
<li>  レポート機能と脅威分析機能の概要。  </li>
<li>  Office 365 の ATP と Microsoft Defender ATP の統合。  </li>
<li>  Microsoft Defender セキュリティ センター ポータルのチュートリアルを実行します。  </li>
<li>  次のオペレーティングシステム。
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
  Windows Server 半期チャネル (SAC) バージョン1803。  
  </li>
<li>  
  macOS バージョン10.13、10.14、および10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注:</strong> Windows Server のすべてのバージョンは、System Center Configuration Manager 2012 (バージョン 1012 R2、1511、または 1602) または Microsoft エンドポイント構成マネージャー (バージョン2002以上) の最新バージョンで管理されている必要があります。 

</li>
</ul>

<strong>次の範囲外です </strong>  
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
  マシン.  
  </li>
<li>  
  モバイルデバイス (Android および iOS)。  
  </li>
</ul></li>
<li>  サーバーのオンボードと構成:
<ul>
<li>  
  オフライン通信用のプロキシサーバーを構成する。  
  </li>
<li>  
  下位レベルの構成マネージャーのインスタンスとバージョンで構成マネージャーの展開パッケージを構成する。  
  </li>
<li>  
  Azure セキュリティセンターへのオンボードサーバー。  
  </li>
<li>  
  構成マネージャーで管理されていないサーバー。  
  </li>
</ul></li>
<li>  macOS のオンボードと構成:
<ul>
<li>  
  手動による Intune ベースの展開。  
  </li>
<li>  
  JAMF ベースの展開。
  </li>
<li>  
  その他のモバイルデバイス管理 (MDM) 製品ベースの展開。  
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
<li>  構成またはトレーニング API またはセキュリティ情報およびイベント管理 (SIEM) 接続を確認します。  </li>
<li>  Microsoft 脅威保護 (MTP) の登録または構成。  </li>
<li>  高度な検出に関するトレーニングまたはガイダンス。  </li>
<li>  Kusto クエリの使用または作成をカバーするトレーニングまたはガイダンス。</li>
</li>
</ul>
これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a> にお問い合わせください。  
</ul></td>
<td></td>

</tbody>
</table>
