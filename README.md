# PixfriOS
My custom operating system programmed in C and C++

## gnu-efi
The bootloader for my kernel

### build the bootloader

  For Windows users:
    open a wsl terminal  
    type "sudo apt-get install mtools build-essential"
    type "make bootloader"
    
  same command for linux users
  
## kernel

### Steps for building
#### 1. build the kernel

  WARNING: Make sure you downloaded the dependencies before 
  
  For Windows users:
    Open a wsl terminal
      type the commands "make kernel" then "make buildimg" for building the image
  
  For Linux users:
    Open a terminal
    Same command
    
 #### 2. Run
  For Windows users:
    execute the run.bat file in the kernel directory
    
  For Linux users:
    type "sudo apt-get install qemu"
    In the same terminal type "make run"
    
## dependencies
[qemu](https://qemu.weilnetz.de/w64/2022/qemu-w64-setup-20220419.exe)
