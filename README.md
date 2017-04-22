# npmtest-cowsay

#### basic test coverage for  [cowsay (v1.1.9)](https://github.com/piuccio/cowsay)  [![npm package](https://img.shields.io/npm/v/npmtest-cowsay.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cowsay) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cowsay.svg)](https://travis-ci.org/npmtest/node-npmtest-cowsay)

#### cowsay is a configurable talking cow

[![NPM](https://nodei.co/npm/cowsay.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cowsay)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cowsay/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cowsay/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cowsay/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cowsay/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cowsay/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cowsay/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cowsay/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cowsay/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cowsay/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cowsay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cowsay/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cowsay/build/test-report.html](https://npmtest.github.io/node-npmtest-cowsay/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cowsay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cowsay/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cowsay/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cowsay/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cowsay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cowsay/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cowsay/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cowsay/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fabio Crisci",
        "url": "https://github.com/piuccio/"
    },
    "bin": {
        "cowsay": "./cli.js",
        "cowthink": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/piuccio/cowsay/issues"
    },
    "dependencies": {
        "get-stdin": "^4.0.1",
        "optimist": "~0.6.1"
    },
    "description": "cowsay is a configurable talking cow",
    "devDependencies": {
        "nodeunit": "~0.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "92eb7d3c4337ee9c374938c183d6fa17e0288705",
        "tarball": "https://registry.npmjs.org/cowsay/-/cowsay-1.1.9.tgz"
    },
    "files": [
        "index.js",
        "cli.js",
        "cows/",
        "lib/"
    ],
    "gitHead": "ba40c7926ffeb642f0186bdf728706d0b34d7490",
    "homepage": "https://github.com/piuccio/cowsay",
    "keywords": [
        "cow",
        "cowsay",
        "cowthink",
        "figlet",
        "talking",
        "ASCII"
    ],
    "main": "./index",
    "maintainers": [
        {
            "name": "piuccio"
        }
    ],
    "name": "cowsay",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/piuccio/cowsay.git"
    },
    "scripts": {
        "test": "node test.js"
    },
    "version": "1.1.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
