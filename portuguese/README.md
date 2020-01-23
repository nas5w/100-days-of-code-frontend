<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Quer aprender mais sobre desenvolvimento front-end? Se inscreva na minha [newsletter gratuita](https://buttondown.email/typeofnan) onde eu mando regularmente porções de conhecimento sobre front-end!

---

Esse é um currículo feito (com uma certa base na minha opinião) para aprender desenvolvimento front-end durante o desafio dos #100DiasDeCodigo. Como ele cobre uma diversa gama de tópicos sobre front-end, ele pode ser visto mais como um "curso introdutório" à estas áreas do que como um aprofundamento em qualquer uma delas. Idealmente, o que você vai levar ao finalizar o currículo é alguma familiaridade com cada tópico e a habilidade de se aprofundar em qualquer área quando for necessário.

Esse currículo foi influenciado fortemente pelo [Mapa de Conceitos Front-End Moderno](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c) de Kamran Ahmed. Dê uma olhada, é excelente!

**Nota**: Eu sei que desenvolvimento front-end pode representar várias coisas diferentes para pessoas diferentes. Se você é um desenvolvedor front-end e acha que esse guia pode ser melhorado, por favor me avise criando um issue como descrito na seção [Contribuindo](#contributing). Obrigado!

# Traduções
Graças à alguns contribuidores incríveis, esse currículo foi traduzido para as seguintes linguagens:

- [Russo русский](/ru) (traduzido por [@Ibochkarev](https://github.com/Ibochkarev) e [@JonikUl](https://github.com/JonikUl))
- [Chinês 中文](/chinese) (traduzido por [@simplefeel](https://github.com/simplefeel))

# :calendar: Currículo

O princípio desse repositório é o [timeboxing](https://eadbox.com/timeboxing/). Se você já usou seu tempo no passado tentando aprender desenvolvimento web ou uma habilidade similar, você provavelmente já teve a experiência de se aprofundar demais em um determinado tópico. Esse repositório visa definir um certo número de dias para cada tecnologia e propõe a você passar para a próxima tecnologia assim que esse número de dias passe.

É antecipado que todos estejam em um nível diferente de conhecimento quando começarem esse desafio, mas isso não é um problema. Qualquer desenvolvedor front-end, seja ele iniciante ou experiente, pode tirar proveito do uso do método *timeboxing* para praticar cada uma dessas áreas.

As atividades recomendadas para cada período de tempo são:

- Dias 1-8: [HTML](#html)
- Dias 9-16: [CSS](#css)
- Dias 17-24: [Javascript Básico](#javascript)
- Dias 25-27: [jQuery](#jquery)
- Dias 28-33: [Web Design Responsivo](#rwd)
- Dias 34-36: [Acessibilidade](#accessibility)
- Dias 37-39: [Git](#git)
- Dias 40-44: [Node e NPM](#node)
- Dias 45-50: [Sass](#sass)
- Dias 51-54: [Bootstrap](#bootstrap)
- Dia 55: [BEM](#bem)
- Dias 57-61: [Gulp](#gulp)
- Dias 62-65: [Webpack](#webpack)
- Dia 66: [ESLint](#eslint)
- Dias 68-83: [React](#react)
- Dias 84-89: [Redux](#redux)
- Dias 90-94: [Jest](#jest)
- Dias 95-97: [TypeScript](#typescript)
- Dias 98-100: [NextJS](#nextjs)

# :mag_right: Detalhes

Abaixo você vai encontrar informações sobre cada tópico junto com um guia/ideias do que fazer para cada um. Caso você queira ideias de projetos para fazer junto com esse currículo, veja a seção de [Ideias de Projetos](#project-ideas).

Como parte do princípio do *timeboxing*, não tem problema se você não completar todos os itens nas seções de "Áreas de aprendizado e ideias". Ao invés disso, você deve se focar em conseguir tirar o maior proveito do número de dias dedicados à cada área e então ir adiante.

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

A Linguagem de Marcação de Hipertexto (HyperText Markup Language - HTML) é a linguagem de marcação padrão para criar páginas e aplicações web. Junto com as Folhas de Estilo em Cascata (Cascading Style Sheets - CSS) e o JavaScript, é formada a tríade das tecnologias fundamentais para a World Wide Web (WWW). Navegadores Web recebem documentos HTML de um servidor web ou do armazenamento local e renderizam os documentos em páginas multimídia. O HTML descreve a estrutura da página de maneira semântica e originalmente também descrevia parte de sua aparência. (Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/HTML))

### :bulb: Para Lembrar

HTML é a base do desenvolvimento web. Mesmo em frameworks baseados em JavaScript você acaba escrevendo HTML, de uma forma ou de outra.

### :book: Áreas de Aprendizado e Ideias

- Faça a [seção de HTML e HTML5 básicos](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Estrutura de página no HTML
- Elementos HTML
- Encadeamento de elementos HTML
- Marcação Semântica
- Links / diversas páginas
- Imagens
- Mídia de áudio/vídeo
- Formulários e elementos de formulário
- Crie um website com diversas páginas! (Veja as [Ideias de Projetos](#project-ideas) se você precisar se inspirar).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Folhas de Estilo em Cascata (Cascading Style Sheets - CSS) é uma linguagem de folhas de estilo usada para descrever a apresentação de um documento escrito em uma linguagem de marcação (como HTML). CSS é uma tecnologia fundamental na World Wide Web (WWW), assim como o HTML e o JavaScript. O CSS foi desenhado para possibilitar a separação entre a apresentação e o conteúdo, incluindo o layout, as cores e as fontes. Essa separação melhora a acessibilidade ao conteúdo, provém mais flexibilidade e controle na especificação das características da apresentação, possibilita múltiplas páginas web compartilharem a formatação especificando o CSS em um arquivo .css separado e reduz a complexidade e a repetição no conteúdo estrutural. (Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Para Lembrar

CSS é outro componente essencial no desenvolvimento web. Mesmo sendo usado principalmente para estilizar e posicionar elementos HTML, ele vem se tornando cada vez mais capaz de realizar tarefas mais dinâmicas (como animações) que seriam originalmente feitas com JavaScript.

### :book: Áreas de Aprendizado e Ideias

- Faça as [seções de CSS básico, CSS flexbox, e CSS grid](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- CSS in-line
- elementos `<style>`
- CSS externo com `<link>`
- Estilizando elementos
- Seletores
- Floats, limpando floats
- Layouts (grid, flexbox)
- Fontes, fontes customizadas
- Estilize a página HTML que você fez quando estava aprendendo HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript, frequentemente abreviado como JS, é uma linguagem interpretada de alto nível que está de acordo com a especificação ECMAScript. Possui tipagem dinâmica fraca, é baseada em protótipos e é multi-paradigma. Junto com HTML e CSS, o JavaScript é uma das três principais tecnologias da World Wide Web. O JavaScript possibilita páginas web interativas e, portanto, é uma parte essencial das aplicações web. A grande maioria dos websites a usam, e todos os principais navegadores possuem um motor JavaScript que possibilita executá-lo. (Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/JavaScript))

### :bulb: Para Lembrar

JavaScript vem se tornando cada vez mais popular no mundo front-end. Ao contrário de quando era usado principalmente para fazer páginas dinâmicas, agora ele é a base de vários frameworks front-end. Esses frameworks realizam diversas tarefas que eram originalmente realizadas pelo back-end (como, por exemplo, roteamento e mostrar diferentes páginas).

### :book: Áreas de Aprendizado e Ideias

- Faça as [seções de JavaScript básico e ES6](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Muitos fundamentos da linguagem para poder listar aqui!
- Elemento `<script>` e seu posicionamento
- Acessar elementos HTML
- Event-loop, pilha de chamadas e fila de eventos
- Herança de Protótipos
- Referência X Valor
- Adicione alguns elementos dinâmicos ou alguma lógica à sua(s) página(s) HTML/CSS desenvolvidas anteriormente!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery é uma biblioteca JavaScript rápida, pequena e rica em funcionalidades. Ela simplifica conceitos como a travessia e manipulação de documentos HTML, eventos, animação e Ajax com uma API fácil de usar que funciona em diversos navegadores. Com uma combinação de versabilidade e extensibilidade, jQuery mudou a maneira como milhões de pessoas escrevem JavaScript (Fonte: [jQuery.com](https://jquery.com/))

### :bulb: Para Lembrar

Depois que você tiver usado um pouco o JavaScript puro (também chamado "vanilla"), você pode ter achado algumas tarefas muito pesadas, especialmente aquelas que envolvem acessar e manipular elementos HTML. Por um bom tempo, jQuery era a principal solução para facilitar essas tarefas e as tornar consistentes em diferentes navegadores. Hoje em dia, o jQuery não é mais tão necessário devido aos avanços no JavaScript puro, no CSS e frameworks JavaScript mais novos (nós veremos esses frameworks mais à frente). Mesmo assim, pode ser benéfico aprender um pouco de jQuery e aplicá-lo em algum projeto pequeno.

### :book: Áreas de Aprendizado e Ideias

- Faça a [seção de jQuery](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Document ready
- Seletores
- Alternância de classes
- Animação
- Adicionar ou mover elementos HTML
- Adicione jQuery ao seu site!

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

Desing Web Responsivo (Responsive Web Desing - RWD) é uma abordagem de design web que faz páginas serem bem apresentadas em uma variedade de dispositivos e tamanhos de tela. Recentemente também vem se considerando a proximidade do usuário como parte do contexto, como uma extensão ao Web Design Responsivo. Conteúdo, design e performance são necessários em todos os dispositivos para garantir usabilidade e satisfação. Um site responsivo adapta o layout à tela usando grids baseados em proporção, imagens flexíveis e *media queries* do CSS3. (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Para Lembrar

A principal ideia do Design Web Responsivo é fazer as aplicações web parecerem e funcionarem corretamente em todos os tipos de dispositivos. Um exemplo é que um site tem que parecer e funcionar bem tanto em um computador quanto em um celular. Entender o Design Web Responsivo é essencial para todos os desenvolvedores front-end!

### :book: Áreas de Aprendizado e Ideias

- Faça a [seção de Princípios de Design Web Responsivo](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Media queries e breakpoints
- Imagens responsivas
- Faça seu site desenvolvido anteriormente responsivo!
- Use a extensão Chrome DevTools para ver seu site em diferentes dispositivos/tamanhos.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Acessibilidade na Web é a prática de incluir, garantindo que não existam barreiras que impessam a interação ou o acesso a um website por pessoas com deficiência. Quando um site é desenhado, desenvolvido e editado de maneira correta, geralmente todos os usuários podem acessar as funcionalidades e o conteúdo. (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Para Lembrar

Acessibilidade, às vezes escrita como "a11y", é um dos tópicos mais importantes no desenvolvimento web front-end, mas às vezes ela não recebe a atenção que merece. Criar aplicações web acessíveis não é somente eticamente correto, mas também faz sentido no âmbito empresarial, se considerado o aumento do público que poderá ver as suas aplicações.

### :book: Áreas de Aprendizado e Ideias

- Faça a [seção de Acessibilidade Aplicada](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Leia um pouco no site do [Projeto A11Y](https://a11yproject.com/about) (em Inglês).
- Veja a [checklist](https://a11yproject.com/checklist) deles
- Deixe seu website acessível com base nessa checklist

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git é um sistema de versionamento gratuito e de código aberto, feito para lidar com todos os tipos e tamanhos de projetos com velocidade e eficiência. (Fonte: [git-scm.com](https://git-scm.com/))

### :bulb: Para Lembrar

Versionamento/Controle de Código é uma ferramenta essencial para todos os desenvolvedores web. Existem diversos sistemas de versionamento de código diferentes, mas o Git é, sem sombra de dúvidas, a mais popular atualmente. Você pode (e deve!) usá-lo para monitorar seus projetos enquanto você aprende.

### :book: Áreas de Aprendizado e Ideias

- [Tutorial de Git para iniciantes (Vídeo em inglês)](https://www.youtube.com/watch?v=HVsySz-h9r4)
- Instale o git
- Crie uma conta no [GitHub](https://github.com)
- Aprenda os comandos do git mais usados:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- Adicione os seus projetos ao GitHub!

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

O Node.js é um ambiente de tempo de execução de código aberto e multiplataforma, que executa código JavaScript fora de um navegador. O JavaScript é usado principalmente no cliente, onde códigos escritos em JavaScript são executados pelo navegador em uma página HTML. O Node.js permite que os desenvolvedores usem JavaScript para desenvolver ferramentas de linha de comando e scripts do lado do servidor - executando scripts no lado do servidor para produzir conteúdo dinâmico na página web antes que a página seja enviada ao navegador do usuário. Consequentemente, o Node.js representa um paradigma de "JavaScript em todos os lugares", unificando o desenvolvimento de aplicativos da Web em torno de uma única linguagem de programação, em vez de diferentes linguagens para scripts do servidor e do cliente. (Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/Node.js))

### :bulb: Para Lembrar

Mesmo o Node.js sendo tipicamente usado como uma ferramenta para o back-end, ele é usado com certa frequência como suporte para o desenvolvimento front-end. Isso é feito de diversas maneiras, incluindo coisas como rodar ferramentas de build, teste e lintagem (Todas serão vistas em breve!). O Node Package Manager (npm) é uma outra funcionalidade interessante do node, usada para gerenciar as dependências do seu projeto (por exemplo, bibliotecas de código que o seu projeto usa, como jQuery).

### :book: Áreas de Aprendizado e Ideias

- Pesquise sobre o node e veja como ele é diferente do navegador
- Instale o node (o NPM vem junto)
- Crie um arquivo JavaScript simples e execute-o com node
- Use o NPM para gerenciar as dependências em seus projetos existentes (jQuery, por exemplo)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

O Sass é uma extensão do CSS que o deixa mais poderoso e elegante. Ela possibilita o uso de variáveis, regras encadeadas, mixins, importações inline e mais, tudo com uma sintaxe compatível com o CSS. O Sass ajuda a manter folhas de estilo grandes organizadas, e possibilita preparar pequenas folhas de estilo rapidamente, com a ajuda da biblioteca de estilos Compass. (Fonte: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Para Lembrar

Sass possibilita escrever CSS de uma maneira mais parecida com uma linguagem de programação. Se você já usou CSS, pode ser que você tenha percebido que existe muita repetição de informações (especificar várias vezes a mesma cor, por exemplo). No Sass, é possível usar variáveis, laços de repetição e encadeamento para reduzir a redundância e facilitar o entendimento. O código em Sass pode ser fácil e rapidamente compilado para CSS normal.

### :book: Áreas de Aprendizado e Ideias

- [Instale o Sass](https://sass-lang.com/install) globalmente com o npm!
- [Curso introdutório de Sass (Vídeo em Inglês)](https://www.youtube.com/watch?v=roywYSEPSvc)
- Siga o [Tutorial do Sass](https://sass-lang.com/guide) e/ou o [Tutorial do Sass no freeCodeCamp](https://learn.freecodecamp.org/) (Sites em Inglês)
- Atualize seu site existente e gere o CSS usando Sass!

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
