<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Quer aprender mais sobre desenvolvimento front-end? Se inscreva na minha [newsletter gratuita](https://buttondown.email/typeofnan) para receber dicas sobre desenvolvimento front-end!

---

Esse é um currículo feito (com uma certa base na minha opinião) para aprender desenvolvimento front-end durante o desafio dos 100 Dias de Código. Como ele cobre uma diversa gama de tópicos sobre front-end, ele pode ser visto mais como um "curso introdutório" à estas áreas do que como um aprofundamento em qualquer uma delas. Idealmente, o que você vai levar ao finalizar o currículo é alguma familiaridade com cada tópico e a habilidade de se aprofundar em qualquer área quando for necessário.

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

\* Algumas alternativas: Foundation, Bulma, Materialize

O Bootstrap é um framework front-end gratuito e de código aberto para desenvolver sites e aplicações web. Ele contém templates baseados em HTML e CSS para tipografia, formulários, botões, navegação e outros componentes de interface, além de extensões JavaScript opcionais. (Fonte: [Wikipedia](<https://pt.wikipedia.org/wiki/Bootstrap_(framework_front-end)>))

### :bulb: Para Lembrar

Existem muitas opções para montar o layout, estilizar e dinamizar a sua aplicação web, mas você verá que começar com um framework vai te ajudar muito a dar o pontapé inicial em uma página. O Bootstrap é um desses frameworks, mas está longe de ser o único! Eu recomendo você se familiarizar com algum framework como esse, mas é muito mais importante saber os fundamentos do HTML, CSS e JavaScript do que se viciar em algum framework.

### :book: Áreas de Aprendizado e Ideias

- Aprenda o que é Bootstrap e porquê você deveria usá-lo
- [Curso introdutório de Bootstrap 4 (Vídeo em Inglês)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Complete a [seção de Bootstrap](https://learn.freecodecamp.org/) no site freeCodeCamp (em Inglês).
- Refatore o seu site usando Bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

A metodologia Bloco, Elemento, Modificador (conhecida como BEM) é uma convenção de nomeação de classes no HTML e no CSS. Desenvolvida pela Yandex, o seu objetivo é ajudar os desenvolvedores a entenderem melhor a relação entre HTML e CSS em um projeto. (Fonte: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Para Lembrar

É importante saber que sistemas de nomeação/organização como o BEM existem e para quê eles são usados. Pesquise um pouco sobre o BEM, mas em um nível iniciante eu não recomendaria dedicar muito tempo a isso.

### :book: Áreas de Aprendizado e Ideias

- Leia a [introdução ao BEM](http://getbem.com/introduction/) (Site em Inglês)
- Como alternativa, [leia esse artigo em Portugês](https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439)
- [Porquê eu uso o BEM (Vídeo em inglês)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Crie uma página web simples usando as convenções do BEM.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

O Gulp é um kit de ferramentas para automatizar tarefas demoradas ou entediantes no seu workflow de desenvolvimento, para que você possa parar de brincar e realmente construir algo. (Fonte: [gulpjs.com](https://gulpjs.com/))

### :bulb: Para Lembrar

No desenvolvimento front-end moderno, você vai frequentemente se encontrar precisando automatizar tarefas como combinar e mover arquivos e injetar referências em arquivos HTML. O Gulp é uma ferramenta que pode te ajudar a realizar essas coisas!

### :book: Áreas de Aprendizado e Ideias

- Instale o Gulp com o npm
- Siga o [tutorial de Gulp para iniciantes](https://css-tricks.com/gulp-for-beginners/) no site CSS-Tricks (Em Inglês)
- No seu site, use o Gulp para:
  - Compilar o Sass para você
  - Colocar o arquivo CSS gerado no subdiretório `build`
  - Mova suas páginas web para o diretório da build
  - Injetar uma referência à seu arquivo CSS gerado anteriormente nas suas páginas.

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

Em seu núcleo, o webpack é um agrupador de módulos estáticos para aplicações JavaScript modernas. Quando o webpack processa uma aplicação, ele mapeia internamente todos os módulos necessários para sua execução e gera um ou mais agrupamentos. (Fonte: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Para Lembrar

Imagine que você tenha um projeto de desenvolvimento web grande, com diversos desenvolvedores trabalhando em diversas tarefas. Ao invés de ter todos eles trabalhando no mesmo arquivo, pode ser que você prefira modularizar os arquivos tanto quanto possível. O webpack ajuda a fazer isso, pois ele deixa o seu time trabalhar de forma modularizada e então, quando for a hora de construir a aplicação, o webpack junta tudo: HTML, CSS/Sass, JavaScript, imagens, etc. O webpack não é o único agrupador de módulos, mas no momento ele está na liderança.

### :book: Áreas de Aprendizado e Ideias

- Leia os [conceitos de webpack](https://webpack.js.org/concepts/) (Site em Inglês)
- [O que é webpack e como ele funciona? (Vídeo em Inglês)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [Esse tutorial de webpack](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1) (Site em Inglẽs)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

O ESLint é uma utilidade de código aberto de lintagem de código JavaScript, criada originalmente por Nicholas C. Zakas em Junho de 2013. Lintagem de código é um tipo de análise estática que é usado frequentemente para encontrar padrões problemáticos ou código que não cumpre certas convenções. Existem softwares de lintagem para a maioria das linguagens de programação, e algumas vezes os próprios compiladores possuem o processo de lintagem incorporado com o processo de compilação. (Fonte: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Para Lembrar

A lintagem é uma ferramenta fantástica para manter a qualidade, a consistência e a legibilidade do código. Usar um software de lintagem vai ajudar a achar erros de sintaxe e formação antes de eles irem para a produção. Você pode rodar esses softwares manualmente ou incluí-los no seu processo de build/deploy.

### :book: Áreas de Aprendizado e Ideias

- Instale o ESLint usando o npm
- [Como configurar o VS Code + Prettier + ESLint (Vídeo em Inglês)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Use o ESLint em um arquivo JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Algumas Alternativas: Vue, Angular, Ember

O React (também conhecido como React.js ou ReactJS) é uma biblioteca JavaScript usada para construir interfaces. Ela é mantida pelo Facebook e por uma comunidade de desenvolvedores e empresas. O React pode ser usado como uma base no desenvolvimento de aplicações de uma página só (SPAs) e aplicações mobile. Aplicações React complexas normalmente necessitam do uso de bibliotecas adicionais para fazer o gerenciamento de estado, roteamento e interações com APIs. (Fonte: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Para Lembrar

Frameworks JavaScript para front-end são os líderes no desenvolvimento front-end moderno. Algo importante para se lembrar é que, apesar de ser incrivelmente popular, o React é somente uma bilbioteca para construir interfaces de usuários, enquanto frameworks como Vue e Angular possuem mais funcionalidades. Por exemplo, se você construir uma aplicação com React que precise rotear para diferentes visões (ver [MVC](https://pt.wikipedia.org/wiki/MVC)), você precisará de algo como o `react-router`.

### :book: Áreas de Aprendizado e Ideias

- Faça o [tutorial do React](https://pt-br.reactjs.org/tutorial/tutorial.html) (Site em Português)
- [Aprenda React com o Mosh (Vídeo em Inglês)](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Refatore o seu site como uma aplicação React!
- Nota: o `create-react-app` é uma ferramenta conveniente para montar o esqueleto de novos projetos React.

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

O Jest é um framework para Testes em programas JavaScript, focado em simplicidade. Ele funciona com projetos contendo Babel, TypeScript, Node, React, Angular, Vue e outros! (Fonte: [jestjs.io](https://jestjs.io))

### :bulb: Para Lembrar

É muito importante desenvolver testes automatizados para seus projetos de front-end. Configurar testes automatizados vai te possibilitar fazer mudanças futuras com confiança. Se você fez mudanças e os testes ainda passam, você vai poder ter quase certeza de que nada foi quebrado. Existem muitos frameworks de testes para poder listar todos, mas o Jest é um dos meus favoritos.

### :book: Áreas de Aprendizado e Ideias

- Aprenda os [básicos do Jest](https://jestjs.io/docs/pt-BR/getting-started)
- Se você usou o comando `create-react-app`, [o Jest já está configurado](https://facebook.github.io/create-react-app/docs/running-tests).
- Crie testes para a sua aplicação!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternativa: Flow

O TypeScript é uma linguagem de programação open-source desenvolvida e mantida pela Microsoft. É um superconjunto sintático do JavaScript, e adiciona tipagem estática opcional à linguagem. O TypeScript foi feito para o desenvolvimento de grandes aplicações e ele transcompila para JavaScript. Já que o TypeScript é um superconjunto do JavaScript, programas em JavaScript também são programas em TypeScript. O TypeScript pode ser usado para desenvolver aplicações JavaScript para serem executadas tanto do lado do cliente quanto do lado do servidor (Node.js). (Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/TypeScript)

### :bulb: Para Lembrar

O JavaScript é dinamicamente tipado. No entanto, é uma crença popular que a tipagem estática (especificando tipos de variáveis, classes e interfaces na declaração) é mais limpa e reduz a possibilidade de ocorrência de erros e bugs. Independente da sua opinião, é importante pelo menos experimentar uma versão com tipagem estática para o JavaScript (como o TypeScript). Perceba que o TypeScript é transpilado para JavaScript, para que ele pode ser interpretado pelo navegador, ou seja, os navegadores não interpretam o TypeScript nativamente.

### :book: Áreas de Aprendizado e Ideias

- [Aprenda TypeScript em 5 minutos](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb) (artigo em Inglês)
- [Aprenda TypeScript em 50 minutos (Vídeo em Inglês)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Opcionalmente, [crie um app React usando TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4) (artigo em Inglês)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js é um framework minimalista para renderizar aplicações React do lado do servidor. (Fonte: [Next.js — Renderização Correta do React no Servidor](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Para Lembrar

Agora tá ficando avançado! Você já construiu uma aplicação em React (ou Vue ou Angular) que faz bastante trabalho no navegador. Por diversas razões (SEO, preocupação com performance do lado do cliente...), você pode querer que sua aplicação front-end seja renderizada no servidor e não no cliente. É aí que entram frameworks como o next.js.

### :book: Áreas de Aprendizado e Ideias

- [Iniciando no Next.js](https://nextjs.org/learn/) (Site em Inglês)
- [Curso Introdutório de Next.js (Vídeo em Inglês)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Crie uma aplicação usando o Next.js ou migre a sua aplicação existente para usá-lo!

# Mas e X tecnologia?

Essa lista existe para te dar uma visão abrangente do ecossistema de front-end, mas é simplesmente impossível abordar todos os tópicos existentes, sem nem mencionar a grande quantidade de ferramentas dentro de cada área! Se você acha que eu esqueci de algo importante, por favor veja a seção de [Contribuição](#contributing) para ver como você pode ajudar a melhorar esse guia!

# Ideias de Projetos

Enquanto você estiver progredindo pelo desafio dos 100 Dias de Código, você vai querer fazer um ou mais projetos nos quais você possa aplicar seus novos conhecimentos. Nessa seção, eu tento disponibilizar algumas ideias de projetos que você pode fazer. Como alternativa, você é encorajado a pensar em seus próprios projetos, já que estes podem te interessar e motivar mais.

- Ideias para iniciantes:
  - Construa um site de portfolio
- Ideias intermediárias/avançadas:
  - Construa uma aplicação de análise de tweets (Se você já souber como integrar com back-ends e APIs)
  
# Precisa de Ajuda?

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
