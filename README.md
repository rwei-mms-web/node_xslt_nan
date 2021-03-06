# node-xslt-transform

This repo is forked from node_xslt. Code is simplified and rewritten using nodejs/nan.

Tested with node versions: 0.10.36, 0.12.18, 4.3.2, 6.9.4, 7.5.0.

## Install
```
npm install node-xslt-transform --save
```

Then:

```JS

var xslt = require('node-xslt-transform');
var transformed = xslt.transform('xml content','xslt content');

```

## Requirements
* GCC compiler. (Install Xcode on Mac)
* [libxml2](http://www.xmlsoft.org/) (libxml2-dev package for Debian-based distros)
* [libxslt](http://xmlsoft.org/xslt/index.html) (libxslt-dev package for Debian-based distros)
* [libexslt](http://xmlsoft.org/xslt/EXSLT/) (libxslt-dev package for Debian-based distros)
* xml2-config (Needs to be on PATH)
