---
title: ソース環境の要件
description: EMS 用 FastTrack センターの特典を使用するためのソース環境の要件
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513152"
---
# <a name="source-environment-expectations"></a>ソース環境要件

[Enterprise Mobility + Security (EMS) 用の Fasttrack センターの特典](EMS-fasttrack-benefit-for-EMS.md)を使用して、Microsoft Azure Active Directory Premium、microsoft Intune、および Azure Information Protection を使用するための準備が整っている場合、環境は期待値を満たす必要があります。次のセクションで説明します。

Enterprise Mobility + Security (EMS) または1つのコンソールから豊富な id 管理を使用する個々のサービスと統合する必要がある組織内のオンプレミスの Active Directory が、既に組織内にある場合があります。 Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典には、既存のオンプレミスの Active Directory 環境と Azure Active Directory を統合するのに役立つ情報が含まれています。

次の表に、既存のソース環境でのオンプレウェアの要件を示します。

|アクティビティ|ソース環境要件|
|------------|----------------------------------|
|オンボードコア|機能フォレストレベルが Windows Server 2008 以上に設定されている Active Directory フォレスト。フォレストの構成は次のとおりです。<br /><br />-単一の Active Directory フォレスト<br />-複数の Active Directory フォレスト </br></br>**注**: すべての複数フォレスト構成では、Active Directory フェデレーションサービス (AD FS) の展開は Fasttrack センターの特典の対象外です。|
|Azure AD Premium のオンボード|オンプレミスの Active Directory とその環境は Azure ad Premium 用に準備されています。これには、Azure AD および Azure AD Premium 機能との統合を妨げる特定の問題の修復が含まれています。|
|Intune のオンボード| IT 管理者は、WiFi および VPN プロファイルを Intune に展開する計画を立てるときに、既存の証明機関、WiFi、および VPN インフラストラクチャを運用環境で既に稼働している必要があります。<br /><br /> **注**: サービス特典には、の証明機関、WIFI、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含まれません。  |
|Comanagement|Comanagement IT 管理者は、オンプレミス環境の準備を担当しています。これには、構成マネージャーと Intune を使用して Windows 10 デバイスを同時に管理できない問題の修復が含まれる場合があります。<br /><br />**注**: fasttrack サービス特典には、Windows 10 デバイスで Comanagement をサポートするために必要な最小要件を設定または構成マネージャークライアントをセットアップまたはアップグレードするための支援は含まれていません。 |
|Intune と Windows Defender Advanced Threat Protection の統合 (Windows Defender ATP)|Windows Defender ATP サブスクリプションは、会社のセキュリティ要件に基づいてライセンス認証され、構成されています。<br /><br />**注**: fasttrack サービス特典は、WINDOWS Defender ATP との Intune の統合、および windows 10 のリスクレベルの評価に基づいたデバイスコンプライアンスポリシーの作成に関するサポートを提供します。 FastTrack サービス特典は、Windows Defender ATP およびそのセキュリティセンターコンソールを購入、ライセンス、アクティブ化、または使用するための支援を提供しません。 |
|Windows Autopilot|IT 管理者は、ハードウェアベンダーに代わってハードウェア Id をアップロードするか、Windows 自動操縦サービスにアップロードすることによって、自分の組織にデバイスを登録する責任があります。 |
|IOS および Android 用の Outlook を、Intune を使用して安全に展開する|<br /><br />-Office 365 の Azure AD で有効になっているユーザー id。<br />-ユーザーライセンスが割り当てられている Exchange Online またはハイブリッド Exchange。<br />|
|Azure Information Protection (P2 または EMS E5)|<br /><br />お客様の場合: <br /> -Azure AD を使用します。<br />-Windows または iOS のどちらかを使用します (その他の OSs は範囲外です)。<br /> -Office Online をメインクライアントとして使用しない office 2010 SP2 より新しい office クライアントを使用します。 <br /> -メインファイル共有の場所を用意します。  <br /> -Active Directory Rights Management サービス (AD RMS) からアップグレードしました。 <br /> -承認された分類分類を持つ。 <br /> -保護されたキーの管理に関する規制の制限について理解します。 <br />|
|Azure Information Protection スキャナー|<br /><br /> お客様の場合: <br /> -Windows Server 2012 R2 または Windows Server 2016 を使用します。<br /> -インターネット接続があること。 <br /> -ローカルまたはリモートのインスタンスに Microsoft SQL Server 2012 以降があること。  <br /> -オンプレミスの Active Directory に対してサービスアカウントが作成され、Azure AD と同期されていること。  <br /> -AzInfoProtection をダウンロードしました。 <br /> -自動分類/保護に対してラベルが構成されている。<br />|

> [!NOTE]
> **詳細情報**
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>次の手順

[EMS のオンボードフェーズの FastTrack センターの特典](EMS-onboarding-phases.md)
