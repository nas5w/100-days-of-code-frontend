<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Это несколько самоуверенный учебный план для изучения разработки интерфейсов во время #100DaysOfCode. Поскольку он охватывает широкий спектр тем разработки для старта, его можно рассматривать как скорее курс в стиле «опроса», а не глубокое погружение в какую-либо одну область. В идеале, вы, пройдя этот учебный план, будете иметь некоторое знакомство с каждой темой и возможность легко углубиться в любую область в будущем, когда это необходимо.

На этот учебный план значительное влияние оказывает Kamran Ahmed's [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c) с дорожной картой. Пожалуйста, посмотрите это - это просто супер.

**Замечание**: Я знаю, что front-end разработка означает много разных вещей для многих людей! Если вы являетесь разработчиком внешнего интерфейса и считаете, что это руководство можно улучшить, сообщите мне об этом, подняв проблему, как описано в секции [Contributing](#contributing). Спасибо Вам!

# :calendar: Учебный план

Основополагающим принципом этого хранилища является [timeboxing] (https://en.wikipedia.org/wiki/Timeboxing). Если в прошлом вы потратили какое-то время, пытаясь научиться веб-разработке или подобным навыкам, вы, вероятно, испытали провал по какой-то одной конкретной теме. Этот репозиторий ставит цель назначить определенное количество дней для каждой технологии и призывает вас перейти к следующему, как только это количество дней истекло.

Предполагается, что при запуске этой задачи все находятся на разных уровнях, и это нормально. Как начинающие, так и опытные разработчики фронт-энда могут извлечь выгоду из временной практики в каждой из этих областей.

Рекомендуемые ежедневные действия следующие:

- Days 1-8: [HTML](#html)
- Days 9-16: [CSS](#css)
- Days 17-24: [JavaScript основы](#javascript)
- Days 25-27: [jQuery](#jquery)
- Days 28-33: [Адаптивный Веб-Дизайн](#rwd)
- Days 34-36: [Доступность](#accessibility)
- Days 37-39: [Git](#git)
- Days 40-44: [Node and NPM](#node)
- Days 45-50: [Sass](#sass)
- Days 51-54: [Bootstrap](#bootstrap)
- Day 55: [BEM](#bem)
- Days 57-61: [Gulp](#gulp)
- Days 62-65: [Webpack](#webpack)
- Day 66: [ESLint](#eslint)
- Days 68-83: [React](#react)
- Days 84-89: [Redux](#redux)
- Days 90-94: [Jest](#jest)
- Days 95-97: [TypeScript](#typescript)
- Days 98-100: [NextJS](#nextjs)

# :mag_right: Детали

Ниже вы можете найти немного информации о каждой теме в учебном плане, а также некоторые идеи/рекомендации о том, что делать для каждого. Для вдохновения на проекты, чтобы сделать наряду с этой учебной программой,  вы можете посмотреть [Раздел проектных идей](#project-ideas).

Как часть принципа timeboxing, это нормально, если вы не пройдете все пункты в разделах «Области обучения и идеи». Вместо этого вам следует сосредоточиться на получении максимально возможного количества дней, назначенных для каждой области, а затем двигаться дальше.

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

Язык разметки гипертекста (HTML) является стандартным языком разметки для создания веб-страниц и веб-приложений. С помощью каскадных таблиц стилей (CSS) и JavaScript он образует триаду краеугольных технологий для Всемирной паутины. Веб-браузеры получают документы HTML с веб-сервера или из локального хранилища и выводят документы на мультимедийные веб-страницы. HTML описывает структуру веб-страницы семантически и изначально включает подсказки для внешнего вида документа. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Кратко

HTML действительно является основой веб-разработки. Даже в основанных на javascript фраемворках вы в конечном итоге пишете HTML в той или иной форме.

### :book: Области обучения и идеи

- Начните с [Основы HTML и HTML5](https://learn.freecodecamp.org/) на freeCodeCamp.
- HTML структура страницы
- HTML элементы
- Вложенные HTML-элементы
- Семантическая разметка
- Ссылки / несколько страниц
- Изображения
- Аудио / видео медиа
- Формы и элементы формы
- Создайте многостраничный сайт! (Смотрите [Идеи проекта](#project-ideas) если вам нужно вдохновение).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Каскадные таблицы стилей (CSS) - это язык таблиц стилей, используемый для описания представления документа, написанного на языке разметки, например HTML. CSS является краеугольной технологией Всемирной паутины, наряду с HTML и JavaScript. CSS предназначен для разделения представления и содержимого, включая макет, цвета и шрифты. Такое разделение может улучшить доступность контента, обеспечить большую гибкость и контроль в спецификации характеристик презентации, дать возможность нескольким веб-страницам совместно использовать форматирование, указав соответствующий CSS в отдельном файле .css, а также уменьшить сложность и повторяемость структурного контента. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Кратко

CSS является еще одним важным компонентом веб-разработки. Хотя он в основном используется для стилизации и размещения элементов HTML, он становится все более способным к более динамичным задачам (например, анимации), которые когда-то обрабатывались бы JavaScript.

### :book: Области обучения и идеи

- Начините с [Основы CSS, CSS flexbox, и разделы сетки CSS](https://learn.freecodecamp.org/) на freeCodeCamp.
- In-line CSS
- `<style>` теги
- Внешний CSS с `<link>`
- Стилизация элементов
- Селекторы
- Флоаты, очистка флоатов
- Сетки (grid, flexbox)
- Шрифты, кастомные шрифты
- Стилизируйте HTML-страницы, которые вы создали, изучая HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript, часто называемый JS, является интерпретируемым языком программирования высокого уровня, который соответствует спецификации ECMAScript. Это язык, который также характеризуется как динамический, слабо типизированный, основанный на прототипах и мультипарадигмальный. Наряду с HTML и CSS, JavaScript является одной из трех основных технологий Всемирной паутины. JavaScript обеспечивает интерактивные веб-страницы и, следовательно, является неотъемлемой частью веб-приложений. Подавляющее большинство веб-сайтов используют его, и все основные веб-браузеры имеют специальный механизм JavaScript для его выполнения. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Кратко

JavaScript становится все более важным в мире переднего плана. Хотя когда-то он использовался главным образом для придания страницам динамического характера, сейчас он является основой многих интерфейсных сред. Эти структуры обрабатывают множество задач, которые ранее выполнялись серверной частью (например, маршрутизация и отображение различных представлений).

### :book: Области обучения и идеи

- Начните с [Основы JavaScript и ES6](https://learn.freecodecamp.org/) на freeCodeCamp.
- Слишком много основ языка, чтобы перечислить здесь!
- `<script>` тег и размещение
- Доступ к элементам HTML
- Цикл событий, стек вызовов и очередь событий
- Прототип наследования
- Ссылка против значения
- Добавьте некоторые динамические элементы или логику к вашим HTML / CSS страницам, разработанным ранее!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery - это быстрая, небольшая и многофункциональная библиотека JavaScript. Она делает такие вещи, как обход и манипулирование документами HTML, обработка событий, анимация и Ajax намного проще с простым в использовании API, который работает во множестве браузеров. Благодаря сочетанию универсальности и расширяемости, jQuery изменил способ, которым миллионы людей пишут JavaScript. (Источник: [jQuery.com](https://jquery.com/))

### :bulb: Кратко

После того, как вы потратили некоторое время на простой (также называемый «ванильным») javascript, некоторые задачи могут оказаться немного громоздкими, особенно те, которые связаны с доступом к элементам HTML и манипулированием ими. В течение долгого времени jQuery была доступной библиотекой для упрощения и согласования таких задач в разных браузерах. В настоящее время jQuery не обязательно является «обязательным» обучением из-за улучшений в vanilla javascript, CSS и более новых фреймворках javascript (мы рассмотрим фреймворки позже). Тем не менее, было бы полезно потратить немного времени на изучение jQuery и применить его к небольшому проекту.

### :book: Области обучения и идеи

- Начните с [jQuery секция](https://learn.freecodecamp.org/) на freeCodeCamp.
- Готовые документы
- Cелекторы
- Переключение классов
- Анимация
- Добавление или перемещение элементов HTML
- Добавьте jQuery на свой сайт!

<a name="rwd"></a>
![Отзывчивый веб-дизайн](https://i.imgur.com/Bt1zWwq.jpg)

Отзывчивый веб-дизайн (RWD) - это подход к веб-дизайну, позволяющий хорошо отображать веб-страницы на различных устройствах и размерах окон или экранов. Недавняя работа также рассматривает близость зрителя как часть контекста просмотра как расширение для RWD. Содержание, дизайн и производительность необходимы на всех устройствах, чтобы обеспечить удобство использования и удовлетворение. Сайт, созданный с использованием RWD, адаптирует макет к среде просмотра с помощью плавных, пропорциональных сеток, гибких изображений и медиазапросов CSS3, что является расширением правила @media. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Кратко

Адаптивный веб-дизайн - это все то, чтобы веб-приложения выглядели и функционировали должным образом при любых условиях. Простой и быстрый пример: веб-браузер должен выглядеть и функционировать должным образом как в настольном веб-браузере, так и в браузере мобильного телефона. Понимание адаптивного дизайна имеет решающее значение для любого front-end разработчика!

### :book: Области обучения и идеи

- Начните с [Responsive Web Design Principles section](https://learn.freecodecamp.org/) на freeCodeCamp.
- Медиа-запросы, брекпоинты
- Адаптивные изображения
- Сделайте свой сайт отзывчивым!
- Используйте Chrome DevTools для просмотра вашего сайта на разных устройствах / экранах.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with disabilities. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Кратко

Accessibility, often written as a11y, is one of the most important topics in front-end web development, yet it seems to often get short shrift. Creating accessible web applications is not only ethically sound, but also makes a lot of business sense considering the additional audience that will be able to view your applications when they are accessible.

### :book: Области обучения и идеи

- Начните с [Applied Accessibility section](https://learn.freecodecamp.org/) на freeCodeCamp.
- Read some content on [The A11Y Project](https://a11yproject.com/about)
- Review their [checklist](https://a11yproject.com/checklist)
- Update your site(s) for accessibility based on this checklist

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. (Источник: [git-scm.com](https://git-scm.com/))

### :bulb: Кратко

Version/code control is an essential part of any web developer's toolkit. There are a number of different version control systems, but Git is by far the most prevalent at the moment. You can (and should!) use it to track your projects as you learn!

### :book: Области обучения и идеи

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

Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. JavaScript is used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML and run client-side by a JavaScript engine in the user's web browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web application development around a single programming language, rather than different languages for server side and client side scripts. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Кратко

While nodejs is typically known as a back-end solution, it is used quite frequently to support front-end development. It does this in a number of ways, including things like running build tools, testing, and linting (all to be covered soon!). Node Package Manager (npm) is another great feature of node and can be used to manage dependencies of your project (i.e., code libraries your project might rely on -- jQuery is an example!).

### :book: Области обучения и идеи

- Research node and how it is different than the browser
- Install node (npm comes with it)
- Create a simple javascript file and run it with node
- Use NPM to manage any dependencies in your existing project(s) (e.g., jQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass is an extension of CSS that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, inline imports, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly, particularly with the help of the Compass style library. (Источник: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Кратко

Sass allows you to write CSS in a more programmatic way. If you've done some CSS, you might have noticed that you end up repeating a lot of information--for example, specifying the same color code. In Sass, you can use things like variables, loops, and nesting to reduce redundancy and increase readability. After writing your code in Sass, you can quickly and easily compile it to regular CSS.

### :book: Области обучения и идеи

- [Install Sass](https://sass-lang.com/install) globally with npm!
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- Follow the [Learn Sass](https://sass-lang.com/guide) tutorial and/or [freeCodeCamp](https://learn.freecodecamp.org/) Sass tutorial.
- Update your existing site to generate your CSS using Sass!

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* Some alternatives: Foundation, Bulma, Materialize

Bootstrap is a free and open-source front-end framework for developing websites and web applications. It contains HTML and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. (Источник: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Кратко

There are many options for laying out, styling, and making your web application dynamic, but you'll find that starting with a framework helps you tremendously in getting a head start. Bootstrap is one such framework, but it is definitely far from the only option! I recommend getting familiar with one framework like this, but it's far more important to grasp HTML, CSS, and JavaScript fundamentals than it is to get caught up in any one framework.

### :book: Области обучения и идеи

- Learn what Bootstrap is and why you would want to use it
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Complete the Bootstrap section on [freeCodeCamp](https://learn.freecodecamp.org/)
- Refactor your site using bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project. (Источник: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Кратко

It's important to know naming and organization systems like BEM exist and why they are used. Do some research here, but at a beginner level I wouldn't recommend devoting too much time to the subject.

### :book: Области обучения и идеи

- Read the [BEM introduction](http://getbem.com/introduction/)
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Create a simple webpage using BEM conventions.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something. (Источник: [gulpjs.com](https://gulpjs.com/))

### :bulb: Кратко

In modern front-end development, you'll often find yourself needing to automate tasks like bundling, moving files, and injecting references into HTML files. Gulp is one tool that can help you do these things!

### :book: Области обучения и идеи

- Install gulp with npm
- Follow the [gulp for beginners tutorial](https://css-tricks.com/gulp-for-beginners/) on CSS-Tricks
- In your website, set up gulp to:
  - Compile Sass for you
  - Put the generated CSS file in `build` subdirectory
  - Move your web pages to the build directory
  - Inject a reference to your generated CSS file into your web pages

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

At its core, webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph which maps every module your project needs and generates one or more bundles. (Источник: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Кратко

Imagine that you have a large web development project with a number of different developers working on a lot of different tasks. Rather than all working in the same files, you might want to modularize them as much as possible. Webpack helps enable this by letting your team work modularly and then, come time to build the application, Webpack will stick it all together: HTML, CSS/Sass, JavasScript, images, etc. Webpack isn't the only module bundler, but it seems to be the front-runner at the moment.

### :book: Области обучения и идеи

- Read [webpack concepts](https://webpack.js.org/concepts/)
- [What is Webpack, How does it work? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [This webpack tutorial](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint is an open source JavaScript linting utility originally created by Nicholas C. Zakas in June 2013. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. There are code linters for most programming languages, and compilers sometimes incorporate linting into the compilation process. (Источник: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Кратко

Linting is a fantastic tool for code quality, readability, and consistency. Using a linter will help you catch syntax and formatting mistakes before they go to production. You can run linters manually or include them in your build/deployment process.

### :book: Области обучения и идеи

- Install eslint using npm
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Lint your JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React (also known as React.js or ReactJS) is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. Complex React applications usually require the use of additional libraries for state management, routing, and interaction with an API. (Источник: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Кратко

Front-end JavaScript frameworks are at the forefront of modern front-end development. One important takeaway here is that React, despite being incredibly popular, is only a library for building user interfaces whereas frameworks like Vue and Angular aim to be more full-featured. For example, if you build an application with in React that needs to route to different views, you'll need to bring in something like `react-router`.

### :book: Области обучения и идеи

- Начните с [React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [Learn React with Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Refactor your website as a React app!
- Note: `create-react-app` is a convenient tool to scaffold new React projects.

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger. (Источник: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Кратко

As you build bigger and bigger front-end applications, you start realizing that it's hard to maintain application state: things like the if the user is logged in, who the user is, and generally what's going on in the application. Redux is a great library that helps you maintain a single source of state on which your application can base its logic.

### :book: Области обучения и идеи

- This [Redux video tutorial](https://www.youtube.com/watch?v=93p3LxR9xfM)
- This [Redux video series](https://egghead.io/courses/getting-started-with-redux) by Dan Abramov, creator of Redux
- Take note of the [Redux three principles](https://redux.js.org/introduction/three-principles)
  - Single source of truth
  - State is read-only
  - Changes are made with pure functions
- Add Redux state management to your app!

<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest is a delightful JavaScript Testing Framework with a focus on simplicity. It works with projects using: Babel, TypeScript, Node, React, Angular, Vue and more! (Источник: [jestjs.io](https://jestjs.io))

### :bulb: Кратко

It is very important to set up automated testing for your front-end projects. Setting up automated testing will allow you to make future changes with confidence--if you make changes and your tests still pass, you will be fairly comfortable you didn't break any existing functionality. There are too many testing frameworks to list; Jest is simply one of my favorties.

### :book: Области обучения и идеи

- Learn [Jest basics](https://jestjs.io/docs/en/getting-started)
- If you used `create-react-app`, [Jest is already configured](https://facebook.github.io/create-react-app/docs/running-tests).
- Add tests to your application!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternative: Flow

TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language. TypeScript is designed for development of large applications and transcompiles to JavaScript. As TypeScript is a superset of JavaScript, existing JavaScript programs are also valid TypeScript programs. TypeScript may be used to develop JavaScript applications for both client-side and server-side (Node.js) execution. (Источник: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Кратко

JavaScript is dynamically typed. However, it is a common belief that static typing (i.e., specifying variable types, classes, interfaces ahead of time) is both clearer and reduces the likelihood of defects/bugs. Regardless of how you feel on the topic, it's important to at least get a feel for a statically-typed version of JavaScript like TypeScript. Note that TypeScript compiles down to JavaScript so it can be interpreted by browsers (i.e., browsers don't natively interpret TypeScript).

### :book: Области обучения и идеи

- [Learn TypeScript in 5 minutes](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Learn TypeScript in 50 minutes (Video)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Optionally [create a React app with TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js is a minimalistic framework for server-rendered React applications. (Источник: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Кратко

Now we're getting advanced! By now you've built a React (or Vue or Angular) application that does quite a bit of work in the browser. For various reasons (e.g., SEO, concerns over client performance), you might actually want your front-end application to be rendered on the server rather than the client. That's where a framework like next.js comes in.

### :book: Области обучения и идеи

- Next.js [Getting Started](https://nextjs.org/learn/)
- [Next.js Crash Course (Video)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Create a Next.js app or migrate your existing app to Next.js

# But What About X?

This list is supposed to give you broad exposure to the front-end ecosystem, but it's simply impossible to hit on every single topic, not to mention the myriad tools within each area! If you do think I missed something very important, please see the [Contributing](#contributing) section to see how you can help make this guide better.

# Project Ideas

As you progress through #100DaysOfCode, you'll want one or multiple projects to which you can apply your new knowledge. In this section, I attempt to provide a few project ideas that you can use. Alternatively, you're encouraged to come up with your own project ideas as those ideas may interest and motivate you more.

- Beginner ideas:
  - Build a portfolio website
- Intermediate/Advanced ideas:
  - Build a tweet analysis app (If you know back-end and API integration already)
  
# Need Help?

Generally, I have found the following resources invaluable to learning software development:

- Googling the issue
- [StackOverflow](http://www.stackoverflow.com) (There's a good chance your question has already been asked and will be a high-ranking result when googling).
- [Mozilla MDN Web Docs](https://developer.mozilla.org/en-US/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- Local software development Meetups! Most are very friendly to all experience levels.

If you'd like my input on anything, feel free to [connect with me on Twitter](http://www.twitter.com/nas5w) and I'll do my best to try to offer some assistance. If you think there's an issue with the curriculum or have a recommendation, see the [contributing section](#contributing) below.

# Contributing

## Spread the Word

If you appreciate the work done here, you can contribute significantly by spreading the word about this repository, including things like:

- Starring and forking this repository
- Sharing this repository on social media

## Contribute to this Repository

This is a work in progress and I very much appreciate any help in maintaining this knowledge base!

When contributing to this repository, please first discuss the change you wish to make via issue before making a change. Otherwise, it will be very hard to understand your proposal and could potentially result in you putting in a lot of work to a change that won't get merged.

Please note that everyone involved in this project is either trying to learn or trying to help--Please be nice!

## Pull Request Process

1. Create an issue outlining the proposed pull request.
2. Obtain approval from a project owner to make the proposed change.
3. Create the pull request.
