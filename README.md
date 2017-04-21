# npmdoc-meld

#### api documentation for  [meld (v1.3.2)](http://cujojs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-meld.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-meld) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-meld.svg)](https://travis-ci.org/npmdoc/node-npmdoc-meld)

#### AOP for JS with before, around, on, afterReturning, afterThrowing, after advice, and pointcut support

[![NPM](https://nodei.co/npm/meld.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/meld)

- [https://npmdoc.github.io/node-npmdoc-meld/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-meld/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-meld/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-meld/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-meld/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-meld/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "meld",
    "version": "1.3.2",
    "description": "AOP for JS with before, around, on, afterReturning, afterThrowing, after advice, and pointcut support",
    "keywords": [
        "aop",
        "aspect",
        "cujo"
    ],
    "homepage": "http://cujojs.com",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/cujojs/meld"
    },
    "bugs": "https://github.com/cujojs/meld/issues",
    "maintainers": [
        {
            "name": "Brian Cavalier",
            "web": "http://hovercraftstudios.com"
        },
        {
            "name": "John Hann",
            "web": "http://unscriptable.com"
        }
    ],
    "contributors": [
        {
            "name": "Brian Cavalier",
            "web": "http://hovercraftstudios.com"
        },
        {
            "name": "John Hann",
            "web": "http://unscriptable.com"
        },
        {
            "name": "Scott Andrews"
        }
    ],
    "devDependencies": {
        "buster": "~0.7",
        "jshint": "~2"
    },
    "main": "meld",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "jshint . && buster-test -e node"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
