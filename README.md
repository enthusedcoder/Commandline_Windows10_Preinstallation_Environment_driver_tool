# Commandline Windows10 Preinstallation Environment driver tool

**Requires Windows 10 to use**

This command line utility will export all third party (non-Microsoft) developed drivers on the host operating system to a folder and will import them into the Windows image file (wim) specified by the user.  This tool requires no other software installation.  This tool is only meant to be run on a Windows 10 machine, and, by extension, should only be used to modify Windows 10 based windows image files (you wouldn't want to try to import windows 8.1 drivers into windows 10 based windows image file)

## How to use

driver.exe `<Path to wim file`>

**Example**

driver.exe "C:\Winpe\sources\winpe.wim"
