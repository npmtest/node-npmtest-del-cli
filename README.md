# npmtest-del-cli

#### basic test coverage for  del-cli (v0.2.1)  [![npm package](https://img.shields.io/npm/v/npmtest-del-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-del-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-del-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-del-cli)

#### Delete files and folders

[![NPM](https://nodei.co/npm/del-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/del-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-del-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-del-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-del-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-del-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-del-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-del-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-del-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-del-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-del-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-del-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-del-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-del-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-del-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-del-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-del-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-del-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-del-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-del-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-del-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-del-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-del-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "del-cli",
    "version": "0.2.1",
    "description": "Delete files and folders",
    "license": "MIT",
    "repository": "sindresorhus/del-cli",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "del": "cli.js",
        "del-cli": "cli.js"
    },
    "engines": {
        "node": ">=0.10"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "cli.js"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "delete",
        "del",
        "remove",
        "destroy",
        "trash",
        "unlink",
        "clean",
        "cleaning",
        "cleanup",
        "rm",
        "rmrf",
        "rimraf",
        "rmdir",
        "glob",
        "file",
        "files",
        "folder",
        "dir",
        "directory",
        "fs",
        "filesystem"
    ],
    "dependencies": {
        "del": "^2.2.0",
        "meow": "^3.6.0",
        "update-notifier": "^1.0.3"
    },
    "devDependencies": {
        "ava": "*",
        "execa": "^0.2.2",
        "temp-write": "^2.0.1",
        "xo": "^0.16.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
