---
title: 製品と機能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: このトピックでは、開始前に FastTrack によってサポートされるワークロード シナリオの詳細と、必要なソース環境要件について説明します。 現在のセットアップ環境に基づいて、お客様と連同してソース環境をオンボーディングを正常に行うための最小要件を満たす修復計画を作成します。
ms.openlocfilehash: d25c1df8e628f14487952cacc86ccf8fb9dad8c1
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817702"
---
# <a name="products-and-capabilities"></a>製品と機能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack によってサポートされるサービスとシナリオ

このトピックでは、開始前に FastTrack によってサポートされるワークロード シナリオの詳細と、必要なソース環境要件について説明します。 現在のセットアップ環境に基づいて、お客様と連同してソース環境をオンボーディングを正常に行うための最小要件を満たす修復計画を作成します。

FastTrack は、最初にコア機能 (すべての Microsoft Online Services に共通) を作成し、次に対象となる各サービスのオンボーディングをサポートするためのガイダンスを提供します。

  - [全般](#general)
  - [Office 365](#office-365)
  - [Enterprise Mobility & Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [App Assure](Win-10-app-assure.md)
  - [新しい Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> Office 365 US Government のソース環境要件については、「 [展開元環境要件:Office 365 US Government」を参照してください](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。
 
## <a name="general"></a>全般

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
<td><strong>コア オンボーディング</strong></td>
<td>  コア オンボーディングに関するガイダンスを提供します。それには、サービスのプロビジョニング、テナント、ID の統合が含まれます。 また、Exchange Online、SharePoint Online、Microsoft Teams などのオンボーディング サービスの基盤を提供する手順も含まれています。これには、セキュリティ、ネットワーク接続、およびコンプライアンスについてのディスカッ <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ションも含まれます</a>。  
  1 つ以上の対象サービスをオンボーディングする作業は、コア オンボーディングを終えてから開始できます。
</li>
</ul>  

<strong> ID 統合 </strong>

次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>Azure Active Directory (シングル フォレストまたは複数フォレスト) とライセンス (グループベースのライセンスを含む) のインストールと構成を含め、Azure AD Active Directory (Azure AD) と同期するためのオンプレミスの Active Directory ID の準備を含む。</li>
<li>グループベースのライセンスの使用を含む一括インポートやライセンスなど、クラウド ID の作成。</li>
<li>クラウドへの移行、パスワード ハッシュ同期、パススルー認証、または Active Directory フェデレーション サービス (AD FS) の正しい認証方法を選択して有効にします。</li>
<li>1 つの AD アカウントと Azure 共有 Active Directory 接続ツールと同期された ID を持つお客様に対ADします。 これには、R2 Windows Server 2012 サービス 2.0 以上の証明書が必要です。</li>
<li>パスワード ハッシュ同期またはパスAD使用して、FS から Azure AD に認証を移行します。</li>
<li>シングル サインオン (SSO) 用に、事前統合されたアプリ (Azure AD ギャラリー ソフトウェア (SaaS) アプリなど) の AD FS から Azure AD への移行。</li>
<li>Azure の仮想システム ギャラリーから SaaS アプリと SSO の統合AD有効にします。</li>
<li>[アプリ統合チュートリアル] リストに記載されている、事前統合された SaaS アプリに対するユーザーの自動プロビジョニング <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">の有効化</a> (Azure AD ギャラリー SaaS アプリと送信プロビジョニングのみに限定されます)。  </li>
</td>

<td>  <strong>ネットワークの有効化 </strong>  
  <br>FastTrack 特典の一部として、Microsoft 365 の最高レベルのパフォーマンスを確実にするために、クラウド サービスに接続するためのベスト プラクティスへのリンクを提供してください。  
  
<strong>Active Directory フォレスト</strong> フォレスト構成は、機能フォレスト レベルを Windows Server 2003 以降に設定します。
<ul>
<li>  1 つの Active Directory フォレスト。  </li>
<li>  単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    </li>
<li>  複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。  </li>
<li>  複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。  </li>
<li>  テナント構成と Azure Active Directory との統合 (必要な場合) に必要なタスク。   </li>
</ul>
  <strong>大事な：</strong>  <ul>
<li>  複数のフォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開される場合は、Exchange と同じ Active Directory フォレスト内に展開する必要があります。  </li>
<li>  複数の Exchange 組織を含む複数の Active Directory フォレストを Exchange マルチ ハイブリッド構成で実装する場合、ソース フォレスト間で共有されているユーザー プリンシパル名 (UPN) の名前空間はサポートされません。 Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。 詳細については、「 <a href="https://go.microsoft.com/fwlink/?linkid=845444">複数の Active Directory フォレストを伴うハイブリッド展開</a>」を参照してください。  </li>
<li>  フォレストが複数あるすべての構成で、Active Directory フェデレーション サービス (AD FS) の展開は対象外です。 この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 アプリ</strong></td>
<td>  以下に関するリモート展開のガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Microsoft 365 アプリのインストール。  </li>
<li>  iOS または Android デバイスへの Office モバイル アプリ (Outlook Mobile、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  ローカルまたはクラウドのインストールの選択とセットアップ。  </li>
<li>  Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。  </li>
<li>  Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。  
  さらに、以前のバージョンの Office で作業していたマクロまたはアドインで互換性の問題が発生した場合、Microsoft は App Assure プログラムによる追加料金なしで互換性の問題を解決するためのガイダンスを提供します。 詳しくは<a href="#windows-10">、Windows 10</a>の App <strong>Assure</strong>の部分をご覧ください。 </li>
</ul></td>
<td><ul>
<li>  オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および組織のシステム要件で定義されている最小レベルを満たOffice。</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>ネットワークの正常性</strong></td>
<td>  Microsoft は、ネットワーク接続のマイクロソフトの原則に組織のサイトを整合する方法を示す、ご利用の環境からお客様の環境から主要なネットワーク接続データを取得して解釈するためのリモート <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">ガイダンスを提供します</a>。 これにより、移行の実行のウィンドウローク性、ユーザー エクスペリエンス、サービスのパフォーマンス、信頼性に直接影響するネットワークのスコアが強調されます。  
  また、このデータによって強調表示される、ネットワーク スコアの改善に役立つ修復手順についても説明します。  </td>
<td><ul>
<li>  Microsoft 365 管理センターへのアクセス。  </li>
<li>  Microsoft 365 アプリの最新バージョンが必要です。  </li>
<li>  Microsoft 365 管理センター <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">(プレビュー) でネットワーク パフォーマンスに関する推奨事項に従って有効になっている場所サービス。</a>  </li>
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
<th><strong>ソース環境要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Exchange Online の場合、組織がメールをすぐに使用できるようにするプロセスを案内します。 正確な手順は、お使いのソース環境とメールの移行プランによって異なります。  
  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Office 365 で検証される、メールが有効なすべてのドメインの Exchange Online Protection (EOP) 機能の設定。  </li>
<li>  メール交換 (MX) レコードのポイントを 365 Officeします。  </li>
<li>  Office 365 ATP 機能がサブスクリプション サービスに含まれています。 詳細については、この表の <strong>「Office 365 Advanced Threat Protection」</strong> の部分を参照してください。  </li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、データ損失防止 (DLP) 機能を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
<li>  サブスクリプション サービスの一部として、Office 365 で検証済みのすべてのメールが有効なドメインに、Office 365 Message Encryption (OME) を設定します。この設定は、MX レコードが Office 365 をポイントすると実行されます。</li>
</ul>
  <strong>注:</strong> メールボックス レプリケーション サービス (MRS) は、オンプレミスのメールボックスから対応する Exchange Online メールボックスへの Information Rights Managed (IRM) で管理されたメールの移行を試行します。 移行後に保護されたコンテンツを読み取る機能は、Active Directory Rights Managed サービス (AD RMS) テンプレートから Azure Rights Management サービス (Azure RMS) への、お客様によるマッピングとコピーに依存しています。  
<ul>
<li>  ファイアウォール ポートの構成。  </li>
<li>  必要な自動検出、Sender Policy Framework (SPF)、DomainKeys Identified Mail (DKIM)、Domain-based Message Authentication、Reporting and Conformance (DMARC)、および MX レコード (必要に応じて) を含む DNS のセットアップ。  </li>
<li>  ソース メッセージング環境と Exchange Online との間のメール フローをセットアップします (必要な場合)。  </li>
<li>  ソースのメッセージング環境から Office 365 にメール移行を実行。  </li>
<li>  メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に関する FastTrack 特典の使用に関する詳細については、「データ移行 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">」を参照してください</a>。   
<td>  ソース環境には、次に示す最低レベルのいずれかが必要です。
<ul>
<li>  Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。  </li>
<li>  1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。  </li>
<li>  単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。  </li>
<li>  複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=872776">、Exchange Online の複数地域機能を参照してください</a>。  </li>
</ul>
Project for Office 365、Office 365 用 Outlook、iOS および Android 用の Outlook、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは、Microsoft 365 Office のシステム要件で定義されている最小 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">レベルを満たしていなけらなけらなけずに、必要です</a>。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 情報ガバナンス</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  情報ガバナンス。  </li>
<li>  保持ラベルとポリシー。  </li>
<li>  レコード管理。  </li>
<li>  削除ポリシー。  </li>
<li>  通信コンプライアンス。  </li>
<li>  インサイダー リスクの管理。  </li>
<li>  Advanced eDiscovery  </li>
</ul></td>
<td>全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 情報保護</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  データの分類。  </li>
<li>  機密情報の種類。  </li>
<li>  機密ラベルを作成する。  </li>
<li>  機密ラベルの適用。  </li>
<li>  統合されたラベル付け。  </li>
<li>  トレーニング可能な分類です。  </li>
<li>  コンテンツ エクスプローラーとアクティビティ エクスプローラーを使ってデータの確認  </li>
<li>  ポリシーを使用してラベルを発行する (手動および自動)。  </li>
<li>  Microsoft Teams のチャットとチャネルのデータ損失防止 (DLP) ポリシーの作成。  </li>
</ul></td>
<td>全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Teams をサポートするための Exchange Online、SharePoint Online、Office 365 グループ、および Azure ADの最小要件を確認する。  </li>
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
<li>  Teams アプリ ポリシー (Teams Web アプリ、Teams デスクトップ アプリ、iOS および Android 用 Teams アプリ) の構成。  </li>
</ul>
該当する場合は、次の操作のガイダンスも提供します。
<ul>
<li>  Microsoft Teams ミーティング デバイス:  </li>
</ul>
<ul>
<li>  Teams デバイス カタログに一覧表示されている、サポート対象のテレフォニー デバイスと会議室デバイスに必要なオンライン <a href="https://go.microsoft.com/fwlink/?linkid=2066478">アカウントの作成</a>。  </li>
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
<li>  通話プランのガイダンス (利用可能<a href="https://go.microsoft.com/fwlink/?linkid=2066478">な市場の提供):</a>
<ul>
<li>  ライセンスを持つユーザーへの番号の割り当て。  </li>
<li>  ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。  </li>
<li>  999 件を超える電話番号の移植サービス リクエスト (SR) サポート。  </li>
</ul></li>
<li>  ダイレクト ルーティングのガイダンス:
<ul>
<li>  パートナー ホスティング シナリオまたは単一サイトでの顧客展開シナリオの直接ルーティング デサインのための組織のセットアップ ガイド。  </li>
</ul></li>
</ul></li>
<li>  Teams ライブ イベントの有効化。  </li>
<li>  組織のセットアップと Microsoft Stream への統合。  </li>
</ul></td>
<td><ul>
<li>  365 用 Azure AD で Office有効になっている。  </li>
<li>  SharePoint Online に対してユーザーが有効になっている。  </li>
<li>  Exchange メールボックスがある (Exchange ハイブリッド構成でオンラインおよびオンプレミス)。  </li>
<li>  Office 365 グループに対して有効になっている。  </li>
</ul>
  <strong>注:</strong>  SharePoint Online ライセンスがユーザーに割り当てられておらない場合は、SharePoint 365 の OneDrive for Business 記憶域Officeできません。 ファイル共有はチャネル内で引き続き動作しますが、Office 365 に OneDrive for Business ストレージがないと、ユーザーはチャットでファイルを共有できません。 Teams はオンプレミスの SharePoint をサポートしていいない。  <br>
  <strong>注:</strong>  すべてのユーザーがメールボックスを Exchange Online のホームに設定するのが理的な状態です。 メールボックスがオンプレミスでホームに設定されているユーザーは、Azure Connect を介して Office 365 ディレクトリと ID をADする必要があります。 これら Exchange ハイブリッドのお客様について、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加したり構成したりできません。  
  Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、ダウンロードできます  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 。  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  安全なリンク、安全な添付ファイル、フィッシング詐欺対策の有効化。  </li>
<li>  自動化、調査、応答の構成。  </li>
<li>  攻撃シミュレータの使用。  </li>
<li>  レポート作成と脅威分析。  </li>
</ul></td>
<td>全般の <strong>コア オンボーディング</strong> 部分を <a href="#general">取</a>り上り、最小のシステム要件は示していません。</td>
</tr>
<tr class="even">
<td><strong>iOS 版および Android 版 Outlook</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Apple App Store や Google Play からの iOS および Android 用の Outlook のダウンロード。  </li>
<li>  アカウントの構成、および Exchange Online メールボックスへのアクセス。  </li>
<li>  Outlook モバイルの保護 (詳細については、Exchange Online で <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Outlook for iOS および Outlook for Android のセキュリティ保護を</a> 参照してください)。  </li>
</ul></td>
<td><ul>
<li>  365 用 Azure AD で Office有効になっている。  </li>
<li>  Exchange Online が構成され、ライセンスが割り当てられている。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Power BI ライセンスの割り当て。  </li>
<li>  Power BI Desktop アプリの展開。  </li>
</ul></td>
<td>Power BI Desktop などのオンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および Microsoft のシステム要件で定義されている最小レベルを満たOffice。</a></td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Project Online が依存している基本的な SharePoint の機能の確認。  </li>
<li>  テナントへの Project Online サービスの追加 (ユーザーへのサブスクリプションの追加を含みます)。  </li>
<li>  エンタープライズ リソース共有元 (ERP) のセットアップ。  </li>
<li>  最初のプロジェクトの作成。  </li>
</ul></td>
<td>Project for Office 365 などのオンライン クライアント ソフトウェアは、Microsoft 365 および <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 のシステム要件で定義されている最小レベルである必要がありますOffice。</a></td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional と Premium</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  展開の問題への対応。  </li>
<li>  Microsoft 365 管理センターと Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。  </li>
<li>  クイック実行を使用した Office 365 ポータルからの Project Online デスクトップ クライアントのインストール。  </li>
<li>  Office 365 展開ツールを使用した更新設定の構成。  </li>
<li>  Office 365 展開ツールで使用するための configuration.xml ファイルの作成サポートを含む、Project Online デスクトップ クライアント用の 1 つのオンサイト配布サーバーのセットアップ。  </li>
<li>  Project Online デスクトップ クライアントの Project Online Professional または Project Online Premium への接続。  </li>
</ul></td>
<td>Project for Office 365 などのオンライン クライアント ソフトウェアは、Microsoft 365 および <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 のシステム要件で定義されている最小レベルである必要がありますOffice。</a></td>
</tr>
<tr class="even">
<td><strong>Sharepoint Online と OneDrive for Business</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
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
SharePoint バージョンに応じて、その他のガイダンスも OneDrive for Business 向けに提供されます。
<ul>
<li>  統合オプションの特定、社内およびオンラインのネットワーク インフラストラクチャおよび帯域幅の確認。  </li>
<li>  SharePoint Online 2013 SP1 (該当する場合)、同期および ID 要件の計画と実装、および OneDrive for Business 同期クライアントの識別。  </li>
<li>  すべてのユーザー (または段階的にロールアウト) を対象に 1 つのロールアウトを計画し、実装します。  </li>
<li>  Office OneDrive へのアクセス制御を行うための対象ユーザーの設定 (SharePoint Online 2013 に適用可能) へのライセンスの割り当ておよび個人用ドキュメント ライブラリの割り当て、個人用ドキュメント ライブラリのリダイレクトを行います (SharePoint Online 2013 に適用されます)。  </li>
<li>既知のフォルダーを OneDrive にリダイレクトまたは移動する。</li>
<li>  OneDrive for Business クライアント同期の展開。  </li>
</ul>
  <strong>データ移行</strong>  <br>
Office 365 へのデータ移行に関する FastTrack 特典の使用に関する詳細については、「データ移行 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">」を参照してください</a>。
</ul></td>
<td><br><strong>SharePoint ハイブリッドの場合:</strong>  
<ul>
<li>  SharePoint ハイブリッド構成には、オンプレミスから単一のターゲット SharePoint Online 環境に接続するハイブリッドの検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、セルフサービス サイト作成の構成が含まれています。  </li>
</ul>
  <strong>注:</strong> セルフサービス サイト作成は、SharePoint 2013を実行する社内サーバーの対象範囲には含みません。  
<ul>
<li>  SharePoint ハイブリッドを有効にするには、2013、2016、2019 のいずれかのオンプレミスの SharePoint Server 環境を持つ必要があります。  </li>
</ul>
  <strong>注:</strong> オンプレミスの SharePoint 環境の SharePoint Server へのアップグレードは対象範囲外です。 Microsoft パートナーに <a href="https://go.microsoft.com/fwlink/?linkid=2080150">お問い</a> 合わせください。 詳細については <a href="https://go.microsoft.com/fwlink/?linkid=853548">、SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベルを参照してください</a><em>。</em>  <br>
  <strong>注:</strong> 複数地域機能の詳細については <a href="https://go.microsoft.com/fwlink/?linkid=831056">、「OneDrive の複数地域機能」および「Office 365 の SharePoint Online の複数地域機能」を参照してください</a><em>。</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  次の機能に関するリモート ガイダンスを提供します。
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
  該当する場合は、FastTrack に次の手順も示されます。  </li>
<li>  ルーム システム デバイスの構成:
<ul>
<li>  Skype for Business ソリューション カタログの [Meeting Room Systems (会議室システム)] タブに一覧表示されている、サポート対象会議室 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">デバイスに必要なオンライン アカウントの作成</a>。  </li>
</ul></li>
<li>  ハイブリッド サーバーと分割ドメイン サーバーの構成。  </li>
<li>  電話会議の構成:
<ul>
<li>  会議ブリッジの既定の設定のための組織のセットアップ。  </li>
<li>  ライセンスを持つユーザーへの会議ブリッジの割り当て。  </li>
</ul></li>
<li>  電話システムの既定の設定の構成:
<ul>
<li>  通話プラン:
<ul>
<li>  ライセンス ユーザーへの番号の割り当て。  </li>
<li>  ユーザー インターフェイスを通じて 99 までの電話番号の移植ガイダンス。  </li>
<li>  999 以上の電話番号の移植サービス要求のサポート  </li>
</ul></li>
</ul></li>
<li>  Skype for Business 会議ブロードキャストを構成します:
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
  <strong>注:</strong> この追加のサービスは分割ドメイン (ハイブリッド) タスクの構成と検証用で、オンプレミスのコンポーネント (たとえば、Lync 2013 管理ツールや Lync 2013/Skype for Business Online サーバー、Lync 2010、Lync 2013、または Skype for Business エッジ サーバー) の導入は含まれていません。  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Microsoft は、エンタープライズ サービスを有効にするためのリモート Yammer提供します。  
</ul></td>
<td>オンライン クライアント ソフトウェアは <a href="https://go.microsoft.com/fwlink/?LinkID=723597">、Microsoft 365 および Microsoft 365 および組織のシステム要件で定義されている最小レベルを満たOffice。</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility & Security

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) と Azure AD Premium</strong></td>
<td>  次のシナリオで、クラウド ID をセキュリティ保護するためのリモート ガイダンスを提供します。  

 <br/>

<strong>セキュアな基礎インフラストラクチャ</strong>  </ul>
<ul>
<li>  ID に対する強力な認証の構成と有効化。Azure 多要素認証 (MFA) による保護 (クラウドのみ)、Microsoft Authenticator アプリ、Azure MFA とセルフサービス パスワード リセット (SSPR) の組み合わせ登録などが含まれます。  </li>
<li>  Azure 以外のお客様には、セキュリティADを使用して ID をセキュリティ保護するためのガイダンスが提供されています。  </li>
<li>  Azure プレミアムADお客様には、条件付きアクセスで ID を保護するためのガイダンスを提供します。  </li>
<li>  Azure AD Password Protection での弱いパスワードの使用を検出、ADブロックします。  </li>
<li>  Azure エンドポイント アプリケーション プロキシを使用して、オンプレミス Web アプリへのリモート ADをセキュリティ保護します。  </li>
<li>  リスク ベースの検出と Azure Identity Protection による修復の有効化。  </li>
<li>  カスタム ブランドを使用して、ロゴ、テキスト、画像など、カスタマイズしたサインイン画面を有効にする。  </li>
<li>  Azure アカウントと B2B を使用して、ゲスト ユーザーとアプリやサービスを安全AD共有します。  </li>
<li>  役割ベースのアクセス制御 (RBAC) 組み込みの管理者ロールを使用して Office 365 管理者のアクセスを管理し、特権管理者アカウントの数を減らします。  </li>
<li>  ハイブリッド Azure への参加AD方法。  </li>
<li>  Azure への参加ADする。  </li>
</ul>
  
<strong>監視とレポート</strong>  
<ul>
<li>  
  Azure Connect Health を使用した AD FS、Azure AD Connect、およびドメイン コントローラーのリモート監視AD有効にします。  
  </li>
</ul>
  
<strong>ガバナンス</strong>  
<ul>
<li>  
  Azure デバイスのエンADメント管理を使用して、大規模な Azure ID とアクセス ライフADを管理します。
  </li>
<li>  
  Azure グループ メンバーシップADエンタープライズ アプリへのアクセス、役割の割り当ての管理と、Azure ADでのアクセス レビュー。  
  </li>
<li>  
  Azure の使用条件ADの確認。  
  </li>
<li>  
  Azure を使用した特権 ID 管理による特権管理者アカウントAD管理と制御。  
  </li>
</ul>
  
<strong>自動化と効率 </strong>  
<ul>
<li>  
  AD Azure SSPR の有効化。  
  </li>
<li>  セルフサービスによるグループ管理を使用して、ユーザーが独自のクラウド セキュリティや Office office 365 ADを作成および管理できるようにする。  </li>
<li>  Azure でグループ管理を委任されたアプリを使用ADアクセスを管理する。  </li>
<li>  動的なグループADの有効化。  </li>
<li>  コレクションを使って [マイ アプリ] ポータルでアプリを展開する。  </li>
</ul></td>
<td>オンプレミスの Active Directory とその環境は Azure AD Premium 用に準備されています。このコンソールには、Azure AD および Azure AD Premium 機能との統合を防止する特定された問題の修復などが含まれます。</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection (P2 または EMS E5)</strong></td>
<td>  次の方法に関するガイダンスが提供されます。
<ul>
<li>  テナントのアクティブ化と構成。  </li>
<li>  ラベルおよびポリシーの作成および設定。  </li>
<li>  情報保護のドキュメントへの適用。  </li>
<li>  Windows で実行され、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) での自動分類およびラベル付け。  </li>
<li>  Azure Information Protection スキャナーを使用した、保管中ファイルの使用。  </li>
<li>  Exchange Online のメール フロー ルールを使用した、転送中メールの監視。  </li>
</ul>
また、Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用する場合は、ガイダンスを提供します。  </td>
<td>  以下の作業が既に必要です。
<ul>
<li>  Azure サブスクリプションをAD。  </li>
<li>  Windows または iOS のいずれかを使用します (その他のオペレーティング システムは対象外)。  
  </ul>
<strong>注</strong>: コンピューターとモバイル デバイスは、Azure Information Protection を <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">サポートしているオペレーティング システム</a> 上で実行する必要があります。  
<li>  メインのファイル共有場所を指定します。  </li>
<strong>注</strong>: ハイブリッド サポートには、RMS コネクタAD必要があります。 
<li>  承認済みの分類の分類がある場合。  </li>
<li>  保護されたキー管理に対するすべての規制制限を理解します。  </li>
</ul>
  
<strong>Azure Information Protection スキャナー</strong>  
  
以下の作業が既に必要です。  
<ul>
<li>  新Windows Server 2012 R2 または Windows Server 2016 を使用します。  </li>
<li>  インターネット接続。  </li>
<li>  ローカルまたはMicrosoft SQL Serverリモートのインスタンスに 2012 以降のバージョンがある。  </li>
<li>  オンプレミスの Active Directory 用のサービス アカウントが作成し、Azure アカウントとAD。  </li>
<li>  ダウンロードしてAzInfoProtection.exe。  </li>
<li>  ラベルを自動分類/保護用に構成している。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Intune を、アプリおよびデバイス用のクラウドベースのモバイル デバイス管理 (MDM) およびモバイル アプリ管理 (MAM) プロバイダーとして使用する準備についてのガイダンスを提供します。 具体的な手順は、使用しているソース環境やモバイル デバイスとモバイル アプリの管理ニーズに依存します。 以下の手順が含まれる可能性があります:
<ul>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID (Azure AD) を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  管理ニーズに基づき、以下の MDM 機関を構成する。
<ul>
<li>  Intune が MDM ソリューションでしかない場合、MDM 機関として Intune を設定します。  </li>
</ul></li>
<li>  以下の MDM ガイダンスの提供:
<ul>
<li>  MDM 管理ポリシーの検証に使用するテストグループの構成。  </li>
<li>  以下のような、MDM 管理ポリシーとサービスの構成:
<ul>
<li>  Web リンクまたは詳細リンクを介した、サポートされている各プラットフォームでのアプリの展開。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  組織に既存の証明機関、ワイヤレス ネットワーク、VPN インフラストラクチャがある場合の、電子メール、ワイヤレス ネットワーク、VPN のプロファイルの展開。  </li>
<li>  Microsoft Intune Exchange Connector のセットアップ (該当する場合)。  </li>
<li>  Intune データ ウェアハウスへの接続。  </li>
<li>  以下との Intune の統合:
<ul>
<li>  リモート アシスタンス用の Team Viewer (チーム ビューアーのサブスクリプションが必要です)。  </li>
<li>  Mobile Threat Defense (MTD) パートナー ソリューション (MTD サブスクリプションが必要です)。  </li>
<li>  通信経費の管理ソリューション (通信経費の管理ソリューションのサブスクリプションが必要です)。  </li>
<li>  Microsoft Defender ATP (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。  </li>
</ul></li>
<li>  サポートされている各プラットフォームのデバイスの Intune への登録。  </li>
</ul></li>
</ul></li>
<li>  以下のアプリ保護ガイダンスの提供:
<ul>
<li>  サポートされている各プラットフォームでのアプリ保護ポリシーの構成。  </li>
<li>  管理対象アプリの条件付きアクセス ポリシーの構成。  </li>
<li>  前述の MAM ポリシーを使って、適切なユーザー グループを対象にできます。  </li>
<li>  管理対象アプリ使用状況レポートの使用。  </li>
</ul></li>
<li>  従来の PC 管理から Intune MDM への移行ガイダンスの提供。  </li>
</ul>
  <strong>注</strong>: 2020 年 10 月 15 日以降、レガシ PC 管理はサポートされなくなりました。  
</li>
</ul>
  
<strong>クラウド接続</strong>  

  Intune を使用して既存の Configuration Manager 環境をクラウド接続する準備を説明しています。 具体的な手順はソース環境によって異なります。 手順には以下が含まれます。  
<ul>
<li>  Intune を使用してクラウドに接続することの利点についての説明。  </li>
<li>  エンド ユーザーのライセンス認証。  </li>
<li>  オンプレミスの Active Directory またはクラウド ID を利用した、Intune で使用する ID の構成。  </li>
<li>  Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。  </li>
<li>  Configuration Manager コンソールでのクラウド接続の有効化。  </li>
<li>  参加へのハイブリッド Azure の移行のガイダンスADします。  </li>
<li>  MDM 自動登録に必要な Azure ADガイダンスの提供。  </li>
<li>  クラウド管理ゲートウェイをセットアップする方法についてのガイダンスの提供。  </li>
<li>  Intune に切り替えることを希望する、サポートされているワークロードの構成。  </li>
<li>  Intune 登録済みデバイスへの Configuration Manager クライアントのインストール。  </li>
</ul> 

<strong>iOS および Android 用の Outlook モバイルを安全に展開する</strong> iOS および Android 用の Outlook モバイルを組織で安全に展開し、必要なアプリがすべてユーザーにインストールされていることが保たれます。  
  Intune を使用して、iOS および Android 用の Outlook モバイルを安全に展開する手順は、ソース環境によって異なります。 これには以下を含むことができます。
<ul>
<li>  Apple App Store または Google Play ストアから iOS および Android 用の Outlook、Microsoft Authenticator、および Intune ポータル サイト アプリをダウンロードする。  </li>
<li>  セットアップのガイダンスを提供:
<ul>
<li>  Android 用の Outlook、Microsoft Authenticator、および Intune ポータル サイト アプリの Intune での展開。  </li>
<li>  アプリ保護ポリシー。  </li>
<li>  条件付きアクセス ポリシー。  </li>
<li>  アプリの構成ポリシー。  </li>
</ul></li>
</ul>
  
  <strong>注</strong>: FastTrack では、Exchange モバイル デバイス メールボックス ポリシーを使用した Outlook for iOS と Outlook for Android のセキュリティ保護はサポートされていません。 この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  
  </td>
<td>  Intune でワイヤレス ネットワークと VPN プロファイルの展開を計画する際には、IT 管理者は既存の証明機関、ワイヤレス ネットワーク、および VPN インフラストラクチャを運用環境であらかじめ運用している必要があります。  
  <strong>注</strong>: FastTrack サービス特典には、Intune 用の認証機関、ワイヤレス ネットワーク、VPN インフラストラクチャ、または Apple MDM プッシュ証明書のセットアップおよび構成に関するサポートは含まれていません。  

<strong>Intune を使用して Configuration Manager をクラウドで接続する</strong>  

 クラウド接続を使用する場合、IT 管理者がオンプレミス環境の準備を行います。 この中には、Intune を使用した Configuration Manager 環境のクラウド接続を回避する問題の修復が含まれます。  
  <strong>注</strong>: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。

  <strong>Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合</strong> 
 
  <strong>注</strong>: Intune を Microsoft Defender ATP と統合し、Windows 10 のリスク レベル評価に基づいてデバイス コンプライアンス ポリシーを作成するための支援を提供します。 購入、ライセンス、ライセンス認証に関するサポートは提供していません。 この方法について <a href="https://go.microsoft.com/fwlink/?linkid=2080150">、Microsoft パートナー</a> にお問い合わせください。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。  
  
<strong>Intune を使用して Outlook for iOS および Outlook for Android を安全に展開する </strong>  
<ul>
<li>  ユーザー ID は、Azure 365 向けAD Azure Office有効になっています。  </li>
<li>  Exchange Online またはハイブリッド Exchange が構成され、ユーザー ライセンスが割り当てられている。  </li>
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
<th><strong>ソース環境要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Microsoft では、アップグレードとアップグレードをサポートWindows 7 ProfessionalWindows 7 Professional.1 Professional から Windows 8 windows 10 Enterprise へのアップグレードをサポートするガイダンスを提供します。  
  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  Windows 10 の目的を理解する。  </li>
<li>  ソース環境と要件を評価する (Windows 10 の展開をサポートするために必要なレベルに Microsoft Endpoint Configuration Manager をアップグレードする必要があります)。  </li>
<li>  Microsoft Endpoint Configuration Manager または Microsoft 365 を使用する Windows 10 Enterprise および Microsoft 365 アプリを展開する。  </li>
<li>  Windows 10 アプリを評価するためのオプションの推奨。  </li>
<li>  Desktop Analytics 展開計画作成を使用する場合の Desktop Analytics とガイダンスの使用を有効にする。  </li>
<li>  Microsoft 365 アプリ互換性評価:「Configuration Manager の Office 365 の準備状態」ダッシュボードやスタンドアロンの準備 Toolkit (Office に加えて Microsoft 365 アプリの展開を支援します)。  </li>
<li>  Microsoft Intune を使用して Configuration Manager をクラウドで接続する場合や、単一のクラウド管理ソリューションとして Intune を展開するなど、最新の管理戦略の評価。  </li>
<li>  ソース環境を展開を成功にするための最小要件を満たすための必要な修復チェックリストの作成。  </li>
<li>  既存のデバイスが必要なデバイスのハードウェア要件を満たしている場合は、Windows 10 Enterprise へのアップグレードガイダンスを提供します。  </li>
<li>  既存の展開モーションをサポートするためのアップグレード ガイダンスを提供します。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと Windows Autopilot の展開シナリオでも使用できます。  </li>
<li>  Windows 10 の展開の一部として Configuration Manager を使用して Microsoft 365 アプリを展開する。   </li>
<li>  既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 アプリを最大に最新のものにするために役立つガイダンスを提供します。  </li>
<li>  Configuration Manager を Intune にクラウドで接続するか、Intune スタンドアロンを展開 (必要な場合) ことによって最新の管理を有効にするためのガイダンスを提供します。  </li>
</ul>
  <strong>次の範囲外である </strong>  
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
<li>  ソース OS: Windows 7 Enterpriseまたは Professional、Windows 8.1 Enterprise または Professional。  </li>
<li>  デバイス: デスクトップ、ノートブック、またはタブレットのフォーム ファクター。  </li>
<li>  ターゲット OS: Window 10 Enterprise。  </li>
</ul>
インフラストラクチャのアップグレードの場合には、次の要件を満たす必要があります。
<ul>
<li>  Microsoft Endpoint Configuration Manager。  </li>
<li>  Configuration Manager バージョンは、Windows 10 のターゲット バージョンでサポートされている必要があります。 詳細については、Configuration Manager の Windows <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">10 サポートに関する Configuration Manager のサポート テーブルを参照してください</a>。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) は、エンタープライズ ネットワークで高度な脅威を回避、検出、調査、対策する際に役立つように設計されたプラットフォームです。  
  次の機能に関するリモート ガイダンスを提供します。
<ul>
<li>  エンドポイントをセキュリティで保護するためのテクノロジを展開する。  </li>
<li>  Endpoint Protection とデバイスの制限プロファイルを構成する。  </li>
<li>  OS のバージョンとデバイス管理 (Intune、Microsoft Endpoint Configuration Manager、グループ ポリシー オブジェクト (GPO)、サード パーティの構成を含む) の評価と、Windows Defender AV サービスやその他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  Windows AV サービスまたはその他のエンドポイント セキュリティ ソフトウェアの状態を評価します。  </li>
<li>  ネットワーク トラフィックを制限するプロキシとファイアウォールの評価。  </li>
<li>  オンボード エンドポイントを使用して ATP エージェント プロファイルを展開する方法を説明して、Microsoft Defender ATP サービスを有効にします。  </li>
<li>  展開のガイダンス、構成サポート、教育機関:
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
<li>  シミュレーションとチュートリアル (プラクティスのシナリオ、偽のマルウェア、自動調査など) を確認する。  </li>
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
  Windows Server 半期チャネル (SAC) バージョン 1803。  
  </li>
<li>  
  macOS バージョン 10.13、10.14、および 10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注:</strong> Windows Server のすべてのバージョンは、System Center Configuration Manager 2012 (バージョン 1012 R2、1511、1602 のバージョン) または Microsoft Endpoint Configuration Manager (バージョン 2002 以降) の最新バージョンで管理する必要があります。 

</li>
</ul>

<strong>次の範囲外である </strong>  
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
<li>  サーバー オンボーディングと構成:
<ul>
<li>  
  オフライン通信のプロキシ サーバーの構成。  
  </li>
<li>  
  Configuration Manager の下位レベルのインスタンスおよびバージョンでの Configuration Manager の展開パッケージの構成。  
  </li>
<li>  
  Azure Security Center へのサーバーのオンボーディング。  
  </li>
<li>  
  Configuration Manager で管理されていないサーバー。  
  </li>
</ul></li>
<li>  macOS オンボーディングと構成:
<ul>
<li>  
  Intune ベースの手動による展開。  
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
  アプリ コントロール。  
  </li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  ネットワーク ファイアウォール。  
  </li>
</ul></li>
<li>  Microsoft 脅威エキスパートの登録または構成。  </li>
<li>  構成またはトレーニング中に API またはセキュリティ情報とイベント管理 (SIEM) 接続を確認します。  </li>
<li>  Microsoft 脅威保護 (MTP) の登録または構成。  </li>
<li>  高度な検出に関するトレーニングまたはガイダンス。  </li>
<li>  Kusto クエリの使用または作成について説明するトレーニングまたはガイダンスです。</li>
</li>
</ul>
これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。  
</ul></td>
<td></td>

</tbody>
</table>
