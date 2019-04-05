Avoiding Viruses and Malware in Windows 7
=========================================

This documentation is intended to be end-user-friendly documentation
on avoiding malware. It is based on our experiences at the Computer
Reycling project. 

The documentation is released under a CC-BY-SA 4.0 license:
<http://creativecommons.org/licenses/by-sa/4.0/>

The documentation format is Sphinx.
 We have since updated the theme to the `sphinx_rtd_theme` and
gotten rid of the `sphinxcontrib_fulltoc` extension. 

The documentation is created using Sphinx 1.2.3 on Debian Jessie, 
using Python 2.7 . To build: 

    apt-get install python-sphinx python-pip
    pip install sphinx_rtd_theme
    cd win7-avoid-viruses
    make html 

The pdf target does not work well at all.

The documentation is mirrored here:
<https://github.io/workingcentre/win7-avoid-viruses> . 

(The mirror uses a
`gh-pages` branch with the files manually checked in. Sorry.
Approximate instructions are here:
<https://github.com/lotharschulz/sphinx-pages/blob/master/sphinx-2-gh-pages-converter.sh>)
