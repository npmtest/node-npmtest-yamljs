# test coverage for  [yamljs (v0.2.9)](https://github.com/jeremyfa/yaml.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-yamljs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yamljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yamljs.svg)](https://travis-ci.org/npmtest/node-npmtest-yamljs)
#### Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.

[![NPM](https://nodei.co/npm/yamljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yamljs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yamljs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yamljs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yamljs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yamljs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yamljs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yamljs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yamljs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yamljs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yamljs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yamljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yamljs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yamljs/build/test-report.html](https://npmtest.github.io/node-npmtest-yamljs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yamljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yamljs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yamljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yamljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Faivre"
    },
    "bin": {
        "yaml2json": "./bin/yaml2json",
        "json2yaml": "./bin/json2yaml"
    },
    "bugs": {
        "url": "https://github.com/jeremyfa/yaml.js/issues"
    },
    "dependencies": {
        "argparse": "^1.0.7",
        "glob": "^7.0.5"
    },
    "description": "Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "coffeeify": "^2.0.1",
        "jasmine-node": "^1.14.5"
    },
    "directories": {},
    "dist": {
        "shasum": "bd3bdaa62ac09deb2a2e1ce803eeb4217b52a82f",
        "tarball": "https://registry.npmjs.org/yamljs/-/yamljs-0.2.9.tgz"
    },
    "gitHead": "e1796d46972b4784973d7593802975af0d138547",
    "homepage": "https://github.com/jeremyfa/yaml.js#readme",
    "keywords": [
        "yaml",
        "json",
        "yaml2json",
        "json2yaml"
    ],
    "license": "MIT",
    "main": "./lib/Yaml.js",
    "maintainers": [
        {
            "name": "jeremyfa"
        }
    ],
    "name": "yamljs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jeremyfa/yaml.js.git"
    },
    "scripts": {
        "test": "cake build; cake test"
    },
    "version": "0.2.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
