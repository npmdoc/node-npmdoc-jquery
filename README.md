# api documentation for  [jquery (v3.2.1)](https://jquery.com)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jquery.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jquery)
#### JavaScript library for DOM operations

[![NPM](https://nodei.co/npm/jquery.png?downloads=true)](https://www.npmjs.com/package/jquery)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jquery/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-jquery_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jquery/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-jquery/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "JS Foundation and other contributors",
        "url": "https://github.com/jquery/jquery/blob/3.2.1/AUTHORS.txt"
    },
    "bugs": {
        "url": "https://github.com/jquery/jquery/issues"
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
    },
    "dependencies": {},
    "description": "JavaScript library for DOM operations",
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
    "directories": {},
    "dist": {
        "shasum": "5c4d9de652af6cd0a770154a631bba12b015c787",
        "tarball": "https://registry.npmjs.org/jquery/-/jquery-3.2.1.tgz"
    },
    "gitHead": "77d2a51d0520d2ee44173afdf4e40a9201f5964e",
    "homepage": "https://jquery.com",
    "keywords": [
        "jquery",
        "javascript",
        "browser",
        "library"
    ],
    "license": "MIT",
    "main": "dist/jquery.js",
    "maintainers": [
        {
            "name": "dmethvin",
            "email": "dave.methvin@gmail.com"
        },
        {
            "name": "mgol",
            "email": "m.goleb@gmail.com"
        },
        {
            "name": "scott.gonzalez",
            "email": "scott.gonzalez@gmail.com"
        },
        {
            "name": "timmywil",
            "email": "4timmywil@gmail.com"
        }
    ],
    "name": "jquery",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jquery/jquery.git"
    },
    "scripts": {
        "build": "npm install && grunt",
        "commitmsg": "node node_modules/commitplease",
        "precommit": "grunt lint:newer",
        "start": "grunt watch",
        "test": "grunt && grunt test:slow"
    },
    "title": "jQuery",
    "version": "3.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module jquery](#apidoc.module.jquery)



# <a name="apidoc.module.jquery"></a>[module jquery](#apidoc.module.jquery)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
