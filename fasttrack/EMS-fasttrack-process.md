---
title: FastTrack プロセス
description: FastTrack Center の特典オンボーディング プロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 6/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b190e4c3c27717988ee4f5e2e21deff56233a670
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/02/2020
ms.locfileid: "44471494"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス
お客様の組織が EMS 向け FastTrack Center の特典を受ける対象である場合は、FastTrack スペシャリストとリモートで作業して Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection を使用できるようにすることができます。 また、Azure Information Protection や Microsoft Cloud App Security の [FastTrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からもヘルプを要求できます。 組織が特典を受ける対象であるかどうかを判断するには、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。


ここでは、オンボーディング プロセスについて説明します。

-   [オンボーディング プロセスの概要](EMS-fasttrack-benefit-overview.md)

-   [ソース環境の要件](EMS-source-environment-expectations.md)

-   [オンボーディング プロセスのフェーズ](EMS-onboarding-phases.md)

-   各フェーズの [FastTrack の責任範囲](EMS-fasttrack-responsibilities.md)

-   各フェーズの [お客様の責任範囲](EMS-your-responsibilities.md)

以下は、オンボード完了時に予測される内容です。

-   選択したサービスの EMS テナントが作成されます。

-   ライセンスを持つユーザーが、以下のいずれかの ID オプションを使用して EMS サービスにアクセスできます。

    -   クラウド ID (固有の EMS アカウント)。

    -   同期 ID: Azure Active Directory Connect ツール (パスワード ハッシュ同期またはパススルー認証) を使用して、オンプレミスの Active Directory から EMS アカウントを同期しています。 このオプションは、単一フォレストまたは複数の Active Directory フォレストを持つお客様向けです。

    -   次の Microsoft EMS アカウントを持つフェデレーション ID:

        -   Active Directory から Azure AD Connect ツールと同期します。 このオプションは、単一の Active Directory フォレスト構成を持つお客様向けです。

        -   オンプレミスの Active Directory から Windows Server 2012 R2 の Active Directory フェデレーション サービス (AD FS) 2.0 以降とフェデレーションされています。

        -   Azure Information Protection を使用して、保存中および転送中の両方で情報を自動分類および保護する機能。 

        -   Azure Information Protection スキャナーを使用して、オンプレミスのファイル共有と SharePoint サーバーの情報を見つける機能。 

        -   Azure Key Vault 内の Azure Information Protection テナント キーを管理する機能。 

