---
title: ソース環境要件
description: EMS 向け FastTrack センター特典を使用するためのソース環境要件
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 4/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ffec6096b8f8bb587318b1f5ee93789a80247a61
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098079"
---
# <a name="source-environment-expectations"></a>ソース環境要件

Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection の使用に向けた準備で [Enterprise Mobility + Security (EMS) 向け FastTrack センターの特典](EMS-fasttrack-benefit-for-EMS.md)を使用する場合、お客様の環境が次のセクションで説明する要件を満たしている必要があります。

Enterprise Mobility + Security (EMS) と統合させることを希望するオンプレミスの Active Directory または単一のコンソールからのリッチ ID 管理を使用する EMS の個別のサービスが既に組織にあるかもしれません。 Enterprise Mobility + Security (EMS) 向け FastTrack センター 特典には、Azure Active Directory を既存のオンプレミスの Active Directory 環境と統合させるためのサポートが含まれます。

次の表に、オンボーディングで既存のソース環境に必要とされる要件を示します。

|アクティビティ|ソース環境要件|
|------------|----------------------------------|
|コア オンボーディング|以下のフォレスト構成で、機能フォレスト レベルが Windows Server 2008 以降に設定された Active Directory フォレスト。<br /><br />- 1 つの Active Directory フォレスト<br />- 複数の Active Directory フォレスト </br></br>**注**: フォレストが複数あるすべての構成において、Active Directory フェデレーション サービス (AD FS) の展開は FastTrack センター特典の対象外です。|
|Azure AD Premium のオンボーディング|オンプレミスの Active Directory とその環境は Azure AD Premium 用に準備されている。これには、特定された、Azure AD および Azure AD Premium 機能との統合を妨げる問題の修復が含まれます。|
|Intune オンボーディング| Intune を使用した Wi-Fi および VPN の展開を計画する段階で、IT 管理者は既存の証明機関、WiFi、および VPN のインフラストラクチャを運用環境で動作させている必要があります。<br /><br /> **注**: サービス特典には、認証機関、Wi-Fi、VPN インフラストラクチャ、または Apple MDM プッシュ証明書のセットアップおよび構成に関するサポートは含まれません。  |
|Intune を使用して Configuration Manager をクラウドで接続する|クラウドで接続する場合、IT 管理者はオンプレミス環境の準備を行う責任があります。これには、Intune を使用した Configuration Manager 環境のクラウド接続を妨げる問題の修正が含まれる場合があります。<br /><br />**注**: FastTrack サービス特典には、Configuration Manager サイト サーバーまたは Configuration Manager クライアントのクラウド接続をサポートするために必要な最小要件への設定またはアップグレードの支援は含まれていません。 |
|Intune と Microsoft Defender Advanced Threat Protection (ATP) の統合|**注**: FastTrack サービス特典は、Intune の Microsoft Defender ATP との統合および Windows 10 のリスク レベル評価に基づいたデバイス コンプライアンス ポリシーの作成に対する支援を提供します。 このサービス特典では、購入、ライセンス、アクティベーションに関するサポートは提供されません。 |
|Windows Autopilot|IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。 |
|Intune を使用して Outlook for iOS および Outlook for Android を安全に展開する|<br /><br />- Office 365 用の Azure AD でユーザー ID が有効になっている。<br />- Exchange Online またはハイブリッド Exchange が構成され、ユーザー ライセンスが割りてられている。<br />|
|Azure Information Protection (P2 または EMS E5)|<br /><br />お客様は既に以下を行っている必要があります。 <br /> - Azure AD を使用している。<br />- Windows または iOS (その他の OS は対象外) を使用している。<br /> - メインのクライアントとして、Office に依存することのない Office 2010 SP2 以降の Office クライアントを使用している。 <br /> - 主なファイル共有場所がある。  <br /> - Active Directory Rights Management サービス (AD RMS) からのアップグレードが完了している。 <br /> - 承認済みの分類方法がある。 <br /> - 保護されたキー管理に対するすべての規制を理解している。 <br />|
|Azure Information Protection スキャナー|<br /><br /> お客様は既に以下を行っている必要があります。 <br /> - Windows Server 2012 R2 または Windows Server 2016 を使用している。<br /> - インターネットに接続されている。 <br /> -ローカルまたはリモートのインスタンスに、Microsoft SQL Server 2012 以降がある。  <br /> - オンプレミスの Active Directory 用のサービス アカウントが作成され、Azure AD との同期が行われている。  <br /> - AzInfoProtection.exe をダウンロードしてある。 <br /> -ラベルを自動分類/保護用にラベルが構成されている。<br />|

> [!NOTE]
> **詳細な情報をご希望の場合は**、
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility) をご覧ください。

## <a name="next-steps"></a>次の手順

[EMS 向け FastTrack センター特典のオンボーディングのフェーズ](EMS-onboarding-phases.md)

