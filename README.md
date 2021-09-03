cpdflib-binary
==============

libcpdf is a C and Python library version of the Coherent PDF Command Line
Tools, which are available in binary form:

http://github.com/coherentgraphics/cpdf-binaries

and also in source form.

The website for commercial sales of the Command Line Tools and C and Pythonm APIs is

http://www.coherentpdf.com/

Contact: contact@coherentgraphics.co.uk


Use with C
==========

There is one header file, cpdflibwrapper.h, and a static library and DLL(s).

Sample linking on Linux with static libraries:
cc program.c -o program -L. -lcpdf -lm -ldl

Sample linking on Windows with DLL:
cc program.c -o program.exe -Wl,-rpath,. -L. -l:libcpdf.dll

Sample linking on OS X with static libraries:
cc program.c -o program -L. -lcpdf


Use with Python
===============

Use pycpdf.py and import Pycpdf.


Documentation
=============

See cpdflibmanual.pdf for C and pycpdflibmanual.pdf for Python.

Python API docs are also online, to be read in conjunction with pycpdflibmanual.pdf.

https://python-libcpdf.readthedocs.io/en/latest/
