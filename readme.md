[![Build Status](https://travis-ci.org/herumi/she-wasm.png)](https://travis-ci.org/herumi/she-wasm)
# Two-level homomorphic encryption for Node.js by WebAssembly

# Abstract

see [mcl](https://github.com/herumi/mcl) and [she demo on browser](https://herumi.github.io/she-wasm/she-demo.html)

# for Node.js

```
node test
```

# Doc
* [slide for ASIA CCS 2018 in English](https://www.slideshare.net/herumi/efficient-twolevel-homomorphic-encryption-in-primeorder-bilinear-groups-and-a-fast-implementation-in-webassembly)
    * [ASIA CCS 2018 accepted paper](http://asiaccs2018.org/?page_id=632)
* [slide for SCIS 2018 in Japanese](https://www.slideshare.net/herumi/2scis2018)
* [she-api](https://github.com/herumi/mcl/blob/master/misc/she/she-api.md)
* [she-api(Japanese)](https://github.com/herumi/mcl/blob/master/misc/she/she-api-ja.md)

# How to build
Install [emsdk](https://github.com/juj/emsdk.git)

```
mkdir work
cd work
git clone git@github.com:herumi/mcl
git clone git@github.com:herumi/cybozulib
git clone git@github.com:herumi/she-wasm
cd mcl
make she-wasm
```

# License

modified new BSD License
http://opensource.org/licenses/BSD-3-Clause

# Author

光成滋生 MITSUNARI Shigeo(herumi@nifty.com)
