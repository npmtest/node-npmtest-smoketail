# npmtest-smoketail

#### basic test coverage for  [smoketail (v0.1.0)](https://github.com/cinema6/smoketail)  [![npm package](https://img.shields.io/npm/v/npmtest-smoketail.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-smoketail) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-smoketail.svg)](https://travis-ci.org/npmtest/node-npmtest-smoketail)

#### Library and utility for tailing AWS CloudWatch Logs.

[![NPM](https://nodei.co/npm/smoketail.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/smoketail)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-smoketail/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-smoketail/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-smoketail/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-smoketail/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-smoketail/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-smoketail/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-smoketail/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-smoketail/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-smoketail/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-smoketail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-smoketail/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-smoketail/build/test-report.html](https://npmtest.github.io/node-npmtest-smoketail/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-smoketail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-smoketail/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-smoketail/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-smoketail/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-smoketail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-smoketail/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-smoketail/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-smoketail/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "smoketail",
    "version": "0.1.0",
    "description": "Library and utility for tailing AWS CloudWatch Logs.",
    "main": "index.js",
    "bin": {
        "smoketail": "./bin/smoketail.js"
    },
    "scripts": {
        "test": "grunt"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/cinema6/smoketail.git"
    },
    "keywords": [
        "aws",
        "cloudwatch",
        "logs",
        "cloudwatchlogs",
        "tail"
    ],
    "author": "Howard Engelhart",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/cinema6/smoketail/issues"
    },
    "homepage": "https://github.com/cinema6/smoketail",
    "dependencies": {
        "q": "^1.4.1",
        "aws-sdk": "^2.2.14",
        "commander": "~2.9.0"
    },
    "devDependencies": {
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-watch": "^0.6.1",
        "grunt": "^0.4.5",
        "jshint": "^2.8.0",
        "jasmine": "^2.3.2",
        "jasmine-reporters": "^2.0.7",
        "load-grunt-config": "^0.19.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
