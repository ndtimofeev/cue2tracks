# How to install cue2tracks #

> To install just run as root:
```
    # make install
```
> You also can use PREFIX and DESTDIR environment variables:
```
    # make install PREFIX="/usr"
    # make install DESTDIR="/usr/bin"
```
> Note: if you are using PREFIX variable then DESTDIR = ${PREFIX}/bin. Default value of PREFIX is "/usr/local".

> To uninstall run:
```
    # make uninstall PREFIX="/usr"
```
> Note: you'll need to use PREFIX again.