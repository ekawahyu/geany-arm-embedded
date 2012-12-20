geany-arm-embedded
==================

VM running linux with geany, gcc-arm-embedded, OpenOCD and picocom

You might want to use it if you
-------------------------------
1. Are beginners to ARM Cortex-M/R open source development environment.
2. Are not willing to spend too much time in building the toolchains from source.
3. Love geany's simplicity and consider using it for arm-non-eabi-*
4. Are minimalists and would like to use old computer to develop ARM Cortex-M/R.

The geany-arm-embedded is a VirtualBox disk image containing Slitaz-4.0 that boots in seconds! The disk image includes everything you need to get started quickly such as geany code editor, gcc-arm-embedded with hardware floating point support, OpenOCD flashing and picocom serial terminal.

System requirement
------------------
1. PC with Windows, Linux or Mac.
2. VirtualBox installation with its extension.

How to use the disk image
-------------------------
1. Download *.tar.bz2 file and extract it.
2. Double click *.vdi
3. When Slitaz finished booting, insert tux as the username with no password required.
4. Open Geany IDE under Applications - Development.
5. Start programming in C!

How to build the project and upload to the development board:
-------------------------------------------------------------
The simple-template provided are intended to be used with F4-DiscoverFree kit, but you can simply modify it to suit your development board. Building and upload the binary to F4-DiscoverFree is straightforward. Choose "Make Custom Target" and type 'all' to build and 'burn-ft2232d' to flash the binary to the board. You may also run Execute to open picocom serial terminal and exercise standard input/output.

Others
------
Slitaz is known as the smallest linux distribution with GUI and highly customizable. If you own some old computers, you might want to install Slitaz directly on it and make it useful like in schools for embedded development and programming. If you want to learn more about Linux, Slitaz is worth trying.

F4-DiscoverFree is an ARM Cortex-M4 development board from Aisenke, released under CC-BY-SA 3.0 Unported and Simplified BSD License. For more information, visit: http://www.aisenke.com/nodinorobotics/f4discoverfree