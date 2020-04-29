# Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome visual regression testing resources.

Regression testing is a type of software testing which verifies that software which was previously developed and tested still performs the same way after it was changed or interfaced with other software. The purpose of regression testing is to ensure that changes to the software have not introduced new faults.

## Foreword

This is intended to be an *incomplete* list of resources about visual regression testing. It is not tailored to a specific area or role (Developer/QA/UX-Designer). Note that this is for all areas of regression software testing *after* the code in question is written. For a awesome list on general software testing see e.g. [awesome-testing](https://github.com/TheJambo/awesome-testing).

Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](.github/CONTRIBUTING.md) page and **Feel free to add to the list!!**. If you think this is helpful **Please give a Star ★**.

## Contents

- [General information](#general-information)
- [Browser automation](#browser-automation)
- [Tools and frameworks](#tools-and-frameworks)
- [Online services](#online-services)
- [Blog posts](#blog-posts)
- [Slideshows, talks and videos](#slideshows-talks-and-videos)
- [Deprecated](#deprecated)
- [Miscellaneous](#Miscellaneous)
  - [Contributing](#contributing)
  - [Code of Conduct](#code-of-conduct)
  - [License](#license)

## General information

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
- [visualregressiontesting.com](https://visualregressiontesting.com/) - Basic collection of links.

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) - Browser automation framework and ecosystem.
- [SlimerJS](https://github.com/laurentj/slimerjs) - Scriptable browser like PhantomJS, based on Firefox.
- [trifleJS](https://github.com/sdesalas/trifleJS) - Headless automation for Internet Explorer.
- [CasperJS](https://github.com/casperjs/casperjs) - Navigation scripting and testing utility for PhantomJS and SlimerJS.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) - Node.js bindings implementation for the W3C WebDriver protocol.
- [Navalia](https://github.com/joelgriffith/navalia) - Browser Automation based on headless Chrome and GraphQL.
- [Chromeless](https://github.com/graphcool/chromeless) - Chrome automation made simple. Runs locally or headless on AWS Lambda.
- [Cypress.io](https://www.cypress.io/) - An automation framework that runs in-browser.

## Tools and frameworks

- [basset](https://basset.io) - Open source platform for generating and reviewing visual differences. Supports multiple browsers, integrations for github and slack.
- [AyeSpy](https://github.com/newsuk/ayespy) - 44 image comparisons in 90 seconds.
- [Wraith](https://github.com/BBC-News/wraith) - Easy to use ruby tool with docker support.
- [BackstopJS](https://github.com/garris/BackstopJS) - Config-driven automated screenshot test framework.
- [Galen](https://github.com/galenframework/galen) - Java framework based on [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) - Feature rich framework with support for [Selenium](https://github.com/SeleniumHQ/selenium) and  [CasperJS](https://github.com/casperjs/casperjs).
- [Huxley](https://github.com/facebookarchive/huxley) - Python framework based on [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) - Experimental approach to UI testing, based on Decision Trees.
- [CSSCritic](https://github.com/cburgmer/csscritic) - Lightweight CSS regression testing.
- [Spectre](https://github.com/wearefriday/spectre) - Provides image comparison capabilities and an admin interface for managing screenshots.
- [Shoov](https://github.com/shoov/shoov) - UI regression and functional testing focused on Drupal 7 sites.
- [qd_screenshottests](https://www.drupal.org/project/qd_screenshottests) - CasperJS-based UI regression and functional testing focused on Drupal 8 sites.
- [OcularJS](https://github.com/mmacartney10/ocularjs) - uses [PhantomJS](https://github.com/ariya/phantomjs).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - WebdriverCSS sits on top of [Webdriver.io](https://github.com/webdriverio/webdriverio/) and hooks into [Selenium](https://github.com/SeleniumHQ/selenium).
- [Look-alike](https://github.com/kdzwinel/Look-alike) - Chrome Extension for taking and comparing screenshots.
- [Hardy](https://github.com/thingsinjars/Hardy) - Selenium-driven, cucumber-powered CSS testing.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
- [Needle](https://github.com/python-needle/needle) - Needle is a tool for testing visuals with Selenium and nose (Python).
- [gatling](https://github.com/gabrielrotbart/gatling) - Integrated visual RSpec matcher which makes real visual testing easy (Ruby).
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) - Plugin to prevent your project of broken layout via screenshot photo sessions of your site.
- [vrtest](https://github.com/nathanmarks/vrtest) - JavaScript library for running visual regression tests on your components cross browser via selenium.
- [Happo](https://github.com/Galooshi/happo) - Visual diffing in CI for user interfaces.
- [reg-cli](https://github.com/bokuweb/reg-cli) - Visual regression test tool which output easy-to-read single file html report.
- [Nightmare](https://github.com/segmentio/nightmare) - High-level browser automation library based on Electron.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Google Chrome Node API.
- [Playwright](https://github.com/microsoft/playwright) - Node library to automate Chromium, Firefox and WebKit with a single API.
- [Visual Review](https://github.com/xebia/VisualReview) - A human-friendly tool for testing and reviewing visual regressions.
- [reg-suit](https://github.com/reg-viz/reg-suit) - Visual regression testing suite which compares images, stores snapshots, and notifies the difference to your GitHub repo.
- [Chimp](https://github.com/xolvio/chimp) - Develop acceptance tests & end-to-end tests with realtime feedback.
- [Differencify](https://github.com/NimaSoroush/differencify) - A library for visual regression testing using [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ResembleJS](https://github.com/Huddle/Resemble.js) - Analyse and compare images with Javascript and HTML5.
- [Muppeteer](https://github.com/HuddleEng/Muppeteer) - Visual regression testing framework for Chrome using [Mocha](https://mochajs.org/) and [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ember-visual-test](https://github.com/Cropster/ember-visual-test) - Simple visual regression testing for [Ember](https://emberjs.com/).
- [AET](https://github.com/Cognifide/aet) - Scalable testing tool providing visual regression testing, accessibility and performance validation, markup analysis and more.
- [Wendigo](https://github.com/angrykoala/wendigo) - Test-oriented browser automation library based on Puppeteer.
- [Loki](https://github.com/oblador/loki) - Visual regression testing for Storybook using Chrome in docker et al.
- [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing using Node.js.
- [CodeceptJS](https://github.com/codeception/codeceptjs/) - Modern Era Acceptance Testing Framework for NodeJS.
- [FuncUnit](https://github.com/bitovi/funcunit) - A functional test suite based on jQuery
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated testing and continuous integration framework based on Node.js and using the Webdriver protocol.
- [Protractor](https://github.com/angular/protractor) - E2E test framework for Angular apps.
- [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) - Visual regression testing with Jest and puppeteer for React components
- [test-crawler](https://github.com/apiel/test-crawler) - Visual regression testing, by crawling a website and providing snapshot comparison reports.
- [wdio-visual-regression](https://github.com/ennjin/wdio-visual-regression) - Visual regression tool for webdriver.io

## Online services

- [BrowserStack](https://www.browserstack.com) - Free for Open Source. Supports [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [LambdaTest](https://www.lambdatest.com/) - Perform Automated and Live Interactive Cross Browser Testing on 2000+ Real Browsers and Operating Systems Online.
- [screener.io](https://screener.io) - For React, looks open source.
- [applitools](https://applitools.com) - Cloud base visual tests.
- [percy.io](https://percy.io) - Continuous visual reviews for web apps.
- [screenster.io](http://screenster.io) - Cloud based automation testing platform for web and mobile UI.
- [browserling](https://www.browserling.com) - LIVE interactive cross-browser testing.
- [Browser Shots](http://browsershots.org) - Screenshots only.
- [Ghost Inspector](https://ghostinspector.com) - See [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com) - Manual & exploratory testing on 1500+ real browsers and mobile devices.
- [Argos-CI](https://www.argos-ci.com) - Automate visual regression testing.
- [Diffy](https://diffy.website) - Cloud based visual regression tool. Uses puppeteer and proprietary comparison algorithm (detect layout shifts). Great scalability with AWS Lambda.
- [Chromatic](https://www.chromaticqa.com) - Visual testing and UI review for component libraries. Cloud-based. [Video](https://youtu.be/6KDLJBcutQE)
- [VisWiz.io](https://www.viswiz.io) - Flexible visual regression testing service.
- [Happo](https://happo.io/) - Cloud-based screenshot testing service with support for multiple browsers.
- [Visual Knight](https://visual-knight.io/) - Cloud-based visual testing platform with realtime results for testing tools.
- [Axcept](https://axcept.io) - Testing for the whole team. Up to 100 tests in parallel. Endpoint Mocking. Code Coverage. 
- [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons and regressions.
- [Vidiff](https://vidiff.com) - Cloud-based visual regression testing across stages.
- [Reflect](https://reflect.run) - Visual regression testing and test automation tool.

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - Compares: Wraith, PhantomCSS, Gemini, WebdriverCSS and Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -  Tutorial using BackstopJS.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - Tutorial using BackstopJS.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - Tutorial using BackstopJS.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - Why you should use BackstopJS.
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) - Introduction to PhantomCSS.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome is shaking up traditional approaches to test automation.
- [Visual regression testing using Jest, Chromeless and AWS Lambda](https://novemberfive.co/blog/visual-regression-testing-jest-chromeless-lambda) - Tutorial using Chromeless and jest-image-snapshot.
- [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - Introduction to [Differencify](https://github.com/NimaSoroush/differencify) and how to use it.
- [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - Tutorial to setup visual testing with Puppeteer, Jest and VisWiz.io.
- [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - Using percy, and jest puppeteer to visually test a React component library.
- [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - Tutorial using WebdriverIO and WebdriverCSS with Spec Reporter
- [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
- [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)

## Slideshows, talks and videos

- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - Screencast: Basic introduction to wraith, a screenshot comparison tool.
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - How to setup shoov and get your first test written.
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) - Talk by Jon Bellah on how to use PhantomCSS during wordpress development.
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - Screencast with code demo and best practices.
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - Tutorial on how to create visual automated tests with Screenster.
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - Demo what the Look-alike Chrome extension is, how it works and how and why it was build.
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - How to write your first CSS test with CSS critic, make it pass, break it, and make it pass again.
- [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) by Nikhil Verma - How the Mobile Web team in Badoo converted and integrated PhantomCSS into their workflow and connected it to their CI process.

## Deprecated

The following projects are no longer maintained actively but are still worth mentioning because of their user base.

- [PhantomJS](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit. No longer maintained since 2 June 2018.
- [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS or SlimerJS. No longer maintained since 22 Dec 2017.
- [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser testing with JavaScript. No longer maintained since 4 Jun 2017.
- [dpxdt](https://github.com/bslatkin/dpxdt) - End-to-end testing with Python.

## Miscellaneous

### Contributing

See the [Contribution Guide](.github/CONTRIBUTING.md) for details on how to contribute.

### Code of Conduct

See the [Code of Conduct](.github/CODE-OF-CONDUCT.md) for details. Basically it comes down to:
> In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and orientation.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
License holders are [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
