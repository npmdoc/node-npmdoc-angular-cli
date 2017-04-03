# api documentation for  [angular-cli (v1.0.0-beta.28.3)](https://github.com/angular/angular-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-angular-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-angular-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-angular-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-angular-cli)
#### CLI tool for Angular

[![NPM](https://nodei.co/npm/angular-cli.png?downloads=true)](https://www.npmjs.com/package/angular-cli)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-cli/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-angular-cli_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-cli/build..beta..travis-ci.org/apidoc.html)

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
            "name": "angular-cli",
            "email": "hansl@google.com"
        }
    ],
    "directories": {},
    "deprecated": "angular-cli has been renamed to @angular/cli. Please update your dependencies.",
    "readme": "ERROR: No README data found!"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module angular-cli](#apidoc.module.angular-cli)
1.  [function <span class="apidocSignatureSpan">angular-cli.</span>git_init ()](#apidoc.element.angular-cli.git_init)
1.  object <span class="apidocSignatureSpan">angular-cli.</span>completion
1.  object <span class="apidocSignatureSpan">angular-cli.</span>config
1.  object <span class="apidocSignatureSpan">angular-cli.</span>create_github_repo
1.  object <span class="apidocSignatureSpan">angular-cli.</span>destroy
1.  object <span class="apidocSignatureSpan">angular-cli.</span>doc
1.  object <span class="apidocSignatureSpan">angular-cli.</span>e2e
1.  object <span class="apidocSignatureSpan">angular-cli.</span>easter_egg
1.  object <span class="apidocSignatureSpan">angular-cli.</span>error
1.  object <span class="apidocSignatureSpan">angular-cli.</span>find_parent_module
1.  object <span class="apidocSignatureSpan">angular-cli.</span>generate
1.  object <span class="apidocSignatureSpan">angular-cli.</span>get
1.  object <span class="apidocSignatureSpan">angular-cli.</span>get_dependent_files
1.  object <span class="apidocSignatureSpan">angular-cli.</span>git_init.prototype
1.  object <span class="apidocSignatureSpan">angular-cli.</span>github_pages_deploy
1.  object <span class="apidocSignatureSpan">angular-cli.</span>github_pages_deploy_run
1.  object <span class="apidocSignatureSpan">angular-cli.</span>glob_copy_webpack_plugin
1.  object <span class="apidocSignatureSpan">angular-cli.</span>help
1.  object <span class="apidocSignatureSpan">angular-cli.</span>init
1.  object <span class="apidocSignatureSpan">angular-cli.</span>init_run
1.  object <span class="apidocSignatureSpan">angular-cli.</span>lint
1.  object <span class="apidocSignatureSpan">angular-cli.</span>new
1.  object <span class="apidocSignatureSpan">angular-cli.</span>npm_install
1.  object <span class="apidocSignatureSpan">angular-cli.</span>package_chunk_sort
1.  object <span class="apidocSignatureSpan">angular-cli.</span>prerender_webpack_plugin
1.  object <span class="apidocSignatureSpan">angular-cli.</span>require_project_module
1.  object <span class="apidocSignatureSpan">angular-cli.</span>serve
1.  object <span class="apidocSignatureSpan">angular-cli.</span>serve_run
1.  object <span class="apidocSignatureSpan">angular-cli.</span>set
1.  object <span class="apidocSignatureSpan">angular-cli.</span>suppress_entry_chunks_webpack_plugin
1.  object <span class="apidocSignatureSpan">angular-cli.</span>version
1.  object <span class="apidocSignatureSpan">angular-cli.</span>webpack_config

#### [module angular-cli.completion](#apidoc.module.angular-cli.completion)
1.  [function <span class="apidocSignatureSpan">angular-cli.completion.</span>default ()](#apidoc.element.angular-cli.completion.default)

#### [module angular-cli.config](#apidoc.module.angular-cli.config)
1.  [function <span class="apidocSignatureSpan">angular-cli.config.</span>CliConfig ()](#apidoc.element.angular-cli.config.CliConfig)
1.  string <span class="apidocSignatureSpan">angular-cli.config.</span>CLI_CONFIG_FILE_NAME

#### [module angular-cli.create_github_repo](#apidoc.module.angular-cli.create_github_repo)
1.  [function <span class="apidocSignatureSpan">angular-cli.create_github_repo.</span>default ()](#apidoc.element.angular-cli.create_github_repo.default)

#### [module angular-cli.destroy](#apidoc.module.angular-cli.destroy)
1.  [function <span class="apidocSignatureSpan">angular-cli.destroy.</span>default ()](#apidoc.element.angular-cli.destroy.default)

#### [module angular-cli.doc](#apidoc.module.angular-cli.doc)
1.  [function <span class="apidocSignatureSpan">angular-cli.doc.</span>default ()](#apidoc.element.angular-cli.doc.default)

#### [module angular-cli.e2e](#apidoc.module.angular-cli.e2e)
1.  [function <span class="apidocSignatureSpan">angular-cli.e2e.</span>default ()](#apidoc.element.angular-cli.e2e.default)

#### [module angular-cli.easter_egg](#apidoc.module.angular-cli.easter_egg)
1.  [function <span class="apidocSignatureSpan">angular-cli.easter_egg.</span>default ()](#apidoc.element.angular-cli.easter_egg.default)

#### [module angular-cli.error](#apidoc.module.angular-cli.error)
1.  [function <span class="apidocSignatureSpan">angular-cli.error.</span>NgToolkitError (message)](#apidoc.element.angular-cli.error.NgToolkitError)

#### [module angular-cli.find_parent_module](#apidoc.module.angular-cli.find_parent_module)
1.  [function <span class="apidocSignatureSpan">angular-cli.find_parent_module.</span>default (project, currentDir)](#apidoc.element.angular-cli.find_parent_module.default)

#### [module angular-cli.generate](#apidoc.module.angular-cli.generate)
1.  [function <span class="apidocSignatureSpan">angular-cli.generate.</span>default ()](#apidoc.element.angular-cli.generate.default)

#### [module angular-cli.get](#apidoc.module.angular-cli.get)
1.  [function <span class="apidocSignatureSpan">angular-cli.get.</span>default ()](#apidoc.element.angular-cli.get.default)

#### [module angular-cli.get_dependent_files](#apidoc.module.angular-cli.get_dependent_files)
1.  [function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>createTsSourceFile (fileName)](#apidoc.element.angular-cli.get_dependent_files.createTsSourceFile)
1.  [function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getAllAssociatedFiles (fileName)](#apidoc.element.angular-cli.get_dependent_files.getAllAssociatedFiles)
1.  [function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getDependentFiles (fileName, rootPath)](#apidoc.element.angular-cli.get_dependent_files.getDependentFiles)
1.  [function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getImportClauses (node)](#apidoc.element.angular-cli.get_dependent_files.getImportClauses)
1.  [function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>hasIndexFile (dirPath)](#apidoc.element.angular-cli.get_dependent_files.hasIndexFile)

#### [module angular-cli.git_init](#apidoc.module.angular-cli.git_init)
1.  boolean <span class="apidocSignatureSpan">angular-cli.git_init.</span>overrideCore
1.  [function <span class="apidocSignatureSpan">angular-cli.</span>git_init ()](#apidoc.element.angular-cli.git_init.git_init)

#### [module angular-cli.git_init.prototype](#apidoc.module.angular-cli.git_init.prototype)
1.  [function <span class="apidocSignatureSpan">angular-cli.git_init.prototype.</span>constructor ()](#apidoc.element.angular-cli.git_init.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">angular-cli.git_init.prototype.</span>run (commandOptions)](#apidoc.element.angular-cli.git_init.prototype.run)
1.  object <span class="apidocSignatureSpan">angular-cli.git_init.prototype.</span>_super

#### [module angular-cli.github_pages_deploy](#apidoc.module.angular-cli.github_pages_deploy)
1.  [function <span class="apidocSignatureSpan">angular-cli.github_pages_deploy.</span>default ()](#apidoc.element.angular-cli.github_pages_deploy.default)

#### [module angular-cli.github_pages_deploy_run](#apidoc.module.angular-cli.github_pages_deploy_run)
1.  [function <span class="apidocSignatureSpan">angular-cli.github_pages_deploy_run.</span>default (options, rawArgs)](#apidoc.element.angular-cli.github_pages_deploy_run.default)

#### [module angular-cli.glob_copy_webpack_plugin](#apidoc.module.angular-cli.glob_copy_webpack_plugin)
1.  [function <span class="apidocSignatureSpan">angular-cli.glob_copy_webpack_plugin.</span>GlobCopyWebpackPlugin (options)](#apidoc.element.angular-cli.glob_copy_webpack_plugin.GlobCopyWebpackPlugin)

#### [module angular-cli.help](#apidoc.module.angular-cli.help)
1.  [function <span class="apidocSignatureSpan">angular-cli.help.</span>default ()](#apidoc.element.angular-cli.help.default)

#### [module angular-cli.init](#apidoc.module.angular-cli.init)
1.  [function <span class="apidocSignatureSpan">angular-cli.init.</span>default ()](#apidoc.element.angular-cli.init.default)

#### [module angular-cli.init_run](#apidoc.module.angular-cli.init_run)
1.  [function <span class="apidocSignatureSpan">angular-cli.init_run.</span>default (commandOptions, rawArgs)](#apidoc.element.angular-cli.init_run.default)

#### [module angular-cli.lint](#apidoc.module.angular-cli.lint)
1.  [function <span class="apidocSignatureSpan">angular-cli.lint.</span>default ()](#apidoc.element.angular-cli.lint.default)

#### [module angular-cli.new](#apidoc.module.angular-cli.new)
1.  [function <span class="apidocSignatureSpan">angular-cli.new.</span>default ()](#apidoc.element.angular-cli.new.default)

#### [module angular-cli.npm_install](#apidoc.module.angular-cli.npm_install)
1.  [function <span class="apidocSignatureSpan">angular-cli.npm_install.</span>default ()](#apidoc.element.angular-cli.npm_install.default)

#### [module angular-cli.package_chunk_sort](#apidoc.module.angular-cli.package_chunk_sort)
1.  [function <span class="apidocSignatureSpan">angular-cli.package_chunk_sort.</span>packageChunkSort (appConfig)](#apidoc.element.angular-cli.package_chunk_sort.packageChunkSort)

#### [module angular-cli.prerender_webpack_plugin](#apidoc.module.angular-cli.prerender_webpack_plugin)
1.  [function <span class="apidocSignatureSpan">angular-cli.prerender_webpack_plugin.</span>PrerenderWebpackPlugin (options)](#apidoc.element.angular-cli.prerender_webpack_plugin.PrerenderWebpackPlugin)

#### [module angular-cli.require_project_module](#apidoc.module.angular-cli.require_project_module)
1.  [function <span class="apidocSignatureSpan">angular-cli.require_project_module.</span>requireDependency (root, moduleName)](#apidoc.element.angular-cli.require_project_module.requireDependency)

#### [module angular-cli.serve](#apidoc.module.angular-cli.serve)
1.  [function <span class="apidocSignatureSpan">angular-cli.serve.</span>default ()](#apidoc.element.angular-cli.serve.default)

#### [module angular-cli.serve_run](#apidoc.module.angular-cli.serve_run)
1.  [function <span class="apidocSignatureSpan">angular-cli.serve_run.</span>default (commandOptions)](#apidoc.element.angular-cli.serve_run.default)

#### [module angular-cli.set](#apidoc.module.angular-cli.set)
1.  [function <span class="apidocSignatureSpan">angular-cli.set.</span>default ()](#apidoc.element.angular-cli.set.default)

#### [module angular-cli.suppress_entry_chunks_webpack_plugin](#apidoc.module.angular-cli.suppress_entry_chunks_webpack_plugin)
1.  [function <span class="apidocSignatureSpan">angular-cli.suppress_entry_chunks_webpack_plugin.</span>SuppressExtractedTextChunksWebpackPlugin ()](#apidoc.element.angular-cli.suppress_entry_chunks_webpack_plugin.SuppressExtractedTextChunksWebpackPlugin)

#### [module angular-cli.version](#apidoc.module.angular-cli.version)
1.  [function <span class="apidocSignatureSpan">angular-cli.version.</span>default ()](#apidoc.element.angular-cli.version.default)

#### [module angular-cli.webpack_config](#apidoc.module.angular-cli.webpack_config)
1.  [function <span class="apidocSignatureSpan">angular-cli.webpack_config.</span>NgCliWebpackConfig (buildOptions)](#apidoc.element.angular-cli.webpack_config.NgCliWebpackConfig)



# <a name="apidoc.module.angular-cli"></a>[module angular-cli](#apidoc.module.angular-cli)

#### <a name="apidoc.element.angular-cli.git_init"></a>[function <span class="apidocSignatureSpan">angular-cli.</span>git_init ()](#apidoc.element.angular-cli.git_init)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.config"></a>[module angular-cli.config](#apidoc.module.angular-cli.config)

#### <a name="apidoc.element.angular-cli.config.CliConfig"></a>[function <span class="apidocSignatureSpan">angular-cli.config.</span>CliConfig ()](#apidoc.element.angular-cli.config.CliConfig)
- description and source-code
```javascript
function CliConfig() {
    _super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.create_github_repo"></a>[module angular-cli.create_github_repo](#apidoc.module.angular-cli.create_github_repo)

#### <a name="apidoc.element.angular-cli.create_github_repo.default"></a>[function <span class="apidocSignatureSpan">angular-cli.create_github_repo.</span>default ()](#apidoc.element.angular-cli.create_github_repo.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.destroy"></a>[module angular-cli.destroy](#apidoc.module.angular-cli.destroy)

#### <a name="apidoc.element.angular-cli.destroy.default"></a>[function <span class="apidocSignatureSpan">angular-cli.destroy.</span>default ()](#apidoc.element.angular-cli.destroy.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.doc"></a>[module angular-cli.doc](#apidoc.module.angular-cli.doc)

#### <a name="apidoc.element.angular-cli.doc.default"></a>[function <span class="apidocSignatureSpan">angular-cli.doc.</span>default ()](#apidoc.element.angular-cli.doc.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.e2e"></a>[module angular-cli.e2e](#apidoc.module.angular-cli.e2e)

#### <a name="apidoc.element.angular-cli.e2e.default"></a>[function <span class="apidocSignatureSpan">angular-cli.e2e.</span>default ()](#apidoc.element.angular-cli.e2e.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.easter_egg"></a>[module angular-cli.easter_egg](#apidoc.module.angular-cli.easter_egg)

#### <a name="apidoc.element.angular-cli.easter_egg.default"></a>[function <span class="apidocSignatureSpan">angular-cli.easter_egg.</span>default ()](#apidoc.element.angular-cli.easter_egg.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.error"></a>[module angular-cli.error](#apidoc.module.angular-cli.error)

#### <a name="apidoc.element.angular-cli.error.NgToolkitError"></a>[function <span class="apidocSignatureSpan">angular-cli.error.</span>NgToolkitError (message)](#apidoc.element.angular-cli.error.NgToolkitError)
- description and source-code
```javascript
function NgToolkitError(message) {
    _super.call(this);
    if (message) {
        this.message = message;
    }
    else {
        this.message = this.constructor.name;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.find_parent_module"></a>[module angular-cli.find_parent_module](#apidoc.module.angular-cli.find_parent_module)

#### <a name="apidoc.element.angular-cli.find_parent_module.default"></a>[function <span class="apidocSignatureSpan">angular-cli.find_parent_module.</span>default (project, currentDir)](#apidoc.element.angular-cli.find_parent_module.default)
- description and source-code
```javascript
function findParentModule(project, currentDir) {
    var sourceRoot = path.join(project.root, project.ngConfig.apps[0].root, 'app');
    // trim currentDir
    currentDir = currentDir.replace(path.join(project.ngConfig.apps[0].root, 'app'), '');
    var pathToCheck = path.join(sourceRoot, currentDir);
    while (pathToCheck.length >= sourceRoot.length) {
        // TODO: refactor to not be based upon file name
        var files = fs.readdirSync(pathToCheck)
            .filter(function (fileName) { return !fileName.endsWith('routing.module.ts'); })
            .filter(function (fileName) { return fileName.endsWith('.module.ts'); })
            .filter(function (fileName) { return fs.statSync(path.join(pathToCheck, fileName)).isFile(); });
        if (files.length === 1) {
            return path.join(pathToCheck, files[0]);
        }
        else if (files.length > 1) {
            throw new SilentError("Multiple module files found: " + pathToCheck.replace(sourceRoot, ''));
        }
        // move to parent directory
        pathToCheck = path.dirname(pathToCheck);
    }
    throw new SilentError('No module files found');
}
```
- example usage
```shell
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.generate"></a>[module angular-cli.generate](#apidoc.module.angular-cli.generate)

#### <a name="apidoc.element.angular-cli.generate.default"></a>[function <span class="apidocSignatureSpan">angular-cli.generate.</span>default ()](#apidoc.element.angular-cli.generate.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.get"></a>[module angular-cli.get](#apidoc.module.angular-cli.get)

#### <a name="apidoc.element.angular-cli.get.default"></a>[function <span class="apidocSignatureSpan">angular-cli.get.</span>default ()](#apidoc.element.angular-cli.get.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.get_dependent_files"></a>[module angular-cli.get_dependent_files](#apidoc.module.angular-cli.get_dependent_files)

#### <a name="apidoc.element.angular-cli.get_dependent_files.createTsSourceFile"></a>[function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>createTsSourceFile (fileName)](#apidoc.element.angular-cli.get_dependent_files.createTsSourceFile)
- description and source-code
```javascript
function createTsSourceFile(fileName) {
    return readFile(fileName, 'utf8')
        .then(function (contents) {
        return ts.createSourceFile(fileName, contents, ts.ScriptTarget.Latest, true);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.angular-cli.get_dependent_files.getAllAssociatedFiles"></a>[function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getAllAssociatedFiles (fileName)](#apidoc.element.angular-cli.get_dependent_files.getAllAssociatedFiles)
- description and source-code
```javascript
function getAllAssociatedFiles(fileName) {
    var fileDirName = path.dirname(fileName);
    var componentName = path.basename(fileName, '.ts');
    return globSearch(path.join(fileDirName, componentName + ".*"), { nodir: true })
        .then(function (files) {
        return files.filter(function (file) {
            return (path.basename(file) !== 'index.ts');
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.angular-cli.get_dependent_files.getDependentFiles"></a>[function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getDependentFiles (fileName, rootPath)](#apidoc.element.angular-cli.get_dependent_files.getDependentFiles)
- description and source-code
```javascript
function getDependentFiles(fileName, rootPath) {
    return globSearch(path.join(rootPath, '**/*.ts'), { nodir: true })
        .then(function (files) { return Promise.all(files.map(function (file) { return createTsSourceFile(file); }))
        .then(function (tsFiles) { return tsFiles.map(function (file) { return getImportClauses(file); }); })
        .then(function (moduleSpecifiers) {
        var allFiles = {};
        files.forEach(function (file, index) {
            var sourcePath = path.normalize(file);
            allFiles[sourcePath] = moduleSpecifiers[index];
        });
        return allFiles;
    })
        .then(function (allFiles) {
        var relevantFiles = {};
        Object.keys(allFiles).forEach(function (filePath) {
            var tempModuleSpecifiers = allFiles[filePath]
                .filter(function (importClause) {
                // Filter only relative imports
                var singleSlash = importClause.specifierText.charAt(0) === '/';
                var currentDirSyntax = importClause.specifierText.slice(0, 2) === './';
                var parentDirSyntax = importClause.specifierText.slice(0, 3) === '../';
                return singleSlash || currentDirSyntax || parentDirSyntax;
            })
                .filter(function (importClause) {
                var modulePath = path.resolve(path.dirname(filePath), importClause.specifierText);
                var resolvedFileName = path.resolve(fileName);
                var fileBaseName = path.basename(resolvedFileName, '.ts');
                var parsedFilePath = path.join(path.dirname(resolvedFileName), fileBaseName);
                return (parsedFilePath === modulePath) || (resolvedFileName === modulePath);
            });
            if (tempModuleSpecifiers.length > 0) {
                relevantFiles[filePath] = tempModuleSpecifiers;
            }
            ;
        });
        return relevantFiles;
    }); });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.angular-cli.get_dependent_files.getImportClauses"></a>[function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>getImportClauses (node)](#apidoc.element.angular-cli.get_dependent_files.getImportClauses)
- description and source-code
```javascript
function getImportClauses(node) {
    return node.statements
        .filter(function (node) { return node.kind === ts.SyntaxKind.ImportDeclaration; }) // Only Imports.
        .map(function (node) {
        var moduleSpecifier = node.moduleSpecifier;
        return {
            specifierText: moduleSpecifier.getText().slice(1, -1),
            pos: moduleSpecifier.pos,
            end: moduleSpecifier.end
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.angular-cli.get_dependent_files.hasIndexFile"></a>[function <span class="apidocSignatureSpan">angular-cli.get_dependent_files.</span>hasIndexFile (dirPath)](#apidoc.element.angular-cli.get_dependent_files.hasIndexFile)
- description and source-code
```javascript
function hasIndexFile(dirPath) {
    return globSearch(path.join(dirPath, 'index.ts'), { nodir: true })
        .then(function (indexFile) {
        return indexFile.length > 0;
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.git_init"></a>[module angular-cli.git_init](#apidoc.module.angular-cli.git_init)

#### <a name="apidoc.element.angular-cli.git_init.git_init"></a>[function <span class="apidocSignatureSpan">angular-cli.</span>git_init ()](#apidoc.element.angular-cli.git_init.git_init)
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



# <a name="apidoc.module.angular-cli.git_init.prototype"></a>[module angular-cli.git_init.prototype](#apidoc.module.angular-cli.git_init.prototype)

#### <a name="apidoc.element.angular-cli.git_init.prototype.constructor"></a>[function <span class="apidocSignatureSpan">angular-cli.git_init.prototype.</span>constructor ()](#apidoc.element.angular-cli.git_init.prototype.constructor)
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

#### <a name="apidoc.element.angular-cli.git_init.prototype.run"></a>[function <span class="apidocSignatureSpan">angular-cli.git_init.prototype.</span>run (commandOptions)](#apidoc.element.angular-cli.git_init.prototype.run)
- description and source-code
```javascript
run = function (commandOptions) {
  var chalk = require('chalk');
  var ui = this.ui;

  if (commandOptions.skipGit) {
    return Promise.resolve();
  }

  return exec('git --version')
    .then(function () {
      // check if we're inside a git repo
      return exec('git rev-parse --is-inside-work-tree')
        .then(function () {
          return true;
        })
        .catch(function() {
          return false;
        })
    })
    .then(function (insideGitRepo) {
      if (insideGitRepo) {
        return ui.writeLine('Directory is already under version control. Skipping initialization of git.');
      }
      return exec('git init')
        .then(function () {
          return exec('git add .');
        })
        .then(function () {
          if (!commandOptions.skipCommit) {
            var commitTemplate = fs.readFileSync(
              path.join(__dirname, '../utilities/INITIAL_COMMIT_MESSAGE.txt'));
            var commitMessage = template(commitTemplate)(pkg);
            return exec(
              'git commit -m "' + commitMessage + '"', { env: gitEnvironmentVariables });
          }
        })
        .then(function () {
          ui.writeLine(chalk.green('Successfully initialized git.'));
        });
    })
    .catch(function (/*error*/) {
      // if git is not found or an error was thrown during the 'git'
      // init process just swallow any errors here
    });
}
```
- example usage
```shell
...
    ],
    run: function (commandOptions, rawArgs) {
        var keyword = rawArgs[0];
        var docTask = new doc_1.DocTask({
            ui: this.ui,
            project: this.project
        });
        return docTask.run(keyword);
    }
});
Object.defineProperty(exports, "__esModule", { value: true });
exports.default = DocCommand;
//# sourceMappingURL=/Users/hans/Sources/angular-cli/packages/angular-cli/commands/doc.js.map
...
```



# <a name="apidoc.module.angular-cli.github_pages_deploy"></a>[module angular-cli.github_pages_deploy](#apidoc.module.angular-cli.github_pages_deploy)

#### <a name="apidoc.element.angular-cli.github_pages_deploy.default"></a>[function <span class="apidocSignatureSpan">angular-cli.github_pages_deploy.</span>default ()](#apidoc.element.angular-cli.github_pages_deploy.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.github_pages_deploy_run"></a>[module angular-cli.github_pages_deploy_run](#apidoc.module.angular-cli.github_pages_deploy_run)

#### <a name="apidoc.element.angular-cli.github_pages_deploy_run.default"></a>[function <span class="apidocSignatureSpan">angular-cli.github_pages_deploy_run.</span>default (options, rawArgs)](#apidoc.element.angular-cli.github_pages_deploy_run.default)
- description and source-code
```javascript
function githubPagesDeployRun(options, rawArgs) {
    var ui = this.ui;
    var root = this.project.root;
    var execOptions = {
        cwd: root
    };
    if (options.environment === '') {
        if (options.target === 'development') {
            options.environment = 'dev';
        }
        if (options.target === 'production') {
            options.environment = 'prod';
        }
    }
    var projectName = this.project.pkg.name;
    var outDir = config_1.CliConfig.fromProject().config.apps[0].outDir;
    var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
    var ghPagesBranch = 'gh-pages';
    var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
    var initialBranch;
    var branchErrMsg = ' You might also need to return to the initial branch manually.';
    // declared here so that tests can stub exec
    var execPromise = denodeify(child_process_1.exec);
    var buildTask = new build_1.default({
        ui: this.ui,
        cliProject: this.project,
        target: options.target,
        environment: options.environment,
        outputPath: outDir
    });
<span class="apidocCodeCommentSpan">    /**
     * BaseHref tag setting logic:
     * First, no value if --custom-domain is provided.
     * Second, use --base-href flag value if provided.
     * Else if --user-page is true, then keep baseHref default as declared in index.html.
     * Otherwise auto-replace with '/${projectName}/'.
     */
</span>    var baseHref = null;
    if (!options.customDomain) {
        baseHref = options.baseHref || (options.userPage ? null : "/" + projectName + "/");
    }
    var buildOptions = {
        target: options.target,
        environment: options.environment,
        outputPath: outDir,
        baseHref: baseHref,
        aot: options.aot,
        vendorChunk: options.vendorChunk,
    };
    var createGithubRepoTask = new create_github_repo_1.default({
        ui: this.ui,
        project: this.project
    });
    var createGithubRepoOptions = {
        projectName: projectName,
        ghUsername: options.ghUsername,
        ghToken: options.ghToken
    };
    return checkForPendingChanges()
        .then(build)
        .then(saveStartingBranchName)
        .then(createGitHubRepoIfNeeded)
        .then(checkoutGhPages)
        .then(cleanGhPagesBranch)
        .then(copyFiles)
        .then(createNotFoundPage)
        .then(createCustomDomainFile)
        .then(addAndCommit)
        .then(returnStartingBranch)
        .then(pushToGitRepo)
        .then(printProjectUrl)
        .catch(failGracefully);
    function checkForPendingChanges() {
        return execPromise('git status --porcelain')
            .then(function (stdout) {
            if (/\w+/m.test(stdout)) {
                var msg = 'Uncommitted file changes found! Please commit all changes before deploying.';
                return Promise.reject(new SilentError(msg));
            }
        });
    }
    function build() {
        if (options.skipBuild) {
            return Promise.resolve();
        }
        return buildTask.run(buildOptions);
    }
    function saveStartingBranchName() {
        return execPromise('git rev-parse --abbrev-ref HEAD')
            .then(function (stdout) { return initialBranch = stdout.replace(/\s/g, ''); });
    }
    function createGitHubRepoIfNeeded() {
        return execPromise('git remote -v')
            .then(function (stdout) {
            if (!/origin\s+(https:\/\/|git@)github\.com/m.test(stdout)) {
                return createGithubRepoTask.run(createGithubRepoOptions)
                    .then(function () { return generateRemoteUrl(); })
                    .then(function (upstream) {
                    // only push starting branch if it's not the destinationBranch
                    // this happens commonly when using github user pages, since
                    // they require the destination branch to be 'master'
                    if (destinationBranch !== initialBranch) {
                        execPromise("git push -u " + upstream + " " + initialBranch);
                    }
                }); ...
```
- example usage
```shell
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.glob_copy_webpack_plugin"></a>[module angular-cli.glob_copy_webpack_plugin](#apidoc.module.angular-cli.glob_copy_webpack_plugin)

#### <a name="apidoc.element.angular-cli.glob_copy_webpack_plugin.GlobCopyWebpackPlugin"></a>[function <span class="apidocSignatureSpan">angular-cli.glob_copy_webpack_plugin.</span>GlobCopyWebpackPlugin (options)](#apidoc.element.angular-cli.glob_copy_webpack_plugin.GlobCopyWebpackPlugin)
- description and source-code
```javascript
function GlobCopyWebpackPlugin(options) {
    this.options = options;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.help"></a>[module angular-cli.help](#apidoc.module.angular-cli.help)

#### <a name="apidoc.element.angular-cli.help.default"></a>[function <span class="apidocSignatureSpan">angular-cli.help.</span>default ()](#apidoc.element.angular-cli.help.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.init"></a>[module angular-cli.init](#apidoc.module.angular-cli.init)

#### <a name="apidoc.element.angular-cli.init.default"></a>[function <span class="apidocSignatureSpan">angular-cli.init.</span>default ()](#apidoc.element.angular-cli.init.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.init_run"></a>[module angular-cli.init_run](#apidoc.module.angular-cli.init_run)

#### <a name="apidoc.element.angular-cli.init_run.default"></a>[function <span class="apidocSignatureSpan">angular-cli.init_run.</span>default (commandOptions, rawArgs)](#apidoc.element.angular-cli.init_run.default)
- description and source-code
```javascript
function initRun(commandOptions, rawArgs) {
    var _this = this;
    if (commandOptions.dryRun) {
        commandOptions.skipNpm = true;
    }
    var installBlueprint = new this.tasks.InstallBlueprint({
        ui: this.ui,
        project: this.project
    });
    // needs an explicit check in case it's just 'undefined'
    // due to passing of options from 'new' and 'addon'
    var gitInit;
    if (commandOptions.skipGit === false) {
        gitInit = new GitInit({
            ui: this.ui,
            project: this.project
        });
    }
    var npmInstall;
    if (!commandOptions.skipNpm) {
        npmInstall = new npm_install_1.default({
            ui: this.ui,
            project: this.project
        });
    }
    var linkCli;
    if (commandOptions.linkCli) {
        linkCli = new link_cli_1.default({
            ui: this.ui,
            project: this.project
        });
    }
    var project = this.project;
    var packageName = commandOptions.name !== '.' && commandOptions.name || project.name();
    if (!packageName) {
        var message = 'The 'ng ' + this.name + '' command requires a ' +
            'package.json in current folder with name attribute or a specified name via arguments. ' +
            'For more details, use 'ng help'.';
        return Promise.reject(new SilentError(message));
    }
    var blueprintOpts = {
        dryRun: commandOptions.dryRun,
        blueprint: 'ng2',
        rawName: packageName,
        targetFiles: rawArgs || '',
        rawArgs: rawArgs.toString(),
        sourceDir: commandOptions.sourceDir,
        style: commandOptions.style,
        prefix: commandOptions.prefix,
        routing: commandOptions.routing,
        inlineStyle: commandOptions.inlineStyle,
        inlineTemplate: commandOptions.inlineTemplate,
        ignoredUpdateFiles: ['favicon.ico'],
        skipGit: commandOptions.skipGit,
        skipTests: commandOptions.skipTests
    };
    if (!validProjectName(packageName)) {
        return Promise.reject(new SilentError('We currently do not support a name of '' + packageName + ''.'));
    }
    blueprintOpts.blueprint = normalizeBlueprint(blueprintOpts.blueprint);
    return installBlueprint.run(blueprintOpts)
        .then(function () {
        if (commandOptions.skipGit === false) {
            return gitInit.run(commandOptions, rawArgs);
        }
    })
        .then(function () {
        if (!commandOptions.skipNpm) {
            return npmInstall.run();
        }
    })
        .then(function () {
        if (commandOptions.linkCli) {
            return linkCli.run();
        }
    })
        .then(function () {
        _this.ui.writeLine(chalk.green("Project '" + packageName + "' successfully created."));
    });
}
```
- example usage
```shell
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.lint"></a>[module angular-cli.lint](#apidoc.module.angular-cli.lint)

#### <a name="apidoc.element.angular-cli.lint.default"></a>[function <span class="apidocSignatureSpan">angular-cli.lint.</span>default ()](#apidoc.element.angular-cli.lint.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.new"></a>[module angular-cli.new](#apidoc.module.angular-cli.new)

#### <a name="apidoc.element.angular-cli.new.default"></a>[function <span class="apidocSignatureSpan">angular-cli.new.</span>default ()](#apidoc.element.angular-cli.new.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.npm_install"></a>[module angular-cli.npm_install](#apidoc.module.angular-cli.npm_install)

#### <a name="apidoc.element.angular-cli.npm_install.default"></a>[function <span class="apidocSignatureSpan">angular-cli.npm_install.</span>default ()](#apidoc.element.angular-cli.npm_install.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.package_chunk_sort"></a>[module angular-cli.package_chunk_sort](#apidoc.module.angular-cli.package_chunk_sort)

#### <a name="apidoc.element.angular-cli.package_chunk_sort.packageChunkSort"></a>[function <span class="apidocSignatureSpan">angular-cli.package_chunk_sort.</span>packageChunkSort (appConfig)](#apidoc.element.angular-cli.package_chunk_sort.packageChunkSort)
- description and source-code
```javascript
function packageChunkSort(appConfig) {
    var entryPoints = ['inline', 'polyfills'];
    var pushExtraEntries = function (extraEntry) {
        if (entryPoints.indexOf(extraEntry.entry) === -1) {
            entryPoints.push(extraEntry.entry);
        }
    };
    if (appConfig.scripts) {
        utils_1.extraEntryParser(appConfig.scripts, './', 'scripts').forEach(pushExtraEntries);
    }
    if (appConfig.styles) {
        utils_1.extraEntryParser(appConfig.styles, './', 'styles').forEach(pushExtraEntries);
    }
    entryPoints.push.apply(entryPoints, ['vendor', 'main']);
    return function sort(left, right) {
        var leftIndex = entryPoints.indexOf(left.names[0]);
        var rightindex = entryPoints.indexOf(right.names[0]);
        if (leftIndex > rightindex) {
            return 1;
        }
        else if (leftIndex < rightindex) {
            return -1;
        }
        else {
            return 0;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.prerender_webpack_plugin"></a>[module angular-cli.prerender_webpack_plugin](#apidoc.module.angular-cli.prerender_webpack_plugin)

#### <a name="apidoc.element.angular-cli.prerender_webpack_plugin.PrerenderWebpackPlugin"></a>[function <span class="apidocSignatureSpan">angular-cli.prerender_webpack_plugin.</span>PrerenderWebpackPlugin (options)](#apidoc.element.angular-cli.prerender_webpack_plugin.PrerenderWebpackPlugin)
- description and source-code
```javascript
function PrerenderWebpackPlugin(options) {
    this.options = options;
    // maintain your platform instance
    this.bootloader = require(this.options.configPath).getBootloader();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.require_project_module"></a>[module angular-cli.require_project_module](#apidoc.module.angular-cli.require_project_module)

#### <a name="apidoc.element.angular-cli.require_project_module.requireDependency"></a>[function <span class="apidocSignatureSpan">angular-cli.require_project_module.</span>requireDependency (root, moduleName)](#apidoc.element.angular-cli.require_project_module.requireDependency)
- description and source-code
```javascript
function requireDependency(root, moduleName) {
    var packageJson = require(path.join(root, 'node_modules', moduleName, 'package.json'));
    var main = path.normalize(packageJson.main);
    return require(path.join(root, 'node_modules', moduleName, main));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.serve"></a>[module angular-cli.serve](#apidoc.module.angular-cli.serve)

#### <a name="apidoc.element.angular-cli.serve.default"></a>[function <span class="apidocSignatureSpan">angular-cli.serve.</span>default ()](#apidoc.element.angular-cli.serve.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.serve_run"></a>[module angular-cli.serve_run](#apidoc.module.angular-cli.serve_run)

#### <a name="apidoc.element.angular-cli.serve_run.default"></a>[function <span class="apidocSignatureSpan">angular-cli.serve_run.</span>default (commandOptions)](#apidoc.element.angular-cli.serve_run.default)
- description and source-code
```javascript
function serveRun(commandOptions) {
    var _this = this;
    // Check angular version.
    version_1.Version.assertAngularVersionIs2_3_1OrHigher(this.project.root);
    commandOptions.liveReloadHost = commandOptions.liveReloadHost || commandOptions.host;
    return checkExpressPort(commandOptions)
        .then(function () { return autoFindLiveReloadPort(commandOptions); })
        .then(function (opts) {
        var serve = new serve_1.default({
            ui: _this.ui,
            project: _this.project,
        });
        return serve.run(opts);
    });
}
```
- example usage
```shell
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.set"></a>[module angular-cli.set](#apidoc.module.angular-cli.set)

#### <a name="apidoc.element.angular-cli.set.default"></a>[function <span class="apidocSignatureSpan">angular-cli.set.</span>default ()](#apidoc.element.angular-cli.set.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.suppress_entry_chunks_webpack_plugin"></a>[module angular-cli.suppress_entry_chunks_webpack_plugin](#apidoc.module.angular-cli.suppress_entry_chunks_webpack_plugin)

#### <a name="apidoc.element.angular-cli.suppress_entry_chunks_webpack_plugin.SuppressExtractedTextChunksWebpackPlugin"></a>[function <span class="apidocSignatureSpan">angular-cli.suppress_entry_chunks_webpack_plugin.</span>SuppressExtractedTextChunksWebpackPlugin ()](#apidoc.element.angular-cli.suppress_entry_chunks_webpack_plugin.SuppressExtractedTextChunksWebpackPlugin)
- description and source-code
```javascript
function SuppressExtractedTextChunksWebpackPlugin() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.angular-cli.version"></a>[module angular-cli.version](#apidoc.module.angular-cli.version)

#### <a name="apidoc.element.angular-cli.version.default"></a>[function <span class="apidocSignatureSpan">angular-cli.version.</span>default ()](#apidoc.element.angular-cli.version.default)
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
...
var indexFilename = config_1.CliConfig.fromProject().config.apps[0].index;
var ghPagesBranch = 'gh-pages';
var destinationBranch = options.userPage ? 'master' : ghPagesBranch;
var initialBranch;
var branchErrMsg = ' You might also need to return to the initial branch manually.';
// declared here so that tests can stub exec
var execPromise = denodeify(child_process_1.exec);
var buildTask = new build_1.default({
    ui: this.ui,
    cliProject: this.project,
    target: options.target,
    environment: options.environment,
    outputPath: outDir
});
/**
...
```



# <a name="apidoc.module.angular-cli.webpack_config"></a>[module angular-cli.webpack_config](#apidoc.module.angular-cli.webpack_config)

#### <a name="apidoc.element.angular-cli.webpack_config.NgCliWebpackConfig"></a>[function <span class="apidocSignatureSpan">angular-cli.webpack_config.</span>NgCliWebpackConfig (buildOptions)](#apidoc.element.angular-cli.webpack_config.NgCliWebpackConfig)
- description and source-code
```javascript
function NgCliWebpackConfig(buildOptions) {
    this.validateBuildOptions(buildOptions);
    var configPath = config_1.CliConfig.configFilePath();
    var projectRoot = path.dirname(configPath);
    var appConfig = config_1.CliConfig.fromProject().config.apps[0];
    appConfig = this.addAppConfigDefaults(appConfig);
    buildOptions = this.addTargetDefaults(buildOptions);
    buildOptions = this.mergeConfigs(buildOptions, appConfig);
    var wco = { projectRoot: projectRoot, buildOptions: buildOptions, appConfig: appConfig };
    var webpackConfigs = [
        webpack_configs_1.getCommonConfig(wco),
        webpack_configs_1.getStylesConfig(wco),
        this.getTargetConfig(wco)
    ];
    if (appConfig.main || appConfig.polyfills) {
        var typescriptConfigPartial = buildOptions.aot
            ? webpack_configs_1.getAotConfig(wco)
            : webpack_configs_1.getNonAotConfig(wco);
        webpackConfigs.push(typescriptConfigPartial);
    }
    // add style config
    this.config = webpackMerge(webpackConfigs);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
