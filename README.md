# Awesome (Visual) Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list around the topic: visual regression testing

## Foreword
This is intended to be an *incomplete* list of resources about visual regression testing. It is not tailored to a specific area or role (Developer/QA/UX-Designer). Note that this is for all areas of regression software testing *after* the code in question is written. For a awesome list on general software testing see e.g. [awsome-testing](https://github.com/TheJambo/awesome-testing).

Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md) page and **Feel free to add to the list!!**. If you think this is helpfull **Please give a Star ★**.


## Contents

* [General information on regression testing](#general-information-on-regression-testing)
* [Browser automation](#browser-automation)
* [Tools and frameworks](#tools-and-frameworks)
* [Online services](#online-services)
* [Blog posts](#blog-posts)
* [Slideshows, Talks and Videos](#slideshows-talks-and-videos)
* [Misc](#Misc)
  * [Contributing](#contributing)
  * [Code of Conduct](#code-of-conduct)
  * [License](#license)

## General information on regression testing

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
- [visualregressiontesting.com](https://visualregressiontesting.com/) - Basic collection of links.

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) - A browser automation framework and ecosystem.
- [PhantomJS](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
- [SlimerJS](https://github.com/laurentj/slimerjs) - A scriptable browser like PhantomJS, based on Firefox.
- [trifleJS](https://github.com/sdesalas/trifleJS) - Headless automation for Internet Explorer.
- [CasperJS](https://github.com/casperjs/casperjs) - Navigation scripting and testing utility for PhantomJS and SlimerJS.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) - A Node.js bindings implementation for the W3C WebDriver protocol.
- [Navalia](https://github.com/joelgriffith/navalia) - Browser Automation based on headless Chrome and GraphQL.
- [Chromeless](https://github.com/graphcool/chromeless) - Chrome automation made simple. Runs locally or headless on AWS Lambda.

## Tools and frameworks

- [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with [PhantomJS](https://github.com/ariya/phantomjs) or [SlimerJS](https://github.com/laurentj/slimerjs).
- [Wraith](https://github.com/BBC-News/wraith) - Easy to use ruby tool with docker support.
- [BackstopJS](https://github.com/garris/BackstopJS) - Config-driven automated screenshot test framework.
- [Galen](https://github.com/galenframework/galen) - Java framework based on [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) - Feature rich framework with support for [Selenium](https://github.com/SeleniumHQ/selenium) and  [CasperJS](https://github.com/casperjs/casperjs).
- [Huxlay](https://github.com/facebookarchive/huxley) - Python framework based on [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) - An experimental approach to UI testing, based on Decision Trees.
- [CSSCritic](https://github.com/cburgmer/csscritic) - Lightweight CSS regression testing.
- [Spectre](https://github.com/wearefriday/spectre) - Provides image comparison capabilities and an admin interface for managing screenshots.
- [Shoov](https://github.com/shoov/shoov) - UI regression and functional testing focused on Drupal 7 sites.
- [OcularJS](https://github.com/mmacartney10/ocularjs) - uses [PhantomJS](https://github.com/ariya/phantomjs).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - WebdriverCSS sits on top of [Webdriver.io](https://github.com/webdriverio/webdriverio/) and hooks into [Selenium](https://github.com/SeleniumHQ/selenium).
- [Look-alike](https://github.com/kdzwinel/Look-alike) - Chrome Extension for taking and comparing scrennshots.
- [Hardy](https://github.com/thingsinjars/Hardy) - Selenium-driven, cucumber-powered CSS testing.
- ~~[DalekJS](https://github.com/dalekjs/dalek)~~ - Not maintained any longer.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
- [Needle](https://github.com/python-needle/needle) - Needle is a tool for testing visuals with Selenium and nose (Python).
- [dpxdt [Depicted]](https://github.com/bslatkin/dpxdt) - End-to-end testing with Python.
- [gatling](https://github.com/gabrielrotbart/gatling) - An integrated visual RSpec matcher which makes real visual testing easy (Ruby).
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) - Plugin to prevent your project of broken layout via screenshot photo sessions of your site.
- [vrtest](https://github.com/nathanmarks/vrtest) - A JavaScript library for running visual regression tests on your components cross browser via selenium.
- [Happo](https://github.com/Galooshi/happo) - Visual diffing in CI for user interfaces.
- [reg-cli](https://github.com/bokuweb/reg-cli) - Visual regression test tool which output easy-to-read single file html repot.
- [Nightmare](https://github.com/segmentio/nightmare) - High-level browser automation library based on Electron.

## Online services

- [BrowserStack](https://www.browserstack.com/) - Free for Open Source. Supports [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [screener.io](https://screener.io/) - For React, looks open source.
- [applitools](https://applitools.com)
- [percy.io](https://percy.io/) - Continuous visual reviews for web apps.
- [screenster.io](http://screenster.io/)
- [siteeffect.io](http://siteeffect.io/)
- [MogoTest](http://mogotest.com)
- [bugsnag](https://www.bugsnag.com)
- [screenbeacon.com](https://www.screenbeacon.com/) - Real time monitoring for visual regressions.
- [browserling](https://www.browserling.com/)
- [Browser Shots](http://browsershots.org/) - Screenshots only.
- [Ghost Inspector](https://ghostinspector.com/) - See [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com/) - Manual & exploratory testing on 1500+ real browsers and mobile devices.
- [Argos-CI](https://www.argos-ci.com/) - Automate visual regression testing.

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - Compares: Wraith, PhantomCSS, Gemini, WebdriverCSS and Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -  Tutorial using BackstopJS.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - Tutorial using BackstopJS.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - Tutorial using BackstopJS.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031)
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss/)
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome is shaking up traditional approaches to test automation.

## Slideshows, Talks and Videos
- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0)
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc)
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw)
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4)
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI)
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8)
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60)

## Misc

### Contributing
See the [Awesome Regression Testing Contribution Guide](CONTRIBUTING.md) for details on how to contribute.

### Code of Conduct
See the [Code of Conduct](CODE-OF-CONDUCT.md) for details. Basically it comes down to:
> In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and orientation.

### License
[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
License holders are [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
