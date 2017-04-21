# npmtest-exectimer

#### basic test coverage for  [exectimer (v2.0.3)](https://github.com/alexandrusavin/exectimer)  [![npm package](https://img.shields.io/npm/v/npmtest-exectimer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-exectimer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-exectimer.svg)](https://travis-ci.org/npmtest/node-npmtest-exectimer)

#### Very simple module to calculate block execution time.

[![NPM](https://nodei.co/npm/exectimer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exectimer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-exectimer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-exectimer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-exectimer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-exectimer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-exectimer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-exectimer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-exectimer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-exectimer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-exectimer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-exectimer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-exectimer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-exectimer/build/test-report.html](https://npmtest.github.io/node-npmtest-exectimer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-exectimer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-exectimer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exectimer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-exectimer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-exectimer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexandru Savin"
    },
    "bugs": {
        "url": "https://github.com/alexandrusavin/exectimer/issues"
    },
    "dependencies": {
        "co": "^4.6.0"
    },
    "description": "Very simple module to calculate block execution time.",
    "devDependencies": {
        "async": "^1.5.0",
        "chai": "^3.4.1",
        "mocha": "^2.3.4",
        "should": "^7.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6b3404ed0ce2193cab8fab72f8ea61472de24888",
        "tarball": "https://registry.npmjs.org/exectimer/-/exectimer-2.0.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "f52d8b42dd7e50d66d7afb46fc35d2044e030720",
    "homepage": "https://github.com/alexandrusavin/exectimer",
    "keywords": [
        "time",
        "timer",
        "profiler",
        "execution",
        "performance",
        "analysis",
        "benchmark"
    ],
    "main": "./index",
    "maintainers": [
        {
            "name": "alexsavin"
        }
    ],
    "name": "exectimer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/alexandrusavin/exectimer.git"
    },
    "scripts": {
        "jshint": "jshint --config .jshintrc --exclude node_modules *.js",
        "test": "mocha test/**/*.js"
    },
    "version": "2.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
