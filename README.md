# Squish Python bindings

Clone of libsquish-python-binding.patch (https://code.google.com/archive/p/libsquish/issues/17)

Updated for libsquish-1.15.tgz (https://sourceforge.net/projects/libsquish/)

Squish is a c++ library for compressing and uncompressing image using S3TC
algorithm.

Check website at http://code.google.com/p/libsquish/

## Installation

To be able to compile this extension, you need:

- a libsquish.a (compile the lib first.)

- cython (http://cython.org/)


You can compile locally::

    python setup.py build_ext --inplace

Or install on your system::

    sudo python setup.py install

## Usage

Check examples directory for a image compress/decompress example using DXT1
algorithm.  Both example require pygame library for reading/writing image.
