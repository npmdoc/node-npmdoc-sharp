# npmdoc-sharp

#### api documentation for  [sharp (v0.17.3)](https://github.com/lovell/sharp)  [![npm package](https://img.shields.io/npm/v/npmdoc-sharp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sharp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sharp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sharp)

#### High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images

[![NPM](https://nodei.co/npm/sharp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sharp)

- [https://npmdoc.github.io/node-npmdoc-sharp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sharp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sharp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sharp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sharp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sharp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lovell Fuller"
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
            "name": "Pierre Inglebert"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Chanon Sajjamanochai"
        },
        {
            "name": "Juliano Julio"
        },
        {
            "name": "Daniel Gasienica"
        },
        {
            "name": "Julian Walker"
        },
        {
            "name": "Amit Pitaru"
        },
        {
            "name": "Brandon Aaron"
        },
        {
            "name": "Andreas Lind"
        },
        {
            "name": "Maurus Cuelenaere"
        },
        {
            "name": "Linus Unnebäck"
        },
        {
            "name": "Victor Mateevitsi"
        },
        {
            "name": "Alaric Holloway"
        },
        {
            "name": "Bernhard K. Weisshuhn"
        },
        {
            "name": "Chris Riley"
        },
        {
            "name": "David Carley"
        },
        {
            "name": "John Tobin"
        },
        {
            "name": "Kenton Gray"
        },
        {
            "name": "Felix Bünemann"
        },
        {
            "name": "Samy Al Zahrani"
        },
        {
            "name": "Chintan Thakkar"
        },
        {
            "name": "F. Orlando Galashan"
        },
        {
            "name": "Kleis Auke Wolthuizen"
        },
        {
            "name": "Matt Hirsch"
        },
        {
            "name": "Matthias Thoemmes"
        },
        {
            "name": "Patrick Paskaris"
        },
        {
            "name": "Jérémy Lal"
        },
        {
            "name": "Rahul Nanwani"
        },
        {
            "name": "Alice Monday"
        },
        {
            "name": "Kristo Jorgenson"
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
            "name": "lovell"
        }
    ],
    "name": "sharp",
    "optionalDependencies": {},
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
