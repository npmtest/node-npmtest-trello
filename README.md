# npmtest-trello

#### basic test coverage for  [trello (v0.7.0)](https://github.com/norberteder/trello)  [![npm package](https://img.shields.io/npm/v/npmtest-trello.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-trello) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-trello.svg)](https://travis-ci.org/npmtest/node-npmtest-trello)

#### This module provides an easy way to make requests to the Trello API.

[![NPM](https://nodei.co/npm/trello.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/trello)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-trello/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-trello/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-trello/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-trello/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-trello/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-trello/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-trello/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-trello/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-trello/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-trello/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-trello/build/test-report.html](https://npmtest.github.io/node-npmtest-trello/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-trello/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-trello/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-trello/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-trello/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-trello/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-trello/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "trello",
    "version": "0.7.0",
    "author": "Norbert Eder <opensource@norberteder.com>",
    "description": "This module provides an easy way to make requests to the Trello API.",
    "contributors": [
        {
            "name": "Graeme Foster"
        },
        {
            "name": "Mike Beasley"
        },
        {
            "name": "Dario Kondratiuk"
        },
        {
            "name": "Sean Madden"
        },
        {
            "name": "Siôn Le Roux"
        }
    ],
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha"
    },
    "main": "main.js",
    "homepage": "https://github.com/norberteder/trello",
    "repository": {
        "type": "git",
        "url": "https://github.com/norberteder/trello.git"
    },
    "keywords": [
        "trello"
    ],
    "dependencies": {
        "es6-promise": "~3.0.2",
        "restler": "~3.3.0",
        "object-assign": "~4.1.0"
    },
    "devDependencies": {
        "mocha": "~2.3.2",
        "chai": "3.2.0",
        "sinon": "~1.16.1",
        "sinon-chai": "~2.8.0",
        "q": "~1.4.1"
    },
    "license": "MIT",
    "engines": {
        "node": ">= 0.10.x"
    },
    "optionalDependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
