# VScode-Config-for-C
Config files which compile C/C++ program and put the executible in `/bin` which is created at the root ie. `${workspaceFolder}`<br>
The repo contain two folders For Linux and For Windows

* task.json
* launch.json

## Shortcuts
#### For Linux
* F5 - Compile and Debug
* Ctrl + F5 - Compile and Run
* Ctrl + Shift + B - Runs the build task which Compiles Executable and stores in `/bin`

#### For Windows
Pre-requisites `mingw32-gdb` & `mingw32-gcc-g++` are required to be installed through MinGW
* F5 - Compile and Debug
* Ctrl + Shift + B - Runs the build task which Compiles Executable and stores in `/bin`

Known Issues with Windows:
1. It doesnt work with integrated terminal
1. F5 need a breakpoint on last line else external terminal closes as soon as the program ends

Feel free to solve these :)