# npmtest-leven

#### test coverage for  [leven (v2.1.0)](https://github.com/sindresorhus/leven#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-leven.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-leven) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-leven.svg)](https://travis-ci.org/npmtest/node-npmtest-leven)

#### Measure the difference between two strings using the fastest JS implementation of the Levenshtein distance algorithm

[![NPM](https://nodei.co/npm/leven.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/leven)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-leven/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-leven/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-leven/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-leven/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-leven/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-leven/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-leven/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-leven/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-leven/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-leven/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-leven/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-leven/build/test-report.html](https://npmtest.github.io/node-npmtest-leven/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-leven/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-leven/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-leven/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-leven/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leven/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leven/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-leven/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-leven/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/leven/issues"
    },
    "dependencies": {},
    "description": "Measure the difference between two strings using the fastest JS implementation of the Levenshtein distance algorithm",
    "devDependencies": {
        "ava": "^0.17.0",
        "fast-levenshtein": "^2.0.5",
        "ld": "^0.1.0",
        "levdist": "^2.0.0",
        "levenshtein": "^1.0.4",
        "levenshtein-component": "0.0.1",
        "levenshtein-edit-distance": "^2.0.0",
        "matcha": "^0.7.0",
        "natural": "^0.4.0",
        "talisman": "^0.18.0",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c2e7a9f772094dee9d34202ae8acce4687875580",
        "tarball": "https://registry.npmjs.org/leven/-/leven-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "0630566a69b5a73aae2e52bb47ea863892a4b5f0",
    "homepage": "https://github.com/sindresorhus/leven#readme",
    "keywords": [
        "leven",
        "levenshtein",
        "distance",
        "algorithm",
        "algo",
        "string",
        "difference",
        "diff",
        "fast",
        "fuzzy",
        "similar",
        "similarity",
        "compare",
        "comparison",
        "edit",
        "text",
        "match",
        "matching"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "leven",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/leven.git"
    },
    "scripts": {
        "bench": "matcha bench.js",
        "test": "xo && ava"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
