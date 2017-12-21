rtl8192du
=========

Source code for RTL8192DU device


Prerequisites
-------------

Debian based Linux

```
# apt-get install build-essential linux-headers-generic git
```

Arch based Linux

```
# pacman -S base-devel
```


Compile && Install
------------------

```
$ git clone https://github.com/lwfinger/rtl8192du.git
$ cd rtl8192du
$ make
# make install
# modprobe 8192du
```

See also [So I have a driver for my Wireless USB adapter...](https://ubuntuforums.org/showthread.php?p=12688576#post12688576)
