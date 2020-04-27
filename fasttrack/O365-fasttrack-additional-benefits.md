---
title: 付録 BFastTrack センターの付加的な利点
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: FastTrack Center の追加サービスは、Exchange Online テナントのライセンスを 20,000 以上ご購入いただいたお客様が対象です。詳細については、「対象となるサービスとプラン」を参照してください。
ms.openlocfilehash: 62d0f5cf99624fbfb69a3bcb950f4718e0372512
ms.sourcegitcommit: 1aa423e2a720d57d2a37fba930fb4d4b0e8f93c9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/22/2020
ms.locfileid: "43666113"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>付録 B - FastTrack Center の付加的な利点

FastTrack Center の追加サービスは、Exchange Online テナントのライセンスを 20,000 以上ご購入いただいたお客様が対象です。詳細については、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。 
  
## <a name="onboarding-and-migration-phases"></a>オンボーディングと移行のフェーズ

## <a name="core"></a>コア

コア オンボーディング サービスの追加内容には、地理的冗長性を備えた Active Directory Federation Services (AD FS) およびサービスの AD FS クライアント アクセス ポリシーの構成ガイダンスが含まれます。 
  
## <a name="exchange-online"></a>Exchange Online

Exchange Online では、次に示す構成ガイダンスを提供します。
- Exchange Online でのユニファイド メッセージング (UM) のセットアップ。
- Exchange Online と従来のオンプレミスのパブリック フォルダーとの共存の構成。
- メールが有効なアプリケーションの統合。 
- メールボックス移行の計画とグループ化。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Skype for Business Online では、オンプレミスの Lync および Skype for Business ユーザーの Skype for Business Online への移行に関するガイダンスを提供します。
  
## <a name="microsoft-365-apps"></a>Microsoft 365 アプリ

Microsoft 365 アプリに関しては、次に示すガイダンスを提供します。 
- Microsoft のベストプラクティスに従って初期展開をして更新を管理するための環境の準備に焦点を当てた評価と計画。 
- Office 365 展開ツールと Office カスタマイズ ツールによる展開構成と更新設定の策定。 
- Microsoft Endpoint Configuration Manager を使用した展開パッケージング。  
- Office 用準備ツールキットの使用を有効化して、Office で使用する Microsoft Visual Basic for Applications (VBA) マクロとアドインで起きる可能性がある互換性の問題を識別します。
    
## <a name="fasttrack-responsibilities"></a>FastTrack の責任範囲

FastTrack スペシャリストには、オンボーディング中に以下の責任があります。これらは、[FastTrack の責任範囲](O365-fasttrack-responsibilities.md)で定義されているアクティビティに追加あるいは置換されることがあります。
  
## <a name="general"></a>全般

- 達成計画の開発と実装、必要な構成アクティビティのための遠隔サポート アシスタンスを提供します。その内容については、「[オンボーディングと移行のフェーズ](#onboarding-and-migration-phases)」で説明しています。
    
## <a name="assess-phase"></a>評価フェーズ

- 達成計画に関する電話会議を行い、ユーザーによる効果的な採用のためのガイダンスを提供します。 
- お使いの環境を評価し、地理的冗長性を備えた AD FS の構成をサポートします。  
- 評価を実行し、AD FS クライアント アクセスの要件を特定します。
    
## <a name="enable-phase"></a>有効化フェーズ

### <a name="geo-redundant-ad-fs-guidance"></a>地理冗長 AD FS のガイダンス

- 2 つのデータ センターにわたる地域冗長 AD FS トポロジに、標準的な参照アーキテクチャの設計を提供します。標準的なアーキテクチャの対象を次に示します。
  - FastTrack Center 特典に含まれるサービスのフェデレーション認証。 
  - 単一サイトの復元。  
  - 高可用性とフェールオーバー。  
  - サイジングに関するガイダンス。 
- AD FS ファームのデータベース インスタンスとして Windows Integrated Database (WID) および SQL Server の使用に関するガイダンスを提供します。   
- スコープ内の各フォレストのフェデレーション認証の確立を検証します。  
- 最大 10 ユーザーに対するフェデレーション認証機能を確認します。
    
> [!NOTE]
> AD FS の展開は、複数の Active Directory フォレスト構成を持つ、追加支援の対象となるお客様が対象になります。 
  
### <a name="ad-fs-client-access-policy-guidance"></a>AD FS クライアント アクセスのポリシーのガイダンス

- セキュリティで保護された Office 365 リソースに必要なポリシーと構成を確認します。  
- サポートされているシナリオの範囲内で識別されたクライアント アクセス シナリオについて AD FS クライアント アクセス ポリシーを構成するためのガイダンスと支援を提供します。詳細については、「[クライアントの場所に基づいて Office 365 サービスへのアクセスを制限する](https://go.microsoft.com/fwlink/?LinkID=525689)」を参照してください。 
- 更新されたクライアント アクセス ポリシーを使用して、最大 10 ユーザーの構成を持つ、認識されたアクセス シナリオのフェデレーション認証機能を検証します。
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Exchange ユニファイド メッセージングのガイダンス

- 以下について最大 10 個を有効にするために、Exchange Online 上で必要な構成に関するガイドラインを提供します。 
  - UM ダイヤル プラン。   
  - UM メールボックス ポリシー。 
  - 自動応答。  
- UM と以下を有効にするために、オンプレミスの Lync または Skype for Business の環境構成に関するガイドラインを提供します。  
  - Exchange Online がホストするポリシー。  
  - Exchange Online がホストするボイス メール ポリシー。 
  - ユーザーを Exchange Online にリダイレクトするための UM の自動応答の連絡先と Outlook 音声メール。 
  - フェデレーションの必要に応じて Service Location (SRV) レコードの作成をサポートします。
> [!NOTE]
> サポートされた UM IP ゲートウェイとセッション ボーダー コントローラー (SBC) で UM を構成できます。詳細については、「[電話システムの UM との統合](https://go.microsoft.com/fwlink/?LinkID=809293)」を参照してください。 
  
### <a name="public-folder-coexistence-guidance"></a>パブリック フォルダーの共存のガイダンス

- 単一のパブリック フォルダー ツリーの共存に関する次のような内容のガイダンスを提供します。  
  - Exchange 2007、Exchange 2010、Exchange 2013 でのパブリック フォルダーの準備。 
  - パブリック フォルダーのアクセスをオンプレミスのパブリック フォルダーにリダイレクトするための Exchange Online の構成。  
  - Exchange Online から単一の Exchange 2007、Exchange 2010、Exchange 2013 のオンプレミス環境へのパブリック フォルダーへのアクセスの構成。  
  - Exchange Online でのパブリック フォルダー環境への最大 10 人のユーザーのアクセス検証のサポート。
    
### <a name="mail-enabled-application-integration-guidance"></a>メールが有効なアプリケーションの統合ガイダンス

- 以下に関するガイダンスのテンプレートを提供します。  
  - 大量メールのアプリケーション。  
  - Exchange を介して電子メールをルーティングするアプリケーション。  
  - Exchange メールボックスを使用するアプリケーション。  
  - サードパーティ製またはカスタムのコンポーネントを Exchange サーバーにインストールするのに必要なアプリケーション。
    
### <a name="mailbox-migration-planning-and-grouping"></a>メールボックス移行の計画とグループ化

- 移行計画作成に関し、次の内容を含めたガイダンスを提供します。  
  - バッチ処理によるユーザーとリソースのグループ化。
  - 移行のバッチ処理による必要なソフトウェア パッケージの展開の調整。   
  - エンド ユーザー向けの通信計画作成のためのガイダンス。 
  - 移行バッチ処理のサイズ、エラー率の調整とヘルプデスクのサポートの予定。 
- バッチ処理により、ユーザーとリソースのメールボックスを、お客様が指定した関連情報に基づき、種類別、ビジネス機能別、委任アクセス別にグループ化する際のガイダンスを提供します。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

- Skype for Business のハイブリッド展開でのバッチ処理によるユーザーの移行 (ユーザーの連絡先リストを保持しながら) についてのガイダンスを提供します。
    
## <a name="microsoft-365-apps"></a>Microsoft 365 アプリ

- 以下についてのガイダンスとサポートを提供します。  
  - 初期展開と更新管理のための Microsoft のベストプラクティスに従った評価と計画。
  - Office 用準備ツールキットの使用を有効化して、Office で使用する Microsoft VBA マクロとアドインで起きる可能性がある互換性の問題を識別します。
  
## <a name="your-responsibilities"></a>お客様の責任

お客様には、オンボーディング中に以下の責任があります。これらは「[お客様の責任](O365-your-responsibilities.md)」セクションで定義されている責任に追加されるものです。 
  
- プロジェクト計画に従いリソースを割り当て、管理する。  
- リスクを緩和し、顧客、パートナーのプロジェクト マネージャー、FastTrack マネージャーから発生した問題を解決するため、適宜対応する。   
- 状況レポートを確認し、それに応じて適切に処理する。   
- 意思決定権限を持つ運営スポンサーまたは責任者を割り当て、運営会議を実施する。  
- Microsoft のエグゼクティブ スポンサーとの連携業務を担うエグゼクティブ スポンサーを割り当てる。  
- 運営委員会の会議を毎月開催する。
