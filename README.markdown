structs
==========

[![Hackage](https://img.shields.io/hackage/v/structs.svg)](https://hackage.haskell.org/package/structs) [![Build Status](https://secure.travis-ci.org/ekmett/structs.png?branch=master)](http://travis-ci.org/ekmett/structs)

This package explores strict mutable data structures in Haskell.

In particular, pointer-based data structures are effectively 'half price' due to the encoding used.

However, the result is that if you use the `slot` and `field` system wrong, you can and will `SEGFAULT`.

This means the `Internal` modules are very much internal.

Some documentation is available at
[http://ekmett.github.io/structs/Data-Struct.html](http://ekmett.github.io/structs/Data-Struct.html).

Contact Information
-------------------

Contributions and bug reports are welcome!

Please feel free to contact me through github or on the #haskell IRC channel on irc.freenode.net.

-Edward Kmett
