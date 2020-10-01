**Windows Virtual Desktop**

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
<td><p>FastTrack では、Microsoft 365 の統合されたセキュリティと管理により、エンタープライズ向けの M365 アプリ用に最適化された Windows 10 のマルチセッション機能を活用しながら、このデスクトップおよびアプリの仮想化サービスを使いやすくするために、Windows 仮想デスクトップの展開に関するガイダンスを提供しています。</p>
<p>次の目的で FastTrack スペシャリストと連携します。</p>
<ul>
<li><p>次のものを使用して、エンタープライズ向けの Windows 10 Enterprise マルチセッション + M365 アプリを使用して WVD 環境を展開します。</p>
<ul>
<li><p>Azure Marketplace イメージ</p></li>
<li><p>共有画像</p></li>
<li><p>Office 展開ツールキット (ODT)</p></li>
</ul></li>
<li><p>FSLogix を構成する</p>
<ul>
<li><p>プロファイルコンテナーを使用して FSLogix エージェントを展開する</p></li>
<li><p>Office コンテナーと共に FSLogix エージェントを展開する</p></li>
<li><p>コンテンツ除外を使用して FSLogix フォルダーを構成する</p></li>
</ul></li>
<li><p>Microsoft Edge を展開する</p></li>
<li><p>Microsoft Teams を展開する</p></li>
<li><p>Windows 仮想デスクトップクライアントを使用して接続する</p></li>
</ul>
<p><strong>次の範囲外です</strong></p>
<ul>
<li><p>お客様の Windows 仮想デスクトップ展開のプロジェクト管理。</p></li>
<li><p>オンサイト サポート。</p></li>
<li><p>サードパーティ製のアプリケーションの仮想化/展開。</p></li>
<li><p>カスタムイメージ。</p></li>
<li><p>VMware および Citrix に関連する移行とシナリオ。</p></li>
<li><p>Linux シナリオ。</p></li>
<li><p>ユーザープロファイルの変換または移行。</p></li>
</ul>
<p>これらのサービスについては、 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft パートナー</a>にお問い合わせください   。</p></td>
<td><p>既に次のものがあるはずです。</p>
<ul>
<li><p><a href="https://docs.microsoft.com/en-us/azure/virtual-desktop/overview#requirements">WVD ライセンスの要件</a></p></li>
<li><p>Azure ネットワーク:</p>
<ul>
<li><p>VNET 作成 &amp; サブネット化</p></li>
<li><p>ファイアウォール/ネットワークセキュリティグループ</p></li>
<li><p>VPN/ExpressRoute</p></li>
<li><p>オンプレミスから Azure へのルーティング</p></li>
<li><p>WVD への接続を許可するファイアウォールルール</p>
<ul>
<li><p><a href="https://docs.microsoft.com/en-us/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs リファレンス</a></p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory の全般セットアップ</p>
<ul>
<li><p>Id 戦略 <strong>(次の3つのオプションのうち1つのみを選択します)</strong></p>
<ul>
<li><p>Azure AD Connect を含む Active Directory</p></li>
<li><p>VPN/ER 経由の Azure AD Connect オンプレミスを含む Active Directory</p></li>
<li><p>Active Directory ドメイン サービス</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
