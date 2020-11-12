# AquaMEND
**This is the repository for an aqueous phase explicit C dynamic model**

This conceptual model is implemented numerically into the open-source geochemical program PHREEQC 3.0 (Parkhurst and Appelo, 2013).
Follow the following steps to install PHREEQC

* Step 1: PHREEQC installation (Mac system) Download is available on USGS website https://wwwbrr.cr.usgs.gov/projects/GWC_coupled/phreeqc/

   * In the .bash_profile under the home directory:
    export PATH="/Users/Jianqiu/Applications/phreeqc/bin:$PATH" export PHREEQC_DATABASE=/Users/Jianqiu/Applications/phreeqc/database/phreeqc.dat

* Step 2: Copy and paste the database file (redox.dat) under the database directory


**Schematic diagram of aqueous-explicit model framework**
![AquaMEND](https://user-images.githubusercontent.com/16612176/98896388-ae507900-245d-11eb-9cc5-151464f2354f.png)


**Summary of files**
1. **MENDplus.R** This is the standalone MENDplus model build in R. In this plus version, we have two DOM pools with different levels of thermodynamic favorability
1. **redox.dat** This is the new PHREEQC database we created 
1. **MENDp.phrq**
1. **MENDp.phrq**
1. **MENDp.phrq**
1. **MENDp.phrq**
