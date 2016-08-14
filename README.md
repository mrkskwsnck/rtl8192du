rtl8192du
=========

Source code for RTL8192DU device


Compile && Install (Debian based Linux)
---------------------------------------

```
sudo apt-get install build-essential linux-headers-generic git
git clone https://github.com/lwfinger/rtl8192du.git
cd rtl8192du
make
sudo make install
sudo modprobe 8192du
```

See also [So I have a driver for my Wireless USB adapter...](https://ubuntuforums.org/showthread.php?p=12688576#post12688576)
