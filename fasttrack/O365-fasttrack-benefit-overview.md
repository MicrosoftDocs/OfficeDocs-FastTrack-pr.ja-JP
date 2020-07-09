---
title: FastTrack Center の特典の概要
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011335"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack Center の特典の概要

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
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
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- 固有の Office 365 アカウントを持つクラウド ID。
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - 1 つの Active Directory フォレスト環境を使っている。
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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

