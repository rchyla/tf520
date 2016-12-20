Terrible Fire 68020 "Accelerator"
=================================

** WARNING THIS IS BETA AT THE MOMENT

This repository contains all the files needed to produce a copy of my accelerator board.

The CPLD Required is a XC9532XL-VQ44

Everything in this repository is released under the GNU GPLv2. You may create or base commercial PCBs from the work in this repository but you must make the sources for all derivative work available. 

Firmware / Requirements
------------

  * Any Xilinx ISE that support XC9500XL Family (I personally work with final 14.7 version). You may need to create project
    manually and imort source files if your ISE can't work with my project file.
  * JTAG Adaptor (use urjtag for adaptors not suppoerted by ISE, requires to generate .svf file)

PCB Manufacture
---------------

You may get any PCB manufacturer to produce the board for you. The board is 2-layer. I recommend DirtyPCBs 

This link takes you to a store to buy them 

http://dirtypcbs.com/store/designer/details/12476/1120/sl520-rev3-zip

To populate a PCB you will likely need the following tools.

  * Soldering Station (with hot air rework and an iron - probably with a few tips)
  * Stereo Microscope (or similar for soldering under)
  * Bench Power Supply (to verify the regulator circuit)
 
There will be those with more experience and great eyesight that could manage it with just a soldering iron but I am trying to be realistic here. 
