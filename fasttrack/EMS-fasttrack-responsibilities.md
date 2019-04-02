---
title: FastTrack の責任範囲
description: ユーザーが EMS に対して fasttrack センターの特典を使用している場合の fasttrack の責任
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ca5de05adc154a6adb0119fd71de46280cb4cb23
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016913"
---
# <a name="fasttrack-responsibilities"></a>FastTrack の責任範囲

fasttrack には、オンボード時の次の責任があります。

## <a name="general"></a>全般

-   詳細なフェーズの説明に記載されている必要な構成アクティビティについて、リモートサポートのサポートを提供します。

-   構成タスクを削減または排除できるように、使用可能なドキュメント、ソフトウェアツール、管理コンソールを提供します。

## <a name="initiate-phase"></a>開始フェーズ

-   あなたと協力して、オンボードを開始します。

-   オンボーディングする対象のサービスを選定します。

## <a name="assess-phase"></a>評価フェーズ

-   管理上の概要を示します。

-   次の点に関するガイダンスを行います。

    -   DNS、ネットワーク、およびインフラストラクチャのニーズ。

    -   クライアントのニーズ (インターネットブラウザー、クライアントオペレーティングシステム、およびサービスのニーズ)。

    -   ユーザー ID およびプロビジョニング

    -   購入済みで、オンボードの一部として定義されている対象サービスの有効化。

-   修復アクティビティのタイムラインの設定。

-   Intune および Azure AD Premium の修復チェックリストを提供します。

## <a name="remediate-phase"></a>修復フェーズ

-   同意済みのスケジュールに従って電話会議を開催します。たとえば、修復アクティビティの進行状況を確認するには、「Microsoft cloud service の前に、インストールの前提条件」を参照してください。

## <a name="enable-phase"></a>有効化フェーズ
次の点に関するガイダンスを行います。

-   Microsoft online service のテナントまたはサブスクリプションをアクティブ化します。

-   TCP/IP プロトコルとファイアウォール ポートの構成。

-   対象サービスの DNS の構成。

-   Microsoft online services への接続を検証します。

-   単一フォレスト環境の場合:

    -   Active directory ドメインサービス (AD DS) と対象となる Microsoft online services の間にディレクトリ同期サーバーをインストールします (必要に応じて、ガイダンスのみ)。

    -   Azure Active Directory Connect ツールを使用して、管理された認証 (パスワードハッシュ同期またはパススルー認証) を構成します。 (必要な場合にのみガイダンス)。

        > [!NOTE]
        > カスタムルールの拡張機能の開発と実装が範囲外です。

-   単一のフォレストの場合: ターゲットがフェデレーション id の場合: 単一サイトのフォールトトレラント構成で、Intune を使用したローカルドメイン認証用の Active Directory フェデレーションサービス (AD FS) のインストールと構成 (必要な場合)。

    > [!NOTE]
    > 複数のフォレスト構成すべてにおいて、AD FS の展開は範囲外です。

-   シングルサインオン (SSO) 機能のテスト (展開されている場合)。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>有効化フェーズ-Microsoft Azure Active Directory Premium

次の点に関するガイダンスを行います。

- Azure AD Premium テナントをアクティブ化します。

- ファイアウォール ポートの構成。

- 対象サービスの DNS の構成。

- Azure AD Premium サービスへの接続を検証します。

- 単一フォレスト環境の場合:

  -   Active directory ドメインサービス (AD DS) と Azure AD Connect の間にディレクトリ同期をインストールする (必要な場合)。

  -   Azure AD Connect ツールを使用して、認証方法 (パスワードハッシュ同期またはパススルー認証) を構成します。

- 複数フォレスト環境の場合:

  -   Azure AD Connect の同期のインストール。複数のフォレストのシナリオ用にセットアップします。
- 単一フォレスト環境および複数フォレスト環境:
  - Azure Active Directory パススルー認証の構成 (必要な場合)。
  - Azure Active Directory シームレス シングル サインオン (SSO) の構成 (必要な場合)。
    > [!NOTE]
    > 複数フォレスト環境の Azure Active Directory パススルー認証は、Active Directory フォレスト間にフォレストの信頼があり、名前サフィックスのルーティングが正しく構成されている場合にサポートされます。 追加のエージェントは、サインイン要求の高可用性を提供するために、複数のオンプレミスのサーバーにインストールできます。

  - 詳細については、「[Azure Active Directory パススルー認証:クイック スタート](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)」および「[Azure Active Directory シームレス シングル サインオン:クイック スタート](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)」を参照してください。
  - パススルー認証の制限の詳細については、「[Azure Active Directory パススルー認証:現在の制限事項](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)」を参照してください。シームレス
  - SSO の問題の詳細については、「[Azure Active Directory シームレス シングル サインオンのトラブルシューティングを行う](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)」を参照してください。

      > [!NOTE]
      > パスワードのハッシュ同期とパスワードの書き戻しで複数のフォレストがサポートされます。 ただし、その他の書き戻しのシナリオはサポートされていません。

  - オンプレミスの active directory フォレストと Microsoft azure active directory Premium ディレクトリ (azure active directory) との間の同期を構成します。

    > [!NOTE]
    > カスタムルールの拡張機能の開発と実装が範囲外です。

- ターゲットがフェデレーション id の場合、単一のフォレストの場合:

  -   単一サイトのフォールトトレラント構成 (必要な場合) で、Azure ad Premium を使用して、ローカルドメイン認証用の AD FS をインストールおよび構成します。

  > [!NOTE]
  > 複数のフォレスト構成すべてにおいて、AD FS の展開は範囲外です。

- SSO 機能のテスト (展開されている場合)。

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>azure ad Connect と ad FS を使用して、フェーズを有効にします。 azure ad Premium

セットアップのガイダンスを提供します。

- ユーザープロビジョニング (ライセンスを含む)。

- Azure AD Connect ディレクトリ同期 (パスワードの書き戻しとパスワードハッシュ同期を使用)。

  - Azure Active Directory Self Service のパスワードのリセット (SSPR)。

  - Azure 多要素認証。

  - [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/)のシングルサインオン (SSO) を使用したサービス (SaaS) アプリケーションの統合として、最大3つ以上のソフトウェア。

  - [アプリ統合チュートリアルリスト](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)に記載されている事前に統合された SaaS アプリケーションの自動ユーザープロビジョニングのみ。送信プロビジョニングのみに制限されます。

  - カスタマイズされたログオン画面 (ロゴ、テキスト、画像など)。

  - セルフサービスおよび動的グループ (グループ)。

  - Azure Active Directory アプリケーションプロキシ。

  - Azure Active Directory Connect Health。

  - Azure Active Directory の条件付きアクセス。

  - Azure Active Directory の使用条件。

  - Azure Active Directory id 保護。

  - Azure Active Directory の特権 id 管理。

  - Azure Active Directory アクセスレビュー。

### <a name="enable-phase---intune"></a>有効化フェーズ-Intune

> [!IMPORTANT]
> fasttrack では、Intune を使用した Windows 10 クラシック PC 管理はサポートされていません。 fasttrack は、Intune モバイルデバイス管理 (MDM) による Windows 10 管理のみをサポートします。

以下に関する**ガイダンス**を提供します。

-   オンプレミスの Active directory またはクラウド id (Azure active directory) を活用することによって、Intune で使用される id を構成します。

-   エンドユーザーのライセンスを取得します。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、およびユーザーとデバイスグループの作成。

-   管理ニーズに応じて、以下のようなモバイルデバイス管理 MDM を構成します。

    -   MDM 権限として Intune を設定します。

    -   MDM 管理ポリシーの検証に使用するテストグループを構成する。

    -   Intune 管理ポータルを移動して、ユーザーとデバイスに関する情報を探します。

    -   Intune の役割の設定 (ヘルプデスクオペレーター、管理者など)

    -   MDM 管理ポリシーおよびサービスの構成は次のように行います。

        -   web リンク、MSI、またはディープリンクを介した、サポートされている各プラットフォームのアプリの展開。

        -   Windows 10 デバイスに Office ProPlus を展開します。

        -   アプリを展開するためのボリューム購入プログラム (Apple の VPP、ビジネス向けの Windows ストア、Google のワークストアの再生など)。

        -   組織内に既存の証明機関、wi-fi、または vpn インフラストラクチャがある場合、電子メール、ワイヤレスネットワーク、および vpn プロファイルを展開します。

        -   Microsoft Intune Exchange Connector のセットアップ (該当する場合)。

        -   サポートされているデバイスプラットフォームのデバイス構成プロファイル。

    -   条件付きアクセスポリシーを設定する。

    -   サポートされている各プラットフォームに対して Intune アプリ保護ポリシーを構成および展開します。

    -   利用可能なオプションに関するガイダンスを使用して、Intune アプリ保護ポリシー用の基幹業務 (LOB) アプリを準備します。

    -   Microsoft intune サービスを使用して、サポートされている各プラットフォームのデバイスを intune または Configuration Manager に登録します。

    -   Intune データウェアハウスに接続します。

    -   Intune との統合:
        -   リモートアシスタンスのチームビューアー (チームビューアーサブスクリプションは必須)。

        -   モバイル脅威防御パートナーソリューション (モバイル脅威防衛パートナーソリューションサブスクリプションが必要)。

        -   通信経費管理ソリューション (通信経費管理ソリューションサブスクリプションは必須)。

        -   windows Defender Advanced Threat Protection (windows e5 または Microsoft 365 E5 ライセンスが必要です)。

    -   該当するサポート対象プラットフォーム用のソフトウェア更新プログラムを構成する。

    -   ユーザー導入計画のリソース。

- Windows 自動操縦のセットアップ:

    - Microsoft Intune for Windows 自動操縦を構成してセットアップします。

    - Azure AD の動的グループを構成する

    - Azure AD に会社のブランド化を追加します。

    - windows 自動操縦プロファイルにデバイスを作成して割り当てます (たとえば、ローカル管理者アカウントの作成を制限する windows 自動操縦プロファイル)。

    - 組織の要件に準拠するように、[標準] (OOBE) をカスタマイズします。

    - Azure AD と Intune で MDM の自動登録を構成する。

    > [!NOTE]
    > Intune 外での Windows 自動操縦の設定は、fasttrack 特典の対象外です。

### <a name="enable-phase---co-management"></a>フェーズ共同管理を有効にする

次の点に関するガイダンスを行います。

-   エンドユーザーのライセンスを取得します。

-   intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、およびユーザーとデバイスグループの作成 (intune がインストールされていない場合)。

-   MDM 自動登録用に Azure Active Directory をセットアップします。

-   ハイブリッド Azure Active Directory の参加を設定します。

-   Cloud Management Gateway をセットアップします。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、およびユーザーとデバイスグループの作成。

-   intune を準備する (intune がインストールされていない場合):

    -   管理ニーズに応じて、以下のようなモバイルデバイス管理 MDM を構成します。

    -   MDM 権限として Intune を設定します。

    -   MDM 管理ポリシーの検証に使用するテストグループを構成する。

    -   Intune 管理ポータルを移動して、ユーザーとデバイスに関する情報を探します。

    -   Intune の役割の設定 (ヘルプデスクオペレーター、管理者など)

    -   サポートされている各プラットフォームに対して Intune アプリ保護ポリシーを構成および展開します。

    -   Windows 10 デバイスを Intune に登録します。

- 構成マネージャーコンソールで共同管理を有効にします。

- ワークロードを Intune に切り替えます。

- ご使用の環境での共同管理作業を監視します。

> [!NOTE]
> **詳細情報**「 [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)」を参照してください。

## <a name="next-steps"></a>次の手順

[EMS の fasttrack の利点-自分の責任](EMS-your-responsibilities.md)
