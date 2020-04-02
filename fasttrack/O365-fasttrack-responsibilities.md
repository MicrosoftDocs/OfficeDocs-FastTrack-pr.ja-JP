---
title: FastTrack の責任範囲
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack スペシャリストには、オンボーディング中に以下の責任があります。
ms.openlocfilehash: 7e004a3cefd54c997e7a5ad8ad831fecc22e0945
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098279"
---
# <a name="fasttrack-responsibilities"></a>FastTrack の責任範囲

FastTrack スペシャリストには、オンボーディング中に以下の責任があります。\*
  
## <a name="general"></a>全般

- 達成計画の開発と実装、必要な構成アクティビティのための遠隔サポート アシスタンスを提供します。その内容については、各フェーズの説明で詳述しています。
- お客様が構成タスクを削減または省略して、リソースの計画を成功できるようガイダンスを提供するため、入手可能な説明書、ソフトウェア ツール、管理コンソール、スクリプトを提供します。 
    
## <a name="initiate-phase"></a>開始フェーズ

- お客様と連携して、お客様の意向、組織の目標、サービスの使用計画を理解します。
- Office 365 コラボレーション サービス (Microsoft Teams など) を使用してお客様と連携し、オンボーディングを開始します。   
- オンボーディングする対象のサービスを選定します。 
    
## <a name="assess-phase"></a>評価フェーズ

- 達成計画に関する電話会議を行い、ユーザーによる効果的な採用のためのガイダンスを提供します。  
- 管理上の概要を示します。
- 次の点に関するガイダンスを行います。 
  - ドメイン ネーム システム (DNS)、ネットワークおよびインフラストラクチャのニーズ。
  - クライアントのニーズ (インターネット ブラウザー、クライアント オペレーティング システム、モバイル デバイス、サービスのニーズ)。
  - ユーザー ID およびプロビジョニング
  - 購入済みでオンボーディングの一部として定義されている対象サービスの有効化。 
  - 正常なサービス採用の促進と価値の増進。  
- 修復アクティビティのタイムラインの設定。
- 修復チェックリストの提供。 
- 既存の SharePoint Server 2013 または SharePoint Server 2016 インフラストラクチャの評価。以下が含まれます。
  - SharePoint Online ハイブリッドの前提条件。 
  - オンプレミスのインフラストラクチャの SharePoint Online ハイブリッド機能の準備状況。
  - 必要な SharePoint Online エンドポイントへのアクセス。
  - OneDrive for Business ハイブリッドの対象ユーザー。 
- 既存の Lync、Skype for Business Online、Microsoft Teams のいずれかのインフラストラクチャの評価。以下が含まれます。
  - サポートされる Skype for Business クライアントまたは Teams クライアントの展開の戦略。
  - エンドポイントへのアクセス。
  - 接続品質。
  - 帯域幅の推定値。
  - 分割ドメイン サーバー構成をサポートする前提条件。
  - Skype for Business Online または Teams に移行するための特定のユーザーの前提条件。
- メッセージング インフラストラクチャの評価。次の内容を含みます。 
  - メール フローとルーティングの全体的な原則。
  - クライアント アクセス (既存の公開済みクライアント アクセス エンドポイントを含む)。
  - 統合のニーズに照らしたソース メッセージング環境。
- FastTrack センターのデータ移行サービスを使用し、かつ資格を満たす場合は、データ移行を提供します。
    
## <a name="remediate-phase"></a>修復フェーズ

- 修復アクティビティと達成計画の進捗状況を確認するために、あらかじめ合意したスケジュールに従って電話会議を行います。 
- 評価ツールを実行することにより、問題を識別して修復し、結果を解釈する方法を示します。
    
## <a name="enable-phase"></a>有効化フェーズ

次の点に関するガイダンスを行います。 
- 達成計画の進捗状況を評価し、必要なサポートを判断します。
- Office 365 テナントのアクティブ化。  
- TCP/IP プロトコルとファイアウォール ポートの構成。
- 対象サービスの DNS の構成。 
- Office 365 への接続の検証。
- Azure Active Directory と、社内の Active Directory の接続。
  - Active Directory ドメイン サービス (AD DS) と Office 365 との間のディレクトリ同期サーバーの設置 (必要な場合)。 
  - Azure Active Directory Connect ツールを使用した Office 365 (Azure Active Directory) へのパスワードの同期 (パスワード ハッシュ) の構成 (必要な場合)。
  - 単一フォレスト環境および複数フォレスト環境:
      - Azure Active Directory パススルー認証の構成 (必要な場合)。\*\*
      - Azure Active Directory シームレス シングル サインオン (SSO) の構成 (必要な場合)。\*\*\*
    > [!NOTE]
    > 複数フォレスト環境の Azure Active Directory パススルー認証は、Active Directory フォレスト間にフォレストの信頼があり、名前サフィックスのルーティングが正しく構成されている場合にサポートされます。追加のエージェントは、サインイン要求の高可用性を提供するために、複数のオンプレミスのサーバーにインストールできます。詳細については、「[Azure Active Directory パススルー認証:クイック スタート](https://go.microsoft.com/fwlink/?linkid=860094)」および「[Azure Active Directory シームレス シングル サインオン:クイック スタート](https://go.microsoft.com/fwlink/?linkid=860095)」を参照してください。 
- フォレストが 1 つで、フェデレーション ID を対象とする場合: 
  - 1 つのサイトのフォールト トレラント構成における Office 365 を使うローカル ドメイン認証用の AD FS のインストールと構成 (必要な場合)。
  - AD FS インフラストラクチャをインターネットに公開するための、WAP のインストールおよび構成 (必要な場合)。
    > [!NOTE]
    > フォレストが複数あるすべての構成において、ADFS の展開は対象外です。 
- シームレスな SSO 機能のテスト (展開されている場合)。
- 正常なサービス採用の促進と価値の増進。
    
\*\*パススルー認証の制限の詳細については、「[Azure Active Directory パススルー認証: 現在の制限事項](https://go.microsoft.com/fwlink/?linkid=860356)」を参照してください。 

\*\*\*シームレス SSO の問題の詳細については、「[Azure Active Directory シームレス シングル サインオンのトラブルシューティングを行う](https://go.microsoft.com/fwlink/?linkid=841926)」を参照してください。

## <a name="exchange-online"></a>Exchange Online

次の点に関するガイダンスを行います。
- DNS レコードの作成または更新。 
- ソース メッセージング システムと Office 365 環境との間での電子メール ルーティングの有効化。 
- Exchange Online Protection、データ損失防止 (DLP)、Office 365 Message Encryption (OME)、Office 365 Advanced Threat Protection (ATP) (サブスクリプションで利用できる場合) を構成して、メールが有効な検証済みのすべてのドメインで MX レコードが Office 365 をポイントしていることを確認します。
- 1 つのオンプレミスの Exchange 組織と Office 365 の間、*または*複数のオンプレミスの Exchange 組織と Office 365 の間におけるハイブリッド セットアップの構成。 
- メールボックス クライアント (Outlook for Windows、Outlook on the web、iOS および Android 用の Outlook) の構成。
- Office 365 ATP の自動化、調査、応答を構成する (サブスクリプションで使用可能な場合)。
    
データ移行の責任について詳しくは、「[データ移行](O365-data-migration.md)」を参照してください。
  
## <a name="microsoft-teams"></a>Microsoft Teams

次の点に関するガイダンスを行います。
- 最小要件の確認。
- ファイアウォール ポートの構成。
- DNS の設定。  
- Teams が Office 365 テナントで有効であることの確認。
- ユーザーのライセンスの有効化と無効化。
- Teams クライアントの配布。
- IT Pro および管理機能。
- コア製品の機能。
- カスタマー サクセスのテンプレート。
- サポートされる会議システム デバイスに関連付けるアカウントの作成 (最大 10 個のアカウント)。 
- 直接ルーティングの有効化。
- 電話会議の有効化。
- 会議ブリッジの既定の設定のための組織のセットアップ。
- ライセンスを持つユーザーへの会議ブリッジの割り当て。
- 電話システムの有効化。
- 電話システムおよび通話プランのオンボーディングの有効化 (利用可能なマーケットのみ)。
- ライセンスを持つユーザーへの番号の割り当て。
- UI を通じた 999 件までの電話番号の移植ガイダンス。
- 999 件を超える電話番号の移植 SR サポート。 
- Teams ライブ イベントの有効化。 
- 組織のセットアップと Microsoft Stream への統合。

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

次の点に関するガイダンスを行います。
- 安全なリンクの有効化。
- 安全な添付ファイル機能の有効化。
- フィッシング詐欺対策ポリシーの有効化。
- 自動化、調査、応答の構成。
- 攻撃シミュレータの使用。
- レポート作成と脅威分析。

## <a name="office-365-proplus"></a>Office 365 ProPlus

次の点に関するガイダンスを行います。
- 展開の問題への対応。
- [Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)と Windows PowerShell を使用したエンドユーザー ライセンスとデバイスベース ライセンスの割り当て。
- クイック実行を使用した Office 365 ポータルからの Office 365 ProPlus のインストール。
- iOS、Android、または Windows Mobile デバイスへの Office Mobile アプリ (iOS および Android 用の Outlook、Word Mobile、Excel Mobile、PowerPoint Mobile など) のインストール。 
- Office 365 展開ツールを使用した更新設定の構成。
- ローカルまたはクラウドのインストールの選択とセットアップ。
- Office カスタマイズ ツールを使用した Office 展開ツールの構成 XML、または展開パッケージを構成するためのネイティブ XML の作成。
- Microsoft Endpoint Configuration Manager パッケージの作成サポートを含む、Microsoft Endpoint Configuration Manager を使用した展開。
    
## <a name="onedrive-for-business"></a>OneDrive for Business

次の点に関するガイダンスを行います。
- オンプレミスの SharePoint バージョンと統合オプションの識別。 
- 同期と ID オプションの識別。
- ロールアウト オプションの選択    
  - ジャストインタイム ロールアウト。
  - 段階的ロールアウト (順序付けとフェーズ)。
- OneDrive for Business 展開用のオンプレミスの環境の準備:
  - 正しい OneDrive for Business 同期クライアントの識別。
  - DNS、ネットワーク ポート、およびファイアウォールの構成。 
- エンドユーザー ライセンスの割り当て。 
- SharePoint Online 対象ユーザーのセットアップ、および OneDrive for Business を取得するユーザーの制御と管理。 
- OneDrive for Business 同期クライアントのデスクトップへの展開。   
- SharePoint Online ハイブリッド OneDrive for Business リダイレクトの構成方法 (SharePoint 2013 および SharePoint 2016 のみ)。
- FastTrack Center のデータ移行サービスを使っており、かつ資格を満たす場合は、データ移行。
    
## <a name="outlook-for-ios-and-android"></a>iOS および Android 用の Outlook

次の点に関するガイダンスを行います。
- iOS および Android デバイスへの Outlook のダウンロード。
- Outlook 内でのメール アカウントの構成。

## <a name="power-bi"></a>Power BI

次の点に関するガイダンスを行います。
- Power BI サブスクリプション プランの確認。 
- Power BI サービスの追加。 
- Power BI Desktop アプリのダウンロード。
    
## <a name="project-online"></a>Project Online

次の点に関するガイダンスを行います。
- サブスクリプション プランの確認。
- 基本的な SharePoint 機能の検証。
- Project Online サービスの追加。
- ERP 同期を含む、Project Online へのユーザーの追加。
- プロジェクト作成による、基本的な Project Online 機能の検証。
    
## <a name="project-online-professional-and-project-online-premium"></a>Project Online Professional および Project Online Premium

次の点に関するガイダンスを行います。
- 展開の問題への対応。
- [Microsoft 365 管理センター](https://go.microsoft.com/fwlink/?linkid=2032704)と Windows PowerShell を使用したエンドユーザー ライセンスの割り当て。
- ポータルからの Project Online デスクトップ クライアントのダウンロードとインストール。   
- Office 365 展開ツールまたはグループ ポリシー テンプレートを使用した更新設定の構成。
- Office 2016 展開ツールの configuration.xml ファイルを作成するためのガイダンスを含む Project Online デスクトップ クライアント 用の 1 つのオンサイト配布サーバーのセットアップ。 
- Project Online デスクトップ クライアント の Project Online への接続。

## <a name="sharepoint-online"></a>SharePoint Online

次の点に関するガイダンスを行います。
- ライセンシングを含むユーザー プロビジョニングのセットアップ。
- SharePoint Online 管理者のサイト作成の有効化。    
- サイト コレクションのプランニング。 
- コンテンツのセキュリティ保護および権限の管理。
- 個人用サイトおよびソーシャル機能の有効化。
- SharePoint Online 機能の構成。 
- FastTrack センターのデータ移行サービスを使用し、かつ資格を満たす場合は、データ移行を提供します。
- SharePoint Online ハイブリッドに必要なオンプレミスの SharePoint ファームのインフラストラクチャ構成を評価します。 
- 次に関してツールと自動化を使用します。
  - オンプレミスのクラウド検索サービス アプリケーションの構成。 
  - SharePoint オンプレミス環境とクラウド環境間の信頼の構成。
- SharePoint Online ハイブリッド機能の使用に向けたオンプレミスの SharePoint サイトの構成。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

次の点に関するガイダンスを行います。
- Office 365 向け Skype for Business 識別情報のプロビジョニング。 
- Office 365 のオンライン会議、インスタント メッセージング (IM)、プレゼンス機能の有効化。 
- サポートされる会議システム デバイスに関連付けるアカウントの作成 (最大 10 個のアカウント)。 
- Lync ハイブリッドまたは Skype for Business Online ハイブリッドのシナリオ (該当する場合) をサポートするための分割ドメイン サーバー環境の構成。
- 電話会議を有効にする:
  - 会議ブリッジの既定の設定のための組織のセットアップ。
  - ライセンスを持つユーザーへの会議ブリッジの割り当て。
- 電話システムを有効にする:
  - 電話システムおよび通話プランのオンボーディングの有効化 (利用可能なマーケットのみ)。
  - ライセンスを持つユーザーへの番号の割り当て。
  - UI を通じた 999 件までの電話番号の移植ガイダンス。
  - 999 件を超える電話番号の移植 SR サポート。
- Skype for Business 会議メディアトを有効にする:
  - Skype for Business 会議メディアのオンボーディング ガイダンスを有効にする。
  - 会議メディア サービスとのフェデレーションのための組織のセットアップ。
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

単一の Yammer ベーシック ネットワークから単一の Yammer エンタープライズ ネットワークへの変換に関するガイダンスを行います。
  
\*Office 365 US Government のための FastTrack でのお客様の責任については、「[Office 365 US Government のための FastTrack での責任](US-Gov-appendix-fasttrack-responsibilities.md)」を参照してください。
