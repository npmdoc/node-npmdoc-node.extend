# api documentation for  [node.extend (v1.1.6)](https://github.com/dreamerslab/node.extend#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node.extend.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node.extend) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node.extend.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node.extend)
#### A port of jQuery.extend that actually works on node.js

[![NPM](https://nodei.co/npm/node.extend.png?downloads=true)](https://www.npmjs.com/package/node.extend)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node.extend/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node.extend_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node.extend/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node.extend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node.extend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dreamerslab",
        "email": "ben@dreamerslab.com"
    },
    "bugs": {
        "url": "https://github.com/dreamerslab/node.extend/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband"
        }
    ],
    "dependencies": {
        "is": "^3.1.0"
    },
    "description": "A port of jQuery.extend that actually works on node.js",
    "devDependencies": {
        "@ljharb/eslint-config": "^8.0.0",
        "covert": "^1.1.0",
        "eslint": "^3.4.0",
        "jscs": "^3.0.7",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a7b882c82d6c93a4863a5504bd5de8ec86258b96",
        "tarball": "https://registry.npmjs.org/node.extend/-/node.extend-1.1.6.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "c4131c74acef44f9ed0f9c30b10bdf496731f15f",
    "homepage": "https://github.com/dreamerslab/node.extend#readme",
    "keywords": [
        "extend",
        "jQuery",
        "jQuery extend",
        "clone",
        "copy",
        "inherit"
    ],
    "license": "(MIT OR GPL-2.0)",
    "main": "index",
    "maintainers": [
        {
            "name": "dreamerslab",
            "email": "ben@dreamerslab.com"
        },
        {
            "name": "ljharb",
            "email": "ljharb@gmail.com"
        }
    ],
    "name": "node.extend",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dreamerslab/node.extend.git"
    },
    "scripts": {
        "coverage": "covert test/index.js",
        "coverage-quiet": "covert test/index.js --quiet",
        "eslint": "eslint *.js */*.js",
        "jscs": "jscs *.js */*.js",
        "lint": "npm run jscs && npm run eslint",
        "posttest": "npm run coverage-quiet",
        "pretest": "npm run lint",
        "test": "npm run --silent tests-only",
        "tests-only": "node test"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "iexplore/6.0..latest",
            "firefox/3.0..6.0",
            "firefox/15.0..latest",
            "firefox/nightly",
            "chrome/4.0..10.0",
            "chrome/20.0..latest",
            "chrome/canary",
            "opera/10.0..latest",
            "opera/next",
            "safari/4.0..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest"
        ]
    },
    "version": "1.1.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node.extend](#apidoc.module.node.extend)
1.  string <span class="apidocSignatureSpan">node.extend.</span>version



# <a name="apidoc.module.node.extend"></a>[module node.extend](#apidoc.module.node.extend)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
