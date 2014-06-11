tnetstring: data serialization using typed netstrings for python3
=================================================================

This is the excelent [tnetstring](http://github.com/rfk/tnetstring) python package ported to Python3.

In order to avoid pitfalls in encode/decoding of strings the support for
encoding was removed from functions. Now, only bytes are allowed as string.

To install using pip, just issue:

    
    pip3 install git+https://github.com/carlopires/tnetstring
    
