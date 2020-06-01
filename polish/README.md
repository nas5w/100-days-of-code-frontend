<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Chcesz dowiedzieć się więcej o programowaniu frontend? Rozważ zapisanie się na mój [bezpłatny biuletyn](https://buttondown.email/devtuts), gdzie okresowo wysyłam przystępnie opisane teksty o frontendzie!

---

Jest to nieco opiniotwórczy program do nauki programowania front-end podczas #100DaysOfCode. Ponieważ obejmuje szeroki zakres tematów związanych z programowaniem front-end, można go traktować bardziej jako kurs typu "przegląd", niż głębokie zanurzenie w jednym obszarze. Idealnym rozwiązaniem na ukończenie tego programu będzie znajomość każdego tematu i możliwość łatwego nurkowania głębiej w dowolnym obszarze w przyszłości, jeśli zajdzie taka potrzeba.

Na ten program nauczania znaczący wpływ miał artykuł Kamrana Ahmed'sa o tytule [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c). Sprawdź to sam - jest doskonały.

**Uwaga**: Wiem, że programowanie frontendu oznacza wiele różnych rzeczy dla wielu ludzi! Jeśli jesteś programistą typu frontend i uważasz, że ten przewodnik można ulepszyć, daj mi znać, tworząc issue zgodnie z opisem w sekcji [Współtworzenie](#contributing). Dziękuję!

# Tłumaczenia

Dzięki niesamowitym współtwórcom program ten został przetłumaczony na następujące języki!

- [Rosyjski русский](/ru) (tłumaczenie od [@Ibochkarev](https://github.com/Ibochkarev) i [@JonikUl](https://github.com/JonikUl))
- [Chiński 中文](/chinese) (tłumaczenie od [@simplefeel](https://github.com/simplefeel))
- [Portugalski Português](/portuguese) (tłumaczenie od [@Zardosh](https://github.com/Zardosh))
- [Polski Polish](/polish) (tłumaczenie od [@mbiesiad](https://github.com/mbiesiad))

# :calendar: Program

Podstawową zasadą tego repozytorium jest [timeboxing](https://en.wikipedia.org/wiki/Timeboxing). Jeśli spędziłeś w przeszłości jak najwięcej czasu, próbując nauczyć się tworzenia stron internetowych lub podobnych umiejętności, prawdopodobnie doświadczyłeś zejścia do króliczej nory na dowolny konkretny temat. To repozytorium ma na celu przypisanie określonej liczby dni do każdej technologii i zachęca do przejścia do następnej, gdy ta liczba dni minie.

Oczekuje się, że wszyscy są na innym poziomie biegłości podczas rozpoczynania tego wyzwania, i to jest w porządku. Zarówno początkujący, jak i doświadczeni programiści mogą korzystać z praktyki timeboxingu w każdym z tych obszarów.

Zalecane codzienne czynności są następujące:

- Dni 1-8: [HTML](#html)
- Dni 9-16: [CSS](#css)
- Dni 17-24: [Podstawy JavaScript](#javascript)
- Dni 25-27: [jQuery](#jquery)
- Dni 28-33: [Responsive Web Design](#rwd)
- Dni 34-36: [Dostępność](#dostępność)
- Dni 37-39: [Git](#git)
- Dni 40-44: [Node i NPM](#node)
- Dni 45-50: [Sass](#sass)
- Dni 51-54: [Bootstrap](#bootstrap)
- Dzień 55: [BEM](#bem)
- Dni 57-61: [Gulp](#gulp)
- Dni 62-65: [Webpack](#webpack)
- Dzień 66: [ESLint](#eslint)
- Dni 68-83: [React](#react)
- Dni 84-89: [Redux](#redux)
- Dni 90-94: [Jest](#jest)
- Dni 95-97: [TypeScript](#typescript)
- Dni 98-100: [NextJS](#nextjs)

# :mag_right: Szczegóły

Poniżej znajdziesz trochę informacji na temat każdego tematu w programie nauczania, a także kilka pomysłów/wskazówek, co zrobić dla każdego z nich. Inspiracje do projektów realizowanych zgodnie z tym programem nauczania można znaleźć w sekcji [Pomysły na projekty](#pomysły-na-projekty).

W ramach zasady timeboxingu, jest w porządku jeśli nie przejdziesz wszystkich elementów w sekcjach "Obszary nauki i pomysły". Zamiast tego powinieneś skupić się na jak największej liczbie dni przypisanych do każdego obszaru, a następnie przejść dalej.

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

Hypertext Markup Language (HTML) to język znaczników do tworzenia stron internetowych i aplikacji internetowych. Dzięki kaskadowym arkuszom stylów (CSS) i JavaScript tworzy triadę podstawowych technologii dla sieci WWW. Przeglądarki internetowe odbierają dokumenty HTML z serwera WWW lub z lokalnej pamięci i renderują je na multimedialne strony internetowe. HTML opisuje semantycznie strukturę strony internetowej i początkowo zawierał wskazówki dotyczące wyglądu dokumentu. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Szybkie podsumowanie

HTML jest naprawdę podstawą do tworzenia stron internetowych. Nawet we frameworkach opartych na Javascript kończy się w pisaniu HTML, w takiej czy innej formie.

### :book: Obszary nauki i pomysły

- Przejdź do sekcji [Podstawowy HTML i HTML5](https://learn.freecodecamp.org/) na stronie freeCodeCamp.
- Struktura strony HTML
- Elementy HTML
- Zagnieżdżanie elementów HTML
- Znaczniki semantyczne
- Linki / wiele stron
- Obrazy
- Media audio/wideo
- Formy i elementy formularzy
- Utwórz witrynę wielostronicową! (Zobacz [Pomysły na projekty](#pomysły-na-projekty) jeśli potrzebujesz nieco inspiracji).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Kaskadowe arkusze stylów (CSS) to język arkuszy stylów używany do opisywania prezentacji dokumentu napisanego w języku znaczników, takim jak HTML. CSS to podstawowa technologia World Wide Web, obok HTML i JavaScript. CSS został zaprojektowany w celu umożliwienia oddzielenia prezentacji i treści, w tym układu, kolorów i czcionek. Ta separacja może poprawić dostępność treści, zapewnić większą elastyczność i kontrolę w specyfikacji cech prezentacji, umożliwić wielu stronom internetowym współdzielenie formatowania poprzez określenie odpowiedniego CSS w osobnym pliku .css, a także zmniejszyć złożoność i powtarzalność treści strukturalnych. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Szybkie podsumowanie

CSS jest kolejnym istotnym elementem tworzenia stron internetowych. Chociaż jest używany głównie do stylizacji i pozycjonowania elementów HTML, staje się coraz bardziej zdolny do wykonywania bardziej dynamicznych zadań (np. animacji), które kiedyś byłyby obsługiwane przez Javascript.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcje [Podstawy CSS, CSS flexbox, oraz CSS grid](https://learn.freecodecamp.org/) na freeCodeCamp.
- In-line CSS
- `<style>` tagi
- Zewnętrzny CSS z `<link>`
- Stylizowanie elementów
- Selektory
- Floaty, czyszczenie floatów
- Layouty (grid, flexbox)
- Czcionki, niestandardowe czcionki
- Stylowanie stron(y) HTML, którą stworzyłeś podczas nauki HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript, często skracany do JS, jest interpretowanym językiem programowania wysokiego poziomu, który jest zgodny ze specyfikacją ECMAScript. Jest to język, który jest również charakteryzowany jako dynamiczny, słabo typowany, oparty na prototypach i oparty na wielu paradygmatach. Oprócz HTML i CSS, JavaScript jest jedną z trzech podstawowych technologii w sieci WWW. JavaScript włącza interaktywne strony internetowe i dlatego jest istotną częścią aplikacji internetowych. Zdecydowana większość stron internetowych z niego korzysta, a wszystkie główne przeglądarki internetowe mają dedykowany silnik JavaScript do jego wykonania. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Szybkie podsumowanie

JavaScript zyskuje na znaczeniu w świecie front-end. Chociaż kiedyś był używany głównie do nadawania dynamiki stronom, obecnie stanowi podstawę wielu frameworków. Frameworki te obsługują wiele zadań, które wcześniej były obsługiwane przez backend (np. routing i wyświetlanie różnych widoków).

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcje [Basic JavaScript and ES6](https://learn.freecodecamp.org/) na freeCodeCamp.
- Zbyt wiele podstaw z języka, aby wymienić tutaj!
- `<script>` tag i rozmieszczanie
- Dostęp do elementów HTML
- Pętla zdarzeń, stos wywołań i kolejka zdarzeń
- Dziedziczenie prototypowe
- Reference vs. value
- Dodaj dynamiczne elementy lub logikę do stron HTML / CSS opracowanych wcześniej!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery to szybka, mała i bogata w funkcje biblioteka JavaScript. Ułatwia ona przechodzenie i manipulowanie dokumentami HTML, obsługę zdarzeń, animację i Ajax dzięki łatwemu w obsłudze interfejsowi API, który działa w wielu przeglądarkach. Dzięki połączeniu wszechstronności i rozszerzalności, jQuery zmieniło sposób, w jaki miliony ludzi piszą JavaScript. (Źródło: [jQuery.com](https://jquery.com/))

### :bulb: Szybkie podsumowanie

Po spędzeniu czasu z prostym (zwanym też "vanilla") Javascriptem, niektóre zadania mogą być nieco uciążliwe, szczególnie związane z dostępem do elementów HTML i manipulowaniem nimi. Przez długi czas jQuery była biblioteką, w której zadania tego typu były łatwiejsze i spójniejsze w różnych przeglądarkach. W dzisiejszych czasach jQuery niekoniecznie trzeba się uczyć "obowiązkowo" ze względu na postępy w 'prostym' Javascript, CSS i nowszych frameworkach Javascript (przyjrzymy się frameworkom później). Mimo to dobrze byłoby poświęcić trochę czasu na poznanie jQuery i zastosowanie go w małym projekcie.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [jQuery](https://learn.freecodecamp.org/) na freeCodeCamp.
- Gotowy dokument
- Selektory
- Toggle classes
- Animacje
- Dodaj lub przenieś elementy HTML
- Dodaj jQuery do swojej witryny!

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

Responsive web design (RWD) to podejście do projektowania stron internetowych, które sprawia, że strony internetowe dobrze renderują się na różnych urządzeniach i rozmiarach okna lub ekranu. Ostatnie prace traktują także bliskość widza jako część kontekstu oglądania, jako rozszerzenie RWD. Treść, konstrukcja i wydajność są niezbędne na wszystkich urządzeniach, aby zapewnić użyteczność i satysfakcję. Strona zaprojektowana przy użyciu RWD dostosowuje układ do środowiska oglądania, używając płynnych, proporcjonalnych siatek, elastycznych obrazów i zapytań o media CSS3, co stanowi rozszerzenie reguły @media. (Źródło:[Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Szybkie podsumowanie

Elastyczne projektowanie stron internetowych polega na tym, aby aplikacje internetowe wyglądały i działały prawidłowo we wszystkich rodzajach urządzeń. Tanim i tandetnym przykładem może być to, że witryna powinna wyglądać i działać poprawnie zarówno w przeglądarce internetowej na komputerze, jak i przeglądarce telefonu komórkowego. Zrozumienie responsywnego projektowania jest kluczowe dla każdego programisty front-end!

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [Responsive Web Design Principles](https://learn.freecodecamp.org/) na freeCodeCamp.
- Zapytania o media, punkty przerwania
- Responsywne obrazy
- Spraw, aby Twoja witryna była responsywna!
- Użyj Chrome DevTools, aby wyświetlić swoją witrynę na różnych urządzeniach / oknach podglądu.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with disabilities. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Szybkie podsumowanie

Accessibility, often written as a11y, is one of the most important topics in front-end web development, yet it seems to often get short shrift. Creating accessible web applications is not only ethically sound, but also makes a lot of business sense considering the additional audience that will be able to view your applications when they are accessible.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [Applied Accessibility](https://learn.freecodecamp.org/) na freeCodeCamp.
- Read some content on [The A11Y Project](https://a11yproject.com/about)
- Review their [checklist](https://a11yproject.com/checklist)
- Update your site(s) for accessibility based on this checklist

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. (Source: [git-scm.com](https://git-scm.com/))

### :bulb: Szybkie podsumowanie

Version/code control is an essential part of any web developer's toolkit. There are a number of different version control systems, but Git is by far the most prevalent at the moment. You can (and should!) use it to track your projects as you learn!

### :book: Obszary nauki i pomysły

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

### :bulb: Szybkie podsumowanie

While nodejs is typically known as a back-end solution, it is used quite frequently to support front-end development. It does this in a number of ways, including things like running build tools, testing, and linting (all to be covered soon!). Node Package Manager (npm) is another great feature of node and can be used to manage dependencies of your project (i.e., code libraries your project might rely on -- jQuery is an example!).

### :book: Obszary nauki i pomysły

- Research node and how it is different than the browser
- Install node (npm comes with it)
- Create a simple javascript file and run it with node
- Use NPM to manage any dependencies in your existing project(s) (e.g., jQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass is an extension of CSS that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, inline imports, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly, particularly with the help of the Compass style library. (Source: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Szybkie podsumowanie

Sass allows you to write CSS in a more programmatic way. If you've done some CSS, you might have noticed that you end up repeating a lot of information--for example, specifying the same color code. In Sass, you can use things like variables, loops, and nesting to reduce redundancy and increase readability. After writing your code in Sass, you can quickly and easily compile it to regular CSS.

### :book: Obszary nauki i pomysły

- [Install Sass](https://sass-lang.com/install) globally with npm!
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- Follow the [Learn Sass](https://sass-lang.com/guide) tutorial and/or [freeCodeCamp](https://learn.freecodecamp.org/) Sass tutorial.
- Update your existing site to generate your CSS using Sass!

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* Some alternatives: Foundation, Bulma, Materialize

Bootstrap is a free and open-source front-end framework for developing websites and web applications. It contains HTML and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. (Source: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Szybkie podsumowanie

There are many options for laying out, styling, and making your web application dynamic, but you'll find that starting with a framework helps you tremendously in getting a head start. Bootstrap is one such framework, but it is definitely far from the only option! I recommend getting familiar with one framework like this, but it's far more important to grasp HTML, CSS, and JavaScript fundamentals than it is to get caught up in any one framework.

### :book: Obszary nauki i pomysły

- Learn what Bootstrap is and why you would want to use it
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Complete the Bootstrap section on [freeCodeCamp](https://learn.freecodecamp.org/)
- Refactor your site using bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project. (Source: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Szybkie podsumowanie

It's important to know naming and organization systems like BEM exist and why they are used. Do some research here, but at a beginner level I wouldn't recommend devoting too much time to the subject.

### :book: Obszary nauki i pomysły

- Read the [BEM introduction](http://getbem.com/introduction/)
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Create a simple webpage using BEM conventions.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something. (Source: [gulpjs.com](https://gulpjs.com/))

### :bulb: Szybkie podsumowanie

In modern front-end development, you'll often find yourself needing to automate tasks like bundling, moving files, and injecting references into HTML files. Gulp is one tool that can help you do these things!

### :book: Obszary nauki i pomysły

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

### :bulb: Szybkie podsumowanie

Imagine that you have a large web development project with a number of different developers working on a lot of different tasks. Rather than all working in the same files, you might want to modularize them as much as possible. Webpack helps enable this by letting your team work modularly and then, come time to build the application, Webpack will stick it all together: HTML, CSS/Sass, JavasScript, images, etc. Webpack isn't the only module bundler, but it seems to be the front-runner at the moment.

### :book: Obszary nauki i pomysły

- Read [webpack concepts](https://webpack.js.org/concepts/)
- [What is Webpack, How does it work? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [This webpack tutorial](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint is an open source JavaScript linting utility originally created by Nicholas C. Zakas in June 2013. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. There are code linters for most programming languages, and compilers sometimes incorporate linting into the compilation process. (Source: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Szybkie podsumowanie

Linting is a fantastic tool for code quality, readability, and consistency. Using a linter will help you catch syntax and formatting mistakes before they go to production. You can run linters manually or include them in your build/deployment process.

### :book: Obszary nauki i pomysły

- Install eslint using npm
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Lint your JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React (also known as React.js or ReactJS) is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. Complex React applications usually require the use of additional libraries for state management, routing, and interaction with an API. (source: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Szybkie podsumowanie

Front-end JavaScript frameworks are at the forefront of modern front-end development. One important takeaway here is that React, despite being incredibly popular, is only a library for building user interfaces whereas frameworks like Vue and Angular aim to be more full-featured. For example, if you build an application with in React that needs to route to different views, you'll need to bring in something like `react-router`.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [tutoriala z Reacta](https://reactjs.org/tutorial/tutorial.html)
- [Learn React with Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Refactor your website as a React app!
- Note: `create-react-app` is a convenient tool to scaffold new React projects.

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger. (Source: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Szybkie podsumowanie

As you build bigger and bigger front-end applications, you start realizing that it's hard to maintain application state: things like the if the user is logged in, who the user is, and generally what's going on in the application. Redux is a great library that helps you maintain a single source of state on which your application can base its logic.

### :book: Obszary nauki i pomysły

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

### :bulb: Szybkie podsumowanie

It is very important to set up automated testing for your front-end projects. Setting up automated testing will allow you to make future changes with confidence--if you make changes and your tests still pass, you will be fairly comfortable you didn't break any existing functionality. There are too many testing frameworks to list; Jest is simply one of my favorties.

### :book: Obszary nauki i pomysły

- Learn [Jest basics](https://jestjs.io/docs/en/getting-started)
- If you used `create-react-app`, [Jest is already configured](https://facebook.github.io/create-react-app/docs/running-tests).
- Add tests to your application!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternative: Flow

TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language. TypeScript is designed for development of large applications and transcompiles to JavaScript. As TypeScript is a superset of JavaScript, existing JavaScript programs are also valid TypeScript programs. TypeScript may be used to develop JavaScript applications for both client-side and server-side (Node.js) execution. (Source: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Szybkie podsumowanie

JavaScript is dynamically typed. However, it is a common belief that static typing (i.e., specifying variable types, classes, interfaces ahead of time) is both clearer and reduces the likelihood of defects/bugs. Regardless of how you feel on the topic, it's important to at least get a feel for a statically-typed version of JavaScript like TypeScript. Note that TypeScript compiles down to JavaScript so it can be interpreted by browsers (i.e., browsers don't natively interpret TypeScript).

### :book: Obszary nauki i pomysły

- [Learn TypeScript in 5 minutes](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Learn TypeScript in 50 minutes (Video)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Optionally [create a React app with TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js is a minimalistic framework for server-rendered React applications. (Source: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Szybkie podsumowanie

Now we're getting advanced! By now you've built a React (or Vue or Angular) application that does quite a bit of work in the browser. For various reasons (e.g., SEO, concerns over client performance), you might actually want your front-end application to be rendered on the server rather than the client. That's where a framework like next.js comes in.

### :book: Obszary nauki i pomysły

- Next.js [Getting Started](https://nextjs.org/learn/)
- [Next.js Crash Course (Video)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Create a Next.js app or migrate your existing app to Next.js

# But What About X?

This list is supposed to give you broad exposure to the front-end ecosystem, but it's simply impossible to hit on every single topic, not to mention the myriad tools within each area! If you do think I missed something very important, please see the [Contributing](#contributing) section to see how you can help make this guide better.

# Pomysły na projekty

W miarę postępów podczas #100DaysOfCode będziesz potrzebować jednego lub wielu projektów, do których możesz zastosować swoją nową wiedzę. W tej sekcji staram się przedstawić kilka pomysłów na projekt, z których możesz skorzystać. Możesz też zaproponować własne pomysły na projekty, które mogą Cię zainteresować i motywować.

- Pomysły dla początkujących:
  - Stwórz stronę z portfolio
- Pomysły dla średniozaawansowanych/zaawansowanych:
  - Zbuduj aplikację do analizy tweetów (jeśli znasz już backend i integrację interfejsu API)
  
# Potrzebujesz pomocy?

Ogólnie rzecz biorąc, uważam następujące materiały za nieocenione przy tworzeniu oprogramowania do nauki:

- Googlowanie określonego problemu
- [StackOverflow](http://www.stackoverflow.com) (Jest duża szansa, że twoje pytanie zostało już zadane i będzie wysoko w rankingu podczas wyszukiwania w Google).
- [Mozilla MDN Web Docs](https://developer.mozilla.org/en-US/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- Lokalne spotkania z dziedziny oprogramowania typu Meetups! Większość jest bardzo przyjazna dla wszystkich poziomów doświadczenia.

Jeśli chcesz mieć cokolwiek do powiedzenia, nie krępuj się [połączyć ze mną na Twitter](http://www.twitter.com/nas5w), dołożę wszelkich starań, aby zaoferować pomoc. Jeśli uważasz, że występuje problem z programem nauczania lub masz zalecenie, zobacz [sekcja Współtworzenie](#współtworzenie), która znajduje się poniżej.

# Współtworzenie

## Podaj dalej

Jeśli doceniasz pracę wykonaną tutaj, możesz znacząco przyczynić się w rozwój projektu rozpowszechniając informacje o tym repozytorium, w tym:

- Dając gwiazdkę lub tworząc fork tego repo
- Podzielić się tym repo w social media

## Współtworz to repozytorium

Jest to praca w toku (WIP) i bardzo doceniam wszelką pomoc w utrzymaniu tej bazy wiedzy!

Współuczestnicząc w tym repozytorium, przed wprowadzeniem zmiany omów najpierw zmianę, którą chcesz wprowadzić za pośrednictwem issue. W przeciwnym razie bardzo trudno będzie zrozumieć Twoją propozycję i może to potencjalnie spowodować, że włożysz dużo pracy w zmianę, która nie zostanie scalona, zmergowana.

Pamiętaj, że wszyscy zaangażowani w ten projekt albo próbują się uczyć, albo próbują pomóc - Bądź miły!

## Proces Pull Requestu

1. Stwórz issue dotyczący zarysu proponowanego pull requesta.
2. Uzyskaj zgodę właściciela projektu na wprowadzenie proponowanej zmiany.
3. Stwórz pull request.

_________________________________________________________________________

Stworzone przez [@nas5w](https://github.com/nas5w), polska wersja od [@mbiesiad](https://github.com/mbiesiad)
