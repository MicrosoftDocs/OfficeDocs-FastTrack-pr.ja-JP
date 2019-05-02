---
title: FastTrack プロセス
description: FastTrack センターの特典のオンボードプロセスの概要
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513776"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス
EMS の FastTrack センター特典の対象となる組織の場合は、FastTrack スペシャリストとリモートで作業して、Microsoft Azure Active Directory Premium、Microsoft Intune、および Azure Information Protection を入手することができます。 また、「Azure Information Protection」、「Microsoft Cloud App Security」、および「Microsoft Advanced Threat Analytics」の[Fasttrack サイト](https://www.microsoft.com/fasttrack/microsoft-365/ems)からサポートを依頼することもできます。 組織が対象となるかどうかについては、「[対象となるサービスとプラン](M365-eligible-services-and-plans.md)」を参照してください。


次に、オンボードプロセスについて説明します。

-   [オンボードプロセスの概要](EMS-fasttrack-benefit-overview.md)

-   [ソース環境に対する期待](EMS-source-environment-expectations.md)

-   [オンボードプロセスのフェーズ](EMS-onboarding-phases.md)

-   各フェーズの[Fasttrack の責任](EMS-fasttrack-responsibilities.md)

-   各フェーズの[お客様の責任](EMS-your-responsibilities.md)

オンボードが完了すると、次のようなことが予想されます。

-   選択したサービスの EMS テナントが作成されます。

-   ライセンスを付与されたユーザーは、次のいずれかの id オプションを使用して EMS サービスにアクセスできます。

    -   クラウド Id (一意の EMS アカウント)。

    -   同期 Id: Azure Active Directory Connect ツール (パスワードハッシュ同期またはパススルー認証) を使用して、オンプレミスの Active Directory から同期された EMS アカウント。 このオプションは、1つのフォレストまたは複数の Active Directory フォレストを持つお客様を対象としています。

    -   フェデレーション Id: 次のような Microsoft EMS アカウントを使用します。

        -   Azure AD Connect ツールを使用して Active Directory から同期されます。 このオプションは、1つの Active Directory フォレスト構成を持つお客様を対象としています。

        -   オンプレミスの Active Directory から Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 またはそれ以降のバージョンとのフェデレーション。

        -   Azure Information Protection を使用して、情報の自動分類と保護を両方とも行うことができます。 

        -   Azure Information Protection スキャナーを使用して、オンプレミスのファイル共有と SharePoint サーバー内の情報を検出できます。 

        -   Azure Key Vault 内で Azure Information Protection のテナントキーを管理する機能。 
