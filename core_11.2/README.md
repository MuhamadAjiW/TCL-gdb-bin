# Core_11.2
> MuhamadAjiW, 29/09/2023

## Description
`gdb_11.2` binary file, compiled inside `Tinycorelinux 13.1` on `virtualbox`. Featured with `python3.6` and is highly stripped.

## Configuration Used
> ./configure --disable-werror --with-system-readline --without-guile --with-python=/usr/local/bin/python3 --disable-multilib --disable-nls --disable-install-libbfd --disable-install-libiberty --without-zlib --without-babeltrace --disable-gdbtk --disable-gdbserver --disable-all-targets --disable-ada --disable-fortran --disable-go --disable-java --disable-rust --disable-d --disable-objc

Stripped further using
> strip gdb