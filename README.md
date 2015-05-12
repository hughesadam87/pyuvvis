Legacy Script for GWU Lab work
------------------------------

Can't find the original source code.  This is the build (eg what gets installed after typing setup.py install).  

**Ignore fold SCIKITSPECTRA_SCRIPT**.  This was the most recent version of script from scikit-spectra.  Once scikit-spectra is updated to have new vesrion of pandas, thsi should work fine; however, don't think this has any updates that `gwuspec` and `gwureport` from the older version.

Put `gwuspec` and `gwureport` into your python usr/bin eg:

    ~/Enthought/Canopy_32bit/User/bin/

Put the egg file your site packages

    ~/Enthought/Canopy_32bit/User/lib/python2.7/site-packages

You must open up the gwuspec and gwureport files and edit the top line to point to your python path (dunno why).  You can type which python in a terminal to find the correct python path.  For example, mine was:

    #!~/anaconda/envs/skspec/bin/python

Because I'm working in anaconda in a virtual environment called skspec.  PUT YOURS IN THE TOP OF BOTH SCRIPTS.

`gwureport` is actually not used.  This used to generated tex reports from python plot if I recall correctly, but has been fully supplanted by the sweave files method.  Can still copy it over, but I don't believe it's actually used.
