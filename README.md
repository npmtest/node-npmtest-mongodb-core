# npmtest-mongodb-core

#### test coverage for  [mongodb-core (v2.1.10)](https://github.com/christkv/mongodb-core)  [![npm package](https://img.shields.io/npm/v/npmtest-mongodb-core.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongodb-core) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongodb-core.svg)](https://travis-ci.org/npmtest/node-npmtest-mongodb-core)

#### Core MongoDB driver functionality, no bells and whistles and meant for integration not end applications

[![NPM](https://nodei.co/npm/mongodb-core.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongodb-core)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongodb-core/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongodb-core/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongodb-core/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongodb-core/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongodb-core/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongodb-core/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongodb-core/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongodb-core/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongodb-core/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongodb-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongodb-core/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongodb-core/build/test-report.html](https://npmtest.github.io/node-npmtest-mongodb-core/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongodb-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongodb-core/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongodb-core/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongodb-core/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongodb-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongodb-core/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongodb-core/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongodb-core/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christian Kvalheim"
    },
    "bugs": {
        "url": "https://github.com/christkv/mongodb-core/issues"
    },
    "dependencies": {
        "bson": "~1.0.4",
        "require_optional": "~1.0.0"
    },
    "description": "Core MongoDB driver functionality, no bells and whistles and meant for integration not end applications",
    "devDependencies": {
        "co": "^4.5.4",
        "coveralls": "^2.11.6",
        "es6-promise": "^3.0.2",
        "gleak": "0.5.0",
        "integra": "0.1.8",
        "jsdoc": "3.3.0-alpha8",
        "mkdirp": "0.5.0",
        "mongodb-topology-manager": "1.0.x",
        "mongodb-version-manager": "github:christkv/mongodb-version-manager#master",
        "nyc": "^5.5.0",
        "optimist": "latest",
        "rimraf": "2.2.6",
        "semver": "4.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "eb290681d196d3346a492161aa2ea0905e63151b",
        "tarball": "https://registry.npmjs.org/mongodb-core/-/mongodb-core-2.1.10.tgz"
    },
    "gitHead": "68034ad1efba288e6fa3137b80fcf67ae01afed2",
    "homepage": "https://github.com/christkv/mongodb-core",
    "keywords": [
        "mongodb",
        "core"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "christkv"
        }
    ],
    "name": "mongodb-core",
    "optionalDependencies": {},
    "peerOptionalDependencies": {
        "kerberos": "~0.0",
        "bson-ext": "1.0.5"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/christkv/mongodb-core.git"
    },
    "scripts": {
        "coverage": "nyc node test/runner.js -t functional -l && node_modules/.bin/nyc report --reporter=text-lcov | node_modules/.bin/coveralls",
        "lint": "eslint lib",
        "test": "node test/runner.js -t functional"
    },
    "version": "2.1.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
