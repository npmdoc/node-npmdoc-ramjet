# npmdoc-ramjet

#### api documentation for  ramjet (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-ramjet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ramjet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ramjet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ramjet)

#### Transform DOM elements into each another with smooth transitions

[![NPM](https://nodei.co/npm/ramjet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ramjet)

- [https://npmdoc.github.io/node-npmdoc-ramjet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ramjet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ramjet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ramjet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ramjet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ramjet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ramjet",
    "description": "Transform DOM elements into each another with smooth transitions",
    "version": "0.5.0",
    "author": "Rich Harris",
    "license": "MIT",
    "repository": "https://github.com/rich-harris/ramjet",
    "main": "dist/ramjet.umd.js",
    "jsnext:main": "dist/ramjet.es6.js",
    "files": [
        "src",
        "dist",
        "README.md"
    ],
    "scripts": {
        "start": "gobble",
        "build": "gobble build -f dist",
        "prepublish": "npm run build",
        "test": "open http://localhost:4567/test.html; npm start"
    },
    "devDependencies": {
        "babel-preset-es2015-rollup": "^1.1.1",
        "eases": "^1.0.8",
        "gobble": "^0.10.2",
        "gobble-babel": "^5.5.8",
        "gobble-browserify": "^0.6.1",
        "gobble-cli": "^0.6.0",
        "gobble-derequire": "^0.1.2",
        "gobble-ractive": "^0.2.0",
        "gobble-rollup": "^0.25.0",
        "gobble-uglifyjs": "^0.2.1",
        "ractive": "^0.7.3",
        "ractive-events-tap": "^0.3.0",
        "ractive-transitions-fade": "^0.3.1",
        "rollup-plugin-babel": "^2.3.9"
    },
    "spm": {
        "main": "dist/ramjet.js",
        "ignore": [
            "demo",
            "test",
            "src",
            "scripts"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
