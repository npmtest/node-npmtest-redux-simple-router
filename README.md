# npmtest-redux-simple-router

#### basic test coverage for  [redux-simple-router (v2.0.4)](https://github.com/rackt/redux-simple-router#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-simple-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-simple-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-simple-router.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-simple-router)

#### Ruthlessly simple bindings to keep react-router and redux in sync

[![NPM](https://nodei.co/npm/redux-simple-router.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-simple-router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-simple-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-simple-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-simple-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-simple-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-simple-router/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-redux-simple-router/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-redux-simple-router/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-simple-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-simple-router/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-simple-router/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-simple-router/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-simple-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-simple-router/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-simple-router/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-simple-router/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-simple-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-simple-router/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-simple-router/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-simple-router/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-simple-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-simple-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-simple-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-simple-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "James Long"
    ],
    "bugs": {
        "url": "https://github.com/rackt/redux-simple-router/issues"
    },
    "dependencies": {},
    "deprecated": "WARNING: This package has been renamed to react-router-redux. See https://github.com/rackt/react-router-redux/issues/80",
    "description": "Ruthlessly simple bindings to keep react-router and redux in sync",
    "devDependencies": {
        "babel-cli": "^6.1.2",
        "babel-core": "^6.2.1",
        "babel-eslint": "^4.1.6",
        "babel-loader": "^6.2.0",
        "babel-preset-es2015": "^6.1.2",
        "babel-preset-stage-2": "^6.3.13",
        "eslint": "^1.10.3",
        "eslint-config-rackt": "^1.1.1",
        "expect": "^1.13.0",
        "history": "^1.14.0",
        "isparta": "^4.0.0",
        "isparta-loader": "^2.0.0",
        "karma": "^0.13.3",
        "karma-chrome-launcher": "^0.2.0",
        "karma-coverage": "^0.5.3",
        "karma-firefox-launcher": "^0.1.7",
        "karma-ie-launcher": "^0.2.0",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^1.0.4",
        "karma-safari-launcher": "^0.1.1",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.3.4",
        "react": "^0.14.3",
        "redux": "^3.0.4",
        "redux-devtools": "^3.0.0",
        "redux-devtools-dock-monitor": "^1.0.1",
        "redux-devtools-log-monitor": "^1.0.1",
        "webpack": "^1.12.9"
    },
    "directories": {},
    "dist": {
        "shasum": "ab4141e1b134d4025018c904d4c423479c0fc20f",
        "tarball": "https://registry.npmjs.org/redux-simple-router/-/redux-simple-router-2.0.4.tgz"
    },
    "files": [
        "*.md",
        "LICENSE",
        "lib",
        "src"
    ],
    "gitHead": "5f1c531e8d425593a229ff78ee47c255bef82c40",
    "homepage": "https://github.com/rackt/redux-simple-router#readme",
    "keywords": [
        "react",
        "redux",
        "router"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "jlongster"
        },
        {
            "name": "timdorr"
        }
    ],
    "name": "redux-simple-router",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rackt/redux-simple-router.git"
    },
    "scripts": {
        "build": "mkdir -p lib && babel ./src/index.js --out-file ./lib/index.js",
        "lint": "eslint src test",
        "prepublish": "npm run build",
        "test": "npm run test:node && npm run test:browser",
        "test:browser": "karma start",
        "test:cov": "npm run test:cov:browser && npm run test:cov:node && npm run test:cov:report",
        "test:cov:browser": "COVERAGE=true karma start",
        "test:cov:node": "babel-node $(npm bin)/isparta cover $(npm bin)/_mocha report --dir ./coverage/node-coverage -- --recursive ./test/node",
        "test:cov:report": "$(npm bin)/istanbul report --dir ./coverage --include **/*coverage.json html text",
        "test:node": "mocha --compilers js:babel-core/register --recursive ./test/node"
    },
    "tags": [
        "react",
        "redux"
    ],
    "version": "2.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
