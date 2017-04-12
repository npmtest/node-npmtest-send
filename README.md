# test coverage for  [send (v0.15.1)](https://github.com/pillarjs/send#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-send.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-send) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-send.svg)](https://travis-ci.org/npmtest/node-npmtest-send)
#### Better streaming static file server with Range and conditional-GET support

[![NPM](https://nodei.co/npm/send.png?downloads=true)](https://www.npmjs.com/package/send)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-send/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-send/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-send/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-send/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-send/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-send/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-send/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-send/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-send/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-send/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-send%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-send/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-send/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-send%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-send/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-send/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-send/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/send/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "James Wyatt Cready",
            "email": "jcready@gmail.com"
        },
        {
            "name": "Jesús Leganés Combarro",
            "email": "piranna@gmail.com"
        }
    ],
    "dependencies": {
        "debug": "2.6.1",
        "depd": "~1.1.0",
        "destroy": "~1.0.4",
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "etag": "~1.8.0",
        "fresh": "0.5.0",
        "http-errors": "~1.6.1",
        "mime": "1.3.4",
        "ms": "0.7.2",
        "on-finished": "~2.3.0",
        "range-parser": "~1.2.0",
        "statuses": "~1.3.1"
    },
    "description": "Better streaming static file server with Range and conditional-GET support",
    "devDependencies": {
        "after": "0.8.2",
        "eslint": "3.17.0",
        "eslint-config-standard": "7.0.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8a02354c26e6f5cca700065f5f0cdeba90ec7b5f",
        "tarball": "https://registry.npmjs.org/send/-/send-0.15.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "ea1748a3b3e00dbcbb0629cf368ced575c6ab7d6",
    "homepage": "https://github.com/pillarjs/send#readme",
    "keywords": [
        "static",
        "file",
        "server"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "name": "send",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/send.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --check-leaks --reporter spec --bail",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot"
    },
    "version": "0.15.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
