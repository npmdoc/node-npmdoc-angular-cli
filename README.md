# api documentation for  [angular-cli (v1.0.0-beta.28.3)](https://github.com/angular/angular-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-angular-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-angular-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-angular-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-angular-cli)
#### CLI tool for Angular

[![NPM](https://nodei.co/npm/angular-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular-cli)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-angular-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-angular-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "angular-cli",
    "version": "1.0.0-beta.28.3",
    "description": "CLI tool for Angular",
    "main": "lib/cli/index.js",
    "trackingCode": "UA-8594346-19",
    "bin": {
        "ng": "./bin/ng"
    },
    "keywords": [
        "angular",
        "angular-cli"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/angular/angular-cli.git"
    },
    "engines": {
        "node": ">= 4.1.0",
        "npm": ">= 3.0.0"
    },
    "author": {
        "name": "Angular Authors"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/angular/angular-cli/issues"
    },
    "homepage": "https://github.com/angular/angular-cli",
    "dependencies": {
        "@angular-cli/ast-tools": "^1.0.14",
        "@angular-cli/base-href-webpack": "^1.0.14",
        "@angular/compiler": "^2.3.1",
        "@angular/compiler-cli": "^2.3.1",
        "@angular/core": "^2.3.1",
        "@ngtools/json-schema": "^1.0.0",
        "@ngtools/webpack": "^1.2.3",
        "async": "^2.1.4",
        "autoprefixer": "^6.5.3",
        "chalk": "^1.1.3",
        "common-tags": "^1.3.1",
        "css-loader": "^0.26.1",
        "cssnano": "^3.10.0",
        "debug": "^2.1.3",
        "denodeify": "^1.2.1",
        "diff": "^2.2.2",
        "ember-cli-normalize-entity-name": "^1.0.0",
        "ember-cli-string-utils": "^1.0.0",
        "exists-sync": "0.0.3",
        "extract-text-webpack-plugin": "^2.0.0-rc.1",
        "file-loader": "^0.8.5",
        "findup": "0.1.5",
        "fs-extra": "^0.30.0",
        "get-caller-file": "^1.0.0",
        "glob": "^7.0.3",
        "html-webpack-plugin": "^2.19.0",
        "inflection": "^1.7.0",
        "inquirer": "^0.12.0",
        "isbinaryfile": "^2.0.3",
        "json-loader": "^0.5.4",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.8.0",
        "less": "^2.7.2",
        "less-loader": "^2.2.3",
        "lodash": "^4.11.1",
        "minimatch": "^3.0.3",
        "node-modules-path": "^1.0.0",
        "node-sass": "^4.3.0",
        "nopt": "^3.0.1",
        "opn": "4.0.1",
        "ora": "^0.2.0",
        "portfinder": "1.0.9",
        "postcss-loader": "^0.9.1",
        "raw-loader": "^0.5.1",
        "remap-istanbul": "^0.6.4",
        "resolve": "^1.1.7",
        "rimraf": "^2.5.3",
        "rsvp": "^3.0.17",
        "sass-loader": "^4.1.1",
        "script-loader": "^0.7.0",
        "semver": "^5.1.0",
        "silent-error": "^1.0.0",
        "source-map-loader": "^0.1.5",
        "sourcemap-istanbul-instrumenter-loader": "^0.2.0",
        "style-loader": "^0.13.1",
        "stylus": "^0.54.5",
        "stylus-loader": "^2.4.0",
        "temp": "0.8.3",
        "through": "^2.3.6",
        "typescript": "~2.0.3",
        "url-loader": "^0.5.7",
        "walk-sync": "^0.2.6",
        "webpack": "2.2.0",
        "webpack-dev-server": "2.2.0-rc.0",
        "webpack-merge": "^2.4.0",
        "webpack-sources": "^0.1.3",
        "zone.js": "^0.7.2"
    },
    "ember-addon": {
        "paths": [
            "./"
        ],
        "main": "./addon/index.js"
    },
    "scripts": {},
    "dist": {
        "shasum": "9751d7414eaf8e0b714b2461a585bfda9713416f",
        "tarball": "https://registry.npmjs.org/angular-cli/-/angular-cli-1.0.0-beta.28.3.tgz"
    },
    "maintainers": [
        {
            "name": "angular-cli"
        }
    ],
    "directories": {},
    "deprecated": "angular-cli has been renamed to @angular/cli. Please update your dependencies."
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module angular-cli](#apidoc.module.angular-cli)
1.  [function <span class="apidocSignatureSpan"></span>angular-cli (options)](#apidoc.element.angular-cli.angular-cli)
1.  [function <span class="apidocSignatureSpan">angular-cli.</span>toString ()](#apidoc.element.angular-cli.toString)
1.  object <span class="apidocSignatureSpan">angular-cli.</span>completion

#### [module angular-cli.completion](#apidoc.module.angular-cli.completion)
1.  [function <span class="apidocSignatureSpan">angular-cli.completion.</span>default ()](#apidoc.element.angular-cli.completion.default)



# <a name="apidoc.module.angular-cli"></a>[module angular-cli](#apidoc.module.angular-cli)

#### <a name="apidoc.element.angular-cli.angular-cli"></a>[function <span class="apidocSignatureSpan"></span>angular-cli (options)](#apidoc.element.angular-cli.angular-cli)
- description and source-code
```javascript
angular-cli = function (options) {

  // patch UI to not print Ember-CLI warnings (which don't apply to Angular-CLI)
  UI.prototype.writeWarnLine = function () { }

  // patch Watcher to always default to node, not checking for Watchman
  Watcher.detectWatcher = function(ui, _options){
    var options = _options || {};
    options.watcher = 'node';
    return Promise.resolve(options);
  }

  options.cli = {
    name: 'ng',
    root: path.join(__dirname, '..', '..'),
    npmPackage: 'angular-cli'
  };

  // ensure the environemnt variable for dynamic paths
  process.env.PWD = path.normalize(process.env.PWD || process.cwd());
  process.env.CLI_ROOT = process.env.CLI_ROOT || path.resolve(__dirname, '..', '..');

  return cli(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.angular-cli.toString"></a>[function <span class="apidocSignatureSpan">angular-cli.</span>toString ()](#apidoc.element.angular-cli.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.completion"></a>[module angular-cli.completion](#apidoc.module.angular-cli.completion)

#### <a name="apidoc.element.angular-cli.completion.default"></a>[function <span class="apidocSignatureSpan">angular-cli.completion.</span>default ()](#apidoc.element.angular-cli.completion.default)
- description and source-code
```javascript
function Class() {
  constructor.apply(this, arguments);
  if (this.init) {
    this.init(options);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
