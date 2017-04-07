# api documentation for  [react-server-example (v1.2.6)](https://github.com/mhart/react-server-example#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-server-example.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-server-example) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-server-example.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-server-example)
#### A very simple implementation of server-side React rendering

[![NPM](https://nodei.co/npm/react-server-example.png?downloads=true)](https://www.npmjs.com/package/react-server-example)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-server-example/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-server-example_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-server-example/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-server-example/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-server-example/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Hart",
        "email": "michael.hart.au@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/mhart/react-server-example/issues"
    },
    "dependencies": {
        "browserify": "^14.0.0",
        "literalify": "^0.4.0",
        "react": "^15.4.2",
        "react-dom": "^15.4.2"
    },
    "description": "A very simple implementation of server-side React rendering",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "baf066712e688261c433b6a71a10f308f1a8b47e",
        "tarball": "https://registry.npmjs.org/react-server-example/-/react-server-example-1.2.6.tgz"
    },
    "gitHead": "feada6183fe2fbb1a746492e157febe49eeafdcd",
    "homepage": "https://github.com/mhart/react-server-example#readme",
    "keywords": [
        "react",
        "reactjs",
        "server",
        "server-side"
    ],
    "license": "MIT",
    "main": "server.js",
    "maintainers": [
        {
            "name": "hichaelmart",
            "email": "michael.hart.au@gmail.com"
        }
    ],
    "name": "react-server-example",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mhart/react-server-example.git"
    },
    "scripts": {
        "start": "node server.js"
    },
    "version": "1.2.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-server-example](#apidoc.module.react-server-example)
1.  [function <span class="apidocSignatureSpan">react-server-example.</span>App (props, context, updater)](#apidoc.element.react-server-example.App)
1.  object <span class="apidocSignatureSpan">react-server-example.</span>App.prototype

#### [module react-server-example.App](#apidoc.module.react-server-example.App)
1.  [function <span class="apidocSignatureSpan">react-server-example.</span>App (props, context, updater)](#apidoc.element.react-server-example.App.App)

#### [module react-server-example.App.prototype](#apidoc.module.react-server-example.App.prototype)
1.  [function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentDidMount ()](#apidoc.element.react-server-example.App.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-server-example.App.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>getInitialState ()](#apidoc.element.react-server-example.App.prototype.getInitialState)
1.  [function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>handleClick ()](#apidoc.element.react-server-example.App.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>render ()](#apidoc.element.react-server-example.App.prototype.render)
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>updateComponent



# <a name="apidoc.module.react-server-example"></a>[module react-server-example](#apidoc.module.react-server-example)

#### <a name="apidoc.element.react-server-example.App"></a>[function <span class="apidocSignatureSpan">react-server-example.</span>App (props, context, updater)](#apidoc.element.react-server-example.App)
- description and source-code
```javascript
App = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-server-example.App"></a>[module react-server-example.App](#apidoc.module.react-server-example.App)

#### <a name="apidoc.element.react-server-example.App.App"></a>[function <span class="apidocSignatureSpan">react-server-example.</span>App (props, context, updater)](#apidoc.element.react-server-example.App.App)
- description and source-code
```javascript
App = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-server-example.App.prototype"></a>[module react-server-example.App.prototype](#apidoc.module.react-server-example.App.prototype)

#### <a name="apidoc.element.react-server-example.App.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>componentDidMount ()](#apidoc.element.react-server-example.App.prototype.componentDidMount)
- description and source-code
```javascript
componentDidMount = function () {
  this.setState({disabled: false})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-server-example.App.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-server-example.App.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-server-example.App.prototype.getInitialState"></a>[function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>getInitialState ()](#apidoc.element.react-server-example.App.prototype.getInitialState)
- description and source-code
```javascript
getInitialState = function () {
  return {items: this.props.items, disabled: true}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-server-example.App.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>handleClick ()](#apidoc.element.react-server-example.App.prototype.handleClick)
- description and source-code
```javascript
handleClick = function () {
  this.setState({
    items: this.state.items.concat('Item ' + this.state.items.length)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-server-example.App.prototype.render"></a>[function <span class="apidocSignatureSpan">react-server-example.App.prototype.</span>render ()](#apidoc.element.react-server-example.App.prototype.render)
- description and source-code
```javascript
render = function () {

  return div(null,

    button({onClick: this.handleClick, disabled: this.state.disabled}, 'Add Item'),

    ul({children: this.state.items.map(function(item) {
      return li(null, item)
    })})

  )
}
```
- example usage
```shell
...
App = React.createFactory(require('./App'))

// This script will run in the browser and will render our component using the
// value from APP_PROPS that we generate inline in the page's html on the server.
// If these props match what is used in the server render, React will see that
// it doesn't need to generate any DOM and the page will load faster

ReactDOM.render(App(window.APP_PROPS), document.getElementById('content'))
'''

'server.js':
'''js
var http = require('http'),
browserify = require('browserify'),
literalify = require('literalify'),
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
