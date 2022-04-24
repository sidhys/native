To get started with compiling, install the [Windows DDK](https://download.microsoft.com/download/9/0/f/90f019ac-8243-48d3-91cf-81fc4093ecfd/1830_usa_ddk.iso) (iso file, use 7-zip to unzip) and run setup.exe to start. This kit is made for Windows XP, but seems to work fine with modern Windows versions. 

After the kit installs,
1. Open the Windows XP Free Build Environment
2. CD into the directory of all the code
3. Run `compile.cmd` (NOTE: naming this "build.bat" or "build.cmd" results in an infinite loop, as the file calls itself)
4. Check the "compiled\i386" folder for the final build.
