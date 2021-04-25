---
title: Windows Virtual Desktop
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack には、このデスクトップにオンボードするのに役立つ Windows Virtual Desktop 展開ガイダンスが提供されています。
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996240"
---
# <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>サービス</strong></th>
<th><strong>FastTrack ガイダンスの詳細</strong></th>
<th><strong>ソース環境要件</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows Virtual Desktop</td>
<td><p>FastTrack は、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化された Windows 10 マルチセッション エクスペリエンスを活用しながら、このデスクトップとアプリの仮想化サービスに簡単にオンボードするのに役立つ Windows Virtual Desktop 展開ガイダンスを提供します。</p>
<p>次の目的で FastTrack スペシャリストと連携します。</p>
<ul>
<li><p>以下を使用して、Windows 10 Enterprise マルチセッション + Microsoft 365 Apps for Enterprise を使用して WVD 環境を展開します。</p>
<ul>
<li><p>Azure Marketplace イメージ</p></li>
<li><p>共有イメージ</p></li>
<li><p>Office展開Toolkit (ODT)</p></li>
</ul></li>
<li><p>FSLogix を構成する</p>
<ul>
<li><p>プロファイル コンテナーを使用して FSLogix エージェントを展開する</p></li>
<li><p>FSLogix エージェントをコンテナーでOfficeする</p></li>
<li><p>コンテンツの除外を使用して FSLogix フォルダーを構成する</p></li>
</ul></li>
<li><p>Microsoft Edge の展開</p></li>
<li><p>Microsoft Teams の展開</p></li>
<li><p>Windows 仮想デスクトップ クライアントを使用した接続</p></li>
</ul>
<p><strong>以下はスコープ外です</strong></p>
<ul>
<li><p>お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</p></li>
<li><p>オンサイト サポート。</p></li>
<li><p>サード パーティ製アプリケーションの仮想化/展開。</p></li>
<li><p>カスタム イメージ。</p></li>
<li><p>VMware と Citrix が関係する移行とシナリオ。</p></li>
<li><p>Linux のシナリオ。</p></li>
<li><p>ユーザー プロファイルの変換または移行。</p></li>
</ul>
<p>これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</p></td>
<td><p>次の情報が既に必要です。</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD ライセンス要件</a></p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>VNET の作成 &amp; サブネット化</p></li>
<li><p>ファイアウォール/ネットワーク セキュリティ グループ</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>オンプレミスから Azure へのルーティング</p></li>
<li><p>WVD への接続を許可するファイアウォールルール</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">ドキュメント リファレンス</a></p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory の全般セットアップ</p>
<ul>
<li><p>ID 戦略 <strong>(次の 3 つのオプションの 1 つのみを選択)</strong></p>
<ul>
<li><p>Azure での Active Directory AD接続</p></li>
<li><p>Azure を使用した Active Directory AD VPN /ER を使用してオンプレミスに接続する</p></li>
<li><p>Active Directory ドメイン サービス</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
