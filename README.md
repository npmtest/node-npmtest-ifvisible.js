# npmtest-ifvisible.js

#### basic test coverage for  [ifvisible.js (v1.0.6)](https://github.com/serkanyersen/ifvisible.js)  [![npm package](https://img.shields.io/npm/v/npmtest-ifvisible.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ifvisible.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ifvisible.js.svg)](https://travis-ci.org/npmtest/node-npmtest-ifvisible.js)

#### Crossbrowser & lightweight way to check if user is looking at the page or interacting with it. (wrapper around HTML5 visibility api)

[![NPM](https://nodei.co/npm/ifvisible.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ifvisible.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ifvisible.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ifvisible.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ifvisible.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ifvisible.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ifvisible.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ifvisible.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ifvisible.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ifvisible.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ifvisible.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ifvisible.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ifvisible.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ifvisible.js/build/test-report.html](https://npmtest.github.io/node-npmtest-ifvisible.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ifvisible.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ifvisible.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ifvisible.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ifvisible.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ifvisible.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ifvisible.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ifvisible.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ifvisible.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ifvisible.js",
    "version": "1.0.6",
    "description": "Crossbrowser & lightweight way to check if user is looking at the page or interacting with it. (wrapper around HTML5 visibility api)",
    "main": "src/ifvisible.js",
    "directories": {
        "doc": "docs",
        "test": "tests"
    },
    "scripts": {
        "test": "node tests/tests.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/serkanyersen/ifvisible.js.git"
    },
    "typescript": {
        "definition": "ifvisible.d.ts"
    },
    "keywords": [
        "visibility",
        "HTML5",
        "cross",
        "browser",
        "api",
        "UI",
        "idle",
        "status",
        "mousemove",
        "reading",
        "mode",
        "tab",
        "change"
    ],
    "author": "Serkan Yersen <serkanyersen@gmail.com> (http://serkan.io/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/serkanyersen/ifvisible.js/issues"
    },
    "homepage": "https://github.com/serkanyersen/ifvisible.js",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-contrib-uglify": "^0.9.1",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-docco": "^0.3.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
