<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

**ページトップの⭐️を押して本リポジトリを支援してください！もっとリソースが欲しいなら[私をフォロー](https://github.com/nas5w)してください！**

もっとフロントエンド開発について学びたいですか？次の考えがあります：

- 私の[無料ニュースレター](https://buttondown.email/devtuts?100DoC)にサインアップしてください。定期的に皆さんが消化しやすい量でフロントエンドの知識を発信しています。
- 私の[YouTubeチャンネル](https://www.youtube.com/c/devtutsco)に登録してください。ここではJavaScript, Typescript, それとReactを教えます。

---

９これは#100DaysOfCode期間中に行うフロントエンド開発のためのちょっとした自習用カリキュラムです。フロントエンド開発の幅広い範囲をカバーし、1つの領域を深堀りするというよりも”調査”スタイルのコースだと思います。最終的に、あなたが本コースを完走することで各トピックに馴染み深くなり、必要に応じてどのトピックにも簡単に深堀りできる能力を得ることになるでしょう。

本カリキュラムはKamran Ahmedの [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c)ロードマップに多大な影響を受けています。是非チェックしてみてください--素晴らしい資料です。

**注意書き**: 私はフロントエンドエンジニアは多くの人にとって様々な意味をもっていることを知っています! もしあなたがフロントエンドエンジニアであり、本ガイドで改善してほしい箇所があるなら、[Contributing](#contributing)セクションの記載内容に従ってissueを立てて私に知らせてください。お願いします!

# 翻訳

驚異的なコントリビューターに感謝します。本カリキュラムは次の言語に翻訳されています！

- [ロシア語](/ru) (翻訳者 [@Ibochkarev](https://github.com/Ibochkarev) と [@JonikUl](https://github.com/JonikUl))
- [中国語](/chinese) (翻訳者 [@simplefeel](https://github.com/simplefeel))
- [ポルトガル語](/portuguese) (翻訳者 [@Zardosh](https://github.com/Zardosh))
- [ポーランド語](/polish) (翻訳者[@mbiesiad](https://github.com/mbiesiad))
- [マレー語/インドネシア語](/Malay) (翻訳者 [@asyraf-labs](https://github.com/asyraf-labs))
- [ベトナム語](/Vietnam) (翻訳者 [@duca7](https://github.com/duca7))

# :calendar: カリキュラム

本リポジトリの基本的な原理は[タイムボックス](https://en.wikipedia.org/wiki/Timeboxing)です。もしあなたが過去にWeb開発や同様の技術を学ぼうとして時間を費やしたことがあるなら、おそらく特定のトピックでハマってしまった経験があるでしょう。本リポジトリは各トピックに一定の日数を割り当てて、その日数が経過したら次のトピックに移るように促すことを目的としています。

このカリキュラムをスタートする際には、みんなの習得度がバラバラであることが予想されますが、これは問題ありません。初心者もベテランフロントエンドエンジニアも各トピックでタイムボックス化された練習をすることで恩恵を受けることができます。

次のスケジュールで進めることをおすすめします：

- 1-8日目: [HTML](#html)
- 9-16日目: [CSS](#css)
- 17-24日目: [JavaScript Basics](#javascript)
- 25-27日目: [jQuery](#jquery)
- 28-33日目: [Responsive Web Design](#rwd)
- 34-36日目: [Accessibility](#accessibility)
- 37-39日目: [Git](#git)
- 40-44日目: [Node and NPM](#node)
- 45-50日目: [Sass](#sass)
- 51-54日目: [Bootstrap](#bootstrap)
- 55日目: [BEM](#bem)
- 57-61日目: [Gulp](#gulp)
- 62-65日目: [Webpack](#webpack)
- 66日目: [ESLint](#eslint)
- 68-83日目: [React](#react)
- 84-89日目: [Redux](#redux)
- 90-94日目: [Jest](#jest)
- 95-97日目: [TypeScript](#typescript)
- 98-100日目: [NextJS](#nextjs)

# :mag_right: 詳細

以下では、カリキュラムの各トピックについての情報と、それぞれのトピックで何をすべきかについてのアイデアや指針を紹介しています。このカリキュラムに沿って行うプロジェクトのアイデアについては、[Project Ideas section](#project-ideas)を確認してください。

タイムボックスの原則の一環として、「学習分野とアイデア」のセクションのすべての項目を完了できなくても構いません。それよりも、各分野に割り当てられた日数を最大限に活用することに集中して、先に進めるべきです。

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

HyperText Markup Language (HTML) は、ウェブページやウェブアプリケーションを作成するための標準的なマークアップ言語です。Cascading Style Sheets (CSS) とJavaScriptと合わせて、World Wide Webの礎となる技術のトライアンドを形成しています。Webブラウザは、WebサーバまたはローカルストレージからHTML文書を受け取り、マルチメディアWebページにレンダリングします。HTMLは、ウェブページの構造を意味的に記述し、元々はドキュメントの外観を表す手がかりを含んでいました。 (出典：[Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Quick Takeaway

HTMLは本当にWeb開発の基本です。たとえJavascriptベースのフレームワークであっても、結局は何らかの形でHTMLを書くことになります。

### :book: 学習分野とアイデア

- freeCodeCampにある [Basic HTML and HTML5 section](https://learn.freecodecamp.org/) に取り掛かりましょう。
- HTMLのページ構造
- HTMLの要素
- HTML要素を入れ子にする
- 意味のあるマークアップ
- リンク / 複数ページ
- 画像
- 音楽/動画媒体
- Formsとform要素
- 複数ページを持ったサイトを作成してみましょう！ (もしインスピレーションが欲しいなら[Project Ideas](#project-ideas)を読んでください)。

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Cascading Style Sheets (CSS)は、HTMLのようなマークアップ言語で書かれた文書の表示を記述するために使用されるスタイルシート言語です。CSSは、HTMLやJavaScriptと並んで、World Wide Webの礎となる技術です。CSSは、レイアウト、色、フォントなど表示するものとコンテンツの分離を可能にするように設計されています。この分離により、コンテンツのアクセシビリティが向上し、プレゼンテーション特性の指定に柔軟性とコントロール性が向上し、関連するCSSを別の.cssファイルで指定することで複数のウェブページでフォーマットを共有することが可能になり、構造的なコンテンツの複雑さや繰り返しを軽減することができます。 (Source: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Quick Takeaway

CSSもウェブ開発には欠かせない要素です。主にHTML要素のスタイル定義や配置に使用されていますが、かつてJavascriptで処理されていたような動的なタスク（アニメーションなど）にも対応できるようになってきています。
### :book: Learning Areas and Ideas

- freeCodeCampの[Basic CSS, CSS flexbox, and CSS grid sections](https://learn.freecodecamp.org/)に取り掛かってみましょう。
- インラインCSS
- `<style>`タグ
- `<link>`を用いた外部CSSの使用
- 要素のスタイル
- セレクター
- FloatとFloatの打ち消し
- レイアウト (grid, flexbox)
- フォント、カスタムフォント
- あなたがHTML学習のときに作成したサイトをCSSでスタイルしてみましょう！

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScriptは、しばしばJSと略される、ECMAScript仕様に準拠した高レベルのインタープリタ型プログラミング言語です。動的で型付けが弱く、プロトタイプベースでマルチパラダイムであることも特徴の言語です。HTMLやCSSと並んで、JavaScriptはWorld Wide Webの3つのコア技術の1つです。JavaScriptはインタラクティブなWebページを可能にするため、Webアプリケーションには欠かせないものとなっています。大多数のWebサイトで使用されており、すべての主要なWebブラウザにはそれを実行するための専用のJavaScriptエンジンが搭載されています。 (出典: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Quick Takeaway

フロントエンドの世界では、JavaScriptの重要性が高まっています。かつては主にページを動的にするために使われていましたが、現在では多くのフロントエンドフレームワークの基盤となっています。これらのフレームワークは、以前バックエンドで処理されていたタスクの多くを処理します (例: ルーティングや異なるビューの表示など)。

### :book: Learning Areas and Ideas

- freeCodeCampの[Basic JavaScript and ES6 sections](https://learn.freecodecamp.org/)に取り掛かりましょう。
- 言語の基礎知識が多すぎるのでここでは挙げられません！
- `<script>`タグと配置
- HTML要素へのアクセス
- イベントループ、コールスタック、イベントキュー
- プロトタイプ継承
- リファレンスと値
- 上記のセクションであなたが作成したHTML/CSSページに動的な要素やロジックを追加してください！

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQueryは、高速で小さく、豊富な機能を持ったJavaScriptライブラリです。多くのブラウザで動作し使いやすいAPIを使用することで、HTMLドキュメントの走査や操作、イベント処理、アニメーション、Ajaxなどの作業をよりシンプルにしてくれます。汎用性と拡張性を兼ね備えたjQueryは、何百万人もの人々が JavaScript を書く方法を変えてきました。(出典: [jQuery.com](https://jquery.com/))

### :bulb: Quick Takeaway

プレーンな (「バニラ」とも呼ばれる) Javascriptをしばらく使っていると、特にHTML要素へのアクセスや操作に関連したタスクが少し面倒に感じることがあるかもしれません。しばらくの間、このようなタスクを容易にし、異なるブラウザ間で一貫性のあるものにするためのライブラリとしてjQueryが使用されていました。現在では、バニラのJavascriptやCSS、新しいJavascriptフレームワークが進歩しているため、jQueryは必ずしも「必須」の学習ではありません（フレームワークについては後ほど説明します）。それでも、少し時間をかけてjQueryを学んで、小さなプロジェクトに応用してみるのは有益でしょう。

### :book: Learning Areas and Ideas

- freeCodeCampの[jQuery section](https://learn.freecodecamp.org/)に取り掛かりましょう。
- ドキュメントの用意
- セレクタ
- クラスの切り替え
- アニメーション
- HTML要素の追加と移動
- あなたのサイトにjQueryを追加してみましょう！

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

レスポンシブ・ウェブ・デザイン（RWD）とは、Webページを様々なデバイスやウィンドウ、スクリーンサイズに対応させるWebデザインのアプローチです。最近の研究では、RWDの延長線上に、ビューイングコンテキストの一部としてビューアの近接性も考慮しています。ユーザビリティと満足度を確保するためには、コンテンツ、デザイン、パフォーマンスがすべてのデバイスにわたって必要です。RWDで設計されたサイトは、流動的でプロポーションベースのグリッド、柔軟な画像、@mediaルールの延長線上にあるCSS3のメディアクエリを使用することで、r利用環境に合わせてレイアウトを適応させています。(出典: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Quick Takeaway

レスポンシブウェブデザインとは、ウェブアプリケーションをあらゆるタイプのデバイス上で適切に表示し、機能させることです。簡単な例を挙げると、ウェブサイトはPCのウェブブラウザと携帯電話のブラウザの両方で適切に表示され、機能しなければなりません。レスポンシブデザインの理解は、フロントエンド開発者にとって非常に重要です！

### :book: Learning Areas and Ideas

- freeCodeCampの[Responsive Web Design Principles section](https://learn.freecodecamp.org/)に取り掛かりましょう。
- メディアクエリ、ブレークポイント
- レスポンシブな画像
- あなたが作成したページをレスポンシブデザインにしてみましょう！
- Chrome DevToolsを使ってあなたが作成したサイトを様々なデバイスやビューポート設定で見てましょう。

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

ウェブアクセシビリティとは、障害を持った人々にとってワールド・ワイド・ウェブ上のウェブサイトとの相互作用やアクセスを妨げる障害がないことを保証する包括的な実践のことです。サイトが正しく設計、開発、編集されていれば、一般的にすべてのユーザーが情報や機能に平等にアクセスできるようになります。(出典: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Quick Takeaway

アクセシビリティ（略してa11yとも）は、フロントエンドのウェブ開発において最も重要なトピックの一つですが、しばしば軽視されているように思います。アクセシブルなWebアプリケーションを作成することは、倫理的に健全であるだけでなく、アプリケーションを見ることができるオーディエンスが増えることを考えると、ビジネス上の意味も大きいと言えます。

### :book: Learning Areas and Ideas

- freeCodeCampの[Applied Accessibility section](https://learn.freecodecamp.org/)に取り掛かりましょう。
- [The A11Y Project](https://a11yproject.com/about)の記事をいくつか読みましょう
- The A11Y Projectの[checklist](https://a11yproject.com/checklist)をレビューしてみましょう
- The A11Y Projectのチェックリストに従って、あなたが作成したサイトのアクセシビリティを向上してみましょう

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Gitはフリーでオープンソースの分散型バージョン管理システムです。小規模なプロジェクトから超大規模なプロジェクトまで、あらゆるものを迅速かつ効率的に処理できるように設計されています。 (出典: [git-scm.com](https://git-scm.com/))

### :bulb: Quick Takeaway

バージョン/コード管理は、ウェブ開発者のツールキットには欠かせないものです。バージョン管理システムにはいくつかの種類がありますが、現在Gitが最も普及しています。Git を使って、学習しながらプロジェクトを追跡管理することができます（そしてそうすべきです！）。

### :book: Learning Areas and Ideas

- [Git Tutorial for Beginners (Video)](https://www.youtube.com/watch?v=HVsySz-h9r4)
- Gitをインストールしましょう
- [Github](https://github.com)アカウントを作成しましょう
- 最も使われるGitコマンドを学びましょう:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- あなたが作成したプロジェクトGithubに追加しましょう！

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

Node.jsは、ブラウザの外でJavaScriptのコードを実行するオープンソースでクロスプラットフォームのJavaScriptランタイム環境です。 JavaScriptは主にクライアントサイドスクリプティングに使用されています。JavaScriptで書かれたスクリプトがWebページのHTMLに埋め込まれ、ユーザーのWebブラウザのJavaScriptエンジンによってクライアントサイドで実行されます。Node.jsを使うことで、開発者はJavaScriptを使ってコマンドラインツールを書いたり、サーバーサイドでスクリプトを実行したりして、ユーザーのWebブラウザにページが送信される前に動的なWebページのコンテンツを生成することができます。その結果、Node.jsは「どこにでもあるJavaScript」のパラダイムを表しており、サーバーサイドとクライアントサイドのスクリプトのための異なる言語ではなく、単一のプログラミング言語におけるWebアプリケーション開発を統一しています。(出典: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Quick Takeaway

Node.jsは一般的にバックエンドのソリューションとして知られていますが、フロントエンド開発のサポートにもかなり頻繁に使用されています。これには、ビルドツールの実行、テスト、リント（すべては近日中に説明します！）など、多くの方法があります。Node Package Manager (npm) はNode のもう一つの素晴らしい機能であり、プロジェクトの依存関係を管理するために使用できます（つまり、プロジェクトが依存する可能性のあるコードライブラリ -- jQuery がその例です！）。

### :book: Learning Areas and Ideas

- ノードとブラウザとの違いを調査してみましょう
- Nodeをインストールしてみましょう (npmも一緒にインストールされます)
- シンプルなJavaScriptファイルを作成して、Nodeで実行してみましょう
- npmを使用して、あなたが作成したプロジェクト(複数可)の依存関係を管理しましょう(例: jQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sassは、生のCSSにパワーとエレガンスを加えたCSSの拡張機能です。Sassは変数、入れ子になったルール、ミックスイン、インラインインポートなどを、CSSと完全に互換性のある構文で使用することができます。Sassは、特にCompassスタイルライブラリの助けを借りて、大規模なスタイルシートを整理したり、小規模なスタイルシートを迅速に作成したりするのに役立ちます。(出典: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Quick Takeaway

Sassを使うと、よりプログラム的な方法でCSSを書くことができます。CSSを書いたことがある人なら、同じカラーコードを指定するなど、結果的に多くの情報を繰り返してしまうことに気づくかもしれません。Sassでは、変数、ループ、ネスティングなどを使用して冗長性を減らし、可読性を高めることができます。Sassでコードを書いた後は、素早く簡単に通常のCSSにコンパイルすることができます。

### :book: Learning Areas and Ideas

- [Install Sass](https://sass-lang.com/install)をnpmでグローバルインストールしましょう！
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- [Learn Sass](https://sass-lang.com/guide)tutorial、もしくは[freeCodeCamp](https://learn.freecodecamp.org/)のSassチュートリアルをやりましょう。
- Sassを使ってあなたの作成したページのCSSをアップデートしましょう！

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* 代用のツール： Foundation, Bulma, Materialize

Bootstrapは、WebサイトやWebアプリケーションを開発するためのフリーでオープンソースのフロントエンドフレームワークです。タイポグラフィ、フォーム、ボタン、ナビゲーション、その他のインターフェースコンポーネントのためのHTMLとCSSベースのデザインテンプレートと、オプションのJavaScript拡張機能が含まれています。 (出典: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Quick Takeaway

ウェブアプリケーションをレイアウトしたり、スタイリングしたり、動的なものにするには多くのオプションがありますが、フレームワークから始めることは、最初の一歩を踏み出すのに非常に役立つことがわかるでしょう。Bootstrapはそのようなフレームワークの一つですが、唯一の選択肢ではありません！このように1つのフレームワークに慣れることをお勧めしますが、1つのフレームワークにとらわれるよりも、HTML、CSS、JavaScriptの基礎を把握することの方がはるかに重要です。

### :book: Learning Areas and Ideas

- Bootstrapとは何か、なぜBootstrapを使いたいのかを学びましょう
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- [freeCodeCamp](https://learn.freecodecamp.org/)のthe Bootstrap sectionを完走しましょう
- Bootstrapを使ってあなたが作成したサイトをリファクタしましょう！

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

Block, Element, Modifier (一般的にBEMと呼ばれる) メソッドは、HTMLとCSSのクラスのための一般的な命名規則です。Yandexのチームによって開発され、その目的は開発者がプロジェクトのHTMLとCSSの関係をよりよく理解できるようにすることにあります。 (出典: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Quick Takeaway

BEMのようなネーミングや組織システムが存在し、なぜそれが使われているのかを知ることは重要です。ここでいくつかの研究をしてみてください、しかし初心者レベルでは、私は主題にあまりにも多くの時間を割くことをお勧めしません。

### :book: Learning Areas and Ideas

- [BEM introduction](http://getbem.com/introduction/)を読みましょう
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- BEM規則を使ってシンプルなサイトを作って見ましょう。

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulpは、開発ワークフローの中で手間のかかるタスクや時間のかかるタスクを自動化するためのツールキットです。そのため、ごちゃごちゃになることなくビルドすることが出来ます。(出典: [gulpjs.com](https://gulpjs.com/))

### :bulb: Quick Takeaway

最近のフロントエンド開発では、バンドル、ファイルの移動、HTMLファイルへの参照の追加などのタスクを自動化する必要があることに気づくでしょう。Gulpはこれらのことを行うのに役立つツールの1つです!

### :book: Learning Areas and Ideas

- npmでGulpをインストールしましょう
- CSS-Tricksの[gulp for beginners tutorial](https://css-tricks.com/gulp-for-beginners/)をフォローしましょう
- あなたが作成したサイトでGulpを設定してみましょう：
  - あなたの設定に合わせたSassをコンパイルしましょう
  - Put the generated CSS file in `build` subdirectory
  - あなたが作成したサイトをビルド用ディレクトリに移動しましょう
  - Inject a reference to your generated CSS file into your web pages

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

その中核をなすwebpackは、最新のJavaScriptアプリケーションのための静的なモジュールバンドルです。webpackがアプリケーションを処理する際には、プロジェクトが必要とするすべてのモジュールをマッピングし、1つ以上のバンドルを生成する依存関係グラフを内部的に構築します。 (出典: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Quick Takeaway

大規模なウェブ開発プロジェクトで、多くの異なる開発者が多くの異なるタスクに取り組んでいると想像してみてください。全員が同じファイルで作業するのではなく、可能な限りモジュール化したいと思うかもしれません。Webpackは、あなたのチームにモジュール化して作業をさせ、アプリケーションを構築する時には、WebpackがHTML、CSS/Sass、JavasScript、画像などをすべて一緒に貼り付けることで、これを可能にします。Webpack は唯一のモジュールバンドルラーではありませんが、現時点ではフロントランナーとなっているようです。

### :book: Learning Areas and Ideas

- [webpack concepts](https://webpack.js.org/concepts/)を読みましょう
- [What is Webpack, How does it work? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [This webpack tutorial](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLintは2013年6月にNicholas C. Zakasによって作成されたオープンソースのJavaScript用リントユーティリティです。コードのリントは静的解析の一種で、問題のあるパターンや特定のスタイルガイドラインに準拠していないコードを見つけるために頻繁に使用されます。ほとんどのプログラミング言語にはコードリンティングがあり、コンパイラはコンパイルプロセスにリントを組み込むことがあります。(出典: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Quick Takeaway

リントは、コードの品質、可読性、一貫性を向上させる素晴らしいツールです。リンターを使用することで、構文やフォーマットの間違いを本番前に発見することができます。リンターは手動で実行することもできますし、ビルド/デプロイのプロセスに組み込むこともできます。

### :book: Learning Areas and Ideas

- npmを使ってESLintをインストールしましょう
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- あなたが書いたJavaScriptコードをLintしてみましょう

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* 代用ツール: Vue, Angular, Ember

React（React.jsまたはReactJSとも呼ばれる）は、ユーザーインターフェイスを構築するためのJavaScriptライブラリです。Facebookや個人の開発者や企業からなるコミュニティによってメンテナンスされています。Reactは、シングルページやモバイルアプリケーションの開発のベースとして使用することができます。複雑なReactアプリケーションを作成する際は基本的に状態管理、ルーティング、APIとのインタラクションのために追加のライブラリを使用する必要があります。(出典: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Quick Takeaway

フロントエンドJavaScriptフレームワークは、現代のフロントエンド開発の最前線にあります。ここで重要なことは、Reactは非常に人気があるにもかかわらずユーザーインターフェイスを構築するためのライブラリに過ぎないのに対し、VueやAngularのようなフレームワークはよりフル機能を目指しているということです。例えば、異なるビューへのルーティングが必要なアプリケーションをReactで構築する場合、`react-router`のようなツールを導入する必要があります。

### :book: Learning Areas and Ideas

- [React tutorial](https://reactjs.org/tutorial/tutorial.html)に取り掛かりましょう
- [Learn React with Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- あなたが作成したサイトをReactアプリにリファクタしましょう！
- 補足: `create-react-app`は新しいReactプロジェクトのベースを作成するのに便利なツールです。

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Reduxは、JavaScriptアプリケーションのための予測可能なステートコンテナです。一貫して動作し、異なる環境（クライアント、サーバー、ネイティブ）でも動作し、さらにテストが容易なアプリケーションを書くのに役立ちます。その上、ライブコード編集とタイムトラベルデバッガを組み合わせたような素晴らしい開発者体験を提供します。(出典: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Quick Takeaway

大規模で大規模なフロントエンドアプリケーションを構築していると、アプリケーションの状態を維持するのが難しいことに気付き始めます（例：ユーザーがログインしているかどうか、ユーザーは誰なのか、アプリケーションで何が起こっているのか）。Reduxは、アプリケーションのロジックのベースとなる状態の単一ソースを維持するのに役立つ素晴らしいライブラリです。

### :book: Learning Areas and Ideas

- [Redux video tutorial](https://www.youtube.com/watch?v=93p3LxR9xfM)
- [Redux video series](https://egghead.io/courses/getting-started-with-redux) 筆者：Dan Abramov（Reduxの作者）
- [Redux three principles](https://redux.js.org/introduction/three-principles)に注意してください
  - 単一の真実のソース
  - Stateは読み取り専用
  - 変更は標準機能で行う
- Reduxの状態管理をあなたが作成したアプリに追加しましょう！

<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest は、シンプルさに焦点を当てた楽しい JavaScript テストフレームワークです。Babel、TypeScript、Node、React、Angular、Vueなどを使ったプロジェクトで動作します！ (出典: [jestjs.io](https://jestjs.io))

### :bulb: Quick Takeaway

フロントエンドプロジェクトでは、自動テストを設定することが非常に重要です。自動テストを設定することで、コードの修正が今後必要になっても自信を持って行うことができます。もし修正を加えてもテストがパスされていれば、既存の機能を壊していないことにかなり安心できるでしょう。テストフレームワークは数え切れないほどありますが、Jestは私のお気に入りの一つです。

### :book: Learning Areas and Ideas

- [Jest basics](https://jestjs.io/docs/en/getting-started)を読んで学びましょう
- もし`create-react-app`を使っているなら, [Jestはすでに設定済みです](https://facebook.github.io/create-react-app/docs/running-tests)。
- あなたが作成したアプリにテストコードを追加してみましょう！

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* 代用できる言語: Flow

TypeScriptはMicrosoftによって開発・保守されているオープンソースのプログラミング言語です。TypeScriptはJavaScriptの厳密で構文的なスーパーセットであり、オプションで静的な型付けが追加されています。TypeScriptは大規模なアプリケーションの開発用に設計されており、JavaScriptへのトランスコンパイルも可能です。TypeScriptはJavaScriptのスーパーセットなので、既存のJavaScriptプログラムも有効なTypeScriptプログラムとなります。TypeScript は、クライアントサイドとサーバーサイド(Node.js)の両方の開発に使用できます。(出典: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Quick Takeaway

JavaScriptは動的に型付けされています。しかし、静的型付け (つまり、変数の型、クラス、インターフェースを事前に指定すること)は、より明確になり、対応漏れやバグの可能性を減らすことができるというのが一般的な信念です。このトピックについてどのように感じるかにかかわらず、少なくともTypeScriptのような静的型付けされたバージョンのJavaScriptに触れることは重要です。TypeScript はブラウザで解釈できるようにJavaScriptにコンパイルされていることには注意してください (つまり、ブラウザはTypeScriptをネイティブには解釈しません)。

### :book: Learning Areas and Ideas

- [Learn TypeScript in 5 minutes](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Learn TypeScript in 50 minutes (Video)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- 可能なら[create a React app with TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.jsは、サーバーレンダリングReactアプリケーションを作成するためのミニマムなフレームワークです。(出典: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Quick Takeaway

上級者向けになってきました。これまで、ブラウザでかなりの量の処理を行うReact（またはVueやAngular）アプリケーションを構築してきました。様々な理由（SEO対策、クライアントのパフォーマンスへの懸念など）から、実際にはフロントエンドアプリケーションをクライアントではなくサーバー上でレンダリングしたいと思うかもしれません。そこでNext.jsのようなフレームワークの出番です。

### :book: Learning Areas and Ideas

- Next.js [Getting Started](https://nextjs.org/learn/)
- [Next.js Crash Course (Video)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Next.jsアプリを新規で作成したり、あなたが作成したアプリをNext.jsに書き換えて見ましょう

# Xとは何なの？

このリストは、フロントエンド開発のエコシステムを広く知ってもらうことを目的としていますが、各分野の無数のツールはもちろんのこと、すべてのトピックを網羅することは単純に不可能です！かなり重要なトピックが記載されていないと思ったら、[貢献](#contributing)セクションを確認して、このガイドをより良いものにするための手伝いをしてください。

# プロジェクトのアイデア

#100DaysOfCodeを進めていく中で、新しく習得した知識を使っていくつかプロジェクトを作りたくなるでしょう。このセクションでは、あなたが作成できるようなプロジェクトをいくつか提案してみようと思います。代わりに、あなた自身でプロジェクトのアイデアを興味が持てて開発し続けられる形で考えてください。

- 初心者向けの考え：
  - ポートフォリオサイトを作成する
- 中級者/上級者向けの考え：
  - ツイート分析アプリを作成する (すでにバックエンドとAPI連携を知っている場合)

# 助けがほしいですか？

ソフトウェア開発を学ぶ方法は一般的に次の方法があります：

- 問題点を検索する
- [StackOverflow](http://www.stackoverflow.com) （あなたの疑問がすでに質問されている可能性が高く、検索すると上位に表示されるでしょう。）
- [Mozilla MDN Web Docs](https://developer.mozilla.org/ja/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- 地元のソフトウェア開発のミートアップ！大抵の場合はすべての経験レベルに非常に親切です。

もし私の意見が欲しかったら、[Twitter](http://www.twitter.com/nas5w)でお気軽に問い合わせてください。少しでもお役に建てるように頑張ります。もしカリキュラムに問題や提案があったら、下の[貢献セクション](#contributing)を読んでください。

# 貢献

## プロジェクトを広める

もしあなたがここでの作業に感謝しているのであれば、このリポジトリを広めることで大きく貢献することができます。例えば次のことができます：

- 本リポジトリをフォーク
- SNSに本リポジトリを共有


## プロジェクトに貢献する

本プロジェクトは進行中であり、この知識ベースをメンテナンスする上での貢献にとても感謝しています！

このリポジトリに貢献する際には、変更を行う前にまずissueを通して変更したい内容を話し合ってください。そうしないと、あなたの提案を理解するのが非常に難しくなり、結果的にマージされないであろう変更に多くの労力を費やすことになる可能性があります。

このプロジェクトに関わるすべての人は、学ぼうとしているか助けようとしていることに注意してください--優しくしてください！

## プルリクエストの仕方

1. 提案されるプルリクエストの概要が説明されたissueを立ててください。
2. 提案された変更を反映するためにプロジェクト所有者から承認を得てください。
3. プルリクエストを作成してください。
