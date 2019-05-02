---
title: オンボーディングと移行のフェーズ
description: FastTrack センターの特典のフェーズ
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: e51f030b-8b08-4fea-96c9-d4ded435a264
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: eb7f106437f51283b36185bd8e19ab8821ba0f4f
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513510"
---
# <a name="onboarding-phases"></a>オンボーディング フェーズ

対象となる[サービスおよびプラン](M365-eligible-services-and-plans.md)を使用して、Microsoft Azure Active Directory Premium、microsoft Intune、および Azure Information Protection を使用できるようにする場合、このプロセスにはいくつかのフェーズが含まれています。 次のセクションでは、オンボードプロセスの各フェーズについて説明します。

オンボードには、4つの主要なフェーズがあります。

![FastTrack のオンボードプロセスの4つのフェーズ](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>開始フェーズ

適切な数のライセンスを購入した後、購入確認メールのガイダンスに従って、ライセンスを既存のテナントまたは新しいテナントに関連付けます。 その後、FastTrack センターの特典の資格が確認され、お客様と連絡して、オンボードのサポートを提供することを試みます。

> [!NOTE]
> 組織のためにこれらのサービスを展開する準備が整っている場合は、 [Fasttrack センター](https://go.microsoft.com/fwlink/?linkid=780698)からサポートを依頼することもできます。

### <a name="to-request-assistance"></a>アシスタンスを要求するには

1. [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。
2. **[FastTrack]** を選択します。
3. **[サービス]** を選択します。
4. **Microsoft 365 フォームのサポート要求**を完了します。

オンボードのサポートが開始されると、オンライン会議のスケジュールが設定されます。

> [!NOTE]
> Office 365 テナントに Microsoft パートナーが登録されている場合、このオプションは表示されません。 詳細については、Microsoft パートナーにお問い合わせください。

Microsoft パートナーは、お客様の代わりに[Fasttrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からサポートを受けることもできます。 To do so:

1. [FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)にサインインします。
2. **[FastTrack]** を選択します。
3. **[顧客]** を選択します。
4. 顧客を検索するか、顧客リストから選択します。
5. **[サービス]** を選択します。
6. **Microsoft 365 フォームのサポート要求**を完了します。

オンボードのサポートが開始されると、FastTrack はオンボードプロセスについて話し、データを検証し、キックオフミーティングを設定するためのオンライン会議のスケジュールを設定します。

![オンボード開始フェーズ](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>評価フェーズ

オンボードプロセスが開始されると、FastTrack センターは、ソース環境と要件を評価するためにお客様と連携します。 お客様の環境を評価するためのツールが実行されており、FastTrack スペシャリストは、オンプレミスの Active Directory、インターネットブラウザー、クライアントデバイスのオペレーティングシステム、ドメインネームシステム (DNS)、ネットワーク、インフラストラクチャ、および id システムを評価しています。オンボードの変更が必要かどうかを確認します。

FastTrack センターでは、対象となるサービスの適切な導入を促進する方法についてのガイダンスもご利用ください。

現在の設定に基づいて、移行計画を提供します。これにより、ソース環境にオンボードが EMS または個別のクラウドサービスを正常に完了するための最小要件が設定されます。 また、修復フェーズのための適切なチェックポイント呼び出しも設定します。

![オンボード評価フェーズ](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>修復フェーズ
移行元環境で修復プランのタスクを実行して、各サービスのオンボードと導入の要件を満たします (必要な場合)。

![オンボード修復フェーズ](./media/ft-remediate-phase.png)

有効化フェーズを開始する前に、修復アクティビティの結果を共同で検証して、続行する準備ができていることを確認してください。

## <a name="enable-phase"></a>有効化フェーズ
すべての修復アクティビティが完了すると、プロジェクトは、サービス利用のためのコアインフラストラクチャの構成、および対象となる EMS クラウドサービスをそれぞれプロビジョニングするために変化します。

**フェーズコア機能を有効にする**

コア オンボーディングには、サービスのプロビジョニングおよびテナントと ID の統合が含まれます。 また、Azure AD Premium、Intune、および Azure Information Protection などのオンボードオンラインサービスの基礎を提供する手順についても説明します。

![オンボード有効化フェーズコア機能](./media/ft-enable-phase-core-01.png)

![オンボード有効化フェーズコア機能](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP は、Web アプリケーション プロキシ (Web Application Proxy) を略したものです。SSL は、Secure Sockets Layer を略したものです。SDS は、School Data Sync を略したものです。SDS の詳細については、「[Microsoft School Data Sync へようこそ](https://go.microsoft.com/fwlink/?linkid=871480)」を参照してください。

> [!NOTE]
> 管理された認証方法にはが含まれていますが、パスワードハッシュの同期に限定されません。 Id の統合は、1回限りのアクティビティであり、管理やフェデレーションなどの既存の認証方法の移行または廃止には含まれません。

### <a name="enable-phase---azure-ad-premium"></a>有効化フェーズ-Azure AD Premium

Azure AD Premium 環境をセットアップするには、Azure Active Directory Connect tool ディレクトリ同期と Active Directory フェデレーションサービス (AD FS) を使用します (必要な場合)。

オンプレミス id とクラウドの同期を含む Azure AD Premium シナリオでは、サブスクリプションに IT 管理者とユーザーを追加し、管理前提条件を構成し、Azure AD Premium を設定し、ディレクトリを設定することによって、お客様を支援します。Azure AD Connect ツールを使用して管理された認証と AD FS を同期し、テストユーザーを構成して、サービスのコアユースケースを検証します。

Azure AD Premium セットアップには、次の機能を有効にすることが含まれます。

-   Azure Active Directory セルフサービスのパスワードのリセット (SSPR)。

-   Azure 多要素認証 (Azure MFA)。

-   [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/)のシングルサインオン (SSO) を使用したサービス (SaaS) アプリケーションの統合として、最大3つ以上のソフトウェア。

-   [アプリ統合チュートリアルリスト](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)に記載されている事前に統合された SaaS アプリケーションの自動ユーザープロビジョニングのみ。送信プロビジョニングのみに制限されます。

-   カスタマイズされたログオン画面 (ロゴ、テキスト、画像など)。

-   セルフサービスおよび動的グループ (グループ)。

-   Azure Active Directory アプリケーションプロキシ。

-   Azure Active Directory Connect Health。

-   Azure Active Directory の条件付きアクセス。

-   Azure Active Directory の使用条件。

-   Azure Active Directory Id 保護。

-   Azure Active Directory の特権 Id 管理。

-   Azure Active Directory アクセスレビュー。

![オンボード有効化フェーズ-Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>有効化フェーズ-Intune

Intune では、Microsoft Intune を使用してデバイスを管理できるようにするためのガイドを提供しています。 正確な手順は、ソース環境によって異なり、モバイルデバイスとモバイルアプリ管理のニーズに基づいています。 手順には次のものがあります。

-   エンドユーザーのライセンスを取得します。 また、必要に応じて、Microsoft クラウドサービスのテナントのボリュームライセンスをアクティブ化する方法についても説明します。

-   オンプレミスの Active Directory またはクラウド id のいずれかを活用して、Intune で使用される id を構成します。

-   Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、およびユーザーとデバイスグループの作成。

-   管理ニーズに応じて、次のようなモバイルデバイス管理 (MDM) 権限を構成します。

    -   Intune が唯一の MDM ソリューションである場合、または Office 365 用のモバイルデバイス管理と連携している場合に、MDM 機関として Intune を設定します。

-   MDM ガイダンスの提供:

    -   MDM 管理ポリシーの検証に使用するテストグループを構成する。

    -   MDM 管理ポリシーおよびサービスの構成は次のように行います。

        -   Web リンクまたはディープリンクを介して、サポートされている各プラットフォームのアプリケーションを展開します。

        -   条件付きアクセスポリシー。

        -   組織内に既存の証明機関、Wi-fi、または VPN インフラストラクチャがある場合、電子メール、ワイヤレスネットワーク、および仮想プライベートネットワーク (VPN) プロファイルを展開します。

        -   Microsoft Intune Exchange Connector のセットアップ (該当する場合)。

        -   Intune データウェアハウスへの接続

        -   Intune との統合:
            -   リモートアシスタンスのチームビューアー (チームビューアーサブスクリプションは必須)。

            -   モバイル脅威防御 (MTD) パートナーソリューション (モバイル脅威防御サブ機能が必要です)。

            -   通信経費管理ソリューション (通信経費管理ソリューションサブスクリプションは必須)。

            -   Windows Defender Advanced Threat Protection (Windows E5 または Microsoft 365 E5 ライセンスが必要です)。

    -   [サポートされている各プラットフォーム](https://technet.microsoft.com/library/dn600287.aspx)のデバイスを Intune に登録します。

-   アプリ保護ガイダンスの提供:

    -   サポートされている各プラットフォームのアプリ保護ポリシーを構成します。

    -   管理対象アプリの条件付きアクセスポリシーを構成する。

    -   上記の MAM ポリシーを使用して、適切なユーザーグループを対象にします。

    -   管理されたアプリケーションの利用状況レポートを使用します。

-   PC 管理ガイダンスの提供:

    -   Intune クライアントソフトウェアをインストールする (必要な場合)。

    -   Intune で利用可能なソフトウェアおよびハードウェアレポートを使用します。

    > [!IMPORTANT]
    > FastTrack では、Intune を使用した Windows 10 クラシック PC 管理はサポートされていません。 FastTrack は、Intune モバイルデバイス管理 (MDM) による Windows 10 デバイスの管理のみをサポートします。

#### <a name="windows-autopilot"></a>Windows Autopilot

FastTrack を使用すると、Windows 自動操縦と Intune を使用してデバイスのプロビジョニングを簡単に行うことができます。これにより、カスタムのオペレーティングシステムイメージを作成、保守、およびユーザーのデバイスに適用する必要なしに、新しいデバイスをエンドユーザーに提供することができます。

FastTrack は、次の自動操縦シナリオをサポートしています。

- **AZURE AD セルフサービス:** デバイスが Azure AD に参加し、Intune に登録されます。 このシナリオは、Windows 10 1703 と最新バージョンを使用している場合にサポートされます。

- **ハイブリッド AAD セルフサービス:** デバイスは、オンプレミスの AD と Azure AD の両方に参加し、Intune に登録します。 このシナリオは、Windows 10 1809 と最新バージョンを使用している場合にサポートされます。

- **セルフプロビジョニング:** デバイスは自動的に Azure AD に参加します。 このシナリオは、Windows 1809 と最新バージョンを使用している場合にサポートされます。

    > [!IMPORTANT]
    > FastTrack は、構成マネージャーから開始された自動操縦シナリオをサポートしていません。

Windows 自動操縦をセットアップする手順は、ソース環境によって異なります。次のものが含まれます。

- Microsoft Intune for Windows 自動操縦を構成してセットアップします。

- Azure AD の動的グループを構成する

- Azure AD に会社のブランド化を追加します。

- Windows 自動操縦プロファイルにデバイスを作成して割り当てます (たとえば、ローカル管理者アカウントの作成を制限する Windows 自動操縦プロファイル)。

- 組織の要件に準拠するように、[標準] (OOBE) をカスタマイズします。

- Azure AD と Intune で MDM の自動登録を構成する。

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>IOS および Android 用の Outlook を安全に展開する

FastTrack は、ユーザーが必要なすべてのアプリをインストールしていることを確認するために、iOS および Android 用の Outlook を安全に組織に展開することによって役立ちます。

Intune を使用して iOS および Android 用の Outlook Mobile を安全に展開するための手順は、ソース環境によって異なります。次のものを含めることができます。

- Apple App Store または Google Play ストア経由で、iOS および Android 用の Outlook、Microsoft Authenticator、Intune ポータルサイトアプリをダウンロードします。
- セットアップのガイダンスも提供します。
    - IOS および Android 用の Outlook、Microsoft Authenticator、および intune を使用した Intune ポータルサイトアプリの展開。
    - アプリ保護ポリシー
    - 条件付きアクセスポリシー
    - アプリ構成ポリシー

    > [!IMPORTANT]
    > FastTrack チームは、Exchange モバイルデバイスメールボックスポリシーを使用して iOS および Android 用の Outlook のセキュリティ保護をサポートしていません。

#### <a name="co-management"></a>共同管理

FastTrack は、構成マネージャーと Intune の両方を使用して、Windows 10 デバイスを同時に管理できるようにするためのガイドです。 正確な手順は、ソース環境によって異なります。次のものが含まれます。

- 共同管理の利点について説明します。

- エンドユーザーにライセンスを付与します。 FastTrack では、必要に応じて Microsoft cloud service テナントのボリュームライセンスをアクティブ化する方法についても説明しています。

- オンプレミスの Active Directory とクラウド id のどちらかを活用して、Intune で使用される id を構成します。

- Intune サブスクリプションへのユーザーの追加、IT 管理者の役割の定義、およびユーザーとデバイスグループの作成。

- System Center Configuration Manager (ハイブリッド) と統合された Intune から Intune スタンドアロンに移行する方法に関するガイダンスを提供します。

- MDM 自動登録用に Azure Active Directory をセットアップするためのガイダンスを提供します。

- ハイブリッド Azure Active Directory の参加を設定するためのガイダンスを提供します。

- クラウド管理ゲートウェイのセットアップ方法についてのガイダンスを提供する

- 構成マネージャーコンソールで共同管理を有効にします。

- Intune に切り替えることができる、サポートされているワークロードを構成します。

- Intune 登録済みデバイスに Configuration Manager クライアントをインストールします。

- ご使用の環境での共同管理アクティビティを監視する方法についてのガイダンスを提供します。

FastTrack は、対象となるサービスの適切な導入を促進する方法についてのガイダンスも提供します。

![オンボード有効化フェーズ-Intune](./media/ft-enable-phase_intune_mam.png)

![オンボード有効化フェーズ-Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![オンボード有効化フェーズ共同管理](./media/ft-9-enable-phase-comanagement.png)

#### <a name="enable-phase--azure-information-protection"></a>有効化フェーズ-Azure Information Protection

Azure Information Protection では、次のサポートが提供されます。 

- お客様は、Windows 上で実行されている Office アプリ (Word、PowerPoint、Excel、Outlook など) の情報を自動的に分類してラベルを付け、Azure Information Protection クライアントを使用します。 
- Azure Information Protection スキャナーを使用して、ファイルを保存します。
- Exchange Online のメールフロールールを使用して転送中の電子メール。 

Microsoft Azure Rights Management Services (Azure RMS)、Office 365 Message Encryption (OME)、データ損失防止 (DLP) を使用して保護を適用するお客様にもサポートが提供されます。 

お客様には、次の方法に関するガイダンスが提供されています。 

- テナントのアクティブ化と構成を行います。
- ラベルとポリシーを作成して設定します。
- ドキュメントに情報保護を適用します。 


> [!NOTE]
> **詳細情報**「 [Enterprise Mobility + Security](https://www.microsoft.com/en-us/cloud-platform/enterprise-mobility)」を参照してください。

## <a name="next-steps"></a>次の手順

[EMS の FastTrack の特典-Microsoft の責任](EMS-fasttrack-responsibilities.md)
