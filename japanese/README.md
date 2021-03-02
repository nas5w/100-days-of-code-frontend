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

Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications. With Cascading Style Sheets (CSS) and JavaScript, it forms a triad of cornerstone technologies for the World Wide Web. Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document. (Source: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Quick Takeaway

HTML is really the foundation of web development. Even in the javascript-based frameworks, you end up writing HTML in one form or another.

### :book: Learning Areas and Ideas

- Take the [Basic HTML and HTML5 section](https://learn.freecodecamp.org/) on freeCodeCamp.
- HTML page structure
- HTML elements
- Nesting HTML elements
- Semantic markup
- Links / multiple pages
- Images
- Audio/video media
- Forms and form elements
- Create a multi-page website! (See [Project Ideas](#project-ideas) if you need some inspiration).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Quick Takeaway

CSS is another essential component of web development. While it is mainly used to style and position HTML elements, it has become increasingly capable of more dynamic tasks (e.g., animations) that would once be handled by javascript.

### :book: Learning Areas and Ideas

- Take the [Basic CSS, CSS flexbox, and CSS grid sections](https://learn.freecodecamp.org/) on freeCodeCamp.
- In-line CSS
- `<style>` tags
- External CSS with `<link>`
- Styling elements
- Selectors
- Floats, clearing floats
- Layouts (grid, flexbox)
- Fonts, custom fonts
- Style the HTML page(s) you made when learning HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript , often abbreviated as JS, is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is a language that is also characterized as dynamic, weakly typed, prototype-based and multi-paradigm. Alongside HTML and CSS, JavaScript is one of the three core technologies of the World Wide Web. JavaScript enables interactive web pages and thus is an essential part of web applications. The vast majority of websites use it, and all major web browsers have a dedicated JavaScript engine to execute it. (Source: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Quick Takeaway

JavaScript has become increasingly important in the front-end world. While it was once used mainly to make pages dynamic, it is now the foundation of many front-end frameworks. These frameworks handle a lot of the tasks that were formerly handled by the back-end (e.g., routing and displaying different views).

### :book: Learning Areas and Ideas

- Take the [Basic JavaScript and ES6 sections](https://learn.freecodecamp.org/) on freeCodeCamp.
- Too many language fundamentals to list here!
- `<script>` tag and placement
- Accessing HTML elements
- The event loop, call stack, and event queue
- Prototypal Inheritance
- Reference vs. value
- Add some dynamic elements or logic to your HTML/CSS page(s) developed earlier!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript. (Source: [jQuery.com](https://jquery.com/))

### :bulb: Quick Takeaway

After you have spent some time with plain (also called "vanilla") javascript, you may find some tasks a bit cumbersome, especially those related to accessing and manipulating HTML elements. For quite a while, jQuery was the go-to library for making these kinds of tasks easier and consistent across different browsers. Nowadays, jQuery isn't necessarily "mandatory" learning because of advancements in vanilla javascript, CSS, and newer javascript frameworks (we'll look at frameworks later). Still, it would be beneficial to take a little time to learn some jQuery and apply it to a small project.

### :book: Learning Areas and Ideas

- Take the [jQuery section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Document ready
- Selectors
- Toggle classes
- Animation
- Add or move HTML elements
- Add jQuery to your site!

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

Responsive web design (RWD) is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes. Recent work also considers the viewer proximity as part of the viewing context as an extension for RWD. Content, design and performance are necessary across all devices to ensure usability and satisfaction. A site designed with RWD adapts the layout to the viewing environment by using fluid, proportion-based grids, flexible images, and CSS3 media queries, an extension of the @media rule. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Quick Takeaway

Responsive web design is all about making web applications look and function properly on all types of device. A quick-and-dirty example would be that a website should look and function properly both in a desktop web browser and on a mobile phone browser. An understanding of responsive design is crucial for any front-end developer!

### :book: Learning Areas and Ideas

- Take the [Responsive Web Design Principles section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Media queries, breakpoints
- Responsive images
- Make your website responsive!
- Use Chrome DevTools to view your site on different devices/viewports.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with disabilities. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Quick Takeaway

Accessibility, often written as a11y, is one of the most important topics in front-end web development, yet it seems to often get short shrift. Creating accessible web applications is not only ethically sound, but also makes a lot of business sense considering the additional audience that will be able to view your applications when they are accessible.

### :book: Learning Areas and Ideas

- Take the [Applied Accessibility section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Read some content on [The A11Y Project](https://a11yproject.com/about)
- Review their [checklist](https://a11yproject.com/checklist)
- Update your site(s) for accessibility based on this checklist

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. (Source: [git-scm.com](https://git-scm.com/))

### :bulb: Quick Takeaway

Version/code control is an essential part of any web developer's toolkit. There are a number of different version control systems, but Git is by far the most prevalent at the moment. You can (and should!) use it to track your projects as you learn!

### :book: Learning Areas and Ideas

- [Git Tutorial for Beginners (Video)](https://www.youtube.com/watch?v=HVsySz-h9r4)
- Install git
- Set up a [github](https://github.com) account
- Learn the most-used git commands:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- Add your existing projects to github!

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. JavaScript is used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML and run client-side by a JavaScript engine in the user's web browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web application development around a single programming language, rather than different languages for server side and client side scripts. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Quick Takeaway

While Node.js is typically known as a back-end solution, it is used quite frequently to support front-end development. It does this in a number of ways, including things like running build tools, testing, and linting (all to be covered soon!). Node Package Manager (npm) is another great feature of Node and can be used to manage dependencies of your project (i.e., code libraries your project might rely on -- jQuery is an example!).

### :book: Learning Areas and Ideas

- Research node and how it is different than the browser
- Install node (npm comes with it)
- Create a simple javascript file and run it with node
- Use NPM to manage any dependencies in your existing project(s) (e.g., jQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass is an extension of CSS that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, inline imports, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly, particularly with the help of the Compass style library. (Source: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Quick Takeaway

Sass allows you to write CSS in a more programmatic way. If you've done some CSS, you might have noticed that you end up repeating a lot of information--for example, specifying the same color code. In Sass, you can use things like variables, loops, and nesting to reduce redundancy and increase readability. After writing your code in Sass, you can quickly and easily compile it to regular CSS.

### :book: Learning Areas and Ideas

- [Install Sass](https://sass-lang.com/install) globally with npm!
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- Follow the [Learn Sass](https://sass-lang.com/guide) tutorial and/or [freeCodeCamp](https://learn.freecodecamp.org/) Sass tutorial.
- Update your existing site to generate your CSS using Sass!

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* Some alternatives: Foundation, Bulma, Materialize

Bootstrap is a free and open-source front-end framework for developing websites and web applications. It contains HTML and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. (Source: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Quick Takeaway

There are many options for laying out, styling, and making your web application dynamic, but you'll find that starting with a framework helps you tremendously in getting a head start. Bootstrap is one such framework, but it is definitely far from the only option! I recommend getting familiar with one framework like this, but it's far more important to grasp HTML, CSS, and JavaScript fundamentals than it is to get caught up in any one framework.

### :book: Learning Areas and Ideas

- Learn what Bootstrap is and why you would want to use it
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Complete the Bootstrap section on [freeCodeCamp](https://learn.freecodecamp.org/)
- Refactor your site using bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project. (Source: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Quick Takeaway

It's important to know naming and organization systems like BEM exist and why they are used. Do some research here, but at a beginner level I wouldn't recommend devoting too much time to the subject.

### :book: Learning Areas and Ideas

- Read the [BEM introduction](http://getbem.com/introduction/)
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Create a simple webpage using BEM conventions.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something. (Source: [gulpjs.com](https://gulpjs.com/))

### :bulb: Quick Takeaway

In modern front-end development, you'll often find yourself needing to automate tasks like bundling, moving files, and injecting references into HTML files. Gulp is one tool that can help you do these things!

### :book: Learning Areas and Ideas

- Install gulp with npm
- Follow the [gulp for beginners tutorial](https://css-tricks.com/gulp-for-beginners/) on CSS-Tricks
- In your website, set up gulp to:
  - Compile Sass for you
  - Put the generated CSS file in `build` subdirectory
  - Move your web pages to the build directory
  - Inject a reference to your generated CSS file into your web pages

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

At its core, webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph which maps every module your project needs and generates one or more bundles. (Source: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Quick Takeaway

Imagine that you have a large web development project with a number of different developers working on a lot of different tasks. Rather than all working in the same files, you might want to modularize them as much as possible. Webpack helps enable this by letting your team work modularly and then, come time to build the application, Webpack will stick it all together: HTML, CSS/Sass, JavasScript, images, etc. Webpack isn't the only module bundler, but it seems to be the front-runner at the moment.

### :book: Learning Areas and Ideas

- Read [webpack concepts](https://webpack.js.org/concepts/)
- [What is Webpack, How does it work? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [This webpack tutorial](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint is an open source JavaScript linting utility originally created by Nicholas C. Zakas in June 2013. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. There are code linters for most programming languages, and compilers sometimes incorporate linting into the compilation process. (Source: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Quick Takeaway

Linting is a fantastic tool for code quality, readability, and consistency. Using a linter will help you catch syntax and formatting mistakes before they go to production. You can run linters manually or include them in your build/deployment process.

### :book: Learning Areas and Ideas

- Install eslint using npm
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Lint your JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React (also known as React.js or ReactJS) is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. Complex React applications usually require the use of additional libraries for state management, routing, and interaction with an API. (source: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Quick Takeaway

Front-end JavaScript frameworks are at the forefront of modern front-end development. One important takeaway here is that React, despite being incredibly popular, is only a library for building user interfaces whereas frameworks like Vue and Angular aim to be more full-featured. For example, if you build an application with in React that needs to route to different views, you'll need to bring in something like `react-router`.

### :book: Learning Areas and Ideas

- Take the [React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [Learn React with Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Refactor your website as a React app!
- Note: `create-react-app` is a convenient tool to scaffold new React projects.

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger. (Source: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Quick Takeaway

As you build bigger and bigger front-end applications, you start realizing that it's hard to maintain application state: things like the if the user is logged in, who the user is, and generally what's going on in the application. Redux is a great library that helps you maintain a single source of state on which your application can base its logic.

### :book: Learning Areas and Ideas

- This [Redux video tutorial](https://www.youtube.com/watch?v=93p3LxR9xfM)
- This [Redux video series](https://egghead.io/courses/getting-started-with-redux) by Dan Abramov, creator of Redux
- Take note of the [Redux three principles](https://redux.js.org/introduction/three-principles)
  - Single source of truth
  - State is read-only
  - Changes are made with pure functions
- Add Redux state management to your app!

<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest is a delightful JavaScript Testing Framework with a focus on simplicity. It works with projects using: Babel, TypeScript, Node, React, Angular, Vue and more! (Source: [jestjs.io](https://jestjs.io))

### :bulb: Quick Takeaway

It is very important to set up automated testing for your front-end projects. Setting up automated testing will allow you to make future changes with confidence--if you make changes and your tests still pass, you will be fairly comfortable you didn't break any existing functionality. There are too many testing frameworks to list; Jest is simply one of my favorties.

### :book: Learning Areas and Ideas

- Learn [Jest basics](https://jestjs.io/docs/en/getting-started)
- If you used `create-react-app`, [Jest is already configured](https://facebook.github.io/create-react-app/docs/running-tests).
- Add tests to your application!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternative: Flow

TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language. TypeScript is designed for development of large applications and transcompiles to JavaScript. As TypeScript is a superset of JavaScript, existing JavaScript programs are also valid TypeScript programs. TypeScript may be used to develop JavaScript applications for both client-side and server-side (Node.js) execution. (Source: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Quick Takeaway

JavaScript is dynamically typed. However, it is a common belief that static typing (i.e., specifying variable types, classes, interfaces ahead of time) is both clearer and reduces the likelihood of defects/bugs. Regardless of how you feel on the topic, it's important to at least get a feel for a statically-typed version of JavaScript like TypeScript. Note that TypeScript compiles down to JavaScript so it can be interpreted by browsers (i.e., browsers don't natively interpret TypeScript).

### :book: Learning Areas and Ideas

- [Learn TypeScript in 5 minutes](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Learn TypeScript in 50 minutes (Video)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Optionally [create a React app with TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js is a minimalistic framework for server-rendered React applications. (Source: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Quick Takeaway

Now we're getting advanced! By now you've built a React (or Vue or Angular) application that does quite a bit of work in the browser. For various reasons (e.g., SEO, concerns over client performance), you might actually want your front-end application to be rendered on the server rather than the client. That's where a framework like next.js comes in.

### :book: Learning Areas and Ideas

- Next.js [Getting Started](https://nextjs.org/learn/)
- [Next.js Crash Course (Video)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Create a Next.js app or migrate your existing app to Next.js

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
