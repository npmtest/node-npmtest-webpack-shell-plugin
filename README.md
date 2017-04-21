# npmtest-webpack-shell-plugin

#### basic test coverage for  [webpack-shell-plugin (v0.5.0)](https://github.com/1337programming/webpack-shell-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-shell-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-shell-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-shell-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-shell-plugin)

#### Run shell commands before and after webpack builds

[![NPM](https://nodei.co/npm/webpack-shell-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-shell-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-shell-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-shell-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-shell-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-shell-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-shell-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-shell-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-shell-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "webpack-shell-plugin",
    "version": "0.5.0",
    "description": "Run shell commands before and after webpack builds",
    "main": "lib/index.js",
    "scripts": {
        "test": "webpack",
        "test:dev": "webpack-dev-server --progress",
        "build": "rollup -c",
        "webpack": "webpack --progress",
        "webpack-dev-server": "webpack-dev-server --progress",
        "lint": "eslint src/webpack-shell-plugin.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/1337programming/webpack-shell-plugin.git"
    },
    "keywords": [
        "webpack",
        "shell",
        "plugin",
        "shell",
        "serve",
        "hmr",
        "browser",
        "script",
        "opie",
        "manion",
        "1337"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/1337programming/webpack-shell-plugin/issues"
    },
    "homepage": "https://github.com/1337programming/webpack-shell-plugin",
    "devDependencies": {
        "babel-core": "^6.7.6",
        "babel-preset-es2015-rollup": "^1.1.1",
        "css-loader": "^0.23.1",
        "eslint": "^2.7.0",
        "rollup": "^0.25.8",
        "rollup-plugin-babel": "^2.4.0",
        "style-loader": "^0.13.1",
        "webpack": "^1.13.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
