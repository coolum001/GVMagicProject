# README for develop directory

## Short Description of GVMagic Project##
This is a collection of files and notebooks that explores the gvmagic capablities.

Areas with example code include:

* nodes with images (only partially working, sadly)
* layout options
* examples of specifying diagrams with DOT

Overall, in many cases, graph-style diagrams can be encoded realtivily easily in DOT.

### Notes

Path searching appears to be problematic, so the original gvmagic.py has been modified to specify

`shell=True`

as an argument of the subprocess POpen call.  This appear to fix the search for the dot utility.