---
title: オンボーディング フェーズ
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Windows 10 オンボーディングには、開始、評価、修復、有効化の 4 つの主なフェーズがあります。
ms.openlocfilehash: e0edad16976fadbe33cee95af5f90d5c02f6bf61
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054100"
---
# <a name="onboarding-phases"></a>オンボーディング フェーズ

Windows 10 オンボーディングには、開始、評価、修復、有効化の 4 つの主なフェーズがあります。

## <a name="initiate"></a>開始する

このフェーズで、オンボーディング プロセスについて説明し、データを検証して、キックオフ ミーティングを設定します。 これには、Windows 10 の目的を理解するための作業が含まれています。

## <a name="assess"></a>評価する

FastTrack のスペシャリストはお客様と作業し、ソース環境と要件を評価します。 System Center Configuration Manager が必要なレベルにアップグレードされていることを確認し、Windows 10 の展開をサポートします。 

Windows 10 のアプリの評価において推奨されるオプションを提供します。

FastTrack では、Configuration Manager で Office 365 の準備ダッシュボードを利用するか、Office のスタンドアロンの準備ツールキットを使用して、Office 365 ProPlus 互換性評価を行うこともできます。 利用可能なサービスの詳細については、「[Office 365 用 FastTrack Center 特典](O365-fasttrack-benefit-for-office-365.md)」を参照してください。 

## <a name="remediate"></a>修復する

ソース環境に基づいて修復タスクを行い、オンボーディングの要件を満たすことができます。 環境を整え、これらの要素が展開を成功させるのにソース環境を最小要件にしていることを検証する修復チェックリストを提供します。 

## <a name="enable"></a>有効にする

FastTrack は、必要なデバイスのハードウェア要件を満たしている限り、既存のデバイスを Windows 10 Enterprise にアップグレードするガイダンスを提供します。 アップグレード ガイダンスが用意されており、既存の展開の動きをサポートします。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) の展開シナリオでも使用できます。 

Office 365 ProPlus の展開方法について説明し、Configuration Manager を Windows 10 の展開の一部として使用します。 関連するサービスの詳細については、「[Office 365 ProPlus](O365-onboarding-and-migration.md#office-365-proplus)」を参照してください。

既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Office 365 ProPlus を常に最新の状態に保つためのガイダンスを提供します。

> [!NOTE]
> 展開および保守用の既存のプランやプロセスがない場合は、インプレース アップグレード シナリオ (推奨) または [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) に基づいて、ベストプラクティスのガイダンスを提供できます。

## <a name="out-of-scope"></a>対象外

FastTrack では以下について説明していません。

- Configuration Manager の Current Branch へのアップグレード。
- Windows 10 展開用のカスタム画像の作成。
- Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。
- Windows 10 のセキュリティ機能の有効化。 
- Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。
- Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。
- ユーザー状態移行ツール (USMT) の使用。

  > [!NOTE]
  > 対象外となっているサービスに関してサポートが必要な場合は、[Microsoft パートナー](https://go.microsoft.com/fwlink/?linkid=2080150)にお問い合わせください。

 