# npmtest-aws-sdk-mock

#### basic test coverage for  [aws-sdk-mock (v1.6.1)](https://github.com/dwyl/aws-sdk-mock#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-aws-sdk-mock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aws-sdk-mock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aws-sdk-mock.svg)](https://travis-ci.org/npmtest/node-npmtest-aws-sdk-mock)

#### Functions to mock the JavaScript aws-sdk

[![NPM](https://nodei.co/npm/aws-sdk-mock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aws-sdk-mock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aws-sdk-mock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aws-sdk-mock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aws-sdk-mock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/test-report.html](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aws-sdk-mock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nikhila Ravi & Jimmy Ruts"
    },
    "bugs": {
        "url": "https://github.com/dwyl/aws-sdk-mock/issues"
    },
    "dependencies": {
        "aws-sdk": "^2.3.0",
        "sinon": "^1.17.3",
        "traverse": "^0.6.6"
    },
    "description": "Functions to mock the JavaScript aws-sdk ",
    "devDependencies": {
        "concat-stream": "^1.5.1",
        "is-node-stream": "^1.0.0",
        "istanbul": "^0.4.2",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "79dce665a8295f76fde7afa7b4a6ca03e1afaa62",
        "tarball": "https://registry.npmjs.org/aws-sdk-mock/-/aws-sdk-mock-1.6.1.tgz"
    },
    "gitHead": "a9816997e94536f45eea81846282fcee43b75db7",
    "homepage": "https://github.com/dwyl/aws-sdk-mock#readme",
    "keywords": [
        "aws-sdk",
        "aws",
        "Amazon",
        "Lambda",
        "API-Gateway",
        "S3",
        "DynamoDB",
        "SNS",
        "test",
        "mock",
        "Node.js"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jruts"
        },
        {
            "name": "nelsonic"
        },
        {
            "name": "nikhilaravi"
        }
    ],
    "name": "aws-sdk-mock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dwyl/aws-sdk-mock.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/tape/bin/tape ./test/*.js && istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100 --report html",
        "nocov": "tape test/*.js",
        "test": "istanbul cover ./node_modules/tape/bin/tape ./test/*.js"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
