# api documentation for  [stream-splicer (v2.0.0)](https://github.com/substack/stream-splicer)  [![npm package](https://img.shields.io/npm/v/npmdoc-stream-splicer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stream-splicer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stream-splicer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stream-splicer)
#### streaming pipeline with a mutable configuration

[![NPM](https://nodei.co/npm/stream-splicer.png?downloads=true)](https://www.npmjs.com/package/stream-splicer)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stream-splicer/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-stream-splicer_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stream-splicer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stream-splicer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stream-splicer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "email": "mail@substack.net",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/stream-splicer/issues"
    },
    "dependencies": {
        "inherits": "^2.0.1",
        "readable-stream": "^2.0.2"
    },
    "description": "streaming pipeline with a mutable configuration",
    "devDependencies": {
        "JSONStream": "^1.0.4",
        "concat-stream": "^1.4.6",
        "split": "^1.0.0",
        "tape": "^4.2.0",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1b63be438a133e4b671cc1935197600175910d83",
        "tarball": "https://registry.npmjs.org/stream-splicer/-/stream-splicer-2.0.0.tgz"
    },
    "gitHead": "9fae7fdf051fc56a6a316416feda5be2291bf220",
    "homepage": "https://github.com/substack/stream-splicer",
    "keywords": [
        "stream",
        "mutable",
        "pipeline"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack",
            "email": "mail@substack.net"
        }
    ],
    "name": "stream-splicer",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/stream-splicer.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "2.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module stream-splicer](#apidoc.module.stream-splicer)
1.  [function <span class="apidocSignatureSpan">stream-splicer.</span>obj (streams, opts)](#apidoc.element.stream-splicer.obj)
1.  [function <span class="apidocSignatureSpan">stream-splicer.</span>super_ (options)](#apidoc.element.stream-splicer.super_)
1.  [function <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_ (options)](#apidoc.element.stream-splicer.super_.super_)
1.  object <span class="apidocSignatureSpan">stream-splicer.</span>super_.prototype
1.  object <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_.PassThrough.prototype
1.  object <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_.Transform.prototype
1.  object <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_.Writable.prototype
1.  object <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_.prototype

#### [module stream-splicer.super_](#apidoc.module.stream-splicer.super_)
1.  [function <span class="apidocSignatureSpan">stream-splicer.</span>super_ (options)](#apidoc.element.stream-splicer.super_.super_)

#### [module stream-splicer.super_.prototype](#apidoc.module.stream-splicer.super_.prototype)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>cork ()](#apidoc.element.stream-splicer.super_.prototype.cork)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype.end)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.stream-splicer.super_.prototype.setDefaultEncoding)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>uncork ()](#apidoc.element.stream-splicer.super_.prototype.uncork)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype.write)
1.  object <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>_writev

#### [module stream-splicer.super_.super_](#apidoc.module.stream-splicer.super_.super_)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.</span>super_ ()](#apidoc.element.stream-splicer.super_.super_.super_)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Duplex (options)](#apidoc.element.stream-splicer.super_.super_.Duplex)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>PassThrough (options)](#apidoc.element.stream-splicer.super_.super_.PassThrough)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Readable (options)](#apidoc.element.stream-splicer.super_.super_.Readable)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>ReadableState (options, stream)](#apidoc.element.stream-splicer.super_.super_.ReadableState)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Stream ()](#apidoc.element.stream-splicer.super_.super_.Stream)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Transform (options)](#apidoc.element.stream-splicer.super_.super_.Transform)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Writable (options)](#apidoc.element.stream-splicer.super_.super_.Writable)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>_fromList (n, state)](#apidoc.element.stream-splicer.super_.super_._fromList)

#### [module stream-splicer.super_.super_.PassThrough.prototype](#apidoc.module.stream-splicer.super_.super_.PassThrough.prototype)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.PassThrough.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.PassThrough.prototype._transform)

#### [module stream-splicer.super_.super_.Transform.prototype](#apidoc.module.stream-splicer.super_.super_.Transform.prototype)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_read (n)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._read)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._transform)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._write)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>push (chunk, encoding)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype.push)

#### [module stream-splicer.super_.super_.Writable.prototype](#apidoc.module.stream-splicer.super_.super_.Writable.prototype)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype._write)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>cork ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.cork)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.end)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>pipe ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.setDefaultEncoding)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>uncork ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.uncork)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.write)
1.  object <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>_writev

#### [module stream-splicer.super_.super_.prototype](#apidoc.module.stream-splicer.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>_read (n)](#apidoc.element.stream-splicer.super_.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.stream-splicer.super_.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>isPaused ()](#apidoc.element.stream-splicer.super_.super_.prototype.isPaused)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.stream-splicer.super_.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>pause ()](#apidoc.element.stream-splicer.super_.super_.prototype.pause)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.stream-splicer.super_.super_.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.stream-splicer.super_.super_.prototype.push)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>read (n)](#apidoc.element.stream-splicer.super_.super_.prototype.read)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>resume ()](#apidoc.element.stream-splicer.super_.super_.prototype.resume)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.stream-splicer.super_.super_.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.stream-splicer.super_.super_.prototype.unpipe)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.stream-splicer.super_.super_.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.stream-splicer.super_.super_.prototype.wrap)



# <a name="apidoc.module.stream-splicer"></a>[module stream-splicer](#apidoc.module.stream-splicer)

#### <a name="apidoc.element.stream-splicer.obj"></a>[function <span class="apidocSignatureSpan">stream-splicer.</span>obj (streams, opts)](#apidoc.element.stream-splicer.obj)
- description and source-code
```javascript
obj = function (streams, opts) {
    if (!opts && !Array.isArray(streams)) {
        opts = streams;
        streams = [];
    }
    if (!streams) streams = [];
    if (!opts) opts = {};
    opts.objectMode = true;
    return new Pipeline(streams, opts);
}
```
- example usage
```shell
...
''' js
var splicer = require('stream-splicer');
var through = require('through2');
var JSONStream = require('JSONStream');
var split = require('split');

var headerData = {};
var headers = through.obj(function (buf, enc, next) {
var line = buf.toString('utf8');
if (line === '') {
    this.push(headerData);
    pipeline.splice(1, 1, JSONStream.parse([ 'rows', true ]));
}
else {
    var m = /^(\S+):(.+)/.exec(line);
...
```

#### <a name="apidoc.element.stream-splicer.super_"></a>[function <span class="apidocSignatureSpan">stream-splicer.</span>super_ (options)](#apidoc.element.stream-splicer.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex)) return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false) this.readable = false;

  if (options && options.writable === false) this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false) this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_"></a>[function <span class="apidocSignatureSpan">stream-splicer.</span>super_.super_ (options)](#apidoc.element.stream-splicer.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  Duplex = Duplex || require('./_stream_duplex');

  if (!(this instanceof Readable)) return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function') this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stream-splicer.super_"></a>[module stream-splicer.super_](#apidoc.module.stream-splicer.super_)

#### <a name="apidoc.element.stream-splicer.super_.super_"></a>[function <span class="apidocSignatureSpan">stream-splicer.</span>super_ (options)](#apidoc.element.stream-splicer.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  Duplex = Duplex || require('./_stream_duplex');

  if (!(this instanceof Readable)) return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function') this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stream-splicer.super_.prototype"></a>[module stream-splicer.super_.prototype](#apidoc.module.stream-splicer.super_.prototype)

#### <a name="apidoc.element.stream-splicer.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('_write() is not implemented'));
}
```
- example usage
```shell
...
    r.once('readable', onreadable);
    self.once('_mutate', onreadable);
}
};

Pipeline.prototype._write = function (buf, enc, next) {
this._notEmpty();
this._streams[0]._write(buf, enc, next);
};

Pipeline.prototype._notEmpty = function () {
var self = this;
if (this._streams.length > 0) return;
var stream = new PassThrough(this._options);
stream.once('end', function () {
...
```

#### <a name="apidoc.element.stream-splicer.super_.prototype.cork"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>cork ()](#apidoc.element.stream-splicer.super_.prototype.cork)
- description and source-code
```javascript
cork = function () {
  var state = this._writableState;

  state.corked++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.prototype.end"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (typeof chunk === 'function') {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (chunk !== null && chunk !== undefined) this.write(chunk, encoding);

  // .end() fully uncorks
  if (state.corked) {
    state.corked = 1;
    this.uncork();
  }

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished) endWritable(this, state, cb);
}
```
- example usage
```shell
...
this._wrapOptions = { objectMode: opts.objectMode !== false };
this._streams = [];

this.splice.apply(this, [ 0, 0 ].concat(streams));

this.once('finish', function () {
    self._notEmpty();
    self._streams[0].end();
});
}

Pipeline.prototype._read = function () {
var self = this;
this._notEmpty();
...
```

#### <a name="apidoc.element.stream-splicer.super_.prototype.setDefaultEncoding"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.stream-splicer.super_.prototype.setDefaultEncoding)
- description and source-code
```javascript
function setDefaultEncoding(encoding) {
  // node::ParseEncoding() requires lower case.
  if (typeof encoding === 'string') encoding = encoding.toLowerCase();
  if (!(['hex', 'utf8', 'utf-8', 'ascii', 'binary', 'base64', 'ucs2', 'ucs-2', 'utf16le', 'utf-16le', 'raw'].indexOf((encoding + '').
toLowerCase()) > -1)) throw new TypeError('Unknown encoding: ' + encoding);
  this._writableState.defaultEncoding = encoding;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.prototype.uncork"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>uncork ()](#apidoc.element.stream-splicer.super_.prototype.uncork)
- description and source-code
```javascript
uncork = function () {
  var state = this._writableState;

  if (state.corked) {
    state.corked--;

    if (!state.writing && !state.corked && !state.finished && !state.bufferProcessing && state.bufferedRequest) clearBuffer(this
, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.prototype.write"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;
  var isBuf = Buffer.isBuffer(chunk);

  if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (isBuf) encoding = 'buffer';else if (!encoding) encoding = state.defaultEncoding;

  if (typeof cb !== 'function') cb = nop;

  if (state.ended) writeAfterEnd(this, cb);else if (isBuf || validChunk(this, state, chunk, cb)) {
    state.pendingcb++;
    ret = writeOrBuffer(this, state, isBuf, chunk, encoding, cb);
  }

  return ret;
}
```
- example usage
```shell
...
    return this._streams.indexOf(stream);
};

Pipeline.prototype._wrapStream = function (stream) {
    if (typeof stream.read === 'function') return stream;
    var w = new Readable(this._wrapOptions).wrap(stream);
    w._write = function (buf, enc, next) {
        if (stream.write(buf) === false) {
            stream.once('drain', next);
        }
        else nextTick(next);
    };
    return w;
};
...
```



# <a name="apidoc.module.stream-splicer.super_.super_"></a>[module stream-splicer.super_.super_](#apidoc.module.stream-splicer.super_.super_)

#### <a name="apidoc.element.stream-splicer.super_.super_.super_"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.</span>super_ ()](#apidoc.element.stream-splicer.super_.super_.super_)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Duplex"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Duplex (options)](#apidoc.element.stream-splicer.super_.super_.Duplex)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex)) return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false) this.readable = false;

  if (options && options.writable === false) this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false) this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.PassThrough"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>PassThrough (options)](#apidoc.element.stream-splicer.super_.super_.PassThrough)
- description and source-code
```javascript
function PassThrough(options) {
  if (!(this instanceof PassThrough)) return new PassThrough(options);

  Transform.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Readable"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Readable (options)](#apidoc.element.stream-splicer.super_.super_.Readable)
- description and source-code
```javascript
function Readable(options) {
  Duplex = Duplex || require('./_stream_duplex');

  if (!(this instanceof Readable)) return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function') this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.ReadableState"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>ReadableState (options, stream)](#apidoc.element.stream-splicer.super_.super_.ReadableState)
- description and source-code
```javascript
function ReadableState(options, stream) {
  Duplex = Duplex || require('./_stream_duplex');

  options = options || {};

  // object stream flag. Used to make read(n) ignore n and to
  // make all the buffer merging and length checks go away
  this.objectMode = !!options.objectMode;

  if (stream instanceof Duplex) this.objectMode = this.objectMode || !!options.readableObjectMode;

  // the point at which it stops calling _read() to fill the buffer
  // Note: 0 is a valid value, means "don't call _read preemptively ever"
  var hwm = options.highWaterMark;
  var defaultHwm = this.objectMode ? 16 : 16 * 1024;
  this.highWaterMark = hwm || hwm === 0 ? hwm : defaultHwm;

  // cast to ints.
  this.highWaterMark = ~~this.highWaterMark;

  // A linked list is used to store data chunks instead of an array because the
  // linked list can remove elements from the beginning faster than
  // array.shift()
  this.buffer = new BufferList();
  this.length = 0;
  this.pipes = null;
  this.pipesCount = 0;
  this.flowing = null;
  this.ended = false;
  this.endEmitted = false;
  this.reading = false;

  // a flag to be able to tell if the onwrite cb is called immediately,
  // or on a later tick.  We set this to true at first, because any
  // actions that shouldn't happen until "later" should generally also
  // not happen before the first write call.
  this.sync = true;

  // whenever we return null, then we set a flag to say
  // that we're awaiting a 'readable' event emission.
  this.needReadable = false;
  this.emittedReadable = false;
  this.readableListening = false;
  this.resumeScheduled = false;

  // Crypto is kind of old and crusty.  Historically, its default string
  // encoding is 'binary' so we have to make this configurable.
  // Everything else in the universe uses 'utf8', though.
  this.defaultEncoding = options.defaultEncoding || 'utf8';

  // when piping, we only care about 'readable' events that happen
  // after read()ing all the bytes and not getting any pushback.
  this.ranOut = false;

  // the number of writers that are awaiting a drain event in .pipe()s
  this.awaitDrain = 0;

  // if true, a maybeReadMore has been scheduled
  this.readingMore = false;

  this.decoder = null;
  this.encoding = null;
  if (options.encoding) {
    if (!StringDecoder) StringDecoder = require('string_decoder/').StringDecoder;
    this.decoder = new StringDecoder(options.encoding);
    this.encoding = options.encoding;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Stream"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Stream ()](#apidoc.element.stream-splicer.super_.super_.Stream)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Transform"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Transform (options)](#apidoc.element.stream-splicer.super_.super_.Transform)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform)) return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function') this._transform = options.transform;

    if (typeof options.flush === 'function') this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function () {
    if (typeof this._flush === 'function') this._flush(function (er, data) {
      done(stream, er, data);
    });else done(stream);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>Writable (options)](#apidoc.element.stream-splicer.super_.super_.Writable)
- description and source-code
```javascript
function Writable(options) {
  Duplex = Duplex || require('./_stream_duplex');

  // Writable ctor is applied to Duplexes, too.
  // 'realHasInstance' is necessary because using plain 'instanceof'
  // would return false, as no '_writableState' property is attached.

  // Trying to use the custom 'instanceof' for Writable here will also break the
  // Node.js LazyTransform implementation, which has a non-trivial getter for
  // '_writableState' that would lead to infinite recursion.
  if (!realHasInstance.call(Writable, this) && !(this instanceof Duplex)) {
    return new Writable(options);
  }

  this._writableState = new WritableState(options, this);

  // legacy.
  this.writable = true;

  if (options) {
    if (typeof options.write === 'function') this._write = options.write;

    if (typeof options.writev === 'function') this._writev = options.writev;
  }

  Stream.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_._fromList"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.</span>_fromList (n, state)](#apidoc.element.stream-splicer.super_.super_._fromList)
- description and source-code
```javascript
function fromList(n, state) {
  // nothing buffered
  if (state.length === 0) return null;

  var ret;
  if (state.objectMode) ret = state.buffer.shift();else if (!n || n >= state.length) {
    // read it all, truncate the list
    if (state.decoder) ret = state.buffer.join('');else if (state.buffer.length === 1) ret = state.buffer.head.data;else ret = state
.buffer.concat(state.length);
    state.buffer.clear();
  } else {
    // read part of list
    ret = fromListPartial(n, state.buffer, state.decoder);
  }

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stream-splicer.super_.super_.PassThrough.prototype"></a>[module stream-splicer.super_.super_.PassThrough.prototype](#apidoc.module.stream-splicer.super_.super_.PassThrough.prototype)

#### <a name="apidoc.element.stream-splicer.super_.super_.PassThrough.prototype._transform"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.PassThrough.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.PassThrough.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  cb(null, chunk);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stream-splicer.super_.super_.Transform.prototype"></a>[module stream-splicer.super_.super_.Transform.prototype](#apidoc.module.stream-splicer.super_.super_.Transform.prototype)

#### <a name="apidoc.element.stream-splicer.super_.super_.Transform.prototype._read"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_read (n)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  var ts = this._transformState;

  if (ts.writechunk !== null && ts.writecb && !ts.transforming) {
    ts.transforming = true;
    this._transform(ts.writechunk, ts.writeencoding, ts.afterTransform);
  } else {
    // mark that we need a transform, so that any data that comes in
    // will get processed, now that we've asked for it.
    ts.needTransform = true;
  }
}
```
- example usage
```shell
...
        Duplex.prototype.push.call(this, buf);
        reads ++;
    }
    if (reads === 0) {
        var onreadable = function () {
            r.removeListener('readable', onreadable);
            self.removeListener('_mutate', onreadable);
            self._read()
        };
        r.once('readable', onreadable);
        self.once('_mutate', onreadable);
    }
};

Pipeline.prototype._write = function (buf, enc, next) {
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Transform.prototype._transform"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  throw new Error('_transform() is not implemented');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Transform.prototype._write"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  var ts = this._transformState;
  ts.writecb = cb;
  ts.writechunk = chunk;
  ts.writeencoding = encoding;
  if (!ts.transforming) {
    var rs = this._readableState;
    if (ts.needTransform || rs.needReadable || rs.length < rs.highWaterMark) this._read(rs.highWaterMark);
  }
}
```
- example usage
```shell
...
    r.once('readable', onreadable);
    self.once('_mutate', onreadable);
}
};

Pipeline.prototype._write = function (buf, enc, next) {
this._notEmpty();
this._streams[0]._write(buf, enc, next);
};

Pipeline.prototype._notEmpty = function () {
var self = this;
if (this._streams.length > 0) return;
var stream = new PassThrough(this._options);
stream.once('end', function () {
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Transform.prototype.push"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Transform.prototype.</span>push (chunk, encoding)](#apidoc.element.stream-splicer.super_.super_.Transform.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  this._transformState.needTransform = false;
  return Duplex.prototype.push.call(this, chunk, encoding);
}
```
- example usage
```shell
...
var stream = new PassThrough(this._options);
stream.once('end', function () {
    var ix = self._streams.indexOf(stream);
    if (ix >= 0 && ix === self._streams.length - 1) {
        Duplex.prototype.push.call(self, null);
    }
});
this._streams.push(stream);
this.length = this._streams.length;
};

Pipeline.prototype.push = function (stream) {
var args = [ this._streams.length, 0 ].concat([].slice.call(arguments));
this.splice.apply(this, args);
return this._streams.length;
...
```



# <a name="apidoc.module.stream-splicer.super_.super_.Writable.prototype"></a>[module stream-splicer.super_.super_.Writable.prototype](#apidoc.module.stream-splicer.super_.super_.Writable.prototype)

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype._write"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('_write() is not implemented'));
}
```
- example usage
```shell
...
    r.once('readable', onreadable);
    self.once('_mutate', onreadable);
}
};

Pipeline.prototype._write = function (buf, enc, next) {
this._notEmpty();
this._streams[0]._write(buf, enc, next);
};

Pipeline.prototype._notEmpty = function () {
var self = this;
if (this._streams.length > 0) return;
var stream = new PassThrough(this._options);
stream.once('end', function () {
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.cork"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>cork ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.cork)
- description and source-code
```javascript
cork = function () {
  var state = this._writableState;

  state.corked++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.end"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (typeof chunk === 'function') {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (chunk !== null && chunk !== undefined) this.write(chunk, encoding);

  // .end() fully uncorks
  if (state.corked) {
    state.corked = 1;
    this.uncork();
  }

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished) endWritable(this, state, cb);
}
```
- example usage
```shell
...
this._wrapOptions = { objectMode: opts.objectMode !== false };
this._streams = [];

this.splice.apply(this, [ 0, 0 ].concat(streams));

this.once('finish', function () {
    self._notEmpty();
    self._streams[0].end();
});
}

Pipeline.prototype._read = function () {
var self = this;
this._notEmpty();
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.pipe"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>pipe ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.pipe)
- description and source-code
```javascript
pipe = function () {
  this.emit('error', new Error('Cannot pipe, not readable'));
}
```
- example usage
```shell
...
            Duplex.prototype.push.call(self, null);
        }
    });
    reps.push(stream);
})(arguments[j]);

for (var i = 0; i < reps.length - 1; i++) {
    reps[i].pipe(reps[i+1]);
}

if (reps.length && self._streams[end]) {
    reps[reps.length-1].pipe(self._streams[end]);
}
if (reps[0] && self._streams[start-1]) {
    self._streams[start-1].pipe(reps[0]);
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.setDefaultEncoding"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.setDefaultEncoding)
- description and source-code
```javascript
function setDefaultEncoding(encoding) {
  // node::ParseEncoding() requires lower case.
  if (typeof encoding === 'string') encoding = encoding.toLowerCase();
  if (!(['hex', 'utf8', 'utf-8', 'ascii', 'binary', 'base64', 'ucs2', 'ucs-2', 'utf16le', 'utf-16le', 'raw'].indexOf((encoding + '').
toLowerCase()) > -1)) throw new TypeError('Unknown encoding: ' + encoding);
  this._writableState.defaultEncoding = encoding;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.uncork"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>uncork ()](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.uncork)
- description and source-code
```javascript
uncork = function () {
  var state = this._writableState;

  if (state.corked) {
    state.corked--;

    if (!state.writing && !state.corked && !state.finished && !state.bufferProcessing && state.bufferedRequest) clearBuffer(this
, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.Writable.prototype.write"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.Writable.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.stream-splicer.super_.super_.Writable.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;
  var isBuf = Buffer.isBuffer(chunk);

  if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (isBuf) encoding = 'buffer';else if (!encoding) encoding = state.defaultEncoding;

  if (typeof cb !== 'function') cb = nop;

  if (state.ended) writeAfterEnd(this, cb);else if (isBuf || validChunk(this, state, chunk, cb)) {
    state.pendingcb++;
    ret = writeOrBuffer(this, state, isBuf, chunk, encoding, cb);
  }

  return ret;
}
```
- example usage
```shell
...
    return this._streams.indexOf(stream);
};

Pipeline.prototype._wrapStream = function (stream) {
    if (typeof stream.read === 'function') return stream;
    var w = new Readable(this._wrapOptions).wrap(stream);
    w._write = function (buf, enc, next) {
        if (stream.write(buf) === false) {
            stream.once('drain', next);
        }
        else nextTick(next);
    };
    return w;
};
...
```



# <a name="apidoc.module.stream-splicer.super_.super_.prototype"></a>[module stream-splicer.super_.super_.prototype](#apidoc.module.stream-splicer.super_.super_.prototype)

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>_read (n)](#apidoc.element.stream-splicer.super_.super_.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  this.emit('error', new Error('_read() is not implemented'));
}
```
- example usage
```shell
...
        Duplex.prototype.push.call(this, buf);
        reads ++;
    }
    if (reads === 0) {
        var onreadable = function () {
            r.removeListener('readable', onreadable);
            self.removeListener('_mutate', onreadable);
            self._read()
        };
        r.once('readable', onreadable);
        self.once('_mutate', onreadable);
    }
};

Pipeline.prototype._write = function (buf, enc, next) {
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.stream-splicer.super_.super_.prototype.addListener)
- description and source-code
```javascript
addListener = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data') {
    // Start flowing on next tick if stream isn't explicitly paused
    if (this._readableState.flowing !== false) this.resume();
  } else if (ev === 'readable') {
    var state = this._readableState;
    if (!state.endEmitted && !state.readableListening) {
      state.readableListening = state.needReadable = true;
      state.emittedReadable = false;
      if (!state.reading) {
        processNextTick(nReadingNextTick, this);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.isPaused"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>isPaused ()](#apidoc.element.stream-splicer.super_.super_.prototype.isPaused)
- description and source-code
```javascript
isPaused = function () {
  return this._readableState.flowing === false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.stream-splicer.super_.super_.prototype.on)
- description and source-code
```javascript
on = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data') {
    // Start flowing on next tick if stream isn't explicitly paused
    if (this._readableState.flowing !== false) this.resume();
  } else if (ev === 'readable') {
    var state = this._readableState;
    if (!state.endEmitted && !state.readableListening) {
      state.readableListening = state.needReadable = true;
      state.emittedReadable = false;
      if (!state.reading) {
        processNextTick(nReadingNextTick, this);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
...
var end = i;

var reps = [], args = arguments;
for (var j = 2; j < args.length; j++) (function (stream) {
    if (Array.isArray(stream)) {
        stream = new Pipeline(stream, self._options);
    }
    stream.on('error', function (err) {
        err.stream = this;
        self.emit('error', err);
    });
    stream = self._wrapStream(stream);
    stream.once('end', function () {
        var ix = self._streams.indexOf(stream);
        if (ix >= 0 && ix === self._streams.length - 1) {
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.pause"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>pause ()](#apidoc.element.stream-splicer.super_.super_.prototype.pause)
- description and source-code
```javascript
pause = function () {
  debug('call pause flowing=%j', this._readableState.flowing);
  if (false !== this._readableState.flowing) {
    debug('pause');
    this._readableState.flowing = false;
    this.emit('pause');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.pipe"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.stream-splicer.super_.super_.prototype.pipe)
- description and source-code
```javascript
pipe = function (dest, pipeOpts) {
  var src = this;
  var state = this._readableState;

  switch (state.pipesCount) {
    case 0:
      state.pipes = dest;
      break;
    case 1:
      state.pipes = [state.pipes, dest];
      break;
    default:
      state.pipes.push(dest);
      break;
  }
  state.pipesCount += 1;
  debug('pipe count=%d opts=%j', state.pipesCount, pipeOpts);

  var doEnd = (!pipeOpts || pipeOpts.end !== false) && dest !== process.stdout && dest !== process.stderr;

  var endFn = doEnd ? onend : cleanup;
  if (state.endEmitted) processNextTick(endFn);else src.once('end', endFn);

  dest.on('unpipe', onunpipe);
  function onunpipe(readable) {
    debug('onunpipe');
    if (readable === src) {
      cleanup();
    }
  }

  function onend() {
    debug('onend');
    dest.end();
  }

  // when the dest drains, it reduces the awaitDrain counter
  // on the source.  This would be more elegant with a .once()
  // handler in flow(), but adding and removing repeatedly is
  // too slow.
  var ondrain = pipeOnDrain(src);
  dest.on('drain', ondrain);

  var cleanedUp = false;
  function cleanup() {
    debug('cleanup');
    // cleanup event handlers once the pipe is broken
    dest.removeListener('close', onclose);
    dest.removeListener('finish', onfinish);
    dest.removeListener('drain', ondrain);
    dest.removeListener('error', onerror);
    dest.removeListener('unpipe', onunpipe);
    src.removeListener('end', onend);
    src.removeListener('end', cleanup);
    src.removeListener('data', ondata);

    cleanedUp = true;

    // if the reader is waiting for a drain event from this
    // specific writer, then it would cause it to never start
    // flowing again.
    // So, if this is awaiting a drain, then we just call it now.
    // If we don't know, then assume that we are waiting for one.
    if (state.awaitDrain && (!dest._writableState || dest._writableState.needDrain)) ondrain();
  }

  // If the user pushes more data while we're writing to dest then we'll end up
  // in ondata again. However, we only want to increase awaitDrain once because
  // dest will only emit one 'drain' event for the multiple writes.
  // => Introduce a guard on increasing awaitDrain.
  var increasedAwaitDrain = false;
  src.on('data', ondata);
  function ondata(chunk) {
    debug('ondata');
    increasedAwaitDrain = false;
    var ret = dest.write(chunk);
    if (false === ret && !increasedAwaitDrain) {
      // If the user unpiped during 'dest.write()', it is possible
      // to get stuck in a permanently paused state if that write
      // also returned false.
      // => Check whether 'dest' is still a piping destination.
      if ((state.pipesCount === 1 && state.pipes === dest || state.pipesCount > 1 && indexOf(state.pipes, dest) !== -1) && !cleanedUp
) {
        debug('false write response, pause', src._readableState.awaitDrain);
        src._readableState.awaitDrain++;
        increasedAwaitDrain = true;
      }
      src.pause();
    }
  }

  // if the dest has an error, then stop piping into it.
  // however, don't suppress the throwing behavior for this.
  function onerror(er) {
    debug('onerror', er);
    unpipe();
    dest.removeListener('error', onerror);
    if (EElistenerCount(dest, 'error') === 0) dest.emit('error', er);
  }

  // Make sure our error handler is attached before userland ones.
  prependListener(dest, 'error', onerror);

  // Both close and finish should trigger unpipe, but only once.
  function onclose() {
    dest.removeListener('finish', onfinish);
    unpipe();
  }
  dest.once('close', onclose);
  function onfinish() {
    debug('onfinish');
    dest.removeListener('close', onclose);
    unpipe();
  }
  dest.once('finish', onfinish);

  function unpipe() {
    debug('unpipe');
    src.unpipe(dest);
  }

  // tell the dest that it's being piped to
  dest.emit('pipe', src);

  // start the flow if it hasn't been started already.
  if (!state.flowing) {
    debug('pipe resume');
    src.resume();
  }

  return dest;
}
```
- example usage
```shell
...
            Duplex.prototype.push.call(self, null);
        }
    });
    reps.push(stream);
})(arguments[j]);

for (var i = 0; i < reps.length - 1; i++) {
    reps[i].pipe(reps[i+1]);
}

if (reps.length && self._streams[end]) {
    reps[reps.length-1].pipe(self._streams[end]);
}
if (reps[0] && self._streams[start-1]) {
    self._streams[start-1].pipe(reps[0]);
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.push"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.stream-splicer.super_.super_.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  var state = this._readableState;

  if (!state.objectMode && typeof chunk === 'string') {
    encoding = encoding || state.defaultEncoding;
    if (encoding !== state.encoding) {
      chunk = bufferShim.from(chunk, encoding);
      encoding = '';
    }
  }

  return readableAddChunk(this, state, chunk, encoding, false);
}
```
- example usage
```shell
...
var stream = new PassThrough(this._options);
stream.once('end', function () {
    var ix = self._streams.indexOf(stream);
    if (ix >= 0 && ix === self._streams.length - 1) {
        Duplex.prototype.push.call(self, null);
    }
});
this._streams.push(stream);
this.length = this._streams.length;
};

Pipeline.prototype.push = function (stream) {
var args = [ this._streams.length, 0 ].concat([].slice.call(arguments));
this.splice.apply(this, args);
return this._streams.length;
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.read"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>read (n)](#apidoc.element.stream-splicer.super_.super_.prototype.read)
- description and source-code
```javascript
read = function (n) {
  debug('read', n);
  n = parseInt(n, 10);
  var state = this._readableState;
  var nOrig = n;

  if (n !== 0) state.emittedReadable = false;

  // if we're doing read(0) to trigger a readable event, but we
  // already have a bunch of data in the buffer, then just trigger
  // the 'readable' event and move on.
  if (n === 0 && state.needReadable && (state.length >= state.highWaterMark || state.ended)) {
    debug('read: emitReadable', state.length, state.ended);
    if (state.length === 0 && state.ended) endReadable(this);else emitReadable(this);
    return null;
  }

  n = howMuchToRead(n, state);

  // if we've ended, and we're now clear, then finish it up.
  if (n === 0 && state.ended) {
    if (state.length === 0) endReadable(this);
    return null;
  }

  // All the actual chunk generation logic needs to be
  // *below* the call to _read.  The reason is that in certain
  // synthetic stream cases, such as passthrough streams, _read
  // may be a completely synchronous operation which may change
  // the state of the read buffer, providing enough data when
  // before there was *not* enough.
  //
  // So, the steps are:
  // 1. Figure out what the state of things will be after we do
  // a read from the buffer.
  //
  // 2. If that resulting state will trigger a _read, then call _read.
  // Note that this may be asynchronous, or synchronous.  Yes, it is
  // deeply ugly to write APIs this way, but that still doesn't mean
  // that the Readable class should behave improperly, as streams are
  // designed to be sync/async agnostic.
  // Take note if the _read call is sync or async (ie, if the read call
  // has returned yet), so that we know whether or not it's safe to emit
  // 'readable' etc.
  //
  // 3. Actually pull the requested chunks out of the buffer and return.

  // if we need a readable event, then we need to do some reading.
  var doRead = state.needReadable;
  debug('need readable', doRead);

  // if we currently have less than the highWaterMark, then also read some
  if (state.length === 0 || state.length - n < state.highWaterMark) {
    doRead = true;
    debug('length less than watermark', doRead);
  }

  // however, if we've ended, then there's no point, and if we're already
  // reading, then it's unnecessary.
  if (state.ended || state.reading) {
    doRead = false;
    debug('reading or ended', doRead);
  } else if (doRead) {
    debug('do read');
    state.reading = true;
    state.sync = true;
    // if the length is currently zero, then we *need* a readable event.
    if (state.length === 0) state.needReadable = true;
    // call internal read method
    this._read(state.highWaterMark);
    state.sync = false;
    // If _read pushed data synchronously, then 'reading' will be false,
    // and we need to re-evaluate how much data we can return to the user.
    if (!state.reading) n = howMuchToRead(nOrig, state);
  }

  var ret;
  if (n > 0) ret = fromList(n, state);else ret = null;

  if (ret === null) {
    state.needReadable = true;
    n = 0;
  } else {
    state.length -= n;
  }

  if (state.length === 0) {
    // If we have nothing in the buffer, then we want to know
    // as soon as we *do* get something into the buffer.
    if (!state.ended) state.needReadable = true;

    // If we tried to read() past the EOF, then emit end on the next tick.
    if (nOrig !== n && state.ended) endReadable(this);
  }

  if (ret !== null) this.emit('data', ret);

  return ret;
}
```
- example usage
```shell
...

Pipeline.prototype._read = function () {
var self = this;
this._notEmpty();

var r = this._streams[this._streams.length-1];
var buf, reads = 0;
while ((buf = r.read()) !== null) {
    Duplex.prototype.push.call(this, buf);
    reads ++;
}
if (reads === 0) {
    var onreadable = function () {
        r.removeListener('readable', onreadable);
        self.removeListener('_mutate', onreadable);
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.resume"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>resume ()](#apidoc.element.stream-splicer.super_.super_.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var state = this._readableState;
  if (!state.flowing) {
    debug('resume');
    state.flowing = true;
    resume(this, state);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.stream-splicer.super_.super_.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function (enc) {
  if (!StringDecoder) StringDecoder = require('string_decoder/').StringDecoder;
  this._readableState.decoder = new StringDecoder(enc);
  this._readableState.encoding = enc;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.unpipe"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.stream-splicer.super_.super_.prototype.unpipe)
- description and source-code
```javascript
unpipe = function (dest) {
  var state = this._readableState;

  // if we're not piping anywhere, then do nothing.
  if (state.pipesCount === 0) return this;

  // just one destination.  most common case.
  if (state.pipesCount === 1) {
    // passed in one, but it's not the right one.
    if (dest && dest !== state.pipes) return this;

    if (!dest) dest = state.pipes;

    // got a match.
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;
    if (dest) dest.emit('unpipe', this);
    return this;
  }

  // slow case. multiple pipe destinations.

  if (!dest) {
    // remove all.
    var dests = state.pipes;
    var len = state.pipesCount;
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;

    for (var i = 0; i < len; i++) {
      dests[i].emit('unpipe', this);
    }return this;
  }

  // try to find the right one.
  var index = indexOf(state.pipes, dest);
  if (index === -1) return this;

  state.pipes.splice(index, 1);
  state.pipesCount -= 1;
  if (state.pipesCount === 1) state.pipes = state.pipes[0];

  dest.emit('unpipe', this);

  return this;
}
```
- example usage
```shell
...
var len = this._streams.length;
start = start < 0 ? len - start : start;
if (removeLen === undefined) removeLen = len - start;
removeLen = Math.max(0, Math.min(len - start, removeLen));

for (var i = start; i < start + removeLen; i++) {
    if (self._streams[i-1]) {
        self._streams[i-1].unpipe(self._streams[i]);
    }
}
if (self._streams[i-1] && self._streams[i]) {
    self._streams[i-1].unpipe(self._streams[i]);
}
var end = i;
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.unshift"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.stream-splicer.super_.super_.prototype.unshift)
- description and source-code
```javascript
unshift = function (chunk) {
  var state = this._readableState;
  return readableAddChunk(this, state, chunk, '', true);
}
```
- example usage
```shell
...

Push one or more streams to the end of the pipeline.

## var stream = pipeline.pop()

Pop a stream from the end of the pipeline.

## pipeline.unshift(stream, ...)

Unshift one or more streams to the begining of the pipeline.

## var stream = pipeline.shift()

Shift a stream from the begining of the pipeline.
...
```

#### <a name="apidoc.element.stream-splicer.super_.super_.prototype.wrap"></a>[function <span class="apidocSignatureSpan">stream-splicer.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.stream-splicer.super_.super_.prototype.wrap)
- description and source-code
```javascript
wrap = function (stream) {
  var state = this._readableState;
  var paused = false;

  var self = this;
  stream.on('end', function () {
    debug('wrapped end');
    if (state.decoder && !state.ended) {
      var chunk = state.decoder.end();
      if (chunk && chunk.length) self.push(chunk);
    }

    self.push(null);
  });

  stream.on('data', function (chunk) {
    debug('wrapped data');
    if (state.decoder) chunk = state.decoder.write(chunk);

    // don't skip over falsy values in objectMode
    if (state.objectMode && (chunk === null || chunk === undefined)) return;else if (!state.objectMode && (!chunk || !chunk.length
)) return;

    var ret = self.push(chunk);
    if (!ret) {
      paused = true;
      stream.pause();
    }
  });

  // proxy all the other methods.
  // important when wrapping filters and duplexes.
  for (var i in stream) {
    if (this[i] === undefined && typeof stream[i] === 'function') {
      this[i] = function (method) {
        return function () {
          return stream[method].apply(stream, arguments);
        };
      }(i);
    }
  }

  // proxy certain important events.
  var events = ['error', 'close', 'destroy', 'pause', 'resume'];
  forEach(events, function (ev) {
    stream.on(ev, self.emit.bind(self, ev));
  });

  // when we try to consume some more bytes, simply unpause the
  // underlying stream.
  self._read = function (n) {
    debug('wrapped _read', n);
    if (paused) {
      paused = false;
      stream.resume();
    }
  };

  return self;
}
```
- example usage
```shell
...

Pipeline.prototype.indexOf = function (stream) {
return this._streams.indexOf(stream);
};

Pipeline.prototype._wrapStream = function (stream) {
if (typeof stream.read === 'function') return stream;
var w = new Readable(this._wrapOptions).wrap(stream);
w._write = function (buf, enc, next) {
    if (stream.write(buf) === false) {
        stream.once('drain', next);
    }
    else nextTick(next);
};
return w;
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
