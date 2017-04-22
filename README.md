# npmtest-ng2-datepicker

#### basic test coverage for  [ng2-datepicker (v1.8.3)](https://github.com/jkuri/ng2-datepicker#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ng2-datepicker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng2-datepicker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng2-datepicker.svg)](https://travis-ci.org/npmtest/node-npmtest-ng2-datepicker)

####

[![NPM](https://nodei.co/npm/ng2-datepicker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-datepicker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng2-datepicker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng2-datepicker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng2-datepicker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng2-datepicker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng2-datepicker/build/test-report.html](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng2-datepicker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-datepicker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-datepicker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng2-datepicker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng2-datepicker",
    "version": "1.8.3",
    "license": "MIT",
    "scripts": {
        "ng": "ng",
        "start": "ng serve",
        "build": "npm run css && ./node_modules/.bin/ngc -p tsconfig.build.json && rollup -c",
        "build:cli": "ng build --aot",
        "build:lib": "nglb --rootDir src/ng2-datepicker --outDir lib-dist",
        "test": "ng test",
        "lint": "ng lint",
        "e2e": "ng e2e",
        "clean": "rimraf node_modules dist dist-lib",
        "clean:install": "npm run clean && npm install",
        "prepublish": "npm run build:lib"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jkuri/ng2-datepicker.git"
    },
    "keywords": [
        "angular",
        "angular2",
        "angular4",
        "ng2",
        "ng4",
        "ngx",
        "datepicker",
        "date",
        "component"
    ],
    "author": "Jan Kuri <jkuri88@gmail.com>",
    "bugs": {
        "url": "https://github.com/jkuri/ng2-datepicker/issues"
    },
    "homepage": "https://github.com/jkuri/ng2-datepicker#readme",
    "main": "./lib-dist/ng2-datepicker.module.js",
    "module": "./lib-dist/ng2-datepicker.module.js",
    "types": "./lib-dist/ng2-datepicker.module.d.ts",
    "peerDependencies": {
        "@angular/common": ">=2.0.0 <5.0.0 || >=4.0.0-beta <5.0.0",
        "@angular/core": ">=2.0.0 <5.0.0 || >=4.0.0-beta <5.0.0",
        "@angular/forms": "^2.4.0",
        "rxjs": ">=5.0.0 || >=5.0.0-beta",
        "zone.js": ">=0.7.0"
    },
    "dependencies": {
        "moment": "^2.17.1",
        "ng2-slimscroll": "^1.2.6"
    },
    "devDependencies": {
        "@angular/cli": "1.0.0-rc.0",
        "@angular/common": "^2.4.0",
        "@angular/compiler": "^2.4.0",
        "@angular/compiler-cli": "^2.4.0",
        "@angular/core": "^2.4.0",
        "@angular/forms": "^2.4.0",
        "@angular/http": "^2.4.0",
        "@angular/platform-browser": "^2.4.0",
        "@angular/platform-browser-dynamic": "^2.4.0",
        "@angular/router": "^3.4.0",
        "@types/jasmine": "2.5.38",
        "@types/node": "~6.0.60",
        "angular-library-builder": "^1.3.1",
        "bulma": "^0.3.2",
        "codelyzer": "~2.0.0",
        "core-js": "^2.4.1",
        "jasmine-core": "~2.5.2",
        "jasmine-spec-reporter": "~3.2.0",
        "karma": "~1.4.1",
        "karma-chrome-launcher": "~2.0.0",
        "karma-cli": "~1.0.1",
        "karma-coverage-istanbul-reporter": "^0.2.0",
        "karma-jasmine": "~1.1.0",
        "karma-jasmine-html-reporter": "^0.2.2",
        "protractor": "~5.1.0",
        "rimraf": "^2.6.1",
        "rxjs": "^5.1.0",
        "ts-node": "~2.0.0",
        "tslint": "~4.4.2",
        "typescript": "~2.0.0",
        "zone.js": "^0.7.6"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
