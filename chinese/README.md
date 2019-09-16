<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

这是一门有点宽泛的在#100DaysOfCode学习前端开发的课程。由于这个课程涉及了大部分的前端开发相关的主题，但并没有深入的去探究某个主题，因而它更适合用来作为一个学习方向性的指导。理想情况下，您完成了这个课程之后，您至少对每个主题都能了解，并且在将来需要的时候能够方便的进行深入探究。

这个课程受 Kamran Ahmed's [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c) 图谱深刻影响，请关注下这个非常优秀的图谱。

**注意**：我知道不同的人对前端开发的理解或者掌握是不一样的，如果您是个前端开发者，认为这个课程可以做的更好，请在[Contributing](#contributing)功能区提交一个issue来描述您的想法，谢谢！

# 翻译

感谢一些热情的贡献者，这个课程已经被翻译成如下的语言！

- [俄文](/ru) (翻译者： [@Ibochkarev](https://github.com/Ibochkarev) 和 [@JonikUl](https://github.com/JonikUl))

# :calendar: 总课程

这个仓库的核心原则是[时间区块](https://en.wikipedia.org/wiki/Timeboxing)。如果你过去你已经花费了一些时间学习web开发或者相似的技能，你可能已经经历过课程中一些主题。这个仓库的目的就是给每个主题划定一个时间段，一旦某个主题的时间已过，你就应该前往下一个主题继续学习。

开始这个挑战前，可能每个参加者的开发水平不一致，这没关系，不管您是初学者或者是专家，都能从每个主题里面收获到新的知识。

推荐的时间安排如下：

- 第 1-8 天: [HTML](#html)
- 第 9-16 天: [CSS](#css)
- 第 17-24 天: [JavaScript Basics](#javascript)
- 第 25-27 天: [jQuery](#jquery)
- 第 28-33 天: [Responsive Web Design](#rwd)
- 第 34-36 天: [Accessibility](#accessibility)
- 第 37-39 天: [Git](#git)
- 第 40-44 天: [Node and NPM](#node)
- 第 45-50 天: [Sass](#sass)
- 第 51-54 天: [Bootstrap](#bootstrap)
- 第 55 天: [BEM](#bem)
- 第 57-61 天: [Gulp](#gulp)
- 第 62-65 天: [Webpack](#webpack)
- 第 66 天: [ESLint](#eslint)
- 第 68-83 天: [React](#react)
- 第 84-89 天: [Redux](#redux)
- 第 90-94 天: [Jest](#jest)
- 第 95-97 天: [TypeScript](#typescript)
- 第 98-100 天: [NextJS](#nextjs)

# :mag_right: 说明

接下来你能从这个课程里找到一些有关每个主题的信息或者学习向导。获取与此项目有关的一些灵感，请看[项目思想章节](#project-ideas)。

作为时间区块原则的一部分，如果你不能通过“学习章节和灵感”当中的所有项目。你应该把主要精力放在你能够投入的部分，然后继续学习其他部分。

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

超文本标记语言（HTML）是创建web页面和应用的标准语言。加上层叠样式表（CSS），是万维网的基石。Web浏览器从服务端或者本地存储接收HTML文档，然后将它渲染层页面。HTML从语义上描述了一个页面的结构，以及包含了文档结构的提示。（来源：[Wikipedia](https://en.wikipedia.org/wiki/HTML)）

### :bulb: 快速了解

HTML真的是web开发的基石。即使是在基于javascript开发框架的今天，你只不过是以另一种形式编写HTML而已。

### :book: 学习要点和想法

- 在freeCodeCamp上学习[基础HTML和HTML5章节](https://learn.freecodecamp.org/).
- HTML页面结构
- HTML元素
- 嵌套HTML元素
- 语义化标记
- 链接 / 多页
- 图片
- 音频 / 视频媒体
- 表单和表单元素
- 创建一个多页网站 (如果你需要一些灵感，查看 [项目灵感](#project-ideas) ).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

层叠样式表（CSS）是一个样式脚本语言，被用来描述通过标记语言例如HTML编写的文档的表现。CSS是万维网的基石技术。CSS能够使文档的表现和内容分离，包括布局，颜色和尺寸。这种分离能够提高文本的可访问性，在表现特征方面，提供了更多的灵活性和可控制性，通过引入分离开的.css文件，使多页应用能够共享表现，降低了复杂度和重复性的内容。（来源：[Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)）


### :bulb: 快速了解

CSS是另外一种很重要的的web组件开发的技术。因为它主要被用于描述和层现HTML元素，它逐渐变得变得越来强大，能够处理一些之前只能由javascript处理的内容，比如动画。

### :book: 学习章节和灵感

- 在freeCodeCamp上学习[基础CSS，CSS felxbox, 和CSS grid 布局部分](https://learn.freecodecamp.org/).
- 形内CSS
- `<style>` 标签
- 通过 `<link>` 引入CSS
- 样式元素
- 选择器
- 浮动，清除浮动
- 布局 (grid, flexbox)
- 字体，自定义字体
- 当学习HTML的时候，布局HTML页面

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript，经常被简称为JS，是一个高水准的，符合ECMAScript规范的解释性语言。它同时也是一个动态型的，弱类型的，基于原型的语言。和HTML和CSS一样，JavaScript是web开发当中三种核心技术之一。JavaScript能够使web页面具有可交互性，因此是web应用开发当中重要的一部分。绝大多数网站都使用它，并且大多数web浏览器都有专门的javascript引擎来执行它。(来源: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: 快速了解

在今天的前端开发世界，JavaScript已经变得越来越重要了。过去它只是被用来创建动态页面，如今它是很多前端开发框架的基石。这些框架处理了很多过去常常是后端处理的一些任务，比如路由和分发不同的视图。

### :book: 学习要点和想法

- 在freeCodeCamp上学习[JavaScript基础知识以及ES6相关知识](https://learn.freecodecamp.org/)。
- 太多有关这门语言的基础需要罗列
- `<script>` 标签和放置位置
- 访问HTML元素
- 事件循环、调用栈和事件队列
- 原型继承
- 值引用和地址引用
- 动态添加一些元素和逻辑到您的页面上

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery是一个快速的，小巧的和功能丰富的JavaScript库。相比使用原生API，他让遍历和操控HTML文档，事件处理，动画和发送Ajax请求变得更容易。由于它的丰富功能以及可扩展性，jQuery已经改变了成千上万开发者编写JavaScript的方式。(来源: [jQuery.com](https://jquery.com/))

### :bulb: 快速了解

在您花费了一些时间使用原生javascript之后，您可能发现它会有点繁琐，尤其是访问和操纵HTML元素。相当一段时间，jQuery是首选的让这些跨浏览器的事情处理起来更容易的库，如今，随着原生javascript，css和新的框架的不断发展（我们之后再细看框架），jQuery不再是必需要学的技术点，然而，花费少量时间去学习它并且把它运用在一些小的项目里还是值得的。

### :book: 学习要点和想法

- 在freeCodeCamp上学习[jQuery](https://learn.freecodecamp.org/).
- 文档初始化
- 选择器
- 切换类
- 动画
- 增加或者删除元素
- 在您的网站上使用jQuery！

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

响应式设计（RWD）是一种能够使页面在不同设备窗口或不同屏幕尺寸良好渲染的设计方式。现在还需要将试图内容显示优先级作为RWD设计的一部分。内容，设计和性能都是重要的，确保跨设备访问的易用性和满意度。一个响应式设计的网站通过使用流式布局，基于比例的网格，伸缩性图片和CSS3媒体查询使得网站能够适配布局不同的显示环境。(来源: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: 快速了解

响应式设计的全部内容就是使得web应用能够在所有的设备里面正常查看和运行。一个实际点的描述就是一个网站能够在桌面浏览器和移动端手机浏览器上能够正常查看和运行。理解响应式设计对于前端开发者来讲很重要。

### :book: 学习要点和想法

- 在freeCodeCamp上学习[响应式设计布局方法](https://learn.freecodecamp.org/).
- 媒体查询，断点
- 响应式图片
- 让你的网站能够响应式
- 使用Chrome开发者工具查看你的网站在不同设备/视图的展现

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

页面可访问性是指网站能够让残疾人正常访问和交互的包容性的一种做法。一个网站如果被合理的设计，开发，应该是能够让所有用户都能够获取信息和使用功能的。(来源: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: 快速了解

可访问性，经常被简写为a11y，是前端web开发重要的主题之一，然而它经常被忽视。创建可访问性web应用不仅仅是出于道德，考虑这部分用户从商业角度也是存在很多价值的。

### :book: 学习要点和想法

- 在freeCodeCamp上学习 [Applied Accessibility section](https://learn.freecodecamp.org/) .
- 查看一些有关响应式设计的项目 [The A11Y Project](https://a11yproject.com/about)
- 复查它们的实现功能列表 [checklist](https://a11yproject.com/checklist)
- 根据这个checklist核查自己的网站并完善遗漏的功能

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git是一个免费和开源的分布式版本控制系统，提升项目开发的速度和效率。(来源： [git-scm.com](https://git-scm.com/))

### :bulb: 快速了解

版本控制是web开发者重要的工具之一。有许多不同的版本控制系统，如今Git是最流行的一个。你应该学会使用Git来管理你的项目！

### :book: 学习要点和想法

- [面向初学者的Git教程](https://www.youtube.com/watch?v=HVsySz-h9r4)
- 安装git
- 简历一个 [github](https://github.com) 账户
- 学习最常使用的Git命令:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- 把您本地的项目上传到github

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

Node.js是一个开源的，跨平台的能够使javascript代码在浏览器之外运行的环境。JavaScript主要用于客户端脚本，其中用JavaScript编写的脚本嵌入在网页的HTML中，并在用户的Web浏览器中通过JavaScript引擎在客户端运行。Node.js允许开发人员使用JavaScript编写命令行工具，并在服务器端运行脚本，以便在将页面发送到用户的Web浏览器之前生成动态网页内容。因此，Node.js代表了“JavaScript无处不在”的范例，围绕单一编程语言统一Web应用程序开发，而不是服务器端和客户端脚本的不同语言。

### :bulb: 快速了解

虽然nodejs通常被称为后端解决方案，但它经常用于支持前端开发。它通过多种方式实现这一点，包括运行构建工具，测试和规范检查（所有这些都很快就会被覆盖！）。节点包管理器（npm）是node的另一个重要特性，可用于管理项目的依赖关系（即，项目可能依赖的代码库 - jQuery就是一个例子！）。

### :book: 学习要点和想法

- 研究node以及它与浏览器的不同之处
- 安装node（包含npm）
- 创建一个简单的javascript文件并使用node运行它
- 使用NPM管理现有项目中的任何依赖项（例如，jQuery！）

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass是CSS的扩展，为基本语言增添了力量和优雅。它允许您使用变量，嵌套规则，混合，内联导入等，所有这些都使用完全CSS兼容的语法。 Sass有助于保持大型样式表的良好组织，并使小样式表快速启动和运行，特别是在Compass样式库的帮助下。(来源: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: 快速了解

Sass允许您以更加编程的方式编写CSS。如果您已经完成了一些CSS，您可能已经注意到最终会重复大量信息 - 例如，指定相同的颜色代码。在Sass中，您可以使用变量，循环和嵌套等内容来减少冗余并提高可读性。在Sass中编写代码后，您可以快速轻松地将其编译为常规CSS。

### :book: 学习要点和想法

- [Install Sass](https://sass-lang.com/install) 通过npm全局安装!
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- 关注 [Learn Sass](https://sass-lang.com/guide) 教程或者 [freeCodeCamp](https://learn.freecodecamp.org/) Sass 教程.
- 更新现有网站，使用Sass生成CSS！

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* 相似的库: Foundation, Bulma, Materialize

Bootstrap是一个免费的开源前端框架，用于开发网站和Web应用程序。它包含用于排版，表单，按钮，导航和其他界面组件的HTML和基于CSS的设计模板，以及可选的JavaScript扩展。(摘自: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))
### :bulb: 快速了解

布局，样式化和使Web应用程序动态化有很多选择，但是你会发现从框架开始可以帮助你获得良好的开端。 Bootstrap就是这样一个框架，但它绝对不是唯一的选择！我建议熟悉这样的一个框架，但掌握HTML，CSS和JavaScript基础知识要比陷入任何一个框架要重要得多。

### :book: 学习要点和想法

- 了解Bootstrap是什么以及为什么要使用它
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- 完成Bootstrap部分在 [freeCodeCamp](https://learn.freecodecamp.org/)
- 使用bootstrap重构您的网站！

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

块，元素，修饰符方法（通常称为BEM）是HTML和CSS中类的流行命名约定。由Yandex团队开发，其目标是帮助开发人员更好地理解给定项目中HTML和CSS之间的关系。(摘自: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: 快速了解

了解BEM等命名和组织系统以及使用它们的原因非常重要。在这里做一些研究，但如果您是初学者，我不建议花太多时间在这个主题上。

### :book: 学习要点和想法

- 了解 [BEM 介绍](http://getbem.com/introduction/)
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- 使用BEM约定创建一个简单的网页。

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp是一个工具包，用于在开发工作流程中自动执行痛苦或耗时的任务，因此您可以停止杂乱的开发并构建一些东西。(摘自: [gulpjs.com](https://gulpjs.com/))

### :bulb: 快速了解

在现代前端开发中，您经常会发现自己需要自动执行捆绑，移动文件和将引用注入HTML文件等任务。 Gulp是一款可以帮助您完成这些工作的工具！

### :book: 学习要点和想法

- 用npm安装gulp
- 关于CSS-Tricks的[gulp for beginners tutorial](https://css-tricks.com/gulp-for-beginners/)
- 在您的网站上，设置gulp为：
   - 为你编译Sass
   - 将生成的CSS文件放在`build`子目录中
   - 将您的网页移动到构建目录
   - 将生成的CSS文件的引用注入到您的网页中

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

webpack的核心是现代JavaScript应用程序的静态模块捆绑器。当webpack处理您的应用程序时，它会在内部构建一个依赖关系图，它映射您的项目所需的每个模块并生成一个或多个包。 (摘自: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: 快速了解

想象一下，您有一个大型的Web开发项目，其中有许多不同的开发人员正在处理许多不同的任务。您可能希望尽可能地模块化它们，而不是所有工作在相同的文件中。 Webpack通过让您的团队以模块化方式工作来帮助实现这一目标，然后花点时间构建应用程序，Webpack将它们粘在一起：HTML，CSS / Sass，JavasScript，图像等.Webpack不是唯一的模块捆绑器，但它目前似乎是领跑者。

### :book: 学习要点和想法

- 阅读 [webpack 核心概念](https://webpack.js.org/concepts/)
- [webpack是什么，它是怎么工作的? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [webpack 教程](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint是一个开源JavaScript linting实用程序，最初由Nicholas C. Zakas于2013年6月创建。代码linting是一种静态分析，经常用于查找不符合某些样式指南的有问题的模式或代码。大多数编程语言都有代码链接，编译器有时会在编译过程中加入linting。 (摘自: [eslint.org](https://eslint.org/docs/about/))

### :bulb: 快速了解

Linting是代码质量，可读性和一致性的绝佳工具。使用linter将帮助您在进入生产之前捕获语法和格式错误。您可以手动运行linters或将其包含在构建/部署过程中。

### :book: 学习要点和想法

- 使用npm安装eslint
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- 检查您的代码

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React（也称为React.js或ReactJS）是用于构建用户界面的JavaScript库。它由Facebook和个人开发者和公司的社区维护。 React可以用作开发单页或移动应用程序的基础。 复杂的React应用程序通常需要使用其他库来进行状态管理，路由以及与API的交互。 (摘自: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: 快速了解

前端JavaScript框架处于现代前端开发的最前沿。这里的一个重要内容是React尽管非常受欢迎，但它只是一个用于构建用户界面的库，而像Vue和Angular这样的框架旨在提供更全面的功能。例如，如果你在React中构建一个需要路由到不同视图的应用程序，你需要引入类似`react-router`的东西。

### :book: 学习要点和想法

- 参考[React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [跟着Mosh学习react](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- 将您的网站重构为React应用程序！
- 注意：`create-react-app`是一个支持新React项目的便捷工具。

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux是JavaScript应用程序的可预测状态容器。它可以帮助您编写行为一致的应用程序，在不同的环境（客户端，服务器和本机）中运行，并且易于测试。最重要的是，它提供了出色的开发人员体验，例如实时代码编辑与时间旅行调试器相结合。 (摘自: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: 快速了解

随着您构建越来越大的前端应用程序，您开始意识到维护应用程序状态很难：例如用户是否登录，用户是谁，以及应用程序中正在发生的事情。 Redux是一个很棒的库，可以帮助您维护应用程序可以基于其逻辑的单一状态源。

### :book: 学习要点和想法

- [Redux视频教程](https://www.youtube.com/watch?v=93p3LxR9xfM)
- Redux的创建者Dan Abramov的[Redux视频系列](https://egghead.io/courses/getting-started-with-redux)
- 注意[Redux三原则](https://redux.js.org/introduction/three-principles)
   - 单一的事实来源
   - 状态是只读的
   - 使用纯函数进行更改
- 将Redux状态管理添加到您的应用程序
  
<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest是一个令人愉快的JavaScript测试框架，专注于简单性。它适用于以下项目：Babel，TypeScript，Node，React，Angular，Vue等等！ (摘自: [jestjs.io](https://jestjs.io))

### :bulb: 快速了解

为前端项目设置自动化测试非常重要。设置自动化测试将使您可以放心地进行未来的更改 - 如果您进行了更改并且测试仍然通过，那么您可以相当自在地放弃任何现有功能。要列出的测试框架太多了; Jest只是我最喜欢的一个。

### :book: 学习要点和想法

- 学习 [Jest 基础](https://jestjs.io/docs/en/getting-started)
- 如果你用 `create-react-app`, [Jest 已经被集成了](https://facebook.github.io/create-react-app/docs/running-tests).
- 给你的应用增加测试

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* 可选择的相似的库: Flow

TypeScript是Microsoft开发和维护的一种开源编程语言。它是JavaScript的严格语法超集，并为该语言添加了可选的静态类型。 TypeScript旨在开发大型应用程序并转换为JavaScript。由于TypeScript是JavaScript的超集，现有的JavaScript程序也是有效的TypeScript程序。 TypeScript可用于为客户端和服务器端（Node.js）执行开发JavaScript应用程序。(摘自: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: 快速了解

JavaScript是动态类型的。然而，人们普遍认为静态类型（即，提前指定变量类型，类，接口）更清晰并且降低了缺陷/错误的可能性。无论您对该主题的看法如何，至少要了解像TypeScript这样的静态类型的JavaScript。请注意，TypeScript可编译为JavaScript，因此浏览器可以解释它（即浏览器本身不会解释TypeScript）。

### :book: 学习要点和想法

- [5分钟内学习TypeScript](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [50分钟内学习TypeScript (视频)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- 可选的 [通过TypeScript来编写一个React应用](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js是服务器呈现的React应用程序的简约框架。(摘自: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: 快速了解

现在我们正在进步！到目前为止，您已经构建了一个React（或Vue或Angular）应用程序，它在浏览器中完成了相当多的工作。由于各种原因（例如，SEO，对客户端性能的担忧），您可能实际上希望您的前端应用程序在服务端渲染，而不是在客户端。这就是像next.js这样的框架进来的地方。

### :book: 学习要点和想法

- Next.js [开始学习](https://nextjs.org/learn/)
- [Next.js速成课程 (视频)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- 创建Next.js应用程序或将现有应用程序迁移到Next.js

# 其它说明？

这个列表可以让你广泛接触前端生态系统，但是根本不可能覆盖到每一个主题，更不用说每个领域内的无数工具了！如果您认为我遗漏了一些非常重要的内容，请参阅[贡献]（＃contributions）部分，了解如何帮助您更好地完善本指南。

# 项目创意

当您进入＃100DaysOfCode时，您想要一个或多个项目能够运用您学习到的新知识。在本节中，我将尝试提供一些您可以使用的项目创意。或者，我们鼓励您提出自己的项目想法，因为这些想法可能会引起您的兴趣和激励。

- 初学者的想法：
   - 建立投资组合网站
- 中级/高级创意：
   - 构建推文分析应用程序（如果您已经知道后端和API集成）

# 需要帮助？

通常，我发现以下资源对学习软件开发非常宝贵：
- 谷歌搜索问题
- [StackOverflow](http://www.stackoverflow.com)（很有可能你的问题已被提出，并且在谷歌搜索时将是一个高级别的结果）。
- [Mozilla MDN Web Docs](https://developer.mozilla.org/en-US/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- 本地软件开发Meetups！大多数人对所有经验水平都非常友好。

如果你喜欢我对任何事情的意见，请随时[在Twitter上与我联系]（http://www.twitter.com/nas5w），我会尽力提供一些帮助。如果您认为课程有问题或有建议，请参阅下面的[贡献部分]（＃contributions）。

# 贡献

## 项目传播

如果您喜欢这个项目，您可以通过传播有关这个仓库的信息来做出重大贡献，包括：

- Starring和forking此仓库
- 在社交媒体上共享这个仓库

## 贡献

这是一项正在进行中的工作，我非常感谢您在维护此知识库方面的任何帮助！

在您为这个仓库做贡献时，请先在issue提出您需要贡献的主题。否则，我将很难理解您的提案，并可能导致您为不会合并的更改投入大量工作。

请注意，参与此项目的每个人都在尝试学习或尝试提供帮助 - 请保持友善！

## PR提交流程

1. 建立一个issue，描述您需要提的pr的目的
2. 获得项目所有者的批准以进行建议的更改。
3. 提一个pr