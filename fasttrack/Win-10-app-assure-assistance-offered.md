---
title: 提供されているサポート
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: Windows 10 または Microsoft 365 のサービスを購入すると、Windows 10 や Microsoft 365 アプリを展開し、最新の状態を保つための FastTrack スペシャリストによるアドバイスと修復ガイダンスが (対象のサブスクリプションでは) 無償で提供されます。
ms.openlocfilehash: 5252f880f126dd20de792e5cbdb18abc2473764d
ms.sourcegitcommit: dd7b2975ade7feaa12be079c8e54fa5612383538
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/22/2020
ms.locfileid: "48206254"
---
# <a name="assistance-offered"></a>提供されているサポート  

Windows 10 サービスまたは Microsoft 365 サービスのいずれか (「 [適格性](eligibility.md)」の詳細) を購入すると、「サポートされている microsoft 製品」に記載 [され](#supported-microsoft-products)ているように新しい Microsoft 製品を展開しているときにアプリの互換性の問題が発生した場合に、fasttrack スペシャリストがアドバイスと修復のガイダンスを提供します。

ヘルプを表示するには、[App Assure のサービス要求](https://go.microsoft.com/fwlink/?linkid=2022721)を実行します。

パートナーも顧客の代理として、[FastTrack サイト](https://go.microsoft.com/fwlink/?linkid=780698)からヘルプを取得することができます。 そのために、パートナーはサイトにサインインして、顧客レコードを選択します。[**サービス**] をクリックし、[**App Assure のサポートを要求する**] フォームを完成させます。

> [!NOTE]
> サポートが提供されているのは、繁体字中国語と簡体字中国語 (リソースは標準中国語のみ)、英語、フランス語、ドイツ語、イタリア語、日本語、韓国語、ポルトガル語 (ブラジル)、スペイン語です。 

## <a name="supported-microsoft-products"></a>サポートされる Microsoft 製品

FastTrack は、次の Microsoft 製品に展開されたアプリの修復支援を提供します。

### <a name="windows-10-and-microsoft-365-apps"></a>Windows 10 および Microsoft 365 アプリ

- Windows 7、Windows 8.1、Office 2010、Office 2013 で動作するアプリは、Windows 10 および Microsoft 365 アプリでも動作します。

### <a name="windows-10-on-arm"></a>ARM 版 Windows 10

- Windows 7、Office 2010、またはそれ以降のバージョンで動作していたアプリは、ARM64 デバイス上の Windows 10 および Microsoft 365 アプリで動作します。

> [!NOTE]
> ARM に準拠していないソフトウェアドライバーに依存しているか、OpenGL または OpenCL を使用しているか、または64ビット (x64) でのみ使用可能であることを示す、Windows 10 での Windows 10 の除外と制限事項があります。

### <a name="the-new-microsoft-edge"></a>新しい Microsoft Edge

- Web アプリまたはサイトが Internet Explorer 11、サポート対象バージョンの Google Chrome、または Microsoft Edge のいずれかのバージョンで動作する場合、それらは新しい Microsoft Edge でも動作します。

Microsoft Edge の展開に関するガイダンスについては、「[Microsoft Edge チャネルの概要](https://docs.microsoft.com/DeployEdge/microsoft-edge-channels)」を参照してください。 Web は常に進化しているため、既知の [Microsoft Edge のサイト互換性に影響を与える変更](https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes)のリストを公開しています。

### <a name="windows-virtual-desktop"></a>Windows Virtual Desktop に移動します。

- Windows Server リモート デスクトップ セッション ホスト (RDSH) で実行される仮想アプリは、Windows Virtual Desktop の一部として Windows 10 Enterprise マルチセッションでも実行されます。
- Windows 7 または Windows 10 の仮想デスクトップインフラストラクチャ (VDI) 環境で実行されているアプリは、windows 7 Enterprise および windows 10 Enterprise で Windows 仮想デスクトップの一部としても実行されます。
- Windows 7 または Windows 10 クライアント デバイスで実行されているアプリは、Windows Virtual Desktop の一部として Windows 7 Enterprise および Windows 10 Enterprise でも実行されます。

> [!NOTE]
> Windows 10 Enterprise マルチセッションの互換性の除外および制限には次のものが含まれます。 
> - ハードウェアのリダイレクトの制限。
> - 音声ビデオを集中的に使用するアプリは、パフォーマンスが低下する可能性があります。
> - 64 ビット Windows Virtual Desktop では、16 ビット アプリはサポートされていません。

詳細については、「[Windows Virtual Desktop とは何ですか?](https://docs.microsoft.com/azure/virtual-desktop/overview)」および「[Windows 10 Enterprise マルチセッションの FAQ](https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq)」を参照してください。

> [!NOTE]
> FastTrack は、互換性の問題を解決するために合理的な範囲であらゆる努力を払います。 

## <a name="out-of-scope"></a>対象外

FastTrack サービスには含まれません:
- アプリのインベントリと、Windows 10 と Microsoft 365 アプリで何が動作し、何が動作しないかを判断するためのテスト。 このプロセスのガイダンスについては、[デスクトップ展開センター](https://go.microsoft.com/fwlink/?linkid=2080140) を参照してください。 詳細なアップグレードの準備状況の評価に興味がある場合、[Customer Request for Modern Desktop Assessment](https://go.microsoft.com/fwlink/?linkid=2053818) のフォームを完了してください。
- サード パーティ製の ISV アプリの Windows 10 との互換性に関する調査とサポートに関する声明。 詳細については、「[Desktop Analytics とは](https://docs.microsoft.com/sccm/desktop-analytics/overview)」を参照してください。
- アプリのパッケージ化専用サービス。 ただし、App Assure チームでは、お客様の環境でアプリが展開できるように Windows 10 向けに修復したアプリはパッケージ化します。

お客様の責任範囲:
- アプリ インベントリの作成。
- Windows 10 および Microsoft 365 アプリでの当該アプリの検証。

> [!NOTE]
> Microsoft はお客様のソース コードを変更することはできません。 ただし、App Assure チームでは、ソース コードがアプリで使用可能な場合はアプリ開発者に対してガイダンスを提供することができます。

> [!NOTE]
> 対象外となっているサービスに関してサポートが必要な場合は、[Microsoft パートナー](https://go.microsoft.com/fwlink/?linkid=2080150)にお問い合わせください。


