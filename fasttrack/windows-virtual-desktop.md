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
# <a name="windows-virtual-desktop"></a><span data-ttu-id="ac4f5-103">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="ac4f5-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="ac4f5-104"><strong>サービス</strong></span><span class="sxs-lookup"><span data-stu-id="ac4f5-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="ac4f5-105"><strong>FastTrack ガイダンスの詳細</strong></span><span class="sxs-lookup"><span data-stu-id="ac4f5-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="ac4f5-106"><strong>ソース環境要件</strong></span><span class="sxs-lookup"><span data-stu-id="ac4f5-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="ac4f5-107">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="ac4f5-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="ac4f5-108">FastTrack では、Windows 仮想デスクトップの展開ガイダンスを提供し、Windows 10 のマルチセッション エクスペリエンスを利用しながら、Microsoft 365 Apps 用に最適化された Enterprise と統合されたセキュリティと管理を備えた Microsoft 365 のデスクトップとアプリの仮想化サービスに簡単に参加できます。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="ac4f5-109">次の目的で FastTrack スペシャリストと連携します。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-110">以下を使用して、Windows 10 Enterpriseセッション + Microsoft 365 Appsを使用Enterprise WVD 環境を展開します。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-111">Azure Marketplace イメージ</span><span class="sxs-lookup"><span data-stu-id="ac4f5-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-112">共有イメージ</span><span class="sxs-lookup"><span data-stu-id="ac4f5-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-113">Office展開Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="ac4f5-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="ac4f5-114">FSLogix を構成する</span><span class="sxs-lookup"><span data-stu-id="ac4f5-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-115">プロファイル コンテナーを使用して FSLogix エージェントを展開する</span><span class="sxs-lookup"><span data-stu-id="ac4f5-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-116">FSLogix エージェントをコンテナーでOfficeする</span><span class="sxs-lookup"><span data-stu-id="ac4f5-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-117">コンテンツの除外を使用して FSLogix フォルダーを構成する</span><span class="sxs-lookup"><span data-stu-id="ac4f5-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="ac4f5-118">Microsoft Edge の展開</span><span class="sxs-lookup"><span data-stu-id="ac4f5-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-119">展開Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="ac4f5-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-120">Connectデスクトップ クライアントWindows使用する方法</span><span class="sxs-lookup"><span data-stu-id="ac4f5-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="ac4f5-121"><strong>以下はスコープ外です</strong></span><span class="sxs-lookup"><span data-stu-id="ac4f5-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-122">Project仮想デスクトップ展開のWindows管理。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-123">オンサイト サポート。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-124">サード パーティ製アプリケーションの仮想化/展開。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-125">カスタム イメージ。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-126">VMware と Citrix が関係する移行とシナリオ。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-127">Linux のシナリオ。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-128">ユーザー プロファイルの変換または移行。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="ac4f5-129">これらのサービス <a href="https://go.microsoft.com/fwlink/?linkid=2080150">のサポートについては、Microsoft パートナー</a> にお問い合わせください。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="ac4f5-130">次の情報が既に必要です。</span><span class="sxs-lookup"><span data-stu-id="ac4f5-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="ac4f5-131">WVD ライセンス要件</span><span class="sxs-lookup"><span data-stu-id="ac4f5-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="ac4f5-132">Azure Networking:</span><span class="sxs-lookup"><span data-stu-id="ac4f5-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-133">VNET の作成 &amp; サブネット化</span><span class="sxs-lookup"><span data-stu-id="ac4f5-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-134">ファイアウォール/ネットワーク セキュリティ グループ</span><span class="sxs-lookup"><span data-stu-id="ac4f5-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="ac4f5-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-136">オンプレミスから Azure へのルーティング</span><span class="sxs-lookup"><span data-stu-id="ac4f5-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-137">WVD への接続を許可するファイアウォールルール</span><span class="sxs-lookup"><span data-stu-id="ac4f5-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="ac4f5-138">ドキュメント リファレンス</span><span class="sxs-lookup"><span data-stu-id="ac4f5-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="ac4f5-139">Azure Active Directory一般的なセットアップ</span><span class="sxs-lookup"><span data-stu-id="ac4f5-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-140">ID 戦略 <strong>(次の 3 つのオプションの 1 つのみを選択)</strong></span><span class="sxs-lookup"><span data-stu-id="ac4f5-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="ac4f5-141">Azure での Azure AD Connect Active Directory</span><span class="sxs-lookup"><span data-stu-id="ac4f5-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-142">オンプレミスの Azure AD Connect Active Directory over VPN / ER</span><span class="sxs-lookup"><span data-stu-id="ac4f5-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="ac4f5-143">Active Directory ドメイン サービス</span><span class="sxs-lookup"><span data-stu-id="ac4f5-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
