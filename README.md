MyVsCodeSettings  
=================

My setting file of  Visual Studio Code and shell script to install my favorite extensions.  

## Description  
My settings.json of Visual Studio Code on my development environment.  
Shell script to install my favorite extensions of VS Code automatically.  

## Author  
Shisato Yano  

## Usage  
1. Clone this repository to your working directory.  

2. Make symbolic link of settings in this repository to the following path.  
~/AppData/Roaming/Code/User  
Usually, settings.json of VS Code should be located in this directory.  

3. Execute install_vscode_extensions.sh  
This script can install some extensions of VS Code by referring to "extensions" file. This file is the list of extensions.  
You can create extensions file by the following command.  
$ code --list-extensions > extensions  

4. Autonomous installation will start.  
![image_alt_text](https://github.com/ShisatoYano/MyVsCodeSettings/blob/master/execute_shell_script.PNG?raw=true)  
