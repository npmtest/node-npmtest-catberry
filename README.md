# npmtest-catberry

#### test coverage for  [catberry (v9.0.0)](https://github.com/catberry/catberry)  [![npm package](https://img.shields.io/npm/v/npmtest-catberry.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-catberry) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-catberry.svg)](https://travis-ci.org/npmtest/node-npmtest-catberry)

#### Catberry is an isomorphic framework for building universal front-end apps using components, Flux architecture and progressive rendering.

[![NPM](https://nodei.co/npm/catberry.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/catberry)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-catberry/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-catberry/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-catberry/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-catberry/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-catberry/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-catberry/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-catberry/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-catberry/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-catberry/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-catberry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-catberry/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-catberry/build/test-report.html](https://npmtest.github.io/node-npmtest-catberry/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-catberry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-catberry/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-catberry/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-catberry/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-catberry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-catberry/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-catberry/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-catberry/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Denis Rechkunov"
    },
    "browser": {
        "./lib/Bootstrapper.js": "./browser/Bootstrapper.js",
        "./lib/Catberry.js": "./browser/Catberry.js",
        "./lib/CookieWrapper.js": "./browser/CookieWrapper.js",
        "./lib/providers/ModuleApiProvider.js": "./browser/providers/ModuleApiProvider.js",
        "./lib/providers/StateProvider.js": "./browser/providers/StateProvider.js",
        "./lib/loaders/ComponentLoader.js": "./browser/loaders/ComponentLoader.js",
        "./lib/loaders/StoreLoader.js": "./browser/loaders/StoreLoader.js",
        "./lib/DocumentRenderer.js": "./browser/DocumentRenderer.js",
        "./lib/RequestRouter.js": "./browser/RequestRouter.js",
        "./lib/helpers/hrTimeHelper.js": "./browser/helpers/hrTimeHelper.js"
    },
    "bugs": {
        "url": "https://github.com/catberry/catberry/issues"
    },
    "contributors": [
        {
            "name": "Denis Rechkunov"
        },
        {
            "name": "Julia Rechkunova"
        },
        {
            "name": "Jonathan Pollack"
        },
        {
            "name": "Mikhail Reenko"
        },
        {
            "name": "Pavel Sokolov"
        },
        {
            "name": "Dmitry Vasilyev"
        },
        {
            "name": "Maxim Chetverikov"
        },
        {
            "name": "Julia Kostyukova"
        },
        {
            "name": "Mansur Gabidullin"
        }
    ],
    "dependencies": {
        "babel-preset-babili": "~0.0.12",
        "babel-preset-env": "^1.2.2",
        "babelify": "^7.3.0",
        "browser-process-hrtime": "~0.1.2",
        "browserify": "^14.1.0",
        "catberry-locator": "^2.2.1",
        "catberry-uri": "^3.2.2",
        "chokidar": "^1.6.1",
        "entities": "^1.1.1",
        "glob": "^7.1.1",
        "mkdirp": "~0.5.1",
        "morphdom": "~2.2.0",
        "pretty-hrtime": "^1.0.3",
        "promise": "^7.1.1",
        "uuid": "^3.0.1",
        "watchify": "^3.9.0"
    },
    "description": "Catberry is an isomorphic framework for building universal front-end apps using components, Flux architecture and progressive rendering.",
    "devDependencies": {
        "codecov": "^2.1.0",
        "eslint": "^3.18.0",
        "istanbul": "~0.4.5",
        "jsdom": "^9.12.0",
        "mocha": "^3.2.0",
        "ncp": "^2.0.0",
        "rimraf": "^2.6.1"
    },
    "directories": {
        "doc": "docs"
    },
    "dist": {
        "shasum": "08aae73219cfd7717877f5c884905a55065cb577",
        "tarball": "https://registry.npmjs.org/catberry/-/catberry-9.0.0.tgz"
    },
    "engines": {
        "node": ">=6.10"
    },
    "gitHead": "74a8fa6272812742af4f8ee79f2c7df817ed516c",
    "homepage": "https://github.com/catberry/catberry",
    "keywords": [
        "progressive rendering",
        "Web",
        "isomorphic",
        "framework",
        "middleware",
        "connect",
        "express",
        "component",
        "Flux"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "pragmadash"
        }
    ],
    "name": "catberry",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/catberry/catberry.git"
    },
    "scripts": {
        "test": "make"
    },
    "version": "9.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
