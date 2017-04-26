# npmtest-systemjs-builder

#### basic test coverage for  [systemjs-builder (v0.16.4)](https://github.com/systemjs/builder)  [![npm package](https://img.shields.io/npm/v/npmtest-systemjs-builder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-systemjs-builder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-systemjs-builder.svg)](https://travis-ci.org/npmtest/node-npmtest-systemjs-builder)

#### SystemJS Build Tool

[![NPM](https://nodei.co/npm/systemjs-builder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/systemjs-builder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-systemjs-builder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-systemjs-builder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-systemjs-builder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-systemjs-builder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-systemjs-builder/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-systemjs-builder/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-systemjs-builder/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-systemjs-builder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-systemjs-builder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-systemjs-builder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-systemjs-builder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-systemjs-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-systemjs-builder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-systemjs-builder/build/test-report.html](https://npmtest.github.io/node-npmtest-systemjs-builder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-systemjs-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-systemjs-builder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-systemjs-builder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-systemjs-builder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-systemjs-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-systemjs-builder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-systemjs-builder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-systemjs-builder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/systemjs/builder/issues"
    },
    "dependencies": {
        "babel-core": "^6.18.2",
        "babel-plugin-transform-amd-system-wrapper": "^0.3.3",
        "babel-plugin-transform-cjs-system-wrapper": "^0.6.0",
        "babel-plugin-transform-es2015-modules-systemjs": "^6.6.5",
        "babel-plugin-transform-global-system-wrapper": "^0.3.0",
        "babel-plugin-transform-system-register": "^0.0.1",
        "bluebird": "^3.3.4",
        "data-uri-to-buffer": "0.0.4",
        "es6-template-strings": "^2.0.0",
        "glob": "^7.0.3",
        "mkdirp": "^0.5.1",
        "rollup": "^0.36.3",
        "source-map": "^0.5.3",
        "systemjs": "^0.19.46",
        "traceur": "0.0.105",
        "uglify-js": "^2.6.1"
    },
    "description": "SystemJS Build Tool",
    "devDependencies": {
        "babel": "^5.8.38",
        "chai": "^3.0.0",
        "mocha": "^2.2.5",
        "mocha-phantomjs": "4.1.0",
        "phantomjs": "2.1.7",
        "systemjs-plugin-babel": "0.0.19",
        "typescript": "1.6.2",
        "unexpected": "^9.11.0",
        "when": "^3.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "516b3451c191fa17eb598f6e0254990b9aa97432",
        "tarball": "https://registry.npmjs.org/systemjs-builder/-/systemjs-builder-0.16.4.tgz"
    },
    "gitHead": "d1e888282b24e4144d521c1780b80dfaa4d8aee5",
    "homepage": "https://github.com/systemjs/builder",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "guybedford"
        }
    ],
    "name": "systemjs-builder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/systemjs/builder.git"
    },
    "scripts": {
        "test": "mocha",
        "update-expectations": "UPDATE_EXPECTATIONS=1 mocha"
    },
    "version": "0.16.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
