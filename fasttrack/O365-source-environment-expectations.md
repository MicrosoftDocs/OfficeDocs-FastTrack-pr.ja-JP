---
title: ソース環境要件
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 533063e2-2630-46f3-9a88-ad07bb7dac9a
description: FastTrack Center 特典は、ソース環境との統合のレベルを設定するためのガイダンスを提供します (たとえば、Office 365 に移動するソース環境内に既にサービスが含まれている場合)。
ms.openlocfilehash: 6dfb952b85d26efcfee9b8dc5d6cd4c68a5fe0cd
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353634"
---
# <a name="source-environment-expectations"></a>ソース環境要件

FastTrack Center 特典は、ソース環境との統合のレベルを設定するためのガイダンスを提供します (たとえば、Office 365 に移動するソース環境内に既にサービスが含まれている場合)。
  
> [!NOTE]
> 統合が必要な場合、お使いのソース環境が対象のアプリケーションに必要な最低要件を満たしている必要があります。 
  
次の表に、オンボーディングで既存のソース環境に必要とされる要件を示します。\*

|**アクティビティ**|**ソース環境要件**|
|:-----|:-----|
|**コア オンボーディング** | 以下のフォレスト構成で、機能フォレスト レベルが Windows Server 2003 以降に設定された Active Directory フォレスト。  <br/>      1 つの Active Directory フォレスト。  <br/>    単一の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    <br/>  複数の Active Directory アカウント フォレストとリソース フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせ。あるいは 4 つのうちいずれか 1 つ) のトポロジ。    <br/>  複数の Active Directory アカウント フォレストで、そのうちの 1 つが一元化された Active Directory アカウント フォレスト (Exchange と、Lync 2010、Lync 2013、Skype for Business のいずれかとの組み合わせか、4 つのうちいずれか 1 つが含まれる)。  <br/>  複数の Active Directory アカウント フォレストで、それぞれに独自の Exchange 組織が含まれるフォレスト。 <br/> <br/> **メモ**  *複数のフォレストの Active Directory シナリオの場合、Lync 2010、Lync 2013、または Skype for Business が展開されるときには、Exchange と同じ Active Directory フォレスト内に展開する必要があります。*   <br/>  <br/>      **メモ**  *複数の Exchange 組織を持つ複数の ActiveDirectory フォレストを Exchange マルチ ハイブリッド構成で実装する場合、ソース フォレスト間で共有されているユーザー プリンシパル名 (UPN) の名前空間はサポートされません。Exchange 組織間のプライマリ SMTP 名前空間も分離する必要があります。詳細については、「[複数の Active Directory フォレストを伴うハイブリッド展開](https://go.microsoft.com/fwlink/?linkid=845444)」を参照してください。*     <br/>   <br/>   **メモ**  *フォレストが複数あるすべての構成において、AD FS の展開は FastTrack Center 特典の対象外です。*           |
|**Exchange Online オンボーディング** | お使いの環境では、最低レベルとして、次のいずれかが必要です。  <br/>  Exchange Server 2003 以降を導入している 1 つまたは複数の Exchange 組織。  <br/>  1 つの IBM Domino 7.0.3 以降の環境 ([付録 A - IBM Domino から Exchange Online への移行](O365-from-ibm-domino-to-exchange-online.md))。  <br/>  1 つのインターネット メッセージ アクセス プロトコル (IMAP) 対応のメール環境。  <br/>  単一の G Suite 環境 (Gmail、連絡先、カレンダーのみ)。  <br/>  1 つの Novell GroupWise 7.0.4 以降の環境。  <br/><br/> **メモ**  *複数地域機能の詳細については、「[Exchange オンラインで複数の地域の機能](https://go.microsoft.com/fwlink/?linkid=872776)」を参照してください。*           |
|**Sharepoint Online と OneDrive for Business オンボーディング**  | **SharePoint ハイブリッド**  <br/>  SharePoint ハイブリッド構成には、オンプレミスから単一のターゲット SharePoint Online 環境に接続するハイブリッドの検索、サイト、分類、コンテンツ タイプ、OneDrive for Business、拡張アプリ起動ツール、エクストラネット サイト、セルフサービス サイト作成のための構成が含まれています。SharePoint ハイブリッドを有効にするには、次に示す SharePoint Server オンプレミス環境のいずれか 1 つを所有している必要があります。  <br/> <br/> ***SharePoint Server 2013***  <br/>  2017 年 6 月のハイブリッド コンテンツ タイプ用のパブリック更新プログラム (PU)。詳細については、「[ハイブリッド SharePoint 分類とハイブリッド コンテンツ タイプを構成する](https://go.microsoft.com/fwlink/?linkid=853547)」を参照してください。<br/>  セルフサービス サイト作成の構成が必要な場合は、2017 年 3 月の PU。ハイブリッド セルフサービス サイトの作成は、SharePoint Server 2013 でのみサポートされています。詳細については、「 [ハイブリッド セルフサービス サイト作成](https://go.microsoft.com/fwlink/?linkid=846015)」を参照してください。  <br/>  ハイブリッド分類を備えた 2016 年 11 月公開の PU 以降。詳細については、「[ハイブリッド SharePoint 分類の計画](https://go.microsoft.com/fwlink/?linkid=844867)」を参照してください。<br/>  他のすべてのハイブリッド構成のシナリオの場合は、2016 年 7 月公開の PU 以降。  <br/><br/> **メモ**  *SharePoint Server 2013 ハイブリッド シナリオは、SharePoint Server 2013 でのみサポートされています。これらのシナリオは、SharePoint Foundation 2013 ではサポートされていません。*  <br/>   <br/>    ***SharePoint Server 2016***  <br/>  2017 年 6 月のハイブリッド コンテンツ タイプ用の PU。詳細については、「[ハイブリッド SharePoint 分類とハイブリッド コンテンツ タイプを構成する](https://go.microsoft.com/fwlink/?linkid=853547)」を参照してください。<br/>  ハイブリッド分類を備えた 2016 年 11 月公開の PU (Feature Pack 1)。詳細については、「[ハイブリッド SharePoint 分類の計画](https://go.microsoft.com/fwlink/?linkid=844867)」を参照してください。<br/>  他のすべてのハイブリッド構成のシナリオの場合は、2016 年 7 月公開の PU 以降。  <br/><br/> **メモ**  *オンプレミス SharePoint 環境の SharePoint Server 2013 または SharePoint Server 2016 へのアップグレードは、FastTrack Center 特典では提供されていません。詳細については、「[SharePoint ハイブリッド機能のパブリック更新プログラムの最小レベル](https://go.microsoft.com/fwlink/?linkid=853548)」を参照してください。*   <br/><br/>        **メモ**  *複数地域機能の詳細については、「[OneDrive の複数地域機能および Office 365 の SharePoint Online](https://go.microsoft.com/fwlink/?linkid=831056)」を参照してください。*           |
|**Skype for Business Online オンボーディング**  | **ネットワーク評価**  <br/>  ポートとエンドポイントの確認。  <br/>  接続品質の確認。  <br/>  帯域幅の推定値。  <br/><br/>  **Lync ハイブリッド**  <br/>  1 つのオンプレミスの Active Directory フォレスト。  <br/>  Lync 2010 Server 環境と、Lync 2013 2013 管理ツールまたは Skype for Business 2015 管理ツール、および Lync 2010 エッジ サーバーの役割。  <br/>  Lync 2013 Server 環境と Lync 2013 エッジ サーバーの役割。  <br/><br/>  **Skype for Business Online ハイブリッド**  <br/>  1 つのオンプレミスの Active Directory フォレスト。  <br/>  1 つの Active Directory アカウント フォレスト以降とリソース フォレスト (Exchange と Skype for Business の一方または両方) のトポロジ。  <br/>  複数の Active Directory アカウント フォレスト、および一元化された Active Directory アカウント フォレストで、その中に Exchange と Skype for Business の一方または両方がある 1 つのフォレスト。  <br/>  Skype for Business エッジ サーバーの役割を含む Skype for Business Server 2015 環境。  <br/><br/> **メモ**  *この追加のサービスは分割ドメイン (ハイブリッド) タスクの構成と検証のためのものであり、オンプレミスのコンポーネント (たとえば、Lync 2013 管理ツールや Lync 2013/Skype for Business Online サーバー、Lync 2010、Lync 2013、または Skype for Business エッジ サーバー) の導入は含まれていません。*    <br/><br/>        **会議室デバイス**  <br/>  [Skype for Business ソリューション カタログ](https://go.microsoft.com/fwlink/?LinkId=615775) の [Meeting Room Systems (会議室システム)] タブに一覧表示されている、サポート対象会議室デバイスに必要なオンライン アカウントの作成。  <br/><br/>  **電話会議を有効にする**  <br/>  会議ブリッジの既定の設定のための組織のセットアップ。  <br/>  ライセンスを持つユーザーへの会議ブリッジの割り当て。  <br/><br/>  **電話システムおよび通話プランのガイダンスを有効にする (米国のみ)**  <br/>  Cloud Voice の既定の設定のための組織のセットアップ。  <br/>  ライセンスを持つユーザーへの番号の割り当て。  <br/>  ユーザー インターフェイス (UI) を通じた 999 件までの電話番号の移植ガイダンス。  <br/>  999 件を超える電話番号の移植サービス リクエスト (SR) サポート。  <br/><br/>  **Skype for Business 会議メディアのガイダンス オンボーディングを有効にする**  <br/>  会議メディア サービスとのフェデレーションのための組織のセットアップ。   |
|**Microsoft Teams オンボーディング**  | Office 365 の Azure Active Directory で ID が有効になっている。  <br/>  SharePoint Online に対してユーザーが有効になっている。  <br/>  Exchange メールボックスがある (Exchange ハイブリッド構成でオンラインまたはオンプレミス、あるいはその両方)。  <br/>  Office 365 グループに対して有効になっている。  <br/><br/> **メモ**  *SharePoint Online ライセンスがユーザーに割り当てられておらず、有効でないと、Office 365 の OneDrive for Business ストレージは与えられません。ファイル共有はチャネル内で引き続き機能しますが、ユーザーは Office 365 の OneDrive for Business ストレージがないとチャットでファイルを共有できません。Microsoft Teams は SharePoint 社内展開をサポートしていません。*   <br/> <br/>       **メモ**  *すべてのユーザーがメールボックスを ExchangeOnline のホームに設定するのが理想的な状態です。メールボックスがオンプレミスでホームに設定されているユーザーは、Azure Active Directory Connect を介して ID を Office 365 ディレクトリと同期させる必要があります。これら Exchange ハイブリッドのお客様について、ユーザーのメールボックスがオンプレミスの場合、ユーザーはコネクタを追加することも構成することもできません。*          |
|**Microsoft StaffHub オンボーディング**  | Office 365 の Azure Active Directory で ID が有効になっている。  <br/><br/> **メモ**  *Microsoft StaffHub は既定で有効になっています。*           |
| **サービス オンボーディング**。次が含まれます。  <br/>  *Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive for Business  <br/>  Skype for Business Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*   |Project for Office 365、Outlook クライアント、OneDrive for Business 同期クライアント、Power BI Desktop、Skype for Business などのオンライン クライアント ソフトウェアは、「[Office のシステム要件](https://go.microsoft.com/fwlink/?LinkID=723597)」で定義されている最小レベルを満たしていなければなりません。  <br/> Microsoft Teams Windows と Mac デスクトップ クライアントのインストーラーは、[https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411) からダウンロードできます。   |
   
\*Office 365 US Government のソース環境要件については、「[Office 365 US Government のソース環境要件](US-Gov-appendix-source-environment-expectations.md)」を参照してください。
  

