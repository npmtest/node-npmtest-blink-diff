# npmtest-blink-diff

#### basic test coverage for  [blink-diff (v1.0.13)](https://github.com/yahoo/blink-diff)  [![npm package](https://img.shields.io/npm/v/npmtest-blink-diff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-blink-diff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-blink-diff.svg)](https://travis-ci.org/npmtest/node-npmtest-blink-diff)

#### A lightweight image comparison tool

[![NPM](https://nodei.co/npm/blink-diff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blink-diff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-blink-diff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-blink-diff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-blink-diff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-blink-diff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-blink-diff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-blink-diff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-blink-diff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-blink-diff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-blink-diff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-blink-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-blink-diff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-blink-diff/build/test-report.html](https://npmtest.github.io/node-npmtest-blink-diff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-blink-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-blink-diff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-blink-diff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blink-diff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blink-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blink-diff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-blink-diff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-blink-diff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "blink-diff",
    "version": "1.0.13",
    "description": "A lightweight image comparison tool",
    "license": "MIT",
    "main": "index.js",
    "bugs": "https://github.com/yahoo/blink-diff/issues",
    "homepage": "https://github.com/yahoo/blink-diff",
    "bin": {
        "blink-diff": "bin/blink-diff"
    },
    "author": {
        "name": "Marcel Erz",
        "url": "http://www.marcelerz.com"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/yahoo/blink-diff.git"
    },
    "keywords": [
        "image-diff",
        "visual-diff",
        "diff",
        "testing",
        "blink",
        "image",
        "difference",
        "compare"
    ],
    "scripts": {
        "test": "istanbul cover -- _mocha --reporter spec",
        "docs": "yuidoc ."
    },
    "dependencies": {
        "pngjs-image": "~0.11.5",
        "preceptor-core": "~0.10.0",
        "promise": "6.0.0"
    },
    "devDependencies": {
        "chai": "1.9.2",
        "coveralls": "2.11.2",
        "codeclimate-test-reporter": "0.0.4",
        "istanbul": "0.3.2",
        "mocha": "1.21.4",
        "sinon": "1.12.2",
        "sinon-chai": "2.7.0",
        "yuidocjs": "0.3.50"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
