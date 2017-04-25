# npmtest-react-overlays

#### basic test coverage for  [react-overlays (v0.7.0)](https://github.com/react-bootstrap/react-overlays#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-overlays.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-overlays) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-overlays.svg)](https://travis-ci.org/npmtest/node-npmtest-react-overlays)

#### Utilities for creating robust overlay components

[![NPM](https://nodei.co/npm/react-overlays.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-overlays)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-overlays/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-overlays/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-overlays/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-overlays/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-overlays/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-overlays/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-overlays/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-overlays/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-overlays/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-overlays/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-overlays/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-overlays/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-overlays/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-overlays/build/test-report.html](https://npmtest.github.io/node-npmtest-react-overlays/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-overlays/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-overlays/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-overlays/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-overlays/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-overlays/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Quense"
    },
    "bugs": {
        "url": "https://github.com/react-bootstrap/react-overlays/issues"
    },
    "dependencies": {
        "classnames": "^2.2.5",
        "dom-helpers": "^3.2.0",
        "prop-types": "^15.5.8",
        "react-prop-types": "^0.4.0",
        "warning": "^3.0.0"
    },
    "description": "Utilities for creating robust overlay components",
    "devDependencies": {
        "@monastic.panic/component-playground": "^2.0.0",
        "babel-cli": "^6.10.1",
        "babel-core": "^6.10.4",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-object-assign": "^1.2.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.5.0",
        "chai": "^3.5.0",
        "component-metadata-loader": "^2.0.3",
        "css-loader": "^0.23.1",
        "es5-shim": "^4.5.9",
        "eslint": "^3.0.1",
        "eslint-plugin-mocha": "^4.0.0",
        "eslint-plugin-react": "^5.2.2",
        "isparta-loader": "^2.0.0",
        "jquery": "^3.1.0",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^1.0.1",
        "karma-coverage": "^1.1.0",
        "karma-coveralls": "^1.1.2",
        "karma-mocha": "^1.1.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sinon-chai": "^1.2.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "less": "^2.7.1",
        "less-loader": "^2.2.3",
        "lodash": "^4.13.1",
        "lolex": "^1.5.0",
        "marked": "^0.3.5",
        "mocha": "^2.5.3",
        "node-libs-browser": "^1.0.0",
        "prop-types": "^15.5.4",
        "raw-loader": "^0.5.1",
        "react": "^15.3.0",
        "react-addons-test-utils": "^15.3.0",
        "react-bootstrap": "^0.30.8",
        "react-component-metadata": "^3.0.0",
        "react-dom": "^15.3.0",
        "react-hot-loader": "^1.3.0",
        "release-script": "^1.0.2",
        "rimraf": "^2.5.3",
        "simulant": "^0.2.2",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.8.0",
        "style-loader": "^0.13.1",
        "teaspoon": "^6.4.1",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1",
        "yargs": "^4.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "531898ff566c7e5c7226ead2863b8cf9fbb5a981",
        "tarball": "https://registry.npmjs.org/react-overlays/-/react-overlays-0.7.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "ea198fa9472fa426a2bd8344bd702c87503f3f29",
    "homepage": "https://github.com/react-bootstrap/react-overlays#readme",
    "keywords": [
        "react-overlays",
        "react-component",
        "react",
        "overlay",
        "react-component",
        "tooltip",
        "bootstrap",
        "popover",
        "modal"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "monastic.panic"
        },
        {
            "name": "taion"
        }
    ],
    "name": "react-overlays",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.9 || >=15.3.0",
        "react-dom": "^0.14.9 || >=15.3.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/react-bootstrap/react-overlays.git"
    },
    "scripts": {
        "build": "npm run clean && babel src --out-dir lib",
        "build:examples": "npm run clean:examples && webpack --config webpack/docs.config.js",
        "clean": "rimraf lib",
        "clean:examples": "rimraf examples/static",
        "examples": "npm run clean:examples && babel-node examples/server.js",
        "lint": "eslint examples/*.js src test *.js",
        "release": "release",
        "tdd": "karma start",
        "test": "npm run lint && npm run testonly",
        "testonly": "karma start --single-run"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
