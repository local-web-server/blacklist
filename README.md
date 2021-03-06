[![view on npm](https://img.shields.io/npm/v/lws-blacklist.svg)](https://www.npmjs.org/package/lws-blacklist)
[![npm module downloads](https://img.shields.io/npm/dt/lws-blacklist.svg)](https://www.npmjs.org/package/lws-blacklist)
[![Build Status](https://travis-ci.org/lwsjs/blacklist.svg?branch=master)](https://travis-ci.org/lwsjs/blacklist)
[![Dependency Status](https://badgen.net/david/dep/lwsjs/blacklist)](https://david-dm.org/lwsjs/blacklist)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](https://github.com/feross/standard)

# lws-blacklist

Middleware for [lws](https://github.com/lwsjs/lws) enabling certain routes to be forbidden. See [here](https://github.com/lwsjs/local-web-server/wiki/How-to-blacklist-certain-routes) for usage instructions.

Adds the following options to lws.

```
--blacklist path ...           A list of routes to forbid, e.g. `--blacklist "/admin/(.*)" "(.*).php"`
```

* * *

&copy; 2016-20 Lloyd Brookes \<75pound@gmail.com\>.
