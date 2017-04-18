# npmtest-jump.js

#### test coverage for  [jump.js (v1.0.2)](https://github.com/callmecavs/jump.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jump.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jump.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jump.js.svg)](https://travis-ci.org/npmtest/node-npmtest-jump.js)

#### A modern smooth scrolling library.

[![NPM](https://nodei.co/npm/jump.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jump.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jump.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jump.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jump.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jump.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jump.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jump.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jump.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jump.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jump.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jump.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jump.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jump.js/build/test-report.html](https://npmtest.github.io/node-npmtest-jump.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jump.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jump.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jump.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jump.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jump.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jump.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jump.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jump.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Cavalea",
        "url": "http://callmecavs.com/"
    },
    "bugs": {
        "url": "https://github.com/callmecavs/jump.js/issues"
    },
    "dependencies": {},
    "description": "A modern smooth scrolling library.",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-preset-es2015-rollup": "^3.0.0",
        "babel-preset-stage-0": "^6.16.0",
        "eslint": "^3.13.0",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "rollup": "^0.41.1",
        "rollup-plugin-babel": "^2.7.1",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-watch": "^3.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e0641b47f40a38f2139c25fda0500bf28e43015a",
        "tarball": "https://registry.npmjs.org/jump.js/-/jump.js-1.0.2.tgz"
    },
    "gitHead": "8aab6239d564a69eccbb99712956418f9a7b43a3",
    "homepage": "https://github.com/callmecavs/jump.js#readme",
    "jsnext:main": "dist/jump.module.js",
    "keywords": [
        "smooth",
        "scroll"
    ],
    "license": "MIT",
    "main": "dist/jump.js",
    "maintainers": [
        {
            "name": "callmecavs"
        }
    ],
    "module": "dist/jump.module.js",
    "name": "jump.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/callmecavs/jump.js.git"
    },
    "scripts": {
        "build": "rollup -c",
        "dev": "rollup -c -w -m inline",
        "prebuild": "eslint src",
        "prepublish": "npm run build",
        "server": "python -m SimpleHTTPServer 3000"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
