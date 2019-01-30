# Front-End Development Curriculum for #100DaysOfCode

This is a somewhat opinionated curriculum for learning front-end development during #100DaysOfCode. As it covers a wide range of front-end develpoment topics, it can be thought of as more of a "survey" style course rather than a deep dive into any one area. Ideally, your takeaway from completing this curriculum will be some familiarity with each topic and the ability to easily dive deeper in any area in the future when necessary.

This curriculum was influenced significantly by Kamran Ahmed's excellent [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c) roadmap. Please check it out--it is excellent.

**Note**: I know front-end development means a lot of different things to a lot of people! If you're a front-end developer and you think this guide could be improved, please let me know by raising an issue as described in the [Contributing](#contibuting) section. Thank you!

# :calendar: Curriculum

* Days 1-8: HTML
* Days 9-16: CSS
* Days 17-24: JavaScript Basics
* Days 25-27: jQuery
* Days 28-33: Responsive Web Design
* Days 34-36: Accessibility
* Days 37-39: Git
* Days 40-44: Node and NPM
* Days 45-50: Sass
* Days 51-54: Bootstrap
* Day 55: BEM
* Days 57-61: Gulp
* Days 62-65: Webpack
* Day 66: ESLint
* Days 68-83: React*
* Days 84-89: Redux*
* Days 90-94: Jest*
* Days 95-97: TypeScript
* Days 98-100: NextJS*

# :mag_right: The Details

Below you can find a little information about each topic in the curriculum as well as some ideas/guidance on what to do for each.

## HTML

### :book: Definition

Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications. With Cascading Style Sheets (CSS) and JavaScript, it forms a triad of cornerstone technologies for the World Wide Web. Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document. (Source: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Quick Takeaway

HTML is really the foundation of web development. Even in the javascript-based frameworks, you end up writing HTML in one form or another.

### :star: Learning Areas and Ideas

## CSS

### :book: Definition

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Quick Takeaway

CSS is another essential component of web development. While it is mainly used to style and position HTML elements, it has become increasingly capable of more dynamic tasks (e.g., animations) that would once be handled by javascript.

### :star: Learning Areas and Ideas

## JavaScript Basics

### :book: Definition

JavaScript , often abbreviated as JS, is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is a language that is also characterized as dynamic, weakly typed, prototype-based and multi-paradigm. Alongside HTML and CSS, JavaScript is one of the three core technologies of the World Wide Web. JavaScript enables interactive web pages and thus is an essential part of web applications. The vast majority of websites use it, and all major web browsers have a dedicated JavaScript engine to execute it. (Source: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Quick Takeaway

JavaScript has become increasingly important in the front-end world. While it was once used mainly to make pages dynamic, it is now the foundation of many front-end frameworks. These frameworks handle a lot of the tasks that were formerly handled by the back-end (e.g., routing and displaying different views).

### :star: Learning Areas and Ideas

## jQuery

### :book: Definition

jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript. (Source: [jQuery.com](https://jquery.com/))

### :bulb: Quick Takeaway

After you have spent some time with plain (also called "vanilla") javascript, you may find some tasks a bit cumbersome, especially those related to accessing and manipulating HTML elements. For quite a while, jQuery was the go-to library for making these kinds of tasks easier and consistent across different browsers. Nowadays, jQuery isn't necessarily "mandatory" learning because of advancements in vanilla javascript, CSS, and newer javascript frameworks (we'll look at frameworks later). Still, it would be beneficial to take a little time to learn some jQuery and apply it to a small project.

### :star: Learning Areas and Ideas

## Responsive Web Design

### :book: Definition

Responsive web design (RWD) is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes. Recent work also considers the viewer proximity as part of the viewing context as an extension for RWD. Content, design and performance are necessary across all devices to ensure usability and satisfaction. A site designed with RWD adapts the layout to the viewing environment by using fluid, proportion-based grids, flexible images, and CSS3 media queries, an extension of the @media rule. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Quick Takeaway

Responsive web design is all about making web applications look and function properly on all types of advice. A quick-and-dirty example would be that a website should look and function properly both in a desktop web browser and on a mobile phone browser. An understanding of responsive design is crucial for any front-end developer!

### :star: Learning Areas and Ideas

## Accessibility

### :book: Definition

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with disabilities. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Quick Takeaway

Accessibility, often written as a11y, is one of the most important topics in front-end web development, yet it seems to often get short shrift. Creating accessible web applications is not only ethically sound, but also makes a lot of business sense considering the additional audience that will be able to view your applications when they are accessible.

### :star: Learning Areas and Ideas

## Git

### :book: Definition

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. (Source: [git-scm.com](https://git-scm.com/))

### :bulb: Quick Takeaway

Version/code control is an essential part of any web developer's toolkit. There are a number of different version control systems, but Git is by far the most prevalent at the moment. You can (and should!) use it to track your projects as you learn!

### :star: Learning Areas and Ideas

## Node and NPM

### :book: Definition

Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. JavaScript is used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML and run client-side by a JavaScript engine in the user's web browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web application development around a single programming language, rather than different languages for server side and client side scripts. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Quick Takeaway

While nodejs is typically known as a back-end solution, it is used quite frequently to support front-end development. It does this in a number of ways, including things like running build tools, testing, and linting (all to be covered soon!). Node Package Manager (npm) is another great feature of node and can be used to manage dependencies of your project (i.e., code libraries your project might rely on -- jQuery is an example!). 

### :star: Learning Areas and Ideas

## Sass

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## Bootstrap

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## BEM

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## Gulp

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## Webpack

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## ESLint

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## React*

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## Redux*

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## Jest*

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## TypeScript

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

## NextJS*

### :book: Definition

### :bulb: Quick Takeaway

### :star: Learning Areas and Ideas

# Contibuting

This is a work in progress and I very much appreciate any help in maintaining this knowledge base! 

When contributing to this repository, please first discuss the change you wish to make via issue before making a change. Otherwise, it will be very hard to understand your proposal and could potentially result in you putting in a lot of work to a change that won't get merged.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

1. Create an issue outlining the proposed pull request.
2. Obtain approval from a project owner to make the proposed change.
3. Create the pull request.
