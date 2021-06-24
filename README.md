cpdflib-binary
==============

libcpdf is a library version of the Coherent PDF Command Line Tools, which are
available in binary form:

http://github.com/coherentgraphics/cpdf-binaries

and also in source form.

The website for commercial sales of the Command Line Tools is

http://www.coherentpdf.com/

To purchase libcpdf for commercial use, contact

contact@coherentgraphics.co.uk


Use
===

There is one header file, cpdflibwrapper.h, and a static library and DLL(s).

Sample linking on Linux with static libraries:
cc program.c -o program -L. -lcpdf -lm -ldl

Sample linking on Windows with DLL:
cc program.c -o program.exe -Wl,-rpath,. -L. -l:libcpdf.dll

Sample linking on OS X with static libraries:
cc program.c -o program -L. -lcpdf


Documentation
=============

See cpdflibmanual.pdf.
