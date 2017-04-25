# npmtest-node-pushserver

#### basic test coverage for  [node-pushserver (v0.5.4)](https://github.com/Smile-SA/node-pushserver)  [![npm package](https://img.shields.io/npm/v/npmtest-node-pushserver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-pushserver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-pushserver.svg)](https://travis-ci.org/npmtest/node-npmtest-node-pushserver)

#### Cross-platform Push Notifications. A project providing a generic API to push messages using Apple's APN and Google's GCM services.

[![NPM](https://nodei.co/npm/node-pushserver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-pushserver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-pushserver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-pushserver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-pushserver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-pushserver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-pushserver/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-pushserver/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-pushserver/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-pushserver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-pushserver/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-pushserver/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-pushserver/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-pushserver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-pushserver/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-pushserver/build/test-report.html](https://npmtest.github.io/node-npmtest-node-pushserver/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-pushserver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-pushserver/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-pushserver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-pushserver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-pushserver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-pushserver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-pushserver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-pushserver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "pushserver": "./bin/pushserver.js"
    },
    "bugs": {
        "url": "https://github.com/Smile-SA/node-pushserver/issues"
    },
    "dependencies": {
        "apn": "~1.3.4",
        "commander": "2.7.1",
        "express": "~3.2.6",
        "lodash": "~1.3.1",
        "mongoose": "~3.6.11",
        "node-gcm": "~0.9.6"
    },
    "description": "Cross-platform Push Notifications. A project providing a generic API to push messages using Apple's APN and Google's GCM services.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5a1de6131c55f5e3e897c1c130e58e1fbf99e603",
        "tarball": "https://registry.npmjs.org/node-pushserver/-/node-pushserver-0.5.4.tgz"
    },
    "gitHead": "19b7c37d4ca23a1d2782faa5bc0ed4b6c80051c9",
    "homepage": "https://github.com/Smile-SA/node-pushserver",
    "keywords": [
        "push",
        "gcm",
        "apn",
        "mongodb"
    ],
    "main": "./lib/PushController.js",
    "maintainers": [
        {
            "name": "smile"
        }
    ],
    "name": "node-pushserver",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Smile-SA/node-pushserver.git"
    },
    "scripts": {
        "start": "node ./bin/pushserver.js",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.5.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
