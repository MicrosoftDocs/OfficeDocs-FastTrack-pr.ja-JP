---
title: オンボーディング フェーズ
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Windows 10 オンボーディングには、開始、評価、修復、有効化の 4 つの主なフェーズがあります。
ms.openlocfilehash: 6cbfe4b41fa3e6dfdb8b69787d1d70672e0b19c2
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776943"
---
# <a name="onboarding-phases"></a>オンボーディング フェーズ

Windows 10 オンボーディングには、開始、評価、修復、有効化の 4 つの主なフェーズがあります。

## <a name="initiate"></a>開始する

このフェーズで、オンボーディング プロセスについて説明し、データを検証して、キックオフ ミーティングを設定します。 これには、Windows 10 の目的を理解するための作業が含まれています。

## <a name="assess"></a>評価する

FastTrack のスペシャリストはお客様と作業し、ソース環境と要件を評価します。 Microsoft Endpoint Configuration Manager が必要なレベルにアップグレードされていることを確認し、Windows 10 の展開をサポートします。 

Windows 10 のアプリの評価において推奨されるオプションを提供します。 FastTrack では、デスクトップ分析の使用を有効にするためのガイダンスと、デスクトップ分析の展開計画を作成する方法について説明します。

FastTrack では、Configuration Manager で Office 365 の準備ダッシュボードを利用するか、Office のスタンドアロンの準備ツールキットを使用して、Microsoft 365 アプリ互換性評価を行うこともできます。 利用可能なサービスの詳細については、「[Office 365 用 FastTrack Center 特典](O365-fasttrack-benefit-for-office-365.md)」を参照してください。 

FastTrack では、Microsoft Intune を使用して Configuration Manager をクラウドで接続するか、それとも単独のクラウド管理ソリューションとして Intune を展開するなど、最新の管理戦略の評価も行います。

## <a name="remediate"></a>修復する

ソース環境に基づいて修復タスクを行い、オンボーディングの要件を満たすことができます。 環境を整え、これらの要素が展開を成功させるのにソース環境を最小要件にしていることを検証する修復チェックリストを提供します。 

## <a name="enable"></a>有効にする

FastTrack は、必要なデバイスのハードウェア要件を満たしている限り、既存のデバイスを Windows 10 Enterprise にアップグレードするガイダンスを提供します。 アップグレード ガイダンスが用意されており、既存の展開の動きをサポートします。 FastTrack では、Windows 10 へのインプレース アップグレードのガイダンスをお勧めし、提供しています。 また、Windows のクリーン画像インストールと [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) の展開シナリオでも使用できます。 

Microsoft 365 アプリの展開方法について説明し、Configuration Manager を Windows 10 の展開の一部として使用します。 関連するサービスの詳細については、「[Microsoft 365 アプリ](O365-onboarding-and-migration.md#microsoft-365-apps)」を参照してください。

既存の Configuration Manager 環境または Microsoft 365 を使用して、組織が Windows 10 Enterprise および Microsoft 365 アプリを常に最新の状態に保つためのガイダンスを提供します。

必要な場面で FastTrack を使用すれば、お客様は Configuration Manager を Intune にクラウドで接続したり、Intune をスタンドアロンで展開したりして、最新の管理を行うことができます。 関連するサービスの詳細については、「[Enterprise Mobility + Security (EMS) 向け FastTrack Center の特典プロセス](EMS-fasttrack-process.md)」を参照してください。

> [!NOTE]
> 展開および保守用の既存のプランやプロセスがない場合は、インプレース アップグレード シナリオ (推奨) または [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) に基づいて、ベストプラクティスのガイダンスをご提供できます。

## <a name="out-of-scope"></a>対象外

FastTrack では以下については説明していません。

- Configuration Manager の Current Branch へのアップグレード。
- Windows 10 展開用のカスタム画像の作成。
- Windows 10 の展開用の展開スクリプトの作成とサポート。
- Windows 10 システムの BIOS から Unified Extensible Firmware Interface (UEFI) への変換。
- Windows 10 のセキュリティ機能の有効化。 
- Preboot Execution Environment (PXE) ブートの Windows 展開サービス (WDS) の構成。
- Microsoft Deployment Toolkit (MDT) を使用した、Windows 10 の画像の取得、展開。
- ユーザー状態移行ツール (USMT) の使用。

  > [!NOTE]
  > 対象外となっているサービスに関してサポートが必要な場合は、[Microsoft パートナー](https://go.microsoft.com/fwlink/?linkid=2080150)にお問い合わせください。

 