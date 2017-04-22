# npmtest-generator-openveo-plugin

#### basic test coverage for  [generator-openveo-plugin (v1.0.0)](https://github.com/veo-labs/openveo-plugin-generator)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-openveo-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-openveo-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-openveo-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-openveo-plugin)

#### A Yeoman generator for OpenVeo plugins

[![NPM](https://nodei.co/npm/generator-openveo-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-openveo-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-openveo-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-openveo-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-openveo-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-openveo-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-openveo-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-openveo-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-openveo-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-openveo-plugin",
    "version": "1.0.0",
    "description": "A Yeoman generator for OpenVeo plugins",
    "keywords": [
        "openveo",
        "plugin",
        "boilerplate",
        "veo-labs",
        "yeoman",
        "yeoman-generator",
        "grunt",
        "angular"
    ],
    "homepage": "https://github.com/veo-labs/openveo-plugin-generator",
    "bugs": {
        "url": "https://github.com/veo-labs/openveo-plugin-generator/issues"
    },
    "license": "AGPL-3.0",
    "author": "Veo-Labs <info@veo-labs.com> (http://www.veo-labs.com/)",
    "repository": {
        "type": "git",
        "url": "https://github.com/veo-labs/openveo-plugin-generator.git"
    },
    "main": "app/index.js",
    "files": [
        "generators"
    ],
    "dependencies": {
        "chalk": "1.1.3",
        "lodash": "4.13.1",
        "yeoman-assert": "2.2.1",
        "yeoman-generator": "0.23.3",
        "yeoman-test": "1.4.0",
        "yosay": "1.1.1"
    },
    "devDependencies": {
        "glob": "5.0.12",
        "grunt": "0.4.5",
        "grunt-cli": "1.2.0",
        "grunt-eslint": "18.1.0",
        "grunt-remove": "0.1.0",
        "grunt-rename": "0.1.4",
        "grunt-gh-pages": "1.1.0",
        "grunt-contrib-yuidoc": "1.0.0",
        "grunt-mkdocs": "0.1.3",
        "pre-commit": "1.1.2"
    },
    "scripts": {
        "eslint": "grunt eslint"
    },
    "precommit": [
        "eslint"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
