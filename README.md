# NASTRAN-95

NASTRAN has been released under the  
[NASA Open Source Agreement version 1.3](https://github.com/nasa/NASTRAN-95/raw/master/NASA%20Open%20Source%20Agreement-NASTRAN%2095.doc).


NASTRAN is the NASA Structural Analysis System, a finite element analysis program (FEA) completed in the early 1970's. It was the first of its kind and opened the door to computer-aided engineering. Subsections of a design can be modeled and then larger groupings of these elements can again be modeled. NASTRAN can handle elastic stability analysis, complex eigenvalues for vibration and dynamic stability analysis, dynamic response for transient and steady state loads, and random excitation, and static response to concentrated and distributed loads, thermal expansion, and enforced deformations.

NOTES: 
1. There is no technical support available for this software. This source code is more than two decades old, and needs a lot of adjustments to run on modern x64 systems.   
2. The purpose of this fork from NASA's original repository, is to turn the original single threaded code into a parallel code with the ability to able to use OpenCL (and possibly CUDA, if enough time is managed for this purpose).
