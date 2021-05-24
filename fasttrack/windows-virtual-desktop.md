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
description: FastTrack には、Windowsデスクトップへのオンボードに役立つ仮想デスクトップ展開ガイダンスが提供されています。
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592440"
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
<td><p>FastTrack では、Windows 仮想デスクトップの展開ガイダンスを提供し、Windows 10 のマルチセッション エクスペリエンスを利用しながら、Microsoft 365 Apps 用に最適化された Enterprise と統合されたセキュリティと管理を備えた Microsoft 365 のデスクトップとアプリの仮想化サービスに簡単に参加できます。</p>
<p>次の目的で FastTrack スペシャリストと連携します。</p>
<ul>
<li><p>以下を使用して、Windows 10 Enterpriseセッション + Microsoft 365 Appsを使用Enterprise WVD 環境を展開します。</p>
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
<li><p>展開Microsoft Teams</p></li>
<li><p>Connectデスクトップ クライアントWindows使用する方法</p></li>
</ul>
<p><strong>以下はスコープ外です</strong></p>
<ul>
<li><p>Project仮想デスクトップ展開のWindows管理。</p></li>
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
<li><p>[WVD ライセンス要件](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>VNET の作成 &amp; サブネット化</p></li>
<li><p>ファイアウォール/ネットワーク セキュリティ グループ</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>オンプレミスから Azure へのルーティング</p></li>
<li><p>WVD への接続を許可するファイアウォールルール</p>
<ul>
<li><p>[ドキュメント リファレンス](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory一般的なセットアップ</p>
<ul>
<li><p>ID 戦略 <strong>(次の 3 つのオプションの 1 つのみを選択)</strong></p>
<ul>
<li><p>Azure での Azure AD Connect Active Directory</p></li>
<li><p>オンプレミスの Azure AD Connect Active Directory over VPN / ER</p></li>
<li><p>Active Directory ドメイン サービス</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
