# FISOC_ElmerIce_ROMS_MISOMIP1_GMD
Data and code available for GMD paper
This directory should contain all the files and information needed to run the "Assessment of oscillation feature in sub-shelf melting from idealized coupled ice sheet ocean models" GMD idealised simulations.
Input files are placed in subdirectories named by CTRL
Coupling code

ESMF 
https://www.earthsystemcog.org/projects/esmf/
Earth System Modelling Framework 
version 8.0.0_beta49

FISOC
URL: https://github.com/RupertGladstone/FISOC
SSH access to the relevant commit:
git clone -b devel git@github.com:RupertGladstone/FISOC.git
git checkout 991b7021fb1037c0b03b80d0a13bdfc5ee3c31b4


Ocean components (the repositories are private, please request access if desired)

ROMSIceShelf
URL: https://github.com/bkgf/ROMSIceShelf_devel
SSH access to the relevant commit:
git clone -b ROMSIceShelfFISOC git@github.com:bkgf/ROMSIceShelf_devel.git
git checkout 9b1852053dc0dfb9ce588d667c10c30f96e39e0c


Ice component

Elmer/Ice
URL https://github.com/ElmerCSC/elmerfem
SSH access to the relevant commit:
git clone -b devel git@github.com:ElmerCSC/elmerfem.git
git checkout 8f9f2c70