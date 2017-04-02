# api documentation for  [sharp (v0.17.3)](https://github.com/lovell/sharp)  [![npm package](https://img.shields.io/npm/v/npmdoc-sharp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sharp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sharp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sharp)
#### High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images

[![NPM](https://nodei.co/npm/sharp.png?downloads=true)](https://www.npmjs.com/package/sharp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sharp/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sharp_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sharp/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-sharp/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Lovell Fuller",
        "email": "npm@lovell.info"
    },
    "bugs": {
        "url": "https://github.com/lovell/sharp/issues"
    },
    "cc": {
        "linelength": "120",
        "filter": [
            "build/include",
            "runtime/indentation_namespace"
        ]
    },
    "config": {
        "libvips": "8.4.2"
    },
    "contributors": [
        {
            "name": "Pierre Inglebert",
            "email": "pierre.inglebert@gmail.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "Chanon Sajjamanochai",
            "email": "chanon.s@gmail.com"
        },
        {
            "name": "Juliano Julio",
            "email": "julianojulio@gmail.com"
        },
        {
            "name": "Daniel Gasienica",
            "email": "daniel@gasienica.ch"
        },
        {
            "name": "Julian Walker",
            "email": "julian@fiftythree.com"
        },
        {
            "name": "Amit Pitaru",
            "email": "pitaru.amit@gmail.com"
        },
        {
            "name": "Brandon Aaron",
            "email": "hello.brandon@aaron.sh"
        },
        {
            "name": "Andreas Lind",
            "email": "andreas@one.com"
        },
        {
            "name": "Maurus Cuelenaere",
            "email": "mcuelenaere@gmail.com"
        },
        {
            "name": "Linus Unnebäck",
            "email": "linus@folkdatorn.se"
        },
        {
            "name": "Victor Mateevitsi",
            "email": "mvictoras@gmail.com"
        },
        {
            "name": "Alaric Holloway",
            "email": "alaric.holloway@gmail.com"
        },
        {
            "name": "Bernhard K. Weisshuhn",
            "email": "bkw@codingforce.com"
        },
        {
            "name": "Chris Riley",
            "email": "criley@primedia.com"
        },
        {
            "name": "David Carley",
            "email": "dacarley@gmail.com"
        },
        {
            "name": "John Tobin",
            "email": "john@limelightmobileinc.com"
        },
        {
            "name": "Kenton Gray",
            "email": "kentongray@gmail.com"
        },
        {
            "name": "Felix Bünemann",
            "email": "Felix.Buenemann@gmail.com"
        },
        {
            "name": "Samy Al Zahrani",
            "email": "samyalzahrany@gmail.com"
        },
        {
            "name": "Chintan Thakkar",
            "email": "lemnisk8@gmail.com"
        },
        {
            "name": "F. Orlando Galashan",
            "email": "frulo@gmx.de"
        },
        {
            "name": "Kleis Auke Wolthuizen",
            "email": "info@kleisauke.nl"
        },
        {
            "name": "Matt Hirsch",
            "email": "mhirsch@media.mit.edu"
        },
        {
            "name": "Matthias Thoemmes",
            "email": "thoemmes@gmail.com"
        },
        {
            "name": "Patrick Paskaris",
            "email": "patrick@paskaris.gr"
        },
        {
            "name": "Jérémy Lal",
            "email": "kapouer@melix.org"
        },
        {
            "name": "Rahul Nanwani",
            "email": "r.nanwani@gmail.com"
        },
        {
            "name": "Alice Monday",
            "email": "alice0meta@gmail.com"
        },
        {
            "name": "Kristo Jorgenson",
            "email": "kristo.jorgenson@gmail.com"
        }
    ],
    "dependencies": {
        "caw": "^2.0.0",
        "color": "^1.0.3",
        "got": "^6.7.1",
        "nan": "^2.5.1",
        "semver": "^5.3.0",
        "tar": "^2.2.1"
    },
    "description": "High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images",
    "devDependencies": {
        "async": "^2.2.0",
        "bufferutil": "^3.0.0",
        "cc": "^1.0.0",
        "cross-env": "^4.0.0",
        "documentation": "^4.0.0-beta.18",
        "exif-reader": "^1.0.2",
        "icc": "^1.0.0",
        "mocha": "^3.2.0",
        "nyc": "^10.2.0",
        "rimraf": "^2.5.4",
        "semistandard": "^10.0.0",
        "unzip": "^0.1.11"
    },
    "directories": {},
    "dist": {
        "shasum": "484cd2a70c900370948dcc43e165f78306bff48a",
        "tarball": "https://registry.npmjs.org/sharp/-/sharp-0.17.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "fcf853712cb0ac96bb6af1a886469d290485912c",
    "gypfile": true,
    "homepage": "https://github.com/lovell/sharp",
    "keywords": [
        "jpeg",
        "png",
        "webp",
        "tiff",
        "gif",
        "svg",
        "dzi",
        "image",
        "resize",
        "thumbnail",
        "crop",
        "libvips",
        "vips"
    ],
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "lovell",
            "email": "npm@lovell.info"
        }
    ],
    "name": "sharp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/lovell/sharp.git"
    },
    "scripts": {
        "clean": "rm -rf node_modules/ build/ vendor/ coverage/ test/fixtures/output.*",
        "docs": "for m in constructor input resize composite operation colour channel output utility; do documentation build --shallow --format=md lib/$m.js >docs/api-$m.md; done",
        "install": "node-gyp rebuild",
        "test": "semistandard && cc && cross-env VIPS_WARNING=0 nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js",
        "test-leak": "./test/leak/leak.sh",
        "test-packaging": "./packaging/test-linux-x64.sh"
    },
    "semistandard": {
        "env": [
            "mocha"
        ]
    },
    "version": "0.17.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sharp](#apidoc.module.sharp)
1.  [function <span class="apidocSignatureSpan">sharp.</span>cache (options)](#apidoc.element.sharp.cache)
1.  [function <span class="apidocSignatureSpan">sharp.</span>concurrency (concurrency)](#apidoc.element.sharp.concurrency)
1.  [function <span class="apidocSignatureSpan">sharp.</span>counters ()](#apidoc.element.sharp.counters)
1.  [function <span class="apidocSignatureSpan">sharp.</span>simd (simd)](#apidoc.element.sharp.simd)
1.  [function <span class="apidocSignatureSpan">sharp.</span>super_ (options)](#apidoc.element.sharp.super_)
1.  object <span class="apidocSignatureSpan">sharp.</span>binding
1.  object <span class="apidocSignatureSpan">sharp.</span>bool
1.  object <span class="apidocSignatureSpan">sharp.</span>colorspace
1.  object <span class="apidocSignatureSpan">sharp.</span>colourspace
1.  object <span class="apidocSignatureSpan">sharp.</span>format
1.  object <span class="apidocSignatureSpan">sharp.</span>gravity
1.  object <span class="apidocSignatureSpan">sharp.</span>interpolator
1.  object <span class="apidocSignatureSpan">sharp.</span>is
1.  object <span class="apidocSignatureSpan">sharp.</span>kernel
1.  object <span class="apidocSignatureSpan">sharp.</span>maximum
1.  object <span class="apidocSignatureSpan">sharp.</span>queue
1.  object <span class="apidocSignatureSpan">sharp.</span>strategy
1.  object <span class="apidocSignatureSpan">sharp.</span>versions

#### [module sharp.binding](#apidoc.module.sharp.binding)
1.  [function <span class="apidocSignatureSpan">sharp.binding.</span>download_vips ()](#apidoc.element.sharp.binding.download_vips)
1.  [function <span class="apidocSignatureSpan">sharp.binding.</span>use_global_vips ()](#apidoc.element.sharp.binding.use_global_vips)

#### [module sharp.is](#apidoc.module.sharp.is)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>bool (val)](#apidoc.element.sharp.is.bool)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>buffer (val)](#apidoc.element.sharp.is.buffer)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>defined (val)](#apidoc.element.sharp.is.defined)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>fn (val)](#apidoc.element.sharp.is.fn)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>inArray (val, list)](#apidoc.element.sharp.is.inArray)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>inRange (val, min, max)](#apidoc.element.sharp.is.inRange)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>integer (val)](#apidoc.element.sharp.is.integer)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>invalidParameterError (name, expected, actual)](#apidoc.element.sharp.is.invalidParameterError)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>number (val)](#apidoc.element.sharp.is.number)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>object (val)](#apidoc.element.sharp.is.object)
1.  [function <span class="apidocSignatureSpan">sharp.is.</span>string (val)](#apidoc.element.sharp.is.string)



# <a name="apidoc.module.sharp"></a>[module sharp](#apidoc.module.sharp)

#### <a name="apidoc.element.sharp.cache"></a>[function <span class="apidocSignatureSpan">sharp.</span>cache (options)](#apidoc.element.sharp.cache)
- description and source-code
```javascript
function cache(options) {
  if (is.bool(options)) {
    if (options) {
      // Default cache settings of 50MB, 20 files, 100 items
      return sharp.cache(50, 20, 100);
    } else {
      return sharp.cache(0, 0, 0);
    }
  } else if (is.object(options)) {
    return sharp.cache(options.memory, options.files, options.items);
  } else {
    return sharp.cache();
  }
}
```
- example usage
```shell
...
/**
* Gets, or when options are provided sets, the limits of _libvips'_ operation cache.
* Existing entries in the cache will be trimmed after any change in limits.
* This method always returns cache statistics,
* useful for determining how much working memory is required for a particular task.
*
* @example
* const stats = sharp.cache();
* @example
* sharp.cache( { items: 200 } );
* sharp.cache( { files: 0 } );
* sharp.cache(false);
*
* @param {Object|Boolean} options - Object with the following attributes, or Boolean where true uses default cache settings and
false removes all caching.
* @param {Number} [options.memory=50] - is the maximum memory in MB to use for this cache
...
```

#### <a name="apidoc.element.sharp.concurrency"></a>[function <span class="apidocSignatureSpan">sharp.</span>concurrency (concurrency)](#apidoc.element.sharp.concurrency)
- description and source-code
```javascript
function concurrency(concurrency) {
  return sharp.concurrency(is.integer(concurrency) ? concurrency : null);
}
```
- example usage
```shell
...
 *
 * The maximum number of images that can be processed in parallel
 * is limited by libuv's 'UV_THREADPOOL_SIZE' environment variable.
 *
 * This method always returns the current concurrency.
 *
 * @example
 * const threads = sharp.concurrency(); // 4
 * sharp.concurrency(2); // 2
 * sharp.concurrency(0); // 4
 *
 * @param {Number} [concurrency]
 * @returns {Number} concurrency
 */
function concurrency (concurrency) {
...
```

#### <a name="apidoc.element.sharp.counters"></a>[function <span class="apidocSignatureSpan">sharp.</span>counters ()](#apidoc.element.sharp.counters)
- description and source-code
```javascript
function counters() {
  return sharp.counters();
}
```
- example usage
```shell
...

/**
 * Provides access to internal task counters.
 * - queue is the number of tasks this module has queued waiting for _libuv_ to provide a worker thread from its pool.
 * - process is the number of resize tasks currently being processed.
 *
 * @example
 * const counters = sharp.counters(); // { queue: 2, process: 4 }
 *
 * @returns {Object}
 */
function counters () {
  return sharp.counters();
}
...
```

#### <a name="apidoc.element.sharp.simd"></a>[function <span class="apidocSignatureSpan">sharp.</span>simd (simd)](#apidoc.element.sharp.simd)
- description and source-code
```javascript
function simd(simd) {
  return sharp.simd(is.bool(simd) ? simd : null);
}
```
- example usage
```shell
...
* Improves the performance of 'resize', 'blur' and 'sharpen' operations
* by taking advantage of the SIMD vector unit of the CPU, e.g. Intel SSE and ARM NEON.
*
* This feature is currently off by default but future versions may reverse this.
* Versions of liborc prior to 0.4.25 are known to segfault under heavy load.
*
* @example
* const simd = sharp.simd();
* // simd is 'true' if SIMD is currently enabled
* @example
* const simd = sharp.simd(true);
* // attempts to enable the use of SIMD, returning true if available
*
* @param {Boolean} [simd=false]
* @returns {Boolean}
...
```

#### <a name="apidoc.element.sharp.super_"></a>[function <span class="apidocSignatureSpan">sharp.</span>super_ (options)](#apidoc.element.sharp.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex))
    return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false)
    this.readable = false;

  if (options && options.writable === false)
    this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false)
    this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sharp.binding"></a>[module sharp.binding](#apidoc.module.sharp.binding)

#### <a name="apidoc.element.sharp.binding.download_vips"></a>[function <span class="apidocSignatureSpan">sharp.binding.</span>download_vips ()](#apidoc.element.sharp.binding.download_vips)
- description and source-code
```javascript
download_vips = function () {
  // Has vips been installed locally?
  const vipsHeaderPath = path.join(__dirname, 'vendor', 'include', 'vips', 'vips.h');
  if (!isFile(vipsHeaderPath)) {
    // Ensure Intel 64-bit or ARM
    if (arch === 'ia32') {
      error('Intel Architecture 32-bit systems require manual installation - please see http://sharp.dimens.io/en/stable/install
/');
    }
    // Ensure glibc >= 2.15
    const lddVersion = process.env.LDD_VERSION;
    if (lddVersion) {
      if (/(glibc|gnu libc)/i.test(lddVersion)) {
        const glibcVersion = lddVersion ? lddVersion.split(/\n/)[0].split(' ').slice(-1)[0].trim() : '';
        if (glibcVersion && semver.lt(glibcVersion + '.0', '2.13.0')) {
          error('glibc version ' + glibcVersion + ' requires manual installation - please see http://sharp.dimens.io/en/stable/install
/');
        }
      } else {
        error(lddVersion.split(/\n/)[0] + ' requires manual installation - please see http://sharp.dimens.io/en/stable/install/');
      }
    }
    // Arch/platform-specific .tar.gz
    const tarFilename = ['libvips', minimumLibvipsVersion, platformId()].join('-') + '.tar.gz';
    const tarPathLocal = path.join(__dirname, 'packaging', tarFilename);
    if (isFile(tarPathLocal)) {
      unpack(tarPathLocal);
    } else {
      // Download to per-process temporary file
      const tarPathTemp = path.join(os.tmpdir(), process.pid + '-' + tarFilename);
      const tmpFile = fs.createWriteStream(tarPathTemp).on('finish', function () {
        unpack(tarPathTemp, function () {
          // Attempt to remove temporary file
          try {
            fs.unlinkSync(tarPathTemp);
          } catch (err) {}
        });
      });
      const gotOpt = {
        agent: caw(null, {
          protocol: 'https'
        })
      };
      const url = distBaseUrl + tarFilename;
      got.stream(url, gotOpt).on('response', function (response) {
        if (response.statusCode !== 200) {
          error(url + ' status code ' + response.statusCode);
        }
      }).on('error', function (err) {
        error('Download of ' + url + ' failed: ' + err.message);
      }).pipe(tmpFile);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sharp.binding.use_global_vips"></a>[function <span class="apidocSignatureSpan">sharp.binding.</span>use_global_vips ()](#apidoc.element.sharp.binding.use_global_vips)
- description and source-code
```javascript
use_global_vips = function () {
  const globalVipsVersion = process.env.GLOBAL_VIPS_VERSION;
  if (globalVipsVersion) {
    const useGlobalVips = semver.gte(
      globalVipsVersion,
      minimumLibvipsVersion
    );
    process.stdout.write(useGlobalVips ? 'true' : 'false');
  } else {
    process.stdout.write('false');
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sharp.is"></a>[module sharp.is](#apidoc.module.sharp.is)

#### <a name="apidoc.element.sharp.is.bool"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>bool (val)](#apidoc.element.sharp.is.bool)
- description and source-code
```javascript
bool = function (val) {
  return typeof val === 'boolean';
}
```
- example usage
```shell
...
* This may be overridden by other sharp operations such as 'toColourspace('b-w')',
* which will produce an output image containing one color channel.
* An alpha channel may be present, and will be unchanged by the operation.
* @param {Boolean} [greyscale=true]
* @returns {Sharp}
*/
function greyscale (greyscale) {
 this.options.greyscale = is.bool(greyscale) ? greyscale : true;
 return this;
}

/**
* Alternative spelling of 'greyscale'.
* @param {Boolean} [grayscale=true]
* @returns {Sharp}
...
```

#### <a name="apidoc.element.sharp.is.buffer"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>buffer (val)](#apidoc.element.sharp.is.buffer)
- description and source-code
```javascript
buffer = function (val) {
  return object(val) && val instanceof Buffer;
}
```
- example usage
```shell
...
 * @private
 */
function _createInputDescriptor (input, inputOptions, containerOptions) {
const inputDescriptor = {};
if (is.string(input)) {
  // filesystem
  inputDescriptor.file = input;
} else if (is.buffer(input)) {
  // Buffer
  inputDescriptor.buffer = input;
} else if (!is.defined(input) && is.object(containerOptions) && containerOptions.allowStream) {
  // Stream
  inputDescriptor.buffer = [];
} else {
  throw new Error('Unsupported input ' + typeof input);
...
```

#### <a name="apidoc.element.sharp.is.defined"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>defined (val)](#apidoc.element.sharp.is.defined)
- description and source-code
```javascript
defined = function (val) {
  return typeof val !== 'undefined' && val !== null;
}
```
- example usage
```shell
...
 * @throws {Error} Invalid parameters
 */
function overlayWith (overlay, options) {
this.options.overlay = this._createInputDescriptor(overlay, options, {
  allowStream: false
});
if (is.object(options)) {
  if (is.defined(options.tile)) {
    if (is.bool(options.tile)) {
      this.options.overlayTile = options.tile;
    } else {
      throw new Error('Invalid overlay tile ' + options.tile);
    }
  }
  if (is.defined(options.cutout)) {
...
```

#### <a name="apidoc.element.sharp.is.fn"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>fn (val)](#apidoc.element.sharp.is.fn)
- description and source-code
```javascript
fn = function (val) {
  return typeof val === 'function';
}
```
- example usage
```shell
...
 *   });
 *
 * @param {Function} [callback] - called with the arguments '(err, metadata)'
 * @returns {Promise<Object>|Sharp}
 */
function metadata (callback) {
const that = this;
if (is.fn(callback)) {
  if (this._isStreamInput()) {
    this.on('finish', function () {
      that._flattenBufferIn();
      sharp.metadata(that.options, callback);
    });
  } else {
    sharp.metadata(this.options, callback);
...
```

#### <a name="apidoc.element.sharp.is.inArray"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>inArray (val, list)](#apidoc.element.sharp.is.inArray)
- description and source-code
```javascript
inArray = function (val, list) {
  return list.indexOf(val) !== -1;
}
```
- example usage
```shell
...
 *   });
 *
 * @param {String} boolOp - one of 'and', 'or' or 'eor' to perform that bitwise operation, like the C logic operators '&', '|' and
 '^' respectively.
 * @returns {Sharp}
 * @throws {Error} Invalid parameters
 */
function bandbool (boolOp) {
  if (is.string(boolOp) && is.inArray(boolOp, ['and', 'or', 'eor'])) {
    this.options.bandBoolOp = boolOp;
  } else {
    throw new Error('Invalid bandbool operation ' + boolOp);
  }
  return this;
}
...
```

#### <a name="apidoc.element.sharp.is.inRange"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>inRange (val, min, max)](#apidoc.element.sharp.is.inRange)
- description and source-code
```javascript
inRange = function (val, min, max) {
  return val >= min && val <= max;
}
```
- example usage
```shell
...
  if (channel === 'red') {
    channel = 0;
  } else if (channel === 'green') {
    channel = 1;
  } else if (channel === 'blue') {
    channel = 2;
  }
  if (is.integer(channel) && is.inRange(channel, 0, 4)) {
    this.options.extractChannel = channel;
  } else {
    throw new Error('Cannot extract invalid channel ' + channel);
  }
  return this;
}
...
```

#### <a name="apidoc.element.sharp.is.integer"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>integer (val)](#apidoc.element.sharp.is.integer)
- description and source-code
```javascript
integer = function (val) {
  return number(val) && val % 1 === 0;
}
```
- example usage
```shell
...
  if (channel === 'red') {
    channel = 0;
  } else if (channel === 'green') {
    channel = 1;
  } else if (channel === 'blue') {
    channel = 2;
  }
  if (is.integer(channel) && is.inRange(channel, 0, 4)) {
    this.options.extractChannel = channel;
  } else {
    throw new Error('Cannot extract invalid channel ' + channel);
  }
  return this;
}
...
```

#### <a name="apidoc.element.sharp.is.invalidParameterError"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>invalidParameterError (name, expected, actual)](#apidoc.element.sharp.is.invalidParameterError)
- description and source-code
```javascript
invalidParameterError = function (name, expected, actual) {
  return new Error(
    'Expected ${expected} for ${name} but received ${actual} of type ${typeof actual}'
  );
}
```
- example usage
```shell
...
 * @throws {Error} Invalid parameters
 */
function resize (width, height, options) {
if (is.defined(width)) {
  if (is.integer(width) && is.inRange(width, 1, this.constructor.maximum.width)) {
    this.options.width = width;
  } else {
    throw is.invalidParameterError('width', 'integer between 1 and ${this.constructor.maximum.width}', width);
  }
} else {
  this.options.width = -1;
}
if (is.defined(height)) {
  if (is.integer(height) && is.inRange(height, 1, this.constructor.maximum.height)) {
    this.options.height = height;
...
```

#### <a name="apidoc.element.sharp.is.number"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>number (val)](#apidoc.element.sharp.is.number)
- description and source-code
```javascript
number = function (val) {
  return typeof val === 'number' && !Number.isNaN(val);
}
```
- example usage
```shell
...
function sharpen (sigma, flat, jagged) {
if (!is.defined(sigma)) {
  // No arguments: default to mild sharpen
  this.options.sharpenSigma = -1;
} else if (is.bool(sigma)) {
  // Boolean argument: apply mild sharpen?
  this.options.sharpenSigma = sigma ? -1 : 0;
} else if (is.number(sigma) && is.inRange(sigma, 0.01, 10000)) {
  // Numeric argument: specific sigma
  this.options.sharpenSigma = sigma;
  // Control over flat areas
  if (is.defined(flat)) {
    if (is.number(flat) && is.inRange(flat, 0, 10000)) {
      this.options.sharpenFlat = flat;
    } else {
...
```

#### <a name="apidoc.element.sharp.is.object"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>object (val)](#apidoc.element.sharp.is.object)
- description and source-code
```javascript
object = function (val) {
  return typeof val === 'object';
}
```
- example usage
```shell
...
 * @returns {Sharp}
 * @throws {Error} Invalid parameters
 */
function overlayWith (overlay, options) {
this.options.overlay = this._createInputDescriptor(overlay, options, {
  allowStream: false
});
if (is.object(options)) {
  if (is.defined(options.tile)) {
    if (is.bool(options.tile)) {
      this.options.overlayTile = options.tile;
    } else {
      throw new Error('Invalid overlay tile ' + options.tile);
    }
  }
...
```

#### <a name="apidoc.element.sharp.is.string"></a>[function <span class="apidocSignatureSpan">sharp.is.</span>string (val)](#apidoc.element.sharp.is.string)
- description and source-code
```javascript
string = function (val) {
  return typeof val === 'string' && val.length > 0;
}
```
- example usage
```shell
...
 *   });
 *
 * @param {String} boolOp - one of 'and', 'or' or 'eor' to perform that bitwise operation, like the C logic operators '&', '|' and
 '^' respectively.
 * @returns {Sharp}
 * @throws {Error} Invalid parameters
 */
function bandbool (boolOp) {
  if (is.string(boolOp) && is.inArray(boolOp, ['and', 'or', 'eor'])) {
    this.options.bandBoolOp = boolOp;
  } else {
    throw new Error('Invalid bandbool operation ' + boolOp);
  }
  return this;
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
