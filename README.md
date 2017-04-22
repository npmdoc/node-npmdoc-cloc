# npmdoc-cloc

#### api documentation for  [cloc (v2.2.0)](https://github.com/kentcdodds/cloc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cloc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cloc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cloc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cloc)

#### An npm module for distributing cloc by Al Danial http://cloc.sourceforge.net/

[![NPM](https://nodei.co/npm/cloc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloc)

- [https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cloc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cloc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cloc",
    "version": "2.2.0",
    "description": "An npm module for distributing cloc by Al Danial http://cloc.sourceforge.net/",
    "main": "lib/cloc",
    "scripts": {
        "test": "echo \"Error: no test specified\"",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post"
    },
    "bin": {
        "cloc": "lib/cloc"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/kentcdodds/cloc.git"
    },
    "keywords": [
        "cloc",
        "count lines of code",
        "lines of code",
        "loc"
    ],
    "author": "Kent C. Dodds <kent@doddsfamily.us> (http://kentcdodds.com)",
    "license": "GPL-2.0",
    "bugs": {
        "url": "https://github.com/kentcdodds/cloc/issues"
    },
    "homepage": "https://github.com/kentcdodds/cloc#readme",
    "devDependencies": {
        "semantic-release": "^6.3.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
