# npmtest-vconsole

#### basic test coverage for  [vconsole (v2.5.2)](https://github.com/WechatFE/vConsole)  [![npm package](https://img.shields.io/npm/v/npmtest-vconsole.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vconsole) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vconsole.svg)](https://travis-ci.org/npmtest/node-npmtest-vconsole)

#### A lightweight, extendable front-end developer tool for mobile web page.

[![NPM](https://nodei.co/npm/vconsole.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vconsole)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vconsole/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vconsole/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vconsole/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vconsole/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vconsole/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vconsole/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vconsole/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vconsole/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vconsole/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vconsole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vconsole/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vconsole/build/test-report.html](https://npmtest.github.io/node-npmtest-vconsole/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vconsole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vconsole/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vconsole/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vconsole/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vconsole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vconsole/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vconsole/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vconsole/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vconsole",
    "version": "2.5.2",
    "description": "A lightweight, extendable front-end developer tool for mobile web page.",
    "homepage": "https://github.com/WechatFE/vConsole",
    "main": "dist/vconsole.min.js",
    "scripts": {
        "test": "mocha",
        "dist": "webpack && npm test"
    },
    "keywords": [
        "console",
        "debug",
        "mobile"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/WechatFE/vConsole.git"
    },
    "dependencies": {},
    "devDependencies": {
        "babel-core": "^6.7.7",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.1.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-stage-3": "^6.5.0",
        "chai": "^3.5.0",
        "css-loader": "^0.23.1",
        "extract-text-webpack-plugin": "^1.0.1",
        "html-loader": "^0.4.3",
        "jsdom": "^9.2.1",
        "json-loader": "^0.5.4",
        "less": "^2.5.3",
        "less-loader": "^2.2.3",
        "mocha": "^2.5.3",
        "style-loader": "^0.13.1",
        "webpack": "~1.12.11"
    },
    "author": "WechatFE Team",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
