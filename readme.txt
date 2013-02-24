Peter J. Lu
23 Feb 2012
http://www.peterlu.org
plu@fas.harvard.edu
Copyright 2013 Peter J. Lu

This document provides instructions on how to build

plu_struct3dt

**If you use this code, please cite in your publications:
Peter J. Lu, Peter A. Sims, Hidekazu Oki, James B. Macarthur, and David A. Weitz, 
"Target-locking acquisition with real-time confocal (TARC) microscopy,"
Optics Express Vol. 15, pp. 8702-8712 (2007).

Information on the details of the algorithm are given in Chapter 6 of: 
Peter J. Lu, "Gelation and Phase Separation of Attractive Colloids,"
Harvard University PhD Thesis (2008).

This project involves a single, self-contained C++ file that manipulates the text data output from plu_link3dt. To build, create an Eclipse project as described in the readme.txt for plu_centerfind2D, with the Intel Toolchain (and, if interested, sharing with EGit). No special build options are needed, and the file should just build with either the Intel Compiler, or g++.

After this program builds successfully, run the verification tests from https://github.com/peterlu/PLuTARC_testbed can be performed (see instructions).

This is a preliminary draft of these instructions. If things are unclear or do not function as described, please contact me so we can resolve the issues.