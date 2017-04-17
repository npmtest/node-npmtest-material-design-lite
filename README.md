# test coverage for  [material-design-lite (v1.3.0)](https://github.com/google/material-design-lite#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-material-design-lite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-material-design-lite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-material-design-lite.svg)](https://travis-ci.org/npmtest/node-npmtest-material-design-lite)
#### Material Design Components in CSS, JS and HTML

[![NPM](https://nodei.co/npm/material-design-lite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/material-design-lite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-material-design-lite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-material-design-lite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-material-design-lite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-material-design-lite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-material-design-lite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-material-design-lite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-material-design-lite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-material-design-lite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-material-design-lite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-material-design-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-material-design-lite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-material-design-lite/build/test-report.html](https://npmtest.github.io/node-npmtest-material-design-lite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-material-design-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-material-design-lite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-material-design-lite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-material-design-lite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-material-design-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-material-design-lite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-material-design-lite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-material-design-lite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Google"
    },
    "babel": {
        "only": "gulpfile.babel.js",
        "presets": [
            "es2015"
        ]
    },
    "bugs": {
        "url": "https://github.com/google/material-design-lite/issues"
    },
    "dependencies": {},
    "description": "Material Design Components in CSS, JS and HTML",
    "devDependencies": {
        "acorn": "^4.0.3",
        "babel-core": "^6.20.0",
        "babel-preset-es2015": "^6.18.0",
        "browser-sync": "^2.2.3",
        "chai": "^3.3.0",
        "chai-jquery": "^2.0.0",
        "del": "^2.0.2",
        "drool": "^0.4.0",
        "escodegen": "^1.6.1",
        "google-closure-compiler": "",
        "gulp": "^3.9.0",
        "gulp-autoprefixer": "^3.0.2",
        "gulp-cache": "^0.4.5",
        "gulp-closure-compiler": "^0.4.0",
        "gulp-concat": "^2.4.1",
        "gulp-connect": "^5.0.0",
        "gulp-css-inline-images": "^0.1.1",
        "gulp-csso": "1.0.0",
        "gulp-file": "^0.3.0",
        "gulp-flatten": "^0.3.1",
        "gulp-front-matter": "^1.2.2",
        "gulp-header": "^1.2.2",
        "gulp-if": "^2.0.0",
        "gulp-iife": "^0.3.0",
        "gulp-imagemin": "^3.1.0",
        "gulp-jscs": "^4.0.0",
        "gulp-jshint": "^2.0.4",
        "gulp-load-plugins": "^1.3.0",
        "gulp-marked": "^1.0.0",
        "gulp-mocha-phantomjs": "^0.12.0",
        "gulp-open": "^2.0.0",
        "gulp-rename": "^1.2.0",
        "gulp-replace": "^0.5.3",
        "gulp-sass": "3.0.0",
        "gulp-shell": "^0.5.2",
        "gulp-size": "^2.0.0",
        "gulp-sourcemaps": "^2.0.1",
        "gulp-subtree": "^0.1.0",
        "gulp-tap": "^0.1.3",
        "gulp-uglify": "^2.0.0",
        "gulp-util": "^3.0.4",
        "gulp-zip": "^3.0.2",
        "humanize": "0.0.9",
        "jquery": "^3.1.1",
        "jshint": "^2.9.4",
        "jshint-stylish": "^2.2.1",
        "merge-stream": "^1.0.0",
        "mocha": "^3.0.2",
        "prismjs": "0.0.1",
        "run-sequence": "^1.0.2",
        "swig": "^1.4.2",
        "through2": "^2.0.0",
        "vinyl-paths": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d004ce3fee99a1eeb74a78b8a325134a5f1171d3",
        "tarball": "https://registry.npmjs.org/material-design-lite/-/material-design-lite-1.3.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "17a19f0a677b26e2b7f1ce1e09dd58270e0558e3",
    "homepage": "https://github.com/google/material-design-lite#readme",
    "license": "Apache-2.0",
    "main": "dist/material.min.js",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "surma"
        },
        {
            "name": "sgomes"
        }
    ],
    "name": "material-design-lite",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/material-design-lite.git"
    },
    "scripts": {
        "test": "gulp && git status | grep 'working directory clean' >/dev/null || (echo 'Please commit all changes generated by building'; exit 1)"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
