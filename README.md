# npmdoc-denodeify

#### api documentation for  [denodeify (v1.2.1)](https://github.com/matthew-andrews/denodeify)  [![npm package](https://img.shields.io/npm/v/npmdoc-denodeify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-denodeify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-denodeify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-denodeify)

#### Tool to turn functions with Node-style callback APIs into functions that return Promises

[![NPM](https://nodei.co/npm/denodeify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/denodeify)

- [https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-denodeify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-denodeify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-denodeify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Andrews"
    },
    "bugs": {
        "url": "https://github.com/matthew-andrews/denodeify/issues"
    },
    "dependencies": {},
    "description": "Tool to turn functions with Node-style callback APIs into functions that return Promises",
    "devDependencies": {
        "es6-promise": "^1.0.0",
        "es6-shim": "^0.18.0",
        "jshint": "^2.5.5",
        "lie": "^2.7.7",
        "lintspaces-cli": "0.0.4",
        "mocha": "^1.21.4",
        "native-promise-only": "^0.7.6-a"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "3a36287f5034e699e7577901052c2e6c94251631",
        "tarball": "https://registry.npmjs.org/denodeify/-/denodeify-1.2.1.tgz"
    },
    "gitHead": "e500054eb336c748264507e9553af949981ee2c3",
    "homepage": "https://github.com/matthew-andrews/denodeify",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mattandrews"
        }
    ],
    "name": "denodeify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matthew-andrews/denodeify.git"
    },
    "scripts": {
        "files": "find . -name '*.js' ! -path './node_modules/*'",
        "jshint": "jshint 'npm run -s files'",
        "lintspaces": "lintspaces -i js-comments -e .editorconfig 'npm run -s files'",
        "test": "mocha test/*test.js && npm run jshint && npm run lintspaces"
    },
    "version": "1.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
