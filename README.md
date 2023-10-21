# pico_scpi_usbtmc_labtool
LabVIEW compatible instrument on a Raspberry Pico

Prerequisites:  
Toolchain (and IDE) that can build Pico projects with CMake  
Pico C SDK 1.5  
Jan Breuer [SCPI library](https://github.com/j123b567/scpi-parser)  

add these two variables to your environment:  
If you use VSCode: Preferences -> User -> Extensions -> CMake Tools -> CMake: Configure Environment

PICO_SDK_PATH (e.g.: C:/Users/jancu/Documents/Pico/pico-sdk)  
SCPI_LIB_PATH (e.g.: C:/Users/jancu/Documents/elektronica/scpi/scpi-parser/libscpi)

clone with subrepositories  
git clone https://github.com/jancumps/pico_scpi_usbtmc_labtool.git  --recurse-submodules


[documentation](https://github.com/jancumps/pico_scpi_usbtmc_labtool/wiki) on GitHub wiki
