# AppImage Installer  
This is used in [HyprUpld](https://github.com/PhoenixAceVFX/hyprupld) to install the command aliasing  

# Dependencies?  
The script has been setup to install any dependencies if they are needed  

# How to use?  
Clone this repo  
Create a folder named "Compiled"  
Put your AppImage files into that folder  
Edit "Installer.sh" to list the AppImage files and what alias you want  
> This is on line 115

Run `bash Installer.sh`  
Your AppImage should now be installed globally  
You can test this by trying to use the command alias you made  
> The script will spit out the commands that should now work  
