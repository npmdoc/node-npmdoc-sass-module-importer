# npmdoc-sass-module-importer

#### api documentation for  [sass-module-importer (v1.4.0)](https://github.com/lucasmotta/sass-module-importer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sass-module-importer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sass-module-importer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sass-module-importer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sass-module-importer)

#### Import Sass files from NPM and Bower Modules

[![NPM](https://nodei.co/npm/sass-module-importer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sass-module-importer)

- [https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sass-module-importer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lucas Motta",
        "url": "lucasmotta.com"
    },
    "bugs": {
        "url": "https://github.com/lucasmotta/sass-module-importer/issues"
    },
    "dependencies": {
        "es6-map": "0.1.3",
        "glob": "^7.1.1",
        "object-assign": "4.0.1",
        "resolve": "1.1.7",
        "resolve-bower": "0.0.1"
    },
    "description": "Import Sass files from NPM and Bower Modules",
    "devDependencies": {
        "buble": "^0.5.6",
        "chai": "^3.5.0",
        "eslint": "^2.8.0",
        "eslint-config-airbnb": "^6.1.0",
        "mocha": "^2.4.5",
        "node-sass": "^3.4.2",
        "rollup": "^0.25.4",
        "rollup-plugin-buble": "^0.5.0",
        "rollup-plugin-commonjs": "^3.1.0",
        "rollup-plugin-json": "^2.0.0",
        "rollup-plugin-node-resolve": "^1.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ed0400f9c1a40f017790a1772da0beb5432f9149",
        "tarball": "https://registry.npmjs.org/sass-module-importer/-/sass-module-importer-1.4.0.tgz"
    },
    "gitHead": "adb115188a7a07119d08b0456b74b7abef32c70d",
    "homepage": "https://github.com/lucasmotta/sass-module-importer#readme",
    "jsnext:main": "src/index.js",
    "keywords": [
        "sass",
        "scss",
        "importer",
        "module",
        "npm",
        "node-sass",
        "bower"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "lucasmotta"
        }
    ],
    "name": "sass-module-importer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lucasmotta/sass-module-importer.git"
    },
    "scripts": {
        "build": "rollup -c",
        "lint": "eslint src/index.js test.js",
        "postversion": "git push && git push --tags",
        "prepublish": "npm test",
        "pretest": "npm run lint && npm run build",
        "preversion": "npm test",
        "test": "mocha --compilers js:buble/register",
        "version": "npm run build"
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
