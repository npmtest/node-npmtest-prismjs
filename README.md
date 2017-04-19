# npmtest-prismjs

#### test coverage for  [prismjs (v1.6.0)](https://github.com/LeaVerou/prism#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-prismjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prismjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prismjs.svg)](https://travis-ci.org/npmtest/node-npmtest-prismjs)

#### Lightweight, robust, elegant syntax highlighting. A spin-off project from Dabblet.

[![NPM](https://nodei.co/npm/prismjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prismjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prismjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prismjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prismjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prismjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prismjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prismjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prismjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prismjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prismjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prismjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prismjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prismjs/build/test-report.html](https://npmtest.github.io/node-npmtest-prismjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prismjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prismjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prismjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prismjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prismjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prismjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prismjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prismjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lea Verou"
    },
    "bugs": {
        "url": "https://github.com/LeaVerou/prism/issues"
    },
    "dependencies": {
        "clipboard": "^1.5.5"
    },
    "description": "Lightweight, robust, elegant syntax highlighting. A spin-off project from Dabblet.",
    "devDependencies": {
        "chai": "^2.3.0",
        "gulp": "^3.8.6",
        "gulp-concat": "^2.3.4",
        "gulp-header": "^1.0.5",
        "gulp-rename": "^1.2.0",
        "gulp-replace": "^0.5.4",
        "gulp-uglify": "^0.3.1",
        "mocha": "^2.2.5",
        "yargs": "^3.26.0"
    },
    "directories": {},
    "dist": {
        "shasum": "118d95fb7a66dba2272e343b345f5236659db365",
        "tarball": "https://registry.npmjs.org/prismjs/-/prismjs-1.6.0.tgz"
    },
    "gitHead": "4fa29a9fb9dbad25c5fc97f0e551206a5bde79c6",
    "homepage": "https://github.com/LeaVerou/prism#readme",
    "jspm": {
        "main": "prism",
        "registry": "jspm",
        "jspmPackage": true,
        "format": "global",
        "files": [
            "components/**/*.min.js",
            "plugins/**/*",
            "themes/*.css",
            "prism.js"
        ]
    },
    "keywords": [
        "prism",
        "highlight"
    ],
    "license": "MIT",
    "main": "prism.js",
    "maintainers": [
        {
            "name": "charleshansen"
        },
        {
            "name": "leaverou"
        },
        {
            "name": "rdy"
        },
        {
            "name": "vinsonchuong"
        },
        {
            "name": "stubbornella"
        },
        {
            "name": "gpleiss"
        }
    ],
    "name": "prismjs",
    "optionalDependencies": {
        "clipboard": "^1.5.5"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/LeaVerou/prism.git"
    },
    "scripts": {
        "test": "mocha tests/testrunner-tests.js && mocha tests/run.js"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
