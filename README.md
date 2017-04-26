# npmdoc-yarnpkg

#### basic api documentation for  [yarnpkg (v0.15.1)](https://github.com/yarnpkg/yarn#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yarnpkg.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yarnpkg) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yarnpkg.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yarnpkg)

#### <p align="center">   <a href="https://yarnpkg.com/">     <img alt="Yarn" src="https://github.com/yarnpkg/assets/blob/master/yarn-kitten-full.png?raw=true" width="546">   </a> </p>

[![NPM](https://nodei.co/npm/yarnpkg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yarnpkg)

- [https://npmdoc.github.io/node-npmdoc-yarnpkg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yarnpkg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yarnpkg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yarnpkg/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yarnpkg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yarnpkg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "yarn": "./bin/yarn.js"
    },
    "bugs": {
        "url": "https://github.com/yarnpkg/yarn/issues"
    },
    "dependencies": {
        "babel-plugin-transform-inline-imports-commonjs": "^1.0.0",
        "babel-runtime": "^6.0.0",
        "bytes": "^2.4.0",
        "camelcase": "^3.0.0",
        "chalk": "^1.1.1",
        "cmd-shim": "^2.0.1",
        "commander": "^2.9.0",
        "death": "^1.0.0",
        "debug": "^2.2.0",
        "defaults": "^1.0.3",
        "diff": "^2.2.1",
        "github": "2.5.1",
        "ini": "^1.3.4",
        "invariant": "^2.2.0",
        "is-builtin-module": "^1.0.0",
        "leven": "^2.0.0",
        "loud-rejection": "^1.2.0",
        "minimatch": "^3.0.3",
        "mkdirp": "^0.5.1",
        "node-emoji": "^1.0.4",
        "node-gyp": "^3.2.1",
        "object-path": "^0.11.2",
        "proper-lockfile": "^1.1.3",
        "read": "^1.0.7",
        "repeating": "^2.0.0",
        "request": "^2.75.0",
        "request-capture-har": "^1.1.4",
        "rimraf": "^2.5.0",
        "roadrunner": "^1.0.6",
        "semver": "^5.1.0",
        "strip-bom": "^2.0.0",
        "tar": "^2.2.1",
        "tar-stream": "^1.5.2",
        "user-home": "^2.0.0",
        "validate-npm-package-license": "^3.0.1"
    },
    "deprecated": "Please use the 'yarn' package instead of 'yarnpkg'",
    "description": "<p align=\"center\">   <a href=\"https://yarnpkg.com/\">     <img alt=\"Yarn\" src=\"https://github.com/yarnpkg/assets/blob/master/yarn-kitten-full.png?raw=true\" width=\"546\">   </a> </p>",
    "devDependencies": {
        "babel-core": "^6.17.0",
        "babel-eslint": "^6.1.2",
        "babel-jest": "^14.0.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.4.3",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-es2015-node4": "^2.1.0",
        "babel-preset-node5": "^10.2.0",
        "babel-preset-react": "^6.0.0",
        "babel-preset-stage-0": "^6.0.0",
        "babylon": "^6.5.0",
        "eslint": "^3.3.1",
        "eslint-config-fb-strict": "^14.1.3",
        "eslint-config-fbjs": "^1.0.0",
        "eslint-config-kittens": "^2.0.1",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flow-vars": "^0.4.0",
        "eslint-plugin-flowtype": "^2.15.0",
        "eslint-plugin-no-async-without-await": "^1.0.0",
        "eslint-plugin-react": "^5.2.2",
        "eslint-plugin-yarn-internal": "file:scripts/eslint-rules",
        "flow-bin": "0.33.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.0.0",
        "gulp-newer": "^1.0.0",
        "gulp-plumber": "^1.0.1",
        "gulp-util": "^3.0.7",
        "gulp-watch": "^4.3.5",
        "jest": "^16.0.1",
        "json-loader": "^0.5.4",
        "mock-stdin": "^0.3.0",
        "temp": "^0.8.3",
        "webpack": "^2.1.0-beta.25"
    },
    "directories": {},
    "dist": {
        "shasum": "704741ba78f35478cd72d7fdae85b098d3108c31",
        "tarball": "https://registry.npmjs.org/yarnpkg/-/yarnpkg-0.15.1.tgz"
    },
    "eslintConfig": {
        "extends": "eslint-config-fb-strict",
        "env": {
            "jest": true
        },
        "plugins": [
            "flowtype",
            "no-async-without-await",
            "yarn-internal"
        ],
        "rules": {
            "yarn-internal/warn-language": 2,
            "max-len": [
                2,
                120
            ],
            "prefer-arrow-callback": 0,
            "babel/arrow-parens": [
                2,
                "always"
            ],
            "flowtype/require-valid-file-annotation": [
                2,
                "always"
            ],
            "flowtype/space-after-type-colon": [
                2,
                "always"
            ],
            "flowtype/require-return-type": [
                2,
                "always",
                {
                    "excludeArrowFunctions": true
                }
            ],
            "no-async-without-await/no-async-without-await": 2
        }
    },
    "gitHead": "918f4400eea9f9abb3254977a4bebc9ecfd6e3b1",
    "homepage": "https://github.com/yarnpkg/yarn#readme",
    "jest": {
        "timers": "fake",
        "testEnvironment": "node",
        "modulePathIgnorePatterns": [
            "__tests__/fixtures/"
        ],
        "testPathIgnorePatterns": [
            "__tests__/(fixtures|__mocks__)/",
            "updates/",
            "/_(temp|mock|install).js$"
        ]
    },
    "license": "BSD-2-Clause",
    "maintainers": [
        {
            "name": "cpojer"
        },
        {
            "name": "sebmck"
        },
        {
            "name": "thejameskyle"
        }
    ],
    "name": "yarnpkg",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/yarnpkg/yarn.git"
    },
    "scripts": {
        "build": "gulp build",
        "build-chocolatey": "powershell ./scripts/build-chocolatey.ps1",
        "build-dist": "./scripts/build-dist.sh",
        "build-win-installer": "scripts\\build-windows-installer.bat",
        "check-lockfile": "./scripts/check-lockfile.sh",
        "lint": "eslint . && flow check",
        "release-branch": "./scripts/release-branch.sh",
        "test": "npm run lint && npm run test-only",
        "test-ci": "npm run build && npm run test-only",
        "test-only": "jest --coverage --verbose",
        "watch": "gulp watch"
    },
    "version": "0.15.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
