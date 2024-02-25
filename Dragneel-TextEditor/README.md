# Dragneel-TextEditor

## A text editor written by a Novice in C
### VERSION 0.1.0 OUT
### Author: Taha Ahmad


### Requirements
- **gcc**
- **make** 

#### Windows

- **Get a Linux Environment**

Install either [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) (Windows 10 64-bit only) or [Cygwin](https://cygwin.com/install.html).

If using WSL then when you are in your WSL run the following:
```
sudo apt-get install gcc make
```

If you choose to use Cygwing then, when the installer asks to select packages to install choose gcc-core and make in the devel category.

#### MacOS

- **Getting C developer tools**

Run either:
```
cc 
```
or:
```
xcode-select --install
```
A window should pop up, where you just need to click "Install" and a C compiler and make will be installed among other things.

#### Linux
- **On Ubuntu or Debian Based Systems**
```
$ sudo apt install gcc make
```

- **On Arch Based Systems**
```
$ sudo pacman -S gcc make
```

### Installation
- **Clone the repository**
```
$ git clone https://github.com/BlackPhoenix/Portfolio
$ cd Portfolio/Dragneel-TextEditor/
```

- **Create the binary**
```
$ make #Compiles the binary
$ sudo cp Dragneel /usr/local/bin/ #To copy the binary to a Path Folder, you may change the destination as you like
```

### Usage
```
Dragneel <path/to/file>
```

- **Simple Keybindings**
1. CTRL + F - to find words/phrases in the file
2. CTRL + S - to save the file
3. ESC - to exit the editor
