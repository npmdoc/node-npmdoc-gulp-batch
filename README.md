# npmdoc-gulp-batch

#### api documentation for  gulp-batch (v1.0.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-batch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-batch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-batch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-batch)

#### Event batcher for gulp-watcher

[![NPM](https://nodei.co/npm/gulp-batch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-batch)

- [https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-batch",
    "version": "1.0.5",
    "description": "Event batcher for gulp-watcher",
    "main": "index.js",
    "keywords": [
        "gulp",
        "batch",
        "throttle",
        "debounce",
        "gulpfriendly",
        "watch",
        "mocha"
    ],
    "scripts": {
        "test": "istanbul cover _mocha -- test/*.js --reporter spec",
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/floatdrop/gulp-batch.git"
    },
    "author": "Vsevolod Strukchinsky",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/floatdrop/gulp-batch/issues"
    },
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.5",
        "mocha": "^2.0.1",
        "mocha-lcov-reporter": "0.0.1",
        "should": "^4.3.1",
        "stream-assert": "^2.0.2"
    },
    "dependencies": {
        "async-done": "^1.0.0",
        "stream-array": "^1.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
