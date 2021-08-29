# GNU Awk for MSYS (msys-gawk)

This repository contains the unofficial **GNU Awk (gawk) 4.0.1-2** release
for **MinGW/MSYS**. This package is intended to be used on **MSYS** only, and
was created to replace the very outdated **3.1.7-2** which is the only one
officially provided in the **MinGW/MSYS** repository.

## Installation

1. Download the `gawk-4.0.1-2-msys-1.0.19-bin.tar.lzma`.
2. Extract the package file in your `%MINGW_ROOT%\msys\1.0\` directory, where
   `%MINGW_ROOT%` is the **MinGW** installation directory (typically `C:\MinGW`).

## Compile

If you want to recompile this source, you will need to have a working 
[MSYS Toolchain](http://www.mingw.org/wiki/HOWTO_Create_an_MSYS_Build_Environment).
Then, follow the instructions in the `src/msys-gawk.RELEASE_NOTES` file.

## Links

* [Please update MSYS awk; current awk-3.1.7 implementation is too old to remain viable](https://osdn.net/projects/mingw/ticket/39246)
* [msysCORE Extended](https://github.com/sizious/msys-core-extended)
