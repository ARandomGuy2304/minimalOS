# x86_64-Limine-OS
-------------------
Create your own x86_64 OS with the Limine bootloader.
At the end, if done correctly, you get an "image.iso" in the "os" folder.
------ How to create it ------

1. Change directory to "os".
   It is highly recommended to clone this repository with git clone instead of downloading the ZIP file.
   Command: `cd ~/os` if cloned with git.
2. Make.
   Compile and link with the GNUmakefile.
   Command: `make`.
3. Download the Limine bootloader and create the ISO file via the provided bash script.
   Command: `chmod +x make.sh && ./make.sh`.
4. Try the ISO file with QEMU.
   Command: `qemu-system-x86_64 -cdrom image.iso`.
-----------------------
