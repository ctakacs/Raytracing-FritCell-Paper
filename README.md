# Raytracing-FritCell-Paper

Python based code for x-ray Raytracing the frit cell geometry. This is the initial code, not overtly user friendly, and left in the state necessary to reproduce some of the figures in the inital Frit cell paper. The intent is to cleanup this code and pacakage it into a more complete, easy to use library. A link will be posted to this repository here when that happens. 

## Suggestions
Trimesh with the accelerated Intel Embree backend can be tricky to install on Windows as they python wrapper package 'pyembree' is not available through conda. This needs to be compiled on Windows by you. Compilation using Microsoft Visual Studio 2015 is not overly difficult but can be intimadating. The Numpy backend is significantly slower. I suggest installation on a MacOS machine or Linux where conda packages for pyembree is available (and even potentially WSL2 on Windows?).

Instructions for those willing to try on windows are here:

https://github.com/scopatz/pyembree/issues/14#issuecomment-433406567
