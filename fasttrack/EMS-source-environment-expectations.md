---
title: ソース環境の要件
description: EMS 用 fasttrack センターの特典を使用するためのソース環境の要件
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0d0fa0415bc27013d7e035b75a5e5d9d9f9919c3
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016769"
---
# <a name="source-environment-expectations"></a>ソース環境要件

[Enterprise Mobility + Security (EMS) 用の fasttrack センターの特典](EMS-fasttrack-benefit-for-EMS.md)を使用して、microsoft Azure Active Directory Premium と microsoft Intune の使用準備が整っている場合、環境は以下のセクションで説明する期待値を満たす必要があります。

Enterprise Mobility + Security (EMS) または1つのコンソールから豊富な id 管理を使用する個々のサービスと統合する必要がある組織内のオンプレミスの Active Directory が、既に組織内にある場合があります。 Enterprise Mobility + Security (EMS) 向け fasttrack Center の特典には、既存のオンプレミスの active directory 環境と Azure active directory を統合するのに役立つ情報が含まれています。

次の表に、既存のソース環境でのオンプレウェアの要件を示します。

|アクティビティ|ソース環境要件|
|------------|----------------------------------|
|オンボードコア|機能フォレストレベルが Windows Server 2008 以上に設定されている Active Directory フォレスト。フォレストの構成は次のとおりです。<br /><br />-単一の Active Directory フォレスト<br />-複数の Active Directory フォレスト </br></br>**注**: すべての複数フォレスト構成では、Active Directory フェデレーションサービス (AD FS) の展開は fasttrack センターの特典の対象外です。|
|Azure AD Premium のオンボード|オンプレミスの Active Directory とその環境は azure ad premium 用に準備されています。これには、azure ad および azure ad premium 機能との統合を妨げる特定の問題の修復が含まれています。|
|Intune のオンボード| IT 管理者は、wifi および vpn プロファイルを Intune に展開する計画を立てるときに、既存の証明機関、wifi、および vpn インフラストラクチャを運用環境で既に稼働している必要があります。<br /><br /> **注**: サービス特典には、の証明機関、WiFi、VPN インフラストラクチャ、または Apple MDM プッシュ証明書を設定または構成するための支援は含まれません。  |
|Comanagement|Comanagement IT 管理者は、オンプレミス環境の準備を担当しています。これには、構成マネージャーと Intune を使用して Windows 10 デバイスを同時に管理できない問題の修復が含まれる場合があります。<br /><br />**注**: fasttrack サービス特典には、Windows 10 デバイスで Comanagement をサポートするために必要な最小要件を設定または構成マネージャークライアントをセットアップまたはアップグレードするための支援は含まれていません。 |
|Intune と windows defender Advanced Threat Protection の統合 (windows defender ATP)|Windows Defender ATP サブスクリプションは、会社のセキュリティ要件に基づいてライセンス認証され、構成されています。<br /><br />**注**: fasttrack サービス特典は、windows Defender ATP との Intune の統合、および windows 10 のリスクレベルの評価に基づいたデバイスコンプライアンスポリシーの作成に関するサポートを提供します。 fasttrack サービス特典は、Windows Defender ATP およびそのセキュリティセンターコンソールを購入、ライセンス、アクティブ化、または使用するための支援を提供しません。 |
|Windows Autopilot|it 管理者は、ハードウェアベンダーに代わってハードウェア id をアップロードするか、Windows 自動操縦サービスにアップロードすることによって、自分の組織にデバイスを登録する責任があります。 |
|iOS および Android 用の Outlook を、Intune を使用して安全に展開する|<br /><br />-Office 365 の Azure AD で有効になっているユーザー id。<br />-ユーザーライセンスが割り当てられている exchange Online またはハイブリッド exchange。<br />|

> [!NOTE]
> **詳細情報**
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>次の手順

[EMS のオンボードフェーズの fasttrack センターの特典](EMS-onboarding-phases.md)
