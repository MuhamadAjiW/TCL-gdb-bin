# TCL12_gdb-python-bin
> MuhamadAjiW, 18/09/2023

## Description
`gdb 8.2.1` binary file for `TinyCoreLinux 12` with `python2` compatibility. You can clone this repo to work on it further. Src is `gdb 8.2.1` source code compiled inside a `VirtualBox run TinyCoreLinux 12` with `python2.7` in case you need it.

## Installation
How to install in TinyCoreLinux:
1. Download the [core](core-files) (`put it inside the linux` in case you run it in a host hardware)
2. move `gdb` to `usr/local/bin` or anywhere in your $PATH
3. move `data-directory` contents to `usr/local/share/gdb`, make the folder to the path in case there wasn't one
4. try running `gdb --version`

Enjoy
