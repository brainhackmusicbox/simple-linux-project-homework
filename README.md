# simple-linux-project-homework
# HOW TO INSTALL

## Configuration
`cd simple-linux-project-homework`

`aclocal && autoconf && automake --add-missing`

`./configure`

## Build:
`make`

## Installation
`sudo make install`
Installs the binary to `/usr/local/bin/`, and the header to `/usr/local/include/`.

## Uninstallation:
`sudo make clean-all`
Removes the binary from `/usr/local/bin/`, and the header from `/usr/local/include/`.
Cleans all files in the working directory except input files (*.c, *.h, *.am, *.ac).
