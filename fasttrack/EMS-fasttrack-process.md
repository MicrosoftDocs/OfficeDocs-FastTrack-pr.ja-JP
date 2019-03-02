---
title: fasttrack プロセス
description: fasttrack センターの特典のオンボードプロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0516035e55bc791645b32ad1819839b6c73f1772
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359841"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス
EMS の fasttrack センターの特典の対象となる組織の場合は、fasttrack スペシャリストとリモートで作業して、microsoft Azure Active Directory Premium と microsoft Intune を利用することができます。また、「Azure Information Protection」、「microsoft Cloud App Security」、および「microsoft Advanced Threat Analytics」の[fasttrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からサポートを依頼することもできます。組織が対象となるかどうかについては、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。


次に、オンボードプロセスについて説明します。

-   [オンボードプロセスの概要](EMS-fasttrack-benefit-overview.md)

-   [ソース環境の要件](EMS-source-environment-expectations.md)

-   [オンボードプロセスのフェーズ](EMS-onboarding-phases.md)

-   各フェーズの[fasttrack の責任](EMS-fasttrack-responsibilities.md)

-   各フェーズの[お客様の責任](EMS-your-responsibilities.md)

オンボーディングを終えると、次のような状態になっているはずです。

-   選択したサービスの EMS テナントが作成されます。

-   ライセンスを付与されたユーザーは、次のいずれかの id オプションを使用して EMS サービスにアクセスできます。

    -   クラウド id (一意の EMS アカウント)。

    -   同期 id: Azure active directory Connect ツール (パスワードハッシュ同期またはパススルー認証) を使用して、オンプレミスの active directory から同期された EMS アカウント。このオプションは、1つのフォレストまたは複数の Active Directory フォレストを持つお客様を対象としています。

    -   フェデレーション id: 次のような Microsoft EMS アカウントを使用します。

        -   Azure AD Connect ツールを使用して Active Directory から同期されます。このオプションは、1つの Active Directory フォレスト構成を持つお客様を対象としています。

        -   オンプレミスの active directory から Windows Server 2012 R2 active directory Federation Services (AD FS) 2.0 またはそれ以降のバージョンとのフェデレーション。
