# WRFHYDRO-5.2-install-script
This is a script that installs all the libararies, software, programs, and geostatic data to run the Weather Research Forecast Model Hydro (WRFHYDRO-5.2) standalone. 
Script assumes a clean directory with no other WRF configure files in the directory.
**This script does not install NETCDF4 to write compressed NetCDF4 files in parallel**

# Installation 
(Make sure to download folder into your Home Directory): $HOME


> git clone https://github.com/whatheway/WRFHYDRO-Standalone-5.2-install-script-linux-32_64bit.git

> cd $HOME/WRFHYDRO-Standalone-5.2-install-script-linux-32_64bit

> chmod 775 WRFHYDRO_STANDALONE_INSTALL.sh
> 
> chmod 775 Miniconda3_Install.sh
>
> ./WRFHYDRO_STANDALONE_INSTALL.sh

# Please make sure to read the WRF_ARW_INSTALL.sh script before installing.  
I have provided comments on what the script is doing and information on configuration files.


# WRF installation with parallel process (dmpar).
Must be installed with GNU compiler, it will not work with other compilers.


- Tested in Ubuntu 20.04.4 LTS.
- Built in 32-bit or 64-bit system.
- Tested with current available libraries on 05/10/2022, execptions have been noted in the script documentation. 
- If newer libraries exist edit script paths for changes in future.


# Estimated Run Time ~ 30 - 50 Minutes @ 10mbps download speed.
### - Special thanks to  Youtube's meteoadriatic, GitHub user jamal919, University of Manchester's  Doug L, University of Tunis El Manar's Hosni S.

