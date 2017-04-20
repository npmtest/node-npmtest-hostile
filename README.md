# npmtest-hostile

#### basic test coverage for  [hostile (v1.3.0)](https://github.com/feross/hostile)  [![npm package](https://img.shields.io/npm/v/npmtest-hostile.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hostile) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hostile.svg)](https://travis-ci.org/npmtest/node-npmtest-hostile)

#### Simple /etc/hosts manipulation

[![NPM](https://nodei.co/npm/hostile.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hostile)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hostile/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hostile/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hostile/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hostile/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hostile/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hostile/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hostile/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hostile/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hostile/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hostile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hostile/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hostile/build/test-report.html](https://npmtest.github.io/node-npmtest-hostile/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hostile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hostile/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hostile/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hostile/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hostile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hostile/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hostile/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hostile/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bin": {
        "hostile": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/feross/hostile/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "minimist": "^1.1.0",
        "once": "^1.3.0",
        "split": "^1.0.0",
        "through": "^2.3.4"
    },
    "description": "Simple /etc/hosts manipulation",
    "devDependencies": {
        "standard": "*",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6c99d1480f9b410181d04de92c41be3fde3a0b47",
        "tarball": "https://registry.npmjs.org/hostile/-/hostile-1.3.0.tgz"
    },
    "gitHead": "034778b8dc0c7034bbe206543060dc61cfc0f9f0",
    "homepage": "https://github.com/feross/hostile",
    "keywords": [
        "/etc/hosts",
        "hosts file",
        "hostname",
        "etc hosts",
        "change hosts"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "hostile",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/hostile.git"
    },
    "scripts": {
        "test": "standard && tape test/*.js"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
