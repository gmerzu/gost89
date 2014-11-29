Gost89
======

Gost89 cipher and hash function implementation in JS

[![Build Status](https://travis-ci.org/dstucrypt/gost89.svg?branch=master)](https://travis-ci.org/dstucrypt/gost89)
[![npm module](https://badge.fury.io/js/gost89.svg)](https://www.npmjs.org/package/gost89)
[![dependencies](https://david-dm.org/dstucrypt/gost89.png)](https://david-dm.org/dstucrypt/gost89)

Warning!
--------

Some things may not work. Only messages aligned to 32 bytes would be hashed or encrypted correctly.
You have been warned!

Algos
-----

* DSTU Gost 34311-95 hash function
* DSTU Gost 28147-2009 CFB mode block cipher
* DSTU Gost 28147-2009 ECB mode block cipher