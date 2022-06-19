# PixfriOS
My custom operating system programmed in C and C++

## gnu-efi

### build the bootloader

  For Windows users:
    open a wsl terminal
    type "sudo apt-get install mtools build-essentials"
    type "make bootloader"
    
  same commands for linux users
  
## kernel

### 1. build the kernel

  WARNING: Make sure you downloaded the dependencies before 
  
  For Windows users:
    Open a wsl terminal
      type the commands "make kernel" then "make buildimg" for building the image
  
  For Linux users:
    Open a terminal
    Same command
    
 ### 2. Run
  For Windows users:
    execute the run.bat file
    
  For Linux users:
    type "sudo apt-get install qemu"
    In the same terminal type "make run"
    
## dependencies
[qemu](https://qemu.weilnetz.de/w64/2022/qemu-w64-setup-20220419.exe)
