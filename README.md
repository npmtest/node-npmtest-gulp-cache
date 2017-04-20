# npmtest-gulp-cache

#### basic test coverage for  [gulp-cache (v0.4.6)](https://github.com/jgable/gulp-cache#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-cache)

#### A cache proxy plugin for Gulp

[![NPM](https://nodei.co/npm/gulp-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cache/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jacob Gable",
        "url": "http://jacobgable.com"
    },
    "bugs": {
        "url": "https://github.com/jgable/gulp-cache/issues"
    },
    "contributors": [
        {
            "name": "Tyler Akins",
            "url": "https://github.com/fidian"
        },
        {
            "name": "Shinnosuke Watanabe",
            "url": "https://github.com/shinnn"
        }
    ],
    "dependencies": {
        "bluebird": "^3.0.5",
        "cache-swap": "^0.3.0",
        "gulp-util": "^3.0.7",
        "object-assign": "^4.0.1",
        "object.omit": "^2.0.0",
        "object.pick": "^1.1.1",
        "readable-stream": "^2.0.4",
        "try-json-parse": "^0.1.1",
        "vinyl": "^1.1.0"
    },
    "description": "A cache proxy plugin for Gulp",
    "devDependencies": {
        "@shinnn/eslint-config-node-legacy": "^1.0.0",
        "eslint": "^1.10.2",
        "istanbul": "^0.4.1",
        "lodash": "^4.1.0",
        "mocha": "^2.3.4",
        "should": "^8.2.1",
        "sinon": "^1.17.2",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2d03b52db4f6a553ae1d5bef01e483e907e9f796",
        "tarball": "https://registry.npmjs.org/gulp-cache/-/gulp-cache-0.4.6.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "d9df16c3d20274845051a29d2e24143c95f2d9c8",
    "homepage": "https://github.com/jgable/gulp-cache#readme",
    "keywords": [
        "gulpplugin",
        "gulp",
        "cache"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jgable"
        },
        {
            "name": "shinnn"
        }
    ],
    "name": "gulp-cache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jgable/gulp-cache.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha test.js",
        "pretest": "eslint --config @shinnn/node-legacy --rule 'no-underscore-dangle: 0' --rule 'no-warning-comments: 0' index.js lib test.js",
        "test": "_mocha test.js"
    },
    "version": "0.4.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
