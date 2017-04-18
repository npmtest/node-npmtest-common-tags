# npmtest-common-tags

#### test coverage for  [common-tags (v1.4.0)](https://github.com/declandewet/common-tags)  [![npm package](https://img.shields.io/npm/v/npmtest-common-tags.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-common-tags) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-common-tags.svg)](https://travis-ci.org/npmtest/node-npmtest-common-tags)

#### a few common utility template tags for ES2015

[![NPM](https://nodei.co/npm/common-tags.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/common-tags)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-common-tags/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-common-tags/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-common-tags/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-common-tags/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-common-tags/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-common-tags/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-common-tags/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-common-tags/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-common-tags/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-common-tags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-common-tags/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-common-tags/build/test-report.html](https://npmtest.github.io/node-npmtest-common-tags/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-common-tags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-common-tags/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-common-tags/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-common-tags/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-common-tags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-common-tags/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-common-tags/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-common-tags/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Declan de Wet"
    },
    "ava": {
        "verbose": true,
        "babel": "inherit",
        "failFast": true,
        "require": [
            "babel-register"
        ],
        "files": [
            "src/**/*.test.js"
        ]
    },
    "bugs": {
        "url": "http://github.com/declandewet/common-tags/issues"
    },
    "contributors": [
        {
            "name": "Declan de Wet",
            "url": "https://github.com/declandewet"
        },
        {
            "name": "Jason Killian",
            "url": "https://github.com/JKillian"
        },
        {
            "name": "Laurent Goudet",
            "url": "https://github.com/laurentgoudet"
        },
        {
            "name": "Kamil Ogórek",
            "url": "https://github.com/kamilogorek"
        }
    ],
    "dependencies": {
        "babel-runtime": "^6.18.0"
    },
    "description": "a few common utility template tags for ES2015",
    "devDependencies": {
        "ava": "^0.16.0",
        "babel-cli": "^6.18.0",
        "babel-eslint": "^7.1.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-runtime": "^6.8.0",
        "babel-preset-latest": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "codecov": "^1.0.1",
        "cross-env": "3.1.3",
        "doctoc": "^1.0.0",
        "micromatch": "^2.3.8",
        "nyc": "^8.3.2",
        "regenerator-runtime": "^0.9.5",
        "rimraf": "^2.5.2",
        "snazzy": "^5.0.0",
        "when": "^3.7.7",
        "which": "^1.2.11"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "1187be4f3d4cf0c0427d43f74eef1f73501614c0",
        "tarball": "https://registry.npmjs.org/common-tags/-/common-tags-1.4.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "55154e8cf6dee4aa99a6d06c1f5a52f94493d03f",
    "homepage": "https://github.com/declandewet/common-tags",
    "jsnext:main": "es",
    "keywords": [
        "array",
        "babel",
        "es2015",
        "es2015-tag",
        "es6",
        "es6-tag",
        "heredoc",
        "html",
        "indent",
        "indents",
        "line",
        "literal",
        "multi",
        "multiline",
        "normalize",
        "one",
        "oneline",
        "single",
        "singleline",
        "string",
        "strings",
        "strip",
        "tag",
        "tagged",
        "template"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "declandewet"
        }
    ],
    "module": "es",
    "name": "common-tags",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/declandewet/common-tags.git"
    },
    "scripts": {
        "build": "npm run clear && npm run build:cjs && npm run build:es",
        "build:cjs": "cross-env BABEL_ENV=cjs babel src -d lib --ignore *.test.js",
        "build:es": "cross-env BABEL_ENV=es babel src -d es --ignore *.test.js",
        "clear": "rimraf lib && rimraf es",
        "codecov": "npm run coverage && codecov",
        "coverage": "nyc report --reporter=lcov",
        "lint": "snazzy",
        "precoveralls": "npm run coverage",
        "prerelease": "npm run build",
        "preversion": "doctoc readme.md --title '# :books: Table of Contents' && npm test",
        "release": "npm publish",
        "test": "npm run lint && cross-env BABEL_ENV=cjs nyc ava",
        "test-ci": "npm run lint && cross-env BABEL_ENV=cjs nyc ava --serial --fail-fast"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "readme.md",
            "es"
        ]
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
