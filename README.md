# npmtest-rstats

#### basic test coverage for  [rstats (v0.3.1)](https://github.com/Planeshifter/node-Rstats)  [![npm package](https://img.shields.io/npm/v/npmtest-rstats.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rstats) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rstats.svg)](https://travis-ci.org/npmtest/node-npmtest-rstats)

#### A node.js interface for statistical programming language R

[![NPM](https://nodei.co/npm/rstats.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rstats)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rstats/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rstats/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rstats/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rstats/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rstats/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rstats/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rstats/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rstats/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rstats/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rstats/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rstats/build/test-report.html](https://npmtest.github.io/node-npmtest-rstats/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rstats/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rstats/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rstats/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rstats",
    "version": "0.3.1",
    "description": "A node.js interface for statistical programming language R",
    "main": "./lib/index.js",
    "scripts": {
        "test": "node-gyp configure build && mocha test",
        "install": "node-gyp rebuild"
    },
    "dependencies": {
        "bindings": "1.2.0",
        "nan": "^1.7.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Planeshifter/node-Rstats.git"
    },
    "keywords": [
        "statistics",
        "R",
        "Rcpp"
    ],
    "author": "Philipp Burckhardt",
    "license": "ISC",
    "gypfile": true,
    "bugs": {
        "url": "https://github.com/Planeshifter/node-Rstats/issues"
    },
    "homepage": "https://github.com/Planeshifter/node-Rstats",
    "devDependencies": {
        "chai": "^2.1.2",
        "mocha": "^2.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
