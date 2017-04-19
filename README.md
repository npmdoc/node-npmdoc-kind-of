# npmdoc-kind-of

#### api documentation for  [kind-of (v3.1.0)](https://github.com/jonschlinkert/kind-of)  [![npm package](https://img.shields.io/npm/v/npmdoc-kind-of.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-kind-of) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-kind-of.svg)](https://travis-ci.org/npmdoc/node-npmdoc-kind-of)

#### Get the native type of a value.

[![NPM](https://nodei.co/npm/kind-of.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kind-of)

- [https://npmdoc.github.io/node-npmdoc-kind-of/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kind-of/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kind-of/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kind-of/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-kind-of/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-kind-of/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/kind-of/issues"
    },
    "contributors": [
        {
            "name": "David Fox-Powell",
            "url": "https://dtothefp.github.io/me"
        },
        {
            "name": "Jon Schlinkert",
            "url": "http://twitter.com/jonschlinkert"
        },
        {
            "name": "Miguel Mota",
            "url": "https://miguelmota.com"
        },
        {
            "name": "Peter deHaan",
            "url": "http://about.me/peterdehaan"
        }
    ],
    "dependencies": {
        "is-buffer": "^1.0.2"
    },
    "description": "Get the native type of a value.",
    "devDependencies": {
        "ansi-bold": "^0.1.1",
        "benchmarked": "^0.2.5",
        "browserify": "^13.1.0",
        "glob": "^7.0.5",
        "gulp-format-md": "^0.1.9",
        "mocha": "^2.5.3",
        "type-of": "^2.0.1",
        "typeof": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "475d698a5e49ff5e53d14e3e732429dc8bf4cf47",
        "tarball": "https://registry.npmjs.org/kind-of/-/kind-of-3.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "eb57ad426b39f25902260f315a1f4ae50d2f760e",
    "homepage": "https://github.com/jonschlinkert/kind-of",
    "keywords": [
        "arguments",
        "array",
        "boolean",
        "check",
        "date",
        "function",
        "is",
        "is-type",
        "is-type-of",
        "kind",
        "kind-of",
        "number",
        "object",
        "of",
        "regexp",
        "string",
        "test",
        "type",
        "type-of",
        "typeof",
        "types"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "doowb"
        }
    ],
    "name": "kind-of",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/kind-of.git"
    },
    "scripts": {
        "prepublish": "browserify -o browser.js -e index.js -s index --bare",
        "test": "mocha"
    },
    "verb": {
        "related": {
            "list": [
                "is-glob",
                "is-number",
                "is-primitive"
            ]
        },
        "toc": false,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        },
        "reflinks": [
            "verb"
        ]
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
