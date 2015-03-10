meta-bytesatwork
================================

Introduction
-------------------------

The official OpenEmbedded/Yocto BSP layer for bytePANEL by bytes at work AG

It is hosted on https://github.com/bytesatwork/meta-bytesatwork.git

This layer depends on:

	URI: git://git.yoctoproject.org/meta-ti
	layer: meta-ti
	tag: ti2014.10.01

	URI: git://git.openembedded.org/meta-openembedded
	layers: meta-oe, meta-networking, meta-python
	branch: dizzy


BSP
-------------------------
This meta layer provides the Board Support Package (U-Boot and Linux kernel) for "bytePANEL" by bytes at work AG.
Simply set the variable MACHINE to "bytepanel" to use this BSP.

Linux Kernel recipe: linux-ti-staging
U-Boot recipe: u-boot-ti-staging


Distro/Images
-------------------------
Besides the BSP, this layer also provides the distribution "poky-bytesatwork" and some images to get you started quickly:

* devbase-image-bytesatwork
This image contains several essential developer tools, such as editors (vim, nano) and debugger (gdb, valgrind).


Reporting bugs
-------------------------
Send pull requests, patches, comments or questions to yocto@bytesatwork.ch
