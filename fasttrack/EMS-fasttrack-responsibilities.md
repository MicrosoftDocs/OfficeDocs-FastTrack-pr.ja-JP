---
title: FastTrack の責任範囲
description: お客様が EMS 向け FastTrack センター特典を使用している場合の FastTrack の責任範囲
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 11/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 65be29729f38b3007399b05b495b56f641680878
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921103"
---
# <a name="fasttrack-responsibilities"></a>FastTrack の責任範囲

FastTrack には、オンボーディング中に以下の責任があります。

## <a name="general"></a>全般

-   必要な構成アクティビティのための遠隔サポートの提供。その内容については、フェーズの詳細な説明で詳述しています。

-   構成タスクを減らしたり省略したりするための、利用可能な説明書やソフトウェア ツール、管理コンソール、スクリプトを提供します。

## <a name="initiate-phase"></a>開始フェーズ

-   お客様と連携してオンボーディングを開始します。

-   オンボーディングする対象のサービスを選定します。

## <a name="assess-phase"></a>評価フェーズ

-   管理上の概要を示します。

-   次の点に関するガイダンスを行います。

    -   DNS、ネットワーク、およびインフラストラクチャのニーズ。

    -   クライアントのニーズ (インターネット ブラウザー、クライアント オペレーティング システム、およびサービスのニーズ)。

    -   ユーザー ID およびプロビジョニング

    -   購入済みの、オンボーディングの一部として規定されている対象サービスの有効化。

-   修復アクティビティのタイムラインの設定。

-   Intune、Azure AD Premium の両方に関する修復チェックリストの提供。

## <a name="remediate-phase"></a>修復フェーズ

-   同意済みのスケジュールに従って電話会議を行い、修復アクティビティの進捗状況を確認します。たとえば、Microsoft クラウド サービスのオンボーディングに先立つインストールの前提条件のガイダンスなどを提供します。

## <a name="enable-phase"></a>有効化フェーズ
次の点に関するガイダンスを行います。

-   Microsoft オンライン サービスのテナントまたはサブスクリプションのライセンス認証。

-   TCP/IP プロトコルとファイアウォール ポートの構成。

-   対象サービスの DNS の構成。

-   Microsoft オンライン サービスへの接続の検証。

-   フォレスト環境が 1 つの場合:

    -   Active Directory Domain Services (AD DS) と対象の Microsoft オンライン サービスとの間へのディレクトリ同期サーバーの設置 (必要な場合は、ガイダンスのみ提供)。

    -   Azure Active Directory Connect ツールを使用した、管理対象の認証 (パスワード ハッシュの同期またはパススルー認証) の構成。 (必要な場合は、ガイダンスのみ提供)。

        > [!NOTE]
        > カスタム ルール拡張機能の開発と実装は対象外です。

-   フォレストが 1 つで、対象がフェデレーション ID の場合: 単一サイトのフォールト トレラント構成における Intune を使用したローカル ドメイン認証用の、 Active Directory フェデレーション サービス (AD FS) のインストールおよび構成 (必要な場合)。

    > [!NOTE]
    > フォレストが複数あるすべての構成において、ADFS の展開は対象外です。

-   シングル サインオン (SSO) 機能のテスト (展開されている場合)。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>有効化フェーズ - Microsoft Azure Active Directory Premium

次の点に関するガイダンスを行います。

- Azure AD Premium テナントのアクティブ化。

- ファイアウォール ポートの構成。

- 対象サービスの DNS の構成。

- Azure AD Premium サービスへの接続の検証。

- フォレスト環境が 1 つの場合:

  -   Active Directory Domain Services (AD DS) と Azure AD Connect との間へのディレクトリ同期の設置 (必要な場合)。

  -   Azure AD Connect ツールを使用した、認証方法 (パスワード ハッシュの同期またはパススルー認証) の構成。

- フォレスト環境が複数の場合:

  -   Azure AD Connect の同期のインストール、複数のフォレスト シナリオ用の設定。
- 単一フォレスト環境および複数フォレスト環境:
  - Azure Active Directory パススルー認証の構成 (必要な場合)。
  - Azure Active Directory シームレス シングル サインオン (SSO) の構成 (必要な場合)。
    > [!NOTE]
    > 複数フォレスト環境の Azure Active Directory パススルー認証は、Active Directory フォレスト間にフォレストの信頼があり、名前サフィックスのルーティングが正しく構成されている場合にサポートされます。 追加のエージェントは、サインイン要求の高可用性を提供するために、複数のオンプレミスのサーバーにインストールできます。

  - 詳細については、「[Azure Active Directory パススルー認証:クイック スタート](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)」および「[Azure Active Directory シームレス シングル サインオン:クイック スタート](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)」を参照してください。
  - パススルー認証の制限の詳細については、「[Azure Active Directory パススルー認証: 現在の制限事項](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)」を参照してください。
  - SSO の問題の詳細については、「[Azure Active Directory シームレス シングル サインオンのトラブルシューティングを行う](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)」を参照してください。

      > [!NOTE]
      > パスワード ハッシュの同期およびパスワード ライトバックは複数のフォレストをサポートします。 ただし、その他のライトバックのシナリオはサポートされていません。

  - オンプレミスの Active Directory フォレストと Microsoft Azure Active Directory Premium ディレクトリ (Azure Active Directory) との間の同期の構成。

    > [!NOTE]
    > カスタム ルール拡張機能の開発と実装は対象外です。

- フォレストが 1 つで、対象がフェデレーション ID の場合:

  -   1 つのサイトのフォールト トレラント構成における、 Azure AD Premium を使用した、ローカル ドメイン認証用の AD FS のインストールと構成 (必要な場合)。

  > [!NOTE]
  > フォレストが複数あるすべての構成において、ADFS の展開は対象外です。

- SSO 機能のテスト (展開されている場合)。

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>有効化フェーズ - Azure Ad Connect - Azure AD Connect および AD FS を使用

セットアップに関するガイダンスを行います。

- ライセンス認証を含むユーザー プロビジョニング。

- Azure AD Connect ディレクトリ同期 (パスワード ライトバックおよびパスワード ハッシュ同期を使用)。

  - Azure Active Directory セルフサービスによるパスワードのリセット (SSPR)。

  - Azure Multi-Factor Authentication。

  - 最大 3 つ (またはそれ以上) のサービスとしてのソフトウェア (SaaS) アプリケーションの、[Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/) からのシングル サインオン (SSO) との統合。

  - 「[アプリ統合に関するチュートリアルのリスト](https://docs.microsoft.com/ja-JP/azure/active-directory/saas-apps/tutorial-list)」に記載される、事前統合された SaaS アプリケーションでの自動ユーザープロビジョニン (外向きプロビジョニングのみに制限されています)。

  - ロゴ、テキスト、画像などを含む、カスタマイズされたログオン画面。

  - セルフサービスと動的グループ (グループ)。

  - Azure Active Directory アプリケーション プロキシ。

  - Azure Active Directory Connect Health。

  - Azure Active Directory の条件付きアクセス。

  - Azure Active Directory の利用規約。

  - Azure Active Directory Identity Protection。

  - Azure Active Directory Privileged Identity Management。

  - Azure Active Directory アクセス レビュー。

### <a name="enable-phase---intune"></a>有効化フェーズ - Intune

> [!IMPORTANT]
> FastTrack では、Intune を使用した Windows 10 の従来の PC 管理をサポートしていません。 FastTrack では、Intune モバイル デバイス管理 (MDM) を経由する Windows 10 の管理のみがサポートされます。

次のような内容のガイダンスを提供します。

-   オンプレミスの Active Directory またはクラウド ID (Azure Active Directory) を利用した、Intune で使用する ID の構成。

-   エンド ユーザーのライセンス認証。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。

-   管理ニーズに応じた、以下を含むモバイル デバイス管理 (MDM) 機関の構成。

    -   Intune を MDM 機関として設定。

    -   MDM 管理ポリシーの検証に使用するテストグループの構成。

    -   ユーザーとデバイスに関する情報を見つけるための、Intune 管理 ポータル内の移動。

    -   Intune の役割 (ヘルプ デスク オペレーター、管理者など) のセットアップ。

    -   以下のような、MDM 管理ポリシーとサービスの構成:

        -   Web リンク、MSI、および/またはディープ リンクを介した、サポートされている各プラットフォームでのアプリの展開。

        -   Windows 10 デバイス上での Office ProPlus の展開。

        -   アプリ展開用のボリューム購入プログラム (Apple の VPP、企業向け Windows ストア、Google の Play for Work ストアなどを含む)。

        -   組織に既存の証明機関や Wi-Fi または VPN インフラストラクチャがある場合の、メール、ワイヤレス ネットワーク、および VPN プロファイルの展開。

        -   Microsoft Intune Exchange Connector のセットアップ (該当する場合)。

        -   サポートされているデバイス プラットフォームでのデバイス構成プロファイル。

    -   条件付きアクセス ポリシーのセットアップ。

    -   サポートされている各プラットフォームでの Intune アプリ保護ポリシーの構成および展開。

    -   Intune アプリ保護ポリシー用の基幹業務 (LOB) アプリの準備、および利用可能なオプションについてのガイダンス。

    -   Microsoft Intune サービスを使用した、サポートされている各プラットフォームのデバイスの Intune または Configuration Manager への登録。

    -   Intune データ ウェアハウスへの接続。

    -   以下との Intune の統合:
        -   リモート アシスタンス用の Team Viewer (Team Viewer のサブスクリプションが必要です)。

        -   Mobile Threat Defense パートナー ソリューション (Mobile Threat Defense パートナー ソリューションのサブスクリプションが必要です)。

        -   通信経費の管理ソリューション (通信経費の管理ソリューションのサブスクリプションが必要です)。

        -   Windows Defender Advanced Threat Protection (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。

    -   該当するサポート対象プラットフォームでのソフトウェア更新プログラムの構成。

    -   ユーザー導入計画のリソース。

- Windows Autopilot のセットアップ:

    - Windows Autopilot での Microsoft Intune のセットアップおよび構成。

    - Azure AD の動的グループの構成

    - Azure AD への会社のブランドの追加。

    - Windows Autopilot プロファイルでのデバイスの作成と割り当て (例: ローカル管理者アカウントの作成を制限する Windows Autopilot プロファイル)。

    - 組織の要件に準拠するための、Out-of-box-experience (OOBE) のカスタマイズ。

    - Azure AD および Intune での MDM 自動登録の構成。

    > [!NOTE]
    > Intune 以外での Windows Autopilot のセットアップは、FastTrack 特典の対象外です。

### <a name="enable-phase---co-management"></a>有効化フェーズ - 共同管理

次のような内容のガイダンスを提供します。

-   エンド ユーザーのライセンス認証。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成 (Intune がインストールされていない場合)。

-   MDM 自動登録のための Azure Active Directory のセットアップ。

-   ハイブリッド Azure Active Directory 参加のセットアッップ。

-   クラウド管理ゲートウェイのセットアップ。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、ユーザーおよびデバイス グループの作成。

-   Intune の準備 (Intune がインストールされていない場合):

    -   管理ニーズに応じた、以下を含むモバイル デバイス管理 (MDM) 機関の構成。

    -   Intune を MDM 機関として設定。

    -   MDM 管理ポリシーの検証に使用するテストグループの構成。

    -   ユーザーとデバイスに関する情報を見つけるための、Intune 管理 ポータル内の移動。

    -   Intune の役割 (ヘルプ デスク オペレーター、管理者など) のセットアップ。

    -   サポートされている各プラットフォームでの Intune アプリ保護ポリシーの構成および展開。

    -   Windows 10 デバイスの Intune への登録。

- Configuration Manager コンソールでの共同管理の有効化。

- ワークロードの Intune への切り替え。

- 環境内での共同管理アクティビティの監視。

### <a name="enable-phase--azure-information-protection"></a>有効化フェーズ - Azure Information Protection

以下に関するガイダンスを提供します。 

- 顧客テナントのアクティブ化と構成。

- ラベルおよびポリシーの作成と設定。

- ドキュメントへの情報保護の適用。 

- Windows で実行されている、Azure Information Protection クライアントを使用する Office アプリ (Word、PowerPoint、Excel、Outlook など) の自動分類およびラベル付け。

- Azure Information Protection スキャナーを使用した、保管中ファイルの使用。

- Exchange Online のメール フロー ルールを使用した、転送中メールの監視。

Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、およびデータ損失防止 (DLP) を使用して保護を適用するお客様にもガイダンスを提供いたします。

> [!NOTE]
> **詳細な情報をご希望の場合は**、[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility) をご覧ください。

## <a name="next-steps"></a>次の手順

[EMS 向けの FastTrack 特典 - ユーザーの責任範囲](EMS-your-responsibilities.md)
