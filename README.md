# H2Numerov

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akanotoe/H2Numerov/HEAD) [![nbviewer](https://img.shields.io/badge/view%20in-nbviewer-orange)](https://nbviewer.jupyter.org/github/akanotoe/H2Numerov/blob/master/H2Numerov.ipynb)

A Jupyter notebook designed to solve the time-independent Schrödinger equation for vibrational energies and wavefunctions of (molecular) potential energy curves (PECs). The INPUT file is where the input parameters for the Jupyter notebook are read from. In order, the lines are  
* PEC file name (e.g. Folder/PEC, leave out extension.)
* Potential energy curve name for plot titles (e.g. EF, B''Bbar, D)
* Ab initio dissociation limit quantum number n (e.g. 2, 3, ...)
* Adiabatic dissociation limit correction.

The program assumes that PECs are in [atomic units](https://en.wikipedia.org/wiki/Hartree_atomic_units).

Part of my Ph.D. work.
