# test coverage for  [angular2-logger (v0.5.1)](https://github.com/code-chunks/angular2-logger#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-logger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-logger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-logger.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-logger)
#### A Log4j inspired Logger for Angular 2.

[![NPM](https://nodei.co/npm/angular2-logger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-logger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-logger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-logger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-logger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-logger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-logger/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-logger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-logger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-logger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-logger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-logger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-logger/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-logger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-logger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-logger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-logger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-logger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-logger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-logger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Armando Garcia Moran"
    },
    "bugs": {
        "url": "https://github.com/code-chunks/angular2-logger/issues"
    },
    "contributors": [
        {
            "name": "Armando Garcia"
        },
        {
            "name": "Juan Hernandez"
        }
    ],
    "dependencies": {},
    "description": "A Log4j inspired Logger for Angular 2.",
    "devDependencies": {
        "@angular/common": "^2.0.0",
        "@angular/compiler": "^2.0.0",
        "@angular/core": "^2.0.0",
        "@angular/platform-browser": "^2.0.0",
        "@angular/platform-browser-dynamic": "^2.0.0",
        "core-js": "^2.4.1",
        "reflect-metadata": "^0.1.3",
        "rimraf": "^2.5.2",
        "rxjs": "5.0.0-beta.12",
        "systemjs": "0.19.41",
        "tslint": "^4.0.2",
        "typescript": "^2.0.2",
        "typings": "^2.0.0",
        "uglify-js": "^2.6.2",
        "zone.js": "^0.6.23"
    },
    "directories": {},
    "dist": {
        "shasum": "0e2d8b7a850270036667a18d10c7d7b31500730d",
        "tarball": "https://registry.npmjs.org/angular2-logger/-/angular2-logger-0.5.1.tgz"
    },
    "gitHead": "0c160d06f826babfb3ef6d7bc8cb246afdd4d450",
    "homepage": "https://github.com/code-chunks/angular2-logger#readme",
    "keywords": [
        "log",
        "angular2",
        "logger",
        "angular 2",
        "angular2-logger",
        "console",
        "ng2",
        "logging",
        "logmanager",
        "log manager",
        "debug",
        "trace",
        "error",
        "info",
        "warn",
        "warning",
        "fatal",
        "log4j",
        "log4ng",
        "log4js",
        "typescript",
        "ng",
        "angular"
    ],
    "license": "MIT",
    "main": "core.js",
    "maintainers": [
        {
            "name": "langley"
        },
        {
            "name": "mech543"
        }
    ],
    "name": "angular2-logger",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/common": "^2.0.0",
        "@angular/compiler": "^2.0.0",
        "@angular/core": "^2.0.0",
        "@angular/platform-browser": "^2.0.0",
        "@angular/platform-browser-dynamic": "^2.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/code-chunks/angular2-logger.git"
    },
    "scripts": {
        "build": "npm run minify",
        "clean": "rimraf *.js *.map app/**/*.js app/**/*.map app/**/*.d.ts demos/*/app**/*.js demos/*/app/*.map demos/*/app/*.d.ts dist bundles",
        "compile": "npm run compile:es5 && npm run compile:sys && npm run compile:es6",
        "compile:amd": "tsc -p tsconfig-amd.json",
        "compile:es2015": "tsc -p tsconfig-es2015.json",
        "compile:es5": "tsc -p tsconfig-es5.json",
        "compile:es6": "tsc -p tsconfig-es6.json",
        "compile:sys": "tsc -p tsconfig-sys.json",
        "lint": "npm run tslint",
        "minify": "uglifyjs -o bundles/angular2-logger.sys.min.js bundles/angular2-logger.sys.js",
        "postbuild": "echo Build Successful.",
        "prebuild": "npm run clean && npm run compile && npm run test",
        "precompile": "typings install",
        "prepublish": "npm run build",
        "pretest": "npm run lint",
        "test": "echo tests pending...",
        "tsc": "tsc",
        "tslint": "tslint *.ts src/**/*.ts",
        "typings": "typings",
        "uglifyjs": "uglifyjs"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
