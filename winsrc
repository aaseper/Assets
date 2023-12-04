/*
 *
 * Windows 10/11 first-runtime
 * Recommended utilities, installations, and most important config paths
 *
 */

# +--------------------------------------+
# |     CTT Ultimate Windows Utility     |
# +--------------------------------------+
iwr -useb https://christitus.com/win | iex 

# +--------------------------------------+
# |           Winaero Tweaker            |
# +--------------------------------------+
https://winaerotweaker.com/

# +--------------------------------------+
# |            WSL2 + Debian             |
# +--------------------------------------+
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
wsl.exe --update
wsl --set-default-version 2
wsl --install -d Debian # callable as 'debian'

# +--------------------------------------+
# |              Features                |
# +--------------------------------------+
optionalfeatures

# +--------------------------------------+
# |         Netname + Workgroup	         |
# +--------------------------------------+
sysdm.cpl

# +--------------------------------------+
# |            Shorcuts path             |
# +--------------------------------------+
cd AppData
start .
