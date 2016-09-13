# jspack
*JavaScript library to pack ints, floats, etc. to octet arrays representing C data structures*

This is a re-implementation of (most of) the Python struct module in JavaScript. It uses arrays of numbers between 0 and 255 in lieu of Python's strings, and omits some of the more obscure types (e.g. Pascal strings). It offers support for:

* Signed & Unsigned 8, 16, and 32 bit integers
* 32 and 64 bit floating point
* ASCII characters and strings
* Raw octet arrays

## License
https://opensource.org/licenses/BSD-3-Clause

## Original repository
Code in this repository was imported from https://code.google.com/archive/p/jspack/
