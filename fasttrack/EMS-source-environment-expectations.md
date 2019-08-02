---
title: ソース環境要件
description: EMS 向け FastTrack センター特典を使用するためのソース環境要件
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 08/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ffb9af7e6a0a4c2358a0bbe054469cf0caae11c4
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053759"
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
|共同管理|共同管理を行う場合、IT 管理者はオンプレミス環境の準備を行う責任があります。これには、Configuration Manager と Intune の両方を使用して行う、Windows 10 デバイスを同時に管理することを妨げている問題の修復が含まれる場合があります。<br /><br />**注**: FastTrack サービス特典には、Configuration Manager サイト サーバーおよび/または Configuration Manager クライアントのセットアップまたは Windows 10 デバイスでの共同管理をサポートするために必要な最小要件へのアップグレードの支援は含まれていません。 |
|Windows Defender Advanced Threat Protection (Windows Defender ATP) と統合された Intune|Windows Defender ATP サブスクリプションのライセンス認証が完了し、組織のセキュリティ要件に基づいて構成されている。<br /><br />**注**: FastTrack サービス特典は、Intune の Windows Defender ATPとの統合および Windows 10 の リスク レベル評価に基づいたデバイス コンプライアンス ポリシーの作成に対する支援を提供します。 FastTrack サービス特典は、Windows Defender ATP およびそのセキュリティ センター コンソールの購入、ライセンス、ライセンス認証、または使用に関する支援は提供しません。 |
|Windows Autopilot|IT 管理者は、管理者自身または管理者の代理としてハードウェアの製造元がハードウェア ID を Windows Autopilot サービスにアップロードすることにより、デバイスを組織に登録する責任があります。 |
|Intune を使用して Outlook for iOS および Outlook for Android を安全に展開する|<br /><br />- Office 365 用の Azure AD でユーザー ID が有効になっている。<br />- Exchange Online またはハイブリッド Exchange が構成され、ユーザー ライセンスが割りてられている。<br />|
|Azure Information Protection (P2 または EMS E5)|<br /><br />お客様は既に以下を行っている必要があります。 <br /> - Azure AD を使用している。<br />- Windows または iOS (その他の OS は対象外) を使用している。<br /> - メインのクライアントとして、Office に依存することのない Office 2010 SP2 以降の Office クライアントを使用している。 <br /> - 主なファイル共有場所がある。  <br /> - Active Directory Rights Management サービス (AD RMS) からのアップグレードが完了している。 <br /> - 承認済みの分類方法がある。 <br /> - 保護されたキー管理に対するすべての規制を理解している。 <br />|
|Azure Information Protection スキャナー|<br /><br /> お客様は既に以下を行っている必要があります。 <br /> - Windows Server 2012 R2 または Windows Server 2016 を使用している。<br /> - インターネットに接続されている。 <br /> -ローカルまたはリモートのインスタンスに、Microsoft SQL Server 2012 以降がある。  <br /> - オンプレミスの Active Directory 用のサービス アカウントが作成され、Azure AD との同期が行われている。  <br /> - AzInfoProtection.exe をダウンロードしてある。 <br /> -ラベルを自動分類/保護用にラベルが構成されている。<br />|

> [!NOTE]
> **詳細な情報をご希望の場合は**、
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility) をご覧ください。

## <a name="next-steps"></a>次の手順

[EMS 向け FastTrack センター特典のオンボーディングのフェーズ](EMS-onboarding-phases.md)
