rtl8192du
=========

Source code for RTL8192DU device

Install Instructions
--------------------

### Prerequisites

#### For Fedora

    sudo dnf install -y dkms git gcc gcc-c++ kernel-headers kernel-devel make

#### For Debian based Linux

    sudo apt-get install build-essential linux-headers-generic git

See also [So I have a driver for my Wireless USB adapter...](https://ubuntuforums.org/showthread.php?p=12688576#post12688576)

#### Arch based Linux

    sudo pacman -S base-devel

### Get the source and build the driver

    git clone https://github.com/lwfinger/rtl8192du.git
    cd rtl8192du
    make
    sudo make install
    sudo modprobe 8192du
