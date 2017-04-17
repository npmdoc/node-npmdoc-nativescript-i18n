# api documentation for  nativescript-i18n (v0.1.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-nativescript-i18n.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nativescript-i18n) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nativescript-i18n.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nativescript-i18n)
#### An i18n nativescript plugin using native standards

[![NPM](https://nodei.co/npm/nativescript-i18n.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-i18n)

- [https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Tamas"
    },
    "dependencies": {
        "format": "^0.2.2",
        "nativescript-hook": "^0.2.1",
        "plist": "^2.0.1",
        "xmldom": "^0.1.27"
    },
    "description": "An i18n nativescript plugin using native standards",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "1d09a231f1e60f883b1185b27a5873d5de466efe",
        "tarball": "https://registry.npmjs.org/nativescript-i18n/-/nativescript-i18n-0.1.6.tgz"
    },
    "gitHead": "1675c0bcf16a194520ed40f5bc99bf177710f4ed",
    "keywords": [
        "nativescript",
        "i18n"
    ],
    "license": "MIT",
    "main": "i18n",
    "maintainers": [
        {
            "name": "rborn"
        }
    ],
    "name": "nativescript-i18n",
    "nativescript": {
        "platforms": {
            "android": "2.5.0",
            "ios": "2.5.0"
        },
        "hooks": [
            {
                "type": "before-prepare",
                "script": "lib/before-prepare.js",
                "inject": true
            }
        ],
        "tns-ios": {
            "version": "2.5.0"
        },
        "tns-android": {
            "version": "2.5.0"
        }
    },
    "optionalDependencies": {},
    "scripts": {
        "postinstall": "node postinstall.js",
        "preuninstall": "node preuninstall.js",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.1.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
