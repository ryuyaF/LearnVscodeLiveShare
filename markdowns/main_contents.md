## [LiveShare](https://visualstudio.microsoft.com/ja/services/live-share/)とは

マイクロソフトが提供している軽量エディタ`VisualStudioCode`の拡張機能です。

--

### 主な機能

<div class="r-stack">
    <div class="fragment fade-out" data-fragment-index="0">
        <img src="https://gyazo.com/c70430551f3336698dd66753e298cdc6.png">
    </div>
    <div class="fragment" data-fragment-index="0">
        <img src="https://gyazo.com/3bfbaec2d013df582d39c5f03f91ac4c.png">
        <small>赤枠で囲ってあるのが特におすすめの機能です。</small>
    </div>
</div>
※画像は公式サイトのものを引用しています


Note:
主な機能をざっと説明する。
特におすすめしたいのが赤枠で囲まれた2つ。

>>>Page

### LiveShareのインストール

--

### 必要なもの

- VSCode(バージョン: 1.22.0以上) ※ここは省略
- LiveShare(VSCode上でインストール)

--

### インストール方法
<img class="r-stretch" src="https://i.gyazo.com/b5c48903d24d3eeac34a5d5ff1be30d4.png">
<p>※インストール後、再起動してください。</p>

--

### インストール方法

<img class="r-stretch" src="https://i.gyazo.com/4c5b4f3ff2ba07466295efa8a6db9deb.png">
<p>インストールできれば、サイドペインにLiveShareのアイコンが追加されています。</p>


--

### サインイン

<img class="" src="https://gyazo.com/0e88bf7ab533110b66222b45e212afd8.png">

<img class="" src="https://gyazo.com/6a118c88abe1a322f81643c8b5daec42.png">

LiveShareをホストとして使用するためには `GitHub` か `Microsoft`のどちらかにサインインする必要があります。
(セッションへの参加のみであればサインインは不要です)


--

### サインイン

<img class="r-stretch" src="https://gyazo.com/99db0952d04b23b1ad028eb5966bb592.png">

このように選択したアカウントでVSCodeにアクセスする権限を求めてきますので、承諾してあげます。
(私はGitHubでサインインしました。)

--

### サインイン

<img class="r-stretch" src="https://gyazo.com/1c080e9b9676e1dc6091b5b85d181486.png">

承諾すると、VSコードに戻るダイアログが出ることがあります。
そのまま開いてください。

--

### サインイン

<img class="r-strech" src="https://gyazo.com/aee2cc9d3ed039b926474aaf17580254.png">

VSCodeに戻ると、サインインが完了し、左下のLiveShareステータスが `サインイン状態` になっています。

--

### これで準備完了です

自分がホストになったり、他の方のLiveに参加することができるようになりました。


>>>Page

### LiveShareを使ってみる

自分がホストになってLiveShareを体験してみましょう。

<small>※ここからは複数人もしくは複数端末での操作を想定しています。</small>

--

### セッションの開始

<img src="https://gyazo.com/6ea0b0fda32c3dc84023fe72f8d397a0.png">

--

### セッションの開始

<img src="https://gyazo.com/aa7296cbd21640b7b2dffc79f48245cd.png">

セッションが開始されると右下にこのようなメッセージが出てきます。
クリップボードに招待用のURLがコピーされているので、招待したい方とURLを共有します。

--

### セッションの開始

<img src="https://gyazo.com/181f9a84c5ee66e373ea7475ee5fe3eb.png">

招待用URLはここからもコピーできます。

--

### セッションの開始

<img class="r-stretch" src="https://gyazo.com/87720f5ca2038dabb36dcfca28560b01.png">

セッションに誰かが参加するとこのような表示になります。
どのファイルの何行目を見ているか、などが情報として表示されています。

ちなみにユーザーをクリックするとフォロー状態になり、そのユーザーの見ているカーソル位置を一緒に見ることが出来ます。

--

### 共同編集

共同編集を試してみましょう。

読み取り専用でセッションを開始していなければ、セッションに参加したユーザーは自由にソースを編集することが出来ます。(保存も可)

--

### 共同編集

<video data-autoplay src="https://i.gyazo.com/27ef49b33056876476c8b97c6961e800.mp4"></video>

ここのセクションを自由に編集して、共同編集を体験してください。
👍

--

### サーバーの共有

個人的にかなり気に入っている機能です。

ホストのPC上で稼働しているサーバーやDBをセッションの参加者に対して開放することが出来ます。

ホストのサーバーを共有できれば、デバッグや確認などがすぐに行えるため、とても重宝する機能です。

--

### サーバーの共有

<img class="r-stretch" src="https://gyazo.com/854b7dbe44030ab806d18968158c0782.png">

--

### サーバーの共有

<img class="r-stretch" src="https://gyazo.com/0b5818049b7bcf862537b28e6f49cfae.png">

共有したいローカルのポートを指定(httpから書く)

--

### サーバーの共有

<img class="r-stretch" src="https://gyazo.com/9990825f1e9eca69af0e55c011ef2eca.png">

共有サーバーの名前を設定

--

### サーバーの共有

<img src="https://gyazo.com/7344b01f3fb6c1e0e16311180a9b4d7e.png">

このように共有サーバーが追加されていれば成功です。

参加者はこれをクリックして、手元の端末で動作を確認することが出来ます。

--

### サーバーの共有

ぜひ他の方とサーバーを共有して動作を確認してみてください。(もしくは複数端末で)


>>>Page

LiveShareの紹介と共有体験は以上になります。

このスライドを見ていただきありがとうございました！