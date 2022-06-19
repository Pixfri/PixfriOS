# kernel
My own kernel for my OS

## Steps for building
### 1. build the kernel

  WARNING: Make sure you downloaded the dependencies before 
  
  For Windows users:
    Open a wsl terminal
      type "sudo apt-get install mtools build-essential"
      type the commands "make kernel" then "make buildimg" for building the image
  
  For Linux users:
    Open a terminal
    Same commands
    
 ### 2. Run
  For Windows users:
    execute the run.bat file
    
  For Linux users:
    type "sudo apt-get install qemu"
    In the same terminal type "make run"
    
 ## Dependencies
 [OVMFbin](https://github.com/Pixfri/OVMFbin)  
 [bootloader](https://github.com/Pixfri/gnu-efi)  
 [qemu](https://qemu.weilnetz.de/w64/2022/qemu-w64-setup-20220419.exe)
 
 ### note
 
 The OVMFbin dependency is necessary only if you use qemu to test the system
