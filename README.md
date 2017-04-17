# test coverage for  [gulp-svg-sprite (v1.3.6)](https://github.com/jkphl/gulp-svg-sprite)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-svg-sprite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-svg-sprite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-svg-sprite.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-svg-sprite)
#### SVG sprites & stacks galore — Gulp plugin wrapping around svg-sprite that reads in a bunch of SVG files, optimizes them and creates SVG sprites and CSS resources in various flavours

[![NPM](https://nodei.co/npm/gulp-svg-sprite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-svg-sprite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-svg-sprite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-svg-sprite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-svg-sprite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-svg-sprite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joschi Kuphal",
        "url": "https://jkphl.is"
    },
    "bugs": {
        "url": "https://github.com/jkphl/gulp-svg-sprite/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.7",
        "svg-sprite": "~1.3.6",
        "through2": "^2.0.1",
        "vinyl": "^1.2.0"
    },
    "description": "SVG sprites & stacks galore — Gulp plugin wrapping around svg-sprite that reads in a bunch of SVG files, optimizes them and creates SVG sprites and CSS resources in various flavours",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "glob": "~7.0.6",
        "gulp": "^3.9.1",
        "gulp-jshint": "^2.0.1",
        "gulp-plumber": "^1.1.0",
        "image-diff": "^1.6.3",
        "istanbul": "*",
        "jshint": "^2.9.3",
        "mkdirp": "^0.5.1",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "pn": "^1.0.0",
        "should": "~11.1.0",
        "svg2png": "github:jkphl/svg2png"
    },
    "directories": {},
    "dist": {
        "shasum": "656083f788aca0df00a485e37f79897e1e2314c7",
        "tarball": "https://registry.npmjs.org/gulp-svg-sprite/-/gulp-svg-sprite-1.3.6.tgz"
    },
    "engines": {
        "node": ">= 4.0"
    },
    "files": [
        "index.js",
        "CHANGELOG.md"
    ],
    "gitHead": "62fce9d131539eabf6ad27961b9811277eac4cad",
    "homepage": "https://github.com/jkphl/gulp-svg-sprite",
    "keywords": [
        "gulpplugin",
        "icon",
        "icons",
        "svg",
        "png",
        "sprite",
        "spritesheet",
        "stack",
        "generator",
        "css",
        "sass",
        "less",
        "stylus",
        "stylesheet",
        "inline",
        "html",
        "vector",
        "rwd",
        "retina",
        "mustache"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jkphl"
        }
    ],
    "name": "gulp-svg-sprite",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jkphl/gulp-svg-sprite.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "gulp && istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "1.3.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
