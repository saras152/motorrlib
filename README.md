## motorrlib
https://motorrlib.gitlab.io/

## How to use

Install Scilab 5.5.2 64 bit version. 

Install FEMM 4.2 64 bit. 

Download Onelab from www.onelab.info, and uncompress.

Add the software paths to the motor variable when it is created. 

If no FEA software is available in the right path, geometry is plotted in Scilab plot itself. 


Load scifemm file in scilab

exec('D:\femm4.2\scifemm\scifemm.sci', -1);


load the required library corresponding to the topology of interest.

load('rlib_odr.bin');

load('rlib_common.bin');

load('rlib_orbldc.bin');


all the important functions are available with the starting string r_


Type r_ in scilab prompt and then press 'tab' on the keyboard. The possible functions appear as suggestions. Typing the function name and pressing 'enter' will let you know the basic help text. 



