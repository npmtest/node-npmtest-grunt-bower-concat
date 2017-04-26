# npmtest-grunt-bower-concat

#### basic test coverage for  [grunt-bower-concat (v1.0.0)](https://github.com/sapegin/grunt-bower-concat)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bower-concat.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bower-concat) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bower-concat.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bower-concat)

#### Automatic concatenation of installed Bower components in right order.

[![NPM](https://nodei.co/npm/grunt-bower-concat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-bower-concat)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bower-concat/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-bower-concat/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bower-concat/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bower-concat/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-bower-concat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-bower-concat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bower-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bower-concat/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bower-concat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Artem Sapegin",
        "url": "http://sapegin.me/"
    },
    "bugs": {
        "url": "https://github.com/sapegin/grunt-bower-concat/issues"
    },
    "dependencies": {
        "async": "~1.5.2",
        "bower": "~1.7.7",
        "detective": "~4.3.1",
        "filesize": "~3.2.1",
        "lodash": "~4.3.0",
        "underscore.string": "~3.2.3"
    },
    "description": "Automatic concatenation of installed Bower components in right order.",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-jshint": "~0.11.2",
        "grunt-jscs": "~2.1.0",
        "grunt-mocha-test": "~0.12.7",
        "load-grunt-tasks": "~3.4.0",
        "mocha": "~2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "f430c7b718704c6815215c6ca94d2fd5dd4a7b5b",
        "tarball": "https://registry.npmjs.org/grunt-bower-concat/-/grunt-bower-concat-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "56cd4fa7b0670335074c42cedf5d32fc393447ab",
    "homepage": "https://github.com/sapegin/grunt-bower-concat",
    "keywords": [
        "gruntplugin",
        "bower",
        "component",
        "package",
        "concat"
    ],
    "license": "MIT",
    "main": "tasks/bower-concat.js",
    "maintainers": [
        {
            "name": "sapegin"
        }
    ],
    "name": "grunt-bower-concat",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/sapegin/grunt-bower-concat.git"
    },
    "scripts": {
        "pretest": "bower install",
        "test": "grunt"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
