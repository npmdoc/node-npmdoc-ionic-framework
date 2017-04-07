# api documentation for  [ionic-framework (v2.0.0-beta.2)](https://github.com/driftyco/ionic/tree/2.0%60#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ionic-framework.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ionic-framework) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ionic-framework.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ionic-framework)
#### An advanced HTML5 mobile app framework built on Angular2

[![NPM](https://nodei.co/npm/ionic-framework.png?downloads=true)](https://www.npmjs.com/package/ionic-framework)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ionic-framework/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ionic-framework_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ionic-framework/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ionic-framework/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ionic-framework/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/driftyco/ionic/issues"
    },
    "dependencies": {
        "colors": "^1.1.2",
        "inquirer": "0.11.0",
        "lodash": "3.10.1",
        "mkdirp-no-bin": "0.5.1",
        "q": "1.4.1"
    },
    "description": "An advanced HTML5 mobile app framework built on Angular2",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "0990ec8fdbc22558dd7f7c81e8517a0778105c2d",
        "tarball": "https://registry.npmjs.org/ionic-framework/-/ionic-framework-2.0.0-beta.2.tgz"
    },
    "homepage": "https://github.com/driftyco/ionic/tree/2.0%60#readme",
    "keywords": [
        "ionic",
        "framework",
        "mobile",
        "app",
        "hybrid",
        "webapp",
        "cordova"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "adamdbradley",
            "email": "hi+adam@ionicframework.com"
        },
        {
            "name": "brandyscarney",
            "email": "brandy@ionic.io"
        },
        {
            "name": "drifty",
            "email": "max@drifty.com"
        },
        {
            "name": "mhartington",
            "email": "mikehartington@gmail.com"
        },
        {
            "name": "perrygovier",
            "email": "perry@ionic.io"
        },
        {
            "name": "tlancina",
            "email": "tim@ionic.io"
        }
    ],
    "name": "ionic-framework",
    "optionalDependencies": {},
    "peerDependencies": {
        "angular2": "^2.0.0-beta.6"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/driftyco/ionic.git#2.0'"
    },
    "scripts": {},
    "version": "2.0.0-beta.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ionic-framework](#apidoc.module.ionic-framework)
1.  [function <span class="apidocSignatureSpan">ionic-framework.</span>generator (options)](#apidoc.element.ionic-framework.generator)
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>click_block
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>events
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>feature_detect
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>generate
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>generator.prototype
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>translate
1.  object <span class="apidocSignatureSpan">ionic-framework.</span>util

#### [module ionic-framework.click_block](#apidoc.module.ionic-framework.click_block)
1.  [function <span class="apidocSignatureSpan">ionic-framework.click_block.</span>ClickBlock ()](#apidoc.element.ionic-framework.click_block.ClickBlock)

#### [module ionic-framework.events](#apidoc.module.ionic-framework.events)
1.  [function <span class="apidocSignatureSpan">ionic-framework.events.</span>Events ()](#apidoc.element.ionic-framework.events.Events)

#### [module ionic-framework.feature_detect](#apidoc.module.ionic-framework.feature_detect)
1.  [function <span class="apidocSignatureSpan">ionic-framework.feature_detect.</span>FeatureDetect ()](#apidoc.element.ionic-framework.feature_detect.FeatureDetect)

#### [module ionic-framework.generate](#apidoc.module.ionic-framework.generate)
1.  [function <span class="apidocSignatureSpan">ionic-framework.</span>generate (options)](#apidoc.element.ionic-framework.generate.generate)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generate.</span>loadGenerator (generator)](#apidoc.element.ionic-framework.generate.loadGenerator)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generate.</span>loadGenerators ()](#apidoc.element.ionic-framework.generate.loadGenerators)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generate.</span>printAvailableGenerators ()](#apidoc.element.ionic-framework.generate.printAvailableGenerators)
1.  object <span class="apidocSignatureSpan">ionic-framework.generate.</span>_generators
1.  object <span class="apidocSignatureSpan">ionic-framework.generate.</span>generators

#### [module ionic-framework.generator](#apidoc.module.ionic-framework.generator)
1.  [function <span class="apidocSignatureSpan">ionic-framework.</span>generator (options)](#apidoc.element.ionic-framework.generator.generator)

#### [module ionic-framework.generator.prototype](#apidoc.module.ionic-framework.generator.prototype)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>loadTemplates ()](#apidoc.element.ionic-framework.generator.prototype.loadTemplates)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>makeDirectories ()](#apidoc.element.ionic-framework.generator.prototype.makeDirectories)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>renderTemplate (template)](#apidoc.element.ionic-framework.generator.prototype.renderTemplate)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>renderTemplates ()](#apidoc.element.ionic-framework.generator.prototype.renderTemplates)
1.  [function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>run ()](#apidoc.element.ionic-framework.generator.prototype.run)

#### [module ionic-framework.translate](#apidoc.module.ionic-framework.translate)
1.  [function <span class="apidocSignatureSpan">ionic-framework.translate.</span>Translate ()](#apidoc.element.ionic-framework.translate.Translate)

#### [module ionic-framework.util](#apidoc.module.ionic-framework.util)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>assign ()](#apidoc.element.ionic-framework.util.assign)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>clamp (min, n, max)](#apidoc.element.ionic-framework.util.clamp)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>debounce (fn, wait, immediate)](#apidoc.element.ionic-framework.util.debounce)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>defaults (dest)](#apidoc.element.ionic-framework.util.defaults)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>getQuerystring (url)](#apidoc.element.ionic-framework.util.getQuerystring)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isArray ()](#apidoc.element.ionic-framework.util.isArray)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isBlank (val)](#apidoc.element.ionic-framework.util.isBlank)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isBoolean (val)](#apidoc.element.ionic-framework.util.isBoolean)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isDefined (val)](#apidoc.element.ionic-framework.util.isDefined)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isFunction (val)](#apidoc.element.ionic-framework.util.isFunction)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isNumber (val)](#apidoc.element.ionic-framework.util.isNumber)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isObject (val)](#apidoc.element.ionic-framework.util.isObject)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isString (val)](#apidoc.element.ionic-framework.util.isString)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isTrueProperty (val)](#apidoc.element.ionic-framework.util.isTrueProperty)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>isUndefined (val)](#apidoc.element.ionic-framework.util.isUndefined)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>merge (dst)](#apidoc.element.ionic-framework.util.merge)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>nextUid ()](#apidoc.element.ionic-framework.util.nextUid)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>pascalCaseToDashCase (val)](#apidoc.element.ionic-framework.util.pascalCaseToDashCase)
1.  [function <span class="apidocSignatureSpan">ionic-framework.util.</span>throttle (fn, wait, options)](#apidoc.element.ionic-framework.util.throttle)
1.  object <span class="apidocSignatureSpan">ionic-framework.util.</span>array



# <a name="apidoc.module.ionic-framework"></a>[module ionic-framework](#apidoc.module.ionic-framework)

#### <a name="apidoc.element.ionic-framework.generator"></a>[function <span class="apidocSignatureSpan">ionic-framework.</span>generator (options)](#apidoc.element.ionic-framework.generator)
- description and source-code
```javascript
function Generator(options) {
  this.name = options.name;
  this.type = options.generator;
  this.appDirectory = options.appDirectory;

  //templateVars
  this.fileName = _.kebabCase(this.name);
  this.jsClassName = _.capitalize(_.camelCase(this.name));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.click_block"></a>[module ionic-framework.click_block](#apidoc.module.ionic-framework.click_block)

#### <a name="apidoc.element.ionic-framework.click_block.ClickBlock"></a>[function <span class="apidocSignatureSpan">ionic-framework.click_block.</span>ClickBlock ()](#apidoc.element.ionic-framework.click_block.ClickBlock)
- description and source-code
```javascript
function ClickBlock() {
    this._enabled = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.events"></a>[module ionic-framework.events](#apidoc.module.ionic-framework.events)

#### <a name="apidoc.element.ionic-framework.events.Events"></a>[function <span class="apidocSignatureSpan">ionic-framework.events.</span>Events ()](#apidoc.element.ionic-framework.events.Events)
- description and source-code
```javascript
function Events() {
    this._channels = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.feature_detect"></a>[module ionic-framework.feature_detect](#apidoc.module.ionic-framework.feature_detect)

#### <a name="apidoc.element.ionic-framework.feature_detect.FeatureDetect"></a>[function <span class="apidocSignatureSpan">ionic-framework.feature_detect.</span>FeatureDetect ()](#apidoc.element.ionic-framework.feature_detect.FeatureDetect)
- description and source-code
```javascript
function FeatureDetect() {
    this._results = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.generate"></a>[module ionic-framework.generate](#apidoc.module.ionic-framework.generate)

#### <a name="apidoc.element.ionic-framework.generate.generate"></a>[function <span class="apidocSignatureSpan">ionic-framework.</span>generate (options)](#apidoc.element.ionic-framework.generate.generate)
- description and source-code
```javascript
function generate(options) {
  if (!options) {
    throw new Error('No options passed to generator');
  }

  if (!options.generator) {
    throw new Error('No generator passed to generate');
  }

  var GeneratorType = Generate.loadGenerator(options.generator);
  return new GeneratorType(options).run();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.generate.loadGenerator"></a>[function <span class="apidocSignatureSpan">ionic-framework.generate.</span>loadGenerator (generator)](#apidoc.element.ionic-framework.generate.loadGenerator)
- description and source-code
```javascript
function loadGenerator(generator) {
  var generateModule;
  try {
    generateModule = require(path.join(__dirname, 'generators', generator));
  } catch (err) {
    if (err.code === 'MODULE_NOT_FOUND') {
      throw new Error('There is no generator available with the name ' + generator + '.');
    } else {
      throw err;
    }
  }
  return generateModule;
}
```
- example usage
```shell
...
  throw new Error('No options passed to generator');
}

if (!options.generator) {
  throw new Error('No generator passed to generate');
}

var GeneratorType = Generate.loadGenerator(options.generator);
return new GeneratorType(options).run();
};


Generate.loadGenerator = function loadGenerator(generator) {
var generateModule;
try {
...
```

#### <a name="apidoc.element.ionic-framework.generate.loadGenerators"></a>[function <span class="apidocSignatureSpan">ionic-framework.generate.</span>loadGenerators ()](#apidoc.element.ionic-framework.generate.loadGenerators)
- description and source-code
```javascript
function loadGenerators() {
  var generators = {};
  try {
    generators = fs.readdirSync(path.join(__dirname, 'generators'));
  } catch(err) {
    throw new Error('There was an error loading the generators list', err);
  }
  return generators;
}
```
- example usage
```shell
...
  path = require('path'),
  inquirer = require('inquirer');

Generate = module.exports;

Generate.__defineGetter__('generators', function() {
if (!Generate._generators) {
  Generate._generators = Generate.loadGenerators();
}

return Generate._generators;
});

Generate.generate = function generate(options) {
if (!options) {
...
```

#### <a name="apidoc.element.ionic-framework.generate.printAvailableGenerators"></a>[function <span class="apidocSignatureSpan">ionic-framework.generate.</span>printAvailableGenerators ()](#apidoc.element.ionic-framework.generate.printAvailableGenerators)
- description and source-code
```javascript
function printAvailableGenerators() {
  console.log('Available generators:'.blue);
  Generate.generators.forEach(function(generator){
    console.log(' *'.blue, generator);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.generator"></a>[module ionic-framework.generator](#apidoc.module.ionic-framework.generator)

#### <a name="apidoc.element.ionic-framework.generator.generator"></a>[function <span class="apidocSignatureSpan">ionic-framework.</span>generator (options)](#apidoc.element.ionic-framework.generator.generator)
- description and source-code
```javascript
function Generator(options) {
  this.name = options.name;
  this.type = options.generator;
  this.appDirectory = options.appDirectory;

  //templateVars
  this.fileName = _.kebabCase(this.name);
  this.jsClassName = _.capitalize(_.camelCase(this.name));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.generator.prototype"></a>[module ionic-framework.generator.prototype](#apidoc.module.ionic-framework.generator.prototype)

#### <a name="apidoc.element.ionic-framework.generator.prototype.loadTemplates"></a>[function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>loadTemplates ()](#apidoc.element.ionic-framework.generator.prototype.loadTemplates)
- description and source-code
```javascript
loadTemplates = function () {
  var generatorPath = path.join(__dirname, 'generators', this.type);
  var templates = [];
  fs.readdirSync(generatorPath)
  .forEach(function(template) {
    var type;
    // Go through all the files in the folder, grab the templates, read in the file contents
    // return as template type, contents
    if (template.indexOf('.tmpl') == -1) {
      return;
    }

    templates.push({path: path.join(generatorPath, template), extension: path.extname(template)});
  }, this);

  return templates;
}
```
- example usage
```shell
...
if (!this.directory) {
  throw new Error('Generators must define their directory in their constructor.\nEx: \'pages\', \'components\', etc.');
}
mkdirp.sync(path.join(this.appDirectory, 'app', this.directory, this.fileName));
}

Generator.prototype.renderTemplates = function renderTemplates() {
var templates = this.loadTemplates();

templates.forEach(function(template) {
  var renderedTemplate = this.renderTemplate(template);
  var renderedTemplateDest = path.join(this.appDirectory, 'app', this.directory, this.fileName, this.fileName + template.extension
);
  console.log('√ Create'.blue, path.relative(this.appDirectory, renderedTemplateDest));
  fs.writeFileSync(renderedTemplateDest, renderedTemplate);
}, this);
...
```

#### <a name="apidoc.element.ionic-framework.generator.prototype.makeDirectories"></a>[function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>makeDirectories ()](#apidoc.element.ionic-framework.generator.prototype.makeDirectories)
- description and source-code
```javascript
makeDirectories = function (){
  if (!this.directory) {
    throw new Error('Generators must define their directory in their constructor.\nEx: \'pages\', \'components\', etc.');
  }
  mkdirp.sync(path.join(this.appDirectory, 'app', this.directory, this.fileName));
}
```
- example usage
```shell
...

//templateVars
this.fileName = _.kebabCase(this.name);
this.jsClassName = _.capitalize(_.camelCase(this.name));
}

Generator.prototype.run = function(){
this.makeDirectories();
this.renderTemplates();
}

Generator.prototype.makeDirectories = function(){
if (!this.directory) {
  throw new Error('Generators must define their directory in their constructor.\nEx: \'pages\', \'components\', etc.');
}
...
```

#### <a name="apidoc.element.ionic-framework.generator.prototype.renderTemplate"></a>[function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>renderTemplate (template)](#apidoc.element.ionic-framework.generator.prototype.renderTemplate)
- description and source-code
```javascript
renderTemplate = function (template) {
  var templateContents = fs.readFileSync(template.path, 'utf8');
  var templateCompiler = _.template(templateContents);
  var result = templateCompiler(this);
  return result;
}
```
- example usage
```shell
...
  mkdirp.sync(path.join(this.appDirectory, 'app', this.directory, this.fileName));
}

Generator.prototype.renderTemplates = function renderTemplates() {
  var templates = this.loadTemplates();

  templates.forEach(function(template) {
    var renderedTemplate = this.renderTemplate(template);
    var renderedTemplateDest = path.join(this.appDirectory, 'app', this.directory, this.fileName, this.fileName + template.extension
);
    console.log('√ Create'.blue, path.relative(this.appDirectory, renderedTemplateDest));
    fs.writeFileSync(renderedTemplateDest, renderedTemplate);
  }, this);
}

Generator.prototype.loadTemplates = function() {
...
```

#### <a name="apidoc.element.ionic-framework.generator.prototype.renderTemplates"></a>[function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>renderTemplates ()](#apidoc.element.ionic-framework.generator.prototype.renderTemplates)
- description and source-code
```javascript
function renderTemplates() {
  var templates = this.loadTemplates();

  templates.forEach(function(template) {
    var renderedTemplate = this.renderTemplate(template);
    var renderedTemplateDest = path.join(this.appDirectory, 'app', this.directory, this.fileName, this.fileName + template.extension
);
    console.log('√ Create'.blue, path.relative(this.appDirectory, renderedTemplateDest));
    fs.writeFileSync(renderedTemplateDest, renderedTemplate);
  }, this);
}
```
- example usage
```shell
...
//templateVars
this.fileName = _.kebabCase(this.name);
this.jsClassName = _.capitalize(_.camelCase(this.name));
}

Generator.prototype.run = function(){
this.makeDirectories();
this.renderTemplates();
}

Generator.prototype.makeDirectories = function(){
if (!this.directory) {
  throw new Error('Generators must define their directory in their constructor.\nEx: \'pages\', \'components\', etc.');
}
mkdirp.sync(path.join(this.appDirectory, 'app', this.directory, this.fileName));
...
```

#### <a name="apidoc.element.ionic-framework.generator.prototype.run"></a>[function <span class="apidocSignatureSpan">ionic-framework.generator.prototype.</span>run ()](#apidoc.element.ionic-framework.generator.prototype.run)
- description and source-code
```javascript
run = function (){
  this.makeDirectories();
  this.renderTemplates();
}
```
- example usage
```shell
...
}

if (!options.generator) {
  throw new Error('No generator passed to generate');
}

var GeneratorType = Generate.loadGenerator(options.generator);
return new GeneratorType(options).run();
};


Generate.loadGenerator = function loadGenerator(generator) {
var generateModule;
try {
  generateModule = require(path.join(__dirname, 'generators', generator));
...
```



# <a name="apidoc.module.ionic-framework.translate"></a>[module ionic-framework.translate](#apidoc.module.ionic-framework.translate)

#### <a name="apidoc.element.ionic-framework.translate.Translate"></a>[function <span class="apidocSignatureSpan">ionic-framework.translate.</span>Translate ()](#apidoc.element.ionic-framework.translate.Translate)
- description and source-code
```javascript
function Translate() {
    this._transMap = {};
    this._language = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ionic-framework.util"></a>[module ionic-framework.util](#apidoc.module.ionic-framework.util)

#### <a name="apidoc.element.ionic-framework.util.assign"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>assign ()](#apidoc.element.ionic-framework.util.assign)
- description and source-code
```javascript
function assign() {
    var args = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        args[_i - 0] = arguments[_i];
    }
    if (typeof Object.assign !== 'function') {
        // use the old-school shallow extend method
        return _baseExtend(args[0], [].slice.call(args, 1), false);
    }
    // use the built in ES6 Object.assign method
    return Object.assign.apply(null, args);
}
```
- example usage
```shell
...
return Math.max(min, Math.min(n, max));
}
exports.clamp = clamp;
/**
 * The assign() method is used to copy the values of all enumerable own
 * properties from one or more source objects to a target object. It will
 * return the target object. When available, this method will use
 * 'Object.assign()' under-the-hood.
 * @param target  The target object
 * @param source(s)  The source object
 */
function assign() {
var args = [];
for (var _i = 0; _i < arguments.length; _i++) {
    args[_i - 0] = arguments[_i];
...
```

#### <a name="apidoc.element.ionic-framework.util.clamp"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>clamp (min, n, max)](#apidoc.element.ionic-framework.util.clamp)
- description and source-code
```javascript
function clamp(min, n, max) {
    return Math.max(min, Math.min(n, max));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.debounce"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>debounce (fn, wait, immediate)](#apidoc.element.ionic-framework.util.debounce)
- description and source-code
```javascript
function debounce(fn, wait, immediate) {
    if (immediate === void 0) { immediate = false; }
    var timeout, args, context, timestamp, result;
    return function () {
        context = this;
        args = arguments;
        timestamp = Date.now();
        var later = function () {
            var last = Date.now() - timestamp;
            if (last < wait) {
                timeout = setTimeout(later, wait - last);
            }
            else {
                timeout = null;
                if (!immediate)
                    result = fn.apply(context, args);
            }
        };
        var callNow = immediate && !timeout;
        if (!timeout) {
            timeout = setTimeout(later, wait);
        }
        if (callNow)
            result = fn.apply(context, args);
        return result;
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.defaults"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>defaults (dest)](#apidoc.element.ionic-framework.util.defaults)
- description and source-code
```javascript
function defaults(dest) {
    var args = [];
    for (var _i = 1; _i < arguments.length; _i++) {
        args[_i - 1] = arguments[_i];
    }
    for (var i = arguments.length - 1; i >= 1; i--) {
        var source = arguments[i] || {};
        for (var key in source) {
            if (source.hasOwnProperty(key) && !dest.hasOwnProperty(key)) {
                dest[key] = source[key];
            }
        }
    }
    return dest;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.getQuerystring"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>getQuerystring (url)](#apidoc.element.ionic-framework.util.getQuerystring)
- description and source-code
```javascript
function getQuerystring(url) {
    var queryParams = {};
    if (url) {
        var startIndex = url.indexOf('?');
        if (startIndex !== -1) {
            var queries = url.slice(startIndex + 1).split('&');
            queries.forEach(function (param) {
                var split = param.split('=');
                queryParams[split[0].toLowerCase()] = split[1].split('#')[0];
            });
        }
    }
    return queryParams;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isArray"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isArray ()](#apidoc.element.ionic-framework.util.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
...
        continue;
    var keys = Object.keys(obj);
    for (var j = 0, jj = keys.length; j < jj; j++) {
        var key = keys[j];
        var src = obj[key];
        if (deep && exports.isObject(src)) {
            if (!exports.isObject(dst[key]))
                dst[key] = exports.isArray(src) ? [] : {};
            _baseExtend(dst[key], [src], true);
        }
        else {
            dst[key] = src;
        }
    }
}
...
```

#### <a name="apidoc.element.ionic-framework.util.isBlank"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isBlank (val)](#apidoc.element.ionic-framework.util.isBlank)
- description and source-code
```javascript
isBlank = function (val) { return val === undefined || val === null; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isBoolean"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isBoolean (val)](#apidoc.element.ionic-framework.util.isBoolean)
- description and source-code
```javascript
isBoolean = function (val) { return typeof val === 'boolean'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isDefined"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isDefined (val)](#apidoc.element.ionic-framework.util.isDefined)
- description and source-code
```javascript
isDefined = function (val) { return typeof val !== 'undefined'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isFunction"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isFunction (val)](#apidoc.element.ionic-framework.util.isFunction)
- description and source-code
```javascript
isFunction = function (val) { return typeof val === 'function'; }
```
- example usage
```shell
...
}
return _baseExtend(dst, [].slice.call(arguments, 1), true);
}
exports.merge = merge;
function _baseExtend(dst, objs, deep) {
for (var i = 0, ii = objs.length; i < ii; ++i) {
    var obj = objs[i];
    if (!obj || !exports.isObject(obj) && !exports.isFunction(obj))
        continue;
    var keys = Object.keys(obj);
    for (var j = 0, jj = keys.length; j < jj; j++) {
        var key = keys[j];
        var src = obj[key];
        if (deep && exports.isObject(src)) {
            if (!exports.isObject(dst[key]))
...
```

#### <a name="apidoc.element.ionic-framework.util.isNumber"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isNumber (val)](#apidoc.element.ionic-framework.util.isNumber)
- description and source-code
```javascript
isNumber = function (val) { return typeof val === 'number'; }
```
- example usage
```shell
...
    for (var i = 0, ii = arr.length; i < ii; i++) {
        if (cb(arr[i], i))
            return arr[i];
    }
},
remove: function (arr, itemOrIndex) {
    var index = -1;
    if (exports.isNumber(itemOrIndex)) {
        index = itemOrIndex;
    }
    else {
        index = arr.indexOf(itemOrIndex);
    }
    if (index < 0) {
        return false;
...
```

#### <a name="apidoc.element.ionic-framework.util.isObject"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isObject (val)](#apidoc.element.ionic-framework.util.isObject)
- description and source-code
```javascript
isObject = function (val) { return typeof val === 'object'; }
```
- example usage
```shell
...
}
return _baseExtend(dst, [].slice.call(arguments, 1), true);
}
exports.merge = merge;
function _baseExtend(dst, objs, deep) {
for (var i = 0, ii = objs.length; i < ii; ++i) {
    var obj = objs[i];
    if (!obj || !exports.isObject(obj) && !exports.isFunction(obj))
        continue;
    var keys = Object.keys(obj);
    for (var j = 0, jj = keys.length; j < jj; j++) {
        var key = keys[j];
        var src = obj[key];
        if (deep && exports.isObject(src)) {
            if (!exports.isObject(dst[key]))
...
```

#### <a name="apidoc.element.ionic-framework.util.isString"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isString (val)](#apidoc.element.ionic-framework.util.isString)
- description and source-code
```javascript
isString = function (val) { return typeof val === 'string'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isTrueProperty"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isTrueProperty (val)](#apidoc.element.ionic-framework.util.isTrueProperty)
- description and source-code
```javascript
isTrueProperty = function (val) {
    if (typeof val === 'string') {
        val = val.toLowerCase().trim();
        return (val === 'true' || val === 'on' || val === '');
    }
    return !!val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.isUndefined"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>isUndefined (val)](#apidoc.element.ionic-framework.util.isUndefined)
- description and source-code
```javascript
isUndefined = function (val) { return typeof val === 'undefined'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.merge"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>merge (dst)](#apidoc.element.ionic-framework.util.merge)
- description and source-code
```javascript
function merge(dst) {
    var args = [];
    for (var _i = 1; _i < arguments.length; _i++) {
        args[_i - 1] = arguments[_i];
    }
    return _baseExtend(dst, [].slice.call(arguments, 1), true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.nextUid"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>nextUid ()](#apidoc.element.ionic-framework.util.nextUid)
- description and source-code
```javascript
function nextUid() {
    return ++uid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.pascalCaseToDashCase"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>pascalCaseToDashCase (val)](#apidoc.element.ionic-framework.util.pascalCaseToDashCase)
- description and source-code
```javascript
function pascalCaseToDashCase(val) {
    if (val === void 0) { val = ''; }
    return val.charAt(0).toLowerCase() + val.substring(1).replace(/[A-Z]/g, function (match) {
        return '-' + match.toLowerCase();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ionic-framework.util.throttle"></a>[function <span class="apidocSignatureSpan">ionic-framework.util.</span>throttle (fn, wait, options)](#apidoc.element.ionic-framework.util.throttle)
- description and source-code
```javascript
function throttle(fn, wait, options) {
    var context, args, result;
    var timeout = null;
    var previous = 0;
    options || (options = {});
    var later = function () {
        previous = options.leading === false ? 0 : Date.now();
        timeout = null;
        result = fn.apply(context, args);
    };
    return function () {
        var now = Date.now();
        if (!previous && options.leading === false)
            previous = now;
        var remaining = wait - (now - previous);
        context = this;
        args = arguments;
        if (remaining <= 0) {
            clearTimeout(timeout);
            timeout = null;
            previous = now;
            result = fn.apply(context, args);
        }
        else if (!timeout && options.trailing !== false) {
            timeout = setTimeout(later, remaining);
        }
        return result;
    };
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
