# Required stuff
## applications
* [CMAKE](https://cmake.org/download/)  
* [ARM toolchain](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads)  
* [openocd](https://openocd.org/pages/getting-openocd.html)  
* [ninja](https://github.com/ninja-build/ninja/releases)  
## vscode extensions
* CMAKE  
* Cortex Debug
### Optional Vscode extensions
* RTOS Views
* Serial Monitor

# How 2 Run
Download Required stuff and add to PATH  
Generate the build stuff with `cmake --preset <target>`. With target in development being `Debug` typically.  
Run and Debug Debug using the provided Debug config, Cortex Debug  
Cry as nothing works

