# npmtest-rbac2

#### basic test coverage for  [rbac2 (v1.1.0)](https://github.com/ramniquesingh/rbac2#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rbac2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rbac2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rbac2.svg)](https://travis-ci.org/npmtest/node-npmtest-rbac2)

#### Simple RBAC checker with support for context checks.

[![NPM](https://nodei.co/npm/rbac2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rbac2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rbac2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rbac2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rbac2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rbac2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rbac2/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-rbac2/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-rbac2/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rbac2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rbac2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rbac2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rbac2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rbac2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rbac2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rbac2/build/test-report.html](https://npmtest.github.io/node-npmtest-rbac2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rbac2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rbac2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rbac2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rbac2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rbac2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rbac2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rbac2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rbac2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ramnique Singh",
        "url": "http://twitter.com/ramniquesingh"
    },
    "bugs": {
        "url": "https://github.com/ramniquesingh/rbac2/issues"
    },
    "contributors": [
        {
            "name": "Jigar Jain",
            "url": "http://twitter.com/ragij"
        }
    ],
    "dependencies": {
        "async": "^1.5.2",
        "lodash": "^4.0.0"
    },
    "description": "Simple RBAC checker with support for context checks.",
    "devDependencies": {
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "55b6aa05be4022aa9076106358a4106f1799a2bc",
        "tarball": "https://registry.npmjs.org/rbac2/-/rbac2-1.1.0.tgz"
    },
    "gitHead": "3462c68411f7a6fac851da7825d2c0bf2a109a22",
    "homepage": "https://github.com/ramniquesingh/rbac2#readme",
    "keywords": [
        "rbac",
        "role",
        "based",
        "access",
        "control",
        "hierarchical",
        "context",
        "business",
        "logic",
        "database"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ramniquesingh"
        }
    ],
    "name": "rbac2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ramniquesingh/rbac2.git"
    },
    "scripts": {
        "test": "PATH=$(npm bin):$PATH mocha --recursive --full-trace --bail --check-leaks --reporter list tests"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
