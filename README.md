# linux-wifi-hotspot-RPM-OPENSUSE
binary files for linux-wifi-hotspot (https://github.com/lakinduakash/linux-wifi-hotspot) for debian like ubuntu and rpm like opensuse linux

## This repo is made only because people find it difficult to make wifi-hotspot on linux
:)
FORKED FROM: https://github.com/lakinduakash/linux-wifi-hotspot/

### For RPM based distributions like opensuse and fedora
download here: https://github.com/QwertyTheCoder/linux-wifi-hotspot-RPM-OPENSUSE/releases/download/v4.4.0/linux-wifi-hotspot-4.4.0-2.x86_64.rpm

### For DEBIAN based distributions like ubuntu
download here: https://github.com/QwertyTheCoder/linux-wifi-hotspot-RPM-OPENSUSE/releases/download/v4.4.0/linux-wifi-hotspot_4.4.0_amd64.deb

## Dependencies
#### General
* bash
* util-linux (for getopt)
* procps or procps-ng
* hostapd
* iproute2
* iw
* iwconfig (you only need this if 'iw' can not recognize your adapter)
* haveged (optional)
_Make sure you have those dependencies by typing them in terminal. If any of dependencies fail install it using your distro's package manager

#### For 'NATed' or 'None' Internet sharing method
* dnsmasq
* iptables
* To build from source
* make
* gcc and g++
* build-essential
* pkg-config
* gtk
* libgtk-3-dev
* libqrencode-dev (for qr code generation)
* libpng-dev (for qr code generation)
#### On Ubuntu or debian install dependencies by,

```bash
sudo apt install -y libgtk-3-dev build-essential gcc g++ pkg-config make hostapd libqrencode-dev libpng-dev
```
On Fedora/CentOS/Red Hat Enterprise Linux/Rocky Linux/Oracle Linux

```bash
sudo dnf install -y gtk3-devel gcc gcc-c++ kernel-devel pkg-config make hostapd qrencode-devel libpng-devel
```

## Running
You can launch the GUI by searching for "Wifi Hotspot" in the Application Menu
or using the terminal with:

    wihotspot

## I OR THE ORIGINAL CREATOR IS NOT RESPONSIBLE FOR ANY TYPE OF DAMAGE
