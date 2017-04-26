# npmdoc-backblaze-b2

#### basic api documentation for  [backblaze-b2 (v1.0.2)](https://github.com/yakovkhalinsky/backblaze-b2)  [![npm package](https://img.shields.io/npm/v/npmdoc-backblaze-b2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-backblaze-b2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-backblaze-b2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-backblaze-b2)

#### Node.js Library for the Backblaze B2 Storage Service

[![NPM](https://nodei.co/npm/backblaze-b2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/backblaze-b2)

- [https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-backblaze-b2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yakov Khalinsky"
    },
    "bugs": {
        "url": "https://github.com/yakovkhalinsky/backblaze-b2/issues"
    },
    "dependencies": {
        "axios": "^0.16.1",
        "q": "^1.4.1",
        "sha1": "^1.1.0"
    },
    "description": "Node.js Library for the Backblaze B2 Storage Service",
    "devDependencies": {
        "eslint": "^3.17.1",
        "expect.js": "^0.3.1",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e43b07082fcb8f252552d25c9231137df54fef04",
        "tarball": "https://registry.npmjs.org/backblaze-b2/-/backblaze-b2-1.0.2.tgz"
    },
    "gitHead": "136d66f0f4a7e227ceb57475b3a0717d2cd0a8be",
    "homepage": "https://github.com/yakovkhalinsky/backblaze-b2",
    "keywords": [
        "backblaze",
        "b2",
        "storage"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "russianator"
        }
    ],
    "name": "backblaze-b2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yakovkhalinsky/backblaze-b2.git"
    },
    "scripts": {
        "lint-all": "npm run lint-lib && npm run lint-test",
        "lint-lib": "eslint \"lib/**/*.js\"",
        "lint-test": "eslint \"test/**/*.js\" --global describe,it,beforeEach",
        "test": "npm run lint-all && npm run test-unit",
        "test-unit": "mocha \"test/**/*Test.js\""
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
