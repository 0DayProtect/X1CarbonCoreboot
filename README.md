# Lenovo X1 Carbon Coreboot


The idea is to use the Debian Live Testing Build to create an ISO. This ISO can then be booted into and the X1CarbonCoreboot repository dumped. This will allow prompt customization of the firmware for your specification.


Contains Submodules + GNAT + coreboot cross toolchains
GNAT and native GCC have to line up or ADA wont work. 

This will kill your display


split -b 95M coreboot.tar.bz2 "coreboot.tar.bz2.part"


ls -lh coreboot.tar.bz2.parta*


cat coreboot.tar.bz2.parta* >coreboot.tar.bz2
