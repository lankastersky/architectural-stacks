![Frontend developer skills](https://www.amarinfotech.com/wp-content/uploads/2017/03/which-skill-requires-for-developer.jpg)

# Guidelines

# Testing frameworks
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

## Testing stacks
- [Automated testing with Headless Chrome](https://developers.google.com/web/updates/2017/06/headless-karma-mocha-chai) - Headless Chrome, karma, mocha, chai

# Package managers
- [Npm](https://www.npmjs.com) - Node Package Manager
- [Yarn](https://yarnpkg.com) - is a superset of NPM that stores the exact versions of dependencies, installs packages in parallel

# Version managers
- [Nvm](https://github.com/creationix/nvm) - a Bash script
- [n](https://github.com/tj/n) - Node module, which can be installed by npm

# Transpilers
Source-to-source compilers, are tools that read source code written in one programming language, and produce the equivalent code in another language
- [Babel](https://babeljs.io) - converts new JS code into old ones

# Bundlers
Module Bundling, on a high level, is a process of integrating together a group of modules in a single file so that multiple modules can be sent to the browser in a single bundle (which is good for performance but bad for debugging).
- [Webpack](https://webpack.js.org) - a modular build tool 
- [Parcel](https://parceljs.org/) - gives you “blazing fast” bundling as it uses multiple worker processes to ensure that the compilation process is executed in parallel on multiple cores without the need of any configuration

# Development frameworks
- Angular
- ReactJS
- Vuejs

# IDEs
- [Visual Studio Code](https://code.visualstudio.com/) - open sourced IDE supporting many languages. Built on top of Webkit

# Other
- Redux https://redux.js.org/
- MobX https://github.com/mobxjs/mobx 
- Flux https://facebook.github.io/flux/ 

- Vuex
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
