This is to downgrade avr gcc in QMK MSYS.
Sometimes results in a smaller hex file, and fixes compiling the production target.

command to downgrade:
```
pacman -U mingw-w64-x86_64-avr-gcc-8.5.0-1-any.pkg.tar.zst
```
