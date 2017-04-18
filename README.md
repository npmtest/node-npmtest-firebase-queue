# npmtest-firebase-queue

#### test coverage for  [firebase-queue (v1.6.1)](https://github.com/firebase/firebase-queue)  [![npm package](https://img.shields.io/npm/v/npmtest-firebase-queue.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-firebase-queue) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-firebase-queue.svg)](https://travis-ci.org/npmtest/node-npmtest-firebase-queue)

#### A fault-tolerant, multi-worker, multi-stage job pipeline built on Firebase

[![NPM](https://nodei.co/npm/firebase-queue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/firebase-queue)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-firebase-queue/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-queue/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-queue/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-firebase-queue/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-queue/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-firebase-queue/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-firebase-queue/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-firebase-queue/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-firebase-queue/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-firebase-queue/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-firebase-queue/build/test-report.html](https://npmtest.github.io/node-npmtest-firebase-queue/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-firebase-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-firebase-queue/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-firebase-queue/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-firebase-queue/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-firebase-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-firebase-queue/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-firebase-queue/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-firebase-queue/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Firebase",
        "url": "https://firebase.google.com/"
    },
    "bugs": {
        "url": "https://github.com/firebase/firebase-queue/issues"
    },
    "dependencies": {
        "lodash": "^4.6.1",
        "rsvp": "^3.2.1",
        "uuid": "^3.0.0",
        "winston": "^2.2.0"
    },
    "description": "A fault-tolerant, multi-worker, multi-stage job pipeline built on Firebase",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "coveralls": "^2.11.8",
        "firebase-admin": "^4.0.3",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-exit": "^0.0.2",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "sinon": "^1.17.3",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fe13c72c274b4f7bfad33997409202a3ed20dc06",
        "tarball": "https://registry.npmjs.org/firebase-queue/-/firebase-queue-1.6.1.tgz"
    },
    "files": [
        "dist/lib/**",
        "dist/queue.js",
        "LICENSE",
        "README.md",
        "package.json"
    ],
    "gitHead": "4ffbdf28c7f781dfcb19e61cb2a5bd254b95e84e",
    "homepage": "https://github.com/firebase/firebase-queue",
    "keywords": [
        "job",
        "task",
        "queue",
        "worker",
        "firebase",
        "realtime",
        "pipeline"
    ],
    "license": "MIT",
    "main": "dist/queue.js",
    "maintainers": [
        {
            "name": "firebase"
        }
    ],
    "name": "firebase-queue",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/firebase/firebase-queue.git"
    },
    "scripts": {
        "test": "gulp test",
        "travis": "gulp"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
