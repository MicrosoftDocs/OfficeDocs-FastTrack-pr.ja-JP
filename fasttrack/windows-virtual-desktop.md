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
# <a name="windows-virtual-desktop"></a><span data-ttu-id="5dedf-103">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="5dedf-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5dedf-104"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="5dedf-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="5dedf-105"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="5dedf-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="5dedf-106"><strong>ソース環境要件</strong></span><span class="sxs-lookup"><span data-stu-id="5dedf-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5dedf-107">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="5dedf-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="5dedf-108">FastTrack は、Microsoft 365 のセキュリティと管理が統合された Microsoft 365 Apps for Enterprise 向けに最適化された Windows 10 マルチセッション エクスペリエンスを活用しながら、このデスクトップとアプリの仮想化サービスに簡単にオンボードするのに役立つ Windows Virtual Desktop 展開ガイダンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="5dedf-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="5dedf-109">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="5dedf-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-110">以下を使用して、Windows 10 Enterprise マルチセッション + Microsoft 365 Apps for Enterprise を使用して WVD 環境を展開します。</span><span class="sxs-lookup"><span data-stu-id="5dedf-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-111">Azure Marketplace イメージ</span><span class="sxs-lookup"><span data-stu-id="5dedf-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="5dedf-112">共有イメージ</span><span class="sxs-lookup"><span data-stu-id="5dedf-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="5dedf-113">Office展開Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="5dedf-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="5dedf-114">FSLogix を構成する</span><span class="sxs-lookup"><span data-stu-id="5dedf-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-115">プロファイル コンテナーを使用して FSLogix エージェントを展開する</span><span class="sxs-lookup"><span data-stu-id="5dedf-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="5dedf-116">FSLogix エージェントをコンテナーでOfficeする</span><span class="sxs-lookup"><span data-stu-id="5dedf-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="5dedf-117">コンテンツの除外を使用して FSLogix フォルダーを構成する</span><span class="sxs-lookup"><span data-stu-id="5dedf-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="5dedf-118">Microsoft Edge の展開</span><span class="sxs-lookup"><span data-stu-id="5dedf-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="5dedf-119">Microsoft Teams の展開</span><span class="sxs-lookup"><span data-stu-id="5dedf-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="5dedf-120">Windows 仮想デスクトップ クライアントを使用した接続</span><span class="sxs-lookup"><span data-stu-id="5dedf-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="5dedf-121"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="5dedf-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-122">お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</span><span class="sxs-lookup"><span data-stu-id="5dedf-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-123">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="5dedf-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-124">サード パーティ製アプリケーションの仮想化/展開。</span><span class="sxs-lookup"><span data-stu-id="5dedf-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-125">カスタム イメージ。</span><span class="sxs-lookup"><span data-stu-id="5dedf-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-126">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="5dedf-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-127">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="5dedf-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="5dedf-128">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="5dedf-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="5dedf-129">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="5dedf-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="5dedf-130">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="5dedf-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD ライセンス要件</a></span><span class="sxs-lookup"><span data-stu-id="5dedf-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="5dedf-132">Azure Networking:</span><span class="sxs-lookup"><span data-stu-id="5dedf-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-133">VNET の作成 &amp; サブネット化</span><span class="sxs-lookup"><span data-stu-id="5dedf-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="5dedf-134">ファイアウォール/ネットワーク セキュリティ グループ</span><span class="sxs-lookup"><span data-stu-id="5dedf-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="5dedf-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="5dedf-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="5dedf-136">オンプレミスから Azure へのルーティング</span><span class="sxs-lookup"><span data-stu-id="5dedf-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="5dedf-137">WVD への接続を許可するファイアウォールルール</span><span class="sxs-lookup"><span data-stu-id="5dedf-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">ドキュメント リファレンス</a></span><span class="sxs-lookup"><span data-stu-id="5dedf-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="5dedf-139">Azure Active Directory の全般セットアップ</span><span class="sxs-lookup"><span data-stu-id="5dedf-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-140">ID 戦略 <strong>(次の 3 つのオプションの 1 つのみを選択)</strong></span><span class="sxs-lookup"><span data-stu-id="5dedf-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="5dedf-141">Azure での Active Directory AD接続</span><span class="sxs-lookup"><span data-stu-id="5dedf-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="5dedf-142">Azure を使用した Active Directory AD VPN /ER を使用してオンプレミスに接続する</span><span class="sxs-lookup"><span data-stu-id="5dedf-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="5dedf-143">Active Directory ドメイン サービス</span><span class="sxs-lookup"><span data-stu-id="5dedf-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
