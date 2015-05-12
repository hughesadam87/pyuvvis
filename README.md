Legacy Script for GWU Lab work
------------------------------

Can't find the original source code.  This is the build (eg what gets installed after typing setup.py install).  

**CURRENT SCRIPTS STILL AVAILBLE IN SCIKIT-SPECTRA.**  Don't take them out until ready to build a separate setup.py file so they can be installed independently.  Do this after sure they work again with new versions of scikit spectra.

Put `gwuspec` and `gwureport` into your python usr/bin eg:

    ~/Enthought/Canopy_32bit/User/bin/

Put the egg file your site packages

    ~/Enthought/Canopy_32bit/User/lib/python2.7/site-packages

You must open up the gwuspec and gwureport files and edit the top line to point to your python path (dunno why).  You can type which python in a terminal to find the correct python path.  For example, mine was:

    #!~/anaconda/envs/skspec/bin/python

Because I'm working in anaconda in a virtual environment called skspec.  PUT YOURS IN THE TOP OF BOTH SCRIPTS.

`gwureport` is actually not used.  This used to generated tex reports from python plot if I recall correctly, but has been fully supplanted by the sweave files method.  Can still copy it over, but I don't believe it's actually used.
