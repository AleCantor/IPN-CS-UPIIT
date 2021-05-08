# Ipn.c

_This is a UPIIT C/C++ languages repository_

## Starting 🚀

_These instructions will allow you to obtain a working copy of the project on your local machine for development and testing purposes_



## Pre-requirements 📋

_What things you need to install the software and how to install it_

```
GCC (GNU Compiler Collection) pre-installed on Mac
```
```
MinGW (Minimalist GNU for Windows)
```
```
Flat text editor as vim, nano or notepad (I use vim)
```


## Installing pre-requirements 🔧

_A series of step-by-step examples that tells you what to run to have a development environment running on Windows and Linux_

_Windows_

_Download and install [MinGW](https://sourceforge.net/projects/mingw/)_

<img src=/Gifs/Instalation/1.png alt="#"/>

_Select the packages you are going to use, in this case we will use the mingw32-base and mingw32-gcc-g++_

<img src=/Gifs/Instalation/2.png alt="#"/>

_If you want to be more specific open all packages and select The GNU C Compiler_

<img src=/Gifs/Instalation/3.png alt="#"/>

_To be able to debug your programs you need the Gdb, it is a debugger for C (and C++), open all programs and select mingw32-gdb_

<img src=/Gifs/Instalation/4.png alt="#"/>

_Apply changes_

<img src=/Gifs/Instalation/5.png alt="#"/>

_Copies the path C:\MinGW\bin to the environment variables_

```
C:\MinGW\bin
```

<img src=/Gifs/Instalation/6.png alt="#"/>

_Open a CMD or Powershell and check the installation with the following commands:_

```
gdb --version
```
```
gcc --version
```

<img src=/Gifs/Instalation/7.png alt="#"/>

_Linux_

_Most distros already have gcc by default but otherwise, copy and paste these commands according to your distribution_

_Debian or Ubuntu_

```
sudo apt install build-essential -y
```
```
sudo apt install gdb -y
```
<img src=/Gifs/Instalation/8.png alt="#"/>

_Red Hat or Fedora_

```
sudo dnf install gcc -y
```
```
sudo dnf install gdb -y
```
_SUSE or OpenSUSE_

```
sudo zypper install gcc -y
```
```
sudo zypper install gdb -y
```

_If you require vim in Windows just open a terminal and write:_

```
winget install vim
```

<img src=/Gifs/Instalation/9.png alt="#"/>

_If you require vim in Linux just open a terminal and write:_

```
sudo apt install vim -y
```
```
sudo dnf install vim -y
```
```
sudo zypper install vim -y
```
<img src=/Gifs/Instalation/10.png alt="#"/>



## Using the compiler ⚙️

### Linux

_Compiler_

```
vim helloworld.c
```
<img src=/Gifs/1.gif alt="#"/>

```
gcc helloworld.c -o helloworld
```
<img src=/Gifs/2.gif alt="#"/>

```
./helloworld
```
<img src=/Gifs/3.gif alt="#"/>

_Assembler_
```
gcc -S helloworld.c
```
```
vim helloworld.s
```
<img src=/Gifs/4.gif alt="#"/>

_Debug_
```
gdb helloworld
```
```
b main
```
```
run
```
```
n
```
```
quit
```
<img src=/Gifs/5.gif alt="#"/>

### Windows

_Same commands but with extension .exe_

_Compiler_
```
vim helloworld.c
```
<img src=/Gifs/11.gif alt="#"/>

```
gcc helloworld.c -o helloworld.exe
```
<img src=/Gifs/12.gif alt="#"/>

```
.\helloworld.exe
```
<img src=/Gifs/13.gif alt="#"/>

_Assembler_
```
gcc -S helloworld.c
```
```
vim helloworld.s
```
<img src=/Gifs/14.gif alt="#"/>

_Debug_
```
gdb .\helloworld.exe
```
```
b main
```
```
run
```
```
n
```
```
quit
```
<img src=/Gifs/15.gif alt="#"/>

### MacOS

_Same commands but with extension .out_

_Compiler_
```
vim helloworld.c
```
```
gcc helloworld.c -o helloworld.out
```
```
./helloworld.out
```

_Assembler_
```
gcc -S helloworld.c
```
```
vim helloworld.s
```

_Debug_
```
gdb helloworld.out
```
```
b main
```
```
run
```
```
n
```
```
quit
```


## Levels 📦

_Beginner_

_Intermediate_

_Advanced_


## Final Project 📦

_Pin Pong_


## Build with 🛠️

* [GCC](https://gcc.gnu.org/) - GNU Compiler Collection
* [MinGW](http://mingw-w64.org/doku.php) - Minimalist GNU for Windows
* [Vim](https://www.vim.org/) - The all-powerful vim
* [WSL](https://docs.microsoft.com/en-us/windows/wsl/) - Windows Subsystem for Linux 2
* [Language C](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628/ref=sr_1_1?dchild=1&keywords=language+c+dennis&qid=1618383287&sr=8-1) - The C programming language of Dennis Ritchie
* [UPIIT](https://www.upiit.ipn.mx/) - Tlaxcala Campus Interdisciplinary Engineering Unit


## Expressions of gratitude

* Thank you for reviewing this repo-tutorial 🤓
* Expect more tutorials of .NET
* I hope I helped you

---
⌨️ With ❤️ By [Jonas-Lara](https://github.com/Jonas-Lara) on behalf of [UPIIT](https://www.upiit.ipn.mx/)
