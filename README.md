# npmtest-parsleyjs

#### basic test coverage for  [parsleyjs (v2.7.0)](https://github.com/guillaumepotier/Parsley.js)  [![npm package](https://img.shields.io/npm/v/npmtest-parsleyjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parsleyjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parsleyjs.svg)](https://travis-ci.org/npmtest/node-npmtest-parsleyjs)

#### Validate your forms, frontend, without writing a single line of javascript!

[![NPM](https://nodei.co/npm/parsleyjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parsleyjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parsleyjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parsleyjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parsleyjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parsleyjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parsleyjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parsleyjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parsleyjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parsleyjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parsleyjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parsleyjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parsleyjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parsleyjs/build/test-report.html](https://npmtest.github.io/node-npmtest-parsleyjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parsleyjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parsleyjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parsleyjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parsleyjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parsleyjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parsleyjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parsleyjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parsleyjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "parsleyjs",
    "version": "2.7.0",
    "homepage": "https://github.com/guillaumepotier/Parsley.js",
    "license": "MIT",
    "description": "Validate your forms, frontend, without writing a single line of javascript!",
    "main": "dist/parsley.js",
    "scripts": {
        "test": "gulp",
        "test-browser": "gulp test-browser",
        "build": "gulp build",
        "coverage": "gulp coverage"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/guillaumepotier/Parsley.js.git"
    },
    "keywords": [
        "parsley",
        "form",
        "validation",
        "html5",
        "polyfill",
        "es6"
    ],
    "author": {
        "name": "Guillaume Potier",
        "url": "http://guillaumepotier.com/"
    },
    "bugs": {
        "url": "https://github.com/guillaumepotier/Parsley.js/issues"
    },
    "dependencies": {
        "jquery": ">=1.8.0"
    },
    "devDependencies": {
        "babel-core": "^5.2.17",
        "babel-eslint": "^4.0.5",
        "babelify": "^6.0.0",
        "browserify": "^11.0.1",
        "expect.js": "*",
        "del": "^1.1.1",
        "esperanto": "^0.7.4",
        "glob": "^5.0.14",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.0.0",
        "docco": "~0.6.3",
        "gulp-eslint": "^1.0.0",
        "gulp-file": "^0.2.0",
        "gulp-filter": "^3.0.0",
        "gulp-header": "*",
        "gulp-istanbul": "^0.10.0",
        "gulp-jscs": "^2.0.0",
        "gulp-livereload": "^3.4.0",
        "gulp-load-plugins": "^0.10.0",
        "gulp-mocha": "^2.0.0",
        "gulp-notify": "^2.1.0",
        "gulp-plumber": "^1.0.1",
        "gulp-rename": "^1.2.0",
        "gulp-replace": "*",
        "gulp-sourcemaps": "^1.3.0",
        "gulp-uglify": "^1.2.0",
        "gulp-git": "^1.7.0",
        "inputevent": "*",
        "isparta": "~3.0.3",
        "mocha": "^2.1.0",
        "moment": "*",
        "run-sequence": "^1.0.2",
        "jsdom": "^9.2",
        "sinon": "^1.12.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.0.0",
        "watchify": "^3.3.1"
    },
    "babelBoilerplateOptions": {
        "entryFileName": "parsley",
        "mainVarName": "parsley",
        "mochaGlobals": [
            "$",
            "stub",
            "spy",
            "expect",
            "expectWarning"
        ]
    },
    "spm": {
        "main": "dist/parsley.js",
        "ignore": [
            "doc",
            "test",
            "src"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
