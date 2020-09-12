PI4 offloader with ansible

This role is meant to install a Freifunk offloader on Raspbian, Debian or Ubuntu.
ffbsee and ffmuc are both supported (simultaneously) including mesh and map.
The role supports a single hardware interface using VLANs as well as two hardware interfaces (uplink + Freifunk VLANs).
Wifi is only partially working.

supported services:
* fastd
* batman-adv
* alfred
* respondd
* dhcpcd
* kdump (when supported by kernel)
* docker install
* wifi (kind of)
