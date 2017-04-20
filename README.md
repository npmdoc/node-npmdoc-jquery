# npmdoc-jquery

#### api documentation for  [jquery (v3.2.1)](https://jquery.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-jquery.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jquery) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jquery.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jquery)

#### JavaScript library for DOM operations

[![NPM](https://nodei.co/npm/jquery.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jquery)

- [https://npmdoc.github.io/node-npmdoc-jquery/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jquery/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jquery/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jquery/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jquery/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jquery/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jquery",
    "title": "jQuery",
    "description": "JavaScript library for DOM operations",
    "version": "3.2.1",
    "main": "dist/jquery.js",
    "homepage": "https://jquery.com",
    "author": {
        "name": "JS Foundation and other contributors",
        "url": "https://github.com/jquery/jquery/blob/3.2.1/AUTHORS.txt"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jquery/jquery.git"
    },
    "keywords": [
        "jquery",
        "javascript",
        "browser",
        "library"
    ],
    "bugs": {
        "url": "https://github.com/jquery/jquery/issues"
    },
    "license": "MIT",
    "dependencies": {},
    "devDependencies": {
        "babel-preset-es2015": "6.6.0",
        "commitplease": "2.6.1",
        "core-js": "2.2.2",
        "cross-spawn": "2.2.3",
        "eslint-config-jquery": "1.0.0",
        "grunt": "1.0.1",
        "grunt-babel": "6.0.0",
        "grunt-cli": "1.2.0",
        "grunt-compare-size": "0.4.2",
        "grunt-contrib-uglify": "1.0.1",
        "grunt-contrib-watch": "1.0.0",
        "grunt-eslint": "19.0.0",
        "grunt-git-authors": "3.2.0",
        "grunt-jsonlint": "1.0.7",
        "grunt-newer": "1.2.0",
        "grunt-npmcopy": "0.1.0",
        "gzip-js": "0.3.2",
        "husky": "0.11.4",
        "insight": "0.8.1",
        "jsdom": "5.6.1",
        "load-grunt-tasks": "3.5.0",
        "native-promise-only": "0.8.1",
        "promises-aplus-tests": "2.1.2",
        "q": "1.4.1",
        "qunit-assert-step": "1.0.3",
        "qunitjs": "1.23.1",
        "requirejs": "2.2.0",
        "sinon": "1.17.3",
        "sizzle": "2.3.3",
        "strip-json-comments": "2.0.1",
        "testswarm": "1.1.0"
    },
    "scripts": {
        "build": "npm install && grunt",
        "start": "grunt watch",
        "test": "grunt && grunt test:slow",
        "precommit": "grunt lint:newer",
        "commitmsg": "node node_modules/commitplease"
    },
    "commitplease": {
        "nohook": true,
        "components": [
            "Docs",
            "Tests",
            "Build",
            "Support",
            "Release",
            "Core",
            "Ajax",
            "Attributes",
            "Callbacks",
            "CSS",
            "Data",
            "Deferred",
            "Deprecated",
            "Dimensions",
            "Effects",
            "Event",
            "Manipulation",
            "Offset",
            "Queue",
            "Selector",
            "Serialize",
            "Traversing",
            "Wrap"
        ],
        "markerPattern": "^((clos|fix|resolv)(e[sd]|ing))|^(refs?)",
        "ticketPattern": "^((Closes|Fixes) ([a-zA-Z]{2,}-)[0-9]+)|^(Refs? [^#])"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
