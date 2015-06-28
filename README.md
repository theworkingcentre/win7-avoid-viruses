Avoiding Viruses and Malware in Windows 7
=========================================

This documentation is intended to be end-user-friendly documentation
on avoiding malware. It is based on our experiences at the Computer
Reycling project. 

The documentation is released under a CC-BY-SA 4.0 license:
<http://creativecommons.org/licenses/by-sa/4.0/>

The documentation format is Sphinx. In our production documentation we
are using the extension `sphinxcontrib-fulltoc`:
<http://sphinxcontrib-fulltoc.readthedocs.org/en/latest/>

The documentation is created using Sphinx 1.1.3 on Debian Squeeze,
using Python 2.7 . To build: 

    apt-get install python-sphinx python-pip
    pip install sphinxcontrib-fulltoc
    cd win7-avoid-viruses
    make html 

The pdf target does not work well at all.
