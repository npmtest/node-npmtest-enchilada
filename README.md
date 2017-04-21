# npmtest-enchilada

#### basic test coverage for  enchilada (v0.13.0)  [![npm package](https://img.shields.io/npm/v/npmtest-enchilada.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-enchilada) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-enchilada.svg)](https://travis-ci.org/npmtest/node-npmtest-enchilada)

#### middleware for automatic javascript bundles

[![NPM](https://nodei.co/npm/enchilada.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/enchilada)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-enchilada/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-enchilada/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-enchilada/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-enchilada/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-enchilada/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-enchilada/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-enchilada/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-enchilada/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-enchilada/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-enchilada/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-enchilada/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-enchilada/build/test-report.html](https://npmtest.github.io/node-npmtest-enchilada/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-enchilada/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-enchilada/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-enchilada/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-enchilada/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-enchilada/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "enchilada",
    "version": "0.13.0",
    "description": "middleware for automatic javascript bundles",
    "main": "index.js",
    "scripts": {
        "test": "mocha test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shtylman/node-enchilada.git"
    },
    "keywords": [
        "browserify",
        "express",
        "script",
        "bundle",
        "compile",
        "minify"
    ],
    "author": "Roman Shtylman <shtylman@gmail.com>",
    "license": "MIT",
    "dependencies": {
        "browserify": "4.1.9",
        "convert-source-map": "1.1.1",
        "debug": "2.2.0",
        "filewatcher": "3.0.0",
        "mime": "1.2.11",
        "ready-signal": "1.3.0",
        "uglify-js": "2.5.0"
    },
    "devDependencies": {
        "through": "2.3.4",
        "connect": "2.12.0",
        "mocha": "1.17.0",
        "after": "0.8.1",
        "supertest": "0.9.0",
        "express": "3.4.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
