# TOC
- [Books](#books)
- [Build tools (Bundlers)](#build-tools-bundlers)
- [Development frameworks](#development-frameworks)
- [Guidelines](#guidelines)
- [IDEs](#ides)
- [Libraries](#libraries)
  - [State managers](#state-managers)
  - [Testing frameworks](#testing-frameworks)
    - [Testing stacks](#testing-stacks)
  - [Transpilers](#transpilers)
- [Package managers](#package-managers)
- [Roadmaps](#roadmaps)
- [Terminology](#terminology)
  - [JavaScript](#javascript)
- [Version managers](#version-managers)


# Roadmaps
- [ManzDev/roadmap-web-developer-2017](https://github.com/ManzDev/roadmap-web-developer-2017) - good collection of detailed roadmaps

- [Frontend technologies, 2017](https://codeforgeek.com/2017/04/become-valuable-full-stack-developer/)
![Frontend technologies](https://i0.wp.com/codeforgeek.com/wp-content/uploads/2017/04/front-end-path.png?resize=768%2C980&ssl=1)

- [State of the JavaScript ecosystem, 2017](https://www.linux.com/blog/learn/2017/7/modern-day-front-end-development-stack)
![State of the JavaScript ecosystem in 2017](https://lh5.googleusercontent.com/WalI-kmOa2_4e2FyLH1K4eIIhoL1heXSS-vHC1nBR7hkuPsb4Dq-qu1WBh2qOJOFxMnaZ8Y1sU6D_PdClmyNeCt-U4hDpAYB5ld8ik8xBGLvMtZ1ntp9qvYErmK0PnPSk5GQO4du)

- Frontend developer skills
![Frontend developer skills](https://www.amarinfotech.com/wp-content/uploads/2017/03/which-skill-requires-for-developer.jpg)

# Books
- [Effective JavaScript by by David Herman, 2012](https://www.amazon.com/Effective-JavaScript-Specific-Software-Development/dp/0321812182)
- [Eloquent JavaScript by Marijn Haverbeke](http://eloquentjavascript.net/) - free
- [JavaScript: The Definitive Guide by David Flanagan, 2011](https://books.google.com/books?id=4RChxt67lvwC&lpg=PR1&dq=javascript%20the%20definitive%20guide&pg=PR1#v=onepage&q&f=false)
- [JavaScript: The Good Parts by Douglas Crockford, 2008](https://books.google.com/books?id=PXa2bby0oQ0C&lpg=PP1&dq=JavaScript%3A%20The%20Good%20Parts&pg=PP1#v=onepage&q&f=false)
- [The Complete JavaScript Reference by Powell, Thomas, Schneider, Fritz (2004)](https://www.amazon.com/JavaScript-Complete-Reference-Schneider-Paperback/dp/B011DBLJP4)

# Guidelines
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)


# Package managers
- [Npm](https://www.npmjs.com) - Node Package Manager
- [Yarn](https://yarnpkg.com) - is a superset of NPM that stores the exact versions of dependencies, installs packages in parallel

# Version managers
- [Nvm](https://github.com/creationix/nvm) - a Bash script
- [n](https://github.com/tj/n) - Node module, which can be installed by npm

# Build Tools (Bundlers)
Module Bundling, on a high level, is a process of integrating together a group of modules in a single file so that multiple modules can be sent to the browser in a single bundle (which is good for performance but bad for debugging).
- [Webpack](https://webpack.js.org) - a modular build tool 
- [Parcel](https://parceljs.org/) - gives you “blazing fast” bundling as it uses multiple worker processes to ensure that the compilation process is executed in parallel on multiple cores without the need of any configuration

# Development frameworks
- Angular
- ReactJS
- Vuejs

# IDEs
- [Visual Studio Code](https://code.visualstudio.com/) - open sourced IDE supporting many languages. Built on top of Webkit
- [Sublime Text](https://www.sublimetext.com/) - A sophisticated text editor for code, markup and prose

# Libraries

## State managers
- [Flux](https://facebook.github.io/flux/) - application architecture that Facebook uses for building client-side web applications. It complements React's composable view components by utilizing a unidirectional data flow
- [Redux](https://redux.js.org/) - A predictable state container for JavaScript apps
- [MobX](https://github.com/mobxjs/mobx) - Simple, scalable state management
- [Vuex](https://vuex.vuejs.org/) - state management pattern + library for Vue.js applications

## Testing frameworks
- Karma - a browser test runner
- Jasmine  - “batteries included” BDD test framework
- Mocha - not a “complete” test framework, covers the basics and allows developers to extend it with other frameworks
- Chai is one of the most popular open-source assertion libraries used with Mocha
- Sinon - a popular mocking and spy library
- [Jest](https://jestjs.io/) - test framework, comes with built-in mocking and assertion abilities, runs your tests concurrently in parallel, providing a smoother, faster test run
- [PhantomJS](http://phantomjs.org/)  - headless Web Kit used for automating web page interaction. 2018: ABANDONED
- [Selenium](https://www.seleniumhq.org/) - open source web-based automation tool for web applications across different browsers and platforms
  - [Selenium WebDriver](https://www.seleniumhq.org/projects/webdriver/) - enables you to use a programming language in creating your test scripts (not possible in Selenium IDE)
- [Headless chrome](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md) - headless Chromium browser, a great tool for automated testing and server environments where you don't need a visible UI shell

### Testing stacks
- [Automated testing with Headless Chrome](https://developers.google.com/web/updates/2017/06/headless-karma-mocha-chai) - Headless Chrome, karma, mocha, chai

## Transpilers
Source-to-source compilers, are tools that read source code written in one programming language, and produce the equivalent code in another language
- [Babel](https://babeljs.io) - converts new JS code into old ones

## Other
- Flexbox
- Scss
- Stylus
- graphql

# Terminology
- Tree shaking - in javascript context, refers to dead code elimination

## JavaScript
- [Closure](https://gist.github.com/AllThingsSmitty/9a5463870d12c62fc33b#3-closure) - inner function, that's accessible outside of its outer function's scope, with its connection to the outer function's variables still intact.
- [Curring](https://gist.github.com/AllThingsSmitty/9a5463870d12c62fc33b#4-currying) - using multiple functions with single arguments, in place of a single function with multiple arguments
- [Hoisting](https://gist.github.com/AllThingsSmitty/9a5463870d12c62fc33b#5-hoisting) - default behavior of moving declarations to the top
- [Mutation](https://gist.github.com/AllThingsSmitty/9a5463870d12c62fc33b#5-hoisting) - referring to the changes that DOM elements went through
