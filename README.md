# npmtest-nsp

#### basic test coverage for  [nsp (v2.6.3)](https://github.com/nodesecurity/nsp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nsp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nsp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nsp.svg)](https://travis-ci.org/npmtest/node-npmtest-nsp)

#### The Node Security (nodesecurity.io) command line interface

[![NPM](https://nodei.co/npm/nsp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nsp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nsp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nsp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nsp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nsp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nsp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nsp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nsp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nsp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nsp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nsp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nsp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nsp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nsp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nsp/build/test-report.html](https://npmtest.github.io/node-npmtest-nsp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nsp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nsp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nsp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nsp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nsp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nsp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nsp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nsp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "^lift security"
    },
    "bin": {
        "nsp": "bin/nsp"
    },
    "bugs": {
        "url": "https://github.com/nodesecurity/nsp/issues"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "cli-table": "^0.3.1",
        "cvss": "^1.0.0",
        "https-proxy-agent": "^1.0.0",
        "joi": "^6.9.1",
        "nodesecurity-npm-utils": "^5.0.0",
        "path-is-absolute": "^1.0.0",
        "rc": "^1.1.2",
        "semver": "^5.0.3",
        "subcommand": "^2.0.3",
        "wreck": "^6.3.0"
    },
    "description": "The Node Security (nodesecurity.io) command line interface",
    "devDependencies": {
        "code": "^1.5.0",
        "eslint": "^2.5.3",
        "eslint-config-nodesecurity": "^1.3.1",
        "eslint-plugin-hapi": "^1.2.2",
        "git-validate": "^2.1.0",
        "lab": "^6.2.0",
        "nock": "^7.7.2",
        "shrinkydink": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "db05035953cda2ab3a571ee82fab84f4cb081d17",
        "tarball": "https://registry.npmjs.org/nsp/-/nsp-2.6.3.tgz"
    },
    "gitHead": "ee544f5fac4899cc6b1f81f123c39c293e4bf01b",
    "homepage": "https://github.com/nodesecurity/nsp#readme",
    "keywords": [
        "security",
        "nsp",
        "nodesecurity"
    ],
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "adam_baldwin"
        },
        {
            "name": "andyet-ops"
        },
        {
            "name": "gar"
        },
        {
            "name": "nlf"
        }
    ],
    "name": "nsp",
    "optionalDependencies": {},
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/nodesecurity/nsp.git"
    },
    "scripts": {
        "lint": "eslint . bin/nsp",
        "nsp": "bin/nsp check",
        "setup-offline": "curl -sS https://api.nodesecurity.io/advisories -o advisories.json",
        "shrinkwrap": "npm shrinkwrap && shrinkydink",
        "test": "lab -a code -t 100 -I Reflect"
    },
    "version": "2.6.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
