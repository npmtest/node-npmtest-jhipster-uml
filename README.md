# npmtest-jhipster-uml

#### basic test coverage for  [jhipster-uml (v2.0.3)](https://github.com/jhipster/jhipster-uml)  [![npm package](https://img.shields.io/npm/v/npmtest-jhipster-uml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jhipster-uml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jhipster-uml.svg)](https://travis-ci.org/npmtest/node-npmtest-jhipster-uml)

#### UML support for JHipster via XMI files

[![NPM](https://nodei.co/npm/jhipster-uml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jhipster-uml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jhipster-uml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jhipster-uml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jhipster-uml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jhipster-uml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jhipster-uml/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jhipster-uml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jhipster-uml/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jhipster-uml/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jhipster-uml/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jhipster-uml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jhipster-uml/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jhipster-uml/build/test-report.html](https://npmtest.github.io/node-npmtest-jhipster-uml/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jhipster-uml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jhipster-uml/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jhipster-uml/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jhipster-uml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jhipster-uml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathieu Abou-Aichi",
        "url": "https://github.com/MathieuAA"
    },
    "bin": {
        "jhipster-uml": "./jhipster-uml.js"
    },
    "bugs": {
        "url": "https://github.com/jhipster/jhipster-uml/issues"
    },
    "contributors": [
        {
            "name": "Mathieu Abou-Aichi"
        },
        {
            "name": "Carl Klagba"
        }
    ],
    "dependencies": {
        "chalk": "1.1.3",
        "deasync": "0.1.9",
        "inquirer": "2.0.0",
        "jhipster-core": "1.2.6",
        "lodash": "4.17.4",
        "xml2js": "0.4.17",
        "yargs": "6.6.0"
    },
    "description": "UML support for JHipster via XMI files",
    "devDependencies": {
        "chai": "3.5.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "mocha-clean": "1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bcf9e215ed00ed9f25fb9801045cc77716bb9dea",
        "tarball": "https://registry.npmjs.org/jhipster-uml/-/jhipster-uml-2.0.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0",
        "npm": ">=2.14.2"
    },
    "gitHead": "48f75dcfcdbfd14fd102713b62d8578699fe1054",
    "homepage": "https://github.com/jhipster/jhipster-uml",
    "keywords": [
        "generator-jhipster",
        "UML",
        "XMI",
        "JSON"
    ],
    "license": "Apache-2.0",
    "licenses": [
        {
            "type": "Apache 2.0"
        }
    ],
    "main": "module/index.js",
    "maintainers": [
        {
            "name": "jdubois"
        },
        {
            "name": "mathieuaa"
        },
        {
            "name": "cklagba"
        }
    ],
    "name": "jhipster-uml",
    "optionalDependencies": {},
    "peerDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jhipster/jhipster-uml.git"
    },
    "scripts": {
        "coverage": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha test; ./node_modules/istanbul/lib/cli.js check-coverage",
        "test": "./node_modules/mocha/bin/mocha test"
    },
    "version": "2.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
