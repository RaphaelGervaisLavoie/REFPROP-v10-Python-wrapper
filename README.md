# REFPROP-v10-Python-wrapper

Modified version of Ben Thelen REFPROP python wrapper (https://github.com/BenThelen/python-refprop) to account for version 10 of REFPROP.

FOR LINUX:
 - Use WINE to install the REFPROP software to .wine/dosdevices/c\:/Program\ Files\ \(x86\)/REFPROP/
 - Run the script (with sudo) rp2s0-10 to compile and link the refprop shared object files. (you need gfortran, sed and dos2unix installed)
 - Install the python API to refprop into the python dist-packages folder. To do that, put the files refprop.py and multiRP.py in "python-installation-files"/lib/python3.6/
