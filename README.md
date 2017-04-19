# npmtest-plato

#### basic test coverage for  [plato (v1.7.0)](https://github.com/es-analysis/plato)  [![npm package](https://img.shields.io/npm/v/npmtest-plato.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-plato) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-plato.svg)](https://travis-ci.org/npmtest/node-npmtest-plato)

#### JavaScript source analysis and visualizer

[![NPM](https://nodei.co/npm/plato.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/plato)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-plato/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-plato/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-plato/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-plato/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-plato/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-plato/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-plato/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-plato/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-plato/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-plato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-plato/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-plato/build/test-report.html](https://npmtest.github.io/node-npmtest-plato/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-plato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-plato/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-plato/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-plato/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-plato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-plato/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-plato/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-plato/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jarrod Overson",
        "url": "http://jarrodoverson.com/"
    },
    "bin": {
        "plato": "bin/plato"
    },
    "bugs": {
        "url": "https://github.com/es-analysis/plato/issues"
    },
    "dependencies": {
        "eslint": "~3.0.1",
        "fs-extra": "~0.30.0",
        "glob": "~7.0.5",
        "jshint": "~2.9.2",
        "lodash": "~4.13.1",
        "posix-getopt": "~1.2.0",
        "typhonjs-escomplex": "0.0.9"
    },
    "description": "JavaScript source analysis and visualizer",
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-casper": "~0.4.0",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "grunt-contrib-uglify": "~1.0.1",
        "grunt-contrib-watch": "~1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9900a5b4910aa190de08a45bae6175334fd646a7",
        "tarball": "https://registry.npmjs.org/plato/-/plato-1.7.0.tgz"
    },
    "engines": {
        "node": ">= 4.4.5"
    },
    "gitHead": "90bf26e285a364c6fc11e80cd04698f84eb3d111",
    "homepage": "https://github.com/es-analysis/plato",
    "keywords": [
        "halstead",
        "visualize",
        "cyclomatic",
        "complexity",
        "report",
        "analysis",
        "analyze"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/es-analysis/plato/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/plato",
    "maintainers": [
        {
            "name": "jsoverson"
        },
        {
            "name": "there4"
        }
    ],
    "name": "plato",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/es-analysis/plato.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
