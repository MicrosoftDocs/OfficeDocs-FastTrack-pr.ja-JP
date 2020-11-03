---
title: FastTrack Center の特典の概要
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Office 365 用 FastTrack Center 特典では、FastTrack スペシャリストとリモートで作業して、組織内で Office 365 環境を使い始められるように準備を行い、ロールアウトと使用法を計画することができます。資格について詳しくは、「Office 365 用 FastTrack Center 特典」を参照してください。
ms.openlocfilehash: 039a1a409f35d12e61e25757e18f481c2b754571
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827083"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack センター特典の概要

> [!CAUTION]
> このコンテンツは最新ではなくなったため、削除される予定です。 最新のコンテンツについては、左側のナビゲーションにある目次を使用してください。

Office 365 用 FastTrack Center 特典では、FastTrack スペシャリストとリモートで作業して、組織内で Office 365 環境を使い始められるように準備を行い、ロールアウトと使用法を計画することができます。資格について詳しくは、「[Office 365 用 FastTrack Center 特典](O365-fasttrack-benefit-for-office-365.md)」を参照してください。
  
以下のトピックについて説明します。
- [FastTrack プロセス](O365-fasttrack-process.md) 
- [ソース環境要件](O365-source-environment-expectations.md)
- [オンボーディングと移行のフェーズ](O365-onboarding-and-migration.md)
- [データ移行](O365-data-migration.md)
- [FastTrack の責任範囲](O365-fasttrack-responsibilities.md)
- [お客様の責任](O365-your-responsibilities.md) 
- [付録 A - FastTrack センターのその他の利点](O365-fasttrack-additional-benefits.md)
- [付録 B: FastTrack Center HIPAA ビジネス アソシエイト契約](O365-hipaa-business-associate-agreement.md)
- [付録 C: Office 365 US Government 向け FastTrack Center の特典の概要](US-Gov-appendix-overview.md)
    
オンボーディングが完了すると、Office 365 テナントが作成されます。ライセンスを持つユーザーが、以下のいずれかの ID オプションを使って Office 365 にアクセスできます。
- 固有の Office 365 アカウントを持つクラウド ID。
- Azure Active Directory Connect (パスワード ハッシュ同期またはパススルー認証) を使って、オンプレミスの Active Directory から同期した Office 365 アカウントを持つ同期した ID。これは、次のお客様を対象としています。
  - 1 つの Active Directory フォレスト環境を使っている。
  - サポートされる複数フォレストの Active Directory トポロジを使っている。サポートされるトポロジについては、「[ソース環境要件](O365-source-environment-expectations.md)」をご覧ください。
- 次の Office 365 アカウントを持つフェデレーション ID:
  - Azure Active Directory Connect ツールを使用して Active Directory から同期されている、次のお客様が対象です。
      - 1 つの Active Directory フォレスト構成を使っている。
      - 1 つの Active Directory アカウント フォレスト (「ログオン フォレスト」とも呼ばれる) と 1 つの Active Directory リソース フォレストの構成を使っている。
  - オンプレミスの Active Directory フェデレーション サービス (AD FS) インフラストラクチャで構成されている。次のようなインフラストラクチャです。
      - オンプレミスの Active Directory から、Windows Server 2012 R2 以降の AD FS の役割によってフェデレーションされている。
      - 必要に応じて、オンプレミスの AD FS インフラストラクチャをインターネットに公開するために使用される、Windows Server 2012 R2 以降の Windows アプリケーション プロキシ (WAP) の役割。
    > [!NOTE]
    > AD FS と WAP の展開と構成は、オンプレミス環境から [Azure AD Connect の構成ウィザード](https://go.microsoft.com/fwlink/?linkid=844794)を使用して行います。 
  
- ライセンス付与済みのユーザーが「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」にアクセスできるようになりました。

