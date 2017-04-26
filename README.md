# npmdoc-heapdump

#### basic api documentation for  [heapdump (v0.3.9)](https://github.com/bnoordhuis/node-heapdump)  [![npm package](https://img.shields.io/npm/v/npmdoc-heapdump.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-heapdump) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-heapdump.svg)](https://travis-ci.org/npmdoc/node-npmdoc-heapdump)

#### Make a dump of the V8 heap for later inspection.

[![NPM](https://nodei.co/npm/heapdump.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/heapdump)

- [https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-heapdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-heapdump/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-heapdump/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Noordhuis",
        "url": "http://bnoordhuis.nl/"
    },
    "bugs": {
        "url": "https://github.com/bnoordhuis/node-heapdump/issues"
    },
    "dependencies": {},
    "description": "Make a dump of the V8 heap for later inspection.",
    "devDependencies": {
        "shelljs": "~0.3.0",
        "tap": "~0.4.12"
    },
    "directories": {},
    "dist": {
        "shasum": "03c74eb0df5d67be0982e83429ba9c9d2b3b7f78",
        "tarball": "https://registry.npmjs.org/heapdump/-/heapdump-0.3.9.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "7cf17e9b2a629fa5708717874ced2a7ae6cb2e13",
    "gypfile": true,
    "homepage": "https://github.com/bnoordhuis/node-heapdump",
    "license": "ISC",
    "main": "./lib/main",
    "maintainers": [
        {
            "name": "bnoordhuis"
        }
    ],
    "name": "heapdump",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bnoordhuis/node-heapdump.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "tap test/test-*"
    },
    "version": "0.3.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
