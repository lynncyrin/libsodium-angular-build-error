# reproduction for libsodium angular build error

terminal output:

```
$ npm test

> libsodium-webpack@1.0.0 test ~/libsodium-webpack
> ng build

Date: 2018-05-06T16:31:27.427Z
Hash: 4627ddaf65e7368bc48e
Time: 2313ms
chunk {main} main.js, main.js.map (main) 3.82 kB [initial] [rendered]
chunk {runtime} runtime.js, runtime.js.map (runtime) 5.4 kB [entry] [rendered]
chunk {vendor} vendor.js, vendor.js.map (vendor) 585 kB [initial] [rendered]

WARNING in ./node_modules/libsodium/dist/modules/libsodium.js
Module not found: Error: Can't resolve 'crypto' in '~/libsodium-webpack/node_modules/libsodium/dist/modules'

ERROR in ./node_modules/libsodium/dist/modules/libsodium.js
Module not found: Error: Can't resolve 'path' in '~/libsodium-webpack/node_modules/libsodium/dist/modules'
```
